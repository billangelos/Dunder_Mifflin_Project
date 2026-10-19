# PRO-007 Secure Software Development Lifecycle Program

## Document Control

| Field | Value |
|---|---|
| Document ID | PRO-007 |
| Title | Secure Software Development Lifecycle Program |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Application, Development, Architecture, or Security Change |

---

# 1. Purpose

This program establishes Dunder Mifflin's Secure Software Development Lifecycle (SDLC) requirements.

The program integrates security into:

**Requirements → Design → Development → Testing → Release → Operation → Maintenance → Retirement**

The program is centered on Infinity, Dunder Mifflin's internally owned customer-facing application, but applies to other internally developed software where appropriate.

---

# 2. Objectives

The Secure SDLC program is intended to:

- Identify security requirements before implementation.
- Reduce application vulnerabilities.
- Protect company-owned source code.
- Maintain development accountability.
- Separate development, testing, and production activities.
- Control application changes.
- Protect production systems.
- Manage contractor development access.
- Test application security.
- Remediate identified vulnerabilities.
- Preserve application documentation.
- Reduce dependency on individual developers or contractors.
- Support application recovery and transferability.

---

# 3. Scope

This program applies to:

- Infinity
- Internally developed applications
- Internally maintained application code
- Application source code
- Application repositories
- Application documentation
- Application databases
- Development environments
- Test environments
- Production environments
- Application releases
- Application security assessments
- Contractors performing development or application-support work

---

# 4. Infinity

Infinity is Dunder Mifflin's internally developed online ordering application.

Infinity supports customer interaction with the company and connects customer ordering activity with the company's broader order-fulfillment process.

---

# 5. Infinity Ownership

Dunder Mifflin owns:

- Infinity application
- Source code
- Source-code repository
- Application data
- Application documentation
- Application backups
- Intellectual property
- Contract work product

Contractor involvement does not transfer ownership of these assets.

---

# 6. Contractor Role

The original Infinity development team is no longer responsible for supporting the application.

A third-party contractor provides application support and development services.

---

# 7. Contractor Dependency

Contractor support creates a dependency that must be managed.

Dunder Mifflin must maintain sufficient:

- Source-code control
- Documentation
- Credentials
- Configuration information
- Recovery information
- Internal oversight

to avoid unnecessary dependence on the contractor.

---

# 8. Authority

This program operates under:

- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-012 Application & Secure Development Policy]]

---

# 9. Security Standard

Detailed Infinity security requirements are established by [[STD-009 Infinity Security Standard]].

---

# 10. Development Procedures

Application development and contractor activities are supported by:

- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-019 Application Security Assessment Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]

---

# 11. Secure SDLC Principle

Security must be considered throughout the application lifecycle rather than only after development is complete.

---

# 12. Risk-Based Development

Security effort should be proportionate to:

- Application criticality
- Information sensitivity
- Internet exposure
- User population
- Business impact
- Privilege
- Architecture
- Known threats
- Identified vulnerabilities

---

# 13. Security Requirements

Security requirements should be identified during application planning or change design.

Requirements may include:

- Authentication
- Authorization
- Input validation
- Session management
- Error handling
- Logging
- Data protection
- Administrative access
- Network exposure
- Recovery
- Availability

---

# 14. Business Requirements

Application security must support legitimate business requirements rather than being designed independently from the business process.

---

# 15. Information Classification

Application information must be classified according to:

- [[POL-004 Information Classification & Handling Policy]]
- [[STD-001 Information Classification Standard]]

---

# 16. Payment Information

Dunder Mifflin's payment processor stores payment card numbers.

Dunder Mifflin retains only applicable payment information such as:

- Payment token
- Card brand
- Last four digits
- Expiration information

Dunder Mifflin does not intentionally retain full payment card numbers within Infinity.

---

# 17. Payment Token Classification

Payment tokens are treated as Confidential information.

---

# 18. Data Minimization

Applications should collect and retain only information reasonably necessary for legitimate business purposes.

---

# 19. Sensitive Data

Sensitive application information must receive protection appropriate to its classification.

---

# 20. Security Architecture

Application security must coordinate with [[PRO-002 Enterprise Security Architecture Program]].

---

# 21. Infinity Architecture

Infinity uses logical separation among:

- Web tier
- Application tier
- Database tier

---

# 22. Internet Exposure

The public-facing Infinity web tier may receive Internet traffic required for customer use.

---

# 23. Database Exposure

The Infinity database must not be directly accessible from the public Internet.

---

# 24. Administrative Exposure

Administrative interfaces must not be unnecessarily exposed to the public Internet.

---

