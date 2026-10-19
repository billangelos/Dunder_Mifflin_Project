# RPT-007 Management Security Report

## Document Control

| Field | Value |
|---|---|
| Document ID | RPT-007 |
| Title | Management Security Report |
| Version | 1.0 |
| Classification | Confidential |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Monthly and Following Material Risk or Security Change |

---

# 1. Purpose

This report provides management with a structured view of Dunder Mifflin's information security and risk program.

It is intended to support:

- Management accountability
- Risk-treatment execution
- Control oversight
- Finding remediation
- Operational prioritization
- Resource planning
- Cross-functional coordination
- Escalation to executive leadership

This report provides more detail than the Executive Security Summary while avoiding unnecessary technical detail maintained in operational records.

---

# 2. Intended Audience

Primary readers include:

- CIO
- IT & Information Security Manager
- Relevant business managers
- Risk owners
- Control owners
- Information Security and Risk Committee members

Other managers may receive applicable portions based on their responsibilities.

---

# 3. Management Reporting Objective

Management reporting answers five primary questions:

1. What risks require management attention?
2. What security treatments are being performed?
3. Are responsible owners completing required work?
4. Are controls producing the expected results?
5. What requires escalation, correction, or additional resources?

---

# 4. Reporting Levels

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

This report represents the Management level.

---

# 5. Reporting Chain

Security information should move through:

**Technical Evidence → Operational Exception → Management Impact → Enterprise Risk → Executive Decision**

Management provides the connection between operational security activity and enterprise risk decisions.

---

# 6. Reporting Integrity

Management reporting must reflect available evidence accurately.

Do not:

- Fabricate results.
- Backdate activity.
- Report planned work as completed.
- Report implemented controls as effective without sufficient validation.
- Hide failed tests.
- Remove unfavorable findings from reporting.
- Present unavailable measurements as zero.
- Alter historical risk ratings to make current performance appear stronger.

---

# 7. Current Enterprise Risk Profile

The enterprise risk assessment contains 35 material risks.

Current residual risk includes High, Moderate, and Low risks.

No Critical current residual risks are identified.

Management attention should remain focused on the High current residual risks while continuing appropriate treatment and monitoring of Moderate and Low risks.

---

# 8. Highest Current Residual Risks

| Risk ID | Risk | Inherent | Current Residual | Target Residual |
|---|---|---:|---:|---:|
| R001 | Phishing / Credential Compromise | 20 Critical | 12 High | 6 Moderate |
| R003 | Ransomware | 25 Critical | 12 High | 6 Moderate |
| R004 | Malware | 20 Critical | 12 High | 6 Moderate |
| R005 | Password / Authentication | 16 High | 12 High | 4 Low |
| R006 | Infinity Compromise | 16 High | 12 High | 8 Moderate |
| R007 | Internet Infrastructure | 16 High | 12 High | 8 Moderate |
| R009 | Sensitive Information Theft / Extortion | 16 High | 12 High | 4 Low |
| R010 | Unauthorized / Excessive Access | 16 High | 12 High | 4 Low |
| R012 | Malicious Insider | 15 High | 10 High | 5 Moderate |
| R013 | Administrative / Configuration Error | 16 High | 12 High | 6 Moderate |
| R027 | Backup Failure | 20 Critical | 12 High | 5 Moderate |

---

# 9. Management Risk Priorities

Management should prioritize coordinated treatment across:

1. Identity and Access Management
2. Phishing and email security
3. Endpoint and malware protection
4. Backup and recovery
5. Infinity security
6. Vulnerability management
7. Configuration management
8. Third-party security
9. Incident response
10. Business Continuity and Disaster Recovery
11. Security assurance

---

# 10. Inherent Risk

Inherent risk remains relevant even after controls reduce current exposure.

Risks with severe inherent exposure may require continued management attention because control failure could restore a significant portion of the original exposure.

Examples include:

- R001 Phishing / Credential Compromise: 20 Critical inherent
- R003 Ransomware: 25 Critical inherent
- R004 Malware: 20 Critical inherent
- R027 Backup Failure: 20 Critical inherent

---

# 11. Current Residual Risk

Current residual risk represents exposure after considering controls that currently exist and receive credit.

Management must not reduce current residual risk merely because additional controls are planned or being implemented.

---

# 12. Target Residual Risk

Target residual risk represents predicted exposure following successful treatment.

