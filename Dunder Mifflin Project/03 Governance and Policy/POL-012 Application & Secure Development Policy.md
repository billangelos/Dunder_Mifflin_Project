# POL-012 Application & Secure Development Policy

## Document Control

| Field | Value |
|---|---|
| Document ID | POL-012 |
| Title | Application & Secure Development Policy |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Application or Development Change |

---

# 1. Purpose

This policy establishes security requirements for applications developed, maintained, modified, or supported on behalf of Dunder Mifflin.

Application security must be incorporated throughout the development and maintenance lifecycle rather than treated solely as a final testing activity.

The policy establishes requirements for:

- Security requirements
- Secure design
- Threat modeling
- Development practices
- Environment separation
- Source-code control
- Code review
- Security testing
- Vulnerability remediation
- Change and release management
- Contractor access
- Documentation
- Application recovery
- Application transferability

---

# 2. Scope

This policy applies to:

- Internally developed applications
- Custom applications
- Significant application modifications
- Application interfaces
- Supporting databases
- Application configurations
- Application source code
- Development tools
- Source repositories
- Development environments
- Test environments
- Production environments
- Contractors developing or supporting Dunder Mifflin applications

The policy applies particularly to Infinity as Dunder Mifflin's internally owned customer-ordering application.

---

# 3. Objectives

Application and secure-development controls must:

1. Incorporate security into application requirements.
2. Identify security threats before production deployment.
3. Protect application source code.
4. Separate development, testing, and production where appropriate.
5. Restrict production access.
6. Review significant code changes.
7. Test application security.
8. Remediate identified vulnerabilities.
9. Validate remediation.
10. Maintain application documentation.
11. Protect application data.
12. Maintain recovery capability.
13. Reduce unnecessary contractor dependency.
14. Preserve application transferability.

---

# 4. Secure Software Development Lifecycle

Dunder Mifflin must use a Secure Software Development Lifecycle (SSDLC) appropriate to application risk.

The lifecycle should address:

**Requirements → Design → Development → Testing → Approval → Release → Operation → Maintenance → Retirement**

Security activities must be integrated into applicable lifecycle stages.

---

# 5. Risk-Based Application Security

Application-security requirements must reflect:

- Business criticality
- Information classification
- Internet exposure
- Authentication requirements
- Privilege
- Transaction sensitivity
- Integration
- Third-party dependency
- Potential business impact

Not every application requires identical security controls or testing depth.

---

# 6. Application Ownership

Significant applications must have an identified business or management owner.

Ownership responsibilities include, as applicable:

- Business requirements
- Security requirements
- Access decisions
- Change priorities
- Risk decisions
- Recovery requirements

Technical administration does not automatically establish business ownership.

---

# 7. Security Requirements

Security requirements must be considered when designing or materially modifying significant applications.

Requirements may include:

- Authentication
- Authorization
- Information protection
- Input validation
- Error handling
- Logging
- Session management
- Data integrity
- Availability
- Recovery
- Administrative access
- Interface security

Security requirements must be proportionate to application risk.

---

# 8. Information Classification

Applications must protect information according to [[POL-004 Information Classification & Handling Policy]] and [[STD-001 Information Classification Standard]].

Application design must consider the highest classification of information the application is authorized to process.

Application criticality and information classification must remain distinct concepts.

---

# 9. Business Impact

Application recovery requirements must support the business functions identified in [[RPT-002 Business Impact Analysis]].

Application teams must not independently establish recovery objectives that conflict with approved business requirements.

---

# 10. Threat Modeling

Significant new applications and material application changes must receive threat analysis appropriate to their risk.

Dunder Mifflin may use a lightweight threat-modeling approach.

Threat analysis should consider categories such as:

- Spoofing
- Tampering
- Repudiation
- Information disclosure
- Denial of service
- Elevation of privilege

Threat modeling must focus on meaningful application threats rather than documentation volume.

---

# 11. Threat Model Scope

Threat modeling should consider:

- Users
- Administrators
- External attackers
- Contractors
- Trust boundaries
- Application components
- Databases
- External interfaces
- Authentication
- Sensitive information
- Privileged functions

Material threats must be addressed through design, controls, testing, risk treatment, or documented acceptance.

