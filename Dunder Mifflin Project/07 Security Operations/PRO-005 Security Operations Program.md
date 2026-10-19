# PRO-005 Security Operations Program

## Document Control

| Field | Value |
|---|---|
| Document ID | PRO-005 |
| Title | Security Operations Program |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Security Operations or Technology Change |

---

# 1. Purpose

This program establishes how Dunder Mifflin, Inc. performs ongoing security operations to identify, review, investigate, escalate, and respond to security-relevant conditions.

The program provides a practical operating model appropriate to the company's Information Technology (IT) organization, business environment, and security risks.

Security Operations provides the connection between preventive controls and operational response.

---

# 2. Scope

This program applies to security operations involving:

- Endpoints
- Servers
- Active Directory
- Network infrastructure
- Firewalls and routers
- Cloud-hosted systems
- Business applications
- Infinity
- Company laptops
- Company mobile devices
- Warehouse technology
- Security tools
- Authentication activity
- Malware protection
- Security-relevant logs
- Vulnerability information
- Third-party security notifications
- Physical-security information when relevant to information security

---

# 3. Authority

This program supports and implements requirements established by:

- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-006 Security Awareness & Training Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-011 Physical & Environmental Security Policy]]
- [[POL-012 Application & Secure Development Policy]]

---

# 4. Objectives

Security Operations must:

1. Maintain reasonable awareness of security-relevant activity.
2. Identify conditions requiring investigation.
3. Escalate significant security events.
4. Support malware prevention and response.
5. Monitor authentication and privileged activity where appropriate.
6. Detect unexpected network devices and wireless infrastructure.
7. Integrate vulnerability information with operational security.
8. Support incident response.
9. Maintain reliable operational evidence.
10. Provide meaningful operational, management, and executive reporting.
11. Improve security operations based on findings and experience.

---

# 5. Operating Model

Dunder Mifflin maintains a small internal IT organization.

Security Operations is performed through coordinated responsibilities rather than a dedicated Security Operations Center (SOC).

The operating model relies on:

- Defined responsibilities
- Security-tool alerts
- Administrative review
- User reporting
- Vulnerability information
- Event escalation
- Incident-response procedures
- Management oversight

---

# 6. IT Organization

The Information Technology organization consists of approximately six personnel:

- IT & Information Security Manager
- System Administrator
- Network/Security Administrator
- Information Security Analyst
- Two IT Support personnel

Security responsibilities are distributed across these roles according to expertise and access.

---

# 7. Information Security Analyst

The Information Security Analyst normally coordinates day-to-day security operations.

Responsibilities include:

- Reviewing security-relevant information
- Investigating suspicious events
- Coordinating vulnerability information
- Supporting malware investigation
- Maintaining operational security records
- Escalating significant events
- Supporting incident response
- Producing security metrics and reports

---

# 8. IT & Information Security Manager

The IT & Information Security Manager provides operational oversight.

Responsibilities include:

- Establishing security priorities
- Reviewing significant events
- Coordinating technical personnel
- Approving appropriate operational actions
- Escalating material issues to the CIO
- Supporting incident-response activation
- Reviewing Security Operations performance

---

# 9. System Administrator

The System Administrator supports Security Operations for:

- Windows servers
- Active Directory
- Authentication
- Server logs
- Server malware events
- System configuration
- Server recovery
- Privileged activity

---

# 10. Network/Security Administrator

The Network/Security Administrator supports Security Operations for:

- Firewalls
- Routers
- Switches
- Network connectivity
- Virtual Private Network (VPN)
- Network-security configuration
- Network discovery
- Unauthorized network devices
- Wireless discovery
- Network-related security events

---

# 11. IT Support

IT Support personnel may identify and report:

- Malware symptoms
- Suspicious user activity
- Lost equipment
- Unusual endpoint behavior
- Security-tool alerts
- User-reported phishing
- Account problems

IT Support must escalate security-relevant conditions rather than independently dismissing them.

---

# 12. Business Personnel

All personnel contribute to Security Operations by reporting suspected:

- Phishing
- Malware
- Unauthorized access
- Lost devices
- Suspicious messages
- Unusual system behavior
- Information exposure
- Physical-security concerns

Security awareness requirements are established by [[POL-006 Security Awareness & Training Policy]].

---

# 13. No Dedicated SOC

Dunder Mifflin does not maintain a dedicated Security Operations Center.

Security Operations must not be represented as a dedicated SOC function unless such a capability is actually implemented.

The absence of a SOC does not eliminate the need for security monitoring and event response.

---

# 14. No 24x7 Monitoring Baseline

Continuous human monitoring 24 hours per day, seven days per week is not an existing company capability.

Security records must not imply that continuous human monitoring occurs when it does not.

Security tools may continue collecting information outside business hours.

---

# 15. After-Hours Coverage

A simple after-hours security contact and on-call process should be maintained for significant events requiring action before the next business period.

After-hours coverage should identify:

- Primary contact
- Alternate contact
- Contact method
- Escalation criteria
- Authority to initiate urgent response

This capability must not be described as 24x7 SOC monitoring.

---

# 16. Security Monitoring Principle

