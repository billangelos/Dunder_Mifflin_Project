# POL-010 Business Continuity & Disaster Recovery Policy

## Document Control

| Field | Value |
|---|---|
| Document ID | POL-010 |
| Title | Business Continuity & Disaster Recovery Policy |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | COO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Business, Technology, or Recovery Change |

---

# 1. Purpose

This policy establishes Dunder Mifflin's requirements for Business Continuity/Disaster Recovery (BC/DR).

BC/DR must provide reasonable capability to:

- Protect human life and safety.
- Continue essential business functions during disruption.
- Recover critical technology and information.
- Restore business operations according to approved priorities.
- Protect information during alternate processing.
- Coordinate business and technical recovery.
- Maintain recovery documentation.
- Validate recovery capability through testing and exercises.
- Improve resilience following incidents, exercises, and significant changes.

Recovery requirements must be based on business need rather than arbitrary technical targets.

---

# 2. Scope

This policy applies to:

- Headquarters
- Branch offices
- Warehouses
- Business processes
- Information Technology
- Applications
- Cloud-hosted systems
- Networks
- Endpoints
- Communications
- Information
- Backups
- Suppliers
- Technology providers
- Contractors
- Personnel dependencies
- Physical facilities
- Transportation dependencies
- Other resources required to continue or recover significant business operations

---

# 3. Objectives

The BC/DR program must:

1. Protect life and safety.
2. Identify critical business requirements.
3. Establish business-approved recovery objectives.
4. Maintain continuity strategies.
5. Maintain technical recovery capability.
6. Protect required recovery information.
7. Maintain usable recovery documentation.
8. Provide manual alternatives where practical.
9. Address significant third-party dependencies.
10. Test backup restoration.
11. Exercise recovery and continuity plans.
12. Identify deficiencies.
13. Track corrective action.
14. Reassess risk when recovery capability materially changes.

---

# 4. Safety Priority

Human life and safety take priority over:

- Systems
- Operations
- Facilities
- Equipment
- Inventory
- Information
- Revenue
- Other company assets

Personnel must not remain in or enter an unsafe location solely to:

- Maintain business operations
- Protect equipment
- Preserve inventory
- Recover information
- Perform technical recovery
- Preserve evidence

Emergency authorities and first responders take precedence when applicable.

---

# 5. Business Continuity and Disaster Recovery

Business Continuity (BC) and Disaster Recovery (DR) are related but distinct.

## Business Continuity

Business Continuity focuses on maintaining or restoring required business functions during disruption.

## Disaster Recovery

Disaster Recovery focuses primarily on restoring technology, information, and supporting infrastructure required by business functions.

Technology recovery must support business continuity requirements rather than establish them independently.

---

# 6. Business Impact Analysis

Dunder Mifflin must maintain a Business Impact Analysis (BIA).

The BIA must identify, as appropriate:

- Business functions
- Criticality
- Dependencies
- Maximum Tolerable Downtime
- Recovery Time Objective
- Recovery Point Objective
- Manual alternatives
- Supporting systems
- Significant personnel dependencies
- Third-party dependencies

The approved BIA is maintained in [[RPT-002 Business Impact Analysis]].

---

# 7. Maximum Tolerable Downtime

Maximum Tolerable Downtime (MTD) identifies the longest period a business function can remain unavailable before the resulting business impact becomes unacceptable.

MTD is a business requirement.

Technology recovery must not establish an RTO that exceeds the MTD of the business function it supports without documented business acceptance.

---

# 8. Recovery Time Objective

Recovery Time Objective (RTO) identifies the targeted time within which a business function or supporting capability should be restored following disruption.

RTO must be based on:

- Business impact
- Dependencies
- Available alternatives
- Operational requirements
- Approved recovery strategy

RTO must not be selected solely because a technology platform can technically recover within a particular period.

---

# 9. Recovery Point Objective

Recovery Point Objective (RPO) identifies the maximum targeted amount of data loss measured in time.

