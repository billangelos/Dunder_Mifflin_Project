# PRO-002 Enterprise Security Architecture Program

## Document Control

| Field | Value |
|---|---|
| Document ID | PRO-002 |
| Title | Enterprise Security Architecture Program |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Architecture Change |

---

# 1. Purpose

This program establishes the enterprise security architecture for Dunder Mifflin, Inc.

The architecture translates:

- Business requirements
- Asset dependencies
- Information classification
- Business Impact Analysis (BIA)
- Enterprise risk
- Security policy
- Recovery requirements

into coordinated technical and administrative security design.

Security architecture must support the business while reducing risk to an acceptable level.

---

# 2. Scope

This program applies to enterprise technology and supporting services including:

- Corporate networks
- Internet connectivity
- Firewalls and routers
- Servers
- Active Directory
- Endpoints
- Laptops
- Mobile devices
- Warehouse technology
- Cloud-hosted systems
- Business applications
- Infinity
- Authentication services
- Remote access
- Backup systems
- Administrative systems
- Security-management systems
- Third-party technology connections

The architecture applies across headquarters and all six branch locations.

---

# 3. Architecture Objectives

The enterprise security architecture must:

1. Support business operations.
2. Protect information according to classification.
3. Support availability requirements established by the BIA.
4. Reduce identified enterprise risks.
5. Apply least privilege.
6. Limit unnecessary exposure.
7. Provide individual accountability where practical.
8. Support secure administration.
9. Protect endpoints and servers.
10. Support secure application operation.
11. Support incident detection and response.
12. Support backup and recovery.
13. Reduce unnecessary single points of failure.
14. Support assessment and evidence collection.
15. Remain appropriate to the size and resources of Dunder Mifflin.

---

# 4. Architecture Inputs

Security architecture must be informed by:

- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[REG-001 Enterprise Asset Register]]
- [[STD-001 Information Classification Standard]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-009 Security Governance Framework]]
- Applicable enterprise policies

Architecture must not be developed independently from business and risk requirements.

---

# 5. Architecture Principles

Dunder Mifflin uses the following architecture principles:

- Business-driven security
- Risk-based control selection
- Least privilege
- Need to know
- Individual accountability
- Defense in depth
- Minimized exposure
- Secure configuration
- Controlled administrative access
- Separation where risk justifies it
- Recoverability
- Simplicity where practical
- Evidence-based assurance

Architecture complexity must have a legitimate security or business purpose.

---

# 6. Defense in Depth

Security must not depend unnecessarily on a single protective mechanism.

Defense in depth may combine:

- Physical controls
- Network controls
- Authentication
- Authorization
- Endpoint protection
- Server protection
- Application security
- Information protection
- Monitoring
- Backup
- Incident response
- Business continuity

Failure of one control should not automatically result in complete compromise where reasonable additional protection can be provided.

---

# 7. Architecture and Current State

This program defines required and planned architecture.

The existence of an architectural requirement does not establish that the control is currently implemented.

Current-state implementation must be distinguished from:

- Planned architecture
- Approved treatment
- Future implementation
- Validated operation

Proposed architecture receives no credit when determining current residual risk until implementation and effectiveness are appropriately validated.

---

# 8. Network Architecture

Each Dunder Mifflin facility uses a primarily wired corporate network.

The general site architecture is:

**Internet Service Provider → Firewall / Router → Network Switches → Authorized Corporate Devices**

Connected devices may include:

- Office workstations
- Laptops
- Printers
- Warehouse workstations
- Warehouse devices
- Approved network equipment

Network design must limit unnecessary exposure between trusted corporate systems and untrusted networks.

---

# 9. Internet Boundary

Each facility's Internet boundary must use an approved firewall or firewall/router providing appropriate traffic control.

Boundary controls must:

- Deny unsolicited inbound connections unless explicitly required.
- Permit only necessary externally accessible services.
- Restrict administrative interfaces.
- Maintain approved configuration.
- Support logging appropriate to operational needs.
- Be included in configuration and change-management processes.

