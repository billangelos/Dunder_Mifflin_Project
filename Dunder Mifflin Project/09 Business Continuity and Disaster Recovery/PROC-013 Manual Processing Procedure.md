# PROC-013 Manual Processing Procedure

## Document Control

| Field | Value |
|---|---|
| Document ID | PROC-013 |
| Title | Manual Processing Procedure |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | COO |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Business Process, Continuity, or System Change |

---

# 1. Purpose

This procedure establishes how Dunder Mifflin continues essential business activities when normal information systems or supporting technology are unavailable.

Manual processing provides a controlled temporary method for conducting necessary business while preserving sufficient information to enter, reconcile, and verify transactions after systems return.

---

# 2. Manual Processing Lifecycle

All manual continuity processing follows:

**Collect → Review → Enter → Reconcile → Verify**

These five stages form the minimum control structure for manual processing.

---

# 3. Objectives

This procedure is intended to:

- Maintain essential business operations during outages.
- Preserve transaction accountability.
- Maintain reasonable authorization controls.
- Reduce missing transactions.
- Reduce duplicate transactions.
- Reduce incorrect transactions.
- Protect sensitive information.
- Support accurate system restoration.
- Provide evidence of continuity activity.
- Enable complete reconciliation after recovery.

---

# 4. Authority

This procedure operates under:

- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[RPT-002 Business Impact Analysis]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]

---

# 5. Scope

This procedure applies when normal technology is unavailable or materially impaired for business activities including:

- Order processing
- Warehouse operations
- Inventory management
- Shipping
- Delivery
- Customer service
- Procurement
- Accounting
- Payroll
- Accounts payable
- Other approved business processes capable of temporary manual operation

---

# 6. Manual Processing Is a Continuity Method

Manual processing is a temporary continuity method.

It is not intended to replace normal business systems permanently.

---

# 7. Manual Processing Limitations

Manual processing may:

- Reduce operating capacity.
- Increase processing time.
- Increase error risk.
- Reduce automated validation.
- Reduce immediate visibility.
- Increase reconciliation work.

Business owners should limit manual activity to what is reasonably necessary to maintain essential operations.

---

# 8. Safety Priority

Human safety takes priority over manual business processing.

Employees must not:

- Enter unsafe facilities.
- Remain in unsafe facilities.
- Retrieve records from unsafe locations.

solely to continue business operations.

---

# 9. Business Impact Analysis

Manual continuity priorities must reflect [[RPT-002 Business Impact Analysis]].

Critical and High business processes generally receive priority over Moderate and Low processes.

---

# 10. Critical Manual Continuity

The Critical business processes are:

- Order Processing
- Warehouse Operations

Both have:

- Maximum Tolerable Downtime (MTD): 3 days
- Recovery Time Objective (RTO): 8 hours
- Recovery Point Objective (RPO): 4 hours

---

# 11. Manual Processing Activation

Manual processing may be activated when:

- An application is unavailable.
- Authentication is unavailable.
- Internet connectivity is unavailable.
- A cloud service is unavailable.
- A facility has limited technology.
- A cyber incident requires system isolation.
- Technology recovery will exceed normal operational tolerance.
- Business Continuity leadership directs manual operation.

---

# 12. Activation Authority

The responsible business manager may authorize manual processing for the affected business function within established continuity requirements.

Enterprise-wide manual continuity may be coordinated through [[PLN-002 Business Continuity Plan]].

---

# 13. Emergency Activation

Employees may take reasonable immediate action necessary to:

- Protect human safety.
- Prevent material business loss.
- Preserve essential customer activity.

when waiting for formal activation would create unacceptable harm.

The activity must be documented as soon as practical.

---

# 14. Manual Processing Decision

Before beginning manual processing, the responsible manager should determine:

- What system is unavailable?
- What business process is affected?
- What activities must continue?
- What activities can wait?
- What records are required?
- What approvals remain necessary?
- How will records be protected?
- How will transactions later be entered?
- Who will perform reconciliation?

---

# 15. Minimum Necessary Processing

Manual operations should focus on essential activity.

Employees should avoid creating unnecessary manual transactions that will later require reconciliation.

---

# 16. Manual Processing Coordinator

For a significant outage, the responsible business manager should designate a Manual Processing Coordinator.

---

