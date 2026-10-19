# REG-007 Cross-Reference Matrix

## Document Control

| Field | Value |
|---|---|
| Document ID | REG-007 |
| Title | Cross-Reference Matrix |
| Version | 1.0 |
| Classification | Internal |
| Status | Active |
| Owner | IT & Information Security |
| Approved By | CIO |
| Review Frequency | Quarterly and Following Material Program Changes |

---

# 1. Purpose

This register provides cross-reference traceability among the principal artifacts within the Dunder Mifflin Enterprise Information Security & Risk Management Program.

The matrix supports verification that identified risks are connected to appropriate governance requirements, treatment activities, controls, operating procedures, assessment activities, and management oversight.

The register also supports identification of:

- Missing artifact relationships
- Orphaned controls
- Unsupported requirements
- Dead-end references
- Inconsistent document references
- Missing procedures
- Missing assurance activities
- Changes that may affect multiple program artifacts

This register does not replace the detailed Enterprise Risk Treatment Plan or Enterprise Security Control Inventory.

---

# 2. Traceability Model

The security program uses the following traceability model:

**Business Requirement → Asset/Process → Classification/BIA → Risk → Treatment → Policy/Standard → Control → Procedure → Implementation → Evidence → Test/Assessment → Finding → Remediation → Retest → Risk Reassessment → Management Decision → Continuous Monitoring**

Not every risk requires a unique artifact at every stage.

A single policy, control, procedure, or assessment activity may support multiple risks. Likewise, a single risk may require several controls operating together.

---

# 3. Authoritative Traceability Sources

Detailed traceability is distributed among several controlled artifacts.

| Artifact | Primary Traceability Function |
|---|---|
| [[RPT-002 Business Impact Analysis]] | Connects business processes and systems to criticality and recovery requirements. |
| [[RPT-003 Enterprise Risk Assessment]] | Documents risk identification, analysis, and current residual risk. |
| [[REG-002 Enterprise Risk Register]] | Maintains the authoritative inventory and scoring of enterprise risks. |
| [[RTP-001 Enterprise Risk Treatment Plan]] | Connects risks to treatment decisions, owners, planned actions, evidence expectations, validation, and target residual risk. |
| [[REG-003 Enterprise Security Control Inventory]] | Connects requirements and risks to individual controls, operators, evidence, assessment methods, status, and effectiveness. |
| [[PLN-005 Annual Assurance Plan]] | Establishes assurance priorities and planned assessment activity. |
| [[TMP-001 Assessment Work Plan Template]] | Defines how an individual assessment is scoped and performed. |
| [[REG-004 Finding & Corrective Action Register]] | Tracks findings, corrective actions, remediation, retesting, and closure. |
| [[REG-005 Security Metrics Catalog]] | Defines security performance and risk indicators used for monitoring and reporting. |

---

# 4. Risk-to-Governance Cross-Reference

The following matrix identifies the principal controlled artifacts associated with each enterprise risk.

The matrix identifies major relationships and is not intended to list every supporting control or evidence source.

## 4.1 Cybersecurity and Information Risks

