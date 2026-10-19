# PROC-008 Security Monitoring Procedure

## Document Control

| Field | Value |
|---|---|
| Document ID | PROC-008 |
| Title | Security Monitoring Procedure |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Security Monitoring or Technology Change |

---

# 1. Purpose

This procedure defines how Dunder Mifflin, Inc. performs routine security monitoring, reviews security-relevant information, investigates suspicious conditions, documents conclusions, and escalates events requiring additional action.

The procedure implements operational monitoring requirements established by [[PRO-005 Security Operations Program]].

---

# 2. Scope

This procedure applies to security monitoring involving:

- Endpoints
- Servers
- Active Directory
- Network infrastructure
- Firewalls and routers
- Virtual Private Network (VPN)
- Cloud-hosted systems
- Business applications
- Infinity
- Company laptops
- Company mobile devices
- Warehouse technology
- Managed antivirus
- Security tools
- Authentication activity
- Privileged activity
- Network and wireless discovery
- Third-party security notifications

---

# 3. Authority

This procedure supports requirements established by:

- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-006 Security Awareness & Training Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[PRO-005 Security Operations Program]]

---

# 4. Objectives

Security monitoring must:

1. Maintain reasonable awareness of security-relevant conditions.
2. Identify events requiring investigation.
3. Detect significant authentication or privileged-access anomalies.
4. Review malware and security-tool alerts.
5. Identify unauthorized network or wireless devices.
6. Identify material security-tool failures.
7. Support timely event escalation.
8. Preserve useful evidence.
9. Support incident response.
10. Produce reliable operational records.

---

# 5. Monitoring Principle

Security monitoring must be proportionate to business risk, system importance, available technology, and staffing.

Security monitoring does not require continuous human observation of every system, user, log, or event.

Monitoring must focus on information capable of supporting meaningful security decisions.

---

# 6. Monitoring Model

Dunder Mifflin does not maintain a dedicated Security Operations Center (SOC).

Monitoring responsibilities are distributed among the Information Technology (IT) team.

The Information Security Analyst normally coordinates routine security-monitoring activity.

---

# 7. No 24x7 Human Monitoring

Continuous human monitoring 24 hours per day, seven days per week is not an existing company capability.

Security records must not state or imply that continuous human review occurs when it does not.

Automated systems may continue:

- Logging
- Detecting
- Alerting
- Blocking

outside normal business hours.

---

# 8. No SIEM Baseline

A Security Information and Event Management (SIEM) platform is not assumed as an existing control.

Monitoring may require review of information directly from:

- Systems
- Applications
- Firewalls
- Security tools
- Cloud services

Centralized logging may be used where available but must not be assumed where it has not been implemented.

---

# 9. No EDR Baseline

Endpoint Detection and Response (EDR) is not assumed as an existing control.

The established endpoint malware-defense baseline uses centrally managed commercial antivirus.

Monitoring activities must reflect actual available capabilities.

---

# 10. Monitoring Responsibilities

The Information Security Analyst normally:

- Reviews security-relevant alerts and information.
- Investigates suspicious activity.
- Documents material events.
- Coordinates with technical administrators.
- Escalates significant events.
- Supports incident response.

---

# 11. Supporting Roles

The following personnel support monitoring within their areas of responsibility:

- System Administrator
- Network/Security Administrator
- IT Support personnel
- IT & Information Security Manager

Business personnel also support monitoring by reporting suspicious activity.

---

# 12. Monitoring Sources

Monitoring may use information from:

- Managed antivirus
- Windows event logs
- Active Directory
- Firewall logs
- VPN records
- Server logs
- Application logs
- Infinity logs
- Cloud-service information
- Vulnerability assessments
- Penetration testing
- Network discovery
- Wireless discovery
- User reports
- Administrator observations
- Third-party notifications
- Physical-security reports

---

# 13. Monitoring Priority

Monitoring effort must prioritize security information associated with:

- Critical business systems
- Privileged accounts
- Restricted information
- Confidential information
- Internet-facing systems
- Authentication
- Malware
- Significant administrative changes
- Known significant vulnerabilities
- Security incidents

---

# 14. Daily Monitoring Activities

During normal operating periods, Security Operations should review available significant security information appropriate to current risk.

Routine activity may include:

- Significant antivirus alerts
- Reported phishing
- Authentication anomalies
- Significant privileged activity
- Security-tool failures
- Administrator-reported concerns
- Third-party security notifications
- Open security events requiring follow-up

The exact volume and source of information may vary.

---

# 15. Event Review Order

When multiple events require review, priority should generally be given to:

1. Human safety implications
2. Active compromise
3. Ransomware or destructive malware
4. Privileged-account compromise
5. Critical-system compromise
6. Restricted-information exposure
7. Significant credential compromise
8. Internet-facing attacks
9. Other material security events
10. Routine lower-risk events

---

# 16. Alert Review

An alert must not automatically be treated as either:

- A confirmed incident, or
- A harmless false positive.

The analyst must evaluate available context.

---

# 17. Initial Alert Review

Initial review should determine:

- What generated the alert
- When it occurred
- What asset is involved
- What user or account is involved
- What activity occurred
- Whether the activity is expected
- Whether related alerts exist
- Whether immediate action is required

---

# 18. Security Event Record

A material security event should be documented with:

- Date and time
- Event source
- Affected asset
- Affected user or account
- Event description
- Initial priority
- Analyst
- Investigation performed
- Evidence
- Conclusion
- Escalation
- Status

---

# 19. Event Classification

After initial review, an event may be classified as:

- Expected activity
- Administrative activity
- Technical issue
- False positive
- Security event requiring further investigation
- Potential security incident

Classification must reflect available evidence.

---

# 20. Event Prioritization

Event priority must consider:

- Asset criticality
- Information classification
- Account privilege
- Internet exposure
- Known vulnerabilities
- Potential business impact
- Number of affected systems
- Evidence of exploitation
- Related events

---

# 21. Critical Event

A Critical event is one that may indicate immediate material harm or compromise requiring urgent coordinated action.

Examples may include:

- Active ransomware
- Widespread destructive malware
- Confirmed privileged-account compromise
- Significant Restricted information exposure
- Active compromise of a Critical system

Critical events require immediate escalation.

---

# 22. High-Priority Event

A High-priority event may involve serious security exposure requiring prompt investigation.

Examples may include:

- Significant malware
- Credible credential compromise
- Unexpected privileged activity
- Significant Internet-facing attack
- Material unauthorized access

---

# 23. Moderate-Priority Event

A Moderate-priority event warrants investigation but does not currently indicate immediate material enterprise impact.

The event must remain visible until appropriately resolved or escalated.

---

# 24. Low-Priority Event

A Low-priority event may be handled through routine monitoring when available evidence indicates limited security impact.

Low priority does not mean the event may be ignored.

---

# 25. Authentication Monitoring

Security Operations should review authentication activity where risk, system capability, or another security event warrants review.

Events of interest may include:

- Repeated failed logins
- Unexpected successful login
- Dormant account activity
- Disabled account activity
- Unexpected privileged login
- Unusual VPN activity
- Authentication from unexpected systems

---

# 26. Failed Authentication

Repeated failed authentication must be evaluated in context.

Potential explanations include:

- User error
- Forgotten password
- Stale stored credentials
- Application configuration
- Password guessing
- Compromised system
- Malicious activity

Failure count alone does not establish intent.

---

# 27. Successful Authentication After Failures

A successful authentication following unusual repeated failures may warrant additional investigation.

The analyst should consider:

- Account
- Source
- Timing
- Privilege
- Related activity
- User confirmation where appropriate

---

# 28. Dormant Account Activity

Accounts inactive for 30 days require investigation under established Identity and Access Management (IAM) requirements.

Accounts inactive for 60 days must be disabled unless justified.

Unexpected authentication involving a dormant account requires security review.

---

# 29. Disabled Account Activity

Attempted or apparent successful activity involving a disabled account must be investigated.

The analyst must determine whether the condition reflects:

- Logging interpretation
- Another linked account
- Administrative error
- Incomplete disablement
- Security compromise

---

# 30. Terminated Worker Account Activity

Authentication associated with a terminated worker requires prompt investigation.

The analyst must coordinate with:

- Human Resources
- System Administrator
- IT & Information Security Manager

where appropriate.

---

# 31. Privileged Account Monitoring

Privileged activity requires heightened attention.

Monitoring should consider:

- Domain Administrator accounts
- Server administrative accounts
- Network administrative accounts
- Backup administration
- Security-tool administration
- Application administration
- Infinity production administration

