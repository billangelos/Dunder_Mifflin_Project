# PROC-011 Evidence Handling Procedure

## Document Control

| Field | Value |
|---|---|
| Document ID | PROC-011 |
| Title | Evidence Handling Procedure |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Evidence-Handling or Incident-Response Change |

---

# 1. Purpose

This procedure defines how Dunder Mifflin, Inc. identifies, collects, documents, protects, transfers, stores, analyzes, retains, and disposes of information used as security evidence.

The procedure is intended to preserve:

- Integrity
- Authenticity
- Traceability
- Confidentiality
- Availability
- Investigative usefulness

Evidence handling must be proportionate to the nature and significance of the event.

---

# 2. Scope

This procedure applies to evidence associated with:

- Security monitoring
- Security events
- Security incidents
- Malware investigations
- Unauthorized access
- Credential compromise
- Information exposure
- Fraud-related security investigations
- Vulnerability assessments
- Penetration testing
- Physical-security events affecting information systems
- Third-party security events
- Corrective-action investigations
- Security assurance activities

---

# 3. Authority

This procedure supports requirements established by:

- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[PRO-005 Security Operations Program]]
- [[PLN-001 Incident Response Plan]]

---

# 4. Objectives

Evidence handling must:

1. Preserve relevant security information.
2. Protect evidence from unauthorized alteration.
3. Record where significant evidence originated.
4. Record who handled significant evidence.
5. Maintain appropriate confidentiality.
6. Support technical investigation.
7. Support management decisions.
8. Support legal or contractual requirements.
9. Support assurance and corrective action.
10. Avoid creating unsupported conclusions about evidence.

---

# 5. Evidence Definition

Security evidence is information preserved because it may help establish:

- What occurred
- When it occurred
- What systems were involved
- What accounts were involved
- What information was affected
- What actions were performed
- What controls operated or failed
- How an event was handled

---

# 6. Evidence Versus Operational Record

Not every security record requires formal evidence handling.

Routine operational records may include:

- Normal antivirus status
- Routine vulnerability scan output
- Standard system logs
- Routine access-review records
- Normal administrative records

These records become investigative evidence when they are preserved or relied upon for a material security investigation, incident, finding, or decision.

---

# 7. Proportional Handling

Evidence handling must reflect:

- Event severity
- Information sensitivity
- Investigation purpose
- Potential legal significance
- Potential disciplinary significance
- Business impact
- Likelihood of future review

A routine malware alert does not necessarily require the same handling as evidence from a significant data-exposure investigation.

---

# 8. Evidence Lifecycle

The evidence lifecycle is:

**Identify → Collect → Document → Protect → Transfer → Store → Analyze → Retain → Dispose**

Each stage must preserve reasonable traceability.

---

# 9. Safety Priority

Human life and safety take priority over evidence preservation.

Personnel must not create unreasonable physical danger merely to:

- Preserve a device
- Maintain system power
- Collect a log
- Protect a storage medium
- Prevent evidence alteration

---

# 10. Evidence Sources

Potential evidence sources include:

- System logs
- Application logs
- Authentication records
- Firewall logs
- VPN records
- Antivirus alerts
- Vulnerability scan results
- Penetration-test results
- Emails
- Files
- Screenshots
- System configuration
- Account records
- Access-control records
- Network information
- Backup records
- Cloud-service records
- Physical-access records
- User statements
- Administrator statements
- Third-party reports
- Security-tool output

---

# 11. Physical Evidence

Physical evidence may include:

- Laptop
- Desktop
- Server
- Hard drive
- External backup drive
- Mobile device
- Removable media
- Access card
- Key
- Printed document
- Other physical item relevant to an investigation

---

# 12. Evidence Identification

Before collecting evidence, the responder should determine:

- What information may be relevant
- Where it exists
- Whether it is volatile
- Whether collection could alter it
- Whether immediate action is required
- Whether specialized expertise is needed

---

# 13. Volatile Evidence

Some evidence may disappear or change when:

- A system is shut down
- A user logs off
- A process terminates
- A network connection ends
- A service restarts

Where practical, responders should consider whether useful volatile information should be captured before changing system state.

---

# 14. Volatility Versus Risk

Preserving volatile evidence must not unnecessarily allow:

- Malware spread
- Continued data theft
- Continued encryption
- Unauthorized access
- Business harm

Containment may take priority when continued operation creates greater risk.

The reason must be documented for significant events.

---

# 15. Collection Authority

Evidence must be collected only by personnel with appropriate:

- Authorization
- Access
- Business purpose

This procedure does not grant additional access merely because information may be useful to an investigation.

---

# 16. Minimum Necessary Collection

Personnel should collect information reasonably necessary for the investigation.

Investigators must avoid unnecessary collection of:

- Personal information
- Unrelated employee information
- Unrelated customer information
- Unrelated business records

---

# 17. Evidence Collection Record

Significant evidence should be documented with:

- Evidence identifier
- Description
- Source
- System or location
- Collector
- Collection date and time
- Collection method
- Original format where relevant
- Classification
- Hash where appropriate
- Related event or incident

---

# 18. Evidence Identifier

Significant evidence should receive a unique identifier sufficient to distinguish it from other evidence.

The identifier should remain associated with the evidence throughout its handling.

---

# 19. Date and Time

Evidence records must include collection date and time where practical.

Investigators must distinguish among:

- Event time
- System-recorded time
- Collection time
- Analyst observation time

These times may differ.

---

# 20. Time Accuracy

Investigators should consider whether relevant systems have reasonably consistent time.

Apparent differences between systems must not automatically be interpreted as evidence of malicious activity.

Known clock discrepancies should be documented.

---

# 21. Unknown Time

If an exact time cannot be established, the record must identify it as:

- Unknown,
- Approximate, or
- Estimated

as appropriate.

Investigators must not invent exact timestamps.

---

# 22. Screenshots

Screenshots may preserve useful evidence such as:

- Error messages
- Ransom notes
- Security alerts
- Account information
- Application behavior
- Configuration
- Malicious messages

A screenshot should identify sufficient context to understand what it represents.

---

# 23. Screenshot Limitations

A screenshot may demonstrate what was displayed but may not establish:

- Root cause
- File integrity
- Full system state
- Attacker identity
- Complete event scope

Investigators must not assign more evidentiary value than the screenshot supports.

---

# 24. Log Collection

Relevant logs should be preserved before routine retention, rotation, or system changes cause their loss.

Collection should preserve:

- Source
- Relevant period
- Format
- Collection method

where practical.

---

# 25. Authentication Evidence

Authentication evidence may include:

- Successful logins
- Failed logins
- Account lockouts
- Account creation
- Account disablement
- Privileged-group changes
- VPN activity
- Administrative activity

---

# 26. Email Evidence

Relevant email evidence should preserve available:

- Sender
- Recipient
- Date and time
- Subject
- Message content
- Attachments
- Links
- Message-routing information where useful

Forwarding a suspicious email alone may not preserve all useful information.

---

# 27. Malware Evidence

Malware evidence may include:

- Antivirus alerts
- Suspicious files
- File hashes
- System logs
- Process information
- Network activity
- Email
- Persistence information
- User observations

Malware handling must also follow [[PROC-009 Malware Response Procedure]].

---

# 28. Malware Samples

Malware samples must be handled carefully.

Personnel must avoid:

- Unnecessary execution
- Accidental distribution
- Storage in ordinary shared locations
- Transmission without appropriate protection
- Exposure of production systems

---

# 29. Vulnerability Evidence

Vulnerability evidence may include:

- Scanner output
- Manual validation
- Configuration evidence
- Screenshots
- Version information
- Penetration-test results
- Retest results

Evidence must support the finding without unnecessarily increasing exploitation risk.

---

# 30. Penetration-Test Evidence

Penetration-test evidence must be handled according to [[STD-007 Penetration Testing Standard]].

Evidence may contain:

- Exploitable vulnerabilities
- Credentials
- Attack paths
- Sensitive system information
- Proof of access

Access to such evidence must be restricted.

---

# 31. Physical Evidence Collection

Physical evidence should be documented before movement when practical.

The record should identify:

- Item
- Location found
- Person collecting it
- Date and time
- Condition
- Related event

---

# 32. Device Handling

A device involved in a significant investigation should not be casually:

- Reassigned
- Reimaged
- Reused
- Disposed of
- Returned to service

