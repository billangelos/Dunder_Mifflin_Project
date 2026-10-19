# REG-003 Enterprise Security Control Inventory

## Document Control

| Field | Value |
|---|---|
| Document ID | REG-003 |
| Title | Enterprise Security Control Inventory |
| Version | 1.0 |
| Classification | Confidential |
| Status | Active |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Quarterly and Following Material Control, Risk, or Security Program Change |

---

# 1. Purpose

This register provides the central inventory of material security controls used or planned by Dunder Mifflin.

It connects enterprise risks and security requirements to specific controls that can be:

- Assigned
- Implemented
- Evidenced
- Assessed
- Improved
- Retested
- Used in risk reassessment

---

# 2. Control Inventory Principle

A security control should answer:

1. What is the control?
2. Why does it exist?
3. What risk does it address?
4. Who is accountable for it?
5. What requirement governs it?
6. Is it currently implemented?
7. What evidence should it produce?
8. How can it be assessed?
9. Is it effective?

---

# 3. Traceability

This register supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

---

# 4. Control Identification

Controls in this register use the identifier:

**CTRL-[Domain]-[Number]**

Examples:

- CTRL-IAM-001
- CTRL-NET-001
- CTRL-BCDR-001

These identifiers identify controls rather than documents.

---

# 5. Control Domains

| Code | Domain |
|---|---|
| GOV | Governance and Risk |
| IAM | Identity and Access Management |
| NET | Network Security |
| END | Endpoint Security |
| SRV | Server and Infrastructure Security |
| VM | Vulnerability Management |
| OPS | Security Operations |
| IR | Incident Response |
| BCDR | Business Continuity and Disaster Recovery |
| PHY | Physical Security |
| PER | Personnel Security |
| TPRM | Third-Party Security |
| APP | Application and Secure Development |
| DATA | Information Protection |
| AWR | Security Awareness |
| FIN | Fraud and Transaction Controls |
| ASSUR | Security Assurance |

---

# 6. Implementation Status

Control implementation status is recorded as:

| Status | Meaning |
|---|---|
| Planned | Control has been identified but is not implemented. |
| Implementing | Implementation work is underway. |
| Implemented | Control has been placed into operation but has not necessarily been validated. |
| Validation Pending | Implementation is believed complete and formal validation remains outstanding. |
| Validated | Appropriate evidence supports that the control operates sufficiently to achieve its intended objective. |

---

# 7. Effectiveness Rating

Control effectiveness is recorded as:

| Rating | Meaning |
|---|---|
| Effective | Evidence supports that the control operates sufficiently to achieve its intended objective. |
| Partially Effective | The control provides meaningful protection but has material limitations. |
| Ineffective | The control exists but does not adequately achieve its intended objective. |
| Not Implemented | The required or planned control is not currently operating. |

**Not Yet Assessed is an assessment state, not an effectiveness rating.** When sufficient assessment evidence is unavailable for an implemented control, the Effectiveness field remains blank until an assessment supports one of the four authorized conclusions.

---

# 8. Status and Effectiveness Are Different

Implementation status and effectiveness must not be treated as the same measurement.

For example:

- A control may be **Implemented** while its effectiveness field remains blank because it has not yet been assessed.
- A control may be **Validated** and **Effective**.
- An existing control may be **Implemented** and **Partially Effective**.
- A planned control may be **Planned** and **Not Implemented**.

---

# 9. Historical Baseline

The inventory distinguishes controls already present in the assessed environment from planned security improvements.

A planned control receives no current residual-risk credit merely because it appears in this register.

---

# 10. Enterprise Control Inventory

## 10.1 Governance and Risk Controls

| Control ID | Control | Owner | Primary Risks | Governing Artifacts | Status | Effectiveness |
|---|---|---|---|---|---|---|
| CTRL-GOV-001 | Enterprise security governance structure and defined security accountability | CIO | Enterprise-wide | [[PRO-001 Enterprise Information Security & Risk Management Program]]; [[PRO-009 Security Governance Framework]] | Implemented | |
| CTRL-GOV-002 | Enterprise risk assessment and risk register | CIO | R001-R035 | [[POL-005 Risk Management Policy]]; [[RPT-003 Enterprise Risk Assessment]]; [[REG-002 Enterprise Risk Register]] | Implemented | |
| CTRL-GOV-003 | Risk treatment planning | CIO | R001-R035 | [[POL-005 Risk Management Policy]]; [[RTP-001 Enterprise Risk Treatment Plan]] | Implemented | |
| CTRL-GOV-004 | Formal risk acceptance and escalation authority | CEO | R001-R035 | [[POL-005 Risk Management Policy]]; [[PRO-009 Security Governance Framework]] | Implemented | |
| CTRL-GOV-005 | Information Security and Risk Committee oversight | CEO | Enterprise-wide | [[PRO-009 Security Governance Framework]] | Planned | Not Implemented |
| CTRL-GOV-006 | Enterprise policy framework | CIO | Enterprise-wide | [[POL-001 Information Security Policy]] | Implemented | |

### Expected Evidence

Governance evidence may include:

- Risk register
- Risk treatment records
- Risk acceptance records
- Policy approvals
- Management review records
- Committee records once the Information Security and Risk Committee (ISRC) is implemented

### Assessment Methods

- Inspection
- Interviews
- Sampling
- Management review

---

# 11. Identity and Access Management Controls

| Control ID | Control | Owner | Primary Risks | Governing Artifacts | Status | Effectiveness |
|---|---|---|---|---|---|---|
| CTRL-IAM-001 | Human Resources authoritative source for employee status | CFO | R010, R011, R012 | [[PRO-003 Identity and Access Management Program]]; [[PROC-001 Joiner-Mover-Leaver Procedure]] | Implemented | Partially Effective |
| CTRL-IAM-002 | Manager authorization based on business need | Business Manager | R010, R011 | [[POL-003 Access Control Policy]]; [[PROC-001 Joiner-Mover-Leaver Procedure]] | Implemented | Partially Effective |
| CTRL-IAM-003 | Least-privilege access | CIO | R005, R010, R012, R019 | [[POL-003 Access Control Policy]]; [[PRO-003 Identity and Access Management Program]] | Implemented | Partially Effective |
| CTRL-IAM-004 | Standard user accounts for ordinary users, including executives | CIO | R004, R005, R010, R013 | [[POL-003 Access Control Policy]]; [[STD-005 Authentication & Account Security Standard]] | Implemented | Effective |
| CTRL-IAM-005 | Separate privileged credentials for IT administrators | CIO | R005, R010, R012, R013 | [[POL-003 Access Control Policy]]; [[PROC-002 Privileged Access Procedure]] | Implemented | Partially Effective |
| CTRL-IAM-006 | Restricted standing Domain Administrator membership | CIO | R005, R010, R012, R013 | [[PROC-002 Privileged Access Procedure]] | Planned | Not Implemented |
| CTRL-IAM-007 | Dedicated administrative workstations | CIO | R005, R010, R012, R013 | [[PROC-002 Privileged Access Procedure]] | Planned | Not Implemented |
| CTRL-IAM-008 | Smart-card multifactor authentication where supported | CIO | R001, R002, R005, R006, R009, R010, R019 | [[POL-003 Access Control Policy]]; [[STD-005 Authentication & Account Security Standard]] | Planned | Not Implemented |
| CTRL-IAM-009 | Ordinary access review at least annually | CIO | R010, R011, R012 | [[PROC-003 Access Review Procedure]] | Planned | Not Implemented |
| CTRL-IAM-010 | Privileged access review at least quarterly | CIO | R005, R010, R012, R013, R019 | [[PROC-003 Access Review Procedure]] | Planned | Not Implemented |
| CTRL-IAM-011 | Transfer access revocation and reauthorization | CIO | R010, R011 | [[PROC-001 Joiner-Mover-Leaver Procedure]] | Planned | Not Implemented |
| CTRL-IAM-012 | Prompt termination of logical access | CIO | R011, R012 | [[PROC-001 Joiner-Mover-Leaver Procedure]] | Implemented | Partially Effective |
| CTRL-IAM-013 | Dormant account investigation at 30 days and disablement at 60 days | CIO | R005, R010, R011 | [[STD-005 Authentication & Account Security Standard]] | Planned | Not Implemented |
| CTRL-IAM-014 | Time-limited contractor access | CIO | R010, R011, R018, R019 | [[PROC-004 Contractor Access Procedure]] | Planned | Not Implemented |
| CTRL-IAM-015 | Controlled emergency access with dual custody | CIO | R005, R010, R012, R026 | [[PROC-005 Emergency Access Procedure]] | Planned | Not Implemented |
| CTRL-IAM-016 | Individual authentication for significant Warehouse Management System transactions | COO | R010, R015, R032 | [[POL-003 Access Control Policy]]; [[PRO-003 Identity and Access Management Program]] | Planned | Not Implemented |

