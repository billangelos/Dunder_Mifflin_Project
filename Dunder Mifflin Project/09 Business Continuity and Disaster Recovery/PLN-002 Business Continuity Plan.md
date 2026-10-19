# PLN-002 Business Continuity Plan

## Document Control

| Field | Value |
|---|---|
| Document ID | PLN-002 |
| Title | Business Continuity Plan |
| Version | 1.0 |
| Classification | Confidential |
| Status | Approved |
| Owner | COO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Business, Technology, Facility, or Recovery Change |

---

# 1. Purpose

This Business Continuity Plan (BCP) establishes how Dunder Mifflin maintains or restores essential business operations during significant disruption.

The plan translates the requirements established by [[RPT-002 Business Impact Analysis]] into coordinated continuity actions for:

- Personnel
- Business processes
- Facilities
- Technology
- Communications
- Suppliers
- Inventory
- Transportation
- Records
- Third parties

---

# 2. Business Continuity Objective

The objective of business continuity is not to preserve normal operations under every condition.

The objective is to maintain or restore the most important business capabilities within acceptable interruption periods while protecting human safety.

---

# 3. Authority

This plan operates under:

- [[POL-001 Information Security Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-011 Physical & Environmental Security Policy]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]

---

# 4. Scope

This plan applies to:

- Scranton Headquarters
- Scranton Branch
- Syracuse Branch
- Utica Branch
- Rochester Branch
- Nashua Branch
- Akron Branch
- Business operations
- Warehousing
- Fulfillment
- Distribution
- Information Technology
- Cloud-hosted systems
- Business applications
- Company communications
- Critical third parties
- Key personnel

---

# 5. Enterprise Operating Model

Dunder Mifflin operates as a business-to-business distributor and reseller of:

- Paper
- Stationery
- Office supplies

The company does not manufacture these products.

The core business process is:

**Acquire Inventory → Sell → Process Orders → Fulfill → Deliver / Ship → Invoice → Receive Payment**

---

# 6. Business Continuity and Disaster Recovery

Business Continuity (BC) and Disaster Recovery (DR) are related but distinct.

Business Continuity focuses on maintaining business operations.

Disaster Recovery focuses primarily on restoring technology and supporting information systems.

This plan coordinates with [[PLN-003 Disaster Recovery Plan]].

---

# 7. Safety Priority

The enterprise recovery priority begins with:

**Human Safety**

Human life and safety take priority over:

- Systems
- Operations
- Facilities
- Equipment
- Inventory
- Revenue
- Other assets

---

# 8. Recovery Priority

After immediate human-safety needs are addressed, recovery priority is:

**Critical → High → Moderate → Low**

Recovery sequencing must be based on business requirements rather than technical convenience.

---

# 9. Business Impact Analysis

[[RPT-002 Business Impact Analysis]] is the authoritative source for:

- Business-process criticality
- Maximum Tolerable Downtime (MTD)
- Recovery Time Objective (RTO)
- Recovery Point Objective (RPO)
- Business dependencies
- Recovery priorities

---

# 10. Maximum Tolerable Downtime

Maximum Tolerable Downtime (MTD) represents the longest interruption a business process can tolerate before consequences become unacceptable.

MTD is a business requirement.

It is not the target restoration time.

---

# 11. Recovery Time Objective

Recovery Time Objective (RTO) establishes the target period within which a disrupted process or supporting capability should be restored.

RTO must remain within the applicable MTD.

---

# 12. Recovery Point Objective

Recovery Point Objective (RPO) establishes the maximum acceptable amount of data loss measured in time.

RPO applies where the business process depends on recoverable electronic information.

---

# 13. BIA Requirements

The approved Business Impact Analysis establishes the following continuity requirements:

| Business Process / Capability | Criticality | MTD | RTO | RPO |
|---|---:|---:|---:|---:|
| Order Processing | Critical | 3 days | 8 hours | 4 hours |
| Warehouse Operations | Critical | 3 days | 8 hours | 4 hours |
| Inventory Management | High | 3 days | 12 hours | 4 hours |
| Shipping / Delivery | High | 3 days | 12 hours | 8 hours |
| Internet Connectivity | High | 24 hours | 4 hours | N/A |
| Active Directory / Authentication | High | 24 hours | 4 hours | 4 hours |
| Customer Relationship Management (CRM) | High | 3 days | 12 hours | 8 hours |
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

# 14. BIA Requirements Are Not Recovery Claims

An RTO or RPO represents a business requirement.

It does not prove that Dunder Mifflin can currently achieve that objective.

Actual recovery capability must be demonstrated through:

- Implementation
- Exercises
- Restore testing
- Recovery testing
- Operational evidence

---

# 15. Recovery Capability Gap

When actual recovery capability cannot meet an approved BIA requirement, the condition must be:

1. Documented.
2. Evaluated for business impact.
3. Assigned for corrective action.
4. Escalated according to risk.
5. Retested after remediation.

---

# 16. Plan Activation

This plan may be activated when an event materially disrupts or threatens to disrupt a business process beyond normal operational recovery capability.

---

# 17. Activation Conditions

Potential activation conditions include:

- Facility loss
- Fire
- Water damage
- Extended utility outage
- Internet outage
- Cloud-service outage
- Significant cyber incident
- Ransomware
- Major system failure
- Regional disaster
- Transportation disruption
- Supplier disruption
- Significant personnel loss
- Other material business interruption

---

# 18. Partial Activation

The entire enterprise does not need to enter continuity operations because one process or location is disrupted.

The plan may be activated for:

- One process
- One department
- One facility
- One branch
- Multiple facilities
- The entire enterprise

---

# 19. Activation Authority

The CEO has overall authority for enterprise continuity activation.

