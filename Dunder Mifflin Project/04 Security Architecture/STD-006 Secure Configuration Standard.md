# STD-006 Secure Configuration Standard

## Document Control

| Field | Value |
|---|---|
| Document ID | STD-006 |
| Title | Secure Configuration Standard |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | CIO |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Technology or Configuration Change |

---

# 1. Purpose

This standard establishes common secure-configuration requirements for Dunder Mifflin, Inc.

Secure configuration reduces preventable security risk by ensuring that systems are deployed and maintained with:

- Required functionality
- Appropriate security settings
- Limited unnecessary services
- Controlled administrative access
- Documented configuration
- Recoverable configuration information
- Managed changes

Secure configuration must support business requirements without introducing unnecessary complexity.

---

# 2. Scope

This standard applies to company-managed or company-controlled:

- Endpoints
- Laptops
- Servers
- Network devices
- Firewalls
- Routers
- Switches
- Authentication systems
- Business applications
- Security tools
- Cloud-hosted systems
- Administrative workstations
- Other significant technology

System-specific standards may establish additional requirements.

---

# 3. Authority

This standard supports:

- [[PRO-002 Enterprise Security Architecture Program]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-007 Change & Configuration Management Policy]]

Requirements in this standard are mandatory unless an approved exception exists.

---

# 4. Configuration Objectives

Secure configuration must:

1. Reduce unnecessary attack surface.
2. Limit unauthorized access.
3. Support least privilege.
4. Remove unnecessary services and software.
5. Protect administrative interfaces.
6. Support consistent system deployment.
7. Support patch and vulnerability management.
8. Support monitoring and investigation.
9. Reduce preventable configuration errors.
10. Support recovery.
11. Support assessment.
12. Maintain accurate technical documentation.

---

# 5. Configuration Responsibility

Information Technology personnel responsible for a system must maintain configuration appropriate to its:

- Business purpose
- Technical role
- Information classification
- Network exposure
- Recovery requirements
- Risk

Business owners remain responsible for business requirements and authorized use of the system.

---

# 6. Configuration Baselines

Dunder Mifflin must establish approved configuration baselines for significant technology where practical.

Baselines must identify important required settings sufficient to:

- Support repeatable deployment
- Reduce unnecessary exposure
- Support security review
- Identify material configuration drift
- Support recovery

Baselines must remain appropriate to the size and complexity of the environment.

---

# 7. Baseline Scope

Configuration baselines should be established for significant categories including:

- Windows endpoints
- Company laptops
- Windows servers
- Domain controllers
- Firewalls and routers
- Administrative workstations
- Significant applications
- Other security-relevant systems

Different system roles may require different baseline configurations.

---

# 8. Baseline Development

Configuration baselines must consider:

- Business requirements
- System purpose
- Vendor guidance
- Security requirements
- Information classification
- Network exposure
- Known vulnerabilities
- Operational compatibility
- Recovery requirements

A secure setting must not be applied blindly when it would prevent a required business function.

---

# 9. Baseline Documentation

Configuration baselines must document significant settings sufficiently to support:

- Deployment
- Administration
- Assessment
- Troubleshooting
- Recovery

Documentation may identify:

- Required settings
- Prohibited settings
- Required services
- Required software
- Administrative requirements
- Approved exceptions

---

# 10. Baseline Approval

Significant configuration baselines must be reviewed and approved by appropriate Information Technology or information-security personnel.

Material baseline changes must follow [[POL-007 Change & Configuration Management Policy]] where applicable.

---

# 11. Current State and Required State

A documented configuration requirement does not establish that every system currently meets that requirement.

Configuration management must distinguish between:

- Required configuration
- Actual configuration
- Approved exception
- Planned remediation

Planned configuration improvements must not be represented as implemented controls.

---

# 12. Default Settings

Default system configurations must be reviewed before production deployment.

Default settings must not be assumed secure merely because they were provided by the vendor.

Review must address, where applicable:

- Accounts
- Credentials
- Services
- Software
- Administrative interfaces
- Network exposure
- Logging
- Security settings

---

# 13. Default Credentials

Default passwords and other default administrative credentials must be changed before production use.

Where a default account cannot be removed, its access must be appropriately:

- Restricted
- Protected
- Monitored where supported

Vendor-default credentials must not remain active solely for convenience.

---

# 14. Default Accounts

Default accounts must be reviewed before production deployment.

Where supported and appropriate, unnecessary default accounts must be:

- Disabled
- Removed
- Renamed
- Restricted