| Risk | Risk Description | Principal Governance and Control Artifacts |
|---|---|---|
| R001 | Phishing / Credential Compromise | [[POL-003 Access Control Policy]]; [[POL-006 Security Awareness & Training Policy]]; [[POL-009 Incident Response Policy]]; [[STD-005 Authentication & Account Security Standard]]; [[PRO-005 Security Operations Program]]; [[PROC-008 Security Monitoring Procedure]]; [[PBK-001 Phishing & Credential Compromise Playbook]] |
| R002 | Business Email Compromise | [[POL-003 Access Control Policy]]; [[POL-006 Security Awareness & Training Policy]]; [[POL-009 Incident Response Policy]]; [[STD-005 Authentication & Account Security Standard]]; [[PRO-005 Security Operations Program]]; [[PBK-001 Phishing & Credential Compromise Playbook]] |
| R003 | Ransomware | [[POL-007 Change & Configuration Management Policy]]; [[POL-009 Incident Response Policy]]; [[POL-010 Business Continuity & Disaster Recovery Policy]]; [[PRO-004 Vulnerability Management Program]]; [[PRO-005 Security Operations Program]]; [[PROC-009 Malware Response Procedure]]; [[PROC-012 Backup & Recovery Procedure]]; [[PBK-002 Malware & Ransomware Playbook]] |
| R004 | Malware | [[POL-007 Change & Configuration Management Policy]]; [[POL-009 Incident Response Policy]]; [[PRO-004 Vulnerability Management Program]]; [[PRO-005 Security Operations Program]]; [[STD-003 Endpoint Security Standard]]; [[PROC-009 Malware Response Procedure]]; [[PBK-002 Malware & Ransomware Playbook]] |
| R005 | Password / Authentication Weakness | [[POL-003 Access Control Policy]]; [[STD-005 Authentication & Account Security Standard]]; [[PRO-003 Identity and Access Management Program]]; [[PROC-001 Joiner-Mover-Leaver Procedure]]; [[PROC-002 Privileged Access Procedure]]; [[PROC-003 Access Review Procedure]]; [[PROC-005 Emergency Access Procedure]] |
| R006 | Infinity Application Compromise | [[POL-012 Application & Secure Development Policy]]; [[PRO-007 Secure Software Development Lifecycle Program]]; [[STD-009 Infinity Security Standard]]; [[PROC-018 Secure Change & Release Procedure]]; [[PROC-019 Application Security Assessment Procedure]]; [[STD-007 Penetration Testing Standard]]; [[PLN-001 Incident Response Plan]] |
| R007 | Internet Infrastructure Compromise | [[POL-007 Change & Configuration Management Policy]]; [[PRO-002 Enterprise Security Architecture Program]]; [[STD-002 Network Security Standard]]; [[STD-006 Secure Configuration Standard]]; [[PRO-004 Vulnerability Management Program]]; [[PROC-008 Security Monitoring Procedure]] |
| R008 | Denial-of-Service Attack | [[PRO-002 Enterprise Security Architecture Program]]; [[STD-002 Network Security Standard]]; [[PLN-001 Incident Response Plan]]; [[PLN-002 Business Continuity Plan]]; [[PROC-010 Security Event Escalation Procedure]] |
| R009 | Sensitive Information Theft / Extortion | [[POL-003 Access Control Policy]]; [[POL-004 Information Classification & Handling Policy]]; [[POL-009 Incident Response Policy]]; [[STD-001 Information Classification Standard]]; [[STD-003 Endpoint Security Standard]]; [[PRO-003 Identity and Access Management Program]]; [[PBK-004 Data Exposure Playbook]] |
| R010 | Unauthorized / Excessive Access | [[POL-003 Access Control Policy]]; [[PRO-003 Identity and Access Management Program]]; [[STD-005 Authentication & Account Security Standard]]; [[PROC-001 Joiner-Mover-Leaver Procedure]]; [[PROC-002 Privileged Access Procedure]]; [[PROC-003 Access Review Procedure]]; [[PROC-004 Contractor Access Procedure]] |
| R011 | Delayed Termination Access Removal | [[POL-003 Access Control Policy]]; [[PRO-003 Identity and Access Management Program]]; [[PROC-001 Joiner-Mover-Leaver Procedure]]; [[PROC-017 Personnel Security Procedure]]; [[PBK-003 Unauthorized Access Playbook]] |
| R012 | Malicious Insider | [[POL-003 Access Control Policy]]; [[POL-004 Information Classification & Handling Policy]]; [[POL-009 Incident Response Policy]]; [[POL-011 Physical & Environmental Security Policy]]; [[PRO-003 Identity and Access Management Program]]; [[PROC-017 Personnel Security Procedure]]; [[PBK-003 Unauthorized Access Playbook]] |
| R013 | Administrative / Configuration Error | [[POL-007 Change & Configuration Management Policy]]; [[STD-006 Secure Configuration Standard]]; [[PROC-018 Secure Change & Release Procedure]]; [[PRO-002 Enterprise Security Architecture Program]]; [[PLN-003 Disaster Recovery Plan]] |
| R014 | Lost or Stolen Device | [[POL-003 Access Control Policy]]; [[POL-004 Information Classification & Handling Policy]]; [[STD-003 Endpoint Security Standard]]; [[STD-005 Authentication & Account Security Standard]]; [[PLN-001 Incident Response Plan]]; [[PBK-004 Data Exposure Playbook]] |
| R015 | Shared Warehouse Account | [[POL-003 Access Control Policy]]; [[PRO-003 Identity and Access Management Program]]; [[STD-005 Authentication & Account Security Standard]]; [[PROC-003 Access Review Procedure]]; [[PROC-008 Security Monitoring Procedure]] |

---

## 4.2 Third-Party, Supplier, and Dependency Risks