### Expected Evidence

Identity and access evidence may include:

- Account lists
- Human Resources records
- Access requests
- Manager approvals
- Privileged account lists
- Access-review records
- Termination records
- Contractor-access records
- Authentication configuration
- Warehouse Management System transaction records

### Assessment Methods

- Inspection
- Sampling
- Technical Testing
- Independent Performance
- Reconciliation

---

# 12. Network Security Controls

| Control ID | Control | Owner | Primary Risks | Governing Artifacts | Status | Effectiveness |
|---|---|---|---|---|---|---|
| CTRL-NET-001 | Site firewall/router protection | CIO | R003, R004, R006, R007, R008 | [[STD-002 Network Security Standard]] | Implemented | Partially Effective |
| CTRL-NET-002 | Unsolicited inbound Internet traffic denied unless explicitly required | CIO | R004, R006, R007 | [[STD-002 Network Security Standard]] | Implemented | Effective |
| CTRL-NET-003 | Internal administrative services not intentionally exposed directly to the public Internet | CIO | R005, R006, R007, R010 | [[STD-002 Network Security Standard]] | Implemented | Effective |
| CTRL-NET-004 | Virtual Private Network protection for authorized access from untrusted networks to nonpublic cloud resources | CIO | R005, R007, R009, R010 | [[STD-002 Network Security Standard]] | Implemented | Partially Effective |
| CTRL-NET-005 | Network configuration backup | CIO | R007, R013, R017 | [[STD-002 Network Security Standard]] | Implemented | Partially Effective |
| CTRL-NET-006 | Network discovery and rogue wireless assessment every six months | CIO | R007, R024 | [[STD-002 Network Security Standard]]; [[PRO-005 Security Operations Program]] | Planned | Not Implemented |
| CTRL-NET-007 | Internet-only guest wireless at Scranton Headquarters lobby | CIO | R007, R024 | [[STD-002 Network Security Standard]] | Implemented | Effective |
| CTRL-NET-008 | No corporate wireless network | CIO | R007, R024 | [[STD-002 Network Security Standard]] | Implemented | Effective |
| CTRL-NET-009 | Company-issued cellular secondary connectivity where applicable | CIO | R017, R034, R035 | [[PLN-002 Business Continuity Plan]] | Implemented | Partially Effective |
| CTRL-NET-010 | Spare critical network equipment at Scranton Headquarters | CIO | R007, R017 | [[STD-002 Network Security Standard]] | Planned | Not Implemented |

### Expected Evidence

Network evidence may include:

- Firewall configuration
- Router configuration
- Network diagrams
- VPN configuration
- Network discovery results
- Wireless discovery results
- Configuration backups
- Equipment inventory

### Assessment Methods

- Inspection
- Technical Testing
- Configuration review
- Network discovery
- Sampling

---

# 13. Endpoint Security Controls

| Control ID | Control | Owner | Primary Risks | Governing Artifacts | Status | Effectiveness |
|---|---|---|---|---|---|---|
| CTRL-END-001 | Managed commercial antivirus | CIO | R003, R004 | [[STD-003 Endpoint Security Standard]] | Implemented | Partially Effective |
| CTRL-END-002 | Standard-user operation on ordinary endpoints | CIO | R003, R004, R005, R013 | [[STD-003 Endpoint Security Standard]] | Implemented | Effective |
| CTRL-END-003 | Full-disk encryption on company laptops | CIO | R009, R014 | [[STD-003 Endpoint Security Standard]] | Implemented | Effective |
| CTRL-END-004 | Automatic screen locking | CIO | R009, R010, R014 | [[STD-003 Endpoint Security Standard]] | Implemented | Effective |
| CTRL-END-005 | Central Windows endpoint management | CIO | R003, R004, R013, R014 | [[STD-003 Endpoint Security Standard]] | Implemented | Partially Effective |
| CTRL-END-006 | Central Windows patch management | CIO | R003, R004, R006, R007, R013 | [[STD-003 Endpoint Security Standard]]; [[STD-006 Secure Configuration Standard]] | Implemented | Partially Effective |
| CTRL-END-007 | Mobile device inventory and management | CIO | R009, R014 | [[STD-003 Endpoint Security Standard]] | Implemented | Partially Effective |
| CTRL-END-008 | Remote lock or wipe for supported mobile devices | CIO | R009, R014 | [[STD-003 Endpoint Security Standard]] | Implemented | Partially Effective |
| CTRL-END-010 | Formal hardened endpoint configuration baseline | CIO | R003, R004, R013 | [[STD-006 Secure Configuration Standard]] | Planned | Not Implemented |

### Expected Evidence

Endpoint evidence may include:

- Antivirus console reports
- Endpoint inventory
- Encryption status
- Patch reports
- Mobile device records
- Configuration records
- Security alerts

### Assessment Methods

- Inspection
- Sampling
- Technical Testing
- Configuration review

---

# 14. Server and Infrastructure Security Controls

| Control ID | Control | Owner | Primary Risks | Governing Artifacts | Status | Effectiveness |
|---|---|---|---|---|---|---|
| CTRL-SRV-001 | Windows Server 2012 administrative controls | CIO | R005, R007, R010, R013 | [[STD-004 Server Security Standard]] | Implemented | Partially Effective |
| CTRL-SRV-002 | At least two cloud-hosted Active Directory domain controllers | CIO | R005, R016, R026 | [[PRO-002 Enterprise Security Architecture Program]]; [[STD-004 Server Security Standard]] | Implemented | Partially Effective |
| CTRL-SRV-003 | Reasonable domain-controller failure-domain separation within the cloud provider | CIO | R016 | [[PRO-002 Enterprise Security Architecture Program]] | Implemented | Partially Effective |
| CTRL-SRV-004 | Server patch management | CIO | R003, R004, R006, R007, R013 | [[STD-004 Server Security Standard]]; [[STD-006 Secure Configuration Standard]] | Implemented | Partially Effective |
| CTRL-SRV-005 | Controlled server administrative access | CIO | R005, R010, R012, R013 | [[STD-004 Server Security Standard]]; [[PROC-002 Privileged Access Procedure]] | Implemented | Partially Effective |
| CTRL-SRV-006 | Formal secure server configuration baseline | CIO | R003, R004, R006, R013 | [[STD-006 Secure Configuration Standard]] | Planned | Not Implemented |

### Expected Evidence

Server evidence may include:

- Server inventory
- Active Directory configuration
- Administrative group membership
- Patch reports
- Configuration records
- Change records
- System logs

### Assessment Methods

- Inspection
- Technical Testing
- Configuration review
- Sampling

---

# 15. Vulnerability Management Controls

