# STD-005 Authentication & Account Security Standard

## Document Control

| Field | Value |
|---|---|
| Document ID | STD-005 |
| Title | Authentication & Account Security Standard |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Change |

---

# 1. Purpose

This standard establishes technical and administrative requirements for authentication, account security, credential protection, privileged access, account lifecycle controls, and authentication-related monitoring at Dunder Mifflin.

The standard supports:

- Individual accountability
- Least privilege
- Need to know
- Appropriate authorization
- Separation of duties
- Protection of authentication credentials
- Control of privileged access
- Timely account removal
- Detection and investigation of authentication-related security events

---

# 2. Scope

This standard applies to:

- Employees
- Executives
- Information Technology personnel
- Contractors
- Temporary personnel
- Service accounts
- Application accounts
- Emergency accounts
- Privileged accounts
- Remote-access accounts

It applies to authentication and accounts associated with:

- Active Directory
- Windows endpoints
- Windows servers
- Business applications
- Cloud-hosted systems
- Virtual Private Network access
- Infinity
- Warehouse systems
- Email
- File services
- Administrative systems
- Other nonpublic company resources

---

# 3. Authority

This standard implements requirements established through:

- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-012 Application & Secure Development Policy]]

Requirements in this standard are mandatory unless an approved exception exists.

The exception process does not apply where this standard or a governing policy explicitly identifies a requirement as non-exempt.

---

# 4. Authentication Principles

Authentication controls must support:

- Individual accountability
- Appropriate assurance for the resource being accessed
- Protection of authentication secrets
- Separation of ordinary and privileged activity
- Prompt removal of unnecessary access
- Investigation of suspicious authentication activity

Authentication strength must reflect risk.

---

# 5. Individual Accounts

Users must receive individually assigned accounts where technically and operationally practical.

Individual accounts must be used for activity requiring reliable attribution.

Users must not share individually assigned credentials.

Account sharing must not be used as a substitute for appropriate account provisioning.

---

# 6. Shared Accounts

Shared accounts must be avoided where individual authentication is practical.

A shared account may be used when:

- Required by legitimate operational need
- Supported by the underlying system design
- Approved by the appropriate owner
- Individual accountability is maintained through other means where significant activity occurs

Shared accounts must not be used merely for convenience.

---

# 7. Warehouse Shared Windows Accounts

Warehouse workstations may use shared Windows accounts where operationally justified.

Shared Windows authentication does not eliminate the requirement for individual accountability for significant Warehouse Management System activity.

Significant WMS transactions must provide reliable individual attribution where supported.

Examples include:

- Inventory adjustments
- Material receiving
- Material shipping
- Other transactions materially affecting inventory accountability

---

# 8. Account Ownership

Every account must have an identifiable accountable owner or responsible function.

Ownership must be clear for:

- User accounts
- Privileged accounts
- Service accounts
- Application accounts
- Contractor accounts
- Emergency accounts
- Generic accounts

Accounts without a legitimate owner or purpose must be investigated.

---

# 9. Account Authorization

Accounts must be authorized before access is granted.

Authorization must consider:

- Business need
- Job responsibility
- Information sensitivity
- Required systems
- Required privileges
- Separation of duties
- Risk

Technical ability to create an account does not constitute authorization.

---

# 10. Account Provisioning

Account provisioning must follow approved identity and access processes.

Provisioning must establish:

- User identity
- Manager or sponsor
- Required systems
- Appropriate access
- Appropriate privilege level
- Required authentication method
- Any expiration or review requirements

Access must not exceed the approved business requirement.

---

# 11. Human Resources Authority

Human Resources is the authoritative source for employee status.

Identity and access processes must use Human Resources information for:

- New employees
- Employment changes
- Transfers
- Terminations

Information Technology must not knowingly maintain ordinary employee access for a person Human Resources identifies as terminated unless a documented legal, investigative, or other exceptional requirement exists and appropriate approval has been obtained.

---

# 12. Joiner Access

New employee access must be based on documented business requirements.

Access must be limited to systems and information required for assigned duties.

Access must not be copied automatically from another employee without determining whether the copied access is appropriate.

