# POL-005 Risk Management Policy

## Document Control

| Field | Value |
|---|---|
| Document ID | POL-005 |
| Title | Risk Management Policy |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Change |

---

# 1. Purpose

This policy establishes Dunder Mifflin's requirements for identifying, analyzing, evaluating, treating, accepting, monitoring, and reassessing enterprise security risk.

Risk management must support informed business decisions by providing management with a consistent understanding of:

- What could go wrong
- What business resources or objectives could be affected
- How likely the event is
- How significant the consequences could be
- What controls currently reduce the risk
- What residual risk remains
- Whether additional treatment is required
- Who owns the risk
- Who has authority to accept the risk

Risk management must support business objectives rather than operate as an isolated Information Technology activity.

---

# 2. Scope

This policy applies to security-related risk involving:

- Business processes
- Information
- Applications
- Infrastructure
- Endpoints
- Networks
- Cloud services
- Facilities
- Warehouses
- Personnel
- Physical security
- Suppliers
- Technology providers
- Contractors
- Financial processes
- Transportation
- Business continuity
- Disaster recovery
- Secure development

Risk may originate from intentional, accidental, environmental, operational, technical, physical, personnel, or third-party sources.

---

# 3. Objectives

The risk-management process must:

1. Identify meaningful enterprise risks.
2. Evaluate risk consistently.
3. Distinguish inherent risk from residual risk.
4. Evaluate existing control effectiveness.
5. Assign accountable risk owners.
6. Prioritize treatment.
7. Document management decisions.
8. Establish target residual risk.
9. Validate treatment effectiveness.
10. Reassess risk after material change.
11. Preserve historical risk information.
12. Support management reporting.
13. Support continuous improvement.

---

# 4. Risk Governance

Risk management operates under [[PRO-009 Security Governance Framework]].

The Information Security and Risk Committee (ISRC) provides coordinated management oversight of significant security risks.

Risk decisions must be made by individuals with appropriate business authority.

Information Technology and security personnel may identify, analyze, monitor, and help treat risk without automatically becoming the owner of every risk involving technology.

---

# 5. Risk Ownership

Each material risk must have an accountable owner.

The risk owner should be the management role with appropriate responsibility for the affected business objective, process, asset, or consequence.

Examples include:

| Risk Area | Typical Owner |
|---|---|
| Cybersecurity | CIO |
| Technology Infrastructure | CIO |
| Applications | CIO / Applicable Business Owner |
| Information | CIO / Information Owner |
| Warehouse Operations | COO |
| Inventory | COO |
| Facilities | COO |
| Transportation | COO |
| Suppliers | COO |
| Accounting | CFO |
| Financial Fraud | CFO |
| Payroll | CFO / Human Resources |
| Personnel Lifecycle | Human Resources / Applicable Executive |
| Enterprise Continuity | CEO / COO |

Shared responsibility may exist when risk crosses organizational boundaries.

Shared responsibility must not result in unclear accountability.

---

# 6. Risk Owner Responsibilities

Risk owners must:

- Understand assigned risks.
- Participate in risk evaluation.
- Review treatment options.
- Support treatment decisions.
- Identify business requirements.
- Provide resources or escalate resource needs.
- Review significant findings.
- Support reassessment.
- Accept risk only within authorized authority.
- Escalate risk exceeding their acceptance authority.

Risk ownership does not require the owner to personally implement every control.

---

# 7. Risk Identification

Risks must be identified using relevant sources including:

- Business-process analysis
- Asset identification
- Information classification
- Business Impact Analysis
- Threat analysis
- Vulnerability assessment
- Security incidents
- Assessment findings
- Operational experience
- Third-party dependencies
- Personnel dependencies
- Environmental conditions
- Management concerns
- Significant technology changes
- Significant business changes

Risk identification must focus on meaningful business scenarios rather than producing large numbers of trivial or duplicative risks.

---

# 8. Risk Statement

Risk statements should identify:

- Threat or event
- Vulnerability or condition
- Affected asset, process, or objective
- Potential business consequence

Risk statements should be sufficiently specific to support treatment and ownership decisions.

---

# 9. Risk Categories

Risk may include categories such as:

- Cybersecurity
- Access control
- Application security
- Infrastructure
- Third party
- Supplier
- Physical security
- Environmental
- Personnel
- Fraud
- Data integrity
- Backup and recovery
- Business continuity
- Transportation
- Operational processing