| Risk | Risk Description | Principal Governance and Control Artifacts |
|---|---|---|
| R016 | Cloud Service Outage | [[POL-010 Business Continuity & Disaster Recovery Policy]]; [[PLN-002 Business Continuity Plan]]; [[PLN-003 Disaster Recovery Plan]]; [[PLN-004 Cloud Exit & Emergency Migration Plan]]; [[PROC-012 Backup & Recovery Procedure]]; [[RPT-002 Business Impact Analysis]] |
| R017 | Internet Service Provider Outage | [[POL-010 Business Continuity & Disaster Recovery Policy]]; [[PLN-002 Business Continuity Plan]]; [[PROC-013 Manual Processing Procedure]]; [[RPT-002 Business Impact Analysis]] |
| R018 | Third-Party Technology Failure / Compromise | [[POL-008 Third-Party Security Policy]]; [[POL-009 Incident Response Policy]]; [[POL-010 Business Continuity & Disaster Recovery Policy]]; [[PBK-005 Third-Party Incident Playbook]]; [[PLN-002 Business Continuity Plan]] |
| R019 | Infinity Contractor Dependency / Compromise | [[POL-003 Access Control Policy]]; [[POL-008 Third-Party Security Policy]]; [[POL-012 Application & Secure Development Policy]]; [[STD-009 Infinity Security Standard]]; [[PROC-004 Contractor Access Procedure]]; [[PROC-020 Contractor Development Access Procedure]]; [[RPT-004 Infinity Transferability Review]] |
| R020 | Supplier Disruption | [[POL-008 Third-Party Security Policy]]; [[POL-010 Business Continuity & Disaster Recovery Policy]]; [[PLN-002 Business Continuity Plan]]; [[RPT-002 Business Impact Analysis]] |

---

## 4.3 Physical, Environmental, and Operational Risks

| Risk | Risk Description | Principal Governance and Control Artifacts |
|---|---|---|
| R021 | Fire | [[POL-010 Business Continuity & Disaster Recovery Policy]]; [[POL-011 Physical & Environmental Security Policy]]; [[PLN-002 Business Continuity Plan]]; [[PLN-003 Disaster Recovery Plan]]; [[PROC-012 Backup & Recovery Procedure]] |
| R022 | Water Damage | [[POL-010 Business Continuity & Disaster Recovery Policy]]; [[POL-011 Physical & Environmental Security Policy]]; [[PLN-002 Business Continuity Plan]]; [[PLN-003 Disaster Recovery Plan]]; [[PROC-012 Backup & Recovery Procedure]] |
| R023 | Utility / Power / HVAC Failure | [[POL-010 Business Continuity & Disaster Recovery Policy]]; [[POL-011 Physical & Environmental Security Policy]]; [[PLN-002 Business Continuity Plan]]; [[PLN-003 Disaster Recovery Plan]]; [[PROC-013 Manual Processing Procedure]] |
| R024 | Unauthorized Physical Access | [[POL-011 Physical & Environmental Security Policy]]; [[PRO-006 Physical & Personnel Security Program]]; [[PROC-014 Facility Access Procedure]]; [[PROC-015 Visitor & Vendor Access Procedure]]; [[PROC-016 Restricted Area Access Procedure]] |
| R025 | Vehicle Loss / Accident | [[POL-010 Business Continuity & Disaster Recovery Policy]]; [[PRO-006 Physical & Personnel Security Program]]; [[PLN-002 Business Continuity Plan]]; [[PROC-013 Manual Processing Procedure]] |
| R026 | Loss of Key Personnel | [[POL-010 Business Continuity & Disaster Recovery Policy]]; [[PRO-006 Physical & Personnel Security Program]]; [[PLN-002 Business Continuity Plan]]; [[PLN-003 Disaster Recovery Plan]]; [[PROC-017 Personnel Security Procedure]] |
| R027 | Backup / Recovery Failure | [[POL-010 Business Continuity & Disaster Recovery Policy]]; [[PLN-003 Disaster Recovery Plan]]; [[PROC-012 Backup & Recovery Procedure]]; [[TMP-003 Recovery Test Template]]; [[RPT-002 Business Impact Analysis]]; [[PLN-005 Annual Assurance Plan]] |
| R028 | Data Corruption | [[POL-007 Change & Configuration Management Policy]]; [[POL-010 Business Continuity & Disaster Recovery Policy]]; [[STD-006 Secure Configuration Standard]]; [[PROC-012 Backup & Recovery Procedure]]; [[PLN-003 Disaster Recovery Plan]] |

