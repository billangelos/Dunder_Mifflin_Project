# PRO-003 Identity and Access Management Program

## Document Control

| Field | Value |
|---|---|
| Document ID | PRO-003 |
| Title | Identity and Access Management Program |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Identity or Access Control Change |

---

# 1. Purpose

This program establishes the enterprise Identity and Access Management (IAM) program for Dunder Mifflin, Inc.

The IAM program governs how identities and access are:

- Established
- Authorized
- Provisioned
- Modified
- Reviewed
- Monitored
- Suspended
- Revoked

The program is designed to ensure that access to company systems, information, applications, and administrative capabilities reflects legitimate business need and supports individual accountability.

---

# 2. Scope

This program applies to identities and access associated with:

- Employees
- Contractors
- Temporary personnel
- Information Technology administrators
- Application administrators
- Service accounts
- Emergency accounts
- Shared accounts
- Active Directory
- Corporate endpoints
- Servers
- Business applications
- Infinity
- Cloud-hosted systems
- Virtual Private Network (VPN) access
- Warehouse systems
- Network infrastructure
- Security systems

Physical-access identity requirements are coordinated with the physical and personnel security program.

---

# 3. Program Objectives

The IAM program must:

1. Provide access only to authorized users.
2. Limit access to legitimate business need.
3. Support least privilege.
4. Support individual accountability.
5. Protect privileged access.
6. Maintain reliable account lifecycle processes.
7. Remove access promptly when no longer authorized.
8. Reevaluate access following role changes.
9. Control contractor access.
10. Manage dormant and shared accounts.
11. Provide controlled emergency access.
12. Support authentication appropriate to risk.
13. Produce evidence supporting assessment.
14. Reduce identity-related enterprise risk.

---

# 4. Governing Requirements

The IAM program operates under:

- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[STD-005 Authentication & Account Security Standard]]

Technical architecture is coordinated with [[PRO-002 Enterprise Security Architecture Program]].

---

# 5. IAM Principles

Dunder Mifflin applies the following IAM principles:

- Unique identity where practical
- Individual accountability
- Least privilege
- Need to know
- Business authorization
- Separation of ordinary and privileged access
- Timely access removal
- Periodic access review
- Controlled emergency access
- Evidence-based assurance

Access must not exist solely because it is technically possible.

---

# 6. Identity Lifecycle

The IAM lifecycle is:

**Identity Established → Access Requested → Access Authorized → Access Provisioned → Access Used → Access Reviewed → Access Modified or Revoked**

Personnel events may restart or terminate portions of the lifecycle.

IAM must address the complete lifecycle rather than account creation alone.

---

# 7. Identity Establishment

An identity must be sufficiently established before nonpublic system access is granted.

Identity establishment must be based on appropriate organizational records or authorization.

For employees, Human Resources provides the authoritative personnel relationship.

For contractors, an authorized business sponsor and approved engagement establish the relationship.

---

# 8. Human Resources Authority

Human Resources is the authoritative source for employee status.

Relevant events include:

- Hire
- Transfer
- Role change
- Leave affecting access
- Termination

Information Technology must receive sufficient notification to perform required account actions.

---

# 9. Business Ownership of Access

Business and system owners determine whether access is required for legitimate business activity.

Information Technology implements approved access but does not independently determine every business entitlement.

Technical ability to grant access does not create authority to approve that access.

---

# 10. Access Request

Access requests must identify, as applicable:

- User
- Business need
- System or application
- Required role or permission
- Manager
- System owner
- Requested duration

Requests for privileged or sensitive access require greater scrutiny.

---

# 11. Access Authorization

Access must be authorized before provisioning.

Authorization must reflect:

- Business need
- Job responsibilities
- Information classification
- System sensitivity
- Least privilege
- Separation of duties where applicable

Authorization must be provided by personnel with authority over the relevant business function or system.

---

# 12. Access Provisioning

