# STD-002 Network Security Standard

## Document Control

| Field | Value |
|---|---|
| Document ID | STD-002 |
| Title | Network Security Standard |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Network or Security Change |

---

# 1. Purpose

This standard establishes mandatory network-security requirements for Dunder Mifflin, Inc.

The standard defines requirements for protecting:

- Corporate wired networks
- Internet connections
- Firewalls and routers
- Network switches
- Network-management interfaces
- Remote access
- Guest wireless
- Network-connected systems
- Third-party network connections

Network security must support business operations while limiting unauthorized access, unnecessary exposure, and preventable disruption.

---

# 2. Scope

This standard applies to network infrastructure and network connectivity supporting:

- Scranton Headquarters
- Scranton Branch
- Syracuse Branch
- Utica Branch
- Rochester Branch
- Nashua Branch
- Akron Branch
- Cloud-hosted systems
- Remote users
- Third-party connections
- Infinity
- Backup and recovery activities

It applies to company-owned or company-managed network infrastructure.

---

# 3. Authority

This standard supports:

- [[PRO-002 Enterprise Security Architecture Program]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-007 Change & Configuration Management Policy]]

Requirements in this standard are mandatory unless an exception is approved through the established exception process.

The exception process does not apply where this standard or a governing policy explicitly identifies a requirement as non-exempt.

---

# 4. Network Security Objectives

Network security must:

1. Limit unauthorized access.
2. Reduce unnecessary Internet exposure.
3. Protect administrative interfaces.
4. Support secure business communications.
5. Provide appropriate trust boundaries.
6. Support individual accountability.
7. Protect network configuration.
8. Support monitoring and investigation.
9. Support business continuity.
10. Reduce the likelihood that one network weakness results in broader compromise.

---

# 5. Network Architecture

The standard facility network architecture is:

**Internet Service Provider → Firewall / Router → Network Switches → Authorized Corporate Devices**

Authorized connected systems may include:

- Office workstations
- Company laptops
- Printers
- Warehouse workstations
- Warehouse devices
- Approved servers
- Approved network equipment

Network connections must have a legitimate business or technical purpose.

---

# 6. Wired Corporate Network

Dunder Mifflin's corporate network is primarily wired.

Corporate wired connectivity must be limited to:

- Authorized company devices
- Approved infrastructure
- Approved third-party devices where required
- Other specifically authorized equipment

Connection to a physical network port does not independently establish authorization to use company systems.

---

# 7. Internet Boundary Protection

Each facility Internet connection must use an approved firewall, router with firewall capability, or equivalent boundary-control device.

The boundary device must:

- Control inbound traffic.
- Control traffic according to approved requirements.
- Restrict administrative access.
- Use an approved configuration.
- Support security logging where available.
- Be included in patch and configuration management.
- Have recoverable configuration information.

Boundary security must not depend solely on endpoint protection.

---

# 8. Default Inbound Rule

Unsolicited inbound Internet connections must be denied by default.

Inbound access may be permitted only when required for an approved business service.

Each permitted inbound service must have:

- Business justification
- Defined destination
- Required protocol or service
- Security review
- Appropriate approval

Rules that are no longer required must be removed.

---

# 9. Public Services

Public-facing services must expose only the network services required for their intended function.

Public access must not automatically provide access to:

- Administrative interfaces
- Internal file services
- Internal management systems
- Databases
- Network-device management
- Other nonpublic services

Infinity's public customer interface must remain distinct from its administrative and database functions.

---

# 10. Administrative Interfaces

Network-device administrative interfaces must not be directly exposed to the public Internet.

Administrative access must be limited to authorized personnel and approved management paths.

Management interfaces must use secure protocols where supported.

Unnecessary management services must be disabled.

---

# 11. Administrative Protocols

Network administration must use protected management protocols where supported by the device.

Unencrypted or otherwise insecure administrative protocols must not be used when an appropriate secure alternative is available and supported.

Legacy administrative protocols may remain only when:

- Technically required,
- Risk is understood,
- Exposure is appropriately restricted, and
- An approved exception exists where required.

---

# 12. Network Device Authentication

Administrative access to network devices must require authentication.

Default credentials must be changed before production use.

Administrative credentials must:

- Be limited to authorized personnel.
- Follow applicable authentication requirements.
- Be protected from unauthorized disclosure.
- Be changed when compromise is suspected or known.

