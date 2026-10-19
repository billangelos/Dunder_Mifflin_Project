# GUIDE-002 Project Artifact Map

## Document Control

| Field | Value |
|---|---|
| Document ID | GUIDE-002 |
| Title | Project Artifact Map |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | As Repository Structure or Controlled Artifacts Change |

---

# 1. Purpose

This guide provides a repository-wide map of the Dunder Mifflin Enterprise Information Security and Risk Management Program.

It explains:

- Where major artifacts are located
- What each artifact contributes
- How artifacts relate to one another
- How information moves through the security program
- Where a reader should go for additional detail
- How business requirements ultimately connect to security evidence and risk decisions

This guide is a navigation aid.

It does not replace the authoritative content of the referenced artifacts.

---

# 2. Repository Model

The repository follows the security lifecycle:

**Business → Assets → Information → Business Impact → Risk → Governance → Treatment → Architecture → Controls → Procedures → Implementation → Evidence → Assessment → Findings → Remediation → Retest → Risk Reassessment → Reporting → Improvement**

The folder structure groups artifacts by major security function while cross-references connect related activities across folders.

---

# 3. Enterprise Traceability Model

The complete traceability model is:

**Business Requirement**

↓

**Asset / Process**

↓

**Classification / BIA**

↓

**Risk**

↓

**Treatment**

↓

**Policy / Standard**

↓

**Control**

↓

**Procedure**

↓

**Implementation**

↓

**Evidence**

↓

**Test / Audit**

↓

**Finding**

↓

**Remediation**

↓

**Retest**

↓

**Risk Reassessment**

This traceability model is central to the repository.

---

# 4. Repository Structure

```text
Dunder-Mifflin-Enterprise-Security-Program/
│
├── README.md
├── 00 Executive/
├── 01 Enterprise Context/
├── 02 Risk Management/
├── 03 Governance and Policy/
├── 04 Security Architecture/
├── 05 Identity and Access Management/
├── 06 Vulnerability and Security Assessment/
├── 07 Security Operations/
├── 08 Incident Response/
├── 09 Business Continuity and Disaster Recovery/
├── 10 Physical and Personnel Security/
├── 11 Secure Development/
├── 12 Assurance Metrics and Improvement/
├── 13 Reports and Dashboards/
├── 14 Learning Path/
└── 99 Reference/
```

---

# 5. Root Repository

## README

[[README]]

The README provides the primary introduction to the project.

It establishes:

- Project purpose
- Fictional organizational context
- Assessment date
- Security philosophy
- Risk model
- Major program concepts
- Repository structure
- Portfolio objective
- Project limitations
- AI assistance disclosure

A new reader should begin here.

---

# 6. Folder 00: Executive

This folder contains enterprise-level security planning intended to communicate strategic direction and sequencing.

### [[PLN-006 Enterprise Security Program Roadmap]]

Purpose:

Defines the planned progression of major security improvements, dependencies, priorities, and implementation horizons.

The roadmap translates risk-treatment requirements into a coordinated enterprise improvement sequence.

---

# 7. Folder 01: Enterprise Context

This folder answers:

> **What organization are we protecting, what does it depend on, what information does it use, and how quickly must important functions recover?**

---

# 8. Enterprise Profile

### [[RPT-001 Enterprise Profile & Security Baseline]]

Establishes:

- Business model
- Organizational structure
- Facilities
- Technology environment
- Existing security baseline
- Major applications
- Third-party dependencies
- Current operating assumptions

This artifact establishes the starting condition against which risk is assessed.

---

# 9. Asset Register

### [[REG-001 Enterprise Asset Register]]

Identifies significant:

- Business processes
- Information
- Applications
- Infrastructure
- Endpoints
- Facilities
- People
- Third parties
- Recovery resources

The register connects business activity to the assets required to support it.

---

# 10. Information Classification

### [[STD-001 Information Classification Standard]]

Defines:

- Public
- Internal
- Confidential
- Restricted

The standard establishes handling expectations based on information sensitivity.

---

# 11. Business Impact Analysis

### [[RPT-002 Business Impact Analysis]]

Establishes:

- Business criticality
- Maximum Tolerable Downtime
- Recovery Time Objective
- Recovery Point Objective
- Major process dependencies

The Business Impact Analysis (BIA) provides business requirements used by continuity and recovery planning.

---

# 12. Enterprise Context Flow

The primary flow is:

**Enterprise Profile**

↓

**Asset Register**

↓

**Information Classification**

↓

**Business Impact Analysis**

↓

**Enterprise Risk Assessment**

---

# 13. Folder 02: Risk Management

This folder answers:

> **What could interfere with business objectives, how serious is the exposure, and what will Dunder Mifflin do about it?**

---

# 14. Enterprise Risk Assessment

### [[RPT-003 Enterprise Risk Assessment]]

Documents:

- Risk methodology
- Risk scenarios
- Likelihood
- Impact
- Inherent risk
- Existing controls
- Current residual risk
- Proposed treatment
- Target residual risk

---

# 15. Enterprise Risk Register

### [[REG-002 Enterprise Risk Register]]

Provides the structured record of the 35 enterprise risks.

The register supports:

- Ownership
- Rating
- Treatment
- Tracking
- Reassessment
- Reporting

---

# 16. Enterprise Risk Treatment Plan

### [[RTP-001 Enterprise Risk Treatment Plan]]

Translates assessed risks into treatment activity.

Treatment options include:

- Mitigate
- Transfer
- Avoid
- Accept

The plan also establishes treatment lifecycle status:

**Planned → Approved → Implementing → Implemented → Validation Pending → Validated**

**Corrective Action Required** may be used when validation identifies a deficiency.

---

# 17. Risk Management Flow

The primary flow is:

**Risk Assessment**

↓

**Risk Register**

↓

**Treatment Decision**

↓

**Risk Treatment Plan**

↓

**Control Implementation**

↓

**Validation**

↓

**Risk Reassessment**

---

# 18. Risk Views

The program preserves three distinct risk views:

### Inherent Risk

Exposure before existing controls.

### Current Residual Risk

Exposure after controls that currently exist and receive credit.

### Target Residual Risk

Predicted exposure after proposed treatment is successfully implemented and validated.

---

# 19. Risk Credit Rule

