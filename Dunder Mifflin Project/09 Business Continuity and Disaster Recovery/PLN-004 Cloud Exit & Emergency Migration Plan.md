# PLN-004 Cloud Exit & Emergency Migration Plan

## Document Control

| Field | Value |
|---|---|
| Document ID | PLN-004 |
| Title | Cloud Exit & Emergency Migration Plan |
| Version | 1.0 |
| Classification | Confidential |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Cloud, Architecture, Recovery, or Provider Change |

---

# 1. Purpose

This plan establishes how Dunder Mifflin prepares for and, when necessary, executes an orderly or emergency departure from its primary cloud environment.

The plan addresses:

- Cloud-provider failure
- Extended cloud outage
- Material provider security compromise
- Loss of provider trust
- Contractual termination
- Provider business failure
- Unacceptable provider risk
- Planned migration to another hosting environment

---

# 2. Objective

The objective is to ensure that Dunder Mifflin can recover essential company systems and information without becoming permanently dependent on the continued operation, cooperation, or trustworthiness of one cloud provider.

---

# 3. Authority

This plan operates under:

- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]

---

# 4. Scope

This plan applies to cloud-hosted:

- Active Directory and authentication
- Servers
- Applications
- Databases
- CRM
- Order Management System (OMS)
- Warehouse Management System (WMS)
- Accounting systems
- Human Resources and Payroll systems
- Email
- File services
- Infinity
- Public Website
- Supporting management services
- Company data
- Configuration information
- Recovery information

---

# 5. Cloud-First Architecture

Dunder Mifflin uses a cloud-first architecture.

Major company systems are hosted outside company facilities rather than in a large company-operated data center at Headquarters.

This architecture reduces some local facility dependencies while increasing dependency on:

- Cloud-provider availability
- Cloud-provider infrastructure
- Provider administration
- Internet connectivity
- Provider recovery capability

---

# 6. Cloud Exit Is a Resilience Control

Cloud exit planning does not mean Dunder Mifflin expects its provider to fail.

It reduces the business impact of excessive dependence on a provider whose service may become:

- Unavailable
- Untrusted
- Unacceptable
- Commercially unsuitable

---

# 7. No Running Alternate Cloud

Dunder Mifflin does not maintain a continuously operating alternate cloud environment.

This plan does not assume:

- Hot standby infrastructure
- Warm standby infrastructure
- Real-time replication to another provider
- Immediate automated failover

An alternate environment must be prepared when migration is required.

---

# 8. Planned Exit and Emergency Migration

Cloud exit may occur through:

1. Planned Exit
2. Emergency Migration

The same information and recovery assets may support both, but urgency and risk differ.

---

# 9. Planned Exit

A Planned Exit occurs when Dunder Mifflin has sufficient time to:

- Select an alternate environment
- Prepare infrastructure
- Transfer data
- Test systems
- Coordinate users
- Schedule cutover
- Validate recovery
- Terminate the former service

---

# 10. Emergency Migration

Emergency Migration occurs when continued dependence on the current cloud provider creates unacceptable:

- Availability risk
- Security risk
- Integrity risk
- Business risk

and migration must begin before a normal planned transition can be completed.

---

# 11. Emergency Migration Is Not Automatic

A provider outage does not automatically require migration.

Migration may introduce substantial:

- Technical risk
- Data risk
- Security risk
- Configuration risk
- Business interruption

The decision must compare the risk of remaining with the provider against the risk of migration.

---

# 12. Business Impact Analysis

Migration priorities must be based on [[RPT-002 Business Impact Analysis]].

The Business Impact Analysis establishes:

- Criticality
- Maximum Tolerable Downtime (MTD)
- Recovery Time Objective (RTO)
- Recovery Point Objective (RPO)

---

# 13. Recovery Priority

Recovery priority is:

**Human Safety → Critical → High → Moderate → Low**

Migration sequencing must support this business priority.

---

# 14. Technical Dependencies

Technical dependencies may require a supporting service to be migrated before the business process it supports.

For example:

**Infrastructure → Authentication → Application → Business Process**

This does not change the underlying business criticality.

---

# 15. Cloud Exit Triggers

Potential cloud exit triggers include:

- Extended provider outage
- Provider security compromise
- Provider loss of data
- Provider data-integrity failure
- Provider business failure
- Provider contract termination
- Unacceptable provider performance
- Material provider control weakness
- Provider refusal or inability to remediate significant risk
- Strategic business decision

---

# 16. Emergency Migration Triggers

Emergency migration should be considered when:

- Provider recovery cannot meet business requirements.
- Provider systems cannot reasonably be trusted.
- Required company data remains available for migration or restoration.
- Continued provider dependence creates greater risk than migration.
- Executive management determines that remaining with the provider is unacceptable.

---

# 17. Cloud Outage Alone

A temporary provider outage does not automatically justify emergency migration.

