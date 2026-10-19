# PBK-005 Third-Party Incident Playbook

## Document Control

| Field | Value |
|---|---|
| Document ID | PBK-005 |
| Title | Third-Party Incident Playbook |
| Version | 1.0 |
| Classification | Confidential |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following a Material Third-Party Security Incident |

---

# 1. Purpose

This playbook provides operational guidance for responding to security incidents involving third parties that provide services, technology, access, facilities, support, or other capabilities to Dunder Mifflin.

It supplements:

- [[POL-008 Third-Party Security Policy]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[PLN-001 Incident Response Plan]]

with focused response actions for third-party security incidents.

---

# 2. Scope

This playbook applies to incidents involving:

- Cloud providers
- Technology vendors
- Managed service providers
- Software providers
- Application support providers
- Infinity contractors
- Consultants
- Security service providers
- Backup or storage providers
- Payment processors
- Temporary specialists
- Other third parties with company system or information access

---

# 3. Third-Party Incident

A third-party incident exists when a security event involving an outside organization:

- Affects Dunder Mifflin systems
- Affects Dunder Mifflin information
- Affects company credentials
- Affects company operations
- Affects company recovery capability
- Creates unauthorized company access
- Creates material risk to company assets or processes

A provider experiencing an incident does not automatically mean Dunder Mifflin is affected.

Company impact must be established.

---

# 4. Authority

This playbook operates under:

- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[PLN-001 Incident Response Plan]]

---

# 5. Objectives

Third-party incident response must:

1. Protect human safety.
2. Determine whether Dunder Mifflin is affected.
3. Contain company exposure.
4. Protect company credentials and access.
5. Identify affected systems, information, and processes.
6. Preserve useful company evidence.
7. Obtain relevant provider information.
8. Independently evaluate company impact.
9. Coordinate contractual and management escalation.
10. Maintain business continuity where necessary.
11. Validate provider and company remediation.
12. Identify corrective action.
13. Reassess risk where appropriate.

---

# 6. Response Lifecycle

The third-party incident response lifecycle is:

**Notification / Detection → Triage → Company Impact Assessment → Containment → Evidence Preservation → Provider Coordination → Scope Determination → Recovery / Continuity → Remediation → Validation → Closure → Risk Reassessment**

Activities may overlap when necessary.

---

# 7. Safety Priority

Human life and safety take priority over:

- Evidence
- Systems
- Operations
- Facilities
- Equipment
- Inventory
- Revenue

Emergency action must not be delayed solely to preserve electronic evidence.

---

# 8. Third-Party Risk Categories

Third parties are categorized as:

- Critical
- Important
- Routine

Classification is based on the service, access, information, business dependency, and potential impact.

---

# 9. Critical Third Parties

A Critical third party may support or affect:

- Critical business processes
- Significant company systems
- Sensitive information
- Privileged access
- Recovery capability
- Major business dependencies

Critical third parties receive heightened security oversight.

---

# 10. Important Third Parties

Important third parties may create meaningful business or security impact but do not meet the Critical classification.

---

# 11. Routine Third Parties

Routine third parties generally have limited:

- System access
- Information access
- Operational dependency
- Security impact

An incident may require reclassification if actual exposure is greater than previously understood.

---

# 12. Detection Sources

A third-party incident may be identified through:

- Provider notification
- Contractor notification
- Security monitoring
- User report
- Authentication anomaly
- Malware detection
- Unauthorized-access investigation
- Data-exposure investigation
- Service outage
- Media or public report
- Customer report
- Internal administrator observation

---

# 13. Provider Notification

A provider notification should be recorded with:

- Provider name
- Notification time
- Person providing notification
- Incident description
- Detection time
- Known affected services
- Known affected information
- Known company impact
- Provider containment status
- Provider contact information

---

# 14. Critical Third-Party Notification Expectation

Critical third parties are expected to notify Dunder Mifflin of qualifying security incidents within 24 hours of discovery as established by [[POL-008 Third-Party Security Policy]].

The notification time and the provider's stated discovery time should both be documented.

---

# 15. Late Notification

When a provider fails to meet an applicable notification requirement, the incident record should document:

- Expected notification
- Actual notification
- Reason provided
- Security impact
- Contractual concern
- Required corrective action

Late notification does not reduce the need to respond to the underlying incident.

---

# 16. Independent Detection

Dunder Mifflin may identify a third-party incident before the provider reports it.

The company should not delay containment while waiting for provider confirmation when available evidence supports reasonable protective action.

---

# 17. Initial Triage

The responder should determine:

- Which provider is involved?
- What service does it provide?
- What third-party category applies?
- What systems can it access?
- What information can it access?
- What credentials does it possess?
- What business processes depend on it?
- Is company access currently active?
- Is exposure continuing?
- Is immediate containment required?

---

# 18. Event Versus Incident

A third party reporting its own security event does not automatically establish a Dunder Mifflin security incident.

Formal company incident response is required when evidence indicates or reasonably suggests material company impact or exposure.

---

# 19. Incident Classification

Company incident severity must be determined according to [[STD-008 Incident Classification & Escalation Standard]].

The provider's own incident classification does not determine Dunder Mifflin's classification.

---

# 20. Severity Considerations

Severity should consider:

- Company systems affected
- Information classification
- Privilege
- Business-process impact
- Recovery impact
- Scope
- Duration
- Provider dependency
- Availability of alternatives
- Evidence of unauthorized access
- Evidence of information exposure

---

# 21. Immediate Escalation Conditions

Immediate escalation is required when a third-party incident involves or reasonably suggests:

- Domain Administrator compromise
- Significant privileged access compromise
- Restricted information exposure
- Significant Confidential information exposure
- Significant Infinity compromise
- Critical cloud-service compromise
- Backup or recovery compromise
- Widespread malware or ransomware
- Significant operational interruption
- Unknown but potentially severe company scope

---

# 22. Company Impact Must Be Independently Determined

Dunder Mifflin must independently determine company impact.

A provider statement such as:

- "No customer impact"
- "Contained"
- "Resolved"
- "No evidence of access"

may be relevant evidence but does not automatically establish Dunder Mifflin's conclusion.

---

# 23. Company Impact Questions

The response should determine:

- Was company information involved?
- Were company systems involved?
- Were company credentials involved?
- Did the provider have active company access?
- Did unauthorized activity reach company systems?
- Was company information accessible?
- Was company information acquired?
- Was company information modified?
- Was company information deleted?
- Was company service availability affected?

---

# 24. Provider Access Inventory

Responders should identify provider access including:

- Accounts
- Applications
- Servers
- Network access
- VPN
- Cloud administration
- Source repositories
- Databases
- Backup systems
- Physical access
- Sensitive information

---

# 25. Provider Account Containment

Provider accounts may be disabled or restricted when continued access creates unacceptable risk.

The responder should document:

- Account
- Provider
- Reason
- Time
- Action
- Business impact
- Conditions for restoration

---

# 26. Credential Protection

If provider compromise may expose company credentials, responders should identify and protect affected credentials.

This may include:

- Password replacement
- Account disablement
- Session termination
- Privilege reduction
- Authentication review

---

# 27. Privileged Third-Party Credentials

Potential exposure of privileged company credentials requires immediate escalation.

Credential replacement should occur from a system reasonably believed to be trusted.

---

# 28. Remote Access

Third-party remote access must be evaluated against approved authorization.

Unexpected or unauthorized remote access requires containment and investigation.

---

# 29. Remote Privileged Administration

External remote privileged administration is prohibited.

Privileged administration of significant production resources must occur through approved company-controlled methods and locations.

Ordinary authorized remote access, including Virtual Private Network (VPN) access, does not authorize privileged administration.

Third-party status, contractor status, operational convenience, incident response, emergency conditions, or ordinary remote-access authorization do not create an exception to this prohibition.

Any external remote privileged administration requires immediate investigation as unauthorized activity.

---

# 30. Infinity Contractor Remote Access

The Infinity contractor does not receive general VPN access for privileged production administration.

External remote privileged administration is prohibited without exception.

Any external remote privileged Infinity activity requires immediate investigation as unauthorized activity.

---

# 31. Infinity Contractor Work Location

Privileged production and administrative work by the Infinity contractor must be performed onsite from the designated company-controlled contractor workspace at Scranton Headquarters.

External remote privileged administration is prohibited and cannot be authorized through an exception or emergency process.

---

# 32. Infinity Contractor Personnel

Expected Infinity contractor personnel should normally be identified at least one business day before scheduled arrival.

Emergency support may require a properly authorized and documented exception to the advance personnel-notification requirement.

Such an exception does not authorize external remote privileged administration.

---

# 33. Contractor Sponsorship

Every contractor with company access must have an accountable company sponsor.

During an incident, the sponsor should assist with:

- Business context
- Access scope
- Personnel identification
- Provider communication
- Service dependency
- Recovery decisions

---

# 34. Contractor Duration

Contractor access is:

- Initially authorized for no more than three months
- Renewable in increments of no more than six months

A third-party incident should determine whether affected access was within its authorized duration.

---

