# STD-008 Incident Classification & Escalation Standard

## Document Control

| Field | Value |
|---|---|
| Document ID | STD-008 |
| Title | Incident Classification & Escalation Standard |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Incident-Response or Classification Change |

---

# 1. Purpose

This standard establishes the required method for classifying information-security incidents and determining the level of escalation, coordination, and management involvement required.

The standard provides a consistent framework for:

- Incident severity
- Business impact
- Information impact
- Technical impact
- Escalation
- Incident Response Team activation
- Cross-functional notification
- Executive notification
- Incident reclassification

---

# 2. Scope

This standard applies to information-security incidents involving:

- Endpoints
- Servers
- Networks
- Active Directory
- Cloud-hosted systems
- Business applications
- Infinity
- Authentication
- Privileged access
- Malware
- Ransomware
- Phishing
- Business Email Compromise (BEC)
- Information exposure
- Third-party technology
- Backup and recovery
- Physical events affecting information systems
- Fraud with a material information-security component

---

# 3. Authority

This standard supports requirements established by:

- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[PRO-005 Security Operations Program]]
- [[PLN-001 Incident Response Plan]]

---

# 4. Objectives

Incident classification must:

1. Establish consistent severity decisions.
2. Prioritize response according to risk and impact.
3. Identify required management involvement.
4. Support timely Incident Response Team (IRT) activation.
5. Identify required business participation.
6. Support executive decision-making.
7. Prevent serious incidents from being treated as routine events.
8. Avoid unnecessary executive escalation of minor events.
9. Support consistent incident reporting.
10. Preserve traceability from event detection through incident closure.

---

# 5. Security Event Versus Security Incident

A security event is an observable occurrence that may have security relevance.

A security incident is an event or collection of events that indicates or reasonably suggests a compromise, violation, disruption, or other security condition requiring coordinated response.

Not every security event becomes an incident.

---

# 6. Event-to-Incident Transition

Security events are initially handled under [[PROC-010 Security Event Escalation Procedure]].

When an event requires formal coordinated incident response, it transitions into the incident-response process governed by:

- [[POL-009 Incident Response Policy]]
- [[PLN-001 Incident Response Plan]]
- This standard

---

# 7. Classification Point

Incident classification must occur as soon as sufficient information exists to reasonably evaluate severity.

Complete investigation is not required before classification.

---

# 8. Initial Classification

Initial classification may be based on incomplete information.

When uncertainty exists, personnel should select a severity sufficient to protect the organization while additional facts are obtained.

---

# 9. Reclassification

Incident severity must be changed when material new evidence demonstrates that the existing classification no longer reflects actual or reasonably expected impact.

An incident may be:

- Upgraded
- Downgraded

The reason for material reclassification must be documented.

---

# 10. Classification Model

Incidents are classified using four severity levels:

- Severity 1: Critical
- Severity 2: High
- Severity 3: Moderate
- Severity 4: Low

Severity 1 represents the highest incident severity.

---

# 11. Classification Factors

Incident severity must consider:

- Human safety
- Business impact
- Information sensitivity
- Information exposure
- System criticality
- Account privilege
- Scope
- Malware behavior
- Persistence
- Data integrity
- Availability
- Recovery impact
- Third-party involvement
- Financial impact
- Legal or contractual implications
- Potential for continued harm

---

# 12. Classification Judgment

Incident classification requires professional judgment.

No single factor automatically determines severity in every circumstance.

The total incident context must be considered.

---

# 13. Human Safety Priority

Human life and safety take priority over:

- Incident classification
- Evidence preservation
- System availability
- Facilities
- Equipment
- Inventory
- Revenue

Incidents involving immediate danger to people require emergency action regardless of security severity terminology.

---

# 14. Severity 1: Critical

A Severity 1 incident creates or reasonably threatens severe enterprise impact requiring immediate coordinated response and executive awareness.

Severity 1 incidents require the highest level of security escalation.

---

# 15. Severity 1 Indicators

Examples include:

- Widespread ransomware
- Destructive malware affecting multiple systems
- Confirmed Domain Administrator compromise with material enterprise exposure
- Significant compromise of multiple Critical systems
- Material compromise of backup and recovery capability
- Significant Restricted information exposure
- Major compromise causing severe business interruption
- Security incident requiring major enterprise recovery decisions
- Significant attack with continuing enterprise-wide impact

---

# 16. Severity 1 Response

Severity 1 incidents require:

- Immediate IT & Information Security Manager notification
- Immediate CIO notification
- Incident Response Team activation
- Appropriate technical containment
- Appropriate business-owner involvement
- Executive notification
- Legal/Compliance involvement when applicable
- Continuous reassessment while the incident remains active

---

# 17. CEO Notification for Severity 1

The CEO must be notified promptly of a Severity 1 incident.

The initial notification does not require complete investigation.

The notification should communicate:

- Known facts
- Current business impact
- Current containment
- Major uncertainties
- Immediate decisions required

---

# 18. Information Security and Risk Committee

The Information Security and Risk Committee (ISRC) should receive appropriate information about Severity 1 incidents.

The committee supports:

- Enterprise risk review
- Cross-functional coordination
- Corrective-action oversight
- Investment decisions
- Risk decisions

The committee does not replace operational incident command.

---

# 19. Severity 2: High

A Severity 2 incident creates serious security or business impact requiring prompt coordinated response and management involvement.

---

# 20. Severity 2 Indicators

Examples include:

- Significant malware infection
- Confirmed credential compromise affecting sensitive systems
- Significant unauthorized privileged activity
- Confirmed unauthorized access to Confidential information
- Material compromise of an important business application
- Significant third-party security incident affecting company operations or information
- Significant localized ransomware
- Material security-control failure with active exposure
- Serious but contained data-integrity compromise

---

# 21. Severity 2 Response

Severity 2 incidents require:

- Prompt IT & Information Security Manager notification
- CIO notification
- Coordinated technical response
- Appropriate business-owner involvement
- Incident Response Team activation when cross-functional coordination is required
- Legal/Compliance notification where appropriate
- Management status reporting

---

# 22. Severity 2 Executive Escalation

The CEO should be notified when a Severity 2 incident creates material:

- Business interruption
- Financial exposure
- Customer impact
- Legal concern
- Sensitive-information exposure
- Enterprise risk
- Executive decision requirement

Not every Severity 2 incident requires immediate CEO involvement.

---

# 23. Severity 3: Moderate

A Severity 3 incident has meaningful but limited impact that can normally be handled through established Information Technology (IT) and Information Security processes.

---

# 24. Severity 3 Indicators

Examples include:

- Confirmed malware isolated to a limited number of systems
- Confirmed compromise of an ordinary user account with limited exposure
- Limited unauthorized access
- Limited Confidential information exposure
- Localized security-control failure
- Security incident requiring coordinated technical remediation but limited management action

---

# 25. Severity 3 Response

Severity 3 incidents require:

- IT & Information Security Manager awareness
- Assigned incident ownership
- Appropriate technical response
- Business-owner notification when business operations are affected
- Documentation
- Escalation if scope or impact increases

The CIO should be notified when circumstances warrant.

---

# 26. Severity 4: Low

A Severity 4 incident has limited confirmed security impact and can normally be resolved through routine security or IT operations.

---

# 27. Severity 4 Indicators

Examples include:

- Minor policy violation with limited impact
- Isolated low-impact unauthorized activity
- Limited compromise with minimal exposure and straightforward remediation
- Other confirmed security incidents with low business and information impact

---

# 28. Severity 4 Response

Severity 4 incidents require:

- Appropriate technical response
- Documentation proportionate to the event
- Assigned ownership
- Corrective action where necessary

Escalation is required if evidence indicates greater impact.

---

# 29. Severity Summary

| Severity | Classification | General Meaning | Required Escalation |
|---|---|---|---|
| 1 | Critical | Severe enterprise impact or immediate threat of severe impact | IT & InfoSec Manager, CIO, IRT, CEO, appropriate business and support functions |
| 2 | High | Serious security or business impact | IT & InfoSec Manager, CIO, appropriate business functions, IRT as required |
| 3 | Moderate | Meaningful but limited impact | IT & InfoSec Manager and appropriate operational/business personnel |
| 4 | Low | Limited confirmed impact | Routine security/IT handling with documented ownership |

---

# 30. Classification Is Not Mechanical

The examples in this standard are guidance.

Responders must not classify an incident solely by matching one phrase in a table.

The complete context must be evaluated.

---

# 31. Scope

Incident scope is a major severity factor.

Scope may include:

- Number of users
- Number of endpoints
- Number of servers
- Number of facilities
- Number of applications
- Number of accounts
- Amount of information
- Number of business processes
- Geographic spread

---

