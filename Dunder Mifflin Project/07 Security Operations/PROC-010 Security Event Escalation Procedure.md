# PROC-010 Security Event Escalation Procedure

## Document Control

| Field | Value |
|---|---|
| Document ID | PROC-010 |
| Title | Security Event Escalation Procedure |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Security Incident or Escalation-Process Change |

---

# 1. Purpose

This procedure defines how Dunder Mifflin, Inc. evaluates security events and determines when, how, and to whom those events must be escalated.

The procedure provides a consistent path from:

**Security Event → Triage → Priority → Escalation → Incident Determination → Coordinated Response**

The objective is to ensure significant security conditions receive appropriate attention without treating every alert or anomaly as a security incident.

---

# 2. Scope

This procedure applies to security events involving:

- Endpoints
- Servers
- Active Directory
- Network infrastructure
- Firewalls and routers
- Cloud-hosted systems
- Business applications
- Infinity
- Authentication
- Privileged access
- Malware
- Phishing
- Business Email Compromise (BEC)
- Information exposure
- Lost or stolen devices
- Third-party security events
- Physical-security events affecting information systems
- Backup or recovery security
- Significant security-control failures

---

# 3. Authority

This procedure supports requirements established by:

- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[PRO-005 Security Operations Program]]
- [[STD-008 Incident Classification & Escalation Standard]]

---

# 4. Objectives

The escalation process must:

1. Identify events requiring additional attention.
2. Prioritize events according to risk.
3. Escalate urgent events promptly.
4. Distinguish security events from security incidents.
5. Notify appropriate technical and management personnel.
6. Support after-hours response.
7. Preserve useful evidence.
8. Support Incident Response Team (IRT) activation.
9. Document escalation decisions.
10. Prevent significant events from being lost or ignored.

---

# 5. Security Event

A security event is an observable occurrence that may have security relevance.

Examples include:

- Malware alert
- Suspicious email
- Failed authentication pattern
- Unexpected privileged activity
- Unauthorized network device
- Lost laptop
- Unexpected firewall change
- Third-party security notification

A security event is not automatically a security incident.

---

# 6. Security Incident

A security incident is a security event or collection of events that indicates or reasonably suggests a compromise, violation, disruption, or other condition requiring coordinated response.

Incident handling is governed by [[POL-009 Incident Response Policy]] and [[PLN-001 Incident Response Plan]].

---

# 7. Escalation Principle

Escalation must be based on risk and available evidence.

The purpose of escalation is to obtain the:

- Authority
- Expertise
- Coordination
- Resources
- Business involvement

required to manage the event appropriately.

---

# 8. Escalation Is Not Failure

Escalating an event does not mean the initial responder failed.

Prompt escalation is expected when the event exceeds:

- Individual authority
- Technical expertise
- Available resources
- Normal operational scope

---

# 9. Under-Escalation

Personnel must not avoid escalation merely because:

- The event may create additional work.
- The cause is uncertain.
- Management may be concerned.
- Business operations could be affected.
- The analyst hopes the issue will resolve itself.

Material uncertainty may itself justify escalation.

---

# 10. Over-Escalation

Not every:

- Antivirus alert
- Failed login
- Firewall event
- Suspicious email
- User mistake
- System error

requires activation of the Incident Response Team.

Routine events should remain within Security Operations when appropriate.

---

# 11. Escalation Workflow

The standard escalation workflow is:

**Detect / Report → Record → Triage → Prioritize → Investigate → Escalate if Required → Determine Incident Status → Activate Response if Required → Track to Resolution**

Immediate escalation may occur before complete investigation when delay would create unacceptable risk.

---

# 12. Event Sources

Events may originate from:

- Security monitoring
- Managed antivirus
- Users
- Administrators
- Vulnerability assessments
- Penetration tests
- Authentication records
- Firewalls
- VPN records
- Cloud providers
- Vendors
- Contractors
- Physical-security personnel
- Management
- Customers
- Other credible sources

---

# 13. Initial Event Record

A material event should be recorded with available:

- Date and time
- Reporter or source
- Affected asset
- Affected account or user
- Description
- Initial evidence
- Initial priority
- Assigned responder
- Current status