# 17. Coordinator Responsibilities

The Manual Processing Coordinator should:

- Coordinate temporary records.
- Assign responsibilities.
- Maintain processing instructions.
- Track manual transaction batches.
- Coordinate review.
- Coordinate system reentry.
- Coordinate reconciliation.
- Escalate unresolved discrepancies.

---

# 18. Individual Accountability

Manual transactions must be attributable to the employee performing or authorizing the activity where practical.

---

# 19. Minimum Transaction Information

A manual transaction should capture sufficient information to determine:

- What occurred
- Who performed it
- Who authorized it where required
- When it occurred
- Which customer, supplier, employee, item, or account was involved
- What quantity or amount was involved
- Whether the transaction was completed
- Whether it was later entered into the system

---

# 20. Date and Time

Manual records should include the date and, where material, the approximate time of the transaction.

---

# 21. Employee Identification

The employee performing the transaction should identify themselves using:

- Name
- Initials
- Employee identifier

or another approved method sufficient to establish accountability.

---

# 22. Customer or Transaction Reference

Where applicable, manual records should include an available:

- Customer reference
- Order number
- Purchase reference
- Shipment reference
- Invoice reference
- Employee reference
- Vendor reference

---

# 23. Temporary Numbering

When normal system-generated transaction numbers are unavailable, temporary identifiers may be used.

---

# 24. Temporary Identifier Requirements

Temporary identifiers should be:

- Unique enough to distinguish transactions.
- Consistently applied.
- Preserved during later system entry.
- Traceable to the final electronic record.

---

# 25. Sequential Records

Where practical, numbered forms or sequential temporary identifiers should be used for higher-volume manual activity.

Sequence gaps should be investigated during reconciliation.

---

# 26. Paper Records

Paper forms may be used when electronic systems are unavailable.

Paper records become company business records.

---

# 27. Offline Electronic Records

Approved offline electronic records may be used where:

- The device remains available.
- The method is appropriate for the information.
- Required security controls remain available.
- The records can later be reconciled.

---

# 28. Personal Devices

Personal devices should not be used as the normal method for storing company manual continuity records.

---

# 29. Information Classification

Manual records retain the classification of the information they contain.

Manual processing does not lower information sensitivity.

---

# 30. Sensitive Paper Records

Confidential or Restricted paper records must be:

- Limited to personnel with a business need.
- Protected from unnecessary viewing.
- Stored securely when unattended.
- Disposed of securely when authorized.

---

# 31. Temporary Electronic Information

Temporary electronic continuity records must receive protection appropriate to:

- Information classification
- Device
- Location
- Business risk

---

# 32. Payment Card Information

Manual continuity must not introduce unnecessary storage of full payment card Primary Account Number (PAN) information.

Dunder Mifflin normally retains payment tokens and limited payment information rather than full PAN.

---

# 33. Unexpected Payment Card Data

Unexpected discovery or creation of full PAN information must be escalated for appropriate handling.

---

# 34. Authorization Requirements

Normal business authorization requirements remain in effect during manual processing unless an authorized continuity exception is required.

---

# 35. Separation of Duties

Separation of Duties (SoD) should remain in place where practical.

Business disruption does not automatically authorize one person to:

- Create
- Approve
- Execute
- Reconcile

the same sensitive transaction.

---

# 36. Emergency Separation-of-Duties Exception

When normal Separation of Duties cannot reasonably be maintained:

1. The exception must be necessary.
2. The activity must be documented.
3. Management approval should be obtained where practical.
4. The transaction must receive independent review as soon as practical.

---

# 37. Financial Controls

Manual processing does not automatically suspend controls for:

- Vendor creation
- Vendor payment changes
- Purchase approval
- Invoice approval
- Payment authorization
- Payroll changes
- Refunds
- Credits

---

# 38. Suspicious Financial Requests

Suspicious or significant payment changes must receive appropriate independent verification using a trusted contact method.

An outage must not be used as justification to bypass fraud controls.

---

# 39. Access Control

Manual processing must maintain reasonable access restrictions.

Only personnel with a legitimate business need should access sensitive manual records.

---

# 40. Manual Record Storage

During an outage, manual records should be stored in:

- Controlled office space
- Locked cabinet
- Restricted work area
- Other appropriate protected location

based on information sensitivity and operating conditions.