A proposed control does not reduce current residual risk merely because it is:

- Planned
- Approved
- Being implemented
- Documented

Validated implementation and documented risk reassessment are required before current residual risk is changed.

---

# 20. Folder 03: Governance and Policy

This folder answers:

> **Who has authority, what security requirements apply, and who is accountable?**

---

# 21. Enterprise Security Program

### [[PRO-001 Enterprise Information Security & Risk Management Program]]

Establishes the overall enterprise security and risk-management structure.

It connects:

- Governance
- Risk
- Policy
- Controls
- Operations
- Assurance
- Reporting
- Improvement

---

# 22. Security Governance Framework

### [[PRO-009 Security Governance Framework]]

Defines:

- Governance authority
- Security responsibilities
- Risk ownership
- Information Security and Risk Committee
- Escalation
- Oversight
- Decision structure

---

# 23. Policy Framework

The security policy framework consists of:

### [[POL-001 Information Security Policy]]

Enterprise security principles and responsibilities.

### [[POL-002 Acceptable Use Policy]]

Acceptable use of company systems, devices, information, and technology resources.

### [[POL-003 Access Control Policy]]

Identity, authorization, least privilege, account lifecycle, privileged access, and accountability.

### [[POL-004 Information Classification & Handling Policy]]

Information classification and protection requirements.

### [[POL-005 Risk Management Policy]]

Risk identification, assessment, treatment, acceptance, reassessment, and escalation.

### [[POL-006 Security Awareness & Training Policy]]

Security education, awareness, knowledge assessment, and phishing simulation.

### [[POL-007 Change & Configuration Management Policy]]

Controlled technology and configuration change.

### [[POL-008 Third-Party Security Policy]]

Third-party classification, due diligence, contractual security, access, review, incident, and exit requirements.

### [[POL-009 Incident Response Policy]]

Incident authority, reporting, escalation, response, and evidence expectations.

### [[POL-010 Business Continuity & Disaster Recovery Policy]]

Business continuity, recovery, testing, and resilience requirements.

### [[POL-011 Physical & Environmental Security Policy]]

Facility, Restricted area, environmental, visitor, and physical protection requirements.

### [[POL-012 Application & Secure Development Policy]]

Secure development, application security, testing, contractor development, and application ownership requirements.

---

# 24. Governance Hierarchy

The general governance hierarchy is:

**Program**

↓

**Policy**

↓

**Standard**

↓

**Control**

↓

**Procedure**

↓

**Implementation**

↓

**Evidence**

---

# 25. Folder 04: Security Architecture

This folder answers:

> **How should technology be structured and secured to support business and risk requirements?**

---

# 26. Enterprise Security Architecture Program

### [[PRO-002 Enterprise Security Architecture Program]]

Establishes security architecture principles for:

- Networks
- Endpoints
- Servers
- Authentication
- Configuration
- Cloud services
- Application environments
- Administrative access
- Recovery

---

# 27. Network Security Standard

### [[STD-002 Network Security Standard]]

Defines requirements involving:

- Firewalls
- Inbound access
- Administrative exposure
- Remote access
- Network devices
- Configuration
- Network discovery
- Rogue wireless assessment

---

# 28. Endpoint Security Standard

### [[STD-003 Endpoint Security Standard]]

Defines requirements involving:

- Managed antivirus
- Standard-user operation
- Full-disk encryption
- Screen locking
- Patch management
- Mobile Device Management
- Endpoint administration

---

# 29. Server Security Standard

### [[STD-004 Server Security Standard]]

Defines requirements for:

- Server administration
- Patching
- Privileged access
- Configuration
- Logging
- Recovery
- Security maintenance

---

# 30. Authentication and Account Security Standard

### [[STD-005 Authentication & Account Security Standard]]

Defines requirements for:

- Authentication
- Account management
- Privileged credentials
- Dormant accounts
- Multifactor authentication
- Contractor accounts
- Emergency access

---

# 31. Secure Configuration Standard

### [[STD-006 Secure Configuration Standard]]

Defines requirements for:

- Configuration baselines
- Change control
- Hardening
- Exceptions
- Configuration documentation
- Verification

---

# 32. Architecture Flow

The architecture relationship is:

**Business / Risk Requirement**

↓

**Security Architecture**

↓

**Technical Standard**

↓

**Control**

↓

**Technical Implementation**

↓

**Evidence**

↓

**Assessment**

---

# 33. Folder 05: Identity and Access Management

This folder answers:

> **Who should receive access, what access should they receive, and how is that access controlled throughout its lifecycle?**

---

# 34. IAM Program

### [[PRO-003 Identity and Access Management Program]]

Establishes the enterprise Identity and Access Management (IAM) framework.

---

# 35. Joiner-Mover-Leaver

### [[PROC-001 Joiner-Mover-Leaver Procedure]]

Controls:

- New access
- Transfers
- Terminations

Human Resources serves as the authoritative source for personnel status.

---

# 36. Privileged Access

### [[PROC-002 Privileged Access Procedure]]

Controls elevated administrative access.

Key principles include:

- Separate privileged credentials
- Least privilege
- Restricted standing Domain Administrator access
- Individual accountability
- Review

---

# 37. Access Review

### [[PROC-003 Access Review Procedure]]

Supports:

- Annual ordinary-user review
- Quarterly privileged-access review

---

# 38. Contractor Access

### [[PROC-004 Contractor Access Procedure]]

Controls:

- Sponsorship
- Authorization
- Duration
- Least privilege
- Review
- Termination

---

# 39. Emergency Access

### [[PROC-005 Emergency Access Procedure]]

Provides controlled emergency access when normal authorization methods cannot satisfy an urgent legitimate need.

Emergency access remains:

- Accountable
- Documented
- Temporary
- Reviewed

---

# 40. IAM Flow

**Personnel / Contractor Need**

↓

**Authorization**

↓

**Account Provisioning**

↓

**Authentication**

↓

**Access**

↓

**Review**

↓

**Transfer / Termination**

↓

**Evidence**

↓

**Assessment**

---

# 41. Folder 06: Vulnerability and Security Assessment

This folder answers:

> **Where are technical weaknesses, how quickly should they be corrected, and how do we verify remediation?**

---

# 42. Vulnerability Management Program

