# REG-005 Security Metrics Catalog

## Document Control

| Field | Value |
|---|---|
| Document ID | REG-005 |
| Title | Security Metrics Catalog |
| Version | 1.0 |
| Classification | Confidential |
| Status | Active |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Quarterly and Following Material Security, Risk, Control, or Reporting Change |

---

# 1. Purpose

This catalog defines Dunder Mifflin's enterprise security metrics.

It establishes a consistent method for measuring:

- Security control performance
- Risk indicators
- Operational security activity
- Corrective-action progress
- Security-program effectiveness
- Management accountability

---

# 2. Objectives

Security metrics must help Dunder Mifflin answer:

1. Are important security activities being performed?
2. Are important controls operating as expected?
3. Is security exposure increasing or decreasing?
4. Are identified weaknesses being corrected?
5. Are security requirements being satisfied?
6. Does management need to act?
7. Does enterprise risk require reassessment?

---

# 3. Authority

This catalog operates under:

- [[POL-001 Information Security Policy]]
- [[POL-005 Risk Management Policy]]
- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[PRO-009 Security Governance Framework]]

---

# 4. Metric Types

Dunder Mifflin uses three primary metric types:

1. Key Performance Indicators (KPIs)
2. Key Risk Indicators (KRIs)
3. Operational Measures

---

# 5. Key Performance Indicator

A Key Performance Indicator measures whether a security activity, control, or process is performing as expected.

Examples include:

- Percentage of required access reviews completed
- Percentage of Critical vulnerabilities remediated within target
- Percentage of scheduled backup restore tests completed

---

# 6. Key Risk Indicator

A Key Risk Indicator provides information concerning increasing, significant, or changing risk exposure.

Examples include:

- Number of overdue Critical vulnerabilities
- Number of unauthorized privileged accounts
- Number of failed recovery tests
- Number of overdue High-priority findings

---

# 7. Operational Measure

An Operational Measure provides detailed information useful for day-to-day security activity.

Examples include:

- Malware alerts investigated
- Accounts disabled
- Vulnerabilities identified
- Backup jobs failed
- Security events escalated

---

# 8. Metric Hierarchy

Operational evidence may support progressively higher levels of reporting:

**Operational Measure → KPI / KRI → Management Impact → Enterprise Risk → Executive Decision**

---

# 9. Reporting Levels

Security metrics support three reporting levels:

| Level | Primary Purpose |
|---|---|
| Executive | Enterprise risk and decisions |
| Management | Accountability, performance, and action |
| Operational | Execution, evidence, exceptions, and technical detail |

---

# 10. Reporting Principle

**Executive → decisions and enterprise risk**

**Management → accountability, performance, and action**

**Operational → execution, evidence, exceptions, and technical detail**

---

# 11. Metric Design Requirements

Each formal metric should define:

- Metric ID
- Metric name
- Type
- Purpose
- Calculation or measurement method
- Data source
- Owner
- Frequency
- Reporting audience
- Interpretation

---

# 12. Metric Identification

Metrics use:

**MET-[Domain]-[Number]**

Examples:

- MET-IAM-001
- MET-VM-001
- MET-BCDR-001

---

# 13. Metric Domains

| Code | Domain |
|---|---|
| GOV | Governance and Risk |
| IAM | Identity and Access Management |
| VM | Vulnerability Management |
| END | Endpoint Security |
| NET | Network Security |
| OPS | Security Operations |
| IR | Incident Response |
| BCDR | Business Continuity and Disaster Recovery |
| PHY | Physical Security |
| PER | Personnel Security |
| TPRM | Third-Party Security |
| APP | Application and Secure Development |
| AWR | Security Awareness |
| ASSUR | Security Assurance |

---

# 14. Metric Integrity

Metrics must reflect actual data.

Personnel must not:

- Invent measurements.
- Alter source data to improve reported performance.
- Exclude unfavorable results without justification.
- Backdate completed activities.
- Report unperformed testing as complete.
- Manipulate calculations to produce a preferred result.

---

# 15. No Fabricated Baseline Data

This catalog defines metrics and measurement methods.

It does not fabricate May 2013 measurements merely to populate a dashboard.

Actual values must come from actual operational or assessment evidence.

---

# 16. Missing Data

Missing data must be reported as:

- Unavailable
- Not measured
- Not applicable

as appropriate.

A missing measurement must not be replaced with an invented value.

---

# 17. Metric Context

Metrics must be interpreted in context.

A numerical change does not automatically establish improvement or deterioration.

---

# 18. Example of Context

An increase in reported security incidents could indicate:

- Increased attack activity
- Improved detection
- Improved employee reporting
- Expanded monitoring
- A combination of these conditions

---

# 19. Metric Target

A metric target should support a legitimate:

- Security objective
- Risk objective
- Business requirement
- Operational requirement

---

# 20. Target Versus Threshold

A target represents desired performance.

A threshold represents a condition requiring attention or escalation.

---

# 21. Thresholds

Where appropriate, metrics may use:

- Green
- Yellow
- Red

thresholds.

---

# 22. Green

Green generally indicates that the measured condition is within the expected range.

---

# 23. Yellow

Yellow generally indicates that the condition requires management or operational attention.

---

# 24. Red

Red generally indicates a material condition requiring prompt attention or escalation.

---

# 25. Threshold Limitation

Color status must not replace the underlying measurement or explanation.

---

# 26. Trend

Metrics may identify trend as:

- Improving
- Stable
- Deteriorating
- Insufficient Data

---

# 27. Trend Period

Trend interpretation must consider a meaningful period rather than a single isolated measurement where practical.

---

# 28. Metric Ownership

Each metric must have one accountable owner.

---

# 29. Data Owner Versus Metric Owner

The owner of the source data may differ from the owner responsible for the metric.

---

# 30. Metric Validation

Material metrics should be periodically reviewed to confirm:

- Calculation remains correct.
- Source data remains appropriate.
- Metric remains useful.
- Thresholds remain meaningful.
- Reporting audience remains appropriate.

---

# 31. Governance and Risk Metrics