Target residual risk becomes relevant to the current risk position only after:

1. Treatment implementation
2. Evidence generation
3. Validation
4. Risk reassessment

---

# 13. Risk Treatment Lifecycle

Risk treatments use:

**Planned → Approved → Implementing → Implemented → Validation Pending → Validated**

**Corrective Action Required** may be used when validation identifies a deficiency.

Primary artifact:

[[RTP-001 Enterprise Risk Treatment Plan]]

---

# 14. Management Treatment Review

Management should review treatment activity for:

- Assigned owner
- Approved scope
- Dependencies
- Target completion
- Current lifecycle status
- Evidence requirements
- Validation requirements
- Delays
- Resource constraints
- Material exceptions

---

# 15. Treatment Status

Management should maintain current treatment status using the Enterprise Risk Treatment Plan.

| Risk ID | Treatment Owner | Current Status | Target Completion | Validation Required | Management Attention |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

This table is populated from current treatment records when the report is issued.

No treatment status is assumed merely because a control appears in program documentation.

---

# 16. Treatment Horizons

Treatment planning uses:

| Horizon | Timeframe |
|---|---|
| Immediate | 0–90 days |
| Near | 3–6 months |
| Medium | 6–12 months |
| Ongoing | Continuing activity |

These horizons support prioritization and do not by themselves establish completion.

---

# 17. Identity and Access Management

Identity and Access Management is a major management priority because identity controls influence multiple High risks.

Primary artifacts include:

- [[POL-003 Access Control Policy]]
- [[PRO-003 Identity and Access Management Program]]
- [[STD-005 Authentication & Account Security Standard]]
- [[PROC-001 Joiner-Mover-Leaver Procedure]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-003 Access Review Procedure]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]

---

# 18. IAM Management Priorities

Management should track:

- Smart-card multifactor authentication implementation where supported
- Individual accountability
- Separate privileged credentials
- Standing Domain Administrator restriction
- Dedicated administrative workstations
- Annual ordinary-user access review
- Quarterly privileged-access review
- Dormant-account management
- Contractor-access duration
- Emergency-access control
- Prompt termination
- Transfer reauthorization
- Individual authentication for significant Warehouse Management System activity

---

# 19. IAM Risk Impact

Identity improvements support treatment of:

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

# 20. IAM Expected Risk Reduction

Examples include:

### R005 Password / Authentication

**12 High → 4 Low**

### R010 Unauthorized / Excessive Access

**12 High → 4 Low**

These remain target values until treatment effectiveness is validated.

---

# 21. Access Review

Management should verify completion of:

- Annual ordinary-user access review
- Quarterly privileged-access review

Review completion alone is not sufficient if identified inappropriate access remains unresolved.

---

# 22. Termination Control

Human Resources is the authoritative source for employee status.

Management should review exceptions involving:

- Delayed notification
- Delayed logical-access disablement
- Unreturned access cards
- Unreturned keys
- Unreturned smart cards
- Unreturned company equipment
- Contractor access remaining active after authorized need

Unreturned company property must not delay required access disablement.

---

# 23. Phishing and Email Security

Management should track treatment of R001 Phishing / Credential Compromise through:

- Improved email filtering
- Anti-phishing protection
- Suspicious-link protection
- Malicious-attachment protection
- Spoofing protection
- Security awareness
- Monthly phishing simulation
- Stronger authentication
- Incident-response readiness

---

# 24. Phishing Management Measures

Relevant management measures may include:

- Phishing simulation completion
- Simulation failure rate
- Repeat failure
- Reported suspicious messages
- Credential-compromise incidents
- Corrective awareness completion
- Email-security exceptions

Metrics should be interpreted as indicators rather than as complete measures of risk.

---

# 25. Endpoint Security

Management should review:

- Managed antivirus coverage
- Malware-definition status
- Malware detections
- Full-disk encryption coverage
- Standard-user configuration
- Local administrative exceptions
- Screen-lock configuration
- Mobile Device Management enrollment
- Lost or stolen devices
- Endpoint-protection improvements

---

# 26. Malware and Ransomware

R003 Ransomware and R004 Malware remain High current residual risks.

Management treatment must remain layered across:

- Endpoint protection
- Vulnerability management
- Patch management
- Least privilege
- Authentication
- Awareness
- Monitoring
- Incident response
- Backup
- Recovery

---

# 27. Vulnerability Management

Primary artifacts include:

- [[PRO-004 Vulnerability Management Program]]
- [[PROC-006 Vulnerability Assessment Procedure]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]
- [[STD-007 Penetration Testing Standard]]

---

# 28. Vulnerability Assessment

Internal vulnerability assessments are scheduled monthly.

Management should track:

- Assessment completion
- Scope failures
- Excluded systems
- Critical vulnerabilities
- High vulnerabilities
- Aging
- Remediation
- Retesting
- Exceptions
- Recurring weaknesses

---

# 29. Vulnerability Remediation Targets

| Severity | Target |
|---|---|
| Critical | 7 days |
| High | 30 days |
| Moderate | 45 days |
| Low | 60 days |

---

# 30. Vulnerability Escalation

Management attention is required when:

- Critical vulnerabilities exceed the remediation target.
- High vulnerabilities exceed the remediation target.
- Important systems cannot be assessed.
- Required remediation repeatedly fails.
- A systemic configuration problem is identified.
- A vulnerability indicates suspected compromise.

---

# 31. Configuration Management

R013 Administrative / Configuration Error remains High.

Management should track:

- Baseline development
- Approved changes
- Testing
- Separation of Duties where practical
- Rollback capability
- Post-change verification
- Configuration backups
- Emergency changes
- Unauthorized changes
- Recurring configuration deficiencies

---

# 32. Expected Configuration Risk Reduction

### R013 Administrative / Configuration Error

**12 High → 6 Moderate**

The target remains Moderate because administrative and technical errors cannot be completely eliminated.

---

# 33. Network Security

Management should review:

- Firewall administration
- Unauthorized inbound exposure
- Administrative-service exposure
- Network-device configuration backups
- Material firewall changes
- Network discovery
- Rogue wireless assessment
- Unexpected devices
- Remote-access exceptions

---

# 34. Wireless Environment

Dunder Mifflin does not operate a corporate wireless network.

The only authorized wireless access point is the Internet-only guest access point in the Scranton Headquarters lobby.

Network discovery and rogue wireless assessment occur every six months.

Unexpected wireless infrastructure requires investigation.

---

# 35. Internet Infrastructure

R007 Internet Infrastructure remains High.

Treatment includes:

- Firewall and router security
- Denial of unsolicited inbound traffic
- No unnecessary exposed administrative services
- Controlled configuration
- Patch management
- Restricted privileged access
- Network discovery
- Rogue wireless detection
- Configuration backup
- Headquarters spare equipment

Target:

**12 High → 8 Moderate**

---

# 36. Security Monitoring

Dunder Mifflin does not operate a 24-hour Security Operations Center.

Management should evaluate whether:

- Required monitoring occurs.
- Material events are investigated.
- Authentication exceptions are reviewed.
- Malware events are handled.
- Monitoring-source failures are addressed.
- Events are escalated appropriately.
- After-hours events receive appropriate response.

Primary artifact:

[[PROC-008 Security Monitoring Procedure]]

---

# 37. Incident Response

Primary artifacts include:

- [[POL-009 Incident Response Policy]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[PLN-001 Incident Response Plan]]

Management should review:

- Material incidents
- Classification
- Escalation
- Containment
- Recovery
- Evidence handling
- Communications
- Lessons learned
- Corrective actions

---

# 38. Incident Playbooks

Scenario-specific response is supported by:

- [[PBK-001 Phishing & Credential Compromise Playbook]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-004 Data Exposure Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]

---

# 39. Retained Incident Response Support

A retained Digital Forensics and Incident Response provider is included as a proposed Critical Security Response Provider.

Management should track:

- Provider selection
- Contract status
- Scope
- Contact process
- Availability expectations
- Confidentiality
- Escalation procedures
- Periodic contact validation

Until the provider relationship is implemented and validated, it does not receive current residual-risk credit.

---

# 40. Backup and Recovery

R027 Backup Failure remains one of the most important management risks.

Existing backup mechanisms include:

- Automated backups
- Cloud backups
- Encrypted external drives
- Off-site storage

---

# 41. External Backup Rotation

Dunder Mifflin uses:

- 7 facilities
- 3 encrypted external drives per facility
- 21 encrypted drives total

The off-site disaster recovery storage provider normally holds:

- 2 latest weekly generations per facility
- 14 encrypted drives total

---

# 42. Backup Management Review

Management should review:

- Backup-job failures
- Backup coverage
- Off-site rotation
- Media exceptions
- Administrative access
- Restore results
- Recovery-test results
- Corrective actions

---

# 43. Recovery Testing

The program requires:

- Quarterly representative restore testing
- Annual meaningful recovery testing for Critical functions

Testing should evaluate applicable:

- Recovery Time Objective
- Recovery Point Objective
- Recovery procedure
- Documentation
- Dependencies
- Data integrity
- Business usability

---

# 44. Recovery Performance

A backup job reporting success does not prove recovery capability.

Management should focus on whether required information and systems can actually be restored within business requirements.

---

# 45. Expected Backup Risk Reduction

### R027 Backup Failure

**12 High → 5 Moderate**

This target depends on validated recovery performance.

---

# 46. Business Continuity

Management should track:

- Business Continuity Plan maintenance
- Disaster Recovery Plan maintenance
- Printed recovery documentation
- Critical contacts
- Manual continuity
- Annual exercises
- Recovery dependencies
- Corrective actions

Primary artifacts:

- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]

---

# 47. Business Impact Requirements

Recovery requirements are derived from:

[[RPT-002 Business Impact Analysis]]

The BIA establishes:

- Business criticality
- Maximum Tolerable Downtime
- Recovery Time Objective
- Recovery Point Objective

---

# 48. Manual Continuity

Manual processing follows:

**Collect → Review → Enter → Reconcile → Verify**

Management should verify that manual continuity:

- Preserves authorization
- Preserves accountability
- Minimizes sensitive information
- Prevents duplicate processing
- Supports reconciliation
- Supports later verification

Primary artifact:

[[PROC-013 Manual Processing Procedure]]

---

# 49. Cloud Resilience

Management should distinguish:

- Cloud-provider outage
- Facility ISP outage
- Regional telecommunications disruption

These conditions have different dependencies and treatment strategies.

---

# 50. Cloud Exit

The company maintains:

[[PLN-004 Cloud Exit & Emergency Migration Plan]]

Management should verify that:

- Required documentation remains available independently of the affected provider.
- Necessary backup data remains recoverable.
- Application and infrastructure dependencies remain understood.
- Emergency migration assumptions remain realistic.
- Material provider changes trigger plan review.

---

# 51. Infinity Security

Infinity remains a significant management priority because it is:

- Public-facing
- Internally owned
- Business-relevant
- Supported by a third-party contractor

R006 Infinity Compromise remains:

**12 High current residual**

with a target of:

**8 Moderate**

---

# 52. Infinity Management Priorities

Management should track:

- Environment separation
- Production-access restriction
- Threat modeling
- Code review
- Security testing
- Change control
- Annual security assessment
- Annual application penetration test
- Finding remediation
- Retesting
- Contractor access
- Documentation
- Recovery
- Transferability

---

# 53. Infinity Assurance

The expected assurance chain is:

**Penetration Test → Finding → Remediation → Retest → Control Effectiveness → R006 Risk Reassessment**

A completed penetration test does not by itself reduce risk.

The results and corrective actions matter.

---

# 54. Infinity Transferability

Dunder Mifflin owns applicable:

- Source code
- Repository
- Intellectual property
- Data
- Documentation
- Work product
- Backups

Management should periodically determine whether another qualified party could assume Infinity support without unreasonable dependence on the current contractor.

Primary artifact:

[[RPT-004 Infinity Transferability Review]]

---

# 55. Third-Party Security

Third parties are classified:

- Critical
- Important
- Routine

Management should review:

- Inventory
- Classification
- Due diligence
- Contractual requirements
- Confidentiality
- Access
- Security incidents
- Recovery
- Findings
- Exit considerations

---

# 56. Third-Party Review Frequency

| Classification | Review |
|---|---|
| Critical | Annual |
| Important | Biennial |
| Routine | Risk-based |

---

# 57. Third-Party Incident Notification

Applicable third parties are expected to report material security incidents within 24 hours of discovery where required by the security relationship.

Management should investigate missed or delayed notification.

---

# 58. Supplier Resilience

R020 Supplier Disruption requires operational management attention beyond cybersecurity.

Treatment includes:

- Alternate suppliers where practical
- Inventory awareness
- Supplier monitoring
- Procurement coordination
- Business communication
- Periodic sourcing review

---

# 59. Physical Security

Management should review:

- Facility-access exceptions
- Lost cards
- Lost keys
- Restricted-area access
- Visitor controls
- Warehouse high-value cages
- Significant Information Technology areas
- Environmental issues
- Annual physical-access review

---

# 60. Environmental Controls

Management oversight includes:

- Fire
- Water
- Power
- HVAC
- Uninterruptible Power Supply availability
- Landlord coordination
- Backup-media protection
- Business continuity

Dunder Mifflin does not maintain generators.

---

# 61. Personnel Security

Management should track:

- Joiner coordination
- Transfer coordination
- Termination coordination
- Confidentiality
- Security responsibilities
- Contractor personnel
- Key-person dependency
- Cross-training
- Alternate personnel capability

---

# 62. Key-Person Dependency

R026 Personnel Loss requires management to identify important functions that depend excessively on one person.

Treatment includes:

- Documentation
- Cross-training
- Alternate personnel
- Delegated authority
- Company ownership of credentials, configuration, source code, and recovery information
- Emergency access

---

# 63. Fraud Controls

Management should review control performance related to:

- R029 Vendor Fraud
- R030 Sales Fraud
- R031 Payroll Fraud
- R032 Inventory Theft

---

# 64. Vendor Fraud

Management controls include:

- Separation of Duties where practical
- Vendor setup authorization
- Purchase authorization
- Invoice review
- Payment approval
- Independent verification of suspicious or significant bank-detail changes using trusted contact information
- Vendor-master restrictions
- Reconciliation

---

# 65. Sales Fraud

Management controls include:

- Individual accountability
- Role-based permissions
- Approval of significant pricing, discount, credit, or refund activity
- Transaction attribution
- Reconciliation across order, fulfillment, invoice, credit, and payment activity
- Investigation of anomalies

---

# 66. Payroll Fraud

Management controls include:

- Separation of Duties where practical
- Human Resources as the authoritative personnel source
- Restricted payroll access
- Authorization of compensation and banking changes
- Independent verification of suspicious payment changes
- Payroll reconciliation
- Investigation of unusual adjustments or unexpected employees

---

# 67. Inventory Theft

Management controls include:

- Controlled warehouse access
- Locked high-value cages
- Restricted cage access
- Warehouse Management System records
- Individual accountability for significant transactions
- Inventory counts
- Receiving records
- Shipping records
- Reconciliation of inventory movement
- Investigation of discrepancies

---

# 68. Security Awareness

Management should track:

- Initial training
- Annual refresher training
- Annual knowledge assessment
- Required 80% assessment threshold
- Monthly phishing simulations
- Corrective awareness activity

Primary artifact:

[[POL-006 Security Awareness & Training Policy]]

---

# 69. Awareness Interpretation

Awareness metrics should identify areas requiring improvement.

They should not become a mechanism for unnecessary or indiscriminate employee surveillance.

---

# 70. Security Control Inventory

Controls are maintained in:

[[REG-003 Enterprise Security Control Inventory]]

Management should use the inventory to understand:

- Control objective
- Owner
- Related risk
- Implementation status
- Expected evidence
- Assessment method
- Effectiveness

---

# 71. Implementation Status

Implementation status and effectiveness must remain separate.

Typical implementation states include:

- Planned
- Implementing
- Implemented
- Validation Pending
- Validated

---

# 72. Control Effectiveness

Where sufficient evidence supports assessment, effectiveness is expressed as:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

A control lacking sufficient assessment evidence must not be assumed effective.

---

# 73. Implemented Does Not Mean Effective

Management must distinguish:

**Did we deploy the control?**

from:

**Does the control achieve its objective?**

The first is an implementation question.

The second is an assurance question.

---

# 74. Security Assurance

Primary artifact:

[[PRO-008 Security Assurance & Continuous Improvement Program]]

Security assurance evaluates whether controls:

- Are appropriately designed
- Are actually implemented
- Operate as intended
- Produce sufficient evidence
- Achieve the expected outcome

---

# 75. Annual Assurance Plan

[[PLN-005 Annual Assurance Plan]] establishes the risk-based assessment schedule.

Management should monitor:

- Scheduled assessments
- Completed assessments
- Delayed assessments
- Critical-control coverage
- Independence
- Findings
- Corrective actions
- Retesting

---

# 76. Assessment Work Plan

Material assessments should use:

[[TMP-001 Assessment Work Plan Template]]

The Assessment Work Plan establishes the specific:

- Objective
- Scope
- Requirement
- Control
- Evidence
- Method
- Sample
- Procedure
- Expected result
- Reporting approach

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

The selected method should match the control and assurance objective.

---

# 78. Findings

A finding is a documented conclusion supported by evidence concerning whether a requirement, control, process, or expected outcome is satisfied.

Material deficiency findings requiring corrective action are tracked in:

[[REG-004 Finding & Corrective Action Register]]

---

# 79. Finding Management

Management should review:

- New findings
- Priority
- Owner
- Corrective action
- Due date
- Aging
- Overdue status
- Validation
- Retest
- Closure
- Risk implications

---

# 80. Finding Status

Corrective-action status uses:

- Open
- In Progress
- Validation Pending
- Closed

A finding should not be closed merely because implementation activity has ended.

---

# 81. Failed Retest

When retesting fails:

- The deficiency remains visible.
- Corrective action should be revised.
- The finding remains open as appropriate.
- Control effectiveness should reflect the result.
- Related risk may require reassessment.

---

# 82. Repeated Findings

Repeated findings may indicate:

- Root-cause failure
- Weak management oversight
- Inadequate training
- Poor control design
- Insufficient resources
- Incomplete corrective action

Repeated deficiencies should receive greater management attention than isolated administrative errors.

---

# 83. Finding Aging

Management should pay particular attention to:

- High-priority overdue findings
- Critical findings
- Repeated findings
- Findings affecting Critical business functions
- Findings affecting multiple risks
- Findings awaiting validation for extended periods

---

# 84. Risk Acceptance

Risk acceptance is a management decision, not remediation.

Accepting a risk does not mean:

- The deficiency was corrected.
- The control became effective.
- The exposure disappeared.

Accepted deficiencies must remain traceable.

---

# 85. Risk Acceptance Authority

| Risk Level | Required Authority |
|---|---|
| Low | Risk Owner |
| Moderate | Risk Owner and Executive Management |
| High | CEO after ISRC review |
| Critical | CEO after ISRC review; exceptional use |

---

# 86. Risk Acceptance Review

High accepted risks must be reassessed within 90 days.

Critical accepted risks must be reassessed within 30 days.

Management should identify approaching expiration or reassessment dates before they are missed.

---

# 87. Security Metrics

Security metrics are defined in:

[[REG-005 Security Metrics Catalog]]

Metrics include:

- Key Performance Indicators
- Key Risk Indicators
- Operational measures

---

# 88. Management Metric Categories

Management reporting should consider measures across:

- Risk
- Identity and access
- Vulnerability management
- Endpoint security
- Security awareness
- Incident response
- Backup and recovery
- Third-party security
- Infinity security
- Findings
- Corrective action
- Assurance coverage

---

# 89. Metric Reporting Table

Populate from approved metric sources when the report is issued.

| Metric ID | Metric | Current Value | Threshold / Interpretation | Trend | Management Action |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

No measurement should be invented when source data is unavailable.

---

# 90. Metric Status

Where applicable, management dashboards may use:

- Green
- Yellow
- Red
- Not Measured
- Not Applicable

Status must be based on the approved metric definition.

---

# 91. Trend

Where sufficient historical data exists, use:

- Improving
- Stable
- Deteriorating
- Insufficient Data

Do not claim a trend from a single measurement.

---

# 92. Missing Data

Missing data should be reported as unavailable or Not Measured.

Missing data must not automatically be converted to:

- Zero
- Green
- Successful
- Complete

In some cases, inability to produce required evidence is itself a management concern.

---

# 93. Operational Security Checklist

Recurring operational activity is supported by:

[[TMP-002 Operational Security Checklist]]

Management should review material exceptions produced by the operational process rather than requiring executives to review the entire checklist.

---

# 94. Operational Exceptions

Operational exceptions may include:

- Missed security activity
- Failed backup
- Overdue vulnerability
- Unauthorized access
- Failed control
- Missing evidence
- Unauthorized change
- Unresolved malware
- Physical-security exception
- Third-party deficiency

---

# 95. Exception Evaluation

Not every operational exception requires a formal finding.

Management should determine whether the condition requires:

- Routine correction
- Formal finding
- Incident response
- Risk reassessment
- Risk acceptance
- Resource escalation

---

# 96. Management Action Register

Use this section to identify management actions arising from the reporting period.

| Action | Related Risk / Finding | Accountable Owner | Target Date | Status | Escalation Required |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

