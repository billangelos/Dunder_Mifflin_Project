# PBK-004 Data Exposure Playbook

## Document Control

| Field | Value |
|---|---|
| Document ID | PBK-004 |
| Title | Data Exposure Playbook |
| Version | 1.0 |
| Classification | Confidential |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following a Material Data-Exposure Incident |

---

# 1. Purpose

This playbook provides operational guidance for responding to suspected or confirmed unauthorized disclosure, access, acquisition, transmission, loss, or exposure of Dunder Mifflin information.

It supplements:

- [[STD-001 Information Classification Standard]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[PLN-001 Incident Response Plan]]

with focused response actions for information-exposure incidents.

---

# 2. Scope

This playbook applies to company information exposed through:

- Email
- File systems
- Endpoints
- Lost or stolen devices
- Business applications
- Infinity
- Cloud-hosted systems
- Backup media
- Removable media
- Printed records
- Third parties
- Contractors
- Unauthorized accounts
- Misconfigured systems
- Physical loss
- Improper disposal
- Accidental disclosure
- Malicious activity

---

# 3. Data Exposure

A data exposure occurs when information is or may have been:

- Accessed without authorization
- Disclosed to an unauthorized party
- Sent to an unintended recipient
- Made available beyond approved access
- Acquired by an unauthorized party
- Lost without adequate protection
- Improperly published
- Improperly disposed of
- Extracted from a compromised system

---

# 4. Exposure Versus Confirmed Acquisition

The response must distinguish between:

- Information that was potentially accessible
- Information confirmed as viewed
- Information confirmed as transmitted
- Information confirmed as acquired
- Information confirmed as modified
- Information confirmed as deleted
- Information whose disposition remains unknown

Potential access must not automatically be described as confirmed acquisition or exfiltration.

---

# 5. Authority

This playbook operates under:

- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[STD-001 Information Classification Standard]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[PLN-001 Incident Response Plan]]

---

# 6. Objectives

Data-exposure response must:

1. Protect human safety.
2. Stop or limit continued exposure.
3. Identify affected information.
4. Determine information classification.
5. Determine reasonable incident scope.
6. Identify affected systems and accounts.
7. Preserve useful evidence.
8. Determine whether information was accessed, acquired, altered, or disclosed where evidence permits.
9. Protect affected credentials where necessary.
10. Coordinate Legal/Compliance review.
11. Support authorized notification decisions.
12. Restore secure information handling.
13. Identify corrective action.
14. Support risk reassessment where appropriate.

---

# 7. Response Lifecycle

The data-exposure response lifecycle is:

**Detect / Report → Triage → Contain → Preserve Evidence → Classify Information → Determine Scope → Investigate → Assess Impact → Recover → Notification Decision → Validate → Close → Improve**

Activities may overlap when necessary.

---

# 8. Safety Priority

Human life and safety take priority over:

- Evidence
- Information
- Systems
- Operations
- Facilities
- Equipment
- Inventory
- Revenue

Emergency action must not be delayed solely to preserve evidence.

---

# 9. Information Classification

Dunder Mifflin uses four information classifications:

- Public
- Internal
- Confidential
- Restricted

Classification requirements are defined in [[STD-001 Information Classification Standard]].

---

# 10. Public Information

Exposure of information properly classified as Public normally does not constitute a confidentiality incident.

The event may still require investigation when it indicates:

- Unauthorized system access
- Integrity compromise
- Improper publication
- Other security weakness

---

# 11. Internal Information

Unauthorized exposure of Internal information requires evaluation based on:

- Content
- Recipient
- Scope
- Business impact
- Method of exposure

---

# 12. Confidential Information

Exposure of Confidential information requires heightened evaluation.

Examples may include:

- Customer information
- Employee information
- Financial information
- Contracts
- Business-sensitive records
- Authentication-related information

---

# 13. Restricted Information

Exposure of Restricted information requires immediate escalation.

Restricted information represents information requiring the highest level of protection within the classification framework.

---

# 14. Classification Uncertainty

If classification is unclear, responders should temporarily handle the information at the higher reasonable classification until ownership and classification can be confirmed.

---

# 15. Backups

Backup information inherits the highest classification of the information contained within it.