Incomplete information must not prevent urgent escalation.

---

# 14. Initial Triage

Initial triage should determine:

- What happened
- What may be affected
- Whether activity is continuing
- Whether immediate containment is required
- Whether credentials may be compromised
- Whether sensitive information may be exposed
- Whether business operations are affected
- Whether additional expertise is required

---

# 15. Priority Factors

Priority must consider:

- Human safety
- Active compromise
- Asset criticality
- Information classification
- Account privilege
- Internet exposure
- Number of affected systems
- Known vulnerabilities
- Business impact
- Potential spread
- Evidence of malicious activity
- Recovery impact

---

# 16. Human Safety

Human life and safety take priority over:

- Evidence
- Systems
- Facilities
- Equipment
- Inventory
- Revenue

Any event presenting a credible safety concern must be escalated immediately to appropriate emergency or management personnel.

---

# 17. Event Priority Levels

Security events are assigned one of four operational priorities:

- Critical
- High
- Moderate
- Low

Operational event priority is used to guide response and does not automatically equal enterprise risk-register scoring.

---

# 18. Critical Event

A Critical event indicates or reasonably suggests immediate material harm, significant compromise, or severe disruption requiring urgent coordinated action.

Examples may include:

- Active ransomware affecting multiple systems
- Confirmed Domain Administrator compromise
- Widespread destructive malware
- Significant Restricted information exposure
- Active compromise of a Critical system
- Material compromise threatening backup recovery
- Security event creating major business disruption

Critical events require immediate escalation.

---

# 19. High-Priority Event

A High-priority event indicates serious security exposure requiring prompt investigation and management awareness.

Examples may include:

- Significant malware infection
- Credible credential compromise
- Unexpected privileged activity
- Significant Internet-facing compromise attempt with evidence of success
- Unauthorized access to sensitive information
- Significant third-party security incident
- Material security-control failure

---

# 20. Moderate-Priority Event

A Moderate-priority event requires investigation but does not currently indicate immediate material enterprise impact.

Examples may include:

- Suspicious authentication requiring review
- Isolated malware blocked by existing controls
- Unauthorized device without evidence of compromise
- Significant configuration discrepancy
- Suspicious email without known user interaction

---

# 21. Low-Priority Event

A Low-priority event has limited apparent security impact and may be handled through normal operational review.

Low priority does not authorize ignoring the event.

---

# 22. Priority Adjustment

Event priority may increase or decrease as additional evidence becomes available.

Priority changes must be documented for material events.

---

# 23. Critical Escalation

A Critical event must be escalated immediately to the IT & Information Security Manager.

The CIO must be notified promptly.

The Incident Response Team must be considered for immediate activation.

---

# 24. High Escalation

A High-priority event must be promptly escalated to the IT & Information Security Manager.

The CIO must be notified when:

- Material business impact exists.
- Sensitive information is affected.
- Privileged compromise is suspected.
- Significant cross-functional coordination is required.
- The event may become Critical.

---

# 25. Moderate Escalation

Moderate events may normally remain within Security Operations unless:

- Investigation identifies increased impact.
- Required action exceeds analyst authority.
- Business coordination is required.
- The event remains unresolved.
- Similar events recur.

---

# 26. Low Escalation

Low-priority events normally remain within routine Security Operations.

Repeated Low events may require escalation when they reveal:

- A pattern
- Control weakness
- Recurring configuration problem
- Emerging threat

---

# 27. IT & Information Security Manager

The IT & Information Security Manager is the primary management escalation point for information-security events.

Responsibilities include:

- Reviewing significant events
- Coordinating technical response
- Determining additional escalation
- Supporting incident classification
- Coordinating with the CIO
- Authorizing appropriate operational actions

---

# 28. CIO

The CIO must receive escalation for events involving significant:

- Enterprise technology risk
- Business interruption
- Information exposure
- Privileged compromise
- Critical systems
- Third-party impact
- Incident-response requirements

The CIO may escalate to the CEO or Information Security and Risk Committee (ISRC) as appropriate.

---

# 29. CEO Escalation

The CEO must be notified when an event may create material enterprise impact requiring executive authority or decision.

Examples include:

- Severe business interruption
- Significant sensitive-information exposure
- Major financial impact
- Major legal concern
- Significant public or customer impact
- Critical enterprise risk
- Major recovery decision

---

# 30. Information Security and Risk Committee

The Information Security and Risk Committee may receive information about significant events when the event requires:

- Enterprise risk review
- Cross-functional management action
- Risk acceptance
- Significant corrective action
- Security investment
- Policy or governance decision

The committee does not replace immediate operational response.

---

# 31. Business Owner Notification

The responsible business owner must be notified when an event materially affects:

- Business operations
- Business information
- Business-system availability
- Customer service
- Financial processing
- Warehouse operations
- Other owned processes

---

# 32. Human Resources Notification

Human Resources (HR) should be involved when an event materially involves:

- Employee misconduct
- Terminated worker access
- Personnel records
- Employee investigation
- Personnel action

Security Operations must not independently make employment decisions.

---

# 33. Finance Notification

Finance must be involved when an event materially involves:

- Business Email Compromise
- Payment fraud
- Vendor bank-account changes
- Payroll fraud
- Financial records
- Unauthorized financial transactions

---

# 34. Legal and Compliance Notification

Legal/Compliance must be involved when an event may create material:

- Legal exposure
- Contractual obligation
- Privacy concern
- Evidence-preservation requirement
- Notification obligation
- Law-enforcement consideration

Technical personnel must not independently make legal determinations outside their authority.

---

# 35. Operations Notification

Operations must be involved when an event materially affects:

- Warehouses
- Inventory
- Fulfillment
- Shipping
- Facilities
- Distribution
- Operational continuity

---

# 36. Third-Party Coordination

A third party may need notification when the event affects or originates from:

- Cloud service
- Payment processor
- Internet service
- Application support
- Managed service
- Vendor technology
- Contractor activity

Third-party communication must follow applicable contractual and security requirements.

---

# 37. Critical Third-Party Notification

Critical providers are expected to notify Dunder Mifflin of material security incidents within 24 hours of discovery under established third-party requirements.

Receipt of such a notification requires prompt evaluation.

---

# 38. Third-Party Notification Failure

Failure of a Critical provider to provide required security notification may require escalation to:

- IT & Information Security Manager
- CIO
- Responsible business owner
- Third-party risk management

The failure may create a separate control concern.

---

# 39. Infinity Escalation

Security events involving Infinity require heightened attention when they involve:

- Production systems
- Authentication
- Administrative access
- Customer information
- Application integrity
- Database access
- Contractor activity
- Internet-facing compromise

---

# 40. Infinity Contractor

The Infinity contractor may provide technical support during an event but does not independently control:

- Incident classification
- Risk acceptance
- Evidence disposition
- Finding closure
- Enterprise escalation

Dunder Mifflin retains accountability.

---

# 41. Privileged Access Event

Unexpected privileged access requires prompt evaluation.

The event must be escalated when it involves:

- Domain Administrator
- Unauthorized server administration
- Firewall administration
- Backup administration
- Security-tool administration
- Infinity production administration
- Significant database administration

---

# 42. Domain Administrator Event

Suspected compromise or unauthorized use of a Domain Administrator account requires immediate escalation to:

- IT & Information Security Manager
- CIO

The event must be evaluated for Incident Response Team activation.

---

# 43. Credential Compromise

Suspected credential compromise must be escalated according to:

- Account privilege
- Systems accessible
- Evidence of use
- Information exposure
- Business impact

A compromised ordinary account may become a Critical event if it provides a path to significant systems or information.

---

# 44. Phishing Escalation

A phishing message should be escalated when:

- Credentials were disclosed.
- Malware may have executed.
- Multiple users were affected.
- Executive impersonation occurred.
- Financial action was requested.
- Sensitive information was disclosed.
- The campaign appears widespread.

---

# 45. Business Email Compromise

Suspected Business Email Compromise requires prompt coordination among:

- Security Operations
- IT & Information Security Manager
- Finance where financial activity is involved
- Affected business management

Significant financial or executive impersonation events may require CIO and CEO notification.

---

# 46. Malware Escalation

Malware must be escalated when it involves:

- Multiple systems
- Ransomware
- Destructive behavior
- Privileged credentials
- Critical systems
- Sensitive information
- Significant business interruption
- Failed containment

Malware response follows [[PROC-009 Malware Response Procedure]].

---

# 47. Ransomware Escalation

Suspected ransomware requires immediate escalation.

At minimum, notify:

- IT & Information Security Manager
- Appropriate technical administrators
- CIO

The Incident Response Team must be considered for immediate activation.

---

# 48. Sensitive Information Exposure

Suspected unauthorized disclosure of Confidential or Restricted information requires escalation appropriate to:

- Information classification
- Volume
- Affected individuals or organizations
- Exposure duration
- Evidence of access
- Legal or contractual obligations

---

# 49. Lost or Stolen Device

A lost or stolen device must be escalated when:

- Restricted information may be present.
- Full-Disk Encryption (FDE) status is uncertain.
- Privileged credentials may be exposed.
- Remote lock or wipe is unavailable or unsuccessful.
- Evidence suggests theft targeted company information.

---

# 50. Network Security Event

A network-security event requires escalation when it indicates:

- Unauthorized access
- Unexpected Internet exposure
- Firewall compromise
- Unauthorized administrative interface
- Significant Denial-of-Service (DoS)
- Potential attacker persistence
- Significant rogue infrastructure

---

# 51. Rogue Device

An unauthorized network or wireless device must be escalated when:

- Malicious purpose is suspected.
- Corporate resources are accessible.
- Sensitive traffic may be exposed.
- Device ownership cannot be reasonably established.
- Removal cannot be promptly completed.

---

# 52. Cloud Security Event

A cloud-security event requires escalation based on:

- Systems affected
- Information affected
- Administrative compromise
- Service availability
- Provider response
- Recovery requirements

A provider outage without evidence of compromise may primarily require Business Continuity/Disaster Recovery (BC/DR) response rather than security incident response.

---

# 53. Backup Security Event

Security events affecting backups require heightened escalation when they may affect:

- Backup integrity
- Backup confidentiality
- Recovery availability
- Backup administration
- Ransomware recovery
- Disaster recovery

---

# 54. Data Integrity Event

Suspected unauthorized or unexplained data modification requires escalation when it materially affects:

- Customer records
- Orders
- Inventory
- Accounting
- Payroll
- Authentication
- Application data
- Recovery data

---

# 55. Physical Security Event

Physical-security events must be escalated to Information Security when they affect:

- IT Restricted areas
- Servers
- Network equipment
- Company devices
- Access credentials
- Sensitive information
- Technology contractors

---

# 56. Vulnerability Escalation

A vulnerability may require Security Operations escalation when:

- Active exploitation is suspected.
- Exploitation is observed.
- The vulnerability affects a Critical system.
- Immediate mitigation is required.
- Normal remediation timing is inadequate.

The vulnerability remains subject to [[PRO-004 Vulnerability Management Program]].

---

# 57. Penetration-Test Escalation

Penetration testing may discover conditions requiring immediate escalation.

Examples include:

- Unexpected active compromise
- Critical exploitable exposure
- Material sensitive-data exposure
- Significant production instability

The tester must follow [[STD-007 Penetration Testing Standard]].

---

# 58. Security-Control Failure

A material failure of a security control requires escalation when it creates meaningful exposure.

Examples include:

- Antivirus disabled across multiple systems
- Authentication logging failure
- Significant firewall misconfiguration
- Backup protection failure
- Unexpected privileged access
- Monitoring blind spot

---

# 59. Multiple Related Events

Multiple individually minor events may require escalation when correlation suggests a broader attack.

Example:

**Phishing Message → Failed Logins → Successful Login → Unexpected Privileged Activity**

Events must not be evaluated only in isolation when evidence supports correlation.

---

# 60. Recurring Events

Repeated similar events may indicate:

- Persistent threat activity
- Unresolved vulnerability
- Control weakness
- Incomplete remediation
- Training need
- Configuration problem

Recurring events may justify escalation even when individual events are not severe.

---

# 61. Escalation Based on Uncertainty

A responder does not need complete proof of compromise before escalating a significant concern.

Escalation is appropriate when available evidence creates a reasonable basis for concern and delay could materially increase harm.