---

# 41. Record Custody

For significant manual processing, the responsible business function should identify who has custody of completed records.

---

# 42. Transfer of Records

When manual records are transferred between personnel or locations, important batches should remain reasonably accountable.

---

# 43. Missing Manual Records

Missing manual records must be investigated.

The investigation should determine:

- Records affected
- Business impact
- Information sensitivity
- Whether transactions can be reconstructed
- Whether security escalation is required

---

# 44. Damaged Manual Records

Damaged records should be preserved where they remain usable.

Information should not be recreated from memory without identifying that reconstruction occurred.

---

# 45. Manual Order Processing

When normal Order Processing is unavailable, authorized personnel may temporarily record customer orders manually.

---

# 46. Manual Order Information

Manual orders should capture sufficient information such as:

- Customer
- Contact information
- Requested items
- Quantity
- Pricing where applicable
- Delivery information
- Salesperson
- Date and time
- Temporary transaction reference

---

# 47. Order Review

Before manual orders proceed to fulfillment, they should receive appropriate review for:

- Customer identification
- Item
- Quantity
- Pricing
- Delivery information
- Required approval

---

# 48. Duplicate Order Risk

Employees should determine whether an order may already exist electronically before recreating it manually where practical.

---

# 49. Customer Confirmation

Where appropriate, customer confirmation may be used to clarify whether an order was:

- Already submitted
- Submitted through Infinity
- Submitted through Sales
- Submitted more than once

---

# 50. Infinity Outage

If Infinity is unavailable, customers may use authorized sales-assisted ordering methods where available.

Infinity outage does not automatically stop all order processing.

---

# 51. Manual Warehouse Processing

Warehouse personnel may use approved paper or offline records when the Warehouse Management System (WMS) or supporting technology is unavailable.

---

# 52. Warehouse Transaction Information

Manual warehouse activity should capture as applicable:

- Order reference
- Item
- Quantity
- Employee
- Date and time
- Pick status
- Packing status
- Shipping status

---

# 53. Warehouse Accountability

The shared Windows workstation model does not remove the need for individual accountability during manual warehouse processing.

Manual records should identify the employee performing significant transactions.

---

# 54. Inventory Movement

Manual inventory movement must be recorded.

This includes material:

- Receipt
- Pick
- Transfer
- Adjustment
- Return
- Shipment

activity.

---

# 55. Inventory Record Requirements

Manual inventory records should identify:

- Item
- Quantity
- Source location
- Destination or purpose
- Employee
- Date and time
- Related order or shipment where applicable

---

# 56. High-Value Inventory

Manual handling of high-value or theft-attractive inventory must continue to use established locked security cages or enclosures where applicable.

---

# 57. Security Cage Access

Manual processing does not automatically expand access to secured inventory cages.

Access remains limited to authorized personnel.

---

# 58. Receiving

Manual receiving records should identify:

- Supplier
- Shipment
- Item
- Quantity
- Receiving employee
- Date
- Exceptions or damage

---

# 59. Shipping

Manual shipping records should identify:

- Customer
- Order
- Items
- Quantity
- Shipping method
- Date
- Responsible employee

where applicable.

---

# 60. Shipping Reconciliation

Manual shipping activity must later be reconciled with:

- Order records
- Inventory records
- Customer records
- Billing records

---

# 61. Customer Service

During system outages, Customer Service may record customer contacts manually when required.

Records should include sufficient information to follow up after systems return.

---

# 62. CRM Outage

When CRM is unavailable, temporary customer records should capture only information required for continuity.

Employees should avoid creating unnecessary duplicate customer records.

---

# 63. Procurement

Manual procurement should preserve:

- Purchase authorization
- Supplier identification
- Item and quantity
- Price where available
- Requestor
- Approver
- Date
- Delivery information

---

# 64. Supplier Verification

Normal supplier-verification requirements remain in effect during manual processing.

---

# 65. New Vendor Risk

Creating a new vendor during an outage requires particular caution because normal automated or electronic records may be unavailable.

Required approval and verification must still occur.

---

# 66. Vendor Payment Changes

A request to change vendor payment information during an outage must not be trusted solely because normal systems are unavailable.

Suspicious or significant changes require independent verification using a trusted contact method.

---

# 67. Accounting

