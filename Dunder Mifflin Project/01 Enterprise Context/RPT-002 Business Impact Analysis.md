# RPT-002 Business Impact Analysis

## Document Control

| Field | Value |
|---|---|
| Document ID | RPT-002 |
| Title | Business Impact Analysis |
| Version | 1.0 |
| Classification | Confidential |
| Status | Approved |
| Owner | COO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Business Change |

---

# 1. Purpose

This Business Impact Analysis (BIA) identifies Dunder Mifflin's important business processes, evaluates the consequences of disruption, establishes business criticality, identifies significant dependencies, and defines recovery requirements.

The BIA provides the business basis for Business Continuity/Disaster Recovery (BC/DR) planning.

The BIA establishes:

- Business-process criticality
- Maximum Tolerable Downtime (MTD)
- Recovery Time Objective (RTO)
- Recovery Point Objective (RPO)
- Significant business dependencies
- Principal outage impacts
- Recovery priorities
- Manual continuity requirements

Recovery requirements established through the BIA guide later continuity strategies, technical recovery design, implementation, and testing.

---

# 2. Scope

The BIA evaluates the principal business functions and supporting capabilities identified through [[REG-001 Enterprise Asset Register]].

The assessment includes:

- Order processing
- Warehouse operations
- Inventory management
- Shipping and delivery
- Internet connectivity
- Identity and authentication
- Customer Relationship Management
- Email
- Accounting
- Procurement
- File services
- Infinity
- Customer service
- Human Resources
- Payroll
- Accounts payable
- Quality assurance
- Legal and Compliance
- Corporate website

The BIA evaluates business impact rather than attempting to assign recovery objectives independently to every individual technical component.

Recovery requirements for supporting systems and technical components must be derived from the business processes they enable, their role in those processes, applicable dependencies, and available continuity alternatives. A supporting system does not automatically inherit the most aggressive RTO or RPO of every business process it supports. Technical recovery objectives must be sufficient to enable the applicable business-process recovery requirements.

---

# 3. BIA Principles

## 3.1 Business Requirements Drive Recovery

Recovery requirements must originate from business needs.

The required sequence is:

**Business Requirement → Criticality → MTD → RTO/RPO → Recovery Strategy → Technical Design → Implementation → Testing**

Technology does not determine acceptable business downtime.

---

## 3.2 Safety Takes Priority

Human life and safety take priority over:

- Systems
- Operations
- Facilities
- Equipment
- Inventory
- Revenue
- Other company assets

Personnel must not place themselves at unreasonable risk to maintain or restore business operations.

---

## 3.3 Availability Has Multiple Meanings

The BIA distinguishes among:

### Facility Availability

Whether personnel can safely use a physical location.

### System Availability

Whether a technology system or service is functioning.

### Business-Process Availability

Whether the organization can perform the required business activity.

These conditions are related but are not interchangeable.

A facility may be unavailable while a business process continues remotely.

A system may be unavailable while a business process continues temporarily through manual procedures.

A facility and its systems may both be operational while a business process remains unavailable because required personnel, suppliers, or information are unavailable.

---

# 4. BIA Definitions

## 4.1 Maximum Tolerable Downtime

**Maximum Tolerable Downtime (MTD)** is the maximum period a business process can remain disrupted before the resulting impact becomes unacceptable to Dunder Mifflin.

MTD represents a business limit rather than a recovery target.

---

## 4.2 Recovery Time Objective

**Recovery Time Objective (RTO)** is the target time within which a business process or supporting capability should be restored following disruption.

RTO must be shorter than the applicable MTD.

---

## 4.3 Recovery Point Objective

**Recovery Point Objective (RPO)** represents the maximum acceptable amount of data loss measured backward in time from the disruption.

For example, an RPO of four hours means the recovery capability should permit restoration without losing more than approximately four hours of relevant data.

RPO does not mean the system must be restored within four hours.

---

## 4.4 Criticality

Criticality reflects the relative importance and time sensitivity of a business process.

Dunder Mifflin uses:

- Critical
- High
- Moderate
- Low

Criticality supports prioritization but does not replace the specific MTD, RTO, and RPO requirements.

---

# 5. Impact Considerations

Business impact may include:

- Personnel safety
- Customer impact
- Lost sales
- Lost revenue
- Delayed revenue
- Order backlog
- Fulfillment disruption
- Inventory uncertainty
- Shipping delays
- Payroll disruption
- Financial-processing delays
- Fraud exposure
- Data loss
- Contractual consequences
- Legal consequences
- Supplier disruption
- Employee productivity loss
- Customer dissatisfaction
- Reputation damage
- Increased manual work
- Reconciliation requirements
- Recovery costs

The significance of an impact may increase as an outage continues.

---

# 6. BIA Summary

| Business Process / Capability | Criticality | MTD | RTO | RPO |
|---|---|---:|---:|---:|
| Order Processing | Critical | 3 days | 8 hours | 4 hours |
| Warehouse Operations | Critical | 3 days | 8 hours | 4 hours |
| Inventory Management | High | 3 days | 12 hours | 4 hours |
| Shipping and Delivery | High | 3 days | 12 hours | 8 hours |
| Internet Connectivity | High | 24 hours | 4 hours | N/A |
| Identity and Authentication | High | 24 hours | 4 hours | 4 hours |
| Customer Relationship Management | High | 3 days | 12 hours | 8 hours |
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
| Legal and Compliance | Moderate | 5 business days | 2 business days | 1 business day |
| Corporate Website | Low | 7 days | 3 days | 24 hours |

**Payroll may temporarily become High priority as a payroll-processing deadline approaches.**

---

# 7. Order Processing

**Criticality:** Critical  
**MTD:** 3 days  
**RTO:** 8 hours  
**RPO:** 4 hours

## Business Function

Order Processing converts customer demand into actionable fulfillment activity.

Orders may originate through:

- Sales personnel
- Customer service
- Infinity

Orders ultimately enter the company's fulfillment process.

## Major Dependencies

- Order Management System
- Customer Relationship Management
- Warehouse Management System
- Internet connectivity
- Active Directory
- Employee endpoints
- Sales personnel
- Customer service personnel
- Warehouse personnel

## Disruption Impact

A prolonged outage may cause:

- Inability to process new orders normally
- Order backlog
- Delayed fulfillment
- Delayed revenue
- Customer dissatisfaction
- Increased manual processing
- Increased reconciliation requirements
- Potential duplicate or missing orders

## Continuity Considerations

Orders may be recorded manually during a system outage when sufficient customer and product information is available.

Manual transactions must later be entered, reconciled, and verified.

---

# 8. Warehouse Operations

**Criticality:** Critical  
**MTD:** 3 days  
**RTO:** 8 hours  
**RPO:** 4 hours

## Business Function

Warehouse Operations supports:

- Receiving
- Storage
- Picking
- Packing
- Fulfillment
- Inventory handling
- Shipping preparation

## Major Dependencies

- Warehouse Management System
- Warehouse personnel
- Inventory
- Warehouse workstations
- Handheld/barcode devices
- Facility access
- Power
- Local network connectivity
- Order information

## Disruption Impact

A prolonged outage may result in:

- Fulfillment delays
- Shipping delays
- Inventory uncertainty
- Order backlog
- Increased manual work
- Customer dissatisfaction
- Increased error rates
- Revenue delays

## Continuity Considerations

Limited warehouse activity may continue using controlled manual records.

Manual activity must preserve sufficient information to permit later system entry and reconciliation.

---

# 9. Inventory Management

**Criticality:** High  
**MTD:** 3 days  
**RTO:** 12 hours  
**RPO:** 4 hours

## Business Function

Inventory Management maintains accurate information concerning:

- Inventory quantities
- Inventory location
- Receiving
- Picking
- Shipping
- Adjustments
- Reconciliation

## Major Dependencies

- Warehouse Management System
- Warehouse personnel
- Receiving records
- Shipping records
- Inventory counts
- Warehouse devices

## Disruption Impact

Loss of accurate inventory information may cause:

- Incorrect fulfillment
- Overselling
- Delayed orders
- Purchasing errors
- Increased theft or fraud opportunity
- Reconciliation difficulty
- Customer dissatisfaction

## Continuity Considerations

Manual inventory records may temporarily support operations but require later reconciliation against the authoritative system.

---

# 10. Shipping and Delivery

**Criticality:** High  
**MTD:** 3 days  
**RTO:** 12 hours  
**RPO:** 8 hours

## Major Dependencies

- Completed orders
- Warehouse operations
- Inventory
- Shipping information
- Vehicles
- Authorized drivers
- Third-party carriers where applicable
- Personnel

## Disruption Impact

Potential consequences include:

- Delayed customer delivery
- Accumulation of completed orders
- Customer dissatisfaction
- Revenue delay
- Increased storage requirements
- Rescheduling and coordination costs

A transportation disruption does not necessarily prevent order processing or warehouse preparation from continuing.

---

# 11. Internet Connectivity

**Criticality:** High  
**MTD:** 24 hours  
**RTO:** 4 hours  
**RPO:** Not Applicable

Internet connectivity does not represent stored business data and does not receive an RPO.

## Major Dependencies

- Internet Service Provider
- Firewall/router
- Local network
- Facility power
- Provider infrastructure

## Business Dependencies

Internet connectivity supports:

- Cloud-hosted business systems
- Email
- CRM
- Infinity administration
- Remote services
- Business communications

## Continuity Considerations

Company-issued cellular connectivity may provide temporary secondary Internet access for applicable personnel and functions.

Not every warehouse or business activity can operate fully through cellular connectivity.

Manual processes may be required for functions that cannot continue through the alternate connection.

---

# 12. Identity and Authentication

**Criticality:** High  
**MTD:** 24 hours  
**RTO:** 4 hours  
**RPO:** 4 hours

## Major Dependencies

- Active Directory
- Cloud hosting
- Domain controllers
- Network connectivity
- Administrative personnel
- Authentication configuration

## Disruption Impact

Loss of authentication services may prevent personnel from accessing multiple systems and resources even when those systems remain technically operational.

Potential impacts include:

- User login failures
- Administrative access problems
- Application access failures
- Delayed business operations
- Recovery complications

Identity services must be included in technical recovery planning because other recovery activities may depend on them.

---

# 13. Customer Relationship Management

**Criticality:** High  
**MTD:** 3 days  
**RTO:** 12 hours  
**RPO:** 8 hours

CRM supports:

- Customer information
- Sales activity
- Customer history
- Relationship management
- Sales coordination

## Major Dependencies

- Internet
- Authentication
- Endpoints
- Sales personnel
- Customer information

## Disruption Impact

An extended outage may reduce sales effectiveness, impair customer service, delay follow-up activity, and increase reliance on incomplete manual information.

---

# 14. Email

**Criticality:** High  
**MTD:** 2 days  
**RTO:** 8 hours  
**RPO:** 4 hours

Email supports:

- Internal communication
- Customer communication
- Supplier communication
- Management coordination
- Security communication
- Operational coordination

## Continuity Considerations

Company-issued mobile phones and other approved communication methods may provide temporary alternate communications.

Alternate communications do not eliminate the need to restore email.

---

# 15. Accounting

**Criticality:** High  
**MTD:** 5 business days  
**RTO:** 24 hours  
**RPO:** 8 hours

Accounting supports:

- Financial records
- Invoicing
- Reconciliation
- Accounts receivable
- Financial reporting
- Payment-related activity

## Disruption Impact

An extended outage may cause:

- Delayed invoicing
- Delayed revenue collection
- Reconciliation problems
- Financial-reporting delays
- Increased manual processing
- Payment errors

---

# 16. Procurement

**Criticality:** High  
**MTD:** 5 business days  
**RTO:** 2 business days  
**RPO:** 1 business day

Procurement supports inventory replenishment and supplier relationships.

## Major Dependencies

- Suppliers
- Communications
- Inventory information
- Accounting
- Authorized personnel

## Disruption Impact

A prolonged outage may cause:

- Inventory shortages
- Delayed replenishment
- Fulfillment problems
- Increased purchasing costs
- Supplier coordination problems

Existing inventory may provide temporary operational tolerance.

---

# 17. File Services

**Criticality:** High  
**MTD:** 3 days  
**RTO:** 12 hours  
**RPO:** 8 hours

File services provide shared access to business documents and operational information.

## Disruption Impact

An extended outage may affect multiple departments simultaneously and may interfere with:

- Business records
- Procedures
- Operational documents
- Financial information
- Management information
- Recovery information

Critical recovery documentation must not exist exclusively on file services that may themselves require recovery.

---

# 18. Infinity Online Ordering

**Criticality:** Moderate  
**MTD:** 3 days  
**RTO:** 24 hours  
**RPO:** 4 hours

## Business Function

Infinity provides customers with an online ordering channel.

## Major Dependencies

- Cloud hosting
- Internet connectivity
- Web function
- Application function
- Database
- Application configuration
- Source code
- Contractor support
- Order processing
- Warehouse fulfillment