Security monitoring means maintaining risk-appropriate awareness of security-relevant conditions.

It does not require continuous human observation of every system, log, event, or user action.

Monitoring must focus on information that can support meaningful security decisions.

---

# 17. Security Event Sources

Security-relevant information may originate from:

- Managed antivirus
- Windows event logs
- Active Directory logs
- Firewall logs
- VPN logs
- Application logs
- Server logs
- Authentication records
- Cloud-service information
- Vulnerability assessments
- Penetration tests
- User reports
- Administrator observations
- Third-party notifications
- Physical-security reports
- Security incidents

---

# 18. Event Collection

Security-relevant systems should generate and retain appropriate records where technically supported.

Collection should prioritize events associated with:

- Authentication
- Privileged activity
- Malware
- Administrative changes
- Access failures
- Significant application events
- Security-control changes
- Network-security events

---

# 19. Log Availability

Security-relevant logs must be available long enough to support reasonable:

- Investigation
- Incident response
- Troubleshooting
- Control assessment
- Evidence collection

Retention requirements may differ by system capability and business need.

---

# 20. Log Protection

Security logs must be protected from unauthorized:

- Modification
- Deletion
- Access

Administrative access to security-relevant logs must be restricted appropriately.

---

# 21. Time Consistency

Systems should maintain reasonably consistent time.

Consistent time supports:

- Event correlation
- Investigation
- Evidence review
- Incident timelines
- Administrative troubleshooting

Material time discrepancies must be corrected.

---

# 22. Centralized Log Management

Centralized collection may improve security monitoring where technically and economically justified.

The program does not assume that all security logs are centrally collected.

Systems may require direct review when centralized capability is unavailable.

---

# 23. No SIEM Baseline

A Security Information and Event Management (SIEM) platform is not assumed as an existing control.

Security monitoring must not depend on capabilities that have not been implemented.

Future implementation of centralized security monitoring may be evaluated based on:

- Risk
- Cost
- Staffing
- Event volume
- Operational benefit

---

# 24. No EDR Baseline

Endpoint Detection and Response (EDR) is not assumed as an existing control.

The current endpoint malware-defense baseline uses centrally managed commercial antivirus.

Future endpoint-security capabilities may be evaluated through the security program.

---

# 25. Antivirus Operations

Managed commercial antivirus must remain deployed and maintained on applicable company systems.

Operational responsibilities include:

- Maintaining protection
- Receiving updates
- Reviewing significant alerts
- Investigating detections
- Addressing failed protection
- Escalating suspected compromise

---

# 26. Antivirus Coverage

Security Operations must maintain reasonable awareness of antivirus coverage.

Systems unexpectedly lacking required protection must be investigated.

Coverage gaps must not be treated as normal merely because no malware has been reported.

---

# 27. Antivirus Updates

Antivirus signatures and software must receive available updates according to the managed protection process.

Persistent update failures require investigation.

---

# 28. Malware Detection

A malware detection requires evaluation.

The analyst must consider:

- Affected system
- Malware type
- Detection source
- Whether execution occurred
- Whether the malware was blocked
- User activity
- Network activity
- Credential exposure
- Potential spread
- Business impact

---

# 29. Malware Containment

A suspected compromised endpoint may require:

- Network isolation
- User notification
- Account protection
- Malware removal
- Reimaging
- Evidence preservation
- Additional system review

Actions must reflect the severity of the event.

---

# 30. Malware Removal

Removal of detected malware does not automatically establish that the incident is resolved.

The response must consider whether:

- Persistence remains.
- Credentials were exposed.
- Other systems were affected.
- Data was accessed.
- Additional investigation is required.

---

# 31. Ransomware

Suspected ransomware requires prompt escalation.

Response priorities include:

1. Human safety where relevant
2. Limiting spread
3. Protecting unaffected systems
4. Preserving useful evidence
5. Protecting backups
6. Determining scope
7. Supporting recovery
8. Evaluating information exposure

Ransomware response is further addressed by [[PBK-002 Malware & Ransomware Playbook]].

---

# 32. Phishing Reports

Reported phishing messages must be evaluated according to risk.

Evaluation may consider:

- Sender
- Message content
- Links
- Attachments
- Requested action
- Credential solicitation
- Spoofing indicators
- Other recipients

---

# 33. Credential Phishing

If a user may have disclosed credentials, Security Operations must promptly evaluate the need to:

- Disable or restrict the account
- Change credentials
- Review authentication activity
- Review related systems
- Preserve evidence
- Escalate the event

Response is further addressed by [[PBK-001 Phishing & Credential Compromise Playbook]].

---

# 34. Business Email Compromise

Suspected Business Email Compromise (BEC) must be escalated when the message involves:

- Payment instructions
- Vendor banking information
- Executive impersonation
- Payroll changes
- Sensitive information
- Unusual financial requests

Security Operations must coordinate with Finance or other affected business functions.

---

# 35. Authentication Monitoring

Security Operations should review authentication information appropriate to system capability and risk.

Events of interest may include:

- Repeated failed authentication
- Unexpected privileged login
- Dormant account activity
- Disabled account activity
- Unusual remote access
- Unexpected authentication patterns

---

# 36. Authentication Context

