# REG-001 Enterprise Asset Register

## Document Control

| Field | Value |
|---|---|
| Document ID | REG-001 |
| Title | Enterprise Asset Register |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | IT & InfoSec Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Change |

---

# 1. Purpose

This register identifies the principal assets and dependencies required to support Dunder Mifflin's business operations.

For purposes of this register, an asset is anything of value to the organization or anything on which an important business function depends.

Assets include:

- Business processes
- Information
- Applications
- Technology infrastructure
- Endpoints and mobile devices
- Facilities
- Personnel and organizational capabilities
- Third-party services
- Recovery resources
- Intellectual property

The register supports information classification, Business Impact Analysis (BIA), enterprise risk assessment, security architecture, continuity planning, access management, and security assurance.

---

# 2. Asset Management Principles

## 2.1 Business Context

Assets must be evaluated according to the business functions they support rather than solely according to their technical characteristics.

A server, application, or network device has value because of the business processes, information, or capabilities that depend on it.

## 2.2 Ownership

Asset ownership represents accountability for determining appropriate business use, protection requirements, access requirements, and acceptable risk.

Ownership does not necessarily mean physical possession or technical administration.

Where multiple departments use or support an asset, one accountable business owner should be identified while other departments may retain supporting responsibilities.

## 2.3 Custody

Custodians operate, maintain, store, administer, or otherwise handle assets on behalf of their owners.

Information Technology may administer a system without owning the business process or information contained within it.

## 2.4 Classification

Information assets are classified according to [[POL-004 Information Classification & Handling Policy]] and [[STD-001 Information Classification Standard]].

## 2.5 Business Criticality

Business criticality and recovery requirements are established through [[RPT-002 Business Impact Analysis]].

Asset classification and business criticality are separate concepts.

Highly sensitive information may support a process with relatively long recovery tolerances, while a less sensitive system may require rapid restoration because operations depend on its availability.

---

# 3. Business Process Assets

| Asset | Business Owner | Primary Dependencies | BIA Priority |
|---|---|---|---|
| Order Processing | COO | OMS, CRM, WMS, Internet, AD, personnel | Critical |
| Warehouse Operations | COO | WMS, inventory, personnel, facility, local infrastructure | Critical |
| Inventory Management | COO | WMS, warehouse personnel, receiving and shipping records | High |
| Shipping and Delivery | COO | WMS, OMS, inventory, vehicles, personnel, suppliers/carriers | High |
| Internet Connectivity | CIO | ISP, network infrastructure, facility power | High |
| Identity and Authentication | CIO | AD, cloud hosting, network connectivity | High |
| Customer Relationship Management | Sales Management | CRM, Internet, AD, endpoints | High |
| Email and Business Communications | CIO | Email service, Internet, endpoints, authentication | High |
| Accounting | CFO | Accounting system, personnel, banking/payment relationships | High |
| Procurement | COO | Suppliers, accounting, communications, personnel | High |
| File Services | CIO | Cloud/hosted services, AD, network connectivity | High |
| Infinity Online Ordering | CIO | Infinity, Internet, cloud hosting, contractor support | Moderate |
| Customer Service | Sales/Operations Management | CRM, email, order information, personnel | Moderate |
| Human Resources | CFO | HR system, personnel records, authorized HR personnel | Moderate |
| Payroll | CFO | HR/Payroll system, banking, employee records, personnel | Moderate* |
| Accounts Payable | CFO | Accounting system, vendor records, banking, personnel | Moderate |
| Quality Assurance | COO | Operational records, personnel, business systems | Moderate |
| Legal and Compliance | CEO | Business records, contracts, communications, personnel | Moderate |
| Corporate Website | CIO | Web hosting, Internet, content administration | Low |

> **Payroll Note:** Payroll may temporarily require High priority as a payroll-processing deadline approaches.

---

# 4. Information Assets

## 4.1 Customer Information

**Owner:** Applicable Sales/Customer Service Management  
**Typical Classification:** Confidential

Includes:

- Customer contact information
- Customer account information
- Order history
- Sales records
- Pricing information
- Customer communications
- Customer service records

Primary systems include CRM, OMS, Infinity, email, and file services.

---

## 4.2 Employee and Personnel Information

**Owner:** CFO  
**Business Custodian:** Human Resources  
**Typical Classification:** Confidential or Restricted depending on content

Includes:

- Employee records
- Compensation information
- Payroll information
- Banking information
- Personnel actions
- Employment documentation
- Benefits-related information
- Performance or disciplinary information

Access must be limited according to legitimate business responsibilities.

---

## 4.3 Financial Information

**Owner:** CFO  
**Typical Classification:** Confidential or Restricted depending on content

Includes:

- Accounting records
- Banking information
- Accounts payable records
- Accounts receivable information
- Payroll records
- Vendor payment information
- Financial reports
- Reconciliation records

---

## 4.4 Vendor and Supplier Information

**Owner:** COO  
**Supporting Responsibility:** CFO for financial and payment information  
**Typical Classification:** Internal or Confidential

Includes:

- Vendor contact information
- Supplier agreements
- Pricing
- Purchase information
- Payment instructions
- Vendor banking information
- Procurement records
- Performance information

Financial and payment information remains subject to CFO oversight even when the supplier relationship is operationally owned by the COO.

---

## 4.5 Authentication Information

**Owner:** CIO  
**Typical Classification:** Restricted

Includes:

- Password-related information
- Authentication secrets
- Privileged credentials
- Service-account credentials
- Recovery credentials
- Emergency-access credentials
- Authentication configuration information

---

## 4.6 Security Information

**Owner:** CIO  
**Typical Classification:** Internal, Confidential, or Restricted depending on content

Includes:

- Vulnerability results
- Security configurations
- Network information
- Security-event records
- Incident records
- Penetration-test results
- Security findings
- Privileged-access information
- Recovery information

Detailed security information that could materially assist unauthorized access or attack requires stronger protection.

---

## 4.7 Infinity Source Code and Intellectual Property

**Owner:** CIO  
**Organizational Ownership:** Dunder Mifflin  
**Typical Classification:** Restricted

Includes:

- Infinity source code
- Source repository
- Application design information
- Technical documentation
- Deployment information
- Development work product
- Proprietary business logic

Dunder Mifflin retains ownership and control of these assets even when contractors perform development or support activities.

---

## 4.8 Business Continuity and Recovery Information

**Owner:** CIO  
**Supporting Responsibility:** COO for business continuity information and operational procedures  
**Typical Classification:** Confidential

Includes:

- Recovery procedures
- Backup configuration information
- Disaster recovery documentation
- Business continuity procedures
- Emergency contact information
- Cloud migration information
- Recovery credentials where applicable

Recovery credentials themselves are Restricted.

---

## 4.9 Payment-Related Information

**Owner:** CFO  
**Typical Classification:** Confidential

Dunder Mifflin relies on a third-party payment processor for complete payment-card processing.

Dunder Mifflin may retain:

- Payment tokens
- Card brand
- Last four digits
- Expiration information where required

Payment tokens are classified as Confidential.

Complete payment-card numbers are not intentionally retained as part of ordinary business processing.

---

# 5. Application Assets

| Application/System | Business Owner | Technical Custodian | Primary Function |
|---|---|---|---|
| Infinity | CIO | IT / Contractor | Customer online ordering |
| CRM | Sales Management | IT | Customer and sales management |
| OMS | COO | IT | Order processing |
| WMS | COO | IT | Warehouse and inventory management |
| Accounting System | CFO | IT | Financial processing |
| HR/Payroll System | CFO | IT / HR | Personnel and payroll |
| Email | CIO | IT | Business communications |
| File Services | CIO | IT | Shared information storage |
| Active Directory | CIO | IT | Identity and authentication |
| Backup Systems | CIO | IT | Data protection and recovery |
| Corporate Website | CIO | IT | Public company presence |
| Endpoint Management | CIO | IT | Endpoint administration |

