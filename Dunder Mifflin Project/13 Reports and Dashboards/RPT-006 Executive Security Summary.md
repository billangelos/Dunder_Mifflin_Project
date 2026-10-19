# RPT-006 Executive Security Summary

## Document Control

| Field | Value |
|---|---|
| Document ID | RPT-006 |
| Title | Executive Security Summary |
| Version | 1.0 |
| Classification | Confidential |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Quarterly and Following Material Risk or Security Change |

---

# 1. Purpose

This report provides the CEO, Information Security and Risk Committee (ISRC), and senior leadership with an enterprise-level summary of Dunder Mifflin's information security and risk posture.

It is intended to support:

- Executive decision-making
- Enterprise risk oversight
- Security investment decisions
- Risk-treatment prioritization
- Accountability
- Business resilience

Detailed technical and operational information is maintained in supporting program artifacts and management reports.

---

# 2. Executive Perspective

Dunder Mifflin depends on information systems, cloud services, Internet connectivity, employees, contractors, suppliers, warehouses, transportation, and physical facilities to conduct business.

The company's security program must protect these dependencies while supporting normal business operations.

The May 2013 assessment demonstrates that Dunder Mifflin has meaningful existing safeguards but retains several High residual risks requiring structured treatment.

The most significant current exposures involve:

- Phishing and credential compromise
- Ransomware and malware
- Authentication weaknesses
- Infinity application security
- Internet infrastructure
- Sensitive-information theft
- Unauthorized or excessive access
- Malicious insiders
- Administrative and configuration error
- Backup and recovery capability

No Critical current residual risks are identified in the enterprise risk register.

---

# 3. Organization

Dunder Mifflin, Inc. is a privately held business-to-business distributor and reseller of:

- Paper
- Stationery
- Office supplies

The company employs approximately 138 personnel.

Operations are distributed across:

- Scranton Headquarters
- Scranton Branch
- Syracuse
- Utica
- Rochester
- Nashua
- Akron

Each branch includes local warehouse and inventory operations.

---

# 4. Executive Governance

The security governance model establishes:

- CEO executive authority
- CIO responsibility for the enterprise security program
- Defined risk ownership
- Policy ownership
- Control ownership
- Information Security and Risk Committee oversight
- Formal risk acceptance
- Management reporting
- Executive reporting

Primary governance artifacts include:

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-009 Security Governance Framework]]
- [[POL-001 Information Security Policy]]
- [[POL-005 Risk Management Policy]]

---

# 5. Security Program Objective

The security program exists to support the business by managing security risk to an acceptable level while protecting:

- People
- Information
- Systems
- Business operations
- Facilities
- Equipment
- Inventory
- Organizational resilience

Human life and safety take priority over systems, operations, facilities, equipment, inventory, revenue, and other assets.

---

# 6. Risk Model

Dunder Mifflin evaluates enterprise security risk using:

**Risk Score = Likelihood × Impact**

Likelihood and Impact use integer values from 1 through 5.

| Score | Risk Level |
|---:|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–16 | High |
| 17–25 | Critical |

---

# 7. Three Risk Views

The program distinguishes three important risk values.

### Inherent Risk

Exposure before considering credited controls.

### Current Residual Risk

Exposure after considering controls that currently exist and receive credit.

### Target Residual Risk

Predicted exposure after proposed treatments are implemented and validated.

These values must not be treated as interchangeable.

---

# 8. Current Enterprise Risk Profile

The enterprise risk assessment contains 35 material risks.

Current residual risk is distributed across High, Moderate, and Low risk levels.

The highest-priority executive concern is the group of risks currently rated High.

---

# 9. Highest Current Residual Risks

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

# 10. Executive Interpretation

The current risk profile does not indicate that the company lacks security controls.

It indicates that several important threats remain capable of causing material business impact despite existing safeguards.

The largest opportunities for risk reduction involve:

1. Identity and authentication
2. Phishing and email protection
3. Endpoint protection
4. Backup and recovery validation
5. Infinity security
6. Vulnerability and configuration management
7. Third-party security
8. Incident response
9. Business continuity and recovery

---

# 11. Inherent Risk Still Matters