A failed login alone does not establish an attack.

Security Operations must consider:

- Frequency
- Account
- Source
- Timing
- Related events
- User activity
- System importance

Context determines whether escalation is warranted.

---

# 37. Privileged Activity

Significant privileged activity should be logged and reviewed where technically supported and appropriate.

Particular attention should be given to:

- Domain Administrator activity
- Security-control changes
- Firewall changes
- Authentication changes
- Significant server administration
- Backup administration
- Infinity production administration

---

# 38. Privileged Credentials

Ordinary user and privileged credentials must remain separate as required by [[POL-003 Access Control Policy]] and [[PROC-002 Privileged Access Procedure]].

Security Operations must investigate suspected misuse of privileged credentials.

---

# 39. Domain Administrator Activity

Standing Domain Administrator access is normally limited to:

- IT & Information Security Manager
- System Administrator

Unexpected Domain Administrator membership or activity requires investigation.

---

# 40. Emergency Access Activity

Use of emergency or break-glass access must be reviewed.

Security Operations must determine whether:

- Use was authorized.
- The emergency condition was legitimate.
- Activity was appropriate.
- Credentials require change.
- Follow-up is required.

Requirements are defined in [[PROC-005 Emergency Access Procedure]].

---

# 41. Dormant Accounts

Security Operations and Identity and Access Management (IAM) must coordinate on dormant accounts.

The established thresholds are:

- 30 days inactivity: investigate
- 60 days inactivity: disable unless justified

Unexpected activity from a dormant account requires investigation.

---

# 42. Terminated Accounts

Authentication activity involving an account associated with a terminated worker requires prompt investigation.

The event may indicate:

- Incomplete termination
- Credential compromise
- Incorrect account ownership
- Administrative error

---

# 43. Contractor Accounts

Contractor account activity must remain consistent with:

- Authorized purpose
- Approved systems
- Approved duration
- Approved access method

Unexpected contractor activity requires investigation.

---

# 44. Infinity Contractor Activity

The Infinity contractor does not have general contractor VPN access for privileged production or administrative work.

Privileged production administration is normally performed from the designated company-controlled contractor workspace at Scranton Headquarters.

Unexpected privileged remote Infinity contractor activity requires investigation.

---

# 45. Network Monitoring

Network-security operations must maintain reasonable awareness of:

- Firewall events
- Remote-access activity
- Unexpected services
- Significant network changes
- Unauthorized devices
- Connectivity anomalies

Monitoring must reflect available tools and actual business risk.

---

# 46. Firewall Monitoring

Firewall information should be reviewed when relevant to:

- Suspected attack
- Unauthorized access
- Unexpected exposure
- Malware
- Incident investigation
- Configuration verification

Routine review must be proportionate to available resources and risk.

---

# 47. Firewall Changes

Unexpected firewall configuration changes require investigation.

Authorized changes must be traceable to the change-management process.

---

# 48. Internet Exposure

Unexpected Internet-accessible services require prompt evaluation.

Security Operations must determine:

- What service is exposed
- Whether exposure is authorized
- Whether administration is exposed
- Whether the system is vulnerable
- Whether immediate restriction is required

---

# 49. Remote Access

VPN activity should be reviewed when security-relevant conditions indicate possible misuse.

Security Operations must consider:

- Account
- Source
- Timing
- Authentication
- Destination
- Privilege
- Related events

---

# 50. Network Discovery

Network discovery must be performed periodically to identify expected and unexpected network-connected devices.

Discovery supports:

- Asset awareness
- Vulnerability assessment
- Unauthorized-device detection
- Architecture validation

---

# 51. Network Discovery Frequency

Network and rogue-device discovery must be performed at least every six months.

Additional discovery may be performed following:

- Significant network change
- Security incident
- Unexpected connectivity
- Suspected unauthorized device

---

# 52. Unauthorized Network Devices

Unexpected network devices must be investigated.

The investigation must determine:

- Device identity
- Owner
- Purpose
- Authorization
- Network location
- Security significance

Unauthorized devices must be removed or otherwise appropriately addressed.

---

# 53. Wireless Discovery

Wireless discovery must verify the authorized wireless baseline.

The expected environment contains exactly:

- One ceiling-mounted wireless access point
- Scranton Headquarters lobby
- Internet-only guest access

Any additional wireless infrastructure requires investigation.

---

# 54. Rogue Wireless

Potential rogue wireless devices must be investigated to determine:

- Whether the device belongs to Dunder Mifflin
- Whether it is authorized
- Whether it provides corporate network access
- Whether it creates security exposure

Unauthorized wireless infrastructure must be addressed promptly.

---

# 55. Guest Wireless

The Scranton Headquarters guest wireless network must remain separated from corporate resources.

Security Operations must investigate evidence suggesting that guest wireless provides unauthorized access to internal company systems.

---

# 56. Vulnerability Information

Security Operations must receive or have access to relevant vulnerability information.

Vulnerability information can improve interpretation of:

- Security alerts
- Suspicious network activity
- Malware events
- Authentication events
- Incident scope

---

# 57. Vulnerability Management Coordination

Security Operations must coordinate with [[PRO-004 Vulnerability Management Program]].