---

# 32. Unexpected Privileged Activity

Unexpected privileged activity requires investigation.

The analyst should determine:

- Account owner
- System
- Activity
- Business purpose
- Related change record
- Authorization
- Potential impact

---

# 33. Domain Administrator Monitoring

Standing Domain Administrator access is normally limited to:

- IT & Information Security Manager
- System Administrator

Unexpected Domain Administrator membership or activity must be investigated.

---

# 34. Privileged Group Change

Changes to significant privileged groups should be traceable to authorized access-management activity.

Unexpected additions or removals require investigation.

---

# 35. Separate Privileged Credentials

Privileged activity must use separate administrative credentials where required.

Evidence that an ordinary user account is being used for inappropriate privileged administration must be investigated.

---

# 36. Emergency Access Monitoring

Use of emergency or break-glass access requires review.

The analyst must verify:

- Emergency condition
- Authorization
- User
- Time
- Activity
- Credential disposition
- Required follow-up

Requirements are established by [[PROC-005 Emergency Access Procedure]].

---

# 37. Contractor Account Monitoring

Contractor activity must be consistent with approved:

- Sponsor
- Purpose
- Systems
- Privileges
- Access method
- Authorization period

Unexpected activity requires investigation.

---

# 38. Expired Contractor Access

Activity associated with expired contractor authorization requires prompt investigation.

The analyst must determine whether:

- Access was not disabled.
- Authorization was renewed but records are incomplete.
- Another administrative error occurred.
- Unauthorized access occurred.

---

# 39. Infinity Contractor Monitoring

The Infinity contractor does not have general VPN access for privileged production or administrative work.

Privileged production administration normally occurs from the designated company-controlled contractor workspace at Scranton Headquarters.

Unexpected privileged remote contractor activity requires investigation.

---

# 40. VPN Monitoring

VPN records should be reviewed when events indicate possible:

- Credential compromise
- Unauthorized remote access
- Unexpected source
- Unusual timing
- Excessive access
- Contractor-access violation

VPN activity must be interpreted in context.

---

# 41. Endpoint Monitoring

Endpoint monitoring relies primarily on available:

- Managed antivirus
- Windows logs
- Endpoint-management information
- User reports
- Administrator observations

No EDR capability is assumed.

---

# 42. Antivirus Alerts

Significant antivirus alerts must be reviewed.

The analyst must determine:

- What was detected
- Whether execution occurred
- Whether the threat was blocked
- Whether removal succeeded
- Whether additional systems may be affected
- Whether credentials may be exposed
- Whether escalation is required

---

# 43. Repeated Malware Detection

Repeated malware detection on the same system requires additional investigation.

Repeated detection may indicate:

- Failed removal
- Persistence
- Reinfection
- User behavior
- Vulnerable software
- Compromised credentials

---

# 44. Antivirus Failure

Security Operations must investigate material antivirus failures including:

- Protection disabled
- Update failure
- Agent failure
- Unexpected uninstall
- Significant coverage gap

A system lacking expected protection may require temporary restriction until corrected.

---

# 45. Malware Escalation

Suspected malware requiring dedicated response must be handled according to [[PROC-009 Malware Response Procedure]].

Ransomware or widespread malware requires prompt escalation.

---

# 46. Phishing Monitoring

Security Operations must review reported suspicious messages.

Review should consider:

- Sender
- Claimed identity
- Links
- Attachments
- Credential requests
- Financial requests
- Other recipients
- Known related activity

---

# 47. Phishing Investigation

The analyst should determine whether:

- The message is malicious.
- A user clicked a link.
- An attachment was opened.
- Credentials were entered.
- Malware may have executed.
- Other employees received the message.
- Additional response is required.

---

# 48. Credential Exposure

If credentials may have been disclosed, Security Operations must promptly coordinate appropriate account protection.

Actions may include:

- Password change
- Account disablement
- Authentication review
- Privileged-access review
- Related system review
- Incident escalation

---

# 49. Business Email Compromise Monitoring

Messages involving financial or identity-sensitive requests require heightened attention.

Examples include:

- Vendor bank-account change
- Payroll change
- Executive payment request
- Unusual wire or payment request
- Request for sensitive employee information

Security Operations must coordinate with the relevant business function.

---

# 50. Network Monitoring

