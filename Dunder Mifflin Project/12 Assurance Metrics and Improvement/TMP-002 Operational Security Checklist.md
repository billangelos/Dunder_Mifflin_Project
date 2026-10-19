# TMP-002 Operational Security Checklist

## Document Control

| Field | Value |
|---|---|
| Document ID | TMP-002 |
| Title | Operational Security Checklist |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved Template |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Operational Security Process Change |

---

# 1. Purpose

This checklist provides a structured method for documenting recurring operational security activities.

It helps Dunder Mifflin determine whether required security activities are:

- Performed
- Documented
- Reviewed
- Escalated when necessary
- Supported by evidence

---

# 2. Checklist Principle

A checked box represents an activity that was actually performed or verified.

It must not represent:

- Intended activity
- Assumed activity
- Planned activity
- Unverified activity

---

# 3. No Fabricated Completion

Personnel must not mark an activity complete unless sufficient evidence supports completion.

Do not:

- Precheck items.
- Backdate completion.
- Invent evidence.
- Conceal exceptions.
- Mark failed activity as successful.
- Mark an unperformed activity Not Applicable merely to complete the checklist.

---

# 4. Checklist Identification

| Field | Entry |
|---|---|
| Checklist ID | |
| Reporting Period | |
| Date Started | |
| Date Completed | |
| Completed By | |
| Reviewed By | |
| Business / Facility Scope | |
| Systems in Scope | |
| Classification | |

---

# 5. Recommended Checklist ID

Use:

**OSC-[Year]-[Number]**

Example:

**OSC-2013-001**

---

# 6. Status Values

Use the following status values:

| Status | Meaning |
|---|---|
| Complete | Required activity was performed and supported by evidence. |
| Exception | Activity was performed or reviewed and a condition requiring attention was identified. |
| Not Complete | Required activity was not completed. |
| Not Applicable | Requirement does not apply to the defined scope or period. |
| Pending | Activity is legitimately awaiting completion within its required period. |

---

# 7. Not Applicable

Not Applicable should include a short explanation when applicability would not otherwise be obvious.

---

# 8. Pending

Pending must not be used to conceal overdue activity.

Once the required completion period has passed, the condition should be identified as Not Complete or Exception as appropriate.

---

# 9. Evidence

Each completed material activity should identify sufficient supporting evidence.

Examples include:

- System records
- Logs
- Reports
- Tickets
- Access records
- Review records
- Backup records
- Vulnerability results
- Incident records
- Change records
- Training records
- Visitor records
- Assessment records

---

# 10. Evidence Reference

Use evidence references that allow an authorized reviewer to locate the supporting record without unnecessarily embedding sensitive information in this checklist.

---

# 11. Exception Handling

An exception identified through this checklist must be evaluated to determine whether it requires:

- Routine correction
- Management attention
- Security event escalation
- Formal finding
- Corrective action
- Risk reassessment

---

# 12. Finding Relationship

A checklist exception does not automatically become a formal finding.

Material control deficiencies requiring corrective action should be recorded in:

[[REG-004 Finding & Corrective Action Register]]

---

# 13. Incident Relationship

Suspected active compromise must be escalated under:

- [[PROC-010 Security Event Escalation Procedure]]
- [[PLN-001 Incident Response Plan]]

---

# 14. Risk Relationship

Material operational exceptions may provide evidence supporting reassessment of risks maintained in:

[[REG-002 Enterprise Risk Register]]

---

# 15. Frequency

This checklist contains activities with different frequencies.

Personnel should complete the sections applicable to the current reporting period.

---

# 16. Frequency Categories

Checklist activities may be:

- Event-driven
- Daily or as operationally required
- Weekly
- Monthly
- Quarterly
- Every 6 months
- Annual

---

# 17. Identity and Access Management

## Monthly / Event-Driven IAM Checklist

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| New accounts were supported by appropriate authorization. | Monthly | | | |
| Access granted to new personnel reflected approved business need. | Monthly | | | |
| Employee transfers were processed through the required revoke-and-reauthorize process. | Event-Driven / Monthly Review | | | |
| Terminated employee logical access was disabled promptly. | Event-Driven / Monthly Review | | | |
| Contractor accounts remained within approved duration. | Monthly | | | |
| Dormant accounts reaching 30 days were investigated. | Monthly | | | |
| Applicable dormant accounts reaching 60 days were disabled unless approved justification existed. | Monthly | | | |
| Emergency-access events were reviewed. | Event-Driven / Monthly | | | |
| Shared warehouse Windows accounts remained limited to approved operational use. | Monthly | | | |
| Significant Warehouse Management System transactions remained individually attributable. | Monthly | | | |