Known vulnerabilities may increase the significance of observed security activity.

Security events may also reveal vulnerabilities requiring assessment and remediation.

---

# 58. Critical Vulnerabilities

Security Operations must be informed of Critical vulnerabilities when knowledge of the vulnerability is important to:

- Monitoring
- Detection
- Containment
- Incident response

An actively exploited vulnerability must not remain solely within the vulnerability-remediation process.

---

# 59. Penetration-Test Information

Relevant penetration-test findings may be used to improve operational monitoring.

Useful information may include:

- Attack paths
- Exposed services
- Authentication weaknesses
- Detection gaps
- Privilege-escalation paths

---

# 60. Security Event

A security event is an observable occurrence that may have security relevance.

Examples include:

- Malware alert
- Failed login pattern
- Unexpected administrative change
- Suspicious email
- Unauthorized device
- Firewall event
- Lost laptop
- Security-tool alert

A security event is not automatically a security incident.

---

# 61. Event Triage

Security events must be evaluated to determine whether further action is required.

Triage should consider:

- Source
- Asset
- User
- Time
- Severity
- Business importance
- Information sensitivity
- Related events
- Known vulnerabilities
- Potential impact

---

# 62. Event Validation

Where practical, Security Operations should determine whether the observed condition is:

- Expected activity
- Administrative activity
- Technical error
- False positive
- Security event requiring investigation
- Potential security incident

The conclusion must be supported by available evidence.

---

# 63. Event Prioritization

Events must be prioritized based on risk rather than alert volume alone.

Higher priority should be considered when events involve:

- Privileged accounts
- Critical systems
- Restricted information
- Internet-facing systems
- Active malware
- Credential compromise
- Significant business operations
- Multiple related systems

---

# 64. Event Escalation

Events meeting escalation criteria must be handled according to [[PROC-010 Security Event Escalation Procedure]].

Escalation must occur promptly when delay could materially increase:

- Exposure
- Business impact
- Evidence loss
- Recovery difficulty

---

# 65. Event to Incident Transition

A security event becomes an incident-response matter when available information indicates or reasonably suggests a security incident requiring coordinated response.

The transition must be documented.

Incident handling is governed by [[PLN-001 Incident Response Plan]].

---

# 66. Incident Response Activation

Security Operations may recommend activation of the Incident Response Team (IRT).

Activation depends on:

- Scope
- Severity
- Business impact
- Information exposure
- Technical complexity
- Need for cross-functional coordination

---

# 67. Incident Response Support

Security Operations supports incident response through:

- Event information
- Logs
- Timeline development
- Technical investigation
- Malware information
- Authentication information
- Network information
- Vulnerability information
- Evidence preservation

---

# 68. Retained DFIR Provider

Dunder Mifflin should maintain access to a retained Digital Forensics and Incident Response (DFIR) provider for incidents exceeding internal capability.

The retained provider is a proposed Critical Security Response Provider.

Until the capability is actually contracted and available, it must not receive current control-effectiveness credit.

---

# 69. DFIR Escalation

The retained DFIR provider may be engaged for incidents involving:

- Significant compromise
- Complex malware
- Ransomware
- Significant data exposure
- Forensic analysis beyond internal capability
- Material legal or regulatory concern
- Significant evidence-preservation requirements

---

# 70. Evidence Handling

Security Operations must preserve evidence according to [[PROC-011 Evidence Handling Procedure]].

Evidence may include:

- Logs
- Emails
- Files
- Malware samples
- Screenshots
- System information
- Authentication records
- Network information
- User reports

---

# 71. Evidence Integrity

Operational security evidence must accurately represent what occurred.

Personnel must not:

- Alter logs to conceal activity.
- Delete material security evidence without authorization.
- Fabricate alerts.
- Backdate investigations.
- Falsify review activity.
- Represent unreviewed events as reviewed.
- Conceal material monitoring failures.
- Represent Planned controls as operational.

---

# 72. Cryptographic Hashing

Where practical and useful for evidence integrity, collected digital evidence should receive a cryptographic hash.

SHA-256 may be used for this purpose.

Hashing supports evidence-integrity verification but does not by itself establish complete chain of custody.

---

# 73. Security Timeline

Significant security investigations should maintain a timeline.

The timeline may include:

- Initial event
- Detection
- User report
- Analyst review
- Escalation
- Containment
- Evidence collection
- Recovery
- Closure

---

# 74. User Reporting

Personnel must have a practical method to report suspected security events.

Reports must be taken seriously and evaluated according to risk.

Users should not be discouraged from reporting because a prior report proved harmless.

---

# 75. False Positives

False positives must be managed without creating complacency.

Recurring false positives should be evaluated to determine whether:

- Tool configuration can be improved.
- Documentation can reduce repeated investigation.
- The event still requires periodic review.

---

# 76. Alert Fatigue

Security Operations should avoid unnecessary alert volume that prevents meaningful review.

Monitoring should prioritize:

- Actionable events
- Higher-risk systems
- Significant authentication activity
- Malware
- Privileged activity
- Material configuration changes

---

# 77. Security Tool Health

Security Operations must maintain reasonable awareness of whether important security tools are functioning.