Network monitoring must focus on security-relevant conditions available through:

- Firewalls
- Routers
- VPN
- Network administration
- Network discovery
- Security investigations

No capability should be claimed beyond what is actually available.

---

# 51. Firewall Events

Firewall information should be reviewed when relevant to:

- Repeated inbound connection attempts
- Unexpected outbound activity
- Suspected malware
- Unauthorized access
- Incident investigation
- Unexpected exposure

High event volume alone does not establish compromise.

---

# 52. Unexpected Internet Exposure

Security Operations must investigate unexpected Internet-accessible services.

The analyst must determine:

- Asset
- Service
- Authorization
- Business purpose
- Administrative exposure
- Vulnerability
- Required containment

---

# 53. Administrative Interface Exposure

Discovery of an administrative interface directly exposed to the Internet requires prompt investigation.

Unnecessary external administrative exposure must be restricted.

---

# 54. Network Discovery

Network discovery must be performed at least every six months.

Discovery should identify:

- Expected network devices
- Unexpected devices
- Address changes
- Unauthorized systems
- Potential rogue infrastructure

---

# 55. Network Discovery Preparation

Before discovery, the responsible personnel should identify:

- Expected network ranges
- Known infrastructure
- Approved devices
- Authorized exceptions

[[REG-001 Enterprise Asset Register]] provides a primary reference.

---

# 56. Network Discovery Reconciliation

Discovery results must be compared with expected assets.

The analyst must identify:

- Expected devices found
- Expected devices not found
- Unexpected devices
- Duplicate or incorrect records
- Significant discrepancies

---

# 57. Unexpected Device Investigation

An unexpected network device must be investigated.

The investigation should determine:

- Device type
- Owner
- Location
- Purpose
- Authorization
- Security exposure

---

# 58. Unauthorized Device

An unauthorized network device must be:

- Removed,
- Disconnected,
- Restricted, or
- Otherwise appropriately addressed.

The event must be escalated when malicious activity or material exposure is suspected.

---

# 59. Wireless Discovery

Wireless discovery must be performed at least every six months as part of network and rogue-device discovery.

The expected wireless baseline is:

- One authorized access point
- Ceiling mounted
- Scranton Headquarters lobby
- Internet-only guest wireless

---

# 60. Wireless Baseline Comparison

Discovery results must be compared with the expected authorized wireless environment.

Any additional wireless infrastructure requires investigation.

---

# 61. Rogue Wireless Investigation

A potential rogue wireless device must be evaluated to determine:

- Device ownership
- Authorization
- Physical location
- Network connectivity
- Whether corporate resources are reachable
- Security impact

---

# 62. Guest Wireless Monitoring

The Scranton Headquarters guest wireless network must remain separated from corporate resources.

Evidence suggesting internal corporate connectivity from guest wireless requires prompt investigation.

---

# 63. Security Tool Health

Security Operations must maintain reasonable awareness of whether significant security tools are operating.

Tools may include:

- Managed antivirus
- Vulnerability scanner
- Firewall logging
- VPN logging
- Endpoint-management systems
- Server logging

---

# 64. Tool Health Review

Material tool-health conditions requiring review include:

- Service failure
- Update failure
- Missing data
- Disabled protection
- Authentication failure
- Corrupt output
- Unexpected configuration change

---

# 65. Monitoring Blind Spot

A material monitoring failure creates a visibility gap.

The analyst must determine:

- What capability failed
- When failure began
- What systems were affected
- What security information may be missing
- Whether alternative evidence exists
- Whether risk requires escalation

---

# 66. Tool Restoration

A failed monitoring capability must be restored promptly according to risk.

Restoration must be verified.

The analyst must not assume successful restoration solely because corrective work was attempted.

---

# 67. Change Monitoring

Security Operations should review unexpected changes to significant security controls where technically practical.

Examples include:

- Firewall rules
- Antivirus configuration
- Logging configuration
- Privileged groups
- Authentication settings
- Security services

---

# 68. Change Record Comparison

Observed material changes should be compared with authorized change records where appropriate.

An authorized change should be traceable to [[POL-007 Change & Configuration Management Policy]].

Unexplained discrepancies require investigation.

---

# 69. Server Monitoring

Server monitoring should consider available information regarding:

- Authentication
- Administrative activity
- Malware
- Service failure
- Security configuration
- Significant errors

