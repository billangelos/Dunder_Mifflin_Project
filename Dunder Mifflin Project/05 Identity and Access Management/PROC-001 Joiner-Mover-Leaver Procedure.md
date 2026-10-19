# PROC-001 Joiner-Mover-Leaver Procedure

## Document Control

| Field | Value |
|---|---|
| Document ID | PROC-001 |
| Title | Joiner-Mover-Leaver Procedure |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Identity or Personnel Process Change |

---

# 1. Purpose

This procedure defines the operational process for managing employee access throughout the personnel lifecycle.

The procedure covers:

- Joiners
- Movers
- Leavers

Its purpose is to ensure that access is:

- Authorized before assignment
- Appropriate to current job responsibilities
- Modified when responsibilities change
- Removed promptly when authorization ends
- Supported by evidence

---

# 2. Scope

This procedure applies to employee access involving:

- Active Directory
- Email
- Corporate endpoints
- Business applications
- Cloud-hosted systems
- Virtual Private Network (VPN)
- Privileged accounts
- Smart cards where implemented
- Physical access credentials
- Other company authentication mechanisms

Contractor-specific lifecycle requirements are maintained in [[PROC-004 Contractor Access Procedure]].

---

# 3. Authority

This procedure implements requirements established by:

- [[POL-003 Access Control Policy]]
- [[PRO-003 Identity and Access Management Program]]
- [[STD-005 Authentication & Account Security Standard]]

Personnel-security requirements are coordinated with [[POL-011 Physical & Environmental Security Policy]].

---

# 4. Roles

The Joiner-Mover-Leaver process involves:

- Human Resources
- Employee Manager
- System or Information Owner
- Information Technology
- Information Security
- Physical-access administrator where applicable

Responsibilities must remain clear throughout the process.

---

# 5. Human Resources

Human Resources is responsible for providing authoritative employee-status information.

Human Resources must notify appropriate personnel of:

- New hires
- Transfers
- Material role changes
- Leave affecting access where applicable
- Terminations

Notifications must contain sufficient information to initiate the required access action.

---

# 6. Employee Manager

The employee's manager is responsible for identifying business access requirements.

The manager must:

- Request required access.
- Confirm business need.
- Identify role changes.
- Identify access no longer required.
- Participate in access review where applicable.

Managers must not request unnecessary access merely because another employee has it.

---

# 7. System and Information Owners

System or information owners must authorize access when required by:

- System sensitivity
- Information classification
- Business process
- Policy

Owners must evaluate whether requested access is appropriate to the user's duties.

---

# 8. Information Technology

Information Technology is responsible for performing authorized technical access changes.

Responsibilities include:

- Account creation
- Account modification
- Account disablement
- Authentication configuration
- Application access changes
- VPN changes
- Privileged-access changes
- Technical verification

Information Technology must not independently expand access beyond approved authorization.

---

# 9. Information Security

Information Security provides oversight for:

- Higher-risk access
- Privileged access
- Exceptions
- Security incidents
- Access-control assessment
- Recurring lifecycle failures

Information Security may require additional review when access presents material security risk.

---

# 10. Personnel Event Categories

Each personnel event must be classified as:

1. Joiner
2. Mover
3. Leaver

The classification determines the required workflow.

A single event may require multiple coordinated actions.

---

# 11. Joiner Workflow

The Joiner workflow is:

**HR Notification → Manager Access Request → Required Owner Approval → IT Provisioning → Authentication Setup → Verification → Evidence Retention**

Access must not be provisioned without appropriate authorization.

---

# 12. Joiner Notification

Human Resources must provide Information Technology with sufficient notice of a new employee where practical.

The notification should include:

- Employee name
- Position
- Department
- Manager
- Start date
- Work location

Sensitive personnel information not required for provisioning must not be unnecessarily distributed.

---

# 13. Joiner Access Request

The employee's manager must identify required business access.

The request should identify:

- Required systems
- Required applications
- Required information
- Required business functions
- Remote access where needed
- Special or sensitive access

Requests must reflect actual job responsibilities.

---

# 14. Role-Based Access Patterns

Existing access patterns for similar roles may be used as a provisioning reference.

They must not replace authorization.

