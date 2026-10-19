# PLN-003 Disaster Recovery Plan

## Document Control

| Field | Value |
|---|---|
| Document ID | PLN-003 |
| Title | Disaster Recovery Plan |
| Version | 1.0 |
| Classification | Confidential |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Technology, Recovery, or Business Impact Change |

---

# 1. Purpose

This Disaster Recovery Plan (DRP) establishes how Dunder Mifflin restores information systems, technology services, and recoverable data following a significant disruption.

The plan translates business recovery requirements established by [[RPT-002 Business Impact Analysis]] into technical recovery priorities and activities.

---

# 2. Disaster Recovery Objective

The objective of Disaster Recovery (DR) is to restore technology capabilities required by the business within approved recovery requirements while maintaining:

- Human safety
- Information confidentiality
- Information integrity
- Information availability
- Appropriate security controls
- Reliable recovery evidence

---

# 3. Authority

This plan operates under:

- [[POL-001 Information Security Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]

---

# 4. Scope

This plan applies to recovery of:

- Active Directory and authentication
- Cloud-hosted servers
- Business applications
- Infinity
- Customer Relationship Management (CRM)
- Order Management System (OMS)
- Warehouse Management System (WMS)
- Accounting systems
- Human Resources and Payroll systems
- Email
- File services
- Website services
- Endpoint-management capabilities
- Network infrastructure
- Backup systems
- Required supporting technology

---

# 5. Business Continuity Relationship

Disaster Recovery supports [[PLN-002 Business Continuity Plan]].

Business Continuity determines which business capabilities require restoration and within what time.

Disaster Recovery determines how supporting technology is restored.

---

# 6. Incident Response Relationship

A cyber incident may require simultaneous activation of:

- [[PLN-001 Incident Response Plan]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]

Incident Response focuses on security-event containment and investigation.

Business Continuity focuses on maintaining business operations.

Disaster Recovery focuses on restoring trusted technology and data.

---

# 7. Safety Priority

Human life and safety take priority over:

- Systems
- Data
- Equipment
- Facilities
- Operations
- Inventory
- Revenue

Personnel must not enter an unsafe location solely to perform technology recovery.

---

# 8. Recovery Priority

After immediate safety requirements are addressed, enterprise recovery priority is:

**Critical → High → Moderate → Low**

Technical dependencies may require supporting systems to be recovered before the business service they support.

---

# 9. Business Impact Analysis

[[RPT-002 Business Impact Analysis]] is the authoritative source for:

- Criticality
- Maximum Tolerable Downtime (MTD)
- Recovery Time Objective (RTO)
- Recovery Point Objective (RPO)
- Business dependencies
- Recovery priority

---

# 10. Recovery Requirements

Key technology-dependent recovery requirements include:

| Business Process / Capability | Criticality | MTD | RTO | RPO |
|---|---:|---:|---:|---:|
| Order Processing | Critical | 3 days | 8 hours | 4 hours |
| Warehouse Operations | Critical | 3 days | 8 hours | 4 hours |
| Inventory Management | High | 3 days | 12 hours | 4 hours |
| Shipping / Delivery | High | 3 days | 12 hours | 8 hours |
| Internet Connectivity | High | 24 hours | 4 hours | N/A |
| Active Directory / Authentication | High | 24 hours | 4 hours | 4 hours |
| CRM | High | 3 days | 12 hours | 8 hours |
| Email | High | 2 days | 8 hours | 4 hours |
| Accounting | High | 5 business days | 24 hours | 8 hours |
| Procurement | High | 5 business days | 2 business days | 1 business day |
| File Services | High | 3 days | 12 hours | 8 hours |
| Infinity | Moderate | 3 days | 24 hours | 4 hours |
| Customer Service | Moderate | 3 days | 24 hours | 8 hours |
| Human Resources | Moderate | 5 business days | 2 business days | 1 business day |
| Payroll | Moderate* | 5 business days | 2 business days | 1 business day |
| Accounts Payable | Moderate | 5 business days | 2 business days | 1 business day |
| Quality Assurance | Moderate | 5 business days | 2 business days | 1 business day |
| Legal / Compliance | Moderate | 5 business days | 2 business days | 1 business day |
| Public Website | Low | 7 days | 3 days | 24 hours |

\*Payroll may increase to High criticality as a biweekly payroll deadline approaches.

---

# 11. RTO

Recovery Time Objective (RTO) is the target period within which a disrupted business capability should be restored.

RTO is a requirement.

It is not proof that the objective can currently be achieved.

---

# 12. RPO

Recovery Point Objective (RPO) represents the maximum acceptable data loss measured in time.

Recovery testing must determine the actual recoverable point rather than assuming that backup schedules satisfy RPO.

---

# 13. Maximum Tolerable Downtime

Maximum Tolerable Downtime (MTD) represents the longest interruption the business can tolerate before consequences become unacceptable.

Recovery must be managed so that RTO remains within MTD.

---

# 14. Recovery Capability

Recovery capability must be demonstrated through evidence such as:

- Successful restoration
- Recovery exercises
- Recovery timing
- Data validation
- Dependency validation
- Security validation

Documentation alone does not establish recovery capability.

---

# 15. Plan Activation

This plan may be activated when technology disruption exceeds or is reasonably expected to exceed normal operational recovery capability.

---

# 16. Activation Conditions

Potential activation conditions include:

- Cloud-service failure
- Server failure
- Authentication failure
- Major application failure
- Data corruption
- Ransomware
- Malware
- Facility loss
- Backup failure
- Network infrastructure failure
- Significant configuration failure
- Regional disaster
- Other material technology disruption

---

# 17. Partial Activation

The entire plan does not need to be activated for every recovery event.

Activation may apply to:

- One system
- One application
- One facility
- One business service
- Multiple systems
- The enterprise technology environment

---

# 18. Activation Authority

The CIO has primary authority for Disaster Recovery activation.

The IT & Information Security Manager may initiate urgent technical recovery actions when delay would materially increase:

- Business interruption
- Security impact
- Data loss

Significant actions must be documented.

---

# 19. Disaster Recovery Leadership

The Disaster Recovery team may include:

- CIO
- IT & Information Security Manager
- System Administrator
- Network / Security Administrator
- Information Security Analyst
- IT Support personnel
- Application owner
- Business owner
- Relevant third-party personnel

Participation depends on the affected service.

---

# 20. CIO Responsibilities

The CIO is responsible for:

- Technology recovery direction
- Priority conflicts
- Significant provider escalation
- Major recovery decisions
- Emergency migration decisions
- Executive technology status
- Significant technology risk decisions within assigned authority

---

# 21. IT & Information Security Manager Responsibilities

The IT & Information Security Manager coordinates:

- Technical recovery
- Recovery assignments
- Security requirements
- Recovery status
- Recovery evidence
- Business coordination
- Recovery validation
- Post-recovery review

---

# 22. System Administrator Responsibilities

The System Administrator supports recovery of:

- Windows Server systems
- Active Directory
- Authentication
- File services
- Application servers
- Backup restoration
- Server configuration

---

# 23. Network / Security Administrator Responsibilities

The Network / Security Administrator supports recovery of:

- Firewall/router infrastructure
- Network connectivity
- VPN
- Network configuration
- Security rules
- Internet connectivity
- Network validation

---

# 24. Information Security Analyst Responsibilities

The Information Security Analyst supports:

- Security-event correlation
- Recovery security validation
- Evidence preservation
- Malware considerations
- Account review
- Security monitoring
- Incident Response coordination

---

# 25. IT Support Responsibilities

IT Support personnel may assist with:

- Endpoint recovery
- User validation
- Device configuration
- Account support
- Application access
- Recovery communications
- Documentation

---

# 26. Business Owner Responsibilities

Business owners are responsible for:

- Confirming business priority
- Identifying minimum required functionality
- Supporting application validation
- Validating recovered business processes
- Identifying unacceptable data loss
- Supporting manual-to-system reconciliation

---

# 27. Recovery Coordinator

For significant recovery events, the IT & Information Security Manager or designated qualified alternate acts as Recovery Coordinator.

---

# 28. Recovery Coordinator Duties

The Recovery Coordinator should maintain:

- Recovery scope
- System priorities
- Assigned personnel
- Dependencies
- Recovery status
- Major decisions
- Recovery timing
- Significant failures
- Validation status

---

# 29. Recovery Lifecycle

The recovery lifecycle is:

**Assess → Authorize → Prioritize → Contain if Necessary → Prepare → Restore → Validate → Reconnect → Business Validate → Monitor → Close → Improve**

---

# 30. Initial Assessment

The initial assessment should determine:

- What failed?
- When did failure begin?
- What business processes are affected?
- What systems are affected?
- Is the environment trusted?
- Is data corrupted?
- Are backups available?
- What dependencies exist?
- What RTO and RPO apply?
- Is a security incident involved?

---

# 31. Security Before Restoration

A system must not be restored directly into an environment known to remain actively compromised unless the recovery strategy specifically requires controlled containment.

Restoring systems without addressing active compromise may immediately recreate the incident.

---

# 32. Security Incident Recovery

When a cyber incident caused the disruption, recovery must coordinate with [[PLN-001 Incident Response Plan]].

Incident Response determines whether evidence or containment requirements affect recovery actions.

---

# 33. Evidence Preservation

Recovery personnel must preserve material evidence before destructive actions where practical.

Evidence handling follows [[PROC-011 Evidence Handling Procedure]].

---

# 34. Emergency Recovery

Immediate recovery action may occur before complete documentation when delay would create unacceptable business or security impact.

The actions and rationale must be documented as soon as practical.

---

# 35. Recovery Sequencing

Recovery sequencing must consider:

1. Human safety.
2. Business criticality.
3. Technical dependencies.
4. Security trust.
5. Data availability.
6. RTO and RPO.
7. Available personnel and resources.

---

# 36. Dependency-Based Recovery

A lower-level technical service may require earlier recovery because a higher-priority business process depends on it.

For example:

**Authentication → Application → Business Process**

Recovering a technical dependency first does not change the business criticality ranking.

---

# 37. Recovery Status

Systems may be tracked as:

- Unavailable
- Recovery Initiated
- Restored
- Technical Validation Pending
- Business Validation Pending
- Validated
- Returned to Service

---

# 38. Recovery Does Not Equal Validation

A system starting successfully does not establish complete recovery.

Validation must address:

- Functionality
- Security
- Data integrity
- Dependencies
- Business usability

---

# 39. Cloud-First Environment

Dunder Mifflin uses a cloud-first architecture.

Major company systems are not dependent on a large company-operated data center at Headquarters.

---

# 40. Cloud Dependency

Cloud hosting reduces some local facility dependencies but creates dependency on:

- Cloud-provider availability
- Cloud-provider administration
- Internet connectivity
- Provider infrastructure
- Provider recovery capability

---

# 41. Cloud Failure Assessment

A cloud failure requires determination of:

- Services affected
- Provider scope
- Expected restoration
- Authentication impact
- Data availability
- Backup availability
- Business-process impact
- Security implications

---

# 42. Provider Escalation

The CIO or designated technical representative should use established provider escalation channels for significant cloud outages.

Provider statements should be recorded as provider-supplied information.

---

# 43. Provider Recovery Is Not Company Validation

A provider reporting that service is restored does not establish that Dunder Mifflin business capability is restored.

Company personnel must validate affected systems and processes.

---

# 44. Cloud Exit

When cloud-provider recovery is unacceptable, [[PLN-004 Cloud Exit & Emergency Migration Plan]] may be activated.

---

# 45. No Running Alternate Cloud

Dunder Mifflin does not maintain a continuously operating alternate cloud environment.

Emergency migration requires deployment and restoration activity.

---

# 46. Emergency Migration Considerations

Emergency migration should consider:

- Expected provider outage
- Security trust
- Available backups
- Infrastructure requirements
- Application dependencies
- Data volume
- DNS or addressing changes
- Authentication
- Recovery time
- Migration risk

---

# 47. Active Directory Recovery Priority

Active Directory / Authentication is High criticality with:

- MTD: 24 hours
- RTO: 4 hours
- RPO: 4 hours

Authentication may be required before multiple business applications can function.

---

# 48. Active Directory Architecture

Dunder Mifflin maintains at least two cloud-hosted Domain Controller/authentication servers.

They operate within the same overall cloud provider with reasonable failure-domain separation.

---

# 49. Domain Controller Failure

Loss of one Domain Controller should be evaluated to determine whether remaining authentication capability can support required operations.

Recovery should avoid unnecessary disruption of a functioning authentication environment.

---

# 50. Multiple Domain Controller Failure

Loss of both authentication servers requires immediate High-priority recovery.

The recovery team should determine:

- Failure cause
- Security status
- Backup availability
- Directory consistency
- Required restoration sequence
- Dependent services

---

# 51. Active Directory Security

Active Directory recovery must preserve:

- Domain integrity
- Administrative accountability
- Appropriate privileged access
- Secure configuration
- Authentication controls

---

# 52. Domain Administrator Access

Standing Domain Administrator access is restricted to:

- IT & Information Security Manager
- System Administrator

unless additional access is specifically authorized.

---

# 53. Emergency Privileged Access

Emergency privileged access during recovery must follow [[PROC-005 Emergency Access Procedure]].

Emergency access does not authorize external remote privileged administration.

---

# 54. Separate Privileged Credentials

Administrators must use separate privileged credentials for administrative recovery activities where required by [[POL-003 Access Control Policy]].

---

# 55. Administrative Workstations

Privileged administration should use designated administrative workstations where applicable.

---

# 56. Remote Privileged Administration

External remote privileged administration is prohibited.

Ordinary remote access or VPN connectivity does not authorize privileged administration from an external location.

This prohibition applies during routine operations, emergencies, Disaster Recovery activities, and other exceptional circumstances. No exception process may authorize external remote privileged administration.

---

# 57. Server Recovery

Server recovery should determine:

- Business function
- Criticality
- Dependencies
- Configuration requirements
- Backup availability
- Recovery point
- Security state

---

# 58. Server Recovery Sources

Recovery may use:

- Existing functioning infrastructure
- Validated backup
- Configuration backup
- Rebuilt operating system
- Application installation media
- Documented configuration
- Provider recovery capability

---

# 59. Known-Good Recovery

When compromise or integrity loss is suspected, recovery should use a source reasonably believed to be trustworthy.

A known-compromised system should not simply be copied into production.

---

# 60. Server Baselines

Recovered servers must comply with [[STD-004 Server Security Standard]] and [[STD-006 Secure Configuration Standard]] as applicable.

---

# 61. Patch Status

Recovered systems should receive required security updates before or promptly after return to service based on:

- Exposure
- Business urgency
- Vulnerability risk
- Recovery constraints

Known exploitable weaknesses that caused the incident must be addressed before normal exposure is restored where practical.

---

# 62. Endpoint Recovery

Endpoint recovery may include:

- Malware removal
- Reimaging
- Operating-system restoration
- Application restoration
- Configuration restoration
- Data restoration
- Security-control validation

---

# 63. Reimage Decision

Reimaging is preferred when reasonable confidence in endpoint integrity cannot otherwise be restored.

---

# 64. Endpoint Security

Recovered endpoints must meet applicable requirements in [[STD-003 Endpoint Security Standard]].

---

# 65. Laptop Recovery

Recovered company laptops should validate:

- Full-disk encryption
- Authentication
- Standard-user configuration
- Screen lock
- Managed antivirus
- Patch status
- Central management

---

# 66. Warehouse Workstation Recovery

Warehouse workstation recovery must account for the existing shared Windows workstation model.

Significant Warehouse Management System transactions must retain individual accountability where required.

---

# 67. Network Recovery

Network recovery may include:

- Firewall/router restoration
- Switch restoration
- Internet connectivity
- VPN
- Network configuration
- Security rules

---

# 68. Network Security Baseline

Recovered network infrastructure must maintain:

- Unsolicited inbound traffic restrictions
- No unnecessary Internet-exposed administration
- Approved configuration
- Required security rules
- Appropriate administrative access

---

# 69. Network Configuration Backups

Current network-device configuration backups should be available to support recovery.

Restored configuration must be reviewed when compromise or configuration error caused the outage.

---

# 70. Headquarters Spare

A spare firewall/router maintained for Headquarters may support recovery from equipment failure.

Its availability does not address broader ISP, facility, or regional outages.

---

# 71. Internet Connectivity Recovery

Internet Connectivity is High criticality with:

- MTD: 24 hours
- RTO: 4 hours
- RPO: N/A

---

# 72. ISP Failure

For a facility-specific wired ISP failure, recovery may include:

- Provider escalation
- Equipment validation
- Local configuration review
- Company-issued cellular connectivity where applicable

---

# 73. Cellular Continuity

Cellular connectivity may support selected personnel and functions when primary wired Internet is unavailable.

It must not be assumed to provide full replacement capacity for every facility or warehouse operation.

---

# 74. Wireless Baseline

Dunder Mifflin does not operate corporate wireless networking.

The only approved wireless Access Point (AP) is the ceiling-mounted Internet-only guest AP in the Scranton Headquarters lobby.

Recovery personnel must not create unauthorized corporate wireless connectivity as an undocumented workaround.

---

# 75. Order Processing Recovery

Order Processing is Critical with:

- MTD: 3 days
- RTO: 8 hours
- RPO: 4 hours

Technology recovery must prioritize the systems and dependencies required to:

- Receive orders
- Record orders
- Verify orders
- Route orders for fulfillment

---

# 76. Order Management System

Order Management System recovery should validate:

- Application availability
- Authentication
- Order data
- Required integrations
- Transaction integrity
- Business access

---

# 77. Warehouse Management System

Warehouse Operations are Critical with:

- MTD: 3 days
- RTO: 8 hours
- RPO: 4 hours

Warehouse Management System recovery must support accurate order and inventory processing.

---

# 78. Inventory Management Recovery

Inventory Management is High with:

- MTD: 3 days
- RTO: 12 hours
- RPO: 4 hours

Recovery must account for manual inventory movement occurring during the outage.

---

# 79. Shipping and Delivery Recovery

Shipping / Delivery is High with:

- MTD: 3 days
- RTO: 12 hours
- RPO: 8 hours

Restored systems must support reconciliation of shipments processed during manual continuity.

---

# 80. CRM Recovery

CRM is High with:

- MTD: 3 days
- RTO: 12 hours
- RPO: 8 hours

Recovery should validate:

- Customer records
- Authentication
- Required access
- Recent business activity
- Manual continuity records

---

# 81. Email Recovery

Email is High with:

- MTD: 2 days
- RTO: 8 hours
- RPO: 4 hours

Recovery should validate:

- User access
- Message flow
- Authentication
- Security controls
- Required retained information

---

# 82. File Services Recovery

File Services are High with:

- MTD: 3 days
- RTO: 12 hours
- RPO: 8 hours

Recovery should validate:

- Required shares
- Permissions
- Information integrity
- Authentication
- Business access

---

# 83. File Permissions

Restoring file data without restoring appropriate access control does not constitute successful recovery.

Permissions must be validated before normal access is restored.

---

# 84. Accounting Recovery

Accounting is High with:

- MTD: 5 business days
- RTO: 24 hours
- RPO: 8 hours

Recovery should preserve:

- Financial records
- Access restrictions
- Approval controls
- Reconciliation capability

---

# 85. Procurement Recovery

Procurement is High with:

- MTD: 5 business days
- RTO: 2 business days
- RPO: 1 business day

Technology recovery must support essential supplier and purchasing activity.

---

# 86. Payroll Recovery

Payroll is normally Moderate with:

- MTD: 5 business days
- RTO: 2 business days
- RPO: 1 business day

Payroll may increase to High criticality near the biweekly payroll deadline.

---

# 87. Payroll Recovery Timing

The Recovery Coordinator must consider the current payroll cycle when prioritizing payroll systems.

Static criticality alone must not override immediate business timing.

---

# 88. Human Resources Recovery

Human Resources is Moderate with:

- MTD: 5 business days
- RTO: 2 business days
- RPO: 1 business day

Personnel safety and accountability activities may receive higher priority during a major emergency.

---

# 89. Infinity Recovery

Infinity is Moderate with:

- MTD: 3 days
- RTO: 24 hours
- RPO: 4 hours

Infinity recovery must consider:

- Web tier
- Application tier
- Database tier
- Authentication
- Customer data
- Order data
- Payment tokens
- Application configuration
- Source code

---

# 90. Infinity Architecture

Infinity uses logical separation among:

**Web Tier → Application Tier → Database Tier**

The database is not intended to be directly accessible from the Internet.

---

# 91. Infinity Recovery Order

The precise technical sequence depends on the failure, but recovery should generally establish:

1. Required infrastructure.
2. Required database capability.
3. Application tier.
4. Web tier.
5. Required integrations.
6. Security validation.
7. Business validation.

---

# 92. Infinity Source Code

Dunder Mifflin owns:

- Infinity source code
- Repository
- Documentation
- Application data
- Intellectual property
- Contractor work product
- Application backups

Recovery must not depend exclusively on the contractor possessing these assets.

---

# 93. Infinity Contractor

The third-party Infinity contractor may assist with application recovery under approved access controls.

---

# 94. Infinity Contractor Privileged Access

Privileged production or administrative contractor work must be performed from the designated controlled Headquarters contractor workspace.

The contractor does not receive general VPN access for privileged production administration.

External remote privileged administration is prohibited. An exception or emergency process does not authorize the contractor to perform privileged production or administrative work from an external location.

---

# 95. Infinity Recovery Validation

Infinity recovery should validate:

- Application functionality
- Authentication
- Authorization
- Database connectivity
- Data integrity
- Customer order processing
- Security configuration
- Logging
- Required integrations

---

# 96. Infinity Compromise

When Infinity recovery follows a security compromise, restoration must coordinate with:

- [[PLN-001 Incident Response Plan]]
- [[PROC-009 Malware Response Procedure]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-004 Data Exposure Playbook]]