Monitoring must reflect server criticality.

---

# 70. Active Directory Monitoring

Active Directory monitoring should prioritize:

- Privileged group changes
- Significant authentication anomalies
- Account creation
- Account disablement
- Administrative changes
- Unexpected Domain Administrator activity

---

# 71. Application Monitoring

Application monitoring should focus on available security-relevant information such as:

- Authentication failures
- Administrative actions
- Unexpected errors
- Access anomalies
- Significant application events

The monitoring approach must reflect application capability.

---

# 72. Infinity Monitoring

Infinity monitoring should consider available:

- Authentication events
- Administrative activity
- Application errors
- Security-relevant application events
- Server events
- Contractor activity

Infinity monitoring does not replace annual application penetration testing or security assessment.

---

# 73. Database Monitoring

Database activity should be reviewed when:

- An application event suggests unauthorized access.
- Privileged database activity is unexpected.
- Data-integrity concerns arise.
- Incident investigation requires it.

Routine monitoring must be proportionate to available capability and risk.

---

# 74. Cloud Monitoring

Security Operations should review relevant information from company-controlled cloud-hosted systems.

Monitoring may include:

- Authentication
- Administrative activity
- Service status
- Security events
- Provider notifications

---

# 75. Cloud Provider Notification

Security-relevant provider notifications must be evaluated.

The analyst must determine:

- Service affected
- Security impact
- Business impact
- Required technical action
- Required incident escalation
- Required continuity action

---

# 76. Third-Party Security Notification

A security notification from a third party must be documented and evaluated when it may affect Dunder Mifflin.

The analyst should determine:

- Provider
- Service
- Event
- Discovery time
- Company systems or information affected
- Required response

---

# 77. Critical Provider Notification

Critical providers are expected to report material security incidents within 24 hours of discovery under established third-party requirements.

Failure to provide required notification may itself require third-party risk review.

---

# 78. Vulnerability Context

Known vulnerability information should be considered during security-event investigation.

An event affecting a system with a known significant vulnerability may warrant increased priority.

---

# 79. Penetration-Test Context

Relevant penetration-test findings may improve monitoring by identifying:

- Known attack paths
- Weak authentication
- Exposed services
- Privilege-escalation paths
- Detection weaknesses

---

# 80. Physical Security Information

Physical-security events may require information-security review when they involve:

- IT Restricted areas
- Servers
- Network equipment
- Company devices
- Access credentials
- Contractors with system access

---

# 81. Lost Device Monitoring

A reported lost or stolen device must be evaluated for:

- Device identity
- Assigned user
- Full-Disk Encryption (FDE)
- Information sensitivity
- Authentication
- Mobile Device Management (MDM)
- Credential exposure
- Remote lock or wipe capability

---

# 82. Backup Security Events

Suspicious activity involving backup systems or backup administration requires heightened attention.

The analyst must consider whether the event could affect:

- Backup confidentiality
- Backup integrity
- Backup availability
- Recovery capability

---

# 83. Data Integrity Monitoring

Reports of unexplained data changes must be investigated when they may indicate unauthorized activity.

Relevant evidence may include:

- Application records
- Database records
- File information
- User reports
- Administrative activity
- Backup information

---

# 84. User Reports

User-reported security concerns must be reviewed.

The analyst must not dismiss a report solely because the user cannot provide technical details.

User observations may provide the first evidence of compromise.

---

# 85. Administrator Reports

Administrators must report unexpected security-relevant conditions.

Examples include:

- Unknown account
- Unexpected service
- Unauthorized software
- Unexplained configuration
- Suspicious privileged activity
- Unusual network behavior

---

# 86. Correlation

Where practical, the analyst should compare information from multiple sources.

For example:

**Phishing Report → Authentication Activity → Endpoint Alert → Firewall Information**

Correlation can provide stronger evidence than an isolated event.

---

# 87. Manual Correlation

Because a SIEM is not assumed, event correlation may require manual review.

The analyst must use available information appropriate to the event.

---

# 88. Investigation Scope

Investigation should expand when evidence suggests broader compromise.

Potential expansion may include:

- Additional accounts
- Additional endpoints
- Related servers
- Network activity
- Email recipients
- Application activity
- Cloud activity

---

# 89. Investigation Restraint

Investigation must remain proportionate.