The recovery team should first determine:

- Expected outage duration
- Provider recovery status
- Business impact
- Manual continuity capability
- Available recovery options
- Migration time
- Migration risk

---

# 18. Security Compromise

A provider security compromise may require emergency migration when:

- Administrative trust is lost.
- Company data integrity cannot reasonably be established.
- Unauthorized access remains possible.
- Provider containment is inadequate.
- Continued operation creates unacceptable company risk.

---

# 19. Provider Business Failure

Provider financial or operational failure may require planned or emergency migration depending on:

- Available notice
- Continued system access
- Data-export capability
- Contractual rights
- Provider cooperation
- Expected service termination

---

# 20. Planned Strategic Migration

The company may conduct a planned cloud exit even when no failure has occurred.

Possible reasons include:

- Cost
- Service quality
- Business strategy
- Contract changes
- Improved capability elsewhere
- Risk reduction

---

# 21. Decision Authority

The CEO has final authority for a material enterprise cloud exit.

The CIO is responsible for:

- Technical recommendation
- Migration planning
- Technology risk evaluation
- Provider coordination
- Recovery strategy

---

# 22. Emergency Technical Action

The CIO may authorize urgent technical preparation or containment when waiting for a complete executive decision would materially increase:

- Data loss
- Security exposure
- Recovery difficulty
- Business interruption

Major migration decisions must be escalated to the CEO as soon as practical.

---

# 23. Cloud Exit Team

The Cloud Exit team may include:

- CEO
- COO
- CFO
- CIO
- Legal/Compliance
- IT & Information Security Manager
- System Administrator
- Network / Security Administrator
- Information Security Analyst
- Relevant business owners
- Application owners
- Relevant third parties

---

# 24. CIO Responsibilities

The CIO coordinates:

- Migration strategy
- Technical priorities
- Alternate environment
- Provider escalation
- Technology resources
- Security requirements
- Executive status
- Cutover recommendation

---

# 25. IT & Information Security Manager Responsibilities

The IT & Information Security Manager coordinates:

- Technical execution
- Recovery documentation
- Migration assignments
- Security controls
- Validation
- Evidence
- Technical status
- Corrective action

---

# 26. Business Owner Responsibilities

Business owners are responsible for:

- Business priority
- Minimum functionality
- Business validation
- Manual continuity
- Data validation
- Cutover acceptance

---

# 27. Legal and Compliance Responsibilities

Legal/Compliance supports:

- Contract review
- Provider obligations
- Data-return requirements
- Data-destruction requirements
- Notification obligations
- Legal preservation
- Termination rights
- Disputes

---

# 28. Provider Responsibilities

Provider responsibilities depend on applicable contracts and service arrangements.

Expected assistance may include:

- Data export
- Documentation
- Account information
- Configuration information
- Service status
- Migration support
- Secure data return or destruction

Provider assistance must not be assumed beyond established rights and capabilities.

---

# 29. Migration Lifecycle

The migration lifecycle is:

**Assess → Decide → Prioritize → Preserve → Prepare → Build → Restore / Transfer → Validate → Cut Over → Monitor → Exit → Verify → Improve**

---

# 30. Initial Assessment

The initial assessment should determine:

- Why is exit being considered?
- Is the provider available?
- Is the provider trusted?
- What systems are affected?
- What business processes are affected?
- What data is accessible?
- What backups are available?
- What configurations are available?
- What alternate environment is available?
- What RTO and RPO requirements apply?
- What provider assistance is available?

---

# 31. Exit Decision Record

A material exit decision should document:

- Trigger
- Known facts
- Major unknowns
- Business impact
- Security impact
- Expected provider recovery
- Migration options
- Major migration risks
- Decision
- Approving authority

---

# 32. Migration Priority

Migration should generally prioritize technology supporting:

1. Critical business processes.
2. High business processes.
3. Moderate business processes.
4. Low business processes.

Technical dependencies may alter the order of individual systems.

---

# 33. Critical Business Processes

Critical business processes include:

- Order Processing
- Warehouse Operations

These have:

- MTD: 3 days
- RTO: 8 hours
- RPO: 4 hours

---

# 34. High-Priority Capabilities

High-priority capabilities include:

- Internet Connectivity
- Active Directory / Authentication
- Inventory Management
- Shipping / Delivery
- CRM
- Email
- Accounting
- Procurement
- File Services

---

# 35. Moderate-Priority Capabilities

Moderate-priority capabilities include:

- Infinity
- Customer Service
- Human Resources
- Payroll
- Accounts Payable
- Quality Assurance
- Legal / Compliance

Payroll may increase to High criticality near the biweekly payroll deadline.

---

# 36. Low-Priority Capability

The Public Website is Low criticality.

It should not displace migration resources needed for higher-priority capabilities.

---

# 37. System Inventory

