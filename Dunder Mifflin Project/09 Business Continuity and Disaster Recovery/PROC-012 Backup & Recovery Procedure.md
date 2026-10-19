# PROC-012 Backup & Recovery Procedure

## Document Control

| Field | Value |
|---|---|
| Document ID | PROC-012 |
| Title | Backup & Recovery Procedure |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Backup, Recovery, or Technology Change |

---

# 1. Purpose

This procedure defines how Dunder Mifflin performs, monitors, protects, tests, and validates backup and recovery activities.

The procedure converts requirements established by [[POL-010 Business Continuity & Disaster Recovery Policy]], [[RPT-002 Business Impact Analysis]], and [[PLN-003 Disaster Recovery Plan]] into repeatable operational activities.

---

# 2. Objectives

The objectives are to:

- Protect required company information.
- Maintain recoverable copies of important systems and data.
- Detect backup failures.
- Maintain off-site backup separation.
- Protect backup confidentiality.
- Validate restoration capability.
- Measure recovery performance against Recovery Time Objective (RTO) and Recovery Point Objective (RPO).
- Document failures.
- Correct identified recovery weaknesses.
- Maintain reliable recovery evidence.

---

# 3. Scope

This procedure applies to backup and recovery activities for systems and information identified as requiring protection through:

- [[REG-001 Enterprise Asset Register]]
- [[RPT-002 Business Impact Analysis]]
- [[STD-001 Information Classification Standard]]
- System recovery documentation
- Business requirements

---

# 4. Authority

This procedure operates under:

- [[POL-001 Information Security Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[STD-006 Secure Configuration Standard]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]

---

# 5. Backup Strategy

Dunder Mifflin uses multiple backup mechanisms, including:

- Automated backups
- Cloud-based backups
- Encrypted external hard drives
- Off-site external-drive storage

No single backup mechanism should automatically be assumed sufficient for every recovery requirement.

---

# 6. Backup and Recovery Lifecycle

The operational lifecycle is:

**Identify → Back Up → Monitor → Protect → Rotate → Verify → Test Restore → Measure → Validate → Correct → Retest**

---

# 7. Backup Is Not Recovery

A completed backup job does not prove that information can be successfully restored.

Recovery capability requires actual restoration and validation.

---

# 8. Backup Success Is Not Business Success

A technically successful restore does not prove that:

- The correct data was protected.
- Required data is complete.
- RPO was achieved.
- RTO was achieved.
- Business processes can operate.
- Recovered data is trustworthy.

---

# 9. Backup Coverage

Backup coverage must be evaluated against:

- Business processes
- Systems
- Databases
- File repositories
- Application data
- Configuration information
- Recovery documentation
- Information classification
- BIA requirements

---

# 10. Backup Coverage Review

Backup coverage should be reviewed when:

- A new significant system is introduced.
- A system is materially changed.
- Business criticality changes.
- Data location changes.
- Recovery requirements change.
- A restore test identifies missing information.
- A backup failure exposes a coverage gap.

---

# 11. System Ownership

The responsible system or business owner must identify information required to support business recovery.

Information Technology determines the technical backup method in coordination with the owner.

---

# 12. Business Impact Analysis

[[RPT-002 Business Impact Analysis]] establishes recovery requirements.

Backup design must support applicable RPO requirements.

Recovery capability must support applicable RTO requirements.

---

# 13. RTO

Recovery Time Objective (RTO) is the target period within which a disrupted capability should be restored.

RTO is measured against actual recovery performance.

---

# 14. RPO

Recovery Point Objective (RPO) is the maximum acceptable amount of data loss measured in time.

RPO is measured against the actual recoverable point.

---

# 15. RTO and RPO Are Separate

A recovery test may:

- Pass RTO and pass RPO.
- Pass RTO and fail RPO.
- Fail RTO and pass RPO.
- Fail both.

Each requirement must be evaluated independently.

---

# 16. Critical Recovery Requirements

Critical business processes include:

| Process | MTD | RTO | RPO |
|---|---:|---:|---:|
| Order Processing | 3 days | 8 hours | 4 hours |
| Warehouse Operations | 3 days | 8 hours | 4 hours |

---

# 17. High Recovery Requirements

High-priority capabilities include:

| Process / Capability | MTD | RTO | RPO |
|---|---:|---:|---:|
| Inventory Management | 3 days | 12 hours | 4 hours |
| Shipping / Delivery | 3 days | 12 hours | 8 hours |
| Internet Connectivity | 24 hours | 4 hours | N/A |
| Active Directory / Authentication | 24 hours | 4 hours | 4 hours |
| CRM | 3 days | 12 hours | 8 hours |
| Email | 2 days | 8 hours | 4 hours |
| Accounting | 5 business days | 24 hours | 8 hours |
| Procurement | 5 business days | 2 business days | 1 business day |
| File Services | 3 days | 12 hours | 8 hours |

---

# 18. Moderate and Low Recovery Requirements

Moderate and Low requirements remain governed by [[RPT-002 Business Impact Analysis]].

Backup design must not ignore lower-priority systems merely because higher-priority systems recover first.

---

# 19. Backup Scheduling

Backup schedules should be established according to:

- RPO
- Data-change rate
- Business criticality
- Technical capability
- Available backup mechanisms
- Recovery requirements

---

# 20. Automated Backups

Automated backups should run according to approved schedules.

Automation reduces dependence on manual initiation but does not eliminate the need for monitoring.

---

# 21. Cloud Backups

Cloud-based backup capability may provide:

- Automated protection
- Remote storage
- Geographic separation
- Recovery options

Cloud backup capability must still be validated through restoration.

---

# 22. External Backup Drives

Dunder Mifflin maintains three encrypted external backup hard drives for each of seven facilities.

Total external backup drives:

**21**

---

# 23. Facility Allocation

The external-drive allocation is:

| Facility | Drives |
|---|---:|
| Scranton Headquarters | 3 |
| Scranton Branch | 3 |
| Syracuse Branch | 3 |
| Utica Branch | 3 |
| Rochester Branch | 3 |
| Nashua Branch | 3 |
| Akron Branch | 3 |
| **Total** | **21** |

---

# 24. External Drive Identification

Each external backup drive should have a unique identifier sufficient to distinguish:

- Facility
- Drive
- Rotation position

The identifier must not unnecessarily disclose sensitive backup contents.

---

# 25. Backup Encryption

External backup drives must remain encrypted.

Encryption protects backup confidentiality if media is:

- Lost
- Stolen
- Misdelivered
- Accessed without authorization

---

# 26. Encryption Does Not Prove Recovery

Backup encryption does not establish:

- Backup completeness
- Backup integrity
- Restore success
- RTO compliance
- RPO compliance

These require separate validation.

---

# 27. External Drive Use

External backup drives must be used only for authorized backup and recovery purposes.

They must not be used as general portable storage.

---

# 28. External Drive Connection

A backup drive should be connected only when required for:

- Backup
- Verification
- Authorized restoration
- Authorized testing

It should not remain unnecessarily connected to production systems.

---

# 29. Malware Consideration

A backup drive must not be unnecessarily connected to a system known or reasonably suspected to be actively compromised.

---

# 30. Ransomware Consideration

During suspected ransomware:

- Protect backup media from affected systems.
- Do not connect offline backup drives merely to test whether data remains available.
- Review backup administrative access.
- Determine whether backup systems may also be affected.

Response must coordinate with [[PROC-009 Malware Response Procedure]] and [[PBK-002 Malware & Ransomware Playbook]].

---

# 31. Weekly External Drive Rotation

Each Friday, the current backup drive for each facility is sent to the off-site Disaster Recovery storage provider.

---

# 32. Off-Site Provider Custody

The off-site provider normally retains the two most recent weekly external-drive generations for each facility.

---

# 33. Normal Off-Site Inventory

Normal off-site external-drive custody is:

**7 facilities × 2 generations = 14 drives**

---

# 34. Rotation Cycle

The normal rotation is:

1. Current facility drive completes the required backup.
2. Backup completion is reviewed.
3. Drive is prepared for off-site transfer.
4. Drive is transferred to the off-site provider.
5. Provider receives the drive.
6. Provider retains the two latest generations.
7. Oldest generation is returned.
8. Returned drive reenters the facility rotation.

---

# 35. Rotation Objective

The rotation provides geographic and physical separation between:

- Production systems
- Local backup media
- Off-site backup media

---

# 36. Off-Site Separation Is Not Immutability

Off-site storage provides useful separation.

The backup environment must not be described as immutable unless immutability is specifically implemented and validated.

---

# 37. Rotation Record

Each external-drive transfer should record:

- Drive identifier
- Facility
- Backup date
- Transfer date
- Person releasing media
- Provider receipt where available
- Returned drive identifier
- Exceptions

---

# 38. Missing Drive

A backup drive that cannot be accounted for must be promptly investigated.

The investigation should determine:

- Last known custody
- Encryption status
- Data sensitivity
- Whether unauthorized access is reasonably possible
- Whether incident escalation is required

---

# 39. Damaged Drive

A damaged backup drive must be:

- Removed from normal rotation.
- Evaluated for recoverability.
- Replaced when necessary.
- Securely disposed of when no longer usable.

---

# 40. Media Disposal

Backup media containing company information must be securely disposed of when retired.

Disposal must account for the sensitivity of the stored information.

---

# 41. Backup Job Monitoring

Backup jobs should be reviewed for:

- Successful completion
- Failure
- Warning
- Missing source
- Capacity issue
- Authentication failure
- Storage failure
- Unexpected duration

---

# 42. Backup Monitoring Responsibility

Information Technology is responsible for operational backup monitoring.

The IT & Information Security Manager is accountable for ensuring material backup failures are addressed.

---

# 43. Backup Failure

A failed backup requires investigation.

The record should identify:

- System
- Backup job
- Failure date and time
- Error
- Expected RPO
- Last known successful backup
- Business impact
- Corrective action

---

# 44. Backup Failure Priority

Backup failure priority should consider:

- System criticality
- RPO
- Time since last successful backup
- Availability of alternate backup mechanisms
- Data-change rate
- Security circumstances

---

# 45. Critical Backup Failure

A backup failure affecting a Critical system or creating a material RPO exposure requires prompt escalation.

---

# 46. Repeated Backup Failure

Repeated backup failure requires analysis beyond simply restarting the job.

The cause may involve:

- Capacity
- Authentication
- Configuration
- Storage
- Network
- Software
- Hardware
- Process weakness

---

# 47. Missed Backup

A missed backup must not be recorded as successful because a later backup completes.

The missed protection period remains part of the operational record.

---

# 48. Backup Warning

Warnings must be reviewed to determine whether the backup remains usable.

A job status of "completed with warnings" must not automatically be treated as successful.

---

# 49. Partial Backup

A partial backup must identify what was and was not protected.

Material omissions require correction and may require escalation.

---

# 50. Backup Capacity

Backup capacity should be monitored sufficiently to identify conditions that could prevent future successful backups.

---

# 51. Backup Credentials

Backup administrative credentials must be restricted to authorized personnel.

---

# 52. Backup Administrative Privilege

Backup administration is privileged activity.

Access must follow:

- [[POL-003 Access Control Policy]]
- [[STD-005 Authentication & Account Security Standard]]
- [[PROC-002 Privileged Access Procedure]]

---

# 53. Separate Privileged Credentials

Personnel performing privileged backup administration must use appropriate separate privileged credentials.

---

# 54. Backup Service Accounts

Backup service accounts must:

- Have a defined purpose.
- Use only required privilege.
- Be documented.
- Be protected from unnecessary interactive use.
- Be reviewed when systems or backup architecture change.

---

# 55. Backup Access Review

Backup administrative access must be included in privileged-access review.

---

# 56. Terminated Personnel

Backup administrative access for terminated personnel must be revoked promptly.

---

# 57. Emergency Backup Access

Emergency access to backup systems or protected recovery credentials must follow [[PROC-005 Emergency Access Procedure]].

---

# 58. Backup Configuration

Backup configuration should identify:

- Protected source
- Schedule
- Destination
- Retention or rotation
- Responsible personnel
- Recovery method

---

# 59. Configuration Change

Material changes to backup configuration must follow [[POL-007 Change & Configuration Management Policy]].

---

# 60. Backup Configuration Protection

Backup configuration and recovery information must be protected from unauthorized modification.

---

# 61. Backup Configuration Documentation

Important backup configuration must be documented sufficiently to support recovery if the normal backup-management environment is unavailable.

---

# 62. Recovery Documentation

Recovery documentation must be sufficient for a qualified IT professional unfamiliar with the specific environment to perform the required restoration.

---

# 63. Recovery Documentation Independence

Critical recovery documentation must not exist solely:

- On the protected production system
- In one cloud environment
- At one facility
- With one employee
- With one contractor

---

# 64. Recovery Documentation Changes

A significant technology or configuration change is not complete until applicable recovery documentation has been reviewed and updated where necessary.

---

# 65. Restore Request

A restore may be initiated because of:

- Accidental deletion
- Data corruption
- System failure
- Application failure
- Security incident
- Disaster Recovery
- Authorized testing

---

# 66. Restore Authorization

Restoration must be authorized according to:

- Business ownership
- System ownership
- Information sensitivity
- Technical responsibility
- Incident requirements

---

# 67. Restore Scope

Before restoration, personnel should determine:

- What must be restored?
- Why is restoration required?
- What recovery point is needed?
- Where will restoration occur?
- Is production restoration appropriate?
- Is the source trusted?
- What validation is required?

---

# 68. Recovery Source Selection

The recovery source should be selected based on:

- Required recovery point
- Integrity
- Security trust
- Availability
- Business requirement

The newest backup is not automatically the correct source.

---

# 69. Corrupted Backup Risk

If corruption may exist in a recent backup, an earlier known-good recovery point may be required.

The resulting data loss must be measured against RPO.

---

# 70. Compromised Backup Risk

If compromise may exist within a backup, personnel must coordinate with Incident Response before restoring it into production.

---

# 71. Restore Destination

Where practical, restoration should first occur in a controlled environment when:

- Integrity is uncertain.
- Malware is suspected.
- The restoration is a test.
- Production replacement is not immediately required.

---

# 72. Production Restore

A production restore must consider:

- Business interruption
- Current data
- Transaction loss
- Security
- Dependencies
- Rollback
- Required reconciliation

---

# 73. Data Overwrite

Personnel must not overwrite current production information without understanding the business impact.

Where practical, preserve the existing state before destructive restoration.

---

# 74. Evidence Preservation

If restoration relates to a security incident, evidence must be preserved before destructive action where practical.

Evidence handling follows [[PROC-011 Evidence Handling Procedure]].

---

# 75. Restore Preparation

Restore preparation should confirm:

- Required backup is available.
- Required credentials are available.
- Destination is prepared.
- Dependencies are understood.
- Required personnel are available.
- Validation criteria are defined.

---

# 76. Restore Execution

Personnel performing restoration should record:

- Start time
- Recovery source
- Recovery point
- System or data restored
- Significant actions
- Errors
- Completion time

---

# 77. Restore Failure

A failed restore must remain documented.

Personnel should record:

- Failure point
- Error
- Recovery source
- Corrective action
- Alternate recovery source if used

---

# 78. Alternate Recovery Source

If the selected backup fails, another recovery source may be used.

The new recovery point must be documented and compared with RPO.

---

# 79. Technical Validation

After restoration, technical personnel should validate as applicable:

- Files or data are accessible.
- Required services operate.
- Application dependencies function.
- Authentication functions.
- Permissions are present.
- Required configuration is present.
- Logging operates.

---

# 80. Security Validation

Security validation should confirm as applicable:

- Required access controls are operating.
- Administrative access is restricted.
- Encryption remains enabled.
- Antivirus is operating.
- Required network restrictions are present.
- Known compromise has been addressed.

---

# 81. Data Validation

Recovered information should be evaluated for:

- Completeness
- Integrity
- Correct recovery point
- Business usability

---

# 82. Business Validation

For material restoration, the business owner or qualified representative should confirm that recovered information supports the required business activity.

---

# 83. Restore Completion

A restore is not complete solely because the restore utility reports success.

Completion requires applicable:

- Technical validation
- Security validation
- Data validation
- Business validation

---

# 84. Manual Continuity Data

When systems recover after manual business operations, continuity records must be processed under [[PROC-013 Manual Processing Procedure]].

---

# 85. Manual Processing Lifecycle

The manual processing lifecycle is:

**Collect → Review → Enter → Reconcile → Verify**

---

# 86. Reconciliation

Restored electronic data must be reconciled with manual transactions where required.

---

# 87. Restore Test Program

Dunder Mifflin maintains two primary recovery-testing requirements:

1. Quarterly representative restore testing.
2. Annual meaningful recovery testing for Critical systems.

---

# 88. Quarterly Representative Restore Testing

Representative restore testing must occur quarterly.

The test should rotate through meaningful:

- Systems
- Data types
- Backup sources
- Facilities

over time.

---

# 89. Quarterly Test Objective

The quarterly test determines whether selected backup information can actually be restored and used.

---

# 90. Quarterly Test Selection

Test selection should consider:

- Business criticality
- Previous testing
- Backup changes
- Previous failures
- Information sensitivity
- Recovery risk

---

# 91. Quarterly Test Independence

Testing should avoid repeatedly selecting only the easiest backup or smallest dataset.

The test program should provide meaningful coverage over time.

---

# 92. Annual Critical Recovery Testing

Critical systems require at least one meaningful recovery test annually.

---

# 93. Meaningful Recovery Test

A meaningful recovery test should demonstrate more than file extraction.

It should evaluate enough of the recovery process to determine whether the required business capability can reasonably be restored.

---

# 94. Annual Critical Test Scope

Annual Critical-system testing should include as applicable:

- Recovery source
- System restoration
- Dependencies
- Authentication
- Data
- Security controls
- Business functionality
- RTO
- RPO

---

# 95. Test Planning

Each formal recovery test should identify:

- System or capability
- Business owner
- Criticality
- RTO
- RPO
- Test objective
- Recovery source
- Start condition
- Success criteria
- Participants
- Validation method

---

# 96. Test Start Time

The test record must define the point at which recovery timing begins.

The method must be consistent enough to permit meaningful comparison.

---

# 97. Recovery Completion Time

The test must identify the point at which required recovery is considered complete.

This should correspond to the defined test success criteria.

---

# 98. RTO Measurement

RTO performance is:

**Actual Recovery Completion Time - Defined Recovery Start Time**

The result is compared with the approved RTO.

---

# 99. RTO Pass

RTO passes when actual recovery time is equal to or less than the approved RTO.

---

# 100. RTO Failure

RTO fails when actual recovery time exceeds the approved RTO.

Eventual successful recovery does not convert an RTO failure into a pass.

---

# 101. Recovery Point

The recovery point is the most recent usable point in time represented by the successfully restored information.

---

# 102. RPO Measurement

RPO performance compares:

- Time of disruption or defined test reference point
- Actual recoverable data point

The difference represents data loss.

---

# 103. RPO Pass

RPO passes when actual data loss is equal to or less than the approved RPO.

---

# 104. RPO Failure

RPO fails when actual data loss exceeds the approved RPO.

---

# 105. RTO/RPO Example

A system has:

- RTO: 8 hours
- RPO: 4 hours

A recovery test produces:

- Recovery time: 11 hours 37 minutes
- Data loss: 58 minutes

Result:

| Requirement | Result |
|---|---|
| RTO | **Failed** |
| RPO | **Passed** |

The recovery capability has not fully met the business requirement.

---

# 106. Corrective Action Example

Following the failed RTO result, the recovery team may identify corrective actions such as:

- Improved recovery documentation
- Better configuration backups
- Faster access to required recovery media
- Removal of unnecessary manual steps
- Improved administrator cross-training
- Corrected dependency information

The actual corrective action must be based on the identified cause.

---

# 107. Retest Example

Following remediation, a later test produces:

- Recovery time: 6 hours 42 minutes
- Data loss: 47 minutes

Result:

| Requirement | Result |
|---|---|
| RTO | **Passed** |
| RPO | **Passed** |

The later test provides evidence that the tested recovery capability improved.

---

# 108. Test Failure

A recovery test is considered failed when defined success criteria are not achieved.

---

# 109. Partial Success

A test that meets some but not all required objectives must be recorded accurately.

Partial success must not be recorded as complete success.

---

# 110. Failed Test Record

A failed test should document:

- Requirement
- Expected result
- Actual result
- Failure
- Business impact
- Cause where known
- Corrective action
- Accountable owner
- Retest requirement

---

# 111. Failed Test Evidence

Failed recovery evidence must be preserved.

Failure is valuable assurance information.

---

# 112. No Backdating

Personnel must not backdate a recovery test to make testing frequency appear compliant.

---

# 113. No Invented Results

Personnel must not:

- Record an unperformed restore as completed.
- Change measured recovery time.
- Change measured data loss.
- Hide failed recovery attempts.
- Claim business validation that did not occur.
- Record an incomplete restore as fully successful.

---

# 114. Test Environment

Recovery testing should use a controlled environment where practical.

Testing must not unnecessarily endanger production systems or data.

---

# 115. Production Recovery Test

When a production recovery activity provides legitimate evidence of recovery capability, it may contribute to assurance if:

- Scope is documented.
- Actual results are recorded.
- RTO and RPO can be evaluated where applicable.
- Required validation occurs.

---

# 116. Production Event Is Not Automatically a Test

An operational recovery event should not automatically be treated as a complete recovery test if required test objectives were not evaluated.

---

# 117. Recovery Documentation Testing

Recovery documentation should periodically be tested by having a qualified IT professional unfamiliar with the specific system perform or follow the recovery process where practical.

---

# 118. Documentation Test Objective

The objective is to identify dependence on:

- Undocumented knowledge
- One employee
- One contractor
- Missing configuration
- Missing credentials
- Unclear recovery sequence

---

# 119. Recovery Credential Test

Recovery testing should confirm that required authorized credentials can be obtained when needed.

The test must not unnecessarily expose protected credentials.

---

# 120. Dependency Validation

Recovery testing should verify required dependencies rather than assuming they exist.

Examples include:

- Authentication
- Database
- DNS
- Network
- Application service
- File service
- Third-party service

---

# 121. Cloud Recovery Testing

Cloud-hosted recovery testing should evaluate:

- Backup availability
- Provider dependency
- Authentication
- Application recovery
- Data restoration
- Security configuration
- Business validation

as appropriate to scope.

---

# 122. Active Directory Recovery Testing

Active Directory testing should consider:

- Directory backup
- Recovery documentation
- Privileged access
- Directory integrity
- Authentication
- Dependent systems

---

# 123. Infinity Recovery Testing

Infinity recovery testing should consider:

- Web tier
- Application tier
- Database tier
- Source code
- Configuration
- Application data
- Authentication
- Required integrations
- Security controls
- Business transactions

---

# 124. Infinity Ownership

Dunder Mifflin owns the Infinity:

- Source code
- Repository
- Documentation
- Application data
- Intellectual property
- Contractor work product
- Backups

Recovery must not depend exclusively on the contractor possessing these assets.

---

# 125. Contractor Participation

A contractor may participate in recovery testing when authorized.

Contractor access must follow [[PROC-004 Contractor Access Procedure]] and applicable access controls.

---

# 126. Independent Recovery Capability

Where practical, testing should determine whether company-controlled documentation and assets permit recovery without exclusive dependence on one contractor.

---

# 127. Backup Resilience Against Production Compromise

Backup testing and architecture review should evaluate whether compromise of production systems could also compromise backup capability.

---

# 128. Backup Administrative Separation

Where practical, backup administrative access should not unnecessarily share the same trust path as ordinary user access.

---

# 129. Backup Exposure Review

Backup systems and media should be reviewed for unnecessary:

- Network exposure
- Administrative access
- Persistent connection
- Shared credentials

---

# 130. Backup Immutability Evaluation

Dunder Mifflin may evaluate technologies or processes that provide stronger resistance to backup alteration or deletion.

Such capability receives no current control credit until implemented and validated.

---

# 131. Recovery Exercise Coordination

Recovery tests may be coordinated with:

- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]
- [[PLN-001 Incident Response Plan]]