until appropriate evidence and investigative needs have been considered.

---

# 33. Original Evidence

Where practical, original evidence should be preserved and analysis performed using an appropriate copy.

The method depends on:

- Evidence type
- Investigation significance
- Available capability
- Business need

---

# 34. Working Copy

A working copy may be created for analysis to reduce unnecessary alteration of original evidence.

The working copy should remain traceable to its source.

---

# 35. Cryptographic Hashing

Where practical and useful, digital evidence should receive a cryptographic hash using SHA-256.

Hashing may be used for:

- Files
- Malware samples
- Disk images
- Collected log packages
- Other digital evidence

---

# 36. Hash Record

When hashing is used, the evidence record should identify:

- Hash algorithm
- Hash value
- Evidence identifier
- Date and time
- Person performing the hash

---

# 37. Purpose of Hashing

A cryptographic hash supports later verification that digital evidence has not changed.

A hash does not establish:

- Who created the evidence
- Whether the original information was accurate
- Whether the evidence proves a particular conclusion
- Whether collection was legally sufficient

---

# 38. Hash Verification

When material digital evidence is transferred or copied, the hash should be verified where practical.

A mismatch must be investigated before relying on the copy.

---

# 39. Evidence Packaging

Physical evidence should be packaged or otherwise protected in a manner appropriate to:

- Item type
- Sensitivity
- Risk of damage
- Risk of alteration

Packaging should permit identification of the evidence.

---

# 40. Evidence Labeling

Significant physical evidence should be labeled with:

- Evidence identifier
- Related event or incident
- Classification where appropriate

Sensitive investigative details should not be unnecessarily displayed on external packaging.

---

# 41. Chain of Custody

A chain of custody is required when significant evidence changes possession or control during an investigation.

The purpose is to document:

- Who possessed the evidence
- When possession changed
- Why it changed
- Where the evidence was stored

---

# 42. Chain-of-Custody Record

The chain-of-custody record should include:

- Evidence identifier
- Person releasing evidence
- Person receiving evidence
- Date and time
- Purpose
- Storage or destination
- Relevant condition or integrity information

---

# 43. Electronic Transfer

Electronic transfer of significant evidence should use an appropriate protected method.

Where practical:

- Access should be restricted.
- Encryption should be used for sensitive evidence.
- Hashes should be verified.
- Transfer should be documented.

---

# 44. Physical Transfer

Physical transfer should maintain reasonable control over the evidence.

Unattended evidence must be stored in an appropriately secured location.

---

# 45. Internal Transfer

Internal transfer does not eliminate chain-of-custody requirements when the evidence is significant.

Transfers between:

- Security Operations
- System administrators
- Management
- Legal/Compliance
- Other authorized personnel

should remain documented where chain of custody is required.

---

# 46. External Transfer

Evidence transferred outside Dunder Mifflin requires appropriate authorization.

Potential recipients may include:

- Retained Digital Forensics and Incident Response (DFIR) provider
- Legal counsel
- Insurance representative
- Law enforcement
- Other authorized specialist

---

# 47. External Recipient Verification

Before transferring significant evidence externally, the sender must verify:

- Recipient identity
- Authorization
- Transfer method
- Information sensitivity
- Applicable confidentiality requirements

---

# 48. Confidentiality Requirement

Nonemployees receiving sensitive evidence must have an enforceable Non-Disclosure Agreement (NDA) or equivalent confidentiality obligation before access where required by the nature of the information.

The requirement is based on access and information sensitivity rather than vendor title.

---

# 49. Third-Party Evidence Handling

Third parties handling company evidence must receive only the access reasonably necessary for the authorized purpose.

Third-party involvement does not transfer Dunder Mifflin's responsibility for:

- Evidence governance
- Incident decisions
- Risk decisions
- Final conclusions

---

# 50. DFIR Provider

A retained DFIR provider is a proposed Critical Security Response Provider.

Once implemented, the provider may support:

- Forensic collection
- Malware analysis
- Disk analysis
- Complex incident investigation
- Evidence preservation

The proposed provider must not receive current control-effectiveness credit before implementation.

---

# 51. Evidence Storage

Significant evidence must be stored in a location appropriate to:

- Classification
- Investigation significance
- Access requirements
- Integrity requirements
- Retention requirements