Migration planning must identify cloud-hosted assets using [[REG-001 Enterprise Asset Register]] and current technical records.

---

# 38. Dependency Mapping

Each material cloud-hosted system should identify dependencies such as:

- Authentication
- Database
- Application server
- Network connectivity
- DNS
- File services
- Email
- External service
- Provider-specific component
- Business process

---

# 39. Dependency Gaps

Unknown dependencies discovered during migration must be documented.

Material gaps should result in:

- Recovery-documentation updates
- Architecture updates
- Corrective action where appropriate

---

# 40. Data Inventory

Migration planning should identify required data by:

- System
- Business owner
- Classification
- Recovery priority
- Recovery source
- RPO

---

# 41. Information Classification

Migrated information retains its classification under:

- [[POL-004 Information Classification & Handling Policy]]
- [[STD-001 Information Classification Standard]]

Migration does not lower information sensitivity.

---

# 42. Data Portability

Dunder Mifflin should maintain reasonable ability to retrieve company data in usable form.

Provider-dependent formats or processes that materially prevent recovery should be identified as continuity risk.

---

# 43. Configuration Portability

Where practical, Dunder Mifflin should maintain sufficient independent configuration information to recreate important systems outside the current provider.

---

# 44. Provider-Specific Dependencies

Provider-specific technology should be documented when loss of the provider would materially affect migration.

The existence of provider-specific capability is not automatically unacceptable.

The dependency must be understood.

---

# 45. Company Ownership

Dunder Mifflin retains ownership of company:

- Information
- Business records
- Configuration documentation
- Recovery documentation
- Application assets owned by the company

---

# 46. Infinity Ownership

Dunder Mifflin owns:

- Infinity application
- Source code
- Repository
- Application data
- Documentation
- Intellectual property
- Contractor work product
- Application backups

Cloud or contractor failure must not transfer ownership or control of these assets.

---

# 47. Independent Recovery Information

Critical recovery information must not exist solely within the cloud environment being replaced.

---

# 48. Recovery Documentation

Recovery documentation must be sufficient for a qualified IT professional unfamiliar with the specific environment to perform required recovery activities.

---

# 49. Documentation Independence

Critical recovery documentation must not exist solely:

- With one employee
- With one contractor
- In one cloud environment
- At Headquarters
- On the affected production system

---

# 50. Printed Documentation

Two printed recovery-documentation sets are maintained to support recovery when electronic documentation is unavailable.

---

# 51. Electronic Documentation

Protected electronic recovery documentation should also be maintained independently of affected production systems.

---

# 52. Backup Strategy

Cloud exit may use:

- Provider data export
- Automated backups
- Cloud-based backups
- Encrypted external hard-drive backups
- Other validated company recovery sources

---

# 53. External Backup Inventory

Dunder Mifflin maintains three encrypted external backup hard drives for each of seven facilities.

Total:

**21 encrypted external backup drives**

---

# 54. Off-Site Rotation

Each Friday, the current external backup drive is sent to the off-site Disaster Recovery storage provider.

The provider normally retains the two most recent weekly generations for each facility.

---

# 55. Off-Site Generations

Normal off-site external-drive inventory is:

**7 facilities × 2 generations = 14 off-site backup drives**

---

# 56. Backup Separation

Off-site storage provides separation from production facilities.

The backup environment is not considered immutable unless immutability is separately implemented and validated.

---

# 57. Backup Selection

Migration recovery sources must be selected based on:

- Integrity
- Availability
- Security trust
- Recovery point
- Business requirement

The newest backup is not automatically the safest recovery source.

---

# 58. Backup Validation

Backup availability does not establish:

- Completeness
- Integrity
- Recoverability
- RTO compliance
- RPO compliance

Recovery capability requires validation.

---

# 59. Alternate Environment

An alternate environment must provide sufficient capability to support the systems selected for migration.

---

# 60. Alternate Environment Selection

Selection should consider:

- Availability
- Capacity
- Security
- Connectivity
- Administrative capability
- Application compatibility
- Data-storage capability
- Recovery time
- Cost
- Provider risk

---

# 61. Alternate Provider Due Diligence

When another provider is used, security review must follow [[POL-008 Third-Party Security Policy]] to the extent practical.

Emergency circumstances may require accelerated review.

Any limitations must be documented.

---

# 62. Emergency Due Diligence

Emergency migration does not eliminate third-party risk evaluation.

When full pre-migration assessment is not possible:

1. Perform available critical checks.
2. Document gaps.
3. Apply compensating controls.
4. Complete remaining review as soon as practical.

---

# 63. Alternate Environment Security

The alternate environment must not be treated as trusted merely because it is new.

Security controls must be configured and validated.

---

# 64. Secure Configuration

New infrastructure must follow [[STD-006 Secure Configuration Standard]].

---

# 65. Server Security