| Control ID | Control | Owner | Primary Risks | Governing Artifacts | Status | Effectiveness |
|---|---|---|---|---|---|---|
| CTRL-VM-001 | Monthly internal vulnerability scanning | IT & Information Security Manager | R003, R004, R006, R007, R013 | [[PRO-004 Vulnerability Management Program]]; [[PROC-006 Vulnerability Assessment Procedure]] | Planned | Not Implemented |
| CTRL-VM-002 | Risk-based vulnerability remediation targets | IT & Information Security Manager | R003, R004, R006, R007, R013 | [[PROC-007 Vulnerability Remediation & Retest Procedure]] | Planned | Not Implemented |
| CTRL-VM-003 | Critical vulnerability remediation target of 7 days | IT & Information Security Manager | R003, R004, R006, R007 | [[PROC-007 Vulnerability Remediation & Retest Procedure]] | Planned | Not Implemented |
| CTRL-VM-004 | High vulnerability remediation target of 30 days | IT & Information Security Manager | R003, R004, R006, R007 | [[PROC-007 Vulnerability Remediation & Retest Procedure]] | Planned | Not Implemented |
| CTRL-VM-005 | Moderate vulnerability remediation target of 45 days | IT & Information Security Manager | R003, R004, R006, R007 | [[PROC-007 Vulnerability Remediation & Retest Procedure]] | Planned | Not Implemented |
| CTRL-VM-006 | Low vulnerability remediation target of 60 days | IT & Information Security Manager | R003, R004, R006, R007 | [[PROC-007 Vulnerability Remediation & Retest Procedure]] | Planned | Not Implemented |
| CTRL-VM-007 | Vulnerability remediation validation and retesting | IT & Information Security Manager | R003, R004, R006, R007, R013 | [[PROC-007 Vulnerability Remediation & Retest Procedure]] | Planned | Not Implemented |
| CTRL-VM-008 | Enterprise penetration testing at least every two years | CIO | R003, R004, R005, R006, R007, R010 | [[STD-007 Penetration Testing Standard]] | Planned | Not Implemented |
| CTRL-VM-009 | Annual Infinity application penetration testing | CIO | R006, R019 | [[STD-007 Penetration Testing Standard]]; [[PROC-019 Application Security Assessment Procedure]] | Planned | Not Implemented |

### Expected Evidence

Vulnerability-management evidence may include:

- Scan reports
- Vulnerability records
- Remediation tickets
- Exception records
- Retest results
- Penetration-test reports
- Corrective-action records

### Assessment Methods

- Inspection
- Technical Testing
- Sampling
- Retesting
- Reconciliation

---

# 16. Security Operations Controls

| Control ID | Control | Owner | Primary Risks | Governing Artifacts | Status | Effectiveness |
|---|---|---|---|---|---|---|
| CTRL-OPS-001 | Central antivirus monitoring | IT & Information Security Manager | R003, R004 | [[PRO-005 Security Operations Program]]; [[PROC-008 Security Monitoring Procedure]] | Implemented | Partially Effective |
| CTRL-OPS-002 | Security event monitoring using available infrastructure and application logs | IT & Information Security Manager | R001, R003, R004, R005, R006, R009, R010 | [[PRO-005 Security Operations Program]]; [[PROC-008 Security Monitoring Procedure]] | Implemented | Partially Effective |
| CTRL-OPS-003 | Security event escalation process | IT & Information Security Manager | R001, R003, R004, R006, R009, R010, R012 | [[PROC-010 Security Event Escalation Procedure]] | Planned | Not Implemented |
| CTRL-OPS-004 | Documented malware response process | IT & Information Security Manager | R003, R004 | [[PROC-009 Malware Response Procedure]] | Planned | Not Implemented |
| CTRL-OPS-005 | Basic after-hours security response capability | IT & Information Security Manager | R001, R003, R004, R006, R009 | [[PRO-005 Security Operations Program]] | Planned | Not Implemented |
| CTRL-OPS-006 | Formal security evidence handling | IT & Information Security Manager | R003, R004, R006, R009, R012 | [[PROC-011 Evidence Handling Procedure]] | Planned | Not Implemented |
| CTRL-OPS-007 | Enhanced email filtering and anti-phishing controls for known malicious senders, suspicious links, malicious attachments, spoofed messages, and common phishing indicators | CIO | R001, R002 | [[PRO-005 Security Operations Program]]; [[RTP-001 Enterprise Risk Treatment Plan]] | Planned | Not Implemented |

### Expected Evidence

Security Operations evidence may include:

- Antivirus alerts
- Security logs
- Escalation records
- Malware investigation records
- On-call records
- Evidence records
- Security event records
- Email-filtering configuration and security-event records

### Assessment Methods

- Inspection
- Sampling
- Technical Testing
- Observation
- Exercises

---

# 17. Incident Response Controls

| Control ID | Control | Owner | Primary Risks | Governing Artifacts | Status | Effectiveness |
|---|---|---|---|---|---|---|
| CTRL-IR-001 | Formal Incident Response Plan | CIO | R001, R002, R003, R004, R006, R009, R012, R018 | [[POL-009 Incident Response Policy]]; [[PLN-001 Incident Response Plan]] | Planned | Not Implemented |
| CTRL-IR-002 | Virtual Incident Response Team | CIO | R001, R002, R003, R004, R006, R009, R012, R018 | [[PLN-001 Incident Response Plan]] | Planned | Not Implemented |
| CTRL-IR-003 | Incident classification and escalation standard | IT & Information Security Manager | Enterprise-wide | [[STD-008 Incident Classification & Escalation Standard]] | Planned | Not Implemented |
| CTRL-IR-004 | Phishing and credential-compromise response playbook | IT & Information Security Manager | R001, R002, R005 | [[PBK-001 Phishing & Credential Compromise Playbook]] | Planned | Not Implemented |
| CTRL-IR-005 | Malware and ransomware response playbook | IT & Information Security Manager | R003, R004 | [[PBK-002 Malware & Ransomware Playbook]] | Planned | Not Implemented |
| CTRL-IR-006 | Unauthorized-access response playbook | IT & Information Security Manager | R005, R009, R010, R012 | [[PBK-003 Unauthorized Access Playbook]] | Planned | Not Implemented |
| CTRL-IR-007 | Data-exposure response playbook | IT & Information Security Manager | R009, R012, R018 | [[PBK-004 Data Exposure Playbook]] | Planned | Not Implemented |
| CTRL-IR-008 | Third-party incident response playbook | IT & Information Security Manager | R018, R019 | [[PBK-005 Third-Party Incident Playbook]] | Planned | Not Implemented |
| CTRL-IR-009 | Retained Digital Forensics and Incident Response provider | CIO | R003, R004, R006, R009, R012, R018 | [[PLN-001 Incident Response Plan]] | Planned | Not Implemented |
| CTRL-IR-010 | Incident evidence integrity and SHA-256 hashing where practical | IT & Information Security Manager | R003, R004, R006, R009, R012 | [[PROC-011 Evidence Handling Procedure]] | Planned | Not Implemented |

### Expected Evidence

Incident Response evidence may include:

- Incident records
- Classification
- Timelines
- Evidence logs
- Playbook records
- Response actions
- Digital Forensics and Incident Response provider records
- Lessons learned
- Corrective actions

### Assessment Methods

- Inspection
- Sampling
- Exercises
- Interviews
- Evidence review

---

# 18. Business Continuity and Disaster Recovery Controls