---

# 62. Immediate Containment Before Escalation

When delay would materially increase harm, authorized personnel may take reasonable immediate containment actions before management notification.

Examples include:

- Isolating an infected endpoint
- Disabling a suspected compromised account
- Blocking malicious communication
- Restricting a vulnerable service

The action and reason must be documented.

---

# 63. Authority Limits

Immediate containment does not authorize unrestricted changes.

Personnel must remain within their:

- Technical authority
- Access authorization
- Role
- Emergency procedures

Actions beyond normal authority require escalation.

---

# 64. Incident Determination

The IT & Information Security Manager, in coordination with the CIO where appropriate, determines whether a significant security event requires formal incident response.

The determination should consider:

- Scope
- Severity
- Business impact
- Information exposure
- Privilege
- Complexity
- Required coordination

---

# 65. Incident Response Team Activation

The Incident Response Team should be activated when coordinated cross-functional response is required.

Examples include:

- Ransomware
- Significant malware
- Material data exposure
- Privileged compromise
- Multiple affected systems
- Significant third-party incident
- Major business interruption
- Legal or executive involvement

---

# 66. Incident Classification

Once formal incident response is activated, the incident must be classified according to [[STD-008 Incident Classification & Escalation Standard]].

Operational event priority and incident classification are related but distinct.

---

# 67. Event Priority Versus Enterprise Risk

Security-event priority is used for immediate operational response.

Enterprise risk scoring is governed by [[POL-005 Risk Management Policy]] and [[RPT-003 Enterprise Risk Assessment]].

A Critical operational event does not automatically create a Critical enterprise risk-register score.

---

# 68. Event Priority Versus Business Impact Analysis

Business Impact Analysis (BIA) criticality identifies the business importance and recovery requirements of processes and systems.

Event priority identifies the urgency of a particular security event.

A lower-criticality system may still experience a High or Critical security event.

---

# 69. Escalation Communication

Escalation communication must be:

- Clear
- Concise
- Fact based
- Timely
- Appropriate to the recipient

Known facts must be distinguished from assumptions.

---

# 70. Initial Escalation Message

An initial escalation should communicate available:

- Event
- Detection time
- Affected system or process
- Current impact
- Evidence
- Containment already performed
- Immediate concern
- Assistance or decision required

Complete investigation is not required before initial escalation.

---

# 71. Facts and Assumptions

Escalation communication must distinguish among:

- Confirmed facts
- Reasonable conclusions
- Suspected conditions
- Unknown information

Uncertainty must not be concealed.

---

# 72. Communication Sensitivity

Security-event information must be distributed according to legitimate need.

Sensitive details such as:

- Credentials
- Exploitable vulnerabilities
- Personal information
- Restricted information

must not be unnecessarily included in broad communications.

---

# 73. Out-of-Band Communication

If normal company communication systems may be compromised or unavailable, responders should use an appropriate alternate communication method.

Company-issued phones and cellular service may support alternate communication where available.

---

# 74. Personal Phones

Personal phones may be used for urgent safety or contact purposes when normal communication is unavailable.

They are not the normal baseline for handling sensitive company information.

---

# 75. After-Hours Escalation

The after-hours process should maintain:

- Primary security contact
- Alternate contact
- Contact method
- Escalation criteria
- Management escalation path

The process provides emergency availability without representing a 24x7 SOC.

---

# 76. Immediate After-Hours Events

Events requiring immediate after-hours escalation may include:

- Ransomware
- Active compromise
- Significant credential compromise
- Critical-system attack
- Material data exposure
- Major security-control failure
- Significant third-party security incident

---

# 77. Nonurgent After-Hours Events

Lower-risk events may be reviewed during the next appropriate operating period when delay does not materially increase:

- Exposure
- Business impact
- Spread
- Evidence loss
- Recovery difficulty

---

# 78. Failed Primary Contact

If the primary after-hours contact cannot be reached for an urgent event, the responder must use the designated alternate.

Urgent events must not remain unaddressed merely because the primary contact is unavailable.

---

# 79. Failed Management Contact

If a required management contact cannot be reached during a Critical event, escalation must continue through the established management chain.

The responder must document attempted contacts.