---

# 12. Application Architecture

Significant applications must use architecture appropriate to their security and business requirements.

Architecture should consider separation of:

- User-facing services
- Application processing
- Data storage
- Administrative functions

Components must not be exposed to untrusted networks without business and technical need.

---

# 13. Infinity Architecture

Infinity must maintain logical separation between:

- Web tier
- Application tier
- Database tier

The Infinity database must not be directly accessible from the Internet.

Administrative services must not be unnecessarily exposed to the Internet.

Detailed requirements are maintained in [[STD-009 Infinity Security Standard]].

---

# 14. Development Environment

Development activity must occur in an environment appropriate to application risk.

Development environments must not be treated as production environments.

Development access must be limited to authorized personnel.

---

# 15. Test Environment

Significant application changes must be tested outside production where practical.

Test environments should support evaluation of:

- Functionality
- Security
- Integration
- Data handling
- Error conditions
- Release readiness

Production must not be used casually as the primary test environment.

---

# 16. Production Environment

Production access must be restricted according to business and technical need.

Production administrative access must follow:

- Least privilege
- Individual accountability
- Appropriate authentication
- Privileged-access requirements
- Change control
- Logging

Development responsibility alone does not automatically justify unrestricted production access.

---

# 17. Environment Separation

Development, test, and production environments must be separated for significant applications.

Separation should reduce the likelihood that:

- Development activity affects production.
- Untested code reaches production.
- Test credentials provide production access.
- Production data is unnecessarily exposed.
- Developers bypass release controls.

The degree of technical separation must reflect application risk.

---

# 18. Production Data in Nonproduction Environments

Production information must not be copied into development or test environments unnecessarily.

When production information is required for legitimate testing:

- Use must be authorized.
- Information must be protected according to classification.
- Access must be limited.
- Information should be reduced or sanitized where practical.
- Copies must be removed when no longer required.

---

# 19. Source-Code Ownership

Dunder Mifflin must retain ownership and control of source code for internally owned applications.

For Infinity, Dunder Mifflin must retain ownership and control of applicable:

- Source code
- Source repositories
- Documentation
- Business data
- Intellectual property
- Work product
- Application backups
- Recovery information

External development support must not transfer ownership of these assets unless explicitly authorized by executive management and Legal and Compliance.

---

# 20. Source Repository

Significant application source code must be maintained in a Dunder Mifflin-controlled repository or other approved source-control system.

The repository must support:

- Controlled access
- Change history
- Version identification
- Recovery
- Accountability

A contractor's private copy of source code must not serve as Dunder Mifflin's authoritative repository.

---

# 21. Source-Code Access

Source-code access must be limited according to:

- Business need
- Development responsibility
- Application sensitivity
- Contractor authorization

Access must be reviewed when personnel responsibilities change.

Access must be removed when no longer required.

---

# 22. Source-Code Backup

Source repositories and other critical development artifacts must be included in appropriate backup and recovery processes.

Backup requirements must support:

- Application recovery
- Development continuity
- Contractor replacement
- Historical version recovery

Backup existence does not eliminate the need for Dunder Mifflin-controlled source repositories.

---

# 23. Secure Development Practices

Developers must use reasonable secure-development practices appropriate to the application.

Practices should address:

- Input validation
- Output handling
- Authentication
- Authorization
- Session management
- Error handling
- Logging
- Data protection
- Database access
- Privileged functions

Application design should avoid unnecessary security complexity.

---

# 24. Input Validation

Applications receiving untrusted input must validate input appropriately.

Validation should consider:

- Expected type
- Length
- Format
- Range
- Business rules

Applications must not assume that input is trustworthy merely because it originated from a user interface controlled by Dunder Mifflin.

---

# 25. Authentication

Applications requiring user authentication must use approved authentication mechanisms.

Authentication must follow applicable requirements from:

- [[POL-003 Access Control Policy]]
- [[STD-005 Authentication & Account Security Standard]]

Applications must not unnecessarily create independent authentication mechanisms when approved enterprise authentication can reasonably be used.

---

# 26. Authorization

Applications must enforce authorization appropriate to user responsibilities.

Authorization must:

- Follow least privilege.
- Restrict privileged functions.
- Prevent ordinary users from performing unauthorized administrative activity.
- Support appropriate business-role separation.

Authentication alone does not establish authorization.

---

# 27. Administrative Functions

Application administrative functions must be limited to authorized personnel.

Administrative interfaces must:

- Use appropriate authentication.
- Be protected from unnecessary exposure.
- Follow privileged-access requirements.
- Generate appropriate accountability where practical.

Administrative functions must not be exposed publicly without documented need and appropriate protection.

---

# 28. Application Logging

Significant applications must generate logs appropriate to:

- Security monitoring
- Troubleshooting
- Incident response
- Transaction accountability
- Administrative activity

Logging must remain proportionate to application risk.

Logs must not unnecessarily record authentication secrets or other sensitive information.

---

# 29. Error Handling

Applications must handle errors in a manner that supports troubleshooting without unnecessarily exposing:

- Source code
- Database information
- Credentials
- Internal paths
- Detailed security configuration
- Other sensitive technical information

User-facing errors should provide sufficient information for legitimate use without unnecessary internal detail.

---

# 30. Sensitive Information

Applications processing Confidential or Restricted information must protect that information according to applicable classification requirements.

Protection must consider:

- Storage
- Transmission
- Access
- Logging
- Error messages
- Backup
- Test data

---

# 31. Payment Information

Infinity must use the approved external payment processor for payment-card processing.

The payment processor stores Primary Account Number (PAN) information.

Dunder Mifflin retains only approved payment references such as:

- Token
- Card brand
- Last four digits
- Expiration information where required

The retained payment token is classified as Confidential.

Infinity must not be modified to store full PAN information without formal security, business, and compliance review.

---

# 32. Cryptography

Applications requiring cryptographic protection must use approved cryptographic mechanisms appropriate to the information and purpose.

Developers must not create proprietary cryptographic algorithms for production use.

Cryptographic keys and authentication secrets must receive protection appropriate to their sensitivity.

---

# 33. Credentials in Source Code

Passwords, private keys, or other authentication secrets must not be embedded unnecessarily in application source code.

Where application credentials are technically required, they must be managed using an approved method and restricted to authorized access.

Exposure of authentication secrets in source code must be treated as a security issue.

---

# 34. Code Review

Material application changes must receive code review appropriate to risk.

Review should evaluate, as applicable:

- Correctness
- Security
- Error handling
- Authentication
- Authorization
- Input handling
- Sensitive information
- Maintainability

The developer who wrote a material change should not be the only reviewer where practical.

---

# 35. Contractor Code Review

Code produced by an external contractor remains subject to Dunder Mifflin review requirements.

Contractor status does not eliminate the need for:

- Change review
- Security review
- Testing
- Approval

Dunder Mifflin may use internal or qualified external personnel to perform review.

---

# 36. Change Management

Production application changes must follow [[POL-007 Change & Configuration Management Policy]].

Changes must address, as applicable:

- Business justification
- Risk
- Testing
- Approval
- Implementation
- Rollback
- Verification
- Documentation

Application development must not bypass enterprise change control.

---

# 37. Secure Release

A significant application release must not enter production until required:

- Testing is completed.
- Material security issues are addressed or formally accepted.
- Change approval is obtained.
- Rollback or recovery capability is prepared where practical.
- Required documentation is updated.

Release approval must reflect actual readiness.

---

# 38. Emergency Application Changes

Emergency application changes may use the emergency-change process established in [[POL-007 Change & Configuration Management Policy]].

Emergency status must not be used merely to avoid:

- Testing
- Review
- Documentation
- Approval

Post-implementation review remains required.

---

# 39. Application Security Testing

Significant applications must receive security testing appropriate to risk.

Testing may include:

- Security-focused code review
- Vulnerability testing
- Authentication testing
- Authorization testing
- Input-validation testing
- Configuration review
- Penetration testing

Testing depth must reflect application exposure and business importance.

---

# 40. Infinity Annual Security Assessment

Infinity must receive a security assessment at least annually.

The assessment must evaluate relevant areas including:

- Architecture
- Authentication
- Authorization
- Application configuration
- Internet exposure
- Data protection
- Logging
- Development controls
- Contractor access
- Known vulnerabilities
- Recovery
- Significant changes

