# PLN-006 Enterprise Security Program Roadmap

## Document Control

| Field | Value |
|---|---|
| Document ID | PLN-006 |
| Title | Enterprise Security Program Roadmap |
| Version | 1.0 |
| Classification | Confidential |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Quarterly and Following Material Risk, Business, Technology, or Security Program Change |

---

# 1. Purpose

This roadmap establishes the prioritized implementation sequence for the Dunder Mifflin Enterprise Information Security and Risk Management Program.

It translates:

- Enterprise risk assessment
- Risk-treatment decisions
- Business Impact Analysis requirements
- Governance requirements
- Security architecture
- Control requirements
- Assurance requirements

into a coordinated implementation plan.

The roadmap is intended to answer:

> **What should Dunder Mifflin improve first, what should follow, and how will management know the improvements actually work?**

---

# 2. Roadmap Principle

Security improvements are prioritized according to business and risk requirements rather than technology preference.

The general sequence is:

**Understand Risk → Establish Governance → Reduce Major Exposure → Improve Resilience → Strengthen Assurance → Validate Results → Reassess Risk**

---

# 3. Relationship to Enterprise Risk

The roadmap is primarily driven by:

[[RPT-003 Enterprise Risk Assessment]]

[[REG-002 Enterprise Risk Register]]

and:

[[RTP-001 Enterprise Risk Treatment Plan]]

The Enterprise Risk Treatment Plan defines the required treatment.

This roadmap coordinates the order in which treatment should be implemented.

---

# 4. Relationship to Current Residual Risk

Roadmap inclusion does not reduce current residual risk.

A planned improvement may be:

- Important
- Approved
- Funded
- Scheduled
- Under implementation

while the associated current residual risk remains unchanged.

Risk reduction requires appropriate implementation, evidence, validation, and risk reassessment.

---

# 5. Roadmap Horizons

The roadmap uses four implementation horizons.

| Horizon | Period |
|---|---|
| Immediate | 0–90 days |
| Near-Term | 3–6 months |
| Medium-Term | 6–12 months |
| Ongoing | Recurring or continuous activity |

The horizons indicate priority and expected sequencing.

They do not eliminate the need to respond immediately to a material incident, vulnerability, business change, or newly identified risk.

---

# 6. Prioritization Factors

Roadmap priority considers:

- Inherent risk
- Current residual risk
- Potential business impact
- Business Impact Analysis criticality
- Existing control weakness
- Dependency on the control
- Treatment effectiveness
- Implementation complexity
- Cost
- Personnel requirements
- Technology dependencies
- Third-party dependencies
- Recovery requirements
- Assurance requirements

---

# 7. Highest Current Residual Risks

The following risks currently remain High:

| Risk ID | Risk | Current Residual |
|---|---|---:|
| R001 | Phishing / Credential Compromise | 12 High |
| R003 | Ransomware | 12 High |
| R004 | Malware | 12 High |
| R005 | Password / Authentication Weakness | 12 High |
| R006 | Infinity Compromise | 12 High |
| R007 | Internet Infrastructure Compromise | 12 High |
| R009 | Sensitive Information Theft / Extortion | 12 High |
| R010 | Unauthorized / Excessive Access | 12 High |
| R012 | Malicious Insider | 10 High |
| R013 | Administrative / Configuration Error | 12 High |
| R027 | Backup Failure | 12 High |

These risks receive significant roadmap attention.

---

# 8. Roadmap Workstreams

Implementation is organized into the following workstreams:

1. Governance and Accountability
2. Identity and Access Management
3. Email, Phishing, and Endpoint Protection
4. Network and Infrastructure Security
5. Vulnerability and Configuration Management
6. Infinity Security
7. Backup, Recovery, and Resilience
8. Incident Response
9. Third-Party Security
10. Physical and Personnel Security
11. Fraud and Transaction Controls
12. Security Assurance and Metrics
13. Training and Awareness

Several risks depend on more than one workstream.

---

# 9. Dependency Principle

Controls should be implemented in an order that supports later controls.

Examples include:

- Asset knowledge before complete vulnerability coverage
- Identity governance before reliable access review
- Recovery requirements before meaningful recovery testing
- Control definition before assurance testing
- Evidence requirements before declaring controls validated
- Secure-development requirements before evaluating contractor adherence
- Incident classification before consistent incident escalation

---

# 10. Immediate Horizon

## 0–90 Days

The Immediate horizon focuses on reducing major current exposure and establishing the governance needed to support later improvements.

Priority should be given to actions affecting the current High risks and controls required by multiple treatment plans.

---

# 11. Immediate Priority 1: Establish Governance and Accountability

Implement and communicate the approved security governance structure.

Primary artifacts include:

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-009 Security Governance Framework]]
- [[POL-001 Information Security Policy]]
- [[POL-005 Risk Management Policy]]

Actions include:

- Establish the Information Security and Risk Committee.
- Confirm enterprise risk ownership.
- Confirm control ownership.
- Establish risk escalation expectations.
- Establish risk-acceptance authority.
- Establish security exception handling.
- Establish treatment tracking.
- Establish quarterly security and risk review.

Primary risks supported:

- All enterprise risks

---

# 12. Immediate Priority 2: Formalize Risk Treatment Tracking

Use:

[[RTP-001 Enterprise Risk Treatment Plan]]

to track the 35 enterprise risks.

For each treatment:

- Confirm accountable owner.
- Confirm required action.
- Confirm dependency.
- Confirm implementation horizon.
- Confirm required evidence.
- Confirm validation method.
- Track implementation status.

Treatment status follows:

**Planned → Approved → Implementing → Implemented → Validation Pending → Validated**

Where validation identifies a deficiency:

**Corrective Action Required**

may be applied.

---

# 13. Immediate Priority 3: Strengthen Authentication

Begin implementation of stronger authentication for supported systems.

Actions include:

- Implement smart-card multifactor authentication where supported.
- Require the associated PIN or approved secret.
- Prioritize privileged and higher-risk access.
- Preserve individual accountability.
- Document systems where stronger authentication is not currently supported.
- Evaluate compensating controls where necessary.

Primary risks:

- R001 Phishing / Credential Compromise
- R005 Password / Authentication Weakness
- R006 Infinity Compromise
- R009 Sensitive Information Theft / Extortion
- R010 Unauthorized / Excessive Access
- R012 Malicious Insider

Target examples include:

- R001: 12 High → 6 Moderate
- R005: 12 High → 4 Low

These target ratings remain predictions until treatment is validated and the risks are reassessed.

---

# 14. Immediate Priority 4: Restrict Privileged Access

Implement the privileged-access requirements established by:

[[POL-003 Access Control Policy]]

[[STD-005 Authentication & Account Security Standard]]

[[PROC-002 Privileged Access Procedure]]

Actions include:

- Separate ordinary and privileged credentials.
- Restrict standing Domain Administrator membership.
- Limit standing Domain Administrator access to the IT & Information Security Manager and System Administrator unless additional access is specifically justified and approved.
- Establish dedicated administrative workstations.
- Restrict unnecessary external privileged administration.
- Review existing privileged accounts.
- Remove unnecessary privileges.
- Establish emergency-access controls.
- Protect emergency credentials through dual custody where required.

Primary risks:

- R005
- R006
- R007
- R009
- R010
- R012
- R013
- R027

---

# 15. Immediate Priority 5: Improve Account Lifecycle Control

Implement:

[[PROC-001 Joiner-Mover-Leaver Procedure]]

[[PROC-003 Access Review Procedure]]

[[PROC-004 Contractor Access Procedure]]

[[PROC-005 Emergency Access Procedure]]

Actions include:

- Use Human Resources as the authoritative personnel-status source.
- Require appropriate authorization before access.
- Revoke previous business permissions during transfers before new permissions are authorized.
- Promptly disable access following termination.
- Recover applicable cards, keys, devices, smart cards, and credentials.
- Investigate accounts dormant for 30 days.
- Disable unresolved dormant accounts after 60 days.
- Establish time-limited contractor access.
- Establish annual ordinary-user access review.
- Establish quarterly privileged-access review.

Primary risks:

- R005
- R010
- R011
- R012
- R015
- R019

---

# 16. Immediate Priority 6: Improve Warehouse Accountability

Reduce reliance on shared identity for significant warehouse activity.

Actions include:

- Retain shared Windows workstation accounts only where operationally justified.
- Require individual authentication for significant Warehouse Management System activity.
- Maintain transaction attribution.
- Restrict workstation permissions.
- Review warehouse access.
- Preserve inventory transaction records.

Primary risks:

- R010
- R015
- R032

---

# 17. Immediate Priority 7: Improve Email and Phishing Protection

Strengthen email protection using available capabilities.

Actions include improving filtering against:

- Known malicious senders
- Suspicious links
- Malicious attachments
- Spoofed messages
- Common phishing indicators

Coordinate technical controls with awareness and incident-response capability.

Primary risks:

- R001
- R002
- R003
- R004
- R009

---

# 18. Immediate Priority 8: Launch Security Awareness Program

Implement:

[[POL-006 Security Awareness & Training Policy]]

Actions include:

- Initial security training within five business days where required.
- Annual refresher training.
- Annual knowledge assessment.
- Minimum passing score of 80 percent.
- Monthly phishing simulations.
- Targeted follow-up where weaknesses are identified.
- Reinforce reporting of suspicious messages and security events.

Primary risks:

- R001
- R002
- R003
- R004
- R009
- R012
- R029
- R030
- R031

---

# 19. Immediate Priority 9: Validate Backup Coverage

R027 Backup Failure remains a High current residual risk.

Use:

[[PROC-012 Backup & Recovery Procedure]]

to validate whether backup coverage supports actual business requirements.

Actions include:

- Compare backup coverage with the asset inventory.
- Compare backup coverage with the Business Impact Analysis.
- Confirm Critical and High systems are included as required.
- Confirm automated backup jobs.
- Confirm cloud backup coverage.
- Confirm encrypted external-drive rotation.
- Confirm off-site separation.
- Review backup failures.
- Verify required recovery documentation exists.
- Identify unsupported recovery dependencies.

Primary risks:

- R027
- R028
- R034
- R035

---

# 20. Immediate Priority 10: Begin Representative Restore Testing

Establish quarterly representative restore testing.

Testing should determine whether:

- Required data can be restored.
- Recovery instructions are usable.
- Recovery sources are available.
- Restored information is usable.
- Results are documented.

Use:

[[TMP-003 Recovery Test Template]]

where applicable.

A successful backup job does not prove recoverability.

---

# 21. Immediate Priority 11: Establish Incident Response Capability

Implement:

[[POL-009 Incident Response Policy]]

[[STD-008 Incident Classification & Escalation Standard]]

[[PLN-001 Incident Response Plan]]

Actions include:

- Establish the virtual Incident Response Team.
- Define contact and escalation paths.
- Establish incident classification.
- Establish after-hours escalation.
- Establish evidence-handling requirements.
- Train appropriate personnel.
- Establish incident documentation.
- Establish management and legal escalation.
- Establish lessons-learned expectations.

---

# 22. Immediate Priority 12: Establish Core Incident Playbooks

Operationalize:

- [[PBK-001 Phishing & Credential Compromise Playbook]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-004 Data Exposure Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]

Playbooks should be accessible to personnel expected to use them.

---

# 23. Immediate Priority 13: Retain Specialized Incident Support

Establish the proposed retained Digital Forensics and Incident Response provider relationship.

The provider should be treated as a Critical Security Response Provider.

Actions include:

- Define engagement terms.
- Define contact procedures.
- Define availability expectations.
- Define confidentiality requirements.
- Define evidence expectations.
- Define escalation.
- Confirm the provider can support required systems and environments.

Until the relationship is implemented and validated, it receives no current residual-risk credit.

---

