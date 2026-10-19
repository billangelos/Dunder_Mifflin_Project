# GUIDE-001 GRC Learning Path

## Document Control

| Field | Value |
|---|---|
| Document ID | GUIDE-001 |
| Title | GRC Learning Path |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Program Change |

---

# 1. Purpose

This guide explains the Dunder Mifflin Enterprise Information Security and Risk Management Program as a practical Governance, Risk, and Compliance (GRC) learning path.

The repository contains policies, standards, procedures, plans, registers, reports, and technical security artifacts.

The purpose of this guide is to explain how those artifacts fit together.

The central lesson is:

> **GRC begins with understanding the business, not with selecting security controls.**

---

# 2. The GRC Learning Sequence

The program can be understood through the following sequence:

**Business → Assets → Information → Business Impact → Risk → Governance → Treatment → Controls → Procedures → Implementation → Evidence → Assessment → Findings → Remediation → Retest → Risk Reassessment → Reporting → Improvement**

Each stage provides information needed by the next.

Skipping stages can create controls that are expensive, unnecessary, ineffective, or disconnected from actual business risk.

---

# 3. Stage 1: Understand the Business

Before evaluating security, understand the organization being protected.

Begin with:

[[RPT-001 Enterprise Profile & Security Baseline]]

The enterprise profile establishes:

- What the company does
- How it makes money
- Where it operates
- How it is organized
- Who makes decisions
- What technology it uses
- What security capabilities already exist
- What important limitations exist

---

# 4. Why Business Context Comes First

A security control has value only in relation to something the organization needs to protect.

Before asking:

> What firewall should we use?

ask:

> What business process depends on this network?

Before asking:

> How quickly should we recover this server?

ask:

> How long can the business process supported by this server actually be unavailable?

Security decisions should follow business requirements.

---

# 5. Dunder Mifflin Business Model

Dunder Mifflin is primarily a business-to-business distributor and reseller of:

- Paper
- Stationery
- Office supplies

The company is not primarily a manufacturer.

Its core operating process is:

**Acquire Inventory → Sell → Process Orders → Fulfill → Deliver / Ship → Invoice → Receive Payment**

This process provides the business foundation for much of the security program.

---

# 6. Organizational Context

Dunder Mifflin operates:

- Scranton Headquarters
- Scranton Branch
- Syracuse Branch
- Utica Branch
- Rochester Branch
- Nashua Branch
- Akron Branch

The company has approximately 138 employees.

Understanding this scale matters.

A security program designed for a global company with tens of thousands of employees would be inappropriate for Dunder Mifflin.

---

# 7. Existing Environment Versus Desired Environment

One of the most important GRC distinctions is:

**What exists now?**

versus:

**What should exist?**

The security baseline documents the existing environment.

The rest of the program may identify additional controls that should be implemented.

Do not confuse the two.

---

# 8. Current and Proposed Controls

A proposed control does not receive credit merely because management intends to implement it.

For example:

**Current condition:**

No general multifactor authentication.

**Proposed treatment:**

Smart-card multifactor authentication where supported.

Until the treatment is implemented and validated, the current residual risk remains based on the existing control environment.

---

# 9. Stage 2: Identify Assets and Dependencies

After understanding the business, identify what the business depends on.

Use:

[[REG-001 Enterprise Asset Register]]

Assets include more than computers.

They include:

- Information
- Applications
- Infrastructure
- Facilities
- People
- Third parties
- Business processes
- Physical inventory
- Recovery resources

---

# 10. Asset Ownership

Asset ownership does not necessarily mean physical possession or technical administration.

An asset owner is accountable for the business use and protection requirements of the asset.

A custodian may operate or maintain it.

For example:

- The business may own the information.
- Information Technology may administer the system.
- A cloud provider may host the infrastructure.

These are different responsibilities.

---

# 11. Dependencies

A business process often depends on several assets.

Order processing may depend on:

- Internet connectivity
- Identity services
- Order Management System
- Customer Relationship Management
- Warehouse Management System
- Employees
- Cloud services
- Communications

A system can also depend on another system.

Understanding these relationships becomes essential during Business Impact Analysis and risk assessment.

---

# 12. Stage 3: Classify Information

Once assets are understood, determine how information should be protected.

Use:

[[STD-001 Information Classification Standard]]

Dunder Mifflin uses four classifications:

1. Public
2. Internal
3. Confidential
4. Restricted

---

# 13. Why Classification Matters

Classification helps determine:

- Who should have access
- How information should be handled
- How information should be stored
- How information should be transmitted
- How information should be disposed of
- What controls are justified

Not all information requires the same level of protection.

---

# 14. Classification Example

A public marketing document does not require the same controls as:

- Payroll records
- Authentication information
- Sensitive personnel information
- Highly sensitive business records

Security should be proportional to sensitivity and business need.

---

# 15. Backup Classification

Backups inherit the highest applicable classification of the information they contain.

Copying information into a backup does not reduce its sensitivity.

---

# 16. Stage 4: Perform the Business Impact Analysis

Before designing recovery systems, determine what the business actually requires.

Use:

[[RPT-002 Business Impact Analysis]]

The Business Impact Analysis (BIA) determines the effect of business-process disruption.

---

# 17. BIA Concepts

The BIA establishes:

### Maximum Tolerable Downtime

