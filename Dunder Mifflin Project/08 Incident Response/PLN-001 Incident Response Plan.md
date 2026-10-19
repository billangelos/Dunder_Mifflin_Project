# PLN-001 Incident Response Plan

## Document Control

| Field | Value |
|---|---|
| Document ID | PLN-001 |
| Title | Incident Response Plan |
| Version | 1.0 |
| Classification | Confidential |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following a Severity 1 Incident or Material Incident-Response Change |

---

# 1. Purpose

This plan establishes the enterprise process Dunder Mifflin, Inc. uses to prepare for, identify, analyze, contain, eradicate, recover from, and learn from information-security incidents.

The plan provides the organizational structure necessary to coordinate:

- Information Technology (IT)
- Information Security
- Business management
- Executive management
- Human Resources
- Finance
- Operations
- Legal/Compliance
- Third parties
- External specialists

during significant security incidents.

---

# 2. Scope

This plan applies to security incidents affecting or potentially affecting:

- Company information
- Employees
- Customers
- Business processes
- Endpoints
- Servers
- Active Directory
- Network infrastructure
- Cloud-hosted systems
- Business applications
- Infinity
- Authentication
- Privileged access
- Warehouses
- Backup and recovery capability
- Third-party technology services
- Physical systems supporting information security

---

# 3. Authority

This plan operates under:

- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[STD-008 Incident Classification & Escalation Standard]]

---

# 4. Objectives

Incident response must:

1. Protect human life and safety.
2. Limit security and business impact.
3. Contain active threats.
4. Protect unaffected systems.
5. Preserve useful evidence.
6. Determine reasonable incident scope.
7. Restore trusted business operations.
8. Coordinate affected business functions.
9. Support management decisions.
10. Meet applicable legal and contractual obligations.
11. Identify corrective action.
12. Improve future prevention, detection, response, and recovery.

---

# 5. Incident Response Lifecycle

Dunder Mifflin uses the following incident-response lifecycle:

**Preparation → Detection & Analysis → Containment → Eradication → Recovery → Closure → Lessons Learned → Improvement**

Activities may overlap.

Responders may return to an earlier stage when new evidence changes the understanding of the incident.

---

# 6. Safety Priority

Human life and safety take priority over:

- Evidence
- Systems
- Operations
- Facilities
- Equipment
- Inventory
- Revenue
- Other company assets

Incident responders must not delay emergency action when people are in danger.

---

# 7. Security Event Versus Incident

A security event is an observable occurrence that may have security relevance.

A security incident is an event or collection of events that indicates or reasonably suggests a compromise, violation, disruption, or other condition requiring coordinated response.

Security events are initially handled under [[PROC-010 Security Event Escalation Procedure]].

---

# 8. Incident Declaration

A significant security event becomes a formal incident when available information demonstrates that coordinated incident response is required.

Incident declaration should not be delayed merely because:

- Scope remains uncertain.
- Root cause is unknown.
- Complete evidence is unavailable.
- Attribution is unknown.

---

# 9. Incident Classification

Formal incidents are classified under [[STD-008 Incident Classification & Escalation Standard]].

The four incident severity levels are:

- Severity 1: Critical
- Severity 2: High
- Severity 3: Moderate
- Severity 4: Low

---

# 10. Severity Is Dynamic

Incident severity may change as evidence develops.

Material reclassification must document:

- Previous severity
- New severity
- Reason
- Supporting evidence
- Date and time

---

# 11. Incident Response Team

The Incident Response Team (IRT) is a virtual cross-functional team activated according to incident requirements.

Dunder Mifflin does not maintain a permanently staffed Security Operations Center (SOC).

---

# 12. Core Incident Response Team

Core technical participants may include:

- IT & Information Security Manager
- Information Security Analyst
- System Administrator
- Network/Security Administrator
- CIO

Additional participants are added according to incident needs.

---

# 13. Extended Incident Response Team

Extended participants may include:

- CEO
- Chief Operating Officer (COO)
- Chief Financial Officer (CFO)
- Human Resources
- Finance
- Operations
- Legal/Compliance
- Business owners
- Third-party providers
- External security specialists

---

# 14. Incident Leadership

Every significant incident must have a clearly identified incident leader.

The incident leader coordinates:

- Response priorities
- Technical activities
- Business coordination
- Escalation
- Communications
- Decision tracking
- Status reporting

---

# 15. Incident Leader Selection

The incident leader may be the:

- IT & Information Security Manager
- CIO
- Other authorized individual

depending on:

- Severity
- Scope
- Business impact
- Required authority
- Technical complexity