# 32. Scope Uncertainty

Unknown scope may justify a higher initial severity when available evidence suggests material compromise.

Severity may be reduced when investigation establishes that the event is limited.

---

# 33. Information Classification

Information sensitivity must be evaluated according to:

- Public
- Internal
- Confidential
- Restricted

as established by [[STD-001 Information Classification Standard]].

---

# 34. Restricted Information

Unauthorized access to or disclosure of Restricted information requires heightened incident evaluation.

Severity depends on:

- Information type
- Volume
- Exposure
- Recipient
- Duration
- Business impact
- Legal or contractual implications

---

# 35. Confidential Information

Unauthorized access to Confidential information may require Severity 2 or Severity 3 classification depending on scope and impact.

---

# 36. Public Information

An incident involving Public information may still be serious if it affects:

- Integrity
- Availability
- Customer trust
- Business operations
- Website control
- Other systems

Classification is not based solely on confidentiality.

---

# 37. Confidentiality Impact

Confidentiality impact considers unauthorized:

- Access
- Disclosure
- Collection
- Copying
- Transmission
- Exfiltration

of information.

---

# 38. Integrity Impact

Integrity impact considers unauthorized or unexplained modification of:

- Business records
- Orders
- Inventory
- Accounting
- Payroll
- Application data
- Authentication information
- Configuration
- Backup data

---

# 39. Availability Impact

Availability impact considers disruption of:

- Systems
- Applications
- Networks
- Facilities
- Business processes
- Recovery capability

Availability impact must be considered alongside Business Impact Analysis requirements.

---

# 40. Business Impact Analysis

Business Impact Analysis (BIA) criticality is maintained in [[RPT-002 Business Impact Analysis]].

BIA criticality helps determine the importance and recovery requirements of affected business processes and systems.

---

# 41. BIA Criticality Versus Incident Severity

BIA criticality and incident severity are distinct.

BIA asks:

**How important is this process or system to business operations and recovery?**

Incident severity asks:

**How serious is this particular security incident?**

A High-criticality system can experience a Low-severity incident.

A lower-criticality system can experience a High-severity incident.

---

# 42. Maximum Tolerable Downtime

Maximum Tolerable Downtime (MTD) may inform incident severity when an incident threatens prolonged business interruption.

MTD does not by itself determine security severity.

---

# 43. Recovery Time Objective

Recovery Time Objective (RTO) should be considered when estimating the operational consequences of an incident.

An incident likely to exceed required recovery time may warrant higher escalation.

---

# 44. Recovery Point Objective

Recovery Point Objective (RPO) should be considered when an incident affects:

- Data integrity
- Backup availability
- Recovery data
- Transaction history

---

# 45. Operational Event Priority

Operational event priority is assigned during security-event handling under [[PROC-010 Security Event Escalation Procedure]].

The operational priorities are:

- Critical
- High
- Moderate
- Low

---

# 46. Event Priority Versus Incident Severity

Event priority and incident severity serve different purposes.

Event priority determines how urgently a security event requires attention.

Incident severity determines the response and escalation requirements after the condition becomes a formal incident.

A Critical event may ultimately become a lower-severity incident after investigation.

A Moderate event may become a Severity 1 incident if additional evidence reveals greater impact.

---

# 47. Enterprise Risk Scoring

Enterprise risk scoring is governed by:

- [[POL-005 Risk Management Policy]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]

Enterprise risk uses:

**Likelihood × Impact**

with integer values from 1 through 5.

---

# 48. Incident Severity Versus Enterprise Risk

Incident severity must not be confused with enterprise risk scoring.

Enterprise risk asks:

**What is the organization's exposure to a defined risk scenario?**

Incident severity asks:

**How serious is the incident currently being handled?**

A Severity 1 incident does not automatically create a Critical enterprise risk score.

---

# 49. Risk Reassessment

A significant incident may provide evidence requiring enterprise risk reassessment.

Examples include:

- Greater likelihood than expected
- Greater impact than expected
- Control failure
- New attack path
- Unexpected dependency
- Recovery weakness

Historical risk results must remain preserved.

---

# 50. Privilege

Incidents involving privileged accounts require heightened consideration.

Privileged accounts may include:

- Domain Administrator
- Server administrator
- Network administrator
- Backup administrator
- Security-tool administrator
- Application administrator
- Database administrator
- Cloud administrator

---

# 51. Domain Administrator Compromise