---

# 13. Transfer Access

A transfer to a materially different role requires review of existing access.

Existing business permissions must be revoked and the new role's required permissions reauthorized.

Access from the previous role must not remain solely because removing it is inconvenient.

Technical accounts that remain necessary for the individual must receive only the permissions appropriate to the new role.

---

# 14. Termination Access

Logical access must be removed promptly when employment or an authorized engagement ends.

Termination processing must address, where applicable:

- Active Directory
- Email
- VPN
- Business applications
- Cloud services
- Privileged accounts
- Smart cards
- Authentication devices
- Contractor accounts
- Other company access

Termination processing must coordinate with [[PROC-001 Joiner-Mover-Leaver Procedure]].

---

# 15. Privileged Accounts

Privileged access must be limited to personnel with a legitimate administrative requirement.

Privileged accounts must:

- Be individually assigned where technically supported.
- Be limited to required administrative functions.
- Be protected from unnecessary use.
- Be reviewed more frequently than ordinary access.
- Be removed when no longer required.

Privileged access must not be assigned solely because of seniority, title, or convenience.

---

# 16. Separate Privileged Credentials

Information Technology personnel must use separate privileged credentials for administrative activity where technically supported.

Privileged credentials must not be used for routine:

- Email
- Web browsing
- Office productivity
- General business activity

Ordinary credentials must be used for ordinary user activity.

---

# 17. Domain Administrative Access

Standing Domain Admin membership must normally be limited to:

- IT & Information Security Manager
- System Administrator

Additional standing Domain Admin access requires documented justification and approval.

Personnel who require occasional elevated access must not receive standing Domain Admin membership solely for convenience.

---

# 18. Dedicated Administrative Workstations

Higher-risk privileged administration must use designated administrative workstations where required by [[PRO-002 Enterprise Security Architecture Program]].

Administrative workstations must be:

- Company controlled
- Securely configured
- Restricted to authorized personnel
- Protected from unnecessary ordinary user activity

---

# 19. Passwords

Passwords must provide reasonable protection against unauthorized access.

Password requirements must consider:

- Account privilege
- Resource sensitivity
- Technical capabilities
- Exposure
- Risk

Default passwords must be changed before production use where applicable.

---

# 20. Password Confidentiality

Users must protect their passwords.

Users must not:

- Share individually assigned passwords
- Disclose passwords to coworkers
- Send passwords through ordinary email
- Post passwords in visible locations
- Store passwords in plainly readable documentation accessible to unauthorized personnel

Information Technology personnel must not request a user's password when another administrative method can accomplish the required task.

---

# 21. Password Reuse

Users must not knowingly reuse company passwords for unrelated personal services.

Privileged credentials must not intentionally use the same password as ordinary user credentials.

Credential reuse must be minimized where technically practical.

---

# 22. Password Changes

Passwords must be changed when:

- Compromise is known or suspected
- A shared credential's authorized users change materially
- A default credential is placed into service
- An emergency credential requires reset following use
- Required by applicable account policy
- Directed as part of incident response

Password changes must not be represented as a complete response when broader credential compromise may exist.

---

# 23. Authentication Secrets

Authentication secrets include:

- Passwords
- PINs
- Recovery codes
- Private authentication information
- Other secrets used to prove identity

Authentication secrets must be protected from unauthorized disclosure.

A smart card does not eliminate the need to protect its associated PIN or secret.

---

# 24. Multi-Factor Authentication

Multi-factor authentication must be implemented using smart-card authentication with a PIN or other approved secret where supported and required by risk.

Multi-factor authentication is a planned security improvement and must not be represented as implemented where deployment has not occurred.

Priority should be given to higher-risk access, including:

- Privileged access
- Sensitive applications
- Remote access where supported
- Infinity administrative access
- Other access identified through risk assessment

---

# 25. Smart-Card Security

Smart cards must:

- Be individually assigned.
- Be protected from unauthorized use.
- Require an associated PIN or other approved secret.
- Be recovered or invalidated when access ends.
- Be reported promptly if lost or stolen.

Possession of a smart card alone must not provide sufficient authentication where a second factor is required.