# 25. Network Controls

Infinity network protections must comply with [[STD-002 Network Security Standard]].

---

# 26. Server Controls

Infinity servers must comply with [[STD-004 Server Security Standard]] where applicable.

---

# 27. Authentication Controls

Infinity authentication and administrative access must comply with [[STD-005 Authentication & Account Security Standard]] where applicable.

---

# 28. Secure Configuration

Infinity components must comply with [[STD-006 Secure Configuration Standard]] where applicable.

---

# 29. Environment Separation

Development, test, and production environments must be logically separated.

---

# 30. Development Environment

Development activity should occur in an environment intended for software development rather than directly within production.

---

# 31. Test Environment

Application changes should be tested outside production before release where practical.

---

# 32. Production Environment

Production must be treated as the authoritative live business environment.

Production access must be more restricted than ordinary development access.

---

# 33. Production Development

Routine software development must not occur directly in production.

---

# 34. Emergency Production Change

A legitimate emergency may require an expedited production change.

Emergency changes must comply with [[POL-007 Change & Configuration Management Policy]] and [[PROC-018 Secure Change & Release Procedure]].

---

# 35. Production Data

Production information must not be copied unnecessarily into development or test environments.

---

# 36. Sensitive Test Data

Where production-derived information is required for testing, sensitive information should be minimized or appropriately protected.

---

# 37. Source-Code Repository

Dunder Mifflin must maintain control of the authoritative Infinity source-code repository.

---

# 38. Repository Access

Repository access must be limited according to:

- Development responsibility
- Support responsibility
- Business need

---

# 39. Source-Code Accountability

Source-code changes should be attributable to an authorized individual.

---

# 40. Source-Code Protection

Source code must be protected against:

- Unauthorized access
- Unauthorized modification
- Accidental loss
- Uncontrolled deletion
- Unnecessary disclosure

---

# 41. Source-Code Backup

Source code and associated documentation must be included in appropriate backup and recovery processes.

---

# 42. Repository Independence

The authoritative source-code repository must not exist solely under the control of an outside contractor.

---

# 43. Contractor Work Product

Contractor-developed:

- Source code
- Scripts
- Configuration
- Documentation
- Other application work product

created for Dunder Mifflin must remain under company control according to contractual requirements.

---

# 44. Development Accountability

Application development activity must maintain sufficient accountability to determine:

- Who made a change
- What changed
- Why the change was made
- Whether the change was reviewed
- Whether the change was tested
- Whether the change was approved for release

---

# 45. Change Management

Application changes must comply with [[POL-007 Change & Configuration Management Policy]].

---

# 46. Change Categories

Application changes may be handled as:

- Standard
- Normal
- Emergency

according to the Change & Configuration Management Policy.

---

# 47. Change Request

A material application change should identify:

- Business purpose
- Affected component
- Requested change
- Security impact where relevant
- Testing requirement
- Rollback approach
- Required approval

---

# 48. Security Impact Review

Changes affecting security-sensitive functionality require explicit consideration of security impact.

Examples include changes to:

- Authentication
- Authorization
- Session handling
- Input processing
- Database access
- Administrative functions
- Sensitive data
- External interfaces
- Logging

---

# 49. Code Review

Material or security-sensitive code changes should receive review by another qualified person where practical.

---

# 50. Review Independence

The person reviewing a significant security-sensitive change should not rely solely on the developer's assertion that the change is secure.

---

# 51. Review Scope

Code review may consider:

- Logic
- Security requirements
- Input handling
- Authorization
- Error handling
- Data exposure
- Logging
- Unintended functionality
- Known insecure patterns

---

# 52. Small-Team Limitation

Dunder Mifflin may not always have enough internal developers to provide complete development-role separation.

Where full Separation of Duties is impractical, compensating review and approval should be used.

---

# 53. Threat Modeling

Material Infinity changes should receive lightweight threat modeling.

---

# 54. Threat Modeling Objective

Threat modeling is intended to identify:

- Important assets
- Trust boundaries
- Entry points
- Threats
- Security assumptions
- Required protections

before or during design.

---

# 55. STRIDE

STRIDE may be used as a practical threat-modeling method.

STRIDE considers:

- Spoofing
- Tampering
- Repudiation
- Information Disclosure
- Denial of Service
- Elevation of Privilege

---

# 56. Threat Modeling Scope

Threat modeling should be proportionate to the change.

A small low-risk change does not require the same analysis as:

- New authentication functionality
- New Internet-facing capability
- New sensitive-data processing
- Major architecture change

---

# 57. Threat Model Documentation

A material threat model should document:

- Scope
- Important components
- Important data
- Trust boundaries
- Significant threats
- Planned controls
- Unresolved concerns

---

# 58. Security Design Review

Security-sensitive design decisions should be reviewed before release where practical.

---

# 59. Input Validation

Applications must validate untrusted input appropriately.

---

# 60. Server-Side Validation

Security-sensitive validation must not depend solely on client-side controls.

---

# 61. Input Handling

Application input should be handled in a manner that reduces risks such as:

- Injection
- Invalid data
- Unexpected commands
- Application errors
- Unauthorized data manipulation

---

# 62. Database Queries

Database access should use secure application-development practices that reduce injection risk.

---

# 63. Output Handling

Application output should be handled appropriately to reduce unintended execution or disclosure.

---

# 64. Authentication

Authentication mechanisms must protect against unauthorized account use.

---

# 65. Authorization

Application authorization must be enforced based on the user's permitted functions and data.

---

# 66. Server-Side Authorization

Security-sensitive authorization decisions must be enforced by trusted application components rather than relying solely on the user interface.

---

# 67. Privilege

Application users must not receive unnecessary administrative or elevated privileges.

---

# 68. Administrative Functions

Administrative functionality must be restricted to specifically authorized personnel.

---

# 69. Session Management

Authenticated sessions must be managed to reduce unauthorized reuse or hijacking.

---

# 70. Credentials

Applications must not unnecessarily expose:

- Passwords
- Authentication secrets
- Administrative credentials
- Service-account credentials

---

# 71. Hard-Coded Credentials

Passwords or other authentication secrets should not be unnecessarily hard-coded in source code.

---

# 72. Service Accounts

Application service accounts must be managed according to applicable authentication and account-security requirements.

---

# 73. Error Handling

Application errors should provide enough information to support legitimate troubleshooting without unnecessarily exposing sensitive technical details to users.

---

# 74. Error Messages

Public-facing error messages should avoid unnecessary disclosure of:

- Credentials
- Database information
- Internal paths
- Sensitive configuration
- Other security-sensitive technical details

---

# 75. Logging

Infinity should generate logs sufficient to support:

- Operations
- Troubleshooting
- Security monitoring
- Incident investigation

---

# 76. Security-Relevant Events

Security-relevant application events may include:

- Authentication failure
- Administrative activity
- Significant authorization failure
- Application error
- Significant security-control failure
- Other suspicious activity

---

# 77. Logging Limitation

Application logging must avoid unnecessarily recording:

- Passwords
- Authentication secrets
- Full payment card numbers
- Other sensitive information not required for legitimate logging

---

# 78. Log Protection

Application logs must be protected from unauthorized modification or unnecessary disclosure.

---

# 79. Security Monitoring

Application-security events should support the monitoring processes established by [[PRO-005 Security Operations Program]] and [[PROC-008 Security Monitoring Procedure]].

---

# 80. Security Event Escalation

Material application-security events must be escalated according to [[PROC-010 Security Event Escalation Procedure]].

---

# 81. Incident Response

Application-security incidents must be handled under [[PLN-001 Incident Response Plan]].

---

# 82. Unauthorized Access

Suspected unauthorized Infinity access may require [[PBK-003 Unauthorized Access Playbook]].

---

# 83. Data Exposure

Suspected exposure of Infinity information may require [[PBK-004 Data Exposure Playbook]].

---

# 84. Third-Party Incident

An Infinity incident involving the support contractor may require [[PBK-005 Third-Party Incident Playbook]].

---

# 85. Secure Development Testing

Application changes must receive testing appropriate to their:

- Scope
- Risk
- Security impact
- Business impact

---

# 86. Functional Testing

Application changes should be tested to determine whether the intended functionality works as expected.

---

# 87. Security Testing

Security-sensitive changes should receive appropriate security testing.

---

# 88. Security Test Methods

Security testing may include:

- Manual review
- Code review
- Input testing
- Authentication testing
- Authorization testing
- Configuration review
- Vulnerability testing
- Penetration testing

depending on scope and risk.

---

# 89. Testing Independence

Security conclusions should not rely solely on the developer who created the change when reasonable independent review is available.

---

# 90. Test Evidence

Material testing should provide evidence sufficient to determine:

- What was tested
- Who performed the test
- When testing occurred
- What result occurred
- Whether significant defects were identified
- Whether remediation was required

---

# 91. Failed Test

A failed security test must not be treated as successful merely because the application remains functional.

---

# 92. Defect Correction

Material security defects must be:

- Documented
- Prioritized
- Corrected or otherwise addressed
- Retested where appropriate

---