Confirmed or strongly suspected Domain Administrator compromise requires immediate escalation.

The incident should normally be treated as Severity 1 or Severity 2 depending on:

- Evidence of use
- Scope
- Persistence
- Systems affected
- Information affected
- Containment status

---

# 52. Ordinary Account Compromise

An ordinary user-account compromise may initially be Severity 3.

Severity must increase when the account:

- Accesses sensitive information
- Enables broader compromise
- Supports financial fraud
- Provides access to Critical systems
- Is used for significant malicious activity

---

# 53. Executive Account Compromise

Executive account compromise requires heightened evaluation because the account may enable:

- Sensitive communications access
- Business Email Compromise
- Fraud
- Impersonation
- Sensitive information access

Executive title alone does not automatically establish Severity 1.

---

# 54. Malware Classification

Malware severity must consider:

- Number of systems
- Malware behavior
- Privilege
- Persistence
- Information exposure
- Spread
- Recovery impact
- Business interruption

Malware response follows [[PROC-009 Malware Response Procedure]].

---

# 55. Ransomware Classification

Ransomware normally requires High or Critical initial treatment until scope and impact are reasonably understood.

Severity 1 is appropriate when ransomware:

- Is widespread
- Affects Critical systems
- Threatens backup recovery
- Creates severe business interruption
- Causes major data-integrity impact

---

# 56. Destructive Malware

Destructive malware requires immediate escalation.

Severity should reflect:

- Systems affected
- Data destruction
- Recovery capability
- Business impact
- Spread

---

# 57. Phishing Classification

A phishing message alone may remain a security event rather than an incident.

Formal incident classification is appropriate when phishing results in or reasonably indicates:

- Credential compromise
- Malware execution
- Sensitive information disclosure
- Fraud
- Unauthorized access

---

# 58. Business Email Compromise

Business Email Compromise severity must consider:

- Account compromise
- Executive impersonation
- Financial action
- Sensitive information
- Fraud amount or potential exposure
- Number of affected parties

Finance must be involved when financial activity is implicated.

---

# 59. Unauthorized Access

Unauthorized-access severity must consider:

- Account used
- Privilege
- Systems accessed
- Information accessed
- Persistence
- Actions performed
- Scope

---

# 60. Information Exposure

Information-exposure severity must consider:

- Classification
- Volume
- Recipient
- Exposure duration
- Evidence of acquisition
- Business impact
- Legal or contractual obligations

---

# 61. Lost or Stolen Device

A lost or stolen device may remain a security event when effective protections substantially limit exposure.

Incident classification should consider:

- Full-Disk Encryption status
- Authentication
- Information stored
- Privileged credentials
- Remote lock or wipe
- Evidence of unauthorized access

---

# 62. Third-Party Incident

Third-party incident severity must reflect Dunder Mifflin's exposure rather than the provider's internal classification.

Consider:

- Company information
- Company credentials
- Service availability
- Business processes
- Recovery
- Provider response
- Contractual requirements

---

# 63. Cloud Provider Incident

A cloud-provider outage without evidence of compromise may primarily require continuity response.

A cloud-provider security compromise affecting company:

- Systems
- Credentials
- Information
- Administrative access

requires incident classification.

---

# 64. Infinity Incident

Infinity incidents require heightened evaluation because Infinity is:

- Internet facing
- Customer accessible
- Internally developed
- Supported by an external contractor
- Integrated with business processing

---

# 65. Infinity Severity Factors

Infinity severity must consider:

- Web-tier compromise
- Application-tier compromise
- Database access
- Customer information
- Administrative access
- Source-code integrity
- Production integrity
- Contractor involvement
- Order-processing impact

---

# 66. Infinity Database

The Infinity database is not intended to be directly Internet accessible.

Evidence of direct unauthorized database access requires prompt escalation.

---

# 67. Backup Incident

An incident affecting backup systems or recovery data requires heightened consideration because it may increase the impact of another incident.

Examples include:

- Backup deletion
- Backup encryption
- Backup credential compromise
- Backup corruption
- Unauthorized backup access

---

# 68. Data Corruption

Data corruption incidents must consider:

- Data affected
- Business process affected
- Recovery point
- Backup integrity
- Reconciliation capability
- Cause
- Scope

---

# 69. Denial of Service

Denial-of-Service incident severity depends on:

- Duration
- Services affected
- Business impact
- Provider response
- Available alternate connectivity
- Recovery expectations

---