| Control ID | Control | Owner | Primary Risks | Governing Artifacts | Status | Effectiveness |
|---|---|---|---|---|---|---|
| CTRL-BCDR-001 | Business Impact Analysis | CIO | R016, R017, R020-R028, R033-R035 | [[RPT-002 Business Impact Analysis]] | Implemented | |
| CTRL-BCDR-002 | Business Continuity Plan | COO | R016, R017, R020-R027, R033-R035 | [[PLN-002 Business Continuity Plan]] | Planned | Not Implemented |
| CTRL-BCDR-003 | Disaster Recovery Plan | CIO | R016, R017, R027, R028, R034, R035 | [[PLN-003 Disaster Recovery Plan]] | Planned | Not Implemented |
| CTRL-BCDR-004 | Cloud Exit and Emergency Migration Plan | CIO | R016, R018, R026, R034, R035 | [[PLN-004 Cloud Exit & Emergency Migration Plan]] | Implemented | |
| CTRL-BCDR-005 | Automated and cloud backup capability | CIO | R016, R027, R028, R034, R035 | [[PROC-012 Backup & Recovery Procedure]] | Implemented | Partially Effective |
| CTRL-BCDR-006 | Encrypted external-drive backup rotation | CIO | R027, R028, R034, R035 | [[PROC-012 Backup & Recovery Procedure]] | Implemented | Partially Effective |
| CTRL-BCDR-007 | Three encrypted external backup drives per facility, 21 total | CIO | R027, R028, R034, R035 | [[PROC-012 Backup & Recovery Procedure]] | Implemented | Partially Effective |
| CTRL-BCDR-008 | Off-site storage of two latest weekly generations per facility, normally 14 drives | CIO | R021, R022, R027, R028, R034, R035 | [[PROC-012 Backup & Recovery Procedure]] | Implemented | Partially Effective |
| CTRL-BCDR-009 | Quarterly representative restore testing | CIO | R027, R028 | [[PROC-012 Backup & Recovery Procedure]] | Planned | Not Implemented |
| CTRL-BCDR-010 | Annual meaningful recovery test for Critical capability | CIO | R016, R027, R028 | [[PLN-003 Disaster Recovery Plan]]; [[PROC-012 Backup & Recovery Procedure]] | Planned | Not Implemented |
| CTRL-BCDR-011 | Recovery documentation usable by a qualified unfamiliar IT professional | CIO | R026, R027, R034, R035 | [[PLN-003 Disaster Recovery Plan]] | Implemented | Partially Effective |
| CTRL-BCDR-012 | Standardized manual processing lifecycle | COO | R016, R017, R023, R033-R035 | [[PROC-013 Manual Processing Procedure]] | Planned | Not Implemented |
| CTRL-BCDR-013 | Manual processing reconciliation after restoration | COO | R028, R033 | [[PROC-013 Manual Processing Procedure]] | Planned | Not Implemented |
| CTRL-BCDR-014 | Cloud-hosted recovery documentation | CIO | R026, R027, R034, R035 | [[PLN-002 Business Continuity Plan]]; [[PLN-003 Disaster Recovery Plan]] | Planned | Not Implemented |
| CTRL-BCDR-015 | Two printed recovery-documentation binders | CIO | R026, R027, R034, R035 | [[PLN-002 Business Continuity Plan]]; [[PLN-003 Disaster Recovery Plan]] | Planned | Not Implemented |
| CTRL-BCDR-016 | Recovery-documentation review following significant technology or configuration change | CIO | R013, R026, R027 | [[PLN-003 Disaster Recovery Plan]] | Planned | Not Implemented |

### Expected Evidence

Business Continuity/Disaster Recovery evidence may include:

- Business Impact Analysis
- Backup reports
- Drive rotation records
- Off-site storage records
- Restore results
- Recovery-test records
- Recovery documentation
- Exercise records
- Manual processing records
- Reconciliation results

### Assessment Methods

- Inspection
- Sampling
- Exercises
- Technical Testing
- Independent Performance
- Reconciliation

---

# 19. Physical Security Controls

| Control ID | Control | Owner | Primary Risks | Governing Artifacts | Status | Effectiveness |
|---|---|---|---|---|---|---|
| CTRL-PHY-001 | Public, Controlled, and Restricted physical security zones | COO | R009, R024, R032 | [[POL-011 Physical & Environmental Security Policy]]; [[PRO-006 Physical & Personnel Security Program]] | Implemented | Partially Effective |
| CTRL-PHY-002 | Reception-controlled public entry | COO | R024 | [[PROC-014 Facility Access Procedure]] | Implemented | Effective |
| CTRL-PHY-003 | Employee card-controlled rear access | COO | R024 | [[PROC-014 Facility Access Procedure]] | Implemented | Effective |
| CTRL-PHY-004 | Visitor registration and escort controls | COO | R009, R024 | [[PROC-015 Visitor & Vendor Access Procedure]] | Implemented | Partially Effective |
| CTRL-PHY-005 | Restricted-area key and access controls | COO | R009, R024, R032 | [[PROC-016 Restricted Area Access Procedure]] | Implemented | Partially Effective |
| CTRL-PHY-006 | Locked high-value inventory cage at each warehouse | COO | R032 | [[PRO-006 Physical & Personnel Security Program]]; [[PROC-016 Restricted Area Access Procedure]] | Implemented | Effective |
| CTRL-PHY-007 | Restricted significant IT areas | CIO | R005, R009, R010, R024 | [[PROC-016 Restricted Area Access Procedure]] | Implemented | Partially Effective |
| CTRL-PHY-008 | Annual physical-access review | COO | R011, R012, R024, R032 | [[PROC-014 Facility Access Procedure]] | Planned | Not Implemented |
| CTRL-PHY-009 | Landlord common-area CCTV where provided | COO | R024, R032 | [[PRO-006 Physical & Personnel Security Program]] | Implemented | Partially Effective |
| CTRL-PHY-010 | UPS protection for critical network equipment and selected management and Sales workstations | CIO | R023 | [[PRO-006 Physical & Personnel Security Program]] | Implemented | Partially Effective |
| CTRL-PHY-011 | Fire and life-safety controls coordinated with landlords | COO | R021 | [[POL-011 Physical & Environmental Security Policy]] | Implemented | Partially Effective |
| CTRL-PHY-012 | Water and environmental hazard inspection and response | COO | R022, R023 | [[POL-011 Physical & Environmental Security Policy]] | Implemented | Partially Effective |

### Expected Evidence

Physical security evidence may include:

- Access records
- Visitor logs
- Key records
- Card records
- Restricted-area authorization
- Warehouse cage inspection
- Physical access reviews
- UPS inspection
- Landlord records
- Facility inspection

### Assessment Methods

- Inspection
- Observation
- Sampling
- Interviews
- Independent Performance

---

# 20. Personnel Security Controls

| Control ID | Control | Owner | Primary Risks | Governing Artifacts | Status | Effectiveness |
|---|---|---|---|---|---|---|
| CTRL-PER-001 | Human Resources personnel lifecycle coordination | CFO | R011, R012, R026 | [[PROC-017 Personnel Security Procedure]] | Implemented | Partially Effective |
| CTRL-PER-002 | Role-appropriate pre-employment or pre-engagement screening where lawful and justified | CFO | R012, R029-R032 | [[PROC-017 Personnel Security Procedure]] | Planned | Not Implemented |
| CTRL-PER-003 | Personnel confidentiality obligations | CFO | R009, R012 | [[PROC-017 Personnel Security Procedure]] | Implemented | Partially Effective |
| CTRL-PER-004 | Coordinated termination of logical and physical access | CFO | R011, R012 | [[PROC-001 Joiner-Mover-Leaver Procedure]]; [[PROC-017 Personnel Security Procedure]] | Planned | Not Implemented |
| CTRL-PER-005 | Recovery of company equipment, cards, keys, and authentication devices | CFO | R011, R014 | [[PROC-017 Personnel Security Procedure]] | Implemented | Partially Effective |
| CTRL-PER-006 | Identification of key-person dependencies | CEO | R026, R034, R035 | [[PROC-017 Personnel Security Procedure]] | Planned | Not Implemented |
| CTRL-PER-007 | Cross-training and alternate personnel for critical functions | CEO | R026, R034, R035 | [[PROC-017 Personnel Security Procedure]]; [[PLN-002 Business Continuity Plan]] | Planned | Not Implemented |
| CTRL-PER-008 | Company-controlled documentation sufficient to reduce exclusive personnel dependency | CIO | R019, R026, R027 | [[PROC-017 Personnel Security Procedure]] | Planned | Not Implemented |
| CTRL-PER-009 | Driver authorization and role-appropriate qualification requirements | COO | R025 | [[RTP-001 Enterprise Risk Treatment Plan]]; [[PRO-006 Physical & Personnel Security Program]] | Planned | Not Implemented |
| CTRL-PER-010 | Vehicle registration, insurance, inspection, maintenance, and incident-reporting requirements | COO | R025 | [[RTP-001 Enterprise Risk Treatment Plan]]; [[PRO-006 Physical & Personnel Security Program]] | Planned | Not Implemented |

### Expected Evidence

Personnel security evidence may include:

- Human Resources records
- Screening records where applicable
- Confidentiality records
- Joiner-Mover-Leaver records
- Termination checklists
- Equipment-return records
- Cross-training records
- Key-person dependency documentation
- Driver authorization and qualification records
- Vehicle registration, insurance, inspection, maintenance, and incident records

### Assessment Methods

- Inspection
- Sampling
- Interviews
- Reconciliation

---

# 21. Third-Party Security Controls