The longest disruption the business can tolerate before the impact becomes unacceptable.

### Recovery Time Objective

The target time for restoring the process or supporting capability.

### Recovery Point Objective

The maximum acceptable amount of data loss measured in time.

---

# 18. Example

Suppose a business process has:

- Maximum Tolerable Downtime: 24 hours
- Recovery Time Objective: 8 hours
- Recovery Point Objective: 4 hours

The business has established the requirement.

Information Technology can now design recovery capability against that requirement.

---

# 19. The Correct Recovery Sequence

The correct sequence is:

**Business Requirement → Criticality → MTD → RTO / RPO → Recovery Strategy → Technical Design → Implementation → Testing**

Do not begin by purchasing backup technology and then inventing recovery objectives around the product.

---

# 20. Business Criticality

Dunder Mifflin uses:

- Critical
- High
- Moderate
- Low

Criticality helps prioritize:

- Recovery
- Security treatment
- Testing
- Assurance
- Management attention

---

# 21. Stage 5: Identify Risk

Once the business, assets, dependencies, information, and impact requirements are understood, evaluate risk.

Use:

- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]

The enterprise assessment contains 35 material risks.

---

# 22. Risk Model

Dunder Mifflin uses:

**Risk Score = Likelihood × Impact**

Likelihood:

**1–5**

Impact:

**1–5**

---

# 23. Risk Rating

| Score | Rating |
|---:|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–16 | High |
| 17–25 | Critical |

---

# 24. Inherent Risk

Inherent risk is the risk before considering existing controls.

It answers:

> **How serious would this risk be without the controls we rely on?**

---

# 25. Current Residual Risk

Current residual risk is the risk remaining after considering controls that currently exist.

It answers:

> **What risk do we actually face with the current control environment?**

---

# 26. Target Residual Risk

Target residual risk is the predicted risk after proposed treatment is successfully implemented and validated.

It answers:

> **Where do we expect the risk to be after treatment works?**

---

# 27. The Three Risk Views

A risk can be represented as:

**Inherent → Current Residual → Target Residual**

Example:

### R001 Phishing / Credential Compromise

**20 Critical → 12 High → 6 Moderate**

This communicates:

- The underlying exposure is severe.
- Existing controls reduce some exposure.
- Additional treatment is expected to reduce it further.

---

# 28. Inherent Risk Still Matters

Residual risk is often emphasized because it represents current exposure.

That does not make inherent risk unimportant.

A risk with very high inherent exposure may deserve continued management attention even when controls reduce its residual rating.

Why?

Because the organization may depend heavily on those controls.

If an important control fails, exposure can move back toward the inherent condition.

---

# 29. Example: R003 Ransomware

R003 has:

- Inherent: 25 Critical
- Current Residual: 12 High
- Target Residual: 6 Moderate

Even if treatment eventually reduces the risk to Moderate, management should remember that ransomware has severe underlying potential.

Control effectiveness matters greatly because the uncontrolled exposure is Critical.

---

# 30. Stage 6: Establish Governance

Risk cannot be managed consistently without decision authority.

Use:

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-009 Security Governance Framework]]
- [[POL-001 Information Security Policy]]

Governance establishes:

- Authority
- Accountability
- Decision rights
- Risk ownership
- Policy structure
- Escalation
- Oversight

---

# 31. Governance Versus Management

Governance determines:

> **What should be required, who has authority, and who is accountable?**

Management determines:

> **How will those requirements be carried out?**

Operations performs the work.

Assurance evaluates whether it works.

---

# 32. Risk Ownership

A risk owner is accountable for managing a risk.

Other departments may participate in treatment, but shared participation should not eliminate clear accountability.

---

# 33. Information Security and Risk Committee

The Information Security and Risk Committee (ISRC) supports:

- Enterprise risk review
- Cross-functional coordination
- Significant risk treatment
- Risk acceptance review
- Security prioritization
- Executive decision support

---

# 34. Stage 7: Select Risk Treatment

Use:

[[RTP-001 Enterprise Risk Treatment Plan]]

The four primary treatment options are:

- Mitigate
- Transfer
- Avoid
- Accept

---

# 35. Mitigate

Mitigation reduces likelihood, impact, or both through controls.

Example:

R001 Phishing / Credential Compromise may be mitigated through:

- Improved email filtering
- Stronger authentication
- Awareness
- Phishing simulation
- Least privilege
- Monitoring
- Incident response

---

# 36. Transfer

Risk transfer shifts some financial or operational consequence to another party.

Examples may include:

- Insurance
- Contractual allocation
- Outsourced services

Transfer does not necessarily eliminate the underlying risk.

---

# 37. Avoid

Risk avoidance removes the activity creating the risk.

Example:

If an unnecessary high-risk service creates unacceptable exposure, the company may choose not to provide that service.

---

# 38. Accept

Risk acceptance is a deliberate decision to retain risk.

Acceptance should include:

- Authority
- Rationale
- Duration where appropriate
- Reassessment

Acceptance does not mean the risk disappeared.

---

# 39. Risk Acceptance Authority

| Risk Level | Authority |
|---|---|
| Low | Risk Owner |
| Moderate | Risk Owner and Executive Management |
| High | CEO after ISRC review |
| Critical | CEO after ISRC review; exceptional use |

High accepted risks must be reassessed within 90 days.

Critical accepted risks must be reassessed within 30 days.