Internet connectivity alone must not provide administrative access to internal systems.

---

# 10. Inbound Connectivity

Unsolicited inbound Internet traffic must be denied by default.

Exceptions require:

- Business need
- Technical justification
- Defined destination
- Required protocol or service
- Security review
- Appropriate approval

Unnecessary externally accessible services must be removed or disabled.

---

# 11. Administrative Exposure

Network, server, application, and security-management interfaces must not be unnecessarily exposed to the Internet.

Administrative interfaces should be accessible only from authorized management locations or systems appropriate to the risk.

Internet exposure must not be used as a substitute for controlled administrative access.

---

# 12. Network Segmentation

Network segmentation must be applied when justified by:

- Risk
- Trust boundary
- Internet exposure
- Information sensitivity
- Administrative function
- Application architecture
- Guest access

Dunder Mifflin does not require separate network segments solely because employees belong to different departments.

Segmentation must address meaningful security boundaries rather than create unnecessary complexity.

---

# 13. Guest Wireless

Dunder Mifflin does not operate a general corporate wireless network.

The only approved company wireless access point is located in the Scranton Headquarters lobby.

The access point provides:

- Guest Internet access only
- No intended corporate-network access

Guest wireless must remain logically separated from corporate systems.

---

# 14. Unauthorized Wireless

Unauthorized wireless access points and network devices are prohibited.

Periodic network discovery must include identification of:

- Unauthorized wireless access points
- Unauthorized routers
- Unauthorized switches
- Other unexpected network devices

The known authorized wireless baseline consists of the single Scranton Headquarters guest access point.

---

# 15. Remote Access

Remote access must be provided only when required for legitimate business activity.

Approved remote access must:

- Use an authorized method.
- Require appropriate authentication.
- Be limited to required resources.
- Follow least privilege.
- Be subject to security monitoring where practical.
- Be removed when no longer required.

Remote access does not automatically authorize privileged administration.

---

# 16. Virtual Private Network

A Virtual Private Network (VPN) may be used when an authorized company laptop must securely reach nonpublic company resources across an external or otherwise untrusted network.

VPN use is not required merely because a device is connected to an internal trusted wired corporate network.

Public services such as Infinity may be accessed through their intended public interface without a corporate VPN.

---

# 17. Privileged Remote Administration

External remote privileged administration is prohibited.

Privileged administration of significant production resources must occur through approved company-controlled methods and locations.

Ordinary authorized remote access does not authorize privileged administration.

Emergency-access procedures do not create an exception to the prohibition on external remote privileged administration.

---

# 18. Cloud Architecture

Dunder Mifflin uses a cloud-first architecture for significant business systems.

Cloud use must consider:

- Business dependency
- Information classification
- Authentication
- Administrative access
- Availability
- Backup
- Recovery
- Provider dependency
- Contractual requirements
- Incident response
- Exit capability

Cloud hosting does not transfer Dunder Mifflin's responsibility for managing business risk.

---

# 19. Cloud Concentration

Critical dependencies on a common cloud provider or service must be identified.

Dunder Mifflin must evaluate the effect of:

- Provider outage
- Administrative lockout
- Security compromise
- Service termination
- Data loss
- Contract failure

The organization is not required to maintain a continuously operating alternate cloud environment unless the BIA and risk analysis justify the cost and complexity.

---

# 20. Cloud Exit

Cloud architecture must support reasonable exit or emergency migration capability.

Required considerations include:

- Data export
- Configuration documentation
- Authentication dependencies
- Application dependencies
- Backup availability
- Provider contacts
- Recovery priorities

Detailed planning is maintained in [[PLN-004 Cloud Exit & Emergency Migration Plan]].

---

# 21. Active Directory Architecture

Active Directory provides centralized identity and authentication services for applicable Dunder Mifflin systems.

The architecture includes at least two cloud-hosted domain controllers or authentication servers.

The servers should use reasonable failure-domain separation within the hosting environment.

Both servers residing within the same overall cloud provider remains a concentration dependency that must be considered in continuity and risk management.

---