Copying another user's complete access profile without reviewing its appropriateness is prohibited.

---

# 15. Sensitive Access Approval

Access to Confidential or Restricted information must receive authorization appropriate to the information and system.

Sensitive access must not be granted solely because:

- The user's manager requested general system access.
- Another employee has the access.
- The user may need it later.

---

# 16. Privileged Access for Joiners

Privileged access must not be included automatically with ordinary account provisioning.

Privileged access requires the process defined in [[PROC-002 Privileged Access Procedure]].

Employment within Information Technology does not automatically establish a need for every administrative privilege.

---

# 17. Account Creation

Information Technology creates the account after required authorization is received.

The account must:

- Be associated with the employee.
- Use the approved naming convention.
- Receive only approved access.
- Use appropriate authentication.
- Follow applicable configuration requirements.

---

# 18. Initial Credentials

Initial or temporary credentials must be protected during issuance.

Where supported, the user must change a temporary password at first use.

Temporary credentials must not remain active indefinitely.

---

# 19. Smart-Card Issuance

Where smart-card authentication has been implemented and is required for the user's access, issuance must include:

- Identity verification
- Individual assignment
- PIN or approved secret setup
- User instructions
- Issuance record

Planned smart-card capability must not be represented as implemented before deployment.

---

# 20. Endpoint Assignment

Where a company endpoint is assigned, the device must be:

- Recorded in the applicable inventory.
- Associated with the employee where appropriate.
- Configured according to [[STD-003 Endpoint Security Standard]].
- Prepared before business use.

Assignment records must support equipment recovery when employment ends.

---

# 21. Physical Access

Physical-access credentials must reflect the employee's authorized facility requirements.

Access may include:

- Employee entrances
- Work areas
- Restricted spaces where specifically authorized

Physical access must not automatically include every company-controlled area.

---

# 22. Joiner Security Awareness

New employees must receive required initial security awareness training within five business days in accordance with [[POL-006 Security Awareness & Training Policy]].

Access requiring specific role-based security knowledge may require additional training.

---

# 23. Joiner Verification

After provisioning, Information Technology must verify that:

- Required accounts were created.
- Approved access was assigned.
- Unauthorized elevated access was not assigned.
- Authentication operates as intended.
- Required endpoint or remote access functions operate where applicable.

Verification must identify obvious provisioning errors.

---

# 24. Joiner Evidence

Joiner evidence may include:

- Human Resources notification
- Manager request
- System-owner approval
- Account-creation record
- Access assignment
- Endpoint assignment
- Authentication issuance
- Physical-access assignment

Evidence must support the relationship between business need and access granted.

---

# 25. Joiner Completion

A Joiner event is complete when:

- Required access has been provisioned.
- Required authentication has been established.
- Required equipment has been assigned.
- Required verification has occurred.
- Required evidence has been retained.

Outstanding access requests must remain identifiable rather than being assumed complete.

---

# 26. Mover Workflow

The Mover workflow is:

**HR or Manager Notification → Identify Existing Access → Revoke Previous Business Access → Determine New Business Need → Obtain New Authorization → Provision New Access → Verify → Retain Evidence**

The objective is to prevent access accumulation across roles.

---

# 27. Mover Notification

Human Resources or the responsible manager must notify Information Technology when an employee:

- Transfers departments
- Changes position
- Changes responsibilities materially
- Changes location in a manner affecting access
- No longer requires previously authorized access

The effective date must be identified.

---

# 28. Existing Access Identification

Before or as part of the transfer, relevant existing access must be identified.

This may include:

- Active Directory groups
- Business applications
- File access
- VPN
- Privileged accounts
- Physical access
- Sensitive information access
- Other significant permissions

The review must focus on business access affected by the role change.

---

# 29. Revoke Before Reauthorize

The expected Mover model is:

**Revoke Previous Business Access → Determine New Business Need → Authorize New Access**

Previous-role access must not automatically remain in place.

This prevents gradual accumulation of unnecessary access.

---

# 30. Common Access

Access legitimately required in both the previous and new roles may remain when:

- It remains appropriate.
- It is included in the new authorization.
- Retention does not create an inappropriate separation-of-duties conflict.

Common access must not be retained merely because removing and re-adding it is inconvenient.