---

# 18. Privileged Access

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Privileged accounts remained individually assigned. | Monthly | | | |
| Administrative personnel used separate privileged credentials from ordinary user credentials. | Monthly | | | |
| Standing Domain Administrator access remained restricted to authorized personnel. | Monthly | | | |
| Privileged access remained appropriate to current responsibilities. | Quarterly | | | |
| Quarterly privileged-access review was completed. | Quarterly | | | |
| Dedicated administrative workstations remained appropriately controlled. | Monthly | | | |
| Unauthorized external remote privileged administration was not identified. | Monthly | | | |
| Break-glass credentials remained controlled under required dual-custody arrangements. | Quarterly | | | |
| Emergency privileged access was reviewed after use. | Event-Driven | | | |

---

# 19. IAM Escalation Conditions

Investigate or escalate conditions including:

- Unauthorized privileged account
- Terminated user retaining access
- Contractor access beyond authorized duration
- Unexplained emergency-access use
- Dormant account remaining active without justification
- Significant transaction lacking individual attribution
- Unauthorized shared credential

---

# 20. Vulnerability Management

## Monthly Vulnerability Checklist

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Scheduled internal vulnerability assessment was completed. | Monthly | | | |
| Assessment scope reflected applicable systems. | Monthly | | | |
| Scan failures or excluded systems were reviewed. | Monthly | | | |
| Critical vulnerabilities were assigned for remediation. | Monthly | | | |
| High vulnerabilities were assigned for remediation. | Monthly | | | |
| Remediation deadlines were tracked. | Monthly | | | |
| Required retesting was completed for remediated vulnerabilities. | Monthly / As Required | | | |
| Approved exceptions remained current. | Monthly | | | |

---

# 21. Vulnerability Remediation Targets

| Severity | Target |
|---|---|
| Critical | 7 days |
| High | 30 days |
| Moderate | 45 days |
| Low | 60 days |

---

# 22. Vulnerability Escalation Conditions

Escalate as appropriate when:

- Critical vulnerability exceeds 7 days.
- High vulnerability exceeds 30 days.
- Repeated remediation fails.
- Material systems cannot be assessed.
- A vulnerability indicates suspected compromise.
- A systemic configuration weakness is identified.

---

# 23. Endpoint Security

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Managed endpoints reported to the approved antivirus management system. | Weekly / Monthly Summary | | | |
| Malware definitions remained current. | Weekly | | | |
| Unresolved malware detections were investigated. | Weekly | | | |
| Company laptops remained protected by full-disk encryption. | Monthly | | | |
| Standard users remained without unnecessary local administrative privileges. | Monthly / Sampled | | | |
| Required screen-lock controls remained configured. | Monthly / Sampled | | | |
| Managed mobile devices remained enrolled where required. | Monthly | | | |
| Lost or stolen devices were handled under required security procedures. | Event-Driven | | | |

---

# 24. Malware Response

When malware is identified:

- Follow [[PROC-009 Malware Response Procedure]].
- Escalate suspected incidents under [[PROC-010 Security Event Escalation Procedure]].
- Use [[PBK-002 Malware & Ransomware Playbook]] where applicable.

---

# 25. Network Security

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Firewall and router configurations remained under approved control. | Monthly | | | |
| Unsolicited inbound Internet traffic remained denied unless specifically authorized. | Monthly / Sampled | | | |
| No unauthorized administrative services were directly exposed to the public Internet. | Monthly | | | |
| Material firewall-rule changes had required authorization. | Monthly | | | |
| Critical network-device configuration backups remained current. | Monthly | | | |
| Network discovery was completed as scheduled. | Every 6 Months | | | |
| Rogue wireless assessment was completed as scheduled. | Every 6 Months | | | |
| Unexpected network devices were investigated. | Event-Driven | | | |

---

# 26. Wireless Baseline

Expected wireless infrastructure:

- No corporate wireless network
- One ceiling-mounted Internet-only guest wireless access point in the Scranton Headquarters lobby

Any additional wireless access point requires investigation and authorization.

---

# 27. Remote Access

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Remote access remained limited to authorized business purposes. | Monthly | | | |
| VPN access remained restricted to approved use. | Monthly | | | |
| Contractor access remained within approved method and location restrictions. | Monthly | | | |
| Unauthorized external remote privileged administration was not identified. | Monthly | | | |

---

# 28. Security Monitoring

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Required security records were reviewed according to established procedures. | Weekly / Monthly | | | |
| Material authentication exceptions were investigated. | Weekly / Monthly | | | |
| Malware events were reviewed. | Weekly | | | |
| Material network-security events were reviewed. | Weekly / Monthly | | | |
| Monitoring-source failures were investigated. | Monthly | | | |
| Material security events were escalated appropriately. | Event-Driven | | | |
| After-hours security events received appropriate response. | Event-Driven | | | |

---

# 29. Monitoring Model

Dunder Mifflin does not operate a 24-hour Security Operations Center.

Operational review and escalation must reflect the approved Security Operations model rather than implying continuous staffed monitoring.

---

# 30. Security Event Review

Security events should be evaluated according to:

[[PROC-008 Security Monitoring Procedure]]

---

# 31. Incident Response

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Suspected incidents were classified and escalated appropriately. | Event-Driven | | | |
| Incident timelines were maintained where required. | Event-Driven | | | |
| Required evidence was preserved. | Event-Driven | | | |
| Containment actions were documented. | Event-Driven | | | |
| Recovery actions were documented. | Event-Driven | | | |
| Required internal communications occurred. | Event-Driven | | | |
| Required third-party communications occurred. | Event-Driven | | | |
| Lessons learned were documented for significant incidents. | Event-Driven | | | |
| Incident-derived corrective actions were tracked. | Monthly | | | |
| Annual Incident Response exercise was completed. | Annual | | | |

---

# 32. Incident Response References

Use:

- [[STD-008 Incident Classification & Escalation Standard]]
- [[PLN-001 Incident Response Plan]]
- [[PBK-001 Phishing & Credential Compromise Playbook]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-004 Data Exposure Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]

as applicable.

---

# 33. Evidence Handling

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Material incident evidence was identified and preserved. | Event-Driven | | | |
| Evidence custody was documented where required. | Event-Driven | | | |
| Evidence integrity was protected. | Event-Driven | | | |
| SHA-256 hashing was used where practical and appropriate for collected digital evidence. | Event-Driven | | | |
| Sensitive evidence access remained restricted. | Event-Driven | | | |

Reference:

[[PROC-011 Evidence Handling Procedure]]

---

# 34. Backup Operations

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Scheduled automated backup jobs were reviewed. | Weekly | | | |
| Backup failures were investigated. | Weekly | | | |
| Required systems remained within backup scope. | Quarterly | | | |
| Encrypted external backup rotation occurred as required. | Weekly | | | |
| Off-site backup transfer occurred as required. | Weekly | | | |
| Backup media exceptions were investigated. | Weekly | | | |
| Backup administrative access remained restricted. | Quarterly | | | |

---

# 35. External Backup Rotation Baseline

The external-drive rotation consists of:

- 7 facilities
- 3 encrypted external drives per facility
- 21 encrypted external drives total

The off-site disaster recovery storage provider normally holds:

- 2 latest weekly generations per facility
- 14 encrypted external drives total

---

# 36. Backup Rotation Process

Each Friday:

1. The current encrypted drive is prepared for off-site storage.
2. The drive is transferred to the off-site disaster recovery storage provider.
3. The provider normally retains the two latest weekly generations for the facility.
4. The oldest applicable generation is returned for reuse.
5. Rotation records are updated.

---

# 37. Recovery Testing

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Representative restore test was completed. | Quarterly | | | |
| Restore result was documented. | Quarterly | | | |
| Failed restore was investigated. | Event-Driven | | | |
| Critical recovery testing was completed. | Annual | | | |
| Applicable RTO was measured. | Annual / Following Critical Test | | | |
| Applicable RPO was measured. | Annual / Following Critical Test | | | |
| Recovery documentation was evaluated during testing. | Annual / Following Critical Test | | | |
| Material recovery deficiencies were entered into corrective-action tracking. | Event-Driven | | | |