Information Technology or an authorized system administrator must provision access according to approved authorization.

Provisioning must not exceed the approved scope.

Where practical, provisioning records must identify:

- Account
- Access granted
- Date
- Administrator
- Supporting authorization

---

# 13. Least Privilege

Users must receive only the access required to perform authorized duties.

Least privilege applies to:

- Employees
- Executives
- Information Technology personnel
- Contractors
- Service accounts
- Application accounts
- Emergency access

Position or seniority does not independently justify elevated access.

---

# 14. Need to Know

Access to sensitive information requires legitimate business need.

Users must not receive Confidential or Restricted information access merely because:

- They work for Dunder Mifflin.
- They work in the same department.
- Access might be useful later.
- The system technically permits it.

Information access must remain consistent with [[POL-004 Information Classification & Handling Policy]].

---

# 15. Individual Accountability

Significant user and administrative activity must be attributable to an individual where practical.

IAM must favor unique identities over shared credentials when individual accountability is required.

Exceptions must be based on legitimate operational or technical requirements.

---

# 16. Joiner-Mover-Leaver Model

Dunder Mifflin uses a Joiner-Mover-Leaver (JML) process to manage personnel access.

The process addresses:

- New personnel
- Role changes
- Transfers
- Departures

Detailed requirements are maintained in [[PROC-001 Joiner-Mover-Leaver Procedure]].

---

# 17. Joiners

New employees must receive only the access required for their approved role.

The joiner process must coordinate:

- Human Resources
- Hiring manager
- System owner where required
- Information Technology
- Security awareness requirements

Access must not be created solely by copying another employee's complete access profile without review.

---

# 18. Initial Access

Initial access should be based on:

- Job responsibilities
- Required applications
- Required information
- Required business processes

Common role patterns may be used to simplify provisioning, but inappropriate inherited access must not be granted.

---

# 19. Movers

Transfers and material role changes require reassessment of access.

The expected model is:

**Revoke Previous Business Access → Determine New Business Need → Authorize New Access**

Previous authorization does not automatically remain valid following a material role change.

---

# 20. Transfer Access

Access common to both the previous and new role may remain only when it is still appropriate and included in the new authorization.

Access no longer required must be removed.

Transfers must not result in indefinite accumulation of permissions.

---

# 21. Leavers

When employment or authorized access ends, applicable access must be revoked promptly.

The leaver process must address:

- Active Directory
- Email
- Business applications
- VPN
- Cloud systems
- Privileged accounts
- Smart cards
- Physical credentials
- Company devices
- Other authentication mechanisms

---

# 22. Termination Timing

Termination processing must reflect the nature and timing of the departure.

Where advance notice exists, required actions must be coordinated so access ends at the appropriate time.

Where immediate termination is required, access must be disabled promptly.

---

# 23. Termination Verification

Completion of a termination request does not independently prove that all access was removed.

Verification must determine whether applicable access was actually disabled or revoked.

Material failures must be investigated.

---

# 24. Delayed Termination

Known delayed access removal must be treated as a security issue.

Material delays must be:

- Corrected
- Investigated
- Documented where appropriate
- Escalated when recurring or significant

Repeated failures may result in a formal finding.

---

# 25. Authentication

Authentication must be appropriate to the risk of the access being granted.

Authentication requirements are maintained in [[STD-005 Authentication & Account Security Standard]].

Authentication must not be treated as authorization.

A successfully authenticated user may perform only authorized actions.

---

# 26. Password Authentication

Where passwords are used, they must comply with applicable account-security requirements.

Users must protect passwords from:

- Sharing
- Disclosure
- Phishing
- Insecure storage
- Reuse that creates unnecessary company risk

Known or suspected credential compromise requires prompt response.

---

# 27. Multi-Factor Authentication

Smart-card multi-factor authentication using the card with a PIN or other approved secret must be implemented where supported and required by risk.