---

# 31. New Business Need

The new manager must identify access required for the employee's new responsibilities.

The request must be evaluated independently from the employee's previous access.

Prior access does not establish future entitlement.

---

# 32. New Authorization

New access must receive appropriate authorization before provisioning.

Sensitive or privileged access requires applicable additional approval.

The authorization must reflect the employee's current role.

---

# 33. Privileged Access During Transfer

If a transfer changes the employee's need for privileged access, the privileged access must be reassessed.

Unnecessary privileged access must be removed promptly.

New privileged access must follow [[PROC-002 Privileged Access Procedure]].

---

# 34. Remote Access During Transfer

VPN or other remote access must be reassessed when the new role changes the business need for remote connectivity.

Remote access must be:

- Retained when still required,
- Modified when requirements change, or
- Removed when no longer required.

---

# 35. Physical Access During Transfer

Physical access must be reassessed when a transfer changes:

- Facility
- Work area
- Restricted-space requirement
- Job responsibility

Access to areas no longer required must be removed.

---

# 36. Mover Provisioning

Information Technology must implement approved access changes.

Changes may include:

- Group membership removal
- Application-role removal
- New application access
- File-permission changes
- VPN changes
- Privileged-account changes
- Physical-access coordination

Provisioning must match approved authorization.

---

# 37. Mover Verification

After changes are implemented, verification must determine whether:

- Previous access was removed as required.
- New access was correctly assigned.
- Excessive access remains.
- Privileged access remains appropriate.
- Business functionality is available.

Verification must not focus solely on whether new access works.

---

# 38. Mover Evidence

Mover evidence may include:

- HR or manager notification
- Existing-access review
- Revocation records
- New access request
- New approvals
- Provisioning records
- Verification record

Evidence must demonstrate that access was reassessed rather than simply accumulated.

---

# 39. Mover Completion

A Mover event is complete when:

- Previous access has been addressed.
- New access has been authorized.
- Required changes have been implemented.
- Verification has occurred.
- Required evidence has been retained.

Unresolved access questions must remain tracked.

---

# 40. Leaver Workflow

The Leaver workflow is:

**HR Notification → Determine Termination Timing → Disable Logical Access → Revoke Remote and Privileged Access → Recover Credentials and Equipment → Remove Physical Access → Verify → Retain Evidence**

Access removal must be coordinated with the effective termination time.

---

# 41. Leaver Notification

Human Resources must notify appropriate personnel when employment will end.

The notification must include:

- Employee
- Effective termination date
- Effective termination time where required
- Manager
- Relevant special instructions

Sensitive termination details not required for access removal must not be unnecessarily distributed.

---

# 42. Planned Termination

For a planned departure, required access-removal actions must be prepared in advance where practical.

Access must remain available only as long as authorized.

Advance preparation must not result in premature disabling that prevents authorized work unless specifically directed.

---

# 43. Immediate Termination

When immediate termination is required, access must be disabled promptly.

Information Technology may prioritize containment over ordinary administrative sequencing when necessary to prevent unauthorized access.

Required documentation must follow the action.

---

# 44. Active Directory Disablement

The employee's Active Directory account must be disabled at the authorized termination time.

Disablement must prevent further ordinary domain authentication.

Associated access must also be addressed rather than assuming Active Directory disablement automatically revokes every external or application account.

---

# 45. Email Access

Employee email access must be disabled or otherwise controlled when employment ends.

Business records and required company communications must be preserved according to company requirements.

Mailbox handling must not require continued authentication using the former employee's credentials.

---

# 46. Business Application Access

Significant business application access must be removed or disabled as applicable.

Applications requiring specific action may include:

- CRM
- Order Management System
- Warehouse Management System
- Accounting
- HR/Payroll
- File services
- Infinity administrative functions
- Other significant systems

---

# 47. VPN Access

VPN access must be revoked when employment ends.

VPN revocation must not be assumed merely because an ordinary workstation account was disabled when the remote-access system requires separate action.

---

# 48. Privileged Access

All privileged access associated with the departing employee must be identified and revoked.

This includes, where applicable:

- Privileged Active Directory accounts
- Domain Admin membership
- Server administration
- Network administration
- Application administration
- Database administration
- Cloud administration