A lost or exposed backup must be evaluated based on its contents rather than being treated as ordinary media.

---

# 16. Payment Card Information

Dunder Mifflin's normal payment architecture does not retain payment card Primary Account Numbers (PANs).

The company retains processor-related information such as:

- Payment token
- Card brand
- Last four digits
- Expiration information

---

# 17. Unexpected PAN Discovery

Discovery or exposure of full payment card PAN information requires immediate escalation.

Responders must not assume that unexpected PAN data is authorized merely because it exists in a company system.

---

# 18. Detection Sources

Potential data exposure may be identified through:

- Employee report
- Customer report
- Third-party notification
- Lost-device report
- Security monitoring
- Unauthorized-access investigation
- Malware investigation
- Email error
- File-permission review
- Application-security assessment
- Physical-security report
- Backup incident
- Administrator observation

---

# 19. Initial Triage

The responder should determine:

- What information may be affected?
- What classification applies?
- How did exposure occur?
- Who may have received or accessed it?
- When did exposure begin?
- Is exposure continuing?
- What systems are involved?
- What accounts are involved?
- Can exposure be contained?
- Is immediate escalation required?

---

# 20. Event Versus Incident

A suspected exposure may initially remain a security event while facts are established.

Formal incident response is required when evidence indicates or reasonably suggests unauthorized exposure of protected company information or another material security impact.

---

# 21. Incident Classification

Formal incidents must be classified according to [[STD-008 Incident Classification & Escalation Standard]].

Classification must consider:

- Information classification
- Volume
- Number of affected individuals or organizations
- Recipient
- Duration
- Method of exposure
- Business impact
- Legal or contractual significance
- Whether exposure continues
- Whether privileged compromise is involved

---

# 22. Immediate Escalation Conditions

Immediate escalation is required when the event involves or reasonably suggests:

- Restricted information
- Significant Confidential information
- Full payment card information
- Significant employee information
- Significant customer information
- Large-scale exposure
- Public Internet exposure of protected information
- Malicious acquisition
- Extortion
- Significant privileged compromise
- Significant third-party exposure

---

# 23. Initial Containment

Containment should stop or limit continued exposure.

Actions may include:

- Removing public access
- Correcting file permissions
- Disabling an account
- Terminating a session
- Recalling or removing a message where possible
- Restricting a shared resource
- Isolating a compromised system
- Blocking malicious access
- Recovering physical records or media
- Suspending third-party access

---

# 24. Containment Before Complete Scope

Responders do not need complete incident scope before taking reasonable action to stop an active exposure.

Containment must not be delayed solely to obtain perfect certainty.

---

# 25. Preserve Evidence Before Change

Where practical, responders should preserve useful evidence before:

- Changing permissions
- Deleting files
- Removing public access
- Disabling accounts
- Reconfiguring applications
- Reimaging systems
- Deleting messages

Immediate containment may take priority when waiting materially increases harm.

---

# 26. Evidence Handling

Evidence must be handled according to [[PROC-011 Evidence Handling Procedure]].

Material evidence should remain traceable to the incident.

---

# 27. Evidence Sources

Data-exposure evidence may include:

- Authentication logs
- Access logs
- File permissions
- Email
- Application logs
- Firewall information
- System configuration
- Screenshots
- Files
- Backup records
- Physical access records
- User statements
- Third-party reports
- Customer reports

---

# 28. Cryptographic Hashing

Where practical and useful, significant digital evidence should receive a SHA-256 cryptographic hash.

---

# 29. Incident Timeline

Significant data-exposure incidents must maintain a timeline sufficient to reconstruct material activity.

The timeline may include:

- Initial exposure
- Access
- Detection
- Reporting
- Containment
- Evidence collection
- Classification
- Investigation
- Recovery
- Notification decisions
- Closure

---

# 30. Unknown Times

Unknown or approximate times must be documented as such.

Responders must not create false precision.

---

# 31. Scope Determination

The responder must determine reasonable incident scope.

Scope may include:

- Information
- Files
- Records
- Accounts
- Endpoints
- Servers
- Applications
- Cloud systems
- Infinity
- Backups
- Third parties
- Physical records
- Affected individuals
- Affected customers

---

# 32. Information Identification

Responders should determine:

- Information owner
- Information classification
- Type of information
- Approximate quantity
- Location
- Business purpose
- Applicable retention
- Affected individuals or organizations where relevant

---

# 33. Volume

Information volume should be described using supportable facts.

If exact volume cannot be established, responders should document a reasonable range or state that the amount remains unknown.

---

# 34. Recipient Identification

Where practical, responders should determine who received or could access the information.

Recipients may include:

- Employee
- Contractor
- Customer
- Vendor
- Unknown external party
- Public Internet users
- Malicious actor

---

# 35. Recipient Authorization

A known recipient is not automatically an authorized recipient.

The responder must determine whether the recipient had legitimate need and authorization for the information.

---

# 36. Exposure Duration

The responder should determine how long information remained exposed where evidence permits.

If the start or end time is unknown, the uncertainty must be documented.

---

# 37. Access Versus Availability

Information being technically available to an unauthorized party does not prove that the party accessed it.

The response record must distinguish availability from confirmed access.

---

# 38. Access Versus Acquisition

Evidence of unauthorized access does not automatically prove that information was copied, downloaded, photographed, or otherwise acquired.

---

# 39. Exfiltration

The term "exfiltration" should be used when evidence reasonably supports unauthorized transfer of information from company control.

It should not be used merely because information was accessible.

---

# 40. Modification

Responders must determine whether exposed information was also modified.

Unauthorized modification may create an integrity incident in addition to a confidentiality incident.

---

# 41. Deletion

Responders must determine whether information was deleted or destroyed.

Deletion may create availability, recovery, or record-retention concerns.

---

# 42. Unauthorized Account Access

If exposure resulted from account compromise, response must also follow:

- [[PBK-001 Phishing & Credential Compromise Playbook]]
- [[PBK-003 Unauthorized Access Playbook]]

as applicable.

---

# 43. Malware-Related Exposure

If malware may have accessed or transmitted information, response must also follow:

- [[PROC-009 Malware Response Procedure]]
- [[PBK-002 Malware & Ransomware Playbook]]

---

# 44. Ransomware and Extortion

A ransomware actor may claim that information was stolen.

Such claims must be evaluated as potential data exposure.

The claim must not automatically be treated as proven or false.

---

# 45. Credential Exposure

If exposed information includes passwords, authentication secrets, or other usable credentials, responders must protect affected accounts promptly.

Credential replacement should occur from a trusted system.

---

# 46. Privileged Credential Exposure

Exposure of privileged credentials requires immediate escalation.

Responders must determine:

- Accounts affected
- Systems administered
- Privilege level
- Related authentication activity
- Whether unauthorized use occurred

---

# 47. Lost Laptop

A lost company laptop requires evaluation of:

- Full-disk encryption status
- Authentication
- Information stored locally
- User privilege
- Remote-management capability
- Last known location
- Account exposure

---

# 48. Full-Disk Encryption

Company laptops are intended to use full-disk encryption.

Verified full-disk encryption may materially reduce confidentiality risk when a powered-off device is lost, but the responder must still evaluate:

- Device state
- Credential exposure
- Encryption status
- Other available evidence

---

# 49. Lost Company Phone

A lost company phone requires evaluation of:

- Device-management enrollment
- Passcode protection
- Company information
- Account access
- Remote lock capability
- Remote wipe capability where available

---

# 50. Remote Lock and Wipe

Remote lock or wipe may be used where supported and appropriate.

The responder should document:

- Action requested
- Time
- Result
- Whether the device confirmed the action

A requested remote wipe must not be represented as successful unless confirmation is available.

---

# 51. Removable Media

Lost or exposed removable media requires evaluation of:

- Information stored
- Classification
- Encryption
- Custody
- Last known location
- Likely recipient

---

# 52. Backup Media

Exposure involving backup media requires heightened evaluation because backups may contain information from multiple systems or classifications.

The encrypted external hard-drive rotation must be considered when relevant.

---

# 53. External Backup Drive Loss

If an external backup drive is lost, responders must determine:

- Facility represented
- Backup generation
- Encryption status
- Information contained
- Custody history
- Whether recovery capability is affected

---

# 54. Off-Site Backup Provider