---

## 4.4 Fraud and Business-Process Risks

| Risk | Risk Description | Principal Governance and Control Artifacts |
|---|---|---|
| R029 | Vendor Fraud | [[POL-008 Third-Party Security Policy]]; [[POL-005 Risk Management Policy]]; [[PRO-008 Security Assurance & Continuous Improvement Program]]; [[REG-003 Enterprise Security Control Inventory]] |
| R030 | Sales Fraud | [[POL-003 Access Control Policy]]; [[POL-005 Risk Management Policy]]; [[PRO-003 Identity and Access Management Program]]; [[REG-003 Enterprise Security Control Inventory]] |
| R031 | Payroll Fraud | [[POL-003 Access Control Policy]]; [[POL-005 Risk Management Policy]]; [[PRO-003 Identity and Access Management Program]]; [[PROC-017 Personnel Security Procedure]]; [[REG-003 Enterprise Security Control Inventory]] |
| R032 | Inventory Theft | [[POL-003 Access Control Policy]]; [[POL-011 Physical & Environmental Security Policy]]; [[PRO-006 Physical & Personnel Security Program]]; [[PROC-014 Facility Access Procedure]]; [[PROC-016 Restricted Area Access Procedure]]; [[REG-003 Enterprise Security Control Inventory]] |
| R033 | Manual Outage Processing Error | [[POL-010 Business Continuity & Disaster Recovery Policy]]; [[PLN-002 Business Continuity Plan]]; [[PROC-013 Manual Processing Procedure]]; [[RPT-002 Business Impact Analysis]] |

---

## 4.5 Enterprise Continuity Risks

| Risk | Risk Description | Principal Governance and Control Artifacts |
|---|---|---|
| R034 | Loss of Corporate Headquarters | [[POL-010 Business Continuity & Disaster Recovery Policy]]; [[PLN-002 Business Continuity Plan]]; [[PLN-003 Disaster Recovery Plan]]; [[PROC-012 Backup & Recovery Procedure]]; [[PROC-013 Manual Processing Procedure]]; [[RPT-002 Business Impact Analysis]] |
| R035 | Regional Disaster | [[POL-010 Business Continuity & Disaster Recovery Policy]]; [[PLN-002 Business Continuity Plan]]; [[PLN-003 Disaster Recovery Plan]]; [[PROC-012 Backup & Recovery Procedure]]; [[PROC-013 Manual Processing Procedure]]; [[RPT-002 Business Impact Analysis]] |

---

# 5. Risk Treatment Traceability

Detailed treatment decisions for all 35 enterprise risks are maintained in [[RTP-001 Enterprise Risk Treatment Plan]].

For each risk, the Risk Treatment Plan identifies or establishes:

1. Risk identifier and description
2. Current residual risk
3. Treatment decision
4. Treatment objective
5. Required treatment activities
6. Responsible parties
7. Implementation priority
8. Dependencies
9. Expected evidence
10. Validation approach
11. Target residual risk
12. Conditions requiring reassessment

A target residual risk rating does not become the current residual risk merely because treatment has been approved or implemented.

Risk reduction must be supported by appropriate evidence and validation.

---

# 6. Policy-to-Program Relationships

| Policy | Principal Supporting Program, Plan, or Standard |
|---|---|
| [[POL-001 Information Security Policy]] | [[PRO-001 Enterprise Information Security & Risk Management Program]] |
| [[POL-002 Acceptable Use Policy]] | [[PRO-003 Identity and Access Management Program]]; [[PRO-005 Security Operations Program]] |
| [[POL-003 Access Control Policy]] | [[PRO-003 Identity and Access Management Program]]; [[STD-005 Authentication & Account Security Standard]] |
| [[POL-004 Information Classification & Handling Policy]] | [[STD-001 Information Classification Standard]] |
| [[POL-005 Risk Management Policy]] | [[RPT-003 Enterprise Risk Assessment]]; [[REG-002 Enterprise Risk Register]]; [[RTP-001 Enterprise Risk Treatment Plan]] |
| [[POL-006 Security Awareness & Training Policy]] | [[PRO-001 Enterprise Information Security & Risk Management Program]] |
| [[POL-007 Change & Configuration Management Policy]] | [[STD-006 Secure Configuration Standard]]; [[PROC-018 Secure Change & Release Procedure]] |
| [[POL-008 Third-Party Security Policy]] | [[RTP-001 Enterprise Risk Treatment Plan]]; [[PBK-005 Third-Party Incident Playbook]] |
| [[POL-009 Incident Response Policy]] | [[PLN-001 Incident Response Plan]]; [[STD-008 Incident Classification & Escalation Standard]] |
| [[POL-010 Business Continuity & Disaster Recovery Policy]] | [[PLN-002 Business Continuity Plan]]; [[PLN-003 Disaster Recovery Plan]] |
| [[POL-011 Physical & Environmental Security Policy]] | [[PRO-006 Physical & Personnel Security Program]] |
| [[POL-012 Application & Secure Development Policy]] | [[PRO-007 Secure Software Development Lifecycle Program]]; [[STD-009 Infinity Security Standard]] |