Shared administrative credentials should be avoided where individual administrative accounts are supported.

---

# 13. Privileged Network Administration

Personnel performing privileged network administration must use separate privileged credentials where supported.

Privileged credentials must not be used for ordinary:

- Email
- Web browsing
- Office productivity
- Other routine user activity

Privileged network access must follow [[POL-003 Access Control Policy]].

---

# 14. External Remote Privileged Administration

External remote privileged administration is prohibited.

Privileged network administration must occur through approved company-controlled methods and locations.

Ordinary authorized remote access, including VPN access, does not authorize privileged network administration.

Emergency-access procedures do not create an exception to the prohibition on external remote privileged administration.

---

# 15. Network Segmentation

Segmentation must be used where justified by meaningful differences in:

- Trust
- Exposure
- Security function
- Information sensitivity
- Application architecture
- Guest access
- Administrative requirements

Segmentation must address identifiable security requirements.

Separate network segments are not required solely because users work in different business departments.

---

# 16. Segmentation Design

Where segmentation is used, communication between segments must be limited to required business and technical traffic.

Segmentation controls should identify:

- Source
- Destination
- Required service
- Business or technical purpose

Unnecessary pathways must not be retained merely because they were previously configured.

---

# 17. Guest Wireless

The only approved company wireless access point is located in the Scranton Headquarters lobby.

It provides:

**Internet-only guest wireless access**

The guest wireless network must not provide intended access to:

- Corporate workstations
- Internal servers
- Active Directory
- Internal business applications
- Network-management interfaces
- Other trusted corporate resources

---

# 18. Corporate Wireless

Dunder Mifflin does not operate a general corporate wireless network.

Installation of corporate wireless requires:

- Documented business need
- Security architecture review
- Approved design
- Authentication requirements
- Network-separation requirements
- Configuration standards
- CIO approval

A new wireless deployment must not be treated as an informal extension of the wired network.

---

# 19. Unauthorized Wireless Devices

Employees and contractors must not connect unauthorized:

- Wireless access points
- Wireless routers
- Personal hotspots providing network bridging
- Other devices that extend or bypass the corporate network

Unauthorized wireless equipment must be disconnected and investigated.

---

# 20. Unauthorized Network Devices

Unauthorized network infrastructure is prohibited.

This includes unauthorized:

- Routers
- Switches
- Bridges
- Access points
- Network appliances
- Other devices capable of altering network connectivity or trust boundaries

Unexpected network devices must be investigated.

---

# 21. Network Discovery

Dunder Mifflin must perform network discovery at least every six months.

Network discovery must seek to identify:

- Expected infrastructure
- Unexpected network devices
- Unauthorized wireless devices
- Unknown hosts where practical
- Material changes from known architecture

The expected wireless baseline includes the single authorized Scranton Headquarters guest access point.

---

# 22. Discovery Results

Network-discovery results must be reviewed by authorized Information Technology or information-security personnel.

Unexpected devices must be:

1. Identified
2. Investigated
3. Authorized or removed
4. Documented when material

Material unauthorized infrastructure may require incident escalation.

---

# 23. Network Equipment Inventory

Significant network equipment must be represented in the enterprise asset inventory or supporting technical inventory.

Records should include, where applicable:

- Device type
- Location
- Purpose
- Owner or custodian
- Relevant configuration information

Inventory must be sufficient to distinguish expected infrastructure from unknown devices.

---

# 24. Network Configuration

Network devices must use approved configuration appropriate to their purpose.

Configuration must address, where supported:

- Administrative access
- Unnecessary services
- Firewall rules
- Routing
- Logging
- Time settings
- Authentication
- Management protocols

Detailed configuration requirements are coordinated with [[STD-006 Secure Configuration Standard]].

---

# 25. Default Configuration

Default network-device configurations must be reviewed before production deployment.

Unnecessary default:

- Accounts
- Credentials
- Services
- Management interfaces
- Rules

must be changed, disabled, removed, or otherwise secured where supported.

---

# 26. Configuration Backup

Configuration information required to restore significant network infrastructure must be backed up or otherwise recoverable.

Configuration backup must include significant:

- Firewalls
- Routers
- Other critical network infrastructure where applicable

Recovery must not depend solely on an administrator remembering how the device was configured.

---

# 27. Configuration Protection

Network configuration backups must be protected against unauthorized access and modification.

