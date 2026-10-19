# STD-003 Endpoint Security Standard

## Document Control

| Field | Value |
|---|---|
| Document ID | STD-003 |
| Title | Endpoint Security Standard |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Endpoint or Security Change |

---

# 1. Purpose

This standard establishes mandatory security requirements for endpoint devices used by Dunder Mifflin, Inc.

Endpoint security must protect:

- Company information
- User credentials
- Business applications
- Corporate networks
- Customer information
- Company operations

while allowing employees to perform authorized business activities.

---

# 2. Scope

This standard applies to company-managed endpoint devices including:

- Windows 7 desktop workstations
- Company laptops
- Warehouse workstations
- Company mobile phones
- Warehouse handheld and barcode devices
- Administrative workstations
- Other company-managed user computing devices

Server-specific requirements are maintained in [[STD-004 Server Security Standard]].

---

# 3. Authority

This standard supports:

- [[PRO-002 Enterprise Security Architecture Program]]
- [[POL-001 Information Security Policy]]
- [[POL-002 Acceptable Use Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-007 Change & Configuration Management Policy]]

Requirements in this standard are mandatory unless an approved exception exists.

The exception process does not apply where this standard or a governing policy explicitly identifies a requirement as non-exempt.

---

# 4. Endpoint Security Objectives

Endpoint security must:

1. Prevent unnecessary administrative access.
2. Reduce malware risk.
3. Protect company information.
4. Protect authentication credentials.
5. Maintain supported security updates.
6. Reduce risk from lost or stolen devices.
7. Support individual accountability.
8. Support incident investigation.
9. Maintain recoverable business information.
10. Support consistent security configuration.

---

# 5. Authorized Endpoints

Devices accessing nonpublic company systems must be authorized for that purpose.

Company-managed endpoints must be used where required by policy or architecture.

Connection of an endpoint to a corporate network does not independently authorize access to company information or applications.

---

# 6. Endpoint Inventory

Company endpoints must be represented in an appropriate asset or technical inventory.

Records should identify, where applicable:

- Device type
- Assigned user or function
- Location
- Operating system
- Management status
- Security status
- Relevant asset identifier

Inventory detail must be sufficient to support administration, security, recovery, and equipment accountability.

---

# 7. Standard Endpoint Platform

The standard corporate workstation platform is Windows 7.

Endpoint configuration must support:

- Central administration
- Patch management
- Managed antivirus
- User authentication
- Standard-user operation
- Screen locking
- Required business applications

Exceptions require documented business or technical justification.

---

# 8. Standard User Operation

Ordinary employees must operate endpoints using standard-user privileges.

Local administrative privileges must not be assigned solely because of:

- Employee seniority
- Executive status
- Convenience
- Personal preference

This requirement applies to executives as well as other employees.

---

# 9. Local Administrative Access

Local administrative privileges require a legitimate business or technical need.

Where local administrative access is required:

- Access must be limited to authorized personnel.
- Privileges must be limited to the required device or function.
- Separate administrative credentials must be used where practical.
- Access must be removed when no longer required.

Routine user accounts must not receive permanent administrative privileges without documented justification.

---

# 10. Privileged Credentials

Information Technology personnel must use separate privileged credentials for administrative activity where supported.

Privileged credentials must not be used for routine:

- Email
- Web browsing
- Office productivity
- Other ordinary user activity

Requirements are coordinated with [[STD-005 Authentication & Account Security Standard]].

---

# 11. Administrative Workstations

Dedicated administrative workstations must be used for higher-risk privileged administration where required by [[PRO-002 Enterprise Security Architecture Program]].

Administrative workstations must:

- Be company controlled.
- Use approved configuration.
- Receive security updates.
- Use managed antivirus.
- Limit unnecessary software.
- Restrict ordinary user activity.
- Be physically protected.
- Be limited to authorized administrators.

---

# 12. Authentication

Endpoints must require approved user authentication before access to nonpublic company resources.

Authentication must support individual accountability except where an approved operational exception exists.

Authentication requirements are established through:

- [[POL-003 Access Control Policy]]
- [[STD-005 Authentication & Account Security Standard]]

---

# 13. Shared Endpoint Accounts

Shared endpoint accounts should be avoided where individual authentication is practical.

An approved shared endpoint account must not be used to eliminate accountability for significant business transactions.

Warehouse workstations may use shared Windows accounts where operationally justified.

---

# 14. Warehouse Accountability