---

# 26. Authentication Assurance

Authentication requirements must reflect:

- Resource sensitivity
- Access type
- Privilege
- Exposure
- Business risk

Higher-risk access requires stronger assurance where technically supported.

Authentication requirements must not be weakened solely for user convenience.

---

# 27. Account Password Reset

Password reset processes must verify the identity of the requester before changing authentication credentials.

Reset procedures must be proportionate to account risk.

Personnel performing resets must not rely solely on:

- Username knowledge
- Claimed urgency
- Claimed executive authority
- Easily obtained personal information

---

# 28. Initial Credentials

Initial credentials must be provided in a manner that reasonably protects them from unauthorized use.

Temporary passwords should require change at first use where technically supported.

Initial credentials must not remain valid indefinitely when the account is not activated.

---

# 29. Dormant Accounts

Accounts inactive for 30 days must be investigated.

The review must determine whether:

- The account remains required.
- The user remains authorized.
- Inactivity is expected.
- Access should be removed.

Accounts inactive for 60 days must be disabled unless a documented legitimate need exists.

---

# 30. Dormant Account Exceptions

A dormant account may remain enabled beyond 60 days only when:

- A legitimate business or technical need exists.
- The reason is documented.
- An accountable owner remains identified.
- Continued access is approved.
- The account remains subject to review.

Dormancy must not be ignored merely because an account has not generated a security incident.

---

# 31. Disabled Accounts

Disabled accounts must not be treated as active authorized access.

Disabled accounts should be retained only as long as required for:

- Operational need
- Recordkeeping
- Investigation
- Legal requirements
- Technical dependency

Accounts no longer required should be removed according to appropriate administrative procedures.

---

# 32. Account Expiration

Temporary and contractor accounts must use expiration dates where technically supported and appropriate.

Expiration should reflect:

- Expected engagement duration
- Approved access period
- Review requirements

Expiration does not replace the requirement for prompt access removal when an engagement ends early.

---

# 33. Ordinary Access Review

Ordinary user access must be reviewed at least annually.

The review must determine whether:

- The user remains active.
- Access remains required.
- Access reflects the current role.
- Excessive access exists.
- Shared access remains justified.
- Remediation is required.

Reviews must produce evidence.

---

# 34. Privileged Access Review

Privileged access must be reviewed at least quarterly.

The review must include:

- Privileged users
- Privileged accounts
- Domain Administrator membership
- Local administrative access where material
- Contractor privileged access
- Emergency-access capability
- Other significant elevated access

Unnecessary privileged access must be removed promptly.

---

# 35. Access Review Responsibility

Managers are responsible for confirming business need.

Information owners are responsible for confirming access to information under their authority where applicable.

Information Technology is responsible for providing account information and implementing approved changes.

Security personnel may review the process and results.

---

# 36. Access Review Independence

Personnel must not approve their own access when another appropriate reviewer exists.

Privileged users must not be the sole reviewers of their own privileged access.

Review design must remain practical for Dunder Mifflin's staffing level while preserving reasonable oversight.

---

# 37. Service Accounts

Service accounts must have:

- A documented purpose
- An accountable owner
- Required privileges only
- Protected credentials
- Appropriate review

Service accounts must not be used for ordinary interactive user activity where avoidable.

---

# 38. Service Account Privileges

Service-account permissions must be limited to those required by the service.

Administrative privileges must not be assigned automatically because an application requests broad access.

Excessive privileges must be reduced where technically practical.

---

# 39. Service Account Credentials

Service-account credentials must be protected from unauthorized disclosure.

Credentials must not be unnecessarily:

- Shared
- Embedded in scripts
- Stored in readable documentation
- Distributed to users who do not require them

Credential changes must consider service dependencies to avoid preventable outages.

---

# 40. Service Account Review

Service accounts must be reviewed periodically.

Review must determine:

- Whether the service remains required
- Whether the account remains required
- Whether the owner remains valid
- Whether privileges remain appropriate
- Whether credentials require change
- Whether interactive use has occurred improperly

---

# 41. Shared Administrative Accounts

