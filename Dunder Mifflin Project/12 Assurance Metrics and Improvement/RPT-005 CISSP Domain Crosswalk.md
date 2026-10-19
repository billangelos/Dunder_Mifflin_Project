# RPT-005 CISSP Domain Crosswalk

## Document Control

| Field | Value |
|---|---|
| Document ID | RPT-005 |
| Title | CISSP Domain Crosswalk |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Program Change |

---

# 1. Purpose

This report maps the Dunder Mifflin Enterprise Information Security & Risk Management Program to the eight domains of the Certified Information Systems Security Professional (CISSP) Common Body of Knowledge.

The purpose is to demonstrate how security concepts represented by the CISSP domains operate together within an enterprise security program.

---

# 2. CISSP Domains

The program addresses the following eight domains:

1. Security and Risk Management
2. Asset Security
3. Security Architecture and Engineering
4. Communication and Network Security
5. Identity and Access Management
6. Security Assessment and Testing
7. Security Operations
8. Software Development Security

---

# 3. Crosswalk Principle

The CISSP domains should not be treated as isolated security functions.

Enterprise security requires interaction among:

- Business objectives
- Assets
- Information
- Risk
- Governance
- Architecture
- Access
- Operations
- Assessment
- Incident response
- Recovery
- Development
- Continuous improvement

---

# 4. Program Lifecycle

The Dunder Mifflin program follows the general lifecycle:

**Business → Assets → Risks → Policies → Architecture → Controls → Operations → Testing → Incidents → Recovery → Improvement**

Each CISSP domain contributes to one or more portions of this lifecycle.

---

# 5. Enterprise Traceability

The program also maintains the traceability chain:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

The CISSP domains intersect throughout this chain.

---

# 6. Domain 1: Security and Risk Management

Security and Risk Management establishes the governance foundation for the enterprise security program.

Major concepts include:

- Governance
- Security policy
- Risk management
- Risk assessment
- Risk treatment
- Security roles and responsibilities
- Ethics
- Compliance
- Personnel security
- Security awareness
- Business Continuity planning
- Third-party risk
- Security program management

---

# 7. Domain 1: Enterprise Governance

Dunder Mifflin establishes security governance through:

- CEO executive authority
- CIO security-program responsibility
- Information Security and Risk Committee (ISRC)
- Defined risk ownership
- Policy ownership
- Control ownership
- Formal risk acceptance
- Management reporting
- Executive reporting

Primary artifacts include:

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-009 Security Governance Framework]]
- [[POL-001 Information Security Policy]]
- [[POL-005 Risk Management Policy]]

---

# 8. Domain 1: Risk Management

Risk management is implemented through:

- Enterprise risk identification
- Likelihood assessment
- Impact assessment
- Inherent risk
- Current residual risk
- Target residual risk
- Risk treatment
- Risk acceptance
- Risk reassessment

Primary artifacts include:

- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[POL-005 Risk Management Policy]]

---

# 9. Domain 1: Risk Formula

Dunder Mifflin uses:

**Risk Score = Likelihood × Impact**

Likelihood and Impact use integer values from 1 through 5.

---

# 10. Domain 1: Risk Levels

| Score | Risk Level |
|---:|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–16 | High |
| 17–25 | Critical |

---

# 11. Domain 1: Inherent Risk

Inherent risk represents exposure before considering credited controls.

Inherent risk remains important after controls are implemented because it helps identify the potential consequence of control failure.

---

# 12. Domain 1: Current Residual Risk

Current residual risk represents exposure after considering controls that actually exist and receive credit in the current assessment.

---

# 13. Domain 1: Target Residual Risk

Target residual risk represents predicted exposure after proposed treatments are implemented and validated.

Target residual risk does not receive current risk-reduction credit.

---

# 14. Domain 1: Risk Treatment

Risk treatment uses:

- Mitigate
- Transfer
- Avoid
- Accept

Primary artifact:

[[RTP-001 Enterprise Risk Treatment Plan]]

---

# 15. Domain 1: Risk Acceptance

Risk acceptance authority increases with risk severity.

| Risk Level | Acceptance Authority |
|---|---|
| Low | Risk Owner |
| Moderate | Risk Owner and Executive Management |
| High | CEO after ISRC review |
| Critical | CEO after ISRC review; exceptional use |

High accepted risks must be reassessed within 90 days.

Critical accepted risks must be reassessed within 30 days.

---

# 16. Domain 1: Security Policies

The security policy framework includes:

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

---

# 17. Domain 1: Security Awareness

Security awareness includes:

- Initial training within 5 business days
- Annual refresher training
- Annual knowledge assessment
- 80% required assessment threshold
- Monthly phishing simulations
- Corrective awareness activity

Primary artifact:

[[POL-006 Security Awareness & Training Policy]]

---

# 18. Domain 1: Personnel Security

Personnel security includes:

- Personnel lifecycle management
- Security responsibilities
- Confidentiality
- Access coordination
- Transfers
- Termination
- Company-property recovery
- Contractor personnel
- Key-person dependency
- Cross-training