# 35. Expired Access

Provider access remaining active beyond authorization requires:

1. Containment.
2. Usage review.
3. Sponsor notification.
4. Root-cause investigation.
5. Corrective action where appropriate.

---

# 36. Confidentiality Requirement

Nonemployees receiving sensitive company information or access must have an enforceable Non-Disclosure Agreement (NDA) or equivalent confidentiality obligation before access.

The requirement is based on access and sensitivity rather than vendor title.

---

# 37. Confidentiality Obligation Does Not Establish Security

An NDA or equivalent agreement does not prove:

- Effective access control
- Technical competence
- Secure configuration
- Adequate monitoring
- Effective incident response
- Effective remediation
- Effective testing

Contractual confidentiality complements other controls.

---

# 38. Initial Containment

Company containment actions may include:

- Disabling provider accounts
- Restricting provider privileges
- Blocking provider network access
- Suspending integration
- Replacing credentials
- Isolating affected systems
- Restricting data sharing
- Activating an alternate process

---

# 39. Containment Before Complete Provider Information

Dunder Mifflin does not need to wait for a complete provider investigation before taking reasonable company containment action.

---

# 40. Containment Business Impact

When containment may interrupt a Critical or High business process, responders should coordinate with:

- Business owner
- IT & Information Security Manager
- CIO
- Appropriate operational leadership

Security risk and business impact must both be considered.

---

# 41. Evidence Preservation

Useful company-controlled evidence should be preserved before destructive remediation where practical.

Evidence handling must follow [[PROC-011 Evidence Handling Procedure]].

---

# 42. Company Evidence Sources

Evidence may include:

- Authentication logs
- Application logs
- Firewall information
- VPN records
- Account configuration
- Provider accounts
- Files
- Email
- Contracts
- Provider notifications
- System configuration
- User reports
- Incident timelines
- Physical access records

---

# 43. Provider Evidence

Provider evidence may include:

- Incident report
- Timeline
- Relevant logs
- Affected-system list
- Affected-data description
- Indicators
- Root-cause analysis
- Containment actions
- Remediation actions
- Validation results

Availability depends on contractual rights, provider capability, and incident circumstances.

---

# 44. Evidence Limitations

If provider evidence is incomplete or unavailable, the limitation must be documented.

Lack of provider evidence must not be converted into an unsupported conclusion of no company impact.

---

# 45. Evidence Integrity

Personnel must not:

- Fabricate evidence.
- Backdate records.
- Alter evidence to support a preferred conclusion.
- Conceal evidence gaps.
- Represent provider statements as independently verified facts when they are not.

---

# 46. Cryptographic Hashing

Where practical and useful, significant digital evidence should receive a SHA-256 cryptographic hash.

---

# 47. Incident Timeline

Significant third-party incidents must maintain a company incident timeline.

The timeline may include:

- Provider incident discovery
- Provider notification
- Company detection
- Company escalation
- Access containment
- Evidence collection
- Provider updates
- Company recovery
- Remediation
- Validation
- Closure

---

# 48. Unknown Times

Unknown or approximate times must be documented as such.

Responders must not create false precision.

---

# 49. Scope Determination

The responder must determine reasonable company scope.

Scope may include:

- Provider accounts
- Company accounts
- Endpoints
- Servers
- Applications
- Cloud systems
- Infinity
- Databases
- Backup systems
- Information
- Business processes
- Facilities

---

# 50. Provider Scope Versus Company Scope

Provider incident scope and Dunder Mifflin incident scope are related but distinct.

A large provider incident may create limited company impact.

A small provider incident may create severe company impact if the affected service is critical.

---

# 51. Information Exposure

If the third-party incident may expose company information, response must also follow [[PBK-004 Data Exposure Playbook]].

---

# 52. Access Versus Acquisition

Provider confirmation that company information was accessible does not automatically establish that it was acquired.

The incident record should distinguish:

- Accessible
- Viewed where known
- Acquired where supported
- Modified
- Deleted
- Unknown

---

# 53. Unauthorized Access

If provider compromise enables unauthorized company access, response must also follow [[PBK-003 Unauthorized Access Playbook]].

---

# 54. Credential Compromise

If company credentials may be compromised, response must also follow [[PBK-001 Phishing & Credential Compromise Playbook]] where applicable.

---

# 55. Malware

If a third-party incident introduces or may introduce malware into company systems, response must also follow:

- [[PROC-009 Malware Response Procedure]]
- [[PBK-002 Malware & Ransomware Playbook]]

---

# 56. Vulnerability Relationship

If provider compromise exploited a company vulnerability, remediation must follow:

- [[PRO-004 Vulnerability Management Program]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]

---

# 57. Configuration Relationship

If the incident exploited a company configuration weakness, remediation must consider:

- [[POL-007 Change & Configuration Management Policy]]
- [[STD-006 Secure Configuration Standard]]

---

# 58. Provider Root Cause

Dunder Mifflin should request provider root-cause information when appropriate.

A provider's root-cause conclusion should be treated as provider-supplied information unless independently validated.

---

# 59. Cloud Provider Incident

A cloud-provider incident requires evaluation of:

- Hosted systems
- Administrative accounts
- Authentication
- Company data
- Provider control plane
- Service availability
- Backup capability
- Recovery capability
- Provider concentration

---

# 60. Cloud Concentration

Dunder Mifflin uses a cloud-first architecture.

A material incident affecting the primary cloud provider may affect multiple company services simultaneously.

Responders must evaluate concentration impact rather than assessing each affected service in isolation.

---

# 61. Domain Controllers

Dunder Mifflin maintains at least two cloud-hosted Domain Controller/authentication servers within the same overall cloud provider with reasonable failure-domain separation.

A provider incident affecting the shared provider environment may threaten both authentication systems.

---

# 62. Cloud Exit and Emergency Migration

A material cloud-provider incident may require consideration of [[PLN-004 Cloud Exit & Emergency Migration Plan]].

Dunder Mifflin does not maintain a continuously operating alternate cloud environment.

---

# 63. Emergency Migration Decision

Emergency migration should be considered when:

- Provider recovery is unacceptable.
- Security trust cannot reasonably be restored.
- Business interruption exceeds acceptable limits.
- Provider access or integrity cannot be relied upon.

Migration is a risk and business decision, not an automatic response to every provider incident.

---

# 64. Infinity Contractor Incident

An incident involving the Infinity contractor requires evaluation of:

- Contractor accounts
- Personnel
- Source repository
- Development environment
- Production environment
- Application configuration
- Customer information
- Database access
- Documentation
- Intellectual property

---

# 65. Dunder Mifflin Ownership of Infinity

Dunder Mifflin owns:

- Infinity application
- Source code
- Repository
- Application data
- Documentation
- Intellectual property
- Contractor work product
- Application backups

Provider or contractor disruption must not prevent the company from exercising ownership of these assets.

---

# 66. Infinity Source Integrity

If the contractor incident may affect source code, responders should evaluate:

- Repository history
- Unauthorized changes
- Malicious code
- Build integrity
- Production differences
- Administrative access

---

# 67. Infinity Production Access

Potential unauthorized contractor production access requires heightened investigation.

The responder should determine:

- Account used
- Access time
- System accessed
- Changes made
- Data accessed
- Business impact

---

# 68. Infinity Database

The Infinity database is not intended to be directly Internet accessible.

A provider or contractor incident resulting in unauthorized direct database exposure requires immediate escalation.

---

# 69. Payment Processor Incident

A payment-processor incident requires evaluation of:

- Company tokens
- Transaction availability
- Customer impact
- Fraud risk
- Provider notification
- Business continuity

Dunder Mifflin's normal architecture does not retain full payment card PAN information.

---

# 70. Unexpected Payment Card Data

If a provider incident reveals that full payment card PAN information is present in company systems unexpectedly, the condition requires immediate escalation and investigation.

---

# 71. Backup Provider Incident

An incident involving the off-site Disaster Recovery storage provider requires evaluation of:

- Backup-drive custody
- Encryption
- Physical security
- Missing media
- Unauthorized access
- Recovery availability
- Backup generations affected

---

# 72. External Backup Rotation

Dunder Mifflin uses three encrypted external backup hard drives for each of seven facilities, for twenty-one drives total.

The off-site provider normally holds the two most recent weekly generations for each facility, for fourteen off-site drive generations.

---

# 73. Backup Provider Compromise

If the storage provider loses control of a backup drive, responders must determine:

- Facility
- Backup generation
- Encryption status
- Information classification
- Custody history
- Recovery impact
- Whether additional media may be affected

---

# 74. Backup Separation

Off-site storage provides geographic and operational separation.

It does not establish backup immutability.

---

# 75. Technology Vendor Incident

A technology-vendor incident should consider whether:

- Company software is affected.
- Updates are affected.
- Credentials are affected.
- Support access is affected.
- Company configuration is affected.
- Continued use remains acceptable.

---

# 76. Compromised Software or Update

If a vendor reports compromised software or an update, Dunder Mifflin should:

1. Identify affected versions.
2. Determine company deployment.
3. Restrict affected software where necessary.
4. Preserve useful evidence.
5. Obtain provider guidance.
6. Validate remediation.
7. Evaluate broader compromise.

---

# 77. Service Provider Outage

A third-party outage may be primarily an availability event rather than a security incident.

Security incident response is required when the outage:

- Results from or suggests malicious activity
- Affects information confidentiality or integrity
- Creates unauthorized access
- Threatens recovery capability
- Creates another material security concern

---

# 78. Business Continuity

When a third-party incident interrupts business operations, [[PLN-002 Business Continuity Plan]] may be activated.

---

# 79. Business Impact Analysis

Continuity decisions must consider [[RPT-002 Business Impact Analysis]].

Recovery priority is:

**Human Safety → Critical → High → Moderate → Low**

---

# 80. Manual Continuity

Where applicable, business operations may use documented manual procedures under [[PROC-013 Manual Processing Procedure]].

The manual lifecycle is:

**Collect → Review → Enter → Reconcile → Verify**

---

# 81. Alternate Provider

An alternate provider may be considered when:

- Current provider recovery is inadequate.
- Security trust cannot be restored.
- Business interruption becomes unacceptable.
- Contractual or operational alternatives exist.

An alternate provider must not be assumed to be immediately available unless established.

---

# 82. Supplier Disruption

A third-party security incident may also create supplier or operational disruption.

Operational leadership should evaluate:

- Alternate suppliers
- Inventory
- Transportation
- Customer communication
- Procurement options

where applicable.

---

# 83. Provider Communications

A primary provider contact should be established for significant incidents.

Communications should seek factual information rather than unsupported assurances.

---

# 84. Provider Questions

Relevant questions may include:

- When was the incident discovered?
- When did it begin?
- What systems were affected?
- What company information was affected?
- What company accounts were affected?
- Was company information accessed?
- Was company information acquired?
- What containment occurred?
- Is unauthorized access still possible?
- What remediation occurred?
- What validation occurred?
- What remains unknown?

---

# 85. Provider Update Frequency

Update frequency should reflect incident severity and business impact.

Critical incidents may require frequent updates.

Lower-severity incidents may use scheduled updates.

Exact update intervals should be established by the incident leader based on need.

---

# 86. Provider Statements

Provider statements must be attributed appropriately.

For example:

**Provider reports that unauthorized access was contained.**

should not be rewritten as:

**Unauthorized access was confirmed contained.**

unless Dunder Mifflin has sufficient evidence to support that conclusion.

---

# 87. Contractual Review

Legal/Compliance and the responsible business owner should review applicable contractual provisions when the incident may involve:

- Notification requirements
- Confidentiality
- Security requirements
- Incident cooperation
- Audit rights
- Recovery obligations
- Liability
- Termination rights

---

# 88. Audit Rights

Where applicable, Dunder Mifflin may use contractual audit or assessment rights to obtain additional assurance.

The decision should consider:

- Incident severity
- Provider cooperation
- Evidence quality
- Remaining risk

---

# 89. Provider Cooperation

Failure to provide reasonable incident information may itself increase third-party risk.

The limitation should be documented and escalated where appropriate.

---

# 90. Legal and Compliance

Legal/Compliance should be involved when a third-party incident may create material:

- Legal exposure
- Contractual obligations
- Information exposure
- Notification requirements
- Evidence-preservation requirements
- Dispute
- Law-enforcement considerations

---

# 91. Human Resources

Human Resources should be involved when the incident materially involves:

- Contractor personnel conduct
- Employee information
- Personnel-related investigation
- Internal personnel action

---

# 92. Finance

Finance should be involved when the incident may affect:

- Payments
- Banking information
- Vendor fraud
- Payroll
- Accounting
- Financial records

---

# 93. Operations

Operations should be involved when the incident materially affects:

- Warehousing
- Fulfillment
- Inventory
- Shipping
- Procurement
- Branch operations
- Distribution

---

# 94. Provider Notification to Affected Parties

A provider must not independently determine Dunder Mifflin's company communications unless contractual or legal requirements specifically establish that authority.

Company notification decisions remain subject to Dunder Mifflin's authorized process.

---

# 95. Customer Notification

Technical personnel must not independently notify customers of a third-party incident.

Customer notification requires appropriate company authorization.

---

# 96. Regulatory Notification

Any required regulatory notification must be coordinated through Legal/Compliance and authorized management.

---

# 97. Public Communication

Public statements must be authorized.

Technical personnel must not independently:

- Issue public statements
- Admit liability
- Speculate about provider fault
- Provide unsupported incident totals
- Make legal conclusions

---

