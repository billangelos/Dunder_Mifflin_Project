# PROC-003 Access Review Procedure

## Document Control

| Field | Value |
|---|---|
| Document ID | PROC-003 |
| Title | Access Review Procedure |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Access Review Process Change |

---

# 1. Purpose

This procedure defines how Dunder Mifflin, Inc. performs periodic reviews of logical access.

Access reviews verify that access remains appropriate after it has been granted.

The procedure is designed to identify:

- Access no longer required
- Excessive access
- Unauthorized access
- Dormant accounts
- Unsupported contractor access
- Unnecessary privileged access
- Access inconsistent with current job responsibilities

Access review is a control activity, not merely an administrative inventory exercise.

---

# 2. Scope

This procedure applies to significant logical access involving:

- Active Directory
- Business applications
- File services
- Servers
- Network administration
- Cloud-hosted systems
- Virtual Private Network (VPN)
- Infinity
- Warehouse Management System (WMS)
- Privileged accounts
- Contractor accounts
- Other security-significant systems

Physical-access reviews are addressed through the physical and personnel security program.

---

# 3. Authority

This procedure implements requirements established by:

- [[POL-003 Access Control Policy]]
- [[PRO-003 Identity and Access Management Program]]
- [[STD-005 Authentication & Account Security Standard]]

Privileged-access requirements are further supported by [[PROC-002 Privileged Access Procedure]].

---

# 4. Access Review Objectives

Access reviews must:

1. Confirm that users remain authorized.
2. Confirm that access remains necessary.
3. Identify excessive permissions.
4. Identify dormant accounts.
5. Identify unauthorized accounts.
6. Confirm privileged access remains justified.
7. Confirm contractor access remains valid.
8. Identify access inconsistent with current roles.
9. Produce evidence.
10. Result in remediation when inappropriate access is identified.

---

# 5. Review Types

Dunder Mifflin performs:

1. Ordinary Access Review
2. Privileged Access Review
3. Dormant Account Review
4. Contractor Access Review
5. Event-Driven Access Review

These activities may overlap when the same account belongs to multiple review populations.

---

# 6. Ordinary Access Review Frequency

Ordinary user access must be reviewed at least annually.

The annual review must address significant access appropriate to the user's:

- Current employment
- Current role
- Business responsibilities
- Information requirements

Higher-risk access may be reviewed more frequently.

---

# 7. Privileged Access Review Frequency

Privileged access must be reviewed at least quarterly.

The quarterly review must include significant privileged access involving:

- Active Directory
- Servers
- Network devices
- Applications
- Databases
- Cloud systems
- Security systems
- Backup systems
- Contractor administration

---

# 8. Dormant Account Review

Accounts with no expected activity for 30 days must be investigated where appropriate.

Accounts reaching 60 days of inactivity must be disabled unless continued access is:

- Legitimately required
- Expected to be inactive
- Appropriately authorized

Dormancy alone does not establish that an account is unauthorized.

---

# 9. Contractor Access Review

Contractor access must be reviewed according to:

- Engagement status
- Sponsor
- Authorized systems
- Required privileges
- Expiration
- Renewal

Contractor accounts must not remain active merely because no one requested their removal.

---

# 10. Event-Driven Review

Access must be reviewed outside the normal schedule when events create reason to question whether existing access remains appropriate.

Events may include:

- Transfer
- Material role change
- Termination
- Contractor personnel change
- Security incident
- Suspected credential compromise
- Significant organizational change
- Material system change

---

# 11. Review Roles

Access review may involve:

- IT & Information Security Manager
- System Administrator
- Network/Security Administrator
- Information Security Analyst
- Business manager
- System owner
- Information owner
- Human Resources
- Contractor sponsor

The reviewer must have sufficient authority and knowledge to evaluate the access.

---

# 12. Information Technology Responsibility

Information Technology must support access reviews by:

- Producing account information
- Producing relevant group or permission information
- Identifying technical account types
- Implementing approved removals or changes
- Providing evidence of remediation

Information Technology must not automatically approve continued business access solely because it administers the system.