Operational activation may also be initiated by the COO or another authorized executive when immediate action is necessary.

Technology recovery may be initiated by the CIO within established authority.

---

# 20. Emergency Action

Immediate action necessary to protect human safety or prevent material harm does not require waiting for formal plan activation.

The decision and resulting actions must be documented as soon as practical.

---

# 21. Continuity Leadership

Continuity leadership includes:

- CEO
- COO
- CFO
- CIO
- Legal/Compliance
- Relevant business managers
- IT & Information Security Manager
- Facility or branch leadership

Participation depends on incident scope.

---

# 22. CEO Responsibilities

The CEO is responsible for:

- Enterprise direction
- Major business decisions
- Significant risk acceptance
- Major external business decisions
- Executive coordination
- Enterprise recovery priorities when conflicts cannot be resolved below the executive level

---

# 23. COO Responsibilities

The COO coordinates continuity for:

- Branch operations
- Warehousing
- Fulfillment
- Distribution
- Procurement
- Quality
- Operational facilities
- Operational personnel

---

# 24. CFO Responsibilities

The CFO coordinates continuity for:

- Accounting
- Payroll
- Accounts payable
- Financial controls
- Human Resources within the CFO organization
- Financial business records

---

# 25. CIO Responsibilities

The CIO coordinates:

- Technology recovery priorities
- Information Technology resources
- Application recovery
- Cloud-provider coordination
- Technology third parties
- Disaster Recovery activation
- Information-security coordination

---

# 26. Legal and Compliance Responsibilities

Legal/Compliance supports:

- Contract interpretation
- Legal obligations
- Regulatory considerations
- Incident notification decisions
- Evidence-preservation requirements
- External legal coordination

---

# 27. IT & Information Security Manager Responsibilities

The IT & Information Security Manager coordinates:

- IT operational recovery
- Security considerations
- Technical recovery status
- Technology dependencies
- Security incident coordination
- Recovery validation
- IT recovery documentation

---

# 28. Business Owner Responsibilities

Business owners are responsible for:

- Identifying minimum operating requirements
- Prioritizing essential activities
- Activating manual procedures
- Assigning available personnel
- Validating recovered business functionality
- Reporting continuity status

---

# 29. Branch Leadership Responsibilities

Branch leadership coordinates:

- Personnel accountability
- Local safety
- Facility status
- Warehouse operations
- Manual operations
- Customer coordination
- Local continuity resources
- Communication with enterprise leadership

---

# 30. Personnel Accountability

Following a disruptive event affecting a facility, management must account for personnel where safety circumstances require it.

Personnel accountability takes priority over business recovery.

---

# 31. Emergency Services

Fire, medical, police, or other emergency services should be contacted when required.

Employees must not enter or remain in unsafe facilities solely to protect:

- Equipment
- Records
- Inventory
- Systems

---

# 32. Facility Evacuation

Facility evacuation follows applicable:

- Building procedures
- Landlord procedures
- Emergency-service direction
- Local safety requirements

Business recovery begins only after immediate safety requirements are addressed.

---

# 33. Facility Reentry

Personnel must not reenter a facility declared unsafe until authorized by appropriate authorities or responsible facility management.

---

# 34. Continuity Communications

Continuity communications should identify:

- What happened
- Who is affected
- What operations are disrupted
- What continuity actions are active
- Where employees should report
- What customers or providers require communication
- When the next update is expected

---

# 35. Communication Accuracy

Continuity communications must distinguish:

- Confirmed facts
- Reasonable estimates
- Unknown information

Unsupported certainty must be avoided.

---

# 36. Alternate Communications

When normal company communication is unavailable, alternate communication may include:

- Company-issued mobile phones
- Cellular voice
- Cellular data
- Approved alternate contact methods
- In-person management coordination

---

# 37. Personal Phones

Personal phones may be used for:

- Safety
- Emergency contact
- Personnel coordination

They are not the normal baseline for routine company business continuity when company-issued capability is available.

---

# 38. Company-Issued Mobile Capability

Company-issued phones and cellular capability may support continuity for personnel whose business functions can reasonably operate through mobile communications.

---

# 39. Communications Limitation

Cellular capability is a continuity option, not a guarantee.

A regional event may affect:

- Wired Internet
- Cellular service
- Power
- Transportation

simultaneously.

---

# 40. Internet Outage

Loss of a facility's primary wired Internet connection may interrupt access to cloud-hosted business systems.

The applicable Internet Connectivity RTO is four hours.

---

# 41. Cellular Internet Continuity

Company-issued cellular connectivity may provide a secondary Internet path where:

- Cellular service remains available.
- The required business device supports it.
- The business function can operate effectively over that connection.

---

# 42. Internet Continuity Limitation

Cellular connectivity may not fully support:

- Warehouse operations
- Large numbers of users
- Every peripheral device
- Every local operational dependency

Manual continuity may be required.

---

# 43. Regional Telecommunications Failure

Simultaneous or widespread failure of wired and cellular communications is treated as a broader regional continuity problem and relates to R035 Regional Disaster.

---

# 44. Cloud-First Architecture

Dunder Mifflin uses a cloud-first architecture.

Major company systems are not dependent on a large company-operated data center at Headquarters.

This reduces some Headquarters facility dependencies but creates cloud-provider dependency.

---

# 45. Cloud Outage

A cloud-provider outage may affect multiple systems simultaneously.

The response must determine:

- Systems affected
- Business processes affected
- Expected provider recovery
- Manual continuity capability
- Backup availability
- Whether emergency migration should be considered

---

# 46. Cloud Exit and Emergency Migration

Cloud-provider failure or unacceptable recovery may require activation of [[PLN-004 Cloud Exit & Emergency Migration Plan]].

