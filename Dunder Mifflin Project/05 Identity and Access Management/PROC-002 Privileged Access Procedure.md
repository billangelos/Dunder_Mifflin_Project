# PROC-002 Privileged Access Procedure

## Document Control

| Field | Value |
|---|---|
| Document ID | PROC-002 |
| Title | Privileged Access Procedure |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Privileged Access Change |

---

# 1. Purpose

This procedure defines how Dunder Mifflin, Inc. requests, approves, provisions, uses, reviews, modifies, and revokes privileged access.

Privileged access requires additional control because it can allow a user to:

- Modify security settings
- Create or modify accounts
- Change permissions
- Access sensitive information
- Modify system configuration
- Disable security controls
- Affect multiple users
- Affect critical business services

Privileged access must be limited to legitimate administrative requirements.

---

# 2. Scope

This procedure applies to privileged access involving:

- Active Directory
- Domain administration
- Windows servers
- Network devices
- Firewalls and routers
- Corporate endpoints
- Business applications
- Databases
- Cloud-hosted systems
- Infinity
- Security systems
- Backup systems
- Other significant administrative functions

It applies to employees and authorized contractors.

---

# 3. Authority

This procedure implements requirements established by:

- [[POL-003 Access Control Policy]]
- [[PRO-003 Identity and Access Management Program]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]

Server and network administration must also comply with:

- [[STD-002 Network Security Standard]]
- [[STD-004 Server Security Standard]]

---

# 4. Privileged Access Objectives

The privileged-access process must:

1. Restrict elevated access to authorized personnel.
2. Apply least privilege.
3. Separate ordinary and privileged activity.
4. Limit standing administrative authority.
5. Support individual accountability.
6. Protect privileged credentials.
7. Prohibit external remote privileged administration.
8. Review privileged access regularly.
9. Remove privileges promptly when no longer required.
10. Support investigation and assessment.

---

# 5. Definition of Privileged Access

Privileged access is access capable of performing security-significant administrative actions beyond ordinary user authority.

Examples include the ability to:

- Create or disable accounts
- Reset credentials
- Modify permissions
- Change system configuration
- Modify firewall rules
- Install system software
- Modify security controls
- Administer databases
- Access protected system data
- Change logging configuration
- Manage backups
- Administer production applications

---

# 6. Privileged Access Categories

Privileged access may include:

- Domain administration
- Server administration
- Network administration
- Endpoint administration
- Application administration
- Database administration
- Security administration
- Backup administration
- Cloud administration

Access must be limited to the category required for the administrator's responsibilities.

---

# 7. Privileged Access Principles

Privileged access must follow:

- Least privilege
- Need to know
- Individual accountability
- Separate privileged credentials
- Appropriate authorization
- Restricted standing access
- Periodic review
- Controlled emergency access

Administrative convenience is not sufficient justification for excessive privilege.

---

# 8. Privileged Access Workflow

The standard privileged-access workflow is:

**Business or Technical Need → Request → Authorization → Provisioning → Verification → Controlled Use → Quarterly Review → Modification or Revocation**

Emergency access follows [[PROC-005 Emergency Access Procedure]].

---

# 9. Privileged Access Request

A request for privileged access must identify:

- User
- Administrative responsibility
- Systems or applications
- Required privilege
- Business or technical justification
- Expected duration where applicable
- Requesting manager or responsible technical manager

The request must be specific enough to determine what authority is actually required.

---

# 10. Least-Privilege Evaluation

Before approval, the requested privilege must be evaluated to determine whether a lower level of authority can satisfy the requirement.

The user must not receive:

- Domain-wide privilege for a local administrative requirement
- Server administration for ordinary application use
- Database administration for ordinary application access
- Network administration without network responsibilities

Privilege must match the administrative task.

---

# 11. Privileged Access Approval

Privileged access requires approval from personnel authorized to approve the affected system or administrative function.

Higher-risk privileges may require review by:

- IT & Information Security Manager
- CIO
- System owner
- Information Security

depending on scope and risk.

---

# 12. Domain Admin Approval

Standing Domain Admin membership must normally be limited to:

- IT & Information Security Manager
- System Administrator

Additional standing Domain Admin membership requires documented justification and CIO approval.

Temporary elevated access should be used when permanent membership is unnecessary.