| Metric ID | Metric | Type | Calculation / Measurement | Source | Owner | Frequency | Audience |
|---|---|---|---|---|---|---|---|
| MET-GOV-001 | High and Critical Risks Without Current Treatment Plan | KRI | Count of High or Critical current residual risks lacking documented treatment | [[REG-002 Enterprise Risk Register]]; [[RTP-001 Enterprise Risk Treatment Plan]] | CIO | Monthly | Management / Executive |
| MET-GOV-002 | Overdue Risk Reassessments | KRI | Count of risk reassessments past required review date | [[REG-002 Enterprise Risk Register]] | CIO | Monthly | Management |
| MET-GOV-003 | Expired Risk Acceptances | KRI | Count of risk acceptances past authorized expiration or reassessment date | Risk acceptance records | CIO | Monthly | Management / Executive |
| MET-GOV-004 | Risk Treatments by Lifecycle Status | Operational | Count of treatments by Planned, Approved, Implementing, Implemented, Validation Pending, and Validated | [[RTP-001 Enterprise Risk Treatment Plan]] | CIO | Monthly | Management |
| MET-GOV-005 | Validated Treatments Resulting in Risk Reassessment | KPI | Validated material treatments followed by risk reassessment ÷ validated material treatments requiring reassessment × 100 | [[RTP-001 Enterprise Risk Treatment Plan]]; [[REG-002 Enterprise Risk Register]] | CIO | Quarterly | Management / Executive |

---

# 32. Governance Metric Interpretation

Governance metrics should identify whether:

- Material risks have accountable treatment.
- Risk decisions remain current.
- Treatments progress beyond planning.
- Validated treatment results feed risk reassessment.

---

# 33. Identity and Access Management Metrics

| Metric ID | Metric | Type | Calculation / Measurement | Source | Owner | Frequency | Audience |
|---|---|---|---|---|---|---|---|
| MET-IAM-001 | Ordinary Access Review Completion | KPI | Completed required ordinary access reviews ÷ scheduled ordinary access reviews × 100 | Access-review records | CIO | Annual with status reporting | Management |
| MET-IAM-002 | Privileged Access Review Completion | KPI | Completed required privileged reviews ÷ scheduled privileged reviews × 100 | Access-review records | CIO | Quarterly | Management |
| MET-IAM-003 | Unauthorized Privileged Accounts | KRI | Count of privileged accounts lacking current authorization | Privileged account inventory; access reviews | CIO | Quarterly | Management |
| MET-IAM-004 | Termination Access Exceptions | KRI | Count of sampled terminations where required logical access was not disabled within the required period | HR records; account records | CIO | Monthly | Management |
| MET-IAM-005 | Dormant Accounts Beyond Disablement Threshold | KRI | Count of applicable accounts active beyond the established 60-day dormant-account threshold without approved justification | Account records | CIO | Monthly | Operational / Management |
| MET-IAM-006 | Contractor Accounts Beyond Authorized Period | KRI | Count of contractor accounts remaining active beyond approved access duration | Contractor-access records; account records | CIO | Monthly | Operational / Management |
| MET-IAM-007 | Emergency Access Events | Operational | Count of emergency-access events during reporting period | Emergency-access records | CIO | Monthly | Operational |
| MET-IAM-008 | Emergency Access Reviews Completed | KPI | Reviewed emergency-access events ÷ emergency-access events requiring review × 100 | Emergency-access records | CIO | Monthly | Management |
| MET-IAM-009 | Significant WMS Transactions Individually Attributable | KPI | Sampled significant Warehouse Management System transactions attributable to an individual ÷ sampled significant transactions × 100 | WMS records | COO | Quarterly | Management |

---

# 34. IAM Metric Interpretation

Identity metrics should help identify:

- Excessive access
- Delayed termination
- Privileged-access weakness
- Dormant-account exposure
- Contractor-access weakness
- Accountability limitations

---

# 35. Vulnerability Management Metrics

| Metric ID | Metric | Type | Calculation / Measurement | Source | Owner | Frequency | Audience |
|---|---|---|---|---|---|---|---|
| MET-VM-001 | Monthly Vulnerability Assessment Completion | KPI | Completed scheduled monthly internal scans ÷ scheduled scans × 100 | Vulnerability assessment records | IT & Information Security Manager | Monthly | Management |
| MET-VM-002 | Open Critical Vulnerabilities | KRI | Count of open Critical vulnerabilities | Vulnerability records | IT & Information Security Manager | Weekly | Operational / Management |
| MET-VM-003 | Open High Vulnerabilities | KRI | Count of open High vulnerabilities | Vulnerability records | IT & Information Security Manager | Weekly | Operational / Management |
| MET-VM-004 | Critical Vulnerabilities Remediated Within 7 Days | KPI | Critical vulnerabilities remediated within 7 days ÷ Critical vulnerabilities due during period × 100 | Vulnerability records | IT & Information Security Manager | Monthly | Management |
| MET-VM-005 | High Vulnerabilities Remediated Within 30 Days | KPI | High vulnerabilities remediated within 30 days ÷ High vulnerabilities due during period × 100 | Vulnerability records | IT & Information Security Manager | Monthly | Management |
| MET-VM-006 | Moderate Vulnerabilities Remediated Within 45 Days | KPI | Moderate vulnerabilities remediated within 45 days ÷ Moderate vulnerabilities due during period × 100 | Vulnerability records | IT & Information Security Manager | Monthly | Management |
| MET-VM-007 | Low Vulnerabilities Remediated Within 60 Days | KPI | Low vulnerabilities remediated within 60 days ÷ Low vulnerabilities due during period × 100 | Vulnerability records | IT & Information Security Manager | Monthly | Management |
| MET-VM-008 | Overdue Critical Vulnerabilities | KRI | Count of Critical vulnerabilities exceeding the 7-day remediation target without approved exception | Vulnerability records | IT & Information Security Manager | Weekly | Management / Executive when material |
| MET-VM-009 | Overdue High Vulnerabilities | KRI | Count of High vulnerabilities exceeding the 30-day remediation target without approved exception | Vulnerability records | IT & Information Security Manager | Weekly | Management |
| MET-VM-010 | Vulnerabilities Successfully Retested | KPI | Remediated vulnerabilities passing required retest ÷ vulnerabilities retested × 100 | Retest records | IT & Information Security Manager | Monthly | Management |

---

# 36. Vulnerability Metric Interpretation

Vulnerability counts alone do not establish security condition.