Required default accounts must receive protection appropriate to their privileges.

---

# 15. Unnecessary Services

Systems must run only services reasonably required for their intended purpose.

Unnecessary services must be disabled or removed where practical.

Service reduction must consider legitimate:

- Business dependencies
- Application dependencies
- Management requirements
- Recovery requirements

---

# 16. Unnecessary Software

Software without a legitimate business, technical, administrative, or security purpose must not be installed on company systems.

Unnecessary software increases:

- Attack surface
- Patch requirements
- Administrative complexity
- Potential software conflicts

Production systems must remain focused on their intended function.

---

# 17. Required Software

Required software must be:

- Authorized
- Supported where practical
- Maintained
- Configured appropriately
- Included in vulnerability and patch management where applicable

Required software must not be exempt from security management merely because it supports an important business function.

---

# 18. Administrative Interfaces

Administrative interfaces must be restricted to authorized personnel and appropriate management paths.

Administrative interfaces must not be unnecessarily exposed to:

- Public networks
- Ordinary users
- Untrusted systems
- Third parties

Internet exposure of administrative interfaces is prohibited unless an approved exception exists.

---

# 19. Administrative Protocols

Secure administrative protocols must be used where supported.

Insecure management protocols must not be used when an appropriate secure alternative is available and supported.

Where a legacy protocol is technically required, exposure must be restricted and risk evaluated.

---

# 20. Administrative Accounts

Administrative accounts must comply with:

- [[POL-003 Access Control Policy]]
- [[STD-005 Authentication & Account Security Standard]]

Administrative privileges must be assigned only to personnel with legitimate responsibilities.

Ordinary user accounts must not receive administrative privileges solely for convenience.

---

# 21. Separate Privileged Credentials

Separate privileged credentials must be used for administrative activity where supported.

Privileged credentials must not routinely be used for:

- Email
- Web browsing
- Office productivity
- Ordinary business activity

Configuration must support separation between ordinary and privileged activity where practical.

---

# 22. Least Functionality

Systems must provide only the functionality required for their authorized purpose.

Configuration should restrict unnecessary:

- Services
- Ports
- Protocols
- Applications
- Accounts
- Administrative capabilities

Least functionality must be balanced against legitimate business and operational requirements.

---

# 23. Network Exposure

System configuration must limit network exposure to required communication.

Configuration must consider:

- Required source systems
- Required destinations
- Required services
- Administrative pathways
- Internet exposure
- Application dependencies

Unnecessary listening services and pathways must be removed where practical.

---

# 24. Host Firewall Configuration

Host-based firewall capability should be enabled where supported and appropriate.

Host firewall configuration must permit required business and administrative communication while restricting unnecessary access.

Host firewall controls supplement network-security controls.

---

# 25. Network Device Configuration

Firewalls, routers, switches, and other significant network devices must comply with [[STD-002 Network Security Standard]].

Configuration must address, where applicable:

- Administrative access
- Required services
- Firewall rules
- Logging
- Authentication
- Management protocols
- Configuration backup

---

# 26. Endpoint Configuration

Endpoints must comply with [[STD-003 Endpoint Security Standard]].

Endpoint configuration must address:

- Standard-user operation
- Managed antivirus
- Patch management
- Screen locking
- Approved software
- Authentication
- Laptop encryption where required
- Logging

---

# 27. Server Configuration

Servers must comply with [[STD-004 Server Security Standard]].

Server configuration must address:

- Required services
- Administrative access
- Authentication
- Patch management
- Logging
- Backup
- Network exposure
- Recovery

---

# 28. Domain Controller Configuration

Domain controllers require configuration appropriate to their enterprise authentication role.

Configuration must:

- Restrict administrative access.
- Limit unnecessary services.
- Restrict unnecessary software.
- Support security logging.
- Support backup and recovery.
- Receive security updates.
- Protect authentication functions.

Ordinary business applications must not be installed on domain controllers without documented technical justification.

---

# 29. Administrative Workstation Configuration

Dedicated administrative workstations must use a more restricted configuration appropriate to privileged activity.

Configuration must:

- Limit unnecessary software.
- Restrict ordinary user activity.
- Use managed antivirus.
- Receive security updates.
- Require approved authentication.
- Limit use to authorized administrators.

Administrative workstations must not become ordinary shared office computers.

---

# 30. Laptop Configuration

Company laptops must use:

- Standard-user operation
- Full-disk encryption
- Managed antivirus
- Central patch management
- Automatic screen locking
- Approved authentication
- Central management where supported