depending on scenario.

---

# 132. Business Continuity Integration

A technology recovery test may include business continuity validation when appropriate.

For example:

**System Outage → Manual Processing → System Recovery → Data Entry → Reconciliation → Verification**

---

# 133. Security Incident Integration

A recovery test involving cyber compromise should account for:

- Evidence preservation
- Containment
- Credential protection
- Trusted recovery source
- Security validation

---

# 134. Third-Party Backup Dependency

Third parties supporting backup or off-site storage must be managed under [[POL-008 Third-Party Security Policy]].

---

# 135. Off-Site Provider Review

The off-site backup-storage relationship should be reviewed for:

- Authorized custody
- Physical protection
- Media accountability
- Confidentiality
- Incident notification
- Return procedures

---

# 136. Provider Incident

A provider incident affecting backup media or recovery capability must be evaluated under [[PBK-005 Third-Party Incident Playbook]] when security-related.

---

# 137. Lost Backup Media

Lost backup media requires evaluation of:

- Encryption status
- Information classification
- Last known custody
- Unauthorized-access possibility
- Incident classification
- Notification requirements

---

# 138. Backup Media Theft

Suspected backup-media theft must be escalated as a security event.

Encryption status is an important factor but does not eliminate the need to investigate custody loss.

---

# 139. Backup Data Confidentiality

