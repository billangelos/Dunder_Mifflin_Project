# STD-004 Server Security Standard

## Document Control

| Field | Value |
|---|---|
| Document ID | STD-004 |
| Title | Server Security Standard |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Server or Security Change |

---

# 1. Purpose

This standard establishes mandatory security requirements for servers supporting Dunder Mifflin, Inc.

Server security must protect:

- Business applications
- Company information
- Authentication services
- File services
- Administrative functions
- Backup and recovery capability
- Business operations

while supporting availability and recovery requirements established by the Business Impact Analysis (BIA).

---

# 2. Scope

This standard applies to company-managed or company-controlled servers, including:

- Windows Server 2012 Standard systems
- Active Directory domain controllers
- Authentication servers
- File servers
- Application servers
- Database servers
- Management servers
- Cloud-hosted servers
- Other company-managed server systems

Application-specific requirements for Infinity are maintained in [[STD-009 Infinity Security Standard]].

---

# 3. Authority

This standard supports:

- [[PRO-002 Enterprise Security Architecture Program]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]

Requirements in this standard are mandatory unless an approved exception exists.

The exception process does not apply where this standard or a governing policy explicitly identifies a requirement as non-exempt.

---

# 4. Server Security Objectives

Server security must:

1. Limit unauthorized access.
2. Restrict privileged administration.
3. Reduce unnecessary services and exposure.
4. Maintain secure configuration.
5. Support timely security updates.
6. Protect authentication services.
7. Protect company information.
8. Generate appropriate security records.
9. Support vulnerability management.
10. Support backup and recovery.
11. Maintain business availability.
12. Support incident investigation.

---

# 5. Authorized Servers

Servers must have a legitimate:

- Business
- Application
- Infrastructure
- Security
- Management

purpose.

Unauthorized server systems must not be connected to production environments.

---

# 6. Server Inventory

Significant servers must be represented in the enterprise asset inventory or supporting technical inventory.

Records should identify, where applicable:

- Server name
- Purpose
- System owner
- Technical custodian
- Hosting location
- Operating system
- Business service supported
- Information classification
- Recovery requirements
- Significant dependencies

Inventory information must support administration, security, assessment, and recovery.

---

# 7. Server Ownership

Each significant server or server service must have an identified accountable owner or responsible business function.

Technical administration may be delegated to Information Technology personnel.

Technical custody does not transfer business ownership of the information or process supported by the server.

---

# 8. Server Platform

The standard Microsoft server platform is Windows Server 2012 Standard where applicable.

Other server platforms may be used when required by:

- Application architecture
- Hosting provider
- Business need
- Technical requirements

Nonstandard platforms require appropriate support and security management.

---

# 9. Server Deployment

New servers must be deployed using an approved configuration appropriate to their purpose.

Deployment must consider:

- Business function
- Information classification
- Required services
- Network exposure
- Administrative access
- Authentication
- Logging
- Patch status
- Backup
- Recovery

A server must not be placed into production solely because the operating system installation completed successfully.

---

# 10. Secure Configuration

Servers must use secure configuration appropriate to their role.

Configuration must address, where applicable:

- Accounts
- Privileges
- Services
- Software
- Network exposure
- Administrative protocols
- Authentication
- Logging
- Security updates
- File permissions
- Backup
- Recovery

Detailed configuration requirements are coordinated with [[STD-006 Secure Configuration Standard]].

---

# 11. Configuration Baseline

Significant server types must have an approved configuration baseline where practical.

The baseline must be sufficient to:

- Support consistent deployment
- Reduce unnecessary exposure
- Identify material configuration drift
- Support assessment
- Support recovery

Baselines must remain practical for the size and complexity of the environment.

---

# 12. Default Configuration

Default server configurations must be reviewed before production use.

Unnecessary default:

- Accounts
- Credentials
- Services
- Applications
- Network services
- Administrative interfaces

must be removed, disabled, changed, or secured where practical.

---

# 13. Unnecessary Services

Servers must run only services reasonably required for their intended role.