Interpretation should consider:

- Severity
- Exposure
- Affected system
- Exploitability
- Business importance
- Age
- Remediation status
- Compensating controls

---

# 37. Endpoint Security Metrics

| Metric ID | Metric | Type | Calculation / Measurement | Source | Owner | Frequency | Audience |
|---|---|---|---|---|---|---|---|
| MET-END-001 | Managed Antivirus Coverage | KPI | Managed applicable endpoints reporting to antivirus management ÷ known applicable endpoints × 100 | Antivirus console; endpoint inventory | IT & Information Security Manager | Monthly | Operational / Management |
| MET-END-002 | Antivirus Definition Currency | KPI | Managed endpoints with current approved malware definitions ÷ reporting endpoints × 100 | Antivirus console | IT & Information Security Manager | Weekly | Operational |
| MET-END-003 | Laptop Full-Disk Encryption Coverage | KPI | Company laptops with verified full-disk encryption ÷ company laptops × 100 | Endpoint inventory; encryption status | IT & Information Security Manager | Monthly | Management |
| MET-END-004 | Unresolved Malware Detections | KRI | Count of malware detections not resolved within the required response period | Antivirus records | IT & Information Security Manager | Weekly | Operational / Management |
| MET-END-005 | Lost or Stolen Managed Devices | Operational | Count of reported lost or stolen company-managed devices | Incident and asset records | IT & Information Security Manager | Monthly | Management |

---

# 38. Network Security Metrics

| Metric ID | Metric | Type | Calculation / Measurement | Source | Owner | Frequency | Audience |
|---|---|---|---|---|---|---|---|
| MET-NET-001 | Network Discovery Completion | KPI | Completed scheduled network-discovery assessments ÷ scheduled assessments × 100 | Network-discovery records | Network / Security Administrator | Every 6 months | Management |
| MET-NET-002 | Unauthorized Wireless Devices Detected | KRI | Count of unauthorized wireless access points or devices identified during assessment | Wireless-discovery records | Network / Security Administrator | Every 6 months | Operational / Management |
| MET-NET-003 | Unauthorized Internet-Exposed Administrative Services | KRI | Count of identified internal or administrative services exposed directly to the public Internet without authorization | Network assessment records | Network / Security Administrator | Quarterly | Management |
| MET-NET-004 | Firewall Configuration Exceptions | KRI | Count of material firewall-rule exceptions lacking current authorization | Firewall records | Network / Security Administrator | Quarterly | Management |
| MET-NET-005 | Critical Network Configuration Backup Coverage | KPI | Critical network devices with current recoverable configuration backup ÷ identified critical network devices × 100 | Configuration-backup records | Network / Security Administrator | Monthly | Operational / Management |

---

# 39. Wireless Baseline

The expected wireless environment is:

- No corporate wireless network
- One ceiling-mounted Internet-only guest wireless access point in the Scranton Headquarters lobby

Network discovery should identify deviation from this baseline.

---

# 40. Security Operations Metrics

| Metric ID | Metric | Type | Calculation / Measurement | Source | Owner | Frequency | Audience |
|---|---|---|---|---|---|---|---|
| MET-OPS-001 | Security Events Escalated | Operational | Count of security events escalated during reporting period | Security event records | IT & Information Security Manager | Monthly | Operational / Management |
| MET-OPS-002 | Security Events Awaiting Review | KRI | Count of security events exceeding the required review period | Security event records | IT & Information Security Manager | Weekly | Operational / Management |
| MET-OPS-003 | Malware Events Investigated | Operational | Count of malware events investigated during reporting period | Malware response records | IT & Information Security Manager | Monthly | Operational |
| MET-OPS-004 | Monitoring Exceptions | KRI | Count of material expected monitoring sources unavailable or not reviewed as required | Monitoring records | IT & Information Security Manager | Monthly | Management |
| MET-OPS-005 | After-Hours Escalations | Operational | Count of security events requiring after-hours response | On-call and incident records | IT & Information Security Manager | Monthly | Management |

---

# 41. Security Operations Limitation

Security Operations metrics must reflect Dunder Mifflin's operating model.

The company does not operate a 24-hour Security Operations Center.

---

# 42. Incident Response Metrics

| Metric ID | Metric | Type | Calculation / Measurement | Source | Owner | Frequency | Audience |
|---|---|---|---|---|---|---|---|
| MET-IR-001 | Security Incidents by Classification | Operational | Count of incidents by classification during reporting period | Incident records | IT & Information Security Manager | Monthly | Management |
| MET-IR-002 | Significant Incidents | KRI | Count of incidents meeting significant escalation criteria | Incident records | CIO | Monthly and Event-Driven | Executive |
| MET-IR-003 | Incident Escalation Timeliness | KPI | Incidents escalated within required period ÷ incidents requiring escalation × 100 | Incident timelines | IT & Information Security Manager | Quarterly | Management |
| MET-IR-004 | Incidents With Complete Required Evidence Records | KPI | Sampled incidents with required evidence records ÷ sampled incidents × 100 | Incident and evidence records | IT & Information Security Manager | Quarterly | Management |
| MET-IR-005 | Incident Corrective Actions Overdue | KRI | Count of incident-derived corrective actions past approved target date | Incident records; [[REG-004 Finding & Corrective Action Register]] | CIO | Monthly | Management |
| MET-IR-006 | Incident Response Exercises Completed | KPI | Completed scheduled Incident Response exercises ÷ scheduled exercises × 100 | Exercise records | CIO | Annual with status reporting | Management / Executive |

---

# 43. Incident Metric Interpretation

Incident volume must not be interpreted in isolation.

Changes may result from:

- Threat activity
- Detection capability
- Employee reporting
- Monitoring changes
- Classification changes

---

# 44. Backup and Recovery Metrics