---

# 38. Recovery Requirements

Recovery results must be evaluated against:

[[RPT-002 Business Impact Analysis]]

and documented using:

[[TMP-003 Recovery Test Template]]

where applicable.

---

# 39. Backup Success Limitation

Successful backup jobs do not prove successful recovery.

Recovery must be tested.

---

# 40. Business Continuity

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Business Continuity documentation remained available. | Quarterly | | | |
| Required printed recovery documentation remained available. | Quarterly | | | |
| Critical contact information remained current. | Quarterly | | | |
| Annual Business Continuity exercise was completed. | Annual | | | |
| Critical manual-processing capability was exercised. | Annual | | | |
| Exercise deficiencies were tracked. | Event-Driven | | | |
| Significant technology or configuration changes included recovery-documentation review. | Event-Driven | | | |

---

# 41. Manual Processing

When manual continuity is activated or exercised, verify:

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Standardized records were used where practical. | Event-Driven | | | |
| Manual records included required attribution. | Event-Driven | | | |
| Required approvals remained in effect. | Event-Driven | | | |
| Sensitive information was minimized. | Event-Driven | | | |
| Manual transactions were entered after restoration. | Event-Driven | | | |
| Duplicate transactions were prevented or identified. | Event-Driven | | | |
| Records were reconciled. | Event-Driven | | | |
| Entered records were verified. | Event-Driven | | | |

---

# 42. Manual Processing Lifecycle

Verify the lifecycle:

**Collect → Review → Enter → Reconcile → Verify**

Reference:

[[PROC-013 Manual Processing Procedure]]

---

# 43. Physical Security

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Public, Controlled, and Restricted areas remained appropriately designated. | Quarterly | | | |
| Facility access credentials remained appropriately controlled. | Monthly | | | |
| Lost or unreturned cards and keys were addressed. | Monthly | | | |
| Restricted-area access remained limited to authorized personnel. | Monthly | | | |
| Annual physical-access review was completed. | Annual | | | |
| Failed locks or access mechanisms were addressed. | Event-Driven | | | |
| Door-propping or tailgating concerns were investigated. | Event-Driven | | | |
| Material environmental-control issues were addressed. | Event-Driven | | | |

---

# 44. Warehouse High-Value Cage

Each warehouse maintains a locked security cage or enclosure for higher-value or theft-attractive inventory.

Verify:

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Cage remained secured when not actively accessed. | Operational / Monthly Review | | | |
| Cage access remained limited to authorized personnel. | Monthly | | | |
| Cage access authorization remained appropriate. | Quarterly | | | |
| Inventory records supported reconciliation of material inventory movement. | Monthly / Sampled | | | |
| Material inventory discrepancies were investigated. | Event-Driven | | | |

---

# 45. Visitor and Vendor Access

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Visitors were appropriately registered. | Operational / Sampled Monthly | | | |
| Required sponsor authorization existed. | Operational / Sampled Monthly | | | |
| Escort requirements were followed. | Operational / Sampled Monthly | | | |
| Temporary access credentials were recovered where applicable. | Operational / Sampled Monthly | | | |
| Sensitive nonemployee access had appropriate confidentiality protection. | Event-Driven / Sampled | | | |
| Vendor and service personnel access remained limited to business need. | Operational / Sampled | | | |

Reference:

[[PROC-015 Visitor & Vendor Access Procedure]]

---

# 46. Restricted Areas

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Restricted areas remained physically secured. | Monthly | | | |
| Keys and access credentials remained controlled. | Monthly | | | |
| Temporary Restricted-area access expired as required. | Monthly | | | |
| Significant IT areas remained appropriately restricted. | Monthly | | | |
| Backup media received appropriate physical protection. | Monthly | | | |

Reference:

[[PROC-016 Restricted Area Access Procedure]]

---

# 47. Personnel Security

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| New personnel security responsibilities were communicated. | Event-Driven / Monthly Review | | | |
| Required confidentiality obligations were completed. | Event-Driven / Monthly Review | | | |
| Personnel transfers triggered appropriate access review. | Event-Driven | | | |
| Terminations triggered coordinated logical and physical access removal. | Event-Driven | | | |
| Company property recovery was addressed. | Event-Driven | | | |
| Unreturned property was escalated without delaying required access disablement. | Event-Driven | | | |
| Material key-person dependencies were reviewed. | Quarterly | | | |
| Critical functions had appropriate documented alternate capability where required. | Quarterly | | | |
| Required cross-training remained current. | Quarterly | | | |