Backup data inherits the highest applicable classification of the information contained within the backup.

---

# 140. Backup Data Integrity

Backup integrity must be sufficient to support reliable restoration.

Unexpected integrity failures require investigation.

---

# 141. Backup Availability

Backup availability includes the ability to obtain:

- Media
- Backup data
- Credentials
- Software
- Documentation
- Required infrastructure

when recovery is needed.

---

# 142. Recovery Records

Recovery records should identify:

- Request
- Authorization
- System
- Recovery source
- Recovery point
- Start time
- Completion time
- Validation
- Exceptions
- Personnel

---

# 143. Test Records

Formal recovery-test records should identify:

- Test date
- Scope
- RTO
- RPO
- Recovery source
- Actual recovery time
- Actual recovery point
- Pass/fail results
- Validation
- Findings
- Corrective actions
- Retest requirement

---

# 144. Evidence Protection

Backup and recovery evidence must be protected from unauthorized alteration.

---

# 145. Evidence Retention

Evidence must be retained sufficiently to support:

- Operational review
- Management reporting
- Assurance
- Findings
- Corrective action
- Risk reassessment

---

# 146. Finding Definition

A finding is a documented conclusion supported by evidence concerning whether a requirement, control, process, or expected outcome was satisfied.

A finding may indicate:

- Satisfactory performance
- Partial performance
- Deficiency
- Control failure
- Recovery failure

---

# 147. Material Findings

Material findings may include:

- Critical backup failure
- Missing required backup coverage
- Unrecoverable backup
- RTO failure
- RPO failure
- Missing recovery documentation
- Failed recovery validation
- Unavailable recovery credentials
- Repeated backup failure
- Backup media custody failure

---

# 148. Corrective Action Register

Material deficiencies and corrective actions must be tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 149. Corrective Action Requirements

A corrective action should identify:

- Finding
- Required action
- Accountable owner
- Due date
- Validation method
- Retest requirement where applicable

---

# 150. Remediation Does Not Equal Closure

A corrective action reported as implemented is not automatically closed.

Required validation must determine whether the deficiency was corrected.

---

# 151. Retesting

Material recovery deficiencies should be retested after corrective action.

Retesting should address the condition that originally failed.

---

# 152. Failed Retest

A failed retest must remain open or be reclassified appropriately.

The result must not be concealed by initiating another corrective-action record without preserving the failed result.

---

# 153. Repeated Failure

Repeated failure may indicate:

- Ineffective remediation
- Incorrect root cause
- Inadequate resources
- Poor documentation
- Architectural limitation
- Unrealistic recovery design

Repeated material failure requires management escalation.