| Metric ID | Metric | Type | Calculation / Measurement | Source | Owner | Frequency | Audience |
|---|---|---|---|---|---|---|---|
| MET-BCDR-001 | Successful Scheduled Backup Jobs | KPI | Successful scheduled backup jobs ÷ scheduled backup jobs × 100 | Backup records | System Administrator | Weekly | Operational |
| MET-BCDR-002 | Unresolved Backup Failures | KRI | Count of failed backup jobs not resolved within the required operational period | Backup records | System Administrator | Weekly | Operational / Management |
| MET-BCDR-003 | Required System Backup Coverage | KPI | Required systems confirmed within approved backup scope ÷ systems requiring backup × 100 | Asset inventory; BIA; backup configuration | CIO | Quarterly | Management |
| MET-BCDR-004 | Quarterly Representative Restore Tests Completed | KPI | Completed representative restore tests ÷ scheduled quarterly restore tests × 100 | Recovery-test records | CIO | Quarterly | Management |
| MET-BCDR-005 | Restore Test Success | KPI | Successful representative restore tests ÷ restore tests performed × 100 | [[TMP-003 Recovery Test Template]] records | CIO | Quarterly | Management |
| MET-BCDR-006 | Critical Recovery Tests Completed | KPI | Completed required annual Critical recovery tests ÷ scheduled Critical recovery tests × 100 | Recovery-test records | CIO | Annual | Management / Executive |
| MET-BCDR-007 | Critical Recovery Tests Meeting RTO | KPI / KRI | Critical recovery tests meeting applicable RTO ÷ Critical recovery tests performed × 100 | Recovery-test records; [[RPT-002 Business Impact Analysis]] | CIO | Annual and Following Test | Management / Executive |
| MET-BCDR-008 | Critical Recovery Tests Meeting RPO | KPI / KRI | Critical recovery tests meeting applicable RPO ÷ Critical recovery tests performed × 100 | Recovery-test records; [[RPT-002 Business Impact Analysis]] | CIO | Annual and Following Test | Management / Executive |
| MET-BCDR-009 | Failed Critical Recovery Tests | KRI | Count of Critical recovery tests failing RTO, RPO, technical recovery, or required business validation | Recovery-test records | CIO | Event-Driven | Management / Executive |
| MET-BCDR-010 | Off-Site Backup Rotation Exceptions | KRI | Count of material deviations from required encrypted external-drive rotation | Backup rotation records | CIO | Monthly | Management |
| MET-BCDR-011 | Recovery Documentation Exceptions | KRI | Count of material recovery-documentation deficiencies identified through review or testing | Recovery records | CIO | Quarterly | Management |

---

# 45. Backup Rotation Baseline

The external backup rotation uses:

- 3 encrypted external drives per facility
- 7 facilities
- 21 drives total

The off-site disaster recovery storage provider normally holds:

- 2 latest weekly generations per facility
- 14 encrypted drives total

---

# 46. Backup Success Does Not Equal Recovery Success

A successful backup job does not prove that:

- Data can be restored.
- Recovery can satisfy RTO.
- Recovery can satisfy RPO.
- Documentation is usable.
- Business operations can resume.

Recovery metrics must include actual testing.

---

# 47. RTO and RPO Measurement

Recovery Time Objective (RTO) and Recovery Point Objective (RPO) measurements must use the requirements established in [[RPT-002 Business Impact Analysis]].

---

# 48. Manual Continuity Metrics

| Metric ID | Metric | Type | Calculation / Measurement | Source | Owner | Frequency | Audience |
|---|---|---|---|---|---|---|---|
| MET-BCDR-012 | Manual Continuity Exercises Completed | KPI | Completed scheduled manual-processing exercises ÷ scheduled exercises × 100 | Exercise records | COO | Annual | Management |
| MET-BCDR-013 | Manual Records Successfully Reconciled | KPI | Sampled manual records successfully entered, reconciled, and verified after restoration ÷ sampled manual records × 100 | Manual-processing and reconciliation records | COO | Following Exercise or Use | Management |
| MET-BCDR-014 | Manual Processing Exceptions | KRI | Count of material duplicate, missing, unauthorized, or unreconciled manual transactions | Manual-processing records | COO | Following Exercise or Use | Management |

---

# 49. Manual Processing Lifecycle

Manual continuity measurement should reflect:

**Collect → Review → Enter → Reconcile → Verify**

---

# 50. Physical Security Metrics

| Metric ID | Metric | Type | Calculation / Measurement | Source | Owner | Frequency | Audience |
|---|---|---|---|---|---|---|---|
| MET-PHY-001 | Annual Physical Access Review Completion | KPI | Completed required physical-access reviews ÷ scheduled reviews × 100 | Physical-access review records | COO | Annual | Management |
| MET-PHY-002 | Unauthorized Restricted-Area Access Events | KRI | Count of confirmed unauthorized Restricted-area access events | Security and access records | COO | Monthly | Management |
| MET-PHY-003 | Lost or Unreturned Physical Access Credentials | KRI | Count of lost or unreturned active cards or keys requiring action | Access-control records | COO | Monthly | Management |
| MET-PHY-004 | Visitor Record Exceptions | KRI | Count of sampled visitor records missing required authorization, registration, escort, or closure information | Visitor logs | COO | Quarterly | Management |
| MET-PHY-005 | Warehouse Cage Access Exceptions | KRI | Count of identified unauthorized or inadequately controlled high-value cage access events | Warehouse access records | COO | Monthly | Management |
| MET-PHY-006 | Material Environmental Control Exceptions | KRI | Count of material fire, water, utility, HVAC, or UPS conditions requiring corrective action | Facility records | COO | Quarterly | Management |

---

# 51. Personnel Security Metrics

| Metric ID | Metric | Type | Calculation / Measurement | Source | Owner | Frequency | Audience |
|---|---|---|---|---|---|---|---|
| MET-PER-001 | Termination Checklist Completion | KPI | Completed required termination checklists ÷ applicable terminations × 100 | HR termination records | CFO | Monthly | Management |
| MET-PER-002 | Unreturned Company Assets Following Termination | KRI | Count of material company assets not returned within required period | HR and asset records | CFO | Monthly | Management |
| MET-PER-003 | Key-Person Dependencies Without Documented Alternate | KRI | Count of identified critical functions dependent on one person without adequate documented alternate capability | Personnel dependency records | Executive Management | Quarterly | Management / Executive |
| MET-PER-004 | Critical Functions With Cross-Trained Alternate | KPI | Critical functions with documented trained alternate personnel ÷ identified critical functions requiring alternate coverage × 100 | Cross-training records | Executive Management | Quarterly | Management |
| MET-PER-005 | Personnel Security Exceptions | KRI | Count of material personnel-security exceptions requiring management attention | HR and security records | CFO | Monthly | Management |