Where a shared Windows account is used on a warehouse workstation, significant Warehouse Management System transactions must still provide reliable individual attribution.

Significant activity may include:

- Inventory adjustments
- Material receiving activity
- Material shipping activity
- Other transactions affecting inventory accountability

The shared workstation account must not become the authoritative identity for significant WMS transactions.

---

# 15. Screen Locking

Company endpoints must use automatic screen locking after a reasonable period of inactivity.

Users must lock their workstation when leaving it unattended when unauthorized access is reasonably possible.

Reauthentication must be required to unlock the endpoint.

---

# 16. Workstation Placement

Endpoint placement must consider:

- Public visibility
- Unauthorized physical access
- Information sensitivity
- Operational requirements

Workstations processing sensitive information must not be positioned unnecessarily where unauthorized individuals can easily view or access them.

---

# 17. Endpoint Configuration

Company endpoints must use an approved configuration appropriate to their purpose.

Configuration must address, where applicable:

- User privileges
- Authentication
- Antivirus
- Patch management
- Screen locking
- Required services
- Approved software
- Logging
- Information protection

Detailed requirements are coordinated with [[STD-006 Secure Configuration Standard]].

---

# 18. Default Configuration

Default endpoint settings must be reviewed before deployment.

Unnecessary default:

- Accounts
- Services
- Software
- Administrative capabilities
- Network services

must be disabled, removed, or secured where practical.

---

# 19. Endpoint Configuration Baseline

Dunder Mifflin must maintain an endpoint configuration baseline sufficient to support consistent deployment and security review.

The baseline must identify significant required settings without creating unnecessary administrative complexity.

Configuration baselines must be reviewed following significant endpoint-platform changes.

---

# 20. Software Installation

Software installed on company endpoints must have a legitimate business or technical purpose.

Users must not install unauthorized software that:

- Creates security risk
- Interferes with company systems
- Bypasses security controls
- Violates licensing requirements
- Introduces unauthorized network services

Administrative restrictions should prevent unauthorized installation where practical.

---

# 21. Prohibited Software

Software known to be malicious, unauthorized, or intended to bypass company security controls is prohibited.

Examples include unauthorized:

- Remote-access tools
- Credential-recovery tools used without authorization
- Network interception tools
- Peer-to-peer file-sharing software
- Security-control disabling tools

Authorized security personnel may use appropriate administrative or security tools for legitimate company purposes.

---

# 22. Managed Antivirus

Company Windows endpoints must use approved centrally managed commercial antivirus protection.

Antivirus protection must be:

- Enabled
- Configured according to company requirements
- Updated
- Monitored where supported
- Protected from unauthorized disabling

Endpoints must not routinely operate without required antivirus protection.

---

# 23. Antivirus Updates

Antivirus signatures and other applicable protection updates must be distributed regularly through the approved management capability.

Update failures must be investigated when they create material security exposure.

Endpoints that remain materially out of date must be remediated.

---

# 24. Antivirus Detection

Malware detections must be handled according to severity.

Responses may include:

- Quarantine
- Removal
- Endpoint isolation
- Additional scanning
- Credential reset
- Investigation
- Reimaging
- Incident escalation

Material malware events must follow [[POL-009 Incident Response Policy]].

---

# 25. Endpoint Detection and Response

Endpoint Detection and Response (EDR) is not an assumed current control.

The existing endpoint-security baseline uses managed commercial antivirus.

Future EDR deployment may be considered through risk treatment based on:

- Threat
- Risk
- Staffing
- Cost
- Monitoring capability
- Response capability

Planned EDR capability must not be represented as an implemented control.

---

# 26. Operating System Updates

Company Windows endpoints must participate in the central Windows patch-management process.

The process must support:

- Update identification
- Testing
- Scheduling
- Distribution
- Monitoring
- Failure handling
- Rollback where practical

Security updates must be prioritized according to risk.

---

# 27. Application Updates

Supported endpoint applications must receive security updates appropriate to:

- Vulnerability severity
- Exposure
- Business criticality
- Vendor guidance
- Operational risk

Applications that cannot be safely maintained must be evaluated for:

- Replacement
- Removal
- Restriction
- Compensating controls

---

# 28. Patch Failures

Material endpoint patch failures must be investigated.

Repeated or unresolved failures must be:

- Documented
- Remediated
- Escalated when necessary

A patch-management system reporting deployment does not independently prove that every endpoint successfully installed the update.

---

# 29. Unsupported Software

Unsupported endpoint operating systems or applications must be identified.