| Control ID | Control | Owner | Primary Risks | Governing Artifacts | Status | Effectiveness |
|---|---|---|---|---|---|---|
| CTRL-TPRM-001 | Critical, Important, and Routine third-party classification | CIO | R018, R019, R020 | [[POL-008 Third-Party Security Policy]] | Planned | Not Implemented |
| CTRL-TPRM-002 | Risk-based third-party security due diligence | CIO | R018, R019, R020, R029 | [[POL-008 Third-Party Security Policy]] | Planned | Not Implemented |
| CTRL-TPRM-003 | Security and confidentiality contractual requirements | Counsel / Compliance | R009, R018, R019 | [[POL-008 Third-Party Security Policy]] | Implemented | Partially Effective |
| CTRL-TPRM-004 | Security incident notification within 24 hours of discovery for applicable third parties | CIO | R018, R019 | [[POL-008 Third-Party Security Policy]] | Planned | Not Implemented |
| CTRL-TPRM-005 | Annual review of Critical third parties | CIO | R018, R019 | [[POL-008 Third-Party Security Policy]] | Planned | Not Implemented |
| CTRL-TPRM-006 | Biennial review of Important third parties | CIO | R018 | [[POL-008 Third-Party Security Policy]] | Planned | Not Implemented |
| CTRL-TPRM-007 | Third-party access limitation and termination | CIO | R010, R011, R018, R019 | [[PROC-004 Contractor Access Procedure]] | Planned | Not Implemented |
| CTRL-TPRM-008 | Third-party continuity and exit planning | CIO | R016, R018, R019, R020 | [[POL-008 Third-Party Security Policy]] | Planned | Not Implemented |
| CTRL-TPRM-009 | Enterprise NDA or equivalent confidentiality requirement before outside sensitive access | Counsel / Compliance | R009, R012, R018, R019 | [[POL-008 Third-Party Security Policy]] | Implemented | Effective |
| CTRL-TPRM-010 | Alternate suppliers and sourcing alternatives maintained where practical for important operational dependencies | COO | R020, R035 | [[RTP-001 Enterprise Risk Treatment Plan]]; [[PLN-002 Business Continuity Plan]] | Planned | Not Implemented |
| CTRL-TPRM-011 | Supplier disruption monitoring, inventory coordination, and sourcing review | COO | R020 | [[RTP-001 Enterprise Risk Treatment Plan]]; [[PLN-002 Business Continuity Plan]] | Planned | Not Implemented |

### Expected Evidence

Third-party evidence may include:

- Third-party inventory
- Classification
- Due diligence
- Contracts
- NDAs
- Incident clauses
- Assessment records
- Access records
- Exit plans
- Corrective actions
- Supplier continuity and alternate-sourcing records
- Supplier disruption and inventory-coordination records

### Assessment Methods

- Inspection
- Sampling
- Interviews
- Contract review

---

# 22. Application and Secure Development Controls

| Control ID | Control | Owner | Primary Risks | Governing Artifacts | Status | Effectiveness |
|---|---|---|---|---|---|---|
| CTRL-APP-001 | Dunder Mifflin ownership and control of Infinity source code, intellectual property, data, documentation, and contractual work product | CIO | R006, R019, R026 | [[POL-012 Application & Secure Development Policy]]; [[STD-009 Infinity Security Standard]] | Implemented | Effective |
| CTRL-APP-002 | Dunder Mifflin-controlled authoritative source-code repository | CIO | R006, R019, R026 | [[STD-009 Infinity Security Standard]]; [[PROC-020 Contractor Development Access Procedure]] | Implemented | Partially Effective |
| CTRL-APP-003 | Development, test, and production separation | CIO | R006, R013, R019 | [[STD-009 Infinity Security Standard]] | Planned | Not Implemented |
| CTRL-APP-004 | Logical Infinity web, application, and database tier separation | CIO | R006 | [[PRO-002 Enterprise Security Architecture Program]]; [[STD-009 Infinity Security Standard]] | Implemented | Partially Effective |
| CTRL-APP-005 | Infinity database not directly exposed to the public Internet | CIO | R006, R009 | [[STD-009 Infinity Security Standard]] | Implemented | Effective |
| CTRL-APP-006 | Threat modeling for material security-sensitive changes | CIO | R006, R013 | [[PRO-007 Secure Software Development Lifecycle Program]] | Planned | Not Implemented |
| CTRL-APP-007 | Security-focused code review | CIO | R006, R013 | [[PRO-007 Secure Software Development Lifecycle Program]] | Planned | Not Implemented |
| CTRL-APP-008 | Security testing before material production release | CIO | R006, R013 | [[PROC-018 Secure Change & Release Procedure]] | Planned | Not Implemented |
| CTRL-APP-009 | Controlled production change and release process | CIO | R006, R013, R019 | [[PROC-018 Secure Change & Release Procedure]] | Planned | Not Implemented |
| CTRL-APP-010 | Annual Infinity security assessment | CIO | R006, R019 | [[PROC-019 Application Security Assessment Procedure]] | Planned | Not Implemented |
| CTRL-APP-011 | Annual Infinity penetration test | CIO | R006, R019 | [[STD-007 Penetration Testing Standard]] | Planned | Not Implemented |
| CTRL-APP-012 | Sponsored, individually attributable, time-limited contractor development access | CIO | R010, R011, R019 | [[PROC-020 Contractor Development Access Procedure]] | Planned | Not Implemented |
| CTRL-APP-013 | Privileged contractor production administration from controlled Scranton Headquarters workspace | CIO | R006, R010, R012, R019 | [[PROC-020 Contractor Development Access Procedure]] | Planned | Not Implemented |
| CTRL-APP-014 | No general contractor VPN for routine privileged production administration | CIO | R006, R010, R019 | [[PROC-020 Contractor Development Access Procedure]] | Planned | Not Implemented |
| CTRL-APP-015 | Annual Infinity transferability review | CIO | R019, R026 | [[RPT-004 Infinity Transferability Review]] | Planned | Not Implemented |
| CTRL-APP-016 | Infinity recovery documentation independent of exclusive contractor knowledge | CIO | R019, R026, R027 | [[STD-009 Infinity Security Standard]]; [[PLN-003 Disaster Recovery Plan]] | Planned | Not Implemented |

### Expected Evidence

Application security evidence may include:

- Repository records
- Source-code history
- Architecture documentation
- Environment configuration
- Threat models
- Code-review records
- Security-test results
- Change records
- Penetration-test results
- Contractor-access records
- Transferability review
- Recovery documentation

### Assessment Methods

- Inspection
- Technical Testing
- Sampling
- Penetration Testing
- Independent Performance
- Application Security Assessment

---

# 23. Information Protection Controls

| Control ID | Control | Owner | Primary Risks | Governing Artifacts | Status | Effectiveness |
|---|---|---|---|---|---|---|
| CTRL-DATA-001 | Public, Internal, Confidential, and Restricted information classification | CIO | R009, R010, R012 | [[POL-004 Information Classification & Handling Policy]]; [[STD-001 Information Classification Standard]] | Implemented | |
| CTRL-DATA-002 | Handling requirements based on classification | CIO | R009, R010, R012 | [[STD-001 Information Classification Standard]] | Implemented | Partially Effective |
| CTRL-DATA-003 | Backup information inherits the highest applicable source classification | CIO | R009, R027 | [[STD-001 Information Classification Standard]] | Implemented | Partially Effective |
| CTRL-DATA-004 | Full payment card number not intentionally retained by Dunder Mifflin | CFO | R009 | [[STD-001 Information Classification Standard]]; [[STD-009 Infinity Security Standard]] | Implemented | Effective |
| CTRL-DATA-005 | Payment processor token retained as Confidential information | CFO | R009 | [[STD-001 Information Classification Standard]] | Implemented | Effective |
| CTRL-DATA-006 | Encryption of sensitive company laptop information through full-disk encryption | CIO | R009, R014 | [[STD-003 Endpoint Security Standard]] | Implemented | Effective |
| CTRL-DATA-007 | Secure destruction and shredding of sensitive paper records | Business Owners | R009, R012 | [[POL-004 Information Classification & Handling Policy]] | Implemented | Partially Effective |

### Expected Evidence

Information-protection evidence may include:

- Classification records
- Handling procedures
- Encryption status
- Payment architecture
- Backup configuration
- Destruction records
- Physical inspection

### Assessment Methods