Priority must be given to:

- Privileged access
- Remote access
- Sensitive systems
- Higher-risk authentication scenarios

Planned multi-factor authentication does not receive current control credit until implemented and validated.

---

# 28. Smart-Card Lifecycle

Smart-card management must address:

- Authorization
- Issuance
- User assignment
- PIN protection
- Loss
- Replacement
- Revocation
- Recovery at termination

A lost card must be invalidated promptly where supported.

---

# 29. Privileged Access

Privileged access requires stronger control because misuse or compromise may affect multiple systems or users.

Privileged access must be:

- Authorized
- Limited
- Separately identified
- Periodically reviewed
- Used only when required
- Logged where supported

Detailed requirements are maintained in [[PROC-002 Privileged Access Procedure]].

---

# 30. Separate Privileged Accounts

Administrators must use separate privileged accounts where supported.

The ordinary account must be used for routine business activity.

The privileged account must be reserved for administrative activity.

---

# 31. Privileged Account Restrictions

Privileged accounts must not routinely be used for:

- Email
- General web browsing
- Office productivity
- Ordinary business applications
- Other nonadministrative work

This reduces unnecessary exposure of privileged credentials.

---

# 32. Domain Admin Membership

Standing Domain Admin membership must normally be limited to:

- IT & Information Security Manager
- System Administrator

Additional standing membership requires documented justification.

Occasional need for elevated authority does not automatically justify permanent Domain Admin membership.

---

# 33. Dedicated Administrative Workstations

Higher-risk privileged administration must use designated company-controlled administrative workstations where required by architecture.

These systems must be configured for administrative activity and must restrict unnecessary ordinary user activity.

---

# 34. External Remote Privileged Administration

External remote privileged administration is prohibited.

Privileged administration of significant production resources must occur through approved company-controlled methods and locations.

Ordinary authorized remote access, including Virtual Private Network (VPN) access, does not authorize privileged administration.

Contractor status, operational convenience, emergency conditions, or ordinary remote-access authorization do not create an exception to this prohibition.

---

# 35. Privileged Access Review

Privileged access must be reviewed at least quarterly.

Review must evaluate:

- Current administrative responsibilities
- Privileged accounts
- Domain Admin membership
- Unnecessary standing access
- Contractor privileged access
- Other elevated permissions

Unnecessary access must be removed.

---

# 36. Ordinary Access Review

Ordinary user access must be reviewed at least annually.

Reviews must evaluate whether access remains appropriate to:

- Employment status
- Current role
- Business need
- Information sensitivity
- System responsibilities

Detailed requirements are maintained in [[PROC-003 Access Review Procedure]].

---

# 37. Access Review Responsibility

Business and system owners must participate in access review where business authorization is required.

Information Technology may provide account information and execute changes but must not automatically approve continued business access on behalf of the responsible owner.

---

# 38. Access Review Decisions

Access reviews must result in explicit decisions where practical, including:

- Retain
- Modify
- Remove
- Investigate

Review results requiring changes must be tracked through completion.

---

# 39. Dormant Accounts

Accounts with no expected activity for 30 days must be investigated where appropriate.

Accounts reaching 60 days of inactivity must be disabled unless continued access is justified and authorized.

Dormant-account review must account for legitimate:

- Leave
- Infrequent administrative use
- Emergency access
- Service accounts

---

# 40. Dormant Account Reauthorization

A disabled dormant account must not be reactivated automatically.

Reactivation requires confirmation that:

- The user remains authorized.
- The business need remains valid.
- The requested access remains appropriate.

---

# 41. Shared Accounts

Shared accounts must be avoided when unique accounts are supported and individual accountability is required.

An approved shared account requires:

- Defined purpose
- Operational or technical justification
- Minimal privileges
- Controlled credential access
- Periodic review

Shared accounts must not be created solely to reduce administrative work.

---

# 42. Warehouse Shared Accounts