---

# 154. Risk Reassessment

Validated recovery evidence may support reassessment of related risks.

---

# 155. Current Residual Risk

Current residual risk reflects controls actually operating at the time of assessment.

A planned recovery improvement does not reduce current residual risk.

---

# 156. Target Residual Risk

Target residual risk represents expected risk after planned treatment.

It is a prediction.

---

# 157. Post-Treatment Risk

After recovery improvements are implemented and validated, risk may be reassessed.

Actual post-treatment risk may be:

- Higher than target
- Equal to target
- Lower than target

---

# 158. Historical Integrity

The original risk assessment must remain preserved.

Later evidence may establish a new current residual risk without rewriting the historical assessment.

---

# 159. R027 Backup / Recovery Failure

R027 has:

- Inherent risk: **20 Critical**
- Current residual risk: **12 High**
- Target residual risk: **5 Moderate**

---

# 160. R027 Treatment Relationship

This procedure directly supports R027 treatment through:

- Backup monitoring
- Backup coverage validation
- Encrypted external-drive rotation
- Off-site separation
- Quarterly representative restore testing
- Annual Critical recovery testing
- Recovery documentation
- Backup administrative protection
- Failed-test remediation
- Retesting

---

# 161. R028 Data Corruption

R028 has:

- Inherent risk: **16 High**
- Current residual risk: **9 Moderate**
- Target residual risk: **4 Low**