Primary artifacts:

- [[PRO-006 Physical & Personnel Security Program]]
- [[PROC-017 Personnel Security Procedure]]

---

# 19. Domain 1: Third-Party Risk

Third-party security includes:

- Critical, Important, and Routine classification
- Risk-based due diligence
- Contractual security requirements
- Confidentiality
- Access restrictions
- Incident notification
- Recovery considerations
- Exit planning
- Periodic review

Primary artifact:

[[POL-008 Third-Party Security Policy]]

---

# 20. Domain 1: Business Continuity

Business Continuity connects security risk with organizational resilience.

Primary artifacts include:

- [[RPT-002 Business Impact Analysis]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]

---

# 21. Domain 1: Applied Risks

Domain 1 contributes to treatment of risks throughout the register, including:

- R001 Phishing / Credential Compromise
- R002 Business Email Compromise
- R003 Ransomware
- R009 Sensitive Information Theft / Extortion
- R010 Unauthorized / Excessive Access
- R011 Delayed Termination
- R012 Malicious Insider
- R018 Third-Party Technology Failure / Compromise
- R019 Infinity Contractor
- R026 Personnel Loss
- R029 Vendor Fraud
- R030 Sales Fraud
- R031 Payroll Fraud

---

# 22. Domain 2: Asset Security

Asset Security addresses identification, classification, ownership, handling, protection, retention, and appropriate disposition of information and other enterprise assets.

---

# 23. Domain 2: Asset Identification

Dunder Mifflin identifies:

- Business processes
- Information
- Applications
- Infrastructure
- Endpoints
- Mobile devices
- Physical assets
- Facilities
- Backup media
- Third-party dependencies

Primary artifact:

[[REG-001 Enterprise Asset Register]]

---

# 24. Domain 2: Ownership and Custody

Asset ownership and custody are treated as separate concepts.

An asset owner is accountable for business requirements and protection expectations.

A custodian may operate, store, maintain, or administer the asset without becoming the business owner.

---

# 25. Domain 2: Information Classification

Dunder Mifflin uses four information classifications:

1. Public
2. Internal
3. Confidential
4. Restricted

Primary artifacts:

- [[POL-004 Information Classification & Handling Policy]]
- [[STD-001 Information Classification Standard]]

---

# 26. Domain 2: Classification Principle

Protection requirements increase with information sensitivity.

Classification influences:

- Access
- Storage
- Transmission
- Sharing
- Physical protection
- Third-party handling
- Disposal

---

# 27. Domain 2: Backup Classification

Backups inherit the highest applicable classification of the information they contain.

---

# 28. Domain 2: Payment Information

Dunder Mifflin's payment processor stores Primary Account Number (PAN) data.

Dunder Mifflin retains:

- Payment token
- Card brand
- Last four digits
- Expiration information

The retained tokenized payment information is classified Confidential.

---

# 29. Domain 2: Business Impact Analysis

Asset importance is also evaluated through the Business Impact Analysis.

Primary artifact:

[[RPT-002 Business Impact Analysis]]

---

# 30. Domain 2: BIA Concepts

The BIA establishes:

- Business criticality
- Maximum Tolerable Downtime (MTD)
- Recovery Time Objective (RTO)
- Recovery Point Objective (RPO)

---

# 31. Domain 2: Physical Asset Protection

Physical asset protection includes:

- Facility access controls
- Restricted areas
- Warehouse high-value cages
- Backup-media protection
- Equipment accountability
- Company-property recovery

Primary artifacts:

- [[PRO-006 Physical & Personnel Security Program]]
- [[PROC-014 Facility Access Procedure]]
- [[PROC-016 Restricted Area Access Procedure]]
- [[PROC-017 Personnel Security Procedure]]

---

# 32. Domain 2: Applied Risks

Domain 2 supports treatment of:

- R009 Sensitive Information Theft / Extortion
- R014 Lost Device
- R024 Physical Access
- R027 Backup Failure
- R028 Data Corruption
- R032 Inventory Theft

---

# 33. Domain 3: Security Architecture and Engineering

Security Architecture and Engineering translates business and security requirements into technical and physical security design.

---

# 34. Domain 3: Architecture Program

Primary artifact:

[[PRO-002 Enterprise Security Architecture Program]]

The architecture program establishes principles for:

- Layered security
- Least privilege
- Segmentation
- Secure configuration
- Endpoint protection
- Server protection
- Authentication
- Recovery
- Physical protection

---

# 35. Domain 3: Defense in Depth

No single security control is expected to prevent every failure.

Dunder Mifflin uses layered safeguards across:

- People
- Process
- Technology
- Physical security
- Recovery

---

# 36. Domain 3: Endpoint Architecture

Endpoint controls include:

- Windows 7 managed endpoints
- Standard-user operation
- Managed commercial antivirus
- Screen locking
- Full-disk encryption on laptops
- Central management
- Mobile Device Management where applicable

Primary artifact:

[[STD-003 Endpoint Security Standard]]

---

# 37. Domain 3: Server Architecture

Server controls include:

- Windows Server 2012
- Restricted administrative access
- Central patch management
- Secure configuration
- Configuration backup
- Change management
- Logging

Primary artifact:

[[STD-004 Server Security Standard]]

---

# 38. Domain 3: Authentication Architecture

Authentication architecture includes:

- Individual accountability
- Separate privileged credentials
- Restricted standing administrative privilege
- Smart-card multifactor authentication where supported as a proposed treatment
- Emergency-access controls

Primary artifact:

[[STD-005 Authentication & Account Security Standard]]

---

# 39. Domain 3: Secure Configuration

Configuration security includes:

- Approved baselines
- Controlled change
- Testing
- Verification
- Rollback
- Configuration backup
- Exception handling

Primary artifact:

[[STD-006 Secure Configuration Standard]]

---

# 40. Domain 3: Physical and Environmental Engineering

Physical and environmental safeguards include:

- Fire protection
- Water-risk controls
- Utility protection
- HVAC considerations
- Uninterruptible Power Supply protection
- Restricted areas
- Off-site backups

Primary artifacts:

- [[POL-011 Physical & Environmental Security Policy]]
- [[PRO-006 Physical & Personnel Security Program]]

---

# 41. Domain 3: Recovery Architecture

Recovery architecture includes:

- Cloud-hosted business systems
- Encrypted off-site backups
- Automated backups
- Recovery documentation
- Manual continuity
- Cloud exit planning
- Geographically distributed facilities

Primary artifacts:

- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]
- [[PROC-012 Backup & Recovery Procedure]]

---

# 42. Domain 3: Applied Risks

Domain 3 supports treatment of:

- R003 Ransomware
- R004 Malware
- R005 Password / Authentication
- R006 Infinity Compromise
- R007 Internet Infrastructure
- R013 Administrative / Configuration Error
- R014 Lost Device
- R016 Cloud Outage
- R021 Fire
- R022 Water
- R023 Utility / Power / HVAC
- R027 Backup Failure
- R028 Data Corruption

---

# 43. Domain 4: Communication and Network Security

Communication and Network Security addresses secure network design, connectivity, transmission, remote access, network protection, and communication resilience.

---

# 44. Domain 4: Network Standard

Primary artifact:

[[STD-002 Network Security Standard]]

---

# 45. Domain 4: Site Network Model

The normal site architecture includes:

**Internet Service Provider → Firewall / Router → Switches → Wired Endpoints / Printers / Warehouse Systems / Phones**

---

# 46. Domain 4: Inbound Protection

Unsolicited inbound Internet traffic is denied unless specifically authorized.

Internal and administrative services must not be unnecessarily exposed to the public Internet.

---

# 47. Domain 4: Wireless Architecture

Dunder Mifflin does not operate a corporate wireless network.

The only authorized wireless access point is:

- Located in the Scranton Headquarters lobby
- Internet-only
- Intended for guest use

---

# 48. Domain 4: Rogue Wireless Detection

Network discovery and rogue wireless assessment are performed every six months.

Unexpected wireless infrastructure requires investigation.

---

# 49. Domain 4: Remote Access

Virtual Private Network (VPN) connectivity is used for authorized remote access from external or untrusted networks to nonpublic cloud resources where required.

Infinity's public customer-facing functionality is accessed directly through its public interface.

---

# 50. Domain 4: Contractor Network Access

Infinity contractors do not receive general contractor VPN access.

Privileged production or administrative work is performed through approved controlled arrangements.

---

# 51. Domain 4: Internet Resilience

Dunder Mifflin distinguishes:

- Facility Internet outage
- Cloud-service outage
- Regional telecommunications disruption

These conditions are represented by separate risks.

---

# 52. Domain 4: Cellular Continuity

Company-issued cellular capability provides a secondary communication or Internet path where applicable.

It does not guarantee full replacement of all wired business functions.

---

# 53. Domain 4: Applied Risks

Domain 4 supports treatment of:

- R001 Phishing / Credential Compromise
- R006 Infinity Compromise
- R007 Internet Infrastructure
- R008 Denial of Service
- R016 Cloud Outage
- R017 ISP Outage
- R018 Third-Party Technology Failure / Compromise
- R035 Regional Disaster

---

# 54. Domain 5: Identity and Access Management

Identity and Access Management (IAM) controls who may access enterprise resources, what access they receive, how that access is authenticated, and how access changes throughout the personnel lifecycle.

---

# 55. Domain 5: IAM Program

Primary artifact:

[[PRO-003 Identity and Access Management Program]]

---

# 56. Domain 5: Identity Lifecycle

The personnel access lifecycle includes:

**Join → Authorize → Work → Review → Transfer → Terminate**

Supporting artifacts include:

- [[PROC-001 Joiner-Mover-Leaver Procedure]]
- [[PROC-003 Access Review Procedure]]

---

# 57. Domain 5: Authoritative Source

Human Resources is the authoritative source for employee status.

Access-management processes depend on timely personnel-status information.

---

# 58. Domain 5: Least Privilege

Users receive only access required for authorized business responsibilities.