Shared Windows accounts may be used on warehouse workstations where operationally justified.

The shared Windows account must:

- Have minimal workstation privileges.
- Not provide unnecessary administrative access.
- Support the warehouse operational model.

This exception does not remove the requirement for accountability in significant Warehouse Management System activity.

---

# 43. Warehouse Management System Accountability

Significant Warehouse Management System transactions must require individual authentication or another reliable method of individual attribution.

Significant activity includes transactions affecting:

- Inventory adjustments
- Receiving
- Shipping
- Other important inventory records

The individual business transaction, rather than merely the Windows workstation session, must provide the required accountability.

---

# 44. Contractor Identity Management

Contractors require:

- Identified business sponsor
- Defined engagement
- Defined access
- Appropriate authorization
- Defined duration
- Appropriate authentication
- Least privilege

Contractor access must not become indefinite.

Detailed requirements are maintained in [[PROC-004 Contractor Access Procedure]].

---

# 45. Contractor Confidentiality

Nonemployees receiving access to sensitive information or systems must have an appropriate Non-Disclosure Agreement (NDA) or equivalent enforceable confidentiality obligation before access when required by the nature of the access.

The confidentiality obligation does not replace:

- Access control
- Authentication
- Technical security
- Third-party review
- Monitoring

---

# 46. Contractor Access Duration

Initial contractor access may be approved for up to three months when appropriate.

Continued access may be renewed for periods not exceeding six months at a time.

Renewal requires confirmation of:

- Sponsor
- Continued business need
- Required systems
- Appropriate privileges

---

# 47. Contractor Termination

Contractor access must be removed promptly when:

- The engagement ends.
- The contractor changes personnel.
- The access is no longer required.
- Authorization is withdrawn.
- Security conditions require removal.

Business sponsors must notify responsible personnel when contractor access should end.

---

# 48. Infinity Contractor Access

Infinity contractor access requires heightened control because of the contractor's ability to affect a significant company-developed application.

Controls must include:

- Individual authorization
- Individual authentication
- Defined duration
- Least privilege
- Change control
- Appropriate logging
- Company-controlled source code and documentation

---

# 49. Infinity Contractor Privileged Administration

Privileged Infinity production or administrative contractor activity must occur from the designated company-controlled contractor workspace at Scranton Headquarters.

General contractor VPN access for privileged production administration is prohibited.

External remote privileged administration is prohibited.

Ordinary remote access authorization does not authorize privileged Infinity production or administrative activity.

Expected onsite personnel names must be provided at least one business day before scheduled access where practical.

Emergency circumstances may permit an exception to the advance personnel-notice requirement when one-business-day notice is not possible, but do not create an exception to the prohibition on external remote privileged administration.

---

# 50. Service Accounts

Service accounts must have:

- Documented purpose
- Accountable owner
- Required privileges only
- Protected credentials
- Periodic review

Service accounts must not become unmanaged identities merely because they are not assigned to a human user.

---

# 51. Service Account Use

Service accounts must avoid ordinary interactive use where practical.

Where interactive use is technically required:

- The reason must be documented.
- Access must be restricted.
- Activity must be attributable where practical.

Service accounts must not be used as informal shared administrator accounts.

---

# 52. Service Account Review

Service accounts must be periodically reviewed to determine:

- Whether the service still exists
- Whether the account remains required
- Whether privileges remain appropriate
- Whether ownership remains valid
- Whether credentials require action

Unused accounts must be disabled or removed.

---

# 53. Application Accounts

Application access must reflect:

- Business role
- Required function
- Information classification
- Least privilege
- Separation of duties where applicable

Application access must not automatically mirror broad network or Active Directory access unless specifically appropriate.

---

# 54. Sensitive System Access

Access to systems processing Confidential or Restricted information requires appropriate authorization.

Higher-risk systems may require:

- Stronger authentication
- More frequent review
- Additional logging
- Restricted administration