- Inspection
- Sampling
- Technical Testing
- Observation

---

# 24. Security Awareness Controls

| Control ID | Control | Owner | Primary Risks | Governing Artifacts | Status | Effectiveness |
|---|---|---|---|---|---|---|
| CTRL-AWR-001 | Initial security awareness training within 5 business days | IT & Information Security Manager | R001, R002, R003, R004, R009, R012 | [[POL-006 Security Awareness & Training Policy]] | Planned | Not Implemented |
| CTRL-AWR-002 | Annual security awareness refresher | IT & Information Security Manager | R001, R002, R003, R004, R009, R012 | [[POL-006 Security Awareness & Training Policy]] | Planned | Not Implemented |
| CTRL-AWR-003 | Annual awareness assessment with 80% passing score | IT & Information Security Manager | R001, R002, R003, R004, R009 | [[POL-006 Security Awareness & Training Policy]] | Planned | Not Implemented |
| CTRL-AWR-004 | Monthly phishing simulations | IT & Information Security Manager | R001, R002 | [[POL-006 Security Awareness & Training Policy]] | Planned | Not Implemented |
| CTRL-AWR-005 | Security-event reporting awareness | IT & Information Security Manager | R001, R002, R003, R004, R009, R012 | [[POL-006 Security Awareness & Training Policy]]; [[PROC-010 Security Event Escalation Procedure]] | Planned | Not Implemented |

### Expected Evidence

Awareness evidence may include:

- Training records
- Completion records
- Quiz results
- Phishing simulation results
- Corrective training
- Awareness communications

### Assessment Methods

- Inspection
- Sampling
- Interviews
- Metrics review

---

# 25. Fraud and Transaction Controls

| Control ID | Control | Owner | Primary Risks | Governing Artifacts | Status | Effectiveness |
|---|---|---|---|---|---|---|
| CTRL-FIN-001 | Separation of Duties for vendor setup, purchasing, invoice approval, and payment where practical | CFO | R029 | [[POL-003 Access Control Policy]]; [[RTP-001 Enterprise Risk Treatment Plan]] | Implemented | Partially Effective |
| CTRL-FIN-002 | Independent verification of suspicious or significant vendor payment-detail changes using a trusted contact method | CFO | R029 | [[RTP-001 Enterprise Risk Treatment Plan]] | Planned | Not Implemented |
| CTRL-FIN-003 | Restricted vendor-master and payment access | CFO | R029 | [[POL-003 Access Control Policy]] | Implemented | Partially Effective |
| CTRL-FIN-004 | Sales transaction attribution and approval of significant pricing, discount, credit, and refund activity | COO | R030 | [[RTP-001 Enterprise Risk Treatment Plan]] | Implemented | Partially Effective |
| CTRL-FIN-005 | Reconciliation among order, fulfillment, invoice, credit, and payment records | CFO | R030 | [[RTP-001 Enterprise Risk Treatment Plan]] | Implemented | Partially Effective |
| CTRL-FIN-006 | Separation of Duties among employee records, payroll preparation, approval, and payment where practical | CFO | R031 | [[RTP-001 Enterprise Risk Treatment Plan]] | Implemented | Partially Effective |
| CTRL-FIN-007 | Independent verification of suspicious payroll banking changes using a trusted contact method | CFO | R031 | [[RTP-001 Enterprise Risk Treatment Plan]] | Planned | Not Implemented |
| CTRL-FIN-008 | Payroll reconciliation against active employees and approved compensation | CFO | R031 | [[RTP-001 Enterprise Risk Treatment Plan]] | Implemented | Partially Effective |
| CTRL-FIN-009 | Inventory counts and reconciliation | COO | R032 | [[RTP-001 Enterprise Risk Treatment Plan]] | Implemented | Partially Effective |
| CTRL-FIN-010 | Receiving, shipping, and transaction records sufficient to reconcile inventory movement | COO | R032 | [[RTP-001 Enterprise Risk Treatment Plan]] | Implemented | Partially Effective |
| CTRL-FIN-011 | Individual accountability for significant Warehouse Management System transactions | COO | R015, R032 | [[POL-003 Access Control Policy]]; [[RTP-001 Enterprise Risk Treatment Plan]] | Planned | Not Implemented |

### Expected Evidence

Fraud-control evidence may include:

- Vendor records
- Purchase records
- Invoice approvals
- Payment records
- Verification records
- Sales records
- Refund and credit records
- Payroll records
- Inventory counts
- Receiving records
- Shipping records
- Warehouse Management System records

### Assessment Methods

- Sampling
- Inspection
- Reconciliation
- Access review
- Independent Performance

---

# 26. Security Assurance Controls

| Control ID | Control | Owner | Primary Risks | Governing Artifacts | Status | Effectiveness |
|---|---|---|---|---|---|---|
| CTRL-ASSUR-001 | Enterprise Security Control Inventory | CIO | R001-R035 | [[PRO-008 Security Assurance & Continuous Improvement Program]] | Implemented | |
| CTRL-ASSUR-002 | Annual Assurance Plan | CIO | R001-R035 | [[PLN-005 Annual Assurance Plan]] | Planned | Not Implemented |
| CTRL-ASSUR-003 | Risk-based Assessment Work Plans | CIO | R001-R035 | [[TMP-001 Assessment Work Plan Template]] | Planned | Not Implemented |
| CTRL-ASSUR-004 | Finding and Corrective Action Register | CIO | R001-R035 | [[REG-004 Finding & Corrective Action Register]] | Planned | Not Implemented |
| CTRL-ASSUR-005 | Corrective-action validation and retesting | CIO | R001-R035 | [[PRO-008 Security Assurance & Continuous Improvement Program]] | Planned | Not Implemented |
| CTRL-ASSUR-006 | Security Metrics Catalog | CIO | R001-R035 | [[REG-005 Security Metrics Catalog]] | Planned | Not Implemented |
| CTRL-ASSUR-007 | Executive, management, and operational security reporting | CIO | R001-R035 | [[PRO-008 Security Assurance & Continuous Improvement Program]] | Planned | Not Implemented |
| CTRL-ASSUR-008 | Biennial independent enterprise control assessment | CIO | R001-R035 | [[PRO-008 Security Assurance & Continuous Improvement Program]] | Planned | Not Implemented |
| CTRL-ASSUR-009 | Risk reassessment following validated material control change | CIO | R001-R035 | [[POL-005 Risk Management Policy]]; [[PRO-008 Security Assurance & Continuous Improvement Program]] | Planned | Not Implemented |
| CTRL-ASSUR-010 | Evidence-integrity requirements for assurance activity | CIO | R001-R035 | [[PRO-008 Security Assurance & Continuous Improvement Program]] | Implemented | |

### Expected Evidence

Assurance evidence may include:

- Control inventory
- Annual Assurance Plan
- Assessment Work Plans
- Assessment results
- Findings
- Corrective actions
- Retest results
- Metrics
- Risk reassessments
- Security reports

### Assessment Methods

- Inspection
- Sampling
- Independent Performance
- Technical Testing
- Exercises
- Reconciliation

---

# 27. Control-to-Risk Summary

The following table provides a high-level view of the principal control domains supporting each enterprise risk.