Dunder Mifflin does not maintain a continuously operating alternate cloud environment.

---

# 47. Cloud Migration Decision

Emergency migration should be based on:

- Expected outage duration
- Security trust
- Business impact
- Recovery requirements
- Available infrastructure
- Data availability
- Migration risk

Migration is not automatically required for every cloud outage.

---

# 48. Active Directory and Authentication

Active Directory and authentication have:

- Criticality: High
- MTD: 24 hours
- RTO: 4 hours
- RPO: 4 hours

Authentication recovery is a high technology priority because multiple business systems may depend on it.

---

# 49. Authentication Architecture

Dunder Mifflin maintains at least two cloud-hosted Domain Controller/authentication servers within the same overall cloud provider with reasonable failure-domain separation.

This provides resilience against some individual-system failures.

It does not eliminate cloud-provider concentration risk.

---

# 50. Order Processing

Order Processing is Critical.

The applicable requirements are:

- MTD: 3 days
- RTO: 8 hours
- RPO: 4 hours

Continuity should prioritize preserving the ability to:

- Receive orders
- Record orders
- Verify orders
- Route orders for fulfillment

---

# 51. Sales-Assisted Orders

Sales personnel may continue customer communication through:

- Company laptops
- Company-issued phones
- Available cellular connectivity

when normal office connectivity is unavailable and the required systems remain accessible.

---

# 52. Infinity Orders

Infinity provides a customer-facing ordering channel.

Infinity orders ultimately converge with the broader fulfillment process.

Loss of Infinity does not automatically eliminate all order-processing capability.

---

# 53. Infinity Continuity

Infinity is Moderate criticality with:

- MTD: 3 days
- RTO: 24 hours
- RPO: 4 hours

During Infinity disruption, sales-assisted or other authorized order methods may support business continuity where available.

---

# 54. Warehouse Operations

Warehouse Operations are Critical.

The applicable requirements are:

- MTD: 3 days
- RTO: 8 hours
- RPO: 4 hours

Continuity must preserve the ability to identify, prepare, and control customer orders where practical.

---

# 55. Warehouse Technology Failure

When normal warehouse technology is unavailable, authorized manual processing may be used.

Manual operations must follow [[PROC-013 Manual Processing Procedure]].

---

# 56. Warehouse Manual Records

Manual warehouse records should capture sufficient information to support later reconciliation.

This may include:

- Customer or order reference
- Item
- Quantity
- Activity
- Employee
- Date and time
- Fulfillment or shipping status

---

# 57. Inventory Management

Inventory Management is High criticality with:

- MTD: 3 days
- RTO: 12 hours
- RPO: 4 hours

Manual inventory movement must be recorded sufficiently to support later reconciliation.

---

# 58. Shipping and Delivery

Shipping / Delivery is High criticality with:

- MTD: 3 days
- RTO: 12 hours
- RPO: 8 hours

Continuity should prioritize:

- Customer orders already prepared
- Critical customer commitments
- Available transportation
- Accurate shipment records

---

# 59. Shipping Records

Manual shipping records should support later reconciliation with:

- Order records
- Inventory records
- Customer records
- Billing records

---

# 60. CRM

Customer Relationship Management (CRM) is High criticality with:

- MTD: 3 days
- RTO: 12 hours
- RPO: 8 hours

During CRM interruption, essential customer information should be captured using authorized temporary records when necessary.

---

# 61. Email

Email is High criticality with:

- MTD: 2 days
- RTO: 8 hours
- RPO: 4 hours

If email is unavailable, alternate communications may be used for urgent business coordination.

---

# 62. File Services

File Services are High criticality with:

- MTD: 3 days
- RTO: 12 hours
- RPO: 8 hours

Business owners should identify essential records required for continuity.

---

# 63. Accounting

Accounting is High criticality with:

- MTD: 5 business days
- RTO: 24 hours
- RPO: 8 hours

Continuity must preserve financial control and reconciliation.

---

# 64. Procurement

Procurement is High criticality with:

- MTD: 5 business days
- RTO: 2 business days
- RPO: 1 business day

Continuity should support essential inventory replenishment and supplier coordination.

---

# 65. Payroll

Payroll is normally Moderate criticality with:

- MTD: 5 business days
- RTO: 2 business days
- RPO: 1 business day

Criticality may increase to High as a biweekly payroll deadline approaches.

---

# 66. Payroll Timing

Continuity leadership must consider payroll-cycle timing rather than relying solely on the normal Moderate classification.

A disruption immediately before payroll processing may require accelerated recovery.

---

# 67. Human Resources

Human Resources is Moderate criticality with:

- MTD: 5 business days
- RTO: 2 business days
- RPO: 1 business day

Personnel accountability and emergency communications may receive higher operational priority during a safety event.

---

# 68. Accounts Payable

Accounts Payable is Moderate criticality with:

- MTD: 5 business days
- RTO: 2 business days
- RPO: 1 business day

Continuity should preserve appropriate approval and financial controls.

---

# 69. Customer Service

Customer Service is Moderate criticality with:

- MTD: 3 days
- RTO: 24 hours
- RPO: 8 hours

Alternate communication methods may support customer coordination during system disruption.

---

# 70. Quality Assurance

Quality Assurance is Moderate criticality with:

- MTD: 5 business days
- RTO: 2 business days
- RPO: 1 business day

Continuity must not eliminate necessary quality controls solely to increase throughput.

---

# 71. Legal and Compliance

Legal / Compliance is Moderate criticality with:

- MTD: 5 business days
- RTO: 2 business days
- RPO: 1 business day

Legal or compliance activity may receive accelerated priority when a disruption creates an immediate legal obligation.

---

# 72. Public Website