Information classification must influence IAM requirements.

---

# 55. Remote Access

Remote access requires:

- Legitimate business need
- Individual authorization
- Approved authentication
- Required systems only
- Periodic review

Remote access does not automatically include administrative authority.

Authorization for ordinary remote access does not authorize external remote privileged administration.

---

# 56. Virtual Private Network Access

Virtual Private Network (VPN) access must be assigned to identifiable authorized users.

VPN access must be:

- Approved
- Limited to business need
- Included in access review
- Removed when no longer required

Smart-card multi-factor authentication must be used where supported and required by risk.

VPN connectivity does not authorize external remote privileged administration.

---

# 57. Emergency Access

Dunder Mifflin must maintain controlled emergency access sufficient to support critical administration when normal access is unavailable.

Emergency access must preserve:

- Authorization
- Accountability
- Credential protection
- Review

Emergency access does not authorize external remote privileged administration.

Detailed requirements are maintained in [[PROC-005 Emergency Access Procedure]].

---

# 58. Break-Glass Access

Break-glass credentials must be protected and available only for legitimate emergency use.

Dual custody must be used where practical.

Emergency credentials must not be used to bypass ordinary access controls for convenience.

Break-glass access does not create an exception to the prohibition on external remote privileged administration.

---

# 59. Break-Glass Review

Every use of break-glass access must be reviewed.

Review must determine:

- Why emergency access was required
- Who used it
- Systems accessed
- Actions performed
- Whether credentials require replacement
- Whether corrective action is required

---

# 60. Account Recovery

Account recovery must verify identity before credentials are reset or replaced.

Urgency, executive status, or familiarity with basic personal information is not sufficient by itself.

Higher-risk accounts require stronger recovery verification.

---

# 61. Privileged Account Recovery

Privileged account recovery must be restricted to authorized personnel and use stronger identity verification.

Where normal privileged access cannot be restored safely, emergency-access procedures must be used.

Emergency recovery remains subject to the prohibition on external remote privileged administration.

---

# 62. Separation of Duties

IAM must support separation of duties where practical and justified by risk.

Particular attention must be given to:

- Vendor setup and payment
- Payroll
- Financial approval
- Privileged administration
- Sensitive configuration changes

Separation of duties must remain proportionate to Dunder Mifflin's staffing and operational requirements.

---

# 63. Financial Access

Access affecting financial transactions must support appropriate separation between functions such as:

- Vendor creation
- Purchasing
- Invoice approval
- Payment
- Payroll preparation
- Payroll approval

IAM supports these business controls but does not replace business-process verification.

---

# 64. Access to Vendor Master Data

Access to create or modify vendor master information must be restricted.

Changes to sensitive payment information require appropriate authorization and business verification.

IAM must support accountability for material vendor changes.

---

# 65. Payroll Access

Payroll and employee compensation access must be limited to authorized personnel.

Access must reflect separation between:

- Employee-record maintenance
- Payroll preparation
- Approval
- Payment

where practical.

---

# 66. IAM and Malicious Insider Risk

IAM reduces malicious insider risk through:

- Least privilege
- Need to know
- Individual accountability
- Privileged separation
- Access review
- Timely termination

IAM cannot eliminate malicious insider risk when an authorized individual intentionally misuses legitimate access.

Personnel, financial, physical, monitoring, and incident-response controls remain necessary.

---

# 67. IAM and Phishing

IAM reduces phishing and credential-compromise risk through:

- Stronger authentication
- Credential protection
- Least privilege
- Privileged-account separation
- Authentication monitoring
- Incident response

Authentication controls must operate alongside email security and security awareness.

---

# 68. IAM and Business Email Compromise

Business Email Compromise (BEC) risk requires coordination between IAM and business-process controls.

Authentication can reduce account compromise, but payment or vendor changes must still receive appropriate business verification.