---

# 7. Procedure and Playbook Relationships

## Identity and Access Management

[[PRO-003 Identity and Access Management Program]] is supported by:

- [[PROC-001 Joiner-Mover-Leaver Procedure]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-003 Access Review Procedure]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]

## Vulnerability Management

[[PRO-004 Vulnerability Management Program]] is supported by:

- [[PROC-006 Vulnerability Assessment Procedure]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]
- [[STD-007 Penetration Testing Standard]]
- [[TMP-001 Assessment Work Plan Template]]

## Security Operations

[[PRO-005 Security Operations Program]] is supported by:

- [[PROC-008 Security Monitoring Procedure]]
- [[PROC-009 Malware Response Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[TMP-002 Operational Security Checklist]]

## Incident Response

[[PLN-001 Incident Response Plan]] is supported by:

- [[STD-008 Incident Classification & Escalation Standard]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PBK-001 Phishing & Credential Compromise Playbook]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-004 Data Exposure Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]

## Business Continuity and Disaster Recovery

[[POL-010 Business Continuity & Disaster Recovery Policy]] is supported by:

- [[RPT-002 Business Impact Analysis]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]
- [[PROC-013 Manual Processing Procedure]]
- [[TMP-003 Recovery Test Template]]

## Physical and Personnel Security

[[PRO-006 Physical & Personnel Security Program]] is supported by:

- [[PROC-014 Facility Access Procedure]]
- [[PROC-015 Visitor & Vendor Access Procedure]]
- [[PROC-016 Restricted Area Access Procedure]]
- [[PROC-017 Personnel Security Procedure]]

## Secure Development

[[PRO-007 Secure Software Development Lifecycle Program]] is supported by:

- [[STD-009 Infinity Security Standard]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-019 Application Security Assessment Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]
- [[RPT-004 Infinity Transferability Review]]

---

# 8. Assurance Traceability

Security requirements and controls are subject to assurance activities based on business importance, risk, control dependency, and potential consequences of control failure.

The primary assurance relationship is:

**Requirement → Control → Expected Evidence → Assessment Method → Assessment Result → Finding → Corrective Action → Retest → Control Effectiveness → Risk Reassessment**

[[REG-003 Enterprise Security Control Inventory]] identifies control-level evidence and assessment requirements.

[[PLN-005 Annual Assurance Plan]] prioritizes planned assurance activity.

[[TMP-001 Assessment Work Plan Template]] establishes the scope and method for individual assessments.

[[REG-004 Finding & Corrective Action Register]] tracks deficiencies through remediation and retesting.

---

# 9. Assessment Methods

The security program recognizes the following principal assessment methods:

| Method | Purpose |
|---|---|
| Inspection | Examine documentation, records, configurations, or other evidence. |
| Observation | Observe personnel, processes, physical conditions, or control operation. |
| Interview | Obtain information from personnel responsible for or affected by a control. |
| Sampling | Examine a representative selection of transactions, accounts, records, or events. |
| Technical Testing | Use technical methods to evaluate security configuration, exposure, behavior, or effectiveness. |
| Independent Performance | Perform a procedure independently to determine whether the expected result can be achieved. |
| Exercise | Simulate or execute a planned operational, incident-response, continuity, or recovery activity. |
| Reconciliation | Compare independent records or data sources to identify inconsistencies, omissions, or unauthorized activity. |

Assessment methods may be combined when appropriate.

---

# 10. Finding and Corrective Action Traceability

A finding should establish a clear relationship among:

**Requirement → Condition → Evidence → Risk/Impact → Corrective Action → Owner → Due Date → Retest → Closure**

Findings requiring remediation are maintained in [[REG-004 Finding & Corrective Action Register]].

A finding must not be closed solely because the responsible party reports that remediation has been completed.

Closure requires evidence appropriate to the nature and significance of the finding.