Exposure involving the off-site Disaster Recovery storage provider requires third-party coordination under [[PBK-005 Third-Party Incident Playbook]].

Dunder Mifflin must independently evaluate company impact.

---

# 55. Email Misdelivery

When protected information is sent to the wrong recipient, responders should determine:

- Recipient
- Information
- Classification
- Whether the message was opened
- Whether attachments were accessed
- Whether deletion can reasonably be requested or verified
- Whether the recipient is trusted

---

# 56. Email Recall

Email recall may be attempted where supported.

A recall attempt must not be represented as successful unless its result is known.

---

# 57. Recipient Deletion Request

An unintended recipient may be asked to:

- Delete the message
- Delete attachments
- Avoid further disclosure
- Confirm deletion

The reliability of this action depends on recipient trust and available evidence.

---

# 58. Sensitive Information in Email

Responders should determine whether the transmission itself violated required information-handling controls.

The incident may identify a broader process weakness even when the unintended recipient cooperates.

---

# 59. File Permission Exposure

If inappropriate file permissions exposed information, responders should:

1. Preserve relevant permission evidence.
2. Correct unauthorized access.
3. Identify affected files.
4. Determine who could access them.
5. Review available access evidence.
6. Evaluate similar permissions elsewhere.

---

# 60. Shared Folder Exposure

A shared folder with excessive permissions may expose multiple records.

Scope must not be limited to the first file reported.

---

# 61. Public Internet Exposure

Protected company information accessible from the public Internet requires immediate containment.

Responders should determine:

- Information exposed
- Duration
- Access method
- Whether authentication was absent or bypassed
- Available access evidence
- Search or indexing exposure where relevant
- Corrective action

---

# 62. Cloud Exposure

Cloud-related data exposure requires evaluation of:

- Company configuration
- Provider responsibility
- Administrative access
- Available logs
- Sharing configuration
- Authentication
- Information
- Third-party involvement

---

# 63. Cloud Provider Responsibility

Cloud hosting does not eliminate Dunder Mifflin's responsibility to determine:

- Company impact
- Information affected
- Business consequences
- Required company actions

---

# 64. Infinity Exposure

Potential Infinity data exposure requires evaluation of:

- Customer information
- Order information
- Payment tokens
- Application records
- Administrative data
- Application logs
- Web tier
- Application tier
- Database tier

---

# 65. Infinity Database

The Infinity database is not intended to be directly Internet accessible.

Evidence that the database was directly exposed or accessed without authorization requires immediate escalation.

---

# 66. Infinity Contractor

Potential exposure involving the Infinity contractor requires evaluation of:

- Authorized access
- Actual access
- Source-code access
- Production access
- Customer information
- Administrative privilege
- Contractual confidentiality requirements

---

# 67. Source-Code Exposure

Unauthorized disclosure of Infinity source code requires evaluation of:

- Repository access
- Files affected
- Recipient
- Intellectual property impact
- Credential exposure
- Potential application-security impact

---

# 68. Third-Party Exposure

When a third party reports a data exposure affecting Dunder Mifflin, responders must determine:

- Provider
- Services involved
- Company information involved
- Incident timeline
- Exposure mechanism
- Containment status
- Available evidence
- Provider corrective action

---

# 69. Independent Company Assessment

Dunder Mifflin must not rely solely on a provider's statement that an incident is resolved.

The company must determine its own:

- Information impact
- Business impact
- Required account actions
- Required continuity actions
- Remaining risk

---

# 70. Third-Party Notification Timing

Critical third parties are expected to notify Dunder Mifflin of qualifying security incidents within 24 hours of discovery as established by [[POL-008 Third-Party Security Policy]].

---

# 71. Third-Party Confidentiality

Nonemployees receiving sensitive company information must have an enforceable Non-Disclosure Agreement (NDA) or equivalent confidentiality obligation before access.

The requirement is based on access and sensitivity rather than vendor title.

---

# 72. NDA Limitations

An NDA does not establish that:

- Access controls are effective.
- The provider is technically secure.
- Monitoring is adequate.
- The incident did not occur.
- Corrective action is effective.

Confidentiality obligations complement technical and administrative controls.

---

# 73. Printed Information

Exposure of printed records requires evaluation of:

- Information classification
- Quantity
- Location
- Custody
- Recipient
- Whether copies may exist
- Whether records can be recovered

---

# 74. Improper Disposal

Improperly discarded protected information must be recovered where practical.

The response should determine:

- Information involved
- Disposal method
- Exposure duration
- Potential recipients
- Whether other records were disposed of similarly

---

# 75. Physical Theft

Theft of records, devices, or media may create both physical-security and information-security incidents.

Response should coordinate with applicable physical-security procedures.

---

# 76. Physical Access Relationship

If information exposure resulted from unauthorized physical access, responders should coordinate with:

- [[PROC-014 Facility Access Procedure]]
- [[PROC-015 Visitor & Vendor Access Procedure]]
- [[PROC-016 Restricted Area Access Procedure]]

when applicable.

---

# 77. Internal Accidental Disclosure

Accidental disclosure by an authorized employee must still be evaluated as a security incident when protected information reaches an unauthorized recipient.

Intent does not determine whether exposure occurred.

---

# 78. Malicious Insider Disclosure

Suspected intentional disclosure by an employee requires coordination with:

- Human Resources
- Legal/Compliance
- Information Security
- Relevant management

Technical personnel should preserve facts and evidence without making personnel conclusions outside their authority.

---

# 79. Customer Information

Exposure involving customer information requires determination of:

- Information type
- Classification
- Customer or customers affected
- Quantity
- Contractual considerations
- Business impact

---

# 80. Employee Information

Exposure involving employee information requires coordination with Human Resources when appropriate.

Responders should minimize additional disclosure during investigation.

---

# 81. Financial Information

Exposure involving financial information requires Finance involvement when appropriate.

Examples may include:

- Banking information
- Payment information
- Accounting records
- Payroll information
- Vendor financial information

---

# 82. Legal Information

Exposure involving legal or privileged material requires prompt Legal/Compliance involvement.

Responders should limit unnecessary distribution of the affected material.

---

# 83. Information Minimization During Investigation

Incident responders should collect and distribute only the information reasonably necessary for response.

An investigation must not unnecessarily create additional copies of sensitive information.

---

# 84. Evidence Copies

Evidence copies containing protected information must be:

- Limited
- Controlled
- Identified
- Protected according to classification
- Disposed of appropriately when no longer required

---

# 85. Screenshots

Screenshots should be used only when they provide useful evidence.

Screenshots containing sensitive information must be protected according to the information shown.

---

# 86. User Statements

User statements may provide important context.

The incident record must distinguish user-reported information from independently verified technical evidence.

---

# 87. Third-Party Statements

Third-party statements should identify:

- Source
- Date
- Provider
- Relevant facts
- Known limitations

Third-party conclusions must not automatically replace Dunder Mifflin's own assessment.

---

# 88. Notification Assessment

Potential notification obligations must be evaluated with Legal/Compliance.

The assessment may consider:

- Information type
- Affected individuals
- Location
- Contractual obligations
- Applicable law
- Evidence of acquisition
- Risk of harm
- Protective controls

---

# 89. Technical Personnel and Notification Decisions

Technical personnel provide:

- Facts
- Evidence
- Scope
- System information
- Security analysis

They do not independently determine legal notification obligations.

---

# 90. Customer Notification

Customer notification requires appropriate authorization.

Technical personnel must not independently notify customers of a data exposure unless specifically directed through the incident-response process.

---

# 91. Employee Notification

Employee notification related to a data exposure should be coordinated with:

- Human Resources
- Legal/Compliance
- Incident leadership

as appropriate.

---

# 92. Regulatory Notification

Any required regulatory notification must be coordinated through Legal/Compliance and authorized management.

---

# 93. Law Enforcement

Law-enforcement involvement should normally be coordinated with:

- Executive management
- Legal/Compliance
- Incident leadership

Immediate safety emergencies may require direct emergency contact.

---

# 94. Public Communication

Public statements must be authorized.

Technical personnel must not independently:

- Issue public statements
- Admit liability
- Speculate about impact
- Provide unsupported incident totals
- Make legal conclusions

---

# 95. Communications Accuracy

Incident communications must distinguish:

- Confirmed facts
- Reasonable conclusions
- Suspected conditions
- Unknown information