---

# 40. Stage 8: Build the Policy Hierarchy

Security requirements move from broad authority toward specific execution.

A simplified hierarchy is:

**Program → Policy → Standard → Procedure → Implementation → Evidence**

---

# 41. Program

A program organizes a major security capability.

Example:

[[PRO-003 Identity and Access Management Program]]

---

# 42. Policy

A policy states management requirements.

Example:

[[POL-003 Access Control Policy]]

A policy may require least privilege.

It should not need to explain every technical configuration required to implement least privilege.

---

# 43. Standard

A standard defines mandatory implementation requirements.

Example:

[[STD-005 Authentication & Account Security Standard]]

Standards provide more specific requirements than policies.

---

# 44. Procedure

A procedure explains how required activity is performed.

Example:

[[PROC-001 Joiner-Mover-Leaver Procedure]]

A procedure may explain:

- Who initiates access
- Who approves access
- How access is created
- What happens during transfer
- How termination is processed
- What evidence is retained

---

# 45. Plan

A plan coordinates actions for a particular condition or objective.

Examples:

- [[PLN-001 Incident Response Plan]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]

---

# 46. Register

A register maintains structured records.

Examples:

- [[REG-001 Enterprise Asset Register]]
- [[REG-002 Enterprise Risk Register]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]

---

# 47. Stage 9: Design Controls

A control is a safeguard or countermeasure used to address a requirement or risk.

Controls may be:

- Administrative
- Technical
- Physical

They may also function as:

- Preventive
- Detective
- Corrective
- Recovery
- Deterrent
- Compensating

---

# 48. Control Inventory

Use:

[[REG-003 Enterprise Security Control Inventory]]

The control inventory connects security controls to:

- Control objectives
- Owners
- Requirements
- Risks
- Implementation
- Evidence
- Assessment
- Effectiveness

---

# 49. Control Design

A well-designed control should answer:

1. What problem is the control addressing?
2. What risk does it affect?
3. Who owns it?
4. What should it do?
5. How often should it operate?
6. What evidence should it produce?
7. How will effectiveness be assessed?

---

# 50. Defense in Depth

Important risks usually require multiple controls.

Ransomware is not adequately addressed by antivirus alone.

A layered treatment may include:

- Endpoint protection
- Patch management
- Least privilege
- Authentication
- Awareness
- Monitoring
- Incident response
- Backup
- Recovery testing

---

# 51. Control Dependency

Controls may depend on other controls.

For example:

A recovery process may depend on:

- Successful backups
- Valid credentials
- Current documentation
- Available infrastructure
- Qualified personnel
- Network access

Assessing only one component can create false confidence.

---

# 52. Stage 10: Implement the Control

A designed control has no operational value until it is implemented.

Implementation status may include:

- Planned
- Implementing
- Implemented
- Validation Pending
- Validated

---

# 53. Implemented Does Not Mean Effective

This distinction is fundamental.

**Implemented** means:

> The control has been deployed or established.

**Effective** means:

> Evidence supports that the control achieves its intended objective.

These are not the same conclusion.

---

# 54. Example: Backup

Suppose a backup system reports successful jobs every night.

The control is implemented.

That does not prove:

- The backup contains everything required.
- The backup can be restored.
- Recovery can meet the RTO.
- Data loss can meet the RPO.
- The recovered application actually works.

Testing is required.

---

# 55. Stage 11: Produce Evidence

Controls should produce evidence demonstrating operation.

Evidence may include:

- Logs
- Tickets
- Reports
- Configuration records
- Access-review records
- Backup records
- Training records
- Scan results
- Test results
- Approval records
- Incident records

---

# 56. Evidence Quality

Evidence should be evaluated for:

- Relevance
- Reliability
- Completeness
- Timeliness
- Integrity

---

# 57. Evidence Integrity

Never:

- Fabricate evidence
- Backdate evidence
- Alter failed results
- Invent completion
- Create documentation claiming activity occurred when it did not

A failed test is useful evidence.

A fabricated successful test is not.

---

# 58. Stage 12: Assess the Control

Use:

[[PRO-008 Security Assurance & Continuous Improvement Program]]

Assurance asks:

> **How do we know the control actually works?**

---

# 59. Assessment Methods

Assessment may include:

- Inspection
- Observation
- Interviews
- Sampling
- Independent Performance
- Technical Testing
- Exercises
- Reconciliation

The assessment method should match the control being evaluated.

---

# 60. Independent Performance

Independent Performance means the assessor performs an approved procedure independently when doing so provides stronger evidence than simply reviewing records.

Example:

Instead of only asking whether a backup can be restored, an assessor may perform or observe an authorized restore procedure and evaluate the result.

---

# 61. Assessment Independence

Independence should be proportional to risk.

Not every control requires an outside auditor.

Higher-risk or more important controls may justify greater independence.

---

# 62. Stage 13: Build an Assessment Work Plan

Before performing a material assessment, define exactly what will be tested.

Use:

[[TMP-001 Assessment Work Plan Template]]

---

# 63. Assessment Work Plan

The Assessment Work Plan identifies:

- Assessment objective
- Scope
- Requirement
- Control
- Evidence
- Assessment method
- Sample
- Procedure
- Expected result
- Reporting approach

---

# 64. Why the Assessment Work Plan Matters

Without a work plan, testing can become:

- Inconsistent
- Incomplete
- Difficult to repeat
- Poorly documented
- Disconnected from the requirement

The work plan creates a bridge between the control requirement and the assessment evidence.

---

# 65. Assessment Example

Suppose the requirement states:

> Privileged access must be reviewed quarterly.

The work plan might identify:

- Population: privileged accounts
- Evidence: current account list and review records
- Method: inspection and sampling
- Procedure: compare authorized privileged accounts against actual privileged accounts
- Expected result: all privileged accounts have valid authorization and review

Now the assessment has a defined objective.

---

# 66. Stage 14: Reach a Finding

A finding is:

> **A documented conclusion supported by evidence concerning whether a requirement, control, process, or expected outcome is satisfied.**

A finding is not merely an opinion.

---

# 67. Finding Outcomes

Assessment may conclude that a condition is:

- Satisfactory
- Partially satisfactory
- A deficiency
- A significant deficiency
- Not applicable
- Unable to determine

Material deficiencies requiring corrective action are tracked in:

[[REG-004 Finding & Corrective Action Register]]

---

# 68. Findings Need Evidence

A useful finding should identify:

- Requirement
- Control
- Condition
- Evidence
- Risk or impact
- Responsible owner
- Required corrective action where applicable

---

# 69. Finding Versus Risk

A finding and a risk are not the same thing.

### Finding

A specific evidence-supported condition.

### Risk

Uncertainty that may affect business objectives.

A finding may increase a risk, demonstrate control weakness, or trigger risk reassessment.

---

# 70. Example

Finding:

> Quarterly privileged-access review was not completed.

Related risk:

**R010 Unauthorized / Excessive Access**

The finding is the observed control deficiency.

R010 is the enterprise risk affected by that deficiency.

---

# 71. Stage 15: Correct the Deficiency

A finding requiring remediation should receive:

- Corrective action
- Accountable owner
- Target date
- Required evidence
- Validation method

Corrective-action status may include:

- Open
- In Progress
- Validation Pending
- Closed

---

# 72. Corrective Action Is Not Closure

A technician saying:

> Fixed.

does not automatically close a finding.

The correction should be validated.

---

# 73. Stage 16: Retest

Retesting determines whether corrective action actually resolved the deficiency.

If the retest fails:

- The deficiency remains visible.
- Corrective action should be revised.
- The finding remains open as appropriate.
- Control effectiveness should reflect the result.
- Related risk may require reassessment.

---

# 74. Complete Assurance Chain

The assurance chain is:

**Requirement → Control → Implementation → Evidence → Assessment → Finding → Corrective Action → Retest → Control Effectiveness**

Risk management then extends the chain:

**Control Effectiveness → Risk Reassessment**

---

# 75. Stage 17: Reassess Risk

Validated evidence may justify changing current residual risk.

Do not simply replace the historical risk assessment.

Preserve:

- Original inherent risk
- Original current residual risk
- Treatment
- Assessment results
- Findings
- Corrective actions
- Retest
- New risk assessment

---

# 76. Target Risk Is a Prediction

Target residual risk is not guaranteed.

After treatment and validation, actual residual risk may be:

- Higher than target
- Equal to target
- Lower than target

Evidence determines the result.

---

# 77. R027 Backup Failure Example

Assume a Critical process has:

- RTO: 8 hours
- RPO: 4 hours

An initial recovery test produces:

- Recovery time: 11 hours 37 minutes
- Data loss: 58 minutes

Result:

- RTO: Fail
- RPO: Pass

The backup existed.

The complete recovery requirement was not satisfied.

---

# 78. Corrective Action

Assume Dunder Mifflin:

- Improves recovery documentation
- Corrects configuration problems
- Improves recovery sequencing
- Clarifies responsibilities

A later retest produces:

- Recovery time: 6 hours 42 minutes
- Data loss: 47 minutes

Result:

- RTO: Pass
- RPO: Pass

These values are illustrative and are not actual recovery-test evidence.

---

# 79. What Changed?

The second test provides evidence that recovery capability improved.

Management may now reassess R027.

The reasoning is:

**Treatment → Evidence → Test → Result → Control Effectiveness → Risk Reassessment**

Not:

**Treatment planned → Risk reduced**

---

# 80. Stage 18: Monitor Continuously

Continuous monitoring means maintaining risk-appropriate ongoing awareness.

It does not mean every control must be watched by a person 24 hours a day.

Monitoring frequency should reflect:

- Risk
- Criticality
- Exposure
- Control importance
- Available capability

---

# 81. Operational Monitoring

Use:

- [[PRO-005 Security Operations Program]]
- [[PROC-008 Security Monitoring Procedure]]
- [[TMP-002 Operational Security Checklist]]
- [[RPT-008 Operational Security Report & Dashboard]]

Operational monitoring identifies:

- Exceptions
- Failures
- Trends
- Events
- Missing evidence
- Conditions requiring investigation

---

# 82. Stage 19: Measure

Use:

[[REG-005 Security Metrics Catalog]]

Metrics may include:

### Key Performance Indicators

Measure whether security processes are performing as expected.

### Key Risk Indicators

Indicate changing risk exposure.

### Operational Measures

Provide information needed to operate security activities.

---

# 83. Metrics Are Not the Goal

A metric exists to support a decision.

Collecting data that nobody uses does not improve security.