---

# 16. IT & Information Security Manager Responsibilities

The IT & Information Security Manager normally coordinates operational security response.

Responsibilities include:

- Initial incident coordination
- Technical-resource assignment
- Containment coordination
- Evidence preservation
- Escalation
- Status reporting
- Corrective-action identification

---

# 17. CIO Responsibilities

The CIO is accountable for enterprise information-security incident management.

Responsibilities include:

- Executive escalation
- Major technical decisions
- Resource authorization
- Cross-functional coordination
- Significant third-party engagement
- Recovery prioritization
- Risk escalation
- Incident closure oversight

---

# 18. CEO Responsibilities

The CEO provides executive authority for incidents requiring significant enterprise decisions.

Responsibilities may include:

- Major business decisions
- Significant risk acceptance
- Major expenditure authorization
- Enterprise communication decisions
- Significant business-continuity decisions
- Executive stakeholder coordination

---

# 19. Business Owner Responsibilities

Affected business owners support:

- Business-impact determination
- Process prioritization
- Operational workarounds
- Recovery validation
- Customer or business coordination
- Corrective action

---

# 20. Human Resources Responsibilities

Human Resources supports incidents involving:

- Employee conduct
- Personnel records
- Employee investigation
- Terminated personnel
- Personnel action

Information Security does not independently determine employment discipline.

---

# 21. Finance Responsibilities

Finance supports incidents involving:

- Business Email Compromise
- Vendor fraud
- Payroll fraud
- Unauthorized financial transactions
- Financial information
- Financial recovery

---

# 22. Operations Responsibilities

Operations supports incidents affecting:

- Warehouses
- Inventory
- Fulfillment
- Shipping
- Distribution
- Facilities
- Operational continuity

---

# 23. Legal and Compliance Responsibilities

Legal/Compliance supports:

- Legal analysis
- Contractual obligations
- Privacy concerns
- Evidence-preservation requirements
- External notification decisions
- Law-enforcement coordination
- Legal-hold decisions

---

# 24. Information Security Analyst Responsibilities

The Information Security Analyst may support:

- Monitoring
- Triage
- Investigation
- Evidence collection
- Malware analysis
- Timeline development
- Technical validation
- Incident documentation

---

# 25. System Administrator Responsibilities

The System Administrator may support:

- Server containment
- Active Directory investigation
- Account actions
- System recovery
- Backup restoration
- Configuration validation
- Server evidence collection

---

# 26. Network/Security Administrator Responsibilities

The Network/Security Administrator may support:

- Firewall changes
- Network containment
- Network evidence
- VPN investigation
- Network configuration
- Connectivity restoration
- Malicious-traffic blocking

---

# 27. Help Desk Responsibilities

Support personnel may:

- Receive user reports
- Record initial information
- Escalate suspected events
- Provide approved user instructions
- Assist with endpoint replacement

Support personnel must not independently close significant security incidents.

---

# 28. Third-Party Responsibilities

Third parties may support incident response when they:

- Host affected systems
- Provide technology services
- Maintain applications
- Provide security expertise
- Control relevant evidence
- Support recovery

Dunder Mifflin retains responsibility for its incident decisions.

---

# 29. Preparation

Incident-response preparation includes:

- Policies
- Standards
- Procedures
- Contact information
- Escalation paths
- Evidence procedures
- Backup and recovery
- Business continuity
- Security monitoring
- Vulnerability management
- Training
- Exercises

---

# 30. Contact Information

Incident-response contact information must identify appropriate:

- Primary contacts
- Alternate contacts
- Executive contacts
- Business contacts
- Critical providers
- External specialists

Contact information must be reviewed periodically.

---

# 31. After-Hours Capability

Dunder Mifflin should maintain a simple after-hours escalation process for urgent incidents.

This capability does not represent:

- A 24x7 SOC
- Continuous human monitoring
- Continuous manual log analysis

---

# 32. After-Hours Escalation

Severity 1 incidents require immediate after-hours escalation.

Severity 2 incidents require prompt after-hours escalation when waiting could materially increase:

- Exposure
- Business impact
- Spread
- Evidence loss
- Recovery difficulty

---

# 33. Failed Contact

If a primary incident-response contact cannot be reached during an urgent incident, escalation must continue through the designated alternate path.

Attempted contacts must be documented.

---

# 34. Incident Detection

Potential incidents may be identified through:

- Security monitoring
- Managed antivirus
- User reports
- Administrator observations
- Vulnerability assessments
- Penetration tests
- Authentication activity
- Firewall information
- Cloud-provider notification
- Vendor notification
- Physical-security reports
- Business-process anomalies