Business and information owners remain responsible for information stored within shared systems even when the CIO owns the supporting technical service.

---

# 6. Infinity Asset Group

Infinity is treated as an important asset group rather than merely a single application.

The group includes:

- Public web interface
- Application functions
- Database
- Source code
- Source repository
- Development environment
- Test environment
- Production environment
- Application documentation
- Deployment information
- Application backups
- Customer-order information
- Contractor-support capability
- Dunder Mifflin intellectual property

Logical separation exists among web, application, and database functions.

The database is not intended to be directly accessible from the public Internet.

The original development team is no longer available, increasing the importance of documentation, source ownership, recovery capability, and contractor transferability.

---

# 7. Identity and Authentication Assets

## Active Directory

**Owner:** CIO  
**Custodian:** IT  
**Business Importance:** High

Active Directory provides centralized identity and authentication services for applicable company systems and endpoints.

At least two cloud-hosted domain controller/authentication servers support the environment.

Compromise or extended loss of these services could affect access to multiple systems.

## Privileged Accounts

**Owner:** CIO  
**Custodian:** IT  
**Classification:** Restricted

Privileged accounts provide elevated administrative capability and require stronger control than ordinary user accounts.

IT personnel use separate privileged credentials for administrative activity.

## Ordinary User Accounts

**Business Owner:** Applicable business management  
**Technical Custodian:** IT

Access should correspond to legitimate job responsibilities.

## Contractor Accounts

**Business Owner/Sponsor:** Applicable Dunder Mifflin manager  
**Technical Custodian:** IT

Contractor access must remain limited to approved business need and duration.

---

# 8. Network and Infrastructure Assets

| Asset | Owner | Custodian | Function |
|---|---|---|---|
| Internet Connections | CIO | Network/Security Administrator | Facility connectivity |
| Firewalls/Routers | CIO | Network/Security Administrator | Network perimeter protection and routing |
| Network Switches | CIO | Network/Security Administrator | Local network connectivity |
| Corporate Guest Wireless AP | CIO | Network/Security Administrator | Internet-only guest wireless at headquarters |
| Cloud-Hosted AD Infrastructure | CIO | System Administrator | Authentication and directory services |
| Hosted Business Systems | Applicable Business/System Owner | IT / Provider | Central business applications |
| UPS Equipment | CIO | IT / Facility Personnel | Short-duration power support for designated technology and selected workstations |

The authorized wireless environment consists of one guest Internet-only access point at corporate headquarters.

No general corporate wireless network is maintained.

---

# 9. Endpoint Assets

## Office Desktops

**Owner:** CIO  
**Custodian:** IT / Assigned User

Windows 7 desktop computers support ordinary office functions.

Ordinary users operate without local administrative rights.

## Company Laptops

**Owner:** CIO  
**Custodian:** IT / Assigned User

Company laptops support mobile business activity and use:

- User authentication
- Standard user privileges
- Automatic screen locking
- Full-disk encryption
- Central management

## Company Mobile Phones

**Owner:** CIO  
**Custodian:** IT / Assigned User

Company-issued mobile phones support business communications and cellular connectivity.

Mobile-device management capabilities are used where supported.

## Warehouse Workstations

**Owner:** COO  
**Technical Custodian:** IT  
**Operational Custodian:** Warehouse Operations

Shared Windows workstation accounts may be used where operational requirements justify them.

Significant Warehouse Management System transactions require stronger individual accountability under the planned Identity and Access Management improvements.

## Warehouse Handheld and Barcode Devices

**Owner:** COO  
**Technical Custodian:** IT  
**Operational Custodian:** Warehouse Operations

These devices support inventory, receiving, shipping, and warehouse activities.

---

# 10. Backup and Recovery Assets

Backup and recovery assets include:

- Automated backups
- Cloud-based backups
- 21 encrypted external hard drives
- Off-site backup-media storage
- Recovery documentation
- Business continuity documentation
- Cloud Exit & Emergency Migration Plan
- Printed recovery information where maintained
- Recovery credentials
- Qualified personnel capable of performing recovery