---

# 13. Information Technology Employment

Employment within Information Technology does not automatically authorize privileged access.

Each administrator must receive only the privileges required for assigned responsibilities.

Support personnel must not receive broad administrative authority solely because elevated access would make troubleshooting easier.

---

# 14. Separate Privileged Account

Where supported, administrators must receive a separate privileged account for administrative activity.

The administrator's ordinary account must remain separate.

The two accounts serve different purposes:

**Ordinary Account → Normal Business Activity**

**Privileged Account → Authorized Administrative Activity**

---

# 15. Privileged Account Naming

Privileged accounts must be identifiable as administrative accounts where practical.

Naming must support:

- Administration
- Review
- Investigation
- Account ownership

The account must remain attributable to the individual administrator.

---

# 16. Privileged Account Provisioning

Information Technology must provision only the privilege approved in the request.

Provisioning must include, as applicable:

- Account creation
- Administrative group membership
- System-specific permissions
- Authentication configuration
- Administrative workstation access
- Required logging

Provisioning must not silently add broader privileges.

---

# 17. Provisioning Verification

After provisioning, the administrator or responsible Information Technology personnel must verify that:

- The required administrative function works.
- The assigned privilege matches authorization.
- Unnecessary privilege was not granted.
- The account is attributable to the administrator.

Errors must be corrected promptly.

---

# 18. Ordinary Account Use

Administrators must use ordinary accounts for routine business activity.

Ordinary activity includes:

- Email
- General web browsing
- Office productivity
- Ordinary business applications
- Routine communications

Privileged accounts must not be used merely because they are convenient.

---

# 19. Privileged Account Use

Privileged accounts must be used only when elevated authority is required.

Administrators must return to ordinary accounts when administrative activity is complete where practical.

This reduces exposure of privileged credentials to ordinary user activity.

---

# 20. Dedicated Administrative Workstations

Higher-risk administration must use designated company-controlled administrative workstations where required by the security architecture.

Administrative workstations must:

- Be restricted to authorized administrators.
- Use approved secure configuration.
- Receive security updates.
- Use managed antivirus.
- Restrict unnecessary software.
- Restrict ordinary user activity.

---

# 21. Administrative Workstation Use

Dedicated administrative workstations must not routinely be used for:

- Personal activity
- General Internet browsing
- Ordinary email
- Entertainment
- Unrelated office work

Their purpose is to provide a more controlled environment for privileged administration.

---

# 22. Authentication

Privileged access must use authentication appropriate to the risk.

Authentication requirements are established in [[STD-005 Authentication & Account Security Standard]].

Smart-card multi-factor authentication using a card with a PIN or other approved secret must be used where supported and required by risk.

---

# 23. Planned Multi-Factor Authentication

Where smart-card multi-factor authentication is planned but not yet implemented, the control must remain identified as Planned or Implementing.

Approval of the requirement does not establish implementation.

Current control effectiveness must be based on controls actually operating.

---

# 24. Privileged Password Protection

Privileged passwords must:

- Be protected from disclosure.
- Not be shared between administrators.
- Not be stored in insecure notes or files.
- Be changed when compromise is suspected.
- Comply with applicable authentication requirements.

A privileged credential must receive protection appropriate to its potential impact.

---

# 25. Privileged Credential Sharing

Individual privileged credentials must not be shared.

Administrators must not:

- Use another administrator's privileged account.
- Allow another user to use their privileged account.
- Share privileged passwords for convenience.

Emergency shared access must use the controlled emergency-access process.

---

# 26. Privileged Sessions

Administrators must protect active privileged sessions.

When leaving an administrative workstation unattended, the administrator must:

- Lock the session, or
- End the session where appropriate.

Privileged sessions must not remain openly available to unauthorized users.

---

# 27. Privileged Access From Ordinary Endpoints

Higher-risk privileged administration should not be performed from ordinary user endpoints when a designated administrative workstation is required and available.

Use of an ordinary endpoint for privileged administration may occur only when the applicable architecture permits it and operational necessity, system availability, incident response, or emergency conditions require it.

The reason must be documented when material.

Use of an ordinary endpoint does not create an exception to the prohibition on external remote privileged administration.

---

# 28. External Remote Privileged Administration