Shared administrative accounts must be avoided where individual accounts are supported.

When a shared administrative credential is technically unavoidable:

- Use must be restricted.
- Credential access must be controlled.
- The reason for use must be documented.
- Individual activity must be attributable through other records where practical.
- The credential must be changed when access changes materially or compromise is suspected.

---

# 42. Generic Accounts

Generic accounts must be avoided unless required for a legitimate system or operational purpose.

Where a generic account is required:

- Purpose must be documented.
- Privileges must be minimized.
- Credential access must be controlled.
- Use must be reviewed.

Generic accounts must not be used to avoid individual accountability.

---

# 43. Application Accounts

Business applications must support individual accounts where required by business and security needs.

Application authorization must be based on:

- Business role
- Required function
- Information sensitivity
- Least privilege

Application authentication does not remove the need for appropriate authorization.

---

# 44. Sensitive Application Access

Access to applications processing Confidential or Restricted information requires appropriate authorization.

Higher-risk access may require:

- Stronger authentication
- More frequent review
- Additional logging
- Restricted administrative access

Classification must influence access requirements.

---

# 45. Contractor Accounts

Contractor accounts must:

- Be individually assigned where supported.
- Have a documented sponsor.
- Have a defined business purpose.
- Be limited to required systems.
- Use least privilege.
- Have a defined duration.
- Be removed when no longer required.

Contractor status does not justify broader access than employee status.

---

# 46. Contractor Sponsorship

Every contractor account must have an accountable Dunder Mifflin sponsor.

The sponsor must confirm:

- Business need
- Required systems
- Required privileges
- Expected duration

Information Technology must not maintain contractor access indefinitely without current sponsorship.

---

# 47. Initial Contractor Authorization

Initial contractor access should normally be authorized for no more than three months.

Continued access requires confirmation that the business need remains valid.

Longer-term contractor access must not become permanent merely because the contractor continues providing services.

---

# 48. Contractor Renewal

Following initial authorization, contractor access may be renewed for periods not exceeding six months at a time.

Renewal requires confirmation of:

- Continued business need
- Sponsor
- Required systems
- Appropriate privileges

Access must be removed when the engagement or requirement ends.

---

# 49. Infinity Contractor Authentication

Infinity contractor access must use individual authentication.

Smart-card multi-factor authentication using a card with a PIN or other approved secret must be used where supported and required by risk.

Contractor credentials must not be shared.

---

# 50. Infinity Contractor Privileged Access

Privileged Infinity production or administrative contractor activity must occur from the designated company-controlled contractor workspace at Scranton Headquarters.

General contractor VPN access for privileged production administration is prohibited.

External remote privileged administration is prohibited.

Contractor status does not create an exception to privileged-access requirements.

---

# 51. Contractor Personnel Changes

The Infinity contractor must provide expected onsite personnel names at least one business day before scheduled access where practical.

Emergency circumstances may allow the advance-notice requirement to be waived with appropriate authorization when one-business-day notice is not possible.

Such circumstances do not create an exception to the prohibition on external remote privileged administration.

Departing or replaced contractor personnel must have access removed promptly.

---

# 52. Remote Access Accounts

Remote access accounts must:

- Be individually authorized.
- Have a legitimate business need.
- Use approved authentication.
- Be limited to required systems.
- Be removed when no longer required.

Remote access must not automatically include privileged access.

Authorization for ordinary remote access does not authorize external remote privileged administration.

---

# 53. Virtual Private Network Authentication

Virtual Private Network (VPN) access must use approved individual authentication.

Smart-card multi-factor authentication must be used where supported and required by risk.

VPN access must be included in applicable account and access reviews.

VPN connectivity does not authorize external remote privileged administration.

---

# 54. External Remote Privileged Access

External remote privileged administration is prohibited.

Privileged administration of significant production resources must occur through approved company-controlled methods and locations.

Ordinary authorized remote access, including VPN access, does not authorize privileged administration.

Emergency-access procedures do not create an exception to the prohibition on external remote privileged administration.

---

# 55. Emergency Access

Emergency access must provide a controlled method of obtaining necessary privileges when ordinary access mechanisms are unavailable or insufficient.