as applicable.

---

# 97. Public Website Recovery

The Public Website is Low criticality with:

- MTD: 7 days
- RTO: 3 days
- RPO: 24 hours

It should not displace recovery resources needed for higher-priority services.

---

# 98. Backup Strategy

Dunder Mifflin uses multiple backup mechanisms, including:

- Automated backups
- Cloud-based backups
- Encrypted external hard drives
- Off-site external-drive storage

---

# 99. External Backup Inventory

Each of the seven facilities has three encrypted external backup hard drives.

Total:

**21 encrypted external backup drives**

---

# 100. Weekly Rotation

Each Friday, the current external backup drive is sent to the off-site Disaster Recovery storage provider.

The provider normally retains the two most recent weekly generations for each facility.

---

# 101. Off-Site Generations

The normal off-site external-drive inventory is:

**7 facilities × 2 generations = 14 off-site backup drives**

When a new drive arrives, the oldest generation is returned for reuse.

---

# 102. Backup Encryption

External backup drives are encrypted.

Encryption protects confidentiality but does not establish recoverability.

---

# 103. Backup Separation

Off-site storage provides separation from the source facility.

The backup environment must not be described as immutable unless immutability is actually implemented and validated.

---

# 104. Backup Coverage

Backup coverage must be evaluated against:

- [[REG-001 Enterprise Asset Register]]
- [[RPT-002 Business Impact Analysis]]
- [[STD-001 Information Classification Standard]]
- System dependencies
- Recovery requirements

---

# 105. Backup Selection

The recovery team should select a backup based on:

- Required recovery point
- Integrity
- Availability
- Security trust
- Business requirement

The newest available backup is not automatically the correct recovery source if it contains corruption or compromise.

---

# 106. Backup Integrity

Before restoration, the team should determine whether there is reason to believe the selected backup contains:

- Malware
- Unauthorized changes
- Corrupted data
- Compromised configuration

---

# 107. Ransomware and Backups

During ransomware response:

- Backup media must be protected from affected systems.
- External backup drives must not be unnecessarily connected to compromised systems.
- Backup administrative access must be reviewed.
- Recovery sources must be evaluated for compromise.

---

# 108. Backup Restoration

Detailed backup and restoration activities are governed by [[PROC-012 Backup & Recovery Procedure]].

---

# 109. Restore Testing

Representative restore testing must occur quarterly.

Testing should demonstrate actual recovery of selected data or systems.

---

# 110. Critical Recovery Test

Critical systems require at least one meaningful recovery test annually.

A test must demonstrate recovery capability rather than merely confirm backup-file existence.