---

# 13. Business Manager Responsibility

Business managers must evaluate whether employee access remains appropriate to current job responsibilities.

Managers must not approve access solely because:

- The user already has it.
- Removing it may be inconvenient.
- The user might need it in the future.

Continued access requires current business need.

---

# 14. System Owner Responsibility

System owners must participate where system-specific authorization is required.

The system owner must evaluate whether access remains appropriate to:

- Business function
- Information sensitivity
- User responsibilities
- Separation-of-duties requirements

---

# 15. Human Resources Support

Human Resources records may be used to verify:

- Employment status
- Position
- Department
- Manager
- Transfer
- Termination

Human Resources information must be handled according to its sensitivity.

---

# 16. Review Population

Before review begins, the reviewer must obtain a sufficiently complete population of relevant accounts and access.

The population may include:

- Active user accounts
- Group memberships
- Application roles
- VPN accounts
- Privileged accounts
- Contractor accounts
- Dormant accounts
- Shared accounts

Known access must not be intentionally excluded.

---

# 17. Population Completeness

The reviewer must consider whether the source used for the review is sufficiently complete.

For example, an Active Directory account list may not include:

- Application-local accounts
- Cloud-provider accounts
- Network-device accounts
- Database-local accounts

Multiple sources may be required for higher-risk reviews.

---

# 18. Account Classification

Accounts should be identified by type where practical.

Account types may include:

- Ordinary employee
- Privileged employee
- Contractor
- Service
- Shared
- Emergency
- System

Account type affects the appropriate review criteria.

---

# 19. Ordinary User Review

For each ordinary user, the reviewer must determine whether:

- The user remains employed or otherwise authorized.
- The user's current role supports the access.
- The access remains necessary.
- Sensitive access remains justified.
- Unnecessary access exists.
- Role changes created access accumulation.

---

# 20. Employment Status

Active accounts must be compared against authoritative personnel information where appropriate.

An account belonging to a terminated employee requires immediate investigation.

The account must not remain active merely because it appears on a prior approved access list.

---

# 21. Current Role

The reviewer must consider the user's current role rather than only the role held when access was originally approved.

Material transfers or job changes must trigger evaluation of previous access.

The review should identify access retained from earlier positions.

---

# 22. Business Need

Continued access must have a current business purpose.

The reviewer should ask:

- Does the user still perform this function?
- Does the user still require this system?
- Does the user still require this information?
- Is this level of permission still necessary?

Access without a current requirement must be removed.

---

# 23. Sensitive Access

Access to Confidential or Restricted information requires specific attention.

The reviewer must determine whether the user's current responsibilities continue to justify the access.

Sensitive access must not be retained solely because it was previously approved.

---

# 24. Least Privilege Review

The review must evaluate whether the user has more authority than required.

Where excessive access exists, the reviewer must determine whether to:

- Reduce permissions
- Remove access
- Investigate the reason
- Document an approved exception

Least privilege must be evaluated against actual job requirements.

---

# 25. Mover Access Accumulation

Access reviews must specifically consider whether transferred employees accumulated permissions from previous roles.

Potential indicators include:

- Membership in groups associated with multiple departments
- Access to systems unrelated to the current role
- Retained privileged access
- Sensitive access without current business need

Mover issues must be remediated.

---

# 26. Privileged Review

Privileged access must receive greater scrutiny because of its potential impact.

For each significant privileged account, the reviewer must determine:

- Account owner
- Administrative responsibility
- Current need
- Privilege level
- Standing-access justification
- Account activity
- Applicable expiration
- Contractor status where relevant

---

# 27. Domain Admin Review

Every quarterly privileged-access review must specifically evaluate Domain Admin membership.

Expected standing membership is normally limited to:

- IT & Information Security Manager
- System Administrator

Additional standing membership requires documented justification and approval.

---

# 28. Separate Privileged Accounts

The review must determine whether administrators use separate privileged accounts where required.

A privileged account used as the administrator's routine business identity requires investigation.

---

# 29. Standing Privilege

The reviewer must determine whether standing administrative authority remains necessary.

