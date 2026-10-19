# TMP-001 Assessment Work Plan Template

## Document Control

| Field | Value |
|---|---|
| Document ID | TMP-001 |
| Title | Assessment Work Plan Template |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved Template |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Assurance Process Change |

---

# 1. Purpose

This template defines the required planning and documentation structure for individual Dunder Mifflin security assessments.

It converts an assurance requirement from [[PLN-005 Annual Assurance Plan]] into specific, documented assessment work.

---

# 2. Assessment Principle

An assessment must be designed to answer a defined question using sufficient evidence.

The basic structure is:

**Requirement → Control → Assessment Objective → Method → Evidence → Test → Conclusion → Finding → Corrective Action → Validation → Retest → Risk Reassessment**

---

# 3. Instructions

Complete the applicable sections before assessment work begins.

Update the work plan during the assessment when material changes to:

- Scope
- Method
- Sampling
- Evidence availability
- Schedule
- Testing limitations

occur.

Sections that do not apply should be marked:

**Not Applicable**

rather than deleted when preserving the section helps demonstrate complete planning.

---

# 4. No Fabricated Information

This template must document actual planned or performed assessment activity.

Do not fabricate:

- Evidence
- Samples
- Interviews
- Observations
- Tests
- Results
- Findings
- Corrective actions
- Retests
- Approvals

---

# 5. Assessment Identification

| Field | Entry |
|---|---|
| Assessment ID | |
| Assessment Title | |
| Assessment Type | |
| Planned Start Date | |
| Planned Completion Date | |
| Actual Start Date | |
| Actual Completion Date | |
| Lead Assessor | |
| Supporting Assessors | |
| Assessment Owner | |
| Business / Technical Owner | |
| Classification | |
| Related Annual Assurance Plan Activity | |

---

# 6. Assessment ID

Use a unique assessment identifier appropriate to the assurance program.

Recommended format:

**ASM-[Year]-[Number]**

Example:

**ASM-2013-001**

---

# 7. Assessment Type

Select or describe the applicable type:

- Control assessment
- Access review
- Configuration assessment
- Vulnerability assessment
- Penetration test
- Application security assessment
- Recovery test
- Business Continuity exercise
- Incident Response exercise
- Physical security assessment
- Personnel security assessment
- Third-party assessment
- Corrective-action validation
- Retest
- Other

---

# 8. Assessment Trigger

Identify why this assessment is being performed.

| Trigger | Applicable | Details |
|---|---|---|
| Annual Assurance Plan | | |
| Scheduled Periodic Review | | |
| Risk Treatment Validation | | |
| Prior Finding | | |
| Failed Retest | | |
| Security Incident | | |
| Material Change | | |
| Management Request | | |
| Risk Reassessment | | |
| Other | | |

---

# 9. Assessment Objective

## Objective

[State exactly what the assessment is intended to determine.]

---

# 10. Objective Guidance

The objective should identify the condition being evaluated.

Example:

> Determine whether privileged access is authorized, individually attributable, limited according to business need, reviewed quarterly, and removed when no longer required.

---

# 11. Assessment Questions

List the specific questions the assessment must answer.

1. 
2. 
3. 
4. 
5. 

---

# 12. Scope

## In Scope

- 
- 
- 

## Out of Scope

- 
- 
- 

---

# 13. Scope Guidance

Scope should identify applicable:

- Business processes
- Systems
- Applications
- Facilities
- Accounts
- Personnel
- Third parties
- Time periods
- Transactions
- Locations
- Control activities

---

# 14. Scope Boundaries

Clearly identify material exclusions.

An assessor must not imply enterprise-wide assurance when only a limited population was assessed.

---

# 15. Business Context

Describe the business process or capability supported by the assessed control.

[Enter business context.]

---

# 16. Business Impact Analysis Relationship

| Field | Entry |
|---|---|
| Related Business Process | |
| BIA Criticality | |
| Maximum Tolerable Downtime (MTD), if applicable | |
| Recovery Time Objective (RTO), if applicable | |
| Recovery Point Objective (RPO), if applicable | |

Reference:

[[RPT-002 Business Impact Analysis]]