# 24. Immediate Priority 14: Strengthen Network Administration

Implement applicable requirements from:

[[STD-002 Network Security Standard]]

Actions include:

- Confirm unsolicited inbound traffic is denied unless specifically authorized.
- Confirm internal administrative interfaces are not unnecessarily Internet-accessible.
- Review firewall and router configurations.
- Protect administrative credentials.
- Maintain configuration backups.
- Review authorized remote access.
- Document approved network devices.
- Establish configuration review.

Primary risks:

- R007
- R013
- R016
- R017

---

# 25. Immediate Priority 15: Establish Network Discovery

Perform network discovery and establish the expected device baseline.

Include rogue wireless identification.

The expected wireless baseline is:

- One ceiling-mounted Access Point
- Scranton Headquarters lobby
- Internet-only guest wireless

No general corporate wireless network is authorized.

Unexpected wireless infrastructure requires investigation.

---

# 26. Immediate Priority 16: Strengthen Configuration Management

Implement:

[[POL-007 Change & Configuration Management Policy]]

and:

[[STD-006 Secure Configuration Standard]]

Actions include:

- Establish configuration baselines.
- Require review and authorization.
- Require testing where practical.
- Maintain rollback capability.
- Verify significant changes after implementation.
- Maintain configuration documentation.
- Maintain configuration backups.
- Review emergency changes.

Primary risks:

- R006
- R007
- R013
- R027
- R028

---

# 27. Immediate Priority 17: Establish Vulnerability Remediation Discipline

Operationalize:

[[PRO-004 Vulnerability Management Program]]

[[PROC-006 Vulnerability Assessment Procedure]]

[[PROC-007 Vulnerability Remediation & Retest Procedure]]

Target remediation periods are:

| Severity | Target |
|---|---:|
| Critical | 7 days |
| High | 30 days |
| Moderate | 45 days |
| Low | 60 days |

Actions include:

- Establish vulnerability ownership.
- Establish remediation tracking.
- Require retesting.
- Escalate overdue material vulnerabilities.
- Document exceptions.

---

# 28. Immediate Priority 18: Establish Infinity Security Governance

Implement:

[[POL-012 Application & Secure Development Policy]]

[[PRO-007 Secure Software Development Lifecycle Program]]

[[STD-009 Infinity Security Standard]]

Actions include:

- Confirm Dunder Mifflin ownership of source code.
- Confirm repository control.
- Confirm ownership of application data.
- Confirm ownership of documentation.
- Confirm ownership of work product.
- Confirm backup arrangements.
- Confirm contractor confidentiality obligations.
- Establish development, test, and production separation.
- Establish controlled change and release.
- Establish security review requirements.

Primary risks:

- R006
- R019
- R028

---

# 29. Immediate Priority 19: Restrict Infinity Contractor Access

Implement:

[[PROC-020 Contractor Development Access Procedure]]

Actions include:

- Require company sponsorship.
- Require named contractor personnel.
- Require expected onsite personnel names one business day before scheduled arrival where practical.
- Maintain an emergency exception process.
- Limit access to required systems.
- Time-limit access.
- Require individual accountability.
- Restrict privileged production administration to the designated Headquarters contractor workspace.
- Do not provide general contractor VPN access.
- Review contractor access.

Primary risks:

- R006
- R010
- R019

---

# 30. Immediate Priority 20: Establish Finding Tracking

Operationalize:

[[REG-004 Finding & Corrective Action Register]]

Material deficiencies identified through assessment should be tracked through:

**Finding → Corrective Action → Validation → Retest → Closure**

Corrective-action status should be visible to management.

---

# 31. Near-Term Horizon

## 3–6 Months

The Near-Term horizon expands control maturity after immediate governance and high-risk weaknesses have been addressed.

---

# 32. Near-Term Priority 1: Complete Access Reviews

Complete the first formal:

- Ordinary-user access review
- Privileged-access review
- Physical-access review

Resolve:

- Unnecessary access
- Excessive access
- Dormant accounts
- Unsupported privileges
- Inappropriate contractor access
- Obsolete physical credentials

Document evidence.

---

# 33. Near-Term Priority 2: Complete Dedicated Administrative Workstation Deployment

Complete deployment of dedicated administrative workstations for appropriate privileged administration.

Actions include:

- Restrict ordinary use.
- Apply secure configuration.
- Limit unnecessary applications.
- Protect privileged credentials.
- Maintain patching.
- Document authorized users.
- Validate intended use.

---

# 34. Near-Term Priority 3: Strengthen Endpoint Protection

Build on the existing centrally managed antivirus baseline.

Actions include:

- Verify antivirus coverage.
- Verify update status.
- Verify full-disk encryption coverage for applicable laptops.
- Verify standard-user configuration.
- Verify screen-lock configuration.
- Verify patch-management coverage.
- Verify Mobile Device Management enrollment for supported company mobile devices.
- Evaluate additional endpoint detection capability where justified by risk and operational need.

Primary risks:

- R003
- R004
- R009
- R014

---

# 35. Near-Term Priority 4: Establish Hardened Endpoint and Server Baselines

Develop and deploy secure configuration baselines for:

- Windows 7 endpoints
- Windows Server 2012 systems
- Administrative workstations
- Applicable network devices

Use:

[[STD-003 Endpoint Security Standard]]

[[STD-004 Server Security Standard]]

[[STD-006 Secure Configuration Standard]]

Baseline implementation should be tested before broad deployment.

---

# 36. Near-Term Priority 5: Complete Initial Vulnerability Assessment Cycle

Complete the first formal monthly vulnerability-assessment cycle across the defined scope.

Validate:

- Asset coverage
- Scan completion
- Finding ownership
- Severity
- Remediation
- Exceptions
- Retesting

Identify assets missing from expected assessment coverage.

---

# 37. Near-Term Priority 6: Conduct Infinity Security Assessment

Perform the annual Infinity security assessment using:

[[PROC-019 Application Security Assessment Procedure]]