Residual risk should not be viewed without considering inherent risk.

For example:

- R003 Ransomware begins at 25 Critical.
- R027 Backup Failure begins at 20 Critical.
- R001 Phishing / Credential Compromise begins at 20 Critical.

Existing controls reduce these exposures, but failure of important controls could restore a substantial portion of the original exposure.

Controls protecting severe inherent risks warrant continued executive attention even after residual risk decreases.

---

# 12. Current Controls Versus Proposed Treatments

The risk assessment distinguishes existing controls from proposed improvements.

Existing controls may receive current residual-risk credit when supported by the established baseline.

Proposed treatments receive no current residual-risk reduction until they are:

1. Implemented
2. Supported by evidence
3. Validated
4. Reflected in a documented risk reassessment

This prevents planned security work from being mistaken for achieved risk reduction.

---

# 13. Target Residual Risk

Target residual risk represents expected risk after successful treatment.

It is a planning estimate rather than a guaranteed result.

Actual post-treatment risk may be:

- Higher than target
- Equal to target
- Lower than target

depending on validation results and changing conditions.

---

# 14. Priority 1: Identity and Authentication

Identity and Access Management represents one of the strongest opportunities for enterprise risk reduction.

Priority improvements include:

- Smart-card multifactor authentication where supported
- Individual accountability
- Separate privileged credentials
- Restricted standing Domain Administrator access
- Dedicated administrative workstations
- Quarterly privileged-access review
- Annual ordinary-user access review
- Stronger contractor-access governance
- Dormant-account management
- Controlled emergency access
- Prompt termination
- Reauthorization following employee transfers

---

# 15. Expected Identity Risk Reduction

Successful implementation and validation are expected to reduce:

### R005 Password / Authentication

**12 High → 4 Low**

### R010 Unauthorized / Excessive Access

**12 High → 4 Low**

Identity improvements also support treatment of:

- R001 Phishing / Credential Compromise
- R002 Business Email Compromise
- R009 Sensitive Information Theft / Extortion
- R011 Delayed Termination
- R012 Malicious Insider
- R015 Shared Warehouse Accounts
- R019 Infinity Contractor

---

# 16. Priority 2: Phishing and Email Protection

Phishing remains a major entry path for credential compromise and malware.

Proposed improvements include:

- Improved email filtering
- Anti-phishing protection
- Blocking known malicious senders
- Suspicious-link protection
- Malicious-attachment protection
- Spoofing protection
- Security awareness
- Monthly phishing simulations
- Stronger authentication
- Incident-response readiness

---

# 17. Expected Phishing Risk Reduction

### R001 Phishing / Credential Compromise

**12 High → 6 Moderate**

The remaining target risk recognizes that phishing cannot be eliminated completely through technical controls or training.

---

# 18. Priority 3: Malware and Ransomware

Existing managed antivirus provides meaningful protection but does not eliminate malware or ransomware exposure.

Treatment requires layered protection involving:

- Endpoint security
- Patch management
- Vulnerability management
- Least privilege
- Authentication
- User awareness
- Security monitoring
- Incident response
- Backup
- Recovery testing

---

# 19. Expected Malware Risk Reduction

### R003 Ransomware

**12 High → 6 Moderate**

### R004 Malware

**12 High → 6 Moderate**

Backup and recovery capability remains especially important because prevention controls cannot guarantee that destructive malware will never succeed.

---

# 20. Priority 4: Backup and Recovery

Backup failure is one of the company's most important resilience risks.

Dunder Mifflin currently uses:

- Automated backups
- Cloud backups
- Encrypted external backup drives
- Off-site backup storage

The external-drive rotation includes:

- 7 facilities
- 3 encrypted drives per facility
- 21 encrypted drives total

The off-site disaster recovery storage provider normally holds the two latest weekly generations for each facility, totaling 14 drives.

---

# 21. Recovery Assurance

The key issue is not simply whether backups exist.

The company must demonstrate that critical information and systems can actually be recovered within business requirements.

The program establishes:

- Quarterly representative restore testing
- Annual meaningful recovery testing for Critical functions
- Recovery documentation
- Recovery Time Objective measurement
- Recovery Point Objective measurement
- Corrective action following failed testing