# 70. Physical Security Incident

A physical event becomes an information-security incident when it materially affects:

- Information systems
- Restricted areas
- Network equipment
- Company devices
- Sensitive information
- Access credentials
- Recovery capability

---

# 71. Insider Incident

A malicious-insider incident requires cross-functional coordination appropriate to the event.

Potential participants include:

- Information Security
- Human Resources
- Legal/Compliance
- Business management
- Executive management

Security personnel must not independently determine employment discipline.

---

# 72. Fraud-Related Incident

Fraud involving information systems may require security incident response when it involves:

- Account compromise
- Unauthorized access
- System manipulation
- Information theft
- Security-control circumvention

Financial or operational fraud without a material security component may be handled primarily through the responsible business process.

---

# 73. Severity Escalation Triggers

An incident should be upgraded when evidence indicates:

- Increased scope
- Greater information exposure
- Privileged compromise
- Additional affected systems
- Persistence
- Failed containment
- Greater business impact
- Greater recovery impact
- Significant third-party involvement

---

# 74. Severity Downgrade

An incident may be downgraded when reliable evidence establishes that:

- Scope is smaller than initially believed.
- Sensitive information was not affected.
- Compromise did not occur as initially suspected.
- Containment is effective.
- Business impact is materially lower.

Downgrade rationale must be documented.

---

# 75. Severity Cannot Be Reduced for Convenience

Incident severity must not be lowered to:

- Avoid executive notification
- Improve metrics
- Reduce workload
- Avoid Incident Response Team activation
- Avoid documenting a significant incident

---

# 76. Incident Commander

A significant incident must have a clearly identified incident leader or coordinator.

The role may be filled by the:

- IT & Information Security Manager
- CIO
- Other authorized person

depending on incident severity and circumstances.

---

# 77. Incident Response Team

The Incident Response Team is a virtual cross-functional team assembled according to incident needs.

It is not assumed to be a permanently staffed Security Operations Center.

---

# 78. Incident Response Team Participants

Depending on the incident, participants may include:

- IT & Information Security Manager
- Information Security Analyst
- System Administrator
- Network/Security Administrator
- CIO
- Business owner
- Human Resources
- Finance
- Operations
- Legal/Compliance
- Executive management
- External specialists

---

# 79. Severity 1 IRT Activation

Severity 1 requires Incident Response Team activation.

The team must include the personnel necessary to manage:

- Technical containment
- Business impact
- Recovery
- Communication
- Legal considerations
- Executive decisions

---

# 80. Severity 2 IRT Activation

Severity 2 requires Incident Response Team activation when the incident needs cross-functional coordination beyond normal Security Operations.

---

# 81. Severity 3 IRT Activation

Severity 3 does not normally require full Incident Response Team activation.

The team may be activated if:

- Scope expands
- Multiple business functions are affected
- Specialized expertise is required

---

# 82. Severity 4 IRT Activation

Severity 4 incidents normally remain within routine IT or Information Security handling.

---

# 83. After-Hours Incidents

Severity 1 incidents require immediate after-hours escalation.

Severity 2 incidents require prompt after-hours escalation when waiting until normal operating hours could materially increase harm.

---

# 84. After-Hours Capability

The after-hours process provides on-call response capability.

It must not be represented as:

- A 24x7 Security Operations Center
- Continuous analyst monitoring
- Continuous manual review of all logs

---

# 85. Failed Contact

If the primary incident contact cannot be reached during an urgent incident, escalation must continue through the established alternate contact path.

Attempted contacts must be documented.

---

# 86. Business Owner Notification

Business owners must be notified when an incident materially affects their:

- Process
- System
- Information
- Customers
- Operations

Business owners support impact assessment and recovery decisions.

---

# 87. Human Resources Notification

Human Resources must be involved when incidents materially involve:

- Employee misconduct
- Personnel records
- Terminated-worker access
- Employee investigation
- Personnel action

---

# 88. Finance Notification

Finance must be involved when incidents materially involve:

- Business Email Compromise
- Vendor fraud
- Payroll fraud
- Unauthorized financial transactions
- Financial information

---

# 89. Operations Notification

Operations must be involved when incidents materially affect:

- Warehouses
- Inventory
- Fulfillment
- Shipping
- Distribution
- Facilities
- Operational continuity

---

# 90. Legal and Compliance Notification

Legal/Compliance must be involved when an incident may create material:

- Legal exposure
- Contractual obligations
- Privacy concerns
- Notification obligations
- Evidence-preservation requirements
- Law-enforcement considerations

---

# 91. External Communication

External communication regarding a significant incident must be authorized.

Technical personnel must not independently issue:

- Public statements
- Customer notifications
- Admissions of liability
- Regulatory statements

outside their authority.

---

# 92. Law Enforcement

Law-enforcement contact should normally be coordinated with:

- Executive management
- Legal/Compliance
- Appropriate incident leadership

Immediate threats to human safety may require direct emergency contact.

---

# 93. Retained DFIR Provider

A retained Digital Forensics and Incident Response (DFIR) provider should be available for incidents exceeding internal capability.

The retained DFIR capability is proposed.

It must not receive current control-effectiveness credit until implemented and available.

---

# 94. DFIR Escalation

External DFIR support may be appropriate for:

- Significant ransomware
- Domain compromise
- Complex malware
- Significant data exposure
- Complex forensic analysis
- Material legal concerns
- Evidence requirements beyond internal capability

---

# 95. Third-Party Confidentiality

Nonemployees receiving sensitive access during incident response must have an enforceable Non-Disclosure Agreement (NDA) or equivalent confidentiality obligation before access.

The requirement is based on access and information sensitivity rather than vendor title.

---

# 96. Evidence

Incident classification must be supported by available evidence.

Evidence may include:

- Logs
- Alerts
- Emails
- Files
- Authentication records
- Network information
- User reports
- Screenshots
- Third-party reports
- Technical analysis

Evidence handling follows [[PROC-011 Evidence Handling Procedure]].

---

# 97. Evidence Limitations

Incident classification may occur before complete evidence is available.

Classification records must distinguish:

- Known facts
- Reasonable conclusions
- Suspected conditions
- Unknown information

---

# 98. Incident Record

The incident record must include:

- Incident identifier
- Detection date and time
- Initial classification
- Current classification
- Classification rationale
- Affected systems
- Affected business processes
- Information involved
- Incident owner
- Required notifications
- Current status

---

# 99. Reclassification Record

A material reclassification must document:

- Previous severity
- New severity
- Date and time
- Reason
- Supporting evidence
- Person authorizing or recording the change

---

# 100. Incident Timeline

Significant incidents must maintain a timeline sufficient to reconstruct material events.

The timeline should include:

- Detection
- Escalation
- Classification
- Containment
- Notifications
- Major decisions
- Recovery
- Reclassification
- Closure

---

# 101. Containment

Classification must not unnecessarily delay containment.

Authorized responders may take reasonable immediate action when waiting for formal classification would materially increase harm.

---

# 102. Recovery

Incident severity must inform recovery coordination but does not replace BIA recovery requirements.

Recovery remains governed by:

- [[RPT-002 Business Impact Analysis]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]

---

# 103. Manual Continuity

When an incident prevents normal system use, affected functions may activate authorized manual procedures under [[PROC-013 Manual Processing Procedure]].

Manual continuity does not reduce incident severity unless actual impact and recovery conditions justify reclassification.

---

# 104. Incident Closure

Incident closure requirements are established in [[PLN-001 Incident Response Plan]].

Severity may inform the level of:

- Closure review
- Lessons learned
- Corrective action
- Management reporting

---

# 105. Severity 1 Closure Review

Severity 1 incidents require formal management review before final closure.

The review should confirm that:

- Immediate response is complete.
- Required recovery is complete.
- Material evidence is preserved.
- Corrective actions are identified.
- Remaining risk is understood.
- Required follow-up is assigned.

---

# 106. Severity 2 Closure Review

Severity 2 incidents require review by the IT & Information Security Manager and appropriate management.

Significant unresolved issues must remain tracked after incident closure.

---

# 107. Severity 3 and 4 Closure

Severity 3 and Severity 4 incidents may use proportionate closure procedures.

Closure must still preserve required records and outstanding corrective actions.

---

# 108. Lessons Learned

Severity 1 and significant Severity 2 incidents require a documented lessons-learned review.

The review should evaluate:

- Detection
- Escalation
- Classification
- Containment
- Communication
- Evidence
- Recovery
- Control performance
- Required improvements

---

# 109. Corrective Action

Incident findings requiring corrective action must identify:

- Deficiency
- Accountable owner
- Required action
- Due date
- Validation method

Material corrective actions are maintained in [[REG-004 Finding & Corrective Action Register]].

