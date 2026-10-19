# RPT-001 Enterprise Profile & Security Baseline

## Document Control

| Field | Value |
|---|---|
| Document ID | RPT-001 |
| Title | Enterprise Profile & Security Baseline |
| Version | 1.1 |
| Classification | Internal |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Assessment Date | May 2013 |
| Review Frequency | Annual and Following Material Organizational Change |

---

# 1. Purpose

This report establishes the enterprise profile and security baseline for Dunder Mifflin, Inc.

It documents the business environment, organizational structure, facilities, technology, information systems, personnel, third-party dependencies, and security capabilities used as the basis for subsequent business impact, risk, architecture, control, continuity, and assurance activities.

The baseline distinguishes existing conditions from proposed security improvements.

Controls described as existing may be considered when evaluating current residual risk when their operation and effectiveness are reasonably supported. Planned or proposed controls do not receive current residual-risk credit until implemented and appropriately validated.

---

# 2. Organization Overview

Dunder Mifflin, Inc. is a privately held business-to-business distributor and reseller of paper, stationery, and office supplies.

The company does not manufacture its principal products. It purchases inventory from suppliers and distributes products to business customers through a combination of sales-assisted and online ordering channels.

David Wallace serves as Owner, President, and Chief Executive Officer.

The company employs approximately 138 personnel across corporate headquarters and six branch locations.

---

# 3. Business Model

Dunder Mifflin's principal business process follows the general sequence:

**Acquire Inventory → Sell → Process Orders → Fulfill → Deliver or Ship → Invoice → Receive Payment**

Orders may originate through traditional sales channels or through the Infinity online ordering platform.

Regardless of sales channel, orders ultimately depend on common fulfillment, inventory, shipping, accounting, and payment processes.

The organization depends on the coordinated operation of:

- Sales
- Customer service
- Procurement
- Inventory management
- Warehousing
- Order processing
- Shipping and delivery
- Accounting
- Accounts payable
- Payroll
- Human Resources
- Information Technology
- Information Security
- Management
- Third-party providers

---

# 4. Workforce and Facilities

Dunder Mifflin employs approximately 138 personnel.

Corporate headquarters employs approximately 30 personnel.

Each of the six branch locations employs approximately 18 personnel.

The organization operates seven leased facilities:

1. Corporate Headquarters
2. Scranton Branch
3. Syracuse Branch
4. Utica Branch
5. Rochester Branch
6. Nashua Branch
7. Akron Branch

Corporate headquarters and the Scranton Branch are separate facilities.

Each branch maintains warehouse space and local inventory to support order fulfillment and distribution.

Because the facilities are leased, Dunder Mifflin depends partly on landlords and property-management organizations for building-level services and infrastructure.

---

# 5. Executive and Management Structure

## 5.1 Chief Executive Officer

The Owner, President, and Chief Executive Officer has overall authority for the company and significant enterprise-risk decisions.

The CEO represents a significant organizational dependency because of the authority and institutional knowledge concentrated in the position.

---

## 5.2 Chief Operating Officer

The Chief Operating Officer is responsible for:

- Branch operations
- Warehousing
- Fulfillment
- Distribution
- Procurement
- Inventory
- Facilities
- Operational quality

---

## 5.3 Chief Financial Officer

The Chief Financial Officer is responsible for:

- Finance
- Accounting
- Accounts payable
- Payroll
- Financial controls
- Human Resources oversight

---

## 5.4 Chief Information Officer

The Chief Information Officer is responsible for:

- Information Technology
- Information Security
- Digital business systems
- Infinity
- Technology strategy

---

## 5.5 Legal and Compliance

Legal and Compliance reports directly to the CEO and supports:

- Legal matters
- Contractual matters
- Confidentiality requirements
- Compliance concerns
- Investigations
- Security incidents with legal implications

---

# 6. Information Technology Organization

The Information Technology and Information Security function consists of approximately six personnel:

- IT & Information Security Manager
- System Administrator
- Network/Security Administrator
- Information Security Analyst
- Two Support Personnel

Dunder Mifflin does not maintain a dedicated Chief Information Security Officer position.

The CIO provides executive oversight of information security.

The IT & Information Security Manager coordinates operational security activities.

The organization does not operate a dedicated 24-hour Security Operations Center.

---

# 7. Primary Business Systems

Dunder Mifflin relies on the following principal business and technology systems:

| System | Primary Purpose |
|---|---|
| Infinity | Customer online ordering and digital business |
| Customer Relationship Management (CRM) | Customer and sales relationship management |
| Order Management System (OMS) | Order processing and management |
| Warehouse Management System (WMS) | Warehouse and inventory operations |
| Accounting System | Accounting and financial processing |
| Human Resources/Payroll System | Personnel and payroll processing |
| Email | Business communications |
| File Services | Shared business information and documents |
| Active Directory (AD) | Central identity and authentication |
| Backup Systems | Data protection and recovery |
| Corporate Website | Public company information |
| Endpoint Management | Central endpoint administration and maintenance |

These systems support multiple business processes and may have dependencies on cloud providers, Internet connectivity, endpoints, authentication services, and third-party support.

---

# 8. Technology Architecture

## 8.1 General Architecture

Dunder Mifflin uses a cloud-first architecture while retaining local technology infrastructure at its facilities.

The environment is not cloud-only.

Major centralized business systems are hosted through commercial cloud or hosted-service providers rather than through a large company-operated data center at corporate headquarters.

Each facility maintains the local infrastructure necessary to support employees, communications, printing, warehouse operations, and access to centralized services.

---

## 8.2 Server Environment

The server environment uses Microsoft Windows Server 2012 Standard where applicable.

Active Directory provides centralized identity and authentication services.

At least two cloud-hosted domain controller/authentication servers support the environment.

The domain controllers are maintained within the same overall cloud-provider environment with reasonable separation intended to reduce dependence on a single server or immediate failure domain.

Dunder Mifflin does not operate a major corporate data center at headquarters.

---

## 8.3 Endpoint Environment

Office users primarily use Windows 7 desktop computers.

Personnel requiring mobility are issued Windows laptops where appropriate.

Ordinary users operate with standard user privileges and do not normally receive local administrative rights.

This restriction applies to executives as well as ordinary employees.

IT personnel use separate privileged credentials when administrative access is required.

---

## 8.4 Mobile Devices

Company-issued mobile phones are provided where required by business responsibilities.

Mobile-device management capabilities include, where supported:

- Device inventory
- Enrollment
- Configuration management
- Passcode requirements
- Device locking
- Device location
- Remote lock
- Remote wipe

General employee use of personally owned devices for company business is not part of the standard operating model.

---

## 8.5 Laptop Security

Company laptops use:

- User authentication
- Standard user privileges for ordinary use
- Automatic screen locking
- Full-disk encryption
- Central management

Laptop users may connect from external locations when business responsibilities require mobility.

---

# 9. Network Environment

Each facility generally uses the following network path:

**Internet Service Provider → Firewall/Router → Network Switches → Local Devices**

Local devices may include:

- Employee workstations
- Printers
- Warehouse workstations
- Network equipment
- Business-support devices

Unsolicited inbound Internet traffic is restricted at the network perimeter.

Internal administrative services are not intentionally exposed directly to the public Internet.

---

# 10. Wireless Networking

Dunder Mifflin does not operate general corporate wireless networking.

The only authorized wireless access point is a ceiling-mounted access point located in the corporate headquarters lobby.

The access point provides guest Internet access only and is not intended to provide access to the corporate network.

The six branch locations do not maintain authorized corporate wireless access points.

Unauthorized or rogue wireless devices remain a potential concern and require periodic detection activities.

---

# 11. Remote Connectivity

Personnel using company laptops from external or untrusted networks use Virtual Private Network (VPN) connectivity when accessing nonpublic company resources requiring protected remote connectivity.

Public services such as the customer-facing Infinity application are accessed directly through their public interfaces and do not require a corporate VPN for ordinary customer use.

Privileged external administration is restricted.

Contractors supporting Infinity do not receive general contractor VPN access for privileged production administration.

Privileged contractor work is performed from a designated controlled workspace at corporate headquarters when required.

---

# 12. Authentication and Access Control Baseline

Active Directory provides centralized authentication for applicable company systems and endpoints.

The existing environment does not use general Multi-Factor Authentication (MFA) across the enterprise.

Ordinary users generally operate without local administrative rights.

IT personnel use separate privileged credentials for administrative functions.

Access is intended to be based on business responsibilities.

Further improvements to authentication, privileged access, access review, lifecycle management, and individual accountability are addressed through the risk-treatment and Identity and Access Management program.

---

# 13. Warehouse Access and Accountability

Warehouse operations use shared Windows workstations and handheld or barcode-related devices as required for operational activity.

Shared Windows workstation accounts may exist where operational requirements justify them.

This arrangement may reduce individual accountability when significant business transactions are performed under shared credentials.

Warehouse access and accountability are evaluated separately from the underlying Windows workstation login model.

Controls requiring individual attribution for significant Warehouse Management System activity are addressed through risk treatment and the Identity and Access Management program.

---

# 14. Endpoint Protection