Unnecessary services increase:

- Attack surface
- Configuration complexity
- Patch requirements
- Potential failure points

Services must not remain enabled merely because they were installed by default.

---

# 14. Unnecessary Software

Software without a legitimate server function must not be installed on production servers.

Production servers must not routinely be used for:

- General web browsing
- Personal email
- Office productivity
- Entertainment
- Other ordinary user activity

Server software must support the intended server role.

---

# 15. Server Administrative Access

Administrative access must be limited to personnel with a legitimate technical requirement.

Access must follow:

- Least privilege
- Need to know
- Individual accountability
- Appropriate approval

Administrative access must be removed when no longer required.

---

# 16. Separate Privileged Credentials

Administrators must use separate privileged credentials for server administration where supported.

Privileged accounts must not be used for routine:

- Email
- Web browsing
- Office productivity
- Other ordinary user activity

Detailed requirements are maintained in [[STD-005 Authentication & Account Security Standard]].

---

# 17. Domain Administrative Access

Standing Domain Admin membership must normally be limited to:

- IT & Information Security Manager
- System Administrator

Additional standing Domain Admin access requires documented justification and approval.

Personnel who require occasional elevated access must not receive standing Domain Admin membership solely for convenience.

---

# 18. Dedicated Administrative Workstations

Higher-risk server administration must use designated administrative workstations where required by [[PRO-002 Enterprise Security Architecture Program]].

Administrative workstations must be:

- Company controlled
- Securely configured
- Restricted to authorized personnel
- Protected from unnecessary ordinary user activity

---

# 19. External Remote Privileged Administration

External remote privileged server administration is prohibited.

Privileged server administration must occur through approved company-controlled methods and locations.

Ordinary authorized remote access, including Virtual Private Network (VPN) access, does not authorize privileged server administration.

Emergency-access procedures do not create an exception to the prohibition on external remote privileged administration.

---

# 20. Server Authentication

Server access must use approved authentication appropriate to the server's function.

Authentication must support individual accountability for administrative activity where technically supported.

Authentication requirements are maintained in [[STD-005 Authentication & Account Security Standard]].

---

# 21. Shared Administrative Accounts

Shared administrative accounts must be avoided where individual accounts are supported.

When a shared administrative credential is technically unavoidable:

- Use must be restricted.
- Access to the credential must be controlled.
- The reason for use must be documented.
- Individual activity must be attributable through other records where practical.
- The credential must be changed when access changes materially or compromise is suspected.

---

# 22. Service Accounts

Service accounts must have:

- A documented purpose
- An accountable owner
- Required privileges only
- Protected credentials
- Appropriate review

Service accounts must not be used for ordinary interactive user activity where avoidable.

---

# 23. Service Account Privileges

Service-account permissions must be limited to those required by the service.

Administrative privileges must not be assigned automatically because an application requests broad access.

Excessive privileges must be reduced when technically practical.

---

# 24. Service Account Credentials

Service-account credentials must be protected from unauthorized disclosure.

Credentials must not be unnecessarily:

- Shared
- Embedded in scripts
- Stored in readable documentation
- Distributed to users who do not require them

Credential changes must consider service dependencies to avoid preventable outages.

---

# 25. Emergency Access

Emergency server access must follow [[PROC-005 Emergency Access Procedure]].

Emergency credentials must:

- Be protected.
- Be available when legitimately required.
- Have controlled access.
- Support accountability.
- Be reviewed following use.

Emergency access must not become a substitute for normal administrative access.

Emergency access does not authorize external remote privileged administration.

---

# 26. Network Exposure

Servers must be reachable only through network pathways required for their business or technical purpose.

Unnecessary network exposure must be removed.

Server administrative services must not be directly exposed to the Internet.

---

# 27. Internet-Facing Servers

Internet-facing servers require additional attention because of their external exposure.

Security must address:

- Required services
- Patch status
- Authentication
- Administrative access
- Logging
- Application security
- Network restrictions
- Vulnerability management