For every metric, ask:

1. Why are we measuring this?
2. What decision could this measurement affect?
3. Who needs the information?
4. What action occurs when the value becomes unacceptable?

---

# 84. Example KPI

Metric:

**Percentage of required vulnerability assessments completed**

This measures process execution.

It does not by itself prove that vulnerability risk is acceptable.

---

# 85. Example KRI

Metric:

**Number of overdue Critical vulnerabilities**

An increase may indicate rising security exposure.

This can support management escalation or risk reassessment.

---

# 86. Missing Metrics

Do not report missing data as zero.

Use:

- Not Measured
- Insufficient Data
- Not Applicable

where appropriate.

An inability to produce required evidence may itself indicate a control problem.

---

# 87. Stage 20: Report at the Correct Level

Security information should be reported differently depending on the audience.

Dunder Mifflin uses three reporting levels.

---

# 88. Executive Reporting

Use:

[[RPT-006 Executive Security Summary]]

Executive reporting focuses on:

- Enterprise risk
- Business impact
- Significant exposure
- Decisions
- Resources

Executives generally do not need raw technical data.

---

# 89. Management Reporting

Use:

[[RPT-007 Management Security Report]]

Management reporting focuses on:

- Accountability
- Performance
- Corrective action
- Trends
- Resource constraints
- Escalation

---

# 90. Operational Reporting

Use:

[[RPT-008 Operational Security Report & Dashboard]]

Operational reporting focuses on:

- Execution
- Evidence
- Exceptions
- Technical detail

---

# 91. Reporting Principle

The reporting model is:

> **Executive → decisions and enterprise risk**  
> **Management → accountability, performance, and action**  
> **Operational → execution, evidence, exceptions, and technical detail**

---

# 92. Reporting Chain

Information moves upward through:

**Technical Evidence → Operational Exception → Management Impact → Enterprise Risk → Executive Decision**

This prevents two common problems:

- Executives receiving excessive technical detail
- Important technical problems never reaching business decision-makers

---

# 93. Example Reporting Flow

Suppose vulnerability scanning identifies a serious vulnerability.

### Operational

The technical team records:

- Vulnerability
- Asset
- Severity
- Age
- Remediation status

### Management

Management sees:

- The vulnerability is overdue.
- A Critical business system is affected.
- Remediation requires downtime.
- Business scheduling is delaying correction.

### Executive

Executive leadership may see:

- A significant enterprise risk remains unresolved.
- Business interruption may be required to correct it.
- A decision is needed.

The same issue is reported differently at each level.

---

# 94. Stage 21: Improve the Program

Security governance is not complete after controls are deployed.

Use:

[[PRO-008 Security Assurance & Continuous Improvement Program]]

Improvement follows:

**Evidence → Assessment → Finding → Corrective Action → Validation → Retest → Risk Reassessment**

---

# 95. Improvement Is Evidence-Based

Program maturity should not be demonstrated by rewriting history.

If a control originally failed:

- Preserve the failure.
- Document the finding.
- Correct it.
- Retest it.
- Show the improved result.

That history demonstrates improvement.

---

# 96. Historical Integrity

A mature program preserves:

- Original assessment
- Original risk rating
- Original control condition
- Findings
- Corrective actions
- Failed tests
- Successful retests
- Revised risk assessments

Improvement is more credible when the evidence shows how it occurred.

---

# 97. Putting the Entire Program Together

The complete Dunder Mifflin traceability model is:

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

---

# 98. Example Traceability: Phishing

### Business Requirement

Protect business operations and sensitive information.

### Asset

Employee accounts, email, business applications.

### Risk

R001 Phishing / Credential Compromise.

### Treatment

Mitigate.

### Governance

[[POL-003 Access Control Policy]]

[[POL-006 Security Awareness & Training Policy]]

### Controls

- Improved email filtering
- Smart-card multifactor authentication where supported
- Least privilege
- Awareness
- Monthly phishing simulation
- Monitoring

### Procedures

Applicable IAM, monitoring, and incident-response procedures.

### Evidence

- Authentication records
- Training records
- Simulation results
- Incident records

### Assessment

Evaluate whether required controls operate as intended.

### Finding

Document material deficiencies.

### Remediation

Correct the deficiency.

### Retest

Validate the correction.

### Risk Reassessment

Determine whether R001 current residual risk should change.

---

# 99. Example Traceability: Backup Failure

### Business Requirement

Recover Critical processes within BIA requirements.

### BIA

Defines RTO and RPO.

### Risk

R027 Backup Failure.

### Treatment

Improve backup validation and recovery capability.

### Governance

[[POL-010 Business Continuity & Disaster Recovery Policy]]

### Procedure

[[PROC-012 Backup & Recovery Procedure]]

### Evidence

- Backup records
- Restore records
- Recovery-test results

### Assessment

Compare actual recovery against RTO and RPO.

### Finding

Document failure to meet required recovery performance.

### Corrective Action

Improve recovery capability.

### Retest

Repeat recovery testing.

### Risk Reassessment

Reevaluate R027 using validated results.

---

# 100. Example Traceability: Infinity

### Business Requirement

Maintain a secure and supportable customer ordering application.

### Asset

Infinity.

### Risks

- R006 Infinity Compromise
- R019 Infinity Contractor

### Governance

[[POL-012 Application & Secure Development Policy]]