---

# 35. Initial Analysis

Initial analysis should determine:

- What occurred
- What may be affected
- Whether malicious activity is continuing
- Whether immediate containment is required
- Whether credentials are affected
- Whether sensitive information is affected
- Whether business operations are affected
- Whether additional expertise is required

---

# 36. Initial Incident Record

The incident record should identify:

- Incident identifier
- Detection date and time
- Detection source
- Initial severity
- Affected assets
- Affected users or accounts
- Initial evidence
- Incident leader
- Current status

---

# 37. Facts and Assumptions

Incident records must distinguish:

- Confirmed facts
- Reasonable conclusions
- Working hypotheses
- Unknown information

Uncertainty must not be concealed.

---

# 38. Scope Determination

Responders must determine the reasonable scope of the incident.

Scope may include:

- Users
- Accounts
- Endpoints
- Servers
- Applications
- Facilities
- Network infrastructure
- Cloud systems
- Third parties
- Business processes
- Information
- Backup systems

---

# 39. Scope Expansion

Investigation must expand when evidence indicates the initial affected system or user is not the full scope.

Responders must not assume an incident is isolated merely because the first detection involved one asset.

---

# 40. Containment

Containment is intended to:

- Stop or limit malicious activity
- Prevent spread
- Protect unaffected systems
- Protect information
- Preserve recovery capability
- Reduce business impact

---

# 41. Containment Decisions

Containment decisions must consider:

- Incident severity
- Threat behavior
- System criticality
- Information sensitivity
- Business impact
- Evidence needs
- Recovery options

---

# 42. Immediate Containment

Authorized personnel may perform reasonable immediate containment when delay would materially increase harm.

Examples include:

- Isolating an endpoint
- Disabling a compromised account
- Blocking malicious traffic
- Restricting a vulnerable service
- Disconnecting an affected system

---

# 43. Containment Authority

Emergency containment does not authorize unrestricted technical changes.

Personnel must remain within their:

- Role
- Access authorization
- Technical authority
- Emergency procedures

Actions beyond normal authority require escalation.

---

# 44. Network Containment

Network containment may include:

- Firewall rules
- Port restrictions
- Device isolation
- VPN restriction
- Malicious destination blocking
- Temporary service restriction

Changes must be documented.

---

# 45. Account Containment

Account containment may include:

- Account disablement
- Password change
- Session termination
- Privileged credential replacement
- Temporary access restriction

Credential changes should be performed from a trusted system.

---

# 46. Privileged Credential Exposure

Potential privileged credential compromise requires heightened response.

Responders must consider:

- Domain Administrator accounts
- Server administration
- Network administration
- Backup administration
- Cloud administration
- Application administration
- Database administration

---

# 47. Domain Administrator Compromise

Confirmed or strongly suspected Domain Administrator compromise requires immediate escalation.

The response must consider:

- Other domain systems
- Privileged-group membership
- Authentication activity
- Persistence
- Credential replacement
- Potential enterprise-wide compromise

---

# 48. Malware Response

Malware incidents must follow [[PROC-009 Malware Response Procedure]].

Malware response includes:

- Triage
- Isolation
- Credential protection
- Evidence preservation
- Scope determination
- Eradication
- Recovery validation

---

# 49. Ransomware Response

Suspected ransomware requires immediate escalation.

Response priorities include:

1. Isolate affected systems.
2. Limit spread.
3. Protect unaffected systems.
4. Protect backup resources.
5. Protect privileged credentials.
6. Preserve useful evidence.
7. Determine scope.
8. Begin recovery planning.

---

# 50. Ransom Decisions

Technical personnel are not authorized to independently approve ransom payment.

Any ransom demand requires escalation to:

- Executive management
- Legal/Compliance
- Other appropriate advisors

Technical response must continue regardless of payment discussions.

---

# 51. Phishing and Credential Compromise

Phishing and credential-compromise incidents must follow [[PBK-001 Phishing & Credential Compromise Playbook]].

Response may include:

- Account protection
- Authentication review
- Email investigation
- Endpoint investigation
- Related-user identification
- Malicious-message containment

---

# 52. Unauthorized Access

Unauthorized-access incidents must follow [[PBK-003 Unauthorized Access Playbook]].

Response must consider:

- Account
- Privilege
- Systems accessed
- Information accessed
- Persistence
- Actions performed
- Scope

---

# 53. Data Exposure

Information-exposure incidents must follow [[PBK-004 Data Exposure Playbook]].

