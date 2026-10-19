# GUIDE-003 Acronym & Terminology Guide

## Document Control

| Field | Value |
|---|---|
| Document ID | GUIDE-003 |
| Title | Acronym & Terminology Guide |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | As Repository Terminology Changes |

---

# 1. Purpose

This guide provides standardized definitions for acronyms and terminology used throughout the Dunder Mifflin Enterprise Information Security and Risk Management Program.

Its purposes are to:

- Promote consistent terminology
- Reduce ambiguity
- Help readers unfamiliar with security terminology
- Support repository navigation
- Distinguish concepts that are commonly confused
- Establish the intended meaning of important project terms

Where another controlled artifact establishes a more specific requirement or definition, that artifact remains authoritative for its subject.

---

# 2. Acronym Reference

| Acronym | Meaning |
|---|---|
| AD | Active Directory |
| AP | Access Point |
| AP | Accounts Payable, when used in a financial context |
| AV | Antivirus |
| BC | Business Continuity |
| BC/DR | Business Continuity / Disaster Recovery |
| BCP | Business Continuity Plan |
| BEC | Business Email Compromise |
| BIA | Business Impact Analysis |
| CEO | Chief Executive Officer |
| CFO | Chief Financial Officer |
| CIO | Chief Information Officer |
| COO | Chief Operating Officer |
| CRM | Customer Relationship Management |
| DA | Domain Administrator |
| DFIR | Digital Forensics and Incident Response |
| DNS | Domain Name System |
| DR | Disaster Recovery |
| DRP | Disaster Recovery Plan |
| FDE | Full-Disk Encryption |
| GRC | Governance, Risk, and Compliance |
| HR | Human Resources |
| IAM | Identity and Access Management |
| IP | Intellectual Property, when used in a legal or ownership context |
| IP | Internet Protocol, when used in a networking context |
| IR | Incident Response |
| IRT | Incident Response Team |
| ISRC | Information Security and Risk Committee |
| IT | Information Technology |
| KPI | Key Performance Indicator |
| KRI | Key Risk Indicator |
| MDM | Mobile Device Management |
| MFA | Multifactor Authentication |
| MTD | Maximum Tolerable Downtime |
| NDA | Non-Disclosure Agreement |
| OMS | Order Management System |
| PAN | Primary Account Number |
| PIN | Personal Identification Number |
| RPO | Recovery Point Objective |
| RTO | Recovery Time Objective |
| SDLC | Software Development Lifecycle |
| SIEM | Security Information and Event Management |
| SoD | Separation of Duties |
| TPRM | Third-Party Risk Management |
| UPS | Uninterruptible Power Supply |
| VPN | Virtual Private Network |
| WMS | Warehouse Management System |

---

# 3. Acronym Context

Some acronyms have more than one meaning.

The intended meaning should be determined from context.

For example:

**AP** may mean:

- Access Point in a network or wireless context
- Accounts Payable in a financial context

**IP** may mean:

- Intellectual Property in an ownership or legal context
- Internet Protocol in a networking context

Where ambiguity could reasonably occur, the term should be written out.

---

# 4. Governance, Risk, and Compliance

**Governance, Risk, and Compliance (GRC)** is the coordinated approach used to:

- Establish organizational direction and accountability
- Identify and manage risk
- Establish and maintain requirements
- Evaluate whether requirements are being satisfied
- Support informed management decisions

GRC is not limited to compliance documentation.

Within this program, GRC connects business objectives to security decisions and evidence.

---

# 5. Governance

**Governance** establishes:

- Authority
- Accountability
- Decision rights
- Oversight
- Policy direction
- Risk-management expectations

Governance answers questions such as:

> Who has authority to make this decision?

and:

> Who is accountable for the result?

See:

[[PRO-009 Security Governance Framework]]

---

# 6. Management

**Management** coordinates resources and activities to carry out governance requirements and achieve organizational objectives.

Governance establishes direction and accountability.

Management organizes execution.

---

# 7. Compliance

**Compliance** is the condition of satisfying an applicable:

- Law
- Regulation
- Contract
- Policy
- Standard
- Requirement

Compliance with a requirement does not automatically mean all related security risk has been eliminated.

---

# 8. Risk

**Risk** is uncertainty that may affect business objectives.

Within this program, risk is evaluated using:

**Likelihood × Impact**

See:

[[POL-005 Risk Management Policy]]

and:

[[RPT-003 Enterprise Risk Assessment]]

---

# 9. Risk Scenario

A **risk scenario** describes a condition or event that could adversely affect an organizational objective.

A useful risk scenario identifies:

- What could happen
- What could be affected
- Why the event matters

---

# 10. Threat

A **threat** is a potential cause of an unwanted event.

Examples include:

- External attacker
- Malicious insider
- Malware
- Fire
- Flood
- Utility failure

A threat is not automatically a risk by itself.

---

# 11. Vulnerability

A **vulnerability** is a weakness that may be exploited or contribute to an adverse outcome.

Examples include:

- Missing security update
- Weak configuration
- Excessive access
- Undocumented recovery dependency
- Vulnerable application code

---

# 12. Likelihood

**Likelihood** represents the assessed probability or expected frequency of a risk scenario.

Dunder Mifflin uses an integer scale from:

**1 through 5**

---

# 13. Impact

**Impact** represents the severity of consequences if a risk scenario occurs.

Dunder Mifflin uses an integer scale from:

**1 through 5**

Impact may involve:

- Financial loss
- Operational disruption
- Information compromise
- Legal or contractual consequences
- Reputation
- Safety

---

# 14. Risk Score

The program calculates risk score as:

**Likelihood × Impact**

Scores range from:

**1 through 25**

---

# 15. Risk Rating

| Score | Rating |
|---:|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–16 | High |
| 17–25 | Critical |

---

# 16. Inherent Risk

**Inherent Risk** is risk evaluated before considering existing controls.

It represents the underlying exposure associated with the risk scenario.

Inherent risk remains important even when controls substantially reduce current exposure.

---

# 17. Current Residual Risk

**Current Residual Risk** is the risk remaining after considering controls that currently exist and receive appropriate credit.

Proposed controls do not reduce current residual risk until implementation and effectiveness are supported by evidence and the risk is reassessed.

---

# 18. Target Residual Risk

**Target Residual Risk** is the predicted level of risk expected after proposed treatment is successfully implemented and validated.

Target residual risk is a planning estimate.

It is not a guaranteed future risk rating.

---

# 19. Validated Post-Treatment Risk

**Validated Post-Treatment Risk** is the risk established after treatment has been implemented, evidence has been evaluated, applicable controls have been validated, and the risk has been formally reassessed.

Once approved, this rating may become the new current residual risk.

Historical risk ratings remain preserved.

---

# 20. Risk Owner

A **Risk Owner** is the person or organizational role accountable for managing a particular risk.

Other personnel may perform treatment activities, but participation by several groups does not remove the need for clear accountability.

---

# 21. Risk Treatment

**Risk Treatment** is the selected response to an identified risk.

Primary treatment options are:

- Mitigate
- Transfer
- Avoid
- Accept

See:

[[RTP-001 Enterprise Risk Treatment Plan]]

---

# 22. Mitigate

**Mitigate** means reducing risk through controls that reduce:

- Likelihood
- Impact
- Or both

---

# 23. Transfer

**Transfer** means shifting some financial or operational consequence of a risk to another party.

Examples may include:

- Insurance
- Contractual allocation
- Outsourced services

Risk transfer does not necessarily eliminate the underlying exposure.

---

# 24. Avoid

**Avoid** means discontinuing or not undertaking the activity creating the risk.

---

# 25. Accept

**Accept** means an authorized decision to retain a known risk.

Risk acceptance does not mean:

- The risk disappeared.
- The control became effective.
- A deficiency was corrected.

Acceptance must follow the authority and reassessment requirements established by:

[[POL-005 Risk Management Policy]]

---

# 26. Risk Register

A **Risk Register** is the structured record used to maintain information about identified risks.

The enterprise register is:

[[REG-002 Enterprise Risk Register]]

---

# 27. Risk Assessment

A **Risk Assessment** is the structured process used to identify and evaluate risk.

The enterprise assessment is:

[[RPT-003 Enterprise Risk Assessment]]

---

# 28. Risk Treatment Plan

A **Risk Treatment Plan** records how identified risks will be addressed.

The enterprise treatment plan is:

[[RTP-001 Enterprise Risk Treatment Plan]]

---

# 29. Control

A **Control** is a safeguard or countermeasure used to address a requirement or risk.

Controls may be:

- Administrative
- Technical
- Physical

Controls may perform several functions, including:

- Preventive
- Detective
- Corrective
- Recovery
- Deterrent
- Compensating

---

# 30. Preventive Control

A **Preventive Control** is intended to prevent an unwanted event or condition.

Examples include:

- Access restrictions
- Authentication
- Firewall rules
- Physical locks

---

# 31. Detective Control

A **Detective Control** is intended to identify an event or condition that has occurred or is occurring.

Examples include:

- Security monitoring
- Reconciliation
- Vulnerability scanning
- Access review

---

# 32. Corrective Control

A **Corrective Control** is intended to correct a condition after it has been identified.

Examples include:

- Removing inappropriate access
- Installing a security update
- Correcting configuration

---

# 33. Recovery Control

A **Recovery Control** supports restoration of systems, information, or business processes following disruption.

Examples include:

- Backups
- Recovery procedures
- Disaster recovery capability

---

# 34. Deterrent Control

A **Deterrent Control** discourages unwanted activity.

Examples may include:

- Warning notices
- Visible access controls
- Disciplinary policy

---

# 35. Compensating Control

A **Compensating Control** is an alternate safeguard used when the preferred control cannot reasonably be implemented.

A compensating control should address the intended security objective sufficiently to justify its use.

---

# 36. Control Objective

A **Control Objective** describes the intended security outcome of a control.

The objective answers:

> What should this control accomplish?

---

# 37. Control Owner

A **Control Owner** is the person or organizational role accountable for the control.

The control owner may rely on other personnel to perform operational activities.

---

# 38. Control Inventory

The **Enterprise Security Control Inventory** is the central structured record of security controls.

See:

[[REG-003 Enterprise Security Control Inventory]]

---

# 39. Implementation Status

Implementation status describes where a control is in its deployment lifecycle.

The program uses:

- Planned
- Implementing
- Implemented
- Validation Pending
- Validated

---

# 40. Planned

**Planned** means a control has been identified for future implementation but is not currently operating as an implemented control.

---

# 41. Implementing

**Implementing** means work to establish the control is underway.

Implementation activity does not by itself establish control effectiveness.

---

# 42. Implemented

**Implemented** means the control has been established or deployed.

Implemented does not mean effective.

---

# 43. Validation Pending

**Validation Pending** means implementation has been reported or observed, but sufficient assurance work has not yet established whether the intended outcome is achieved.

---

# 44. Validated

**Validated** means appropriate evidence and assessment support the conclusion that the implemented control operates as evaluated.

Validation remains subject to future change, monitoring, and reassessment.

---

# 45. Control Effectiveness

**Control Effectiveness** describes whether a control achieves its intended objective.

The program uses:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

---

# 46. Effective

**Effective** means evidence supports that the control achieves its intended objective at the level required.

---

# 47. Partially Effective

**Partially Effective** means the control provides meaningful protection but has one or more limitations that prevent full achievement of the intended objective.

---

# 48. Ineffective

**Ineffective** means the control does not provide sufficient support for its intended objective.

---

# 49. Not Implemented

**Not Implemented** means the control is not currently established sufficiently to operate as intended.

---

# 50. Design Effectiveness

**Design Effectiveness** evaluates whether a control, if operated as designed, is capable of achieving its intended objective.

---

# 51. Implementation Effectiveness

**Implementation Effectiveness** evaluates whether the control has actually been established as designed.

---

# 52. Operational Effectiveness

**Operational Effectiveness** evaluates whether the control operates consistently and achieves the intended result.

---

# 53. Defense in Depth

**Defense in Depth** uses multiple complementary controls rather than relying on a single safeguard.

If one control fails, other controls may continue reducing exposure.

---

# 54. Least Privilege

**Least Privilege** means granting only the access required to perform authorized responsibilities.

Access should not be granted merely because it may be convenient in the future.

---

# 55. Need to Know

**Need to Know** limits access to information required for an authorized business purpose.

Authorization to use a system does not automatically create a need to access all information within it.

---

# 56. Separation of Duties

**Separation of Duties (SoD)** divides important responsibilities so one person cannot independently perform incompatible or high-risk activities without appropriate oversight.

Examples include separating:

- Vendor creation from payment
- Payroll preparation from payment approval
- Development from production approval where practical

---

# 57. Accountability

**Accountability** means activity can be attributed to the responsible individual or organizational role.

Individual accounts and attributable transactions support accountability.

---

# 58. Policy

A **Policy** establishes management requirements and expectations.

Policies state what is required.

They generally do not contain every implementation detail.

---

# 59. Standard

A **Standard** defines mandatory requirements supporting policy.

Standards generally provide more specific implementation requirements than policies.

---

# 60. Procedure

A **Procedure** describes how an activity is performed.

Procedures translate requirements into repeatable operational actions.

---

# 61. Program

A **Program** organizes related security activities, governance, responsibilities, and controls around a major security capability.

---

# 62. Plan

A **Plan** coordinates actions for a defined objective, event, or future activity.

Examples include:

- Incident Response Plan
- Business Continuity Plan
- Disaster Recovery Plan
- Annual Assurance Plan

---

# 63. Playbook

A **Playbook** provides scenario-specific response guidance.

Within this repository, playbooks support incident response for defined incident types.

---

# 64. Register

A **Register** is a structured record maintained over time.

Examples include:

- Asset Register
- Risk Register
- Control Inventory
- Finding & Corrective Action Register
- Document Control Register

---

# 65. Report

A **Report** communicates analyzed information, conclusions, status, or decision-relevant information to an intended audience.