Each facility has three encrypted external backup drives assigned to its physical-media rotation.

Under normal rotation, the off-site provider retains the two most recent weekly generations for each facility, resulting in 14 encrypted drives normally held off-site.

Backup assets require protection independent of the production resources they are intended to recover.

---

# 11. Facility Assets

| Facility | Type | Primary Business Functions |
|---|---|---|
| Corporate Headquarters | Leased corporate facility | Executive management, corporate functions, IT/security, controlled Infinity contractor work |
| Scranton Branch | Leased branch/warehouse | Sales, warehouse, fulfillment, inventory, shipping |
| Syracuse Branch | Leased branch/warehouse | Sales, warehouse, fulfillment, inventory, shipping |
| Utica Branch | Leased branch/warehouse | Sales, warehouse, fulfillment, inventory, shipping |
| Rochester Branch | Leased branch/warehouse | Sales, warehouse, fulfillment, inventory, shipping |
| Nashua Branch | Leased branch/warehouse | Sales, warehouse, fulfillment, inventory, shipping |
| Akron Branch | Leased branch/warehouse | Sales, warehouse, fulfillment, inventory, shipping |

Each branch maintains local inventory and warehouse capability.

The geographic distribution of facilities provides some operational resilience while also creating additional physical, network, personnel, and coordination dependencies.

---

# 12. Physical Security Assets

Physical-security assets include:

- Employee access credentials
- Keys
- Restricted rooms
- Warehouse security cages
- Reception areas
- Controlled rear entrances
- Visitor records
- Facility access records
- Building fire-protection systems
- UPS equipment
- Landlord-provided common-area security capabilities

Each warehouse maintains a locked security cage or similar secured enclosure for higher-value or theft-attractive inventory.

Landlord-operated common-area video surveillance is not treated as a substitute for Dunder Mifflin access controls.

---

# 13. Inventory Assets

**Owner:** COO  
**Custodian:** Warehouse Operations

Inventory includes:

- Paper products
- Stationery
- Office supplies
- Higher-value products
- Theft-attractive products
- Received goods awaiting processing
- Goods staged for shipment

Inventory records are maintained through the Warehouse Management System and supporting receiving, shipping, and reconciliation records.

Higher-value and theft-attractive inventory is stored in secured warehouse cages where appropriate.

---

# 14. Vehicle and Transportation Assets

**Owner:** COO  
**Custodian:** Operations / Authorized Drivers

Transportation assets and dependencies include:

- Company vehicles where applicable
- Authorized drivers
- Vehicle registration
- Insurance
- Inspection and maintenance records
- Delivery documentation
- Shipping information
- Third-party carriers where used

Vehicles support customer delivery and other operational requirements.

Transportation disruption does not necessarily prevent all order processing or warehouse activity but may interfere with fulfillment and delivery.

---

# 15. Personnel and Capability Assets

Dunder Mifflin depends on both individual personnel and organizational knowledge.

Important roles and capabilities include:

- CEO
- COO
- CFO
- CIO
- Legal and Compliance
- Human Resources
- IT & InfoSec Manager
- System Administrator
- Network/Security Administrator
- Information Security Analyst
- IT Support Personnel
- Branch Management
- Sales Personnel
- Warehouse Personnel
- Accounting Personnel
- Payroll Personnel
- Procurement Personnel
- Customer Service Personnel

The organization must avoid unreasonable dependency on a single individual's undocumented knowledge or exclusive access.

---

# 16. Key-Person Dependencies

Key-person dependency may exist where:

- Specialized knowledge is concentrated in one individual.
- Credentials or administrative capability are exclusively held by one person.
- Recovery procedures depend on undocumented knowledge.
- Business approval authority lacks a designated alternate.
- A critical process lacks cross-trained personnel.
- A contractor holds knowledge that Dunder Mifflin cannot independently recover.