RPO must be based on:

- Business transaction requirements
- Information criticality
- Reconciliation capability
- Manual records
- Backup capability
- Business tolerance for data loss

Backup schedules must be evaluated against applicable RPO requirements.

---

# 10. Recovery Objectives and Technology

Information Technology must design recovery capability to support approved business recovery requirements.

The sequence is:

**Business Requirement → Criticality → MTD → RTO/RPO → Recovery Strategy → Technical Design → Implementation → Testing**

Technical capability must not silently redefine business requirements.

---

# 11. Recovery Priorities

Recovery priority is:

1. Human life and safety
2. Critical business functions and supporting capabilities
3. High business functions and supporting capabilities
4. Moderate business functions and supporting capabilities
5. Low business functions and supporting capabilities

Dependencies may require supporting technology to be recovered before the business function it enables.

---

# 12. Supporting Systems

Supporting systems must be recovered according to the requirements of the business functions they support, as applicable.

Shared infrastructure may require earlier recovery when multiple higher-priority functions depend upon it.

Examples may include:

- Internet connectivity
- Active Directory
- Email
- File services
- Network infrastructure

Recovery sequencing must consider dependencies rather than system names alone.

---

# 13. Recovery Strategies

Recovery strategies must be proportionate to:

- Business criticality
- Recovery objectives
- Risk
- Cost
- Operational feasibility
- Existing architecture
- Available alternatives

Possible strategies include:

- Cloud recovery
- Backup restoration
- Replacement equipment
- Manual processing
- Alternate communications
- Personnel relocation
- Use of unaffected branches
- Alternate suppliers
- Temporary work arrangements

Not every system requires a dedicated alternate facility or continuously operating alternate environment.

---

# 14. Business Continuity Plan

Dunder Mifflin must maintain [[PLN-002 Business Continuity Plan]].

The plan must address:

- Activation
- Roles
- Communications
- Business priorities
- Manual continuity
- Personnel
- Facilities
- Suppliers
- Alternate work arrangements
- Return to normal operations

The plan must be understandable by personnel responsible for continuity activities.

---

# 15. Disaster Recovery Plan

Dunder Mifflin must maintain [[PLN-003 Disaster Recovery Plan]].

The plan must address:

- Activation
- Technical recovery priorities
- Dependencies
- Recovery responsibilities
- Required configurations
- Backup restoration
- Validation
- Escalation
- Return to normal operations

Recovery documentation must be sufficient for a qualified Information Technology professional unfamiliar with the environment to perform required recovery activities.

---

# 16. Recovery Documentation

Recovery documentation must identify information necessary to restore significant technology and business capability.

Documentation may include:

- System dependencies
- Recovery sequence
- Configuration information
- Required software
- Required services
- Backup locations
- Provider contacts
- Administrative requirements
- Validation steps
- Escalation contacts

Documentation must be maintained separately from the systems it is intended to recover where practical.

---

# 17. Recovery Documentation Availability

Recovery documentation must remain available when normal systems are unavailable.

Dunder Mifflin must maintain:

- Accessible electronic recovery documentation
- Two controlled printed recovery binders containing information required when electronic documentation is unavailable

Printed copies must be reviewed and updated when material recovery information changes.

---

# 18. Recovery Documentation Protection

Recovery documentation may contain sensitive information concerning:

- Systems
- Networks
- Administrative processes
- Providers
- Configurations
- Security controls

Documentation must be protected according to [[POL-004 Information Classification & Handling Policy]].

Authentication secrets should not be unnecessarily embedded in general recovery documentation.

---

# 19. Change Management and Recovery

Significant technology or configuration changes must include review of applicable recovery documentation.

A significant change is not complete until applicable recovery documentation has been:

- Reviewed,
- Updated where required, or
- Identified for explicit corrective action when immediate update is not practical.

Requirements are established in [[POL-007 Change & Configuration Management Policy]].

---

# 20. Backup Program

Dunder Mifflin must maintain backup capability appropriate to business and recovery requirements.

