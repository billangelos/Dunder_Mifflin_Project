# RPT-008 Operational Security Report & Dashboard

## Document Control

| Field | Value |
|---|---|
| Document ID | RPT-008 |
| Title | Operational Security Report & Dashboard |
| Version | 1.0 |
| Classification | Confidential |
| Status | Approved Template |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Monthly and Following Material Security Event or Operational Change |

---

# 1. Purpose

This report provides Dunder Mifflin's operational security reporting layer.

It consolidates security activity, evidence, exceptions, technical conditions, findings, and treatment activity so Information Technology and Information Security personnel can identify conditions requiring:

- Investigation
- Correction
- Management attention
- Formal finding
- Incident escalation
- Risk reassessment

---

# 2. Reporting Level

Dunder Mifflin uses three security-reporting levels.

### Executive

Focus:

- Decisions
- Enterprise risk
- Significant exposure
- Resources

### Management

Focus:

- Accountability
- Performance
- Corrective action
- Trends

### Operational

Focus:

- Execution
- Evidence
- Exceptions
- Technical detail

This report represents the Operational level.

---

# 3. Reporting Chain

Operational reporting begins the reporting chain:

**Technical Evidence → Operational Exception → Management Impact → Enterprise Risk → Executive Decision**

Operational personnel should preserve sufficient detail to support management conclusions without requiring executive reports to contain unnecessary technical information.

---

# 4. Report Identification

| Field | Entry |
|---|---|
| Reporting Period | |
| Report Date | |
| Prepared By | |
| Reviewed By | |
| Systems in Scope | |
| Facilities in Scope | |
| Significant Scope Limitations | |

---

# 5. Reporting Integrity

This report must reflect available evidence accurately.

Do not:

- Fabricate measurements.
- Backdate activity.
- Report planned work as completed.
- Report failed activity as successful.
- Mark missing measurements as zero.
- Hide unfavorable results.
- Alter historical results.
- Assume a control is effective merely because it exists.

---

# 6. Data Availability

When required information is unavailable, use:

**Not Measured**

or:

**Insufficient Data**

as appropriate.

Missing evidence may itself represent an operational or assurance concern.

---

# 7. Dashboard Status

Where applicable, dashboard status uses:

| Status | Meaning |
|---|---|
| Green | Condition is within the approved expectation or threshold. |
| Yellow | Condition requires attention or may be approaching an unacceptable threshold. |
| Red | Condition exceeds the approved threshold or requires significant action. |
| Not Measured | Required measurement is unavailable. |
| Not Applicable | Measure does not apply to the reporting scope. |

Status must be based on the applicable definition in [[REG-005 Security Metrics Catalog]].

---

# 8. Trend

Where sufficient historical data exists, use:

- Improving
- Stable
- Deteriorating
- Insufficient Data

A single measurement does not establish a trend.

---

# 9. Operational Dashboard

| Security Area | Status | Trend | Primary Exception / Condition | Action Owner |
|---|---|---|---|---|
| Identity & Access | | | | |
| Privileged Access | | | | |
| Vulnerability Management | | | | |
| Endpoint Security | | | | |
| Network Security | | | | |
| Security Monitoring | | | | |
| Security Awareness | | | | |
| Incident Response | | | | |
| Backup Operations | | | | |
| Recovery Testing | | | | |
| Business Continuity | | | | |
| Infinity Security | | | | |
| Third-Party Security | | | | |
| Physical Security | | | | |
| Personnel Security | | | | |
| Findings & Corrective Action | | | | |
| Risk Treatments | | | | |
| Assurance Activities | | | | |

---

# 10. Operational Summary

## Significant Conditions

[Enter significant security conditions identified during the reporting period.]

## Material Exceptions

[Enter material operational exceptions.]

## Immediate Actions

[Enter actions requiring immediate operational attention.]

## Management Attention Required

[Enter conditions requiring management review.]

---

# 11. Identity and Access Management

Operational Identity and Access Management (IAM) reporting should be based on:

- [[PRO-003 Identity and Access Management Program]]
- [[PROC-001 Joiner-Mover-Leaver Procedure]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-003 Access Review Procedure]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]

---

# 12. Account Activity