Protection must reflect the sensitivity of configuration information.

Network configurations may disclose:

- Internal addressing
- Security rules
- Administrative settings
- Network relationships
- External connections

Access must be limited accordingly.

---

# 28. Network Change Management

Material network changes must follow [[POL-007 Change & Configuration Management Policy]].

Changes must address, as applicable:

- Business justification
- Security impact
- Testing
- Approval
- Implementation
- Rollback
- Verification
- Documentation

Emergency network changes require appropriate after-action review.

---

# 29. Firewall Rule Changes

Material firewall-rule changes must identify:

- Business or technical need
- Source
- Destination
- Required service
- Expected duration when temporary
- Approval

Temporary rules must be removed when no longer required.

---

# 30. Firewall Rule Review

Firewall rules must be periodically reviewed to identify:

- Obsolete rules
- Unnecessary exposure
- Temporary rules that should have expired
- Unexpected externally accessible services
- Rules inconsistent with documented architecture

Material deficiencies must be corrected through change management.

---

# 31. Internet-Exposed Services

Dunder Mifflin must maintain awareness of services intentionally exposed to the Internet.

Unexpected externally accessible services must be investigated.

Internet exposure review must consider:

- Business purpose
- Patch status
- Authentication
- Administrative interfaces
- Application architecture
- Risk

---

# 32. Remote Access

Remote access to nonpublic company resources must:

- Have a legitimate business purpose.
- Use an approved access method.
- Require appropriate authentication.
- Be limited to authorized users.
- Be limited to required resources.
- Be removed when no longer required.

Remote access must not create unnecessary administrative exposure.

Remote access authorization does not authorize external remote privileged administration.

---

# 33. Virtual Private Network

A Virtual Private Network (VPN) may be used to protect authorized connections from company laptops across external or otherwise untrusted networks to nonpublic company resources.

VPN use is not required solely because a company device is operating on an internal trusted wired corporate network.

Public applications intended for direct Internet access do not require corporate VPN access merely because the user is outside a company facility.

VPN connectivity does not authorize external remote privileged administration.

---

# 34. VPN Authorization

VPN access must be:

- Authorized
- Associated with a legitimate business need
- Assigned to an identifiable user
- Limited to required access
- Removed when no longer necessary

VPN authorization must be reviewed as part of applicable access reviews.

---

# 35. VPN Authentication

VPN authentication must comply with [[POL-003 Access Control Policy]] and [[STD-005 Authentication & Account Security Standard]].

Smart-card multi-factor authentication using a card with a PIN or other approved secret must be used where supported and required by risk.

Higher-risk remote access receives priority for stronger authentication.

---

# 36. Contractor Remote Access

Contractor remote access must not be enabled by default.

It requires:

- Business sponsorship
- Defined purpose
- Authorized systems
- Defined duration
- Appropriate authentication
- Least privilege
- Appropriate monitoring

Access must be removed when the approved requirement ends.

Contractor remote access does not authorize external remote privileged administration.

---

# 37. Infinity Contractor Access

The Infinity contractor does not receive general VPN access for privileged production administration.

Privileged production or administrative activity must be performed from the designated controlled contractor workspace at Scranton Headquarters.

External remote privileged administration by the Infinity contractor is prohibited.

---

# 38. Third-Party Network Connections

Third-party network connections require:

- Business justification
- Identified sponsor
- Defined purpose
- Defined access
- Security review
- Appropriate authentication
- Termination requirements

Third-party connectivity must not provide broader network access than required.

Third-party connectivity does not authorize external remote privileged administration.

---

# 39. Third-Party Trust

Third-party status does not establish trusted network status automatically.

Network access must be based on:

- Business need
- Required systems
- Required services
- Information sensitivity
- Risk

Third-party connections must be restricted appropriately.

---

# 40. Cloud Connectivity

Connectivity to cloud-hosted systems must use the intended secure service interface.

Cloud architecture must consider:

- Public versus nonpublic services
- Administrative access
- Authentication
- Encryption where required
- Provider dependency
- Availability

Cloud hosting does not remove the need for network-security controls.

---

# 41. Active Directory Connectivity

Network architecture must support secure communication with Active Directory and other authentication services.

Active Directory administrative services must not be directly exposed to the public Internet.

Network changes affecting authentication connectivity must consider:

- User authentication
- Administrative access
- Business applications
- Recovery
- Cloud dependency