---

# 110. Classification Metrics

Incident-classification metrics may include:

- Incidents by severity
- Severity 1 incidents
- Severity 2 incidents
- Incidents reclassified upward
- Incidents reclassified downward
- Incidents requiring IRT activation
- Incidents requiring executive notification
- Incidents with classification exceptions

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 111. Key Performance Indicators

Key Performance Indicators (KPIs) may include:

- Percentage of incidents classified
- Percentage of Severity 1 incidents receiving required escalation
- Percentage of Severity 2 incidents receiving required management notification
- Percentage of material reclassifications with documented rationale
- Percentage of significant incidents with required cross-functional participation

---

# 112. Key Risk Indicators

Key Risk Indicators (KRIs) may include:

- Unclassified active incidents
- Severity 1 incidents without required escalation
- Repeated upward reclassification caused by inadequate initial triage
- Significant incidents with unclear ownership
- Repeated classification disagreements
- Significant incidents closed without required review

---

# 113. Metric Interpretation

Incident counts must be interpreted in context.

More reported incidents may indicate:

- Increased threat activity
- Improved detection
- Better reporting
- Better classification

A lower incident count does not automatically indicate lower risk.

---

# 114. Operational Reporting

Operational incident reporting should include:

- Incident identifier
- Severity
- Affected assets
- Current owner
- Current status
- Containment
- Evidence
- Required actions
- Exceptions

---

# 115. Management Reporting

Management reporting should focus on:

- Significant incidents
- Business impact
- Incident ownership
- Response performance
- Corrective actions
- Recurring causes
- Resource requirements

---

# 116. Executive Reporting

Executive reporting should focus on:

- Material enterprise impact
- Significant business interruption
- Major information exposure
- Significant control failures
- Enterprise risk
- Decisions required
- Material recovery concerns

---

# 117. Reporting Principle

Incident reporting follows the enterprise reporting model:

**Operational → Execution, Evidence, Exceptions, Technical Detail**

**Management → Accountability, Performance, Action**

**Executive → Decisions and Enterprise Risk**

---

# 118. Reporting Chain

Incident information should support:

**Technical Evidence → Operational Exception → Management Impact → Enterprise Risk → Executive Decision**

Not every incident requires executive reporting.

---

# 119. Classification Testing

The classification model must be periodically tested.

Testing may use:

- Tabletop exercises
- Historical incident records
- Simulated scenarios
- Sampling
- Incident-response exercises

---

# 120. Classification Exercise

A classification exercise should provide participants with a scenario and require them to determine:

- Whether the condition is an event or incident
- Incident severity
- Required escalation
- Required business functions
- Incident Response Team requirements
- Required management notification

---

# 121. Example Scenario: Phishing

A user receives a phishing email but does not interact with it.

This may remain a security event rather than an incident.

If credentials are entered and unauthorized access occurs, formal incident classification is required.

---

# 122. Example Scenario: Isolated Malware

Managed antivirus detects and blocks malware on one standard user workstation.

Investigation confirms no execution, spread, or credential exposure.

The event may remain within Security Operations rather than becoming a formal incident.

---

# 123. Example Scenario: Ransomware

Multiple systems begin encrypting files and shared business data becomes unavailable.

The incident should initially be treated as Severity 1 until scope, containment, recovery capability, and business impact are better understood.

---

# 124. Example Scenario: Lost Laptop

A company laptop is lost.

Records confirm:

- Full-Disk Encryption is active.
- Authentication is required.
- No privileged credentials are stored.
- Remote management remains available.

The event may remain a security event or receive a lower incident classification depending on the circumstances.

---

# 125. Example Scenario: Domain Administrator

Evidence indicates a Domain Administrator credential was used from an unauthorized system.

The event requires immediate escalation and should normally be treated as a Severity 1 or Severity 2 incident while scope is determined.

---

# 126. Example Scenario: Infinity

A penetration test demonstrates unauthorized access from the Infinity web tier into the application tier but no database compromise is identified.

The condition requires immediate remediation and incident evaluation.

Severity depends on:

- Actual unauthorized activity
- Information exposure
- Production impact
- Evidence of preexisting compromise

The penetration test finding itself does not automatically prove an external incident occurred.

---

# 127. Example Scenario: Cloud Outage

The primary cloud provider experiences a service outage with no evidence of malicious activity.

The event primarily invokes availability and continuity processes.

It does not automatically become a security incident merely because systems are unavailable.