Categories support organization and reporting but do not replace evaluation of the individual risk.

---

# 10. Risk Analysis

Risk analysis must consider:

- Likelihood
- Impact
- Existing controls
- Control effectiveness
- Business context
- Dependencies
- Existing vulnerabilities
- Relevant threat conditions

Risk analysis must distinguish the risk that exists before controls from the risk that remains after controls.

---

# 11. Likelihood Scale

Likelihood must be scored using whole numbers from 1 through 5.

| Score | Rating | General Meaning |
|---:|---|---|
| 1 | Rare | Unlikely under expected conditions |
| 2 | Unlikely | Possible but not expected frequently |
| 3 | Possible | Reasonably capable of occurring |
| 4 | Likely | Expected to occur or recur |
| 5 | Almost Certain | Highly likely or expected frequently |

Fractional likelihood scores must not be used.

Likelihood must reflect the scenario being assessed rather than an unsupported mathematical probability.

---

# 12. Impact Scale

Impact must be scored using whole numbers from 1 through 5.

| Score | Rating | General Meaning |
|---:|---|---|
| 1 | Insignificant | Minimal business consequence |
| 2 | Minor | Limited and manageable consequence |
| 3 | Moderate | Meaningful business disruption or loss |
| 4 | Major | Serious business, financial, operational, legal, or security consequence |
| 5 | Severe | Potentially extreme enterprise consequence |

Fractional impact scores must not be used.

Impact evaluation should consider relevant consequences including:

- Safety
- Operations
- Financial loss
- Information exposure
- Integrity
- Availability
- Legal obligations
- Contractual obligations
- Customer impact
- Reputation

---

# 13. Risk Calculation

Risk score is calculated as:

**Likelihood × Impact = Risk Score**

Example:

**Likelihood 4 × Impact 4 = 16**

The score must use the applicable whole-number likelihood and impact values.

---

# 14. Risk Rating Thresholds

Dunder Mifflin uses the following risk-rating thresholds:

| Score | Rating |
|---:|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–16 | High |
| 17–25 | Critical |

These thresholds must be used consistently unless formally revised through the risk-management process.

---

# 15. Inherent Risk

Inherent risk is the risk that would exist before considering the effect of existing controls.

Inherent risk provides management with information about:

- The underlying importance of the risk
- The potential consequence if controls fail
- Control dependency
- Assurance priority
- Business exposure

Inherent risk must not be discarded merely because existing controls reduce current residual risk.

---

# 16. Current Residual Risk

Current residual risk is the risk remaining after considering controls that actually exist and operate in the assessed environment.

Current residual risk must not receive credit for:

- Planned controls
- Proposed technology
- Future procedures
- Unimplemented policy requirements
- Intended improvements
- Controls that management expects to purchase later

Only existing controls may affect the current residual-risk assessment.

---

# 17. Target Residual Risk

Target residual risk is the expected risk level following successful implementation and operation of planned treatment.

Target residual risk is a forecast.

It is not:

- A guaranteed result
- An automatically achieved score
- A minimum possible score
- Evidence of implementation
- Evidence of effectiveness

Validated post-treatment risk may be:

- Higher than target
- Equal to target
- Lower than target

---

# 18. Validated Residual Risk

After treatment has been implemented and appropriately validated, the risk must be reassessed.

The resulting risk becomes the current residual risk for the new assessment period.

The target rating must not simply be copied into the current residual-risk field.

Reassessment must consider actual evidence.

---

# 19. Existing Controls

An existing control is a control actually operating in the assessed environment.

Examples may include:

- Managed antivirus
- Existing access restrictions
- Existing encryption
- Existing physical controls
- Existing backup processes
- Existing administrative practices
- Existing confidentiality agreements

Existing controls may receive credit when their existence and relevant operation are reasonably supported.

---

# 20. Proposed Controls

A proposed control is a control that management intends to implement or improve.

Proposed controls may support:

- Treatment planning
- Target residual-risk estimation
- Resource decisions
- Roadmap development

Proposed controls receive zero credit toward current residual risk until implemented and appropriately validated.

---

# 21. Control Effectiveness

Existing controls must be evaluated using the following ratings:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

## Effective

The control is appropriately designed and operating sufficiently to achieve its intended purpose.