If elevated authority is required only occasionally, temporary access may be more appropriate.

Standing privilege must not be retained solely because it may be convenient later.

---

# 30. Administrative Scope

The review must compare administrative access with actual technical responsibilities.

Examples include:

- Network administrator access to network infrastructure
- System administrator access to servers
- Application administrator access to assigned applications

Broad enterprise administration must not be granted when narrower authority is sufficient.

---

# 31. Contractor Privileged Access

Contractor privileged access must be reviewed for:

- Active engagement
- Current sponsor
- Authorized systems
- Required privilege
- Expiration
- Renewal
- Compliance with location and access restrictions

Unsupported contractor privileged access must be removed.

---

# 32. Dormant Privileged Accounts

Dormant privileged accounts require heightened attention.

An inactive privileged account must not remain active merely because it may be useful later.

The reviewer must determine whether the account should be:

- Retained with justification
- Disabled
- Removed

---

# 33. Service Account Review

Service accounts must be reviewed according to their function.

The reviewer must determine whether:

- The service still exists.
- The account remains required.
- Ownership is known.
- Privileges remain appropriate.
- Interactive use is restricted where appropriate.

Service accounts must not be evaluated as ordinary employee accounts.

---

# 34. Service Account Dormancy

Normal user inactivity may not be a meaningful indicator for every service account.

Review must consider:

- Service function
- Expected authentication pattern
- Application dependency

A service account must not be disabled solely because ordinary interactive logon activity is absent.

---

# 35. Shared Account Review

Shared accounts must be reviewed to determine whether:

- The account remains operationally or technically necessary.
- Unique accounts could replace it.
- Privileges remain minimal.
- Credential access remains controlled.
- The account has become unnecessary.

Shared accounts must not persist solely because they are familiar.

---

# 36. Warehouse Shared Windows Accounts

Warehouse shared Windows accounts may remain where operationally justified.

Review must confirm that the shared account:

- Remains required.
- Has minimal workstation privileges.
- Does not provide unnecessary administrative authority.

The review must separately consider individual WMS accountability.

---

# 37. Warehouse Management System Review

Significant Warehouse Management System activity must remain attributable to individuals.

Review must evaluate whether individual authorization remains appropriate for personnel performing significant:

- Inventory adjustments
- Receiving
- Shipping
- Other important inventory transactions

A shared Windows workstation account must not undermine transaction accountability.

---

# 38. Contractor Review

Contractor accounts must be compared with current contractor records.

The reviewer must confirm:

- Current business sponsor
- Active engagement
- Authorized systems
- Appropriate privilege
- Current authorization period

Unsupported access must be removed.

---

# 39. Contractor Expiration

Accounts approaching expiration must be reviewed before renewal.

Renewal must not occur automatically.

The sponsor must confirm continued:

- Business need
- Engagement
- Required systems
- Appropriate privileges

---

# 40. Contractor Renewal

Initial contractor access may be approved for up to three months.

Subsequent renewals may not exceed six months at a time.

Each renewal requires a new confirmation of continued need.

---

# 41. Infinity Contractor Review

Infinity contractor access requires specific review because of the contractor's ability to affect the company-developed application.

Review must consider:

- Current personnel
- Current sponsor
- Production access
- Privileged access
- Source-code access
- Authorized duration
- Onsite administrative restrictions
- Individual authentication

---

# 42. VPN Access Review

VPN access must be reviewed to confirm continued remote-access need.

The reviewer must determine whether:

- The user remains authorized.
- Remote access remains required.
- The account is active for legitimate reasons.
- Access should be removed.

VPN access must not remain indefinitely after the business requirement ends.

---

# 43. Application Access Review

Significant application access must be reviewed according to application risk.

The review should consider:

- User
- Role
- Permissions
- Sensitive functions
- Administrative access
- Current business need

Application-local accounts must not be omitted merely because they are not visible in Active Directory.

---

# 44. File Access Review

Sensitive file access should be reviewed where appropriate.

Review may consider:

- Group membership
- Folder permissions
- Current role
- Information classification
- Business need