---

# 66. Template

A **Template** provides a controlled structure for recurring work.

A blank template is not evidence that the activity occurred.

---

# 67. Artifact

An **Artifact** is a controlled document, record, template, report, plan, register, standard, policy, procedure, playbook, or guide within the security program repository.

---

# 68. Evidence

**Evidence** is information used to support an assessment conclusion.

Examples include:

- Logs
- Configuration records
- Tickets
- Approvals
- Reports
- Test results
- Access records
- Training records
- Backup records

---

# 69. Evidence Relevance

**Relevance** describes whether evidence relates directly to the requirement or control being evaluated.

---

# 70. Evidence Reliability

**Reliability** describes whether evidence can reasonably be trusted.

Factors may include:

- Source
- Integrity
- Independence
- Method of creation
- Ability to corroborate

---

# 71. Evidence Completeness

**Completeness** describes whether enough evidence exists to support the intended conclusion.

---

# 72. Evidence Timeliness

**Timeliness** describes whether evidence relates to the period or condition being evaluated.

---

# 73. Evidence Integrity

**Evidence Integrity** means evidence has been protected sufficiently to support confidence that it accurately represents the recorded condition or activity.

Evidence must not be:

- Fabricated
- Improperly altered
- Backdated
- Manufactured to create the appearance that an activity occurred

---

# 74. Assurance

**Assurance** is the process of obtaining sufficient confidence that requirements and controls are appropriately designed, implemented, operating, and achieving intended outcomes.

The central assurance question is:

> **How do we know the control actually works?**

See:

[[PRO-008 Security Assurance & Continuous Improvement Program]]

---

# 75. Assessment

An **Assessment** is a structured evaluation of a requirement, control, process, system, or security condition using defined methods and evidence.

---

# 76. Assessment Objective

An **Assessment Objective** states what the assessment is intended to determine.

---

# 77. Assessment Scope

**Assessment Scope** identifies what is included and excluded from an assessment.

Scope may define:

- Systems
- Processes
- Locations
- Controls
- Time period
- Personnel
- Evidence

---

# 78. Assessment Work Plan

An **Assessment Work Plan** defines how a specific assessment will be performed.

It may identify:

- Objective
- Scope
- Requirement
- Control
- Evidence
- Method
- Sample
- Procedure
- Expected result
- Reporting

See:

[[TMP-001 Assessment Work Plan Template]]

---

# 79. Inspection

**Inspection** evaluates documents, records, configurations, or other evidence.

---

# 80. Observation

**Observation** evaluates how an activity or control is actually performed.

---

# 81. Interview

An **Interview** gathers information from personnel who understand or perform an activity.

Interview statements may require corroborating evidence depending on the assessment objective and risk.

---

# 82. Sampling

**Sampling** evaluates a selected portion of a larger population when reviewing every item is unnecessary or impractical.

The sample should be appropriate for the assessment objective.

---

# 83. Independent Performance

**Independent Performance** means an assessor performs an approved procedure independently when direct execution provides stronger evidence than reviewing documentation or asking personnel whether the procedure works.

Example:

An assessor may perform an authorized recovery procedure using documented instructions to determine whether the procedure can actually be completed.

---

# 84. Technical Testing

**Technical Testing** uses authorized technical methods to evaluate security conditions or control performance.

Examples include:

- Vulnerability scanning
- Penetration testing
- Configuration testing
- Recovery testing

---

# 85. Exercise

An **Exercise** evaluates plans, procedures, responsibilities, or response capability through a controlled scenario.

---

# 86. Reconciliation

**Reconciliation** compares related records or transactions to identify:

- Missing activity
- Duplicate activity
- Unauthorized changes
- Inconsistencies
- Errors

---

# 87. Finding

A **Finding** is:

> **A documented conclusion supported by evidence concerning whether a requirement, control, process, or expected outcome is satisfied.**

A finding is not merely an unsupported opinion.

---

# 88. Satisfactory

**Satisfactory** means available evidence supports that the assessed requirement or expected outcome is satisfied.

---

# 89. Partially Satisfactory

**Partially Satisfactory** means the requirement or outcome is substantially satisfied, but one or more limitations require attention.

---

# 90. Deficiency

A **Deficiency** is a condition in which a requirement, control, process, or expected outcome is not adequately satisfied.

---

# 91. Significant Deficiency

A **Significant Deficiency** is a deficiency important enough to require elevated management attention because of its potential impact, scope, persistence, or relationship to material risk.

---

# 92. Unable to Determine

**Unable to Determine** means available evidence is insufficient to support a reliable assessment conclusion.

This is not equivalent to satisfactory.

---

# 93. Corrective Action

**Corrective Action** is activity taken to address a documented deficiency.

Corrective action should identify:

- Accountable owner
- Required action
- Target date
- Required evidence
- Validation method

---

# 94. Validation

**Validation** determines whether implementation or corrective action achieved the intended result.

Reported completion does not automatically establish validated completion.

---

# 95. Retest

A **Retest** evaluates a previously identified condition after corrective action to determine whether the deficiency has actually been corrected.

---

# 96. Closure

**Closure** occurs when applicable requirements for resolving a finding or corrective action have been satisfied and appropriate validation has occurred.

Closing a ticket is not by itself evidence that the underlying deficiency was corrected.

---

# 97. Root Cause

**Root Cause** is an underlying condition that contributed to a problem or deficiency.

Correcting only the visible symptom may allow the problem to recur.

---

# 98. Continuous Monitoring

**Continuous Monitoring** is risk-appropriate ongoing awareness of security conditions, control operation, and relevant changes.

It does not mean every system or control must receive continuous human monitoring 24 hours a day.

---

# 99. Continuous Improvement

**Continuous Improvement** is the recurring process of using evidence, assessments, findings, corrective actions, retesting, metrics, and risk reassessment to improve the security program.

---

# 100. Key Performance Indicator

A **Key Performance Indicator (KPI)** measures performance of an activity or process.

Example:

Percentage of required vulnerability assessments completed.

---

# 101. Key Risk Indicator

A **Key Risk Indicator (KRI)** provides information about changing risk exposure.

Example:

Number of overdue Critical vulnerabilities.

---

# 102. Operational Measure

An **Operational Measure** provides information needed to manage or execute security activity.

Not every operational measure needs to become a KPI or KRI.

---

# 103. Metric

A **Metric** is a defined measurement used to support:

- Monitoring
- Management
- Risk evaluation
- Performance evaluation
- Decision-making

See:

[[REG-005 Security Metrics Catalog]]

---

# 104. Business Impact Analysis

A **Business Impact Analysis (BIA)** evaluates the effect of business-process disruption and establishes business recovery requirements.

See:

[[RPT-002 Business Impact Analysis]]

---

# 105. Maximum Tolerable Downtime

**Maximum Tolerable Downtime (MTD)** is the longest period a business process can remain disrupted before the resulting impact becomes unacceptable.

---

# 106. Recovery Time Objective

**Recovery Time Objective (RTO)** is the target amount of time within which a process or capability should be restored following disruption.