The assessment should consider:

- Architecture
- Authentication
- Authorization
- Application configuration
- Development practices
- Change control
- Contractor access
- Data protection
- Logging
- Recovery
- Documentation
- Known vulnerabilities

---

# 38. Near-Term Priority 7: Conduct Infinity Application Penetration Test

Perform the annual authorized application penetration test.

Use:

[[STD-007 Penetration Testing Standard]]

Maintain the assurance chain:

**Penetration Test → Finding → Remediation → Retest → Control Effectiveness → R006 Reassessment**

---

# 39. Near-Term Priority 8: Perform Infinity Transferability Review

Use:

[[RPT-004 Infinity Transferability Review]]

to evaluate whether another qualified party could assume Infinity support.

Review:

- Source ownership
- Repository
- Build instructions
- Deployment instructions
- Configuration
- Dependencies
- Credentials
- Documentation
- Recovery
- Knowledge transfer

Primary risks:

- R019
- R026

---

# 40. Near-Term Priority 9: Strengthen Third-Party Risk Management

Implement:

[[POL-008 Third-Party Security Policy]]

Actions include:

- Maintain third-party inventory.
- Classify providers as Critical, Important, or Routine.
- Establish risk-based due diligence.
- Establish security requirements in contracts where appropriate.
- Maintain confidentiality requirements.
- Limit third-party access.
- Establish incident-notification expectations.
- Review recovery and continuity dependencies.
- Establish exit considerations.
- Review concentration risk.

Critical third parties receive annual review.

Important third parties receive biennial review.

Material security incidents require notification within 24 hours of discovery where contractually required.

---

# 41. Near-Term Priority 10: Review Supplier Resilience

Address R020 Supplier Disruption.

Actions include:

- Identify important supplier dependencies.
- Identify practical alternate suppliers.
- Review inventory dependency.
- Review transportation dependency.
- Monitor significant supplier disruption.
- Establish procurement escalation.
- Maintain business communication procedures.
- Periodically review sourcing alternatives.

---

# 42. Near-Term Priority 11: Strengthen Financial Fraud Controls

Coordinate Finance, Human Resources, Sales, Operations, and Information Technology controls for:

- R029 Vendor Fraud
- R030 Sales Fraud
- R031 Payroll Fraud
- R032 Inventory Theft

Actions include:

- Strengthen separation of duties where practical.
- Restrict vendor-master changes.
- Restrict payment changes.
- Independently verify suspicious or significant banking changes using trusted contact information.
- Reconcile financial records.
- Review significant discounts, credits, refunds, and adjustments.
- Maintain transaction attribution.
- Investigate unusual activity.

---

# 43. Near-Term Priority 12: Strengthen Inventory Controls

Actions include:

- Maintain locked high-value inventory cages.
- Restrict cage access.
- Require individual accountability for significant Warehouse Management System transactions.
- Maintain receiving records.
- Maintain shipping records.
- Maintain inventory movement records.
- Perform counts and reconciliation.
- Investigate material discrepancies.

Primary risk:

- R032 Inventory Theft

---

# 44. Near-Term Priority 13: Formalize Personnel Security

Operationalize:

[[PROC-017 Personnel Security Procedure]]

Actions include:

- Establish risk-appropriate screening where lawful and appropriate.
- Maintain confidentiality requirements.
- Coordinate access with personnel status.
- Identify key-person dependencies.
- Improve documentation.
- Establish cross-training.
- Establish alternate personnel for important responsibilities.
- Coordinate termination actions.
- Protect personnel records.

Primary risks:

- R011
- R012
- R026
- R029
- R030
- R031
- R032

---

# 45. Near-Term Priority 14: Exercise Manual Continuity

Use:

[[PROC-013 Manual Processing Procedure]]

Exercise the lifecycle:

**Collect → Review → Enter → Reconcile → Verify**

Exercises should evaluate:

- Order processing
- Warehouse activity
- Inventory movement
- Shipping
- Relevant financial processes
- Restoration entry
- Duplicate prevention
- Reconciliation

Primary risk:

- R033 Manual Outage Error

---

# 46. Near-Term Priority 15: Review Business Continuity Capability

Operationalize:

[[PLN-002 Business Continuity Plan]]

Review:

- Critical and High processes
- Personnel dependencies
- Communications
- Manual workarounds
- Alternate locations
- Company-issued mobile capability
- Supplier dependencies
- Facility disruption
- Management succession
- Delegated authority

---

# 47. Near-Term Priority 16: Review Disaster Recovery Capability

Operationalize:

[[PLN-003 Disaster Recovery Plan]]

Review recovery capability against:

[[RPT-002 Business Impact Analysis]]

Confirm that technical recovery strategy aligns with established:

- MTD
- RTO
- RPO

---

# 48. Near-Term Priority 17: Validate Cloud Exit Capability

Review:

[[PLN-004 Cloud Exit & Emergency Migration Plan]]

Confirm:

- Provider dependencies are understood.
- Required documentation is independent of the provider.
- Backup sources are accessible.
- Required credentials are controlled.
- Recovery priorities are understood.
- Migration dependencies are documented.
- Alternate providers can be evaluated when required.

The roadmap does not require maintaining an unnecessary continuously operating alternate cloud environment.

---

# 49. Near-Term Priority 18: Establish Security Metrics

Operationalize:

[[REG-005 Security Metrics Catalog]]

Begin collecting approved:

- Key Performance Indicators
- Key Risk Indicators
- Operational measures

Metrics should support decisions rather than exist only for reporting volume.

---

# 50. Near-Term Priority 19: Establish Operational Reporting

Use:

[[RPT-008 Operational Security Report & Dashboard]]

to report:

- Execution
- Evidence
- Exceptions
- Technical detail

Do not fabricate values where measurements do not yet exist.

---

# 51. Near-Term Priority 20: Establish Management Reporting

Use:

[[RPT-007 Management Security Report]]

to communicate:

- Accountability
- Performance
- Corrective actions
- Trends
- Escalation
- Treatment progress