---

# 111. Recovery Test Start

Recovery testing must define the point from which elapsed recovery time is measured.

The test record should make the measurement method clear.

---

# 112. RTO Measurement

Actual recovery time must be compared with the approved RTO.

A system restored after the RTO has failed the RTO requirement even if eventual recovery is successful.

---

# 113. RPO Measurement

The actual recoverable point must be compared with the approved RPO.

The team must determine the amount of data loss represented by the restored state.

---

# 114. Example RTO and RPO Test

For a system requiring:

- RTO: 8 hours
- RPO: 4 hours

a test resulting in:

- Recovery time: 11 hours 37 minutes
- Data loss: 58 minutes

produces:

- RTO: Failed
- RPO: Passed

Overall recovery capability has not fully met the business requirement.

---

# 115. Successful Retest Example

A later validated test producing:

- Recovery time: 6 hours 42 minutes
- Data loss: 47 minutes

produces:

- RTO: Passed
- RPO: Passed

This evidence may support improved control-effectiveness and risk conclusions.

---

# 116. Failed Recovery

When recovery fails, personnel must document:

- Failure
- Time
- Recovery step
- Error or observed condition
- Business impact
- Corrective action
- Next recovery approach

---

# 117. Failed Recovery Must Remain Visible

A failed recovery attempt must not be removed from the record merely because a later attempt succeeds.