Public availability does not justify unnecessary administrative exposure.

---

# 28. Internal Servers

Internal servers must not be assumed secure solely because they are not directly Internet accessible.

Internal server security must still include:

- Access control
- Secure configuration
- Patch management
- Logging
- Backup
- Vulnerability management

Internal network location is one layer of protection.

---

# 29. Firewall Protection

Server network access must follow [[STD-002 Network Security Standard]].

Firewall and network controls must restrict access based on legitimate:

- Application
- Administrative
- Infrastructure
- Business

requirements.

Unnecessary pathways must be removed.

---

# 30. Administrative Protocols

Server administration must use secure administrative protocols where supported.

Insecure administrative protocols must not be used when an appropriate secure alternative is supported.

Legacy protocols that cannot be replaced must be restricted and evaluated according to risk.

---

# 31. Patch Management

Windows servers must participate in the approved central Windows patch-management process where supported.

Patch management must include:

- Identification
- Evaluation
- Testing
- Scheduling
- Deployment
- Monitoring
- Failure handling
- Rollback where practical

Server patching must balance security risk and operational availability.

---

# 32. Security Update Prioritization

Server security updates must be prioritized based on factors including:

- Vulnerability severity
- Exploitability
- Internet exposure
- Information sensitivity
- Server criticality
- Available mitigations
- Vendor guidance

Higher-risk exposure requires faster attention.

---

# 33. Patch Testing

Material server updates must be tested where practical before broad production deployment.

Testing should consider:

- Operating-system stability
- Application compatibility
- Authentication
- Business functionality
- Recovery capability

Testing must not create unnecessary delay when a serious actively exploitable condition requires urgent action.

---

# 34. Patch Failures

Material server patch failures must be investigated.

Failed updates must not be counted as successfully implemented solely because deployment was attempted.

Unresolved failures must be:

- Documented
- Risk evaluated
- Remediated
- Escalated when necessary

---

# 35. Unsupported Server Software

Unsupported server operating systems or applications must be identified.

When security support is unavailable, Dunder Mifflin must evaluate:

- Replacement
- Upgrade
- Removal
- Network restriction
- Compensating controls
- Risk acceptance

Unsupported systems must not remain indefinitely without documented risk consideration.

---

# 36. Malware Protection

Applicable Windows servers must use approved malware protection when compatible with the server role and supported by the security product.

Server malware protection must be:

- Enabled where required
- Updated
- Monitored where supported
- Protected from unauthorized disabling

Any exclusion required for application compatibility must be limited and documented.

---

# 37. Malware Exclusions

Antivirus or malware-protection exclusions must not be broader than technically required.

Exclusions must identify:

- Technical reason
- Affected server or application
- Scope
- Responsible administrator

Unnecessary exclusions must be removed.

---

# 38. Server Firewall

Host-based firewall capability should be enabled and configured where supported and appropriate to the server role.

Required traffic must be permitted while unnecessary services remain restricted.

Host-based firewall controls supplement network-boundary controls.

---

# 39. File and Directory Permissions

Server file and directory permissions must follow least privilege.

Access must reflect:

- Business need
- Information classification
- Application requirements
- Administrative requirements

Broad access must not be granted solely to avoid managing permissions.

---

# 40. Sensitive Information

Servers storing or processing Confidential or Restricted information require controls appropriate to that classification.

Controls may include:

- Restricted access
- Stronger authentication
- Network restriction
- Encryption where required
- Logging
- Backup protection
- Physical protection

Classification requirements are maintained in [[POL-004 Information Classification & Handling Policy]] and [[STD-001 Information Classification Standard]].

---

# 41. Encryption

Encryption must be used where required by:

- Information classification
- Transmission risk
- Storage risk
- Contractual requirements
- Security architecture

Encryption does not replace:

- Access control
- Authentication
- Physical protection
- Backup
- Monitoring

---

# 42. Data Transmission

Sensitive server communications across untrusted networks must use suitable transmission protection where supported and required.