---

# 52. Digital Evidence Storage

Digital evidence should be stored in a restricted location with access limited to authorized personnel.

Where practical, sensitive digital evidence should be encrypted.

---

# 53. Physical Evidence Storage

Physical evidence should be stored in a secured area appropriate to the evidence.

Access must be restricted to authorized personnel.

---

# 54. Evidence Access

Access to significant evidence must be based on legitimate need.

Evidence must not be accessed merely because an employee has technical administrative privileges.

---

# 55. Privileged Administrators

Administrative capability does not automatically establish investigative authorization.

Privileged administrators must access evidence only when required for:

- Collection
- Analysis
- Technical support
- Authorized investigation

---

# 56. Evidence Access Record

For significant investigations, access to restricted evidence should be documented where practical.

The record may identify:

- Person
- Date and time
- Evidence
- Purpose

---

# 57. Evidence Classification

Evidence inherits the classification of the information it contains.

If evidence contains multiple classifications, it must be protected according to the highest applicable classification.

---

# 58. Restricted Evidence

Evidence containing Restricted information requires heightened protection.

Examples may include:

- Sensitive personnel information
- Authentication secrets
- Highly sensitive investigation material
- Other Restricted business information

---

# 59. Credentials in Evidence

Evidence may contain:

- Passwords
- Authentication tokens
- Session information
- Administrative credentials

Such information must be protected from unnecessary disclosure.

Credentials exposed during an investigation may require replacement.

---

# 60. Payment Information

Dunder Mifflin's payment architecture does not retain payment card Primary Account Numbers (PANs).

Payment evidence may contain:

- Processor token
- Card brand
- Last four digits
- Expiration information

Unexpected discovery of full PAN data must be escalated for investigation.

---

# 61. Evidence Analysis

Evidence analysis must be performed by personnel with appropriate:

- Authorization
- Technical capability
- Business purpose

Complex evidence may require external specialist assistance.

---

# 62. Analysis Documentation

Material analysis should document:

- Evidence reviewed
- Method
- Significant observations
- Conclusions
- Limitations
- Unresolved questions

---

# 63. Fact Versus Conclusion

Evidence records must distinguish between:

- Observed fact
- Analyst interpretation
- Working hypothesis
- Final conclusion

An analyst conclusion must not be recorded as an observed fact.

---

# 64. Correlation

Evidence from multiple sources may be correlated to improve understanding.

Example:

**Email → Authentication Log → Endpoint Alert → Firewall Record → Privileged Activity**

Correlation must preserve the source of each piece of evidence.

---

# 65. Missing Evidence

Missing evidence must be documented when it materially limits an investigation.

Examples include:

- Log rotated
- Logging disabled
- System unavailable
- Device destroyed
- Provider data unavailable
- Collection occurred too late

---

# 66. Evidence Gap

A material evidence gap may indicate a separate control weakness.

Examples include:

- Required logging not enabled
- Logs not retained long enough
- Monitoring tool failure
- Time inconsistency
- Unauthorized evidence deletion

Material deficiencies may require corrective action.

---

# 67. Altered Evidence

If evidence appears altered, the investigator must:

1. Stop relying on the affected evidence as unchanged.
2. Preserve the available version.
3. Document the discrepancy.
4. Investigate the cause.
5. Determine whether another reliable source exists.

---

# 68. Evidence Contamination

Potential evidence contamination must be documented.

Contamination may result from:

- User activity
- Administrator activity
- Malware
- Cleanup activity
- System restart
- Analysis activity
- Improper storage

Contamination does not automatically make all evidence useless, but its effect must be understood.

---

# 69. Evidence Before Remediation

Where practical, relevant evidence should be collected before:

- Malware removal
- System reimaging
- Account deletion
- Configuration replacement
- Log clearing
- Device disposal

Immediate containment may take priority when delay would materially increase harm.

---

# 70. Evidence During Emergency Action

Emergency action may change or destroy evidence.

When this occurs, responders should document:

- Action performed
- Time
- Person
- Reason
- Expected effect on evidence

---

# 71. Evidence and Recovery

Evidence preservation must be balanced with business recovery.

A Critical system must not remain unnecessarily unavailable solely to preserve evidence when adequate collection has occurred or other reasonable evidence exists.