Configuration must account for operation outside company facilities.

---

# 31. Warehouse Workstation Configuration

Warehouse workstations must use configuration appropriate to their operational role.

Configuration must:

- Limit unnecessary software.
- Limit unnecessary privileges.
- Use managed antivirus.
- Participate in patch management.
- Support required business applications.
- Protect significant transaction accountability.

Shared Windows accounts do not authorize broad workstation privileges.

---

# 32. Mobile Device Configuration

Company mobile devices must use supported security settings appropriate to the device.

Configuration should include:

- Passcode requirements
- Automatic locking
- Enrollment
- Remote lock
- Remote wipe
- Inventory
- Other available management settings

Mobile controls must be centrally managed where supported.

---

# 33. Application Configuration

Significant applications must use configuration appropriate to:

- Business function
- Information classification
- Authentication
- Authorization
- Network exposure
- Logging
- Recovery

Application configuration must not provide broader access than required.

---

# 34. Infinity Configuration

Infinity configuration must comply with:

- [[POL-012 Application & Secure Development Policy]]
- [[STD-009 Infinity Security Standard]]

Configuration must support logical separation between:

**Web Tier → Application Tier → Database Tier**

The production database must not be directly accessible from the public Internet.

---

# 35. Development, Test, and Production Configuration

Development, test, and production environments must be separated for significant applications.

Configuration must reduce the likelihood that:

- Development credentials provide production access.
- Test systems expose production information.
- Development changes directly affect production.
- Unapproved code reaches production.

---

# 36. Authentication Configuration

Authentication configuration must comply with [[STD-005 Authentication & Account Security Standard]].

Configuration must support, where applicable:

- Unique accounts
- Password controls
- Account lockout
- Privileged-account separation
- Dormant-account management
- Smart-card authentication where implemented
- Authentication logging

---

# 37. Smart-Card Configuration

Where smart-card multi-factor authentication is implemented, configuration must require:

- The authorized smart card, and
- The associated PIN or other approved secret.

Smart-card capability must not be represented as implemented before deployment and validation.

---

# 38. Logging Configuration

Significant systems must enable security-relevant logging appropriate to their capabilities and risk.

Logging may include:

- Authentication
- Administrative activity
- Security events
- Configuration changes
- Application events
- Malware detections
- System failures

Logging must support reasonable investigation and accountability.

---

# 39. Logging Limitations

Configuration documentation must accurately reflect system logging capability.

Personnel must not represent a system as logging events it does not actually record.

Where required security events cannot be logged, the limitation must be evaluated according to risk.

---

# 40. Time Configuration

Significant systems must maintain reasonably consistent system time where supported.

Consistent timestamps support:

- Authentication
- Event correlation
- Incident investigation
- Change review
- Transaction analysis

Material time discrepancies must be corrected.

---

# 41. Malware Protection Configuration

Applicable Windows endpoints and servers must use approved managed commercial antivirus.

Configuration must support:

- Active protection
- Security updates
- Detection
- Quarantine or response capability
- Central status visibility where supported

Users must not disable required protection without authorization.

---

# 42. Malware Protection Exclusions

Antivirus exclusions must be limited to legitimate technical requirements.

An exclusion must not be created solely to stop a security alert without determining whether the affected activity is legitimate.

Material exclusions must be documented where appropriate.

---

# 43. Patch Configuration

Applicable systems must be configured to participate in approved patch-management processes.

Patch configuration must support, where applicable:

- Update distribution
- Deployment status
- Failure identification
- Scheduling
- Testing
- Rollback

Patch management must not rely solely on individual users installing updates.

---

# 44. Unsupported Configuration

Systems that cannot support required security configuration must be identified.

The organization must evaluate:

- Upgrade
- Replacement
- Restriction
- Compensating controls
- Risk acceptance

Technical limitation does not automatically create an indefinite exception.

---

# 45. Information Protection Configuration

System configuration must support information handling requirements established through:

- [[POL-004 Information Classification & Handling Policy]]
- [[STD-001 Information Classification Standard]]

Controls must reflect the sensitivity of information processed or stored by the system.

---

# 46. Encryption Configuration

Encryption must be configured where required by:

- Information classification
- Device type
- Transmission risk
- Storage risk
- Security architecture
- Contractual requirements

Encryption configuration must use approved capabilities appropriate to the system.

---

# 47. Laptop Encryption Configuration

Company laptops must use approved full-disk encryption.

Configuration must ensure that:

- Protection is enabled.
- Recovery information is available to authorized Information Technology personnel.
- Encryption status can be verified.