Credentials and administrative sessions must not be transmitted in clear text when an appropriate secure alternative is available.

---

# 43. Server Logging

Significant servers must generate security-relevant logs appropriate to their role and capabilities.

Logs may include:

- Authentication activity
- Administrative activity
- Security events
- Service failures
- Application events
- System errors
- Configuration changes

Logging must support reasonable investigation and accountability.

---

# 44. Administrative Logging

Administrative activity must be logged where supported.

Logs should provide sufficient information to determine:

- Account used
- Time
- System affected
- Relevant administrative event

Administrative logging must support investigation of unauthorized or erroneous changes.

---

# 45. Authentication Logging

Authentication events must be logged where supported.

Relevant events may include:

- Successful logons
- Failed logons
- Account lockouts
- Privileged authentication
- Other significant authentication events

Repeated or unusual authentication failures must be reviewed when appropriate.

---

# 46. Time Consistency

Significant servers must maintain reasonably consistent system time.

Consistent time supports:

- Authentication
- Log correlation
- Incident investigation
- Transaction review
- Change review

Material time discrepancies must be corrected.

---

# 47. Log Protection

Server logs must be protected against unauthorized modification or deletion appropriate to their importance.

Administrative access to logs must be limited to personnel with a legitimate requirement.

Logs associated with an active incident must be preserved according to evidence-handling requirements.

---

# 48. Log Review

Server logs must be reviewed based on:

- Server criticality
- Risk
- Known security concerns
- Incident requirements
- Available capabilities

Dunder Mifflin does not require continuous manual review of every server event.

Review must remain practical and risk based.

---

# 49. Active Directory Architecture

Dunder Mifflin maintains at least two cloud-hosted domain controllers or authentication servers.

The systems must use reasonable failure-domain separation within the hosting environment.

Both systems remain dependent on the same overall cloud provider.

That dependency must be considered in:

- Risk management
- Business continuity
- Disaster recovery
- Cloud exit planning

---

# 50. Domain Controller Security

Domain controllers require stronger protection because compromise may affect enterprise authentication and authorization.

Domain controllers must:

- Limit administrative access.
- Run only required services.
- Receive security updates.
- Generate security logs.
- Be backed up appropriately.
- Restrict unnecessary software.
- Restrict unnecessary network exposure.

Ordinary business applications must not be installed on domain controllers without documented technical justification.

---

# 51. Active Directory Changes

Material changes to Active Directory must follow appropriate change-management requirements.

Changes requiring particular care include:

- Domain administrative membership
- Authentication configuration
- Group Policy
- Trust relationships
- Significant group changes
- Domain-controller deployment or removal

Changes must be documented sufficiently to support investigation and recovery.

---

# 52. Cloud-Hosted Servers

Cloud-hosted servers must receive security controls appropriate to their function.

Cloud hosting does not remove the need for:

- Secure configuration
- Access control
- Patch management
- Logging
- Vulnerability management
- Backup
- Recovery

Responsibility for controls must be understood between Dunder Mifflin and the provider.

---

# 53. Cloud Administrative Access

Administrative access to cloud-hosted servers must be restricted to authorized personnel.

Access must use:

- Approved authentication
- Least privilege
- Controlled administrative pathways
- Appropriate logging

Cloud management credentials require protection consistent with their potential enterprise impact.

External remote privileged administration of cloud-hosted servers is prohibited.

---

# 54. Cloud Provider Dependency

Server architecture must recognize provider dependencies.

Potential scenarios include:

- Provider outage
- Administrative lockout
- Security compromise
- Service termination
- Data loss
- Contract failure

Continuity requirements are coordinated with [[PLN-004 Cloud Exit & Emergency Migration Plan]].

---

# 55. Infinity Servers

Infinity server architecture must maintain logical separation between:

**Web Tier → Application Tier → Database Tier**

The public-facing web tier may provide the intended customer interface.

The application and database tiers must not be unnecessarily exposed to the Internet.

---

# 56. Infinity Database Server