# 97. Overdue Management Actions

Overdue actions should identify:

- Original due date
- Reason for delay
- Current exposure
- Revised target
- Accountable owner
- Escalation decision

Repeated extensions require increased scrutiny.

---

# 98. Resource Constraints

Management should identify when security work is delayed or weakened by:

- Staffing
- Budget
- Technology limitations
- Vendor dependency
- Business scheduling
- Competing priorities
- Required specialist expertise

Resource constraints should be visible when they materially affect risk.

---

# 99. Cross-Functional Dependencies

Many security treatments require coordination beyond Information Technology.

Examples include:

| Area | Key Participants |
|---|---|
| Identity lifecycle | HR, Management, IT |
| Fraud prevention | Finance, HR, Sales, Operations |
| Physical security | Operations, Facility Management, IT |
| Third-party security | Business Owner, IT, Legal / Compliance |
| Business Continuity | Executive Management, Business Managers, IT |
| Infinity | CIO, IT, Contractor, Business Stakeholders |
| Incident response | IT, Management, HR, Legal / Compliance |
| Personnel security | HR, Management, IT, Operations |

---

# 100. Management Accountability

Each material treatment, finding, corrective action, and risk should have clear accountability.

Shared participation does not eliminate the need for one accountable owner.

---

# 101. Management Escalation Criteria

Management should consider executive escalation when:

- Current residual risk becomes Critical.
- High risk cannot be treated within an acceptable period.
- Significant treatment requires executive resources.
- A Critical business function cannot meet recovery requirements.
- A significant control repeatedly fails.
- A major security incident occurs.
- A material third-party dependency becomes unacceptable.
- A significant finding remains unresolved.
- Management authority is insufficient to resolve the issue.

---

# 102. Immediate Operational Escalation

Some conditions require immediate security or safety action rather than waiting for the next management report.

Examples include:

- Suspected active compromise
- Unauthorized privileged access
- Material data exposure
- Destructive malware
- Serious physical-security breach
- Immediate safety concern
- Significant third-party incident

---

# 103. Executive Reporting

Issues requiring executive attention should be summarized in:

[[RPT-006 Executive Security Summary]]

Executive reporting should focus on the decision required rather than transferring raw operational detail upward.

---

# 104. Operational Reporting

Detailed operational evidence and exceptions are maintained in:

[[RPT-008 Operational Security Report & Dashboard]]

---

# 105. Management Reporting Cycle

The Management Security Report is reviewed monthly.

Material security or risk changes may require reporting outside the normal monthly cycle.

---

# 106. Monthly Management Review

The monthly review should consider:

1. Current High and Critical risks
2. Risk-treatment progress
3. IAM exceptions
4. Vulnerability status
5. Endpoint and malware conditions
6. Security events and incidents
7. Backup and recovery
8. Infinity security
9. Third-party security
10. Findings and corrective actions
11. Assurance activity
12. Security metrics
13. Overdue actions
14. Resource requirements
15. Executive escalation

---

# 107. Quarterly Management Review

Quarterly review should additionally consider:

- Enterprise risk trends
- Treatment effectiveness
- Privileged-access review
- Backup coverage
- Recovery performance
- Third-party review status
- Assurance-plan progress
- Control effectiveness
- Risk acceptance
- Cross-functional dependencies
- Executive reporting requirements

---

# 108. Annual Management Review

Annual review should consider:

- Enterprise risk assessment
- Business Impact Analysis
- Policy framework
- Access reviews
- Business Continuity exercise
- Critical recovery testing
- Incident Response exercise
- Infinity security assessment
- Infinity penetration testing
- Infinity transferability
- Annual assurance planning
- Third-party reviews
- Security awareness
- Program roadmap

---

# 109. Evidence Supporting Management Reporting

Management conclusions may be supported by:

- Risk records
- Treatment records
- Access-review records
- Vulnerability reports
- Patch records
- Malware records
- Security-event records
- Incident records
- Backup records
- Recovery tests
- Change records
- Assessment results
- Finding records
- Training records
- Third-party reviews
- Physical-access records

---

# 110. Evidence Integrity

Management reporting must preserve evidence integrity.

Records must not be altered to create the appearance that:

- Work occurred earlier than it did.
- Failed testing passed.
- Findings were resolved before validation.
- Controls existed before implementation.
- Risk was lower than assessed.

---

# 111. Historical Integrity