# 98. External DFIR Assistance

External Digital Forensics and Incident Response (DFIR) assistance may be appropriate when a third-party incident creates:

- Significant unauthorized company access
- Significant data exposure
- Domain compromise
- Complex malware
- Significant forensic requirements
- Broad unknown company scope

---

# 99. Proposed DFIR Capability

A retained DFIR provider is a proposed Critical Security Response Provider capability.

It must not receive current residual-risk or control-effectiveness credit until:

- Contracted
- Available
- Appropriately integrated into response

---

# 100. Provider Remediation

Provider remediation may include:

- Credential replacement
- Vulnerability remediation
- Configuration correction
- Access restriction
- Malware removal
- System rebuilding
- Process correction
- Personnel action
- Monitoring improvements

Dunder Mifflin must identify which provider remediation is material to company risk.

---

# 101. Company Remediation

Company remediation may include:

- Credential replacement
- Account disablement
- Access redesign
- Integration changes
- Configuration correction
- Additional monitoring
- Business continuity changes
- Contract changes
- Provider replacement

---

# 102. Provider Remediation Is Not Company Validation

A provider stating that remediation is complete does not automatically establish that Dunder Mifflin's risk has been adequately addressed.

---

# 103. Remediation Validation

Validation should determine whether:

- Company exposure has stopped.
- Affected credentials are protected.
- Unauthorized access is removed.
- Required configuration is corrected.
- Required provider changes are complete.
- Required company changes are complete.
- Business service is restored.
- Remaining risk is acceptable.

---

# 104. Validation Methods

Validation may include:

- Documentation review
- Account review
- Configuration review
- Log review
- Technical testing
- Provider evidence review
- Interviews
- Sampling
- Reconciliation
- Independent Performance

---

# 105. Service Restoration

Suspended third-party access or service should be restored when there is reasonable confidence that:

- Immediate threat is contained.
- Required credentials are protected.
- Required remediation is complete or appropriately mitigated.
- Necessary validation is complete.
- Business ownership approves restoration where appropriate.

---

# 106. Restricted Restoration

Restoration may occur with temporary restrictions when:

- Business need requires service.
- Full remediation is not complete.
- Compensating controls reduce risk.
- Remaining risk is documented.
- Appropriate approval is obtained.

---

# 107. Compensating Controls

Temporary compensating controls may include:

- Reduced privilege
- Limited connectivity
- Increased review
- Manual approval
- Restricted information access
- Additional monitoring

Compensating controls must be documented and validated.

---

# 108. Risk Acceptance

Residual third-party risk requiring formal acceptance must follow [[POL-005 Risk Management Policy]].

Risk acceptance must not be implied merely because business operations continue.

---

# 109. Provider Replacement

Provider replacement may be considered when:

- Security trust cannot reasonably be restored.
- Repeated incidents demonstrate unacceptable weakness.
- Provider cooperation is inadequate.
- Required remediation is not completed.
- Business risk exceeds approved tolerance.

---

# 110. Provider Termination

Termination must consider:

- Access revocation
- Credential replacement
- Information return
- Information destruction
- Company asset return
- Data migration
- Business continuity
- Contract requirements

---

# 111. Exit Verification

Following provider termination, Dunder Mifflin should verify:

- Accounts disabled
- Remote access removed
- Privileges removed
- Credentials replaced where necessary
- Company assets returned
- Required information returned or disposed of
- Remaining dependencies identified

---

# 112. Incident Closure

A third-party incident may be closed when:

- Immediate company exposure has been addressed.
- Reasonable company scope has been determined.
- Required company containment is complete.
- Required provider actions are understood.
- Required company recovery is complete.
- Material evidence is preserved.
- Required remediation is documented.
- Required validation is complete or remaining gaps are formally tracked.
- Remaining risk is understood.

---

# 113. Provider Closure Does Not Equal Company Closure

A provider closing its own incident does not automatically close Dunder Mifflin's incident.

Company closure depends on company impact, remediation, validation, and remaining risk.

---

# 114. Closure With Provider Unknowns

A company incident may be closed with unresolved provider unknowns when:

- Further information is not reasonably obtainable.
- The unknowns are documented.
- Company exposure has been addressed.
- Remaining uncertainty is reflected in risk.
- Appropriate management accepts remaining risk where required.

---

# 115. Closure Does Not End Corrective Action

Incident closure does not automatically close:

- Provider remediation
- Contractual action
- Access-control remediation
- Vulnerability remediation
- Continuity improvements
- Corrective actions
- Risk treatments
- Provider reassessment

---

# 116. Lessons Learned