### Program

[[PRO-007 Secure Software Development Lifecycle Program]]

### Standard

[[STD-009 Infinity Security Standard]]

### Procedures

- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-019 Application Security Assessment Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]

### Assurance

- Annual Infinity security assessment
- Annual application penetration test
- Annual transferability review

### Transferability

[[RPT-004 Infinity Transferability Review]]

### Evidence

- Code-review records
- Change records
- Test results
- Access records
- Assessment results
- Repository evidence
- Documentation

### Findings

Tracked in:

[[REG-004 Finding & Corrective Action Register]]

### Risk Reassessment

Validated evidence may support reassessment of R006 or R019.

---

# 101. Example Traceability: Unauthorized Access

### Business Requirement

Ensure people receive only the access required for authorized work.

### Risk

R010 Unauthorized / Excessive Access.

### Policy

[[POL-003 Access Control Policy]]

### Program

[[PRO-003 Identity and Access Management Program]]

### Procedures

- [[PROC-001 Joiner-Mover-Leaver Procedure]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-003 Access Review Procedure]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]

### Evidence

- Access requests
- Approvals
- Account records
- Access reviews
- Termination records

### Assessment

Determine whether access remains authorized and appropriate.

### Finding

Document material unauthorized or excessive access.

### Remediation

Remove or correct access.

### Retest

Verify access is corrected.

### Risk Reassessment

Determine whether evidence supports changing R010.

---

# 102. Common GRC Mistake: Starting With Controls

A common mistake is:

> We should implement this security technology because it is considered best practice.

A better question is:

> What requirement or risk does this control address?

A control without a clear purpose can become:

- Expensive
- Difficult to maintain
- Poorly adopted
- Impossible to justify
- Unrelated to meaningful risk

---

# 103. Common GRC Mistake: Compliance Equals Security

Passing an audit does not automatically mean the organization is secure.

Compliance may demonstrate that specified requirements were satisfied.

Security risk may still exist outside those requirements.

GRC should connect compliance activity to actual business risk.

---

# 104. Common GRC Mistake: Documentation Equals Implementation

A policy stating:

> Multifactor authentication is required.

does not prove multifactor authentication exists.

Evidence is required.

---

# 105. Common GRC Mistake: Implementation Equals Effectiveness

A firewall can exist and still be poorly configured.

A backup can exist and still fail restoration.

An access review can occur and still fail to remove inappropriate access.

Implementation must be distinguished from effectiveness.

---

# 106. Common GRC Mistake: Testing Equals Success

Performing a test does not mean the control passed.

A failed test can be extremely valuable because it identifies a weakness before a real incident exposes it.

---

# 107. Common GRC Mistake: Closing Findings Too Early

A finding should not be closed merely because someone reports that corrective action is complete.

Where appropriate:

**Correct → Validate → Retest → Close**

---

# 108. Common GRC Mistake: Hiding Failure

A mature security program does not require every test to succeed.

It requires failures to be:

- Identified
- Documented
- Understood
- Corrected
- Retested

---

# 109. Common GRC Mistake: Treating Risk Scores as Facts

Risk scoring supports structured decision-making.

A score is not a physical measurement.

Likelihood and impact involve professional judgment.

The value of the method comes from:

- Consistency
- Defined criteria
- Documented rationale
- Repeatability
- Decision usefulness

---

# 110. Common GRC Mistake: Ignoring Inherent Risk

Two risks may both have Moderate residual risk while having very different inherent exposure.

A risk reduced from Critical to Moderate may depend heavily on important controls.

A risk that was Moderate before controls may require less assurance attention.

Residual rating alone does not tell the complete story.

---

# 111. Common GRC Mistake: Confusing Findings With Risks

Finding:

> A required quarterly access review was missed.

Risk:

> Unauthorized or excessive access may remain active.

The finding provides evidence affecting the risk.

It is not the risk itself.

---

# 112. Common GRC Mistake: Measuring Everything

Not every available data point should become a security metric.

A useful metric should:

- Have a defined purpose
- Have an owner
- Have a reliable source
- Support interpretation
- Influence a decision or action

---

# 113. Common GRC Mistake: Sending Technical Detail to Executives

Executive leadership generally needs:

- Business impact
- Risk
- Decision
- Resource requirement

It generally does not need pages of:

- Vulnerability identifiers
- Firewall logs
- Authentication events
- Patch details

Those belong at the operational level unless a specific technical fact is necessary for the decision.

---

# 114. How to Study This Repository

A learner should study the repository in the following order:

1. [[RPT-001 Enterprise Profile & Security Baseline]]
2. [[REG-001 Enterprise Asset Register]]
3. [[STD-001 Information Classification Standard]]
4. [[RPT-002 Business Impact Analysis]]
5. [[RPT-003 Enterprise Risk Assessment]]
6. [[REG-002 Enterprise Risk Register]]
7. [[RTP-001 Enterprise Risk Treatment Plan]]
8. [[PRO-009 Security Governance Framework]]
9. Policies
10. Programs
11. Standards
12. Procedures
13. [[REG-003 Enterprise Security Control Inventory]]
14. [[PRO-008 Security Assurance & Continuous Improvement Program]]
15. [[PLN-005 Annual Assurance Plan]]
16. [[TMP-001 Assessment Work Plan Template]]
17. [[REG-004 Finding & Corrective Action Register]]
18. [[REG-005 Security Metrics Catalog]]
19. [[RPT-008 Operational Security Report & Dashboard]]
20. [[RPT-007 Management Security Report]]
21. [[RPT-006 Executive Security Summary]]