# 93. Vulnerability Management

Application vulnerabilities must coordinate with [[PRO-004 Vulnerability Management Program]].

---

# 94. Vulnerability Remediation

Application vulnerabilities must be prioritized according to:

- Severity
- Exploitability
- Internet exposure
- Information sensitivity
- Business impact
- Existing controls

---

# 95. Remediation Procedure

Application vulnerability remediation and retesting must comply with [[PROC-007 Vulnerability Remediation & Retest Procedure]].

---

# 96. Remediation Deadlines

Applicable vulnerability-remediation targets are:

| Severity | Target |
|---|---:|
| Critical | 7 days |
| High | 30 days |
| Moderate | 45 days |
| Low | 60 days |

Risk-based exceptions must follow approved exception processes.

---

# 97. Security Finding

A security finding is not closed solely because code was changed.

The corrective action must be validated.

---

# 98. Retesting

Security findings requiring technical correction should be retested where appropriate.

---

# 99. Retest Result

Retest should determine whether:

- The original weakness was corrected.
- The correction introduced another material weakness.
- Additional action is required.

---

# 100. Application Security Assessment

Infinity must receive an annual application security assessment.

---

# 101. Annual Assessment Scope

The annual Infinity security assessment should evaluate areas such as:

- Architecture
- Authentication
- Authorization
- Input handling
- Session management
- Sensitive-data protection
- Administrative access
- Configuration
- Logging
- Contractor access
- Development controls
- Significant vulnerabilities

---

# 102. Application Penetration Testing

Infinity must receive application penetration testing at least annually.

---

# 103. Penetration Testing Standard

Infinity penetration testing must comply with [[STD-007 Penetration Testing Standard]].

---

# 104. Penetration Test Authorization

Penetration testing must have documented authorization and defined scope before testing begins.

---

# 105. Penetration Test Scope

Scope should identify:

- Application
- Environment
- Authorized targets
- Testing limitations
- Testing period
- Responsible personnel

---

# 106. Penetration Test Evidence

Penetration-test evidence should identify:

- Scope
- Authorization
- Method
- Test activity
- Results
- Findings
- Remediation
- Retest where applicable

---

# 107. Penetration Test Chain

Infinity penetration testing supports the assurance chain:

**Penetration Test → Finding → Remediation → Retest → Control Effectiveness → R006 Risk Reassessment**

---

# 108. Annual Assessment Is Not Continuous Proof

Completion of an annual assessment does not establish that Infinity remains free from vulnerabilities for the rest of the year.

---

# 109. Assessment Findings

Material Infinity findings must be tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 110. Finding Ownership

Each material finding must have an accountable owner.

---

# 111. Corrective Action

Corrective action must identify:

- Finding
- Required action
- Accountable owner
- Due date
- Validation method
- Retest requirement where applicable

---

# 112. Finding Closure

A finding must not be closed solely because:

- A developer states it was fixed.
- Code was committed.
- A ticket was marked complete.
- A configuration was changed.

Closure requires appropriate validation.

---

# 113. Release Management

Application releases must follow a controlled release process.

---

# 114. Release Authorization

A release should not enter production until appropriate:

- Testing
- Review
- Approval

has occurred.

---

# 115. Release Package

A material release should identify:

- Included changes
- Required configuration
- Dependencies
- Database changes where applicable
- Deployment steps
- Validation steps
- Rollback approach

---

# 116. Production Deployment

Production deployment must be performed by authorized personnel.

---

# 117. Deployment Verification

After deployment, responsible personnel should confirm:

- Application availability
- Intended functionality
- Required configuration
- Security-sensitive functionality where applicable
- No immediately apparent material failure

---

# 118. Rollback

Material releases must have a reasonable rollback approach where technically practical.

---

# 119. Failed Deployment

If a release causes unacceptable:

- Security
- Availability
- Integrity
- Functional

impact, rollback or corrective action should be initiated.

---

# 120. Emergency Release

An emergency release may use expedited review but must still be:

- Authorized
- Documented
- Tested as reasonably possible
- Verified after implementation
- Reviewed afterward

---

# 121. Change Evidence

Material application-change evidence should include as applicable:

- Change request
- Approval
- Code change
- Review
- Testing
- Deployment
- Validation
- Rollback information
- Exception

---

# 122. Configuration Management

Application configuration must be managed under [[POL-007 Change & Configuration Management Policy]] and [[STD-006 Secure Configuration Standard]].

---

# 123. Configuration Baseline

Important application configuration should have an identifiable approved state.

---

# 124. Unauthorized Configuration Change

Suspected unauthorized application configuration change must be investigated.