Recovered or newly deployed servers must follow [[STD-004 Server Security Standard]].

---

# 66. Network Security

The alternate environment must follow [[STD-002 Network Security Standard]].

Unnecessary Internet-exposed administration must not be created merely to accelerate migration.

---

# 67. Authentication Security

Authentication must follow:

- [[POL-003 Access Control Policy]]
- [[STD-005 Authentication & Account Security Standard]]

---

# 68. Privileged Access

Migration personnel must use appropriate separate privileged credentials.

Privileged access must remain limited to authorized personnel.

---

# 69. Emergency Access

Emergency access must follow [[PROC-005 Emergency Access Procedure]].

Emergency access does not authorize external remote privileged administration.

---

# 70. Temporary Migration Accounts

Temporary migration accounts must be:

- Authorized
- Individually attributable where practical
- Limited in privilege
- Limited in duration
- Removed when no longer required

---

# 71. Provider Administrative Accounts

Administrative accounts associated with the former provider must be reviewed during exit.

Accounts no longer required must be disabled or removed.

---

# 72. Credential Replacement

Credentials should be replaced when:

- The former environment may be compromised.
- Provider personnel may know the credential.
- Credential secrecy cannot be established.
- Migration materially changes the trust boundary.

---

# 73. Active Directory Migration

Active Directory / Authentication is High criticality with:

- MTD: 24 hours
- RTO: 4 hours
- RPO: 4 hours

Authentication is likely to be an early technical migration priority because other systems depend on it.

---

# 74. Existing Authentication Architecture

Dunder Mifflin maintains at least two cloud-hosted Domain Controller/authentication servers within the same overall provider with reasonable failure-domain separation.

This protects against some individual-system failures but does not eliminate provider concentration risk.

---

# 75. Active Directory Migration Planning

Migration should consider:

- Domain integrity
- Directory data
- DNS dependencies
- Authentication
- Administrative access
- Application dependencies
- Backup state
- Security trust

---

# 76. Compromised Authentication Environment

If the existing authentication environment is reasonably suspected to be compromised, migration must prioritize restoration of trust rather than simple duplication of the existing state.

---

# 77. Domain Administrator Access

Standing Domain Administrator access remains restricted to:

- IT & Information Security Manager
- System Administrator

unless additional access is specifically authorized.

---

# 78. Active Directory Validation

Authentication migration must validate:

- User authentication
- Administrative authentication
- Directory integrity
- Required policies
- DNS or other required dependencies
- Application authentication

---

# 79. Application Migration

Each application migration should identify:

- Business owner
- Criticality
- Dependencies
- Application components
- Data
- Configuration
- Authentication
- Integration
- Recovery source
- Validation criteria

---

# 80. Database Migration

Database migration should protect:

- Confidentiality
- Integrity
- Availability
- Access control
- Recoverability

---

# 81. Database Integrity

A database should not be treated as successfully migrated merely because it can be opened.

Required business information and transaction integrity must be validated.

---

# 82. Order Processing Migration

Order Processing is Critical with:

- MTD: 3 days
- RTO: 8 hours
- RPO: 4 hours

Migration must prioritize the technology required to receive, record, verify, and route customer orders.

---

# 83. Warehouse System Migration

Warehouse Operations are Critical with:

- MTD: 3 days
- RTO: 8 hours
- RPO: 4 hours

Migration must support accurate warehouse processing and later reconciliation of manual transactions.

---

# 84. Inventory Migration

Inventory Management is High with:

- MTD: 3 days
- RTO: 12 hours
- RPO: 4 hours

Inventory data must be reconciled with inventory movement occurring during the disruption.

---

# 85. CRM Migration

CRM is High with:

- MTD: 3 days
- RTO: 12 hours
- RPO: 8 hours

Migration should validate customer records, authentication, and required business access.

---

# 86. Email Migration

Email is High with:

- MTD: 2 days
- RTO: 8 hours
- RPO: 4 hours

Migration should validate:

- User access
- Message flow
- Authentication
- Required historical information
- Security controls

---

# 87. File Services Migration

File Services are High with:

- MTD: 3 days
- RTO: 12 hours
- RPO: 8 hours

Migration must preserve required:

- Files
- Permissions
- Access control
- Integrity
- Business usability

---

# 88. Accounting Migration

Accounting is High with:

- MTD: 5 business days
- RTO: 24 hours
- RPO: 8 hours

Migration must preserve financial data and required financial controls.

---

# 89. Procurement Migration

Procurement is High with:

- MTD: 5 business days
- RTO: 2 business days
- RPO: 1 business day

---

# 90. Payroll Migration

Payroll is normally Moderate with:

- MTD: 5 business days
- RTO: 2 business days
- RPO: 1 business day

Payroll may increase to High criticality near the biweekly payroll deadline.

---

# 91. Infinity Migration

Infinity is Moderate with:

- MTD: 3 days
- RTO: 24 hours
- RPO: 4 hours

---

# 92. Infinity Components

Infinity migration must account for:

- Web tier
- Application tier
- Database tier
- Source repository
- Configuration
- Customer data
- Order data
- Payment tokens
- Authentication
- Logging
- Required integrations

---

# 93. Infinity Architecture

Infinity maintains logical separation:

**Web Tier → Application Tier → Database Tier**

The database must not become directly Internet accessible as part of migration.

---

# 94. Infinity Source Availability

Company-owned Infinity source code and repository must remain available independently enough to support migration or reconstruction.

---

# 95. Infinity Contractor Assistance

The Infinity contractor may support migration under approved contractor access requirements.

---

# 96. Infinity Contractor Privileged Access

Privileged production or administrative work by the Infinity contractor must be performed from the designated controlled Headquarters contractor workspace.

The contractor does not receive general VPN access for privileged production administration.

External remote privileged administration is prohibited. An exception or emergency process does not authorize the contractor to perform privileged production or administrative work from an external location.

---

# 97. Infinity Contractor Dependency

Migration must not depend exclusively on undocumented contractor knowledge.

Required architecture, configuration, build, deployment, and recovery information must be maintained by Dunder Mifflin.

---

# 98. Infinity Transferability

Infinity transferability must be evaluated through [[RPT-004 Infinity Transferability Review]].

The review should determine whether a qualified replacement resource can reasonably:

- Understand the application
- Build it
- Deploy it
- Administer it
- Recover it
- Support it

using company-controlled assets and documentation.

---

# 99. Infinity Security Validation

Before cutover, Infinity should be validated for:

- Authentication
- Authorization
- Web-tier exposure
- Application-tier communication
- Database isolation
- Logging
- Data integrity
- Required security configuration

---

# 100. Public Website Migration

The Public Website is Low criticality with:

- MTD: 7 days
- RTO: 3 days
- RPO: 24 hours

It should not displace migration resources required for higher-priority systems.

---

# 101. DNS Changes

Migration may require Domain Name System (DNS) changes.

DNS changes must be:

- Authorized
- Documented
- Verified
- Coordinated with cutover

---

# 102. Network Addressing

Required network addressing and routing changes must be documented and validated.

---

# 103. Firewall Rules

Firewall rules created for migration must follow:

- Least required access
- Approved exposure
- Change control
- Validation

Temporary rules must be removed when no longer required.

---

# 104. Internet Exposure

Migration urgency does not justify unnecessary Internet exposure.

Administrative interfaces must not be publicly exposed merely to simplify migration.

---

# 105. VPN

VPN may support authorized access to nonpublic resources from company laptops operating over external or untrusted networks.

Public Infinity access does not require VPN.

---

# 106. Remote Privileged Administration

External remote privileged administration is prohibited.

Ordinary remote access or VPN connectivity does not authorize privileged administration from an external location.

This prohibition applies during routine operations, emergencies, cloud exit, migration, recovery, and other exceptional circumstances. No exception process may authorize external remote privileged administration.

---

# 107. Data Transfer

Data transfer must consider:

- Classification
- Encryption
- Integrity
- Source trust
- Destination trust
- Transfer completeness

---

# 108. Sensitive Data Transfer

Confidential and Restricted information must receive appropriate protection during migration.

---

# 109. Payment Data

Dunder Mifflin does not normally retain full payment card PAN information.

The company retains payment tokens and limited payment information such as:

- Brand
- Last four digits
- Expiration information

as applicable.

---

# 110. Unexpected PAN Discovery

Discovery of full payment card PAN information during migration requires immediate escalation and investigation.

---

# 111. Data Integrity Validation

Migrated data should be validated using appropriate methods such as:

- Record counts
- Application validation
- Reconciliation
- File comparison
- Database checks
- Business-owner review

---

# 112. Migration Evidence

Significant migration activities should produce evidence including:

- Source
- Destination
- Date and time
- Data or system migrated
- Personnel
- Validation result
- Exceptions
- Approval

---

# 113. Evidence Handling

Security-related migration evidence must follow [[PROC-011 Evidence Handling Procedure]].

---

# 114. Change Management

Planned migration must follow [[POL-007 Change & Configuration Management Policy]].

---

# 115. Emergency Change

Emergency migration may require accelerated change procedures.

Emergency changes still require:

- Authorization
- Documentation
- Verification
- Post-change review

---

# 116. Testing Before Cutover

Where time permits, the alternate environment should be tested before business cutover.

Testing should address:

- Connectivity
- Authentication
- Application functionality
- Data integrity
- Security controls
- Business transactions
- Required integrations

---

# 117. Emergency Testing

Emergency migration may reduce the amount of pre-cutover testing possible.

Reduced testing must be documented and followed by increased post-cutover validation where necessary.

---

# 118. Cutover Criteria