A laptop must not be recorded as encrypted merely because encryption software is installed.

---

# 48. Backup Media Encryption

External hard drives used for company backup must remain encrypted.

Encryption must protect backup information during:

- Local storage
- Transportation
- Off-site storage
- Rotation

Encryption configuration must not prevent authorized recovery.

---

# 49. Secure Communications

Systems transmitting sensitive information or credentials across untrusted networks must use appropriate protected communication where supported.

Unencrypted protocols must not be used when an appropriate secure alternative is supported.

Legacy requirements must be restricted according to risk.

---

# 50. Configuration Changes

Material configuration changes must follow [[POL-007 Change & Configuration Management Policy]].

Changes must address, as applicable:

- Business need
- Security impact
- Testing
- Approval
- Implementation
- Rollback
- Verification
- Documentation

---

# 51. Standard Changes

Routine, low-risk, repeatable configuration changes may be handled as approved Standard Changes when they meet the criteria established by change management.

Standard status must not be used to bypass appropriate control.

A Standard Change must remain:

- Defined
- Repeatable
- Low risk
- Authorized

---

# 52. Normal Changes

Normal configuration changes require review and approval appropriate to:

- Risk
- Scope
- Business impact
- Technical complexity

Testing and rollback requirements must reflect the potential impact of failure.

---

# 53. Emergency Changes

Emergency configuration changes may use expedited approval when necessary to:

- Address a serious security condition
- Restore critical service
- Prevent material business harm

Emergency status does not eliminate documentation, verification, or after-action review requirements.

---

# 54. Testing Configuration Changes

Material configuration changes must be tested where practical before production deployment.

Testing must consider:

- Business functionality
- Security
- Application compatibility
- Authentication
- Connectivity
- Recovery

Testing must be proportionate to the change.

---

# 55. Rollback

Material changes must have a reasonable rollback or recovery approach where practical.

Rollback planning must consider:

- Previous configuration
- Configuration backup
- System dependencies
- Data impact
- Business impact

A change must not assume that the previous state can be reconstructed from memory.

---

# 56. Post-Change Verification

Material changes must be verified after implementation.

Verification must determine whether:

- The intended change occurred.
- Required functionality remains available.
- Security controls remain operational.
- Unexpected exposure was introduced.
- Further corrective action is required.

Successful execution of a change command alone is not sufficient verification.

---

# 57. Configuration Documentation After Change

Material changes must result in updates to affected technical documentation where required.

Documentation may include:

- Configuration baselines
- Network diagrams
- Recovery procedures
- Application documentation
- Administrative instructions

A significant change is not complete until required documentation is updated or an explicit corrective action exists.

---

# 58. Configuration Drift

Configuration drift occurs when actual system configuration materially differs from the approved or expected configuration without appropriate authorization.

Material configuration drift must be:

1. Identified
2. Investigated
3. Authorized or corrected
4. Documented where appropriate

Drift must not automatically be treated as malicious activity.

---

# 59. Drift Detection

Configuration drift may be identified through:

- Administrative review
- Vulnerability assessment
- Configuration inspection
- Change review
- Troubleshooting
- Security assessment
- Incident investigation

Dunder Mifflin does not require continuous automated configuration monitoring for every system.

---

# 60. Unauthorized Configuration Changes

Known unauthorized configuration changes must be investigated.

Investigation must consider whether the change resulted from:

- Administrative error
- Informal operational activity
- Unauthorized user activity
- Malware
- Compromise
- Failed change management

Security-related unauthorized changes may require incident escalation.

---

# 61. Configuration Backup

Configuration information necessary to restore significant technology must be backed up or otherwise recoverable.

This applies, where relevant, to:

- Firewalls
- Routers
- Servers
- Authentication systems
- Significant applications
- Other critical infrastructure

Recovery must not depend solely on administrator memory.

---

# 62. Configuration Backup Protection

Configuration backups must be protected according to the sensitivity of the information they contain.

Configuration information may expose:

- Internal network structure
- Security settings
- Administrative details
- System dependencies
- Access-control information

Access must be limited to authorized personnel.

---

# 63. Configuration Recovery

Configuration backups must be usable for recovery.

Where practical, recovery testing should verify that required configuration can be:

- Located
- Accessed
- Understood
- Applied

Possession of an unreadable, obsolete, or incomplete configuration copy does not establish recovery capability.

---

# 64. Recovery Documentation

Configuration documentation required for recovery must be sufficient for a qualified Information Technology professional unfamiliar with the environment to perform the required work.