---

# 52. Near-Term Priority 21: Establish Executive Reporting

Use:

[[RPT-006 Executive Security Summary]]

to communicate:

- Enterprise risk
- Business impact
- Significant exposure
- Resource requirements
- Decisions

---

# 53. Medium-Term Horizon

## 6–12 Months

The Medium-Term horizon focuses on validating the broader security program, improving resilience, and establishing repeatable assurance.

---

# 54. Medium-Term Priority 1: Execute Annual Assurance Plan

Use:

[[PLN-005 Annual Assurance Plan]]

to perform risk-based security assessment.

Priority should consider:

- Inherent risk
- Current residual risk
- Critical controls
- BIA criticality
- Previous findings
- Material changes

---

# 55. Medium-Term Priority 2: Use Formal Assessment Work Plans

For material assessments, use:

[[TMP-001 Assessment Work Plan Template]]

Define:

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

This supports consistent and defensible assurance work.

---

# 56. Medium-Term Priority 3: Validate Critical Controls

Identify and assess Critical controls from:

[[REG-003 Enterprise Security Control Inventory]]

Critical controls should receive assurance priority because their failure could materially increase enterprise risk or disrupt important business capability.

---

# 57. Medium-Term Priority 4: Perform Annual Critical Recovery Test

Perform a meaningful recovery test for Critical capability.

Compare actual results with:

- Recovery Time Objective
- Recovery Point Objective
- Functional requirements
- Security requirements

Record results using:

[[TMP-003 Recovery Test Template]]

Failed recovery tests create findings and corrective actions where appropriate.

---

# 58. Medium-Term Priority 5: Improve Backup Resilience

Based on backup and recovery assessment results, evaluate additional protection against compromise of production and backup environments.

Consider:

- Administrative separation
- Access restrictions
- Backup credential protection
- Recovery-source independence
- Additional protected backup copies
- Appropriate resistance to production compromise

Technology should be selected based on actual risk and recovery requirements.

---

# 59. Medium-Term Priority 6: Evaluate Internet Resilience

Address:

- R017 ISP Outage
- R035 Regional Disaster

Actions include:

- Validate company-issued cellular connectivity where applicable.
- Validate alternate communications.
- Determine which functions can continue using cellular service.
- Maintain manual continuity where cellular capability is insufficient.
- Evaluate provider diversity where justified.

---

# 60. Medium-Term Priority 7: Evaluate Facility Resilience

Address:

- R021 Fire
- R022 Water
- R023 Utility / Power / HVAC
- R034 Loss of Headquarters
- R035 Regional Disaster

Actions include:

- Review landlord coordination.
- Review fire and life-safety controls.
- Review water exposure.
- Review UPS coverage.
- Review orderly shutdown capability.
- Review alternate work locations.
- Review geographic distribution.
- Review insurance.
- Review recovery documentation.
- Review alternate personnel.

Generator installation is not automatically required.

It should be justified by business requirements, risk, feasibility, and cost.

---

# 61. Medium-Term Priority 8: Conduct Physical Security Review

Use:

[[PRO-006 Physical & Personnel Security Program]]

and associated procedures.

Review:

- Public areas
- Controlled areas
- Restricted areas
- Employee access
- Visitor access
- Vendor access
- Contractor access
- Keys
- Access cards
- Warehouse cages
- Significant Information Technology areas

---

# 62. Medium-Term Priority 9: Conduct Physical Access Review

Complete the annual physical-access review.

Identify:

- Unnecessary access
- Obsolete credentials
- Excessive Restricted-area access
- Unreturned keys
- Unsupported exceptions

Document corrective action where required.

---

# 63. Medium-Term Priority 10: Evaluate Security Architecture

Review:

[[PRO-002 Enterprise Security Architecture Program]]

against actual implementation.

Evaluate:

- Network design
- Endpoint protection
- Server security
- Authentication
- Administrative access
- Cloud dependencies
- Infinity architecture
- Recovery architecture

Architecture should continue to follow business and risk requirements rather than unnecessary complexity.

---

# 64. Medium-Term Priority 11: Review Third-Party Concentration Risk

Determine whether excessive dependency exists on:

- Cloud providers
- Technology providers
- Critical suppliers
- Infinity support contractor
- Other important service providers

Identify practical exit or continuity strategies where required.

---

# 65. Medium-Term Priority 12: Conduct Security Program Effectiveness Review

Evaluate whether the security program is producing intended outcomes.

Consider:

- Risk trends
- Control effectiveness
- Findings
- Overdue corrective actions
- Incident trends
- Vulnerability trends
- Access-review results
- Recovery results
- Awareness results
- Third-party results
- Business changes

---

# 66. Medium-Term Priority 13: Reassess Treated Risks

When sufficient validated evidence exists, reassess affected risks.

The sequence is:

**Treatment Implemented**

↓

**Evidence Collected**

↓

**Control Validated**

↓

**Effectiveness Determined**

↓

**Risk Reassessed**

↓

**New Current Residual Risk Approved**

The original May 2013 risk assessment remains preserved.

---

# 67. Target Residual Risk Validation

Target residual risk should be compared with actual validated results.

Possible outcomes include:

**Validated Risk > Target**

Treatment was less effective than predicted.

**Validated Risk = Target**

Treatment performed approximately as predicted.

**Validated Risk < Target**

Treatment performed better than predicted.

None of these outcomes should be assumed before validation.

---

# 68. Medium-Term Priority 14: Review Security Program Roadmap

At the end of the first implementation cycle:

- Review completed work.
- Review delayed work.
- Review failed validation.
- Review changed business conditions.
- Review changed risks.
- Review new findings.
- Review resource constraints.
- Reprioritize remaining work.

The roadmap should evolve with enterprise risk.

---

# 69. Ongoing Activities

The following activities continue after initial implementation.

---

# 70. Ongoing Governance

Continue:

- Quarterly security and risk review
- Information Security and Risk Committee activity
- Risk acceptance review
- Exception review
- Treatment tracking
- Executive reporting