The Public Website is Low criticality with:

- MTD: 7 days
- RTO: 3 days
- RPO: 24 hours

It should not displace recovery resources required for higher-priority business functions.

---

# 73. Manual Processing

Manual continuity follows the lifecycle:

**Collect → Review → Enter → Reconcile → Verify**

Detailed requirements are maintained in [[PROC-013 Manual Processing Procedure]].

---

# 74. Collect

Required business information is captured using approved temporary records.

---

# 75. Review

Manual records are reviewed for:

- Completeness
- Legibility
- Required authorization
- Obvious duplication
- Required supporting information

---

# 76. Enter

When normal systems become available, authorized personnel enter manual transactions into the appropriate system.

---

# 77. Reconcile

Entered transactions are reconciled against the manual records.

The objective is to identify:

- Missing transactions
- Duplicate transactions
- Incorrect transactions
- Incomplete transactions

---

# 78. Verify

The responsible business function verifies that the recovered electronic records reasonably reflect authorized continuity activity.

---

# 79. Manual Records Are Business Records

Manual continuity records must be treated as business records.

They must not be discarded merely because the electronic system has returned.

---

# 80. Manual Processing Security

Manual operations must preserve reasonable:

- Authorization
- Accountability
- Information protection
- Financial control
- Inventory control
- Record integrity

Continuity does not suspend security requirements.

---

# 81. Manual Processing Limitations

Manual processing may reduce efficiency and increase error risk.

Business owners should limit manual activity to what is necessary to maintain essential operations.

---

# 82. Reconciliation Requirement

Recovery from manual operations is not complete until required reconciliation and verification are performed.

---

# 83. Distributed Branch Model

Dunder Mifflin operates six branches in addition to Headquarters.

Geographic distribution provides continuity options when one facility is unavailable.

---

# 84. Unaffected Branch Support

An unaffected branch may support a disrupted location through:

- Customer communication
- Order coordination
- Inventory assistance
- Fulfillment support
- Shipping support
- Management assistance

when operationally practical.

---

# 85. Branch Capacity

An unaffected branch must not be assumed to have unlimited capacity.

Before transferring workload, management should consider:

- Personnel
- Inventory
- Warehouse capacity
- Transportation
- Technology
- Customer geography

---

# 86. Headquarters Loss

Loss of Headquarters does not automatically mean loss of all enterprise technology because major systems are cloud hosted.

Headquarters loss may still materially affect:

- Executive management
- IT personnel
- Finance
- Human Resources
- Legal/Compliance
- Administrative functions

---

# 87. Headquarters Continuity

Headquarters personnel may continue operations through:

- Company laptops
- Company-issued phones
- Cloud-hosted systems
- Alternate work locations
- Other company facilities

where safety and technology permit.

---

# 88. Alternate Work Location

Dunder Mifflin does not maintain a dedicated hot or warm alternate office site.

Temporary relocation may use:

- Another company facility
- Temporary commercial space
- Other authorized location

based on the disruption.

---

# 89. Facility Loss

A facility-loss response should determine:

- Safety status
- Expected outage duration
- Personnel availability
- Inventory impact
- Technology impact
- Records impact
- Alternate operating location
- Customer impact

---

# 90. Fire

Fire continuity priorities include:

1. Human safety.
2. Emergency services.
3. Personnel accountability.
4. Facility status.
5. Operational relocation.
6. Technology and records recovery.
7. Inventory and insurance assessment.

---

# 91. Water Damage

Water-related disruption should consider:

- Electrical safety
- Building access
- Paper records
- Inventory
- IT equipment
- Landlord response
- Alternate operations
- Off-site backups

---

# 92. Utility Failure

Utility failure may involve:

- Electrical power
- Heating
- Cooling
- Building services

The response must consider both personnel safety and business continuity.

---

# 93. UPS Capability

Critical network equipment and selected management and Sales workstations have approximately thirty minutes of Uninterruptible Power Supply (UPS) capability.

UPS capability is intended primarily for:

- Short interruption
- Orderly shutdown
- Limited transitional operation

It is not long-duration facility power.

---

# 94. Generators

Dunder Mifflin does not maintain generators as a standard facility baseline.

Generator capability should be added only when BIA, risk, operational requirements, and cost justify it.

---

# 95. Extended Power Outage

During extended power loss, continuity may require:

- Orderly shutdown
- Mobile communications
- Relocation
- Manual processing
- Workload transfer
- Facility closure

---

# 96. Supplier Disruption

Supplier disruption should be managed through:

- Alternate suppliers where practical
- Available inventory
- Procurement coordination
- Customer communication
- Sourcing review

---

# 97. Alternate Suppliers

Alternate suppliers should be used when practical and commercially reasonable.

The plan does not assume that every product has an immediately available alternate source.

---

# 98. Inventory During Supplier Disruption

Available inventory should be prioritized according to:

- Customer commitments
- Business need
- Product availability
- Replacement lead time

Management retains authority for allocation decisions.

---

# 99. Transportation Disruption

Transportation disruption may affect:

- Supplier deliveries
- Customer deliveries
- Inter-branch movement
- Employee access to facilities

Operations should evaluate alternate transportation where practical.

---

# 100. Vehicle Loss

Loss of a company vehicle should not automatically stop the related business process.

Operations should evaluate:

- Other company vehicles
- Rescheduling
- Alternate transportation
- Third-party shipping

where practical.

---

# 101. Personnel Loss

Loss or unavailability of key personnel may result from:

- Illness
- Injury
- Resignation
- Termination
- Travel disruption
- Regional emergency
- Other absence

Continuity must not depend on one individual where practical alternatives can be established.

---

# 102. Key-Person Dependency

Business and technical functions should identify capabilities whose loss would materially affect continuity.