Manual accounting activity should be limited to transactions necessary to support business continuity.

Financial records must remain attributable and reconcilable.

---

# 68. Accounts Payable

Manual Accounts Payable activity should preserve:

- Vendor
- Invoice
- Amount
- Approval
- Payment status
- Employee performing activity
- Date

---

# 69. Duplicate Payment Risk

Before manually issuing a payment, personnel should determine where practical whether payment may already have been processed.

---

# 70. Payroll

Payroll is normally Moderate criticality but may increase to High as a biweekly payroll deadline approaches.

Manual payroll processing must preserve required authorization and reconciliation.

---

# 71. Payroll Changes

Manual changes to:

- Compensation
- Employee banking information
- Deductions
- Payroll status

require appropriate authorization and verification.

---

# 72. Employee Payment Changes

Suspicious changes to employee payment information should be independently verified through a trusted method.

---

# 73. Human Resources

Human Resources manual records must protect sensitive personnel information.

Access must remain limited to authorized personnel.

---

# 74. Manual Records During Internet Outage

A local Internet outage may require temporary manual activity even when cloud systems remain operational elsewhere.

Affected facilities should use manual continuity only for functions that cannot reasonably continue through approved cellular connectivity or other available means.

---

# 75. Company-Issued Cellular Capability

Company-issued phones or cellular connectivity may allow some personnel to continue business activity without switching fully to manual processing.

---

# 76. Cellular Limitation

Cellular connectivity must not be assumed to support:

- All warehouse devices
- Every workstation
- Full facility capacity
- Every peripheral
- Every business function

---

# 77. Regional Outage

A regional disruption may affect:

- Wired Internet
- Cellular communications
- Power
- Transportation
- Personnel

Manual processing must adapt to available resources.

---

# 78. Cyber Incident

Manual processing may be required when systems are intentionally isolated during a security incident.

---

# 79. Security Isolation

Employees must not reconnect an isolated system merely to avoid manual processing.

Security containment decisions remain under the applicable Incident Response process.

---

# 80. Ransomware

Ransomware may require manual continuity while systems are:

- Isolated
- Investigated
- Rebuilt
- Restored
- Validated

Response follows [[PBK-002 Malware & Ransomware Playbook]].

---

# 81. Unauthorized Access

If systems are unavailable because of unauthorized access, manual operations must not recreate the same access weakness as a workaround.

---

# 82. Data Corruption

When system data may be corrupted, manual processing may be used while the trustworthy recovery point is determined.

---

# 83. Manual Processing Start Record

For significant manual processing, the responsible function should record:

- Reason for activation
- Affected system
- Start date and time
- Responsible manager
- Manual process being used
- Known limitations

---

# 84. Transaction Batches

Where practical, manual transactions should be organized into identifiable batches.

---

# 85. Batch Identification

A batch may identify:

- Business function
- Date
- Location
- Sequence
- Responsible employee

---

# 86. Batch Control

Batch control may be used to compare:

- Transactions created
- Transactions reviewed
- Transactions entered
- Transactions reconciled
- Transactions verified

---

# 87. Stage One: Collect

The first stage is:

**Collect**

Required business information is captured in an approved temporary record.

---

# 88. Collect Requirements

Collection should capture enough information to:

- Understand the transaction.
- Identify responsible personnel.
- Establish required authorization.
- Enter the transaction later.
- Reconcile it after entry.

---

# 89. Collection Accuracy

Employees should record information at the time of the transaction where practical.

Reliance on later memory should be minimized.

---

# 90. Stage Two: Review

The second stage is:

**Review**

A manual transaction must be reviewed as required before system entry or further processing.

---

# 91. Review Requirements

Review should evaluate:

- Completeness
- Legibility
- Required authorization
- Obvious error
- Possible duplication
- Required supporting information

---

# 92. Review Responsibility

The reviewer should be someone authorized and reasonably capable of evaluating the transaction.

For higher-risk transactions, the reviewer should be independent of the originator where practical.

---

# 93. Review Result

The review should result in one of the following:

- Approved for processing
- Returned for correction
- Held for investigation
- Rejected

---

# 94. Corrected Manual Record

Corrections must preserve accountability.

Original information should not be obscured in a manner that prevents understanding what changed.

---

# 95. Stage Three: Enter

The third stage is:

**Enter**