Reference:

[[PROC-017 Personnel Security Procedure]]

---

# 48. Security Awareness

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| New applicable personnel completed initial awareness training within 5 business days. | Monthly | | | |
| Annual refresher completion remained on schedule. | Monthly / Annual | | | |
| Annual knowledge assessment was administered. | Annual | | | |
| Required 80% assessment threshold was applied. | Annual | | | |
| Monthly phishing simulation was conducted. | Monthly | | | |
| Simulation results were reviewed. | Monthly | | | |
| Required corrective awareness activity was completed. | Monthly | | | |

---

# 49. Awareness Privacy

Awareness metrics should support security improvement and must not be used as justification for unnecessary or indiscriminate employee surveillance.

---

# 50. Third-Party Security

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Third-party inventory remained current. | Quarterly | | | |
| Critical third-party reviews remained within annual requirement. | Quarterly Status | | | |
| Important third-party reviews remained within biennial requirement. | Quarterly Status | | | |
| Required confidentiality agreements remained in place. | Quarterly / Event-Driven | | | |
| Third-party access remained limited to approved need. | Monthly | | | |
| Contractor accounts remained within approved duration. | Monthly | | | |
| Required security terms remained current for applicable third parties. | Quarterly | | | |
| Reported third-party security incidents were evaluated. | Event-Driven | | | |
| Material third-party findings were tracked. | Monthly | | | |

---

# 51. Third-Party Classification

Third parties are classified:

- Critical
- Important
- Routine

Security review frequency and depth must reflect classification and actual risk.

---

# 52. Confidentiality Requirement

Nonemployees receiving sensitive access must have an appropriate Non-Disclosure Agreement (NDA) or equivalent enforceable confidentiality obligation before access.

This requirement does not automatically apply to ordinary:

- Drivers
- Visitors
- Vendor sales representatives
- Building maintenance personnel

when they do not receive sensitive access.

If access scope changes, confidentiality requirements must be satisfied before sensitive access occurs.

---

# 53. Confidentiality Limitation

An NDA does not establish:

- Technical competence
- Effective security
- Appropriate access
- Assessment quality
- Adequate monitoring

---

# 54. Infinity Operations

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Development, test, and production separation remained in place. | Monthly / Following Material Change | | | |
| Production access remained restricted. | Monthly | | | |
| Contractor development access remained within approved scope and duration. | Monthly | | | |
| Contractor privileged production work occurred only through approved arrangements. | Event-Driven / Monthly Review | | | |
| Material application changes followed approved change and release procedure. | Monthly | | | |
| Required code review occurred. | Per Applicable Release | | | |
| Required security testing occurred. | Per Applicable Release | | | |
| Material vulnerabilities were tracked to remediation. | Monthly | | | |
| Source code remained under Dunder Mifflin control. | Quarterly | | | |
| Required application documentation remained available. | Quarterly | | | |
| Annual Infinity security assessment remained on schedule. | Quarterly Status / Annual | | | |
| Annual Infinity penetration test remained on schedule. | Quarterly Status / Annual | | | |
| Annual Infinity transferability review remained on schedule. | Quarterly Status / Annual | | | |

---

# 55. Infinity Contractor Access

Verify that applicable contractor development access follows:

[[PROC-020 Contractor Development Access Procedure]]

including:

- Sponsorship
- Approved duration
- Least privilege
- Controlled work location for privileged production activity
- Required confidentiality
- Named personnel
- Access removal

---

# 56. Infinity Change and Release

Material Infinity changes must follow:

[[PROC-018 Secure Change & Release Procedure]]

---

# 57. Infinity Security Assessment

Infinity security assessment must follow:

[[PROC-019 Application Security Assessment Procedure]]

---

# 58. Infinity Security Standard

Infinity must comply with:

[[STD-009 Infinity Security Standard]]

---

# 59. Infinity Assurance Chain

Operational evidence supports:

**Assessment / Penetration Test → Finding → Remediation → Retest → Control Effectiveness → R006 Risk Reassessment**