---

# 72. Evidence and Backup Recovery

Before restoring a system involved in a significant incident, responders should consider preserving evidence necessary to understand:

- Compromise
- Corruption
- Malware
- Recovery point
- Affected credentials

---

# 73. Backup as Evidence

Backup media or backup data may become evidence when relevant to:

- Timeline reconstruction
- Data integrity
- Malware analysis
- Recovery validation
- Historical system state

Normal backup media should not automatically be treated as investigative evidence.

---

# 74. Security Event Evidence

Security event evidence must remain traceable to the event record.

If the event becomes an incident, the evidence must remain traceable to both records.

---

# 75. Incident Evidence

Incident evidence must be associated with the incident identifier or other controlled incident record.

The relationship must remain intact throughout investigation and closure.

---

# 76. Evidence Inventory

Significant investigations should maintain an evidence inventory.

The inventory should identify:

- Evidence identifier
- Description
- Classification
- Current location
- Custodian
- Hash where applicable
- Status

---

# 77. Evidence Custodian

A significant investigation should identify a person responsible for maintaining evidence records.

The custodian may be:

- Information Security Analyst
- IT & Information Security Manager
- Other authorized investigator

Custodianship does not imply ownership of the underlying business information.

---

# 78. Evidence Ownership

Business information contained in evidence remains company information subject to applicable ownership, classification, and retention requirements.

---

# 79. Evidence Duplication

Evidence should not be unnecessarily duplicated.

Each additional copy can increase:

- Exposure
- Storage requirements
- Handling complexity
- Risk of unauthorized disclosure

Necessary copies must remain appropriately protected.

---

# 80. Evidence Transmission by Email

Sensitive evidence should not be transmitted through ordinary email when a more appropriate protected method is available.

If email is necessary, information sensitivity and protection requirements must be considered.

---

# 81. Evidence on Removable Media

When removable media is required for evidence transfer or storage:

- Media must be authorized.
- Sensitive evidence should be encrypted.
- Media must be physically controlled.
- Transfer must be documented where appropriate.

---

# 82. Evidence Printing

Evidence should be printed only when there is a legitimate need.

Printed evidence must be:

- Classified appropriately
- Physically protected
- Distributed only to authorized recipients
- Securely disposed of when no longer required

---

# 83. Evidence Disposal

Evidence must not be destroyed while it is required for:

- Active investigation
- Incident response
- Corrective action
- Legal hold
- Contractual requirement
- Management review
- Assurance

---

# 84. Authorized Disposal

Once evidence is no longer required, disposal must reflect:

- Classification
- Media type
- Business requirements
- Legal requirements
- Contractual requirements

---

# 85. Digital Disposal

Sensitive digital evidence should be securely deleted or otherwise rendered inaccessible when authorized for disposal.

The disposal method must be appropriate to the storage medium and sensitivity.

---

# 86. Physical Disposal

Sensitive paper evidence must be destroyed using an approved secure-destruction method.

Physical media containing sensitive evidence must be sanitized or destroyed as appropriate.

---

# 87. Legal Hold

Evidence subject to legal hold must not be destroyed or altered contrary to Legal/Compliance instructions.

Legal/Compliance controls the applicable legal-hold requirements.

---

# 88. Law-Enforcement Transfer

Evidence transferred to law enforcement must be appropriately documented.

The transfer record should identify:

- Evidence
- Recipient
- Agency
- Date and time
- Purpose
- Person authorizing transfer

---

# 89. Original Evidence After Transfer

Where appropriate and legally permitted, Dunder Mifflin should retain sufficient records or copies to support continued internal response.

Legal/Compliance should guide handling when law enforcement takes possession of original evidence.

---

# 90. Personnel Investigation

Evidence used in personnel investigations must be coordinated with Human Resources and Legal/Compliance as appropriate.

Information Security personnel must not independently determine disciplinary outcomes.

---

# 91. Fraud Investigation

Security evidence related to suspected fraud must be coordinated with the appropriate business function.

Depending on the event, this may include:

- Finance
- Human Resources
- Operations
- Legal/Compliance
- Executive management

---

# 92. Third-Party Investigation

When a third party provides evidence, the investigator should record:

- Source
- Provider
- Date received
- Description
- Relevant integrity information
- Related incident or event

The organization must not assume third-party evidence is complete merely because it was supplied by a provider.

---

# 93. Evidence Reliability

Evidence reliability must be evaluated in context.

Factors may include:

- Source
- Collection method
- Integrity
- Completeness
- Time accuracy
- Corroboration
- Potential alteration

---

# 94. Conflicting Evidence

When evidence sources conflict, the investigator must document the conflict.

The investigator should determine whether the difference can be explained by:

- Time discrepancy
- Different system perspectives
- Incomplete logging
- Configuration
- Human error
- Evidence alteration

Unsupported certainty must be avoided.

---

# 95. Evidence-Based Conclusions

Security conclusions must be supported by available evidence.

The absence of evidence does not automatically prove that an event did not occur.

The presence of an alert does not automatically prove compromise.

---

# 96. Evidence Integrity Prohibitions

Personnel must not:

- Fabricate evidence.
- Alter evidence to support a preferred conclusion.
- Backdate evidence records.
- Delete unfavorable evidence.
- Conceal evidence gaps.
- Falsify chain-of-custody records.
- Change timestamps to improve apparent response performance.
- Represent uncollected evidence as collected.
- Represent unverified evidence as verified.

---

# 97. Corrections

An error in an evidence record must be corrected transparently.

The correction should preserve:

- Original information where practical
- Corrected information
- Date of correction
- Person making the correction
- Reason

Material history must not be silently rewritten.

---

# 98. Evidence and Findings

Evidence may support a formal finding when it demonstrates whether a:

- Requirement
- Control
- Procedure
- Process
- Expected outcome

was satisfied.

Formal findings are maintained in [[REG-004 Finding & Corrective Action Register]].

---

# 99. Evidence and Control Effectiveness

Evidence may support a control-effectiveness conclusion of:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

The conclusion must reflect actual control operation.

---

# 100. Evidence and Risk Reassessment

Evidence from incidents, testing, monitoring, or investigations may support risk reassessment.

Risk reassessment must preserve historical risk results and document the reason for any new evaluation.

---

# 101. No Premature Risk Credit

Evidence that a control is:

- Planned
- Purchased
- Documented
- Partially configured

does not establish that the control is operating effectively.

Risk reduction requires appropriate implementation and validation.

---

# 102. Evidence for Implemented Controls

Evidence supporting control implementation may include:

- Configuration
- System output
- Logs
- Completed records
- Observation
- Technical Testing
- Independent Performance

Implementation evidence and effectiveness evidence are related but not identical.

---

# 103. Evidence for Control Effectiveness

Control-effectiveness evidence should demonstrate whether the control:

- Operates as intended
- Produces the required result
- Covers the required population
- Operates with sufficient consistency

---

# 104. Evidence for Corrective Action

Corrective-action closure must be supported by evidence demonstrating that the required action was completed.

Where validation is required, implementation evidence alone is insufficient.

---

# 105. Evidence for Retesting

Retest evidence should identify:

- Original finding
- Remediation performed
- Retest method
- Retest date
- Result
- Tester

The evidence must support whether the original condition remains.

---

# 106. Evidence Quality

Evidence quality should be evaluated for:

- Relevance
- Reliability
- Completeness
- Timeliness
- Traceability

More evidence is not automatically better evidence.

---

# 107. Evidence Sufficiency

Evidence is sufficient when it provides a reasonable basis for the required conclusion.

The required amount and quality depend on:

- Control importance
- Risk
- Assessment objective
- Evidence reliability

---

# 108. Evidence Independence

Evidence created solely by the person responsible for operating a control may require additional validation when independence is important.

Additional evidence may include:

- Independent inspection
- Technical Testing
- Sampling
- Reconciliation
- Independent Performance

---

# 109. Independent Performance

An assessor may independently perform a documented procedure or control activity to determine whether it produces the expected result.

For example, the assessor may:

1. Select a sample.
2. Obtain the required source information.
3. Apply the documented procedure independently.
4. Record the result.
5. Compare it with the original control record.
6. Investigate material differences.

---

# 110. Evidence From Independent Performance

Evidence produced through Independent Performance must identify:

- Procedure performed
- Population or sample
- Assessor
- Date
- Result
- Comparison with expected result
- Exceptions