---

# 125. Configuration Backup

Important application configuration required for recovery must be appropriately backed up or documented.

---

# 126. Application Recovery

Application development and support must coordinate with:

- [[PLN-003 Disaster Recovery Plan]]
- [[PROC-012 Backup & Recovery Procedure]]

---

# 127. Recovery Documentation

Infinity recovery documentation must be sufficient for a qualified Information Technology professional unfamiliar with the environment to perform required recovery activities.

---

# 128. Recovery Dependency

Infinity recovery must not depend solely on undocumented contractor knowledge.

---

# 129. Recovery Testing

Infinity should participate in appropriate recovery testing based on Business Impact Analysis requirements.

---

# 130. Infinity BIA Requirement

Infinity has:

- Business Criticality: **Moderate**
- Maximum Tolerable Downtime: **3 days**
- Recovery Time Objective: **24 hours**
- Recovery Point Objective: **4 hours**

---

# 131. BIA Authority

Recovery requirements are established by [[RPT-002 Business Impact Analysis]].

The Secure SDLC program does not independently redefine them.

---

# 132. Recovery Requirement Is Not Proof

The existence of an RTO or RPO does not demonstrate that the requirement can be achieved.

Recovery capability must be validated through testing.

---

# 133. Application Documentation

Infinity documentation should include sufficient information to support:

- Development
- Support
- Security assessment
- Recovery
- Maintenance
- Contractor transition

---

# 134. Documentation Types

Documentation may include:

- Architecture
- Application components
- Dependencies
- Data flows
- Configuration
- Deployment
- Recovery
- Administrative procedures
- Development procedures
- Important external services

---

# 135. Documentation Maintenance

Material application changes must include review of affected documentation.

---

# 136. Documentation Completion

A significant technical change should not be considered complete until affected recovery and operational documentation has been reviewed and updated where necessary.

---

# 137. Transferability

Dunder Mifflin must maintain Infinity in a condition that can reasonably be transferred to another qualified development or support provider.

---

# 138. Transferability Objective

Transferability reduces dependence on:

- One contractor
- One developer
- Undocumented knowledge
- Contractor-controlled credentials
- Contractor-controlled source code
- Contractor-controlled infrastructure knowledge

---

# 139. Transferability Review

Infinity transferability must be reviewed at least annually.

---

# 140. Transferability Artifact

Transferability review results are documented in [[RPT-004 Infinity Transferability Review]].

---

# 141. Transferability Review Scope

The review should consider whether Dunder Mifflin controls or can access:

- Current source code
- Repository
- Build information
- Deployment procedures
- Architecture documentation
- Configuration information
- Required credentials
- Database information
- Recovery information
- Contractor work product
- Relevant vendor contacts

---

# 142. Transferability Finding

A material dependency preventing reasonable transfer must be documented as a finding.

---

# 143. Contractor Development Access

Contractor development access must comply with [[PROC-020 Contractor Development Access Procedure]].

---

# 144. Contractor Sponsorship

Contractor access requires an identified Dunder Mifflin sponsor.

---

# 145. Contractor Access Duration

Contractor access must be time-limited and periodically renewed according to [[PROC-004 Contractor Access Procedure]].

---

# 146. Contractor Least Privilege

Contractor access must be limited to systems, environments, repositories, and information required for authorized work.

---

# 147. Contractor Production Access

Production access must be specifically authorized and more restricted than ordinary development access.

---

# 148. Contractor Privileged Access

Privileged contractor production or administrative activity must use individually attributable authorized credentials.

---

# 149. Contractor Physical Location

Privileged Infinity contractor production or administrative work is performed from a designated controlled workspace at Scranton Headquarters when required.

---

# 150. No General Contractor VPN

The Infinity contractor does not receive general VPN access for privileged production administration.

Routine external remote privileged administration is not authorized.

---

# 151. Contractor Personnel Notice

Expected Infinity contractor personnel should be identified at least one business day before scheduled arrival where practical.

---

# 152. Emergency Contractor Exception

An emergency may require contractor personnel who could not reasonably be identified one business day in advance.

The exception must be documented.

---

# 153. Contractor Physical Access

Contractor physical access must comply with:

- [[PROC-014 Facility Access Procedure]]
- [[PROC-015 Visitor & Vendor Access Procedure]]
- [[PROC-016 Restricted Area Access Procedure]]

where applicable.

---

# 154. Contractor Confidentiality

Appropriate confidentiality obligations must exist before contractor personnel receive sensitive information.

---

# 155. Contractor Change Control

Contractor personnel must not bypass Dunder Mifflin change-control requirements.