# 22. Active Directory Protection

Active Directory security must include:

- Restricted administrative access
- Separate privileged credentials
- Controlled Domain Admin membership
- Secure configuration
- Patch management
- Logging
- Backup and recovery
- Change management

Standing Domain Admin membership must normally be limited to the:

- IT & Information Security Manager
- System Administrator

Additional standing membership requires documented justification.

---

# 23. Authentication Architecture

Authentication architecture must support:

- Unique user identification
- Individual accountability
- Appropriate password controls
- Account lifecycle management
- Privileged-account separation
- Dormant-account management
- Contractor restrictions
- Emergency access
- Multi-factor authentication where required

Detailed requirements are maintained in [[STD-005 Authentication & Account Security Standard]].

---

# 24. Multi-Factor Authentication

Smart-card multi-factor authentication using the card with a PIN or other approved secret must be implemented where supported and required by risk.

Priority must be given to:

- Privileged access
- Sensitive systems
- Remote access
- Higher-risk authentication scenarios

Multi-factor authentication strengthens authentication but does not replace authorization or least privilege.

---

# 25. Endpoint Architecture

Corporate endpoints must use security controls appropriate to their role.

Endpoint architecture includes:

- Windows 7 corporate workstations
- Company laptops
- Warehouse workstations
- Approved mobile devices
- Central management where supported
- Managed commercial antivirus
- Patch management
- Standard-user operation
- Screen locking
- Appropriate information protection

Detailed requirements are maintained in [[STD-003 Endpoint Security Standard]].

---

# 26. Standard User Operation

Ordinary users, including executives, must operate without local administrative privileges unless a documented business and technical need requires an exception.

Administrative capability must not be provided solely because of:

- Seniority
- Job title
- Convenience

Administrative privileges must reflect actual job requirements.

---

# 27. Laptop Security

Company laptops must use:

- Approved authentication
- Standard-user operation
- Automatic screen locking
- Full-disk encryption
- Central management where supported
- Managed antivirus
- Patch management

Loss or theft must be reported promptly.

---

# 28. Mobile Device Architecture

Company mobile devices must be centrally managed where supported.

Mobile-device management should provide capabilities including:

- Inventory
- Enrollment
- Security configuration
- Passcode requirements
- Remote lock
- Remote wipe
- Device location where available and authorized

Mobile controls must reflect the capabilities of the device platform.

---

# 29. Personally Owned Devices

General Bring Your Own Device (BYOD) access to corporate systems is not part of the normal enterprise architecture.

Personal devices may be used for emergency safety or communication when necessary, subject to applicable policy.

Use of personal devices during an emergency does not establish permanent authorization for corporate access.

---

# 30. Warehouse Workstations

Warehouse workstations must support operational requirements while maintaining reasonable security.

Shared Windows workstation accounts may be used where operationally justified.

Shared workstation use must not eliminate individual accountability for significant Warehouse Management System transactions.

Significant WMS activity must require individual authentication or other reliable individual attribution.

---

# 31. Warehouse Devices

Warehouse handheld and barcode devices must:

- Be authorized.
- Be inventoried where practical.
- Use only required access.
- Be physically protected appropriate to their environment.
- Support individual accountability where the business transaction requires it.

Operational convenience must be balanced against transaction integrity and inventory accountability.

---

# 32. Server Architecture

Servers must be configured according to:

- Business purpose
- Information classification
- Application requirements
- Risk
- Recovery requirements

Server architecture must limit unnecessary:

- Services
- Software
- Accounts
- Administrative access
- Network exposure

Detailed requirements are maintained in [[STD-004 Server Security Standard]].

---

# 33. Secure Configuration

Dunder Mifflin must establish secure configuration requirements for significant technology.

Configuration requirements must address, as applicable:

- Operating systems
- Servers
- Endpoints
- Network devices
- Authentication
- Applications
- Security tools

Detailed requirements are maintained in [[STD-006 Secure Configuration Standard]].

---

# 34. Configuration Baselines

Approved configuration baselines must be established where practical for significant systems.