---

# 71. Ongoing Risk Management

Continue:

- Risk identification
- Risk reassessment
- Treatment review
- Risk acceptance
- Escalation
- Monitoring of material changes

Risk assessment is not a one-time project.

---

# 72. Ongoing Access Management

Continue:

- Joiner-Mover-Leaver activity
- Prompt termination
- Contractor-access review
- Dormant-account management
- Privileged-access management
- Emergency-access review

---

# 73. Ongoing Access Reviews

Perform:

- Ordinary-user review annually
- Privileged-access review quarterly
- Physical-access review annually

---

# 74. Ongoing Vulnerability Management

Perform internal vulnerability assessment monthly.

Maintain remediation targets:

- Critical: 7 days
- High: 30 days
- Moderate: 45 days
- Low: 60 days

Retest corrected vulnerabilities.

---

# 75. Ongoing Network Discovery

Perform network discovery and rogue wireless review every six months.

Investigate unexpected:

- Devices
- Services
- Wireless infrastructure
- Administrative exposure

---

# 76. Ongoing Patch Management

Continue centralized patch management.

Activities include:

- Evaluate
- Test
- Schedule
- Distribute
- Monitor
- Correct failures
- Maintain rollback capability where appropriate

---

# 77. Ongoing Configuration Management

Continue:

- Baseline maintenance
- Change authorization
- Testing
- Documentation
- Verification
- Configuration backup
- Emergency-change review

---

# 78. Ongoing Security Monitoring

Continue risk-appropriate monitoring of:

- Authentication
- Malware
- Security events
- Network conditions
- Monitoring failures

Continuous monitoring does not mean universal 24-hour human monitoring.

---

# 79. Ongoing Incident Response

Maintain:

- Incident contacts
- Classification
- Escalation
- Playbooks
- Evidence handling
- External response support
- Lessons learned
- Corrective actions

---

# 80. Ongoing Backup Operations

Continue:

- Automated backups
- Cloud backups
- Encrypted external-drive rotation
- Off-site storage
- Backup-job monitoring
- Recovery documentation

The external-drive model remains:

- 7 facilities
- 3 encrypted drives per facility
- 21 encrypted drives total
- 2 latest weekly generations per facility normally held off-site
- 14 encrypted drives normally held by the off-site provider

---

# 81. Ongoing Recovery Testing

Perform:

- Quarterly representative restore testing
- Annual meaningful Critical recovery testing

Recovery testing should produce evidence.

Failure should produce corrective action where appropriate.

---

# 82. Ongoing Awareness

Continue:

- Initial training
- Annual refresher training
- Annual knowledge assessment
- Monthly phishing simulation
- Targeted follow-up
- Incident-reporting reinforcement

---

# 83. Ongoing Infinity Security

Continue:

- Secure change
- Code review
- Security testing
- Contractor-access control
- Documentation
- Annual Infinity security assessment
- Annual application penetration testing
- Remediation
- Retesting
- Annual transferability review

---

# 84. Ongoing Third-Party Security

Continue:

- Third-party inventory
- Critical provider annual review
- Important provider biennial review
- Access review
- Contractual security oversight
- Incident notification
- Continuity review
- Exit planning

---

# 85. Ongoing Physical and Personnel Security

Continue:

- Facility-access management
- Visitor control
- Restricted-area control
- Personnel lifecycle coordination
- Confidentiality requirements
- Termination coordination
- Key-person dependency review
- Cross-training
- Environmental review

---

# 86. Ongoing Assurance

Continue:

- Annual assurance planning
- Risk-based assessments
- Critical-control review
- Evidence evaluation
- Finding management
- Corrective-action tracking
- Validation
- Retesting

---

# 87. Ongoing Metrics

Continue collecting and reviewing approved metrics from:

[[REG-005 Security Metrics Catalog]]

Metrics should be changed when they no longer provide useful decision information.

---

# 88. Ongoing Reporting

Maintain the three reporting levels.

### Operational

[[RPT-008 Operational Security Report & Dashboard]]

Focus:

- Execution
- Evidence
- Exceptions
- Technical detail

### Management

[[RPT-007 Management Security Report]]

Focus:

- Accountability
- Performance
- Action

### Executive

[[RPT-006 Executive Security Summary]]

Focus:

- Decisions
- Enterprise risk

---

# 89. Ongoing Findings Management

Use:

[[REG-004 Finding & Corrective Action Register]]

to maintain visibility into:

- Open findings
- Corrective actions
- Due dates
- Overdue actions
- Validation
- Retesting
- Recurring deficiencies

A reported fix does not close a finding without appropriate validation.

---

# 90. Ongoing Continuous Improvement

Use results from:

- Incidents
- Assessments
- Recovery tests
- Vulnerability management
- Metrics
- Findings
- Access reviews
- Third-party reviews
- Infinity assessments
- Business changes

to improve the security program.

---

# 91. Roadmap Dependencies

Major dependencies include:

| Initiative | Major Dependency |
|---|---|
| Access Review | Reliable identity and account inventory |
| Privileged Access Improvement | Account identification and administrative architecture |
| Smart-Card MFA | System support, credential issuance, enrollment, and recovery |
| Vulnerability Management | Asset visibility and scanning capability |
| Recovery Testing | BIA requirements, backup coverage, recovery procedures |
| Infinity Assessment | Application scope, documentation, contractor coordination |
| Third-Party Review | Third-party inventory and classification |
| Security Metrics | Reliable source data |
| Assurance | Defined controls and available evidence |
| Risk Reassessment | Validated control results |

---

# 92. Roadmap Risk Mapping