Documentation must not depend unnecessarily on undocumented personal knowledge.

---

# 65. Configuration and Business Continuity

Secure configuration must support Business Continuity/Disaster Recovery (BC/DR).

Configuration management must consider:

- Recovery sequence
- System dependencies
- Authentication
- Network connectivity
- Required services
- Backup
- Replacement equipment

Significant configuration changes must trigger review of affected recovery documentation.

---

# 66. Configuration and Vulnerability Management

Secure configuration and vulnerability management are related but distinct activities.

A vulnerability may result from:

- Missing security update
- Insecure configuration
- Unnecessary service
- Unsupported software
- Excessive exposure

Configuration-related vulnerabilities must be handled through [[PRO-004 Vulnerability Management Program]] where applicable.

---

# 67. Vulnerability Remediation Changes

Configuration changes used to remediate vulnerabilities must follow applicable change-management requirements.

Urgent vulnerability remediation may use emergency-change procedures when justified by risk.

Remediation must be verified after implementation.

---

# 68. Configuration and Incident Response

Security incidents may require configuration changes for:

- Containment
- Credential protection
- Network restriction
- Service disabling
- Recovery

Emergency incident-response changes must be documented and reviewed after the immediate condition is controlled.

---

# 69. Configuration Evidence During Incidents

When configuration is relevant to an incident, investigators must preserve appropriate evidence before making changes where practical.

Evidence may include:

- Configuration exports
- Screenshots
- Logs
- System settings
- Firewall rules
- Account settings

Evidence preservation must not prevent necessary emergency containment.

---

# 70. Third-Party Configuration

Third-party support personnel may modify company configuration only when:

- Authorized
- Within approved scope
- Required for the engagement
- Subject to applicable change control

Third-party status does not authorize unrestricted configuration changes.

---

# 71. Infinity Contractor Configuration Changes

Infinity contractor changes to production systems must comply with:

- [[POL-012 Application & Secure Development Policy]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]

Contractor changes must remain under Dunder Mifflin's authorization and oversight.

---

# 72. Cloud Configuration

Company-controlled cloud configuration must follow the same risk-based principles applied to other systems.

Cloud configuration must consider:

- Administrative access
- Authentication
- Network exposure
- Application access
- Logging
- Backup
- Recovery
- Provider dependencies

Cloud hosting does not make insecure configuration acceptable.

---

# 73. Provider-Controlled Configuration

Where configuration is controlled by a service provider, Dunder Mifflin must understand the division of responsibility.

The organization must not claim direct configuration control where the provider controls the setting.

Provider-controlled security must be addressed through:

- Third-party review
- Contractual requirements
- Service configuration options
- Risk management

---

# 74. Configuration Documentation

Significant configuration documentation must be:

- Accurate
- Understandable
- Protected appropriately
- Updated following material changes
- Available to authorized personnel

Documentation must describe actual configuration rather than an idealized design.

---

# 75. Configuration Records

Configuration records may include:

- Baseline documents
- Device configurations
- System settings
- Application settings
- Firewall rules
- Group Policy settings
- Change records
- Exception records
- Configuration backups
- Diagrams

Records must be retained according to operational and security needs.

---

# 76. Sensitive Configuration Information

Configuration documentation containing sensitive security information must be protected.

Sensitive configuration information may include:

- Internal addressing
- Firewall rules
- Administrative paths
- Security settings
- Authentication details
- System dependencies

Access must be limited according to business need.

---

# 77. Configuration Review

Significant configuration must be reviewed periodically based on:

- Risk
- System criticality
- Exposure
- Change frequency
- Known security concerns

Review must focus on meaningful security conditions rather than unnecessary documentation volume.

---

# 78. High-Risk Configuration

Higher-risk configuration includes settings affecting:

- Privileged access
- Internet exposure
- Authentication
- Sensitive information
- Firewall rules
- Domain administration
- Production databases
- Backup and recovery

Changes to higher-risk configuration require stronger review and verification.

---

# 79. Configuration Assessment

Secure-configuration controls may be assessed using:

- Inspection
- Observation
- Interviews
- Configuration review
- Technical Testing
- Vulnerability assessment
- Sampling
- Independent Performance
- Comparison with approved baselines

Assessment must evaluate actual system configuration.

---

# 80. Configuration Sampling

When assessment of every system is impractical, representative sampling may be used.

Sampling must consider:

- System type
- Risk
- Criticality
- Location
- Configuration differences