The objective is to reduce exclusive dependency on individual knowledge.

---

# 103. Cross-Training

Critical responsibilities should have reasonable cross-training or alternate personnel where practical.

Cross-training should prioritize functions whose loss would threaten BIA objectives.

---

# 104. Recovery Documentation

Recovery documentation must be sufficient for a qualified IT professional unfamiliar with the specific environment to perform required recovery tasks.

---

# 105. Documentation Independence

Critical recovery knowledge must not exist solely:

- In one employee's memory
- On one production server
- At one physical facility
- With one contractor

---

# 106. Printed Recovery Documentation

Two printed recovery-documentation sets are maintained as part of the continuity and recovery strategy.

Printed documentation provides access when electronic documentation is unavailable.

---

# 107. Electronic Recovery Documentation

Recovery documentation should also be maintained in appropriately protected electronic form.

Electronic and printed documentation should be kept reasonably synchronized.

---

# 108. Recovery Documentation Changes

A significant technology or configuration change is not complete until related recovery documentation has been reviewed and updated where necessary.

---

# 109. Third-Party Dependency

Continuity planning must consider third parties supporting:

- Cloud services
- Infinity
- Payment processing
- Backup storage
- Technology
- Communications
- Other important business services

---

# 110. Third-Party Incident

Security-related third-party disruption should also follow [[PBK-005 Third-Party Incident Playbook]].

---

# 111. Critical Third-Party Continuity

Critical third parties should be evaluated for:

- Recovery capability
- Incident response
- Service dependency
- Contractual obligations
- Exit capability
- Concentration risk

---

# 112. Provider Failure

Provider failure may require:

- Escalation
- Alternate process
- Manual continuity
- Provider replacement
- Emergency migration
- Risk acceptance

depending on impact and duration.

---

# 113. Backup Strategy

Dunder Mifflin uses:

- Automated backups
- Cloud-based backups
- Encrypted external hard drives
- Off-site external-drive storage

as part of its recovery strategy.

---

# 114. External Backup Rotation

Each of the seven facilities has three encrypted external backup hard drives.

Total external drives:

**21**

---

# 115. Weekly Off-Site Rotation

Each Friday, the current external backup drive is sent to the off-site Disaster Recovery storage provider.

The provider normally retains the two most recent weekly generations for each facility.

---

# 116. Off-Site Backup Generations

The normal off-site external-drive inventory is:

**7 facilities × 2 generations = 14 off-site backup drives**

When a new drive arrives, the oldest generation is returned for reuse in the rotation.

---

# 117. Backup Encryption

External backup hard drives are encrypted.

Encryption protects confidentiality but does not prove:

- Backup completeness
- Recoverability
- Integrity
- RTO achievement
- RPO achievement

---

# 118. Backup Immutability

The backup environment must not be described as immutable unless that capability is implemented and validated.

The current design provides separation but does not establish immutability.

---

# 119. Backup Coverage

Backup coverage must be evaluated against:

- System inventory
- Information classification
- Business Impact Analysis
- Recovery requirements

A successful backup job does not prove that every required system or dataset is protected.

---

# 120. Backup Monitoring

Backup jobs should be monitored for:

- Completion
- Failure
- Exceptions
- Missing systems
- Capacity concerns

Failures require investigation.

---

# 121. Restore Testing

Representative backup restoration should be tested quarterly.

Testing should demonstrate actual ability to recover selected information or systems.

---

# 122. Critical Recovery Testing

Critical systems require at least one meaningful recovery test annually.

The test should demonstrate recovery capability rather than merely confirming that a backup file exists.

---

# 123. RTO Testing

Recovery testing should measure actual elapsed recovery time against the applicable RTO.

---

# 124. RPO Testing

Recovery testing should determine the actual recoverable point and compare data loss against the applicable RPO.

---

# 125. Example Recovery Result

If a system requires:

- RTO: 8 hours
- RPO: 4 hours

and a recovery test produces:

- Recovery time: 11 hours 37 minutes
- Recoverable data loss: 58 minutes

the result is:

- RTO: Failed
- RPO: Passed

The overall recovery capability has not fully met the business requirement.

---

# 126. Improved Recovery Result

If a later validated test produces:

- Recovery time: 6 hours 42 minutes
- Recoverable data loss: 47 minutes

the result is:

- RTO: Passed
- RPO: Passed

The evidence may support reassessment of recovery control effectiveness and related risk.

---

# 127. Failed Recovery Test

A failed recovery test requires:

1. Documentation.
2. Root-cause analysis.
3. Corrective action.
4. Accountable ownership.
5. Retesting.

A failed test must not be recorded as successful because recovery eventually occurred.

---

# 128. Disaster Recovery Coordination

Technology recovery is performed under [[PLN-003 Disaster Recovery Plan]].

Business continuity leadership identifies the required business priority.

Information Technology determines the technical recovery sequence necessary to support that priority.

---

# 129. Business and Technical Priorities

Technical dependencies may require recovery of supporting systems before the business process itself can resume.

For example, authentication may need to be restored before an application can be used.

This does not change the underlying business priority.

---

# 130. Cyber Incident Continuity

A cyber incident may require simultaneous activation of:

- [[PLN-001 Incident Response Plan]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]

Each plan retains its own purpose.

---

# 131. Ransomware Continuity

Ransomware continuity must consider:

- System isolation
- Backup protection
- Credential protection
- Manual operations
- Recovery priorities
- Data integrity
- Business communications

Response guidance is maintained in [[PBK-002 Malware & Ransomware Playbook]].

---

# 132. Data Corruption

Data corruption may require:

- Application isolation
- Transaction suspension
- Backup recovery
- Manual processing
- Reconciliation
- Business validation