When vendor security support is unavailable, Dunder Mifflin must evaluate:

- Business need
- Security exposure
- Replacement
- Removal
- Isolation
- Compensating controls

Unsupported software must not remain indefinitely without risk consideration.

---

# 30. Laptop Security

Company laptops must use:

- Approved authentication
- Standard-user operation
- Automatic screen locking
- Full-disk encryption
- Managed antivirus
- Patch management
- Central management where supported

Laptop security must account for operation outside company facilities.

---

# 31. Full-Disk Encryption

Company laptops must use approved full-disk encryption.

Encryption must protect information when a laptop is:

- Lost
- Stolen
- Removed from company control

Encryption status must be verifiable through appropriate management or inspection.

---

# 32. Encryption Recovery Information

Recovery information required to administer company laptop encryption must be protected and recoverable by authorized Information Technology personnel.

Recovery information must not be accessible to unauthorized users.

Loss of an individual employee must not make company-owned encrypted information permanently inaccessible.

---

# 33. Laptop Physical Security

Users must take reasonable measures to protect company laptops from:

- Theft
- Loss
- Unauthorized use
- Unnecessary unattended exposure
- Environmental damage

Laptops containing company information must not be left unnecessarily unattended in publicly accessible locations.

---

# 34. Lost or Stolen Devices

Lost or stolen company devices must be reported promptly.

The response must consider:

- Device type
- Assigned user
- Information stored
- Encryption
- Credentials
- Remote-management capability
- Required credential changes
- Remote lock or wipe
- Incident escalation

Loss of an encrypted device must still be documented and evaluated.

---

# 35. Company Mobile Devices

Company mobile devices must use security controls supported by the platform.

Controls should include:

- Device enrollment
- Passcode requirements
- Inventory
- Security configuration
- Remote lock
- Remote wipe
- Device location where available and authorized

Mobile-device controls must be centrally managed where supported.

---

# 36. Mobile Device Passcodes

Company mobile devices must require an approved passcode or equivalent device-authentication mechanism where supported.

Passcodes must not be disabled for convenience.

Device-lock settings must reduce the risk of unauthorized access following loss or theft.

---

# 37. Remote Lock and Wipe

Company mobile devices must support remote lock or wipe where the device and management platform provide the capability.

Remote lock or wipe should be considered when a device is:

- Lost
- Stolen
- Assigned to a terminated employee
- Believed to be compromised
- Otherwise outside authorized company control

Use of remote wipe must consider preservation needs when the device may contain incident evidence.

---

# 38. Device Location

Device-location capability may be used for legitimate:

- Recovery
- Security
- Asset-management

purposes where available and authorized.

Location capability must not be used for unnecessary employee surveillance.

---

# 39. Personally Owned Devices

General Bring Your Own Device (BYOD) access to corporate systems is not part of the standard endpoint model.

Personally owned devices must not be treated as company-managed endpoints.

Any approved exception must address:

- Business need
- Information access
- Authentication
- Security capability
- Support
- Data handling
- Removal of company access

---

# 40. Personal Devices During Emergencies

Personal devices may be used for emergency safety or communication when necessary.

Emergency use does not automatically authorize:

- Permanent corporate access
- Storage of Restricted information
- Bypass of authentication
- Bypass of security policy

Normal security requirements must resume when emergency conditions end.

---

# 41. Removable Media

Use of removable media must be limited to legitimate business purposes.

Users must take reasonable precautions to prevent:

- Malware introduction
- Unauthorized copying
- Loss of sensitive information
- Uncontrolled distribution

Sensitive information stored on removable media must receive protection appropriate to its classification.

---

# 42. Unknown Removable Media

Unknown or untrusted removable media must not be connected to company endpoints merely to determine its contents.

Suspicious media must be referred to authorized Information Technology or information-security personnel.

Media associated with a suspected incident must be handled according to incident-response and evidence requirements.

---

# 43. External Backup Media

Approved encrypted external hard drives used for company backup are governed by the backup and recovery program rather than ordinary user removable-media use.

Backup media must remain:

- Encrypted
- Controlled
- Tracked
- Protected during storage and transport

Requirements are coordinated with [[POL-010 Business Continuity & Disaster Recovery Policy]].

---

# 44. Sensitive Information on Endpoints

Storage of Confidential or Restricted information on endpoints must be limited to legitimate business need.

Users must not create unnecessary local copies of sensitive information.

Protection must reflect:

- Classification
- Device type
- Encryption
- Physical exposure
- Business need

---

# 45. Restricted Information

Restricted information requires stronger protection than ordinary Internal or Confidential information.

Endpoint use involving Restricted information must be specifically appropriate to:

- User authorization
- Device security
- Storage protection
- Physical environment
- Business purpose

Restricted information must not be placed on unmanaged endpoints.

---

# 46. Payment Information

Endpoints must not be used to create unnecessary storage of full payment-card Primary Account Number (PAN) information.

Dunder Mifflin's payment architecture relies on the approved external payment processor.

Approved retained payment references may include:

- Token
- Card brand
- Last four digits
- Expiration information where required

The payment token is Confidential information.

---

# 47. Email Attachments

Users must exercise caution with unexpected or suspicious email attachments.

Endpoint controls must support detection of malicious files where available.

Suspicious attachments must not be opened merely to determine whether they are malicious.

Potential phishing or malware must be reported according to established procedures.

---

# 48. Web Downloads

Software and files downloaded from the Internet must have a legitimate business purpose.

Users must not bypass endpoint protections to execute blocked or suspicious downloads.

Unexpected security warnings must be reported when appropriate.

---

# 49. Browser Security

Company endpoints must use supported browser configurations appropriate to business applications.

Browser security settings must not be weakened without legitimate technical justification.

Browser extensions or add-ons that create unnecessary security risk must not be installed.

---

# 50. Local Data

Business information stored locally must be limited to what is reasonably required.

Where practical, important business information must be stored or synchronized to approved company systems that support:

- Backup
- Access control
- Recovery
- Business continuity

The only copy of important business information must not remain unnecessarily on one workstation.

---

# 51. Endpoint Backup

Ordinary endpoint backup requirements must reflect business need.

Critical company information should reside on approved company systems covered by established backup processes rather than depend solely on individual workstation backup.

Endpoint replacement must not create unacceptable loss of important business information.

---

# 52. Endpoint Logging

Endpoints must generate security-relevant logs supported by the operating system and security tools.

Relevant events may include:

- Authentication
- Administrative activity
- Malware detection
- System errors
- Security events
- Configuration changes

Logging requirements must remain appropriate to endpoint capabilities and risk.

---

# 53. Endpoint Monitoring

Endpoint monitoring may use:

- Antivirus management
- Patch-management status
- Device-management status
- Security logs
- Inventory
- User reports

Dunder Mifflin does not require continuous observation of every endpoint activity.

Monitoring must remain focused on legitimate security and operational needs.

---

# 54. User Privacy

Endpoint security must not be used as justification for unnecessary or indiscriminate employee surveillance.

Security monitoring must have a legitimate:

- Security
- Operational
- Compliance
- Investigative

purpose.

Monitoring must remain consistent with company policy and applicable requirements.

---

# 55. Endpoint Network Connections

Company endpoints must use authorized network connections.

Users must not configure company endpoints to:

- Bypass company network controls
- Bridge trusted and untrusted networks without authorization
- Provide unauthorized network services
- Act as unauthorized wireless access points

Unexpected network behavior must be investigated.

---

# 56. Remote Endpoint Use

Company laptops used outside Dunder Mifflin facilities must receive the same core endpoint protections required inside company facilities.

Remote users must:

- Protect the device physically.
- Use approved authentication.
- Use approved remote-access methods where required.
- Avoid unnecessary exposure to untrusted systems.
- Report security incidents promptly.

---

# 57. Virtual Private Network

When a company laptop requires access to nonpublic company resources across an external or otherwise untrusted network, an approved Virtual Private Network (VPN) must be used where required by network architecture.

VPN use does not remove the need for:

- Endpoint security
- Authentication
- Least privilege
- Information protection

VPN connectivity does not authorize external remote privileged administration.

---

# 58. Public Applications

Public applications intended for direct Internet access, including Infinity's public customer interface, do not require a corporate VPN solely because the user is outside a company facility.

Public application access remains subject to the application's authentication and authorization requirements.

---

# 59. External Remote Privileged Administration

External remote privileged administration is prohibited.

Company endpoints must not be used to perform external remote privileged administration.

Privileged administration must follow [[POL-003 Access Control Policy]] and [[PRO-002 Enterprise Security Architecture Program]].

Ordinary authorized remote access, including VPN access, does not authorize privileged administration.

Emergency-access procedures do not create an exception to the prohibition on external remote privileged administration.

---

# 60. Contractor Endpoints