---

# 42. Infinity Network Architecture

Infinity must maintain logical separation between:

**Web Tier → Application Tier → Database Tier**

The public Internet may reach only the services required for the intended public-facing interface.

The application tier must not be unnecessarily exposed to the Internet.

The production database must not be directly Internet accessible.

---

# 43. Infinity Database Connectivity

Database connections must be limited to authorized application and administrative requirements.

The database must not accept arbitrary public Internet connections.

Administrative database access must:

- Be restricted.
- Require authorization.
- Use appropriate authentication.
- Follow least privilege.

External remote privileged database administration is prohibited.

---

# 44. Network Services

Network services must exist only where required for business or technical operation.

Unnecessary services must be disabled where practical.

Examples include unnecessary:

- Remote-management services
- File-sharing services
- Discovery services
- Legacy services
- Administrative services

Service removal must consider legitimate operational dependencies before implementation.

---

# 45. Secure Network Protocols

Secure protocols must be used where supported and appropriate.

Protocols transmitting sensitive:

- Credentials
- Administrative sessions
- Confidential information
- Restricted information

must use suitable protection when transmitted across untrusted networks.

---

# 46. Unencrypted Legacy Protocols

Legacy protocols lacking appropriate protection must be restricted when they cannot be replaced.

Risk reduction may include:

- Limiting source systems
- Limiting destination systems
- Restricting network exposure
- Limiting use to trusted networks
- Replacing the protocol when practical

Continued use must not result from convenience alone when a supported secure alternative exists.

---

# 47. Network Addressing

Internal network addressing must be documented sufficiently to support:

- Administration
- Troubleshooting
- Security assessment
- Incident response
- Recovery

Addressing documentation must be protected according to its sensitivity.

---

# 48. Network Diagrams

Dunder Mifflin must maintain diagrams of significant network architecture.

Diagrams must identify, as applicable:

- Internet boundaries
- Firewalls
- Routers
- Significant switches
- Network segments
- Guest wireless
- Critical systems
- External connections
- Administrative paths

Diagrams must represent actual architecture.

---

# 49. Diagram Maintenance

Network diagrams must be reviewed following material architecture changes.

A significant network change is not complete until affected documentation is:

- Updated, or
- Assigned an explicit corrective action with an accountable owner and due date.

Outdated diagrams must not knowingly be represented as current.

---

# 50. Network Logging

Network infrastructure must generate security-relevant logs where supported and appropriate.

Logging may include:

- Administrative authentication
- Configuration changes
- Firewall events
- Connection events
- Security events
- Device errors

Logging requirements must reflect the capabilities and importance of the device.

---

# 51. Log Review

Network logs must be reviewed according to:

- Risk
- Device criticality
- Available capabilities
- Known security concerns
- Incident needs

Dunder Mifflin does not require continuous manual review of every network event.

Monitoring must remain practical for the available Information Technology and information-security staff.

---

# 52. Time Settings

Significant network devices should maintain reasonably consistent time.

Consistent timestamps support:

- Event correlation
- Incident investigation
- Change review
- Troubleshooting

Material time discrepancies affecting investigation or accountability must be corrected.

---

# 53. Network Monitoring

Network monitoring must focus on meaningful security and operational conditions.

Monitoring may include:

- Device availability
- Firewall events
- Unexpected connectivity
- Unauthorized devices
- Configuration changes
- Repeated authentication failures
- Internet exposure

Monitoring requirements are coordinated with [[PRO-005 Security Operations Program]].

---

# 54. Security Information and Event Management

This standard does not require an enterprise Security Information and Event Management (SIEM) platform as a current control.

Available network and system logs must still be used appropriately.

Future SIEM adoption may be considered through risk treatment and program planning.

---

# 55. Intrusion Detection and Prevention

Network Intrusion Detection System (IDS) or Intrusion Prevention System (IPS) capability may be implemented when justified by risk and operational requirements.

Deployment must consider:

- Monitoring capability
- Staffing
- Tuning
- False positives
- Response capability
- Cost

Installation without the ability to review and act on meaningful alerts is not sufficient assurance.

---

# 56. Denial-of-Service Protection

Network architecture must use reasonable available protections against denial-of-service conditions.

Controls may include:

- Firewall capabilities
- Provider protections
- Provider escalation
- Incident response
- Business continuity
- Alternate communication