The failure is assurance evidence.

---

# 118. Alternate Recovery Source

If the selected backup cannot be restored, the recovery team may select another appropriate recovery source.

The resulting recovery point must be recalculated.

---

# 119. Recovery Documentation

Recovery documentation must be sufficient for a qualified IT professional unfamiliar with the specific environment to perform the required recovery.

---

# 120. Documentation Content

Recovery documentation should include as applicable:

- System purpose
- Dependencies
- Recovery priority
- Required infrastructure
- Installation information
- Configuration
- Backup location
- Restoration procedure
- Validation procedure
- Escalation information

---

# 121. Documentation Independence

Critical recovery documentation must not exist solely:

- On the affected system
- In one cloud environment
- At Headquarters
- With one employee
- With one contractor

---

# 122. Printed Recovery Documentation

Two printed recovery-documentation sets are maintained.

Printed copies support recovery when normal electronic documentation is unavailable.

---

# 123. Electronic Documentation

Protected electronic recovery documentation should also be maintained.

Electronic and printed documentation should remain reasonably synchronized.

---

# 124. Documentation Following Change

A significant technology or configuration change is not complete until applicable recovery documentation is reviewed and updated where necessary.

---

# 125. Configuration Backups

Required infrastructure and system configurations should be backed up or otherwise documented sufficiently to support recovery.

---

# 126. Recovery Credentials

Required recovery credentials must be available to authorized personnel without creating unnecessary standing privilege.

---

# 127. Emergency Credentials

Emergency or break-glass credentials must be managed under [[PROC-005 Emergency Access Procedure]].

Emergency or break-glass access does not authorize external remote privileged administration.

---

# 128. Credential Availability

Recovery must not depend solely on credentials known to one unavailable individual.

---

# 129. Compromised Credentials

Credentials known or reasonably suspected to be compromised must not be trusted for restored production access without appropriate replacement or other corrective action.

---

# 130. Service Accounts

Service-account recovery must consider:

- Account identity
- Required privilege
- Application dependency
- Credential protection
- Configuration
- Authentication

---

# 131. Security Controls During Recovery

Recovery does not automatically suspend security controls.

Recovered systems should maintain required:

- Authentication
- Authorization
- Least privilege
- Encryption
- Antivirus
- Logging
- Network restrictions
- Secure configuration

---

# 132. Temporary Security Exceptions

A temporary security exception may be necessary when strict adherence would prevent required emergency recovery.

The exception must be:

- Necessary
- Authorized
- Limited
- Documented
- Time-bound
- Removed when no longer needed

A temporary security exception cannot authorize external remote privileged administration. That prohibition remains in effect during emergency recovery.

---

# 133. Change Management

Recovery changes must follow [[POL-007 Change & Configuration Management Policy]] to the extent practical under the circumstances.

---

# 134. Emergency Changes

Emergency changes may occur when delay would create unacceptable impact.

Emergency changes require:

- Authorization
- Documentation
- Verification
- Post-change review

---

# 135. Rollback

Recovery changes should include a rollback approach where practical.

Rollback may not be possible for every emergency restoration.

The limitation should be documented.

---

# 136. Malware Recovery

Malware-related recovery must follow [[PROC-009 Malware Response Procedure]] and applicable playbooks.

---

# 137. Ransomware Recovery

Ransomware recovery must coordinate:

- Containment
- Credential protection
- Backup protection
- System rebuilding
- Data restoration
- Security validation
- Business validation

---

# 138. Ransomware Restoration

Systems must not be restored into an actively compromised environment merely to accelerate business recovery.

---

# 139. Data Corruption Recovery

When data corruption is suspected, the recovery team must determine:

- Systems affected
- Data affected
- Corruption start point where possible
- Valid recovery source
- Required reconciliation
- Business validation

---

# 140. Data Integrity

Technical restoration does not establish data integrity.

Affected business owners must validate important recovered business data.

---

# 141. Manual Continuity Records

Transactions created during system outage must be incorporated according to [[PROC-013 Manual Processing Procedure]].

---

# 142. Manual Processing Lifecycle

The manual processing lifecycle is:

**Collect → Review → Enter → Reconcile → Verify**

---

# 143. Manual Records After Recovery

Manual records must not be discarded simply because technology is restored.

They remain necessary for reconciliation and verification.

---

# 144. Duplicate Prevention

Personnel must take reasonable steps to prevent transactions completed manually from being processed again unintentionally after systems return.

---

# 145. Reconciliation

Recovered systems must be reconciled with manual activity where required.

Reconciliation should identify:

- Missing transactions
- Duplicate transactions
- Incorrect transactions
- Incomplete transactions
- Unresolved discrepancies

---

# 146. Recovery Validation

Recovery validation has three primary components:

1. Technical validation.
2. Security validation.
3. Business validation.

---

# 147. Technical Validation

Technical validation should confirm as applicable:

- System starts correctly.
- Required services operate.
- Dependencies function.
- Connectivity functions.
- Required integrations operate.
- Backup restoration completed.
- Expected data is present.

---

# 148. Security Validation

Security validation should confirm as applicable:

- Authentication works.
- Authorization is appropriate.
- Administrative access is controlled.
- Required encryption is enabled.
- Antivirus is operating.
- Logging is operating.
- Required network restrictions remain in place.
- Known compromise has been addressed.

---

# 149. Business Validation

The responsible business owner or qualified representative must determine whether the restored system supports required business operations.

---

# 150. Validation Failure

A failed validation means recovery is incomplete.

The system should remain in an appropriate restricted state until the deficiency is:

- Corrected
- Mitigated
- Formally accepted under appropriate authority

---

# 151. Controlled Reconnection

Recovered systems should be reconnected to normal production connectivity in a controlled manner.

The team should consider:

- Security trust
- Dependencies
- Business priority
- Monitoring
- Potential reinfection or recurrence

---

# 152. Post-Recovery Monitoring

Significant recovered systems may receive heightened monitoring after restoration.

Monitoring should focus on relevant failure or compromise indicators.

---

# 153. Business Return to Service

A system may be returned to normal business service when:

- Technical recovery is complete.
- Required security validation is complete.
- Required business validation is complete.
- Remaining risk is understood.
- Required approval has been obtained.

---

# 154. Recovery Communications

Recovery status communications should identify:

- System
- Business process
- Current status
- Recovery owner
- RTO status
- RPO status where applicable
- Major blockers
- Expected next action

---

# 155. Recovery Status Accuracy

A system must not be reported as recovered merely because:

- The server powers on.
- The operating system starts.
- The provider reports service restoration.
- A backup job existed.
- A recovery ticket is closed.

Recovery requires applicable validation.

---

# 156. Recovery Event Record

A significant recovery event should record:

- Event
- Activation
- Systems affected
- Business processes affected
- RTO
- RPO
- Recovery actions
- Personnel
- Recovery sources
- Failures
- Actual recovery time
- Actual recovery point
- Validation
- Return to service
- Corrective actions

---

# 157. Recovery Timing

Recovery timing must be based on actual elapsed time.

Personnel must not modify timing records to make recovery appear compliant with RTO.

---

# 158. Recovery Point Evidence

The recovery record should identify how the actual recovery point was determined.

---

# 159. Evidence Integrity

Recovery personnel must not:

- Backdate recovery tests.
- Invent successful restore results.
- Hide failed recovery attempts.
- Change measured recovery time.
- Change measured data loss.
- Record unperformed validation as complete.

---

# 160. Recovery Closure

A recovery event may be closed when:

- Required systems are restored or an approved alternate process remains in place.
- Technical validation is complete.
- Security validation is complete.
- Business validation is complete.
- Required reconciliation is complete.
- Material recovery failures are documented.
- Corrective actions are assigned.
- Remaining risk is understood.

---

# 161. Closure Does Not Eliminate Findings