After normal systems return, authorized personnel enter approved manual transactions into the appropriate system.

---

# 96. Entry Timing

System entry should begin after:

- The system is restored.
- Required technical validation is complete.
- Required security validation is complete.
- Business use is authorized.

---

# 97. Entry Authorization

Only personnel normally authorized for the applicable transaction should enter it unless a documented continuity exception applies.

---

# 98. Entry Sequence

Where sequence affects business accuracy, transactions should be entered in an appropriate chronological or dependency order.

---

# 99. Temporary Identifier Retention

The temporary manual identifier should be retained in the electronic record or reconciliation documentation where practical.

This supports traceability between manual and electronic records.

---

# 100. Entry Confirmation

The employee entering the transaction should record sufficient information to show:

- Transaction entered
- Date entered
- Electronic reference
- Employee performing entry

---

# 101. Duplicate Check Before Entry

Before entering a manual transaction, personnel must determine where practical whether the transaction already exists in the restored system.

---

# 102. Duplicate Found

If the transaction already exists:

- Do not enter it again.
- Link the manual record to the existing electronic transaction.
- Investigate discrepancies where necessary.

---

# 103. Conflicting Record

If the restored system contains a transaction that conflicts with the manual record, personnel must not silently choose one version.

The discrepancy must be investigated.

---

# 104. Stage Four: Reconcile

The fourth stage is:

**Reconcile**

Manual records are compared against electronic records after entry.

---

# 105. Reconciliation Objective

Reconciliation identifies:

- Missing transactions
- Duplicate transactions
- Incorrect transactions
- Incomplete transactions
- Unauthorized transactions
- Unresolved differences

---

# 106. Reconciliation Scope

Reconciliation should include all material manual activity performed during the outage.

---

# 107. Reconciliation Sources

Depending on the process, reconciliation may compare:

- Manual transaction records
- Electronic system records
- Orders
- Inventory
- Receiving
- Shipping
- Invoices
- Payments
- Payroll
- Customer records
- Supplier records

---

# 108. Order Reconciliation

Manual orders should be reconciled against:

- Restored Order Management System records
- Infinity orders
- Sales-assisted orders
- Fulfillment records
- Shipping records

where applicable.

---

# 109. Inventory Reconciliation

Manual inventory movement must be reconciled against:

- WMS records
- Receiving records
- Shipping records
- Physical inventory information
- Order records

as appropriate.

---

# 110. Financial Reconciliation

Manual financial activity should be reconciled against:

- Accounting records
- Bank or payment records
- Invoices
- Vendor records
- Payroll records

as applicable.

---

# 111. Sequence Reconciliation

Missing sequential manual records should be investigated.

A missing number does not automatically establish loss or fraud, but it must be explained where the sequence is used as a control.

---

# 112. Duplicate Transaction

A duplicate transaction should be:

1. Identified.
2. Evaluated.
3. Corrected where authorized.
4. Documented.
5. Investigated further when suspicious.

---

# 113. Missing Transaction

A missing transaction should be:

1. Identified.
2. Located or reconstructed where possible.
3. Entered when authorized.
4. Documented.
5. Escalated when material or suspicious.

---

# 114. Incorrect Transaction

An incorrect transaction should be corrected through normal authorized business procedures.

The correction must remain traceable.

---

# 115. Unauthorized Transaction

A suspected unauthorized transaction must be escalated as a potential security or fraud event.

---

# 116. Unresolved Discrepancy

A discrepancy that cannot be resolved must remain documented and be escalated based on:

- Business impact
- Financial impact
- Information sensitivity
- Security implications

---

# 117. Stage Five: Verify

The fifth stage is:

**Verify**

The responsible business function confirms that manual continuity activity has been appropriately incorporated into normal operations.

---

# 118. Verification Objective

Verification provides reasonable assurance that:

- Required transactions were entered.
- Reconciliation was completed.
- Material discrepancies were addressed.
- Required records remain available.
- Normal processing can continue.

---

# 119. Verification Responsibility

Verification should be performed by:

- Business owner
- Responsible manager
- Qualified designee

with sufficient authority and understanding of the process.

---

# 120. Verification Is Not Data Entry

The person verifying the completed process should not merely confirm that someone marked the records as entered.

Verification should consider the reconciliation result.

---