| Risk | Primary Control Domains |
|---|---|
| R001 Phishing / Credential Compromise | IAM, OPS, IR, AWR |
| R002 Business Email Compromise | IAM, OPS, IR, AWR, FIN |
| R003 Ransomware | END, VM, OPS, IR, BCDR |
| R004 Malware | END, VM, OPS, IR, AWR |
| R005 Password / Authentication Weakness | IAM, NET, SRV, ASSUR |
| R006 Infinity Compromise | NET, VM, APP, IR, TPRM |
| R007 Internet Infrastructure Compromise | NET, VM, SRV, OPS |
| R008 Denial of Service | NET, IR, BCDR |
| R009 Sensitive Information Theft / Extortion | IAM, END, DATA, IR, PHY |
| R010 Unauthorized / Excessive Access | IAM, PHY, APP, ASSUR |
| R011 Delayed Termination | IAM, PER, PHY, TPRM |
| R012 Malicious Insider | IAM, PER, PHY, DATA, FIN |
| R013 Administrative / Configuration Error | IAM, END, SRV, APP, GOV |
| R014 Lost or Stolen Device | END, DATA, PER |
| R015 Shared Warehouse Accounts | IAM, FIN |
| R016 Cloud Outage | BCDR, TPRM, SRV |
| R017 ISP Outage | NET, BCDR |
| R018 Third-Party Technology Failure / Compromise | TPRM, IR, APP, BCDR |
| R019 Infinity Contractor | TPRM, APP, IAM, PER |
| R020 Supplier Disruption | TPRM, BCDR, GOV |
| R021 Fire | PHY, BCDR |
| R022 Water | PHY, BCDR |
| R023 Utility / Power / HVAC Failure | PHY, BCDR |
| R024 Physical Access | PHY, PER, IAM |
| R025 Vehicle Risk | PER, BCDR |
| R026 Personnel Loss | PER, BCDR, APP |
| R027 Backup Failure | BCDR, ASSUR |
| R028 Data Corruption | BCDR, APP, FIN |
| R029 Vendor Fraud | FIN, IAM, TPRM |
| R030 Sales Fraud | FIN, IAM |
| R031 Payroll Fraud | FIN, IAM, PER |
| R032 Inventory Theft | PHY, FIN, IAM |
| R033 Manual Outage Error | BCDR, FIN |
| R034 Loss of Headquarters | BCDR, PER, NET |
| R035 Regional Disaster | BCDR, PER, TPRM |

---

# 28. Critical Controls

Controls may be designated Critical when failure could materially affect:

- High or Critical enterprise risk
- Critical business processes
- Restricted or significant Confidential information
- Privileged access
- Recovery capability
- Material fraud prevention
- Significant third-party dependency

---

# 29. Initial Critical Control Candidates

The following controls receive elevated assurance consideration:

| Control ID | Control | Reason |
|---|---|---|
| CTRL-IAM-003 | Least-privilege access | Broad access-risk dependency |
| CTRL-IAM-005 | Separate privileged credentials | Administrative compromise impact |
| CTRL-IAM-012 | Prompt termination of logical access | Former-user exposure |
| CTRL-NET-001 | Site firewall/router protection | Internet boundary protection |
| CTRL-NET-002 | Unsolicited inbound traffic denied | Internet exposure control |
| CTRL-END-001 | Managed commercial antivirus | Primary malware protection |
| CTRL-END-003 | Full-disk encryption | Mobile information protection |
| CTRL-SRV-002 | Multiple Active Directory domain controllers | Enterprise authentication dependency |
| CTRL-BCDR-005 | Automated and cloud backup capability | Recovery dependency |
| CTRL-BCDR-006 | Encrypted external-drive backup rotation | Independent recovery copy |
| CTRL-BCDR-008 | Off-site backup storage | Facility-loss resilience |
| CTRL-PHY-006 | Locked high-value inventory cages | Material inventory-theft control |
| CTRL-TPRM-009 | Outside-party confidentiality requirement | Sensitive third-party exposure |
| CTRL-APP-001 | Dunder Mifflin ownership of Infinity source and work product | Application continuity and contractor dependency |
| CTRL-APP-005 | Infinity database not publicly exposed | Application and information protection |
| CTRL-DATA-004 | No intentional storage of full payment card numbers | Payment-data exposure reduction |

---

# 30. Critical Control Designation Is Not an Effectiveness Rating

A control may be Critical and still be:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

A Critical control may also be awaiting assessment. In that case, no effectiveness conclusion is assigned until sufficient evidence is available.

Criticality describes the importance of the control.

Effectiveness describes how well it operates.

---

# 31. Assurance Priority

Assurance priority must consider both:

- Inherent risk
- Current residual risk

A control supporting a risk with lower current residual exposure may still require substantial assurance when failure of that control could restore a severe inherent-risk condition.

---

# 32. Inherent Risk Still Matters

A reduced residual-risk score may depend heavily on one or more controls continuing to operate.

The underlying inherent risk remains relevant when deciding how much assurance those controls require.

---

# 33. Control Dependencies

Controls must not be assessed in isolation when effectiveness depends on another control.

---

# 34. Dependency Example: Authentication

Smart-card multifactor authentication may depend on:

- Identity proofing
- Credential issuance
- PIN or secret protection
- Account lifecycle
- Termination
- Access review
- Authentication logging

Failure of a supporting process may reduce the effectiveness of the overall authentication control.

---

# 35. Dependency Example: Backup

Backup effectiveness may depend on:

- Correct system coverage
- Successful backup jobs
- Encryption
- Off-site separation
- Retention
- Credential protection
- Recovery documentation
- Restore capability
- Recovery testing

A successful backup job alone does not establish recoverability.

---

# 36. Dependency Example: Infinity

Infinity security depends on multiple controls including:

- Network exposure
- Authentication
- Authorization
- Secure development
- Change control
- Vulnerability management
- Contractor access
- Source-code control
- Backup
- Recovery
- Incident response

---

# 37. Control Evidence

Each control must produce or be capable of producing evidence appropriate to its purpose.

---

# 38. Evidence Does Not Need to Be a Report

Valid evidence may exist as:

- Configuration
- Logs
- Records
- Transactions
- Approvals
- Physical conditions
- Test results
- System behavior

---

# 39. Evidence Integrity

Control evidence must reflect actual conditions.

Personnel must not:

- Fabricate evidence.
- Backdate approvals.
- Invent test results.
- Record unperformed control activity as complete.
- Alter logs to support a desired conclusion.
- Conceal material control failure.

---

# 40. Control Assessment

Controls may be assessed through:

- Inspection
- Observation
- Interviews
- Sampling
- Independent Performance
- Technical Testing
- Exercises
- Reconciliation

---

# 41. Assessment Work Plan

Material control assessments should use [[TMP-001 Assessment Work Plan Template]].

---

# 42. Assessment Planning

Assessment planning should identify:

- Objective
- Scope
- Requirement
- Control
- Evidence
- Method
- Sample
- Assessor
- Expected result

before material testing begins.

---

# 43. Control Test Result

A control test should produce a supportable conclusion concerning whether the control:

- Operated as expected
- Operated partially
- Failed
- Was not implemented
- Could not be adequately assessed

---

# 44. Finding

A finding is a documented conclusion supported by evidence concerning whether a requirement, control, process, or expected outcome was satisfied.

---

# 45. Deficiency Findings

Material deficiency findings must be recorded in [[REG-004 Finding & Corrective Action Register]].

---

# 46. Finding Traceability

A finding should be traceable to:

- Requirement
- Control
- Evidence
- Related risk
- Corrective action
- Retest

where applicable.

---

# 47. Corrective Action

Corrective action must address the underlying control weakness.

---

# 48. Validation Pending

A control corrected following a finding may remain in Validation Pending status until appropriate evidence demonstrates that the correction works.

---

# 49. Retesting

Material control deficiencies must be retested where appropriate before effectiveness is considered restored.

---

# 50. Failed Retest

A failed retest means:

- The control remains deficient, or
- Corrective action requires revision.

The finding remains open unless another authorized disposition applies.

---

# 51. Successful Retest

A successful retest may support:

- Finding closure
- Updated control effectiveness
- Risk reassessment

when other required corrective actions are complete.

---

# 52. Control Effectiveness and Risk

Control effectiveness informs residual-risk analysis.

It does not mechanically determine the risk score.

---

# 53. No Automatic Risk Reduction

A control's movement from:

**Planned → Implemented**

does not automatically justify reducing current residual risk.

---

# 54. Validated Control Change

A material control improvement should normally progress through:

**Planned → Approved → Implementing → Implemented → Validation Pending → Validated**

before expected risk reduction is treated as demonstrated.

---

# 55. Target Residual Risk

Target residual risk remains a prediction until treatment has been implemented and validated.

---

# 56. Post-Treatment Reassessment

After material controls are validated, the risk owner and appropriate security personnel must reassess the applicable risk.

---

# 57. Reassessment Outcome

Validated post-treatment risk may be:

- Higher than target
- Equal to target
- Lower than target

---

# 58. Historical Integrity

Later control validation must not rewrite the historical May 2013 assessment.

Historical:

- Inherent risk
- Current residual risk
- Control conditions
- Assessment evidence