| Measure | Current Period | Prior Period | Status | Evidence / Comment |
|---|---:|---:|---|---|
| New employee accounts created | | | | |
| Employee transfers processed | | | | |
| Employee terminations processed | | | | |
| Contractor accounts created | | | | |
| Contractor accounts expired / removed | | | | |
| 30-day dormant accounts investigated | | | | |
| 60-day dormant accounts disabled | | | | |
| Emergency-access events | | | | |

---

# 13. Access Exceptions

Record material exceptions involving:

- Unauthorized account creation
- Excessive access
- Delayed termination
- Inappropriate transfer access
- Dormant accounts
- Shared credentials
- Contractor access
- Emergency access
- Missing authorization

| Exception | Account / System | Condition | Owner | Action | Status |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

# 14. Privileged Access

| Measure | Current Period | Status | Evidence / Comment |
|---|---:|---|---|
| Authorized standing Domain Administrator accounts | | | |
| Unauthorized privileged accounts identified | | | |
| Privileged-access exceptions | | | |
| Emergency privileged-access events | | | |
| Privileged accounts awaiting review | | | |

---

# 15. Privileged Access Review

Quarterly privileged-access review status:

| Field | Result |
|---|---|
| Review Required This Period | |
| Review Completed | |
| Completion Date | |
| Exceptions Identified | |
| Unresolved Exceptions | |
| Evidence Reference | |

---

# 16. Ordinary Access Review

Annual ordinary-user access review status:

| Field | Result |
|---|---|
| Review Required This Period | |
| Review Completed | |
| Completion Date | |
| Exceptions Identified | |
| Unresolved Exceptions | |
| Evidence Reference | |

---

# 17. Warehouse Accountability

Shared Windows workstation accounts may remain where operationally justified.

Significant Warehouse Management System activity requires individual authentication and accountability.

| Measure | Result / Status | Evidence / Comment |
|---|---|---|
| Shared Windows use remains within approved scope | | |
| Significant WMS transactions individually attributable | | |
| Unauthorized shared credentials identified | | |
| Material attribution failures | | |

---

# 18. Vulnerability Management

Operational vulnerability reporting should be based on:

- [[PRO-004 Vulnerability Management Program]]
- [[PROC-006 Vulnerability Assessment Procedure]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]

---

# 19. Vulnerability Assessment Status

| Measure | Current Period | Prior Period | Status | Evidence / Comment |
|---|---:|---:|---|---|
| Systems expected in assessment scope | | | | |
| Systems successfully assessed | | | | |
| Systems excluded or failed | | | | |
| Critical vulnerabilities open | | | | |
| High vulnerabilities open | | | | |
| Moderate vulnerabilities open | | | | |
| Low vulnerabilities open | | | | |
| Vulnerabilities remediated | | | | |
| Vulnerabilities retested | | | | |

---

# 20. Vulnerability Remediation Targets

| Severity | Target |
|---|---|
| Critical | 7 days |
| High | 30 days |
| Moderate | 45 days |
| Low | 60 days |

---

# 21. Overdue Vulnerabilities

| Vulnerability / Reference | Severity | Asset | Age | Owner | Reason | Action |
|---|---|---|---:|---|---|---|
| | | | | | | |
| | | | | | | |

---

# 22. Vulnerability Exceptions

Material conditions requiring attention include:

- Critical vulnerability beyond 7 days
- High vulnerability beyond 30 days
- Required system excluded from assessment
- Repeated remediation failure
- Recurring vulnerability
- Systemic configuration weakness
- Vulnerability indicating possible compromise

---

# 23. Endpoint Security

Operational endpoint reporting should consider:

- Managed antivirus
- Malware definitions
- Malware detections
- Laptop full-disk encryption
- Standard-user configuration
- Local administrative privilege
- Screen locking
- Mobile Device Management
- Lost or stolen devices

---

# 24. Endpoint Dashboard

| Measure | Current Period | Status | Evidence / Comment |
|---|---:|---|---|
| Managed endpoints | | | |
| Endpoints reporting to antivirus management | | | |
| Endpoints with current malware protection | | | |
| Unresolved malware detections | | | |
| Applicable laptops with full-disk encryption | | | |
| Unauthorized local administrator exceptions | | | |
| Applicable mobile devices enrolled in MDM | | | |
| Lost or stolen devices | | | |

---

# 25. Malware Activity

| Event / Reference | Device | Detection | Action | Escalated | Status |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

Material malware activity should follow:

[[PROC-009 Malware Response Procedure]]