Personnel must not unnecessarily access:

- Employee personal information
- Unrelated business information
- Sensitive records unrelated to the event

Monitoring authority is limited to legitimate security purposes.

---

# 90. Privacy

Security monitoring must respect reasonable privacy expectations and company requirements.

The procedure does not authorize indiscriminate surveillance.

Security information must be accessed only for legitimate business and security purposes.

---

# 91. Immediate Containment

Security Operations may coordinate immediate containment when delay could materially increase harm.

Containment may include:

- Disable account
- Isolate endpoint
- Restrict network access
- Block malicious communication
- Disable vulnerable service
- Restrict privileged access

Containment must be documented.

---

# 92. Escalation Decision

The analyst must escalate when evidence indicates:

- Actual or suspected compromise
- Material unauthorized access
- Significant malware
- Credential compromise
- Sensitive-information exposure
- Significant privileged misuse
- Material security-control failure
- Significant business impact

---

# 93. Security Event Escalation

Escalation must follow [[PROC-010 Security Event Escalation Procedure]].

The escalation record must identify:

- Event
- Priority
- Reason
- Evidence
- Person notified
- Time
- Required action

---

# 94. Event to Incident

A security event becomes an incident-response matter when available evidence indicates or reasonably suggests a security incident requiring coordinated response.

The transition must be documented.

---

# 95. Incident Response

Incident handling is governed by:

- [[POL-009 Incident Response Policy]]
- [[PLN-001 Incident Response Plan]]
- Applicable incident playbooks

Security Monitoring supports, but does not replace, the Incident Response Team (IRT).

---

# 96. After-Hours Monitoring

Security tools may continue collecting and generating security information outside normal business hours.

Dunder Mifflin does not currently maintain a formal after-hours human monitoring or on-call security capability.

A simple after-hours security contact and on-call process is proposed for significant events requiring action before the next business period.

Until that process is implemented and validated, it must not be represented as an existing monitoring capability or receive current control-effectiveness credit.

---

# 97. Proposed After-Hours Contact

The proposed after-hours process should identify:

- Primary contact
- Alternate contact
- Contact method
- Escalation criteria
- Incident-response activation method

Implementation of the process must be documented before it is treated as an operational control.

---

# 98. Immediate After-Hours Events

Once the proposed after-hours process is implemented, events that may justify immediate after-hours action include:

- Ransomware
- Active compromise
- Significant credential compromise
- Critical-system attack
- Material data exposure
- Major security-control failure
- Significant third-party incident

---

# 99. Nonurgent After-Hours Events

Once the proposed after-hours process is implemented, lower-risk events may wait until the next appropriate operating period when delay does not materially increase risk.

This decision should reflect:

- Severity
- Asset criticality
- Information sensitivity
- Potential for spread
- Potential evidence loss

Until the proposed process is implemented, events generated outside normal business hours may not receive human review until the next operating period unless personnel become aware of the event through another available reporting or escalation path.

---

# 100. After-Hours Documentation

When after-hours security activity occurs, it must be documented consistently with normal security-event handling.

The record should identify:

- Detection or notification time
- Person contacted
- Response time
- Action taken
- Escalation
- Follow-up

Documentation of individual after-hours events does not by itself establish that a formal on-call monitoring capability has been implemented.

---

# 101. Evidence Collection

Monitoring investigations must preserve evidence appropriate to the event.

Evidence may include:

- Logs
- Alerts
- Emails
- Files
- Screenshots
- Authentication records
- Network information
- User reports
- System information

---

# 102. Evidence Handling

Evidence must be handled according to [[PROC-011 Evidence Handling Procedure]].

Evidence collection must avoid unnecessary modification of relevant information.

---

# 103. Evidence Integrity

Personnel must not:

- Fabricate monitoring activity.
- Alter evidence to support a preferred conclusion.
- Delete material events to improve metrics.
- Backdate reviews.
- Falsely record events as reviewed.
- Conceal monitoring failures.
- Falsify escalation.
- Represent Planned controls as operational.

Known discrepancies must be documented.

---

# 104. Cryptographic Hashing

Where practical and useful, collected digital evidence may be hashed using SHA-256.

The hash should be recorded with the evidence record.

Hashing supports integrity verification but does not replace complete evidence handling.

---

# 105. Event Timeline

Significant events should have a timeline sufficient to reconstruct important activity.