Backup strategy must consider:

- Information
- Applications
- Configuration
- Recovery objectives
- Retention
- Geographic separation
- Encryption
- Administrative access
- Restoration capability

Backups exist to support recovery and must not be treated merely as an archival activity.

---

# 21. Automated and Cloud Backups

Significant systems must use automated or cloud-based backup capability where appropriate.

Backup jobs must be monitored sufficiently to identify material failures.

A successful backup job does not independently prove that information can be restored.

---

# 22. External Hard-Drive Rotation

Dunder Mifflin maintains encrypted external hard-drive backup rotation for each of its seven facilities.

Each facility has three encrypted external backup drives.

This provides:

**7 facilities × 3 drives = 21 encrypted external backup drives**

The rotation provides geographically separated recovery copies in addition to other backup capability.

---

# 23. Off-Site Backup Rotation

Each Friday, the current facility backup drive is transferred to the approved off-site disaster-recovery storage provider.

The provider normally retains the two most recent weekly generations for each facility.

This results in approximately:

**7 facilities × 2 off-site generations = 14 encrypted drives stored off site**

When a new generation arrives:

1. The new drive is accepted into off-site storage.
2. The two most recent generations are retained.
3. The oldest generation is returned for continued rotation.

Backup media must remain encrypted throughout the rotation.

---

# 24. Backup Media Protection

Backup media must be protected against:

- Unauthorized access
- Theft
- Loss
- Physical damage
- Unnecessary exposure

Protection must include, as applicable:

- Encryption
- Controlled custody
- Secure storage
- Geographic separation
- Access restriction

Backups inherit the highest information classification represented within them.

---

# 25. Backup Administrative Access

Administrative access to backup systems must be restricted according to least privilege.

Backup administration must be protected from unnecessary dependency on ordinary production credentials where practical.

The organization must evaluate whether compromise of production systems could also compromise backup capability.

---

# 26. Backup Coverage

Backup coverage must be evaluated against:

- [[REG-001 Enterprise Asset Register]]
- [[STD-001 Information Classification Standard]]
- [[RPT-002 Business Impact Analysis]]

The review must determine whether information and systems requiring recovery are actually included in the backup program.

Assuming that a system is backed up is not sufficient.

---

# 27. Restore Testing

Dunder Mifflin must perform representative backup restoration testing at least quarterly.

Testing must demonstrate actual restoration capability.

Representative testing should cover different:

- Systems
- Data types
- Backup methods
- Recovery scenarios

The same simple file restoration must not be used indefinitely as the sole evidence that enterprise recovery capability works.

---

# 28. Critical Recovery Testing

Critical systems and services must receive a meaningful recovery test at least annually.

Testing should evaluate:

- Restoration
- Dependencies
- Configuration
- Authentication
- Data integrity
- RTO
- RPO where measurable
- Recovery documentation
- Personnel capability

A successful technical restoration does not automatically mean business recovery objectives were achieved.

---

# 29. Recovery Test Measurement

Recovery testing must compare actual results with approved recovery objectives.

For example, if a service has:

- RTO: 8 hours
- RPO: 4 hours

and a recovery test produces:

- Actual recovery time: 11 hours 37 minutes
- Actual data loss: 58 minutes

the result is:

- RTO: **Failed**
- RPO: **Passed**

The test must not be reported simply as successful because the system eventually returned to service.

---

# 30. Recovery Improvement

If a later test of the same service produces:

- Actual recovery time: 6 hours 42 minutes
- Actual data loss: 47 minutes

the result is:

- RTO: **Passed**
- RPO: **Passed**

The later successful test provides evidence of improved recovery capability.

It does not erase the earlier failed test from historical records.

---

# 31. Recovery Test Records

Recovery tests must document:

- System or service
- Test date
- Test scope
- Recovery objective
- Participants
- Recovery method
- Start time
- Restoration time
- Data-loss measurement where applicable
- Validation performed
- Problems encountered
- Findings
- Corrective actions