Severity 1 and significant Severity 2 third-party incidents require a documented lessons-learned review.

The review should consider:

- Provider notification
- Detection
- Company escalation
- Access containment
- Evidence
- Provider cooperation
- Business continuity
- Recovery
- Remediation
- Validation
- Contract effectiveness

---

# 117. Root Cause

Where evidence permits, likely root cause should be identified.

Possible causes include:

- Provider credential compromise
- Provider malware
- Provider vulnerability
- Provider configuration weakness
- Excessive provider access
- Contractor misuse
- Company integration weakness
- Provider process failure
- Physical loss
- Supply-chain compromise

---

# 118. Contributing Factors

Contributing factors may include:

- Excessive provider privilege
- Incomplete access inventory
- Weak contract requirements
- Delayed notification
- Provider concentration
- Inadequate documentation
- Weak monitoring
- Poor exit planning
- Inadequate provider oversight

---

# 119. Provider Reassessment

A material incident should trigger reassessment of the affected provider.

The reassessment should consider:

- Risk category
- Access
- Information
- Business dependency
- Incident history
- Provider cooperation
- Remediation
- Control effectiveness
- Remaining risk

---

# 120. Critical Provider Review

Critical third parties receive at least annual security review under [[POL-008 Third-Party Security Policy]].

A material incident may require additional review before the next scheduled assessment.

---

# 121. Important Provider Review

Important third parties receive security review at least biennially.

A material incident may justify accelerated reassessment.

---

# 122. Corrective Action

Material deficiencies must identify:

- Deficiency
- Accountable owner
- Required action
- Due date
- Validation method

Material corrective actions are tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 123. Corrective-Action Validation

Corrective action is not complete merely because:

- The provider reports completion.
- A ticket is closed.
- A contract amendment is signed.
- A company action is marked complete.

Required validation must determine whether the intended condition was achieved.

---

# 124. R018 Relationship

R018 addresses Third-Party Technology Failure / Compromise.

Inherent risk is:

**12 High**

Current residual risk is:

**8 Moderate**

Target residual risk after proposed treatment is:

**6 Moderate**

---

# 125. R018 Treatment Support

R018 treatment includes:

- Third-party classification
- Security due diligence
- Contractual security requirements
- Confidentiality obligations
- Incident-notification requirements
- Access limitation
- Security review
- Recovery requirements
- Exit planning
- Incident response

Third-party risk cannot be eliminated solely through contract language.

---

# 126. R019 Relationship

R019 addresses Infinity Contractor Dependency / Compromise.

Inherent risk is:

**12 High**

Current residual risk is:

**8 Moderate**

Target residual risk after proposed treatment is:

**4 Low**

---

# 127. R019 Treatment Support

R019 treatment includes:

- Dunder Mifflin ownership of Infinity assets
- Contractor sponsorship
- Limited access duration
- Confidentiality obligations
- Restricted privileged access
- Controlled Headquarters workspace
- No general contractor VPN for privileged production administration
- Change control
- Security testing
- Documentation
- Annual transferability review

---

# 128. R016 Relationship

R016 addresses Cloud Outage.

Inherent risk is:

**15 High**

Current residual risk is:

**8 Moderate**

Target residual risk after proposed treatment is:

**6 Moderate**

A cloud security incident may create both security and availability impacts.

---

# 129. R020 Relationship

R020 addresses Supplier Disruption.

Inherent risk is:

**16 High**

Current residual risk is:

**9 Moderate**

Target residual risk after proposed treatment is:

**6 Moderate**

A supplier security incident may create operational disruption even when company systems are not compromised.

---

# 130. Other Risk Relationships

This playbook may also support response for:

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
- R027 Backup / Recovery Failure
- R028 Data Corruption
- R029 Vendor Fraud

---

# 131. Current and Proposed Controls

Response records must distinguish among:

- Current controls
- Partially implemented controls
- Planned controls
- Implemented controls awaiting validation
- Validated controls

---

# 132. No Premature Risk Credit

Current residual risk must not be reduced merely because:

- This playbook exists.
- A provider promises remediation.
- A contract is being revised.
- An assessment is scheduled.
- A retained DFIR provider is proposed.
- A provider replacement is planned.

Risk reduction requires implementation and appropriate validation.

---

# 133. Risk Reassessment

Third-party incidents may require reassessment when evidence demonstrates:

- Greater likelihood
- Greater impact
- Provider-control weakness
- Concentration risk
- Excessive access
- Contractual weakness
- Recovery weakness
- New attack path
- Improved control effectiveness

Historical May 2013 risk results must remain preserved.

---

# 134. Operational Metrics