must remain available for comparison.

---

# 59. Current Control Versus Proposed Control

This register must preserve the distinction between:

**Controls already operating in the assessed environment**

and

**Controls proposed through the security program**

---

# 60. Proposed Control Limitation

The existence of a proposed control in:

- This register
- A policy
- A standard
- A procedure
- The Risk Treatment Plan
- The program roadmap

does not establish implementation.

---

# 61. Assurance Plan Relationship

[[PLN-005 Annual Assurance Plan]] determines which controls receive scheduled assurance attention during the year.

---

# 62. Assurance Planning Inputs

Control assessment priority should consider:

- Inherent risk
- Current residual risk
- Control criticality
- Business Impact Analysis
- Prior findings
- Security incidents
- Vulnerability results
- Major changes
- Third-party dependencies
- Management concerns

---

# 63. Continuous Monitoring

Controls may also receive ongoing awareness between formal assessments.

---

# 64. Continuous Monitoring Principle

Continuous monitoring means risk-appropriate ongoing awareness.

It does not require:

- Constant testing of every control
- Continuous employee surveillance
- Continuous manual log review
- A 24-hour Security Operations Center

---

# 65. Continuous Monitoring Sources

Sources may include:

- Security alerts
- Vulnerability reports
- Backup results
- Access reviews
- Change records
- Incident records
- Metrics
- Findings
- Exception reports
- Third-party notifications

---

# 66. Metrics

Control-level metrics are defined in [[REG-005 Security Metrics Catalog]].

---

# 67. Control Metrics

Control metrics may measure:

- Execution
- Coverage
- Timeliness
- Exceptions
- Failures
- Remediation
- Retesting
- Effectiveness

---

# 68. Metrics Do Not Establish Effectiveness Alone

A favorable metric does not automatically prove that a control is effective.

Assessment must consider the control objective and supporting evidence.

---

# 69. Control Exceptions

Material exceptions must be:

- Documented
- Justified
- Risk evaluated
- Approved
- Time-limited where practical
- Reviewed

---

# 70. Exception Expiration

An expired exception does not become permanent authorization.

---

# 71. Exception and Effectiveness

An approved exception may affect control-effectiveness conclusions even when the exception is properly authorized.

---

# 72. Control Changes

Material changes to a security control must be reflected in this inventory.

---

# 73. Change Examples

Material control changes may include:

- New control
- Control retirement
- Owner change
- Major design change
- Implementation
- Validation
- Significant failure
- Effectiveness change

---

# 74. Control Retirement

A control must not be removed from the inventory solely because it is no longer operating.

Retired controls should retain sufficient historical information to preserve traceability where material.

---

# 75. Control Duplication

Multiple documents may support the same control.

This does not require creation of duplicate control records unless materially different control objectives exist.

---

# 76. Policy Does Not Equal Control

A policy establishes management requirements.

The operational or technical mechanism satisfying the requirement is the control.

---

# 77. Procedure Does Not Equal Control

A procedure explains how an activity should be performed.

Actual performance of the activity establishes control operation.

---

# 78. Technology Does Not Equal Control Effectiveness

Technology may provide a control mechanism.

The presence of technology does not by itself prove:

- Correct configuration
- Correct coverage
- Proper operation
- Appropriate monitoring
- Effective risk reduction

---

# 79. Control Layering

Multiple controls may work together to reduce one risk.

Examples include:

- Preventive controls
- Detective controls
- Corrective controls
- Recovery controls
- Administrative controls
- Technical controls
- Physical controls

---

# 80. Defense in Depth

No single control should be assumed to prevent every relevant security event.

Layered controls are used where justified by risk.

---

# 81. Compensating Controls

A compensating control may be used when a preferred control is:

- Technically unavailable
- Operationally impractical
- Disproportionately expensive
- Temporarily unavailable

provided the resulting risk remains appropriately managed.

---

# 82. Compensating Control Documentation

A material compensating control should identify:

- Requirement not met
- Reason
- Compensating mechanism
- Remaining risk
- Owner
- Approval
- Review requirement

---

# 83. Control Failure

A control failure must be evaluated according to:

- Control importance
- Related risk
- Business impact
- Duration
- Existing compensating controls
- Need for immediate action

---

# 84. Immediate Control Failure

A control failure creating immediate material security risk must be escalated without waiting for a scheduled assessment or reporting cycle.

---

# 85. Incident Relationship

Evidence suggesting active compromise must be handled under:

- [[PROC-010 Security Event Escalation Procedure]]
- [[PLN-001 Incident Response Plan]]

---

# 86. Reporting

Control information supports three reporting levels.

---

# 87. Operational Reporting

Operational reporting focuses on:

- Control execution
- Evidence
- Technical results
- Exceptions
- Failures
- Corrective actions

---

# 88. Management Reporting

Management reporting focuses on:

- Control performance
- Accountability
- Trends
- Findings
- Corrective actions
- Overdue activity

---

# 89. Executive Reporting

Executive reporting focuses on:

- Material control weakness
- Enterprise risk
- Significant treatment status
- Required decisions
- Risk acceptance
- Resource requirements

---

# 90. Reporting Chain

Control information should support:

**Technical Evidence → Operational Exception → Management Impact → Enterprise Risk → Executive Decision**

---

# 91. Register Maintenance

The CIO is accountable for ensuring that this register remains maintained.

Control owners are responsible for reporting material changes affecting their controls.

---

# 92. Quarterly Review

The control inventory must be reviewed at least quarterly for material changes involving:

- Ownership
- Implementation
- Effectiveness
- Findings
- Treatment
- Risk
- Control retirement

---

# 93. Annual Assurance Review

The inventory must be considered when developing [[PLN-005 Annual Assurance Plan]].

---

# 94. Register Accuracy

This register must not intentionally represent:

- Planned controls as implemented.
- Implemented controls as validated without evidence.
- Failed controls as effective.
- Closed findings as open.
- Open findings as resolved.
- Proposed risk reduction as achieved risk reduction.

---

# 95. Current-State Limitation

Several controls in this inventory are formal requirements established through the security program but have not yet been implemented or validated.

Their presence in this register documents the intended control environment.

It does not alter the current residual-risk ratings in [[REG-002 Enterprise Risk Register]].

---

# 96. Program Evolution

As planned controls are implemented, this register becomes the authoritative control-level record for documenting:

- Implementation
- Evidence
- Validation
- Effectiveness
- Findings
- Corrective action
- Risk reassessment

---

# 97. Related Artifacts

- [[README]]
- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-002 Enterprise Security Architecture Program]]
- [[PRO-003 Identity and Access Management Program]]
- [[PRO-004 Vulnerability Management Program]]
- [[PRO-005 Security Operations Program]]
- [[PRO-006 Physical & Personnel Security Program]]
- [[PRO-007 Secure Software Development Lifecycle Program]]
- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[PRO-009 Security Governance Framework]]
- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[RPT-004 Infinity Transferability Review]]
- [[REG-001 Enterprise Asset Register]]
- [[REG-002 Enterprise Risk Register]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[POL-001 Information Security Policy]]
- [[POL-002 Acceptable Use Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-006 Security Awareness & Training Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-011 Physical & Environmental Security Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[STD-001 Information Classification Standard]]
- [[STD-002 Network Security Standard]]
- [[STD-003 Endpoint Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[STD-007 Penetration Testing Standard]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[STD-009 Infinity Security Standard]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]
- [[PLN-005 Annual Assurance Plan]]
- [[PLN-006 Enterprise Security Program Roadmap]]
- [[TMP-001 Assessment Work Plan Template]]
- [[TMP-002 Operational Security Checklist]]
- [[TMP-003 Recovery Test Template]]

---

# 98. Review

This register must be reviewed:

- At least quarterly
- Following material control implementation
- Following material control failure
- Following significant assessment findings
- Following material risk reassessment
- Following significant security architecture change
- Following significant business change

The CIO coordinates review.

Material structural changes require CEO approval.

Routine control-status, evidence, effectiveness, owner, and assessment updates may be maintained as part of normal security governance.

---

# 99. Revision History

| Version | Date     | Description                                   | Approval |
| ------- | -------- | --------------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Enterprise Security Control Inventory | CEO      |