When controls improve, preserve:

- Original risk assessment
- Original control condition
- Treatment history
- Assessment results
- Finding history
- Corrective-action history
- Retest results
- Revised risk assessment

Improvement should be demonstrated through history rather than by replacing history.

---

# 112. Control Validation

A control should receive increased confidence when evidence demonstrates that it:

1. Exists.
2. Is appropriately designed.
3. Is implemented.
4. Operates as intended.
5. Achieves the expected outcome.

The required depth of validation depends on control importance and risk.

---

# 113. R027 Recovery Example

The recovery assurance model illustrates why management should focus on demonstrated outcomes.

Assume a Critical process has:

- RTO: 8 hours
- RPO: 4 hours

An initial recovery exercise produces:

- Recovery time: 11 hours 37 minutes
- Data loss: 58 minutes

Result:

- RTO: Fail
- RPO: Pass

The backup exists, but the recovery capability does not yet satisfy the complete business requirement.

---

# 114. R027 Corrective Action Example

Following corrective action, assume a retest produces:

- Recovery time: 6 hours 42 minutes
- Data loss: 47 minutes

Result:

- RTO: Pass
- RPO: Pass

Only after sufficient validation should management consider whether R027 current residual risk should be reassessed.

These values are illustrative and do not represent actual recovery-test evidence.

---

# 115. Risk Reassessment

Risk reassessment should occur when evidence materially changes understanding of:

- Likelihood
- Impact
- Control effectiveness
- Threat conditions
- Business dependency
- Recovery capability

---

# 116. Risk Improvement

Validated post-treatment risk may be:

- Higher than the original target
- Equal to the original target
- Lower than the original target

The target is a prediction.

Evidence determines the reassessed result.

---

# 117. Continuous Monitoring

Continuous monitoring means maintaining risk-appropriate ongoing awareness.

It does not mean that every system, control, or event must receive continuous 24-hour human observation.

Monitoring frequency should reflect:

- Risk
- Business criticality
- Threat exposure
- Control importance
- Available capability

---

# 118. Continuous Improvement

Management should use:

**Evidence → Assessment → Finding → Corrective Action → Validation → Retest → Risk Reassessment**

to improve the program.

---

# 119. Management Dashboard Summary

Populate this section from approved records when the report is issued.

| Area | Status | Trend | Primary Concern | Management Action |
|---|---|---|---|---|
| Enterprise Risk | | | | |
| Identity & Access | | | | |
| Vulnerability Management | | | | |
| Endpoint Security | | | | |
| Network Security | | | | |
| Security Monitoring | | | | |
| Incident Response | | | | |
| Backup & Recovery | | | | |
| Business Continuity | | | | |
| Infinity Security | | | | |
| Third-Party Security | | | | |
| Physical Security | | | | |
| Personnel Security | | | | |
| Findings & Remediation | | | | |
| Security Assurance | | | | |

---

# 120. Status Interpretation

Dashboard status should reflect approved metrics and evidence.

Do not assign Green merely because:

- No incident was reported.
- No finding was entered.
- No complaint was received.
- No measurement exists.

Absence of evidence is not automatically evidence of satisfactory performance.

---

# 121. Management Decisions Required

Use this section when management decisions are required.

| Decision | Reason | Risk / Finding | Options | Decision Owner | Required By |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

# 122. Executive Escalations

Use this section for matters requiring executive review.

| Matter | Enterprise Impact | Recommendation | Executive Decision Required |
|---|---|---|---|
| | | | |
| | | | |

---

# 123. Management Conclusion

Dunder Mifflin's security program requires active management coordination rather than isolated technical activity.

Management is responsible for converting enterprise risk decisions into accountable action.

The management layer must ensure that:

- Treatments have owners.
- Work is completed.
- Evidence is retained.
- Controls are validated.
- Deficiencies become findings.
- Corrective actions are completed.
- Failed validation remains visible.
- Material risk changes are reassessed.
- Significant issues reach executive leadership.

The management reporting principle is:

> **Turn enterprise security objectives into accountable action, measurable performance, validated results, and timely escalation.**

---

# 124. Related Artifacts

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
- [[RPT-008 Operational Security Report & Dashboard]]

---

# 125. Revision History

| Version | Date     | Description                        | Approval |
| ------- | -------- | ---------------------------------- | -------- |
| 1.0     | May 2013 | Initial Management Security Report | CEO      |