Emergency access must not bypass accountability.

Emergency access does not authorize external remote privileged administration.

Detailed requirements are maintained in [[PROC-005 Emergency Access Procedure]].

---

# 56. Break-Glass Credentials

Break-glass credentials must be:

- Restricted
- Protected
- Available when legitimately required
- Subject to dual custody where practical
- Documented
- Reviewed following use

Knowledge or possession of emergency credentials must be limited to authorized personnel.

---

# 57. Break-Glass Use

Use of break-glass access must be documented.

The review must determine:

- Why emergency access was required
- Who used it
- What systems were accessed
- What actions were performed
- Whether the credential must be changed
- Whether corrective action is required

Emergency access must return to protected status following use.

---

# 58. Account Naming

Account naming must support identification and administration.

User accounts should be distinguishable from:

- Privileged accounts
- Service accounts
- Emergency accounts
- System accounts

Naming must not create unnecessary disclosure of sensitive information.

---

# 59. Default Accounts

Default vendor accounts must be reviewed before production deployment.

Where supported and appropriate, default accounts must be:

- Disabled
- Renamed
- Restricted
- Assigned new credentials

Default passwords must not remain active in production.

---

# 60. Authentication and Authorization

Successful authentication establishes identity to the degree supported by the authentication mechanism.

Authentication does not independently authorize every action available within a system.

Authorization must separately determine what the authenticated user is permitted to access or perform.

---

# 61. Least Privilege

Accounts must receive only the privileges required for authorized duties.

Least privilege applies to:

- Ordinary users
- Executives
- Administrators
- Contractors
- Service accounts
- Application accounts
- Emergency access

Seniority does not independently justify broader access.

---

# 62. Need to Know

Access to sensitive information must reflect legitimate business need.

A user must not receive access to Confidential or Restricted information solely because:

- The user is employed by Dunder Mifflin.
- The user works in the same department.
- The information is technically accessible.
- Access might be convenient in the future.

---

# 63. Separation of Duties

Account design must support separation of duties where practical and justified by risk.

Particular attention must be given to functions involving:

- Vendor setup and payment
- Payroll
- Financial approval
- Privileged administration
- Sensitive changes

Separation must remain proportionate to the organization's staffing and operational requirements.

---

# 64. Account Locking and Disabling

Information Technology may lock or disable an account when necessary due to:

- Suspected compromise
- Termination
- Unauthorized activity
- Dormancy
- Security investigation
- Policy violation
- Other material security concern

Emergency disabling may occur before normal approval when necessary to protect company systems.

---

# 65. Credential Compromise

Known or suspected credential compromise requires prompt action.

Actions may include:

- Password reset
- Account lock
- Smart-card invalidation
- VPN revocation
- Session termination
- Authentication-log review
- Endpoint investigation
- Incident escalation

Response must reflect the privilege and systems associated with the credential.

---

# 66. Privileged Credential Compromise

Suspected compromise of a privileged credential requires immediate escalation.

Response must consider:

- Account disablement
- Credential change
- Other privileged accounts
- Administrative activity
- Persistence
- Affected systems
- Configuration changes
- Evidence preservation

Privileged compromise may require broader investigation than compromise of an ordinary account.

---

# 67. Authentication Logging

Significant authentication systems must log relevant authentication activity where supported.

Events may include:

- Successful authentication
- Failed authentication
- Account lockout
- Privileged authentication
- Account creation
- Account disablement
- Significant account changes

Logs must support reasonable accountability and investigation.

---

# 68. Privileged Activity Logging

Privileged activity must be logged where supported.

Logging should provide sufficient information to determine:

- Account used
- System affected
- Time
- Relevant administrative activity

Logging must not be represented as complete when the underlying system does not record the activity.

---

# 69. Authentication Monitoring

Authentication monitoring must focus on meaningful security conditions.

Examples include:

- Repeated failed logons
- Unexpected privileged access
- Disabled-account activity
- Suspicious remote authentication
- Unusual contractor access
- Authentication associated with a known incident

Dunder Mifflin does not require continuous manual review of every authentication event.