### [[PRO-004 Vulnerability Management Program]]

Establishes:

- Assessment scope
- Vulnerability identification
- Prioritization
- Remediation
- Retesting
- Exception handling
- Reporting

---

# 43. Vulnerability Assessment Procedure

### [[PROC-006 Vulnerability Assessment Procedure]]

Defines recurring vulnerability-assessment activity.

Internal vulnerability assessment occurs monthly.

---

# 44. Vulnerability Remediation and Retest

### [[PROC-007 Vulnerability Remediation & Retest Procedure]]

Defines:

- Remediation ownership
- Target timeframes
- Validation
- Retesting
- Escalation

Target remediation periods:

| Severity | Target |
|---|---|
| Critical | 7 days |
| High | 30 days |
| Moderate | 45 days |
| Low | 60 days |

---

# 45. Penetration Testing Standard

### [[STD-007 Penetration Testing Standard]]

Defines requirements for authorized penetration testing, including:

- Scope
- Approval
- Testing rules
- Evidence
- Findings
- Remediation
- Retesting

---

# 46. Vulnerability Flow

**Asset**

↓

**Assessment**

↓

**Vulnerability**

↓

**Prioritization**

↓

**Remediation**

↓

**Retest**

↓

**Evidence**

↓

**Control / Risk Reassessment**

---

# 47. Folder 07: Security Operations

This folder answers:

> **How are routine security conditions observed, investigated, escalated, and preserved as evidence?**

---

# 48. Security Operations Program

### [[PRO-005 Security Operations Program]]

Establishes routine security operations without assuming a dedicated 24-hour Security Operations Center.

---

# 49. Security Monitoring

### [[PROC-008 Security Monitoring Procedure]]

Defines monitoring of applicable:

- Authentication activity
- Malware
- Network conditions
- Security events
- Monitoring-source failures

---

# 50. Malware Response

### [[PROC-009 Malware Response Procedure]]

Defines operational handling of malware detections and suspected infections.

---

# 51. Security Event Escalation

### [[PROC-010 Security Event Escalation Procedure]]

Defines when a security event requires:

- Investigation
- Management escalation
- Incident declaration

---

# 52. Evidence Handling

### [[PROC-011 Evidence Handling Procedure]]

Defines:

- Evidence identification
- Collection
- Custody
- Integrity
- Documentation
- Access
- SHA-256 hashing where practical and appropriate

---

# 53. Security Operations Flow

**Security Activity**

↓

**Event / Condition**

↓

**Review**

↓

**Investigation**

↓

**Operational Correction or Escalation**

↓

**Incident / Finding / Risk Action Where Required**

---

# 54. Folder 08: Incident Response

This folder answers:

> **What happens when a security event becomes an incident?**

---

# 55. Incident Classification and Escalation

### [[STD-008 Incident Classification & Escalation Standard]]

Defines incident classification and escalation expectations.

---

# 56. Incident Response Plan

### [[PLN-001 Incident Response Plan]]

Coordinates:

- Preparation
- Identification
- Analysis
- Containment
- Eradication
- Recovery
- Communications
- Evidence
- Lessons learned

---

# 57. Incident Playbooks

Scenario-specific response is supported by:

### [[PBK-001 Phishing & Credential Compromise Playbook]]

### [[PBK-002 Malware & Ransomware Playbook]]

### [[PBK-003 Unauthorized Access Playbook]]

### [[PBK-004 Data Exposure Playbook]]

### [[PBK-005 Third-Party Incident Playbook]]

---

# 58. Incident Response Flow

**Security Event**

↓

**Triage**

↓

**Classification**

↓

**Incident Declaration**

↓

**Containment**

↓

**Eradication**

↓

**Recovery**

↓

**Lessons Learned**

↓

**Corrective Action**

↓

**Risk Reassessment Where Required**

---

# 59. Incident Support

The program includes a proposed retained Digital Forensics and Incident Response provider as a Critical Security Response Provider.

Until the relationship is implemented and validated, it does not receive current residual-risk credit.

---

# 60. Folder 09: Business Continuity and Disaster Recovery

This folder answers:

> **How will important business functions continue and recover when normal systems, facilities, or services are unavailable?**

---

# 61. Business Continuity Plan

### [[PLN-002 Business Continuity Plan]]

Coordinates continuity of important business activity during disruption.

---

# 62. Disaster Recovery Plan

### [[PLN-003 Disaster Recovery Plan]]

Coordinates restoration of required technology and supporting services.

---

# 63. Cloud Exit and Emergency Migration

### [[PLN-004 Cloud Exit & Emergency Migration Plan]]

Addresses significant cloud-provider failure, loss, or emergency migration requirements.

The plan does not assume that Dunder Mifflin maintains a continuously operating alternate cloud environment.

---

# 64. Backup and Recovery Procedure

### [[PROC-012 Backup & Recovery Procedure]]

Defines:

- Backup operation
- Backup coverage
- Encrypted external-drive rotation
- Off-site storage
- Restore testing
- Recovery testing
- Evidence

---

# 65. Backup Rotation

The external-drive rotation consists of:

- 7 facilities
- 3 encrypted drives per facility
- 21 encrypted drives total

The off-site disaster recovery storage provider normally holds:

- 2 latest weekly generations per facility
- 14 encrypted drives total

---

# 66. Manual Processing Procedure

### [[PROC-013 Manual Processing Procedure]]

Defines the manual continuity lifecycle:

**Collect → Review → Enter → Reconcile → Verify**

This supports business operation during applicable system outages.

---

# 67. Recovery Test Template

### [[TMP-003 Recovery Test Template]]

Provides a controlled format for documenting:

- Test scope
- BIA requirements
- Recovery source
- Actual recovery time
- Actual data loss
- RTO result
- RPO result
- Validation
- Findings
- Corrective action
- Retest

---

# 68. BC/DR Flow

**BIA Requirement**

↓

**Continuity / Recovery Strategy**

↓

**Backup / Manual Capability**

↓

**Recovery Procedure**

↓

**Exercise / Test**

↓

**Evidence**

↓

**Finding**

↓

**Corrective Action**

↓

**Retest**

↓

**Risk Reassessment**

---

# 69. Recovery Priority

Recovery priority is:

**Human Safety → Critical → High → Moderate → Low**

Human safety takes priority over system recovery.

---

# 70. Folder 10: Physical and Personnel Security

This folder answers:

> **How are facilities, physical assets, sensitive areas, personnel processes, and physical access protected?**

---

# 71. Physical and Personnel Security Program

### [[PRO-006 Physical & Personnel Security Program]]

Establishes the physical and personnel security framework.

---

# 72. Facility Access

### [[PROC-014 Facility Access Procedure]]

Controls general facility access.

---

# 73. Visitor and Vendor Access

### [[PROC-015 Visitor & Vendor Access Procedure]]

Controls temporary physical access by:

- Visitors
- Vendors
- Service personnel
- Contractors
- Delivery personnel

---

# 74. Restricted Areas

### [[PROC-016 Restricted Area Access Procedure]]

Controls physical access to areas requiring greater protection.

Examples include:

- Significant Information Technology areas
- Sensitive records
- Warehouse high-value cages

---

# 75. Personnel Security

### [[PROC-017 Personnel Security Procedure]]

Coordinates personnel security across:

- Hiring
- Access authorization
- Work
- Transfer
- Termination
- Confidentiality
- Contractor personnel
- Key-person dependency
- Cross-training

---

# 76. Physical Security Model

Dunder Mifflin uses:

- Public
- Controlled
- Restricted

physical-access concepts.

---

# 77. Physical and Personnel Flow

**Business Need**

↓

**Personnel / Visitor Identity**

↓

**Authorization**

↓

**Facility / Restricted Access**

↓

**Monitoring / Accountability**

↓

**Access Removal**

↓

**Evidence**

↓

**Review**

---

# 78. Folder 11: Secure Development

This folder answers:

> **How is Infinity developed, changed, tested, supported, and kept under Dunder Mifflin control?**

---

# 79. Secure Software Development Lifecycle Program

### [[PRO-007 Secure Software Development Lifecycle Program]]

Establishes secure development requirements throughout the application lifecycle.

---

# 80. Infinity Security Standard

### [[STD-009 Infinity Security Standard]]

Defines security requirements specific to Infinity.

---

# 81. Secure Change and Release

### [[PROC-018 Secure Change & Release Procedure]]

Controls:

- Change authorization
- Development
- Testing
- Review
- Release
- Verification
- Rollback

---

# 82. Application Security Assessment

### [[PROC-019 Application Security Assessment Procedure]]

Defines application-focused security assessment requirements.

Infinity receives:

- Annual security assessment
- Annual application penetration test

---

# 83. Contractor Development Access

### [[PROC-020 Contractor Development Access Procedure]]

Controls contractor access to Infinity development and production-support resources.

Key principles include:

- Sponsorship
- Named personnel
- Least privilege
- Time limitation
- Individual accountability
- Controlled privileged activity
- No general contractor VPN access

---

# 84. Infinity Transferability

### [[RPT-004 Infinity Transferability Review]]

Evaluates whether another qualified party could assume Infinity support without unreasonable dependence on the current contractor.

It evaluates:

- Ownership
- Source and repository
- Architecture
- Build and deployment
- Configuration
- Access and credentials
- Documentation
- Dependencies
- Recovery
- Knowledge transfer

---

# 85. Secure Development Flow

**Business Requirement**

↓

**Application Requirement**

↓

**Threat / Risk**

↓

**Secure Design**

↓

**Development**

↓

**Review / Testing**

↓

**Controlled Release**

↓

**Production**

↓

**Assessment**

↓

**Finding**

↓

**Remediation / Retest**

---

# 86. Infinity Assurance Chain

The Infinity assurance chain is:

**Assessment / Penetration Test → Finding → Remediation → Retest → Control Effectiveness → R006 Risk Reassessment**

---

# 87. Folder 12: Assurance, Metrics, and Improvement

This folder answers:

> **How do we know the security program actually works?**

---

# 88. Security Assurance Program

### [[PRO-008 Security Assurance & Continuous Improvement Program]]

Establishes the assurance framework.

The central assurance question is:

> **How do we know the control actually works?**

---

# 89. Enterprise Security Control Inventory

### [[REG-003 Enterprise Security Control Inventory]]

Provides the central inventory of enterprise security controls.

The inventory connects:

- Control objective
- Owner
- Related risk
- Implementation status
- Evidence
- Assessment
- Effectiveness

---

# 90. Finding and Corrective Action Register

### [[REG-004 Finding & Corrective Action Register]]

Tracks material control deficiencies and corrective actions.

It supports:

**Finding → Corrective Action → Validation → Retest → Closure**

---

# 91. Security Metrics Catalog

### [[REG-005 Security Metrics Catalog]]

Defines:

- Key Performance Indicators
- Key Risk Indicators
- Operational measures
- Data sources
- Owners
- Reporting frequency
- Interpretation
- Reporting level

---

# 92. Annual Assurance Plan

### [[PLN-005 Annual Assurance Plan]]

Establishes the risk-based annual assessment schedule.

Assessment priority considers:

- Inherent risk
- Current residual risk
- Critical controls
- BIA criticality
- Previous findings
- Material change

---

# 93. Assessment Work Plan

### [[TMP-001 Assessment Work Plan Template]]

Defines the detailed plan for an individual assessment.

It establishes:

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

---

# 94. Operational Security Checklist

### [[TMP-002 Operational Security Checklist]]

Supports recurring operational security review and exception identification.

---

# 95. CISSP Domain Crosswalk

### [[RPT-005 CISSP Domain Crosswalk]]

Maps project activities to the eight CISSP domains.

The crosswalk demonstrates that the security program incorporates the domains naturally through enterprise security work rather than organizing the company around certification topics.

---

# 96. Assurance Flow

**Requirement**

↓

**Control**

↓

**Implementation**

↓

**Evidence**

↓

**Assessment**

↓

**Finding**

↓

**Corrective Action**

↓

**Validation**

↓

**Retest**

↓

**Control Effectiveness**

↓

**Risk Reassessment**

---

# 97. Control Effectiveness

Control effectiveness is evaluated separately from implementation.

Effectiveness may be:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

A control should not be assumed effective merely because it has been deployed.

---

# 98. Assessment Methods

Assessment may use:

- Inspection
- Observation
- Interviews
- Sampling
- Independent Performance
- Technical Testing
- Exercises
- Reconciliation

The method should match the control and assessment objective.

---

# 99. Findings

A finding is:

> **A documented conclusion supported by evidence concerning whether a requirement, control, process, or expected outcome is satisfied.**

Findings provide the connection between assessment evidence and corrective action.

---

# 100. Folder 13: Reports and Dashboards

This folder answers:

> **How is security information communicated to the people who need to act on it?**

---

# 101. Executive Security Summary

### [[RPT-006 Executive Security Summary]]

Audience:

- CEO
- Information Security and Risk Committee
- Senior leadership

Focus:

- Enterprise risk
- Business impact
- Significant exposure
- Decisions
- Resources

---

# 102. Management Security Report

### [[RPT-007 Management Security Report]]

Audience:

- CIO
- IT & Information Security Manager
- Business managers
- Risk owners
- Control owners

Focus:

- Accountability
- Performance
- Corrective action
- Trends
- Escalation

---

# 103. Operational Security Report

### [[RPT-008 Operational Security Report & Dashboard]]

Audience:

- Information Technology
- Information Security
- Operational control owners

Focus:

- Execution
- Evidence
- Exceptions
- Technical detail

---

# 104. Reporting Model

The reporting model is:

> **Executive → decisions and enterprise risk**  
> **Management → accountability, performance, and action**  
> **Operational → execution, evidence, exceptions, and technical detail**

---

# 105. Reporting Chain

Security information moves through:

**Technical Evidence → Operational Exception → Management Impact → Enterprise Risk → Executive Decision**

---

# 106. Folder 14: Learning Path

This folder explains how to study the project.

### [[GUIDE-001 GRC Learning Path]]

The guide walks a learner through:

- Business understanding
- Asset identification
- Classification
- BIA
- Risk
- Governance
- Treatment
- Controls
- Implementation
- Evidence
- Assessment
- Findings
- Remediation
- Retesting
- Risk reassessment
- Reporting
- Continuous improvement

---

# 107. Folder 99: Reference

This folder contains repository-level navigation, terminology, document control, and cross-reference artifacts.

---

# 108. Artifact Index

### [[INDEX-001 Artifact Index]]

Provides the authoritative list of controlled artifacts and their repository locations.

Use the Artifact Index when locating a specific document.

---

# 109. Document Control Register

### [[REG-006 Document Control Register]]

Tracks document-control information across the repository.

It supports:

- Artifact identification
- Version control
- Status
- Ownership
- Approval
- Review frequency
- Classification

---

# 110. Cross-Reference Matrix

### [[REG-007 Cross-Reference Matrix]]

Provides repository-wide cross-reference support.

It helps verify that references between artifacts resolve to the intended controlled documents.

---

# 111. Acronym and Terminology Guide

### [[GUIDE-003 Acronym & Terminology Guide]]

Provides a centralized reference for acronyms and important security, risk, continuity, governance, and project terminology used throughout the repository.

---

# 112. Artifact Type Map

| Prefix | Artifact Type | Primary Purpose |
|---|---|---|
| POL | Policy | Establish management requirements |
| PRO | Program | Organize a security capability |
| STD | Standard | Define mandatory implementation requirements |
| PLN | Plan | Coordinate future or event-driven action |
| PROC | Procedure | Explain how required activity is performed |
| REG | Register | Maintain structured records |
| RTP | Risk Treatment Plan | Coordinate enterprise risk treatment |
| RPT | Report | Analyze or communicate information |
| TMP | Template | Provide controlled structure for recurring work |
| PBK | Playbook | Guide scenario-specific response |
| GUIDE | Guide | Explain navigation, learning, or reference information |
| INDEX | Index | Provide repository-wide artifact navigation |

---

# 113. Artifact Relationship Example: Identity and Access

The IAM artifact chain includes:

**[[POL-003 Access Control Policy]]**

↓

**[[PRO-003 Identity and Access Management Program]]**

↓

**[[STD-005 Authentication & Account Security Standard]]**

↓

**[[REG-003 Enterprise Security Control Inventory]]**

↓

**[[PROC-001 Joiner-Mover-Leaver Procedure]]**

**[[PROC-002 Privileged Access Procedure]]**

**[[PROC-003 Access Review Procedure]]**

**[[PROC-004 Contractor Access Procedure]]**

**[[PROC-005 Emergency Access Procedure]]**

↓

**Implementation**

↓

**Evidence**

↓

**Assessment**

↓

**[[REG-004 Finding & Corrective Action Register]]**

↓

**Risk Reassessment**

---

# 114. Artifact Relationship Example: Vulnerability Management

**[[PRO-004 Vulnerability Management Program]]**

↓

**[[PROC-006 Vulnerability Assessment Procedure]]**

↓

**Vulnerability Evidence**

↓

**[[PROC-007 Vulnerability Remediation & Retest Procedure]]**

↓

**Retest**

↓

**Control Effectiveness**

↓

**Risk Reassessment**

Penetration testing is governed by:

[[STD-007 Penetration Testing Standard]]

---

# 115. Artifact Relationship Example: Incident Response

**[[POL-009 Incident Response Policy]]**

↓

**[[STD-008 Incident Classification & Escalation Standard]]**

↓

**[[PLN-001 Incident Response Plan]]**

↓

**Scenario Playbook**

↓

**Incident Action**

↓

**Evidence**

↓

**Lessons Learned**

↓

**Finding / Corrective Action**

↓

**Risk Reassessment**

---

# 116. Artifact Relationship Example: Business Continuity

**[[RPT-002 Business Impact Analysis]]**

↓

**[[POL-010 Business Continuity & Disaster Recovery Policy]]**

↓

**[[PLN-002 Business Continuity Plan]]**

and

**[[PLN-003 Disaster Recovery Plan]]**

↓

**[[PROC-012 Backup & Recovery Procedure]]**

and

**[[PROC-013 Manual Processing Procedure]]**

↓

**[[TMP-003 Recovery Test Template]]**

↓

**Recovery Evidence**

↓

**Finding**

↓

**Corrective Action**

↓

**Retest**

↓

**Risk Reassessment**

---

# 117. Artifact Relationship Example: Infinity