---

# 26. Network Security

Operational network reporting should be based on:

[[STD-002 Network Security Standard]]

and:

[[PROC-008 Security Monitoring Procedure]]

---

# 27. Network Dashboard

| Measure | Result / Status | Evidence / Comment |
|---|---|---|
| Material firewall changes | | |
| Unauthorized inbound exposure identified | | |
| Publicly exposed administrative services identified | | |
| Network-device configuration backup exceptions | | |
| Unexpected network devices | | |
| Remote-access exceptions | | |
| Material Internet infrastructure incidents | | |

---

# 28. Wireless Security

The authorized wireless baseline is:

- No corporate wireless network
- One ceiling-mounted Internet-only guest wireless access point in the Scranton Headquarters lobby

---

# 29. Rogue Wireless Assessment

| Field | Result |
|---|---|
| Assessment Required This Period | |
| Assessment Completed | |
| Expected Access Points | 1 |
| Unexpected Access Points Identified | |
| Investigation Required | |
| Evidence Reference | |

An unexpected wireless access point must not be assumed malicious, but it requires investigation.

---

# 30. Security Monitoring

Dunder Mifflin does not operate a 24-hour Security Operations Center.

Operational reporting must not imply continuous staffed monitoring when that capability does not exist.

---

# 31. Monitoring Activity

| Measure | Current Period | Status | Evidence / Comment |
|---|---:|---|---|
| Material authentication exceptions reviewed | | | |
| Malware events reviewed | | | |
| Material network-security events reviewed | | | |
| Monitoring-source failures | | | |
| Events escalated for investigation | | | |
| After-hours security events | | | |

---

# 32. Monitoring Exceptions

Record significant:

- Missing logs
- Monitoring-source failures
- Repeated authentication anomalies
- Unexpected network activity
- Unresolved security alerts
- Escalation failures

| Exception | Source | Condition | Owner | Action | Status |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

# 33. Security Awareness

Operational awareness reporting should be based on:

[[POL-006 Security Awareness & Training Policy]]

---

# 34. Awareness Dashboard

| Measure | Current Period | Status | Evidence / Comment |
|---|---:|---|---|
| New personnel requiring initial training | | | |
| Initial training completed within 5 business days | | | |
| Annual refresher completion | | | |
| Annual knowledge assessment completion | | | |
| Personnel meeting 80% threshold | | | |
| Monthly phishing simulation completed | | | |
| Phishing simulation failure rate | | | |
| Corrective awareness activity completed | | | |

---

# 35. Awareness Interpretation

Phishing simulation results should be used to:

- Identify training needs
- Evaluate trends
- Improve awareness
- Support risk assessment

They should not be used to justify unnecessary or indiscriminate employee surveillance.

---

# 36. Incident Response

Operational incident reporting should be based on:

- [[STD-008 Incident Classification & Escalation Standard]]
- [[PLN-001 Incident Response Plan]]
- [[PROC-010 Security Event Escalation Procedure]]

---

# 37. Incident Dashboard

| Measure | Current Period | Prior Period | Status | Evidence / Comment |
|---|---:|---:|---|---|
| Security events escalated | | | | |
| Incidents declared | | | | |
| Material incidents | | | | |
| Incidents closed | | | | |
| Incidents with open corrective actions | | | | |
| Third-party incidents | | | | |

---

# 38. Incident Register Summary

| Incident / Reference | Classification | Affected Asset / Process | Status | Corrective Action | Management Escalation |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

# 39. Incident Playbooks

Applicable incidents should use:

- [[PBK-001 Phishing & Credential Compromise Playbook]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-004 Data Exposure Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]

---

# 40. Evidence Handling

Material incident evidence should follow:

[[PROC-011 Evidence Handling Procedure]]

Operational review should consider:

- Evidence identification
- Custody
- Integrity
- Access restriction
- Documentation
- SHA-256 hashing where practical and appropriate

---

# 41. Backup Operations

Operational backup reporting should be based on:

[[PROC-012 Backup & Recovery Procedure]]

---

# 42. Backup Dashboard

| Measure | Current Period | Status | Evidence / Comment |
|---|---:|---|---|
| Scheduled backup jobs | | | |
| Successful backup jobs | | | |
| Failed backup jobs | | | |
| Unresolved backup failures | | | |
| Systems with confirmed required backup coverage | | | |
| External-drive rotation completed | | | |
| Off-site transfer exceptions | | | |
| Backup administrative-access exceptions | | | |