Recovery-event closure does not automatically close:

- Backup findings
- Recovery findings
- Security findings
- Documentation deficiencies
- Corrective actions
- Risk treatments

---

# 162. Post-Recovery Review

Significant recovery events require a documented post-recovery review.

---

# 163. Post-Recovery Review Topics

The review should consider:

- Activation
- Recovery priority
- Dependencies
- Backup performance
- RTO
- RPO
- Personnel
- Documentation
- Provider performance
- Security controls
- Validation
- Business impact

---

# 164. Root Cause

Where practical, the recovery team should identify the underlying cause of the technology disruption.

Examples include:

- Hardware failure
- Software failure
- Configuration error
- Cloud outage
- Internet outage
- Malware
- Ransomware
- Unauthorized access
- Data corruption
- Facility loss
- Human error

---

# 165. Recovery Contributing Factors

Contributing factors may include:

- Incomplete backup coverage
- Poor documentation
- Single-person dependency
- Configuration drift
- Unsupported technology
- Provider concentration
- Inadequate testing
- Missing recovery credentials
- Unidentified dependencies

---

# 166. Corrective Action

Material recovery deficiencies must identify:

- Deficiency
- Accountable owner
- Required action
- Due date
- Validation method

Material corrective actions are tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 167. Corrective-Action Validation

Corrective action is not complete merely because an implementation task is marked finished.

Required validation must determine whether the intended recovery capability was achieved.

---

# 168. Retesting

Recovery deficiencies affecting material RTO, RPO, security, or business functionality require appropriate retesting.

---

# 169. Recovery Exercises

Disaster Recovery capability must be exercised periodically.

Testing should demonstrate actual capability rather than document existence.

---

# 170. Quarterly Representative Restore Testing

Representative backup restores should be performed quarterly.

Tests should rotate through meaningful data and systems over time.

---

# 171. Annual Critical Recovery Testing

Critical systems require at least one meaningful recovery test annually.

---

# 172. Test Scope

Recovery tests should define:

- Objective
- System
- Business process
- Recovery source
- RTO
- RPO
- Start condition
- Success criteria
- Participants
- Validation method

---

# 173. Test Limitations

Any limitation preventing a test from representing real recovery capability must be documented.

Examples include:

- Partial data set
- Simplified infrastructure
- Unavailable provider participation
- Simulated dependency
- Reduced user validation

---

# 174. Test Success

A test is successful only when defined success criteria are satisfied.

Partial success must not be recorded as full success.

---

# 175. Failed Test

A failed test is useful assurance evidence.

The failure should lead to:

1. Documentation.
2. Analysis.
3. Corrective action.
4. Retesting.
5. Risk reassessment when material.

---

# 176. Recovery Documentation Test

Recovery documentation should periodically be evaluated by a qualified IT professional unfamiliar with the specific environment where practical.

---

# 177. Documentation Test Objective

The objective is to determine whether recovery depends on:

- Undocumented knowledge
- One individual's memory
- One contractor
- Missing credentials
- Missing configuration
- Unavailable documentation

---

# 178. Cloud Recovery Exercise

A cloud-recovery scenario should evaluate:

- Provider escalation
- Authentication dependency
- Backup availability
- Application recovery
- Manual continuity
- Emergency migration decision criteria

---

# 179. Active Directory Exercise

An Active Directory recovery exercise should evaluate:

- Recovery documentation
- Backup availability
- Privileged access
- Directory integrity
- Authentication validation
- Dependent service validation

---

# 180. Infinity Recovery Exercise

An Infinity recovery exercise should evaluate:

- Infrastructure
- Database
- Application tier
- Web tier
- Source availability
- Configuration
- Security controls
- Order-processing validation
- Contractor dependency

---

# 181. Ransomware Recovery Exercise

A ransomware recovery exercise should evaluate:

- Isolation
- Backup protection
- Credential response
- Recovery-source selection
- Rebuilding
- Restoration
- Security validation
- Business validation

---

# 182. Exercise Safety

Recovery exercises must not unnecessarily:

- Interrupt production
- Damage data
- Expose sensitive information
- Disable required security controls
- Create uncontrolled privileged access

---

# 183. Exercise Evidence

Exercise evidence should include:

- Scenario
- Date
- Participants
- Systems
- Objectives
- RTO
- RPO
- Actual results
- Failures
- Validation
- Findings
- Corrective actions

---

# 184. Assessment Methods

Disaster Recovery assurance may use:

- Inspection
- Observation
- Interviews
- Sampling
- Exercises
- Technical Testing
- Reconciliation
- Independent Performance

---

# 185. Independent Performance

An assessor may independently perform selected authorized recovery activities.

For example, the assessor may:

1. Select a recovery scenario.
2. Identify the applicable BIA requirement.
3. Identify required dependencies.
4. Select the documented recovery procedure.
5. Retrieve the appropriate recovery source.
6. Perform or observe controlled restoration.
7. Measure recovery time.
8. Determine the recovery point.
9. Validate required controls.
10. Compare actual performance with RTO and RPO.

---

# 186. Recovery Metrics

Recovery metrics may include:

- Restore tests completed
- Restore success rate
- Critical recovery tests completed
- RTO pass rate
- RPO pass rate
- Failed recovery attempts
- Recovery-documentation deficiencies
- Open recovery findings
- Overdue corrective actions
- Recovery tests requiring retest

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 187. Key Performance Indicators

Key Performance Indicators (KPIs) may include:

- Percentage of required quarterly restore tests completed
- Percentage of Critical systems receiving annual recovery testing
- Percentage of Critical recovery tests meeting RTO
- Percentage of Critical recovery tests meeting RPO
- Percentage of recovery corrective actions completed and validated