A successfully authenticated email request does not independently prove that a financial transaction is legitimate.

---

# 69. Access Logging

Significant systems must log access and authentication activity where supported.

Relevant records may include:

- Authentication
- Failed authentication
- Account creation
- Account disablement
- Privileged access
- Significant account changes
- Remote access

Logging must support reasonable investigation and accountability.

---

# 70. IAM Monitoring

IAM monitoring must focus on meaningful security conditions including:

- Repeated failed authentication
- Unexpected privileged access
- Disabled-account activity
- Suspicious remote access
- Unexpected contractor activity
- Dormant accounts
- Access associated with known incidents

Continuous manual review of every authentication event is not required.

---

# 71. IAM Incident Response

Known or suspected identity compromise must be handled according to:

- [[POL-009 Incident Response Policy]]
- [[PLN-001 Incident Response Plan]]
- [[PBK-001 Phishing & Credential Compromise Playbook]]
- [[PBK-003 Unauthorized Access Playbook]]

Response must consider both the identity and the systems accessible through that identity.

---

# 72. Credential Compromise Response

Response to known or suspected credential compromise may include:

- Account lock
- Password reset
- Smart-card invalidation
- VPN revocation
- Session termination
- Authentication-log review
- Endpoint investigation
- Privileged-account review
- Incident escalation

Response must reflect the potential impact of the affected credential.

---

# 73. IAM Documentation

IAM documentation must be sufficient to support:

- Provisioning
- Access review
- Termination
- Contractor administration
- Privileged access
- Emergency access
- Assessment
- Investigation

IAM processes must not depend unnecessarily on undocumented personal knowledge.

---

# 74. Access Records

IAM records may include:

- Access requests
- Approvals
- Provisioning records
- Modification records
- Termination records
- Access reviews
- Privileged-access reviews
- Contractor records
- Emergency-access records
- Authentication records

Records must be protected according to their sensitivity.

---

# 75. Evidence Requirements

IAM activities must produce sufficient evidence to demonstrate that required actions occurred.

Evidence must answer questions such as:

- Who received access?
- Who approved it?
- What access was granted?
- When was it granted?
- Does the access remain appropriate?
- When was it removed?
- Was required review completed?

Policy statements alone are not evidence that IAM controls operated.

---

# 76. Joiner Evidence

Joiner evidence may include:

- Human Resources record
- Manager request
- System-owner approval
- Account-creation record
- Assigned access
- Authentication setup

Evidence must support the relationship between business need and access granted.

---

# 77. Mover Evidence

Mover evidence may include:

- Role-change notification
- Previous access review
- Revocation records
- New access authorization
- New provisioning records

Evidence must demonstrate that previous-role access was not simply accumulated.

---

# 78. Leaver Evidence

Leaver evidence may include:

- Human Resources termination record
- Account-disablement record
- VPN removal
- Application-access removal
- Privileged-account removal
- Authentication-device recovery
- Company-device recovery

Evidence must support timely termination.

---

# 79. Access Review Evidence

Access reviews must document:

- Population reviewed
- Reviewer
- Date
- Access evaluated
- Decisions
- Required changes
- Completion of remediation

A completed review checklist without evidence of required access removal is not sufficient to prove remediation.

---

# 80. Privileged Access Evidence

Privileged-access evidence may include:

- Approval
- Privileged account
- Assigned administrator
- Scope
- Review record
- Administrative logs
- Removal record

Standing privileged access must remain justifiable.

---

# 81. Contractor Access Evidence

Contractor-access evidence may include:

- Business sponsor
- Engagement
- Confidentiality agreement where required
- Access authorization
- Account
- Systems authorized
- Start date
- Expiration
- Renewal
- Termination

Contractor access must remain traceable to an active business requirement.

---

# 82. Emergency Access Evidence

Emergency-access evidence must include:

- Reason
- Authorization where practical
- User
- Time
- Systems accessed
- Actions performed
- Post-use review
- Credential action where required