Restoring a technically functional system is insufficient if business data remains unreliable.

---

# 133. Manual Processing Risk

Manual continuity increases the risk of:

- Duplicate transactions
- Missing transactions
- Incorrect data entry
- Unauthorized transactions
- Reconciliation errors

Controls must remain in place during continuity operations.

---

# 134. Financial Controls During Continuity

Business disruption does not automatically suspend:

- Approval requirements
- Separation of Duties (SoD)
- Vendor verification
- Payment authorization
- Payroll authorization
- Reconciliation

Emergency exceptions must be documented and reviewed.

---

# 135. Security Controls During Continuity

Continuity does not automatically suspend:

- Authentication
- Least privilege
- Information classification
- Access control
- Evidence preservation
- Change management
- Incident reporting

Temporary exceptions must be authorized and documented.

---

# 136. Emergency Access

Emergency technology access required during continuity must follow [[PROC-005 Emergency Access Procedure]].

Emergency access must remain:

- Limited
- Accountable
- Time-bound
- Reviewed after use

---

# 137. Emergency Changes

Emergency technology changes may be used when delay would create unacceptable business or security risk.

Emergency changes must follow [[POL-007 Change & Configuration Management Policy]].

---

# 138. Information Protection

Protected information must continue to receive reasonable safeguards during disruption.

Continuity does not automatically lower information classification.

---

# 139. Paper Records

Temporary paper records must be protected according to:

- Information sensitivity
- Business need
- Physical environment

Sensitive paper must not be left unnecessarily exposed.

---

# 140. Temporary Electronic Records

Temporary electronic continuity records must be stored in approved locations where practical and later reconciled with authoritative systems.

---

# 141. Customer Communications

Customer communication during a disruption should provide:

- Accurate service information
- Reasonable expectations
- Approved alternatives
- Relevant contact information

Personnel should avoid unsupported recovery promises.

---

# 142. Supplier Communications

Supplier communication may address:

- Delivery changes
- Order changes
- Alternate locations
- Inventory priorities
- Transportation
- Expected recovery

---

# 143. Employee Communications

Employee continuity communication should provide information necessary for:

- Safety
- Reporting location
- Work status
- Alternate work arrangements
- Communication methods
- Required continuity duties

---

# 144. External Statements

Public statements related to significant disruption require authorization.

Employees must not independently:

- Speak for the company
- Admit liability
- Speculate about incident cause
- Provide unsupported recovery estimates

---

# 145. Insurance Coordination

Material facility, inventory, vehicle, or business-loss events may require insurance coordination.

Responsible management should preserve documentation necessary to support legitimate claims.

---

# 146. Recovery Status Tracking

During significant continuity activation, management should track:

- Process
- Criticality
- Current status
- Continuity method
- Recovery owner
- Expected recovery
- Major dependency
- Major blocker

---

# 147. Recovery Status Categories

Operational status may be described as:

- Unavailable
- Manual Continuity
- Partially Restored
- Restored
- Validated

A process should not be reported as fully restored solely because a supporting system is online.

---

# 148. Business Validation

The responsible business owner or qualified representative should validate restored business capability.

Validation should determine whether the process can perform required business functions.

---

# 149. Technical Validation

Information Technology validates applicable technical recovery, including:

- System operation
- Authentication
- Connectivity
- Security controls
- Backup restoration
- Logging
- Required dependencies

---

# 150. Data Validation

Business and technical personnel should validate recovered information for:

- Completeness
- Integrity
- Appropriate recovery point
- Business usability

---

# 151. Return to Normal Operations

Return to normal operations should occur when:

- Immediate safety concerns are addressed.
- Required systems and processes are restored.
- Required business validation is complete.
- Manual records can be reconciled.
- Remaining risks are understood.
- Leadership approves transition where appropriate.

---

# 152. Manual-to-System Transition

The transition from manual operations must be controlled.

Personnel must not simply discard manual records after system restoration.

---

# 153. Reconciliation

Manual records must be reconciled against restored electronic systems.

The reconciliation should identify:

- Missing transactions
- Duplicate transactions
- Incorrect transactions
- Unauthorized transactions
- Unresolved discrepancies

---

# 154. Verification

The responsible business function must verify that required continuity transactions were correctly incorporated into normal systems.

---

# 155. Continuity Event Closure

A continuity event may be closed when:

- Safety issues are resolved or transferred to the appropriate authority.
- Essential business processes are restored.
- Required recovery validation is complete.
- Manual records are reconciled.
- Significant discrepancies are addressed.
- Required corrective actions are documented.
- Remaining risk is understood.

---

# 156. Closure Does Not End Corrective Action

Closing a continuity event does not automatically close:

- Recovery deficiencies
- Backup findings
- Facility issues
- Supplier issues
- Personnel dependencies
- Corrective actions
- Risk treatments

These remain tracked through their appropriate processes.

---

# 157. Lessons Learned

Significant continuity events require a documented lessons-learned review.

The review should consider:

- Activation
- Leadership
- Communications
- Personnel
- Facilities
- Technology
- Manual processing
- Suppliers
- Recovery
- Reconciliation
- Documentation

---

# 158. Root Cause

Where practical, the cause of the disruption should be identified.

Examples include:

- Technology failure
- Cloud outage
- Internet outage
- Fire
- Water damage
- Utility failure
- Cyber incident
- Supplier failure
- Personnel loss
- Regional disaster

---

# 159. Contributing Factors

Contributing factors may include:

- Single-person dependency
- Incomplete documentation
- Insufficient backup coverage
- Inadequate recovery testing
- Provider concentration
- Inadequate manual procedures
- Limited alternate communications
- Facility dependency

---

# 160. Corrective Action