Uncertainty should be communicated rather than hidden.

---

# 96. External DFIR Assistance

External Digital Forensics and Incident Response (DFIR) assistance may be appropriate for:

- Significant malicious acquisition
- Complex unauthorized access
- Large-scale exposure
- Significant malware-related exposure
- Complex forensic requirements
- Broad unknown scope

---

# 97. Proposed DFIR Capability

A retained DFIR provider is a proposed Critical Security Response Provider capability.

It receives no current residual-risk or control-effectiveness credit until implemented and available.

---

# 98. Recovery

Recovery from a data-exposure incident focuses on restoring secure information handling.

Actions may include:

- Correcting permissions
- Replacing credentials
- Removing unauthorized sharing
- Reconfiguring systems
- Recovering devices or records
- Rebuilding compromised systems
- Restoring validated information
- Correcting business processes

---

# 99. Access Restoration

Access removed during containment should be restored only when:

- Authorization is confirmed.
- Required credentials are protected.
- Required permissions are correct.
- The underlying weakness is addressed or appropriately mitigated.

---

# 100. Information Integrity

If exposed information may also have been modified, the responsible owner must validate information integrity.

Recovery may require:

- Reconciliation
- Comparison with authoritative records
- Backup restoration
- Business review

---

# 101. Backup Restoration

If information was deleted or corrupted, recovery may require [[PROC-012 Backup & Recovery Procedure]].

The existence of a backup does not establish successful recovery.

---

# 102. Business Validation

The responsible business owner or qualified representative should validate affected business information or processes when integrity or availability was affected.

---

# 103. Containment Validation

Responders must verify that intended containment occurred.

Examples include confirming:

- Public access removed
- Permissions corrected
- Account disabled
- Session terminated
- Shared link disabled
- Device remotely locked
- Third-party access suspended

---

# 104. Failed Containment

If containment fails:

1. Document the failure.
2. Determine why it failed.
3. Reevaluate scope.
4. Escalate where appropriate.
5. Select additional containment.
6. Reassess incident severity.

---

# 105. Heightened Monitoring

Following significant exposure, relevant systems or accounts may receive heightened monitoring.

Monitoring should focus on relevant indicators rather than indiscriminate surveillance.

---

# 106. Recurring Exposure

Repeated exposure after remediation may indicate:

- Incomplete containment
- Excessive permissions
- Process weakness
- Misconfiguration
- Compromised credentials
- Inadequate training
- Third-party control weakness

The incident or corrective action must be reevaluated.

---

# 107. Incident Closure

A data-exposure incident may be closed when:

- Active exposure has been addressed.
- Reasonable scope has been determined.
- Information classification is understood.
- Affected systems and accounts are addressed.
- Required recovery is complete.
- Material evidence is preserved.
- Notification decisions are documented where applicable.
- Required corrective actions are documented.
- Remaining risk is understood.

---

# 108. Closure Does Not Require Proof of Every Unknown

Incident closure does not require impossible certainty.

Material unknowns must be:

- Documented
- Considered in impact assessment
- Considered in notification decisions
- Considered in remaining risk

---

# 109. Closure Does Not End Corrective Action

Incident closure does not automatically close:

- Access-control remediation
- Vulnerability remediation
- Configuration remediation
- Third-party remediation
- Training improvements
- Corrective actions
- Risk treatments

---

# 110. Lessons Learned

Severity 1 and significant Severity 2 data-exposure incidents require a documented lessons-learned review.

The review should consider:

- Cause
- Detection
- Classification
- Containment
- Scope
- Evidence
- Notification assessment
- Recovery
- Control performance
- Corrective action

---

# 111. Root Cause

Where evidence permits, likely root cause should be identified.

Examples include:

- Credential compromise
- Excessive permissions
- Misconfiguration
- Human error
- Malware
- Vulnerability exploitation
- Lost device
- Physical theft
- Third-party compromise
- Improper disposal
- Insider misuse

---

# 112. Contributing Factors

Contributing factors may include:

- Excessive access
- Inadequate classification
- Weak information handling
- Missing encryption
- Incomplete monitoring
- Poor configuration
- Delayed termination
- Inadequate third-party controls
- Insufficient training

---

# 113. Broader Review