Where appropriate, remediation must be retested before closure.

Repeated or significant control failures may require reassessment of the associated enterprise risk.

---

# 11. Risk Reassessment

Risk reassessment should consider whether:

1. Planned treatment was actually implemented.
2. The implemented control operates as intended.
3. Required evidence exists.
4. Testing supports control effectiveness.
5. Identified deficiencies have been corrected.
6. Remediation has been appropriately retested.
7. The treatment materially changes likelihood, impact, or both.
8. New dependencies or risks have been introduced.
9. Existing assumptions remain valid.
10. The target residual risk remains a reasonable planning estimate.

Validated post-treatment risk may be higher than, equal to, or lower than the target residual risk.

The validated result becomes the basis for the new current residual risk while prior assessment results are preserved as historical risk records.

---

# 12. Reporting Traceability

Security information moves through the reporting structure according to audience and decision requirements.

## Operational

[[RPT-008 Operational Security Report & Dashboard]]

Focus:

- Technical execution
- Evidence
- Vulnerabilities
- Events
- Exceptions
- Remediation
- Retesting
- Deadlines

## Management

[[RPT-007 Management Security Report]]

Focus:

- Accountability
- Performance
- Trends
- Treatment progress
- Exceptions
- Findings
- Corrective action
- Required management action

## Executive

[[RPT-006 Executive Security Summary]]

Focus:

- Enterprise risk
- Business impact
- Significant trends
- Major treatment priorities
- Resource requirements
- Management decisions

The reporting relationship is:

**Technical Evidence → Operational Exception → Management Impact → Enterprise Risk → Executive Decision**

---

# 13. Cross-Reference Control Requirements

Controlled artifacts should use the following reference format when practical:

**Document ID + Full Artifact Title + Applicable Heading**

Example:

**PROC-012 Backup & Recovery Procedure, Restoration Testing**

Section numbers may be added after final document structure is stable.

Generic references such as "see the security policy," "see the recovery document," or "refer to the applicable procedure" should be avoided when a specific authoritative artifact can be identified.

---

# 14. Cross-Reference Validation

Cross-references must be reviewed for:

- Correct document ID
- Correct artifact title
- Existing authoritative destination
- Correct relationship to the source requirement
- Correct heading or section where applicable
- Duplicate or conflicting references
- Superseded artifacts
- Dead-end references
- References to controls that do not exist
- References that incorrectly imply implementation or effectiveness

Cross-reference validation is performed during scheduled document review and following material changes to the security program.

---

# 15. Proposed-Control Safeguard

A cross-reference from a risk to a policy, standard, procedure, plan, or proposed control does not demonstrate that the control is currently implemented or effective.

Planned controls receive no credit toward current residual risk until implementation and effectiveness are supported by appropriate evidence and validation.

The distinction among the following must be preserved:

**Documented → Approved → Implemented → Operating → Validated Effective**

---

# 16. Risk Boundary Safeguard

Cross-references must preserve the defined boundaries among enterprise risks.

Examples include:

- Malicious use of legitimately authorized insider access is principally addressed under **R012 Malicious Insider**, rather than being used to inflate unrelated unauthorized-access risks.
- Cloud-provider service outage is principally addressed under **R016 Cloud Service Outage**, while loss of a facility's primary wired Internet connection is addressed under **R017 Internet Service Provider Outage**.
- Regional events affecting multiple facilities or communications services are principally addressed under **R035 Regional Disaster**, rather than being counted as ordinary local utility or facility failures.
- Device loss does not automatically constitute information compromise when controls protect the information stored on the device.
- Backup-job success does not by itself demonstrate successful system recovery.

These boundaries support consistent risk scoring and reduce double counting.

---

# 17. Maintenance

This register should be updated when:

- A controlled artifact is created, retired, renamed, or superseded.
- A document identifier changes.
- A material cross-reference is added or removed.
- A risk treatment materially changes.
- A new control is introduced.
- An existing control is materially redesigned.
- Assessment identifies a missing traceability relationship.
- A finding changes the understanding of control effectiveness.
- Risk reassessment changes the relationship between a risk and its treatment.
- Repository restructuring changes authoritative artifact locations.

Minor editorial changes that do not alter artifact relationships do not require immediate register revision.

---

# 18. Related Artifacts

- [[INDEX-001 Artifact Index]]
- [[REG-006 Document Control Register]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[PLN-005 Annual Assurance Plan]]
- [[TMP-001 Assessment Work Plan Template]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]