## Disruption Impact

An Infinity outage may result in:

- Loss of online ordering
- Customer inconvenience
- Increased reliance on Sales and Customer Service
- Delayed online revenue
- Increased manual workload

## Continuity Considerations

Infinity is not the company's only method for receiving customer orders.

Customers may continue placing orders through Sales or Customer Service during an Infinity-specific outage.

This alternate business channel provides greater downtime tolerance than Order Processing itself.

---

# 19. Customer Service

**Criticality:** Moderate  
**MTD:** 3 days  
**RTO:** 24 hours  
**RPO:** 8 hours

Customer Service supports:

- Customer inquiries
- Order assistance
- Order status
- Problem resolution
- Alternate ordering support

## Major Dependencies

- CRM
- Email
- Order information
- Personnel
- Communications

An extended disruption may increase customer dissatisfaction and reduce the company's ability to compensate for disruptions in other sales channels.

---

# 20. Human Resources

**Criticality:** Moderate  
**MTD:** 5 business days  
**RTO:** 2 business days  
**RPO:** 1 business day

Human Resources supports:

- Employee records
- Employment status
- Personnel actions
- Access lifecycle information
- Compensation information
- Management support

HR is the authoritative business source for employee status.

Temporary HR system disruption may be managed manually for limited periods when records and appropriate personnel remain available.

---

# 21. Payroll

**Normal Criticality:** Moderate  
**Time-Sensitive Criticality:** High near payroll deadline  
**MTD:** 5 business days  
**RTO:** 2 business days  
**RPO:** 1 business day

Payroll has time-dependent criticality.

An outage occurring immediately after payroll completion may permit more recovery time than an outage immediately before payroll must be processed.

## Disruption Impact

Failure to process payroll may cause:

- Employee hardship
- Employee dissatisfaction
- Administrative burden
- Financial reconciliation issues
- Legal or contractual concerns

Recovery priority must increase as the payroll deadline approaches.

---

# 22. Accounts Payable

**Criticality:** Moderate  
**MTD:** 5 business days  
**RTO:** 2 business days  
**RPO:** 1 business day

Accounts Payable supports vendor payment and supplier relationships.

A prolonged disruption may result in:

- Late vendor payments
- Supplier concerns
- Penalties
- Reconciliation problems
- Potential supply disruption

---

# 23. Quality Assurance

**Criticality:** Moderate  
**MTD:** 5 business days  
**RTO:** 2 business days  
**RPO:** 1 business day

Quality Assurance supports operational quality and process consistency.

A temporary disruption may be tolerated, but extended loss may increase:

- Operational errors
- Customer complaints
- Process inconsistencies
- Corrective workload

---

# 24. Legal and Compliance

**Criticality:** Moderate  
**MTD:** 5 business days  
**RTO:** 2 business days  
**RPO:** 1 business day

Legal and Compliance supports:

- Contracts
- Investigations
- Legal matters
- Confidentiality obligations
- Compliance matters
- Security incidents with legal implications

The urgency of Legal and Compliance activity may increase immediately when a significant security incident, legal deadline, investigation, or contractual matter occurs.

---

# 25. Corporate Website

**Criticality:** Low  
**MTD:** 7 days  
**RTO:** 3 days  
**RPO:** 24 hours

The corporate website primarily provides public information.

An outage may cause:

- Customer inconvenience
- Reputation concerns
- Loss of public information availability

The website is not the primary order-processing capability and receives lower recovery priority than Infinity and core business-processing systems.

---

# 26. Recovery Priority

The general recovery priority is:

## Priority 1: Safety

Before business recovery:

- Protect personnel.
- Account for personnel where required.
- Follow emergency instructions.
- Do not enter unsafe facilities.
- Do not attempt equipment recovery when unsafe.

## Priority 2: Critical Business Functions

Restore capabilities necessary for:

- Order Processing
- Warehouse Operations

## Priority 3: High-Priority Functions

Restore capabilities supporting:

- Inventory Management
- Shipping and Delivery
- Internet Connectivity
- Identity and Authentication
- CRM
- Email
- Accounting
- Procurement
- File Services

## Priority 4: Moderate-Priority Functions

Restore:

- Infinity
- Customer Service
- Human Resources
- Payroll
- Accounts Payable
- Quality Assurance
- Legal and Compliance

Priority may change according to business conditions.

For example, Payroll may move ahead of other Moderate functions when a payroll deadline is imminent.