Sampling must not intentionally exclude systems known or suspected to have configuration problems.

---

# 81. Baseline Validation

Configuration baselines must be periodically evaluated to determine whether they remain:

- Technically appropriate
- Operationally usable
- Consistent with security requirements
- Consistent with current architecture

A baseline can become outdated even when systems continue to match it.

---

# 82. Configuration Evidence

Evidence may include:

- Approved baselines
- Configuration exports
- Screenshots
- System settings
- Device configurations
- Change records
- Approval records
- Vulnerability results
- Configuration-review results
- Backup records
- Recovery-test results
- Exception records

Evidence must accurately represent actual conditions.

---

# 83. Evidence Integrity

Personnel must not:

- Falsify configuration records.
- Alter evidence to conceal unauthorized changes.
- Represent Planned configuration as implemented.
- Record baseline compliance without verifying it.
- Conceal material configuration drift.
- Record tests that were not performed.
- Represent failed configuration validation as successful.

Known discrepancies must be documented and addressed.

---

# 84. Configuration Findings

Material secure-configuration deficiencies must be documented.

Examples include:

- Default credential remaining active
- Unnecessary service
- Unauthorized administrative interface
- Excessive network exposure
- Missing configuration backup
- Unapproved configuration change
- Material baseline deviation
- Insecure legacy protocol without appropriate restriction
- Missing required logging
- Incorrect authentication configuration
- Configuration inconsistent with recovery documentation

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 85. Corrective Action

Configuration corrective action must identify:

- Deficiency
- Affected system
- Responsible owner
- Required remediation
- Due date
- Validation method

Corrective action is not complete until remediation is implemented and appropriately verified.

---

# 86. Configuration Metrics

Configuration-security metrics may include:

- Baseline coverage
- Material baseline deviations
- Unauthorized configuration changes
- Default credentials identified
- Unnecessary services identified
- Configuration backups available
- Changes awaiting documentation
- Emergency changes
- Failed post-change verification
- Open configuration findings
- Overdue corrective actions

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 87. Risk Relationships

This standard provides significant treatment support for risks including:

- R003 Ransomware
- R004 Malware
- R005 Password / Authentication Weakness
- R006 Infinity Application Compromise
- R007 Internet Infrastructure Compromise
- R009 Sensitive Information Theft / Extortion
- R010 Unauthorized / Excessive Access
- R012 Malicious Insider
- R013 Administrative / Configuration Error
- R014 Lost Device
- R015 Shared Warehouse Account Risk
- R016 Cloud Outage
- R018 Third-Party Technology Failure / Compromise
- R019 Infinity Contractor Dependency / Compromise
- R027 Backup / Recovery Failure
- R028 Data Corruption
- R034 Loss of Headquarters

Risk treatment is maintained in [[RTP-001 Enterprise Risk Treatment Plan]].

---

# 88. Exceptions

Exceptions to this standard require:

- Business justification
- Identification of the affected requirement
- Risk evaluation
- Compensating controls where practical
- Accountable owner
- Defined duration
- Appropriate approval

High or Critical residual risk must be escalated according to [[POL-005 Risk Management Policy]].

---

# 89. Exception Review

Configuration exceptions must be reviewed before expiration.

Review must determine whether the exception should be:

- Closed
- Remediated
- Renewed with justification
- Escalated

An expired exception does not automatically become permanent authorization.

---

# 90. Enforcement

Failure to comply with this standard may result in:

- Configuration correction
- Access restriction
- Privilege removal
- Service disabling
- System isolation
- Change reversal
- Incident investigation
- Management escalation
- Other appropriate corrective action

Enforcement must be proportionate to the circumstances.

---

# 91. Traceability

This standard supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Secure-configuration requirements must remain traceable to applicable business and risk requirements.

---

# 92. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-002 Enterprise Security Architecture Program]]
- [[PRO-003 Identity and Access Management Program]]
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
- [[POL-012 Application & Secure Development Policy]]
- [[STD-001 Information Classification Standard]]
- [[STD-002 Network Security Standard]]
- [[STD-003 Endpoint Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-009 Infinity Security Standard]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-006 Vulnerability Assessment Procedure]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]
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

# 93. Review

This standard must be reviewed:

- At least annually
- Following material technology changes
- Following significant configuration-related incidents
- Following material assessment findings
- Following significant changes in configuration-related risk

The CIO is responsible for approving material revisions.

---

# 94. Revision History

| Version | Date     | Description                           | Approval |
| ------- | -------- | ------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Secure Configuration Standard | CIO      |