External remote privileged administration is prohibited.

Privileged administration of significant production resources must occur through approved company-controlled methods and locations.

Ordinary authorized remote access, including Virtual Private Network (VPN) access, does not authorize privileged administration.

Contractor status, operational convenience, incident response, emergency conditions, or ordinary remote-access authorization do not create an exception to this prohibition.

---

# 29. Privileged Administration Location

Privileged administration must occur from an approved location and through an approved administrative pathway.

Where the security architecture requires a designated administrative workstation or controlled workspace, administrators must use that environment.

Privileged access approval authorizes the administrative function. It does not authorize the administrator to perform that function externally through an unapproved remote connection.

---

# 30. External Remote Privileged Access Prevention

Information Technology must configure administrative pathways, remote-access services, and applicable system controls to prevent external remote privileged administration where technically supported.

Review of privileged access must consider whether:

- External administrative interfaces are exposed.
- VPN or other ordinary remote-access mechanisms can be used for privileged administration.
- Contractor access enables prohibited external administration.
- Emergency-access mechanisms unintentionally bypass the prohibition.
- Administrative pathways remain consistent with approved architecture.

Any identified external remote privileged administration must be stopped and investigated.

---

# 31. Network Administration

Administrative access to firewalls, routers, switches, and other significant network devices must be restricted to authorized Information Technology personnel.

Network administrators must use:

- Approved administrative pathways
- Individual credentials where supported
- Secure management protocols where supported

Network administrative interfaces must not be exposed to the Internet.

External remote privileged administration of network infrastructure is prohibited.

---

# 32. Server Administration

Server administration must follow [[STD-004 Server Security Standard]].

Administrators must:

- Use authorized privileged accounts.
- Limit changes to approved requirements.
- Avoid unnecessary ordinary activity on servers.
- Follow change-management requirements.
- Preserve required logs and configuration records.

External remote privileged administration of servers is prohibited.

---

# 33. Active Directory Administration

Active Directory administration requires particular care because changes may affect enterprise authentication and authorization.

Administrative activity affecting:

- Domain Admin membership
- Group Policy
- Authentication configuration
- Trust relationships
- Domain controllers
- Significant security groups

must follow appropriate change and documentation requirements.

External remote privileged administration of Active Directory is prohibited.

---

# 34. Endpoint Administration

Endpoint administrative authority must be limited to personnel with legitimate support or security responsibilities.

Ordinary users, including executives, must not receive local administrative access solely for convenience.

Exceptions require documented justification.

An endpoint privilege exception does not authorize external remote privileged administration of enterprise systems.

---

# 35. Application Administration

Application administrative access must be separated from ordinary application use where supported.

Administrative authority must be limited to required functions such as:

- User administration
- Configuration
- Application maintenance
- Security settings

Application administrators must not receive unrelated infrastructure privileges without separate authorization.

External remote privileged administration of significant production applications is prohibited.

---

# 36. Database Administration

Database administrative access must be restricted to authorized personnel.

Database administrators must receive only the authority required for:

- Administration
- Maintenance
- Recovery
- Authorized troubleshooting

Production database access must receive additional scrutiny when sensitive information is involved.

External remote privileged administration of production databases is prohibited.

---

# 37. Infinity Administration

Infinity administrative access must comply with:

- [[POL-012 Application & Secure Development Policy]]
- [[STD-009 Infinity Security Standard]]

Privileged production activity must be:

- Authorized
- Individually attributable
- Restricted to required functions
- Subject to change control
- Logged where supported

External remote privileged administration of Infinity production resources is prohibited.

---

# 38. Infinity Contractor Administration

Privileged Infinity production or administrative work performed by the external contractor must occur from the designated company-controlled contractor workspace at Scranton Headquarters.

General contractor VPN access for privileged production administration is prohibited.

External remote privileged administration is prohibited.

Contractor access must remain:

- Sponsored
- Time limited
- Individually authorized
- Individually authenticated
- Least privilege

Ordinary contractor remote access does not authorize privileged production administration.

---

# 39. Contractor Personnel Notification

Expected Infinity contractor personnel must be identified at least one business day before scheduled onsite access where practical.

Emergency exceptions may be authorized when advance personnel notification is not possible.