The Infinity production database must not be directly accessible from the public Internet.

Database access must be limited to:

- Required application connections
- Authorized administrative activity
- Other specifically approved requirements

Database administrative access must follow least privilege and appropriate authentication.

External remote privileged database administration is prohibited.

---

# 57. Development, Test, and Production

Development, test, and production server environments must be separated for significant applications.

Separation must reduce the likelihood that:

- Development activity affects production.
- Test credentials provide production access.
- Untested changes reach production.
- Production information is unnecessarily exposed.

Requirements are coordinated with [[POL-012 Application & Secure Development Policy]].

---

# 58. Production Data in Nonproduction Systems

Production information must not be copied into development or test systems unless required.

When production information is required:

- Business need must be established.
- Access must be restricted.
- Information must be sanitized where practical.
- Classification requirements continue to apply.

Nonproduction status does not remove information-protection requirements.

---

# 59. Database Security

Database servers must use security controls appropriate to:

- Information sensitivity
- Application architecture
- Administrative access
- Network exposure
- Backup
- Recovery

Database administrative privileges must be restricted.

Applications must not receive broader database privileges than required.

---

# 60. Server Change Management

Material server changes must follow [[POL-007 Change & Configuration Management Policy]].

Changes must address, as applicable:

- Business justification
- Security impact
- Testing
- Approval
- Implementation
- Rollback
- Verification
- Documentation

Emergency changes require appropriate after-action review.

---

# 61. Configuration Changes

Material configuration changes must be documented sufficiently to determine:

- What changed
- Why it changed
- Who authorized it
- Who implemented it
- Whether it succeeded
- Whether recovery documentation was affected

Undocumented significant configuration changes must be investigated.

---

# 62. Server Configuration Backup

Configuration information necessary to restore significant servers must be backed up or otherwise recoverable.

Recovery information may include:

- System configuration
- Application configuration
- Service configuration
- Required software
- Dependencies
- Administrative requirements

Recovery must not rely solely on administrator memory.

---

# 63. Server Backup

Servers containing business information or supporting recoverable services must be included in backup processes appropriate to their BIA requirements.

Backup requirements must consider:

- Information
- Configuration
- Application data
- Recovery dependencies
- Recovery Point Objective (RPO)
- Recovery Time Objective (RTO)

Backup requirements are coordinated with [[PROC-012 Backup & Recovery Procedure]].

---

# 64. Backup Monitoring

Backup activity must be monitored sufficiently to identify material failures.

A completed backup job does not independently prove that information can be successfully restored.

Repeated backup failures must be investigated and corrected.

---

# 65. Restore Testing

Server recovery capability must be tested according to [[POL-010 Business Continuity & Disaster Recovery Policy]].

Representative restoration testing must occur at least quarterly.

Critical systems require a meaningful recovery test at least annually.

Testing must evaluate actual recovery capability rather than backup-job completion alone.

---

# 66. Recovery Requirements

Server recovery must follow the BIA.

Technical recovery design must consider:

- Maximum Tolerable Downtime
- Recovery Time Objective
- Recovery Point Objective
- Dependencies
- Recovery sequence
- Required personnel
- Required documentation

Technical personnel must not independently redefine business recovery requirements.

---

# 67. Recovery Documentation

Recovery documentation must be sufficient for a qualified Information Technology professional unfamiliar with the environment to perform required recovery activities.

Documentation should identify, where applicable:

- Server purpose
- Dependencies
- Required software
- Required configuration
- Backup location
- Authentication requirements
- Recovery sequence
- Validation steps

---

# 68. Recovery Validation

A recovered server must not be considered successfully restored solely because it starts.

Recovery validation must confirm applicable:

- System operation
- Application operation
- Authentication
- Data availability
- Required connectivity
- Business functionality

Validation must reflect the purpose of the recovered service.

---

# 69. Server Availability

Availability design must reflect BIA requirements.

Availability may be supported through:

- Multiple servers
- Cloud-provider capability
- Backup
- Recovery
- Alternate processes
- Manual continuity
- Documented replacement procedures