Validated backups provide a recovery mechanism when trustworthy data must be restored.

---

# 162. R003 Ransomware

R003 has:

- Inherent risk: **25 Critical**
- Current residual risk: **12 High**
- Target residual risk: **6 Moderate**

Backup resilience is an important part of ransomware recovery but does not prevent ransomware itself.

---

# 163. R013 Administrative / Configuration Error

R013 has:

- Inherent risk: **16 High**
- Current residual risk: **12 High**
- Target residual risk: **6 Moderate**

Configuration backups and validated restoration may reduce the operational impact of significant configuration errors.

---

# 164. R016 Cloud Outage

R016 has:

- Inherent risk: **15 High**
- Current residual risk: **8 Moderate**
- Target residual risk: **6 Moderate**

Independent recovery information and backups support recovery when normal cloud capability is unavailable.

---

# 165. R026 Personnel Loss

R026 has:

- Inherent risk: **16 High**
- Current residual risk: **9 Moderate**
- Target residual risk: **4 Low**

Documented recovery procedures reduce dependence on individual knowledge.

---

# 166. R033 Manual Outage Processing Error

R033 has:

- Inherent risk: **12 High**
- Current residual risk: **9 Moderate**
- Target residual risk: **4 Low**

Recovery must coordinate with manual transaction reconciliation after outages.

---

# 167. R034 Loss of Headquarters

R034 has:

- Inherent risk: **10 High**
- Current residual risk: **8 Moderate**
- Target residual risk: **4 Low**

Off-site backup storage and cloud-hosted systems reduce dependence on Headquarters.

---

# 168. R035 Regional Disaster

R035 has:

- Inherent risk: **9 Moderate**
- Current residual risk: **6 Moderate**
- Target residual risk: **5 Moderate**

Geographically separated recovery resources support regional resilience.

---

# 169. Control Effectiveness

Backup and recovery evidence may support conclusions that controls are:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

---

# 170. Effectiveness Evidence

Control-effectiveness conclusions should consider:

- Backup success
- Backup coverage
- Restore success
- RTO
- RPO
- Documentation
- Security
- Repeat failures
- Corrective-action results