Cutover should occur when:

- Required infrastructure is available.
- Required data is restored or transferred.
- Required authentication works.
- Required applications operate.
- Material security controls are functioning.
- Business validation is sufficient.
- Remaining risk is understood.

---

# 119. Cutover Authority

The CIO recommends technical cutover.

Relevant business owners confirm required business capability.

Material enterprise cutover is authorized by the CEO or delegated executive authority.

---

# 120. Cutover Sequence

A cutover may include:

1. Freeze or control transactions where required.
2. Complete final data transfer.
3. Validate destination state.
4. Change routing or DNS.
5. Enable business access.
6. Validate transactions.
7. Monitor.
8. Restrict obsolete source access.

---

# 121. Transaction Freeze

A temporary transaction freeze may be required to prevent:

- Duplicate transactions
- Missing transactions
- Conflicting records
- Divergent source and destination data

The duration should be minimized.

---

# 122. Manual Continuity During Migration

Business processes may use manual continuity while systems are being migrated.

Manual activity follows [[PROC-013 Manual Processing Procedure]].

---

# 123. Manual Processing Lifecycle

The manual processing lifecycle is:

**Collect → Review → Enter → Reconcile → Verify**

---

# 124. Manual Reconciliation

Transactions processed manually during migration must be reconciled after system restoration.

---

# 125. Rollback

Planned migrations should include a rollback strategy where practical.

---

# 126. Rollback Criteria

Rollback may be appropriate when:

- Critical functionality fails.
- Data integrity cannot be established.
- Security controls fail.
- Required dependencies fail.
- Business operation is materially worse after cutover.

---

# 127. Emergency Migration Rollback

Rollback may be impossible when the former provider is:

- Unavailable
- Compromised
- Untrusted
- Terminated

The limitation must be identified during decision-making.

---

# 128. Source Environment Trust

Rollback to a compromised or untrusted source environment must not occur solely because migration is difficult.

The security consequences must be considered.

---

# 129. Post-Cutover Monitoring

After cutover, heightened monitoring should focus on:

- Authentication
- Privileged access
- Application errors
- Connectivity
- Data integrity
- Security alerts
- Business transaction failures

---

# 130. Business Validation

Business owners must validate that migrated systems support required business processes.

Technical availability alone is insufficient.

---

# 131. Technical Validation

Technical personnel should validate:

- System operation
- Connectivity
- Dependencies
- Authentication
- Application operation
- Logging
- Backup capability

---

# 132. Security Validation

Security validation should confirm:

- Least privilege
- Administrative controls
- Authentication
- Encryption
- Firewall rules
- Required antivirus
- Logging
- Secure configuration
- Appropriate Internet exposure

---

# 133. Recovery Validation

Migration must be evaluated against applicable RTO and RPO requirements.

---

# 134. RTO Measurement

Actual elapsed recovery or migration time must be measured against the approved RTO.

---

# 135. RPO Measurement

Actual recoverable data loss must be measured against the approved RPO.

---

# 136. RTO or RPO Failure

Failure to meet RTO or RPO must be:

1. Documented.
2. Evaluated.
3. Assigned for corrective action.
4. Escalated based on impact.
5. Retested where appropriate.

---

# 137. Provider Data Return

At exit, Dunder Mifflin should obtain required company information from the former provider in usable form where applicable.

---

# 138. Provider Data Destruction

When contractually and technically applicable, the company should obtain appropriate confirmation that former-provider copies of company information no longer required for legitimate retention have been destroyed or otherwise disposed of as required.

---

# 139. Provider Account Removal

Former-provider access to Dunder Mifflin systems must be removed when no longer required.

---

# 140. Credential Cleanup

Credentials associated with the former provider should be:

- Disabled
- Removed
- Replaced

as appropriate.

---

# 141. Integration Cleanup

Connections to the former provider should be reviewed for removal, including:

- Network connections
- Application integrations
- Accounts
- Scheduled jobs
- Data transfers
- Administrative access

---

# 142. Contract Closure

Legal/Compliance and responsible management should address:

- Termination provisions
- Final service obligations
- Data return
- Data destruction
- Outstanding disputes
- Required records

---

# 143. Former Environment Preservation

When the exit involves a security incident or legal matter, required evidence must be preserved before destruction or termination where practical.

---

# 144. Decommissioning

Company-controlled infrastructure no longer required after migration should be securely decommissioned.

---

# 145. Migration Closure

Migration may be closed when:

- Required business services operate in the destination.
- Technical validation is complete.
- Security validation is complete.
- Business validation is complete.
- Required data reconciliation is complete.
- Former-provider access is addressed.
- Material findings are documented.
- Remaining risk is understood.

---

# 146. Closure Does Not End Corrective Action

Migration closure does not automatically close:

- Recovery findings
- Security findings
- Provider findings
- Documentation gaps
- Corrective actions
- Risk treatments