Material continuity deficiencies must identify:

- Deficiency
- Accountable owner
- Required action
- Due date
- Validation method

Material corrective actions are tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 161. Corrective-Action Validation

Corrective action is not complete merely because an action is reported as finished.

Required validation must determine whether the intended condition was achieved.

---

# 162. Plan Exercises

The Business Continuity Plan must be exercised periodically.

Exercises should evaluate actual continuity decisions rather than only confirming that the plan exists.

---

# 163. Exercise Types

Exercises may include:

- Tabletop exercise
- Communications exercise
- Manual-processing exercise
- Facility-loss exercise
- Technology-recovery exercise
- Backup-restore test
- Personnel-unavailability exercise
- Supplier-disruption exercise

---

# 164. Annual Exercise

At least one meaningful enterprise or multi-function Business Continuity/Disaster Recovery exercise should be performed annually.

The exercise should involve material business and technical dependencies.

---

# 165. Critical Process Exercise

Critical business processes should receive sufficient exercise coverage to establish reasonable confidence in continuity capability.

---

# 166. Manual Processing Exercise

Manual continuity exercises should evaluate the full lifecycle:

**Collect → Review → Enter → Reconcile → Verify**

A test that stops before reconciliation does not demonstrate complete manual continuity.

---

# 167. Communications Exercise

A communications exercise should determine whether required personnel can be reached using:

- Primary methods
- Relevant alternate methods

Contact information should be corrected when deficiencies are found.

---

# 168. Facility-Loss Exercise

A facility-loss scenario should evaluate:

- Personnel accountability
- Alternate location
- Communications
- Business-process continuity
- Technology access
- Records
- Customer impact
- Management coordination

---

# 169. Personnel-Loss Exercise

A personnel-loss scenario should determine whether an alternate qualified person can perform essential responsibilities using available documentation.

---

# 170. Recovery Documentation Exercise

A qualified IT professional unfamiliar with the specific system should periodically be used where practical to evaluate whether recovery documentation is sufficient.

The purpose is to test documentation quality rather than individual memory.

---

# 171. Exercise Evidence

Exercise evidence should include:

- Scenario
- Participants
- Date
- Objectives
- Actions
- Observed results
- Deficiencies
- Corrective actions
- Responsible owners
- Retest requirements

---

# 172. No Manufactured Exercise Evidence

Exercises must reflect actual results.

Personnel must not:

- Backdate exercises
- Record unperformed steps as completed
- Hide failed objectives
- Convert assumptions into successful test results

---

# 173. Exercise Findings

A finding is a documented conclusion supported by evidence concerning whether a requirement, control, process, or expected outcome was satisfied.

Findings may identify:

- Satisfactory performance
- Partial performance
- Deficiency
- Control failure
- Recovery gap

---

# 174. Failed Exercise

A failed exercise is useful assurance evidence.

Failure should result in:

1. Documentation.
2. Analysis.
3. Corrective action.
4. Retesting where appropriate.
5. Risk reassessment when material.

---

# 175. Assessment Methods

Business continuity assurance may use:

- Inspection
- Observation
- Interviews
- Sampling
- Exercises
- Technical Testing
- Reconciliation
- Independent Performance

---

# 176. Independent Performance

An assessor may independently perform selected continuity activities using an authorized scenario.

For example, the assessor may:

1. Identify the affected business process.
2. Retrieve its BIA requirements.
3. Determine continuity priority.
4. Select the applicable manual or alternate process.
5. Identify dependencies.
6. Determine required recovery coordination.
7. Define business validation.
8. Compare the result with expected continuity actions.

---

# 177. Continuity Metrics

Metrics may include:

- BCP exercises completed
- Critical processes exercised
- Recovery tests completed
- RTO pass rate
- RPO pass rate
- Manual-processing exercises completed
- Open continuity findings
- Overdue corrective actions
- Recovery-documentation exceptions
- Critical personnel dependencies

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 178. Key Performance Indicators

Key Performance Indicators (KPIs) may include:

- Percentage of required continuity exercises completed
- Percentage of Critical recovery tests meeting RTO
- Percentage of Critical recovery tests meeting RPO
- Percentage of manual-processing exercises completing reconciliation
- Percentage of continuity corrective actions completed and validated

---

# 179. Key Risk Indicators

Key Risk Indicators (KRIs) may include:

- Failed Critical recovery tests
- Repeated RTO failure
- Repeated RPO failure
- Unresolved key-person dependency
- Unrecoverable backup
- Significant recovery-documentation deficiency
- Critical provider recovery weakness
- Increasing continuity findings

---

# 180. Metric Interpretation

Continuity metrics must be interpreted in context.

For example, an increased number of findings may reflect:

- Degraded capability
- More thorough testing
- Expanded assessment coverage
- Improved reporting

Finding count alone does not establish whether continuity risk increased or decreased.

---

# 181. Risk Relationships

This plan supports treatment and response for risks including:

- R003 Ransomware
- R006 Infinity Application Compromise
- R007 Internet Infrastructure Compromise
- R008 Denial of Service
- R016 Cloud Outage
- R017 ISP Outage
- R018 Third-Party Technology Failure / Compromise
- R020 Supplier Disruption
- R021 Fire
- R022 Water Damage
- R023 Utility / Power / HVAC Failure
- R025 Vehicle Loss / Disruption
- R026 Personnel Loss
- R027 Backup / Recovery Failure
- R028 Data Corruption
- R033 Manual Outage Processing Error
- R034 Loss of Headquarters
- R035 Regional Disaster

---

# 182. R016 Cloud Outage

R016 has:

- Inherent risk: **15 High**
- Current residual risk: **8 Moderate**
- Target residual risk: **6 Moderate**