Test records must represent actual results.

---

# 32. Recovery Test Failure

Failure to meet an RTO or RPO must be evaluated as a potential control deficiency.

The review must determine:

- Cause
- Business impact
- Affected risk
- Required corrective action
- Need for retesting
- Whether recovery strategy remains appropriate

A failed test must not be converted into a passing result by changing the recovery objective after the test without appropriate business analysis and authorization.

---

# 33. Manual Continuity

Business functions requiring continued operation during system outages must maintain manual alternatives where practical.

Manual continuity may use:

- Paper forms
- Offline records
- Telephone
- Company-issued mobile phones
- Temporary spreadsheets where appropriately controlled
- Other approved methods

Manual processing must remain controlled.

---

# 34. Manual Processing Lifecycle

Manual continuity must follow:

**Collect → Review → Enter → Reconcile → Verify**

This lifecycle ensures that transactions created during an outage are appropriately incorporated into restored systems.

Detailed requirements are established in [[PROC-013 Manual Processing Procedure]].

---

# 35. Manual Records

Manual records should identify, as appropriate:

- Customer
- Order
- Employee
- Transaction
- Date
- Time
- Responsible person
- Required approval

Records must be sufficiently complete to support later reconciliation.

---

# 36. Reconciliation

After system restoration, manually processed transactions must be reconciled.

Reconciliation must identify:

- Missing transactions
- Duplicate transactions
- Incorrect transactions
- Incomplete transactions
- Transactions entered into the restored system

Material discrepancies must be investigated.

---

# 37. Order Processing Continuity

When normal order-processing systems are unavailable, personnel may use approved manual methods to record customer orders.

Manual order records must contain sufficient information to support:

- Customer identification
- Order fulfillment
- Later system entry
- Reconciliation
- Verification

Manual continuity does not guarantee normal processing speed.

---

# 38. Warehouse Continuity

Warehouses must maintain practical manual capability for essential operations during significant system outages.

Paper order slips or other approved records may support temporary operations.

Warehouse personnel must preserve individual accountability for significant transactions where practical.

---

# 39. Sales Continuity

Sales personnel may continue appropriate business activity using:

- Company laptops where functional
- Company-issued mobile phones
- Cellular connectivity where available
- Approved manual records

Continuity capability depends on the nature and geographic scope of the disruption.

---

# 40. Internet Connectivity Continuity

Loss of a facility's primary wired Internet service must be addressed through reasonable alternate connectivity where applicable.

Company-issued cellular capability may provide a secondary Internet path for:

- Management
- Sales
- Selected business functions

Cellular connectivity is not assumed to provide full replacement capacity for all warehouse or branch operations.

---

# 41. Communications

Continuity plans must identify alternate communication methods where practical.

Methods may include:

- Company-issued mobile phones
- Cellular data
- Telephone
- Alternate email access
- Contact lists
- In-person coordination

Personal phones may be used for emergency safety and contact purposes when necessary.

Routine business continuity should use company-provided communications where available.

---

# 42. Utility Disruption

Facilities must maintain continuity procedures appropriate to disruption of:

- Electrical power
- Heating
- Cooling
- Other material utilities

Critical network equipment and selected management and Sales workstations are supported by Uninterruptible Power Supply (UPS) capability providing approximately 30 minutes of temporary power.

UPS capability is intended primarily to support:

- Short disruptions
- Orderly shutdown
- Limited continuity

It is not a substitute for long-duration power generation.

---

# 43. Generator Strategy

Dunder Mifflin does not maintain dedicated generators as a general facility baseline.

Generator acquisition or other long-duration power capability should be considered when justified by:

- Business Impact Analysis
- Risk
- Outage experience
- Facility requirements
- Cost

Technology must not be acquired solely because it is commonly associated with disaster recovery.

---

# 44. Facility Loss

Continuity planning must address temporary or extended loss of a facility.

Strategies may include:

- Remote work
- Temporary relocation
- Use of unaffected branches
- Company laptops
- Company-issued mobile connectivity
- Manual processing
- Redistribution of work
- Alternate suppliers
- Alternate shipping arrangements

The strategy must reflect the facility's actual business role.

---

# 45. Headquarters Loss

Loss of headquarters must not automatically be treated as loss of Dunder Mifflin's primary data center because major company systems are cloud hosted.

Headquarters continuity must address:

- Management coordination
- Information Technology personnel
- Business administration
- Communications
- Recovery documentation
- Alternate work arrangements
- Delegated authority
- Personnel availability

The six branch locations provide geographic distribution of company operations.

---

# 46. Branch Loss

Loss of a branch must be addressed through strategies appropriate to:

- Sales
- Warehouse operations
- Inventory
- Shipping
- Customer service
- Personnel
- Local communications

Other branches may support affected operations where practical.

---

# 47. Regional Disaster

Continuity planning must consider disruption affecting multiple facilities or a broader geographic region.

Strategies may include:

- Geographic distribution of facilities
- Cloud-hosted systems
- Geographically separated backups
- Alternate communications
- Unaffected branches
- Supplier alternatives
- Transportation alternatives
- Personnel reassignment
- Manual continuity

Safety and personnel accountability remain the first priority.

---

# 48. Personnel Continuity

Critical business functions must identify significant personnel dependencies.

Continuity planning should reduce unnecessary dependence on a single individual through:

- Documentation
- Cross-training
- Alternate personnel
- Delegated authority
- Emergency access
- Knowledge transfer

Dunder Mifflin must retain control of critical company information, credentials, configurations, source code, and recovery information.

---

# 49. Succession and Delegated Authority

Continuity plans must identify appropriate decision authority when normal responsible personnel are unavailable.

Delegated authority may be required for:

- Business decisions
- Recovery activation
- Financial decisions
- Technology recovery
- Third-party escalation
- Emergency access

Authority must remain appropriate to the decision.

---

# 50. Third-Party Continuity

Critical and Important third-party relationships must be evaluated for continuity implications.

Considerations include:

- Provider outage
- Provider recovery
- Escalation
- Data availability
- Replacement
- Manual alternatives
- Contract commitments
- Concentration risk

Requirements are established in [[POL-008 Third-Party Security Policy]].

---

# 51. Cloud Service Continuity

Cloud-hosted systems must have continuity strategies appropriate to business dependency.

Strategies may include:

- Provider recovery
- Dunder Mifflin backups
- Manual processing
- Recovery documentation
- Data export
- Provider escalation
- Emergency migration

Cloud hosting does not eliminate continuity risk.

---

# 52. Cloud Exit and Emergency Migration

Dunder Mifflin must maintain [[PLN-004 Cloud Exit & Emergency Migration Plan]].

The plan must address:

- Provider failure
- Extended outage
- Service termination
- Data access
- Data export
- Configuration
- Authentication
- Application dependencies
- Replacement hosting
- Recovery priorities

Dunder Mifflin is not required to maintain a continuously operating alternate cloud environment unless justified by business requirements.

---

# 53. Supplier Continuity

Significant supplier dependencies must be evaluated.

Operations should consider:

- Alternate suppliers
- Available inventory
- Replacement lead time
- Transportation
- Geographic concentration
- Communication
- Product substitution where appropriate

Supplier continuity must support business requirements without assuming every supplier requires a dedicated alternate.

---

# 54. Transportation Continuity

Continuity planning must consider material transportation disruption affecting:

- Receiving
- Shipping
- Customer delivery
- Supplier delivery
- Inventory movement

Alternative arrangements should be evaluated where practical.

---

# 55. Recovery Activation

BC/DR plans must define activation authority.

Activation decisions should consider:

- Safety
- Expected outage duration
- Business impact
- Affected facilities
- Affected systems
- Available alternatives
- Recovery requirements

Not every incident requires formal BC/DR activation.

---