---

# 17. Information Classification

Identify the highest applicable information classification.

- Public
- Internal
- Confidential
- Restricted

Reference:

[[STD-001 Information Classification Standard]]

---

# 18. Related Enterprise Risks

| Risk ID | Risk Title | Inherent Risk | Current Residual Risk | Target Residual Risk | Relevance to Assessment |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

Reference:

[[REG-002 Enterprise Risk Register]]

---

# 19. Inherent Risk Consideration

Document whether severe inherent risk increases the importance of this assessment even if current residual risk is lower.

[Enter analysis.]

---

# 20. Inherent Risk Still Matters

Do not select assessment depth solely from current residual risk.

A control that materially reduces severe inherent exposure may warrant significant assurance because control failure could restore that exposure.

---

# 21. Related Risk Treatments

| Risk ID | Treatment Action | Treatment Status | Validation Required | Relevance |
|---|---|---|---|---|
| | | | | |
| | | | | |

Reference:

[[RTP-001 Enterprise Risk Treatment Plan]]

---

# 22. Requirements

Identify the requirements against which the assessment will be performed.

| Requirement Source | Document ID | Section / Heading | Requirement |
|---|---|---|---|
| | | | |
| | | | |
| | | | |

---

# 23. Requirement Sources

Requirements may originate from:

- Policy
- Standard
- Procedure
- Program
- Risk treatment
- Business Impact Analysis
- Contract
- Approved security requirement

---

# 24. Controls

Identify the controls being assessed.

| Control ID | Control Name | Objective | Owner | Implementation Status | Current Effectiveness |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

Reference:

[[REG-003 Enterprise Security Control Inventory]]

---

# 25. Control Importance

For each material control, consider:

- Related inherent risk
- Current residual risk
- Business impact
- Information sensitivity
- Dependency
- Prior findings
- Incident history
- Failure impact

---

# 26. Assessment Criteria

Define the criteria that will be used to determine whether each requirement or control is satisfied.

| Control / Requirement | Expected Condition | Satisfactory Criteria | Deficiency Criteria |
|---|---|---|---|
| | | | |
| | | | |

---

# 27. Criteria Timing

Assessment criteria should be defined before results are evaluated where practical.

Criteria must not be changed solely to convert an unfavorable result into a satisfactory result.

---

# 28. Assessor Information

| Field | Entry |
|---|---|
| Lead Assessor | |
| Department / Organization | |
| Role | |
| Relevant Qualifications | |
| Relationship to Control | |
| Potential Conflict of Interest | |
| Independence Level | |

---

# 29. Assessment Independence

Describe the independence appropriate to the assessment.

[Enter independence analysis.]

---

# 30. Independence Factors

Consider:

- Enterprise risk
- Control importance
- Technical complexity
- Potential conflict of interest
- Required expertise
- Prior control ownership
- Regulatory or contractual requirement

---

# 31. Independence Is Proportional

Not every assessment requires an external assessor.

The level of independence must be appropriate to the risk and assessment objective.

---

# 32. Assessment Methods

Select all methods that apply.

| Method | Selected | Planned Use |
|---|---|---|
| Inspection | | |
| Observation | | |
| Independent Performance | | |
| Technical Testing | | |
| Sampling | | |
| Exercise | | |
| Reconciliation | | |

---

# 33. Inspection

Inspection evaluates:

- Documents
- Configurations
- Records
- Logs
- Reports
- Contracts
- Approvals
- Other evidence

---

# 34. Observation

Observation evaluates a control or procedure while personnel perform it.

---

# 35. Independent Performance

Independent Performance means the assessor performs an authorized procedure independently to determine whether the expected result occurs.

---

# 36. Independent Performance Safety

Independent Performance must not create unnecessary:

- Operational disruption
- Security exposure
- Data corruption
- Safety risk

---

# 37. Technical Testing

Technical Testing may include:

- Vulnerability testing
- Penetration testing
- Configuration testing
- Application testing
- Network discovery
- Authentication testing
- Recovery testing

---

# 38. Sampling

Sampling evaluates selected items from a larger population.

---

# 39. Exercises