This order follows the logic of the security program rather than simply the repository folder order.

---

# 115. First Learning Objective

After studying the enterprise context, the learner should be able to answer:

- What does the company do?
- What makes money?
- What processes are important?
- What systems support those processes?
- What information is sensitive?
- What facilities matter?
- What third parties matter?
- What existing security controls are already present?

If these questions cannot be answered, risk analysis is premature.

---

# 116. Second Learning Objective

After studying the BIA, the learner should be able to explain:

- Why one process is more critical than another
- What MTD means
- What RTO means
- What RPO means
- Why business requirements should precede recovery architecture

---

# 117. Third Learning Objective

After studying the risk assessment, the learner should be able to distinguish:

- Threat
- Vulnerability
- Risk
- Control
- Inherent risk
- Current residual risk
- Target residual risk

---

# 118. Fourth Learning Objective

After studying governance and policy, the learner should be able to distinguish:

- Governance
- Policy
- Standard
- Procedure
- Plan
- Register
- Control

---

# 119. Fifth Learning Objective

After studying the control inventory, the learner should be able to explain:

- Why a control exists
- What risk it affects
- Who owns it
- What evidence it should produce
- How it should be assessed

---

# 120. Sixth Learning Objective

After studying assurance, the learner should be able to distinguish:

- Control design
- Control implementation
- Control operation
- Control effectiveness
- Evidence
- Assessment
- Finding
- Corrective action
- Retest

---

# 121. Seventh Learning Objective

After studying the reporting artifacts, the learner should be able to take one technical issue and explain it differently to:

- An operator
- A manager
- An executive

That is an important GRC skill.

---

# 122. Practical Exercise 1: Follow One Risk

Select one risk from:

[[REG-002 Enterprise Risk Register]]

Follow it through:

1. Business context
2. Asset
3. BIA if applicable
4. Risk assessment
5. Treatment
6. Policy
7. Control
8. Procedure
9. Evidence
10. Assessment
11. Potential finding
12. Corrective action
13. Retest
14. Risk reassessment
15. Reporting

---

# 123. Practical Exercise 2: Evaluate One Control

Select one control from:

[[REG-003 Enterprise Security Control Inventory]]

Answer:

1. What requirement created it?
2. What risk does it address?
3. Who owns it?
4. Is it preventive, detective, corrective, or recovery?
5. Is it implemented?
6. What evidence should exist?
7. How would you assess it?
8. What would failure look like?
9. What finding might result?
10. What risk could be affected?

---

# 124. Practical Exercise 3: Build an Assessment

Use:

[[TMP-001 Assessment Work Plan Template]]

Select a control and define:

- Objective
- Scope
- Requirement
- Evidence
- Method
- Sample
- Procedure
- Expected result

Then determine what evidence would support a conclusion.

---

# 125. Practical Exercise 4: Write a Finding

Create a hypothetical deficiency.

Document:

- Requirement
- Condition
- Evidence
- Risk
- Owner
- Corrective action
- Validation method

Then determine what would be required to close it.

Do not create fictional evidence and present it as an actual Dunder Mifflin finding.

---

# 126. Practical Exercise 5: Translate Technical Detail

Select a technical issue.

Write it three ways:

### Operational

What happened technically?

### Management

What needs to be corrected, by whom, and when?

### Executive

What business risk or decision matters?

This exercise demonstrates the reporting model.

---

# 127. Practical Exercise 6: Challenge a Risk Score

Select one risk.

Ask:

- Is the likelihood reasonable?
- Is the impact reasonable?
- What evidence supports the current residual rating?
- Are controls receiving credit they have not earned?
- Is target residual risk realistic?
- What evidence would cause the rating to change?

A GRC professional should be able to challenge assumptions constructively.

---

# 128. Practical Exercise 7: Test Recovery Logic

Select a process from:

[[RPT-002 Business Impact Analysis]]

Identify:

- MTD
- RTO
- RPO
- Supporting systems
- Recovery dependencies
- Required backup
- Required recovery test

Then determine what evidence would prove the recovery strategy actually satisfies the business requirement.

---

# 129. Practical Exercise 8: Review Infinity

Study:

- [[PRO-007 Secure Software Development Lifecycle Program]]
- [[STD-009 Infinity Security Standard]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-019 Application Security Assessment Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]
- [[RPT-004 Infinity Transferability Review]]

Then explain how Dunder Mifflin addresses:

- Application security
- Contractor access
- Change control
- Security testing
- Source ownership
- Knowledge dependency
- Transferability

---

# 130. Practical Exercise 9: Follow a Failed Control

Assume a control fails.

Trace:

**Failed Control → Evidence → Finding → Corrective Action → Retest → Effectiveness → Risk Reassessment → Management Reporting**

This is one of the most important workflows in the repository.

---

# 131. Practical Exercise 10: Explain the Program Without Security Jargon

Explain the entire program to a business manager without using specialized security terminology.

A strong explanation might be:

> First we determine what the business needs and what it depends on. Then we identify what could interfere with those objectives. We decide which problems require action, put safeguards in place, collect evidence showing whether they work, test them, correct weaknesses, and update management when the risk changes.