---

# 171. Backup Metrics

Metrics may include:

- Backup-job success rate
- Backup failures
- Repeated backup failures
- Backup coverage exceptions
- Missing off-site media
- Restore tests completed
- Restore-test success rate
- Critical recovery tests completed
- RTO pass rate
- RPO pass rate
- Open recovery findings
- Overdue corrective actions

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 172. Key Performance Indicators

Key Performance Indicators (KPIs) may include:

- Percentage of scheduled backups completed successfully
- Percentage of quarterly representative restore tests completed
- Percentage of Critical systems receiving annual meaningful recovery testing
- Percentage of recovery tests meeting RTO
- Percentage of recovery tests meeting RPO
- Percentage of recovery corrective actions validated

---

# 173. Key Risk Indicators

Key Risk Indicators (KRIs) may include:

- Critical backup failure
- Repeated backup failure
- Failed Critical restore
- RTO failure
- RPO failure
- Unrecoverable backup
- Unknown backup coverage
- Missing backup media
- Critical recovery finding overdue
- Backup administrative compromise

---

# 174. Reporting

Backup and recovery information should support:

**Operational Reporting**
- Backup status
- Failed jobs
- Media rotation
- Restore activity
- Immediate exceptions

**Management Reporting**
- Trends
- Recovery-test results
- RTO/RPO performance
- Corrective actions
- Significant gaps

**Executive Reporting**
- Material recovery risk
- Critical recovery failure
- Significant resilience gap
- Required risk decision

---

# 175. Escalation

Material backup or recovery failures must be escalated according to business and security impact.

Security-related events also follow [[PROC-010 Security Event Escalation Procedure]].

---

# 176. Assessment

Backup and recovery controls are subject to assurance under [[PRO-008 Security Assurance & Continuous Improvement Program]].

---

# 177. Assessment Methods

Assessment may use:

- Inspection
- Observation
- Interviews
- Sampling
- Technical Testing
- Exercises
- Reconciliation
- Independent Performance

---

# 178. Independent Performance

An assessor may independently perform selected authorized recovery activities.

For example:

1. Select a backup.
2. Identify the applicable system.
3. Identify its RTO and RPO.
4. Retrieve required recovery documentation.
5. Restore selected data or a controlled system.
6. Measure recovery time.
7. Determine the recovery point.
8. Validate recovered information.
9. Compare results with requirements.
10. Document the conclusion.

---

# 179. Assessment Work Plan

Formal assurance activities should be defined through an Assessment Work Plan when appropriate.

The work plan should identify:

- Control or requirement
- Objective
- Scope
- Evidence
- Assessment method
- Sample
- Expected result
- Actual result
- Conclusion

The standard template is [[TMP-001 Assessment Work Plan Template]].

---

# 180. Current and Proposed Controls

Backup and recovery documentation must distinguish among:

- Current controls
- Partially implemented controls
- Planned controls
- Implemented controls awaiting validation
- Validated controls

---

# 181. No Premature Risk Credit

Current residual risk must not be reduced merely because:

- A backup is scheduled.
- A new backup method is proposed.
- Additional media has been purchased.
- A restore test is planned.
- A corrective action is assigned.
- A recovery improvement is documented.

Risk reduction requires implementation and appropriate validation.

---

# 182. Procedure Exceptions

Exceptions to this procedure must be:

- Documented
- Justified
- Risk evaluated
- Approved under appropriate authority
- Time-limited where practical
- Reviewed when conditions change

---

# 183. Procedure Maintenance

This procedure must be reviewed when material changes affect:

- Backup architecture
- Recovery architecture
- Cloud hosting
- Critical systems
- BIA requirements
- External media rotation
- Off-site storage
- Recovery testing
- Security requirements

---

# 184. Traceability

This procedure supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Backup existence alone does not complete this chain.

Validated recovery provides the evidence required to determine whether the control achieves its intended result.

---

# 185. Related Artifacts

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
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-009 Malware Response Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-013 Manual Processing Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]
- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[TMP-001 Assessment Work Plan Template]]

---

# 186. Review

This procedure must be reviewed:

- At least annually
- Following material backup architecture change
- Following material recovery architecture change
- Following significant BIA change
- Following significant cloud-provider change
- Following material recovery failure
- Following significant recovery-test findings

The IT & Information Security Manager coordinates review.

Material revisions require CIO approval.

---

# 187. Revision History

| Version | Date     | Description                         | Approval |
| ------- | -------- | ----------------------------------- | -------- |
| 1.0     | May 2013 | Initial Backup & Recovery Procedure | CIO      |