**R006 Infinity Compromise**

and

**R019 Infinity Contractor**

↓

**[[POL-012 Application & Secure Development Policy]]**

↓

**[[PRO-007 Secure Software Development Lifecycle Program]]**

↓

**[[STD-009 Infinity Security Standard]]**

↓

**[[PROC-018 Secure Change & Release Procedure]]**

**[[PROC-019 Application Security Assessment Procedure]]**

**[[PROC-020 Contractor Development Access Procedure]]**

↓

**[[RPT-004 Infinity Transferability Review]]**

↓

**Assessment / Penetration Test**

↓

**Finding**

↓

**Remediation**

↓

**Retest**

↓

**Control Effectiveness**

↓

**Risk Reassessment**

---

# 118. Artifact Relationship Example: Assurance

**[[REG-003 Enterprise Security Control Inventory]]**

↓

**[[PLN-005 Annual Assurance Plan]]**

↓

**[[TMP-001 Assessment Work Plan Template]]**

↓

**Assessment**

↓

**Evidence**

↓

**[[REG-004 Finding & Corrective Action Register]]**

↓

**Corrective Action**

↓

**Validation / Retest**

↓

**Control Effectiveness**

↓

**Risk Reassessment**

↓

**Reporting**

---

# 119. Artifact Relationship Example: Reporting

Operational evidence is summarized in:

[[RPT-008 Operational Security Report & Dashboard]]

Material management information flows to:

[[RPT-007 Management Security Report]]

Enterprise-level risk and decisions flow to:

[[RPT-006 Executive Security Summary]]

The relationship is:

**Operational → Management → Executive**

---

# 120. Risk-to-Control Navigation

When investigating a risk:

1. Locate the risk in [[REG-002 Enterprise Risk Register]].
2. Review analysis in [[RPT-003 Enterprise Risk Assessment]].
3. Review treatment in [[RTP-001 Enterprise Risk Treatment Plan]].
4. Identify applicable controls in [[REG-003 Enterprise Security Control Inventory]].
5. Follow the control to applicable policy, standard, and procedure.
6. Identify required evidence.
7. Review applicable assurance activity.
8. Review findings in [[REG-004 Finding & Corrective Action Register]].
9. Review applicable risk reassessment.
10. Review management or executive reporting where required.

---

# 121. Control-to-Risk Navigation

When investigating a control:

1. Locate the control in [[REG-003 Enterprise Security Control Inventory]].
2. Identify the requirement.
3. Identify related risks.
4. Identify the owner.
5. Identify implementation status.
6. Identify expected evidence.
7. Identify the assessment method.
8. Review applicable findings.
9. Review corrective actions.
10. Determine whether validated evidence supports risk reassessment.

---

# 122. Finding-to-Risk Navigation

When investigating a finding:

1. Locate the finding in [[REG-004 Finding & Corrective Action Register]].
2. Identify the failed requirement.
3. Identify the affected control.
4. Identify related assets or processes.
5. Identify related risk.
6. Review corrective action.
7. Review validation.
8. Review retest.
9. Update control effectiveness where supported.
10. Reassess risk where the evidence materially changes exposure.

---

# 123. BIA-to-Recovery Navigation

When investigating recovery requirements:

1. Locate the process in [[RPT-002 Business Impact Analysis]].
2. Identify criticality.
3. Identify Maximum Tolerable Downtime.
4. Identify Recovery Time Objective.
5. Identify Recovery Point Objective.
6. Identify supporting systems.
7. Review [[PLN-002 Business Continuity Plan]].
8. Review [[PLN-003 Disaster Recovery Plan]].
9. Review [[PROC-012 Backup & Recovery Procedure]].
10. Review applicable recovery-test evidence.

---

# 124. Third-Party Navigation

When investigating a third party:

1. Determine business dependency.
2. Determine third-party classification.
3. Review [[POL-008 Third-Party Security Policy]].
4. Identify sensitive access.
5. Verify confidentiality requirements where applicable.
6. Review logical and physical access.
7. Review incident requirements.
8. Review continuity and exit considerations.
9. Identify related controls in [[REG-003 Enterprise Security Control Inventory]].
10. Identify related risks.

---

# 125. Physical Security Navigation

When investigating physical access:

1. Review [[POL-011 Physical & Environmental Security Policy]].
2. Review [[PRO-006 Physical & Personnel Security Program]].
3. Determine whether the area is Public, Controlled, or Restricted.
4. Review [[PROC-014 Facility Access Procedure]].
5. Review [[PROC-015 Visitor & Vendor Access Procedure]] where applicable.
6. Review [[PROC-016 Restricted Area Access Procedure]] where applicable.
7. Identify required evidence.
8. Review exceptions and findings.

---

# 126. Personnel Security Navigation

When investigating personnel security:

1. Review [[PROC-017 Personnel Security Procedure]].
2. Determine personnel status.
3. Review confidentiality requirements.
4. Review logical access.
5. Review physical access.
6. Review transfer or termination requirements.
7. Review key-person dependency.
8. Review cross-training or alternate capability where applicable.
9. Identify evidence.
10. Review findings or risk impact.

---

# 127. Evidence Navigation

Evidence should always be connected to a purpose.

Ask:

1. What requirement does this evidence support?
2. What control produced it?
3. What period does it cover?
4. Is it reliable?
5. Is it complete?
6. Is it timely?
7. Has its integrity been preserved?
8. What conclusion can it support?

---

# 128. Assessment Navigation

For a planned assessment:

1. Review [[PLN-005 Annual Assurance Plan]].
2. Identify the control in [[REG-003 Enterprise Security Control Inventory]].
3. Create an assessment work plan using [[TMP-001 Assessment Work Plan Template]].
4. Gather evidence.
5. Perform the approved assessment procedure.
6. Reach an evidence-supported conclusion.
7. Record material deficiencies in [[REG-004 Finding & Corrective Action Register]].
8. Assign corrective action.
9. Validate and retest.
10. Update control effectiveness and risk where supported.

---

# 129. Metrics Navigation

For a security metric:

1. Locate the definition in [[REG-005 Security Metrics Catalog]].
2. Identify its purpose.
3. Identify the source.
4. Identify the owner.
5. Identify reporting frequency.
6. Apply the approved calculation.
7. Interpret the result.
8. Report it at the appropriate level.
9. Escalate material conditions where required.