## Partially Effective

The control provides meaningful protection but has limitations, inconsistent operation, incomplete coverage, or other material weakness.

## Ineffective

The control exists but does not provide meaningful assurance that its intended objective is achieved.

## Not Implemented

The control is absent or has not been put into operation.

---

# 22. Control Effectiveness and Risk

Control effectiveness must influence residual-risk analysis when relevant.

A control must not receive full risk-reduction credit merely because:

- A policy requires it.
- Technology has been installed.
- A procedure exists.
- Management believes it should work.

Risk reduction should reflect the control's actual ability to reduce likelihood, impact, or both.

---

# 23. Avoiding Double Counting

The same control effect must not be counted repeatedly in a way that artificially lowers risk.

Likewise, one risk must not be inflated by including consequences or scenarios already explicitly represented by another risk unless the overlap is necessary to understand the business exposure.

Risk relationships should be documented when risks share:

- Threats
- Controls
- Dependencies
- Consequences
- Treatment activities

---

# 24. Risk Evaluation

Current residual risk must be evaluated against:

- Business requirements
- Risk acceptance authority
- Treatment feasibility
- Control dependencies
- Legal or contractual requirements
- Management priorities

Risk evaluation determines whether the risk should be:

- Mitigated
- Transferred
- Avoided
- Accepted

---

# 25. Risk Treatment Options

## 25.1 Mitigate

Implement or improve controls to reduce likelihood, impact, or both.

## 25.2 Transfer

Shift or share specified financial or contractual consequences through mechanisms such as:

- Insurance
- Contracts
- Service agreements
- Indemnification

Transfer does not necessarily eliminate the underlying operational risk.

## 25.3 Avoid

Discontinue or materially change the activity producing the risk.

## 25.4 Accept

Retain the risk following appropriate management review and authorization.

---

# 26. Risk Treatment Plan

Material treatment activities must be documented in [[RTP-001 Enterprise Risk Treatment Plan]].

Treatment planning should identify:

- Risk
- Treatment decision
- Current residual risk
- Target residual risk
- Accountable owner
- Responsible parties
- Planned actions
- Priority
- Implementation horizon
- Dependencies
- Expected evidence
- Validation method
- Status

---

# 27. Treatment Status

Treatment status follows:

**Planned → Approved → Implementing → Implemented → Validation Pending → Validated**

**Corrective Action Required** may be assigned when treatment fails validation or a material deficiency is identified.

Implemented does not mean effective.

---

# 28. Treatment Priority

Treatment priority must consider more than current residual score.

Management should consider:

- Current residual risk
- Inherent risk
- Business criticality
- Information sensitivity
- Common-control dependencies
- Expected treatment effectiveness
- Treatment dependencies
- Cost
- Resource availability
- Legal requirements
- Contractual requirements
- Operational feasibility

A lower-rated risk may receive earlier treatment when it represents a dependency for several higher-rated risks.

---

# 29. Implementation Horizons

Treatment activities may use the following planning horizons:

| Horizon | General Period |
|---|---|
| Immediate | 0–90 days |
| Near Term | 3–6 months |
| Medium Term | 6–12 months |
| Ongoing | Recurring or continuous activity |

Planning horizons do not replace specific due dates when specific deadlines are required.

---

# 30. Risk Acceptance

Risk acceptance is a management decision to retain identified residual risk.

Acceptance must be:

- Explicit
- Documented
- Made by authorized management
- Based on sufficient understanding of the risk
- Subject to review

Failure to treat a risk does not automatically constitute valid risk acceptance.

---

# 31. Risk Acceptance Authority

Risk acceptance authority is:

| Residual Risk | Acceptance Authority |
|---|---|
| Low | Risk Owner |
| Moderate | Risk Owner + Appropriate Executive |
| High | CEO following ISRC review |
| Critical | CEO following ISRC review and exceptional justification |

An individual must not accept risk beyond assigned authority.

---

# 32. High Risk Acceptance

High residual risk may be accepted only by the CEO following ISRC review.

High risk acceptance must:

- Be documented.
- Include business justification.
- Identify the risk owner.
- Identify applicable conditions.
- Identify available treatment alternatives.
- Be reassessed within a maximum of 90 days.

High risk acceptance should not become an indefinite substitute for treatment without continued management review.