Being able to explain security simply is an important professional skill.

---

# 132. The GRC Professional's Role

A GRC professional does not need to personally operate every technical control.

The GRC professional should understand enough to ask:

- What is the requirement?
- What are we protecting?
- What could go wrong?
- What control addresses it?
- Who owns the control?
- What evidence should exist?
- How do we know it works?
- What happens if it fails?
- Who needs to know?

---

# 133. Technical Knowledge Still Matters

GRC is not separate from technology.

Understanding:

- Networks
- Authentication
- Servers
- Endpoints
- Vulnerabilities
- Logging
- Encryption
- Backup
- Applications
- Cloud services

helps a GRC professional evaluate whether controls and evidence make sense.

The goal is not necessarily to become the primary administrator of every technology.

The goal is to understand the relationship between technology and risk.

---

# 134. Business Knowledge Matters Equally

A technically perfect security control may still be inappropriate if it:

- Prevents necessary business activity
- Costs more than the risk justifies
- Creates unacceptable operational disruption
- Protects something that is not important
- Fails to protect the actual business dependency

GRC connects security to business objectives.

---

# 135. Security Is Not Zero Risk

The objective is not:

> Eliminate every risk.

That is rarely possible.

The objective is:

> Understand risk, make informed decisions, apply appropriate controls, validate their performance, and keep residual risk within acceptable limits.

---

# 136. Documentation Is a Decision System

The artifacts in this repository should not be viewed as paperwork created merely to satisfy documentation requirements.

Together they record:

- What the business needs
- What can go wrong
- What management decided
- What controls should exist
- Who is responsible
- What evidence should exist
- Whether controls work
- What failed
- What was corrected
- What risk remains

---

# 137. GRC Maturity

A more mature GRC program is not simply one with more documents.

Maturity is demonstrated when:

- Requirements are clear.
- Risks are understood.
- Controls have purpose.
- Accountability is defined.
- Evidence is reliable.
- Testing is meaningful.
- Findings lead to correction.
- Risk changes are supported by evidence.
- Reporting supports decisions.

---

# 138. Portfolio Interpretation

This repository demonstrates the development of an integrated enterprise security program rather than isolated documents.

The artifacts should be evaluated as connected components.

For example:

A risk register without treatment is incomplete.

A policy without controls is incomplete.

A control without evidence is difficult to validate.

Evidence without assessment does not automatically establish effectiveness.

A finding without corrective action does not improve the organization.

Corrective action without retesting may not prove the problem was resolved.

---

# 139. CISSP Relationship

The project also demonstrates concepts across all eight CISSP domains.

Use:

[[RPT-005 CISSP Domain Crosswalk]]

The project is not organized around memorizing CISSP domains.

Instead, the domains appear naturally as the enterprise security program is built.

---

# 140. Learning Outcome

After studying this repository, the learner should be able to explain the complete security-governance lifecycle:

1. Understand the business.
2. Identify assets and dependencies.
3. Classify information.
4. Determine business impact.
5. Identify and assess risk.
6. Establish governance.
7. Select treatment.
8. Establish policy and standards.
9. Design controls.
10. Define procedures.
11. Implement controls.
12. Collect evidence.
13. Assess effectiveness.
14. Document findings.
15. Perform corrective action.
16. Retest.
17. Reassess risk.
18. Monitor.
19. Measure.
20. Report.
21. Improve.

---

# 141. Final GRC Model

The entire project can be summarized as:

> **Understand what the business needs.**
>
> **Determine what could prevent it from achieving those needs.**
>
> **Decide what level of risk is acceptable.**
>
> **Implement appropriate controls.**
>
> **Collect evidence.**
>
> **Test whether the controls work.**
>
> **Correct what does not work.**
>
> **Reassess the risk.**
>
> **Give the right information to the right decision-maker.**
>
> **Repeat as the business and risk environment change.**

---

# 142. Final Principle

The strongest lesson from the program is:

> **A security program is not a collection of controls. It is a system for making risk-informed business decisions and proving whether those decisions produce the intended result.**

---

# 143. Related Artifacts

## Enterprise Context

- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[REG-001 Enterprise Asset Register]]
- [[STD-001 Information Classification Standard]]
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

## Security Controls

- [[REG-003 Enterprise Security Control Inventory]]

## Assurance and Improvement

- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[PLN-005 Annual Assurance Plan]]
- [[TMP-001 Assessment Work Plan Template]]
- [[TMP-002 Operational Security Checklist]]

## Secure Development

- [[PRO-007 Secure Software Development Lifecycle Program]]
- [[STD-009 Infinity Security Standard]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-019 Application Security Assessment Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]
- [[RPT-004 Infinity Transferability Review]]

## Reporting

- [[RPT-006 Executive Security Summary]]
- [[RPT-007 Management Security Report]]
- [[RPT-008 Operational Security Report & Dashboard]]

## Reference

- [[RPT-005 CISSP Domain Crosswalk]]
- [[INDEX-001 Artifact Index]]
- [[REG-006 Document Control Register]]
- [[REG-007 Cross-Reference Matrix]]

---

# 144. Revision History

| Version | Date     | Description               | Approval |
| ------- | -------- | ------------------------- | -------- |
| 1.0     | May 2013 | Initial GRC Learning Path | CEO      |