Exercises may evaluate:

- Incident Response
- Business Continuity
- Disaster Recovery
- Manual processing
- Escalation
- Communication

---

# 40. Reconciliation

Reconciliation compares related records to identify:

- Missing records
- Duplicate records
- Unauthorized activity
- Inconsistency
- Integrity problems

---

# 41. Evidence Plan

Identify expected evidence before assessment begins where practical.

| Evidence ID | Evidence Description | Source | Owner / Custodian | Collection Method | Classification |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

# 42. Potential Evidence

Evidence may include:

- Policies
- Standards
- Procedures
- Configuration records
- System settings
- Logs
- Access records
- Approval records
- Change records
- Training records
- Backup records
- Recovery records
- Contracts
- Incident records
- Source-code records
- Vulnerability results
- Penetration-test results
- Visitor records
- Personnel records
- Transaction records
- Interviews
- Physical observations

---

# 43. Evidence Quality

Evaluate evidence for:

- Relevance
- Reliability
- Completeness
- Timeliness

---

# 44. Evidence Integrity

Evidence must represent actual conditions.

Do not:

- Fabricate records.
- Backdate records.
- Alter logs.
- Create false approvals.
- Conceal unfavorable evidence.
- Record an unperformed test as complete.

---

# 45. Evidence Handling

Sensitive assessment evidence must be handled according to:

[[PROC-011 Evidence Handling Procedure]]

where applicable.

---

# 46. Evidence Location

| Evidence ID | Storage / Reference Location | Access Restriction | Retention Requirement |
|---|---|---|---|
| | | | |
| | | | |

---

# 47. Evidence Limitations

Document known evidence limitations.

[Enter limitations.]

---

# 48. Population

Where sampling is used, define the population.

| Field | Entry |
|---|---|
| Population Description | |
| Population Size | |
| Period Covered | |
| Population Source | |

---

# 49. Sampling Plan

| Field | Entry |
|---|---|
| Sample Size | |
| Selection Method | |
| Risk-Based Selection Factors | |
| Random Selection Used | |
| Judgmental Selection Used | |
| Known Exceptions Included | |

---

# 50. Sampling Factors

Sample selection should consider:

- Population size
- Control frequency
- Risk
- Materiality
- Prior findings
- Known exceptions
- Business criticality

---

# 51. Sampling Integrity

Samples must not be selected solely to avoid known deficiencies or produce a favorable conclusion.

---

# 52. Sample Register

| Sample ID | Population Item | Selection Basis | Evidence Reference | Result |
|---|---|---|---|---|
| | | | | |
| | | | | |
| | | | | |

---

# 53. Interviews

| Interview ID | Role | Purpose | Date | Relevant Evidence / Notes |
|---|---|---|---|---|
| | | | | |
| | | | | |

---

# 54. Interview Limitation

Interviews provide useful context but may not independently establish that a control operates effectively.

Corroborating evidence should be obtained where appropriate.

---

# 55. Assessment Procedures

Document each planned assessment procedure.

| Step | Control / Requirement | Procedure | Method | Evidence | Expected Result |
|---|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

---

# 56. Procedure Design

Assessment procedures should be sufficiently specific that a qualified assessor can understand:

- What to examine
- What to perform
- What evidence to collect
- What result is expected

---

# 57. Procedure Example

| Step | Control / Requirement | Procedure | Method | Evidence | Expected Result |
|---|---|---|---|---|---|
| Example | Quarterly privileged access review | Select the approved privileged-account population and compare current access to documented authorization and review records | Inspection / Sampling | Account list; approval records; review records | Sampled privileged accounts have current authorization and required quarterly review |

---

# 58. Assessment Schedule

| Activity | Planned Date | Responsible Person | Dependency | Status |
|---|---|---|---|---|
| Planning | | | | |
| Evidence Collection | | | | |
| Testing | | | | |
| Analysis | | | | |
| Finding Review | | | | |
| Reporting | | | | |

---

# 59. Dependencies

Identify material dependencies.

- 
- 
- 

---

# 60. Potential Dependencies

Dependencies may include:

- Personnel availability
- System availability
- Vendor support
- Test environment
- Production schedule
- Required authorization
- Evidence availability
- Business operations

---

# 61. Technical Test Authorization

Complete when Technical Testing is included.

| Field | Entry |
|---|---|
| Authorized By | |
| Systems Authorized | |
| Testing Window | |
| Permitted Methods | |
| Prohibited Methods | |
| Emergency Contact | |
| Stop Conditions | |

---

# 62. Production Testing

Testing against production systems must be planned to avoid unreasonable:

- Business interruption
- Data corruption
- Availability impact
- Security exposure

---

# 63. Stop Conditions

Testing must stop or be modified when continuing would create unacceptable:

- Safety risk
- Operational risk
- Security risk
- Data integrity risk

---

# 64. Penetration Testing

When this work plan supports penetration testing, also apply:

[[STD-007 Penetration Testing Standard]]

---

# 65. Application Security Assessment

When this work plan supports Infinity application security assessment, also apply:

- [[STD-009 Infinity Security Standard]]
- [[PROC-019 Application Security Assessment Procedure]]

---

# 66. Recovery Testing

When this work plan supports recovery testing, use:

[[TMP-003 Recovery Test Template]]

for detailed recovery results.

---

# 67. Recovery Criteria

Recovery assessment should evaluate applicable:

- Maximum Tolerable Downtime
- Recovery Time Objective
- Recovery Point Objective
- Technical recovery
- Documentation
- Personnel readiness
- Business validation

---

# 68. Access Assessment

Access assessment may evaluate:

- Authorization
- Least privilege
- Individual accountability
- Privileged access
- Dormant accounts
- Contractor access
- Transfer handling
- Termination
- Emergency access

---

# 69. Physical Security Assessment

Physical assessment may evaluate:

- Public areas
- Controlled areas
- Restricted areas
- Access credentials
- Visitors
- Vendors
- Warehouse cages
- Significant Information Technology areas
- Environmental safeguards

---

# 70. Personnel Security Assessment

Personnel assessment may evaluate:

- Joiners
- Movers
- Leavers
- Contractors
- Confidentiality
- Training
- Company-property recovery
- Key-person dependency
- Cross-training

---

# 71. Third-Party Assessment

Third-party assessment may evaluate:

- Classification
- Due diligence
- Contractual security requirements
- Confidentiality
- Access
- Incident notification
- Recovery
- Exit planning
- Prior findings

---

# 72. Change Management Assessment

Change assessment may evaluate:

- Authorization
- Testing
- Risk consideration
- Separation of duties
- Rollback
- Implementation
- Verification
- Documentation

---

# 73. Fraud-Control Assessment

Fraud-control assessment may evaluate:

- Separation of Duties
- Approval
- Transaction attribution
- Independent verification
- Reconciliation
- Access restriction

---

# 74. Assessment Execution Record

Record procedures actually performed.

| Step | Date | Assessor | Procedure Performed | Evidence Reference | Result | Exception |
|---|---|---|---|---|---|---|
| | | | | | | |
| | | | | | | |
| | | | | | | |

---

# 75. Deviations From Plan

Document material deviations from the approved work plan.

| Deviation | Reason | Risk / Impact | Approved By | Date |
|---|---|---|---|---|
| | | | | |

---

# 76. Additional Procedures

If initial results require expanded testing, document the additional procedures.

| Procedure | Reason | Method | Evidence | Result |
|---|---|---|---|---|
| | | | | |

---

# 77. Assessment Results

Summarize the assessment results.

[Enter results.]

---

# 78. Control Results

| Control ID | Control | Result | Evidence | Effectiveness Conclusion |
|---|---|---|---|---|
| | | | | |
| | | | | |

---

# 79. Control Effectiveness Categories

Use:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

when sufficient evidence supports an effectiveness conclusion.

---

# 80. Not Yet Assessed

Use **Not Yet Assessed** when sufficient assessment work has not been performed to support an effectiveness conclusion.

---

# 81. Unable to Determine

Use **Unable to Determine** when assessment work was performed but available evidence remains insufficient to support a conclusion.

---

# 82. Effective