---

# 130. Reporting Navigation

Use the reporting level that matches the audience.

### Operational

[[RPT-008 Operational Security Report & Dashboard]]

Question:

> What happened, what evidence exists, and what requires operational action?

### Management

[[RPT-007 Management Security Report]]

Question:

> What requires accountability, correction, resources, or escalation?

### Executive

[[RPT-006 Executive Security Summary]]

Question:

> What enterprise risk or business decision requires leadership attention?

---

# 131. Learning Navigation

A learner seeking to understand how the complete program works should use:

[[GUIDE-001 GRC Learning Path]]

The learning path explains the program in the order the concepts should be understood rather than simply following folder order.

---

# 132. CISSP Navigation

Use:

[[RPT-005 CISSP Domain Crosswalk]]

to identify how project activities correspond to:

1. Security and Risk Management
2. Asset Security
3. Security Architecture and Engineering
4. Communication and Network Security
5. Identity and Access Management
6. Security Assessment and Testing
7. Security Operations
8. Software Development Security

---

# 133. Document Control Navigation

Use:

[[REG-006 Document Control Register]]

to verify:

- Document ID
- Version
- Status
- Owner
- Approval
- Review frequency
- Classification

---

# 134. Cross-Reference Navigation

Use:

[[REG-007 Cross-Reference Matrix]]

to verify relationships between controlled artifacts.

The matrix supports repository maintenance and helps prevent unresolved or misleading references.

---

# 135. Terminology Navigation

Use:

[[GUIDE-003 Acronym & Terminology Guide]]

when:

- An acronym is unfamiliar.
- A security term requires clarification.
- Similar terms must be distinguished.
- Consistent repository terminology is required.

---

# 136. Roadmap Navigation

Use:

[[PLN-006 Enterprise Security Program Roadmap]]

to understand:

- Implementation priority
- Treatment sequence
- Dependencies
- Near-term work
- Medium-term work
- Ongoing security activities

The roadmap should be read with the risk treatment plan rather than as an independent list of technology projects.

---

# 137. Security Program Roadmap Relationship

The roadmap is driven by:

**Enterprise Risk Assessment**

↓

**Risk Treatment Plan**

↓

**Business and Technical Dependencies**

↓

**Implementation Sequence**

↓

**Security Program Roadmap**

---

# 138. Artifact Ownership

Artifact ownership establishes accountability for maintaining the artifact.

Ownership does not mean the owner personally performs every activity described by the document.

For example:

A CIO may own a program while:

- Information Technology implements technical controls.
- Human Resources performs personnel activities.
- Operations manages facilities.
- Finance performs financial controls.
- Business managers authorize access.

---

# 139. Artifact Approval

Approval indicates that the appropriate authority accepts the document as part of the security program.

Approval does not prove that every control described in the document has been implemented or validated.

---

# 140. Artifact Status

Artifact status and control implementation status are different concepts.

An approved policy can require a control that remains planned.

The policy may be approved while the control is not yet implemented.

---

# 141. Document Versus Evidence

A controlled document establishes requirements or records structured information.

It does not automatically prove operational performance.

Example:

[[PROC-012 Backup & Recovery Procedure]]

defines how backup and recovery should operate.

Actual backup records and recovery-test results provide evidence of operation.

---

# 142. Template Versus Evidence

A template is not evidence.

Examples:

- [[TMP-001 Assessment Work Plan Template]]
- [[TMP-002 Operational Security Checklist]]
- [[TMP-003 Recovery Test Template]]

A completed, authorized instance may become evidence.

The blank template does not prove that the activity occurred.

---

# 143. Plan Versus Capability

A plan documents intended coordinated action.

A plan does not prove the organization can successfully execute it.

Capability requires:

- Implementation
- Training
- Resources
- Evidence
- Exercises or testing where appropriate

---

# 144. Policy Versus Control

A policy establishes a requirement.

A control implements or supports that requirement.

Example:

[[POL-003 Access Control Policy]]

may require least privilege.

Actual account permissions, approval workflows, reviews, and administrative restrictions provide the controls implementing that requirement.

---

# 145. Control Versus Procedure

A control states what safeguard should exist or what objective should be achieved.

A procedure explains how personnel perform the required activity.

One control may rely on several procedures.

One procedure may support several controls.

---

# 146. Control Versus Evidence

A control is not its evidence.

Example:

Control:

> Terminated employee access is promptly disabled.

Evidence may include:

- HR termination notification
- Account-disable record
- Access-system record
- Termination checklist

The evidence helps determine whether the control operated.

---

# 147. Evidence Versus Finding

Evidence is information used to support a conclusion.

A finding is the conclusion.

Example:

Evidence:

> A privileged account existed without current authorization.

Finding:

> Privileged access was not maintained in accordance with the access-control requirement.

---

# 148. Finding Versus Corrective Action

A finding identifies a condition.

Corrective action addresses that condition.

Example:

Finding:

> Required quarterly privileged-access review was not completed.

Corrective action:

> Complete the review, resolve inappropriate access, determine why the review was missed, and correct the process as appropriate.

---

# 149. Corrective Action Versus Validation

Corrective action is what management does to address the finding.

Validation determines whether the corrective action actually corrected the deficiency.

Do not confuse reported completion with validated correction.

---

# 150. Validation Versus Risk Reassessment

Validation determines whether a control or corrective action achieved the expected result.

Risk reassessment determines whether that evidence materially changes the risk.

A successful control test does not automatically dictate a specific new risk score.

---

# 151. Continuous Improvement Model

The repository supports:

**Identify → Decide → Implement → Measure → Assess → Correct → Validate → Reassess → Improve**

This cycle applies across:

- Risk
- IAM
- Vulnerability management
- Security operations
- Incident response
- Recovery
- Physical security
- Personnel security
- Third-party security
- Secure development

---

# 152. Historical Integrity

The repository preserves historical security information rather than rewriting it when conditions improve.

Preserve applicable:

- Original risk ratings
- Original control conditions
- Failed tests
- Findings
- Corrective actions
- Retest results
- Revised risk assessments

Improvement should be visible through the record.

---

# 153. No Manufactured Evidence