Examples include:

- Antivirus
- Vulnerability scanner
- Logging
- Firewall
- VPN
- Endpoint-management systems

A silent failed security tool can create false confidence.

---

# 78. Monitoring Failure

Material monitoring failures must be investigated.

Examples include:

- Missing logs
- Disabled antivirus
- Failed security updates
- Vulnerability scanner failure
- Authentication logging failure
- Firewall logging failure

The response must consider the duration and resulting visibility gap.

---

# 79. Configuration Change Monitoring

Security Operations should identify significant security-control changes where technically practical.

Examples include:

- Firewall rule change
- Logging disabled
- Antivirus disabled
- Privileged group change
- Authentication configuration change
- Security-service shutdown

Unexpected changes require investigation.

---

# 80. Change Management Coordination

Authorized changes must be traceable to [[POL-007 Change & Configuration Management Policy]].

Security Operations may compare observed changes with approved change records.

Unexplained discrepancies require investigation.

---

# 81. Cloud Security Events

Cloud-hosted systems remain within Security Operations responsibility where Dunder Mifflin controls the relevant service or system.

Security Operations should consider:

- Provider notifications
- Administrative access
- Authentication
- Service availability
- Security configuration
- Application events

---

# 82. Cloud Provider Incident

A cloud-provider event affecting Dunder Mifflin may require coordination among:

- Security Operations
- IT
- Provider support
- Business Continuity/Disaster Recovery (BC/DR)
- Incident Response
- Management

The response depends on whether the event affects confidentiality, integrity, availability, or multiple areas.

---

# 83. Third-Party Notifications

Security-relevant third-party notifications must be evaluated.

Examples include:

- Provider security incident
- Vulnerability notification
- Service compromise
- Unauthorized access
- Material outage
- Data exposure

Critical providers are subject to requirements established in [[POL-008 Third-Party Security Policy]].

---

# 84. Third-Party Incident Notification

Critical third parties are expected to notify Dunder Mifflin of material security incidents within 24 hours of discovery according to established third-party requirements.

Receipt of notification must trigger appropriate evaluation.

---

# 85. Physical Security Coordination

Security Operations must coordinate with physical-security personnel or facility management when events cross physical and information-security boundaries.

Examples include:

- Unauthorized access to an IT Restricted area
- Theft of equipment
- Lost access credential
- Tampering with network equipment
- Unauthorized contractor presence

---

# 86. Lost or Stolen Device

A lost or stolen company device requires evaluation of:

- Device type
- User
- Information stored
- Full-Disk Encryption (FDE)
- Authentication
- Mobile Device Management (MDM)
- Remote lock or wipe capability
- Credential exposure
- Physical circumstances

Response must be proportionate to risk.

---

# 87. Mobile Device Response

Where supported and appropriate, a lost company mobile device may be:

- Located
- Locked
- Wiped

Security Operations must coordinate with the responsible IT personnel.

---

# 88. Backup Security Monitoring

Security Operations must coordinate with backup and recovery personnel when security events may affect backup integrity.

Particular attention is required during:

- Ransomware
- Administrative compromise
- Data corruption
- Destructive malware

Backups must not be assumed safe merely because they exist.

---

# 89. Backup Administrative Access

Unexpected or suspicious backup-administration activity requires investigation.

Compromise of backup administration may increase the impact of:

- Ransomware
- Malicious insider activity
- Data destruction
- Recovery failure

---

# 90. Data Integrity Events

Suspected unauthorized data modification requires evaluation.

Potential indicators include:

- Unexpected database changes
- Application discrepancies
- File changes
- Inventory discrepancies
- Financial discrepancies
- Backup inconsistencies

Technical and business personnel may need to coordinate.

---

# 91. Manual Business Processes

Security Operations must recognize that outages may cause business processes to shift to manual procedures.

Security-relevant issues during manual operation may include:

- Lost records
- Duplicate transactions
- Unauthorized changes
- Incomplete attribution
- Reconciliation failures

Manual processing requirements are defined in [[PROC-013 Manual Processing Procedure]].

---

# 92. Security Operations During Outage

During significant outages, Security Operations must continue to support:

- Incident evaluation
- Evidence preservation
- Access control
- Communication
- Recovery security
- Monitoring where available

Reduced technical capability during an outage must not eliminate security responsibility.

---

# 93. Recovery Security

Systems returning to service after significant security disruption must be evaluated for appropriate security before normal operations resume.

Recovery should consider:

- Malware status
- Authentication
- Configuration
- Patching
- Logging
- Data integrity
- Administrative access

---

# 94. Security Operations Documentation

Security Operations must maintain documentation sufficient for qualified IT personnel to understand:

- Monitoring responsibilities
- Escalation paths
- Security-tool use
- Event-handling expectations
- After-hours contacts
- Evidence requirements

Documentation must not depend solely on one employee's knowledge.

---

# 95. Operational Security Records

Operational records may include:

- Security event records
- Malware records
- Alert investigations
- Network-discovery results
- Wireless-discovery results
- Escalation records
- Security-tool health records
- Significant log reviews
- Incident referrals

---

# 96. Event Record

A material security-event record should identify:

- Date and time
- Source
- Affected asset or user
- Event description
- Initial priority
- Analyst
- Investigation performed
- Evidence
- Conclusion
- Escalation
- Status

---

# 97. Event Closure

A security event may be closed when available evidence reasonably supports a conclusion such as:

- Expected activity
- False positive
- Administrative activity
- Technical problem
- Resolved security event
- Escalated security incident

Closure must be supported by the investigation performed.

---

# 98. Incomplete Investigation

An event must not be recorded as harmless merely because available information is incomplete.

Where uncertainty remains material, the event must be:

- Further investigated,
- Escalated, or
- Documented with the remaining uncertainty.

---

# 99. Security Operations Metrics

Security Operations metrics may include:

- Security events reviewed
- Events escalated
- Malware detections
- Phishing reports
- Credential-compromise events
- Unauthorized devices discovered
- Rogue wireless findings
- Security-tool failures
- After-hours escalations
- Events converted to incidents
- Significant monitoring gaps

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 100. Key Performance Indicators

Key Performance Indicators (KPIs) may include:

- Percentage of material security events reviewed
- Percentage of significant events escalated within required time
- Percentage of required network-discovery activities completed
- Percentage of required wireless-discovery activities completed
- Percentage of material security-tool failures investigated

KPIs measure operational execution.

---

# 101. Key Risk Indicators

Key Risk Indicators (KRIs) may include:

- Unresolved malware events
- Confirmed credential compromises
- Unauthorized network devices
- Rogue wireless devices
- Significant monitoring gaps
- Unexpected privileged activity
- Repeated security-tool failures
- Unresolved Critical security events

KRIs indicate security exposure.

---

# 102. Metric Interpretation

Security metrics must be interpreted carefully.

For example:

- More phishing reports may indicate increased attack activity.
- More phishing reports may also indicate improved employee reporting.
- Fewer malware detections may indicate reduced malware.
- Fewer malware detections may also indicate failed protection.

Metrics require context.

---

# 103. Operational Reporting

Operational reporting must provide enough detail to support:

- Investigation
- Escalation
- Remediation
- Evidence
- Technical action

Operational reporting should emphasize current work and exceptions.

---

# 104. Management Reporting

Management reporting should identify:

- Significant events
- Security Operations performance
- Unresolved issues
- Monitoring gaps
- Resource constraints
- Recurring weaknesses
- Required management action

---

# 105. Executive Reporting

Executive reporting should focus on:

- Material enterprise risk
- Significant incidents
- Meaningful security trends
- Major control weaknesses
- Required investment
- Decisions requiring executive action

Technical alert volume alone is not useful executive reporting.

---

# 106. Reporting Principle

Security Operations follows the enterprise reporting model:

**Operational → Execution, Evidence, Exceptions, Technical Detail**

**Management → Accountability, Performance, Action**

**Executive → Decisions and Enterprise Risk**

---

# 107. Operational Dashboard

Security Operations contributes information to [[RPT-008 Operational Security Report & Dashboard]].

The dashboard may include:

- Identity and access status
- Vulnerability status
- Endpoint security
- Email and phishing
- Backup and recovery
- Security events
- Infinity security
- Third-party security
- Findings
- Risk treatments
- Exceptions

---

# 108. Security Operations and Findings

A Security Operations weakness becomes a formal finding when evidence supports a conclusion that a required control, process, or security outcome is not adequately satisfied.

Examples include:

- Required monitoring repeatedly not performed
- Security events not escalated
- Malware alerts ignored
- Known monitoring failure not addressed
- Unauthorized device not investigated
- Security evidence falsified

---

# 109. Finding Management

Material Security Operations deficiencies must be tracked through [[REG-004 Finding & Corrective Action Register]].

A finding must identify:

- Condition
- Requirement
- Evidence
- Impact
- Owner
- Corrective action
- Due date
- Validation method

---

# 110. Corrective Action

Corrective action may include:

- Tool repair
- Configuration correction
- Procedure change
- Training
- Staffing adjustment
- Escalation improvement
- Documentation improvement
- Technical control improvement

Corrective action remains open until appropriately validated.

---

# 111. Security Operations Assurance

Security Operations must be periodically assessed to determine whether required controls operate as intended.

Assessment should evaluate:

- Event review
- Escalation
- Malware response
- Authentication monitoring
- Network discovery
- Wireless discovery
- Evidence handling
- Tool health
- Reporting

---

# 112. Assessment Methods

Assessment methods may include:

- Inspection
- Observation
- Interviews
- Sampling
- Technical Testing
- Reconciliation
- Independent Performance

The assessment method must match the control being evaluated.

---

# 113. Event Review Testing

An assessor may select security events and determine whether:

- The event was reviewed.
- Investigation was appropriate.
- Evidence supports the conclusion.
- Escalation occurred when required.
- Closure was reasonable.

---

# 114. Malware Response Testing

An assessor may select malware detections and determine whether:

- Detection was reviewed.
- Containment was appropriate.
- Credential exposure was considered.
- Additional affected systems were considered.
- Incident escalation occurred when warranted.

---

# 115. Network Discovery Testing

An assessor may review network-discovery evidence and determine whether:

- Required discovery occurred.
- Results were reviewed.
- Unexpected devices were investigated.
- Material findings were addressed.

---

# 116. Wireless Discovery Testing

An assessor may compare discovery results against the authorized wireless baseline.

The expected result is one authorized wireless access point at the Scranton Headquarters lobby.

Additional wireless devices require documented investigation.

---

# 117. Privileged Activity Testing

An assessor may sample privileged activity and determine whether:

- The account was authorized.
- The activity was consistent with responsibilities.
- Significant changes were traceable.
- Unexpected activity was investigated.

---

# 118. Independent Performance

An assessor may perform selected Security Operations activities independently.

For example, the assessor may:

1. Select a period of authentication activity.
2. Apply the documented review criteria.
3. Identify events that should receive investigation.
4. Compare the result with actual Security Operations records.
5. Determine whether material events were appropriately handled.

Independent Performance provides evidence beyond inspection of completed operational records.

---

# 119. Assessment Exceptions

Exceptions identified during assessment must be investigated.

Potential causes include:

- Tool failure
- Missing log
- Process failure
- Documentation error
- Analyst error
- Approved limitation
- Control deficiency

The cause determines corrective action.

---

# 120. Control Effectiveness

Security Operations evidence may support conclusions that a control is:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

Effectiveness must be based on evidence rather than design intent.

---

# 121. Current and Proposed Controls

Security Operations must distinguish among:

- Current controls
- Partially implemented controls
- Planned controls
- Implemented controls awaiting validation
- Validated controls

A planned monitoring capability does not provide current security coverage.

---

# 122. No Premature Risk Credit

Current residual risk must not be reduced merely because:

- A monitoring tool is planned.
- A SIEM is being considered.
- EDR is being considered.
- An after-hours process is proposed.
- A DFIR contract is planned.
- A procedure has been approved.

Risk reduction requires implementation and appropriate validation.

---

# 123. Risk Reassessment

Security Operations evidence may require enterprise risk reassessment when it reveals:

- New attack activity
- Control failure
- Unexpected exposure
- Repeated security events
- Successful control operation
- Material monitoring gap
- Significant incident

Historical risk results must remain preserved.

---

# 124. Risk Relationships

This program provides significant treatment support for:

- R001 Phishing / Credential Compromise
- R002 Business Email Compromise
- R003 Ransomware
- R004 Malware
- R005 Password / Authentication Weakness
- R006 Infinity Application Compromise
- R007 Internet Infrastructure Compromise
- R008 Denial of Service
- R009 Sensitive Information Theft / Extortion
- R010 Unauthorized / Excessive Access
- R011 Delayed Termination
- R012 Malicious Insider
- R013 Administrative / Configuration Error
- R014 Lost Device
- R015 Shared Warehouse Account
- R016 Cloud Outage
- R017 Internet Service Provider Outage
- R018 Third-Party Technology Failure / Compromise
- R019 Infinity Contractor Dependency / Compromise
- R024 Physical Access
- R027 Backup / Recovery Failure
- R028 Data Corruption

Risk treatment is maintained in [[RTP-001 Enterprise Risk Treatment Plan]].

---

# 125. Phishing and Credential Risk

Security Operations supports R001 through:

- User reporting
- Email-event investigation
- Credential-compromise response
- Authentication review
- Escalation
- Incident response

Improved email filtering, anti-phishing controls, smart-card authentication, and monthly phishing simulations remain separate treatment components.

---

# 126. Business Email Compromise Risk

Security Operations supports R002 through:

- Suspicious-message investigation
- Authentication review
- Financial-function coordination
- Escalation of impersonation or payment fraud indicators

Financial approval and verification controls remain necessary outside Security Operations.

---

# 127. Ransomware and Malware Risk

Security Operations supports R003 and R004 through:

- Managed antivirus
- Alert review
- Malware investigation
- Isolation
- Escalation
- Backup coordination
- Incident response

No EDR capability is assumed as an existing control.

---

# 128. Authentication Risk

Security Operations supports R005 through:

- Authentication-event review
- Privileged-activity review
- Dormant-account investigation
- Contractor-account monitoring
- Emergency-access review
- Credential-compromise response

Identity governance remains managed through the Identity and Access Management (IAM) program.

---

# 129. Infinity Risk

Security Operations supports R006 and R019 through:

- Relevant log review
- Authentication monitoring
- Privileged-activity awareness
- Vulnerability information
- Contractor-access monitoring
- Incident escalation

Security Operations does not replace annual Infinity security assessment or penetration testing.

---

# 130. Internet Infrastructure Risk

Security Operations supports R007 and R008 through:

- Firewall-event review
- Unexpected exposure investigation
- Network discovery
- Provider coordination
- Security-event escalation

---

# 131. Sensitive Information Risk

Security Operations supports R009 through:

- Suspicious access investigation
- Malware response
- Authentication review
- Incident escalation
- Evidence collection

Information classification and access controls remain separate preventive controls.

---

# 132. Insider Risk

Security Operations supports R012 through proportionate review of security-relevant activity.

Monitoring must focus on legitimate security purposes.

The program does not authorize indiscriminate employee surveillance.