---

# 70. Authentication Time Consistency

Systems generating authentication records must maintain reasonably consistent time where supported.

Consistent timestamps support:

- Incident investigation
- Account review
- Event correlation
- Administrative accountability

Material discrepancies must be corrected.

---

# 71. Account Review Evidence

Access reviews must produce evidence sufficient to demonstrate:

- Systems reviewed
- Accounts reviewed
- Reviewer
- Date
- Decisions
- Required removals or changes
- Completion status

A statement that access was reviewed without supporting evidence is not sufficient assurance.

---

# 72. Privileged Review Evidence

Quarterly privileged-access reviews must specifically identify:

- Privileged users
- Privileged accounts
- Current business or technical need
- Unnecessary standing access
- Contractor privileged access
- Required remediation

Review results must be retained according to applicable record requirements.

---

# 73. Dormant Account Review Evidence

Dormant-account review must document material actions including:

- Account investigated
- Reason for inactivity where known
- Continued authorization
- Disablement
- Exception

Dormant accounts must not remain active solely because no one reviewed them.

---

# 74. Authentication Incident Response

Authentication-related incidents must follow:

- [[POL-009 Incident Response Policy]]
- [[PLN-001 Incident Response Plan]]
- [[PBK-001 Phishing & Credential Compromise Playbook]]
- [[PBK-003 Unauthorized Access Playbook]]

Response must consider both the compromised identity and systems accessible through that identity.

---

# 75. Phishing

Potential phishing involving company credentials must be reported promptly.

Response may include:

- Credential reset
- Account review
- Authentication-log review
- Endpoint examination
- Message investigation
- User notification
- Incident escalation

Entering credentials into a suspected phishing site must be reported even if no unauthorized activity is immediately observed.

---

# 76. Business Email Compromise

Suspected Business Email Compromise (BEC) requires evaluation of:

- Email-account access
- Credential compromise
- Authentication records
- Payment or vendor changes
- Fraudulent messages
- Mailbox settings
- Affected business processes

Authentication controls must be coordinated with financial verification and business-process controls.

---

# 77. Account Recovery

Account-recovery processes must verify the user's identity before resetting or replacing authentication credentials.

Help-desk or administrative personnel must not reset credentials solely because a requester:

- Knows the username
- Claims urgency
- Claims executive authority
- Provides easily obtained personal information

Identity verification must be proportionate to account risk.

---

# 78. Privileged Account Recovery

Recovery of privileged accounts requires stronger verification than ordinary low-risk account recovery.

Privileged credential reset must be performed only by authorized personnel.

Emergency recovery must follow controlled emergency-access processes where applicable.

---

# 79. Authentication Device Replacement

Replacement of a lost or damaged smart card or other authentication device requires:

- Identity verification
- Invalidation of the lost device where appropriate
- Authorization
- Issuance of the replacement
- Documentation

A lost authentication device must not remain valid indefinitely after replacement.

---

# 80. Authentication Testing

Authentication controls must be tested according to risk.

Testing may include:

- Account review
- Configuration inspection
- Dormant-account review
- Privileged-access review
- Authentication-log review
- Termination testing
- Access sampling
- Independent Performance of account procedures
- Technical Testing

Testing must evaluate actual operation rather than policy existence alone.

---

# 81. Termination Testing

Periodic testing must determine whether terminated users have access removed promptly.

Testing may compare:

- Human Resources termination records
- Active Directory
- Business applications
- VPN
- Privileged accounts
- Other significant systems

Exceptions must be investigated.

---

# 82. Access Review Testing

Assessment must evaluate whether required access reviews:

- Occurred
- Covered the required population
- Used appropriate reviewers
- Identified unnecessary access
- Resulted in required remediation

Completion of a review form alone does not prove that inappropriate access was removed.

---

# 83. Authentication Evidence

Evidence may include:

- Account inventories
- Access approvals
- Human Resources notifications
- Account-creation records
- Account-disablement records
- Access reviews
- Privileged-access reviews
- Dormant-account reviews
- Authentication logs
- VPN records
- Smart-card records
- Contractor-access records
- Emergency-access records
- Incident records