---

# 156. Contractor Repository Access

Contractor repository access must be:

- Authorized
- Individually attributable
- Limited to business need
- Removed when no longer required

---

# 157. Contractor Departure

When contractor personnel no longer require access:

- Repository access must be removed.
- Application access must be removed.
- Production access must be removed.
- Physical access must be removed.
- Company credentials must be recovered or disabled.
- Company information must remain under company control.

---

# 158. Contractor Replacement

A change in contractor must not result in loss of Dunder Mifflin's:

- Source code
- Documentation
- Credentials
- Configuration information
- Application data
- Recovery capability

---

# 159. Third-Party Security

The Infinity contractor is treated as a Critical third party under [[POL-008 Third-Party Security Policy]].

---

# 160. Critical Provider Review

Critical third parties are subject to annual security review according to the Third-Party Security Policy.

---

# 161. Third-Party Incident Notice

Applicable third-party agreements should require notification of material security incidents within 24 hours of discovery.

---

# 162. Contractor Security Does Not Replace Internal Responsibility

Use of a contractor does not transfer Dunder Mifflin's responsibility for:

- Risk ownership
- Security requirements
- Access authorization
- Change approval
- Application ownership
- Security assessment
- Recovery

---

# 163. Open-Source and Third-Party Components

Third-party software components used by an application should be understood sufficiently to manage associated security risk.

---

# 164. Component Risk

Known material vulnerabilities in application components must be evaluated and remediated according to risk.

---

# 165. Component Inventory

For significant application components, Dunder Mifflin should maintain sufficient documentation to identify important third-party dependencies where practical.

---

# 166. Unsupported Component

Use of an unsupported or materially insecure application component must be evaluated for:

- Replacement
- Upgrade
- Compensating control
- Risk acceptance

---

# 167. External Interfaces

Application interfaces with external systems or services must be documented and protected according to risk.

---

# 168. Interface Security

Security considerations for external interfaces may include:

- Authentication
- Authorization
- Data validation
- Encryption
- Error handling
- Availability
- Logging

---

# 169. Payment Processor

Infinity's payment-processing relationship must avoid unnecessary storage of full payment card numbers by Dunder Mifflin.

---

# 170. Payment Processor Dependency

Failure or compromise of the payment provider may affect Infinity and must be considered within third-party and continuity risk management.

---

# 171. Security Defect Reporting

Application-security defects identified through:

- Development
- Testing
- Operations
- Security monitoring
- Assessment
- Penetration testing
- User reporting

must be documented and evaluated.

---

# 172. Bug Reporting

Dunder Mifflin may maintain a limited external bug-reporting incentive for legitimate security findings.

---

# 173. Bug Bounty Limit

The approved Infinity security bug bounty may provide rewards up to **$500** based on the value and validity of the reported issue.

---

# 174. Bug Bounty Authorization

The bug bounty does not authorize:

- Destructive testing
- Data theft
- Service disruption
- Social engineering
- Unauthorized access beyond what is necessary to demonstrate the issue
- Testing of systems outside the defined scope

---

# 175. Bug Report Handling

A reported security issue should be:

1. Received.
2. Recorded.
3. Evaluated.
4. Validated where appropriate.
5. Prioritized.
6. Remediated where required.
7. Retested where appropriate.
8. Closed with supporting evidence.

---

# 176. Duplicate Findings

Duplicate reports should be identified without creating duplicate remediation effort.

---

# 177. Security Finding Register

Material application-security findings are tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 178. Risk Relationship

Secure development primarily supports treatment of:

- R006 Infinity Compromise
- R013 Administrative / Configuration Error
- R018 Third-Party Technology Failure / Compromise
- R019 Infinity Contractor
- R027 Backup Failure
- R028 Data Corruption

and may support other risks depending on the issue.

---

# 179. R006 Infinity Compromise

R006 has:

- Inherent Risk: **16 High**
- Current Residual Risk: **12 High**
- Target Residual Risk: **8 Moderate**

---

# 180. R006 Treatment

R006 treatment includes:

- [[POL-012 Application & Secure Development Policy]]
- Web/application/database separation
- Dunder Mifflin ownership of source code and documentation
- Threat modeling
- Development/test/production separation
- Code review
- Security testing
- Annual Infinity security assessment
- Annual application penetration testing
- Vulnerability remediation
- Retesting
- Contractor access controls
- Incident Response
- Recovery capability

---

# 181. R013 Administrative / Configuration Error

R013 has:

- Inherent Risk: **16 High**
- Current Residual Risk: **12 High**
- Target Residual Risk: **6 Moderate**