Dunder Mifflin uses centrally managed commercial antivirus protection on applicable endpoints.

The environment does not currently include a dedicated enterprise Endpoint Detection and Response (EDR) platform.

Endpoint protection is supported by:

- Standard user privileges
- Central antivirus management
- Patch management
- Full-disk encryption on laptops
- Screen-lock requirements
- Central endpoint management

---

# 15. Patch and Change Management

Dunder Mifflin maintains centralized Windows patch-management capabilities.

The process supports:

- Patch identification
- Testing
- Scheduling
- Distribution
- Monitoring
- Rollback where necessary

Basic change-management practices are used for technology changes.

The environment does not currently rely on a comprehensive Center for Internet Security (CIS) configuration baseline or application allowlisting program.

Further change and configuration requirements are addressed through [[POL-007 Change & Configuration Management Policy]].

---

# 16. Security Monitoring

Dunder Mifflin maintains basic security monitoring through existing system, application, antivirus, authentication, and infrastructure capabilities.

The company does not currently operate:

- A dedicated Security Information and Event Management (SIEM) platform
- A 24-hour Security Operations Center
- A dedicated Endpoint Detection and Response platform
- A mature centralized security-analytics capability

Security events may require manual review and correlation across multiple systems.

Additional monitoring improvements are addressed through [[PRO-005 Security Operations Program]] and the Enterprise Risk Treatment Plan.

---

# 17. Infinity Application

Infinity is Dunder Mifflin's internally developed customer ordering platform.

The application provides a digital channel through which customers can place orders.

Infinity orders ultimately enter the same general fulfillment process used by other customer orders.

Dunder Mifflin owns:

- The Infinity application
- Source code
- Source repository
- Application data
- Documentation
- Intellectual property
- Application backups
- Applicable development work product

The original internal development team is no longer available.

A third-party contractor provides ongoing application support.

Dunder Mifflin remains responsible for the application and must retain sufficient ownership, documentation, access, and recovery capability to avoid unreasonable dependency on the contractor.

---

# 18. Infinity Architecture and Support

Infinity uses logical separation among its web, application, and database functions.

The database is not intended to be directly accessible from the public Internet.

Contractor access is limited according to business need.

Privileged contractor production or administrative activity is performed from a designated controlled workspace at corporate headquarters rather than through general remote privileged access.

Contractor support creates both security and continuity dependencies that are evaluated separately in the enterprise risk assessment.

---

# 19. Payment Information

Payment-card processing is performed through a third-party payment processor.

Dunder Mifflin does not intentionally retain complete payment-card numbers as part of its ordinary business processing.

Dunder Mifflin may retain limited payment-related information such as:

- Payment token
- Card brand
- Last four digits
- Expiration information where required for business processing

Payment tokens are treated as Confidential information.

The third-party processor's handling of complete payment-card information reduces Dunder Mifflin's direct storage exposure but creates a third-party dependency.

---

# 20. Backup Environment

Dunder Mifflin uses a combination of physical and automated backup capabilities.

The physical backup process uses 21 encrypted external hard drives distributed across the seven facilities.

Each facility has three drives assigned to its rotation.

The general weekly process is:

1. A facility uses its current backup drive.
2. On Friday, the current drive is transferred to the off-site disaster-recovery storage provider.
3. The provider normally retains the two most recent weekly generations for that facility.
4. The provider supplies the next drive for rotation.
5. The oldest retained drive is returned for reuse.

Under normal operation, the off-site provider holds approximately 14 encrypted drives representing two recent weekly generations for each of the seven facilities.

Dunder Mifflin also uses automated or cloud-based backup capabilities for applicable systems and information.

---

# 21. Backup Limitations

The existence of backups does not by itself demonstrate successful recovery.

Current limitations include:

- Backup coverage has not been comprehensively validated against the complete system and information inventory.
- Restoration testing is inconsistent.
- Recovery Time Objective achievement has not been consistently demonstrated.
- Recovery Point Objective achievement has not been consistently demonstrated.
- Resilience against compromise of both production and accessible backup resources has not been fully validated.
- Immutable backup capability has not been established as an enterprise baseline.

These limitations are addressed principally through **R027 Backup / Recovery Failure** and the Business Continuity/Disaster Recovery program.

---

# 22. Recovery Documentation

Recovery documentation exists for significant technology and business recovery activities.

Recovery documentation is expected to contain sufficient information for a qualified Information Technology professional unfamiliar with the affected system to perform the documented recovery process.

Documentation must not depend exclusively on the availability of the system it is intended to recover.

Dunder Mifflin maintains a Cloud Exit & Emergency Migration Plan for circumstances requiring migration away from a cloud provider.