---

# 22. Expected Backup Risk Reduction

### R027 Backup Failure

**12 High → 5 Moderate**

This target depends on demonstrated recovery performance.

A successful backup job alone does not demonstrate successful recovery.

---

# 23. Priority 5: Infinity Security

Infinity is a public-facing, internally owned business application supported by a third-party contractor.

Dunder Mifflin owns applicable:

- Source code
- Repository
- Intellectual property
- Application data
- Documentation
- Work product
- Backups

---

# 24. Infinity Security Priorities

Security treatment includes:

- Development, test, and production separation
- Threat modeling
- Secure design
- Code review
- Security testing
- Controlled change and release
- Restricted production access
- Contractor-access controls
- Annual Infinity security assessment
- Annual application-focused penetration testing
- Remediation
- Retesting
- Recovery capability
- Documentation
- Annual transferability review

---

# 25. Expected Infinity Risk Reduction

### R006 Infinity Compromise

**12 High → 8 Moderate**

The target remains Moderate because a public-facing application retains meaningful exposure even after improved controls.

---

# 26. Infinity Contractor Risk

Dunder Mifflin must avoid dependence on a contractor becoming equivalent to dependence on an uncontrolled owner of the application.

Contractor controls include:

- Dunder Mifflin ownership of source and documentation
- Named contractor personnel
- Sponsorship
- Time-limited access
- Least privilege
- Confidentiality
- Controlled privileged production activity
- No general contractor VPN
- Access removal
- Transferability review

Primary artifacts include:

- [[PRO-007 Secure Software Development Lifecycle Program]]
- [[STD-009 Infinity Security Standard]]
- [[PROC-020 Contractor Development Access Procedure]]
- [[RPT-004 Infinity Transferability Review]]

---

# 27. Priority 6: Vulnerability and Configuration Management

Administrative and configuration error currently remains High.

Treatment priorities include:

- Secure configuration baselines
- Controlled changes
- Testing
- Approval
- Rollback
- Verification
- Configuration backup
- Vulnerability assessment
- Remediation
- Retesting

---

# 28. Expected Configuration Risk Reduction

### R013 Administrative / Configuration Error

**12 High → 6 Moderate**

The remaining risk recognizes that human and technical errors cannot be completely eliminated.

---

# 29. Vulnerability Management

The vulnerability-management program establishes:

- Monthly internal vulnerability assessment
- Risk-based remediation targets
- Retesting
- Exception management
- Escalation
- Periodic penetration testing

Remediation targets are:

| Severity | Target |
|---|---|
| Critical | 7 days |
| High | 30 days |
| Moderate | 45 days |
| Low | 60 days |

---

# 30. Priority 7: Sensitive Information Protection

Sensitive-information protection depends on multiple layers, including:

- Information classification
- Need-to-know access
- Least privilege
- Full-disk encryption
- Physical security
- Secure disposal
- Confidentiality agreements
- Incident response
- Backup protection
- Security awareness

---

# 31. Expected Information Risk Reduction

### R009 Sensitive Information Theft / Extortion

**12 High → 4 Low**

The target assumes successful implementation and validation of the planned treatment set.

Malicious activity by personnel with legitimate authorized access remains separately represented by R012 Malicious Insider.

---

# 32. Priority 8: Internet Infrastructure

Dunder Mifflin depends heavily on Internet connectivity because major enterprise applications are cloud-hosted.

Current protections include:

- Firewalls and routers
- Denial of unsolicited inbound traffic
- Controlled network changes
- Configuration backups
- Restricted administration
- Wired corporate networks

---

# 33. Network Environment

Dunder Mifflin does not operate a corporate wireless network.

The only authorized wireless access point is the Internet-only guest wireless access point in the Scranton Headquarters lobby.

Network discovery and rogue wireless assessment help detect unauthorized infrastructure.

---

# 34. Expected Internet Infrastructure Risk Reduction

### R007 Internet Infrastructure

**12 High → 8 Moderate**

The target remains Moderate because business operations retain dependency on network and Internet infrastructure.

---

# 35. Business Resilience

Dunder Mifflin's resilience strategy reflects the company's actual operating model.

The company does not operate a major headquarters data center.