Baselines should identify required settings sufficient to:

- Reduce unnecessary exposure
- Support repeatable deployment
- Detect material configuration drift
- Support recovery
- Support assessment

Baseline complexity must remain appropriate to the size of the environment.

---

# 35. Configuration Changes

Material configuration changes must follow [[POL-007 Change & Configuration Management Policy]].

Changes must address:

- Authorization
- Testing where practical
- Implementation
- Rollback
- Verification
- Documentation

Emergency changes remain subject to appropriate after-action review.

---

# 36. Configuration Backup

Configuration information necessary to restore significant infrastructure must be backed up or otherwise recoverable.

This includes appropriate configuration information for:

- Firewalls
- Routers
- Servers
- Authentication systems
- Critical applications

Recovery must not depend unnecessarily on undocumented administrator knowledge.

---

# 37. Patch Architecture

Dunder Mifflin uses centralized Windows patch-management capability.

Patch management must support:

- Identification
- Testing
- Scheduling
- Distribution
- Monitoring
- Failure handling
- Rollback where practical

Patch deployment must balance security risk with operational stability.

---

# 38. Malware Protection

Corporate endpoints and applicable servers must use centrally managed commercial antivirus protection.

Protection must be:

- Enabled
- Updated
- Monitored where supported
- Protected from unauthorized disabling

Antivirus is one security layer and must not be treated as complete protection against malware.

---

# 39. Endpoint Detection and Response

Endpoint Detection and Response (EDR) is not assumed as part of the existing architecture.

Any future adoption must be evaluated through:

- Risk treatment
- Operational requirements
- Staffing
- Cost
- Monitoring capability

The absence of EDR does not remove the need for endpoint protection, logging, incident response, and recovery.

---

# 40. Security Information and Event Management

Dunder Mifflin does not assume an enterprise Security Information and Event Management (SIEM) platform.

Security monitoring must use available logs and management capabilities appropriate to risk.

Future SIEM adoption must be justified by:

- Monitoring requirements
- Risk
- Staffing
- Cost
- Operational capability

Technology must not be deployed merely to create the appearance of security maturity.

---

# 41. Logging Architecture

Significant systems must generate security-relevant logs appropriate to their risk and capabilities.

Logging may include:

- Authentication activity
- Administrative activity
- Security events
- Application events
- Malware detections
- Network events
- Significant transactions

Logs must support reasonable:

- Monitoring
- Troubleshooting
- Incident investigation
- Accountability

---

# 42. Time Consistency

Significant systems should maintain reasonably consistent system time.

Consistent timestamps support:

- Log correlation
- Incident investigation
- Transaction analysis
- Change review
- Evidence analysis

Material time discrepancies affecting investigation or accountability must be corrected.

---

# 43. Administrative Workstations

Privileged administration must use designated administrative workstations where required by risk.

Administrative workstations must:

- Be company controlled.
- Be securely configured.
- Limit unnecessary software.
- Restrict ordinary user activity.
- Use appropriate authentication.
- Receive security updates.
- Be used only by authorized personnel.

They must not become general-purpose shared workstations.

---

# 44. Privileged Credentials

Personnel with administrative responsibilities must use separate privileged credentials for administrative activity.

Privileged credentials must not be used for routine:

- Email
- Web browsing
- Ordinary office work

Separating ordinary and privileged activity reduces unnecessary exposure of administrative credentials.

---

# 45. Service Accounts

Service accounts must:

- Have an identified purpose.
- Have an accountable owner.
- Receive only required privileges.
- Avoid interactive use where practical.
- Be reviewed periodically.
- Use protected credentials.

Unnecessary service accounts must be disabled or removed.

---

# 46. Application Architecture

Significant applications must use security architecture appropriate to:

- Business function
- Information classification
- Internet exposure
- Authentication
- Authorization
- Availability
- Recovery

Application architecture requirements are established through [[POL-012 Application & Secure Development Policy]].

---

# 47. Infinity Architecture

Infinity must maintain logical separation between:

**Web Tier → Application Tier → Database Tier**