---

# 33. Critical Risk Acceptance

Critical residual risk may be accepted only by the CEO following ISRC review and exceptional justification.

Critical risk acceptance must:

- Be documented.
- Explain why immediate treatment or avoidance is not practical.
- Identify the risk owner.
- Identify interim controls where practical.
- Identify available treatment alternatives.
- Be reassessed within a maximum of 30 days.

Critical risk requires active executive attention.

---

# 34. Moderate Risk Acceptance

Moderate residual risk requires acceptance by:

- The risk owner
- The appropriate executive

Moderate risks should remain subject to routine monitoring and reassessment.

---

# 35. Low Risk Acceptance

Low residual risk may be accepted by the risk owner.

Low risk does not mean no risk.

Controls supporting a Low residual-risk rating may still require monitoring and assessment.

---

# 36. Risk Acceptance Record

A documented acceptance should identify:

- Risk ID
- Risk description
- Current residual rating
- Owner
- Reason for acceptance
- Available treatment alternatives
- Business justification
- Compensating controls where applicable
- Approver
- Approval date
- Review date
- Conditions

---

# 37. Security Exceptions and Risk

A security exception may create or increase residual risk.

Exceptions must identify the associated risk.

Exception approval must not be used to bypass required risk-acceptance authority.

If an exception produces High or Critical residual risk, the applicable High or Critical acceptance requirements apply.

Exception governance is established in [[PRO-009 Security Governance Framework]].

---

# 38. Risk Reassessment

Risk must be reassessed when appropriate.

Triggers may include:

- Treatment implementation
- Control validation
- Significant incidents
- Significant findings
- Material technology changes
- Material business changes
- Significant third-party changes
- New vulnerabilities
- Significant control failure
- Major continuity events
- Significant environmental changes

Risk reassessment must use current evidence.

---

# 39. Post-Treatment Reassessment

Following treatment, reassessment must determine:

1. Was the treatment actually implemented?
2. Does the control operate as designed?
3. Does it materially reduce the risk?
4. What is the revised likelihood?
5. What is the revised impact?
6. What is the validated residual risk?

The target residual risk is not the answer to these questions.

It is the earlier prediction against which actual results may be compared.

---

# 40. Risk Score Changes

Risk scores may change because:

- Likelihood changed.
- Impact changed.
- Controls improved.
- Controls degraded.
- Business conditions changed.
- Threat conditions changed.
- Dependencies changed.
- New evidence became available.

A score must not be changed merely to make performance appear improved.

---

# 41. Historical Risk Preservation

Previous risk assessments must be preserved.

When residual risk changes, the prior rating must not simply be overwritten without retaining appropriate history.

Historical information should support understanding of:

- Original exposure
- Treatment decisions
- Risk movement
- Control effectiveness
- Management decisions

The May 2013 assessment remains the historical baseline for the current enterprise security program.

---

# 42. Risk Register

The authoritative enterprise risk inventory is maintained in [[REG-002 Enterprise Risk Register]].

The register must identify, as appropriate:

- Risk ID
- Risk
- Category
- Owner
- Inherent risk
- Existing controls
- Control effectiveness
- Current residual risk
- Treatment decision
- Proposed controls
- Target residual risk
- Treatment status

---

# 43. Risk Register Review

The Enterprise Risk Register must be reviewed at least quarterly.

Review should consider:

- New risks
- Closed risks
- Changed risks
- Treatment progress
- Control failures
- Findings
- Incidents
- Exceptions
- Risk acceptance
- Material business changes
- Material technology changes

Quarterly review does not require every risk score to change.

---

# 44. Risk Closure

A risk should not be removed from the risk register solely because treatment has been implemented.

Closure requires an appropriate determination that:

- The risk no longer meaningfully exists,
- The activity creating the risk has ended,
- The risk has been consolidated into another authoritative risk, or
- Another documented reason supports closure.

Historical records must be preserved.

---

# 45. Control Validation

Controls relied upon for material risk reduction must receive validation appropriate to their importance.

Validation methods may include:

- Inspection
- Observation
- Independent Performance
- Technical Testing
- Sampling
- Exercises
- Reconciliation

The method must be appropriate to the control objective.

---

# 46. Evidence

Risk and control decisions should be supported by appropriate evidence.

Evidence may include:

- Configurations
- Logs
- Access records
- Approvals
- Test results
- Assessment reports
- Training records
- Backup records
- Recovery-test results
- Contracts
- Reconciliations
- Physical inspection
- Incident records

Evidence quality must be appropriate to the conclusion being reached.

---

# 47. Evidence Integrity

Evidence must accurately represent actual activity.

Personnel must not:

- Manufacture evidence
- Backdate evidence
- Alter evidence to conceal control failure
- Represent planned activity as completed
- Create records for activities that did not occur

Control failure must be documented and addressed rather than concealed.

---

# 48. Findings

A finding is a documented conclusion supported by evidence concerning whether a requirement, control, process, or expected outcome has been satisfied.

Findings may indicate:

- Satisfactory performance
- Partial performance
- Deficiency
- Control failure
- Improvement opportunity

Material deficiency findings requiring corrective action must be tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 49. Corrective Action

Corrective action should identify:

- Finding
- Affected control
- Affected risk
- Responsible party
- Required remediation
- Due date
- Status
- Expected evidence
- Retest requirements

Corrective action is not complete merely because remediation has been reported as implemented.

Validation may be required before closure.

---

# 50. Control Failure and Risk

A control failure may require risk reassessment.

Depending on the importance of the failed control:

- Residual risk may remain unchanged.
- Residual risk may increase.
- Additional treatment may be required.
- Risk acceptance may require reconsideration.
- Other dependent risks may require reassessment.

Common-control failure must be evaluated across all material risks relying on that control.

---

# 51. Inherent Risk and Assurance Priority

Inherent risk remains relevant even after controls reduce residual risk.

A risk with high inherent risk and low residual risk may still deserve significant assurance attention because the organization depends heavily on controls to maintain the lower risk.

Assurance planning must consider:

- Inherent risk
- Current residual risk
- Business criticality
- Control dependency
- Previous findings
- Significant changes
- Incident history

---

# 52. Business Impact Analysis

Risk assessment must use business-impact information where relevant.

[[RPT-002 Business Impact Analysis]] provides information concerning:

- Business criticality
- Maximum Tolerable Downtime
- Recovery Time Objective
- Recovery Point Objective
- Business dependencies

Risk assessment must not independently invent recovery requirements that conflict with the approved BIA.

---

# 53. Information Classification

Risk assessment must consider information sensitivity.

Classification requirements are established in:

- [[POL-004 Information Classification & Handling Policy]]
- [[STD-001 Information Classification Standard]]

Classification and business criticality must remain distinct.

---

# 54. Third-Party Risk

Third-party risk must be evaluated according to:

- Access
- Information sensitivity
- Service criticality
- Business dependency
- Replacement difficulty
- Security exposure
- Contractual protections
- Recovery considerations

Third-party controls are governed by [[POL-008 Third-Party Security Policy]].

---

# 55. Risk Dependencies

Risks may share controls or dependencies.

Examples include:

- Identity controls supporting multiple access risks
- Backup controls supporting ransomware, corruption, and continuity risks
- Security awareness supporting phishing and fraud risks
- Third-party controls supporting cloud and contractor risks
- Physical controls supporting facility and inventory risks

Dependencies must be considered when prioritizing treatment and assurance.

---

# 56. Risk Aggregation

Management must consider whether several individually Moderate risks create a more significant enterprise concern because of:

- Shared dependencies
- Common causes
- Concentration
- Correlated failures
- Cascading effects

Risk aggregation must not be used to arbitrarily change individual risk scores.

It is a management consideration for enterprise-level decision making.

---

# 57. Security Metrics and Risk Indicators

Risk management may use:

- Key Performance Indicators (KPIs)
- Key Risk Indicators (KRIs)
- Control metrics
- Treatment metrics
- Finding metrics

Metrics should help management understand:

- Whether risk is changing
- Whether treatment is progressing
- Whether controls are operating
- Whether exceptions are increasing
- Whether corrective action is effective

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 58. Risk Reporting

Risk information must be reported according to audience.

## Executive Reporting

Focus:

- Significant enterprise risk
- Risk movement
- Decisions
- Resource needs
- Risk acceptance

See [[RPT-006 Executive Security Summary]].

## Management Reporting

Focus:

- Risk ownership
- Treatment progress
- Control performance
- Findings
- Corrective actions

See [[RPT-007 Management Security Report]].