Controlled changes, testing, rollback, configuration management, and verification support R013 treatment.

---

# 182. R018 Third-Party Technology Failure / Compromise

R018 has:

- Inherent Risk: **12 High**
- Current Residual Risk: **8 Moderate**
- Target Residual Risk: **6 Moderate**

Third-party oversight and application dependency management support R018 treatment.

---

# 183. R019 Infinity Contractor

R019 has:

- Inherent Risk: **12 High**
- Current Residual Risk: **8 Moderate**
- Target Residual Risk: **4 Low**

---

# 184. R019 Treatment

R019 treatment includes:

- Dunder Mifflin ownership of source code and work product
- Contractor confidentiality
- Sponsorship
- Time-limited access
- Individual accountability
- Controlled physical access
- Restricted privileged access
- No general contractor VPN for privileged production administration
- Change control
- Code review
- Security testing
- Documentation
- Annual transferability review

---

# 185. R027 Backup Failure

R027 has:

- Inherent Risk: **20 Critical**
- Current Residual Risk: **12 High**
- Target Residual Risk: **5 Moderate**

Application backup and recovery documentation support R027 treatment.

---

# 186. R028 Data Corruption

R028 has:

- Inherent Risk: **16 High**
- Current Residual Risk: **9 Moderate**
- Target Residual Risk: **4 Low**

Application controls supporting R028 include:

- Controlled changes
- Database access restriction
- Integrity validation
- Logging
- Backup and recovery
- Reconciliation where appropriate
- Investigation of integrity concerns

---

# 187. Application Security Metrics

Metrics may include:

- Security-sensitive changes reviewed
- Application vulnerabilities identified
- Critical vulnerabilities overdue
- High vulnerabilities overdue
- Findings awaiting remediation
- Findings awaiting retest
- Annual Infinity assessment status
- Annual penetration-test status
- Contractor access exceptions
- Failed releases
- Emergency changes
- Transferability findings

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 188. Key Performance Indicators

Key Performance Indicators (KPIs) may include:

- Percentage of material application changes receiving required testing
- Percentage of security-sensitive changes receiving required review
- Percentage of vulnerabilities remediated within target
- Percentage of material findings successfully validated after remediation
- Completion of annual Infinity security assessment
- Completion of annual Infinity penetration testing
- Completion of annual Infinity transferability review

---

# 189. Key Risk Indicators

Key Risk Indicators (KRIs) may include:

- Overdue Critical vulnerability
- Overdue High vulnerability
- Unauthorized production change
- Unresolved Internet-facing vulnerability
- Contractor access outside approved scope
- Missing current source code
- Missing recovery documentation
- Failed annual penetration-test remediation
- Material transferability dependency
- Repeated emergency change

---

# 190. Reporting

Secure development information should support:

**Operational Reporting**
- Vulnerabilities
- Failed tests
- Release exceptions
- Contractor access issues
- Immediate remediation activity

**Management Reporting**
- Vulnerability trends
- Change-control performance
- Assessment findings
- Penetration-test remediation
- Transferability
- Overdue corrective actions

**Executive Reporting**
- Material Infinity risk
- Significant unresolved application weakness
- Major contractor dependency
- Material overdue security treatment
- Required risk decision

---

# 191. Finding

A finding is a documented conclusion supported by evidence concerning whether a requirement, control, process, or expected outcome was satisfied.

---

# 192. Application Findings

Potential findings include:

- Authentication weakness
- Authorization weakness
- Injection vulnerability
- Sensitive-data exposure
- Excessive contractor access
- Uncontrolled production change
- Missing code review
- Inadequate environment separation
- Missing documentation
- Recovery weakness
- Transferability dependency
- Overdue vulnerability remediation

---

# 193. Corrective Action

Material application-security deficiencies must identify:

- Finding
- Required corrective action
- Accountable owner
- Due date
- Validation method
- Retest requirement where appropriate

---

# 194. Corrective Action Validation

A corrective action is not complete merely because:

- Code was changed.
- Configuration was changed.
- A developer states the issue is fixed.
- A ticket is closed.

Validation must determine whether the identified weakness was corrected.

---

# 195. Assurance

Secure-development controls are subject to assurance under [[PRO-008 Security Assurance & Continuous Improvement Program]].

---

# 196. Assessment Methods

Assessment may use:

- Inspection
- Interviews
- Sampling
- Code review
- Configuration review
- Technical testing
- Penetration testing
- Independent Performance

---

# 197. Independent Performance

An assessor may independently perform an authorized application-security procedure.

For example:

1. Select a material application change.
2. Obtain the change record.
3. Identify the security requirements.
4. Verify review.
5. Verify testing.
6. Verify approval.
7. Verify production deployment evidence.
8. Identify exceptions.
9. Document the result.

---

# 198. Vulnerability Sample

An assessor may select application vulnerabilities and determine whether:

- Severity was assigned.
- Remediation was completed within the required period or appropriately excepted.
- Corrective action was documented.
- Retesting occurred where required.
- Closure was supported by evidence.

---

# 199. Contractor Access Sample

An assessor may select contractor personnel and determine whether:

- Sponsor was valid.
- Access was authorized.
- Access was appropriately limited.
- Production access was specifically authorized.
- Access duration remained valid.
- Access was removed when no longer required.

---

# 200. Source-Code Control Testing

An assessor may determine whether Dunder Mifflin retains:

- Access to the authoritative source code
- Repository control
- Appropriate backup
- Development history
- Contractor work product

---

# 201. Transferability Testing

An assessor may determine whether a qualified replacement could reasonably obtain the information required to assume Infinity support.

---

# 202. Evidence Integrity

Assessment evidence must reflect actual conditions.

Personnel must not:

- Invent code reviews.
- Backdate change approvals.
- Create fictional test results.
- Record a penetration test that did not occur.
- Conceal failed testing.
- Record remediation that was not completed.
- Invent contractor-access reviews.
- Alter findings to make controls appear effective.

---

# 203. Control Effectiveness

Secure-development controls may be assessed as:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

---

# 204. Effectiveness Evidence

Control-effectiveness conclusions should consider:

- Change records
- Code-review evidence
- Test results
- Vulnerability records
- Penetration-test results
- Contractor-access records
- Source-code control
- Documentation
- Transferability results
- Findings
- Corrective-action validation

---

# 205. Current and Proposed Controls

Secure-development reporting must distinguish among:

- Current controls
- Partially implemented controls
- Planned controls
- Implemented controls awaiting validation
- Validated controls

---

# 206. No Premature Risk Credit

Current residual risk must not be reduced merely because:

- A secure-development requirement is documented.
- A penetration test is scheduled.
- A vulnerability fix is planned.
- A contractor control is approved.
- Documentation is being written.
- A corrective action is assigned.

Risk reduction requires implementation and appropriate validation.

---

# 207. Target Residual Risk

Target residual risk represents expected risk after planned treatment.

It is a prediction.

---

# 208. Validated Post-Treatment Risk

After secure-development controls are implemented and validated, applicable risks may be reassessed.

Actual validated risk may be:

- Higher than target
- Equal to target
- Lower than target

---

# 209. Historical Integrity

The original May 2013 risk assessment must remain preserved.

Later validated assessments may establish a new current residual risk without rewriting the historical assessment.

---

# 210. Exceptions

Exceptions to this program must be:

- Documented
- Justified
- Risk evaluated
- Approved under appropriate authority
- Time-limited where practical
- Reviewed when conditions change

---

# 211. Program Review

This program must be reviewed when material changes affect:

- Infinity
- Application architecture
- Development practices
- Contractor support
- Source-code management
- Application security testing
- Application recovery
- Secure-development risk

---

# 212. Traceability

This program supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Secure development is not demonstrated merely by writing secure-development requirements.

Effective application security requires:

**Requirement → Design → Implementation → Review → Test → Release → Monitor → Assess → Remediate → Retest**

---

# 213. Related Artifacts

- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[RPT-004 Infinity Transferability Review]]
- [[REG-001 Enterprise Asset Register]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[PRO-002 Enterprise Security Architecture Program]]
- [[PRO-003 Identity and Access Management Program]]
- [[PRO-004 Vulnerability Management Program]]
- [[PRO-005 Security Operations Program]]
- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[STD-001 Information Classification Standard]]
- [[STD-002 Network Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[STD-007 Penetration Testing Standard]]
- [[STD-009 Infinity Security Standard]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]
- [[PROC-008 Security Monitoring Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-014 Facility Access Procedure]]
- [[PROC-015 Visitor & Vendor Access Procedure]]
- [[PROC-016 Restricted Area Access Procedure]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-019 Application Security Assessment Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-004 Data Exposure Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

---

# 214. Review

This program must be reviewed:

- At least annually
- Following material Infinity architecture change
- Following material development-process change
- Following significant application-security incident
- Following significant contractor-support change
- Following significant application-security assessment findings

The CIO coordinates program review.

Material revisions require CEO approval.

---

# 215. Revision History

| Version | Date     | Description                                           | Approval |
| ------- | -------- | ----------------------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Secure Software Development Lifecycle Program | CEO      |