---

# 60. Change and Configuration Management

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Material changes had required authorization. | Monthly / Sampled | | | |
| Changes received appropriate testing before production. | Monthly / Sampled | | | |
| Rollback capability was documented where appropriate. | Monthly / Sampled | | | |
| Material changes were verified after implementation. | Monthly / Sampled | | | |
| Emergency changes received required follow-up review. | Event-Driven | | | |
| Material configuration deviations were investigated. | Monthly | | | |
| Critical configuration backups remained available. | Monthly | | | |

---

# 61. Unauthorized Change

Suspected unauthorized material change requires investigation and may require:

- Corrective action
- Finding
- Incident escalation
- Risk reassessment

---

# 62. Findings

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| New material findings were entered into REG-004. | Monthly | | | |
| Each material finding had one accountable owner. | Monthly | | | |
| Corrective actions had target dates. | Monthly | | | |
| Overdue findings were identified. | Monthly | | | |
| High-priority overdue findings were escalated. | Monthly | | | |
| Critical findings received appropriate executive attention. | Event-Driven / Monthly | | | |
| Completed corrective actions awaiting validation were identified. | Monthly | | | |
| Required retests were tracked. | Monthly | | | |
| Failed retests remained open. | Monthly | | | |
| Risk-accepted findings remained within approved acceptance period. | Monthly | | | |

Reference:

[[REG-004 Finding & Corrective Action Register]]

---

# 63. Finding Closure

A finding must not be closed solely because:

- A ticket was closed.
- A policy was issued.
- Equipment was purchased.
- A change was submitted.
- The owner reports completion.

Required validation must occur.

---

# 64. Corrective Action Validation

Verify that corrective action reported complete has moved through appropriate validation before closure.

---

# 65. Risk Treatments

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Risk-treatment lifecycle status remained current. | Monthly | | | |
| Planned treatments were not reported as implemented. | Monthly | | | |
| Implemented treatments awaiting validation were identified. | Monthly | | | |
| Validated treatments had supporting evidence. | Monthly | | | |
| Overdue treatment actions were identified. | Monthly | | | |
| Material validated treatments were considered for risk reassessment. | Quarterly / Event-Driven | | | |

Reference:

[[RTP-001 Enterprise Risk Treatment Plan]]

---

# 66. Treatment Lifecycle

Use:

**Planned → Approved → Implementing → Implemented → Validation Pending → Validated**

Corrective Action Required may be used when validation identifies deficiencies.

---

# 67. No Premature Risk Credit

Do not reduce current residual risk merely because a treatment is:

- Planned
- Approved
- Implementing
- Implemented

Validated performance and risk reassessment are required before demonstrated risk reduction is recognized.

---

# 68. Risk Management

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Material risk changes were identified. | Monthly / Event-Driven | | | |
| High and Critical risks had appropriate treatment or acceptance. | Monthly | | | |
| Risk acceptances remained within authorized duration. | Monthly | | | |
| High accepted risks were reassessed within 90 days. | Monthly Review | | | |
| Critical accepted risks were reassessed within 30 days. | Monthly Review | | | |
| Material assessment evidence was considered during risk reassessment. | Event-Driven | | | |

---

# 69. Risk Scoring

Enterprise risk uses:

**Risk Score = Likelihood × Impact**

Likelihood and Impact use integer values from 1 through 5.

---

# 70. Risk Levels

| Score | Level |
|---:|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–16 | High |
| 17–25 | Critical |

---

# 71. Risk Acceptance Authority

| Risk Level | Required Authority |
|---|---|
| Low | Risk Owner |
| Moderate | Risk Owner and Executive Management |
| High | CEO after Information Security and Risk Committee review |
| Critical | CEO after Information Security and Risk Committee review; exceptional use |

---

# 72. Security Metrics

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Required operational metrics were collected. | Monthly | | | |
| Missing data was identified rather than replaced with zero. | Monthly | | | |
| Metric calculations remained consistent. | Quarterly | | | |
| Material unfavorable trends were investigated. | Monthly / Quarterly | | | |
| Metric limitations were disclosed. | Monthly / Quarterly | | | |
| Executive metrics focused on decision-relevant conditions. | Quarterly | | | |

Reference:

[[REG-005 Security Metrics Catalog]]