The timeline may include:

- Initial activity
- Detection
- User report
- Analyst review
- Escalation
- Containment
- Incident activation
- Recovery
- Closure

---

# 106. Monitoring Record Retention

Monitoring records must be retained sufficiently to support:

- Investigation
- Incident response
- Assurance
- Trend analysis
- Corrective action
- Risk reassessment

Retention must reflect information sensitivity and business need.

---

# 107. Event Closure

A security event may be closed when available evidence reasonably supports a conclusion.

Closure categories may include:

- Expected activity
- False positive
- Administrative activity
- Technical issue resolved
- Security event resolved
- Escalated to incident response

---

# 108. Closure Evidence

The event record must contain sufficient information to explain why closure was reasonable.

A status change to "closed" without supporting investigation is insufficient for material events.

---

# 109. Unresolved Event

An event must remain open when material uncertainty remains and additional investigation is reasonably required.

The analyst must not close an event merely to reduce the open-event count.

---

# 110. False Positive

A false-positive conclusion must be supported by available evidence.

Recurring false positives should be documented where useful to improve future review.

---

# 111. Monitoring Metrics

Monitoring metrics may include:

- Material security events reviewed
- Events by priority
- Events escalated
- Events converted to incidents
- Malware alerts
- Phishing reports
- Authentication anomalies
- Unexpected privileged activity
- Unauthorized devices
- Rogue wireless findings
- Security-tool failures
- Monitoring gaps
- After-hours escalations

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 112. Key Performance Indicators

Key Performance Indicators (KPIs) may include:

- Percentage of material events reviewed
- Percentage of significant events appropriately escalated
- Percentage of required network-discovery activities completed
- Percentage of required wireless-discovery activities completed
- Percentage of material security-tool failures investigated

---

# 113. Key Risk Indicators

Key Risk Indicators (KRIs) may include:

- Unresolved Critical security events
- Confirmed credential compromises
- Unexpected privileged activity
- Unauthorized network devices
- Rogue wireless devices
- Significant monitoring gaps
- Repeated security-tool failures
- Unresolved malware events

---

# 114. Metrics Context

Metrics must not be interpreted without context.

An increase in reported phishing may indicate:

- More phishing attacks,
- Better employee awareness and reporting, or
- Both.

A decrease in security alerts may indicate:

- Lower attack activity,
- Improved controls,
- Monitoring failure, or
- Reduced visibility.

---

# 115. Operational Reporting

Operational reporting should identify:

- Current significant events
- Required investigation
- Escalations
- Technical evidence
- Monitoring gaps
- Security-tool failures
- Open exceptions

---

# 116. Management Reporting

Management reporting should identify:

- Significant event trends
- Unresolved issues
- Monitoring performance
- Control failures
- Resource constraints
- Required management action

---

# 117. Executive Reporting

Executive reporting should focus on:

- Material enterprise risk
- Significant incidents
- Meaningful trends
- Major control weaknesses
- Decisions requiring executive action

Raw alert counts should not be presented without business context.

---

# 118. Reporting Chain

Monitoring information should support the reporting chain:

**Technical Evidence → Operational Exception → Management Impact → Enterprise Risk → Executive Decision**

Not every technical event reaches every reporting level.

---

# 119. Quality Review

The IT & Information Security Manager must periodically review monitoring quality.

The review should consider:

- Event coverage
- Investigation quality
- Escalation
- Evidence
- Monitoring gaps
- Tool health
- Documentation
- Closure quality

---

# 120. Monitoring Process Assessment

The security-monitoring process must itself be periodically assessed.

Assessment should determine whether:

- Required monitoring occurs.
- Significant events are reviewed.
- Escalation works.
- Evidence supports conclusions.
- Required discovery occurs.
- Tool failures are addressed.
- Monitoring limitations are accurately represented.

---

# 121. Assessment Methods

Assessment methods may include:

- Inspection
- Observation
- Interviews
- Sampling
- Technical Testing
- Reconciliation
- Independent Performance

The method must match the control being evaluated.

---

# 122. Event Review Testing

An assessor may sample security-event records and determine whether:

- Events were reviewed.
- Investigation matched risk.
- Evidence supports conclusions.
- Escalation occurred when required.
- Closure was appropriate.

---

# 123. Authentication Monitoring Testing