The web tier may provide the intended public customer interface.

The application and database tiers must not be unnecessarily exposed to the Internet.

The production database must not be directly accessible from the Internet.

Detailed requirements are maintained in [[STD-009 Infinity Security Standard]].

---

# 48. Infinity Administration

Infinity administrative functions must:

- Require authorization.
- Use appropriate authentication.
- Follow least privilege.
- Avoid unnecessary Internet exposure.
- Generate appropriate accountability.
- Follow change-management requirements.

Public access to Infinity's customer interface does not authorize public access to administrative services.

---

# 49. Infinity Contractor Architecture

Infinity contractor access must be designed so that Dunder Mifflin retains control of the application and production environment.

Contractor architecture must support:

- Individual authorization
- Time-limited access
- Appropriate authentication
- Least privilege
- Change control
- Logging
- Company-controlled source code
- Company-controlled documentation

Privileged production or administrative contractor activity must occur from the designated controlled contractor workspace at headquarters.

General contractor VPN access for privileged production administration is prohibited.

---

# 50. Development Architecture

Development, test, and production environments must be separated for significant applications.

Architecture must reduce the likelihood that:

- Development changes directly affect production.
- Untested code reaches production.
- Test credentials provide production access.
- Production information is unnecessarily exposed.
- Release controls are bypassed.

Detailed requirements are maintained in [[PRO-007 Secure Software Development Lifecycle Program]].

---

# 51. Third-Party Connections

Third-party technology connections must be limited to legitimate business requirements.

Architecture must consider:

- Connection purpose
- Authentication
- Authorization
- Information exposure
- Network exposure
- Monitoring
- Termination
- Provider compromise

Third-party status does not establish trusted access automatically.

---

# 52. Third-Party Architecture Review

Critical third-party technology dependencies must receive architecture consideration appropriate to their risk.

Review should evaluate:

- Data flows
- Authentication
- Access
- Interfaces
- Provider dependency
- Recovery
- Exit capability
- Security responsibilities

Requirements are coordinated with [[POL-008 Third-Party Security Policy]].

---

# 53. Information Protection Architecture

Information protection must reflect classification.

Architecture must consider:

- Access
- Storage
- Transmission
- Endpoint protection
- Backup
- External sharing
- Disposal

Detailed requirements are established through:

- [[POL-004 Information Classification & Handling Policy]]
- [[STD-001 Information Classification Standard]]

---

# 54. Encryption

Encryption must be used where required by:

- Information sensitivity
- Device risk
- Transmission risk
- Contractual requirement
- Security architecture

Company laptops use full-disk encryption.

Backup external hard drives are encrypted.

Cryptographic controls must not be treated as a substitute for access control.

---

# 55. Payment Architecture

Payment-card processing must remain with the approved external payment processor.

Dunder Mifflin does not retain full Primary Account Number (PAN) information as part of the normal architecture.

Dunder Mifflin retains approved payment references such as:

- Token
- Card brand
- Last four digits
- Expiration information where required

The payment token is classified as Confidential.

---

# 56. Backup Architecture

Backup architecture must support business recovery requirements.

Dunder Mifflin uses:

- Automated backup
- Cloud-based backup capability
- Encrypted external hard-drive rotation
- Off-site backup-media storage

Backup architecture must support recovery rather than merely creation of backup copies.

---

# 57. External Backup Rotation

Each of the seven Dunder Mifflin facilities maintains three encrypted external backup hard drives.

The enterprise rotation contains:

**7 facilities × 3 drives = 21 encrypted external drives**

Each Friday, the current drive is transferred to the off-site disaster-recovery storage provider.

The provider normally retains the two most recent weekly generations for each facility:

**7 facilities × 2 generations = approximately 14 drives off site**

When a new drive arrives, the oldest applicable generation is returned for reuse.

---

# 58. Backup Separation

Backup architecture must provide reasonable separation from production systems.

Separation must reduce the likelihood that a single:

- System failure
- Administrative error
- Security compromise
- Facility event