RTO should fit within the Maximum Tolerable Downtime.

---

# 107. Recovery Point Objective

**Recovery Point Objective (RPO)** is the maximum acceptable amount of data loss measured in time.

An RPO of four hours means recovery should not require the organization to lose more than approximately four hours of data.

---

# 108. Business Continuity

**Business Continuity (BC)** is the capability to continue important business functions during disruption.

Business continuity may use:

- Alternate processes
- Manual procedures
- Alternate communications
- Alternate personnel
- Alternate locations

---

# 109. Business Continuity Plan

The **Business Continuity Plan (BCP)** coordinates continuity of important business activity during disruption.

See:

[[PLN-002 Business Continuity Plan]]

---

# 110. Disaster Recovery

**Disaster Recovery (DR)** focuses on restoration of technology and supporting capabilities following disruption.

---

# 111. Disaster Recovery Plan

The **Disaster Recovery Plan (DRP)** coordinates restoration of required technology and supporting services.

See:

[[PLN-003 Disaster Recovery Plan]]

---

# 112. BC/DR

**Business Continuity / Disaster Recovery (BC/DR)** refers collectively to continuity of business operations and restoration of supporting technology.

The two concepts are related but are not identical.

---

# 113. Recovery Strategy

A **Recovery Strategy** defines how the organization intends to satisfy established recovery requirements.

The correct sequence is:

**Business Requirement → Criticality → MTD → RTO / RPO → Recovery Strategy → Technical Design → Implementation → Testing**

---

# 114. Recovery Test

A **Recovery Test** evaluates whether recovery capability can satisfy established requirements.

A recovery test should compare actual results against applicable:

- RTO
- RPO
- Functional requirements
- Security requirements

---

# 115. Manual Processing

**Manual Processing** is a controlled temporary method used to continue applicable business activity when normal systems are unavailable.

The Dunder Mifflin manual-processing lifecycle is:

**Collect → Review → Enter → Reconcile → Verify**

See:

[[PROC-013 Manual Processing Procedure]]

---

# 116. Backup

A **Backup** is a protected copy of information or system data maintained to support recovery.

The existence of a backup does not prove successful recoverability.

---

# 117. Restore

A **Restore** retrieves information from a backup and returns it to a usable location or system.

A successful restore is an important component of recovery assurance.

---

# 118. Recovery

**Recovery** is the broader process of returning a system or business capability to an acceptable operational condition following disruption.

Recovery may require more than restoring data.

---

# 119. Cloud Exit

**Cloud Exit** is the planned process for moving services, information, or operational dependency away from a cloud provider when required.

See:

[[PLN-004 Cloud Exit & Emergency Migration Plan]]

---

# 120. Emergency Migration

**Emergency Migration** is an accelerated movement of services or information from an existing provider or environment because continued operation there has become unacceptable or impossible.

---

# 121. Identity and Access Management

**Identity and Access Management (IAM)** is the coordinated management of:

- Identity
- Authentication
- Authorization
- Account lifecycle
- Privileged access
- Access review
- Accountability

See:

[[PRO-003 Identity and Access Management Program]]

---

# 122. Identification

**Identification** is the process of claiming an identity.

Example:

Entering a username.

---

# 123. Authentication

**Authentication** verifies a claimed identity.

Examples include:

- Password
- Smart card
- Personal Identification Number
- Cryptographic credential

---

# 124. Authorization

**Authorization** determines what an authenticated identity is permitted to access or perform.

---

# 125. Multifactor Authentication

**Multifactor Authentication (MFA)** uses more than one authentication factor from different factor categories.

Common categories include:

- Something you know
- Something you have
- Something you are

---

# 126. Smart Card

A **Smart Card** is a physical credential capable of storing and using authentication information.

Within the proposed access-control design, smart cards are used with a PIN or other required secret where supported.

---

# 127. Privileged Account

A **Privileged Account** has elevated authority capable of performing administrative or security-significant activity.

Privileged accounts require stronger control than ordinary user accounts.

---

# 128. Domain Administrator

A **Domain Administrator (DA)** is a highly privileged Active Directory administrative role.

Standing Domain Administrator access is restricted to personnel with documented need.

---

# 129. Break-Glass Access

**Break-Glass Access** is emergency access reserved for circumstances in which normal administrative access cannot satisfy an urgent legitimate requirement.

Such access requires strong protection, accountability, and post-use review.

---

# 130. Joiner-Mover-Leaver

**Joiner-Mover-Leaver** describes the identity lifecycle associated with:

- Joining the organization
- Changing responsibilities
- Leaving the organization

See:

[[PROC-001 Joiner-Mover-Leaver Procedure]]

---

# 131. Dormant Account

A **Dormant Account** is an account that has not been used for a defined period and requires investigation or disabling under established account-management requirements.

---

# 132. Shared Account

A **Shared Account** is an account used by more than one individual.

Shared accounts reduce individual accountability and should be limited to justified situations.

Dunder Mifflin may retain shared Windows workstation accounts in warehouse environments where operationally justified, while significant Warehouse Management System activity requires individual authentication.

---

# 133. Service Account

A **Service Account** is a nonhuman account used by an application, service, scheduled process, or system function.

Service accounts require controlled ownership, privilege, credential management, and review.

---

# 134. Active Directory

**Active Directory (AD)** provides centralized identity, authentication, and directory services for the Windows environment.

---

# 135. Full-Disk Encryption

**Full-Disk Encryption (FDE)** protects information stored on a device by encrypting the storage volume.

It primarily protects data when a device is lost, stolen, or accessed outside normal authorization.

---

# 136. Mobile Device Management

**Mobile Device Management (MDM)** provides centralized management of supported mobile devices.

Capabilities may include:

- Enrollment
- Inventory
- Configuration
- Passcode requirements
- Remote lock
- Remote wipe

---

# 137. Virtual Private Network

A **Virtual Private Network (VPN)** provides an encrypted network connection across an untrusted network.

Within this program, VPN access is used where authorized for external access to nonpublic resources.

Infinity's public customer interface does not require customer VPN access.

---

# 138. Firewall

A **Firewall** controls network traffic according to defined security rules.

The network baseline denies unsolicited inbound access unless specifically authorized.

---

# 139. Network Segmentation

**Network Segmentation** separates network resources or traffic to reduce unnecessary access and exposure.

Segmentation should be based on actual security requirements rather than automatically separating every organizational department.

---

# 140. Access Point

An **Access Point (AP)** provides wireless network connectivity.

The Dunder Mifflin environment has one ceiling-mounted Access Point in the Scranton Headquarters lobby providing Internet-only guest wireless access.

There is no general corporate wireless network.

---

# 141. Rogue Wireless

**Rogue Wireless** refers to unauthorized wireless networking equipment or wireless capability that could bypass approved network controls.

Periodic network discovery includes checking for unauthorized wireless devices.

---

# 142. Antivirus

**Antivirus (AV)** is endpoint protection intended to identify and block known or suspicious malicious software.

The existing environment uses centrally managed commercial antivirus.