Dunder Mifflin is not required to eliminate all denial-of-service risk.

---

# 57. Internet Service Provider Dependency

Each facility's primary wired Internet Service Provider represents an availability dependency.

Dunder Mifflin must maintain:

- Provider contact information
- Escalation information
- Outage-response procedures
- Business-continuity procedures

Internet-service failure must be addressed according to business impact.

---

# 58. Cellular Continuity

Company-issued cellular capability may provide a secondary communication or Internet path for applicable functions during wired Internet outages.

Cellular continuity is appropriate for functions that can operate using:

- Company laptops
- Company phones
- Cloud-hosted applications

Cellular connectivity does not guarantee full warehouse or facility operation.

---

# 59. Simultaneous Connectivity Failure

A condition affecting both wired Internet and cellular service may exceed the ordinary Internet Service Provider outage scenario.

Broader telecommunications or regional disruption must be addressed through:

- Business continuity
- Manual processing
- Geographic distribution
- Regional-disaster planning

---

# 60. Network Equipment Power Protection

Critical network equipment must use Uninterruptible Power Supply (UPS) protection where designated.

UPS capability should support approximately 30 minutes of temporary operation for designated equipment.

The purpose is to support:

- Short interruptions
- Orderly shutdown
- Limited temporary operation

UPS capability does not replace long-duration facility power.

---

# 61. Network Equipment Physical Security

Significant network equipment must be physically protected according to its importance and location.

Protection may include:

- Restricted rooms
- Locked cabinets
- Controlled facility access
- Other appropriate physical controls

Physical protection requirements are coordinated with [[POL-011 Physical & Environmental Security Policy]].

---

# 62. Spare Network Equipment

Scranton Headquarters must maintain reasonable replacement capability for its firewall/router or equivalent critical Internet-boundary equipment.

Spare equipment must be:

- Compatible with the environment.
- Securely stored.
- Documented.
- Capable of being restored to an approved configuration.

Replacement capability must be periodically reviewed.

---

# 63. Network Vulnerability Management

Network devices must be included in vulnerability-management activities appropriate to their capabilities and risk.

Activities may include:

- Vulnerability scanning where supported
- Version review
- Vendor security advisory review
- Configuration review
- Patch or firmware review

Requirements are coordinated with [[PRO-004 Vulnerability Management Program]].

---

# 64. Network Security Updates

Security updates for network devices must be evaluated based on:

- Severity
- Exposure
- Exploitability
- Business impact
- Device criticality
- Vendor guidance

Updates must follow applicable change-management requirements.

---

# 65. Unsupported Network Equipment

Network equipment that is no longer reasonably supportable must be identified.

Risk must be evaluated when:

- Security updates are unavailable.
- Vendor support has ended.
- Known vulnerabilities cannot be corrected.
- Required secure protocols are unavailable.

Replacement or compensating controls must be considered according to risk.

---

# 66. Network Incident Response

Suspected network compromise must be handled according to [[POL-009 Incident Response Policy]] and [[PLN-001 Incident Response Plan]].

Potential indicators include:

- Unauthorized configuration changes
- Unknown devices
- Unexpected external connections
- Unauthorized wireless
- Unexpected administrative activity
- Evidence of traffic interception
- Unexpected Internet exposure

Network personnel must preserve relevant evidence where practical.

---

# 67. Isolation During Incidents

Authorized Information Technology or incident-response personnel may isolate affected systems or network paths when necessary to contain a security incident.

Isolation decisions must consider:

- Life safety
- Business impact
- Incident severity
- Evidence
- Recovery

Emergency containment actions must be documented.

---

# 68. Network Recovery

Network recovery documentation must be sufficient for a qualified Information Technology professional unfamiliar with the environment to restore significant network capability.

Documentation should include, as applicable:

- Device purpose
- Connection information
- Required configuration
- Configuration backup location
- Provider information
- Replacement procedures
- Dependencies

Recovery must not rely solely on individual memory.

---

# 69. Network Continuity Priority

Network recovery priority must follow the Business Impact Analysis.

Technical personnel must not independently assign higher recovery priority solely because a device is technically complex.

Network restoration must support the business functions with the highest established recovery requirements.

---

# 70. Network Security Testing

Network security controls must be tested according to risk.

Testing may include:

- Configuration inspection
- Network discovery
- External exposure review
- Vulnerability assessment
- Firewall-rule review
- Penetration testing
- Recovery testing
- Independent Performance of selected procedures