The original Infinity development team's departure demonstrates the importance of maintaining company-controlled documentation, source code, credentials, and transferability.

Key-person risk is addressed principally through **R026 Loss of Key Personnel**.

---

# 17. Third-Party Assets and Dependencies

| Third Party / Service Type | Business Dependency | General Significance |
|---|---|---|
| Cloud Hosting Provider | Central systems and infrastructure | Critical |
| Payment Processor | Customer payment processing | Critical |
| Infinity Support Contractor | Application maintenance and support | Critical |
| Internet Service Providers | Facility connectivity | Critical/Important depending on supported function |
| Off-Site Backup Storage Provider | Physical backup separation | Critical |
| Product Suppliers | Inventory availability | Critical/Important depending on supplier dependency and substitutability |
| Building Landlords | Facilities and building services | Important |
| Technology Vendors | Product support and maintenance | Important/Routine depending on service |
| Shipping/Transportation Providers | Distribution support where used | Important |
| Other Professional Services | Specialized business support | Based on service |

Third-party significance must be evaluated according to the actual service, information access, system access, business dependency, substitutability, and potential impact of failure or compromise.

Vendor or supplier name alone does not determine risk or significance.

Formal third-party classification is assigned according to [[POL-008 Third-Party Security Policy]].

---

# 18. Supplier Dependencies

Dunder Mifflin depends on suppliers for paper, stationery, office supplies, and related inventory.

Supplier disruption may affect:

- Product availability
- Customer fulfillment
- Inventory levels
- Pricing
- Delivery commitments
- Revenue
- Customer relationships

Supplier resilience should include, where practical:

- Alternate suppliers
- Inventory monitoring
- Supplier disruption monitoring
- Procurement and Operations coordination
- Customer communication when fulfillment is affected
- Periodic sourcing review

Alternate suppliers should be maintained where practical and economically reasonable.

Supplier disruption is addressed principally through **R020 Supplier Disruption**.

---

# 19. Information Flow

A typical customer transaction may involve the following information flow:

**Customer → Sales or Infinity → CRM/OMS → Warehouse/WMS → Shipping/Delivery → Accounting → Payment**

Supporting information may pass through:

- Email
- File services
- Customer service
- Procurement
- Payment processor
- Financial systems

The security of a transaction depends on more than the system where the order originates.

Controls must consider the complete business process.

---

# 20. Remote Sales and Mobile Work

Authorized mobile personnel may conduct business using:

- Company laptops
- Company mobile phones
- Internet connectivity
- Cellular connectivity
- Email
- CRM
- Other authorized cloud-hosted services
- VPN access when required for nonpublic resources

Mobile work creates dependencies on endpoint security, authentication, communications, device management, and loss/theft response.

VPN access by ordinary authorized users does not establish external remote privileged administration.

---

# 21. Manual Processing Assets

Business continuity may require temporary manual processing.

Manual-processing assets may include:

- Paper order records
- Offline forms
- Customer information required for processing
- Employee attribution
- Timestamps
- Reconciliation records
- Verification records
- Procedures
- Trained personnel

Manual records created during an outage become business information assets and require appropriate protection.

Manual processing follows the lifecycle:

**Collect → Review → Enter → Reconcile → Verify**

Detailed requirements are maintained in [[PROC-013 Manual Processing Procedure]].

---

# 22. Recovery Dependencies

Recovery may depend on:

- Qualified personnel
- Recovery documentation
- Authentication services
- Cloud providers
- Internet connectivity
- Backup media
- Automated backups
- Encryption keys or credentials
- Vendor support
- Replacement equipment
- Alternate communications
- Management authority

A backup copy alone does not represent a complete recovery capability.

Recovery dependencies are evaluated through [[RPT-002 Business Impact Analysis]], [[PLN-002 Business Continuity Plan]], and [[PLN-003 Disaster Recovery Plan]].

---

# 23. Asset Relationships

Assets frequently depend on one another.

For example:

**Order Processing**

depends on:

**Personnel → Endpoint → Authentication → Internet → OMS → WMS → Inventory → Shipping → Accounting**

Similarly:

**Infinity**

depends on:

**Internet → Cloud Hosting → Web/Application/Database Functions → Authentication/Administration → Source Code → Contractor Support → Order Processing → Warehouse Fulfillment**

Asset risk must be evaluated in the context of these relationships rather than as isolated technology components.

---

# 24. Asset Ownership and Custody Examples

| Asset | Accountable Owner | Custodian / Supporting Function |
|---|---|---|
| Customer Information | Applicable Sales/Business Owner | IT and Authorized Users |
| Payroll Information | CFO | Human Resources, Payroll Personnel, IT |
| WMS | COO | IT |
| Active Directory | CIO | IT |
| Infinity | CIO | IT / Authorized Contractor |
| Inventory | COO | Warehouse Operations |
| Backup Infrastructure | CIO | IT |
| Facilities | COO | Operations / Landlord as applicable |
| Employee Records | CFO | Human Resources / Authorized IT Support |
| Financial Records | CFO | Finance / IT |

Ownership and custody should not be treated as interchangeable.

Supporting functions may participate in protection, administration, operation, or use without becoming co-owners of the asset.

---

# 25. Asset Protection Requirements

Protection requirements are determined using factors including:

- Information classification
- Business criticality
- Legal obligations
- Contractual obligations
- Risk
- Access requirements
- Recovery requirements
- Fraud exposure
- Safety considerations
- Third-party dependency

Not every asset requires identical controls.

Controls must remain proportional to the asset's business value and risk.

---

# 26. Asset Change Management

Material changes to the asset environment should be evaluated for security and risk implications.

Examples include:

- Introduction of a new business system
- Retirement of a significant system
- New cloud provider
- New facility
- Facility closure
- New critical supplier
- Significant Infinity architecture change
- New remote-access capability
- Major network change
- New category of sensitive information
- Significant outsourcing
- Acquisition or divestiture
- Material business-process change

Applicable registers, Business Impact Analysis results, risk assessments, recovery documentation, and controls should be reviewed when such changes occur.

---

# 27. Asset Register Maintenance

The register should be reviewed at least annually.

Business and technical owners must report material asset changes when identified.

Information Technology maintains technical asset information for systems under its administration.

Business owners remain responsible for identifying business processes, information, third-party dependencies, and other assets that may not be visible through technical inventory tools.

The asset register does not require every individual low-value office item to be listed separately.

Assets may be grouped where grouping provides sufficient information for risk management and accountability.

---

# 28. Relationship to Information Classification

Information assets identified in this register are classified according to [[STD-001 Information Classification Standard]].

Backups inherit the highest applicable classification of the information they contain.

Information classification determines handling and protection requirements but does not independently establish recovery priority.

---

# 29. Relationship to Business Impact Analysis

Business processes and supporting assets identified in this register provide input to [[RPT-002 Business Impact Analysis]].

The Business Impact Analysis determines:

- Business criticality
- Maximum Tolerable Downtime
- Recovery Time Objective
- Recovery Point Objective

These requirements guide continuity and recovery design.

---

# 30. Relationship to Risk Management

Assets and dependencies identified in this register provide input to:

- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]

Risk assessment considers threats, vulnerabilities, existing controls, business impact, dependencies, and potential consequences affecting these assets.

---

# 31. Relationship to Security Controls

Security controls should be traceable to the assets, business processes, information, or risks they protect.

Control relationships are maintained through [[REG-003 Enterprise Security Control Inventory]].

The existence of an asset does not automatically justify a particular security control.

Control selection must remain based on legitimate business, risk, security, legal, contractual, or recovery requirements.

---

# 32. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[STD-001 Information Classification Standard]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-011 Physical & Environmental Security Policy]]

---

# 33. Revision History

| Version | Date     | Description                       | Approval |
| ------- | -------- | --------------------------------- | -------- |
| 1.0     | May 2013 | Initial enterprise asset register | CIO      |