---

# 52. Third-Party Security Metrics

| Metric ID | Metric | Type | Calculation / Measurement | Source | Owner | Frequency | Audience |
|---|---|---|---|---|---|---|---|
| MET-TPRM-001 | Critical Third Parties Reviewed Annually | KPI | Critical third parties reviewed within required annual period ÷ Critical third parties × 100 | Third-party records | CIO | Quarterly Status / Annual Measure | Management |
| MET-TPRM-002 | Important Third Parties Reviewed Biennially | KPI | Important third parties reviewed within required two-year period ÷ Important third parties × 100 | Third-party records | CIO | Quarterly Status | Management |
| MET-TPRM-003 | Critical Third Parties With Current Security Requirements | KPI | Critical third parties with current required security and confidentiality terms ÷ Critical third parties × 100 | Contracts; third-party records | CIO | Quarterly | Management |
| MET-TPRM-004 | Overdue Third-Party Security Reviews | KRI | Count of Critical or Important third parties past required review date | Third-party records | CIO | Monthly | Management |
| MET-TPRM-005 | Third-Party Security Incidents | KRI | Count of reported third-party security incidents materially affecting Dunder Mifflin | Incident and third-party records | CIO | Event-Driven / Monthly | Management / Executive |
| MET-TPRM-006 | Third-Party Access Exceptions | KRI | Count of third-party accounts or physical access permissions exceeding approved scope or duration | Access records | CIO | Monthly | Management |

---

# 53. Third-Party Metric Limitation

A completed vendor review does not automatically establish that the third party is secure.

Review metrics measure performance of the governance process.

Assessment results determine identified security condition.

---

# 54. Infinity and Secure Development Metrics

| Metric ID | Metric | Type | Calculation / Measurement | Source | Owner | Frequency | Audience |
|---|---|---|---|---|---|---|---|
| MET-APP-001 | Infinity Security Assessment Completion | KPI | Required annual Infinity security assessment completed by due date | [[PROC-019 Application Security Assessment Procedure]] | CIO | Annual | Management / Executive |
| MET-APP-002 | Infinity Penetration Test Completion | KPI | Required annual Infinity penetration test completed by due date | Penetration-test records | CIO | Annual | Management / Executive |
| MET-APP-003 | Open High or Critical Infinity Security Findings | KRI | Count of open High or Critical Infinity security findings | [[REG-004 Finding & Corrective Action Register]] | CIO | Monthly | Management / Executive |
| MET-APP-004 | Infinity Findings Successfully Retested | KPI | Infinity findings passing required retest ÷ Infinity findings retested × 100 | Application assessment and retest records | CIO | Quarterly | Management |
| MET-APP-005 | Material Infinity Releases With Required Security Review | KPI | Material releases receiving required security review ÷ material releases × 100 | Change and release records | CIO | Quarterly | Management |
| MET-APP-006 | Material Infinity Releases With Required Testing | KPI | Material releases receiving required testing ÷ material releases × 100 | Change and release records | CIO | Quarterly | Management |
| MET-APP-007 | Unauthorized Production Changes | KRI | Count of identified production changes lacking required authorization | Change records | CIO | Monthly | Management |
| MET-APP-008 | Contractor Access Beyond Authorized Duration | KRI | Count of Infinity contractor access permissions active beyond approved period | Contractor-access records | CIO | Monthly | Management |
| MET-APP-009 | Annual Infinity Transferability Review Completion | KPI | Required annual transferability review completed by due date | [[RPT-004 Infinity Transferability Review]] | CIO | Annual | Management / Executive |
| MET-APP-010 | Material Transferability Deficiencies | KRI | Count of material conditions preventing a qualified replacement from assuming support without unreasonable dependency on the incumbent contractor | Transferability review | CIO | Annual | Management / Executive |

---

# 55. Infinity Assurance Chain

Infinity metrics should support:

**Security Assessment / Penetration Test → Finding → Remediation → Retest → Control Effectiveness → R006 Risk Reassessment**

---

# 56. Security Awareness Metrics

| Metric ID | Metric | Type | Calculation / Measurement | Source | Owner | Frequency | Audience |
|---|---|---|---|---|---|---|---|
| MET-AWR-001 | Initial Awareness Training Completion | KPI | Applicable personnel completing initial security training within 5 business days ÷ applicable personnel × 100 | Training records | IT & Information Security Manager | Monthly | Management |
| MET-AWR-002 | Annual Awareness Training Completion | KPI | Applicable personnel completing annual refresher ÷ applicable personnel × 100 | Training records | IT & Information Security Manager | Annual with status reporting | Management |
| MET-AWR-003 | Annual Awareness Assessment Pass Rate | KPI | Personnel scoring at least 80% ÷ personnel completing annual assessment × 100 | Assessment records | IT & Information Security Manager | Annual | Management |
| MET-AWR-004 | Monthly Phishing Simulation Interaction Rate | KRI | Personnel performing defined unsafe interaction ÷ personnel receiving simulation × 100 | Phishing simulation records | IT & Information Security Manager | Monthly | Management |
| MET-AWR-005 | Monthly Phishing Simulation Reporting Rate | KPI | Personnel correctly reporting simulation ÷ personnel receiving simulation × 100 | Phishing simulation records | IT & Information Security Manager | Monthly | Management |
| MET-AWR-006 | Required Corrective Awareness Completion | KPI | Personnel completing assigned corrective awareness activity ÷ personnel assigned corrective activity × 100 | Training records | IT & Information Security Manager | Monthly | Management |

---

# 57. Phishing Metric Interpretation

Phishing simulation metrics must be interpreted carefully.

A failed simulation does not by itself establish:

- Malicious behavior
- Employee misconduct
- Overall awareness-program failure

Trends and repeated behavior are more useful than isolated events.

---

# 58. Security Assurance Metrics