| Workstream | Primary Risks |
|---|---|
| Governance | All risks |
| IAM | R001, R005, R006, R009, R010, R011, R012, R015, R019 |
| Email / Awareness | R001, R002, R003, R004, R009 |
| Endpoint Security | R003, R004, R009, R014 |
| Network Security | R007, R008, R013, R017 |
| Vulnerability Management | R003, R004, R006, R007, R013 |
| Infinity Security | R006, R019, R028 |
| Third-Party Security | R018, R019, R020 |
| Incident Response | R001, R002, R003, R004, R006, R007, R009, R010, R012, R018 |
| Backup / Recovery | R016, R017, R021, R022, R023, R027, R028, R033, R034, R035 |
| Physical Security | R021, R022, R023, R024, R032, R034, R035 |
| Personnel Security | R011, R012, R026 |
| Financial Controls | R029, R030, R031 |
| Inventory Controls | R032 |
| Assurance | All risks |

---

# 93. Business Impact Analysis Alignment

Roadmap implementation should remain aligned with:

[[RPT-002 Business Impact Analysis]]

Critical and High business processes should receive priority where security weakness could prevent required recovery or continued operation.

Security priority and recovery priority should support one another.

---

# 94. Resource Allocation

Security resources should be prioritized according to:

- Risk
- Business impact
- Dependency
- Treatment urgency
- Control effectiveness
- Implementation feasibility

The roadmap does not assume Dunder Mifflin can implement every improvement simultaneously.

Sequencing is intentional.

---

# 95. Technology Acquisition Principle

Technology should be acquired because it satisfies a defined requirement.

The preferred sequence is:

**Requirement → Risk → Control Objective → Architecture → Technology Selection → Implementation → Evidence → Validation**

Avoid:

**Product Purchase → Search for Problem**

---

# 96. Proportionality

Dunder Mifflin is a company of approximately 138 employees.

Security controls should be proportionate to:

- Organizational size
- Business risk
- Information sensitivity
- Operational complexity
- Available personnel
- Business requirements

The goal is not to reproduce the security organization of a much larger enterprise.

The goal is to manage Dunder Mifflin's risk effectively.

---

# 97. No Unnecessary Complexity

The roadmap should not introduce complexity without a business or security reason.

Examples include:

- Unnecessary network segmentation
- Unnecessary alternate infrastructure
- Excessive approval layers
- Technology without defined control objectives
- Monitoring that produces information nobody uses

Complexity can itself create risk.

---

# 98. Documentation Requirement

Implementation should update applicable:

- Policies
- Standards
- Procedures
- Architecture documentation
- Asset records
- Recovery documentation
- Control inventory

A significant technical or configuration change is not complete until applicable recovery documentation has been reviewed and updated.

---

# 99. Evidence Requirement

Implementation should generate appropriate evidence.

Examples include:

- Approval records
- Configuration records
- Access records
- Review records
- Test results
- Training records
- Scan results
- Recovery results
- Contractor-access records

Evidence should be sufficient to support later assurance.

---

# 100. Evidence Integrity

Evidence must not be:

- Fabricated
- Backdated
- Improperly altered
- Manufactured to create the appearance that an activity occurred

Missing evidence should be treated as missing evidence.

---

# 101. Assurance Requirement

Major roadmap initiatives should identify how successful implementation will be validated.

Assessment methods may include:

- Inspection
- Observation
- Interviews
- Sampling
- Independent Performance
- Technical Testing
- Exercises
- Reconciliation

---

# 102. Implementation Does Not Mean Effective

A control may be implemented but fail to achieve its objective.

For this reason:

**Implemented ≠ Effective**

Control effectiveness requires appropriate assessment.

---

# 103. Treatment Does Not End at Deployment

The complete treatment lifecycle is:

**Plan**

↓

**Approve**

↓

**Implement**

↓

**Collect Evidence**

↓

**Validate**

↓

**Correct Deficiencies**

↓

**Retest**

↓

**Determine Effectiveness**

↓

**Reassess Risk**

---

# 104. Failed Validation

When a control fails validation:

1. Document the result.
2. Create or update the finding.
3. Determine the cause.
4. Assign corrective action.
5. Establish an accountable owner.
6. Establish an appropriate due date.
7. Implement correction.
8. Retest.
9. Update control effectiveness.
10. Reassess risk where appropriate.

Failed results must not be rewritten as successful results.

---

# 105. Roadmap Metrics

Roadmap performance may be evaluated using approved measures such as:

- Percentage of planned initiatives started
- Percentage of initiatives implemented
- Percentage awaiting validation
- Percentage validated
- Number of overdue material actions
- Number of failed validations
- Number of open significant findings
- Percentage of High risks with active treatment
- Percentage of Critical controls assessed

Definitions and reporting requirements are maintained in:

[[REG-005 Security Metrics Catalog]]

---

# 106. Roadmap Reporting

Roadmap status should be reported according to audience.

### Operational

Detailed implementation activity, evidence, exceptions, and blockers.

### Management

Progress, accountability, overdue actions, resource constraints, and corrective actions.

### Executive

Material risk reduction, unresolved exposure, significant resource requirements, and decisions.

---

# 107. Escalation

Escalate roadmap conditions when:

- A material treatment is significantly delayed.
- A High or Critical risk lacks appropriate action.
- A Critical control fails validation.
- Required resources are unavailable.
- A significant dependency cannot be resolved.
- A treatment proves ineffective.
- Business conditions materially change.
- A major incident changes the risk environment.

---

# 108. Risk Acceptance

If management determines that planned treatment should not proceed, the associated risk must not silently disappear from the roadmap.

The risk must be:

- Reassessed where appropriate
- Formally accepted by authorized management where applicable
- Documented
- Subject to required review

See:

[[POL-005 Risk Management Policy]]

---

# 109. Exceptions

Temporary deviations from roadmap-related security requirements should follow applicable exception and risk-management processes.

Exceptions should identify:

- Requirement
- Reason
- Risk
- Approval
- Compensating controls where applicable
- Duration
- Review or expiration

---

# 110. Change in Business Conditions

Roadmap priority should be reviewed when material changes occur involving:

- Business operations
- Organizational structure
- Technology
- Facilities
- Third parties
- Threat conditions
- Significant incidents
- Legal or contractual obligations
- Major findings