---

# 43. External Backup Rotation

The established external-drive rotation consists of:

- 7 facilities
- 3 encrypted external drives per facility
- 21 encrypted external drives total

The off-site disaster recovery storage provider normally holds:

- 2 latest weekly generations per facility
- 14 encrypted external drives total

---

# 44. Backup Exceptions

| Exception | System / Facility | Condition | Owner | Action | Status |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

# 45. Recovery Testing

Recovery testing should be documented using:

[[TMP-003 Recovery Test Template]]

---

# 46. Recovery Dashboard

| Measure | Current Period | Status | Evidence / Comment |
|---|---:|---|---|
| Quarterly representative restore required | | | |
| Quarterly representative restore completed | | | |
| Restore tests passed | | | |
| Restore tests failed | | | |
| Critical annual recovery tests required | | | |
| Critical annual recovery tests completed | | | |
| RTO failures | | | |
| RPO failures | | | |
| Recovery findings opened | | | |

---

# 47. Recovery Objective Results

| System / Process | Criticality | RTO | Actual Recovery Time | RTO Result | RPO | Actual Data Loss | RPO Result |
|---|---|---|---|---|---|---|---|
| | | | | | | | |
| | | | | | | | |

Do not populate actual recovery performance without supporting test evidence.

---

# 48. Recovery Interpretation

Successful backup completion does not demonstrate successful recovery.

Operational reporting should distinguish:

- Backup success
- Restore success
- Recovery Time Objective achievement
- Recovery Point Objective achievement
- Business validation

---

# 49. Business Continuity

Operational Business Continuity reporting should consider:

- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]
- [[PROC-013 Manual Processing Procedure]]

---

# 50. Continuity Dashboard

| Measure | Result / Status | Evidence / Comment |
|---|---|---|
| Critical contact information current | | |
| Printed recovery documentation available | | |
| Annual Business Continuity exercise status | | |
| Manual-processing exercise status | | |
| Cloud Exit Plan reviewed after material provider change | | |
| Continuity deficiencies open | | |

---

# 51. Manual Processing

When manual processing is used or exercised, verify:

**Collect → Review → Enter → Reconcile → Verify**

---

# 52. Manual Processing Dashboard

| Measure | Result / Status | Evidence / Comment |
|---|---|---|
| Manual records appropriately controlled | | |
| Required attribution preserved | | |
| Required approvals preserved | | |
| Sensitive information minimized | | |
| Duplicate processing identified / prevented | | |
| Reconciliation completed | | |
| Verification completed | | |
| Material errors identified | | |

---

# 53. Infinity Security

Infinity operational reporting should be based on:

- [[PRO-007 Secure Software Development Lifecycle Program]]
- [[STD-009 Infinity Security Standard]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-019 Application Security Assessment Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]

---

# 54. Infinity Dashboard

| Measure | Current Period | Status | Evidence / Comment |
|---|---:|---|---|
| Material releases | | | |
| Releases with required code review | | | |
| Releases with required security testing | | | |
| Unauthorized production changes | | | |
| Production-access exceptions | | | |
| Contractor-access exceptions | | | |
| Open application-security findings | | | |
| Overdue application-security findings | | | |
| Annual security assessment status | | | |
| Annual application penetration test status | | | |
| Annual transferability review status | | | |

---

# 55. Infinity Production Access

Operational review should verify:

- Production access is restricted.
- Privileged access is individually attributable.
- Contractor privileged production work follows approved arrangements.
- General contractor VPN access is not provided.
- Access is removed when no longer required.

---

# 56. Infinity Contractor Personnel

Expected contractor personnel should be identified at least one business day before scheduled arrival where practical.

Emergency exceptions should be documented.

---

# 57. Infinity Findings

| Finding ID | Condition | Priority | Owner | Corrective Action | Retest Status |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

# 58. Infinity Assurance Chain

Infinity assurance follows:

**Assessment / Penetration Test → Finding → Remediation → Retest → Control Effectiveness → R006 Risk Reassessment**

---

# 59. Infinity Transferability

Operational evidence supporting transferability may include:

- Source-code availability
- Repository access
- Documentation
- Build instructions
- Configuration information
- Recovery information
- Administrative knowledge
- Contractor-access records