An assessor may select a period of authentication activity and independently apply documented review criteria.

The assessor may compare identified events with actual monitoring records to determine whether material anomalies were appropriately handled.

---

# 124. Privileged Monitoring Testing

An assessor may sample privileged activity and determine whether:

- Account ownership was known.
- Activity was authorized.
- Significant changes were traceable.
- Unexpected activity was investigated.

---

# 125. Network Discovery Testing

An assessor may verify whether network discovery occurred at least every six months and whether:

- Expected devices were reconciled.
- Unexpected devices were investigated.
- Material discrepancies were resolved.

---

# 126. Wireless Discovery Testing

An assessor may compare wireless-discovery results with the authorized baseline.

The expected authorized baseline is one ceiling-mounted access point in the Scranton Headquarters lobby providing Internet-only guest access.

Additional wireless infrastructure requires documented investigation.

---

# 127. Security Tool Health Testing

An assessor may sample security tools and determine whether:

- Expected protection was operating.
- Updates were current where applicable.
- Material failures were detected.
- Failures were investigated.
- Restoration was verified.

---

# 128. Independent Performance

An assessor may perform selected monitoring activities independently.

For example, the assessor may:

1. Select a defined period.
2. Obtain available authentication or security-event information.
3. Apply documented monitoring criteria.
4. Identify events warranting investigation.
5. Compare the results with actual monitoring records.
6. Determine whether material events were appropriately handled.

Independent Performance provides evidence beyond inspection of completed monitoring records.

---

# 129. Assessment Exceptions

Exceptions identified during assessment must be investigated.

Potential causes include:

- Missing log
- Tool failure
- Analyst error
- Documentation failure
- Monitoring gap
- Approved limitation
- Control deficiency

The cause determines the appropriate response.

---

# 130. Findings

Material weaknesses in the monitoring process must be documented.

Examples include:

- Significant security event not reviewed
- Critical event not escalated
- Malware alert ignored
- Required network discovery not performed
- Rogue wireless finding not investigated
- Material security-tool failure not addressed
- Privileged activity not investigated
- Monitoring activity falsely documented
- Material monitoring gap concealed

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 131. Corrective Action

Corrective action must identify:

- Deficiency
- Responsible owner
- Required remediation
- Due date
- Validation method

Corrective action remains open until implementation and appropriate validation.

---

# 132. Control Effectiveness

Monitoring evidence may support a conclusion that a control is:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

The conclusion must be based on evidence rather than intended design.

---

# 133. Current and Proposed Controls

Monitoring personnel must distinguish among:

- Current controls
- Partially implemented controls
- Planned controls
- Implemented controls awaiting validation
- Validated controls

A planned monitoring capability must not be treated as current coverage.

---

# 134. No Premature Risk Credit

Current residual risk must not be reduced merely because:

- A SIEM is proposed.
- EDR is proposed.
- An after-hours process is proposed.
- Additional logging is proposed.
- A monitoring procedure has been approved.
- A security tool has been purchased but not implemented and validated.

---

# 135. Risk Reassessment

Monitoring evidence may require risk reassessment when it identifies:

- New threat activity
- Control failure
- Unexpected exposure
- Repeated suspicious activity
- Significant monitoring gap
- Successful control operation
- Material security incident

Historical risk results must remain preserved.

---

# 136. Risk Relationships

This procedure provides significant treatment support for:

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

# 137. Traceability

This procedure supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Monitoring records must support traceability from observed security activity through investigation, escalation, corrective action, validation, and risk reassessment.

---

# 138. Related Artifacts

- [[PRO-005 Security Operations Program]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-006 Security Awareness & Training Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
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
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-006 Vulnerability Assessment Procedure]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]
- [[PROC-009 Malware Response Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PBK-001 Phishing & Credential Compromise Playbook]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[REG-001 Enterprise Asset Register]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[RPT-008 Operational Security Report & Dashboard]]

---

# 139. Review

This procedure must be reviewed:

- At least annually
- Following material monitoring-process changes
- Following significant security incidents
- Following significant monitoring failures
- Following material technology changes
- Following material assurance findings

The IT & Information Security Manager coordinates review.

Material revisions require CIO approval.

---

# 140. Revision History

| Version | Date     | Description                           | Approval |
| ------- | -------- | ------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Security Monitoring Procedure | CIO      |