Effective means sufficient evidence demonstrates that the control is appropriately designed and operates sufficiently to achieve its intended objective.

---

# 83. Partially Effective

Partially Effective means the control provides meaningful protection but contains deficiencies or limitations reducing expected effectiveness.

---

# 84. Ineffective

Ineffective means the control does not provide sufficient protection to achieve its intended objective.

---

# 85. Not Implemented

Not Implemented means the required control does not currently exist or has not been deployed sufficiently to operate.

---

# 86. Implementation Is Not Effectiveness

A control may be implemented without being effective.

Do not use implementation status as a substitute for assessment evidence.

---

# 87. Exceptions Identified

| Exception ID | Control / Requirement | Condition | Evidence | Materiality |
|---|---|---|---|---|
| | | | | |
| | | | | |

---

# 88. Exception Evaluation

Each material exception should be evaluated to determine whether it represents:

- Isolated condition
- Control deficiency
- Significant deficiency
- Systemic weakness
- Security incident
- Risk change

---

# 89. Findings

| Finding ID | Finding Title | Related Control | Related Risk | Priority | Owner | Status |
|---|---|---|---|---|---|---|
| | | | | | | |
| | | | | | | |

---

# 90. Finding Register

Material deficiency findings requiring corrective action must be entered into:

[[REG-004 Finding & Corrective Action Register]]

---

# 91. Finding Requirement

A finding must identify:

- Expected requirement
- Observed condition
- Supporting evidence
- Security or business significance

---

# 92. Finding Versus Observation

Not every observation must become a formal deficiency finding.

The assessor must determine whether the evidence demonstrates a meaningful failure to satisfy a requirement or expected control outcome.

---

# 93. Corrective Actions

| Finding ID | Corrective Action | Accountable Owner | Target Date | Validation Method | Retest Required |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

# 94. One Accountable Owner

Each material finding must have one accountable owner.

Supporting departments may participate without making accountability ambiguous.

---

# 95. Corrective Action Quality

Corrective action should address the underlying weakness rather than merely the visible symptom.

---

# 96. Root-Cause Consideration

For material or recurring findings, document root-cause analysis where appropriate.

[Enter root-cause analysis.]

---

# 97. Potential Root Causes

Potential causes may include:

- Control-design weakness
- Missing procedure
- Configuration error
- Inadequate training
- Technical limitation
- Communication failure
- Resource limitation
- Inadequate oversight
- Unclear accountability
- Dependency failure

---

# 98. Validation Plan

| Finding ID | Corrective Action | Validation Method | Validator | Expected Evidence | Planned Date |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

# 99. Validation Methods

Corrective-action validation may use:

- Inspection
- Observation
- Independent Performance
- Technical Testing
- Sampling
- Exercises
- Reconciliation

---

# 100. Validation Independence

Where practical and appropriate to risk, the person validating corrective action should differ from the person who performed the corrective action.

---

# 101. Retest Plan

| Finding ID | Retest Required | Retest Procedure | Expected Result | Retest Owner | Planned Date |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

# 102. Retest Requirement

Retesting is required when demonstrating that the corrected control operates properly requires repeating appropriate assessment activity.

---

# 103. Retest Result

| Finding ID | Retest Date | Result | Evidence | Further Action |
|---|---|---|---|---|
| | | | | |
| | | | | |

---

# 104. Failed Retest

A failed retest means the finding remains open.

Document:

- Failure
- Evidence
- Revised corrective action
- Risk impact
- Required escalation

---

# 105. Successful Retest

A successful retest may support:

- Finding closure
- Updated control-effectiveness conclusion
- Risk reassessment

---

# 106. Risk Impact

Document whether assessment results affect enterprise risk.

| Risk ID | Previous Current Residual Risk | Assessment Evidence | Reassessment Required | Reason |
|---|---|---|---|---|
| | | | | |
| | | | | |

---

# 107. Upward Risk Reassessment

Consider upward reassessment when evidence demonstrates:

- Control failure
- Greater exposure
- Incorrect assumptions
- New weakness
- Ineffective treatment

---

# 108. Downward Risk Reassessment

Consider downward reassessment only when sufficient evidence demonstrates meaningful improvement in relevant control effectiveness.

