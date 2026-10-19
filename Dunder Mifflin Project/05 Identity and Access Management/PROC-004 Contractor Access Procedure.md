# PROC-004 Contractor Access Procedure

## Document Control

| Field | Value |
|---|---|
| Document ID | PROC-004 |
| Title | Contractor Access Procedure |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Contractor Access or Third-Party Security Change |

---

# 1. Purpose

This procedure defines how Dunder Mifflin, Inc. manages contractor access to company systems, applications, information, networks, and administrative capabilities.

The procedure ensures that contractor access is:

- Sponsored
- Authorized
- Individually attributable where required
- Limited to legitimate business need
- Time limited
- Protected by appropriate authentication
- Reviewed
- Removed when no longer required
- Supported by evidence

Contractor status does not create an exception to company security requirements.

---

# 2. Scope

This procedure applies to nonemployee personnel requiring logical access to Dunder Mifflin resources, including:

- Consultants
- Information Technology service providers
- Infinity development and support personnel
- Temporary specialists
- Security assessors
- Penetration testers
- Other third-party personnel

This procedure applies when access is provided to:

- Corporate systems
- Business applications
- Cloud-hosted systems
- Source code
- Administrative interfaces
- Company information
- Network resources
- Production environments
- Development or test environments

---

# 3. Authority

This procedure implements requirements established by:

- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[PRO-003 Identity and Access Management Program]]
- [[STD-005 Authentication & Account Security Standard]]

Infinity-specific requirements are further supported by [[STD-009 Infinity Security Standard]].

---

# 4. Contractor Access Objectives

Contractor access management must:

1. Establish accountable sponsorship.
2. Verify legitimate business need.
3. Limit access to authorized systems.
4. Apply least privilege.
5. Protect sensitive information.
6. Establish individual accountability.
7. Limit access duration.
8. Control privileged administration.
9. Review continued need.
10. Remove access promptly when the requirement ends.
11. Produce evidence supporting assessment.
12. Reduce third-party and contractor risk.

---

# 5. Contractor Access Principles

Contractor access must follow:

- Need to know
- Least privilege
- Individual accountability
- Defined scope
- Defined duration
- Appropriate authentication
- Business sponsorship
- Periodic review
- Prompt revocation

Contractors must not receive broad access solely because doing so simplifies support.

---

# 6. Business Sponsor

Every contractor requiring company access must have an identified Dunder Mifflin business sponsor.

The sponsor is responsible for confirming:

- Business relationship
- Need for access
- Required systems
- Required duration
- Continued need
- End of access requirement

Contractor access without an accountable sponsor is prohibited.

---

# 7. Sponsor Responsibility

The sponsor must understand that sponsorship is an access-control responsibility.

The sponsor must not approve access merely because:

- The contractor requested it.
- The contractor previously had access.
- The contractor may need it later.
- Broad access would simplify troubleshooting.

Access must reflect actual requirements.

---

# 8. Contractor Identification

Contractor access must be assigned to identifiable personnel where individual accountability is required.

The organization must know, as applicable:

- Contractor company
- Individual contractor
- Business sponsor
- Engagement
- Systems authorized
- Access duration

Generic identification of only the contractor company is insufficient for significant individual access.

---

# 9. Contractor Access Workflow

The standard workflow is:

**Business Need → Sponsor → Confidentiality Requirement → Access Request → Authorization → Provisioning → Verification → Controlled Use → Review / Renewal → Revocation**

Privileged contractor access requires additional controls.

---

# 10. Pre-Access Requirements

Before access is granted, the responsible parties must determine:

- Contractor identity
- Business sponsor
- Business purpose
- Systems required
- Information required
- Privilege required
- Access method
- Access location
- Required duration
- Confidentiality requirements

Access must not begin until required approvals are complete.

---

# 11. Confidentiality Requirement

A contractor or other nonemployee receiving access to sensitive company information or systems must have an appropriate Non-Disclosure Agreement (NDA) or equivalent enforceable confidentiality obligation before access where required by the nature of the access.

This requirement is based on:

- Access
- Information sensitivity
- Business relationship

It is not based solely on the contractor's job title.

---

# 12. Confidentiality Scope

Confidentiality requirements may apply to:

- Consultants
- Infinity contractors
- Penetration testers
- Information Technology service providers
- Temporary specialists
- Service personnel with sensitive access
- Other third parties receiving sensitive information

The obligation must be established before sensitive access begins.

---

# 13. Confidentiality Limitations

A confidentiality agreement does not independently establish effective contractor security.

It does not replace:

- Access control
- Authentication
- Least privilege
- Technical security
- Contractor oversight
- Security assessment
- Monitoring
- Incident response
- Access termination

The existence of an NDA must not be used as evidence that unrelated contractor controls are effective.

---

# 14. Access Request

The contractor access request must identify, as applicable:

- Individual contractor
- Contractor organization
- Sponsor
- Business purpose
- Required systems
- Required permissions
- Information sensitivity
- Access location
- Remote-access requirement
- Start date
- Requested expiration

The request must be specific enough to support authorization.

---

# 15. Access Authorization

Contractor access must be authorized before provisioning.

Authorization must consider:

- Business need
- Information classification
- System sensitivity
- Required privilege
- Duration
- Third-party risk
- Separation of duties
- Access method

Sensitive or privileged access requires additional scrutiny.

---

# 16. System Owner Approval

System-owner approval is required where the system owner controls business authorization for the requested access.

A sponsor's request does not automatically authorize access to every company system.

---

# 17. Information Owner Approval

Where contractor access involves sensitive information, the appropriate information owner must participate in authorization when required.

Access must be limited to information necessary for the engagement.

---

# 18. Initial Authorization Period

Initial contractor access may be approved for up to three months.

The approved period may be shorter based on:

- Engagement length
- System sensitivity
- Privilege
- Business need
- Risk

An initial three-month authorization is a maximum, not an automatic duration.

---

# 19. Account Expiration

Contractor accounts should use a defined expiration date where supported.

The expiration must reflect the approved access period.

Technical expiration supports, but does not replace, sponsor responsibility for timely access removal.

---

# 20. Contractor Account Provisioning

Information Technology must provision contractor access according to approved authorization.

Provisioning must:

- Identify the individual where required.
- Limit access to approved systems.
- Apply least privilege.
- Configure appropriate authentication.
- Apply expiration where supported.
- Avoid unnecessary privileged access.

---

# 21. Individual Accounts

Contractors must receive individual accounts where:

- The system supports them, and
- Individual accountability is required.

Individual contractor credentials must not be shared among contractor personnel.

---

# 22. Contractor Account Identification

Contractor accounts should be distinguishable from ordinary employee accounts where practical.

Account records must make it possible to determine:

- User
- Contractor status
- Sponsor
- Expiration
- Authorized purpose

Account naming alone does not replace supporting records.

---

# 23. Authentication

Contractor authentication must comply with [[STD-005 Authentication & Account Security Standard]].

Authentication must be appropriate to:

- System sensitivity
- Access method
- Privilege
- Information sensitivity
- Risk

---

# 24. Contractor Passwords

Contractor passwords must receive the same protection required for comparable employee accounts.

Contractors must not:

- Share individual credentials.
- Store credentials insecurely.
- Provide credentials to other contractor personnel.
- Reuse another contractor's account.

Suspected credential compromise must be reported promptly.

---

# 25. Multi-Factor Authentication

Smart-card multi-factor authentication using the card with a PIN or other approved secret must be used for contractor access where supported and required by risk.

Priority must be given to higher-risk contractor access.

Planned multi-factor authentication must not be represented as implemented until deployment and validation occur.

---

# 26. Least Privilege

Contractors must receive only the access required for the engagement.

Contractor access must not automatically include:

- Administrative access
- Production access
- Sensitive information
- Broad file access
- Remote access
- Unrelated business applications

Each access requirement must be justified.

---

# 27. Need to Know

Contractors may access sensitive company information only when required for authorized work.

Access must reflect the information classification established through:

- [[POL-004 Information Classification & Handling Policy]]
- [[STD-001 Information Classification Standard]]

Access to one sensitive system does not establish a need for unrelated sensitive information.

---

# 28. Production Access

Contractor production access must be limited to legitimate operational requirements.

Development responsibility alone does not automatically justify unrestricted production access.

Production access must receive additional scrutiny when the contractor can:

- Modify application behavior
- Modify configuration
- Access sensitive information
- Affect availability
- Change production data

---

# 29. Privileged Contractor Access

Privileged contractor access must comply with [[PROC-002 Privileged Access Procedure]].

Privileged access requires:

- Specific authorization
- Defined systems
- Defined purpose
- Appropriate authentication
- Limited duration
- Individual accountability
- Review
- Use of approved company-controlled administrative methods and locations

External remote privileged administration is prohibited.

---

# 30. Contractor Administrative Accounts

Where supported, contractor privileged access must use an account separate from ordinary contractor access.

Privileged contractor accounts must not routinely be used for:

- General web browsing
- Ordinary email
- Unrelated application activity
- Other nonadministrative work

---

# 31. Remote Contractor Access

Ordinary remote contractor access must be specifically authorized.

Approval must consider:

- Business need
- Systems
- Authentication
- Connection method
- Duration
- Risk

Contractor status does not automatically create a remote-access entitlement.

Authorization for ordinary remote access, including Virtual Private Network (VPN) access where required, does not authorize privileged administration.

---

# 32. External Remote Privileged Administration

External remote privileged administration is prohibited.

Contractors requiring privileged administration of significant production resources must perform that activity through approved company-controlled methods and locations.

Ordinary remote-access authorization, including VPN access, does not authorize privileged administration.

Contractor status, operational convenience, incident response, emergency conditions, or support urgency do not create an exception to this prohibition.

---

# 33. Infinity Contractor

The external contractor supporting Infinity is subject to additional controls because the contractor can materially affect a company-developed business application.

Infinity contractor access must remain:

- Sponsored
- Individually authorized
- Time limited
- Least privilege
- Individually attributable
- Subject to change control
- Subject to security requirements

---

# 34. Infinity Contractor Personnel

Expected Infinity contractor personnel requiring onsite access must be identified at least one business day before scheduled arrival where practical.

The notification must provide sufficient information to verify expected personnel.

An emergency exception may be approved when advance notice is not practical.

The emergency exception applies only to the advance-notice requirement. It does not authorize external remote privileged administration or bypass other contractor-access requirements.

---

# 35. Unexpected Infinity Contractor Personnel

Unexpected contractor personnel must not receive sensitive or privileged access solely because they:

- Work for the approved contractor company.
- Arrive with another authorized contractor.
- State that they were sent to perform support.

Authorization must be confirmed before access.

---

# 36. Infinity Contractor Workspace

Privileged Infinity production or administrative contractor activity must occur from the designated company-controlled contractor workspace at Scranton Headquarters.

The workspace provides a controlled location for higher-risk contractor administration.

External remote privileged administration of Infinity production resources is prohibited.

---

# 37. Infinity Contractor VPN

General contractor VPN access for privileged Infinity production administration is prohibited.

Public-facing Infinity functionality may be accessed normally as required for legitimate testing, but privileged production administration must follow the controlled administrative-access model.

Ordinary contractor VPN access does not authorize privileged production administration.

---

# 38. Infinity Source Code

Dunder Mifflin owns and controls:

- Infinity source code
- Source repository
- Application documentation
- Company data
- Intellectual property
- Contractor work product
- Applicable backups

Contractor access to source code does not transfer ownership or control.

---

# 39. Source Repository Access

Contractor source-repository access must be:

- Individually authorized
- Limited to required repositories
- Appropriate to the engagement
- Removed when no longer required

Source access must not remain active solely because the contractor may perform future work.

---

# 40. Development Environment Access

Contractor development access must be limited to the environment required for authorized work.

Development access must not automatically provide:

- Production access
- Production credentials
- Production database access
- Unrestricted company network access

Development, test, and production separation must be maintained.

---

# 41. Test Environment Access

Contractor test access must reflect:

- Testing responsibility
- Information sensitivity
- Environment separation
- Required application functions

Production information used in test environments must be restricted or appropriately sanitized where required.

---

# 42. Infinity Production Access

Production access must be limited to authorized support or administrative activity.

The contractor must not make production changes outside the approved change process.

Production access must not become routine merely because the contractor maintains Infinity.

Privileged production administration must occur from the designated company-controlled contractor workspace at Scranton Headquarters.

---

# 43. Infinity Change Control

Contractor changes to Infinity must comply with:

- [[POL-007 Change & Configuration Management Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]

Contractor access does not independently authorize production changes.

---

# 44. Contractor Access to Other Systems

An Infinity contractor or other specialist must not receive access to unrelated company systems solely because the contractor already has trusted access elsewhere.

Each additional system requires legitimate business need and appropriate authorization.

---

# 45. Security Assessor Access

Security assessors and penetration testers must receive only the access required by the approved assessment scope.

Access must reflect:

- Written authorization
- Defined systems
- Defined testing activity
- Defined testing period
- Required credentials

Assessment authorization does not permit unrestricted activity outside scope.

Assessment authorization does not authorize external remote privileged administration unless the activity is not privileged administration as defined by [[PROC-002 Privileged Access Procedure]].

---

# 46. Penetration Tester Confidentiality

Penetration testers receiving sensitive technical information or access must have an appropriate confidentiality obligation before access.

This requirement does not independently establish:

- Tester competence
- Testing quality
- Appropriate scope
- Independence
- Remediation
- Retesting

Those requirements must be evaluated separately.

---

# 47. Temporary Specialist Access

Temporary specialists must receive only the access required for the defined assignment.

Short engagement duration does not justify bypassing:

- Sponsorship
- Authorization
- Authentication
- Confidentiality
- Access termination

Temporary or emergency status does not authorize external remote privileged administration.

---

# 48. Third-Party Support Personnel

Third-party support personnel requiring sensitive system access must be individually authorized where practical.

Vendor affiliation alone does not authorize access.

Support personnel must remain within the approved support scope.

Support responsibility does not create an exception to the prohibition on external remote privileged administration.

---

# 49. Service Personnel

Service personnel who do not require logical or sensitive information access do not automatically require contractor system accounts.

Physical presence at a facility does not independently justify logical access.

---

# 50. Renewal Review

Contractor access approaching expiration must be reviewed before renewal.

The sponsor must confirm:

- Engagement remains active.
- Contractor personnel remain assigned.
- Business need remains valid.
- Systems remain required.
- Privilege remains appropriate.

Renewal must not occur automatically.

---

# 51. Renewal Period

Following the initial authorization, contractor access may be renewed for periods not exceeding six months at a time.

A shorter renewal period may be required based on:

- Risk
- Privilege
- Engagement length
- System sensitivity

---

# 52. Renewal Authorization

Renewal requires appropriate authorization.

The renewal record must identify:

- Contractor
- Sponsor
- Continued business need
- Systems
- Privilege
- New expiration

Prior authorization alone is not sufficient for indefinite continuation.

---

# 53. Renewal and Access Reduction

Renewal provides an opportunity to reduce access that is no longer required.

The reviewer must not assume that the previous access scope remains necessary.

Access may be:

- Retained
- Reduced
- Modified
- Removed

---

# 54. Contractor Access Review

Contractor access must be included in applicable access reviews under [[PROC-003 Access Review Procedure]].

Review must evaluate:

- Sponsor
- Engagement
- Systems
- Privilege
- Expiration
- Continued need

---

# 55. Privileged Contractor Review

Privileged contractor access must be included in the quarterly privileged-access review.

The review must determine whether:

- Access remains required.
- Privilege remains appropriate.
- Authorization remains current.
- Access restrictions remain effective.
- Expiration remains valid.
- Administrative activity complies with approved company-controlled methods and locations.
- No external remote privileged administration is occurring.

---

# 56. Contractor Dormancy

Unexpected contractor-account inactivity must be investigated according to applicable dormant-account requirements.

The review must consider whether:

- Work is temporarily paused.
- The engagement remains active.
- The contractor no longer requires access.
- The account should be disabled.

Dormant contractor accounts must not remain active indefinitely.

---

# 57. Contractor Personnel Change

The sponsor must notify Information Technology when contractor personnel change.

Departing or replaced contractor personnel must have access removed promptly.

A contractor company's continuing engagement does not justify retaining access for an individual who is no longer assigned.

---

# 58. Contractor Role Change

If a contractor's responsibilities materially change, existing access must be reassessed.

Access no longer required must be removed.

New access requires appropriate authorization.

Contractor permissions must not accumulate across assignments.

---

# 59. Contractor Termination

Contractor access must be revoked when:

- Engagement ends.
- Individual assignment ends.
- Sponsor withdraws authorization.
- Business need ends.
- Access expires without renewal.
- Security conditions require removal.

Revocation must occur promptly.

---

# 60. Contractor Revocation Workflow

The revocation workflow is:

**Termination Notification → Identify Access → Disable Accounts → Remove Remote Access → Remove Privileged Access → Recover Authentication Devices Where Applicable → Verify → Retain Evidence**

All applicable access paths must be addressed.

---

# 61. Logical Account Disablement

Contractor logical accounts must be disabled or removed as appropriate.

This may include:

- Active Directory
- Application accounts
- Cloud accounts
- Source repository
- VPN
- Administrative accounts
- Database access
- Other significant systems

---

# 62. Remote Access Removal

Remote contractor access must be explicitly revoked when no longer required.

Ordinary account disablement must not be assumed to revoke a separate remote-access mechanism without verification.

---

# 63. Privileged Access Removal

Contractor privileged access must receive explicit termination verification.

Review must address, as applicable:

- Application administration
- Server administration
- Database administration
- Cloud administration
- Source repository privileges
- Other elevated access

---

# 64. Authentication Device Recovery

Company-issued smart cards or other authentication devices must be recovered where practical.

Unrecovered devices must be invalidated where supported.

Recovery of a physical device does not replace account disablement.

---

# 65. Physical Access Removal

Where the contractor has company-issued physical-access credentials, those credentials must be:

- Recovered, or
- Disabled

when the access requirement ends.

Physical-access requirements are coordinated with [[PROC-015 Visitor & Vendor Access Procedure]] and [[PROC-016 Restricted Area Access Procedure]].

---

# 66. Shared Credential Exposure

If a departing contractor knew an authorized shared credential, the credential must be evaluated for change.

The decision must consider:

- Privilege
- Systems affected
- Information sensitivity
- Reason for departure
- Risk

Higher-risk credentials must be changed when continued knowledge creates material risk.

---

# 67. Contractor Work Product

Required contractor work product must remain under Dunder Mifflin control.

Work product may include:

- Source code
- Configuration information
- Documentation
- Test results
- Recovery information
- Technical records

Termination of contractor access must not leave required company information solely under contractor control.

---

# 68. Knowledge Transfer

Where contractor knowledge is important to continued operations, required documentation and knowledge transfer must occur before the engagement ends where practical.

The organization must reduce unnecessary dependency on undocumented contractor knowledge.

Infinity transferability is evaluated through [[RPT-004 Infinity Transferability Review]].

---

# 69. Access Revocation Verification

Contractor termination is not complete until applicable access removal is verified.

Verification must determine whether the individual retains access through:

- User accounts
- Privileged accounts
- VPN
- Applications
- Source repository
- Cloud systems
- Physical credentials
- Other significant mechanisms

---

# 70. Failed Revocation

If contractor access cannot be revoked promptly:

1. The condition must be escalated.
2. Risk must be evaluated.
3. Compensating controls must be applied where practical.
4. Resolution must be tracked.

Failed revocation must not be recorded as completed termination.

---

# 71. Contractor Credential Compromise

Known or suspected contractor credential compromise requires prompt action.

Potential actions include:

- Account lock
- Credential reset
- Smart-card invalidation
- Remote-access revocation
- Session termination
- Log review
- Sponsor notification
- Incident escalation

The response must reflect the systems and privileges accessible through the credential.

---

# 72. Contractor Security Incident

A security incident involving contractor access must be handled under:

- [[POL-009 Incident Response Policy]]
- [[PLN-001 Incident Response Plan]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]

Access may be restricted or revoked before the investigation is complete when necessary to protect the organization.

Incident-response requirements do not authorize external remote privileged administration.

---

# 73. Third-Party Incident Notification

Applicable third-party agreements must require Critical providers to notify Dunder Mifflin of material security incidents within 24 hours of discovery as established by [[POL-008 Third-Party Security Policy]].

Contractor personnel must promptly report suspected incidents through their established Dunder Mifflin contact.

---

# 74. Contractor Activity Logging

Significant contractor authentication and administrative activity must be logged where supported.

Relevant records may include:

- Authentication
- Failed authentication
- Privileged activity
- Application administration
- Source repository activity
- Configuration changes
- Remote access

Logging capability must be represented accurately.

---

# 75. Contractor Monitoring

Monitoring must focus on meaningful conditions including:

- Access outside authorized scope
- Unexpected privileged activity
- Access after expiration
- Unexpected remote access
- Evidence of external remote privileged administration
- Authentication anomalies
- Activity associated with an incident

Dunder Mifflin does not require continuous manual surveillance of contractor activity.

---

# 76. Privacy and Proportionality

Contractor monitoring must be proportionate to legitimate security and business requirements.

Monitoring must not be used for unnecessary surveillance.

Access controls, logging, and review should focus on protecting:

- Company systems
- Company information
- Business operations
- Accountability

---

# 77. Contractor Access Records

Records must be sufficient to identify:

- Contractor
- Contractor organization
- Sponsor
- Business purpose
- Systems
- Privilege
- Start date
- Expiration
- Renewal
- Termination

Higher-risk access requires more detailed evidence.

---

# 78. Initial Access Evidence

Initial contractor-access evidence may include:

- Business request
- Sponsor approval
- System-owner approval
- Confidentiality agreement where required
- Account record
- Authentication setup
- Access expiration
- Provisioning verification

Evidence must support the access actually granted.

---

# 79. Renewal Evidence

Renewal evidence must demonstrate that continued access was affirmatively reviewed.

Evidence may include:

- Sponsor confirmation
- Current engagement
- Systems required
- Privilege review
- New expiration
- Approval

An unchanged expiration date is not evidence of a completed renewal review.

---

# 80. Termination Evidence

Termination evidence may include:

- Sponsor notification
- Account disablement
- VPN removal
- Privileged-access removal
- Source-repository removal
- Authentication-device recovery
- Physical-access removal
- Verification record

Evidence must support the timing and completeness of revocation.

---

# 81. Evidence Integrity

Personnel must not:

- Create false contractor approvals.
- Conceal contractor access.
- Alter expiration dates to conceal overdue access.
- Record renewal that was not performed.
- Record access as revoked when it remains active.
- Conceal excessive contractor privileges.
- Represent Planned authentication controls as implemented.
- Falsify confidentiality records.
- Conceal failed termination actions.
- Represent prohibited external remote privileged administration as an approved exception.

Known discrepancies must be documented and addressed.

---

# 82. Contractor Access Testing

Contractor-access controls must be periodically tested.

Assessment methods may include:

- Inspection
- Sampling
- Account review
- Access reconciliation
- Interviews
- Log review
- Technical Testing
- Independent Performance

Testing must evaluate actual contractor access rather than policy documentation alone.

---

# 83. Initial Authorization Testing

An assessor may select active contractor accounts and determine whether:

- Sponsor exists.
- Business need exists.
- Authorization exists.
- Confidentiality requirement was satisfied where applicable.
- Access matches authorization.
- Expiration is defined.

Unsupported access requires investigation.

---

# 84. Expiration Testing

An assessor may compare active contractor accounts with approved expiration dates.

The assessment must identify:

- Expired active accounts
- Accounts nearing expiration
- Renewals lacking support
- Accounts without defined duration

Expired active access requires prompt investigation.

---

# 85. Renewal Testing

An assessor may sample renewed contractor accounts and determine whether:

- Sponsor reconfirmed need.
- Engagement remained active.
- Systems were reassessed.
- Privileges were reassessed.
- Renewal did not exceed six months.
- Supporting evidence exists.

---

# 86. Privileged Contractor Testing

Assessment of privileged contractor access must determine whether:

- Privilege is specifically authorized.
- Access remains required.
- Individual accountability exists.
- Quarterly review occurred.
- Privileged administration occurs through approved company-controlled methods and locations.
- External remote privileged administration is not occurring.
- Expiration remains valid.

Ordinary remote-access authorization must not be accepted as authorization for privileged administration.

---

# 87. Infinity Contractor Testing

Assessment may verify whether Infinity contractor controls operate as required.

Testing may examine:

- Individual contractor authorization
- Sponsor
- Account status
- Source-repository access
- Production access
- Privileged access
- Access duration
- Onsite administrative requirements
- Personnel notification
- Compliance with the prohibition on external remote privileged administration

---

# 88. Termination Testing

An assessor may select former contractor personnel and determine whether access was removed.

Testing may include:

- Active Directory
- VPN
- Applications
- Source repository
- Privileged accounts
- Cloud systems

Active access belonging to a former contractor requires investigation.

---

# 89. Independent Performance

An assessor may perform selected contractor-access review activities independently.

For example, the assessor may:

1. Obtain a current contractor-account population.
2. Identify each account's sponsor.
3. Confirm the engagement remains active.
4. Compare the account with approved systems and privileges.
5. Check expiration and renewal.
6. Identify unsupported access.

Independent Performance provides evidence beyond review of completed access forms.

---

# 90. Testing Exceptions

Testing exceptions must be investigated before final conclusions are reached.

An exception may result from:

- Unauthorized access
- Expired authorization
- Incorrect account data
- Documentation failure
- Technical failure
- Legitimate approved exception to an eligible requirement

The cause determines the appropriate response.

External remote privileged administration is not an eligible approved exception.

---

# 91. Contractor Access Findings

Material deficiencies must be documented.

Examples include:

- Contractor account without sponsor
- Access without authorization
- Missing required confidentiality obligation
- Excessive contractor access
- Expired active contractor account
- Renewal without review
- Shared contractor credential
- Unauthorized privileged access
- External remote privileged administration
- Former contractor account still active
- Infinity contractor access outside approved controls
- Missing termination verification

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 92. Corrective Action

Corrective action must identify:

- Deficiency
- Affected contractor or system
- Responsible owner
- Required remediation
- Due date
- Validation method

Corrective action is not complete until remediation is implemented and appropriately verified.

---

# 93. Contractor Access Metrics

Metrics may include:

- Active contractor accounts
- Contractor accounts without current sponsor
- Contractor accounts approaching expiration
- Expired active contractor accounts
- Contractor renewals completed
- Privileged contractor accounts
- Contractor access-review completion
- Contractor termination failures
- Unsupported contractor accounts
- External remote privileged administration events
- Open contractor-access findings
- Overdue corrective actions

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 94. Risk Relationships

This procedure provides significant treatment support for:

- R001 Phishing / Credential Compromise
- R003 Ransomware
- R004 Malware
- R005 Password / Authentication Weakness
- R006 Infinity Application Compromise
- R009 Sensitive Information Theft / Extortion
- R010 Unauthorized / Excessive Access
- R011 Delayed Termination
- R012 Malicious Insider
- R018 Third-Party Technology Failure / Compromise
- R019 Infinity Contractor Dependency / Compromise
- R027 Backup / Recovery Failure
- R028 Data Corruption

Risk treatment is maintained in [[RTP-001 Enterprise Risk Treatment Plan]].

---

# 95. Exceptions

Exceptions to this procedure require:

- Business justification
- Identification of the affected requirement
- Risk evaluation
- Compensating controls where practical
- Accountable owner
- Defined duration
- Appropriate approval

High or Critical residual risk must be escalated according to [[POL-005 Risk Management Policy]].

This exception process does not authorize an exception to the prohibition on external remote privileged administration.

---

# 96. Traceability

This procedure supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Contractor access must remain traceable from business sponsorship through authorization, implementation, review, termination, assessment, and remediation.

---

# 97. Related Artifacts

- [[PRO-003 Identity and Access Management Program]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[STD-001 Information Classification Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-009 Infinity Security Standard]]
- [[PROC-001 Joiner-Mover-Leaver Procedure]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-003 Access Review Procedure]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-015 Visitor & Vendor Access Procedure]]
- [[PROC-016 Restricted Area Access Procedure]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]
- [[RPT-004 Infinity Transferability Review]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

---

# 98. Review

This procedure must be reviewed:

- At least annually
- Following material contractor-access changes
- Following significant third-party security incidents
- Following material assessment findings
- Following significant changes to Infinity contractor access
- Following material changes to third-party security requirements

The IT & Information Security Manager coordinates review.

Material revisions require CIO approval.

---

# 99. Revision History

| Version | Date     | Description                         | Approval |
| ------- | -------- | ----------------------------------- | -------- |
| 1.0     | May 2013 | Initial Contractor Access Procedure | CIO      |