---

# 111. Evidence From Sampling

When sampling is used, the evidence record should identify:

- Population
- Sample selection
- Sample size
- Period
- Exceptions

Sampling conclusions must not imply examination of the entire population.

---

# 112. Evidence From Observation

Observation may demonstrate that a process occurred at a particular time.

Observation alone may not establish that the process operates consistently across all periods.

---

# 113. Evidence From Interviews

Interviews may provide useful context and explanation.

An interview alone may not prove that a technical or operational control operates effectively.

Important statements should be corroborated where appropriate.

---

# 114. Evidence From Inspection

Inspection may verify the existence or content of:

- Policy
- Procedure
- Configuration
- Record
- Report
- Approval
- Contract

Existence of documentation does not automatically establish operational effectiveness.

---

# 115. Evidence From Technical Testing

Technical Testing may directly evaluate:

- Configuration
- Access
- Vulnerability
- Network exposure
- Authentication
- Application behavior
- Recovery capability

Technical Testing must remain authorized and appropriately scoped.

---

# 116. Evidence From Reconciliation

Reconciliation compares independent or related records to identify discrepancies.

Examples include:

- Asset inventory versus network discovery
- Active accounts versus Human Resources records
- Privileged accounts versus approved authorization
- Inventory records versus physical inventory
- Backup jobs versus expected backup coverage

---

# 117. Assessment Work Plan

Evidence requirements should be defined in the applicable [[TMP-001 Assessment Work Plan Template]] before significant assurance work where practical.

The work plan should identify:

- Objective
- Scope
- Control
- Evidence required
- Assessment method
- Population
- Sample
- Expected result
- Responsible assessor

---

# 118. Evidence Request

An evidence request should be sufficiently specific that the recipient understands:

- What is required
- Relevant period
- Relevant systems
- Required format where necessary
- Due date

Evidence requests should avoid unnecessary data collection.

---

# 119. Evidence Request Tracking

Material evidence requests should be tracked when needed to support:

- Completeness
- Timeliness
- Follow-up
- Assessment documentation

Missing requested evidence must not be silently treated as satisfactory evidence.

---

# 120. Unavailable Evidence

When required evidence is unavailable, the assessor must determine whether:

- Alternative evidence exists.
- Scope must change.
- Testing can continue.
- A control deficiency may exist.
- A finding is required.

Unavailable evidence must be documented.

---

# 121. Evidence and Continuous Monitoring

Continuous monitoring means maintaining risk-appropriate ongoing awareness.

It does not require:

- Continuous human observation
- Collection of every possible log
- Permanent retention of all information
- 24x7 analysis of every event

Evidence collection must remain purposeful.

---

# 122. Evidence and Privacy

Evidence handling must respect legitimate privacy concerns.

Investigators must not use security investigations as justification for unnecessary access to:

- Personal communications
- Unrelated employee information
- Unrelated customer information
- Unrelated business records

---

# 123. Need to Know

Sensitive investigative evidence must be shared only with personnel who require access for a legitimate purpose.

Management position alone does not automatically require access to every investigative detail.

---

# 124. Executive Reporting

Executive reporting should generally summarize:

- Material impact
- Significant findings
- Enterprise risk
- Required decisions

Raw evidence should be provided only when needed.

---

# 125. Management Reporting

Management reporting should provide sufficient evidence context to support:

- Accountability
- Corrective action
- Resource decisions
- Risk decisions

---

# 126. Operational Reporting

Operational personnel may require greater technical detail to:

- Investigate
- Remediate
- Retest
- Recover
- Validate controls

Access remains limited by legitimate need.

---

# 127. Evidence Metrics

Evidence-handling metrics may include:

- Significant investigations with complete evidence inventories
- Evidence items with required source information
- Evidence transfers with complete chain-of-custody records
- Digital evidence with verified hashes where required
- Evidence-handling exceptions
- Missing evidence affecting investigations
- Unauthorized evidence-access events

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 128. Key Performance Indicators

Key Performance Indicators (KPIs) may include:

- Percentage of significant evidence items with complete required documentation
- Percentage of required transfers with complete custody records
- Percentage of significant digital evidence with hash verification where required
- Percentage of evidence-handling deficiencies remediated