Emergency conditions do not remove evidence requirements or authorize external remote privileged administration.

---

# 83. Evidence Integrity

Personnel must not:

- Create false access approvals.
- Alter access dates to conceal delayed provisioning or termination.
- Conceal unauthorized accounts.
- Conceal excessive privileges.
- Represent Planned multi-factor authentication as implemented.
- Record access reviews that were not performed.
- Falsify contractor expiration or renewal.
- Represent failed IAM tests as successful.

Known discrepancies must be documented and addressed.

---

# 84. IAM Assessment

IAM controls must be assessed using methods appropriate to the control.

Methods may include:

- Inspection
- Interviews
- Account review
- Access sampling
- Authentication configuration review
- Log review
- Technical Testing
- Independent Performance
- Reconciliation with Human Resources records

Assessment must evaluate actual operation.

---

# 85. Joiner Testing

Assessment may sample new employees and determine whether:

- Authorization existed.
- Access matched the approved role.
- Sensitive access received required approval.
- Provisioning records exist.

Testing must identify excessive or unauthorized initial access.

---

# 86. Mover Testing

Assessment may sample transferred employees and determine whether:

- Previous access was reassessed.
- Unnecessary access was removed.
- New access was authorized.
- Access accumulation occurred.

Mover testing is important because role changes can create excessive access over time.

---

# 87. Leaver Testing

Assessment must periodically compare terminated personnel records against significant systems.

Testing may include:

- Active Directory
- VPN
- Business applications
- Privileged accounts
- Other significant access

Active access belonging to a terminated user requires investigation.

---

# 88. Privileged Access Testing

Privileged-access assessment must determine whether:

- Access is authorized.
- Separate privileged accounts are used where required.
- Standing Domain Admin membership is justified.
- Quarterly reviews occurred.
- Unnecessary privileges were removed.
- Contractor privileged access remains appropriate.
- External remote privileged administration has not been authorized or enabled.

---

# 89. Access Review Testing

Assessment must determine whether required access reviews:

- Occurred on schedule.
- Included the appropriate population.
- Used appropriate reviewers.
- Identified inappropriate access.
- Resulted in completed remediation.

Review completion and remediation completion are separate conditions.

---

# 90. Contractor Access Testing

Assessment may compare active contractor accounts against:

- Current engagements
- Approved sponsors
- Authorized systems
- Expiration dates
- Renewal records

Expired or unsupported contractor access requires investigation.

For contractor privileged access, assessment must also confirm that the prohibition on external remote privileged administration is maintained.

---

# 91. Emergency Access Testing

Emergency-access assessment must determine whether:

- Credentials remain protected.
- Access remains available for legitimate emergencies.
- Dual custody is maintained where practical.
- Use is documented.
- Post-use review occurs.
- Emergency-access mechanisms do not enable external remote privileged administration.

A break-glass account that cannot be accessed during an emergency is not an effective emergency-access control.

---

# 92. IAM Findings

Material IAM deficiencies must be documented.

Examples include:

- Unauthorized account
- Excessive access
- Delayed termination
- Unnecessary Domain Admin membership
- Missing privileged-access review
- Unreviewed dormant account
- Contractor account beyond authorized duration
- Shared privileged account without justification
- Missing access approval
- Weak account recovery
- Uncontrolled emergency credential
- Failed access-removal process
- External remote privileged administration

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 93. IAM Corrective Action

IAM corrective action must identify:

- Deficiency
- Affected identity or process
- Responsible owner
- Required remediation
- Due date
- Validation method

Corrective action is not complete until remediation is implemented and appropriately verified.

---

# 94. IAM Metrics

IAM metrics may include:

- New-account provisioning accuracy
- Termination completion timeliness
- Delayed termination exceptions
- Dormant accounts
- Privileged-account population
- Domain Admin membership
- Quarterly privileged-review completion
- Annual ordinary-access-review completion
- Contractor accounts approaching expiration
- Expired contractor accounts
- Unauthorized shared accounts
- Multi-factor authentication coverage where implemented
- Open IAM findings
- Overdue IAM corrective actions

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 95. IAM Key Performance Indicators

Key Performance Indicators (KPIs) may measure whether IAM processes are operating as intended.

Examples include:

- Percentage of required access reviews completed on time
- Percentage of sampled terminations completed within required timing
- Percentage of contractor accounts with current authorization
- Percentage of IAM findings remediated by due date

KPIs measure performance and do not independently establish control effectiveness.

---

# 96. IAM Key Risk Indicators

Key Risk Indicators (KRIs) may identify increasing identity-related risk.

Examples include:

- Increase in delayed terminations
- Increase in dormant active accounts
- Increase in unnecessary privileged accounts
- Increase in expired contractor access
- Increase in unauthorized shared accounts

KRI thresholds must be defined in [[REG-005 Security Metrics Catalog]] where used.

---

# 97. IAM Reporting

IAM information must be reported at a level appropriate to the audience.

Operational reporting may include:

- Accounts requiring action
- Access-review status
- Dormant accounts
- Contractor expirations
- Authentication exceptions

Management reporting may include:

- IAM performance
- Significant findings
- Overdue remediation
- Privileged-access concerns
- Risk trends

Executive reporting should focus on material enterprise risk and decisions requiring senior leadership.

---

# 98. IAM and Risk Management

IAM control performance must inform risk management.

Material IAM weaknesses may affect current residual risk for risks including:

- Credential compromise
- Excessive access
- Delayed termination
- Malicious insider
- Contractor compromise
- Fraud

Validated improvement may support future risk reassessment.

---

# 99. Current and Target Residual Risk

Planned IAM controls may support target residual-risk estimates.

They do not reduce current residual risk merely because they are:

- Approved
- Documented
- Budgeted
- Scheduled
- Partially deployed

Control effectiveness must be supported by implementation and validation.

---

# 100. Risk Relationships

This program provides significant treatment support for risks including:

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

# 101. Program Exceptions

IAM exceptions require:

- Business justification
- Affected requirement
- Risk evaluation
- Compensating controls where practical
- Accountable owner
- Defined duration
- Appropriate approval

High or Critical residual risk must be escalated according to [[POL-005 Risk Management Policy]].

This exception process does not authorize an exception to the prohibition on external remote privileged administration.

---

# 102. Continuous Improvement

IAM improvement follows:

**Requirement → Access Control → Implementation → Evidence → Assessment → Finding → Remediation → Retest → Risk Reassessment**

IAM must improve when evidence demonstrates that existing processes or controls do not adequately manage access risk.

Improvement must focus on meaningful risk reduction rather than unnecessary administrative complexity.

---

# 103. Control Inventory

IAM controls must be represented in [[REG-003 Enterprise Security Control Inventory]] where applicable.

Control records should identify:

- Control objective
- Control owner
- Related requirement
- Related risk
- Implementation status
- Evidence
- Assessment method
- Effectiveness

The control inventory connects IAM requirements to assurance activity.

---

# 104. Traceability

The IAM program supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

IAM requirements must remain traceable through the control lifecycle.

---

# 105. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-002 Enterprise Security Architecture Program]]
- [[PRO-005 Security Operations Program]]
- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[PRO-009 Security Governance Framework]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[STD-003 Endpoint Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
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

# 106. Program Review

This program must be reviewed:

- At least annually
- Following material IAM changes
- Following significant identity-related incidents
- Following material assessment findings
- Following significant organizational changes
- Following material changes in identity-related risk

The CIO coordinates program review.

Material revisions require CEO approval.

---

# 107. Revision History

| Version | Date     | Description                                    | Approval |
| ------- | -------- | ---------------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Identity and Access Management Program | CEO      |