Access is not granted merely because it may be convenient.

---

# 59. Domain 5: Transfers

Transfers require:

1. Removal of prior business permissions that are no longer required.
2. Authorization of access required for the new role.

Access is not automatically inherited from the previous position.

---

# 60. Domain 5: Termination

Termination requires prompt coordination among:

- Human Resources
- Management
- Information Technology
- Facility or physical-access personnel

Logical access must not remain active merely because company property has not yet been returned.

---

# 61. Domain 5: Privileged Access

Privileged access controls include:

- Separate privileged credentials
- Individual accountability
- Restricted standing Domain Administrator membership
- Dedicated administrative workstations
- Quarterly privileged-access review
- Controlled emergency access

Primary artifact:

[[PROC-002 Privileged Access Procedure]]

---

# 62. Domain 5: Ordinary Access Review

Ordinary user access is reviewed annually.

Primary artifact:

[[PROC-003 Access Review Procedure]]

---

# 63. Domain 5: Dormant Accounts

Dormant accounts are:

- Investigated after 30 days
- Disabled after 60 days unless documented justification supports continued access

---

# 64. Domain 5: Contractor Access

Contractor access requires:

- Sponsor
- Business justification
- Approved duration
- Least privilege
- Confidentiality where applicable
- Periodic review
- Prompt removal

Primary artifact:

[[PROC-004 Contractor Access Procedure]]

---

# 65. Domain 5: Emergency Access

Emergency access must be:

- Controlled
- Limited
- Documented
- Reviewed after use

Primary artifact:

[[PROC-005 Emergency Access Procedure]]

---

# 66. Domain 5: Shared Warehouse Accounts

Shared Windows workstation accounts may remain where operationally justified.

Significant Warehouse Management System activity must use individual authentication and accountability.

---

# 67. Domain 5: Applied Risks

Domain 5 directly supports treatment of:

- R001 Phishing / Credential Compromise
- R002 Business Email Compromise
- R005 Password / Authentication
- R009 Sensitive Information Theft / Extortion
- R010 Unauthorized / Excessive Access
- R011 Delayed Termination
- R012 Malicious Insider
- R015 Shared Warehouse Accounts
- R019 Infinity Contractor

---

# 68. Domain 6: Security Assessment and Testing

Security Assessment and Testing determines whether controls exist, operate as intended, and produce sufficient evidence of effectiveness.

---

# 69. Domain 6: Assurance Program

Primary artifact:

[[PRO-008 Security Assurance & Continuous Improvement Program]]

---

# 70. Domain 6: Control Inventory

Enterprise controls are maintained in:

[[REG-003 Enterprise Security Control Inventory]]

The inventory records:

- Control objective
- Owner
- Related requirement
- Related risk
- Implementation status
- Effectiveness
- Evidence
- Assessment method
- Assessment frequency

---

# 71. Domain 6: Implementation and Effectiveness

Implementation and effectiveness are separate.

**Implemented does not mean Effective.**

---

# 72. Domain 6: Effectiveness Categories

Where supported by sufficient evidence:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

may be used.

Where sufficient assessment has not occurred:

**Not Yet Assessed**

should be used as appropriate.

---

# 73. Domain 6: Assessment Methods

Assessment methods include:

1. Inspection
2. Observation
3. Independent Performance
4. Technical Testing
5. Sampling
6. Exercises
7. Reconciliation

---

# 74. Domain 6: Independent Performance

Independent Performance means an assessor independently performs an authorized procedure to determine whether the expected result occurs.

This method must not create unnecessary operational, security, data-integrity, or safety risk.

---

# 75. Domain 6: Annual Assurance Planning

Primary artifact:

[[PLN-005 Annual Assurance Plan]]

The annual plan determines:

- What should be assessed
- Why it should be assessed
- When it should be assessed
- Who should perform the assessment
- Required independence
- Assessment methods

---

# 76. Domain 6: Assessment Work Planning

Primary artifact:

[[TMP-001 Assessment Work Plan Template]]

The Assessment Work Plan converts scheduled assurance activity into specific testing.

---

# 77. Domain 6: Assessment Work Plan

An Assessment Work Plan identifies:

- Objective
- Scope
- Requirements
- Controls
- Risks
- Assessor
- Independence
- Methods
- Evidence
- Sampling
- Test procedures
- Expected results
- Reporting

---

# 78. Domain 6: Vulnerability Management

Primary artifacts:

- [[PRO-004 Vulnerability Management Program]]
- [[PROC-006 Vulnerability Assessment Procedure]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]

Internal vulnerability assessments are performed monthly.

---

# 79. Domain 6: Penetration Testing

Primary artifact:

[[STD-007 Penetration Testing Standard]]

Enterprise penetration testing occurs at least every two years.

Infinity receives annual application-focused penetration testing.

---

# 80. Domain 6: Findings

Material assessment deficiencies requiring corrective action are tracked in:

[[REG-004 Finding & Corrective Action Register]]

---

# 81. Domain 6: Finding Lifecycle

The lifecycle is:

**Assessment → Finding → Corrective Action → Validation → Retest → Closure → Risk Reassessment**