An emergency exception to the advance-notice requirement does not create an exception to the prohibition on external remote privileged administration.

Unexpected personnel must not receive privileged access solely because they identify themselves as contractor employees.

---

# 40. Contractor Privileged Account Duration

Contractor privileged access must have defined duration.

Initial contractor access may be approved for up to three months.

Continued access may be renewed for periods not exceeding six months at a time when business need remains valid.

---

# 41. Contractor Privileged Access Review

Contractor privileged access must be included in quarterly privileged-access review.

The review must confirm:

- Active engagement
- Current sponsor
- Continued business need
- Authorized systems
- Appropriate privilege
- Valid expiration
- Compliance with approved administration-location requirements

Unsupported access must be removed.

---

# 42. Service Account Administration

Administrative access to service accounts must be limited to personnel responsible for the associated service.

Service-account credentials must not be treated as general-purpose administrator credentials.

Changes must consider service dependencies.

---

# 43. Backup Administration

Administrative access to backup systems and backup media must be restricted.

Backup administrators may have access to information from multiple systems and must receive privileges appropriate to their responsibilities.

Backup administration must not automatically provide unrelated production administration.

External remote privileged administration of backup systems is prohibited.

---

# 44. Security Administration

Administrative access to security systems must be restricted to authorized personnel.

Security administration may include:

- Antivirus management
- Security configuration
- Vulnerability tools
- Logging systems
- Security monitoring tools

Security-tool access does not automatically authorize unrestricted administration of every system being monitored.

---

# 45. Cloud Administration

Cloud administrative access must be restricted to authorized personnel.

Cloud administration must consider:

- Provider management interfaces
- Server administration
- Authentication
- Network configuration
- Backup
- Application administration

Provider-level administrative credentials require protection appropriate to their potential impact.

External remote privileged administration of significant cloud-hosted production resources is prohibited.

---

# 46. Change Management

Privileged access authorizes an administrator to perform approved administrative duties.

It does not authorize unrestricted configuration changes.

Material changes must follow [[POL-007 Change & Configuration Management Policy]].

---

# 47. Emergency Administrative Changes

Emergency changes may be performed when required to:

- Contain a security incident
- Restore critical service
- Address a serious security condition
- Prevent material business harm

Emergency actions must be documented and reviewed afterward.

Emergency change authority does not create an exception to the prohibition on external remote privileged administration.

---

# 48. Privileged Access and Separation of Duties

Privileged access must support separation of duties where practical.

An individual should not unnecessarily control:

- Request
- Approval
- Implementation
- Validation

for the same high-risk action.

Dunder Mifflin's staffing level must be considered when applying separation of duties.

---

# 49. Administrative Approval of Own Access

Administrators must not approve their own new privileged access when an appropriate independent approver is available.

The request must be approved by an authorized manager, system owner, CIO, or other appropriate authority.

---

# 50. Temporary Privileged Access

Temporary privileged access should be used when elevated authority is needed only for:

- A specific task
- Troubleshooting
- A project
- A temporary assignment

Temporary access must have a defined end condition.

Temporary privileged access does not authorize external remote privileged administration.

---

# 51. Temporary Access Removal

Temporary privileged access must be removed when:

- The task is complete.
- The project ends.
- The authorized period expires.
- The business requirement ends.

Temporary access must not silently become permanent standing access.

---

# 52. Emergency Access

Emergency privileged access must follow [[PROC-005 Emergency Access Procedure]].

Emergency access must not become a routine method of obtaining elevated privileges.

Emergency access does not authorize external remote privileged administration.

---

# 53. Break-Glass Credentials

Break-glass credentials must be:

- Protected
- Restricted
- Available for legitimate emergencies
- Subject to dual custody where practical
- Reviewed following use

Break-glass credentials must not be used for ordinary administration.

Break-glass credentials do not create an exception to the prohibition on external remote privileged administration.

---

# 54. Break-Glass Use

Following break-glass use, responsible personnel must determine:

- Who used the credential
- Why it was required
- Systems accessed
- Actions performed
- Whether the credential requires change
- Whether corrective action is required

Use must produce appropriate evidence.

Review must also determine whether the emergency access complied with the prohibition on external remote privileged administration.

---

# 55. Privileged Account Modification

Changes to privileged access require authorization appropriate to the change.