---

# 143. Malware

**Malware** is malicious software intended to compromise, disrupt, damage, spy on, or gain unauthorized access to systems or information.

The term includes several forms of malicious software.

---

# 144. Ransomware

**Ransomware** is malware that disrupts access to systems or information, commonly through encryption or other denial of access, and demands payment or another concession.

---

# 145. Phishing

**Phishing** is a social-engineering attack that attempts to deceive a person into:

- Revealing credentials
- Opening malicious content
- Visiting a malicious site
- Authorizing fraudulent activity
- Disclosing sensitive information

---

# 146. Business Email Compromise

**Business Email Compromise (BEC)** is fraud using compromised, spoofed, or deceptive email communications to manipulate business activity.

Common targets include:

- Payments
- Vendor banking changes
- Payroll
- Sensitive information

---

# 147. Vulnerability Management

**Vulnerability Management** is the recurring process of:

**Identify → Evaluate → Prioritize → Remediate → Retest → Report**

See:

[[PRO-004 Vulnerability Management Program]]

---

# 148. Vulnerability Assessment

A **Vulnerability Assessment** identifies and evaluates technical weaknesses in authorized systems or applications.

---

# 149. Vulnerability Scan

A **Vulnerability Scan** uses automated technical methods to identify known or suspected vulnerabilities.

A scan result requires appropriate evaluation and does not automatically establish exploitability.

---

# 150. Penetration Test

A **Penetration Test** is an authorized security assessment that actively evaluates whether vulnerabilities or security weaknesses can be exploited within an approved scope.

See:

[[STD-007 Penetration Testing Standard]]

---

# 151. Retesting

**Retesting** in vulnerability management verifies whether remediation successfully corrected an identified vulnerability.

A vulnerability should not be assumed corrected merely because remediation was reported.

---

# 152. Security Event

A **Security Event** is an observable occurrence that may have security relevance.

Not every security event is an incident.

---

# 153. Security Incident

A **Security Incident** is a security event or series of events requiring coordinated response because confidentiality, integrity, availability, policy, operations, or another protected interest may be materially affected.

---

# 154. Incident Response

**Incident Response (IR)** is the coordinated process used to identify, analyze, contain, eradicate, recover from, and learn from security incidents.

See:

[[PLN-001 Incident Response Plan]]

---

# 155. Incident Response Team

The **Incident Response Team (IRT)** is the coordinated group responsible for performing or directing incident-response activities.

Dunder Mifflin uses a virtual team model rather than a permanently staffed dedicated incident-response department.

---

# 156. Digital Forensics and Incident Response

**Digital Forensics and Incident Response (DFIR)** combines incident-response activities with specialized collection, preservation, examination, and analysis of digital evidence.

The security program proposes a retained DFIR provider as a Critical Security Response Provider.

---

# 157. Containment

**Containment** limits the spread, impact, or continued operation of an incident.

---

# 158. Eradication

**Eradication** removes the identified cause, malicious component, unauthorized access, or other condition sustaining an incident.

---

# 159. Incident Recovery

**Incident Recovery** restores affected systems and business capabilities to an acceptable operational condition after containment and eradication.

---

# 160. Lessons Learned

**Lessons Learned** evaluates what happened, what worked, what failed, and what should change following an incident, exercise, assessment, or other significant event.

Lessons learned should feed corrective action and program improvement.

---

# 161. Security Operations

**Security Operations** coordinates recurring activities used to observe, identify, investigate, and escalate security conditions.

Dunder Mifflin does not assume a dedicated 24-hour Security Operations Center.

---

# 162. Security Operations Center

A **Security Operations Center (SOC)** is a dedicated function that monitors, analyzes, and responds to security events.

The Dunder Mifflin baseline does not include a dedicated SOC.

---

# 163. Security Information and Event Management

**Security Information and Event Management (SIEM)** refers to technology that centralizes and analyzes security-relevant log and event information.

The Dunder Mifflin baseline does not assume an existing SIEM platform.

---

# 164. Logging

**Logging** records system, application, network, authentication, or security activity for operational, investigative, or assurance purposes.

---

# 165. Monitoring

**Monitoring** is the recurring review or automated observation of relevant conditions, events, or control operation.

Monitoring does not automatically require a dedicated 24-hour monitoring center.

---

# 166. Escalation

**Escalation** moves an issue to a person or organizational level with greater authority, responsibility, or decision-making capability.

---

# 167. Information Classification

**Information Classification** assigns information to a defined sensitivity category so appropriate protection requirements can be applied.

Dunder Mifflin uses:

- Public
- Internal
- Confidential
- Restricted

---

# 168. Public

**Public** information is approved for unrestricted public disclosure.

---

# 169. Internal

**Internal** information is intended primarily for Dunder Mifflin business use and is not generally intended for unrestricted public distribution.

---

# 170. Confidential

**Confidential** information requires protection because unauthorized disclosure, alteration, or loss could create material business or individual harm.

---

# 171. Restricted

**Restricted** information requires the strongest protection within the classification model because unauthorized access could create significant harm.

---

# 172. Primary Account Number

A **Primary Account Number (PAN)** is the payment-card number associated with a payment card account.

Dunder Mifflin does not retain full PAN as part of the defined payment-processing model.

The payment processor stores payment-card information while Dunder Mifflin retains limited tokenized information such as:

- Token
- Card brand
- Last four digits
- Expiration information

as applicable.

---

# 173. Token

A **Token** is a substitute value used in place of sensitive payment information.

Within this program, the payment token is classified as Confidential.

A token is not treated as equivalent to storing full PAN.

---

# 174. Encryption

**Encryption** transforms information using cryptographic methods so unauthorized parties cannot readily interpret it.

Encryption supports confidentiality but does not replace:

- Authorization
- Access control
- Integrity protection
- Monitoring
- Secure handling

---

# 175. Hash

A **Hash** is a fixed-length value derived from data using a cryptographic hash function.

Hashes can support integrity verification.

---

# 176. SHA-256

**SHA-256** is a cryptographic hash function used where practical to support evidence-integrity verification.

A matching hash supports confidence that the evaluated data has not changed between hash calculations.

---

# 177. Confidentiality

**Confidentiality** protects information from unauthorized disclosure.

---

# 178. Integrity

**Integrity** protects information and systems from unauthorized or improper modification or destruction and supports confidence in accuracy and completeness.

---

# 179. Availability

**Availability** means information, systems, facilities, or business capabilities are accessible and usable when required.

---

# 180. Facility Availability

**Facility Availability** concerns whether a physical location can support required business activity.

---

# 181. System Availability

**System Availability** concerns whether a technology system or service is operational and accessible.

---

# 182. Business-Process Availability

**Business-Process Availability** concerns whether the business can continue performing a required function.

A system outage does not always mean the business process is completely unavailable if an acceptable manual process exists.

---

# 183. Non-Disclosure Agreement

A **Non-Disclosure Agreement (NDA)** is an enforceable confidentiality agreement used to protect sensitive information disclosed to another party.