---

# 80. External Emergency Services

Events involving immediate threats to human life, fire, violence, or other physical emergencies must be escalated to appropriate emergency services.

Security-event procedures must not delay emergency response.

---

# 81. Law Enforcement

Contact with law enforcement should normally be coordinated with:

- Executive management
- Legal/Compliance
- Appropriate security or operational management

Immediate threats to human safety may require direct emergency contact.

---

# 82. Customer Communication

Technical personnel must not independently make external customer statements about significant security incidents unless authorized.

Customer communication must be coordinated with appropriate management and Legal/Compliance.

---

# 83. Public Communication

Public statements regarding significant security incidents require authorized executive communication.

Security Operations personnel must not independently disclose incident information publicly.

---

# 84. Vendor Communication

Technical communication with a vendor may occur as necessary for response.

Statements involving:

- Liability
- Contractual breach
- Public disclosure
- Formal acceptance of responsibility

must be coordinated with appropriate management and Legal/Compliance.

---

# 85. Evidence Preservation During Escalation

Escalation must not unnecessarily destroy useful evidence.

Responders should preserve relevant:

- Logs
- Emails
- Files
- Screenshots
- Authentication records
- Network information
- System information
- User reports

Evidence handling follows [[PROC-011 Evidence Handling Procedure]].

---

# 86. Timeline

Significant escalated events must maintain a timeline sufficient to reconstruct:

- Detection
- Initial review
- Escalation
- Notifications
- Containment
- Incident activation
- Major decisions
- Recovery
- Closure

Unknown times must remain identified as unknown rather than invented.

---

# 87. Escalation Record

A material escalation record should identify:

- Event identifier
- Priority
- Reason for escalation
- Date and time
- Person escalating
- Person notified
- Method
- Evidence available
- Action requested
- Response received

---

# 88. Escalation Acknowledgment

For Critical and significant High events, the responder should obtain confirmation that the escalation was received where practical.

Lack of acknowledgment may require escalation to an alternate contact.

---

# 89. Status Updates

Significant events require status updates appropriate to:

- Event severity
- Rate of change
- Business impact
- Management needs

Updates should occur when material new information becomes available.

---

# 90. Avoiding Unsupported Precision

Event records must not invent:

- Exact compromise times
- Attacker identity
- Data volume
- Root cause
- Impact

when evidence does not support those conclusions.

---

# 91. Escalation Closure

Escalation may be closed when:

- The event is resolved within Security Operations,
- The event is transferred into formal incident response, or
- Another authorized process assumes responsibility.

The disposition must be documented.

---

# 92. Event Transfer to Incident Response

When an event becomes a formal incident, the event record must identify:

- Incident status
- Incident owner
- Transfer time
- Available evidence
- Actions already performed
- Outstanding concerns

The original event record must remain preserved.

---

# 93. No Record Replacement

Creation of an incident record must not erase or overwrite the original security-event history.

The records should remain traceable.

---

# 94. Escalation to Vulnerability Management

Events identifying technical vulnerabilities must be referred to:

- [[PRO-004 Vulnerability Management Program]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]

Operational containment does not replace vulnerability remediation.

---

# 95. Escalation to Change Management

Events requiring technical configuration changes must coordinate with [[POL-007 Change & Configuration Management Policy]].

Emergency changes may be performed when delay creates unacceptable risk.

Required documentation must follow promptly.

---

# 96. Escalation to Business Continuity

An event must be referred to Business Continuity/Disaster Recovery when it materially affects:

- Critical business processes
- System availability
- Facility availability
- Recovery capability
- Normal communications

---

# 97. Escalation to Risk Management

An event should be referred for enterprise risk review when it reveals:

- New material risk
- Greater likelihood than expected
- Greater impact than expected
- Material control failure
- Significant recurring weakness
- Need for risk acceptance

---

# 98. Escalation to Corrective Action

A material control or process deficiency identified during an event must be documented and tracked when corrective action is required.

Material deficiencies are maintained in [[REG-004 Finding & Corrective Action Register]].

---

# 99. Retained DFIR Provider

A retained Digital Forensics and Incident Response (DFIR) provider should be available for events exceeding internal capability.