Broad file access without a current requirement must be corrected.

---

# 45. Cloud Access Review

Company-controlled cloud access must be included in applicable reviews.

Review must address:

- User accounts
- Administrative accounts
- Remote access
- Provider-management access
- Application access

Cloud hosting does not remove the need for access review.

---

# 46. Emergency Account Review

Emergency or break-glass accounts must be reviewed to determine whether:

- The account remains required.
- Credentials remain protected.
- Access remains available for legitimate emergencies.
- Unauthorized use occurred.
- Post-use review was completed where applicable.

Emergency accounts must not be treated as ordinary dormant accounts.

---

# 47. Dormant Account Identification

Information Technology must identify dormant accounts using available system records.

The review must distinguish between:

- Unexpected inactivity
- Approved leave
- Infrequently used administrative accounts
- Emergency accounts
- Service accounts
- Other legitimate inactivity

---

# 48. Thirty-Day Dormancy

At 30 days of unexpected inactivity, the account must be investigated where appropriate.

Investigation may include confirmation with:

- Manager
- Human Resources
- System owner
- Account owner

The objective is to determine whether access remains legitimate.

---

# 49. Sixty-Day Dormancy

At 60 days of inactivity, an account must be disabled unless continued access is justified and authorized.

The justification must be documented where appropriate.

Dormant access must not remain active indefinitely without review.

---

# 50. Dormant Account Reactivation

A disabled dormant account may be reactivated only after confirming:

- User remains authorized.
- Business need remains valid.
- Requested access remains appropriate.

Reactivation must not occur solely because the user remembers the old credentials.

---

# 51. Review Preparation

Before performing an access review, the reviewer must identify:

- Systems in scope
- Review population
- Review period
- Review type
- Required reviewers
- Relevant personnel information
- Relevant contractor information

Preparation must support a complete and efficient review.

---

# 52. Review Data

Review data may include:

- User account lists
- Group membership
- Application roles
- Privileged groups
- VPN accounts
- Contractor records
- Dormant-account reports
- Human Resources records
- Prior review results

Data must be sufficiently current to support the review.

---

# 53. Review Distribution

Access-review information must be provided only to personnel who require it.

Review records may contain:

- Employee information
- Security information
- Privileged-account details
- Sensitive application information

Distribution must be controlled accordingly.

---

# 54. Reviewer Instructions

Reviewers must receive sufficient instructions to understand that the task is not merely to confirm that the listed user is familiar.

The reviewer must determine whether the listed access remains appropriate.

Recognition of the employee's name does not establish continued authorization.

---

# 55. Review Decisions

Each reviewed access item should result in one of the following decisions where practical:

- Retain
- Modify
- Remove
- Investigate

The decision must be based on current need.

---

# 56. Retain

Access may be retained when:

- User remains authorized.
- Business need remains valid.
- Permission level remains appropriate.
- No conflicting requirement exists.

Retention does not prevent future review.

---

# 57. Modify

Access must be modified when the user requires access but the current permission level is inappropriate.

Modification may include:

- Reduced privilege
- Different application role
- Removal from unnecessary groups
- Narrower data access
- Removal of administrative authority

---

# 58. Remove

Access must be removed when:

- Business need ended.
- User is no longer authorized.
- Role changed.
- Contractor engagement ended.
- Privilege is unnecessary.
- Authorization expired.

Removal must be implemented, not merely recommended.

---

# 59. Investigate

Access must be investigated when the reviewer cannot determine whether it is appropriate.

The account must not automatically be approved solely because information is incomplete.

Investigation must be assigned and resolved.

---

# 60. Remediation Assignment

Required access changes must be assigned to personnel authorized to implement them.

The remediation record should identify:

- Account
- System
- Required action
- Responsible administrator
- Due date where appropriate

Higher-risk inappropriate access requires faster action.

---

# 61. Remediation Implementation

Information Technology or the appropriate system administrator must implement approved access changes.

Actions may include:

- Remove group membership
- Reduce permissions
- Disable account
- Remove VPN access
- Remove privileged access
- Change application role