---

# 147. Post-Migration Review

A material cloud migration requires a documented post-migration review.

---

# 148. Post-Migration Review Topics

The review should consider:

- Exit decision
- Provider cooperation
- Data portability
- Configuration portability
- Documentation
- Recovery timing
- RPO
- Security
- Application dependencies
- Business validation
- Manual continuity
- Cutover
- Rollback capability

---

# 149. Lessons Learned

Lessons learned should be incorporated into:

- Architecture
- Recovery documentation
- Provider requirements
- Business Continuity
- Disaster Recovery
- Risk treatment
- Future cloud selection

---

# 150. Corrective Action

Material migration deficiencies must identify:

- Deficiency
- Accountable owner
- Required action
- Due date
- Validation method

Material corrective actions are tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 151. Corrective-Action Validation

Corrective action is not complete merely because the assigned activity is reported as finished.

Validation must determine whether the intended outcome was achieved.

---

# 152. Cloud Exit Exercises

The Cloud Exit and Emergency Migration capability should be exercised periodically.

A full production-provider migration is not required for every exercise.

---

# 153. Exercise Types

Exercises may include:

- Tabletop exercise
- Provider-failure scenario
- Data-export exercise
- Backup-restoration exercise
- Alternate-environment build exercise
- Authentication recovery exercise
- Application migration exercise
- Infinity transferability exercise

---

# 154. Exercise Scope

Exercise scope should be selected based on:

- Business criticality
- Provider concentration
- Recovery risk
- Previous findings
- Architecture changes

---

# 155. Data Export Exercise

A data-export exercise should determine whether required company information can be retrieved in a usable form.

---

# 156. Configuration Recovery Exercise

A configuration exercise should determine whether company-controlled documentation is sufficient to recreate important technology outside the existing provider.

---

# 157. Alternate Environment Exercise

Where practical, selected systems may be built or restored into a controlled alternate environment to validate portability.

---

# 158. Authentication Exercise

An authentication migration exercise should evaluate whether required directory and authentication capability can be reconstructed or restored outside the current provider.

---

# 159. Infinity Transferability Exercise

An Infinity exercise should determine whether a qualified replacement resource can use company-controlled:

- Source code
- Repository
- Documentation
- Configuration
- Backup
- Deployment information

to restore or transfer the application.

---

# 160. Exercise Evidence

Exercise evidence should include:

- Scenario
- Scope
- Participants
- Assumptions
- Actions
- Actual results
- Limitations
- Findings
- Corrective actions
- Retest requirements

---

# 161. No Manufactured Evidence

Personnel must not:

- Backdate exercises.
- Record unperformed migration steps as successful.
- Conceal failed recovery.
- Claim data portability without testing it.
- Claim provider independence without supporting evidence.

---

# 162. Failed Exercise

A failed cloud-exit exercise is useful assurance evidence.

Failure should result in:

1. Documentation.
2. Analysis.
3. Corrective action.
4. Retesting where appropriate.
5. Risk reassessment when material.

---

# 163. Assessment Methods

Cloud-exit assurance may use:

- Inspection
- Observation
- Interviews
- Sampling
- Exercises
- Technical Testing
- Reconciliation
- Independent Performance

---

# 164. Independent Performance

An assessor may independently perform selected authorized cloud-exit activities.

For example, the assessor may:

1. Select a cloud-hosted system.
2. Identify its BIA requirements.
3. Identify dependencies.
4. Locate company-controlled recovery information.
5. Identify an appropriate recovery source.
6. Determine alternate-environment requirements.
7. Perform or observe controlled restoration where authorized.
8. Validate functionality and security.
9. Identify portability gaps.
10. Compare actual capability with documented requirements.

---

# 165. Cloud Exit Metrics

Metrics may include:

- Critical systems with documented cloud-exit procedures
- Systems with independently available recovery documentation
- Successful data-export tests
- Successful alternate-environment recovery tests
- Cloud-exit exercise completion
- Portability findings
- Provider-dependency findings
- Open cloud-exit corrective actions
- Overdue corrective actions

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 166. Key Performance Indicators

Key Performance Indicators (KPIs) may include:

- Percentage of Critical cloud-hosted systems with documented exit procedures
- Percentage of Critical systems with validated independent recovery information
- Percentage of required cloud-exit exercises completed
- Percentage of selected data-export tests completed successfully
- Percentage of cloud-exit corrective actions completed and validated

---

# 167. Key Risk Indicators

Key Risk Indicators (KRIs) may include:

- Critical system without independent recovery documentation
- Failed data-export test
- Failed alternate-environment restoration
- Undocumented provider-specific dependency
- Unrecoverable cloud-hosted data
- Excessive provider administrative dependency
- Critical cloud-exit finding overdue
- Repeated portability failure

---

# 168. Metric Interpretation