---

# 129. Key Risk Indicators

Key Risk Indicators (KRIs) may include:

- Missing material evidence
- Unexplained hash mismatch
- Unauthorized evidence access
- Broken chain of custody
- Evidence destruction during active investigation
- Repeated evidence-handling deficiencies
- Material logging gaps preventing investigation

---

# 130. Procedure Assessment

This procedure must be periodically assessed to determine whether evidence is:

- Properly identified
- Appropriately collected
- Traceable
- Protected
- Accessible only to authorized personnel
- Transferred appropriately
- Retained appropriately
- Disposed of appropriately

---

# 131. Assessment Methods

Assessment methods may include:

- Inspection
- Observation
- Interviews
- Sampling
- Reconciliation
- Technical Testing
- Independent Performance

The method must match the evidence-handling control being evaluated.

---

# 132. Evidence Inventory Testing

An assessor may sample evidence from significant investigations and determine whether:

- Evidence identifiers exist.
- Sources are documented.
- Collection information exists.
- Current location is known.
- Classification is appropriate.
- Custody records exist where required.

---

# 133. Hash Verification Testing

An assessor may select digital evidence with recorded hashes and independently calculate the SHA-256 value.

The assessor compares the calculated value with the recorded value.

A mismatch requires investigation.

---

# 134. Chain-of-Custody Testing

An assessor may select transferred evidence and determine whether:

- Releasing person is documented.
- Receiving person is documented.
- Transfer date and time are documented.
- Purpose is documented.
- Current custody is known.

---

# 135. Access Testing

An assessor may review access to significant evidence and determine whether access was limited to authorized personnel with legitimate need.

---

# 136. Disposal Testing

An assessor may sample disposed evidence and determine whether:

- Disposal was authorized.
- No active hold existed.
- Disposal method matched sensitivity.
- Required records were maintained.

---

# 137. Assessment Exceptions

Evidence-handling exceptions must be investigated.

Potential causes include:

- Missing documentation
- Unauthorized access
- Improper storage
- Broken custody record
- Hash mismatch
- Inappropriate disposal
- Training failure
- Process weakness

---

# 138. Findings

Material evidence-handling deficiencies must be documented.

Examples include:

- Significant evidence intentionally altered
- Material evidence destroyed without authorization
- Chain of custody falsified
- Unauthorized access to Restricted evidence
- Material evidence lost
- Known hash mismatch ignored
- Evidence fabricated
- Evidence record backdated
- Significant evidence gap concealed

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 139. Corrective Action

Corrective action must identify:

- Deficiency
- Accountable owner
- Required action
- Due date
- Validation method

Corrective action remains open until appropriately validated.

---

# 140. Risk Relationships

This procedure provides treatment and assurance support for risks including:

- R001 Phishing / Credential Compromise
- R002 Business Email Compromise
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
- R018 Third-Party Technology Failure / Compromise
- R019 Infinity Contractor Dependency / Compromise
- R027 Backup / Recovery Failure
- R028 Data Corruption
- R029 Vendor Fraud
- R030 Sales Fraud
- R031 Payroll Fraud
- R032 Inventory Theft

Evidence handling also supports assurance across the broader enterprise risk portfolio.

---

# 141. Traceability

This procedure supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Evidence handling provides the integrity and traceability necessary to support the later stages of this chain.

---

# 142. Related Artifacts

- [[PRO-005 Security Operations Program]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[STD-007 Penetration Testing Standard]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-006 Vulnerability Assessment Procedure]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]
- [[PROC-008 Security Monitoring Procedure]]
- [[PROC-009 Malware Response Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PLN-001 Incident Response Plan]]
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
- [[TMP-001 Assessment Work Plan Template]]

---

# 143. Review

This procedure must be reviewed:

- At least annually
- Following a material evidence-handling failure
- Following a significant security incident
- Following material investigation-process changes
- Following material legal or contractual requirement changes
- Following significant assurance findings

The IT & Information Security Manager coordinates review.

Material revisions require CIO approval.

---

# 144. Revision History

| Version | Date     | Description                         | Approval |
| ------- | -------- | ----------------------------------- | -------- |
| 1.0     | May 2013 | Initial Evidence Handling Procedure | CIO      |