---

# 109. No Automatic Risk Reduction

Do not reduce enterprise risk merely because:

- A control was purchased.
- A control was installed.
- A policy was approved.
- A treatment was marked complete.
- A finding was administratively closed.

---

# 110. Target Residual Risk

Target residual risk is a prediction.

Actual validated post-treatment risk may differ from the target.

---

# 111. Historical Integrity

Do not overwrite the historical May 2013 assessment when later evidence changes the current risk assessment.

Preserve the historical rating and record the later reassessment separately.

---

# 112. Assessment Limitations

Document limitations that could affect conclusions.

| Limitation | Impact | Compensating Assessment Work | Remaining Concern |
|---|---|---|---|
| | | | |
| | | | |

---

# 113. Potential Limitations

Examples include:

- Missing evidence
- Incomplete logs
- Limited sample
- Unavailable personnel
- Unavailable system
- Vendor restriction
- Testing restriction
- Operational constraint

---

# 114. Material Limitation

A material limitation may require:

- Additional testing
- Expanded sampling
- Unable to Determine conclusion
- Finding
- Management escalation
- Risk consideration

---

# 115. Assessment Conclusion

## Overall Conclusion

[Enter conclusion.]

---

# 116. Conclusion Requirements

The conclusion should answer the original assessment objective.

It should distinguish among:

- What evidence demonstrated
- What could not be determined
- What deficiencies were identified
- What corrective action is required
- What risk implications exist

---

# 117. Assessment Summary

| Field | Result |
|---|---|
| Assessment Objective Achieved | |
| Controls Assessed | |
| Effective Controls | |
| Partially Effective Controls | |
| Ineffective Controls | |
| Not Implemented Controls | |
| Unable to Determine | |
| Findings Created | |
| High-Priority Findings | |
| Critical Findings | |
| Risk Reassessment Required | |
| Follow-Up Required | |

---

# 118. Management Actions

Document required management actions.

1. 
2. 
3. 

---

# 119. Immediate Escalation

If assessment activity identifies an immediate material threat, personnel must not wait for final report completion before escalation.

---

# 120. Active Security Compromise

Suspected active compromise must be handled under:

- [[PROC-010 Security Event Escalation Procedure]]
- [[PLN-001 Incident Response Plan]]

---

# 121. Safety Priority

Human life and safety take priority over:

- Assessment completion
- Testing
- Systems
- Operations
- Facilities
- Equipment
- Inventory
- Revenue
- Other assets

---

# 122. Reporting Level

Identify required reporting audiences.

| Audience | Required | Report / Communication |
|---|---|---|
| Operational | | |
| Management | | |
| Executive | | |
| Information Security and Risk Committee | | |

---

# 123. Reporting Principle

**Executive → decisions and enterprise risk**

**Management → accountability, performance, and action**

**Operational → execution, evidence, exceptions, and technical detail**

---

# 124. Reporting Chain

Assessment results should support:

**Technical Evidence → Operational Exception → Management Impact → Enterprise Risk → Executive Decision**

---

# 125. Operational Reporting

Operational reporting should contain sufficient detail to support:

- Correction
- Investigation
- Evidence
- Retesting
- Technical action

---

# 126. Management Reporting

Management reporting should focus on:

- Control performance
- Accountability
- Findings
- Corrective actions
- Due dates
- Exceptions
- Risk impact

---

# 127. Executive Reporting

Executive reporting should focus on:

- Material enterprise risk
- Significant control weakness
- Significant overdue remediation
- Resource requirements
- Decisions

---

# 128. Information Security and Risk Committee

Material assurance results may be reviewed by the Information Security and Risk Committee (ISRC).

---

# 129. ISRC Escalation

Consider ISRC review for:

- Significant deficiencies
- High or Critical risk implications
- Material overdue remediation
- Failed significant recovery tests
- Significant third-party weakness
- Significant Infinity weakness
- Risk acceptance

---

# 130. Assessment Metrics

Record relevant metrics produced or affected by the assessment.

| Metric ID | Metric | Previous Value | Current Value | Interpretation |
|---|---|---|---|---|
| | | | | |
| | | | | |