Cloud-exit metrics must be interpreted in context.

Additional findings may result from:

- Increased assessment coverage
- More realistic exercises
- Improved documentation
- Actual degradation

Finding count alone does not establish whether cloud risk increased or decreased.

---

# 169. R016 Cloud Outage

R016 has:

- Inherent risk: **15 High**
- Current residual risk: **8 Moderate**
- Target residual risk: **6 Moderate**

---

# 170. R016 Treatment

R016 treatment includes:

- Business Continuity/Disaster Recovery planning
- Cloud Exit and Emergency Migration planning
- Independent recovery documentation
- Encrypted backups
- Manual continuity
- Provider escalation
- Provider resilience review
- Provider concentration consideration

---

# 171. R018 Third-Party Technology Failure / Compromise

R018 has:

- Inherent risk: **12 High**
- Current residual risk: **8 Moderate**
- Target residual risk: **6 Moderate**

Cloud-provider failure or compromise may trigger both third-party incident response and cloud-exit evaluation.

---

# 172. R026 Personnel Loss

R026 has:

- Inherent risk: **16 High**
- Current residual risk: **9 Moderate**
- Target residual risk: **4 Low**

Independent recovery documentation reduces dependence on individual administrators or contractors.

---

# 173. R027 Backup / Recovery Failure

R027 has:

- Inherent risk: **20 Critical**
- Current residual risk: **12 High**
- Target residual risk: **5 Moderate**

Cloud exit depends heavily on validated recovery capability.

---

# 174. R034 Loss of Headquarters

R034 has:

- Inherent risk: **10 High**
- Current residual risk: **8 Moderate**
- Target residual risk: **4 Low**

Cloud-hosted systems reduce dependence on Headquarters for technology hosting.

Independent recovery documentation and alternate access remain important.

---

# 175. R035 Regional Disaster

R035 has:

- Inherent risk: **9 Moderate**
- Current residual risk: **6 Moderate**
- Target residual risk: **5 Moderate**

A regional disaster may affect personnel, facilities, telecommunications, and access to recovery resources even when the cloud provider remains available.

---

# 176. Other Risk Relationships

This plan may also support treatment or response for:

- R003 Ransomware
- R005 Password / Authentication Weakness
- R006 Infinity Application Compromise
- R007 Internet Infrastructure Compromise
- R013 Administrative / Configuration Error
- R019 Infinity Contractor Dependency / Compromise
- R028 Data Corruption

---

# 177. Current and Proposed Controls

Cloud-exit records must distinguish among:

- Current controls
- Partially implemented controls
- Planned controls
- Implemented controls awaiting validation
- Validated controls

---

# 178. No Premature Risk Credit

Current residual risk must not be reduced merely because:

- This plan exists.
- An alternate provider has been identified.
- Migration is technically possible in theory.
- A data export has been scheduled.
- Recovery documentation is being developed.
- A migration exercise is planned.

Risk reduction requires implementation and appropriate validation.

---

# 179. Target Residual Risk

Target residual risk represents expected risk after proposed treatment.

It is a prediction rather than a guaranteed outcome.

---

# 180. Validated Post-Treatment Risk

After treatment is implemented and validated, actual risk may be reassessed.

Validated post-treatment risk may be:

- Higher than target
- Equal to target
- Lower than target

Evidence determines the result.

---

# 181. Historical Risk Integrity

The original May 2013 risk assessment must remain preserved.

Future validated assessments may establish new current residual risk without rewriting the historical assessment.

---

# 182. Findings

Material cloud-exit deficiencies must be documented.

Examples include:

- Critical data cannot be exported.
- Recovery documentation exists only in the primary cloud.
- Critical system cannot be rebuilt outside the provider.
- Required configuration is undocumented.
- Provider-specific dependency prevents recovery.
- Authentication cannot be restored within required time.
- Infinity cannot be transferred using company-controlled assets.
- Alternate environment fails required security validation.

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 183. Control Effectiveness

Cloud-exit evidence may support conclusions that relevant controls are:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

Control effectiveness must reflect actual evidence rather than the existence of this plan.

---

# 184. Traceability

This plan supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Cloud exit provides evidence connecting provider concentration risk to recoverable business capability.

---

# 185. Related Artifacts

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
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[STD-001 Information Classification Standard]]
- [[STD-002 Network Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-013 Manual Processing Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-004 Data Exposure Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

---

# 186. Review

This plan must be reviewed:

- At least annually
- Following a material cloud-provider incident
- Following significant cloud architecture change
- Following significant provider change
- Following significant BIA change
- Following a cloud-exit exercise
- Following material portability or recovery findings

The CIO coordinates plan review.

Material revisions require CEO approval.

---

# 187. Revision History

| Version | Date     | Description                                   | Approval |
| ------- | -------- | --------------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Cloud Exit & Emergency Migration Plan | CEO      |