| Metric ID | Metric | Type | Calculation / Measurement | Source | Owner | Frequency | Audience |
|---|---|---|---|---|---|---|---|
| MET-ASSUR-001 | Annual Assurance Plan Completion | KPI | Completed planned assessments ÷ assessments scheduled to date × 100 | [[PLN-005 Annual Assurance Plan]] | CIO | Quarterly | Management / Executive |
| MET-ASSUR-002 | Critical Controls Assessed as Scheduled | KPI | Critical controls assessed as scheduled ÷ Critical controls scheduled for assessment × 100 | [[REG-003 Enterprise Security Control Inventory]]; assessment records | CIO | Quarterly | Management |
| MET-ASSUR-003 | Effective Controls | Operational | Count and percentage of assessed controls rated Effective | [[REG-003 Enterprise Security Control Inventory]] | CIO | Quarterly | Management |
| MET-ASSUR-004 | Partially Effective Controls | KRI | Count and percentage of assessed controls rated Partially Effective | [[REG-003 Enterprise Security Control Inventory]] | CIO | Quarterly | Management |
| MET-ASSUR-005 | Ineffective Controls | KRI | Count of assessed controls rated Ineffective | [[REG-003 Enterprise Security Control Inventory]] | CIO | Monthly | Management / Executive when material |
| MET-ASSUR-006 | Controls Awaiting Validation | Operational | Count of controls in Validation Pending status | [[REG-003 Enterprise Security Control Inventory]] | CIO | Monthly | Management |
| MET-ASSUR-007 | Open Findings | Operational | Count of open findings | [[REG-004 Finding & Corrective Action Register]] | CIO | Monthly | Management |
| MET-ASSUR-008 | Open High-Priority Findings | KRI | Count of open High-priority findings | [[REG-004 Finding & Corrective Action Register]] | CIO | Monthly | Management / Executive |
| MET-ASSUR-009 | Open Critical Findings | KRI | Count of open Critical findings | [[REG-004 Finding & Corrective Action Register]] | CIO | Event-Driven / Monthly | Executive |
| MET-ASSUR-010 | Overdue Findings | KRI | Count of open findings beyond approved target date | [[REG-004 Finding & Corrective Action Register]] | CIO | Monthly | Management |
| MET-ASSUR-011 | Overdue High or Critical Findings | KRI | Count of High or Critical findings beyond approved target date | [[REG-004 Finding & Corrective Action Register]] | CIO | Monthly | Management / Executive |
| MET-ASSUR-012 | Corrective Actions Awaiting Validation | Operational | Count of corrective actions reported complete but awaiting validation | [[REG-004 Finding & Corrective Action Register]] | CIO | Monthly | Management |
| MET-ASSUR-013 | Successful Retests | KPI | Successful retests ÷ completed retests × 100 | [[REG-004 Finding & Corrective Action Register]] | CIO | Quarterly | Management |
| MET-ASSUR-014 | Failed Retests | KRI | Count of failed retests | [[REG-004 Finding & Corrective Action Register]] | CIO | Monthly | Management |
| MET-ASSUR-015 | Reopened Findings | KRI | Count of previously closed findings reopened because remediation was ineffective or unsupported | [[REG-004 Finding & Corrective Action Register]] | CIO | Quarterly | Management |
| MET-ASSUR-016 | Recurring Findings | KRI | Count of findings representing recurrence of previously corrected material weakness | [[REG-004 Finding & Corrective Action Register]] | CIO | Quarterly | Management |
| MET-ASSUR-017 | Expired Security Exceptions | KRI | Count of security exceptions past approved expiration without authorized renewal or closure | Exception records | CIO | Monthly | Management |
| MET-ASSUR-018 | Material Findings With Accountable Owner | KPI | Material findings with one identified accountable owner ÷ material findings × 100 | [[REG-004 Finding & Corrective Action Register]] | CIO | Monthly | Management |

---

# 59. Finding Aging Metrics

Finding aging may also be reported by:

- Less than 30 days
- 30 to 60 days
- 61 to 90 days
- More than 90 days

when useful for management oversight.

---

# 60. Finding Age Limitation

Finding age does not replace priority.

A new Critical finding may require more urgent action than an older Low finding.

---

# 61. Control Effectiveness Metrics

Control effectiveness reporting should distinguish among:

- Effective
- Partially Effective
- Ineffective
- Not Implemented
- Not Yet Assessed

---

# 62. Not Yet Assessed

Controls lacking sufficient assessment evidence must not be reported as Effective merely because no failure is known.

---

# 63. Implementation Metrics

Implementation status should distinguish among:

- Planned
- Implementing
- Implemented
- Validation Pending
- Validated

---

# 64. Implemented Does Not Mean Effective

A control may be implemented without sufficient evidence to establish effectiveness.

Metrics must preserve that distinction.

---

# 65. Risk Treatment Metrics

| Metric ID | Metric | Type | Calculation / Measurement | Source | Owner | Frequency | Audience |
|---|---|---|---|---|---|---|---|
| MET-GOV-006 | Planned Treatments | Operational | Count of treatment actions in Planned status | [[RTP-001 Enterprise Risk Treatment Plan]] | CIO | Monthly | Management |
| MET-GOV-007 | Treatments Implementing | Operational | Count of treatment actions in Implementing status | [[RTP-001 Enterprise Risk Treatment Plan]] | CIO | Monthly | Management |
| MET-GOV-008 | Treatments Awaiting Validation | KRI | Count of treatment actions in Validation Pending status | [[RTP-001 Enterprise Risk Treatment Plan]] | CIO | Monthly | Management |
| MET-GOV-009 | Validated Treatments | KPI | Count of treatment actions reaching Validated status during reporting period | [[RTP-001 Enterprise Risk Treatment Plan]] | CIO | Quarterly | Management / Executive |
| MET-GOV-010 | Overdue Treatment Actions | KRI | Count of treatment actions exceeding approved target completion date | [[RTP-001 Enterprise Risk Treatment Plan]] | CIO | Monthly | Management / Executive when material |

---

# 66. No Premature Risk Credit

Treatment metrics must not imply that risk reduction has occurred merely because a treatment is:

- Planned
- Approved
- Implementing
- Implemented

Validated control performance and risk reassessment are required before demonstrated risk reduction is recognized.

---

# 67. Executive Metrics

Executive reporting should use a limited set of metrics that communicate:

- Material enterprise risk
- Significant control weakness
- Significant overdue corrective action
- Treatment progress
- Recovery readiness
- Major third-party exposure
- Required decisions

---

# 68. Executive Reporting Limitation