---

# 82. Domain 6: Evidence

Assessment conclusions must be supported by evidence.

Evidence may include:

- Configuration
- Logs
- Access records
- Reports
- Test results
- Change records
- Recovery records
- Contracts
- Training records
- Physical observations
- Transaction records

---

# 83. Domain 6: Evidence Integrity

Evidence must not be:

- Fabricated
- Backdated
- Altered to hide failure
- Invented
- Misrepresented

---

# 84. Domain 6: Recovery Testing

Representative restore testing occurs quarterly.

Critical recovery capability receives meaningful testing annually.

Primary artifacts:

- [[PROC-012 Backup & Recovery Procedure]]
- [[TMP-003 Recovery Test Template]]

---

# 85. Domain 6: Applied Risks

Domain 6 contributes to every enterprise risk because control effectiveness cannot be established without evidence.

It has especially strong relationships with:

- R003 Ransomware
- R005 Password / Authentication
- R006 Infinity Compromise
- R007 Internet Infrastructure
- R010 Unauthorized / Excessive Access
- R013 Administrative / Configuration Error
- R018 Third-Party Technology Failure / Compromise
- R027 Backup Failure

---

# 86. Domain 7: Security Operations

Security Operations addresses the day-to-day activities required to operate, monitor, protect, respond, recover, and maintain enterprise security.

---

# 87. Domain 7: Security Operations Program

Primary artifact:

[[PRO-005 Security Operations Program]]

---

# 88. Domain 7: Operational Security

Operational security includes:

- Security monitoring
- Malware response
- Event escalation
- Evidence handling
- Vulnerability operations
- Backup operations
- Recovery
- Change management
- Physical security
- Incident response

---

# 89. Domain 7: Security Monitoring

Primary artifact:

[[PROC-008 Security Monitoring Procedure]]

Dunder Mifflin does not operate a 24-hour Security Operations Center.

Monitoring and escalation are performed using available personnel and an after-hours response process.

---

# 90. Domain 7: Malware Response

Primary artifact:

[[PROC-009 Malware Response Procedure]]

Malware response includes:

- Identification
- Isolation
- Investigation
- Containment
- Removal
- Recovery
- Escalation where required

---

# 91. Domain 7: Security Event Escalation

Primary artifact:

[[PROC-010 Security Event Escalation Procedure]]

Security events are evaluated to determine whether they require:

- Routine operational handling
- Investigation
- Incident declaration
- Management escalation
- Executive escalation

---

# 92. Domain 7: Incident Response

Primary artifacts:

- [[POL-009 Incident Response Policy]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[PLN-001 Incident Response Plan]]

---

# 93. Domain 7: Incident Playbooks

Scenario-specific playbooks include:

- [[PBK-001 Phishing & Credential Compromise Playbook]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-004 Data Exposure Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]

---

# 94. Domain 7: Evidence Handling

Primary artifact:

[[PROC-011 Evidence Handling Procedure]]

Evidence handling addresses:

- Identification
- Collection
- Protection
- Documentation
- Custody
- Integrity
- Restricted access

SHA-256 hashing is used where practical and appropriate for collected digital evidence.

---

# 95. Domain 7: Change Management

Primary artifact:

[[POL-007 Change & Configuration Management Policy]]

Change management includes:

- Authorization
- Testing
- Rollback
- Verification
- Documentation
- Emergency change review

---

# 96. Domain 7: Backup Operations

Primary artifact:

[[PROC-012 Backup & Recovery Procedure]]

Backup protection includes:

- Automated backups
- Cloud backups
- Encrypted external drives
- Off-site storage
- Backup-job monitoring
- Restore testing
- Recovery documentation

---

# 97. Domain 7: External Backup Rotation

Dunder Mifflin uses:

- 7 facilities
- 3 encrypted external drives per facility
- 21 encrypted drives total

The off-site provider normally holds the two latest weekly generations for each facility, totaling 14 drives.

---

# 98. Domain 7: Manual Continuity

Primary artifact:

[[PROC-013 Manual Processing Procedure]]

The manual-processing lifecycle is:

**Collect → Review → Enter → Reconcile → Verify**

---

# 99. Domain 7: Business Continuity and Disaster Recovery

Primary artifacts:

- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]

---

# 100. Domain 7: Recovery Priority

Recovery priority is:

1. Human life and safety
2. Critical functions
3. High functions
4. Moderate functions
5. Low functions

---

# 101. Domain 7: Physical Security

Operational physical security includes:

- Facility access
- Visitor management
- Restricted areas
- Warehouse cages
- Personnel access changes
- Environmental protection

Primary artifacts:

- [[PROC-014 Facility Access Procedure]]
- [[PROC-015 Visitor & Vendor Access Procedure]]
- [[PROC-016 Restricted Area Access Procedure]]
- [[PROC-017 Personnel Security Procedure]]

---

# 102. Domain 7: Operational Checklist

Recurring operational activity is supported by:

[[TMP-002 Operational Security Checklist]]

---

# 103. Domain 7: Applied Risks