# 56. Incident Response Coordination

Business continuity and disaster recovery must coordinate with incident response.

A security incident may require:

- Incident containment
- Business continuity
- Disaster recovery
- All three simultaneously

Incident response requirements are established in [[POL-009 Incident Response Policy]] and [[PLN-001 Incident Response Plan]].

---

# 57. Crisis Communications

Significant disruptions must have coordinated communications.

Communications should identify:

- Known conditions
- Business impact
- Safety information
- Actions underway
- Employee instructions
- Management decisions
- Expected next update

Unverified information must be identified as such.

---

# 58. Personnel Accountability

During significant facility or regional emergencies, management must account for affected personnel where practical.

Safety-related personnel accountability takes priority over business recovery.

Personnel must follow applicable emergency instructions.

---

# 59. Return to Normal Operations

BC/DR plans must address transition from continuity operations back to normal operations.

The process should consider:

- System validation
- Data reconciliation
- Manual transaction entry
- Facility readiness
- Personnel communication
- Outstanding work
- Temporary access
- Temporary controls
- Recovery documentation

Return to normal operation must be controlled.

---

# 60. Temporary Controls

Temporary controls established during recovery must be:

- Documented where material
- Limited to the disruption where practical
- Reviewed for continued need
- Removed or formally approved when normal operations resume

Emergency conditions must not create permanent undocumented security exceptions.

---

# 61. Exercises

Business continuity and disaster recovery capability must be exercised periodically.

Exercises may include:

- Tabletop exercises
- Manual-processing exercises
- Communications exercises
- Backup restoration
- Technical recovery
- Facility-loss scenarios
- Third-party scenarios

Exercise complexity must remain proportionate to risk.

---

# 62. Exercise Objectives

Exercises must have defined objectives.

Objectives may include:

- Validate roles
- Validate communication
- Validate manual procedures
- Validate recovery documentation
- Validate dependencies
- Measure recovery time
- Identify missing information
- Identify control deficiencies

An exercise is not successful merely because it was completed.

---

# 63. Exercise Records

Exercise records should identify:

- Scenario
- Scope
- Date
- Participants
- Objectives
- Actions
- Actual results
- Problems
- Findings
- Corrective actions

Records must reflect actual performance.

---

# 64. Recovery Evidence

BC/DR evidence may include:

- Backup records
- Backup-job reports
- Off-site rotation records
- Restore-test records
- Recovery-test results
- Exercise records
- Manual-processing records
- Updated recovery documentation
- Provider recovery information
- Corrective-action records

Evidence must represent actual activity.

---

# 65. Findings

Material BC/DR deficiencies must be documented.

Examples include:

- Failed restore
- RTO not achieved
- RPO not achieved
- Missing backup coverage
- Missing recovery documentation
- Outdated recovery instructions
- Unusable manual procedure
- Missing dependency
- Inadequate third-party recovery information
- Recovery capability dependent on unavailable personnel

Material corrective actions must be tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 66. Corrective Action

Corrective action must identify, as appropriate:

- Finding
- Affected business function
- Affected system
- Affected control
- Associated risk
- Responsible party
- Required remediation
- Due date
- Expected evidence
- Retest requirement

Corrective action must remain open until required remediation and validation are complete.

---

# 67. Retesting

Material recovery deficiencies must be retested when necessary to demonstrate that corrective action works.

Closing a corrective action based solely on a statement that the issue was fixed is insufficient when technical or operational validation is reasonably required.

---

# 68. Risk Reassessment

Material BC/DR findings must be evaluated to determine whether affected risks require reassessment.

Examples include:

- Backup failure
- Recovery test failure
- Unexpected provider dependency
- Inability to meet recovery objectives
- Loss of alternate capability
- Significant personnel dependency
- New geographic concentration

Risk reassessment must follow [[POL-005 Risk Management Policy]].

---

# 69. Recovery Metrics

BC/DR metrics may include:

- Backup-job success
- Backup failures
- Quarterly restore tests completed
- Restore-test pass rate
- Critical annual recovery tests completed
- RTO achievement
- RPO achievement
- Open recovery findings
- Overdue corrective actions
- Recovery documentation review status
- Exercise completion
- Manual-processing exercise results

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 70. Metric Interpretation

Recovery metrics must be interpreted in context.

For example:

- A successful backup job does not prove successful restoration.
- A successful restoration does not prove the RTO was achieved.
- Meeting RTO does not prove the RPO was achieved.
- Completing an exercise does not prove the plan worked.
- One successful test does not prove every recovery scenario will succeed.

Management must consider the evidence supporting each conclusion.

---

# 71. Assessment

BC/DR controls must be periodically assessed.

Assessment may include:

- Inspection
- Observation
- Sampling
- Independent Performance
- Technical Testing
- Exercises
- Reconciliation
- Review of recovery evidence

Assessment must evaluate actual capability rather than documentation alone.

---

# 72. Evidence Integrity

Personnel must not:

- Manufacture backup records.
- Record restore tests that did not occur.
- Alter recovery times to show RTO compliance.
- Conceal failed recovery tests.
- Record exercises as successful without supporting results.
- Represent planned recovery capability as implemented.

Failed recovery activities must be documented and addressed.

---

# 73. Risk Relationships

This policy provides significant treatment support for risks including:

- R003 Ransomware
- R016 Cloud Service Outage
- R017 Internet Service Provider Outage
- R018 Third-Party Technology Failure / Compromise
- R020 Supplier Disruption
- R021 Fire
- R022 Water Damage
- R023 Utility / Power / HVAC Failure
- R025 Vehicle / Transportation Incident
- R026 Key Personnel Loss
- R027 Backup / Recovery Failure
- R028 Data Corruption
- R033 Manual Outage Processing Error
- R034 Loss of Headquarters
- R035 Regional Disaster

Risk treatment is documented in [[RTP-001 Enterprise Risk Treatment Plan]].

---

# 74. Exceptions

Exceptions to this policy require:

- Documented business justification
- Affected requirement
- Associated risk
- Defined duration
- Compensating controls where practical
- Responsible owner
- Appropriate approval

High or Critical residual risk resulting from an exception requires escalation according to [[POL-005 Risk Management Policy]].

Emergency actions necessary to protect life and safety do not require advance exception approval.

---

# 75. Enforcement

Failure to comply with this policy may result in:

- Corrective action
- Management review
- Risk escalation
- Access restriction
- Personnel action
- Contractual action
- Other appropriate management action

Intentional concealment of material recovery deficiencies must be escalated.

---

# 76. Policy Review

This policy must be reviewed:

- At least annually
- Following significant business change
- Following significant technology change
- Following material recovery failure
- Following significant continuity activation
- Following major exercises
- Following significant assessment findings
- When BIA requirements materially change

The COO coordinates business review with the CIO and applicable business owners.

Material revisions require CEO approval.

---

# 77. Traceability

Business continuity and disaster recovery must support the enterprise security lifecycle:

**Business Requirement → BIA → MTD/RTO/RPO → Recovery Strategy → Control → Procedure → Implementation → Exercise/Test → Evidence → Finding → Corrective Action → Retest → Risk Reassessment**

Detailed relationships are maintained through [[REG-007 Cross-Reference Matrix]].

---

# 78. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-009 Security Governance Framework]]
- [[POL-001 Information Security Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-011 Physical & Environmental Security Policy]]
- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[RPT-002 Business Impact Analysis]]
- [[REG-001 Enterprise Asset Register]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-013 Manual Processing Procedure]]
- [[TMP-003 Recovery Test Template]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[REG-007 Cross-Reference Matrix]]

---

# 79. Revision History

| Version | Date     | Description                                            | Approval |
| ------- | -------- | ------------------------------------------------------ | -------- |
| 1.0     | May 2013 | Initial Business Continuity & Disaster Recovery Policy | CEO      |