Response must consider:

- Information classification
- Volume
- Recipient
- Exposure duration
- Evidence of acquisition
- Business impact
- Legal or contractual requirements

---

# 54. Third-Party Incidents

Third-party incidents must follow [[PBK-005 Third-Party Incident Playbook]] where applicable.

Dunder Mifflin must determine its own exposure rather than relying solely on the provider's classification.

---

# 55. Infinity Incidents

Infinity incidents require heightened evaluation because the application is:

- Internet facing
- Customer accessible
- Internally developed
- Supported by an external contractor
- Integrated with business processing

---

# 56. Infinity Incident Scope

Infinity investigation may include:

- Web tier
- Application tier
- Database tier
- Authentication
- Administrative access
- Customer information
- Source-code integrity
- Production configuration
- Contractor activity
- Order-processing impact

---

# 57. Infinity Contractor

The Infinity contractor may provide authorized technical support.

The contractor does not control:

- Incident classification
- Risk acceptance
- Evidence disposition
- Incident closure
- Enterprise escalation

---

# 58. Infinity Contractor Access

Incident-response access for the Infinity contractor must follow:

- [[PROC-004 Contractor Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]

An incident does not automatically authorize general contractor VPN access.

---

# 59. Third-Party Confidentiality

Nonemployees receiving sensitive incident information or system access must have an enforceable Non-Disclosure Agreement (NDA) or equivalent confidentiality obligation before access.

The requirement is based on access and information sensitivity rather than vendor title.

---

# 60. Critical Provider Notification

Critical providers are expected to notify Dunder Mifflin of material security incidents within 24 hours of discovery under established third-party requirements.

Such notifications require prompt evaluation.

---

# 61. Retained DFIR Provider

Dunder Mifflin should maintain a retained Digital Forensics and Incident Response (DFIR) provider for incidents exceeding internal capability.

The retained DFIR capability is proposed.

It must not receive current residual-risk or control-effectiveness credit until implemented and available.

---

# 62. DFIR Engagement Criteria

External DFIR support may be appropriate for:

- Significant ransomware
- Complex malware
- Domain compromise
- Significant information exposure
- Complex forensic investigation
- Material legal concerns
- Evidence requirements beyond internal capability

---

# 63. DFIR Authority

The DFIR provider operates under Dunder Mifflin authorization.

The provider must comply with applicable:

- Confidentiality
- Access
- Evidence
- Third-party security
- Incident-response requirements

---

# 64. Evidence Preservation

Incident evidence must be handled according to [[PROC-011 Evidence Handling Procedure]].

Evidence may include:

- Logs
- Emails
- Files
- Malware samples
- Authentication records
- Firewall information
- Screenshots
- System configuration
- User reports
- Third-party reports

---

# 65. Evidence Before Remediation

Where practical, useful evidence should be collected before:

- Malware removal
- Reimaging
- Account deletion
- Configuration replacement
- Log clearing
- Device disposal

Immediate containment may take priority when waiting would materially increase harm.

---

# 66. Evidence Integrity

Personnel must not:

- Fabricate evidence.
- Alter evidence to support a preferred conclusion.
- Backdate evidence records.
- Delete material evidence without authorization.
- Conceal evidence gaps.
- Falsify timelines.
- Represent unverified evidence as verified.

---

# 67. Cryptographic Hashing

Where practical and useful, significant digital evidence should receive a SHA-256 cryptographic hash.

The hash supports integrity verification.

---

# 68. Incident Timeline

Significant incidents must maintain a timeline sufficient to reconstruct material activities.

The timeline may include:

- Initial activity
- Detection
- Escalation
- Classification
- Containment
- Evidence collection
- Eradication
- Recovery
- Notifications
- Major decisions
- Closure

---

# 69. Unknown Times

Unknown or approximate incident times must be identified as such.

Responders must not invent exact timestamps.

---

# 70. Eradication

Eradication removes the malicious condition and addresses relevant causes.

Actions may include:

- Malware removal
- System reimaging
- Credential replacement
- Unauthorized-account removal
- Vulnerability remediation
- Configuration correction
- Software update
- Persistence removal

---

# 71. Vulnerability Remediation

Vulnerabilities contributing to an incident must be handled through:

- [[PRO-004 Vulnerability Management Program]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]

Incident containment does not replace permanent remediation.

---

# 72. Configuration Remediation

Configuration weaknesses contributing to an incident must be addressed through:

- [[POL-007 Change & Configuration Management Policy]]
- [[STD-006 Secure Configuration Standard]]

The organization should determine whether the same weakness exists elsewhere.

---

# 73. Emergency Changes

Emergency changes may be performed when normal change timing would create unacceptable risk.

Emergency changes must be documented and reviewed after implementation.

---

# 74. Recovery

Recovery restores trusted systems and business processes.

Recovery must consider:

- Business Impact Analysis (BIA)
- System dependencies
- Backup integrity
- Security configuration
- Credentials
- Data integrity
- Business validation

---

# 75. Recovery Priority

Recovery priority follows:

**Human Safety → Critical → High → Moderate → Low**

Recovery requirements are defined in [[RPT-002 Business Impact Analysis]].

---

# 76. Recovery Time Objective

Recovery decisions must consider applicable Recovery Time Objectives (RTOs).

An incident may require business-continuity action when normal technical recovery cannot meet required timing.

---

# 77. Recovery Point Objective

Recovery decisions involving data must consider applicable Recovery Point Objectives (RPOs).

The selected recovery point must not unnecessarily restore:

- Malware
- Corrupted information
- Compromised configuration

---

# 78. Backup and Recovery

Backup recovery must follow [[PROC-012 Backup & Recovery Procedure]].

The existence of a backup does not establish successful recovery.

Recovery must be validated.

---

# 79. Backup Protection During Incidents

Incidents involving malware, ransomware, privileged compromise, or destructive activity require explicit consideration of:

- Automated backups
- Cloud backups
- External backup drives
- Backup credentials
- Recovery documentation

---

# 80. Business Continuity

An incident may require activation of [[PLN-002 Business Continuity Plan]] when normal business operations cannot continue within acceptable limits.

---

# 81. Disaster Recovery

An incident may require activation of [[PLN-003 Disaster Recovery Plan]] when significant technology recovery is required.

Incident response and disaster recovery may operate concurrently.

---

# 82. Cloud Exit and Emergency Migration

A material cloud incident may require consideration of [[PLN-004 Cloud Exit & Emergency Migration Plan]].

Dunder Mifflin does not maintain a continuously running alternate cloud environment.

---

# 83. Manual Processing

When systems are unavailable, authorized manual procedures may be used under [[PROC-013 Manual Processing Procedure]].

The manual lifecycle is:

**Collect → Review → Enter → Reconcile → Verify**

---

# 84. Facility Loss

An incident affecting Scranton Headquarters does not automatically eliminate enterprise technology capability because major systems are cloud hosted.

Response must still address:

- Personnel
- Communications
- Management coordination
- Local equipment
- Printed recovery documentation
- Alternate work arrangements

---

# 85. Regional Event

A regional event may require simultaneous:

- Incident response
- Business continuity
- Disaster recovery
- Personnel accountability
- Supplier coordination
- Alternate communication

Safety remains the first priority.

---

# 86. System Recovery Validation

A recovered system must not return to normal operation merely because it starts successfully.

Validation should consider:

- Security configuration
- Malware status
- Required updates
- Authentication
- Logging
- Application functionality
- Data integrity
- Network connectivity

---

# 87. Business Recovery Validation

The responsible business owner or qualified representative should confirm that restored business functionality is acceptable for normal operation.

Technical recovery alone does not establish complete business recovery.

---

# 88. Return-to-Service Decision

Return to service requires reasonable confidence that:

- Immediate threat activity has been addressed.
- Required containment is complete.
- Required credentials are protected.
- Material vulnerabilities have been addressed or appropriately mitigated.
- Recovery is validated.
- Required monitoring is available.

---

# 89. Heightened Monitoring

Recovered systems may receive heightened monitoring when incident risk warrants.

Monitoring should focus on indicators relevant to the incident.

---

# 90. Failed Recovery

A failed recovery attempt must be documented.

The response must determine whether to:

- Retry
- Use another backup
- Rebuild
- Activate additional continuity measures
- Escalate recovery support

---

# 91. Incident Communications

Incident communications must be:

- Timely
- Accurate
- Fact based
- Appropriate to the recipient
- Limited according to legitimate need

---

# 92. Initial Management Notification

Initial management notification should communicate available:

- Incident
- Severity
- Detection time
- Affected systems or processes
- Current business impact
- Containment
- Major uncertainties
- Decisions required

Complete investigation is not required before notification.

---

# 93. Status Updates

Significant incidents require periodic status updates appropriate to:

- Severity
- Rate of change
- Business impact
- Management needs

Material changes should be communicated promptly.

---

# 94. Severity 1 Communications

Severity 1 communications must include appropriate:

- CIO
- CEO
- Incident Response Team members
- Affected business leadership
- Legal/Compliance where applicable

---

# 95. Severity 2 Communications

Severity 2 communications must include:

- IT & Information Security Manager
- CIO
- Appropriate business management
- Other required functions

CEO notification depends on material enterprise impact.

---

# 96. Out-of-Band Communication

When normal company communication may be compromised or unavailable, responders should use an appropriate alternate method.

Company-issued phones and cellular service may support alternate communications where available.

---

# 97. Personal Phones

Personal phones may be used for urgent safety or contact purposes when normal communication is unavailable.

They are not the normal baseline for transmitting sensitive company information.

---

# 98. Customer Communication

Customer communication about a significant incident requires authorization and coordination with appropriate management and Legal/Compliance.

Technical personnel must not independently issue external incident statements.

---

# 99. Public Communication

Public statements regarding incidents require executive authorization.

Unauthorized public disclosure of incident information is prohibited.

---

# 100. Media Inquiries

Media inquiries related to an incident must be referred to authorized company leadership.

Technical personnel should not speculate or provide unofficial statements.

---

# 101. Law Enforcement

Law-enforcement involvement should normally be coordinated with:

- Executive management
- Legal/Compliance
- Incident leadership

Immediate threats to human safety may require direct emergency contact.

---

# 102. Insurance

Where applicable, management should evaluate whether an incident requires notification to the company's insurance provider.

Notification decisions must follow applicable policy terms and management authority.

---

# 103. Decision Log

Significant incidents should maintain a record of material decisions.

The record should identify:

- Decision
- Date and time
- Decision maker
- Available information
- Reason
- Required follow-up

---

# 104. Major Decision Examples

Material decisions may include:

- System shutdown
- Major network isolation
- Business-continuity activation
- Disaster-recovery activation
- External DFIR engagement
- Customer communication
- Law-enforcement contact
- Major recovery strategy
- Risk acceptance

---

# 105. Incident Documentation

Incident documentation should be sufficient for a qualified person unfamiliar with the incident to understand:

- What occurred
- What was affected
- What actions were taken
- Why significant decisions were made
- How recovery occurred
- What remains unresolved

---

# 106. Incident Record Protection

Incident records must be protected according to:

- Information classification
- Investigation sensitivity
- Legitimate need
- Evidence requirements

---

# 107. Incident Classification Changes

All material severity changes must remain visible in incident history.

The current severity must not overwrite the fact that a different initial classification existed.

---

# 108. Incident Closure Criteria

An incident may be closed when:

- Active threat activity has been addressed.
- Required containment is complete.
- Required eradication is complete.
- Required recovery is complete.
- Business validation is complete where applicable.
- Material evidence is preserved.
- Required notifications are complete.
- Outstanding corrective actions are documented.
- Remaining risk is understood.

---

# 109. Closure Does Not Mean All Work Is Finished

Incident closure does not automatically close:

- Vulnerability findings
- Corrective actions
- Risk treatments
- Recovery improvements
- Training improvements
- Policy changes
- Third-party remediation

These items remain tracked through their respective processes.

---

# 110. Severity 1 Closure

Severity 1 incidents require formal management review before final closure.

The review should confirm:

- Response completion
- Recovery status
- Evidence preservation
- Remaining risk
- Corrective actions
- Required follow-up

---

# 111. Severity 2 Closure

Severity 2 incidents require review by the IT & Information Security Manager and appropriate management.

Material unresolved issues must remain tracked.

---

# 112. Severity 3 and Severity 4 Closure

Severity 3 and Severity 4 incidents may use proportionate closure procedures.

Required records and outstanding actions must still be preserved.

---

# 113. Lessons Learned

Severity 1 and significant Severity 2 incidents require a documented lessons-learned review.

Other incidents may receive a lessons-learned review when useful.

---

# 114. Lessons-Learned Timing

Lessons learned should occur after sufficient stabilization and recovery to permit meaningful review.

The review should occur while relevant facts remain reasonably available.

---

# 115. Lessons-Learned Participants

Participants should reflect the incident and may include:

- Incident responders
- IT & Information Security Manager
- CIO
- Business owner
- Human Resources
- Finance
- Operations
- Legal/Compliance
- External specialists

---

# 116. Lessons-Learned Questions

The review should consider:

- How was the incident detected?
- Was escalation appropriate?
- Was classification appropriate?
- Was containment effective?
- Was evidence sufficient?
- Was communication effective?
- Was recovery effective?
- Did controls operate as expected?
- What delayed response?
- What should change?

---

# 117. No-Blame Technical Review

Lessons learned should focus on:

- Facts
- Decisions
- Controls
- Processes
- Dependencies
- Improvement

Personnel misconduct may require separate Human Resources or Legal/Compliance handling.

---

# 118. Root Cause

Where evidence permits, significant incidents should identify likely root cause.

Potential root causes include:

- Phishing
- Vulnerability
- Configuration weakness
- Excessive privilege
- Credential compromise
- Third-party compromise
- Human error
- Process weakness

---

# 119. Contributing Factors

Contributing factors should be identified separately from root cause.

Examples include:

- Delayed detection
- Missing logs
- Excessive access
- Weak recovery preparation
- Incomplete documentation
- Inadequate segmentation
- Insufficient awareness

---

# 120. Corrective Action

Required corrective action must identify:

- Deficiency
- Accountable owner
- Required action
- Due date
- Validation method

Material corrective actions are maintained in [[REG-004 Finding & Corrective Action Register]].

---

# 121. Corrective-Action Ownership

Every material corrective action must have one accountable owner.

Shared participation may be documented, but accountability must not be ambiguous.

---

# 122. Corrective-Action Validation

Corrective action is not complete merely because an owner reports that work was performed.

Required validation must determine whether the intended condition was achieved.

---

# 123. Recurring Incidents

Repeated incidents of the same or similar type require broader review.

Recurrence may indicate:

- Incomplete remediation
- Control weakness
- Inadequate monitoring
- Training weakness
- Vulnerability-management failure
- Configuration-management failure
- Risk underestimated

---

# 124. Risk Reassessment

A significant incident may require reassessment of related enterprise risks.

Reassessment may be appropriate when evidence demonstrates:

- Greater likelihood
- Greater impact
- Control failure
- New attack path
- Unexpected dependency
- Recovery weakness
- Improved control effectiveness

---

# 125. Historical Risk Integrity

Risk reassessment must preserve the historical May 2013 risk assessment.

A new validated risk result must not silently replace the original assessment.

---

# 126. Target Residual Risk

Target residual risk is a prediction of expected risk after treatment.

An incident may demonstrate that:

- The treatment is incomplete.
- The control is less effective than expected.
- The target requires revision.

Target residual risk must not be treated as a guaranteed floor or outcome.

---

# 127. Current and Proposed Controls

Incident records must distinguish among:

- Current controls
- Partially implemented controls
- Planned controls
- Implemented controls awaiting validation
- Validated controls

---

# 128. No Premature Risk Credit

Current residual risk must not be reduced merely because:

- This plan exists.
- A playbook exists.
- A DFIR provider is proposed.
- An exercise is planned.
- A control is purchased.
- A corrective action is assigned.

Risk reduction requires implementation and appropriate validation.

---

# 129. Incident Metrics

Incident metrics may include:

- Incidents by severity
- Incidents by category
- Severity 1 incidents
- Severity 2 incidents
- Incidents requiring IRT activation
- Incidents requiring executive notification
- Repeat incidents
- Incidents involving privileged compromise
- Incidents involving third parties
- Incidents requiring business-continuity activation

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 130. Response Performance Metrics

Response-performance metrics may include:

- Time from detection to escalation
- Time from escalation to containment
- Incidents with documented scope
- Incidents with complete required evidence
- Incidents with required closure review
- Corrective actions assigned
- Repeat incidents

Metrics must be interpreted in context.

---

# 131. Metric Integrity

Incident metrics must not be manipulated by:

- Delaying incident declaration
- Lowering severity without evidence
- Closing incidents prematurely
- Altering timestamps
- Excluding material incidents without justification

---

# 132. Operational Reporting

Operational incident reporting should provide:

- Incident identifier
- Severity
- Affected assets
- Technical evidence
- Containment
- Recovery status
- Required actions
- Exceptions

---

# 133. Management Reporting

Management incident reporting should focus on:

- Accountability
- Business impact
- Response performance
- Corrective actions
- Resource requirements
- Recurring causes

---

# 134. Executive Reporting

Executive incident reporting should focus on:

- Enterprise impact
- Major business interruption
- Significant information exposure
- Material financial impact
- Major recovery concerns
- Enterprise risk
- Decisions required

---

# 135. Reporting Principle

Incident reporting follows:

**Operational → Execution, Evidence, Exceptions, Technical Detail**

**Management → Accountability, Performance, Action**

**Executive → Decisions and Enterprise Risk**

---

# 136. Reporting Chain

Incident information should support:

**Technical Evidence → Operational Exception → Management Impact → Enterprise Risk → Executive Decision**

---

# 137. Incident Exercises

The incident-response program must conduct periodic exercises.

Exercises may include:

- Tabletop exercises
- Technical exercises
- Communication exercises
- Recovery exercises
- Cross-functional scenarios

---

# 138. Exercise Scenarios

Exercise scenarios may include:

- Phishing and credential compromise
- Business Email Compromise
- Ransomware
- Unauthorized privileged access
- Infinity compromise
- Third-party compromise
- Sensitive information exposure
- Backup compromise

---

# 139. Exercise Safety

Exercises must be designed to avoid unnecessary:

- Production disruption
- Data loss
- Customer impact
- Security exposure

Exercise activity must be clearly distinguished from actual malicious activity where appropriate.

---

# 140. Exercise Evidence

Exercise records should identify:

- Scenario
- Participants
- Objectives
- Actions
- Decisions
- Observed gaps
- Corrective actions

---

# 141. Incident Response Assessment

Incident-response controls must be periodically assessed.

Assessment should determine whether:

- Incidents are identified.
- Escalation occurs.
- Classification is appropriate.
- Response roles are understood.
- Evidence is preserved.
- Recovery is validated.
- Corrective action is tracked.

---

# 142. Assessment Methods

Assessment methods may include:

- Inspection
- Observation
- Interviews
- Sampling
- Exercises
- Technical Testing
- Reconciliation
- Independent Performance

The method must match the control being evaluated.

---

# 143. Incident Sampling

An assessor may sample incident records and determine whether:

- Classification was appropriate.
- Escalation occurred.
- Required personnel participated.
- Containment was documented.
- Evidence was preserved.
- Recovery was validated.
- Closure requirements were satisfied.

---

# 144. Severity 1 Assessment

An assessor may select Severity 1 incidents and determine whether:

- CIO notification occurred.
- CEO notification occurred.
- Incident Response Team activation occurred.
- Cross-functional participation was appropriate.
- Closure review occurred.
- Corrective actions were identified.

---

# 145. Independent Performance

An assessor may independently perform selected incident-response activities within an authorized exercise or assessment.

For example, the assessor may:

1. Receive a simulated security scenario.
2. Apply escalation criteria.
3. Classify the incident.
4. Identify required responders.
5. Identify required containment.
6. Identify evidence requirements.
7. Compare the result with documented procedures.

---

# 146. Assessment Exceptions

Incident-response assessment exceptions must be investigated.

Potential causes include:

- Missing documentation
- Incorrect classification
- Delayed escalation
- Unclear roles
- Inadequate evidence
- Failed communication
- Recovery weakness
- Training deficiency

---

# 147. Findings

Material incident-response deficiencies must be documented.

Examples include:

- Severity 1 incident not escalated
- Required executive notification omitted
- Significant evidence deliberately destroyed
- Incident closed without required recovery validation
- Material corrective action not assigned
- Incident records falsified
- Recurring incident not investigated
- Required Incident Response Team activation omitted

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 148. Plan Effectiveness

Evidence may support conclusions that incident-response controls are:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

The conclusion must reflect actual operation rather than documentation alone.

---

# 149. Risk Relationships

This plan provides response and treatment support across the enterprise risk portfolio, particularly:

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

Not every event associated with these risks is a security incident.

---

# 150. Traceability

This plan supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Incident-response records must preserve traceability from detection through escalation, classification, response, recovery, findings, corrective action, validation, and risk reassessment.

---

# 151. Related Artifacts

- [[PRO-005 Security Operations Program]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-006 Security Awareness & Training Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-011 Physical & Environmental Security Policy]]
- [[STD-001 Information Classification Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[STD-007 Penetration Testing Standard]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]
- [[PROC-008 Security Monitoring Procedure]]
- [[PROC-009 Malware Response Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-013 Manual Processing Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]
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
- [[RPT-006 Executive Security Summary]]
- [[RPT-007 Management Security Report]]
- [[RPT-008 Operational Security Report & Dashboard]]

---

# 152. Plan Maintenance

This plan must be reviewed:

- At least annually
- Following a Severity 1 incident
- Following a material incident-response failure
- Following significant organizational change
- Following significant technology change
- Following material legal or contractual change
- Following significant assurance findings

The CIO coordinates plan maintenance.

Material revisions require CEO approval.

---

# 153. Revision History

| Version | Date     | Description                    | Approval |
| ------- | -------- | ------------------------------ | -------- |
| 1.0     | May 2013 | Initial Incident Response Plan | CEO      |