Domain 7 supports treatment of risks throughout the register, particularly:

- R001 Phishing / Credential Compromise
- R002 Business Email Compromise
- R003 Ransomware
- R004 Malware
- R007 Internet Infrastructure
- R008 Denial of Service
- R011 Delayed Termination
- R013 Administrative / Configuration Error
- R016 Cloud Outage
- R017 ISP Outage
- R021 Fire
- R022 Water
- R023 Utility / Power / HVAC
- R024 Physical Access
- R027 Backup Failure
- R028 Data Corruption
- R033 Manual Outage Error
- R034 Loss of Headquarters
- R035 Regional Disaster

---

# 104. Domain 8: Software Development Security

Software Development Security addresses secure design, development, testing, release, maintenance, and protection of software throughout its lifecycle.

For Dunder Mifflin, the primary application requiring this discipline is Infinity.

---

# 105. Domain 8: Secure Development Program

Primary artifact:

[[PRO-007 Secure Software Development Lifecycle Program]]

---

# 106. Domain 8: Secure Development Policy

Primary artifact:

[[POL-012 Application & Secure Development Policy]]

---

# 107. Domain 8: Infinity Security Standard

Primary artifact:

[[STD-009 Infinity Security Standard]]

---

# 108. Domain 8: Company Ownership

Dunder Mifflin owns applicable Infinity:

- Application
- Source code
- Repository
- Intellectual property
- Data
- Documentation
- Work product
- Backups

Contractor access does not transfer ownership.

---

# 109. Domain 8: Development Lifecycle

The secure development lifecycle includes:

**Requirement → Design → Develop → Review → Test → Approve → Release → Verify → Maintain**

---

# 110. Domain 8: Environment Separation

Infinity maintains logical separation among:

- Development
- Test
- Production

Production access is more restricted than development access.

---

# 111. Domain 8: Threat Modeling

Infinity uses lightweight threat modeling during material design or architectural change.

Threat modeling considers applicable concerns such as:

- Spoofing
- Tampering
- Repudiation
- Information disclosure
- Denial of service
- Elevation of privilege

---

# 112. Domain 8: Secure Design

Secure design considers:

- Authentication
- Authorization
- Input validation
- Session management
- Data protection
- Error handling
- Logging
- Least privilege
- Dependency security
- Administrative interfaces

---

# 113. Domain 8: Code Review

Material changes receive appropriate code review before production release.

---

# 114. Domain 8: Security Testing

Security testing is proportional to:

- Change significance
- Application exposure
- Data sensitivity
- Security impact
- Prior findings

---

# 115. Domain 8: Change and Release

Primary artifact:

[[PROC-018 Secure Change & Release Procedure]]

The process includes:

- Change request
- Risk evaluation
- Development
- Review
- Testing
- Approval
- Release
- Verification
- Rollback where required

---

# 116. Domain 8: Application Assessment

Primary artifact:

[[PROC-019 Application Security Assessment Procedure]]

Infinity receives an annual security assessment.

---

# 117. Domain 8: Application Penetration Testing

Infinity receives annual application-focused penetration testing.

The assessment chain is:

**Penetration Test → Finding → Remediation → Retest → Control Effectiveness → R006 Risk Reassessment**

---

# 118. Domain 8: Contractor Development Access

Primary artifact:

[[PROC-020 Contractor Development Access Procedure]]

Contractor development access requires:

- Sponsor
- Named personnel
- Business need
- Approved duration
- Least privilege
- Confidentiality
- Controlled production access
- Prompt revocation

---

# 119. Domain 8: Contractor Production Access

Infinity contractor privileged production or administrative work is performed through approved controlled arrangements.

General contractor VPN access is not provided.

---

# 120. Domain 8: Contractor Personnel Notice

Expected contractor personnel should be identified at least one business day before scheduled arrival where practical.

Emergency exceptions may be approved when necessary.

---

# 121. Domain 8: Documentation

Infinity documentation must support:

- Operation
- Maintenance
- Security
- Recovery
- Change
- Troubleshooting
- Knowledge transfer

---

# 122. Domain 8: Transferability

Dunder Mifflin must maintain sufficient ownership, documentation, access, and knowledge to transfer Infinity support to another qualified party if necessary.

Primary artifact:

[[RPT-004 Infinity Transferability Review]]

---

# 123. Domain 8: Applied Risks

Domain 8 directly supports treatment of:

- R006 Infinity Compromise
- R013 Administrative / Configuration Error
- R018 Third-Party Technology Failure / Compromise
- R019 Infinity Contractor
- R026 Personnel Loss
- R028 Data Corruption

---

# 124. Cross-Domain Example: Phishing

R001 Phishing / Credential Compromise demonstrates cross-domain security.

| CISSP Domain | Contribution |
|---|---|
| Domain 1 | Risk assessment, policy, awareness |
| Domain 2 | Protection of sensitive information |
| Domain 3 | Endpoint and authentication safeguards |
| Domain 4 | Email and network protections |
| Domain 5 | Authentication and account controls |
| Domain 6 | Control assessment and phishing simulation |
| Domain 7 | Monitoring, escalation, incident response |
| Domain 8 | Relevant application authentication safeguards |