Major systems are cloud-hosted, reducing dependence on the continued availability of the headquarters building for system operation.

---

# 36. Geographic Resilience

The company operates across seven facilities.

Geographic distribution provides some resilience because the loss of one facility does not automatically eliminate all enterprise operations.

This supports treatment of:

- R034 Loss of Headquarters
- R035 Regional Disaster

---

# 37. Business Impact Analysis

Recovery priorities are based on:

[[RPT-002 Business Impact Analysis]]

The Business Impact Analysis establishes:

- Business criticality
- Maximum Tolerable Downtime
- Recovery Time Objective
- Recovery Point Objective

Recovery strategy is derived from these business requirements.

---

# 38. Recovery Priority

Recovery priority is:

1. Human life and safety
2. Critical functions
3. High functions
4. Moderate functions
5. Low functions

---

# 39. Manual Continuity

Dunder Mifflin maintains manual continuity procedures for applicable business processes when normal systems are unavailable.

The manual-processing lifecycle is:

**Collect → Review → Enter → Reconcile → Verify**

Manual processing provides temporary continuity rather than a permanent substitute for normal systems.

---

# 40. Cloud Resilience

Cloud-hosted systems reduce dependence on individual company facilities but introduce dependency on:

- Cloud providers
- Internet connectivity
- Provider security
- Provider availability
- Provider recovery capability

These dependencies are represented separately in the enterprise risk assessment.

---

# 41. Cloud Exit Planning

Dunder Mifflin maintains a Cloud Exit & Emergency Migration Plan.

The plan supports recovery from severe provider failure without requiring the company to maintain an unnecessary continuously operating alternate cloud environment.

Primary artifact:

[[PLN-004 Cloud Exit & Emergency Migration Plan]]

---

# 42. Third-Party Security

Dunder Mifflin depends on third parties for important business and technology services.

The third-party program classifies providers as:

- Critical
- Important
- Routine

---

# 43. Third-Party Review

The program establishes:

- Annual review for Critical third parties
- Biennial review for Important third parties
- Risk-based treatment for Routine third parties
- Security requirements
- Confidentiality
- Incident notification
- Access restrictions
- Recovery considerations
- Exit planning

---

# 44. Incident Notification

Applicable third parties are expected to notify Dunder Mifflin of material security incidents within 24 hours of discovery where required by the security relationship.

---

# 45. Confidentiality

Nonemployees receiving sensitive access must have an appropriate Non-Disclosure Agreement or equivalent enforceable confidentiality obligation before receiving that access.

Confidentiality agreements do not replace:

- Technical controls
- Access controls
- Security assessment
- Monitoring
- Vendor governance

---

# 46. Incident Response

Dunder Mifflin maintains a virtual Incident Response Team rather than a permanent dedicated response department.

The program includes:

- Incident classification
- Escalation
- Investigation
- Containment
- Evidence handling
- Recovery
- Communication
- Lessons learned
- Corrective action

---

# 47. Incident Response Capability

Scenario-specific playbooks address:

- Phishing and credential compromise
- Malware and ransomware
- Unauthorized access
- Data exposure
- Third-party incidents

A retained Digital Forensics and Incident Response provider is included as a proposed Critical Security Response Provider.

---

# 48. Security Operations

Dunder Mifflin does not operate a 24-hour Security Operations Center.

The security-operations model is designed around:

- Available internal personnel
- Defined monitoring responsibilities
- Event escalation
- A practical after-hours response process
- External specialist support when required

---

# 49. Physical Security

Physical protection includes:

- Public reception areas
- Controlled employee areas
- Restricted areas
- Employee access cards
- Visitor controls
- Escort requirements
- Warehouse security
- Locked high-value inventory cages
- Restricted significant Information Technology areas

---

# 50. Environmental Risk

Physical and environmental treatment addresses:

- Fire
- Water
- Power
- HVAC
- Facility access
- Backup-media protection

Dunder Mifflin does not maintain generators.

Uninterruptible Power Supply protection supports critical network equipment and selected management and Sales workstations for approximately 30 minutes.

---

# 51. Personnel Security

Personnel security supports enterprise risk reduction through:

- Clear responsibilities
- Confidentiality
- Access coordination
- Transfer procedures
- Termination procedures
- Company-property recovery
- Cross-training
- Key-person dependency management

---

# 52. Fraud Risk

The enterprise risk assessment separately considers:

- Vendor fraud
- Sales fraud
- Payroll fraud
- Inventory theft

Treatment emphasizes:

- Separation of Duties where practical
- Authorization
- Individual accountability
- Independent verification
- Reconciliation
- Restricted access
- Investigation of anomalies

---

# 53. Security Assurance

Security assurance answers the question:

> **How do we know the control actually works?**

The assurance program evaluates security through:

- Inspection
- Observation
- Independent Performance
- Technical Testing
- Sampling
- Exercises
- Reconciliation

Primary artifact:

[[PRO-008 Security Assurance & Continuous Improvement Program]]

---

# 54. Annual Assurance Planning

[[PLN-005 Annual Assurance Plan]] establishes a risk-based schedule for evaluating security controls.

Assessment priority considers:

- Inherent risk
- Current residual risk
- Business criticality
- Control importance
- Prior findings
- Incidents
- Material changes

---

# 55. Assessment Work Planning

Individual material assessments use:

[[TMP-001 Assessment Work Plan Template]]

The Assessment Work Plan establishes:

- Objective
- Scope
- Requirements
- Controls
- Evidence
- Methods
- Sampling
- Testing
- Expected results
- Reporting

---

# 56. Findings and Corrective Action

Material deficiencies requiring corrective action are tracked through:

[[REG-004 Finding & Corrective Action Register]]

The lifecycle is:

**Identify → Validate → Record → Assign → Correct → Validate → Retest → Close → Reassess Risk**

---

# 57. Implemented Does Not Mean Effective

A security treatment is not proven effective merely because implementation is complete.

Validation must determine whether the control achieves its intended objective.

---

# 58. Failed Validation

If validation demonstrates that a treatment does not operate as intended:

- The deficiency remains visible.
- Corrective action is required.
- Retesting may be required.
- Control effectiveness must reflect the evidence.
- Risk may require reassessment.

---

# 59. Security Metrics

Security metrics are defined in:

[[REG-005 Security Metrics Catalog]]

Metrics are intended to help management understand:

- Control performance
- Operational performance
- Risk indicators
- Findings
- Corrective action
- Assurance coverage
- Trends

---

# 60. Executive Metrics

Executive reporting should emphasize a limited number of decision-relevant measures rather than large volumes of technical data.

Examples include:

- High and Critical current residual risks
- Significant overdue corrective actions
- Material failed control tests
- Critical recovery performance
- Significant security incidents
- Material third-party exposure
- Infinity assurance status
- Risk-treatment progress

---

# 61. Metrics Are Evidence, Not Objectives

A favorable metric does not automatically mean the underlying risk is acceptable.

Metrics support decisions.

They must not replace judgment, risk assessment, or control evaluation.

---

# 62. Reporting Levels

Security information is communicated at three levels.

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

---

# 63. Reporting Artifacts

The reporting model is implemented through:

- [[RPT-006 Executive Security Summary]]
- [[RPT-007 Management Security Report]]
- [[RPT-008 Operational Security Report & Dashboard]]

---

# 64. Reporting Chain

Security information should move upward through:

**Technical Evidence → Operational Exception → Management Impact → Enterprise Risk → Executive Decision**

This prevents executives from being overwhelmed by technical data while preserving traceability to the underlying evidence.

---

# 65. Executive Decisions

Executive leadership should focus on decisions involving:

- Risk acceptance
- Security investment
- Major treatment priorities
- Resource allocation
- Business continuity
- Significant third-party exposure
- Significant findings
- Material overdue remediation
- Major architecture changes

---

# 66. Risk Acceptance

Risk acceptance does not mean the risk has been eliminated.

Acceptance means authorized management has consciously decided to retain the identified exposure for a defined period or under defined conditions.

---

# 67. High Risk Acceptance

High risks require:

- CEO approval
- Prior ISRC review
- Reassessment within 90 days

---

# 68. Critical Risk Acceptance

Critical risk acceptance is exceptional.

It requires:

- CEO approval
- Prior ISRC review
- Reassessment within 30 days

---

# 69. Historical Risk Integrity

Later risk improvement must not erase the original May 2013 assessment.

Historical ratings should be preserved so management can distinguish:

- Original exposure
- Existing control effect
- Planned treatment
- Validated improvement

---

# 70. Program Priorities

Executive priority should remain focused on the following areas:

1. Identity and authentication
2. Phishing and email protection
3. Endpoint and malware protection
4. Backup and recovery assurance
5. Infinity security
6. Vulnerability and configuration management
7. Third-party security
8. Incident response
9. Business Continuity and Disaster Recovery
10. Security assurance and corrective action

---

# 71. Priority Dependencies

Many treatment activities support multiple risks.

For example:

### Stronger Identity Controls

Support:

- R001
- R002
- R005
- R009
- R010
- R011
- R012
- R015
- R019

### Recovery Improvement

Supports:

- R003
- R016
- R021
- R022
- R023
- R027
- R028
- R034
- R035

### Security Assurance

Supports the entire risk program by determining whether controls actually work.

---

# 72. Resource Prioritization

Security investment should prioritize controls that:

- Address High or Critical exposure
- Protect Critical business functions
- Reduce multiple risks
- Address material control weakness
- Improve recovery capability
- Reduce concentrated dependency
- Produce measurable assurance

---

# 73. Control Inventory

Enterprise security controls are maintained in:

[[REG-003 Enterprise Security Control Inventory]]

The inventory connects controls to:

- Requirements
- Owners
- Risks
- Evidence
- Assessment methods
- Effectiveness

---

# 74. Control Effectiveness

Control effectiveness uses:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

when sufficient evidence supports an assessment.

Controls lacking sufficient assessment evidence must not be assumed effective.

---

# 75. Continuous Improvement

The security program follows the improvement cycle:

**Risk → Treatment → Control → Evidence → Assessment → Finding → Corrective Action → Validation → Retest → Risk Reassessment**

This process allows the security program to change as the business, threats, technology, and evidence change.

---

# 76. Program Strengths

Existing program strengths include:

- Distributed business operations
- Cloud-hosted enterprise systems
- Managed antivirus
- Central Windows patch management
- Standard-user endpoint operation
- Laptop full-disk encryption
- Mobile Device Management
- Network firewalls
- Controlled physical access
- Warehouse high-value cages
- Encrypted off-site backup rotation
- Automated and cloud backups
- Existing confidentiality requirements
- Dunder Mifflin ownership of Infinity source and intellectual property
- Existing Cloud Exit & Emergency Migration planning

---

# 77. Material Program Gaps

Important gaps requiring continued treatment include:

- General multifactor authentication
- Formalized access-review maturity
- Stronger phishing protection
- Stronger endpoint protection
- Recovery validation
- Formalized vulnerability-management maturity
- Formalized third-party security governance
- Infinity assurance
- More mature security monitoring
- Formalized control assurance
- Corrective-action tracking

---

# 78. Security Maturity Direction

The objective is not to deploy every available security technology.

The objective is to establish controls proportional to:

- Business need
- Risk
- Information sensitivity
- Business impact
- Operational practicality
- Cost

---

# 79. No Unnecessary Complexity

Dunder Mifflin is approximately a 138-person organization.

Security architecture and governance should be sufficiently strong to manage material risk without creating unnecessary complexity that the organization cannot operate or sustain.

---

# 80. Executive Oversight Questions

Senior leadership should periodically ask:

1. What are our highest current risks?
2. Which risks could become severe if important controls fail?
3. Which treatments are overdue?
4. Which implemented controls have not yet been validated?
5. Which significant findings remain open?
6. Can Critical business functions recover within their required objectives?
7. Are major third-party dependencies being managed?
8. Is Infinity support transferable?
9. Are security resources focused on the most important exposures?
10. Has evidence changed our understanding of risk?

---

# 81. Executive Security Review

Quarterly executive security review should consider:

- Enterprise risk profile
- High and Critical risks
- Treatment progress
- Significant findings
- Corrective-action aging
- Material incidents
- Recovery results
- Infinity assurance
- Third-party security
- Resource requirements
- Required risk acceptance