Reference:

[[REG-005 Security Metrics Catalog]]

---

# 131. Metric Limitation

Assessment metrics must use actual evidence.

Do not use invented values to complete the work plan.

---

# 132. Final Evidence Index

| Evidence ID | Description | Source | Classification | Supports |
|---|---|---|---|---|
| | | | | |
| | | | | |
| | | | | |

---

# 133. Final Finding Index

| Finding ID | Title | Priority | Owner | Corrective Action | Status |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

# 134. Follow-Up Requirements

| Follow-Up Activity | Owner | Due Date | Evidence Required | Status |
|---|---|---|---|---|
| | | | | |
| | | | | |

---

# 135. Assessment Closeout

Before closing the assessment, confirm:

- [ ] Assessment objective was addressed.
- [ ] Approved scope was completed or deviations documented.
- [ ] Required procedures were performed.
- [ ] Evidence was recorded.
- [ ] Evidence limitations were documented.
- [ ] Samples were documented.
- [ ] Exceptions were evaluated.
- [ ] Material findings were entered into REG-004.
- [ ] Corrective-action owners were assigned.
- [ ] Validation requirements were established.
- [ ] Retesting requirements were established.
- [ ] Risk implications were considered.
- [ ] Required reporting was completed.
- [ ] Evidence was retained appropriately.

---

# 136. Assessment Approval

| Role | Name | Decision | Date |
|---|---|---|---|
| Lead Assessor | | | |
| Assessment Owner | | | |
| Control / Business Owner | | | |
| CIO, if required | | | |

---

# 137. Approval Limitation

Approval of the assessment record acknowledges the documented assessment and its disposition.

Approval must not be used to suppress or rewrite evidence-supported unfavorable conclusions.

---

# 138. Assessment Record Retention

Completed work plans and supporting evidence must be retained sufficiently to support:

- Assurance history
- Findings
- Corrective actions
- Retesting
- Risk reassessment
- Future assessments
- Management review

---

# 139. Continuous Improvement

Lessons from completed assessments should be considered when improving:

- Controls
- Procedures
- Assessment methods
- Evidence collection
- Sampling
- Training
- Risk treatment

---

# 140. Work Plan Improvement

If the assessment demonstrates that the planned procedures were insufficient, future work plans should be improved.

---

# 141. Reusable Template Principle

This template provides a consistent assessment structure without forcing every assessment to use identical testing.

Assessment depth and methods must remain risk-based.

---

# 142. Assessment Work Plan Value

The Assessment Work Plan creates a documented bridge between high-level assurance planning and actual testing.

Without this bridge, an organization may know that a control should be assessed without clearly defining:

- What the assessor will test
- What evidence is required
- What success means
- How conclusions will be supported

---

# 143. Complete Assurance Chain

A properly executed Assessment Work Plan supports:

**Annual Assurance Plan**

↓

**Assessment Work Plan**

↓

**Control Testing**

↓

**Evidence**

↓

**Assessment Conclusion**

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

# 144. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[PRO-009 Security Governance Framework]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-011 Physical & Environmental Security Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[STD-007 Penetration Testing Standard]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[STD-009 Infinity Security Standard]]
- [[PROC-003 Access Review Procedure]]
- [[PROC-006 Vulnerability Assessment Procedure]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-017 Personnel Security Procedure]]
- [[PROC-019 Application Security Assessment Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PLN-005 Annual Assurance Plan]]
- [[TMP-003 Recovery Test Template]]
- [[RPT-006 Executive Security Summary]]
- [[RPT-007 Management Security Report]]
- [[RPT-008 Operational Security Report & Dashboard]]

---

# 145. Template Review

This template must be reviewed:

- At least annually
- Following material assurance-process change
- When completed assessments identify significant template deficiencies
- When enterprise governance or assessment requirements materially change

Routine use of this template does not require CEO approval.

Material changes to the assessment methodology require approval consistent with the enterprise security governance framework.

---

# 146. Revision History

| Version | Date     | Description                           | Approval |
| ------- | -------- | ------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Assessment Work Plan Template | CEO      |