# 121. Verification Evidence

Verification evidence may include:

- Signed or initialed reconciliation
- Manager approval
- Completed batch record
- Electronic review record
- Documented exception list

---

# 122. Manual Processing Completion

Manual continuity processing is not complete until all five stages are addressed:

**Collect → Review → Enter → Reconcile → Verify**

---

# 123. System Recovery Does Not End Manual Processing

Restoration of the affected system ends the need to create new manual transactions only when business use resumes.

It does not complete outstanding:

- Entry
- Reconciliation
- Verification

activities.

---

# 124. Return to Normal Processing

The responsible manager should authorize return to normal processing after:

- The system is available.
- Required technical validation is complete.
- Required security validation is complete.
- Business functionality is confirmed.

---

# 125. Cutoff Time

A clear cutoff should be established between:

- Transactions handled manually
- Transactions handled normally after restoration

This reduces duplicate processing.

---

# 126. Cutoff Communication

Personnel involved in the affected process should be informed when manual transaction creation stops and normal system processing resumes.

---

# 127. Outstanding Manual Records

Outstanding manual records must remain controlled until:

- Entered
- Reconciled
- Verified
- Retained or disposed of according to requirements

---

# 128. Record Retention

Manual continuity records must be retained according to applicable business, legal, financial, and information-retention requirements.

---

# 129. Secure Disposal

Temporary manual records that are no longer required must be securely disposed of according to their information classification.

---

# 130. Manual Processing Failure

A manual-processing failure may include:

- Missing transaction
- Duplicate transaction
- Incorrect transaction
- Unauthorized transaction
- Missing record
- Failed reconciliation
- Unresolved inventory discrepancy
- Unresolved financial discrepancy

---

# 131. Significant Error

A significant manual-processing error must be documented and evaluated for:

- Business impact
- Customer impact
- Financial impact
- Security impact
- Root cause
- Corrective action

---

# 132. Security Event Escalation

Suspected:

- Fraud
- Unauthorized activity
- Data exposure
- Deliberate record alteration
- Theft
- Security-control bypass

must be escalated under [[PROC-010 Security Event Escalation Procedure]].

---

# 133. Evidence Handling

Evidence associated with suspected misconduct or a security incident must follow [[PROC-011 Evidence Handling Procedure]].

---

# 134. Incident Response

When manual processing is associated with a security incident, coordination must occur with [[PLN-001 Incident Response Plan]].

---

# 135. Business Continuity Coordination

Significant manual processing activity should be coordinated under [[PLN-002 Business Continuity Plan]].

---

# 136. Disaster Recovery Coordination

Technology restoration supporting manual processing transition is governed by [[PLN-003 Disaster Recovery Plan]].

---

# 137. Cloud Exit Coordination

Manual processing may support business continuity during cloud migration under [[PLN-004 Cloud Exit & Emergency Migration Plan]].

---

# 138. Manual Processing Exercise

Manual continuity capability should be exercised periodically.

---

# 139. Exercise Objective

A manual-processing exercise should determine whether personnel can complete:

**Collect → Review → Enter → Reconcile → Verify**

using documented procedures.

---

# 140. Exercise Scope

An exercise should identify:

- Business process
- Outage scenario
- Participants
- Manual records
- Required approvals
- System restoration assumption
- Reconciliation method
- Success criteria

---

# 141. Full Lifecycle Exercise

A manual-processing exercise that stops after collecting paper transactions does not demonstrate complete manual continuity capability.

The exercise should include reconciliation and verification where practical.

---

# 142. Order Processing Exercise

An Order Processing exercise may simulate:

1. Order system outage.
2. Manual customer order.
3. Review.
4. System restoration.
5. Electronic entry.
6. Duplicate check.
7. Reconciliation.
8. Verification.

---

# 143. Warehouse Exercise

A Warehouse Operations exercise may simulate:

1. WMS outage.
2. Manual pick or inventory movement.
3. Manual shipping record.
4. WMS restoration.
5. Transaction entry.
6. Inventory reconciliation.
7. Verification.

---

# 144. Financial Exercise

A financial manual-processing exercise should preserve appropriate authorization and Separation of Duties.

The exercise should not require actual payment movement merely to demonstrate the control.

---

# 145. Exercise Evidence

Exercise evidence should include:

- Date
- Scenario
- Process
- Participants
- Records created
- Review result
- Entry result
- Reconciliation result
- Verification result
- Errors
- Findings
- Corrective actions

---

# 146. Exercise Limitations

Any limitation affecting the realism of an exercise must be documented.

---

# 147. Failed Exercise

A failed manual-processing exercise is useful assurance evidence.

Failure should result in:

1. Documentation.
2. Analysis.
3. Corrective action.
4. Retesting where appropriate.
5. Risk reassessment when material.

---

# 148. No Manufactured Evidence

Personnel must not:

- Backdate manual-processing exercises.
- Invent transactions that were not tested.
- Hide reconciliation failures.
- Record unperformed verification as complete.
- Change results to make the process appear effective.

---

# 149. Findings

A finding is a documented conclusion supported by evidence concerning whether a requirement, control, process, or expected outcome was satisfied.

---

# 150. Manual Processing Findings

Potential findings include:

- Required manual form unavailable
- Transactions not individually attributable
- Required approval missing
- Duplicate transaction
- Missing transaction
- Reconciliation incomplete
- Verification not performed
- Sensitive records inadequately protected
- Personnel unable to perform documented procedure

---

# 151. Corrective Action

Material deficiencies must identify:

- Finding
- Required action
- Accountable owner
- Due date
- Validation method
- Retest requirement where appropriate

Material corrective actions are tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 152. Corrective-Action Validation

A corrective action is not complete solely because an assigned task is marked finished.

Validation must determine whether the identified manual-processing weakness was corrected.

---

# 153. Assessment Methods

Manual-processing assurance may use:

- Inspection
- Observation
- Interviews
- Sampling
- Exercises
- Reconciliation
- Independent Performance

---

# 154. Independent Performance

An assessor may independently perform an authorized manual-processing scenario.

For example:

1. Select a business process.
2. Define a system outage.
3. Create an authorized test transaction.
4. Record the transaction manually.
5. Perform the required review.
6. Enter the transaction into a controlled test or authorized environment.
7. Reconcile the manual and electronic records.
8. Verify the result.
9. Document any control weakness.

---

# 155. Sampling

An assessor may select a sample of manual transactions and determine whether each includes:

- Required information
- Employee accountability
- Required approval
- Electronic entry
- Reconciliation
- Verification

---

# 156. Manual Processing Metrics

Metrics may include:

- Manual-processing activations
- Manual transactions created
- Manual transactions reconciled
- Duplicate transactions
- Missing transactions
- Reconciliation errors
- Unresolved discrepancies
- Manual-processing exercises completed
- Exercise failures
- Open corrective actions

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 157. Key Performance Indicators

Key Performance Indicators (KPIs) may include:

- Percentage of manual transactions successfully reconciled
- Percentage of manual transaction batches verified
- Percentage of required manual-processing exercises completed
- Percentage of manual-processing corrective actions completed and validated

---

# 158. Key Risk Indicators

Key Risk Indicators (KRIs) may include:

- Unreconciled Critical-process transactions
- Repeated duplicate transactions
- Missing manual records
- Unresolved inventory discrepancy
- Unresolved financial discrepancy
- Manual transaction without required approval
- Repeated manual-processing exercise failure
- Overdue material corrective action

---

# 159. Metric Interpretation

Manual-processing metrics must be interpreted in context.

A higher number of identified discrepancies may result from:

- Poorer process performance
- More extensive reconciliation
- Better detection
- Greater outage volume

The number alone does not establish control effectiveness.

---

# 160. R033 Manual Outage Processing Error

R033 has:

- Inherent risk: **12 High**
- Current residual risk: **9 Moderate**
- Target residual risk: **4 Low**

---

# 161. R033 Treatment

Treatment for R033 includes:

- Documented manual procedures
- Standardized temporary records
- Individual accountability
- Review before system entry
- Reconciliation
- Verification
- Training
- Exercises

---

# 162. R033 Control Objective

The primary control objective for R033 is to ensure that temporary manual operations can later be incorporated into authoritative systems without unacceptable:

- Loss
- Duplication
- Error
- Unauthorized activity

---

# 163. R020 Supplier Disruption

Manual procurement and supplier coordination may support continuity during R020 Supplier Disruption.

---

# 164. R028 Data Corruption