Redundancy is not automatically required for every server.

---

# 70. Server Capacity

Significant servers must maintain reasonable capacity for expected business operation.

Material resource exhaustion affecting availability must be investigated.

Capacity planning should consider:

- Storage
- Memory
- Processing
- Application growth
- Backup requirements

Excess capacity alone is not a security control, but inadequate capacity can create availability risk.

---

# 71. Server Vulnerability Management

Servers must participate in vulnerability-management activities appropriate to their risk.

Activities include, as applicable:

- Vulnerability scanning
- Patch review
- Configuration review
- Software-version review
- Vendor advisory review

Requirements are coordinated with [[PRO-004 Vulnerability Management Program]].

---

# 72. Vulnerability Remediation

Server vulnerabilities must be prioritized according to risk.

Prioritization must consider:

- Severity
- Exploitability
- Internet exposure
- Information sensitivity
- Business criticality
- Existing controls
- Operational impact

Remediation must follow applicable change-management requirements.

---

# 73. Vulnerability Retesting

Material server vulnerabilities must be retested or otherwise verified after remediation where appropriate.

Closing a vulnerability finding requires evidence that the corrective action addressed the identified condition.

A remediation ticket marked complete is not sufficient by itself.

---

# 74. Server Security Assessment

Server security may be assessed using:

- Configuration inspection
- Account review
- Patch review
- Vulnerability assessment
- Log review
- Backup review
- Restore testing
- Observation
- Sampling
- Independent Performance

Assessment must evaluate actual conditions.

---

# 75. Server Penetration Testing

Servers may be included in authorized penetration testing according to risk and scope.

Testing must follow [[STD-007 Penetration Testing Standard]].

Production testing must be designed to avoid unnecessary business disruption.

---

# 76. Physical Server Security

Company-managed physical server equipment must receive physical protection appropriate to its importance.

Controls may include:

- Restricted rooms
- Locked enclosures
- Controlled facility access
- Environmental protection

Requirements are coordinated with [[POL-011 Physical & Environmental Security Policy]].

---

# 77. Cloud Physical Security

Physical protection of cloud-hosted servers is primarily provided by the hosting provider.

Dunder Mifflin must consider provider physical-security responsibilities as part of third-party security review.

Use of cloud hosting does not eliminate Dunder Mifflin's responsibility for its own:

- Access control
- Configuration
- Information protection
- Recovery
- Provider-risk management

---

# 78. Server Decommissioning

Servers must be securely decommissioned when no longer required.

Decommissioning must address:

- Business information
- Accounts
- Credentials
- Network access
- Backup requirements
- Asset records
- Storage media
- Application dependencies
- Documentation

A server must not simply be abandoned because it is no longer actively used.

---

# 79. Data Retention During Decommissioning

Required business records must be preserved according to applicable retention requirements before server removal.

Unnecessary copies of sensitive information must not be retained solely because the server once hosted them.

Decommissioning must coordinate with business and information owners where necessary.

---

# 80. Storage Media Disposal

Server storage media leaving company control must be handled according to information sensitivity.

Sensitive information must be securely removed or the media destroyed where appropriate before disposal or reuse.

Disposal activity must be documented when required.

---

# 81. Server Incident Response

Suspected server compromise must be handled according to:

- [[POL-009 Incident Response Policy]]
- [[PLN-001 Incident Response Plan]]

Potential indicators include:

- Unauthorized administrative access
- Unexpected services
- Malware
- Unauthorized configuration changes
- Unexpected network connections
- Suspicious authentication
- Data-integrity concerns

---

# 82. Server Isolation

Authorized personnel may isolate a server when necessary to contain a security incident.

Isolation decisions must consider:

- Life safety
- Business impact
- Incident severity
- Evidence
- Dependencies
- Recovery

Emergency containment actions must be documented.

---

# 83. Evidence Preservation

Server incident response must preserve relevant evidence where practical.

Evidence may include:

- Security logs
- Authentication logs
- Application logs
- Configuration
- Files
- Network information
- System information
- Relevant timestamps

Evidence handling must follow [[PROC-011 Evidence Handling Procedure]].

---

# 84. Server Recovery Following Compromise

A compromised server must be restored to a trusted state before normal operation resumes.

Recovery may require:

- Rebuilding
- Reimaging
- Configuration correction
- Patch installation
- Credential reset
- Data restoration
- Application validation

Returning a compromised server to service without addressing the cause is not sufficient recovery.

---

# 85. Server Evidence

Server-security evidence may include:

- Server inventory
- Configuration records
- Account records
- Privileged-access records
- Patch records
- Vulnerability results
- Malware-protection status
- Logs
- Change records
- Backup records
- Restore-test results
- Incident records
- Recovery records

Evidence must accurately represent actual conditions.

---

# 86. Evidence Integrity

Personnel must not:

- Falsify server-security status.
- Record failed patches as successful.
- Conceal unauthorized administrative access.
- Conceal known server vulnerabilities.
- Represent Planned controls as implemented.
- Record backups or restore tests that did not occur.
- Represent failed recovery tests as successful.
- Alter evidence to conceal deficiencies.

Known discrepancies must be documented and addressed.

---

# 87. Server Findings

Material server-security deficiencies must be documented.

Examples include:

- Excessive administrative access
- Internet-exposed management service
- Missing critical security updates
- Unsupported server software
- Unnecessary service
- Missing required backup
- Failed recovery test
- Insecure service-account configuration
- Missing security logging
- Unapproved configuration change
- Excessive database access
- Missing recovery documentation

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 88. Server Metrics

Server-security metrics may include:

- Patch compliance
- Material patch failures
- Critical vulnerabilities
- Vulnerability-remediation age
- Unsupported servers
- Excessive privileged access
- Backup failures
- Restore-test results
- Unapproved configuration changes
- Open server-security findings

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 89. Risk Relationships

This standard provides significant treatment support for risks including:

- R001 Phishing / Credential Compromise
- R003 Ransomware
- R004 Malware
- R005 Password / Authentication Weakness
- R006 Infinity Application Compromise
- R007 Internet Infrastructure Compromise
- R009 Sensitive Information Theft / Extortion
- R010 Unauthorized / Excessive Access
- R011 Delayed Termination
- R012 Malicious Insider
- R013 Administrative / Configuration Error
- R016 Cloud Outage
- R018 Third-Party Technology Failure / Compromise
- R019 Infinity Contractor Dependency / Compromise
- R026 Personnel Loss
- R027 Backup / Recovery Failure
- R028 Data Corruption
- R034 Loss of Headquarters
- R035 Regional Disaster

Risk treatment is maintained in [[RTP-001 Enterprise Risk Treatment Plan]].

---

# 90. Exceptions

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

# 91. Enforcement

Failure to comply with this standard may result in:

- Configuration remediation
- Privilege removal
- Access restriction
- Server isolation
- Software removal
- Incident investigation
- Management escalation
- Other appropriate corrective action

Enforcement must be proportionate to the circumstances.

---

# 92. Traceability

This standard supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Server-security requirements must remain traceable to applicable business and risk requirements.

---

# 93. Related Artifacts

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
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-011 Physical & Environmental Security Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[STD-001 Information Classification Standard]]
- [[STD-002 Network Security Standard]]
- [[STD-003 Endpoint Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[STD-007 Penetration Testing Standard]]
- [[STD-009 Infinity Security Standard]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
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

# 94. Review

This standard must be reviewed:

- At least annually
- Following material server-platform changes
- Following significant server-security incidents
- Following material assessment findings
- Following significant changes in server-related risk

The IT & Information Security Manager coordinates review.

The CIO is responsible for approving material revisions.

---

# 95. Revision History

| Version | Date     | Description                      | Approval |
| ------- | -------- | -------------------------------- | -------- |
| 1.0     | May 2013 | Initial Server Security Standard | CIO      |