Evidence must accurately represent actual conditions.

---

# 84. Evidence Integrity

Personnel must not:

- Falsify access approvals.
- Conceal unauthorized accounts.
- Conceal excessive privileges.
- Alter termination dates to make access removal appear timely.
- Represent Planned multi-factor authentication as implemented.
- Record access reviews that were not performed.
- Represent failed account tests as successful.
- Alter authentication evidence to conceal deficiencies.

Known discrepancies must be documented and addressed.

---

# 85. Authentication Findings

Material authentication or account-security deficiencies must be documented.

Examples include:

- Unauthorized account
- Excessive access
- Unnecessary Domain Admin membership
- Shared privileged credential without justification
- Delayed termination
- Unreviewed dormant account
- Contractor access beyond authorized duration
- Missing privileged-access review
- Weak account-recovery process
- Unprotected service-account credential
- Missing required authentication logging
- Failed smart-card control
- External remote privileged administration

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 86. Authentication Metrics

Authentication and account-security metrics may include:

- Termination completion timeliness
- Delayed termination exceptions
- Dormant accounts
- Disabled dormant accounts
- Privileged-account population
- Domain Admin membership
- Quarterly privileged-review completion
- Annual ordinary-access-review completion
- Contractor accounts approaching expiration
- Unauthorized shared accounts
- Authentication failures requiring investigation
- Multi-factor authentication coverage where implemented
- Open authentication findings

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 87. Risk Relationships

This standard provides significant treatment support for risks including:

- R001 Phishing / Credential Compromise
- R002 Business Email Compromise
- R003 Ransomware
- R004 Malware
- R005 Password / Authentication Weakness
- R006 Infinity Application Compromise
- R009 Sensitive Information Theft / Extortion
- R010 Unauthorized / Excessive Access
- R011 Delayed Termination
- R012 Malicious Insider
- R013 Administrative / Configuration Error
- R014 Lost Device
- R015 Shared Warehouse Account Risk
- R018 Third-Party Technology Failure / Compromise
- R019 Infinity Contractor Dependency / Compromise
- R029 Vendor Fraud
- R030 Sales Fraud
- R031 Payroll Fraud
- R032 Inventory Theft

Risk treatment is maintained in [[RTP-001 Enterprise Risk Treatment Plan]].

---

# 88. Exceptions

Exceptions to this standard require:

- Business justification
- Identification of the affected requirement
- Risk evaluation
- Compensating controls where practical
- Accountable owner
- Defined duration
- Appropriate approval

High or Critical residual risk must be escalated according to [[POL-005 Risk Management Policy]].

This exception process does not authorize exceptions to the prohibition on external remote privileged administration.

---

# 89. Enforcement

Failure to comply with this standard may result in:

- Account disablement
- Privilege removal
- Credential reset
- Access restriction
- Contractor-access removal
- Incident investigation
- Corrective action
- Management escalation
- Other appropriate action

Enforcement must be proportionate to the circumstances.

---

# 90. Traceability

This standard supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Authentication requirements must remain traceable to applicable business and risk requirements.

---

# 91. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-002 Enterprise Security Architecture Program]]
- [[PRO-003 Identity and Access Management Program]]
- [[PRO-005 Security Operations Program]]
- [[PRO-009 Security Governance Framework]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[STD-002 Network Security Standard]]
- [[STD-003 Endpoint Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[STD-009 Infinity Security Standard]]
- [[PROC-001 Joiner-Mover-Leaver Procedure]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-003 Access Review Procedure]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-008 Security Monitoring Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PBK-001 Phishing & Credential Compromise Playbook]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-001 Enterprise Asset Register]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

---

# 92. Review

This standard must be reviewed:

- At least annually
- Following material authentication changes
- Following significant account-security incidents
- Following material assessment findings
- Following significant changes in authentication-related risk

The IT & Information Security Manager coordinates review.

The CIO is responsible for approving material revisions.

---

# 93. Revision History

| Version | Date     | Description                                        | Approval |
| ------- | -------- | -------------------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Authentication & Account Security Standard | CIO      |