Contractor-owned endpoints must not receive unrestricted access to Dunder Mifflin systems.

Contractor access must be based on:

- Business need
- Sponsorship
- System requirements
- Information sensitivity
- Security capability
- Duration
- Risk

Company-controlled endpoints must be used when required by the applicable access design.

Contractor remote access does not authorize external remote privileged administration.

---

# 61. Infinity Contractor Workstation

Privileged Infinity production or administrative contractor activity must occur from the designated company-controlled contractor workspace at Scranton Headquarters.

The workstation must follow applicable endpoint-security requirements.

General contractor VPN access for privileged production administration is prohibited.

External remote privileged administration by the Infinity contractor is prohibited.

---

# 62. Warehouse Endpoint Security

Warehouse endpoints must balance:

- Operational efficiency
- Individual accountability
- Malware protection
- Patch management
- Physical security
- Business continuity

Security controls must not unnecessarily prevent warehouse operations, but operational convenience does not justify eliminating significant transaction accountability.

---

# 63. Endpoint Physical Access

Endpoints in public, shared, or operational areas must be protected against unauthorized physical use.

Controls may include:

- Screen locking
- Workstation placement
- Facility access controls
- User supervision
- Restricted areas where appropriate

Physical security requirements are coordinated with [[POL-011 Physical & Environmental Security Policy]].

---

# 64. Endpoint Security During Personnel Termination

When employment or authorized access ends, applicable endpoint actions must include:

- Account disablement
- Recovery of company devices
- Recovery of authentication devices
- Removal of remote access
- Protection of company information

Requirements are coordinated with [[PROC-001 Joiner-Mover-Leaver Procedure]].

---

# 65. Endpoint Reassignment

Before reassignment to another user, an endpoint must be reviewed and prepared to prevent inappropriate access to the previous user's:

- Credentials
- Sensitive information
- Personal working files not required by the new user
- Privileged access

Reassignment must preserve company records that remain required.

---

# 66. Endpoint Disposal

Endpoints leaving company control must be processed to prevent unauthorized recovery of company information.

Disposal or reuse must consider:

- Storage media
- Information classification
- Encryption
- Required records
- Asset inventory

Sensitive information must be securely removed before disposal where applicable.

---

# 67. Malware Incident Response

Suspected malware must be handled according to:

- [[POL-009 Incident Response Policy]]
- [[PBK-002 Malware & Ransomware Playbook]]

Response may include:

1. Identification
2. Isolation
3. Investigation
4. Containment
5. Credential protection
6. Eradication
7. Recovery
8. Validation
9. Lessons learned

Users must not intentionally conceal malware detections.

---

# 68. Phishing and Credential Compromise

Endpoint controls support the response to phishing and credential compromise.

Potential response actions may include:

- Disconnecting affected systems
- Resetting credentials
- Reviewing authentication activity
- Scanning for malware
- Reviewing suspicious messages
- Investigating unauthorized access

Detailed response is maintained in [[PBK-001 Phishing & Credential Compromise Playbook]].

---

# 69. Ransomware

Suspected ransomware requires prompt escalation.

Affected endpoints may need to be isolated to reduce:

- Further encryption
- Network propagation
- Damage to shared resources
- Additional credential compromise

Recovery must use validated company recovery processes.

Payment of a ransom is not an endpoint remediation method.

---

# 70. Endpoint Isolation

Authorized Information Technology or incident-response personnel may isolate an endpoint when necessary to contain:

- Malware
- Unauthorized access
- Suspicious network activity
- Other security incidents

Isolation actions must consider business impact and incident severity.

---

# 71. Evidence Preservation

Endpoint incident response must preserve relevant evidence where practical.

Evidence may include:

- Security logs
- Antivirus alerts
- Files
- User reports
- Authentication records
- System information
- Relevant timestamps

Evidence handling must follow [[PROC-011 Evidence Handling Procedure]].

---

# 72. Endpoint Recovery

Compromised or materially damaged endpoints must be restored to a trusted state.

Recovery may include:

- Malware removal
- Configuration correction
- Patch installation
- Credential reset
- Restoration from approved sources
- Reimaging

Recovery must not consist solely of returning the endpoint to service without addressing the cause of compromise.

---

# 73. Reimaging

Reimaging should be used when it provides greater confidence than attempting to repair a compromised endpoint in place.

Reimaged endpoints must receive:

- Approved operating-system configuration
- Required patches
- Managed antivirus
- Required business software
- Appropriate user access