destroys both production information and all usable recovery copies.

Backup architecture must be periodically evaluated against ransomware and other production-compromise scenarios.

---

# 59. Recovery Architecture

Recovery architecture must follow business requirements established by the BIA.

Recovery priority is:

**Life Safety → Critical → High → Moderate → Low**

Technical architecture must not independently redefine business recovery priority.

---

# 60. Recovery Documentation

Recovery documentation must be sufficient for a qualified Information Technology professional unfamiliar with the environment to perform required recovery activities.

Recovery capability must not depend solely on:

- Individual memory
- Undocumented configuration
- A single employee
- A single contractor

Significant technical changes must trigger review of affected recovery documentation.

---

# 61. Internet Continuity

Loss of a facility's primary wired Internet service must not automatically eliminate all business communication capability where practical alternatives exist.

Company-issued cellular capability may provide a secondary Internet or communication path for applicable business functions.

Not every function can operate fully through cellular connectivity.

Warehouse and other functions may require documented manual continuity procedures.

---

# 62. Power Architecture

Critical network equipment and selected management and Sales workstations must use Uninterruptible Power Supply (UPS) protection where designated.

The expected design objective is approximately 30 minutes of temporary power for designated equipment.

UPS capability is intended to support:

- Short interruptions
- Orderly shutdown
- Limited temporary operation

It is not equivalent to long-duration facility power generation.

---

# 63. Generators

General facility generators are not required as part of the enterprise architecture unless justified by:

- BIA
- Risk
- Facility conditions
- Cost-benefit analysis

Cloud-hosted business systems reduce some dependence on facility power but do not eliminate local operational dependencies.

---

# 64. Physical Architecture

Technical security architecture must coordinate with physical security.

Significant Information Technology and network infrastructure must be placed in Restricted areas where appropriate.

Physical controls must support protection of:

- Servers
- Network equipment
- Backup media
- Administrative systems
- Sensitive information

Requirements are established through [[POL-011 Physical & Environmental Security Policy]].

---

# 65. Facility Independence

Dunder Mifflin Headquarters is not a major company data center.

Loss of headquarters must not automatically destroy:

- Cloud-hosted business systems
- Enterprise source code
- Off-site backups
- Recovery documentation
- All branch operations

Architecture must support reasonable continuation from unaffected locations.

---

# 66. Geographic Distribution

Dunder Mifflin operates headquarters and six geographically distributed branches.

Architecture should use this distribution where practical to support resilience.

Geographic distribution does not eliminate regional risk when multiple facilities or supporting providers may be affected by the same event.

---

# 67. Availability Architecture

Availability design must reflect the BIA.

Architecture may use:

- Redundancy
- Backup
- Alternate communication
- Manual processing
- Geographic distribution
- Provider resilience
- Recovery procedures

High availability must not be implemented automatically when less complex recovery capability adequately satisfies business requirements.

---

# 68. Resilience Versus Redundancy

Redundancy is one method of improving resilience but is not the only method.

Resilience may also be provided through:

- Recovery
- Alternate processes
- Manual procedures
- Spare equipment
- Provider escalation
- Geographic distribution
- Documentation
- Personnel alternatives

Architecture must select the method appropriate to the business requirement.

---

# 69. Spare Equipment

Critical infrastructure should maintain reasonable replacement capability where justified by business impact.

The Scranton Headquarters network should maintain an appropriate spare firewall/router or equivalent replacement capability.

Spare equipment must be:

- Compatible
- Securely stored
- Documented
- Recoverable to an approved configuration

---

# 70. Security Architecture and Incident Response

Architecture must support incident response by providing reasonable capability for:

- Identification
- Isolation
- Log collection
- Account restriction
- Malware response
- Recovery
- Evidence preservation

Incident response requirements are established through:

- [[POL-009 Incident Response Policy]]
- [[PLN-001 Incident Response Plan]]

---

# 71. Security Architecture and Business Continuity

Architecture must support Business Continuity/Disaster Recovery (BC/DR) requirements.

Design must consider:

- BIA requirements
- Backup
- Recovery
- Alternate communications
- Manual operation
- Facility loss
- Cloud outage
- Personnel loss
- Third-party dependency

Architecture decisions that materially affect recovery must be coordinated with [[POL-010 Business Continuity & Disaster Recovery Policy]].

---

# 72. Security Architecture and Change Management

Material architecture changes must follow [[POL-007 Change & Configuration Management Policy]].

Architecture changes must evaluate, as applicable:

- Business impact
- Security impact
- Dependencies
- Testing
- Rollback
- Recovery documentation
- Risk
- Monitoring

A significant architecture change is not complete until required documentation is updated or an explicit corrective action exists.

---

# 73. Architecture Documentation

Significant architecture must be documented sufficiently to support:

- Administration
- Troubleshooting
- Security review
- Incident response
- Recovery
- Assessment
- Personnel replacement

Documentation may include:

- Network diagrams
- Data flows
- System relationships
- Trust boundaries
- Administrative paths
- Dependencies
- Security controls

Documentation must reflect actual architecture rather than an idealized design.

---

# 74. Network Diagrams

Network diagrams must identify significant:

- Internet boundaries
- Firewalls
- Routers
- Network segments
- Critical systems
- External connections
- Guest wireless
- Administrative paths

Diagrams must be updated following material architecture changes.

---

# 75. Data Flow Documentation

Significant applications and processes should document important data flows where required to understand:

- Information exposure
- Trust boundaries
- Third-party dependencies
- Authentication
- Application architecture
- Security controls

Infinity data flows require particular attention because the application is publicly accessible and contractor supported.

---

# 76. Architecture Review

The enterprise security architecture must be reviewed:

- At least annually
- Following material technology changes
- Following significant business changes
- Following significant incidents
- Following material assessment findings
- When significant risk changes
- When major third-party dependencies change

Review must consider whether the architecture continues to support business and risk requirements.

---

# 77. Architecture Exceptions

Exceptions to architecture requirements require:

- Business justification
- Affected requirement
- Risk evaluation
- Compensating controls where practical
- Responsible owner
- Defined duration
- Appropriate approval

High or Critical residual risk must be escalated according to [[POL-005 Risk Management Policy]].

This exception process does not authorize exceptions to the prohibition on external remote privileged administration.

---

# 78. Architecture Assessment

Architecture controls must be assessed using methods appropriate to the control.

Methods may include:

- Inspection
- Observation
- Interviews
- Configuration review
- Network discovery
- Technical Testing
- Sampling
- Independent Performance
- Recovery testing

Assessment must evaluate actual implementation rather than design documentation alone.

---

# 79. Architecture Evidence

Evidence may include:

- Network diagrams
- Configuration records
- Firewall rules
- Access-control records
- Authentication settings
- Endpoint-management records
- Patch records
- Antivirus status
- Backup records
- Restore-test results
- Change records
- Architecture reviews
- Vulnerability results
- Network-discovery results

Evidence must accurately represent actual conditions.

---

# 80. Evidence Integrity

Personnel must not:

- Create false architecture diagrams.
- Record security configurations that do not exist.
- Represent Planned architecture as implemented.
- Conceal unauthorized network exposure.
- Record tests that were not performed.
- Represent failed tests as successful.
- Alter evidence to conceal architecture deficiencies.

Known discrepancies must be documented and corrected.

---

# 81. Architecture Findings

Material architecture deficiencies must be documented.

Examples include:

- Unexpected Internet exposure
- Unauthorized network device
- Unauthorized wireless access point
- Excessive administrative exposure
- Missing configuration backup
- Inadequate environment separation
- Unsupported recovery dependency
- Undocumented critical connection
- Excessive privileged access
- Architecture inconsistent with BIA requirements

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 82. Architecture Metrics

Architecture metrics may include:

- Unauthorized network devices identified
- Unauthorized wireless access points identified
- Internet-exposed services
- Architecture exceptions
- Configuration-baseline deviations
- Unsupported systems
- Unresolved architecture findings
- Backup coverage
- Recovery-test results
- Significant architecture changes awaiting documentation

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 83. Risk Relationships