Continuity treatment includes:

- Business Continuity/Disaster Recovery planning
- Cloud Exit and Emergency Migration planning
- Recovery documentation
- Backups
- Manual processes
- Provider escalation
- Provider resilience review

---

# 183. R017 ISP Outage

R017 has:

- Inherent risk: **16 High**
- Current residual risk: **9 Moderate**
- Target residual risk: **4 Low**

Treatment includes company-issued cellular connectivity where applicable and manual continuity for functions that cannot operate effectively through cellular connectivity.

---

# 184. R020 Supplier Disruption

R020 has:

- Inherent risk: **16 High**
- Current residual risk: **9 Moderate**
- Target residual risk: **6 Moderate**

Treatment includes alternate suppliers where practical, inventory management, monitoring, operational coordination, and sourcing review.

---

# 185. R026 Personnel Loss

R026 has:

- Inherent risk: **16 High**
- Current residual risk: **9 Moderate**
- Target residual risk: **4 Low**

Treatment includes:

- Documentation
- Cross-training
- Alternate personnel
- Company ownership of essential information
- Emergency access
- Dependency review

---

# 186. R027 Backup / Recovery Failure

R027 has:

- Inherent risk: **20 Critical**
- Current residual risk: **12 High**
- Target residual risk: **5 Moderate**

Target risk depends on validated recovery capability rather than backup existence alone.

---

# 187. R033 Manual Outage Processing Error

R033 has:

- Inherent risk: **12 High**
- Current residual risk: **9 Moderate**
- Target residual risk: **4 Low**

Treatment depends on the documented lifecycle:

**Collect → Review → Enter → Reconcile → Verify**

---

# 188. R034 Loss of Headquarters

R034 has:

- Inherent risk: **10 High**
- Current residual risk: **8 Moderate**
- Target residual risk: **4 Low**

Treatment includes:

- Cloud-hosted systems
- Off-site backups
- Independent recovery documentation
- Company laptops
- Company-issued cellular capability
- Alternate work locations
- Distributed branch support
- Insurance
- Alternate personnel and delegated authority

---

# 189. R035 Regional Disaster

R035 has:

- Inherent risk: **9 Moderate**
- Current residual risk: **6 Moderate**
- Target residual risk: **5 Moderate**

Treatment includes:

- Geographic distribution
- Cloud-hosted systems
- Geographically separated backups
- Alternate communications
- Unaffected branch support
- Manual continuity
- Supplier and transportation alternatives
- Personnel succession
- Insurance

---

# 190. Current and Proposed Controls

Continuity records must distinguish among:

- Current controls
- Partially implemented controls
- Planned controls
- Implemented controls awaiting validation
- Validated controls

---

# 191. No Premature Risk Credit

Current residual risk must not be reduced merely because:

- This plan exists.
- An exercise is scheduled.
- A recovery improvement is planned.
- A provider promises improved resilience.
- A corrective action is assigned.
- A proposed capability has been documented.

Risk reduction requires implementation and appropriate validation.

---

# 192. Target Residual Risk

Target residual risk represents expected risk after proposed treatment.

It is a prediction rather than a guaranteed result.

---

# 193. Validated Post-Treatment Risk

After treatment is implemented and validated, risk may be reassessed.

Validated post-treatment risk may be:

- Higher than target
- Equal to target
- Lower than target

The evidence determines the result.

---

# 194. Historical Risk Integrity

The original May 2013 risk assessment must remain preserved.

A later validated risk score becomes the new current residual risk without rewriting the historical assessment.

---

# 195. Plan Maintenance

The Business Continuity Plan must be updated when material changes affect:

- Business processes
- BIA requirements
- Facilities
- Technology
- Personnel dependencies
- Suppliers
- Cloud services
- Recovery methods
- Communications
- Manual procedures

---

# 196. Contact Information

Operational contact information should be maintained separately where practical so routine personnel or telephone changes do not require full plan revision.

Contact information must remain accessible during disruption.

---

# 197. Recovery Documentation Availability

Required continuity and recovery documentation must be accessible when:

- Normal cloud access is unavailable.
- Headquarters is unavailable.
- Primary Internet access is unavailable.
- Key personnel are unavailable.

---

# 198. Document Protection

Because this plan contains internal operational and recovery information, access must be limited according to its Confidential classification.

---

# 199. Findings

Material continuity deficiencies must be documented.

Examples include:

- Critical recovery unable to meet RTO
- Recovery unable to meet RPO
- Required backup unavailable
- Manual process cannot be reconciled
- Critical process depends on unavailable undocumented knowledge
- Recovery documentation cannot support qualified alternate personnel
- Critical provider lacks adequate recovery capability
- Required continuity exercise not performed

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 200. Control Effectiveness

Continuity evidence may support conclusions that relevant controls are:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

Control effectiveness must reflect actual evidence rather than documentation alone.

---

# 201. Traceability

This plan supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Business continuity provides a direct connection between business requirements and recovery capability.

---

# 202. Related Artifacts

- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-001 Enterprise Asset Register]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[POL-001 Information Security Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-011 Physical & Environmental Security Policy]]
- [[STD-001 Information Classification Standard]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-013 Manual Processing Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

---

# 203. Review

This plan must be reviewed:

- At least annually
- Following a material continuity event
- Following significant BIA change
- Following significant business-process change
- Following significant facility change
- Following significant technology or provider change
- Following material exercise findings

The COO coordinates the business review.

The CIO coordinates review of technology and recovery dependencies.

Material revisions require CEO approval.

---

# 204. Revision History

| Version | Date     | Description                      | Approval |
| ------- | -------- | -------------------------------- | -------- |
| 1.0     | May 2013 | Initial Business Continuity Plan | CEO      |