Operational third-party incident metrics may include:

- Third-party security incidents
- Critical-provider incidents
- Late provider notifications
- Provider-access incidents
- Third-party data exposures
- Third-party malware incidents
- Third-party outages with security impact
- Repeat provider incidents
- Open provider corrective actions

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 135. Key Performance Indicators

Key Performance Indicators (KPIs) may include:

- Percentage of material third-party incidents receiving documented company impact assessment
- Percentage of affected provider accounts receiving required containment
- Percentage of material incidents receiving provider reassessment
- Percentage of required provider remediation receiving validation
- Percentage of material corrective actions completed and validated

---

# 136. Key Risk Indicators

Key Risk Indicators (KRIs) may include:

- Increasing Critical-provider incidents
- Repeated late incident notification
- Repeated incidents involving the same provider
- Provider remediation remaining overdue
- Excessive third-party access
- Significant provider concentration
- Repeated third-party data exposure
- Provider failure to supply required incident information

---

# 137. Metric Interpretation

An increase in third-party incident reports may indicate:

- Increased provider incidents
- Improved provider reporting
- Improved contractual notification
- Improved internal detection

Incident count alone does not establish whether third-party risk increased or decreased.

---

# 138. Playbook Exercises

This playbook should be periodically exercised.

Scenarios may include:

- Cloud provider security incident
- Infinity contractor compromise
- Off-site backup provider loses encrypted media
- Payment processor security incident
- Technology vendor reports compromised software
- Critical provider reports ransomware
- Provider account is used to access company systems without authorization

---

# 139. Exercise Objectives

Exercises should evaluate whether responders can:

- Identify provider dependency
- Determine company impact
- Contain provider access
- Protect credentials
- Preserve evidence
- Obtain provider information
- Independently assess company scope
- Coordinate continuity
- Validate remediation
- Reassess provider risk

---

# 140. Exercise Safety

Exercises must not unnecessarily:

- Disable Critical services
- Expose sensitive information
- Create uncontrolled provider access
- Interrupt production
- Alter real provider contracts

Tabletop and controlled simulations should be used where practical.

---

# 141. Playbook Assessment

Assessment may determine whether:

- Provider incidents are identified.
- Company impact is independently assessed.
- Provider access is contained.
- Evidence is preserved.
- Provider information is obtained.
- Company scope is determined.
- Continuity needs are addressed.
- Remediation is validated.
- Provider risk is reassessed.

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

---

# 143. Independent Performance

An assessor may independently perform selected response steps using an authorized scenario.

For example, the assessor may:

1. Receive a simulated provider incident notification.
2. Identify the provider's company access.
3. Determine potential company impact.
4. Identify required containment.
5. Identify evidence requirements.
6. Identify provider questions.
7. Determine continuity requirements.
8. Determine remediation validation.
9. Determine whether provider reassessment is required.
10. Compare the result with expected playbook actions.

---

# 144. Assessment Exceptions

Exceptions may include:

- Material provider incident not escalated
- Company impact not independently assessed
- Provider access left active without justification
- Provider credentials not protected
- Material evidence not preserved
- Provider statement accepted without reasonable company assessment
- Required continuity action omitted
- Provider remediation not validated
- Material provider risk not reassessed

---

# 145. Findings

Material playbook deficiencies must be documented.

Examples include:

- Critical provider incident ignored
- Significant provider access left active despite known compromise
- Provider compromise not evaluated for company impact
- Significant provider data exposure not escalated
- Material evidence deliberately destroyed
- Provider remediation accepted without required validation
- Repeated provider incident left without corrective action

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 146. Control Effectiveness

Third-party incident evidence may support conclusions that relevant controls are:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

The conclusion must reflect actual evidence rather than the existence of a contract or policy alone.

---

# 147. Traceability

This playbook supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

A third-party incident may provide evidence across multiple stages of this chain.

---

# 148. Related Artifacts

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
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-003 Access Review Procedure]]
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
- [[PLN-001 Incident Response Plan]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]
- [[PBK-001 Phishing & Credential Compromise Playbook]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-004 Data Exposure Playbook]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[RPT-004 Infinity Transferability Review]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

---

# 149. Review

This playbook must be reviewed:

- At least annually
- Following a material third-party security incident
- Following significant third-party access change
- Following significant provider or contractual change
- Following material lessons learned
- Following significant assurance findings

The IT & Information Security Manager coordinates review.

Material revisions require CIO approval.

---

# 150. Revision History

| Version | Date     | Description                           | Approval |
| ------- | -------- | ------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Third-Party Incident Playbook | CIO      |