Primary artifact:

[[RPT-004 Infinity Transferability Review]]

---

# 60. Third-Party Security

Operational third-party reporting should be based on:

[[POL-008 Third-Party Security Policy]]

---

# 61. Third-Party Dashboard

| Measure | Current Period | Status | Evidence / Comment |
|---|---:|---|---|
| Critical third parties | | | |
| Critical reviews due | | | |
| Critical reviews completed | | | |
| Important reviews due | | | |
| Important reviews completed | | | |
| Third-party access exceptions | | | |
| Third-party security incidents | | | |
| Open third-party findings | | | |
| Overdue third-party findings | | | |

---

# 62. Third-Party Review Frequency

| Classification | Review |
|---|---|
| Critical | Annual |
| Important | Biennial |
| Routine | Risk-based |

---

# 63. Third-Party Confidentiality

Nonemployees receiving sensitive access require an appropriate Non-Disclosure Agreement or equivalent enforceable confidentiality obligation before access.

An NDA does not establish:

- Effective technical controls
- Competence
- Appropriate access
- Security monitoring
- Assessment quality

---

# 64. Supplier Resilience

Operational conditions affecting R020 Supplier Disruption should include:

- Supplier availability
- Significant shortages
- Alternate-source availability
- Inventory conditions
- Procurement exceptions
- Transportation constraints

Material conditions should be escalated to Operations and Procurement management.

---

# 65. Physical Security

Operational physical-security reporting should be based on:

- [[PRO-006 Physical & Personnel Security Program]]
- [[PROC-014 Facility Access Procedure]]
- [[PROC-015 Visitor & Vendor Access Procedure]]
- [[PROC-016 Restricted Area Access Procedure]]

---

# 66. Physical Security Dashboard

| Measure | Current Period | Status | Evidence / Comment |
|---|---:|---|---|
| Lost access cards | | | |
| Lost keys | | | |
| Unauthorized access events | | | |
| Restricted-area exceptions | | | |
| Visitor-control exceptions | | | |
| Warehouse-cage exceptions | | | |
| Significant IT-area exceptions | | | |
| Material environmental incidents | | | |

---

# 67. Warehouse Security

Each warehouse maintains a locked cage or enclosure for higher-value or theft-attractive inventory.

Operational review should consider:

- Cage security
- Authorized access
- Inventory records
- Receiving records
- Shipping records
- Significant WMS transactions
- Inventory counts
- Material discrepancies

---

# 68. Inventory Theft Indicators

Conditions requiring investigation may include:

- Unexplained inventory discrepancy
- Missing receiving record
- Missing shipping record
- Significant transaction lacking attribution
- Unauthorized cage access
- Repeated adjustment patterns

Material inventory theft should be difficult without bypassing physical controls or creating discrepancies in inventory, receiving, shipping, or transaction records.

---

# 69. Environmental Security

Operational review should identify material conditions involving:

- Fire protection
- Water intrusion
- Power
- HVAC
- Uninterruptible Power Supply equipment
- Landlord-managed building systems

Human safety takes priority over equipment and operational continuity.

---

# 70. Personnel Security

Operational personnel-security reporting should be based on:

[[PROC-017 Personnel Security Procedure]]

---

# 71. Personnel Security Dashboard

| Measure | Current Period | Status | Evidence / Comment |
|---|---:|---|---|
| Personnel transfers requiring security action | | | |
| Terminations requiring coordinated access removal | | | |
| Confidentiality exceptions | | | |
| Unreturned company property | | | |
| Key-person dependency exceptions | | | |
| Cross-training deficiencies | | | |
| Contractor personnel exceptions | | | |

---

# 72. Fraud Indicators

Operational evidence may identify conditions related to:

- R029 Vendor Fraud
- R030 Sales Fraud
- R031 Payroll Fraud
- R032 Inventory Theft

Operational personnel should report anomalies rather than assume that an anomaly proves fraud.

---

# 73. Fraud-Related Exceptions

| Area | Condition | Evidence / Reference | Owner | Escalation | Status |
|---|---|---|---|---|---|
| Vendor | | | | | |
| Sales | | | | | |
| Payroll | | | | | |
| Inventory | | | | | |

---

# 74. Change and Configuration Management

Operational reporting should be based on:

[[POL-007 Change & Configuration Management Policy]]