This is a proposed capability.

It must not receive current control-effectiveness credit until implemented and available.

---

# 100. DFIR Escalation Criteria

External DFIR support may be appropriate for:

- Significant ransomware
- Complex malware
- Domain compromise
- Significant data exposure
- Complex forensic investigation
- Material legal concern
- Evidence requirements beyond internal capability

---

# 101. DFIR Authorization

Engagement of the retained DFIR provider must follow authorized incident-response and procurement arrangements.

External responders must comply with applicable:

- Confidentiality
- Access
- Evidence
- Third-party security requirements

---

# 102. Confidentiality Requirement

Nonemployees receiving sensitive system or information access during escalation or incident response must have an enforceable Non-Disclosure Agreement (NDA) or equivalent confidentiality obligation before access.

The requirement is based on access and information sensitivity rather than vendor title.

Emergency urgency does not eliminate confidentiality requirements for sensitive access.

---

# 103. Security Event Metrics

Escalation metrics may include:

- Events by priority
- Events escalated
- Critical events
- High events
- Events converted to incidents
- After-hours escalations
- Events requiring executive notification
- Recurring escalated events
- Escalation failures
- Events with delayed escalation

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 104. Key Performance Indicators

Key Performance Indicators (KPIs) may include:

- Percentage of Critical events appropriately escalated
- Percentage of significant High events appropriately escalated
- Percentage of escalated events with complete required records
- Percentage of events transferred correctly to incident response
- Percentage of after-hours urgent events reaching an authorized responder

---

# 105. Key Risk Indicators

Key Risk Indicators (KRIs) may include:

- Critical events not promptly escalated
- Repeated escalation failures
- Significant events discovered after delayed response
- Repeated privileged-access events
- Significant events with unclear ownership
- Recurring events without corrective action

---

# 106. Metric Interpretation

Escalation metrics must be interpreted in context.

An increase in escalated events may indicate:

- Increased attack activity
- Better detection
- Improved escalation behavior
- Broader system exposure

A decrease does not automatically indicate reduced risk.

---

# 107. Operational Reporting

Operational reporting should identify:

- Active escalated events
- Priority
- Affected assets
- Current owner
- Required action
- Technical evidence
- Incident status
- Exceptions

---

# 108. Management Reporting

Management reporting should focus on:

- Significant events
- Escalation performance
- Delayed responses
- Recurring event categories
- Ownership
- Resource needs
- Required corrective action

---

# 109. Executive Reporting

Executive reporting should focus on:

- Material enterprise exposure
- Significant incidents
- Major business impact
- Significant control failures
- Required decisions
- Risk requiring acceptance or investment

---

# 110. Reporting Principle

Escalation supports the enterprise reporting model:

**Operational → Execution, Evidence, Exceptions, Technical Detail**

**Management → Accountability, Performance, Action**

**Executive → Decisions and Enterprise Risk**

---

# 111. Reporting Chain

Security-event information should support:

**Technical Evidence → Operational Exception → Management Impact → Enterprise Risk → Executive Decision**

Escalation should move information only as high as necessary to support the required decision.

---

# 112. Procedure Testing

The escalation procedure must be periodically tested.

Testing may occur through:

- Tabletop exercises
- Incident-response exercises
- Review of actual events
- Sampling of event records
- After-hours contact tests

---

# 113. After-Hours Contact Test

The after-hours escalation process should be periodically tested to verify:

- Contact information is current.
- Primary contact can be reached.
- Alternate contact is available.
- Escalation instructions are understood.

Testing must not be represented as a real incident.

---

# 114. Tabletop Testing

A tabletop exercise may present scenarios such as:

- Ransomware
- Domain Administrator compromise
- Business Email Compromise
- Data exposure
- Cloud-provider security incident
- Lost encrypted laptop

Participants should identify appropriate escalation paths.

---

# 115. Assessment Methods

Assessment methods may include:

- Inspection
- Observation
- Interviews
- Sampling
- Exercises
- Reconciliation
- Independent Performance

The method must match the control being evaluated.

---

# 116. Escalation Record Testing

An assessor may sample significant security events and determine whether:

- Priority was reasonable.
- Required escalation occurred.
- Appropriate personnel were notified.
- Escalation was timely.
- Evidence supports the disposition.