Dunder Mifflin requires an NDA or equivalent enforceable confidentiality obligation before a nonemployee or outside party receives sensitive access when appropriate to the access and information involved.

An NDA does not replace technical or physical controls.

---

# 184. Third Party

A **Third Party** is an external organization or individual providing goods, services, support, access, or another business dependency.

Examples may include:

- Cloud providers
- Application contractors
- IT service providers
- Suppliers
- Professional services
- Payment processors

---

# 185. Third-Party Risk Management

**Third-Party Risk Management (TPRM)** is the structured management of risk arising from external organizations and service providers.

See:

[[POL-008 Third-Party Security Policy]]

---

# 186. Critical Third Party

A **Critical Third Party** is a provider whose failure, compromise, access, or unavailability could materially affect important Dunder Mifflin operations or security.

Critical third parties receive greater oversight than routine providers.

---

# 187. Third-Party Classification

The program uses:

- Critical
- Important
- Routine

to support risk-based third-party oversight.

---

# 188. Due Diligence

**Due Diligence** is the evaluation performed before or during a business relationship to understand whether a party can reasonably satisfy relevant business, security, legal, or contractual requirements.

---

# 189. Secure Software Development Lifecycle

The **Secure Software Development Lifecycle (Secure SDLC)** integrates security activities throughout software:

- Planning
- Design
- Development
- Testing
- Release
- Maintenance
- Retirement

See:

[[PRO-007 Secure Software Development Lifecycle Program]]

---

# 190. Infinity

**Infinity** is Dunder Mifflin's internally owned customer ordering application.

Dunder Mifflin retains ownership of applicable:

- Source code
- Repository
- Intellectual property
- Application data
- Documentation
- Work product
- Backups

A third-party contractor provides support.

---

# 191. Threat Modeling

**Threat Modeling** is a structured process for identifying potential security threats, trust boundaries, attack paths, and required safeguards during application design or change.

---

# 192. STRIDE

**STRIDE** is a threat-modeling framework addressing:

- Spoofing
- Tampering
- Repudiation
- Information Disclosure
- Denial of Service
- Elevation of Privilege

The Infinity secure-development process may use a lightweight STRIDE-based approach.

---

# 193. Development Environment

A **Development Environment** is used to create and modify software.

It should be appropriately separated from production.

---

# 194. Test Environment

A **Test Environment** is used to validate software changes before authorized production release.

---

# 195. Production Environment

A **Production Environment** is the live environment used to provide actual business services.

Production access and change require stronger control because errors or unauthorized activity may directly affect business operations.

---

# 196. Code Review

**Code Review** evaluates software changes for:

- Correctness
- Quality
- Security
- Maintainability
- Compliance with development requirements

---

# 197. Secure Change

A **Secure Change** is an authorized technology or application change that follows applicable:

- Review
- Testing
- Approval
- Documentation
- Deployment
- Verification
- Rollback requirements

---

# 198. Transferability

**Transferability** is the ability to transfer application support or operational responsibility to another qualified party without unacceptable dependency on the current provider.

For Infinity, transferability includes control of:

- Source
- Repository
- Documentation
- Configuration
- Credentials
- Dependencies
- Recovery information
- Organizational knowledge

See:

[[RPT-004 Infinity Transferability Review]]

---

# 199. Key-Person Dependency

**Key-Person Dependency** exists when important capability depends excessively on one individual.

Controls may include:

- Documentation
- Cross-training
- Alternate personnel
- Delegated authority
- Organizational ownership of credentials and information

---

# 200. Configuration Management

**Configuration Management** is the controlled establishment, maintenance, documentation, and change of system configuration.

---

# 201. Configuration Baseline

A **Configuration Baseline** is an approved set of configuration requirements used as a reference for maintaining systems consistently.

---

# 202. Change Management

**Change Management** controls technology or configuration changes to reduce:

- Unauthorized change
- Operational failure
- Security weakness
- Uncontrolled production impact

See:

[[POL-007 Change & Configuration Management Policy]]

---

# 203. Standard Change

A **Standard Change** is a routine, understood, authorized change performed through an established process.

---

# 204. Normal Change

A **Normal Change** requires appropriate review, testing, approval, implementation, and verification before completion.

---

# 205. Emergency Change

An **Emergency Change** is an urgent change that cannot reasonably follow the complete normal timeline without creating unacceptable business or security impact.

Emergency changes remain subject to:

- Authorization
- Documentation
- Verification
- Post-change review

---

# 206. Rollback

**Rollback** returns a system or configuration toward the previous known condition when a change produces unacceptable results.

---

# 207. Patch Management

**Patch Management** is the controlled process used to:

- Identify
- Evaluate
- Test
- Schedule
- Deploy
- Monitor

software and security updates.

---

# 208. Hardening

**Hardening** reduces unnecessary system exposure through secure configuration.

Hardening may include:

- Removing unnecessary services
- Restricting access
- Applying secure configuration
- Reducing unnecessary privileges
- Disabling unnecessary functionality

---

# 209. Business Email Filtering

**Email Filtering** uses technical controls to identify or block unwanted or malicious email based on available characteristics.

Improved filtering may address:

- Known malicious senders
- Suspicious links
- Malicious attachments
- Spoofed messages
- Common phishing indicators

---

# 210. Endpoint

An **Endpoint** is a user or operational computing device connected to or managed as part of the enterprise technology environment.

Examples include:

- Desktop computers
- Laptops
- Supported mobile devices
- Warehouse workstations

---

# 211. Server

A **Server** provides centralized computing, application, authentication, file, infrastructure, or other services.

---

# 212. Cloud Service

A **Cloud Service** is computing capability delivered using externally hosted infrastructure or services.

Dunder Mifflin uses a cloud-first architecture but is not cloud-only.

---

# 213. Data Center

A **Data Center** is a facility designed to host significant computing infrastructure.

Dunder Mifflin Headquarters is not treated as a major company data center.

---

# 214. Uninterruptible Power Supply

An **Uninterruptible Power Supply (UPS)** provides temporary battery-backed electrical power during a utility interruption.

Dunder Mifflin uses UPS protection for critical network equipment and selected management and Sales workstations with approximately 30 minutes of expected support.

UPS capability is not equivalent to generator-backed long-duration power.

---

# 215. Environmental Control

**Environmental Control** protects facilities and equipment from conditions such as:

- Fire
- Water
- Excessive heat
- Power disruption
- Heating, ventilation, and air-conditioning failure

---

# 216. Restricted Area

A **Restricted Area** is a physical area requiring stronger access control because of the sensitivity or value of the assets located there.

Examples may include:

- Significant Information Technology areas
- Sensitive record storage
- Warehouse high-value cages

---

# 217. Controlled Area

A **Controlled Area** is a nonpublic area requiring authorized access but not necessarily the strongest Restricted-area controls.

---

# 218. Public Area

A **Public Area** is an area intended for normal access by customers, visitors, or members of the public without granting access to controlled business spaces.

---

# 219. Visitor

A **Visitor** is a person who does not have normal authorized employee access to the facility or area being entered.

Visitors may require:

- Registration
- Sponsorship
- Escort
- Temporary credentials
- Access restrictions

depending on the circumstances.

---

# 220. Physical Access Review

A **Physical Access Review** evaluates whether physical access remains appropriate for the individuals holding:

- Access cards
- Keys
- Restricted-area permissions
- Other physical credentials

---

# 221. Inventory Movement

**Inventory Movement** refers to the receiving, storage, transfer, picking, shipping, or other controlled movement of physical inventory.

The term is used consistently instead of unnecessarily indirect wording.

---

# 222. Reconciliation

In an operational or financial context, **Reconciliation** compares related records to identify:

- Missing transactions
- Duplicate transactions
- Unauthorized changes
- Inconsistencies
- Errors

Reconciliation is important in:

- Inventory
- Order processing
- Accounts payable
- Payroll
- Manual continuity

---

# 223. Fraud

**Fraud** is intentional deception or manipulation for unauthorized benefit.

Enterprise risks include scenarios involving:

- Vendor fraud
- Sales fraud
- Payroll fraud
- Inventory theft

---

# 224. Business Process

A **Business Process** is a coordinated series of activities used to achieve a business objective.

Business processes may depend on several systems, people, facilities, and third parties.

---

# 225. Asset

An **Asset** is something of value to the organization or something required to support business objectives.

Assets may include:

- Information
- Systems
- Applications
- Facilities
- People
- Processes
- Inventory
- Third parties
- Recovery resources

---

# 226. Asset Owner

An **Asset Owner** is accountable for the business use, importance, and protection requirements of an asset.

The asset owner does not necessarily operate the technology supporting the asset.

---

# 227. Custodian

A **Custodian** performs operational or technical activities on behalf of an asset owner.

Examples may include:

- Information Technology administrators
- Cloud providers
- Records personnel

Ownership and custody are distinct.

---

# 228. Criticality

**Criticality** represents the importance of a process or capability to continued business operation.

The BIA uses:

- Critical
- High
- Moderate
- Low

---

# 229. Dependency

A **Dependency** is a resource, system, person, provider, facility, or condition required for another process or capability to operate successfully.

---

# 230. Single Point of Dependency

A **Single Point of Dependency** exists when one resource, person, provider, or capability can prevent an important function from operating because an adequate alternative does not exist.

---

# 231. Resilience

**Resilience** is the ability to withstand disruption, continue important activity, recover, and adapt.

Resilience may involve:

- Geographic distribution
- Alternate personnel
- Backups
- Manual processes
- Alternate communications
- Supplier alternatives
- Recovery planning

---

# 232. Exception

An **Exception** is an authorized departure from a security requirement.

An exception should identify:

- Requirement
- Rationale
- Risk
- Approval
- Compensating controls where applicable
- Duration
- Review or expiration

An exception does not erase the underlying requirement.

---

# 233. Escalation Threshold

An **Escalation Threshold** is a defined condition that requires an issue to be brought to a higher level of authority or management attention.

---

# 234. Reporting Level

A **Reporting Level** identifies the audience and type of information appropriate for security reporting.

Dunder Mifflin uses:

- Operational
- Management
- Executive

---

# 235. Operational Reporting

**Operational Reporting** focuses on:

- Execution
- Evidence
- Exceptions
- Technical detail

See:

[[RPT-008 Operational Security Report & Dashboard]]

---

# 236. Management Reporting

**Management Reporting** focuses on:

- Accountability
- Performance
- Corrective action
- Trends
- Escalation

See:

[[RPT-007 Management Security Report]]

---

# 237. Executive Reporting

**Executive Reporting** focuses on:

- Enterprise risk
- Business impact
- Significant exposure
- Decisions
- Resources

See:

[[RPT-006 Executive Security Summary]]

---

# 238. Reporting Chain

The program reporting chain is:

**Technical Evidence → Operational Exception → Management Impact → Enterprise Risk → Executive Decision**

---

# 239. Information Security and Risk Committee

The **Information Security and Risk Committee (ISRC)** provides cross-functional governance and review for significant security and risk matters.

Responsibilities include supporting:

- Risk review
- Risk acceptance
- Treatment prioritization
- Cross-functional coordination
- Executive decision-making

---

# 240. Critical Control

A **Critical Control** is a control whose failure could materially increase significant enterprise risk or impair an important business or security capability.

Critical controls may receive greater assurance priority.

---

# 241. Annual Assurance Plan

The **Annual Assurance Plan** establishes the risk-based schedule for security assessment activity.

See:

[[PLN-005 Annual Assurance Plan]]

Assessment priority considers factors including:

- Inherent risk
- Current residual risk
- Business criticality
- Control importance
- Previous findings
- Material change

---

# 242. Operational Security Checklist

The **Operational Security Checklist** provides a structured method for recurring operational review.

See:

[[TMP-002 Operational Security Checklist]]

A blank checklist is not evidence that the review occurred.

---

# 243. Corrective Action Register

The **Finding & Corrective Action Register** maintains material deficiencies and related remediation activity.

See:

[[REG-004 Finding & Corrective Action Register]]

---

# 244. Document Control

**Document Control** establishes consistent management of controlled artifacts, including:

- Identification
- Version
- Status
- Ownership
- Approval
- Classification
- Review

See:

[[REG-006 Document Control Register]]

---

# 245. Version

A **Version** identifies the revision state of an artifact.

The project generally uses:

- 0.x for draft development
- 1.0 for initial approved release
- 1.1 for minor revision
- 2.0 for significant revision

Version changes should reflect actual document history rather than invented revisions.

---

# 246. Effective Date

The **Effective Date** identifies when an approved controlled artifact becomes applicable.

---

# 247. Review Frequency

**Review Frequency** identifies when an artifact should be evaluated for continued accuracy and suitability.

A scheduled review does not require unnecessary revision when the document remains appropriate.

---

# 248. Classification

Within document control, **Classification** identifies the information-handling category assigned to the artifact.

---

# 249. Approved

**Approved** means the appropriate authority has accepted the artifact as an official part of the security program.

Approval of a document does not prove every control described within it is implemented.

---

# 250. Active

**Active** means a register, index, or similar artifact is currently maintained as part of the security program.

---

# 251. Historical Integrity

**Historical Integrity** means preserving the actual sequence of security decisions and results rather than rewriting earlier records when conditions improve.

Preserve applicable:

- Original risk ratings
- Failed tests
- Findings
- Corrective actions
- Retests
- Revised assessments

---

# 252. Traceability

**Traceability** is the ability to follow a requirement or security issue through related program artifacts and activities.

The full program traceability model is:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

---

# 253. Business Requirement

A **Business Requirement** describes something the organization needs in order to achieve its objectives.

Security requirements should ultimately support business requirements.

---

# 254. Security Requirement

A **Security Requirement** defines a protection or assurance condition needed to support business, risk, legal, contractual, or policy objectives.

---

# 255. Technical Evidence

**Technical Evidence** is system-generated or technically derived information used to support security operations or assurance.

Examples include:

- Logs
- Scan results
- Configuration output
- Authentication records
- Backup records