---

# 111. Annual Roadmap Review

At least annually, management should review:

- Risk changes
- Completed treatment
- Incomplete treatment
- Control effectiveness
- Findings
- Recovery results
- Incident trends
- Third-party changes
- Business changes
- Security metrics
- Resource requirements

The next roadmap cycle should reflect the results.

---

# 112. Roadmap Success

Roadmap success is not measured solely by the number of projects completed.

Successful implementation should produce:

- Better control performance
- Better evidence
- Fewer material deficiencies
- Improved recovery capability
- Improved accountability
- Reduced exposure where supported
- Better management information
- More defensible risk decisions

---

# 113. Executive Decision Points

Executive decisions may be required for:

- Material funding
- Significant staffing
- Risk acceptance
- Major third-party changes
- Major architecture changes
- Business continuity strategy
- Significant unresolved findings
- Treatments that cannot achieve acceptable risk

---

# 114. Relationship to the Executive Security Summary

[[RPT-006 Executive Security Summary]]

identifies enterprise-level security exposure and leadership priorities.

This roadmap converts those priorities into sequenced action.

---

# 115. Relationship to the Management Security Report

[[RPT-007 Management Security Report]]

should provide management visibility into:

- Roadmap progress
- Ownership
- Delays
- Corrective actions
- Metrics
- Risk impact

---

# 116. Relationship to the Operational Security Report

[[RPT-008 Operational Security Report & Dashboard]]

should provide operational evidence supporting roadmap implementation and control performance.

---

# 117. Relationship to Assurance

Roadmap implementation feeds:

[[PRO-008 Security Assurance & Continuous Improvement Program]]

The relationship is:

**Roadmap Initiative → Control Implementation → Evidence → Assessment → Finding → Corrective Action → Retest → Risk Reassessment**

---

# 118. Relationship to the Control Inventory

All material controls established through the roadmap should be reflected in:

[[REG-003 Enterprise Security Control Inventory]]

The inventory should show:

- Control
- Owner
- Related risk
- Implementation status
- Expected evidence
- Assessment method
- Effectiveness

---

# 119. Relationship to Findings

Implementation weaknesses identified through assurance should be recorded in:

[[REG-004 Finding & Corrective Action Register]]

A roadmap item reported as complete may still require corrective action if validation identifies a deficiency.

---

# 120. Relationship to Metrics

Implementation and control-performance measurements are defined in:

[[REG-005 Security Metrics Catalog]]

Metrics should support management action and not merely produce additional reporting.

---

# 121. Relationship to the Learning Path

[[GUIDE-001 GRC Learning Path]]

explains why roadmap activities occur in this order.

The roadmap demonstrates an important GRC principle:

> Security improvement begins with business and risk requirements, not with a list of products to purchase.

---

# 122. Relationship to the Project Artifact Map

[[GUIDE-002 Project Artifact Map]]

provides repository-wide navigation for the artifacts supporting roadmap implementation.

---

# 123. Immediate Horizon Summary

## 0–90 Days

Primary focus:

- Governance
- Risk-treatment tracking
- Authentication
- Privileged access
- Account lifecycle
- Warehouse accountability
- Email and phishing protection
- Awareness
- Backup validation
- Restore testing
- Incident response
- Network administration
- Configuration management
- Vulnerability remediation
- Infinity governance
- Contractor access
- Finding tracking

---

# 124. Near-Term Horizon Summary

## 3–6 Months

Primary focus:

- Access reviews
- Administrative workstation deployment
- Endpoint protection
- Secure configuration baselines
- Vulnerability assessment maturity
- Infinity assessment
- Infinity penetration testing
- Infinity transferability
- Third-party risk management
- Supplier resilience
- Fraud controls
- Inventory controls
- Personnel security
- Manual continuity
- BC/DR
- Cloud exit validation
- Security metrics
- Reporting

---

# 125. Medium-Term Horizon Summary

## 6–12 Months

Primary focus:

- Annual assurance
- Assessment work plans
- Critical-control validation
- Critical recovery testing
- Backup resilience
- Internet resilience
- Facility resilience
- Physical security review
- Architecture review
- Third-party concentration
- Program effectiveness
- Validated risk reassessment

---

# 126. Ongoing Summary

Recurring activities include:

- Governance
- Risk management
- Access management
- Access reviews
- Vulnerability management
- Network discovery
- Patching
- Configuration management
- Security monitoring
- Incident response
- Backup
- Recovery testing
- Awareness
- Infinity security
- Third-party security
- Physical and personnel security
- Assurance
- Metrics
- Reporting
- Findings management
- Continuous improvement

---

# 127. Program Maturity Direction

The roadmap moves Dunder Mifflin from a security environment containing useful but uneven safeguards toward a more structured enterprise security program.

The intended progression is:

**Informal / Inconsistent**

↓

**Defined**

↓

**Implemented**

↓

**Measured**

↓

**Validated**

↓

**Improved**

The objective is not maturity for its own sake.

The objective is reliable risk management.

---

# 128. Final Roadmap Principle

The Enterprise Security Program Roadmap connects security strategy to execution.

Its central principle is:

> **Prioritize the risks that matter, implement controls that address them, collect evidence that the controls operate, validate whether they work, and change the risk assessment only when the evidence supports the change.**

---

# 129. Related Artifacts

## Executive and Repository

- [[README]]
- [[RPT-006 Executive Security Summary]]
- [[RPT-007 Management Security Report]]
- [[RPT-008 Operational Security Report & Dashboard]]
- [[GUIDE-001 GRC Learning Path]]
- [[GUIDE-002 Project Artifact Map]]
- [[INDEX-001 Artifact Index]]

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

## Security Operations and Incident Response

- [[PRO-005 Security Operations Program]]
- [[PROC-008 Security Monitoring Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
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

---

# 130. Revision History

| Version | Date     | Description                                 | Approval |
| ------- | -------- | ------------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Enterprise Security Program Roadmap | CEO      |