---

# 73. Metric Integrity

Do not:

- Invent measurements.
- Alter source data.
- Exclude unfavorable data without justification.
- Present unavailable data as zero.
- Manipulate calculations to improve apparent performance.

---

# 74. Assurance Activities

| Check | Frequency | Status | Evidence / Reference | Exception / Action |
|---|---|---|---|---|
| Scheduled assurance activities remained on track. | Monthly / Quarterly | | | |
| Critical controls were assessed as scheduled. | Quarterly | | | |
| Assessment limitations were documented. | Event-Driven | | | |
| Material deficiencies became formal findings where appropriate. | Event-Driven | | | |
| Corrective-action validation was performed as required. | Event-Driven | | | |
| Required retesting was performed. | Event-Driven | | | |
| Assurance results were considered during risk reassessment. | Event-Driven | | | |

---

# 75. Annual Assurance Plan

Assurance scheduling follows:

[[PLN-005 Annual Assurance Plan]]

---

# 76. Assessment Work Plan

Material individual assessments should be planned using:

[[TMP-001 Assessment Work Plan Template]]

---

# 77. Assessment Methods

Assessment may use:

- Inspection
- Observation
- Independent Performance
- Technical Testing
- Sampling
- Exercises
- Reconciliation

---

# 78. Independent Performance

Independent Performance may be used when an assessor independently performs an authorized procedure to determine whether the expected result occurs.

It must not create unnecessary operational, security, data-integrity, or safety risk.

---

# 79. Control Effectiveness

Where supported by sufficient assessment evidence, use:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

---

# 80. Not Yet Assessed

Do not assign an effectiveness rating when sufficient assessment work has not occurred.

Use **Not Yet Assessed** where appropriate.

---

# 81. Implemented Does Not Mean Effective

Implementation status and effectiveness status must remain separate.

A control can exist and still fail to achieve its objective.

---

# 82. Exceptions Requiring Immediate Attention

Immediate attention may be required for:

- Suspected active compromise
- Unauthorized privileged access
- Terminated user retaining access
- Critical vulnerability beyond required remediation period
- Failed Critical recovery capability
- Material backup failure
- Unauthorized production change
- Material data exposure
- Significant physical-security breach
- Serious third-party security event
- Immediate safety concern

---

# 83. Immediate Security Escalation

Suspected active compromise must be handled through:

[[PROC-010 Security Event Escalation Procedure]]

and:

[[PLN-001 Incident Response Plan]]

---

# 84. Safety Priority

Human life and safety take priority over:

- Checklist completion
- Systems
- Operations
- Facilities
- Equipment
- Inventory
- Revenue
- Other assets

---

# 85. Checklist Exceptions

Record material exceptions identified during the reporting period.

| Exception ID | Area | Condition | Evidence | Owner | Required Action | Due Date | Escalated |
|---|---|---|---|---|---|---|---|
| | | | | | | | |
| | | | | | | | |

---

# 86. Exception Evaluation

For each material exception, determine whether it requires:

- Operational correction
- Management action
- Finding
- Incident response
- Risk reassessment
- Risk acceptance

---

# 87. Formal Findings Created

| Finding ID | Exception ID | Finding | Priority | Owner | Status |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

# 88. Risk Implications

| Risk ID | Operational Condition | Risk Reassessment Required | Reason |
|---|---|---|---|
| | | | |
| | | | |

---

# 89. Corrective Actions

| Action | Owner | Target Date | Validation Required | Status |
|---|---|---|---|---|
| | | | | |
| | | | | |

---

# 90. Outstanding Items

| Item | Owner | Original Due Date | Revised Due Date | Reason | Escalation |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

# 91. Reporting Summary

## Operational Summary

[Enter significant operational security conditions.]

## Management Attention Required

[Enter conditions requiring management action.]

## Executive Attention Required

[Enter only material enterprise-risk or decision issues.]

---

# 92. Reporting Principle

**Executive → decisions and enterprise risk**

**Management → accountability, performance, and action**

**Operational → execution, evidence, exceptions, and technical detail**

---

# 93. Reporting Chain

This checklist should support:

**Technical Evidence → Operational Exception → Management Impact → Enterprise Risk → Executive Decision**

---

# 94. Checklist Metrics