---

# 133. Lost Device Risk

Security Operations supports R014 through:

- Prompt reporting
- Device assessment
- Credential response
- Mobile Device Management coordination
- Remote lock or wipe where supported
- Incident evaluation

---

# 134. Shared Warehouse Account Risk

Security Operations supports R015 by investigating security-relevant activity involving shared Windows warehouse workstations.

Significant Warehouse Management System (WMS) transactions must maintain individual accountability even when the Windows workstation uses an operationally justified shared account.

---

# 135. Cloud and Third-Party Risk

Security Operations supports R016 and R018 through:

- Provider notifications
- Security-event coordination
- Availability awareness
- Incident escalation
- Third-party communication

Security Operations does not replace third-party risk management or Business Continuity/Disaster Recovery (BC/DR).

---

# 136. Backup and Data Integrity Risk

Security Operations supports R027 and R028 through:

- Investigation of suspicious backup activity
- Malware and ransomware coordination
- Data-integrity event evaluation
- Incident escalation
- Recovery-security support

Backup effectiveness must be validated through recovery testing.

---

# 137. Privacy and Proportionality

Security monitoring must be proportionate to legitimate security and business needs.

Access to monitoring information must be limited appropriately.

Security Operations must not use its capabilities for unrelated personal surveillance.

---

# 138. Separation of Duties

Where practical, personnel should not be the sole reviewer of their own high-risk privileged activity.

Staffing limitations may require practical compensating review by another qualified individual or manager.

---

# 139. Access to Security Tools

Security-tool access must follow least privilege.

Administrative access must be limited to personnel who require it.

Privileged tool access must use separate administrative credentials where applicable.

---

# 140. Security Tool Changes

Material changes to security tools must comply with [[POL-007 Change & Configuration Management Policy]].

Changes should consider:

- Testing
- Approval
- Rollback
- Verification
- Documentation

---

# 141. Security Operations During Personnel Change

Security Operations responsibilities must remain covered during:

- Vacation
- Illness
- Departure
- Role transfer
- Extended absence

Critical operational knowledge must not depend exclusively on one individual.

---

# 142. Cross-Training

IT personnel must receive sufficient cross-training to support essential Security Operations when primary personnel are unavailable.

Cross-training must reflect role and privilege requirements.

---

# 143. After-Hours Escalation

Events requiring immediate after-hours action may include:

- Suspected ransomware
- Active compromise
- Significant credential compromise
- Critical system attack
- Material data exposure
- Major security-control failure
- Significant third-party incident

The on-call contact must determine whether broader incident-response activation is required.

---

# 144. Nonurgent After-Hours Events

Not every after-hours alert requires immediate human action.

Lower-risk events may be reviewed during the next appropriate operating period when delay does not materially increase risk.

This distinction prevents an informal on-call process from becoming an unsupported 24x7 monitoring claim.

---

# 145. Security Operations Documentation Review

Operational documentation must be reviewed when material changes occur to:

- Security tools
- Network architecture
- Authentication
- Cloud services
- Infinity
- Incident-response processes
- Staffing
- Escalation contacts

---

# 146. Continuous Improvement

Security Operations must improve based on:

- Incidents
- Findings
- Vulnerability information
- Penetration testing
- Security assessments
- Operational failures
- Metrics
- Management review
- Changes in business risk

---

# 147. Lessons Learned

Significant incidents and operational failures should identify lessons that can improve:

- Detection
- Escalation
- Documentation
- Tool configuration
- Training
- Architecture
- Procedures
- Recovery

Lessons must lead to corrective action when warranted.

---

# 148. Program Assurance

Security Operations is not considered effective merely because:

- Tools exist.
- Logs exist.
- Antivirus is installed.
- Procedures are written.
- Personnel have security responsibilities.

Effectiveness requires evidence that appropriate security events are identified, evaluated, escalated, and acted upon.

---

# 149. Traceability

This program supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Security Operations records must support traceability from operational activity through investigation, escalation, incident response, corrective action, and risk reassessment.

---

# 150. Related Artifacts

- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-006 Security Awareness & Training Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-011 Physical & Environmental Security Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[PRO-003 Identity and Access Management Program]]
- [[PRO-004 Vulnerability Management Program]]
- [[STD-002 Network Security Standard]]
- [[STD-003 Endpoint Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[STD-007 Penetration Testing Standard]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[STD-009 Infinity Security Standard]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-006 Vulnerability Assessment Procedure]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]
- [[PROC-008 Security Monitoring Procedure]]
- [[PROC-009 Malware Response Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-013 Manual Processing Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PBK-001 Phishing & Credential Compromise Playbook]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[RPT-008 Operational Security Report & Dashboard]]

---

# 151. Review

This program must be reviewed:

- At least annually
- Following material Security Operations changes
- Following significant security incidents
- Following material technology changes
- Following significant monitoring failures
- Following material assurance findings

The IT & Information Security Manager coordinates review.

Material revisions require CIO approval.

---

# 152. Revision History

| Version | Date     | Description                         | Approval |
| ------- | -------- | ----------------------------------- | -------- |
| 1.0     | May 2013 | Initial Security Operations Program | CIO      |