Executive reporting should not overwhelm senior leadership with unnecessary:

- Log counts
- Individual vulnerability details
- Routine tickets
- Raw technical alerts

unless those details have material decision value.

---

# 69. Management Metrics

Management reporting should emphasize:

- Accountability
- Performance against requirements
- Open findings
- Corrective actions
- Treatment progress
- Exceptions
- Trends
- Upcoming deadlines

---

# 70. Operational Metrics

Operational reporting should contain the detailed measurements needed to:

- Execute controls
- Investigate exceptions
- Correct deficiencies
- Maintain evidence
- Support assessment

---

# 71. Metric Escalation

A metric crossing a material threshold may require:

- Investigation
- Corrective action
- Management escalation
- Finding creation
- Risk reassessment
- Incident response

depending on the condition.

---

# 72. Metric Does Not Automatically Create Finding

An unfavorable metric does not automatically become a formal finding.

The condition must be evaluated to determine whether a requirement or control deficiency exists.

---

# 73. Metric Does Not Automatically Create Incident

An unfavorable metric does not automatically constitute a security incident.

Suspected active compromise must be evaluated under:

- [[PROC-010 Security Event Escalation Procedure]]
- [[PLN-001 Incident Response Plan]]

---

# 74. Metric Does Not Automatically Change Risk

A metric does not mechanically change an enterprise risk score.

It provides evidence that may support risk reassessment.

---

# 75. Risk Reassessment

Material metric trends should be considered during risk reassessment when they indicate that:

- Exposure has changed.
- Control effectiveness has changed.
- Business impact has changed.
- An important assumption is no longer valid.

---

# 76. Inherent Risk Still Matters

Metric prioritization must not rely only on current residual risk.

Controls reducing severe inherent risk may require strong monitoring because failure could restore substantial exposure.

---

# 77. Example

A control supporting a risk with:

- Inherent Risk: **20 Critical**
- Current Residual Risk: **12 High**

may warrant greater metric attention than a control supporting a naturally Low-risk condition.

---

# 78. BIA Relationship

Metrics involving recovery and availability must use requirements established in [[RPT-002 Business Impact Analysis]].

---

# 79. BIA Measures

Relevant Business Impact Analysis measures include:

- Maximum Tolerable Downtime (MTD)
- Recovery Time Objective (RTO)
- Recovery Point Objective (RPO)

---

# 80. Metric Source Integrity

Source systems and records used for metrics should be protected against unauthorized modification appropriate to their importance.

---

# 81. Manual Metric Collection

Where automated reporting is unavailable, metrics may be calculated manually from reliable records.

---

# 82. Manual Collection Requirements

Manual collection should identify:

- Source records
- Measurement period
- Calculation
- Collector
- Review where appropriate

---

# 83. Calculation Consistency

The same metric should use the same approved calculation across reporting periods unless the definition is formally revised.

---

# 84. Metric Definition Change

A material change to:

- Formula
- Scope
- Population
- Data source
- Threshold

must be documented because it may affect trend comparability.

---

# 85. Historical Comparability

Where a metric definition changes materially, reports should avoid presenting old and new measurements as directly comparable without explanation.

---

# 86. Zero Values

A zero value must represent an actual measured zero.

It must not be used when data is unavailable.

---

# 87. Percentage Metrics

Percentage metrics should identify the relevant denominator.

---

# 88. Small Population Caution

Percentages based on very small populations should be interpreted with the underlying count.

---

# 89. Example

If one of two required recovery tests fails, reporting only a 50% success rate may obscure the small sample.

Appropriate reporting may show:

**1 of 2 tests passed, 50%**

---

# 90. Metric Period

Each measurement must clearly identify its reporting period.

---

# 91. Point-in-Time Metrics

Some metrics represent a point-in-time condition.

Examples include:

- Open Critical vulnerabilities
- Active unauthorized privileged accounts
- Overdue findings

---

# 92. Period Metrics

Some metrics represent activity during a period.

Examples include:

- Incidents during the month
- Vulnerabilities remediated during the quarter
- Phishing simulations during the month

---

# 93. Cumulative Metrics

Cumulative metrics must clearly state the period over which accumulation occurs.

---

# 94. Metric Exceptions

Known material data-quality or scope limitations must accompany the metric.

---

# 95. Incomplete Coverage

A metric covering only part of the enterprise must not be represented as enterprise-wide.

---

# 96. Control Metrics and Evidence

Metrics are a form of evidence but may require supporting records during assessment.

---

# 97. Assessment Use

Assessors may use metrics to:

- Identify trends
- Select samples
- Identify exceptions
- Prioritize testing
- Support conclusions

---

# 98. Metrics Do Not Replace Assessment

A dashboard showing favorable metrics does not eliminate the need for:

- Inspection
- Sampling
- Technical Testing
- Independent Performance
- Exercises
- Reconciliation

where appropriate.

---

# 99. Assessment Work Plan Relationship

[[TMP-001 Assessment Work Plan Template]] may identify metrics as:

- Assessment evidence
- Sampling inputs
- Control-performance indicators

---

# 100. Finding Relationship

Material metric exceptions may result in findings maintained in [[REG-004 Finding & Corrective Action Register]].

---

# 101. Control Inventory Relationship

Metrics should be connected to applicable controls in [[REG-003 Enterprise Security Control Inventory]] where practical.

---

# 102. Risk Register Relationship

Material KRI results should be considered against [[REG-002 Enterprise Risk Register]].

---

# 103. Risk Treatment Relationship

Metrics may demonstrate whether treatments in [[RTP-001 Enterprise Risk Treatment Plan]] are progressing or operating as expected.

---

# 104. Metric Reporting Cycle

Operational metrics may be reviewed:

- Weekly
- Monthly
- Event-driven

depending on the control.

Management metrics are generally reviewed:

- Monthly
- Quarterly

Executive metrics are generally reviewed:

- Quarterly
- Event-driven for material conditions

---

# 105. Event-Driven Reporting

Material conditions must not wait for the normal reporting cycle.

---

# 106. Immediate Escalation

Immediate escalation is required where metric evidence indicates a material threat to:

- Human safety
- Sensitive information
- Critical systems
- Significant business operations

---

# 107. Safety Priority

Human life and safety take priority over:

- Systems
- Operations
- Facilities
- Equipment
- Inventory
- Revenue
- Other assets

---

# 108. Dashboard Status

The operational dashboard may use:

- Green
- Yellow
- Red
- Not Measured
- Not Applicable

---

# 109. Dashboard Trend

Dashboard trend may use:

- Improving
- Stable
- Deteriorating
- Insufficient Data

---

# 110. Dashboard Placeholders

Where actual measurement has not occurred, dashboards must use placeholders or explicit unavailable status rather than invented values.

---

# 111. Example Dashboard Entry

| Metric | Current | Target | Status | Trend | Comment |
|---|---:|---:|---|---|---|
| Critical vulnerabilities remediated within 7 days | # / % | Defined target | Green / Yellow / Red / Not Measured | Improving / Stable / Deteriorating / Insufficient Data | Evidence-based explanation |

---

# 112. Executive Security Summary

Executive metrics support [[RPT-006 Executive Security Summary]].

---

# 113. Management Security Report

Management metrics support [[RPT-007 Management Security Report]].

---

# 114. Operational Security Report

Operational metrics support [[RPT-008 Operational Security Report & Dashboard]].

---

# 115. Reporting Consistency

The three reporting levels should derive from consistent underlying evidence.

The reports differ primarily in:

- Detail
- Aggregation
- Context
- Decision purpose

---

# 116. Reporting Example

A technical condition may progress as:

**12 overdue Critical vulnerabilities**

↓

**Critical vulnerability remediation target is not being met**

↓

**Management remediation performance requires action**

↓

**Exposure affecting R003, R004, R006, or R007 may be greater than expected**

↓

**Executive decision may be required if the condition is material**

---

# 117. Metrics and Accountability

Metrics should identify accountable ownership without being designed primarily to punish individuals.

Their purpose is to improve:

- Visibility
- Accountability
- Risk management
- Control performance
- Decision-making

---

# 118. Privacy

Security metrics involving personnel must be handled with appropriate privacy.

---

# 119. No Indiscriminate Surveillance

The security metrics program must not be used as justification for unnecessary or indiscriminate employee surveillance.

---

# 120. Personnel-Level Data

Individual-level information should be included only when required for:

- Security operations
- Investigation
- Corrective action
- Management responsibility
- Legal or Human Resources purposes

---

# 121. Metric Retention

Metric records must be retained sufficiently to support:

- Trend analysis
- Assurance
- Findings
- Risk reassessment
- Management reporting
- Historical comparison

---

# 122. Metric Review

The metric catalog must be reviewed at least quarterly for:

- Relevance
- Data availability
- Calculation accuracy
- Ownership
- Reporting frequency
- Threshold usefulness

---

# 123. Metric Retirement

A metric may be retired when:

- It no longer supports a meaningful decision.
- The related control no longer exists.
- A superior metric replaces it.
- The measured risk is no longer applicable.

---

# 124. Metric Retirement History

Retired metrics should retain sufficient history to explain prior reports when material.

---

# 125. New Metrics

New metrics may be added when:

- New controls are implemented.
- New risks are identified.
- Findings reveal measurement gaps.
- Management requires additional visibility.
- New systems provide useful evidence.

---

# 126. Metric Quality Questions

Before adopting a metric, Dunder Mifflin should ask:

1. What question does this metric answer?
2. Who needs the answer?
3. What action could result?
4. Is the source reliable?
5. Is the calculation understandable?
6. Can the metric be collected consistently?
7. Could the metric be misleading without context?

---

# 127. Avoid Vanity Metrics

A metric should not be maintained solely because:

- The number is large.
- The number appears favorable.
- It is easy to collect.
- It makes a dashboard look complete.

---

# 128. Useful Metric Principle

A useful metric should contribute to:

- Action
- Accountability
- Risk understanding
- Control understanding
- Decision-making

---

# 129. Continuous Improvement

Metrics provide input to continuous improvement.

---

# 130. Continuous Improvement Chain

**Measure → Interpret → Investigate → Act → Validate → Reassess**

---

# 131. Metrics and Findings

Metrics may identify a potential weakness.

Assessment determines whether the condition constitutes a finding.

---

# 132. Metrics and Corrective Action

Corrective-action metrics help management determine whether identified weaknesses are actually progressing toward validated closure.

---

# 133. Metrics and Retesting

Retest metrics help identify whether corrective actions are solving the underlying problem.

---

# 134. Metrics and Risk

Metrics provide evidence for risk decisions.

They do not replace risk analysis.

---

# 135. Metrics and Executive Decisions

Executive metrics should make clear when leadership must:

- Accept risk
- Provide resources
- Resolve ownership
- Change priority
- Approve significant treatment
- Address significant overdue remediation

---

# 136. Initial Catalog State

At initial publication, this catalog defines the required measurement framework.

Actual metric values will be populated only as supporting operational and assessment evidence becomes available.

---

# 137. Related Artifacts

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
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[POL-003 Access Control Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-006 Security Awareness & Training Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[STD-007 Penetration Testing Standard]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[STD-009 Infinity Security Standard]]
- [[PROC-001 Joiner-Mover-Leaver Procedure]]
- [[PROC-003 Access Review Procedure]]
- [[PROC-006 Vulnerability Assessment Procedure]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]
- [[PROC-008 Security Monitoring Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-013 Manual Processing Procedure]]
- [[PROC-017 Personnel Security Procedure]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-019 Application Security Assessment Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PLN-005 Annual Assurance Plan]]
- [[TMP-001 Assessment Work Plan Template]]
- [[TMP-003 Recovery Test Template]]
- [[RPT-006 Executive Security Summary]]
- [[RPT-007 Management Security Report]]
- [[RPT-008 Operational Security Report & Dashboard]]

---

# 138. Review

This catalog must be reviewed:

- At least quarterly
- Following material control change
- Following material risk change
- Following significant assessment findings
- Following significant reporting change
- When a metric is found to be misleading, unreliable, or no longer useful

Routine metric values do not require CEO approval.

Material changes to the security measurement framework require approval consistent with the enterprise security governance framework.

---

# 139. Revision History

| Version | Date     | Description                      | Approval |
| ------- | -------- | -------------------------------- | -------- |
| 1.0     | May 2013 | Initial Security Metrics Catalog | CEO      |