Assessment must evaluate actual conditions rather than documentation alone.

---

# 41. Infinity Annual Penetration Test

Infinity must receive an application penetration test at least annually.

Testing must:

- Be authorized.
- Have defined scope.
- Use qualified personnel.
- Protect production availability.
- Document methodology.
- Document results.
- Identify findings.
- Support remediation.
- Support retesting.

Detailed requirements are established in [[STD-007 Penetration Testing Standard]].

---

# 42. Penetration Test Independence

Application penetration testing must provide sufficient independence from the personnel responsible for the application condition being tested.

Independence may be provided by:

- Qualified Dunder Mifflin personnel not responsible for the tested development activity
- Qualified external specialists

The required level of independence must reflect test purpose and risk.

---

# 43. Penetration Test Authorization

Penetration testing must have documented authorization before testing begins.

Authorization must define:

- Application
- Scope
- Testing period
- Approved techniques
- Restrictions
- Contacts
- Escalation
- Data-handling requirements

Technical capability to perform a test does not constitute authorization.

---

# 44. Penetration Test Evidence

Penetration testing evidence must include sufficient information to support:

- Scope
- Authorization
- Methodology
- Results
- Findings
- Remediation
- Retesting

A statement that a penetration test occurred is not sufficient evidence of application security.

---

# 45. Vulnerability Findings

Application-security weaknesses must be evaluated according to:

- Exploitability
- Business impact
- Information sensitivity
- Internet exposure
- Privilege
- Existing controls

Findings must be managed according to applicable vulnerability and corrective-action processes.

---

# 46. Vulnerability Remediation

Application vulnerabilities must be remediated according to risk.

Remediation may include:

- Code correction
- Configuration correction
- Access restriction
- Architecture change
- Compensating control
- Removal of vulnerable functionality

Material remediation must follow change-management requirements.

---

# 47. Retesting

Material application vulnerabilities must be retested after remediation when technical validation is reasonably required.

The control chain is:

**Security Test → Finding → Remediation → Retest → Control Effectiveness → Risk Reassessment**

A statement that a vulnerability was fixed is insufficient when validation can reasonably demonstrate whether the correction works.

---

# 48. Unresolved Vulnerabilities

When a material vulnerability cannot be remediated within the required timeframe, management must evaluate:

- Compensating controls
- Reduced exposure
- Function restriction
- Additional monitoring
- Temporary shutdown
- Risk acceptance

Risk acceptance must follow [[POL-005 Risk Management Policy]].

---

# 49. Vulnerability Management Integration

Application vulnerabilities must be coordinated with [[PRO-004 Vulnerability Management Program]] where applicable.

Application testing and infrastructure vulnerability management are related but distinct activities.

A network vulnerability scan does not replace application-security testing.

---

# 50. Contractor Development Access

External developers must receive only the access necessary to perform authorized work.

Access must:

- Have an identified sponsor.
- Be individually attributable where practical.
- Follow least privilege.
- Be time limited.
- Be reviewed.
- Be removed when no longer required.

Requirements are established in [[POL-003 Access Control Policy]] and [[POL-008 Third-Party Security Policy]].

---

# 51. Infinity Contractor Authentication

Infinity contractors must use smart-card multi-factor authentication where supported for applicable access.

Authentication must combine the smart card with a PIN or other approved secret.

Authentication requirements do not independently authorize production access.

---

# 52. Infinity Contractor Production Access

Infinity contractors must not receive general remote VPN access for privileged production administration.

Privileged production or administrative work must occur from the designated controlled contractor workspace at Dunder Mifflin headquarters.

Access must follow applicable:

- Authentication requirements
- Privileged-access requirements
- Change management
- Logging
- Physical-security requirements

---

# 53. Infinity Contractor Scheduling

Expected Infinity contractor personnel names should be provided at least one business day before scheduled access when practical.

Emergency support may receive an exception when advance notice is not practical.

Emergency access must remain:

- Authorized
- Documented
- Limited to legitimate need
- Reviewed afterward where appropriate

---

# 54. Contractor Confidentiality

External developers and support personnel must have appropriate enforceable confidentiality obligations before receiving sensitive access.