---

# 82. Information Security and Risk Committee

The ISRC provides structured management review before significant risk decisions reach the CEO.

The committee supports:

- Cross-functional risk review
- Treatment prioritization
- Risk acceptance review
- Significant finding review
- Resource discussion
- Program oversight

---

# 83. Executive Reporting Limitation

This summary intentionally excludes much of the technical and operational detail maintained elsewhere in the program.

Executive reporting should not become a replacement for:

- Management reporting
- Operational reporting
- Technical evidence
- Assessment work papers
- Incident records
- Recovery-test records

---

# 84. Management Report

Detailed management accountability and treatment performance are addressed in:

[[RPT-007 Management Security Report]]

---

# 85. Operational Report

Detailed operational execution, evidence, exceptions, and technical status are addressed in:

[[RPT-008 Operational Security Report & Dashboard]]

---

# 86. Overall Security Posture

Dunder Mifflin has a meaningful security foundation but retains several High enterprise security risks.

The company does not require an unnecessarily complex security architecture to improve its posture substantially.

The largest improvements are expected from disciplined implementation of:

- Identity controls
- Phishing protection
- Endpoint protection
- Vulnerability management
- Configuration management
- Recovery validation
- Infinity assurance
- Third-party governance
- Incident response
- Security assessment

---

# 87. Expected Direction

Successful treatment is expected to reduce several major risks.

Examples include:

| Risk | Current Residual | Target Residual |
|---|---:|---:|
| R001 Phishing / Credential Compromise | 12 High | 6 Moderate |
| R005 Password / Authentication | 12 High | 4 Low |
| R009 Sensitive Information Theft / Extortion | 12 High | 4 Low |
| R010 Unauthorized / Excessive Access | 12 High | 4 Low |
| R027 Backup Failure | 12 High | 5 Moderate |

These targets remain predictions until treatment effectiveness is validated.

---

# 88. Executive Conclusion

Dunder Mifflin's security challenge is not simply to acquire additional security technology.

The company must consistently connect:

**Business Need → Risk → Treatment → Control → Evidence → Assurance → Decision**

The current program establishes that structure.

Executive leadership should continue prioritizing treatment of the highest residual risks while requiring evidence that implemented improvements actually reduce exposure.

Security progress should be measured by demonstrated improvement in control effectiveness and enterprise risk, not by the number of technologies purchased or policies issued.

---

# 89. Related Artifacts

## Enterprise Context

- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[REG-001 Enterprise Asset Register]]
- [[RPT-002 Business Impact Analysis]]

## Risk Management

- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]

## Governance

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-009 Security Governance Framework]]
- [[POL-001 Information Security Policy]]
- [[POL-005 Risk Management Policy]]

## Architecture and Identity

- [[PRO-002 Enterprise Security Architecture Program]]
- [[PRO-003 Identity and Access Management Program]]
- [[STD-002 Network Security Standard]]
- [[STD-003 Endpoint Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]

## Vulnerability and Operations

- [[PRO-004 Vulnerability Management Program]]
- [[PRO-005 Security Operations Program]]
- [[STD-007 Penetration Testing Standard]]

## Incident Response

- [[PLN-001 Incident Response Plan]]
- [[STD-008 Incident Classification & Escalation Standard]]

## Business Continuity and Disaster Recovery

- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-013 Manual Processing Procedure]]

## Physical and Personnel Security

- [[PRO-006 Physical & Personnel Security Program]]
- [[PROC-017 Personnel Security Procedure]]

## Secure Development

- [[PRO-007 Secure Software Development Lifecycle Program]]
- [[STD-009 Infinity Security Standard]]
- [[RPT-004 Infinity Transferability Review]]

## Assurance

- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[PLN-005 Annual Assurance Plan]]
- [[TMP-001 Assessment Work Plan Template]]

## Reporting

- [[RPT-007 Management Security Report]]
- [[RPT-008 Operational Security Report & Dashboard]]

---

# 90. Revision History

| Version | Date     | Description                        | Approval |
| ------- | -------- | ---------------------------------- | -------- |
| 1.0     | May 2013 | Initial Executive Security Summary | CEO      |