Required business information must be restored only from approved sources.

---

# 74. Endpoint Vulnerability Management

Endpoints must participate in applicable vulnerability-management activities.

Activities may include:

- Vulnerability scanning
- Patch-status review
- Software-version review
- Configuration assessment
- Antivirus-status review

Requirements are coordinated with [[PRO-004 Vulnerability Management Program]].

---

# 75. Endpoint Security Assessment

Endpoint security may be assessed using:

- Configuration inspection
- Patch review
- Antivirus review
- Encryption verification
- Account review
- Software inventory
- Vulnerability assessment
- Observation
- Sampling
- Independent Performance

Assessment must evaluate actual conditions rather than policy statements alone.

---

# 76. Endpoint Evidence

Evidence may include:

- Asset inventory
- Endpoint configuration
- Patch records
- Antivirus-management records
- Encryption status
- Mobile-device management records
- Access records
- Vulnerability results
- Incident records
- Lost-device reports
- Change records
- Endpoint assessment results

Evidence must accurately represent actual endpoint conditions.

---

# 77. Evidence Integrity

Personnel must not:

- Falsify endpoint-security status.
- Record patches as installed when they failed.
- Record encryption as enabled when it is not.
- Conceal malware detections.
- Conceal lost devices.
- Represent Planned endpoint controls as implemented.
- Record security tests that were not performed.
- Alter evidence to hide deficiencies.

Known discrepancies must be documented and corrected.

---

# 78. Endpoint Findings

Material endpoint-security deficiencies must be documented.

Examples include:

- Missing antivirus
- Materially outdated antivirus protection
- Missing required patches
- Unapproved local administrative access
- Unencrypted company laptop
- Unauthorized software
- Unsupported software
- Missing screen lock
- Unmanaged company mobile device
- Unknown endpoint
- Repeated security-control failure

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 79. Endpoint Metrics

Endpoint-security metrics may include:

- Managed endpoint coverage
- Antivirus coverage
- Antivirus update failures
- Patch compliance
- Material patch failures
- Laptop encryption coverage
- Mobile-device enrollment
- Unauthorized local administrators
- Malware detections
- Lost or stolen devices
- Unsupported software
- Open endpoint-security findings

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 80. Risk Relationships

This standard provides significant treatment support for risks including:

- R001 Phishing / Credential Compromise
- R002 Business Email Compromise
- R003 Ransomware
- R004 Malware
- R005 Password / Authentication Weakness
- R009 Sensitive Information Theft / Extortion
- R010 Unauthorized / Excessive Access
- R011 Delayed Termination
- R012 Malicious Insider
- R013 Administrative / Configuration Error
- R014 Lost Device
- R015 Shared Warehouse Account Risk
- R018 Third-Party Technology Failure / Compromise
- R019 Infinity Contractor Dependency / Compromise
- R027 Backup / Recovery Failure
- R028 Data Corruption

Risk treatment is maintained in [[RTP-001 Enterprise Risk Treatment Plan]].

---

# 81. Exceptions

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

# 82. Enforcement

Failure to comply with this standard may result in:

- Configuration correction
- Software removal
- Access restriction
- Endpoint isolation
- Privilege removal
- Incident investigation
- Management escalation
- Other appropriate corrective action

Enforcement must be proportionate to the circumstances.

---

# 83. Traceability

This standard supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Endpoint requirements must remain traceable to applicable business and risk requirements.

---

# 84. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-002 Enterprise Security Architecture Program]]
- [[PRO-003 Identity and Access Management Program]]
- [[PRO-004 Vulnerability Management Program]]
- [[PRO-005 Security Operations Program]]
- [[POL-001 Information Security Policy]]
- [[POL-002 Acceptable Use Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-011 Physical & Environmental Security Policy]]
- [[STD-002 Network Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[PROC-001 Joiner-Mover-Leaver Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PBK-001 Phishing & Credential Compromise Playbook]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-001 Enterprise Asset Register]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

---

# 85. Review

This standard must be reviewed:

- At least annually
- Following material endpoint-platform changes
- Following significant endpoint-security incidents
- Following material assessment findings
- Following significant changes in endpoint-related risk

The IT & Information Security Manager coordinates review.

The CIO is responsible for approving material revisions.

---

# 86. Revision History

| Version | Date     | Description                        | Approval |
| ------- | -------- | ---------------------------------- | -------- |
| 1.0     | May 2013 | Initial Endpoint Security Standard | CIO      |