Implementation must match the review decision.

---

# 62. Remediation Verification

A review finding is not remediated merely because an access-removal request was submitted.

Verification must confirm that the required change actually occurred.

Evidence may include:

- Updated account listing
- Group membership
- Application record
- Administrative confirmation
- Technical inspection

---

# 63. High-Risk Access Removal

Unauthorized or clearly unnecessary high-risk access must be addressed promptly.

Examples include:

- Unexpected Domain Admin membership
- Terminated-user access
- Expired contractor privileged access
- Unauthorized remote privileged access
- Sensitive access without authorization

Immediate restriction may occur before ordinary review closeout.

---

# 64. Review Completion

An access review is complete when:

- Required population was reviewed.
- Decisions were recorded.
- Required remediation was assigned.
- High-risk issues were addressed.
- Required evidence was retained.

Open remediation must remain tracked even after the review period closes.

---

# 65. Review Evidence

Access-review evidence must identify:

- Review scope
- Review date
- Population
- Reviewer
- Decisions
- Required changes
- Remediation status
- Verification where applicable

Evidence must be sufficient for later assessment.

---

# 66. Review Sign-Off

The responsible reviewer must confirm completion of the review.

Sign-off means that the reviewer performed the required evaluation.

It does not mean that unresolved remediation is complete.

Open corrective actions must remain visible.

---

# 67. Evidence Integrity

Personnel must not:

- Approve access without performing the review.
- Alter review dates to make a late review appear timely.
- Conceal unauthorized accounts.
- Conceal excessive privilege.
- Record remediation that did not occur.
- Exclude known problematic accounts from the population.
- Falsify dormant-account status.
- Represent Planned controls as implemented.

Known discrepancies must be documented.

---

# 68. Missed Review

If a required access review is missed:

1. The review must be completed as soon as practical.
2. The reason for delay must be identified.
3. Risk from the missed review must be considered.
4. Recurring failure must be escalated.

A missed review must not be backdated.

---

# 69. Incomplete Review

If the review population is discovered to be incomplete, the missing population must be evaluated.

The review must not be represented as complete if significant known access was omitted.

Material omissions may require reopening the review.

---

# 70. Disputed Access

If a reviewer and account owner disagree about whether access is required, the issue must be escalated to the appropriate:

- Manager
- System owner
- Information owner
- IT & Information Security Manager
- CIO

Access must not remain indefinitely unresolved.

---

# 71. Access Review and Incidents

Access identified during review as potentially unauthorized or malicious must be escalated according to:

- [[POL-009 Incident Response Policy]]
- [[PROC-010 Security Event Escalation Procedure]]

The review process must not attempt to resolve a potential security incident solely as an administrative access correction.

---

# 72. Review Records and Privacy

Access-review information must be handled in a manner appropriate to its sensitivity.

Reviews must focus on authorization and security requirements.

The process must not be used for unnecessary employee surveillance.

---

# 73. Access Review Testing

The access-review process must itself be periodically assessed.

Testing must determine whether:

- Reviews occurred on schedule.
- Populations were sufficiently complete.
- Appropriate reviewers participated.
- Decisions were meaningful.
- Required remediation occurred.
- Evidence exists.

---

# 74. Ordinary Review Testing

An assessor may select a sample of ordinary users and determine whether:

- The user was included in the annual review.
- The reviewer was appropriate.
- Access matched current responsibilities.
- Required changes were implemented.

---

# 75. Privileged Review Testing

An assessor may select privileged accounts and determine whether:

- The account was included in quarterly review.
- The user remains authorized.
- Privilege remains appropriate.
- Standing access remains justified.
- Required remediation occurred.

---

# 76. Dormant Account Testing

An assessor may obtain inactive-account information and determine whether:

- Accounts exceeding 30 days received appropriate investigation.
- Accounts reaching 60 days were disabled or had documented justification.
- Disabled accounts were not improperly reactivated.

---

# 77. Contractor Review Testing

An assessor may compare active contractor accounts against:

- Current engagement
- Sponsor
- Authorized systems
- Expiration
- Renewal