---

# 125. Cross-Domain Example: Ransomware

R003 Ransomware involves:

| CISSP Domain | Contribution |
|---|---|
| Domain 1 | Risk treatment and awareness |
| Domain 2 | Data classification and asset identification |
| Domain 3 | Endpoint, server, configuration, and recovery architecture |
| Domain 4 | Network protection |
| Domain 5 | Least privilege and privileged-access controls |
| Domain 6 | Vulnerability assessment and recovery testing |
| Domain 7 | Malware response, incident response, backup, recovery |
| Domain 8 | Application-security controls where applicable |

---

# 126. Cross-Domain Example: Infinity

R006 Infinity Compromise involves:

| CISSP Domain | Contribution |
|---|---|
| Domain 1 | Governance, risk, third-party security |
| Domain 2 | Application and information ownership |
| Domain 3 | Secure architecture and engineering |
| Domain 4 | Network exposure and communications |
| Domain 5 | Application and administrative access |
| Domain 6 | Assessment, penetration testing, findings, retesting |
| Domain 7 | Monitoring, incident response, recovery |
| Domain 8 | Secure development lifecycle |

---

# 127. Cross-Domain Example: Backup Failure

R027 Backup Failure involves:

| CISSP Domain | Contribution |
|---|---|
| Domain 1 | Risk management and continuity governance |
| Domain 2 | Information classification and asset protection |
| Domain 3 | Recovery architecture |
| Domain 4 | Connectivity required for cloud recovery |
| Domain 5 | Backup administrative access |
| Domain 6 | Restore and recovery testing |
| Domain 7 | Backup operations and disaster recovery |
| Domain 8 | Application recovery requirements |

---

# 128. Cross-Domain Example: Malicious Insider

R012 Malicious Insider involves:

| CISSP Domain | Contribution |
|---|---|
| Domain 1 | Personnel security, policy, risk management |
| Domain 2 | Information protection |
| Domain 3 | Security architecture |
| Domain 4 | Network restrictions |
| Domain 5 | Least privilege and accountability |
| Domain 6 | Access review and control assessment |
| Domain 7 | Monitoring, investigation, incident response |
| Domain 8 | Development and production-access controls |

---

# 129. Cross-Domain Example: Regional Disaster

R035 Regional Disaster involves:

| CISSP Domain | Contribution |
|---|---|
| Domain 1 | Business Continuity and risk management |
| Domain 2 | Asset and information identification |
| Domain 3 | Resilient architecture |
| Domain 4 | Alternate communications |
| Domain 5 | Emergency and alternate access |
| Domain 6 | Recovery testing and exercises |
| Domain 7 | Continuity, recovery, and operations |
| Domain 8 | Application recovery and documentation |

---

# 130. CISSP Domain Coverage Summary

| Domain | Primary Program Area | Representative Artifacts |
|---|---|---|
| 1. Security and Risk Management | Governance, risk, policy, awareness, continuity | PRO-001, PRO-009, RPT-003, REG-002, RTP-001, POL-001 through POL-012 |
| 2. Asset Security | Assets, classification, handling, BIA | REG-001, STD-001, POL-004, RPT-002 |
| 3. Security Architecture and Engineering | Architecture, endpoint, server, authentication, configuration, physical protection | PRO-002, STD-003, STD-004, STD-005, STD-006, PRO-006 |
| 4. Communication and Network Security | Network architecture, Internet, VPN, wireless, resilience | STD-002, PRO-002, PROC-008 |
| 5. Identity and Access Management | Identity lifecycle, access, privileged access, contractors, emergency access | PRO-003, PROC-001 through PROC-005 |
| 6. Security Assessment and Testing | Assurance, vulnerability management, testing, findings, evidence | PRO-004, PRO-008, STD-007, PLN-005, TMP-001, REG-003, REG-004 |
| 7. Security Operations | Monitoring, incident response, malware, evidence, backup, recovery, physical operations | PRO-005, PLN-001 through PLN-004, PROC-008 through PROC-017, PBK-001 through PBK-005 |
| 8. Software Development Security | Infinity SDLC, application security, release, contractor development | PRO-007, POL-012, STD-009, PROC-018 through PROC-020, RPT-004 |

---

# 131. Domain Interaction

No major enterprise security risk belongs exclusively to one CISSP domain.

A single material risk commonly requires:

- Governance
- Technical controls
- Access controls
- Operational procedures
- Assessment
- Incident response
- Recovery

---

# 132. Governance Before Technology

The program demonstrates that security begins with understanding:

- The business
- Assets
- Dependencies
- Information
- Business impact
- Risk

Technology controls are selected after those requirements are understood.

---

# 133. Controls Before Testing

Assessment cannot be meaningful without knowing:

- The requirement
- The control objective
- The control owner
- Expected operation

Testing is not an isolated activity.

---

# 134. Evidence Before Assurance

A control cannot be considered effective solely because:

- A policy requires it.
- Management says it exists.
- Technology was purchased.
- A project was completed.

Effectiveness requires sufficient evidence.

---

# 135. Findings Before Improvement

Assessment identifies whether control deficiencies exist.

Material deficiencies become findings.

Findings drive:

- Corrective action
- Validation
- Retesting
- Risk reassessment
- Program improvement

---

# 136. Recovery as Security

Recovery is not separate from security.

Security includes maintaining the ability to:

- Restore information
- Restore systems
- Continue critical business functions
- Operate manually when necessary
- Recover from destructive events

---

# 137. Human Factors

Human behavior affects every CISSP domain.

Examples include:

- Phishing susceptibility
- Administrative mistakes
- Malicious insiders
- Access approvals
- Secure development
- Incident escalation
- Manual processing
- Physical access

---

# 138. Management Responsibility

Security is not solely an Information Technology responsibility.

The program assigns responsibility across:

- CEO
- CIO
- COO
- CFO
- Human Resources
- Legal / Compliance
- Business managers
- Information Technology
- Information Security
- Employees
- Contractors
- Third parties

---

# 139. Security Program Maturity

Program maturity develops through:

**Understand → Govern → Design → Implement → Operate → Assess → Correct → Reassess → Improve**

---

# 140. Continuous Improvement

Security assurance feeds continuous improvement through:

**Control → Evidence → Assessment → Finding → Corrective Action → Validation → Retest → Risk Reassessment**

Primary artifact:

[[PRO-008 Security Assurance & Continuous Improvement Program]]

---

# 141. Metrics

Security metrics provide management with evidence concerning:

- Control performance
- Operational performance
- Findings
- Remediation
- Risk indicators
- Assurance coverage

Primary artifact:

[[REG-005 Security Metrics Catalog]]

---

# 142. Reporting Levels

Security information is communicated at three levels:

### Executive

Focus:

- Decisions
- Enterprise risk
- Significant exposure
- Resource requirements

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

---

# 143. Reporting Artifacts

The three reporting levels are represented by:

- [[RPT-006 Executive Security Summary]]
- [[RPT-007 Management Security Report]]
- [[RPT-008 Operational Security Report & Dashboard]]

---

# 144. Reporting Chain

The reporting model is:

**Technical Evidence → Operational Exception → Management Impact → Enterprise Risk → Executive Decision**

---

# 145. CISSP Knowledge Application

This project applies CISSP knowledge through practical enterprise activities rather than presenting the domains only as theoretical concepts.

Examples include:

- Building a Business Impact Analysis before establishing recovery requirements
- Distinguishing inherent, current residual, and target residual risk
- Designing risk treatments
- Creating policy and standards
- Designing security architecture
- Establishing Identity and Access Management processes
- Defining vulnerability-management processes
- Creating incident-response procedures
- Designing Business Continuity and Disaster Recovery
- Establishing secure development controls
- Building an assurance program
- Creating findings and corrective-action processes
- Establishing management reporting

---

# 146. Crosswalk Limitation

This crosswalk demonstrates alignment with CISSP knowledge domains.

It does not represent:

- Certification by ISC2
- Independent audit
- Regulatory certification
- Formal compliance attestation
- Proof that every control is effective

---

# 147. Portfolio Purpose

The crosswalk demonstrates the ability to connect security theory with enterprise security-program design.

The portfolio is intended to demonstrate understanding of:

- Why a control exists
- Which risk it addresses
- Which requirement drives it
- How it operates
- What evidence it produces
- How it is tested
- How failure becomes a finding
- How remediation affects risk

---

# 148. Complete Program Chain

The overall project can be understood as:

**Business**

↓

**Assets and Dependencies**

↓

**Classification and Business Impact**

↓

**Risk**

↓

**Governance and Policy**

↓

**Security Architecture**

↓

**Controls and Procedures**

↓

**Operations**

↓

**Assessment and Evidence**

↓

**Findings and Corrective Action**

↓

**Incident Response and Recovery**

↓

**Risk Reassessment**

↓

**Continuous Improvement**

---

# 149. Related Artifacts

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

## Reports

- [[RPT-006 Executive Security Summary]]
- [[RPT-007 Management Security Report]]
- [[RPT-008 Operational Security Report & Dashboard]]

---

# 150. Conclusion

The eight CISSP domains collectively represent an integrated body of security knowledge.

The Dunder Mifflin Enterprise Information Security & Risk Management Program demonstrates that effective enterprise security depends on connecting those domains rather than implementing them independently.

The program begins with the business and its assets, identifies risk, establishes governance, designs controls, operates those controls, evaluates evidence, identifies deficiencies, corrects weaknesses, responds to incidents, restores business capability, reassesses risk, and continually improves.

The central principle is:

> **Security exists to support the business by managing risk to an acceptable level while protecting people, information, systems, operations, and organizational resilience.**

---

# 151. Revision History

| Version | Date     | Description                    | Approval |
| ------- | -------- | ------------------------------ | -------- |
| 1.0     | May 2013 | Initial CISSP Domain Crosswalk | CEO      |