---

# 128. Example Scenario: Third-Party Compromise

A Critical provider reports a security incident affecting systems used to support Dunder Mifflin.

Dunder Mifflin must independently determine its own incident severity based on:

- Company exposure
- Information affected
- Credentials affected
- Service impact
- Recovery impact

---

# 129. Assessment Methods

Assessment of this standard may use:

- Inspection
- Observation
- Interviews
- Sampling
- Exercises
- Reconciliation
- Independent Performance

The method must match the classification control being evaluated.

---

# 130. Classification Record Testing

An assessor may sample incident records and determine whether:

- Classification was documented.
- Classification matched available evidence.
- Required escalation occurred.
- Reclassification was documented.
- Required management involvement occurred.

---

# 131. Severity 1 Testing

An assessor may select Severity 1 incidents and determine whether:

- IT & Information Security Manager was notified.
- CIO was notified.
- Incident Response Team was activated.
- CEO was notified.
- Appropriate cross-functional personnel participated.
- Closure review occurred.

---

# 132. Severity 2 Testing

An assessor may select Severity 2 incidents and determine whether:

- Management escalation occurred.
- CIO notification occurred.
- Business-owner involvement occurred where required.
- IRT activation occurred where appropriate.
- Significant follow-up was tracked.

---

# 133. Independent Performance

An assessor may independently classify a sample of historical incident scenarios using the requirements in this standard.

The assessor may:

1. Select the incident.
2. Review the evidence available at the classification point.
3. Apply the classification criteria.
4. Determine the required severity.
5. Determine the required escalation.
6. Compare the result with actual handling.
7. Investigate material differences.

---

# 134. Assessment Exceptions

Classification exceptions must be investigated.

Potential causes include:

- Incomplete triage
- Incorrect severity
- Missing escalation
- Inadequate documentation
- Unclear authority
- Inadequate training
- Process weakness

---

# 135. Findings

Material classification or escalation deficiencies must be documented.

Examples include:

- Severity 1 incident deliberately classified lower to avoid escalation
- Required executive notification omitted
- Significant incident left unclassified
- Incident Response Team not activated when required
- Material reclassification not documented
- Significant incident closed without required review
- Classification record falsified

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 136. Control Effectiveness

Incident-classification evidence may support conclusions that relevant controls are:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

The conclusion must reflect actual evidence.

---

# 137. Current and Proposed Controls

Incident-response records must distinguish among:

- Existing controls
- Partially implemented controls
- Planned controls
- Implemented controls awaiting validation
- Validated controls

The existence of this standard does not prove that incident-classification controls operate effectively.

---

# 138. No Premature Risk Credit

Current residual risk must not be reduced merely because:

- This standard has been approved.
- An Incident Response Team structure is documented.
- A retained DFIR provider is proposed.
- New incident-response capabilities are planned.
- Exercises are scheduled.

Risk reduction requires implementation and appropriate validation.

---

# 139. Risk Reassessment

Incident evidence may support risk reassessment when it demonstrates:

- Increased likelihood
- Increased impact
- Control failure
- New attack path
- Recovery weakness
- Improved control effectiveness

Target residual risk remains a prediction until treatment is implemented and validated.

Historical May 2013 risk results must remain preserved.

---

# 140. Risk Relationships

This standard provides significant treatment and response support across the enterprise risk portfolio, particularly:

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

Not every event associated with these risks becomes a security incident.

---

# 141. Traceability

This standard supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Incident records must preserve traceability from event detection through classification, escalation, response, evidence, findings, corrective action, and risk reassessment.

---

# 142. Related Artifacts

- [[PRO-005 Security Operations Program]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[STD-001 Information Classification Standard]]
- [[STD-007 Penetration Testing Standard]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-008 Security Monitoring Procedure]]
- [[PROC-009 Malware Response Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PBK-001 Phishing & Credential Compromise Playbook]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-004 Data Exposure Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[RPT-008 Operational Security Report & Dashboard]]

---

# 143. Review

This standard must be reviewed:

- At least annually
- Following a Severity 1 incident
- Following a material incident-classification failure
- Following significant incident-response changes
- Following material organizational changes
- Following significant assurance findings

The IT & Information Security Manager coordinates review.

Material revisions require CIO approval.

---

# 144. Revision History

| Version | Date     | Description                                           | Approval |
| ------- | -------- | ----------------------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Incident Classification & Escalation Standard | CIO      |