---

# 256. Operational Exception

An **Operational Exception** is a condition identified during security operation that differs from expected or required performance and may require investigation, correction, escalation, or formal assessment.

---

# 257. Management Impact

**Management Impact** describes why an operational or technical condition matters to:

- Accountability
- Performance
- Resources
- Deadlines
- Business operations
- Risk

---

# 258. Enterprise Risk

**Enterprise Risk** is risk significant enough to affect organizational objectives or require coordinated business-level management.

---

# 259. Executive Decision

An **Executive Decision** is a leadership decision involving matters such as:

- Risk acceptance
- Priority
- Funding
- Resource allocation
- Business interruption
- Strategic direction

---

# 260. No Premature Risk Credit

**No Premature Risk Credit** is the program principle that planned, approved, or partially implemented controls do not automatically reduce current residual risk.

Risk reduction must be supported by actual control implementation, appropriate evidence, validation, and risk reassessment.

---

# 261. No Manufactured Evidence

**No Manufactured Evidence** is the assurance principle that documentation must not falsely imply that an activity, test, review, or control operation occurred.

Do not:

- Fabricate records
- Backdate records
- Invent successful test results
- Populate blank registers with fictional operational evidence
- Alter failed results to create the appearance of success

---

# 262. Safety Priority

**Safety Priority** means human life and safety take precedence over:

- Systems
- Operations
- Facilities
- Equipment
- Inventory
- Revenue
- Other organizational assets

---

# 263. Repository

The **Repository** is the organized collection of controlled artifacts making up the Dunder Mifflin Enterprise Information Security and Risk Management Program.

See:

[[GUIDE-002 Project Artifact Map]]

---

# 264. Artifact Index

The **Artifact Index** provides the central list of controlled artifacts and their repository locations.

See:

[[INDEX-001 Artifact Index]]

---

# 265. Cross-Reference Matrix

The **Cross-Reference Matrix** records and validates important relationships among controlled artifacts.

See:

[[REG-007 Cross-Reference Matrix]]

---

# 266. GRC Learning Path

The **GRC Learning Path** explains the security program in the order a learner should understand its concepts.

See:

[[GUIDE-001 GRC Learning Path]]

---

# 267. CISSP

**Certified Information Systems Security Professional (CISSP)** is a professional information security certification organized around eight security domains.

The project maps its activities to those domains in:

[[RPT-005 CISSP Domain Crosswalk]]

---

# 268. CISSP Domain 1

**Security and Risk Management**

Includes concepts involving:

- Governance
- Risk
- Policy
- Compliance
- Ethics
- Awareness
- Business continuity concepts

---

# 269. CISSP Domain 2

**Asset Security**

Includes concepts involving:

- Asset ownership
- Information classification
- Handling
- Retention
- Protection

---

# 270. CISSP Domain 3

**Security Architecture and Engineering**

Includes concepts involving:

- Security design
- Architecture
- Cryptography
- System security
- Engineering principles

---

# 271. CISSP Domain 4

**Communication and Network Security**

Includes concepts involving:

- Network architecture
- Network security
- Communications
- Secure connectivity

---

# 272. CISSP Domain 5

**Identity and Access Management**

Includes concepts involving:

- Identity
- Authentication
- Authorization
- Account lifecycle
- Access review
- Privileged access

---

# 273. CISSP Domain 6

**Security Assessment and Testing**

Includes concepts involving:

- Assessment
- Testing
- Vulnerability assessment
- Penetration testing
- Evidence
- Assurance

---

# 274. CISSP Domain 7

**Security Operations**

Includes concepts involving:

- Monitoring
- Incident response
- Vulnerability remediation
- Recovery
- Operational security
- Physical security

---

# 275. CISSP Domain 8

**Software Development Security**

Includes concepts involving:

- Secure development
- Application security
- Secure change
- Code review
- Application assessment
- Development access

---

# 276. Final Terminology Principle

Security terminology should improve understanding rather than make simple ideas unnecessarily complicated.

When a specialized term is needed:

1. Use it consistently.
2. Define it clearly.
3. Connect it to the business purpose.
4. Avoid using different terms for the same concept without a reason.
5. Distinguish similar concepts when the difference affects decisions.

The terminology principle for this repository is:

> **Use precise language so requirements, responsibilities, evidence, and risk decisions mean the same thing to everyone who relies on them.**

---

# 277. Related Artifacts

## Repository Reference

- [[README]]
- [[INDEX-001 Artifact Index]]
- [[REG-006 Document Control Register]]
- [[REG-007 Cross-Reference Matrix]]
- [[GUIDE-001 GRC Learning Path]]
- [[GUIDE-002 Project Artifact Map]]

## Enterprise Context

- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[REG-001 Enterprise Asset Register]]
- [[STD-001 Information Classification Standard]]
- [[RPT-002 Business Impact Analysis]]

## Risk Management

- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]

## Governance and Policy

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-009 Security Governance Framework]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-012 Application & Secure Development Policy]]

## Security Architecture

- [[PRO-002 Enterprise Security Architecture Program]]
- [[STD-002 Network Security Standard]]
- [[STD-003 Endpoint Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]

## Identity and Access Management

- [[PRO-003 Identity and Access Management Program]]
- [[PROC-001 Joiner-Mover-Leaver Procedure]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-003 Access Review Procedure]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]

## Vulnerability and Security Assessment

- [[PRO-004 Vulnerability Management Program]]
- [[PROC-006 Vulnerability Assessment Procedure]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]
- [[STD-007 Penetration Testing Standard]]

## Security Operations and Incident Response

- [[PRO-005 Security Operations Program]]
- [[PROC-008 Security Monitoring Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[PLN-001 Incident Response Plan]]

## Business Continuity and Disaster Recovery

- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-013 Manual Processing Procedure]]
- [[TMP-003 Recovery Test Template]]

## Physical and Personnel Security

- [[PRO-006 Physical & Personnel Security Program]]
- [[PROC-014 Facility Access Procedure]]
- [[PROC-015 Visitor & Vendor Access Procedure]]
- [[PROC-016 Restricted Area Access Procedure]]
- [[PROC-017 Personnel Security Procedure]]

## Secure Development

- [[PRO-007 Secure Software Development Lifecycle Program]]
- [[STD-009 Infinity Security Standard]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-019 Application Security Assessment Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]
- [[RPT-004 Infinity Transferability Review]]

## Assurance, Metrics, and Improvement

- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[PLN-005 Annual Assurance Plan]]
- [[TMP-001 Assessment Work Plan Template]]
- [[TMP-002 Operational Security Checklist]]
- [[RPT-005 CISSP Domain Crosswalk]]

## Reporting

- [[RPT-006 Executive Security Summary]]
- [[RPT-007 Management Security Report]]
- [[RPT-008 Operational Security Report & Dashboard]]

---

# 278. Revision History

| Version | Date     | Description                         | Approval |
| ------- | -------- | ----------------------------------- | -------- |
| 1.0     | May 2013 | Initial Acronym & Terminology Guide | CEO      |