---

# 188. Key Risk Indicators

Key Risk Indicators (KRIs) may include:

- Failed Critical recovery test
- Repeated RTO failure
- Repeated RPO failure
- Unrecoverable backup
- Unknown backup coverage
- Significant undocumented dependency
- Single-person recovery dependency
- Critical recovery finding overdue
- Provider recovery weakness

---

# 189. Metric Interpretation

Recovery metrics must be interpreted in context.

An increase in failed tests may result from:

- Declining capability
- More realistic testing
- Expanded test scope
- Improved identification of weaknesses

Test failure count alone does not establish whether overall risk increased or decreased.

---

# 190. R027 Backup / Recovery Failure

R027 has:

- Inherent risk: **20 Critical**
- Current residual risk: **12 High**
- Target residual risk: **5 Moderate**

---

# 191. R027 Treatment

R027 treatment includes:

- Automated backups
- Cloud backups
- Encrypted external-drive rotation
- Off-site separation
- Backup coverage validation
- Backup-job monitoring
- Quarterly representative restores
- Annual meaningful Critical recovery testing
- Independent recovery documentation
- Protected backup administration
- Evaluation of backup resilience against production compromise

---

# 192. R027 Validation

Target residual risk for R027 must not be treated as achieved until recovery capability is implemented and validated.

---

# 193. R028 Data Corruption

R028 has:

- Inherent risk: **16 High**
- Current residual risk: **9 Moderate**
- Target residual risk: **4 Low**

Recovery treatment includes:

- Validated backups
- Integrity checks
- Controlled access
- Controlled change
- Reconciliation
- Business validation

---

# 194. R016 Cloud Outage

R016 has:

- Inherent risk: **15 High**
- Current residual risk: **8 Moderate**
- Target residual risk: **6 Moderate**

Recovery treatment includes:

- Provider escalation
- Business Continuity/Disaster Recovery planning
- Independent recovery documentation
- Backups
- Manual continuity
- Cloud Exit and Emergency Migration planning

---

# 195. R017 ISP Outage

R017 has:

- Inherent risk: **16 High**
- Current residual risk: **9 Moderate**
- Target residual risk: **4 Low**

Technology continuity includes company-issued cellular capability where applicable.

---

# 196. R034 Loss of Headquarters

R034 has:

- Inherent risk: **10 High**
- Current residual risk: **8 Moderate**
- Target residual risk: **4 Low**

Cloud hosting reduces dependence on Headquarters as a technology hosting location.

---

# 197. R035 Regional Disaster

R035 has:

- Inherent risk: **9 Moderate**
- Current residual risk: **6 Moderate**
- Target residual risk: **5 Moderate**

A regional disaster may simultaneously affect:

- Facilities
- Personnel
- Wired communications
- Cellular communications
- Transportation
- Suppliers

---

# 198. Other Risk Relationships

This plan may also support treatment or response for:

- R003 Ransomware
- R004 Malware
- R006 Infinity Application Compromise
- R007 Internet Infrastructure Compromise
- R008 Denial of Service
- R013 Administrative / Configuration Error
- R018 Third-Party Technology Failure / Compromise
- R021 Fire
- R022 Water Damage
- R023 Utility / Power / HVAC Failure
- R026 Personnel Loss
- R033 Manual Outage Processing Error

---

# 199. Current and Proposed Controls

Recovery records must distinguish among:

- Current controls
- Partially implemented controls
- Planned controls
- Implemented controls awaiting validation
- Validated controls

---

# 200. No Premature Risk Credit

Current residual risk must not be reduced merely because:

- This plan exists.
- A backup exists.
- A recovery test is scheduled.
- A recovery improvement is planned.
- A provider states that recovery capability exists.
- A corrective action has been assigned.

Risk reduction requires implementation and appropriate validation.

---

# 201. Target Residual Risk

Target residual risk is a prediction of expected risk after proposed treatment.

It is not a guaranteed outcome.

---

# 202. Validated Post-Treatment Risk

After treatment is implemented and validated, the risk may be reassessed.

Validated post-treatment risk may be:

- Higher than target
- Equal to target
- Lower than target

Actual evidence determines the result.

---

# 203. Historical Risk Integrity

The original May 2013 risk assessment must remain preserved.

A later validated assessment may establish a new current residual risk without rewriting the historical result.

---

# 204. Findings

Material Disaster Recovery deficiencies must be documented.

Examples include:

- Critical system unable to meet RTO
- Recovery unable to meet RPO
- Backup unavailable
- Backup restoration failure
- Recovery documentation insufficient
- Required recovery credential unavailable
- Recovered system fails security validation
- Business owner cannot validate recovered information
- Critical dependency omitted from recovery documentation

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 205. Control Effectiveness

Recovery evidence may support conclusions that relevant controls are:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

Control effectiveness must reflect actual evidence rather than plan existence.

---

# 206. Traceability

This plan supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Disaster Recovery connects business recovery requirements to validated technical recovery capability.

---

# 207. Related Artifacts

- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
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
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[STD-001 Information Classification Standard]]
- [[STD-002 Network Security Standard]]
- [[STD-003 Endpoint Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-009 Malware Response Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-013 Manual Processing Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

---

# 208. Review

This plan must be reviewed:

- At least annually
- Following a material Disaster Recovery event
- Following significant BIA change
- Following significant technology change
- Following significant cloud-provider change
- Following significant backup or recovery change
- Following material recovery-test findings

The CIO coordinates plan review.

Material revisions require CEO approval.

---

# 209. Revision History

| Version | Date     | Description                    | Approval |
| ------- | -------- | ------------------------------ | -------- |
| 1.0     | May 2013 | Initial Disaster Recovery Plan | CEO      |