Accounts without current support must be investigated.

---

# 78. Domain Admin Testing

An assessor must periodically compare actual Domain Admin membership with approved standing and temporary authorization.

Unexpected membership requires investigation.

This test should not rely solely on the prior reviewer's conclusion.

---

# 79. Remediation Testing

Assessment must determine whether access identified for removal or reduction was actually changed.

The assessor should inspect the resulting access state rather than relying only on a closed request.

---

# 80. Independent Performance

An assessor may perform selected access-review activities independently.

For example, the assessor may:

1. Obtain a current account population.
2. Select a sample.
3. Determine each user's current role.
4. Compare current access with business need.
5. Identify potential excessive access.
6. Compare results with the completed access review.

Independent Performance provides assurance beyond inspection of review documentation.

---

# 81. Sampling

Sampling may be used when reviewing every access record is impractical for assessment.

Sampling should consider:

- Sensitive access
- Privileged access
- Contractors
- Recent transfers
- Recent terminations
- Dormant accounts
- Ordinary users

Sampling must not intentionally exclude known or suspected problems.

---

# 82. Assessment Exceptions

An assessment exception must be investigated before determining whether it represents a control deficiency.

Potential causes include:

- Unauthorized access
- Incomplete review
- Incorrect source data
- Technical error
- Documentation failure
- Approved exception

The cause determines the appropriate response.

---

# 83. Findings

Material access-review deficiencies must be documented.

Examples include:

- Missed annual review
- Missed quarterly privileged review
- Incomplete review population
- Unauthorized access retained
- Excessive access retained
- Dormant account not disabled
- Expired contractor account
- Unnecessary Domain Admin membership
- Required remediation not implemented
- Falsified review evidence

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 84. Corrective Action

Corrective action must identify:

- Deficiency
- Affected process or system
- Responsible owner
- Required remediation
- Due date
- Validation method

Corrective action is not complete until remediation is implemented and appropriately verified.

---

# 85. Metrics

Access-review metrics may include:

- Annual ordinary-access-review completion
- Quarterly privileged-access-review completion
- Accounts reviewed
- Access removals identified
- Access reductions identified
- Remediation completion
- Dormant accounts
- Dormant accounts disabled
- Expired contractor accounts
- Unnecessary privileged accounts
- Missed reviews
- Open access-review findings
- Overdue corrective actions

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 86. Risk Relationships

This procedure provides significant treatment support for:

- R005 Password / Authentication Weakness
- R009 Sensitive Information Theft / Extortion
- R010 Unauthorized / Excessive Access
- R011 Delayed Termination
- R012 Malicious Insider
- R015 Shared Warehouse Account Risk
- R019 Infinity Contractor Dependency / Compromise
- R029 Vendor Fraud
- R030 Sales Fraud
- R031 Payroll Fraud
- R032 Inventory Theft

Risk treatment is maintained in [[RTP-001 Enterprise Risk Treatment Plan]].

---

# 87. Exceptions

Exceptions to this procedure require:

- Business justification
- Identification of the affected requirement
- Risk evaluation
- Compensating controls where practical
- Accountable owner
- Defined duration
- Appropriate approval

High or Critical residual risk must be escalated according to [[POL-005 Risk Management Policy]].

---

# 88. Traceability

This procedure supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Access-review evidence must support traceability from authorization through review, remediation, validation, and risk reassessment.

---

# 89. Related Artifacts

- [[PRO-003 Identity and Access Management Program]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[STD-005 Authentication & Account Security Standard]]
- [[PROC-001 Joiner-Mover-Leaver Procedure]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

---

# 90. Review

This procedure must be reviewed:

- At least annually
- Following material IAM changes
- Following significant access-review failures
- Following material assessment findings
- Following significant organizational or system changes affecting access

The IT & Information Security Manager coordinates review.

Material revisions require CIO approval.

---

# 91. Revision History

| Version | Date     | Description                     | Approval |
| ------- | -------- | ------------------------------- | -------- |
| 1.0     | May 2013 | Initial Access Review Procedure | CIO      |