Examples include:

- Adding systems
- Increasing privilege
- Changing administrative role
- Extending temporary access
- Changing contractor scope

Material expansion of privilege must not be treated as routine maintenance.

No privileged-access modification may authorize external remote privileged administration.

---

# 56. Role Change

When an administrator changes roles, existing privileged access must be reassessed.

The Mover process in [[PROC-001 Joiner-Mover-Leaver Procedure]] applies.

Previous administrative authority must not automatically transfer to the new role.

---

# 57. Privileged Access Revocation

Privileged access must be revoked when:

- Employment ends.
- Contractor engagement ends.
- Administrative responsibility ends.
- Role changes eliminate the need.
- Authorization expires.
- Security conditions require removal.

Revocation must occur promptly.

---

# 58. Privileged Termination Actions

Termination of an administrator requires explicit review of:

- Privileged Active Directory accounts
- Domain Admin membership
- Server access
- Network-device access
- Cloud administration
- Application administration
- Database administration
- Backup administration
- Security-tool administration
- Emergency credential knowledge

Ordinary account disablement does not independently prove privileged access was removed.

---

# 59. Shared Administrative Credentials

Shared administrative credentials must be avoided.

Where technically unavoidable, they require:

- Documented justification
- Controlled access
- Minimal distribution
- Appropriate protection
- Review
- Credential change when access materially changes

Shared administrative credentials must not replace individual privileged accounts when individual accounts are supported.

---

# 60. Shared Credential Personnel Changes

When an administrator who knows a shared privileged credential no longer requires access, the credential must be evaluated for change.

The decision must consider:

- Privilege
- Systems affected
- Reason for access change
- Risk
- Operational dependencies

Higher-risk shared credentials must be changed promptly where continued knowledge creates material risk.

---

# 61. Privileged Credential Compromise

Known or suspected compromise of a privileged credential requires immediate security evaluation.

Potential actions include:

- Disable account
- Change credential
- Terminate sessions
- Remove administrative group membership
- Restrict network access
- Review administrative activity
- Preserve evidence
- Escalate the incident

---

# 62. Scope of Compromise Review

Privileged credential compromise requires consideration of all systems accessible through the affected credential.

Investigation must not focus solely on the system where compromise was first detected.

Review may include:

- Account activity
- Configuration changes
- New accounts
- Permission changes
- Malware
- Persistence
- Data access
- Logging changes

---

# 63. Privileged Incident Response

Privileged-access incidents must follow:

- [[POL-009 Incident Response Policy]]
- [[PLN-001 Incident Response Plan]]
- [[PBK-003 Unauthorized Access Playbook]]

Malware-related compromise must also consider [[PBK-002 Malware & Ransomware Playbook]].

Incident-response authority does not create an exception to the prohibition on external remote privileged administration.

---

# 64. Privileged Logging

Significant privileged activity must be logged where supported.

Relevant records may include:

- Privileged authentication
- Account changes
- Group membership changes
- Configuration changes
- Administrative application activity
- Security-control changes

Logging capability must be represented accurately.

---

# 65. Privileged Monitoring

Monitoring must focus on meaningful conditions including:

- Unexpected privileged authentication
- Unauthorized privilege changes
- Unexpected Domain Admin membership
- Disabled-account activity
- Contractor activity outside authorized scope
- Privileged activity associated with an incident
- Evidence of external remote privileged administration

Dunder Mifflin does not require continuous manual review of every administrative event.

---

# 66. Quarterly Privileged Access Review

Privileged access must be reviewed at least quarterly.

The review must include significant privileged access across:

- Active Directory
- Servers
- Network devices
- Applications
- Databases
- Cloud systems
- Security systems
- Backup systems
- Contractor accounts

---

# 67. Review Population

The reviewer must obtain a sufficiently complete population of privileged accounts.

The review must not rely solely on a list manually supplied by the account holders when system-generated or administrative records are available.

Known privileged access must not be intentionally excluded.

---

# 68. Review Criteria

For each significant privileged account, the reviewer must determine:

- Is the account assigned to an identifiable authorized user?
- Is privileged access still required?
- Is the privilege level appropriate?
- Is standing access necessary?
- Is the account active?
- Is contractor access still valid?
- Does the access comply with approved administrative pathways and locations?