and applicable configuration standards.

---

# 75. Change Dashboard

| Measure | Current Period | Status | Evidence / Comment |
|---|---:|---|---|
| Material changes implemented | | | |
| Changes with required approval | | | |
| Changes with required testing | | | |
| Changes with rollback capability where required | | | |
| Changes successfully verified | | | |
| Emergency changes | | | |
| Unauthorized changes | | | |
| Change-related incidents | | | |

---

# 76. Configuration Exceptions

| Asset / System | Deviation | Authorization | Risk / Impact | Owner | Action |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

# 77. Security Control Inventory

Operational control information is maintained in:

[[REG-003 Enterprise Security Control Inventory]]

The inventory connects controls to:

- Requirements
- Risks
- Owners
- Implementation
- Evidence
- Assessment
- Effectiveness

---

# 78. Control Status Summary

| Implementation Status | Count |
|---|---:|
| Planned | |
| Implementing | |
| Implemented | |
| Validation Pending | |
| Validated | |

Do not infer effectiveness from implementation status.

---

# 79. Control Effectiveness Summary

Where sufficient assessment evidence exists:

| Effectiveness | Count |
|---|---:|
| Effective | |
| Partially Effective | |
| Ineffective | |
| Not Implemented | |

Controls lacking sufficient assessment evidence should remain identified as not yet assessed rather than being assumed effective.

---

# 80. Control Exceptions

| Control ID | Control | Condition | Related Risk | Owner | Required Action |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

# 81. Findings and Corrective Actions

Formal material deficiencies are maintained in:

[[REG-004 Finding & Corrective Action Register]]

---

# 82. Finding Dashboard

| Measure | Current Period | Prior Period | Status | Comment |
|---|---:|---:|---|---|
| Open findings | | | | |
| New findings | | | | |
| Findings closed after validation | | | | |
| Overdue findings | | | | |
| Findings awaiting validation | | | | |
| Failed retests | | | | |
| Repeated findings | | | | |
| Risk-accepted deficiencies | | | | |

---

# 83. Open Findings

| Finding ID | Priority | Control | Related Risk | Owner | Due Date | Status |
|---|---|---|---|---|---|---|
| | | | | | | |
| | | | | | | |

---

# 84. Corrective Actions

| Corrective Action ID | Finding ID | Owner | Target Date | Status | Validation Required |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

# 85. Validation and Retest

| Finding ID | Validation Method | Retest Required | Retest Date | Result | Closure Status |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

# 86. Failed Retest

A failed retest does not close the finding.

The deficiency should remain visible and corrective action should be revised as necessary.

---

# 87. Risk Treatments

Risk-treatment activity is maintained in:

[[RTP-001 Enterprise Risk Treatment Plan]]

---

# 88. Treatment Dashboard

| Lifecycle Status | Count |
|---|---:|
| Planned | |
| Approved | |
| Implementing | |
| Implemented | |
| Validation Pending | |
| Validated | |
| Corrective Action Required | |

---

# 89. Treatment Activity

| Risk ID | Treatment | Owner | Status | Evidence Available | Validation Status | Exception |
|---|---|---|---|---|---|---|
| | | | | | | |
| | | | | | | |

---

# 90. No Premature Risk Credit

Current residual risk must not be reduced merely because a treatment is:

- Planned
- Approved
- Implementing
- Implemented

Validated performance and documented risk reassessment are required.

---

# 91. Enterprise Risk Indicators

Operational evidence may identify conditions requiring reassessment of risks in:

[[REG-002 Enterprise Risk Register]]

---

# 92. Risk Change Indicators

Examples include:

- New threat
- Material incident
- Control failure
- Failed recovery test
- Repeated finding
- Material architecture change
- Significant third-party change
- Business dependency change
- Material improvement supported by validation

---

# 93. Risks Requiring Operational Attention

| Risk ID | Operational Condition | Evidence | Current Residual | Action |
|---|---|---|---|---|
| | | | | |
| | | | | |

---

# 94. Risk Reassessment Requests

| Risk ID | Reason | Requested By | Evidence Reference | Status |
|---|---|---|---|---|
| | | | | |
| | | | | |

---

# 95. Security Assurance

Operational assurance activity should be based on:

[[PRO-008 Security Assurance & Continuous Improvement Program]]

and:

[[PLN-005 Annual Assurance Plan]]