Record applicable metrics from [[REG-005 Security Metrics Catalog]].

| Metric ID | Metric | Current Value | Status | Trend | Comment |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

# 95. Metric Status

Use:

- Green
- Yellow
- Red
- Not Measured
- Not Applicable

as appropriate.

---

# 96. Metric Trend

Use:

- Improving
- Stable
- Deteriorating
- Insufficient Data

as appropriate.

---

# 97. Checklist Review

The reviewer should verify that:

- Required sections were completed.
- Evidence references are sufficient.
- Exceptions were documented.
- Material exceptions were escalated.
- Required findings were created.
- Corrective actions were assigned.
- Risk implications were considered.

---

# 98. Completion Certification

The person completing this checklist certifies that the recorded information reflects the security activities and evidence reviewed for the identified period.

| Role | Name | Date | Signature / Approval |
|---|---|---|---|
| Completed By | | | |
| Reviewed By | | | |

---

# 99. Certification Limitation

Checklist approval does not establish that every security control is effective.

It confirms that the identified operational review was performed and documented.

---

# 100. Record Retention

Completed checklists must be retained sufficiently to support:

- Operational history
- Metrics
- Assessments
- Findings
- Corrective actions
- Risk reassessment
- Management reporting

---

# 101. Historical Integrity

Later correction of an exception must not erase evidence that the exception previously existed.

---

# 102. Checklist Trend Analysis

Recurring checklist exceptions should be evaluated for:

- Systemic weakness
- Process failure
- Training deficiency
- Resource problem
- Control-design weakness
- Accountability problem

---

# 103. Recurring Exceptions

A recurring operational exception may justify:

- Formal finding
- Root-cause analysis
- Control redesign
- Additional training
- Increased monitoring
- Risk reassessment

---

# 104. Checklist Scope Limitation

This checklist supports recurring operational oversight.

It does not replace:

- Formal control assessment
- Penetration testing
- Vulnerability assessment
- Incident investigation
- Recovery testing
- Risk assessment
- Independent assurance

---

# 105. Operational Security Cycle

The checklist supports:

**Perform → Record → Review → Identify Exception → Correct / Escalate → Validate → Improve**

---

# 106. Assurance Relationship

Operational evidence generated through this checklist may become input to:

- [[TMP-001 Assessment Work Plan Template]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[RPT-008 Operational Security Report & Dashboard]]

---

# 107. Complete Traceability

Operational evidence contributes to the enterprise traceability chain:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

---

# 108. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-003 Identity and Access Management Program]]
- [[PRO-004 Vulnerability Management Program]]
- [[PRO-005 Security Operations Program]]
- [[PRO-006 Physical & Personnel Security Program]]
- [[PRO-007 Secure Software Development Lifecycle Program]]
- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[PRO-009 Security Governance Framework]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[POL-003 Access Control Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-006 Security Awareness & Training Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-011 Physical & Environmental Security Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[STD-002 Network Security Standard]]
- [[STD-003 Endpoint Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[STD-007 Penetration Testing Standard]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[STD-009 Infinity Security Standard]]
- [[PROC-001 Joiner-Mover-Leaver Procedure]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-003 Access Review Procedure]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-006 Vulnerability Assessment Procedure]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]
- [[PROC-008 Security Monitoring Procedure]]
- [[PROC-009 Malware Response Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-013 Manual Processing Procedure]]
- [[PROC-014 Facility Access Procedure]]
- [[PROC-015 Visitor & Vendor Access Procedure]]
- [[PROC-016 Restricted Area Access Procedure]]
- [[PROC-017 Personnel Security Procedure]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-019 Application Security Assessment Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PLN-005 Annual Assurance Plan]]
- [[TMP-001 Assessment Work Plan Template]]
- [[TMP-003 Recovery Test Template]]
- [[RPT-008 Operational Security Report & Dashboard]]

---

# 109. Template Review

This template must be reviewed:

- At least annually
- Following material operational-security process change
- Following significant control change
- When recurring checklist use identifies material deficiencies in the template

Routine completion of this checklist does not require CIO approval.

Material changes to the checklist structure or operational assurance requirements require approval consistent with the enterprise security governance framework.

---

# 110. Revision History

| Version | Date     | Description                            | Approval |
| ------- | -------- | -------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Operational Security Checklist | CIO      |