A data exposure may indicate a weakness affecting additional systems or information.

Responders should consider whether similar conditions exist across:

- Shared folders
- Applications
- Accounts
- Endpoints
- Cloud systems
- Third parties
- Physical records

---

# 114. Corrective Action

Material deficiencies must identify:

- Deficiency
- Accountable owner
- Required action
- Due date
- Validation method

Material corrective actions are tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 115. Corrective-Action Validation

Corrective action is not complete merely because an action was reported as finished.

Required validation must determine whether the intended condition was achieved.

---

# 116. R009 Relationship

R009 addresses sensitive information theft and extortion.

Inherent risk is:

**16 High**

Current residual risk is:

**12 High**

Target residual risk after proposed treatment is:

**4 Low**

---

# 117. R009 Treatment Support

R009 treatment includes layered:

- Information classification
- Encryption
- Full-disk encryption
- Least privilege
- Physical protection
- Secure disposal
- Confidentiality obligations
- Incident response
- Backup and recovery
- Security awareness

No single control eliminates information-exposure risk.

---

# 118. R010 Relationship

R010 addresses unauthorized or excessive access.

Inherent risk is:

**16 High**

Current residual risk is:

**12 High**

Target residual risk after proposed treatment is:

**4 Low**

Unauthorized access and data exposure may occur together but remain distinct risk concepts.

---

# 119. R014 Relationship

R014 addresses lost devices.

Inherent risk is:

**16 High**

Current residual risk is:

**8 Moderate**

Target residual risk after proposed treatment is:

**4 Low**

Full-disk encryption and mobile-device controls are important exposure-limiting measures.

---

# 120. R018 Relationship

R018 addresses third-party technology failure or compromise.

Inherent risk is:

**12 High**

Current residual risk is:

**8 Moderate**

Target residual risk after proposed treatment is:

**6 Moderate**

---

# 121. R019 Relationship

R019 addresses Infinity contractor dependency and compromise.

Inherent risk is:

**12 High**

Current residual risk is:

**8 Moderate**

Target residual risk after proposed treatment is:

**4 Low**

---

# 122. Other Risk Relationships

This playbook may also support response for:

- R001 Phishing / Credential Compromise
- R002 Business Email Compromise
- R003 Ransomware
- R004 Malware
- R005 Password / Authentication Weakness
- R006 Infinity Application Compromise
- R007 Internet Infrastructure Compromise
- R011 Delayed Termination
- R012 Malicious Insider
- R013 Administrative / Configuration Error
- R024 Physical Access
- R027 Backup / Recovery Failure
- R028 Data Corruption

---

# 123. Current and Proposed Controls

Response records must distinguish among:

- Current controls
- Partially implemented controls
- Planned controls
- Implemented controls awaiting validation
- Validated controls

---

# 124. No Premature Risk Credit

Current residual risk must not be reduced merely because:

- This playbook exists.
- A retained DFIR provider is proposed.
- Additional encryption is planned.
- Access improvements are planned.
- Monitoring improvements are proposed.
- Corrective action has been assigned.

Risk reduction requires implementation and appropriate validation.

---

# 125. Risk Reassessment

Data-exposure incidents may require risk reassessment when evidence demonstrates:

- Greater likelihood
- Greater impact
- Information-handling weakness
- Access-control failure
- Encryption weakness
- Third-party weakness
- New exposure path
- Improved control effectiveness

Historical May 2013 risk results must remain preserved.

---

# 126. Operational Metrics

Operational metrics may include:

- Data-exposure events
- Confirmed data-exposure incidents
- Confidential information exposures
- Restricted information exposures
- Lost-device exposures
- Third-party exposures
- Accidental disclosures
- Malicious disclosures
- Repeat exposure incidents

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 127. Key Performance Indicators

Key Performance Indicators (KPIs) may include:

- Percentage of confirmed exposures receiving documented containment
- Percentage of significant exposures with documented scope
- Percentage of incidents with classification confirmed
- Percentage of required notification assessments completed
- Percentage of material corrective actions completed and validated

---

# 128. Key Risk Indicators

Key Risk Indicators (KRIs) may include:

- Increasing Confidential information exposures
- Any Restricted information exposure
- Repeated lost-device exposure
- Repeated excessive-permission exposure
- Significant third-party exposure
- Repeated accidental disclosure
- Delayed containment
- Recurring exposure after corrective action

---

# 129. Metric Interpretation

An increase in reported data-exposure events may indicate:

- Increased exposure
- Improved employee reporting
- Better detection
- Broader monitoring

Event count alone does not establish whether enterprise risk increased or decreased.

---

# 130. Playbook Exercises

This playbook should be periodically exercised.

Scenarios may include:

- Confidential email sent to the wrong recipient
- Lost encrypted company laptop
- Publicly exposed shared folder
- Compromised account accessing customer information
- Infinity customer-information exposure
- Lost backup drive
- Third-party provider reporting company-data exposure

---

# 131. Exercise Objectives

Exercises should evaluate whether responders can:

- Identify affected information
- Determine classification
- Contain exposure
- Preserve evidence
- Determine reasonable scope
- Distinguish access from acquisition
- Escalate appropriately
- Coordinate Legal/Compliance review
- Identify corrective action

---

# 132. Exercise Safety

Exercises must not unnecessarily expose real sensitive information.

Simulated information should be used where practical.

---

# 133. Playbook Assessment

Assessment may determine whether:

- Exposure is identified.
- Information is classified.
- Containment occurs.
- Scope is investigated.
- Evidence is preserved.
- Access and acquisition are distinguished.
- Notification decisions are appropriately supported.
- Recovery is validated.
- Significant incidents receive corrective action.

---

# 134. Assessment Methods

Assessment methods may include:

- Inspection
- Observation
- Interviews
- Sampling
- Exercises
- Technical Testing
- Reconciliation
- Independent Performance

---

# 135. Independent Performance

An assessor may independently perform selected response steps using an authorized scenario.

For example, the assessor may:

1. Receive a simulated data-exposure report.
2. Identify the information.
3. Determine classification.
4. Identify immediate containment.
5. Determine evidence requirements.
6. Determine reasonable scope.
7. Distinguish potential access from confirmed acquisition.
8. Identify required escalation.
9. Identify required notification decision support.
10. Compare the result with expected playbook actions.

---

# 136. Assessment Exceptions

Exceptions may include:

- Protected information exposure not escalated
- Classification not determined
- Active exposure not contained
- Scope not investigated
- Access represented as confirmed exfiltration without evidence
- Material evidence not preserved
- Required Legal/Compliance coordination omitted
- Recovery not validated

---

# 137. Findings

Material playbook deficiencies must be documented.

Examples include:

- Known public exposure of Restricted information left active without justification
- Significant data exposure not escalated
- Evidence deliberately destroyed
- Unsupported claims of exfiltration recorded as fact
- Required notification assessment omitted
- Lost sensitive backup media not investigated
- Repeated exposure left without corrective action

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 138. Control Effectiveness

Data-exposure incident evidence may support conclusions that relevant controls are:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

The conclusion must reflect actual evidence rather than documentation alone.

---

# 139. Traceability

This playbook supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

A data-exposure incident may provide evidence across multiple stages of this chain.

---

# 140. Related Artifacts

- [[PRO-003 Identity and Access Management Program]]
- [[PRO-005 Security Operations Program]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[STD-001 Information Classification Standard]]
- [[STD-003 Endpoint Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[PROC-001 Joiner-Mover-Leaver Procedure]]
- [[PROC-003 Access Review Procedure]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-008 Security Monitoring Procedure]]
- [[PROC-009 Malware Response Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-014 Facility Access Procedure]]
- [[PROC-015 Visitor & Vendor Access Procedure]]
- [[PROC-016 Restricted Area Access Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PBK-001 Phishing & Credential Compromise Playbook]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

---

# 141. Review

This playbook must be reviewed:

- At least annually
- Following a material data-exposure incident
- Following significant information-classification change
- Following significant information-handling change
- Following material lessons learned
- Following significant assurance findings

The IT & Information Security Manager coordinates review.

Material revisions require CIO approval.

---

# 142. Revision History

| Version | Date     | Description                    | Approval |
| ------- | -------- | ------------------------------ | -------- |
| 1.0     | May 2013 | Initial Data Exposure Playbook | CIO      |