Portfolio documentation must not imply that operational evidence exists when it does not.

Blank:

- Registers
- Dashboards
- Assessment templates
- Recovery-test templates
- Finding records

remain intentionally unpopulated until supported by actual authorized activity.

---

# 154. Repository Navigation Principle

When a question arises, begin with the artifact closest to the business question and follow the traceability chain.

Do not begin with a technical control unless the question itself is technical.

Examples:

### Business interruption question

Begin with:

[[RPT-002 Business Impact Analysis]]

### Enterprise risk question

Begin with:

[[REG-002 Enterprise Risk Register]]

### Control question

Begin with:

[[REG-003 Enterprise Security Control Inventory]]

### Assessment question

Begin with:

[[PLN-005 Annual Assurance Plan]]

or:

[[TMP-001 Assessment Work Plan Template]]

### Finding question

Begin with:

[[REG-004 Finding & Corrective Action Register]]

---

# 155. Program-Level Navigation

For a high-level understanding of the security program, read:

1. [[README]]
2. [[RPT-001 Enterprise Profile & Security Baseline]]
3. [[RPT-003 Enterprise Risk Assessment]]
4. [[RTP-001 Enterprise Risk Treatment Plan]]
5. [[PRO-001 Enterprise Information Security & Risk Management Program]]
6. [[PRO-009 Security Governance Framework]]
7. [[REG-003 Enterprise Security Control Inventory]]
8. [[PRO-008 Security Assurance & Continuous Improvement Program]]
9. [[RPT-006 Executive Security Summary]]

---

# 156. Practitioner Navigation

For operational understanding, read:

1. Applicable policy
2. Applicable program
3. Applicable standard
4. Applicable procedure
5. [[REG-003 Enterprise Security Control Inventory]]
6. [[TMP-002 Operational Security Checklist]]
7. [[RPT-008 Operational Security Report & Dashboard]]

---

# 157. Assessor Navigation

For assurance work, read:

1. [[PRO-008 Security Assurance & Continuous Improvement Program]]
2. [[REG-003 Enterprise Security Control Inventory]]
3. [[PLN-005 Annual Assurance Plan]]
4. [[TMP-001 Assessment Work Plan Template]]
5. Applicable requirement artifact
6. Applicable procedure
7. Available evidence
8. [[REG-004 Finding & Corrective Action Register]]
9. [[REG-005 Security Metrics Catalog]]

---

# 158. Manager Navigation

For management oversight, read:

1. [[RPT-007 Management Security Report]]
2. [[REG-002 Enterprise Risk Register]]
3. [[RTP-001 Enterprise Risk Treatment Plan]]
4. [[REG-004 Finding & Corrective Action Register]]
5. [[REG-005 Security Metrics Catalog]]
6. Applicable program or policy

---

# 159. Executive Navigation

For executive oversight, begin with:

[[RPT-006 Executive Security Summary]]

Follow supporting references only when additional detail is needed.

Executive review should remain focused on:

- Enterprise risk
- Business impact
- Significant unresolved exposure
- Resource requirements
- Decisions

---

# 160. Learner Navigation

For educational use, begin with:

[[GUIDE-001 GRC Learning Path]]

Then use this artifact map to move between the documents referenced in each learning stage.

---

# 161. Repository Maintenance

When an artifact is:

- Added
- Renamed
- Moved
- Replaced
- Retired
- Significantly revised

review applicable:

- [[INDEX-001 Artifact Index]]
- [[REG-006 Document Control Register]]
- [[REG-007 Cross-Reference Matrix]]
- [[GUIDE-002 Project Artifact Map]]
- [[GUIDE-003 Acronym & Terminology Guide]]

and affected artifact cross-references.

---

# 162. Cross-Reference Principle

A cross-reference should help the reader reach a real destination.

Avoid references to:

- Documents that do not exist
- Obsolete artifact IDs
- Temporary artifact names
- Unclear destination documents

Where practical, references should identify the controlled artifact and the relevant heading or section.

---

# 163. Final Repository Relationship

The repository can be understood as four connected questions.

### 1. What matters?

Answered by:

- Enterprise context
- Assets
- Classification
- BIA

### 2. What could go wrong?

Answered by:

- Risk assessment
- Risk register

### 3. What are we doing about it?

Answered by:

- Governance
- Treatment
- Policies
- Architecture
- Controls
- Procedures
- Operations
- Recovery

### 4. How do we know it works?

Answered by:

- Evidence
- Assurance
- Assessment
- Findings
- Corrective action
- Retesting
- Metrics
- Reporting
- Risk reassessment

---

# 164. Final Artifact Map

The complete program relationship is:

**Business Context**

↓

**Assets and Dependencies**

↓

**Classification and BIA**

↓

**Enterprise Risk**

↓

**Governance and Treatment**

↓

**Architecture and Controls**

↓

**Procedures and Operations**

↓

**Evidence**

↓

**Assessment**

↓

**Findings**

↓

**Corrective Action**

↓

**Validation and Retest**

↓

**Risk Reassessment**

↓

**Operational Reporting**

↓

**Management Reporting**

↓

**Executive Decision**

↓

**Continuous Improvement**

---

# 165. Final Principle

The repository is not intended to demonstrate how many security documents can be created.

It is intended to demonstrate how security decisions remain traceable from business need to evidence-supported results.

The project artifact principle is:

> **Every important security requirement should have a reason, an accountable owner, an implementation path, evidence, and a way to determine whether it works.**

---

# 166. Related Artifacts

## Repository

- [[README]]
- [[INDEX-001 Artifact Index]]
- [[REG-006 Document Control Register]]
- [[REG-007 Cross-Reference Matrix]]
- [[GUIDE-003 Acronym & Terminology Guide]]

## Executive

- [[PLN-006 Enterprise Security Program Roadmap]]

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

## Reports and Dashboards

- [[RPT-006 Executive Security Summary]]
- [[RPT-007 Management Security Report]]
- [[RPT-008 Operational Security Report & Dashboard]]

## Learning Path

- [[GUIDE-001 GRC Learning Path]]

---

# 167. Revision History

| Version | Date     | Description                  | Approval |
| ------- | -------- | ---------------------------- | -------- |
| 1.0     | May 2013 | Initial Project Artifact Map | CEO      |