## Priority 5: Low-Priority Functions

Restore the Corporate Website after higher-priority recovery requirements have been addressed unless circumstances justify earlier recovery.

---

# 27. Recovery Dependencies

Recovery sequencing must account for dependencies.

For example, restoring an application may provide little business value if required authentication, connectivity, data, or personnel remain unavailable.

A simplified dependency sequence may include:

**Safety → Communications/Connectivity → Authentication → Core Systems → Business Applications → Business Processes → Reconciliation**

Actual sequencing depends on the incident.

---

# 28. Manual Continuity

Manual processing provides temporary continuity for selected business processes.

Manual processing may support:

- Order intake
- Warehouse activity
- Inventory records
- Shipping records
- Customer communication
- Selected financial activities

Manual processes are not considered equivalent to normal system operation.

They may:

- Reduce capacity
- Increase error rates
- Increase fraud opportunity
- Require additional review
- Create reconciliation work
- Delay downstream processing

Manual transactions must follow:

**Collect → Review → Enter → Reconcile → Verify**

Detailed requirements are maintained in [[PROC-013 Manual Processing Procedure]].

---

# 29. Manual Record Requirements

Manual records created during an outage should contain sufficient information to reconstruct the business transaction.

Where applicable, records should include:

- Customer
- Order or transaction information
- Responsible employee
- Date
- Time
- Items or services involved
- Quantity
- Approval
- Processing status
- Relevant notes

Manual records must be protected according to the sensitivity of the information they contain.

---

# 30. Return to Normal Operations

Recovery is not complete merely because a system becomes available.

Following restoration, responsible personnel must determine whether:

- Systems are functioning correctly.
- Required data is available.
- Manual transactions have been entered.
- Duplicate transactions have been identified.
- Missing transactions have been investigated.
- Inventory records have been reconciled.
- Financial records have been reconciled where required.
- Customers or suppliers require follow-up.
- Temporary workarounds can be retired.
- Remaining issues require corrective action.

The return to normal operation includes reconciliation and verification.

---

# 31. Backup Requirements

Backup design must support the recovery requirements established by this BIA.

Backup decisions should consider:

- RPO
- RTO
- Data volume
- System dependencies
- Restoration time
- Backup frequency
- Backup location
- Media availability
- Encryption
- Administrative access
- Provider dependency
- Recovery documentation
- Testing

A backup schedule that appears to satisfy an RPO does not demonstrate that the corresponding RTO can be achieved.

---

# 32. Recovery Testing

Recovery capability must be validated through testing.

Testing should determine whether:

- Required backups exist.
- Required data can be restored.
- Recovery documentation is usable.
- Qualified personnel can perform recovery.
- Dependencies are understood.
- Recovered systems function correctly.
- RPO requirements are met.
- RTO requirements are met.
- Business operations can resume.

A successful backup job is not equivalent to a successful recovery test.

---

# 33. Example Recovery Evaluation

Assume a Critical business system has:

- **RTO:** 8 hours
- **RPO:** 4 hours

A recovery test produces:

- Restoration time: **11 hours 37 minutes**
- Data loss: **58 minutes**

Result:

- **RTO: Failed**
- **RPO: Passed**

The system recovered with acceptable data loss, but recovery took longer than the business requirement permits.

A later test produces:

- Restoration time: **6 hours 42 minutes**
- Data loss: **47 minutes**

Result:

- **RTO: Passed**
- **RPO: Passed**

The second test provides evidence that the tested recovery process can satisfy both requirements under the tested conditions.

It does not guarantee that every future recovery will produce the same result.

---

# 34. Facility Loss

Loss of a Dunder Mifflin facility does not automatically mean loss of centralized business systems because major systems are cloud-hosted.

Facility loss may still affect:

- Personnel
- Warehouse operations
- Inventory
- Local network access
- Shipping
- Local equipment
- Records
- Customer service
- Management activities

Continuity strategies must distinguish between loss of a building and loss of centralized technology.

---

# 35. Corporate Headquarters Loss

Loss of corporate headquarters creates significant management and coordination challenges but does not represent loss of a company-operated data center.

Potential impacts include:

- Executive displacement
- Corporate-function disruption
- IT coordination challenges
- Loss of local equipment
- Loss of the controlled Infinity contractor workspace
- Loss of physical records
- Communication challenges