---

# 117. Critical Event Testing

An assessor may select Critical events and determine whether:

- Immediate escalation occurred.
- IT & Information Security Manager was notified.
- CIO was notified.
- Incident Response Team activation was considered.
- Major decisions were documented.

---

# 118. Incident Transition Testing

An assessor may select events converted to incidents and determine whether:

- The transition was documented.
- Incident ownership was established.
- Evidence transferred appropriately.
- The original event history remained preserved.

---

# 119. Independent Performance

An assessor may independently evaluate selected security events.

For example, the assessor may:

1. Select a sample of event records.
2. Review available evidence.
3. Apply the documented priority criteria.
4. Determine the escalation path required by this procedure.
5. Compare that result with actual handling.
6. Identify material differences.

Independent Performance provides evidence beyond inspection of the final event status.

---

# 120. Assessment Exceptions

Assessment exceptions must be investigated.

Potential causes include:

- Incorrect priority
- Delayed escalation
- Missing notification
- Outdated contact information
- Incomplete evidence
- Documentation failure
- Unclear authority
- Control deficiency

---

# 121. Findings

Material escalation deficiencies must be documented.

Examples include:

- Critical event not escalated
- Significant High event ignored
- Required CIO notification omitted
- Event incorrectly closed to avoid escalation
- After-hours escalation path unavailable
- Material incident not transferred to incident response
- Escalation records falsified
- Significant recurring events not elevated

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 122. Corrective Action

Corrective action must identify:

- Deficiency
- Accountable owner
- Required action
- Due date
- Validation method

Corrective action remains open until appropriately validated.

---

# 123. Control Effectiveness

Escalation evidence may support conclusions that a control is:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

The conclusion must be supported by actual evidence.

---

# 124. Current and Proposed Controls

Escalation records must distinguish among:

- Current controls
- Partially implemented controls
- Planned controls
- Implemented controls awaiting validation
- Validated controls

A proposed escalation capability must not be represented as operational.

---

# 125. No Premature Risk Credit

Current residual risk must not be reduced merely because:

- An after-hours process is proposed.
- A DFIR provider is proposed.
- An escalation procedure has been approved.
- A communication tool is planned.
- An incident-response improvement is planned.

Risk reduction requires implementation and appropriate validation.

---

# 126. Risk Reassessment

Escalated security events may require risk reassessment when they reveal:

- New threat activity
- Unexpected attack path
- Material control failure
- Greater likelihood
- Greater impact
- Significant recurring weakness
- Successful control performance

Historical risk results must remain preserved.

---

# 127. Risk Relationships

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
- R021 Fire
- R022 Water
- R023 Utility / Power / HVAC
- R024 Physical Access
- R025 Vehicle
- R027 Backup / Recovery Failure
- R028 Data Corruption
- R029 Vendor Fraud
- R030 Sales Fraud
- R031 Payroll Fraud
- R032 Inventory Theft
- R033 Manual Outage Error
- R034 Loss of Headquarters
- R035 Regional Disaster

Risk treatment is maintained in [[RTP-001 Enterprise Risk Treatment Plan]].

---

# 128. Traceability

This procedure supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Escalation records must support traceability from event detection through priority determination, notification, incident transition, corrective action, validation, and risk reassessment.

---

# 129. Related Artifacts

- [[PRO-005 Security Operations Program]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-006 Security Awareness & Training Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-011 Physical & Environmental Security Policy]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]
- [[PROC-008 Security Monitoring Procedure]]
- [[PROC-009 Malware Response Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-013 Manual Processing Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PBK-001 Phishing & Credential Compromise Playbook]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-004 Data Exposure Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[RPT-008 Operational Security Report & Dashboard]]

---

# 130. Review

This procedure must be reviewed:

- At least annually
- Following a material security incident
- Following a significant escalation failure
- Following a material change to the escalation process
- Following significant organizational change
- Following material assurance findings

The IT & Information Security Manager coordinates review.

Material revisions require CIO approval.

---

# 131. Revision History

| Version | Date     | Description                                 | Approval |
| ------- | -------- | ------------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Security Event Escalation Procedure | CIO      |