External remote privileged administration is not an eligible exception.

---

# 69. Domain Admin Review

Every quarterly privileged-access review must specifically verify Domain Admin membership.

Expected standing membership is normally limited to:

- IT & Information Security Manager
- System Administrator

Any additional standing member requires documented justification.

---

# 70. Review Decision

Each reviewed privileged account should result in a decision such as:

- Retain
- Reduce
- Remove
- Investigate

Required changes must be assigned and tracked.

---

# 71. Review Remediation

Identifying unnecessary privileged access does not complete remediation.

The privilege must actually be:

- Removed
- Reduced
- Disabled
- Otherwise corrected

Completion must be verified.

---

# 72. Privileged Review Evidence

Quarterly review evidence must identify:

- Review date
- Systems reviewed
- Privileged accounts reviewed
- Reviewer
- Access decision
- Required remediation
- Remediation completion

Evidence must support assessment of the control.

---

# 73. Access Review Independence

Where practical, privileged access should be reviewed by someone other than the individual whose access is being evaluated.

The reviewer must have sufficient authority and understanding to challenge unnecessary privilege.

---

# 74. Privileged Access Inventory

Information Technology must maintain sufficient records to identify significant privileged accounts.

The inventory may be supported by:

- Active Directory records
- Server account records
- Application records
- Network-device records
- Cloud administrative records
- Security-tool records

The inventory must support quarterly review.

---

# 75. Orphaned Privileged Accounts

A privileged account without an identifiable authorized owner must be investigated promptly.

The account must be:

- Assigned to a legitimate owner,
- Disabled, or
- Removed

as appropriate.

An orphaned privileged account must not remain active because its purpose is unknown.

---

# 76. Dormant Privileged Accounts

Dormant privileged accounts require heightened review.

An inactive privileged account must not remain enabled indefinitely merely because it may be useful later.

Dormant-account requirements in [[STD-005 Authentication & Account Security Standard]] apply.

---

# 77. Privileged Access Evidence

Evidence may include:

- Privileged-access requests
- Approvals
- Account records
- Group membership
- Administrative logs
- Quarterly reviews
- Contractor authorizations
- Temporary-access records
- Revocation records
- Emergency-access records
- Incident records

Evidence must accurately represent actual conditions.

---

# 78. Evidence Integrity

Personnel must not:

- Falsify privileged-access approvals.
- Conceal privileged accounts.
- Conceal excessive privileges.
- Alter access dates to make removal appear timely.
- Record quarterly reviews that were not performed.
- Represent Planned authentication controls as implemented.
- Conceal unauthorized Domain Admin membership.
- Alter administrative records to conceal activity.
- Represent prohibited external remote privileged administration as an approved exception.

Known discrepancies must be documented and addressed.

---

# 79. Privileged Access Testing

Privileged-access controls must be periodically tested.

Assessment methods may include:

- Inspection
- Sampling
- Account review
- Configuration review
- Log review
- Interviews
- Technical Testing
- Independent Performance

Testing must evaluate actual privilege rather than account names alone.

---

# 80. Authorization Testing

An assessor may select privileged accounts and verify whether:

- Authorization exists.
- The approver had authority.
- The privilege matches the approved scope.
- The access remains required.

Missing or unsupported authorization requires investigation.

Authorization documentation cannot make prohibited external remote privileged administration permissible.

---

# 81. Domain Admin Testing

An assessor must compare actual Domain Admin membership against:

- Approved standing administrators
- Temporary authorizations
- Documented authorization records

Unexpected membership must be investigated.

---

# 82. Separate Account Testing

Assessment may determine whether administrators use:

- Ordinary accounts for routine activity, and
- Separate privileged accounts for administration

where supported and required.

Evidence may include account records, interviews, and administrative logs.

---

# 83. Administrative Workstation Testing

Assessment may determine whether higher-risk administration uses designated administrative workstations as required.

Testing may include:

- Workstation inspection
- Configuration review
- Administrator interviews
- Administrative records

Use of an administrative workstation must not be assumed solely because one exists.

---

# 84. Quarterly Review Testing

Assessment must determine whether quarterly privileged-access reviews:

- Occurred on schedule.
- Covered the required population.
- Evaluated actual business need.
- Identified inappropriate access.
- Resulted in required remediation.