This program provides significant treatment support for risks including:

- R001 Phishing / Credential Compromise
- R003 Ransomware
- R004 Malware
- R005 Password / Authentication Weakness
- R006 Infinity Application Compromise
- R007 Internet Infrastructure Compromise
- R008 Denial of Service
- R009 Sensitive Information Theft / Extortion
- R010 Unauthorized / Excessive Access
- R013 Administrative / Configuration Error
- R014 Lost Device
- R015 Shared Warehouse Account Risk
- R016 Cloud Outage
- R017 Internet Service Provider Outage
- R018 Third-Party Technology Failure / Compromise
- R019 Infinity Contractor Dependency / Compromise
- R021 Fire
- R022 Water Damage
- R023 Utility / Power / HVAC Failure
- R024 Unauthorized Physical Access
- R026 Personnel Loss
- R027 Backup / Recovery Failure
- R028 Data Corruption
- R033 Manual Outage Processing Error
- R034 Loss of Headquarters
- R035 Regional Disaster

Risk treatment is maintained in [[RTP-001 Enterprise Risk Treatment Plan]].

---

# 84. Architecture Governance

The CIO is accountable for the enterprise security architecture.

The IT & Information Security Manager coordinates architecture implementation and operation.

Technical personnel are responsible for maintaining architecture within their assigned areas.

Business owners must participate when architecture decisions affect:

- Business requirements
- Availability
- Information handling
- Business processes
- Significant risk

Major architecture decisions must be escalated through the governance structure when appropriate.

---

# 85. Relationship to Standards

This program establishes the overall security architecture.

Detailed technical requirements are established through:

- [[STD-002 Network Security Standard]]
- [[STD-003 Endpoint Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[STD-009 Infinity Security Standard]]

Standards must remain consistent with this program and applicable enterprise policies.

---

# 86. Relationship to Procedures

Architecture requirements are implemented through applicable procedures including:

- [[PROC-002 Privileged Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-006 Vulnerability Assessment Procedure]]
- [[PROC-008 Security Monitoring Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]

Procedures must not weaken mandatory architecture requirements without an approved exception.

The prohibition on external remote privileged administration remains mandatory and is not subject to the general architecture-exception process.

---

# 87. Control Inventory

Architecture controls must be represented in [[REG-003 Enterprise Security Control Inventory]] where applicable.

Control records should identify:

- Control objective
- Control owner
- Related requirement
- Related risk
- Implementation status
- Evidence
- Assessment method
- Effectiveness

The control inventory provides the bridge between architecture requirements and assurance.

---

# 88. Continuous Improvement

Architecture improvement follows:

**Business Requirement → Risk → Architecture Requirement → Implementation → Evidence → Assessment → Finding → Remediation → Retest → Risk Reassessment**

Architecture must evolve when evidence demonstrates that existing design does not adequately support business or security requirements.

Improvement does not require adoption of every available security technology.

---

# 89. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-003 Identity and Access Management Program]]
- [[PRO-004 Vulnerability Management Program]]
- [[PRO-005 Security Operations Program]]
- [[PRO-007 Secure Software Development Lifecycle Program]]
- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[PRO-009 Security Governance Framework]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-011 Physical & Environmental Security Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[STD-001 Information Classification Standard]]
- [[STD-002 Network Security Standard]]
- [[STD-003 Endpoint Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[STD-009 Infinity Security Standard]]
- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-001 Enterprise Asset Register]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[REG-007 Cross-Reference Matrix]]

---

# 90. Program Review

This program must be reviewed:

- At least annually
- Following material architecture changes
- Following significant security incidents
- Following significant assessment findings
- Following material business changes
- Following significant risk changes

The CIO coordinates review.

Material revisions require CEO approval.

---

# 91. Revision History

| Version | Date     | Description                                      | Approval |
| ------- | -------- | ------------------------------------------------ | -------- |
| 1.0     | May 2013 | Initial Enterprise Security Architecture Program | CEO      |