## Operational Reporting

Focus:

- Control execution
- Evidence
- Exceptions
- Technical deficiencies
- Remediation

See [[RPT-008 Operational Security Report & Dashboard]].

---

# 59. Risk Escalation

Risk must be escalated when:

- It exceeds the owner's acceptance authority.
- It becomes Critical.
- Significant treatment cannot be implemented.
- A critical control fails.
- Required resources are unavailable.
- A material finding remains unresolved.
- An exception materially increases risk.
- A significant incident changes the risk environment.

Escalation must occur soon enough to support meaningful management action.

---

# 60. Information Security and Risk Committee Review

The ISRC reviews matters including:

- High and Critical risks
- Significant treatment priorities
- Significant dependencies
- Risk acceptance
- Material findings
- Significant control failures
- Significant exceptions
- Resource conflicts
- Risk movement

The ISRC may challenge risk assumptions and request additional analysis or validation.

---

# 61. Continuous Monitoring

Risk management requires ongoing awareness of material changes.

Continuous monitoring may include:

- Security monitoring
- Vulnerability assessment
- Access reviews
- Backup testing
- Recovery exercises
- Third-party review
- Metrics
- Findings
- Incident analysis
- Management review

Continuous monitoring does not mean that every risk or control must be observed continuously.

Frequency must be proportionate to risk and business need.

---

# 62. Annual Risk Assessment

A formal enterprise risk assessment must be performed at least annually.

The assessment must review:

- Existing risks
- New risks
- Inherent risk
- Existing controls
- Control effectiveness
- Current residual risk
- Treatment status
- Target residual risk
- Risk ownership
- Significant dependencies

Material changes may require reassessment before the annual cycle.

---

# 63. Assessment Integrity

Risk assessment must reflect the environment as it actually exists.

Assessors and management must not:

- Credit controls that are merely planned.
- Suppress known deficiencies.
- Lower scores to improve appearance.
- Inflate scores to justify predetermined spending.
- Alter evidence to support a preferred conclusion.
- Treat target residual risk as an achieved result.

Risk analysis must remain supportable and transparent.

---

# 64. Documentation

Risk-management documentation must be sufficient to allow a qualified reviewer to understand:

- The risk
- The scoring
- Existing controls
- Control effectiveness
- Treatment decision
- Ownership
- Target outcome
- Validation
- Management decision

Documentation must remain proportionate to the importance of the risk.

---

# 65. Exceptions

Exceptions to this policy require:

- Documented business justification
- Identification of affected requirement
- Associated risk
- Responsible owner
- Defined duration
- Compensating controls where practical
- Appropriate approval

An exception must not be used to bypass risk-acceptance authority.

---

# 66. Enforcement

Failure to comply with this policy may result in:

- Corrective action
- Management review
- Risk escalation
- Access restriction
- Personnel action
- Contractual action
- Other appropriate management action

Intentional manipulation or concealment of material risk information must be escalated.

---

# 67. Policy Review

This policy must be reviewed:

- At least annually
- Following material changes to the risk methodology
- Following significant business change
- Following significant technology change
- Following significant incidents
- Following significant assessment findings
- When governance or acceptance authority materially changes

The CIO coordinates review.

Material revisions require CEO approval.

---

# 68. Traceability

Risk management must remain connected to the broader security lifecycle.

The enterprise traceability model is:

**Business Requirement → Asset/Process → Classification/BIA → Risk → Treatment → Policy/Standard → Control → Procedure → Implementation → Evidence → Test/Assessment → Finding → Remediation → Retest → Risk Reassessment → Management Decision → Continuous Monitoring**

Detailed relationships are maintained through [[REG-007 Cross-Reference Matrix]].

---

# 69. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-009 Security Governance Framework]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-001 Enterprise Asset Register]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[PLN-005 Annual Assurance Plan]]
- [[TMP-001 Assessment Work Plan Template]]
- [[RPT-006 Executive Security Summary]]
- [[RPT-007 Management Security Report]]
- [[RPT-008 Operational Security Report & Dashboard]]
- [[REG-007 Cross-Reference Matrix]]

---

# 70. Revision History

| Version | Date     | Description                    | Approval |
| ------- | -------- | ------------------------------ | -------- |
| 1.0     | May 2013 | Initial Risk Management Policy | CEO      |