Privileged access removal requires explicit verification.

---

# 49. Shared Credential Exposure

If the departing employee knew a shared credential that remains required, the credential must be evaluated for change.

Higher-risk shared credentials must be changed promptly when continued knowledge by the departing employee creates material risk.

Shared credentials must not remain unchanged solely because changing them is inconvenient.

---

# 50. Service Account Knowledge

If the departing employee knew service-account credentials, Information Technology must determine whether those credentials require change.

The decision must consider:

- Privilege
- Systems affected
- Employee role
- Reason for departure
- Technical dependencies
- Risk

Credential changes must be coordinated to avoid preventable service outages.

---

# 51. Smart Cards and Authentication Devices

Company-issued authentication devices must be recovered where practical.

Lost or unrecovered devices must be invalidated where supported.

Recovery of the physical device does not replace logical access disablement.

---

# 52. Company Equipment

Company equipment must be recovered as applicable.

Equipment may include:

- Laptop
- Mobile phone
- Authentication device
- Storage media
- Other company technology

Recovered equipment must be processed according to applicable endpoint and information-handling requirements.

---

# 53. Physical Access Credentials

Physical-access credentials must be recovered or disabled as applicable.

This may include:

- Access cards
- Keys
- Restricted-area credentials

Physical access removal must be coordinated with [[PROC-014 Facility Access Procedure]] and related physical-security procedures.

---

# 54. Restricted Area Access

Access to Restricted physical areas must end when the employee no longer has an authorized requirement.

Recovery of a general employee credential does not independently prove that all keys or specialized access mechanisms were recovered.

---

# 55. Company Information

Departing employees must return company information and company-controlled media in their possession as required.

Termination processing must consider:

- Local files
- Removable media
- Printed material
- Company devices
- Sensitive documents

Information handling must comply with [[POL-004 Information Classification & Handling Policy]].

---

# 56. Access Transfer

A departing employee's access credentials must not be transferred to another employee.

Business responsibilities must be transferred through:

- New authorization
- New or existing individual accounts
- Appropriate access provisioning

Credential sharing is not a continuity strategy.

---

# 57. Business Record Preservation

Required business information must be preserved before account or equipment disposition where necessary.

Examples may include:

- Business correspondence
- Customer records
- Project records
- Administrative documentation
- Required operational files

Preservation must not require keeping the former employee's access active.

---

# 58. Leaver Verification

Termination is not complete until required access removal has been verified.

Verification must determine whether applicable access remains in:

- Active Directory
- VPN
- Business applications
- Privileged accounts
- Cloud systems
- Physical access
- Other significant systems

Verification must reflect the employee's actual access footprint.

---

# 59. Leaver Evidence

Leaver evidence may include:

- Human Resources termination notice
- Active Directory disablement record
- Application-access removal
- VPN revocation
- Privileged-access removal
- Authentication-device recovery
- Equipment recovery
- Physical-access removal
- Verification record

Evidence must support the timing and completeness of access removal.

---

# 60. Leaver Completion

A Leaver event is complete when:

- Required logical access has been removed.
- Required privileged access has been removed.
- Required remote access has been removed.
- Physical credentials have been recovered or invalidated.
- Company equipment has been addressed.
- Required verification has occurred.
- Evidence has been retained.

Unresolved items must remain tracked to closure.

---

# 61. Access Removal Priority

When all termination actions cannot be completed simultaneously, priority must be given to access that creates the greatest security risk.

Priority generally includes:

1. Privileged access
2. Remote access
3. Enterprise authentication
4. Sensitive business applications
5. Other business access
6. Physical credentials and equipment according to the circumstances

This prioritization does not eliminate the requirement to complete all applicable termination actions.

---

# 62. High-Risk Departures

A high-risk departure may require additional coordination when circumstances create elevated concern regarding:

- Privileged access
- Sensitive information
- Fraud
- Malicious activity
- Intellectual property
- Security incidents

Human Resources, management, Information Technology, Information Security, and Legal must coordinate as appropriate.

---

# 63. Preservation During High-Risk Departures

Where investigation may be required, relevant evidence must be preserved before unnecessary alteration where practical.

Evidence may include:

- Authentication logs
- Administrative activity
- Endpoint information
- Email records
- Access records
- Relevant files

Evidence preservation must not delay necessary access termination.

---

# 64. Leave of Absence

A leave of absence must be evaluated to determine whether access should:

- Remain active
- Be restricted
- Be temporarily disabled

The decision must reflect:

- Business need
- Duration
- Information sensitivity
- Role
- Risk

Leave must not automatically be treated as termination.

---

# 65. Return From Leave

Access disabled during leave must not be restored without confirmation that:

- The employee has returned.
- Access remains required.
- The previous authorization remains appropriate.

Material role changes during leave require the Mover process.

---

# 66. Dormancy During Leave

Expected inactivity resulting from approved leave must be considered during dormant-account review.

An account must not be treated as suspicious solely because inactivity corresponds to an authorized leave.

Security concerns identified during leave must still be investigated.

---

# 67. Emergency Personnel Changes

Urgent personnel events may require access changes before the normal workflow is complete.

Emergency action may occur when necessary to:

- Protect company systems
- Protect sensitive information
- Respond to suspected compromise
- Support immediate termination

Documentation and required approvals must be completed as soon as practical after the emergency action.

---

# 68. Failed Provisioning

If required Joiner or Mover access cannot be provisioned:

- The failure must be identified.
- The requester must be informed.
- Business impact must be evaluated.
- Alternative authorized arrangements may be considered.

Security controls must not be bypassed merely to accelerate access.

---

# 69. Failed Revocation

If required access cannot be revoked promptly:

- The condition must be escalated.
- Risk must be evaluated.
- Compensating controls must be applied where practical.
- Resolution must be tracked.

A failed revocation must not be treated as completed termination.

---

# 70. Compensating Actions

Temporary compensating actions for failed access removal may include:

- Account lockout
- Network restriction
- Credential change
- Device recovery
- Additional monitoring
- Application-specific blocking

The compensating action must address the actual access path.

---

# 71. Separation of Duties

Joiner and Mover provisioning must consider separation-of-duties requirements.

Particular attention must be given to access affecting:

- Vendor setup
- Purchasing
- Invoice approval
- Payment
- Payroll
- Privileged administration

Access must not create avoidable conflicts solely for convenience.

---

# 72. Executive Accounts

Executives are subject to the same lifecycle requirements as other users.

Executive status does not justify:

- Unnecessary administrative privileges
- Delayed termination processing
- Unreviewed access
- Shared credentials
- Bypass of authentication requirements

Access must reflect business need.

---

# 73. Information Technology Personnel

Information Technology personnel require both ordinary and, where authorized, privileged identities.

A personnel change affecting an IT employee requires particular attention to:

- Privileged accounts
- Domain Admin membership
- Server access
- Network-device access
- Service-account knowledge
- Backup access
- Emergency credentials

---

# 74. Information Security Personnel

Information-security access must be limited to responsibilities required for:

- Monitoring
- Assessment
- Investigation
- Security administration

Security responsibilities do not automatically justify unrestricted administrative access to every company system.

---

# 75. Shared Account Impact

When a Joiner, Mover, or Leaver event affects knowledge of a shared credential, the credential must be reviewed.

The review must determine whether:

- The individual still requires access.
- The credential must be changed.
- Individual authentication can replace the shared account.
- Additional controls are required.

---

# 76. Warehouse Personnel Changes

Warehouse personnel changes must address both:

- Shared workstation access where applicable, and
- Individual Warehouse Management System accountability.

Termination of a warehouse employee must prevent continued individual WMS transaction authorization even if a shared Windows workstation account remains operational.

---

# 77. Evidence Retention

Joiner-Mover-Leaver records must be retained long enough to support:

- Access review
- Security assessment
- Incident investigation
- Management oversight
- Corrective action

Records must be protected according to their sensitivity.

---

# 78. Evidence Integrity

Personnel must not:

- Create false access approvals.
- Alter personnel dates to conceal delayed action.
- Record access as removed when it remains active.
- Conceal failed termination actions.
- Record verification that was not performed.
- Falsify equipment or credential recovery.
- Represent Planned controls as implemented.

Known discrepancies must be documented.

---

# 79. Procedure Testing

This procedure must be tested periodically.