Cloud-hosted systems, off-site backups, mobile equipment, alternate communications, and other Dunder Mifflin facilities provide continuity options.

Headquarters loss is addressed principally through **R034 Loss of Corporate Headquarters**.

---

# 36. Regional Disaster

A regional event may affect multiple resources simultaneously.

Potential impacts include:

- Multiple facilities
- Personnel
- Wired Internet
- Cellular service
- Transportation
- Suppliers
- Utilities
- Shipping
- Management availability

Geographic distribution reduces dependence on a single location but does not eliminate regional risk.

Regional disaster is addressed principally through **R035 Regional Disaster**.

---

# 37. Cloud Service Disruption

Cloud-hosted systems reduce dependence on Dunder Mifflin facilities but introduce dependence on external providers.

Continuity considerations include:

- Provider availability
- Provider support
- Internet access
- Authentication
- Backup availability
- Recovery documentation
- Data portability
- Contractual arrangements
- Migration capability

Dunder Mifflin maintains a [[PLN-004 Cloud Exit & Emergency Migration Plan]].

The company does not maintain a continuously operating alternate cloud environment solely for emergency migration.

---

# 38. Personnel Dependencies

Business recovery may fail even when technology is available if required personnel are unavailable.

Continuity planning must consider:

- Key-person dependencies
- Cross-training
- Alternate personnel
- Delegated authority
- Recovery documentation
- Administrative credentials
- Management succession
- Contractor dependencies

Recovery documentation should contain sufficient information for a qualified professional unfamiliar with the affected system to perform the documented recovery process.

---

# 39. Third-Party Dependencies

Recovery planning must consider significant third parties, including:

- Cloud hosting provider
- Internet Service Providers
- Payment processor
- Infinity support contractor
- Off-site backup provider
- Suppliers
- Shipping and transportation providers
- Building landlords
- Technology vendors

Dunder Mifflin cannot assume that a third party will always remain available during the same event affecting company operations.

---

# 40. BIA Validation

Business owners must review BIA assumptions and recovery requirements.

Validation should confirm:

- The business function remains accurately described.
- Dependencies remain current.
- Criticality remains appropriate.
- MTD remains acceptable.
- RTO remains appropriate.
- RPO remains appropriate.
- Manual alternatives remain practical.
- Recovery priorities remain aligned with business requirements.

Information Technology may advise on technical feasibility but does not independently determine acceptable business downtime.

---

# 41. Change Management

The BIA should be reviewed when material changes occur involving:

- Business processes
- Major systems
- Facilities
- Suppliers
- Cloud providers
- Organizational structure
- Customer channels
- Inventory operations
- Recovery capabilities
- Significant outsourcing
- Legal or contractual requirements

A significant technology or configuration change affecting recovery is not complete until applicable recovery documentation and recovery requirements have been reviewed and updated as necessary.

---

# 42. Relationship to Risk Management

The BIA provides business-impact information used in:

- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]

BIA criticality must not be substituted directly for risk impact scoring.

Risk impact considers the specific risk scenario and consequences.

The BIA provides important evidence for making that determination.

---

# 43. Relationship to Business Continuity and Disaster Recovery

The BIA establishes requirements.

Business Continuity and Disaster Recovery planning determines how those requirements will be satisfied.

The relationship is:

**BIA Requirement → Recovery Strategy → Recovery Design → Procedure → Implementation → Test → Evidence → Improvement**

The primary implementation artifacts are:

- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]
- [[PROC-013 Manual Processing Procedure]]
- [[TMP-003 Recovery Test Template]]

---

# 44. BIA Review Cycle

The BIA must be reviewed:

- At least annually
- Following significant business change
- Following significant technology change affecting recovery
- Following a major incident when assumptions are challenged
- Following recovery testing that demonstrates requirements are impractical or inaccurate
- When management identifies a material change in business tolerance

Changing an RTO or RPO solely because the existing technology cannot meet it is not sufficient justification.

If a business requirement cannot reasonably be achieved, management must evaluate the business requirement, risk, cost, and available recovery strategies before approving a change.

---

# 45. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[REG-001 Enterprise Asset Register]]
- [[STD-001 Information Classification Standard]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]
- [[PROC-013 Manual Processing Procedure]]
- [[TMP-003 Recovery Test Template]]

---

# 46. Revision History

| Version | Date | Description | Approval |
|---|---|---|---|
| 1.0 | May 2013 | Initial Business Impact Analysis | CEO |