Confidentiality obligations do not independently demonstrate:

- Technical competence
- Effective security controls
- Appropriate access
- Adequate testing
- Adequate documentation
- Adequate contractor oversight

These requirements must be evaluated separately.

---

# 55. Contractor Work Product

Application contracts must ensure that required work product is available to Dunder Mifflin.

Work product may include:

- Source code
- Documentation
- Configuration information
- Build instructions
- Deployment instructions
- Test information
- Recovery information

Required company assets must not exist solely under contractor control.

---

# 56. Application Documentation

Significant applications must maintain documentation appropriate to their complexity and business importance.

Documentation may include:

- Architecture
- Dependencies
- Interfaces
- Configuration
- Build process
- Deployment
- Authentication
- Authorization
- Recovery
- Administrative procedures
- Known operational requirements

Documentation must support continued operation and personnel replacement.

---

# 57. Infinity Documentation

Infinity documentation must be sufficient for a qualified development or support organization unfamiliar with the application to understand its significant:

- Architecture
- Source structure
- Dependencies
- Configuration
- Deployment
- Database requirements
- Administrative requirements
- Recovery process

Documentation must remain under Dunder Mifflin control.

---

# 58. Knowledge Concentration

Application support must avoid unnecessary dependence on a single:

- Employee
- Developer
- Contractor
- Consultant

Risk reduction may include:

- Documentation
- Source-code ownership
- Repository control
- Cross-training
- Knowledge transfer
- Transferability review

---

# 59. Infinity Transferability

Infinity must receive a transferability review at least annually.

The review must determine whether a qualified replacement development organization could reasonably assume support using Dunder Mifflin-controlled assets.

The review must consider:

- Source code
- Repository
- Documentation
- Architecture
- Configuration
- Build information
- Deployment information
- Dependencies
- Recovery information
- Business requirements

Results are documented in [[RPT-004 Infinity Transferability Review]].

---

# 60. Transferability Findings

Transferability deficiencies may include:

- Missing source code
- Contractor-controlled repository
- Missing documentation
- Undocumented build process
- Undocumented deployment process
- Unknown dependencies
- Missing recovery information
- Exclusive contractor knowledge

Material deficiencies must receive corrective action.

---

# 61. Application Recovery

Significant applications must have recovery capability appropriate to business requirements.

Recovery must consider:

- Source code
- Application binaries
- Configuration
- Database
- Dependencies
- Authentication
- Documentation
- Required infrastructure

Recovery requirements must align with [[POL-010 Business Continuity & Disaster Recovery Policy]].

---

# 62. Application Backup

Application backup must include information required to restore the application where applicable.

Backup coverage may include:

- Source repository
- Application data
- Configuration
- Database
- Required deployment artifacts
- Supporting documentation

Backup coverage must be validated rather than assumed.

---

# 63. Recovery Documentation

Application recovery documentation must be sufficient for qualified personnel to restore required application capability.

Significant application changes must trigger review of recovery documentation according to [[POL-007 Change & Configuration Management Policy]].

---

# 64. Application Dependencies

Significant application dependencies must be documented sufficiently to support:

- Security analysis
- Change management
- Recovery
- Incident response
- Transferability

Dependencies may include:

- Databases
- Authentication
- Cloud hosting
- Network services
- External services
- Payment processing
- Other applications

Unknown dependencies create operational and recovery risk.

---

# 65. Third-Party Components

Use of third-party software components must consider:

- Business need
- Security
- Supportability
- Known vulnerabilities
- Licensing
- Maintenance

Components with known material security weaknesses must be evaluated and remediated according to risk.

---

# 66. Unsupported Components

Unsupported or obsolete application components must be evaluated for risk.

Possible responses include:

- Upgrade
- Replacement
- Isolation
- Compensating controls
- Removal
- Risk acceptance

Unsupported status alone does not determine risk without considering exposure and impact.

---

# 67. Application Interfaces

Application interfaces must be protected according to:

- Information sensitivity
- Authentication requirements
- Authorization
- Exposure
- Business function

Interfaces must not provide broader access than required.

---

# 68. Database Security

Application databases must:

- Be restricted to authorized access.
- Avoid unnecessary Internet exposure.
- Use appropriate authentication.
- Limit administrative access.
- Support backup and recovery.
- Protect sensitive information.

Infinity's production database must not be directly accessible from the Internet.

---

# 69. Data Integrity

Applications performing significant business transactions must support appropriate data integrity.

Controls may include:

- Validation
- Authorization
- Transaction accountability
- Reconciliation
- Controlled changes
- Backup
- Recovery

Suspected material corruption must be investigated.

---

# 70. Application Security Incidents

Suspected application compromise must be handled under [[POL-009 Incident Response Policy]].

Response may include:

- Access restriction
- Account disablement
- Application isolation
- Log review
- Contractor coordination
- Vulnerability analysis
- Evidence preservation
- Recovery

Infinity incidents must use applicable incident-response playbooks.

---

# 71. Application Logs During Incidents

Application logs required for incident analysis must be preserved when practical.

Preservation must follow [[PROC-011 Evidence Handling Procedure]] when formal evidence handling is required.

Logging must support reasonable reconstruction of significant security activity.

---

# 72. Secure Development Training

Developers and personnel performing significant application-security responsibilities must receive training appropriate to their roles.

Training may address:

- Secure coding
- Authentication
- Authorization
- Input validation
- Error handling
- Data protection
- Threat modeling
- Code review
- Security testing

Requirements are established in [[POL-006 Security Awareness & Training Policy]].

---

# 73. Bug Reporting

Dunder Mifflin should provide a reasonable method for employees, customers, researchers, or other persons to report suspected Infinity security weaknesses.

Reports must be:

- Received
- Evaluated
- Prioritized
- Escalated where appropriate

Good-faith reports must not be ignored solely because they originated outside the formal development process.

---

# 74. Security Bug Recognition

Dunder Mifflin may provide recognition or a discretionary reward for a responsibly reported, validated Infinity security vulnerability.

Any reward:

- Must be authorized.
- Must reflect vulnerability significance.
- Must not exceed **$500** without separate executive approval.
- Does not create an automatic entitlement to payment.

The program is intended to encourage responsible reporting rather than unauthorized testing.

---

# 75. Authorization to Test

A vulnerability-reporting mechanism does not provide general authorization to:

- Penetrate systems
- Access other users' information
- Disrupt services
- Modify production data
- Exceed explicitly authorized testing

Formal penetration testing requires documented authorization under [[STD-007 Penetration Testing Standard]].

---

# 76. Application Retirement

Application retirement must address:

- Information retention
- Information destruction
- Account removal
- Interface removal
- Infrastructure removal
- Backup requirements
- Documentation
- Contract termination
- Dependency removal

Retired applications must not remain unnecessarily exposed or administratively accessible.

---

# 77. Application Inventory

Significant applications must be reflected in [[REG-001 Enterprise Asset Register]].

The inventory must support identification of:

- Owner
- Business purpose
- Information
- Criticality
- Dependencies
- Relevant security requirements

Material application changes must trigger asset-record review.

---

# 78. Application Risk Review

Significant application changes must be evaluated for risk.

Risk review may determine whether:

- Existing risk changed.
- A new risk exists.
- Existing treatment remains appropriate.
- Additional controls are required.
- Target residual risk should be revised.

Risk-management requirements are established in [[POL-005 Risk Management Policy]].

---

# 79. Findings

Material application-security deficiencies must be documented.

Examples include:

- Authentication weakness
- Authorization weakness
- Internet-exposed administrative function
- Significant input-validation vulnerability
- Sensitive information exposure
- Missing security testing
- Missing code review
- Inadequate contractor restriction
- Missing source code
- Missing recovery documentation
- Failed penetration-test remediation
- Transferability deficiency

Material corrective actions must be tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 80. Corrective Action

Application-security corrective action must identify, as appropriate:

- Finding
- Application
- Affected control
- Associated risk
- Responsible party
- Required remediation
- Due date
- Expected evidence
- Retest requirement

Corrective action must remain open until required remediation and validation are complete.

---

# 81. Application Security Metrics

Application-security metrics may include:

- Security assessments completed
- Penetration tests completed
- Open application vulnerabilities
- Vulnerabilities by severity
- Overdue remediation
- Retests completed
- Failed retests
- Unauthorized production changes
- Contractor access exceptions
- Transferability findings
- Open application corrective actions

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 82. Metric Interpretation

Application-security metrics must be interpreted in context.

For example:

- More findings may reflect better testing rather than worsening security.
- A completed penetration test does not prove vulnerabilities were corrected.
- A closed finding does not prove remediation was effective unless required validation occurred.
- Low vulnerability counts do not prove adequate testing occurred.

Metrics must support security decisions rather than encourage artificial reduction of reported findings.

---

# 83. Assessment

Application and development controls must be periodically assessed.

Assessment may include:

- Inspection
- Interviews
- Observation
- Code review
- Configuration review
- Technical Testing
- Penetration testing
- Sampling
- Independent Performance
- Documentation review

Assessment must evaluate actual control operation rather than written requirements alone.

---

# 84. Evidence

Application-security evidence may include:

- Requirements
- Threat models
- Architecture documentation
- Source-control records
- Code-review records
- Change records
- Test results
- Penetration-test reports
- Findings
- Remediation records
- Retest results
- Contractor access records
- Recovery records
- Transferability reviews

Evidence must accurately represent actual activity.

---

# 85. Evidence Integrity

Personnel must not:

- Manufacture code-review records.
- Record testing that did not occur.
- Alter penetration-test results to conceal findings.
- Represent untested remediation as validated.
- Conceal material application vulnerabilities.
- Represent missing source code as company controlled.
- Record transferability review activities that did not occur.

Known deficiencies must be documented and managed.

---

# 86. Risk Relationships

This policy provides significant treatment support for risks including:

- R003 Ransomware
- R004 Malware
- R005 Password / Authentication Weakness
- R006 Infinity Application Compromise
- R009 Sensitive Information Theft / Extortion
- R010 Unauthorized / Excessive Access
- R012 Malicious Insider
- R013 Administrative / Configuration Error
- R018 Third-Party Technology Failure / Compromise
- R019 Infinity Contractor Dependency / Compromise
- R027 Backup / Recovery Failure
- R028 Data Corruption

Risk treatment is documented in [[RTP-001 Enterprise Risk Treatment Plan]].

---

# 87. Exceptions

Exceptions to this policy require:

- Documented business justification
- Affected requirement
- Associated risk
- Defined duration
- Compensating controls where practical
- Responsible owner
- Appropriate approval

High or Critical residual risk resulting from an exception requires escalation according to [[POL-005 Risk Management Policy]].

Emergency application changes remain subject to the emergency-change requirements of [[POL-007 Change & Configuration Management Policy]].

---

# 88. Enforcement

Failure to comply with this policy may result in:

- Release rejection
- Production-access restriction
- Corrective action
- Management review
- Contractor action
- Personnel action
- Risk escalation
- Contractual action

Intentional unauthorized modification of production applications must be escalated according to risk.

---

# 89. Policy Review

This policy must be reviewed:

- At least annually
- Following material application changes
- Following significant application-security incidents
- Following significant penetration-test findings
- Following significant assessment findings
- Following material development-process changes
- When significant contractor relationships change

The CIO coordinates review.

Material revisions require CEO approval.

---

# 90. Traceability

Application security must support the enterprise security lifecycle:

**Business Requirement → Application → Information / Criticality → Threat → Risk → Security Requirement → Control → Secure Development Activity → Implementation → Evidence → Security Test → Finding → Remediation → Retest → Control Effectiveness → Risk Reassessment**

Detailed relationships are maintained through [[REG-007 Cross-Reference Matrix]].

---

# 91. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-007 Secure Software Development Lifecycle Program]]
- [[PRO-009 Security Governance Framework]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-006 Security Awareness & Training Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[STD-001 Information Classification Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-007 Penetration Testing Standard]]
- [[STD-009 Infinity Security Standard]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-019 Application Security Assessment Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-004 Infinity Transferability Review]]
- [[REG-001 Enterprise Asset Register]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[REG-007 Cross-Reference Matrix]]

---

# 92. Revision History

| Version | Date     | Description                                     | Approval |
| ------- | -------- | ----------------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Application & Secure Development Policy | CEO      |