Testing must be authorized and appropriately scoped.

---

# 71. Penetration Testing

Network penetration testing must follow [[STD-007 Penetration Testing Standard]].

Testing must define:

- Authorization
- Scope
- Method
- Timing
- Safety limitations
- Evidence
- Findings
- Remediation
- Retesting

Testing must not unnecessarily disrupt business operations.

---

# 72. Network Assessment Evidence

Evidence may include:

- Network diagrams
- Device inventories
- Firewall configurations
- Firewall-rule reviews
- Configuration backups
- Network-discovery results
- Vulnerability results
- Change records
- Authentication settings
- Log samples
- Recovery-test records
- Incident records

Evidence must reflect actual network conditions.

---

# 73. Evidence Integrity

Network-security personnel must not:

- Invent network-discovery results.
- Conceal unauthorized devices.
- Falsify firewall configurations.
- Represent Planned controls as implemented.
- Record tests that were not performed.
- Represent failed tests as successful.
- Alter evidence to conceal deficiencies.

Discrepancies must be documented and addressed.

---

# 74. Network Findings

Material network-security deficiencies must be documented.

Examples include:

- Unauthorized wireless access point
- Unauthorized router or switch
- Unexpected Internet exposure
- Exposed administrative interface
- Obsolete firewall rule
- Missing configuration backup
- Unsupported critical network device
- Excessive remote access
- Unapproved third-party connection
- Network architecture inconsistent with documented requirements

Material corrective actions must be tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 75. Network Metrics

Network-security metrics may include:

- Unauthorized devices identified
- Unauthorized wireless access points identified
- Internet-exposed services
- Firewall-rule exceptions
- Network vulnerabilities
- Unsupported network devices
- Network changes awaiting documentation
- Network-security findings
- Internet outages
- Network recovery-test results

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 76. Risk Relationships

This standard provides significant treatment support for risks including:

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
- R016 Cloud Outage
- R017 Internet Service Provider Outage
- R018 Third-Party Technology Failure / Compromise
- R019 Infinity Contractor Dependency / Compromise
- R023 Utility / Power / HVAC Failure
- R024 Unauthorized Physical Access
- R034 Loss of Headquarters
- R035 Regional Disaster

Risk treatment is maintained in [[RTP-001 Enterprise Risk Treatment Plan]].

---

# 77. Exceptions

Exceptions to this standard require:

- Business justification
- Identification of the affected requirement
- Risk evaluation
- Compensating controls where practical
- Accountable owner
- Defined duration
- Appropriate approval

High or Critical residual risk must be escalated according to [[POL-005 Risk Management Policy]].

This exception process does not authorize exceptions to the prohibition on external remote privileged administration.

---

# 78. Enforcement

Failure to comply with this standard may result in:

- Corrective action
- Access restriction
- Removal of unauthorized equipment
- Configuration remediation
- Incident investigation
- Management escalation
- Other action appropriate to the circumstances

Enforcement must be proportionate and consistent with company policy.

---

# 79. Assessment

Compliance with this standard may be assessed through:

- Inspection
- Observation
- Interviews
- Configuration review
- Network discovery
- Technical Testing
- Sampling
- Independent Performance
- Vulnerability assessment
- Penetration testing

Assessment must evaluate actual implementation and operation.

---

# 80. Traceability

This standard supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Network-security requirements must remain traceable to applicable business and risk requirements.

---

# 81. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-002 Enterprise Security Architecture Program]]
- [[PRO-004 Vulnerability Management Program]]
- [[PRO-005 Security Operations Program]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-011 Physical & Environmental Security Policy]]
- [[STD-003 Endpoint Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[STD-007 Penetration Testing Standard]]
- [[STD-009 Infinity Security Standard]]
- [[PLN-001 Incident Response Plan]]
- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-001 Enterprise Asset Register]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

---

# 82. Review

This standard must be reviewed:

- At least annually
- Following material network changes
- Following significant network-security incidents
- Following material assessment findings
- Following significant changes in network-related risk

The IT & Information Security Manager coordinates review.

The CIO is responsible for approving material revisions.

---

# 83. Revision History

| Version | Date     | Description                       | Approval |
| ------- | -------- | --------------------------------- | -------- |
| 1.0     | May 2013 | Initial Network Security Standard | CIO      |