---

# 96. Assurance Dashboard

| Measure | Current Period | Status | Evidence / Comment |
|---|---:|---|---|
| Assessments scheduled | | | |
| Assessments completed | | | |
| Assessments delayed | | | |
| Critical controls assessed | | | |
| Material findings identified | | | |
| Corrective actions validated | | | |
| Retests completed | | | |
| Failed retests | | | |

---

# 97. Assessment Work Plans

Material individual assessments should use:

[[TMP-001 Assessment Work Plan Template]]

---

# 98. Assessment Methods

Assessment may include:

- Inspection
- Observation
- Independent Performance
- Technical Testing
- Sampling
- Exercises
- Reconciliation

---

# 99. Assurance Exceptions

| Assessment | Condition | Control / Requirement | Owner | Action | Status |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

# 100. Operational Security Checklist

Recurring operational review is supported by:

[[TMP-002 Operational Security Checklist]]

Material exceptions from completed checklists should be reflected in this report.

---

# 101. Checklist Completion

| Field | Result |
|---|---|
| Checklist Required for Reporting Period | |
| Checklist Completed | |
| Checklist ID | |
| Material Exceptions | |
| Formal Findings Created | |
| Management Escalation Required | |

---

# 102. Security Metrics

Approved metric definitions are maintained in:

[[REG-005 Security Metrics Catalog]]

---

# 103. Operational Metrics

| Metric ID | Metric | Current Value | Prior Value | Status | Trend |
|---|---|---:|---:|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

# 104. Metric Interpretation

Operational metrics should help answer:

- Is required security work occurring?
- Are exceptions increasing?
- Are vulnerabilities being corrected?
- Are access controls operating?
- Are backups recoverable?
- Are findings being resolved?
- Are treatments progressing?
- Are controls producing expected evidence?

---

# 105. Metric Limitation

Metrics do not replace:

- Investigation
- Control assessment
- Risk analysis
- Management judgment

A favorable metric can coexist with material risk.

---

# 106. Significant Operational Exceptions

Use this section to consolidate the most important exceptions for management.

| Exception ID | Area | Condition | Related Risk / Finding | Owner | Required Action | Due Date |
|---|---|---|---|---|---|---|
| | | | | | | |
| | | | | | | |

---

# 107. Exception Priority

Priority should consider:

- Safety
- Business criticality
- Risk severity
- Control importance
- Exploitability
- Exposure
- Data sensitivity
- Recovery impact
- Repetition
- Existing compensating controls

---

# 108. Management Escalation

Operational personnel should escalate conditions requiring:

- Cross-functional action
- Additional resources
- Policy decision
- Risk acceptance
- Significant corrective action
- Business prioritization

to the appropriate management level.

---

# 109. Executive Escalation

Operational personnel normally escalate through management.

Immediate executive escalation may be appropriate when required by:

- Incident severity
- Safety
- Critical business impact
- Legal or compliance concern
- Existing escalation requirements

---

# 110. Management Action Summary

| Matter | Operational Impact | Management Decision / Action Required | Owner |
|---|---|---|---|
| | | | |
| | | | |

---

# 111. Open Operational Actions

| Action | Source | Owner | Due Date | Status | Evidence Required |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

# 112. Overdue Operational Actions

| Action | Original Due Date | Owner | Reason | Current Exposure | Escalation |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

# 113. Evidence References

Use this section to identify major supporting evidence for the report.

| Evidence Reference | Description | Source | Classification | Location / Custodian |
|---|---|---|---|---|
| | | | | |
| | | | | |

---

# 114. Evidence Integrity

Evidence must not be:

- Fabricated
- Backdated
- Altered to hide failure
- Invented
- Misrepresented

Evidence should be sufficiently protected to preserve its usefulness for operational review and assurance.

---

# 115. Historical Integrity

Later correction of an operational problem must not erase the fact that the problem existed.

Preserve applicable:

- Original condition
- Evidence
- Action
- Finding
- Remediation
- Validation
- Retest
- Closure

---

# 116. Operational Reporting and Findings

An operational exception does not automatically become a formal finding.

The condition should be evaluated based on:

- Requirement
- Control objective
- Evidence
- Risk
- Materiality
- Persistence
- Management significance

---

# 117. Operational Reporting and Incidents

An operational exception may require immediate incident escalation when it indicates:

- Active compromise
- Unauthorized access
- Malware
- Data exposure
- Significant third-party compromise
- Other material security event

Use:

[[PROC-010 Security Event Escalation Procedure]]

---

# 118. Operational Reporting and Risk

Operational evidence may support:

- Increased risk
- Reduced risk
- Changed likelihood
- Changed impact
- Changed control effectiveness

Risk changes must be documented through the established risk-management process.

---

# 119. Operational Reporting and Management

The operational report should provide management with enough information to:

- Understand material conditions
- Assign accountability
- Remove obstacles
- Allocate resources
- Escalate enterprise risk
- Verify corrective action

It should not require management to interpret raw technical data without context.

---

# 120. Operational Reporting and Executive Leadership

Raw operational detail should normally be summarized before reaching executive leadership.

Executive reporting should emphasize:

- Enterprise impact
- Risk
- Decision required
- Resource requirement
- Significant unresolved exposure

---

# 121. Reporting Flow

The reporting flow is:

**Operational Security Report**

↓

**Management Security Report**

↓

**Executive Security Summary**

represented by:

- [[RPT-008 Operational Security Report & Dashboard]]
- [[RPT-007 Management Security Report]]
- [[RPT-006 Executive Security Summary]]

---

# 122. Monthly Operational Review

The monthly operational review should consider:

1. IAM activity
2. Privileged access
3. Vulnerabilities
4. Endpoint security
5. Network security
6. Monitoring
7. Awareness
8. Incidents
9. Backup
10. Recovery
11. Continuity
12. Infinity
13. Third parties
14. Physical security
15. Personnel security
16. Findings
17. Corrective actions
18. Risk treatments
19. Assurance activity
20. Metrics
21. Operational exceptions

---

# 123. Quarterly Operational Review

Quarterly review should additionally consider:

- Privileged-access review
- Backup coverage
- Representative restore testing
- Critical-control assessment progress
- Third-party review status
- Risk-treatment progress
- Finding trends
- Metric trends

---

# 124. Semiannual Operational Review

Every six months, verify completion of:

- Network discovery
- Rogue wireless assessment

The expected wireless baseline remains one authorized Internet-only guest access point at Scranton Headquarters.

---

# 125. Annual Operational Review

Annual activities include, as applicable:

- Ordinary-user access review
- Security awareness refresher
- Awareness knowledge assessment
- Incident Response exercise
- Business Continuity exercise
- Critical recovery testing
- Infinity security assessment
- Infinity application penetration test
- Infinity transferability review
- Critical third-party review
- Physical-access review
- Assurance planning

---

# 126. Event-Driven Review

Additional reporting may be required following:

- Significant incident
- Material control failure
- Failed recovery test
- Significant third-party event
- Major architecture change
- Material business change
- Significant finding
- Material change in risk

---

# 127. Safety

Human life and safety take priority over:

- Security reporting
- Systems
- Operations
- Facilities
- Equipment
- Inventory
- Revenue
- Other assets

Operational personnel should never delay necessary safety action to preserve normal security process.

---

# 128. Operational Reporting Principle

The purpose of operational reporting is not to produce favorable numbers.

The purpose is to produce reliable information that allows Dunder Mifflin to identify weakness, correct problems, understand risk, and make informed decisions.

---

# 129. Complete Operational Chain

The operational reporting process supports:

**Execute → Record → Review → Identify Exception → Investigate → Correct / Escalate → Validate → Report → Improve**

---

# 130. Enterprise Traceability

Operational reporting contributes evidence to:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

---

# 131. Related Artifacts

## Enterprise Context

- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[REG-001 Enterprise Asset Register]]
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
- [[POL-006 Security Awareness & Training Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-011 Physical & Environmental Security Policy]]
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

## Security Operations

- [[PRO-005 Security Operations Program]]
- [[PROC-008 Security Monitoring Procedure]]
- [[PROC-009 Malware Response Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-011 Evidence Handling Procedure]]

## Incident Response

- [[STD-008 Incident Classification & Escalation Standard]]
- [[PLN-001 Incident Response Plan]]
- [[PBK-001 Phishing & Credential Compromise Playbook]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-004 Data Exposure Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]

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

---

# 132. Revision History

| Version | Date     | Description                                     | Approval |
| ------- | -------- | ----------------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Operational Security Report & Dashboard | CIO      |