The company does not maintain a continuously operating alternate cloud environment solely for emergency migration.

---

# 23. Business Continuity Capabilities

Dunder Mifflin has several characteristics that provide existing continuity benefits:

- Centralized cloud-hosted business systems
- Seven geographically distributed facilities
- Company-issued laptops for mobile personnel
- Company-issued cellular devices for applicable roles
- Off-site encrypted backup media
- Automated or cloud-based backups
- Manual business-processing capability for selected functions
- Recovery documentation
- Cloud exit and emergency migration planning

These capabilities do not eliminate the need for formal Business Impact Analysis, continuity planning, recovery testing, or validation of recovery objectives.

---

# 24. Power and Environmental Resilience

Dunder Mifflin does not maintain standby generators as a general facility capability.

Uninterruptible Power Supply (UPS) protection is provided for:

- Critical network equipment
- Selected management workstations
- Selected Sales workstations

UPS capacity is intended to provide approximately 30 minutes of temporary operation under expected conditions.

The UPS capability supports short interruptions and orderly shutdown. It is not intended to provide extended facility operation.

Cloud-hosted centralized systems are not dependent on continued electrical service at an individual Dunder Mifflin facility.

---

# 25. Facility Access

Facilities use a combination of public, employee, and restricted areas.

The front entrance generally provides access through a receptionist or similar staffed entry point during business hours.

Employee access is available through controlled rear entrances using company-issued access credentials where applicable.

Warehouse visitors, vendors, and delivery personnel are subject to facility access requirements appropriate to their activities.

Restricted spaces use additional access controls where required.

---

# 26. Restricted Areas

Dunder Mifflin maintains approximately two secured or Restricted areas at facilities where operational needs require additional protection.

Significant Information Technology infrastructure and other sensitive resources may be maintained in Restricted areas.

Access to Restricted areas is limited according to business need.

Keyed access or other appropriate physical-access mechanisms are used according to the facility and resource involved.

---

# 27. Warehouse Security

Each warehouse contains a locked security cage or similar secured enclosure for higher-value or theft-attractive inventory.

Operations manages access to these secured inventory areas.

Warehouse security also relies on:

- Controlled facility access
- Inventory records
- Receiving records
- Shipping records
- Physical counts
- Reconciliation
- Investigation of significant discrepancies

---

# 28. Video Surveillance

Building landlords may operate video surveillance covering common building areas.

Dunder Mifflin does not maintain a general internal camera-surveillance program across company work areas.

Landlord-operated surveillance is not treated as a substitute for Dunder Mifflin's own access controls or security procedures.

---

# 29. Third-Party Environment

Dunder Mifflin depends on third parties for services including:

- Cloud hosting
- Internet connectivity
- Payment processing
- Infinity application support
- Off-site backup-media storage
- Building and property services
- Technology products and support
- Suppliers
- Shipping and transportation services where applicable

The company performs basic third-party due diligence but does not currently operate a mature centralized Third-Party Risk Management (TPRM) program.

Third-party relationships are categorized according to business significance as:

- Critical
- Important
- Routine

Additional third-party security requirements are established through [[POL-008 Third-Party Security Policy]] and associated risk treatment.

---

# 30. Confidentiality Agreements

Dunder Mifflin requires a Non-Disclosure Agreement (NDA) or equivalent enforceable confidentiality obligation before a nonemployee or outside party receives access to sensitive company information when the access and sensitivity warrant such protection.

This requirement may apply to:

- Consultants
- Infinity contractors
- Information Technology service providers
- Penetration testers
- Service personnel requiring sensitive access
- Temporary specialists
- Outside support personnel
- Other third parties receiving sensitive information

An ordinary visitor, delivery driver, vendor sales representative, or building-maintenance worker does not automatically require an NDA when the person's authorized activities do not provide sensitive access.

If the scope of access changes, applicable confidentiality requirements must be satisfied before sensitive access is provided.

The existence of an NDA does not demonstrate that a third party has been comprehensively assessed, continuously monitored, technically restricted, or independently validated.

---

# 31. Security Governance Baseline

Information security responsibilities are distributed among executive management, business management, Information Technology, Information Security, Human Resources, Legal and Compliance, and other responsible personnel.

The company does not maintain a dedicated Chief Information Security Officer position.

The CIO provides executive information-security oversight.

The IT & Information Security Manager coordinates operational implementation.

Business leaders remain responsible for risks associated with their business functions rather than automatically transferring ownership of those risks to Information Technology or Information Security.

---

# 32. Current Security Strengths

Existing strengths include:

- Centralized identity services
- Standard-user operation for ordinary users
- Separate privileged credentials for IT personnel
- Full-disk encryption on company laptops
- Centrally managed antivirus
- Central Windows patch management
- Mobile-device management capabilities
- Restricted unsolicited inbound network access
- Lack of publicly exposed internal administrative services
- Limited corporate wireless exposure
- Cloud-hosted centralized business systems
- Multiple geographically distributed facilities
- Encrypted off-site backup media
- Automated or cloud-based backups
- Existing recovery documentation
- Cloud exit and emergency migration planning
- Locked warehouse security cages
- Existing physical-access controls
- Confidentiality requirements for sensitive third-party access
- Company ownership of Infinity source code, documentation, data, intellectual property, and related work product

These strengths are considered when assessing current risk where applicable.

---

# 33. Current Security Limitations

Material limitations include:

- No general enterprise Multi-Factor Authentication baseline
- Potential shared warehouse Windows accounts
- Limited centralized security-event correlation
- No dedicated Security Information and Event Management platform
- No Endpoint Detection and Response platform
- No 24-hour Security Operations Center
- Inconsistent restoration testing
- Incomplete validation of backup coverage
- Recovery Time Objective achievement not consistently demonstrated
- Recovery Point Objective achievement not consistently demonstrated
- No established enterprise immutable-backup baseline
- Basic rather than mature Third-Party Risk Management
- Contractor dependency for Infinity support
- Original Infinity development team no longer available
- Limited formalized security-assurance processes
- Opportunities to strengthen configuration standards
- Opportunities to strengthen access lifecycle management
- Opportunities to strengthen privileged-access controls
- Opportunities to improve security monitoring and incident-response readiness

These conditions provide input to the Enterprise Risk Assessment and do not automatically imply that every listed capability requires a complex or expensive technology solution.

---

# 34. Baseline and Proposed Controls

This report establishes the current enterprise baseline.

Later policies, standards, plans, procedures, programs, and risk-treatment documents may describe controls that do not yet exist.

The existence of a proposed requirement elsewhere in the security program must not be interpreted as evidence that the control exists in the baseline.

The following distinction must be preserved:

**Existing Baseline Control → May Affect Current Residual Risk**

**Proposed Control → No Current Residual-Risk Credit**

**Implemented and Validated Control → May Affect Future Reassessment**

This distinction applies throughout the security program.

---

# 35. Relationship to Risk Assessment

The conditions documented in this report provide evidence and assumptions supporting:

- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]

Changes to material baseline facts may require risk reassessment.

A later discovery that corrects an inaccurate baseline assumption may justify revising a risk score when the revision is documented and traceable.

A planned security improvement does not justify changing current residual risk before implementation and validation.

---

# 36. Relationship to Security Architecture

The existing architecture documented in this report provides the starting point for [[PRO-002 Enterprise Security Architecture Program]].

Future architecture requirements should improve security while remaining proportional to:

- Business requirements
- Identified risk
- Information sensitivity
- Business criticality
- Operational requirements
- Available resources

The security architecture should not assume capabilities that are absent from this baseline unless those capabilities are explicitly identified as proposed or future-state controls.

---

# 37. Relationship to Business Continuity

The existing environment provides the starting point for [[RPT-002 Business Impact Analysis]], [[PLN-002 Business Continuity Plan]], and [[PLN-003 Disaster Recovery Plan]].

Recovery priorities and technical recovery requirements must be driven by business impact.

Existing backup or continuity capabilities must not be assumed to satisfy a Recovery Time Objective or Recovery Point Objective until appropriate testing demonstrates that the requirement can be achieved.

---

# 38. Baseline Maintenance

The enterprise baseline should be reviewed at least annually and following material changes involving:

- Organizational structure
- Facilities
- Business processes
- Major systems
- Cloud providers
- Network architecture
- Infinity
- Significant third parties
- Backup architecture
- Identity systems
- Security technologies
- Personnel responsibilities
- Business continuity capabilities

Material changes should be evaluated for their effect on existing risk assessments, controls, recovery requirements, and assurance activities.

---

# 39. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[REG-001 Enterprise Asset Register]]
- [[STD-001 Information Classification Standard]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-011 Physical & Environmental Security Policy]]
- [[POL-012 Application & Secure Development Policy]]

---

# 40. Revision History

| Version | Date     | Description                                                                                                                        | Approval |
| ------- | -------- | ---------------------------------------------------------------------------------------------------------------------------------- | -------- |
| 1.0     | May 2013 | Initial enterprise profile and security baseline                                                                                   | CEO      |
| 1.1     | May 2013 | Baseline refinements and clarification of enterprise security, continuity, physical-security, third-party, and Infinity conditions | CEO      |