Manual processing may support operations while trustworthy data is restored following R028 Data Corruption.

Manual records must later be reconciled against validated recovered data.

---

# 165. R016 Cloud Outage

Manual processing may support essential business functions during R016 Cloud Outage when cloud-hosted systems are unavailable.

---

# 166. R017 ISP Outage

Manual processing may support functions that cannot continue through available company-issued cellular connectivity during R017 ISP Outage.

---

# 167. R023 Utility / Power / HVAC Failure

Manual processing may support limited operations during facility utility disruption when safety and operating conditions permit.

---

# 168. R034 Loss of Headquarters

Manual continuity and distributed operations may support selected business processes during R034 Loss of Headquarters.

---

# 169. R035 Regional Disaster

Manual processing may support continuity during R035 Regional Disaster, but widespread:

- Personnel loss
- Power failure
- Telecommunications failure
- Transportation disruption

may substantially limit manual capability.

---

# 170. Current and Proposed Controls

Manual-processing records must distinguish among:

- Current controls
- Partially implemented controls
- Planned controls
- Implemented controls awaiting validation
- Validated controls

---

# 171. No Premature Risk Credit

Current residual risk must not be reduced merely because:

- This procedure exists.
- Manual forms have been designed.
- Training is planned.
- An exercise is scheduled.
- A corrective action is assigned.

Risk reduction requires implementation and appropriate validation.

---

# 172. Target Residual Risk

Target residual risk represents expected risk after planned treatment.

It is a prediction rather than a guaranteed outcome.

---

# 173. Validated Post-Treatment Risk

After controls are implemented and validated, actual risk may be reassessed.

Validated post-treatment risk may be:

- Higher than target
- Equal to target
- Lower than target

Evidence determines the result.

---

# 174. Historical Risk Integrity

The original May 2013 risk assessment must remain preserved.

Future validated assessments may establish a new current residual risk without rewriting the historical assessment.

---

# 175. Control Effectiveness

Manual-processing evidence may support conclusions that relevant controls are:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

Control effectiveness must reflect actual operation and evidence rather than procedure existence.

---

# 176. Training

Personnel expected to perform significant manual continuity duties should understand:

- When manual processing is used
- Required records
- Authorization requirements
- Information protection
- The five-stage lifecycle
- Reconciliation responsibilities
- Escalation requirements

---

# 177. Procedure Availability

Required manual-processing instructions and forms must remain accessible when the normal system is unavailable.

---

# 178. Form Availability

Where predesigned manual forms are required for Critical processes, reasonable copies should be maintained in a location accessible during system outages.

---

# 179. Form Protection

Unused controlled forms should be protected appropriately when their format or numbering could be misused.

---

# 180. Local Procedure Variations

A branch or business function may maintain process-specific manual instructions consistent with this procedure.

Local instructions must not weaken enterprise requirements.

---

# 181. Process-Specific Requirements

Process-specific manual instructions should identify:

- Trigger
- Required form
- Required fields
- Authorization
- Reviewer
- Record custody
- Entry method
- Reconciliation method
- Verification authority

---

# 182. Process Changes

Material changes to business processes must include review of associated manual continuity capability.

---

# 183. Technology Changes

A significant technology change is not complete until related manual continuity and recovery documentation has been reviewed where applicable.

---

# 184. Procedure Exceptions

Exceptions must be:

- Documented
- Justified
- Risk evaluated
- Approved under appropriate authority
- Time-limited where practical
- Reviewed when conditions change

---

# 185. Traceability

This procedure supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Manual continuity is not complete when a paper record is created.

The full control chain requires:

**Collect → Review → Enter → Reconcile → Verify**

---

# 186. Related Artifacts

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
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-011 Physical & Environmental Security Policy]]
- [[STD-001 Information Classification Standard]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

---

# 187. Review

This procedure must be reviewed:

- At least annually
- Following material business-process change
- Following significant continuity activation
- Following significant technology change
- Following material manual-processing failure
- Following material exercise findings

The COO coordinates business-process review.

The CIO coordinates technology and security review.

Material revisions require CIO approval.

---

# 188. Revision History

| Version | Date     | Description                         | Approval |
| ------- | -------- | ----------------------------------- | -------- |
| 1.0     | May 2013 | Initial Manual Processing Procedure | CIO      |