Review completion and remediation completion are separate conditions.

---

# 85. Contractor Privileged Access Testing

Assessment may compare contractor privileged accounts against:

- Active engagements
- Sponsors
- Authorized systems
- Approved duration
- Current renewal
- Onsite administration requirements
- Approved administrative pathways and locations

Assessment must confirm that contractor access does not enable external remote privileged administration.

Unsupported contractor access must be investigated.

---

# 86. Revocation Testing

Assessment may sample administrators who:

- Terminated employment
- Changed roles
- Ended contractor assignments
- Lost administrative responsibilities

The assessor must determine whether privileged access was removed promptly.

---

# 87. Independent Performance

An assessor may perform selected portions of the privileged-access process independently.

For example, the assessor may:

1. Obtain actual Domain Admin membership.
2. Identify each account owner.
3. Compare membership with approved authorization.
4. Identify unexpected members.
5. Verify whether required remediation occurred.

Independent Performance provides evidence beyond review of a completed access-review form.

---

# 88. Testing Exceptions

Testing exceptions must be investigated before final conclusions are reached.

An exception may result from:

- Unauthorized access
- Expired authorization
- Incorrect system records
- Documentation failure
- Technical error
- Legitimate approved exception to an eligible requirement

The cause determines the appropriate finding and corrective action.

External remote privileged administration is not an eligible approved exception.

---

# 89. Privileged Access Findings

Material deficiencies must be documented.

Examples include:

- Unauthorized privileged account
- Excessive administrative access
- Unnecessary Domain Admin membership
- Shared privileged credential without justification
- Privileged account used for routine activity
- Missing quarterly review
- Contractor access beyond authorization
- Privileged access not removed after termination
- External remote privileged administration
- Uncontrolled emergency credential
- Missing privileged activity records where required

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 90. Corrective Action

Corrective action must identify:

- Deficiency
- Affected account or system
- Responsible owner
- Required remediation
- Due date
- Validation method

Corrective action is not complete until the remediation is implemented and appropriately verified.

---

# 91. Metrics

Privileged-access metrics may include:

- Total privileged accounts
- Standing Domain Admin accounts
- Unauthorized privileged accounts
- Quarterly review completion
- Unnecessary privilege identified
- Privileges removed following review
- Dormant privileged accounts
- Contractor privileged accounts
- Expired contractor privileged accounts
- Privileged termination failures
- External remote privileged administration events
- Open privileged-access findings
- Overdue corrective actions

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 92. Risk Relationships

This procedure provides significant treatment support for:

- R001 Phishing / Credential Compromise
- R003 Ransomware
- R004 Malware
- R005 Password / Authentication Weakness
- R006 Infinity Application Compromise
- R007 Internet Infrastructure Compromise
- R009 Sensitive Information Theft / Extortion
- R010 Unauthorized / Excessive Access
- R011 Delayed Termination
- R012 Malicious Insider
- R013 Administrative / Configuration Error
- R018 Third-Party Technology Failure / Compromise
- R019 Infinity Contractor Dependency / Compromise
- R027 Backup / Recovery Failure
- R028 Data Corruption

Risk treatment is maintained in [[RTP-001 Enterprise Risk Treatment Plan]].

---

# 93. Exceptions

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

# 94. Traceability

This procedure supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Privileged-access activity must remain traceable from authorization through implementation, evidence, assessment, and remediation.

---

# 95. Related Artifacts

- [[PRO-003 Identity and Access Management Program]]
- [[POL-003 Access Control Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[STD-002 Network Security Standard]]
- [[STD-003 Endpoint Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[STD-009 Infinity Security Standard]]
- [[PROC-001 Joiner-Mover-Leaver Procedure]]
- [[PROC-003 Access Review Procedure]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

---

# 96. Review

This procedure must be reviewed:

- At least annually
- Following material privileged-access changes
- Following significant privileged-access incidents
- Following material assessment findings
- Following significant changes to administrative architecture

The IT & Information Security Manager coordinates review.

Material revisions require CIO approval.

---

# 97. Revision History

| Version | Date     | Description                         | Approval |
| ------- | -------- | ----------------------------------- | -------- |
| 1.0     | May 2013 | Initial Privileged Access Procedure | CIO      |