Testing may use:

- Sampling
- Inspection
- Reconciliation
- Interviews
- Independent Performance

Testing must evaluate actual Joiner, Mover, and Leaver events.

---

# 80. Joiner Testing

Joiner testing should determine whether sampled new employees had:

- Valid personnel status
- Manager authorization
- Required owner approval
- Appropriate access
- No unnecessary privilege
- Supporting evidence

---

# 81. Mover Testing

Mover testing should determine whether sampled role changes resulted in:

- Identification of previous access
- Removal of access no longer required
- Authorization of new access
- Appropriate provisioning
- Verification
- Supporting evidence

The assessment must specifically look for accumulated access.

---

# 82. Leaver Testing

Leaver testing must compare authoritative termination records with applicable access records.

Testing may include:

- Active Directory
- VPN
- Business applications
- Privileged accounts
- Physical access

The assessment must determine whether access was removed promptly.

---

# 83. Independent Performance

An assessor may perform selected portions of the procedure independently using approved records.

For example, the assessor may:

1. Select a terminated employee.
2. Determine the authorized termination time.
3. Identify applicable accounts.
4. Check whether the accounts remain active.
5. Compare disablement timing with the termination record.

Independent Performance provides evidence beyond review of a completed checklist.

---

# 84. Exceptions Identified During Testing

Testing exceptions must be investigated.

An exception may result from:

- Process failure
- Incorrect source data
- Technical failure
- Documentation failure
- Legitimate approved exception

The cause must be determined before concluding whether the control failed.

---

# 85. Findings

Material Joiner-Mover-Leaver deficiencies must be documented.

Examples include:

- Account created without approval
- Excessive initial access
- Previous-role access retained without authorization
- Delayed termination
- Active terminated-user account
- Privileged access not removed
- VPN access not removed
- Physical access not removed
- Missing verification
- Repeated lifecycle process failure

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 86. Corrective Action

Corrective action must identify:

- Deficiency
- Cause where known
- Responsible owner
- Required remediation
- Due date
- Validation method

Corrective action is not complete until remediation has been appropriately verified.

---

# 87. Procedure Metrics

Metrics may include:

- Joiner provisioning accuracy
- Mover access-removal accuracy
- Termination completion timeliness
- Delayed termination count
- Failed access revocations
- Privileged access removal failures
- VPN removal failures
- Open JML findings
- Overdue JML corrective actions

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 88. Risk Relationships

This procedure provides significant treatment support for:

- R005 Password / Authentication Weakness
- R009 Sensitive Information Theft / Extortion
- R010 Unauthorized / Excessive Access
- R011 Delayed Termination
- R012 Malicious Insider
- R014 Lost Device
- R015 Shared Warehouse Account Risk
- R029 Vendor Fraud
- R030 Sales Fraud
- R031 Payroll Fraud
- R032 Inventory Theft

Risk treatment is maintained in [[RTP-001 Enterprise Risk Treatment Plan]].

---

# 89. Exceptions

Exceptions to this procedure require:

- Business justification
- Affected requirement
- Risk evaluation
- Compensating controls where practical
- Accountable owner
- Defined duration
- Appropriate approval

High or Critical residual risk must be escalated according to [[POL-005 Risk Management Policy]].

---

# 90. Traceability

This procedure supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Joiner-Mover-Leaver evidence must support traceability from personnel events through access action and assessment.

---

# 91. Related Artifacts

- [[PRO-003 Identity and Access Management Program]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-006 Security Awareness & Training Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-011 Physical & Environmental Security Policy]]
- [[STD-003 Endpoint Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-003 Access Review Procedure]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-014 Facility Access Procedure]]
- [[PROC-016 Restricted Area Access Procedure]]
- [[PROC-017 Personnel Security Procedure]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

---

# 92. Review

This procedure must be reviewed:

- At least annually
- Following material IAM process changes
- Following significant Joiner-Mover-Leaver failures
- Following material assessment findings
- Following significant personnel-process changes

The IT & Information Security Manager coordinates review.

Material revisions require CIO approval.

---

# 93. Revision History

| Version | Date     | Description                           | Approval |
| ------- | -------- | ------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Joiner-Mover-Leaver Procedure | CIO      |