# REG-004 Finding & Corrective Action Register

## Document Control

| Field | Value |
|---|---|
| Document ID | REG-004 |
| Title | Finding & Corrective Action Register |
| Version | 1.0 |
| Classification | Confidential |
| Status | Active |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Monthly and Following Material Assessment, Finding, or Corrective Action Change |

---

# 1. Purpose

This register provides Dunder Mifflin's central record for material security findings and corrective actions.

It supports the lifecycle:

**Assessment → Finding → Corrective Action → Validation → Retest → Closure → Risk Reassessment**

---

# 2. Objectives

The register is intended to ensure that material security deficiencies are:

- Documented
- Supported by evidence
- Connected to requirements
- Connected to security controls
- Connected to enterprise risk
- Assigned to one accountable owner
- Given an appropriate corrective action
- Tracked to completion
- Validated before closure
- Retested where appropriate
- Considered during risk reassessment

---

# 3. Authority

This register operates under:

- [[POL-001 Information Security Policy]]
- [[POL-005 Risk Management Policy]]
- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[PRO-009 Security Governance Framework]]

---

# 4. Traceability

This register supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

---

# 5. Finding Definition

A finding is a documented conclusion supported by evidence concerning whether a requirement, control, process, or expected outcome was satisfied.

---

# 6. Findings Are Not Automatically Negative

A finding may document:

- Satisfactory condition
- Partial satisfaction
- Deficiency
- Significant deficiency
- Not applicable
- Unable to determine

This register primarily tracks findings requiring corrective action or continuing management attention.

---

# 7. Deficiency

A deficiency exists when evidence demonstrates that a required control or expected outcome is not adequately satisfied.

---

# 8. Significant Deficiency

A Significant Deficiency is a weakness with material security or business significance requiring elevated management attention.

---

# 9. Unable to Determine

Unable to Determine may be used when available evidence is insufficient to reach a supportable effectiveness conclusion.

Lack of evidence must not be converted into a satisfactory result merely to complete an assessment.

---

# 10. Finding Identification

Findings use the identifier:

**FND-[Year]-[Number]**

Example:

**FND-2013-001**

---

# 11. Finding Identifier Permanence

Once assigned, a Finding ID must not be reused for another finding.

---

# 12. Finding Status

Finding status may include:

| Status | Meaning |
|---|---|
| Open | Finding has been confirmed and requires disposition. |
| In Progress | Corrective action is underway. |
| Validation Pending | Corrective action is reported complete but has not been sufficiently validated. |
| Retest Required | Validation requires additional testing of the corrected control. |
| Risk Accepted | Authorized management has accepted the remaining risk rather than correcting the deficiency within the current period. |
| Closed | Required corrective action and validation are complete. |

---

# 13. Corrective Action Status

Corrective actions may use:

- Open
- In Progress
- Validation Pending
- Closed

---

# 14. Finding Priority

Finding priority is separate from enterprise risk rating.

Finding priority indicates the urgency and management attention appropriate to the identified deficiency.

---

# 15. Finding Priority Levels

| Priority | General Meaning |
|---|---|
| Critical | Immediate material exposure requiring urgent executive attention and action. |
| High | Significant weakness requiring prompt management action. |
| Moderate | Meaningful weakness requiring scheduled corrective action. |
| Low | Limited weakness that should be corrected through normal management activity. |

---

# 16. Finding Priority Factors

Priority should consider:

- Related enterprise risk
- Business impact
- Information sensitivity
- Exploitability
- Exposure
- Control importance
- Control failure duration
- Existing compensating controls
- Recovery impact
- Fraud potential
- Third-party dependency
- Likelihood of recurrence

---

# 17. Finding Priority Is Not Enterprise Risk

A finding does not automatically receive the same rating as its related enterprise risk.

For example, a Moderate finding may affect a High enterprise risk without changing the enterprise risk rating by itself.

---

# 18. Finding Source

Findings may originate from:

- Security assessment
- Vulnerability assessment
- Penetration test
- Access review
- Recovery test
- Business continuity exercise
- Incident
- Security monitoring
- Configuration review
- Application security assessment
- Third-party review
- Physical security assessment
- Personnel security review
- Management review
- Internal control review
- Independent enterprise control assessment

---

# 19. Finding Record Requirements

A material finding should identify:

- Finding ID
- Date identified
- Finding title
- Source
- Requirement
- Control ID
- Condition
- Supporting evidence
- Related risk
- Priority
- Accountable owner
- Corrective action
- Target date
- Validation method
- Retest requirement
- Status
- Closure evidence
- Closure date

as applicable.

---

# 20. Finding Register

No material deficiency findings have been entered at initial register creation.

| Finding ID | Date | Finding | Source | Requirement / Control | Related Risk | Priority | Owner | Corrective Action | Target Date | Validation / Retest | Status |
|---|---|---|---|---|---|---|---|---|---|---|---|
| _None recorded_ | | | | | | | | | | | |

---

# 21. No Fabricated Findings

The empty initial register is intentional.

Dunder Mifflin must not create fictional:

- Findings
- Test failures
- Remediation records
- Retest results
- Closure evidence

merely to populate the register.

---

# 22. Program Design Versus Assessment Evidence

The enterprise security project identifies known risk conditions and proposed improvements.

Those design decisions do not automatically constitute assessment findings.

A formal finding requires an assessment conclusion supported by evidence.

---

# 23. Finding Title

Finding titles should be concise and describe the material issue.

Example structure:

**Privileged Access Review Not Completed at Required Frequency**

---

# 24. Finding Description

The finding description should explain the condition clearly enough for management and the control owner to understand:

- What was expected
- What was observed
- Why the difference matters

---

# 25. Requirement

Each finding should identify the requirement against which the condition was assessed.

The requirement may originate from:

- Policy
- Standard
- Procedure
- Program
- Risk treatment
- Business Impact Analysis
- Contract
- Approved security requirement

---

# 26. Control Reference

Where applicable, the finding must identify the affected control from [[REG-003 Enterprise Security Control Inventory]].

---

# 27. Multiple Controls

A finding may affect multiple controls when the same underlying deficiency materially affects each control.

---

# 28. Multiple Risks

A finding may relate to multiple enterprise risks.

The finding should identify the risks materially affected rather than listing unrelated risks merely because they share a security domain.

---

# 29. Evidence

Every finding must be supported by sufficient evidence.

---

# 30. Evidence Examples

Supporting evidence may include:

- Configuration
- Logs
- Reports
- Screenshots
- Access records
- Change records
- Vulnerability results
- Test results
- Recovery results
- Incident records
- Training records
- Visitor records
- Backup records
- Source-code records
- Physical observations
- Interviews
- Transaction records

---

# 31. Evidence Quality

Evidence should be evaluated for:

- Relevance
- Reliability
- Completeness
- Timeliness

---

# 32. Evidence Integrity

Evidence must represent actual conditions.

Personnel must not:

- Fabricate evidence.
- Backdate approvals.
- Invent testing activity.
- Alter logs to support a preferred result.
- Conceal unfavorable evidence.
- Create false remediation records.
- Record an unperformed retest as complete.

---

# 33. Evidence Reference

The finding record should reference the evidence supporting the conclusion.

Large or sensitive evidence does not need to be embedded directly in this register if it is securely maintained elsewhere.

---

# 34. Evidence Limitation

Where evidence is incomplete, the limitation must be documented.

---

# 35. Condition

The condition describes what the assessor actually observed.

It should be factual and supported by evidence.

---

# 36. Condition Versus Cause

The observed condition and the suspected underlying cause should not be confused.

Example:

**Condition:** Three sampled terminated accounts remained active after the employees' final work dates.

**Potential cause:** Human Resources termination notifications were not consistently delivered to Information Technology.

The cause should be confirmed before corrective action is designed around it.

---

# 37. Root Cause

Material or recurring findings should receive root-cause consideration where practical.

---

# 38. Potential Root Causes

Root causes may include:

- Inadequate control design
- Missing procedure
- Unclear responsibility
- Insufficient training
- Technical limitation
- Inadequate resources
- Configuration error
- Process failure
- Communication failure
- Inadequate oversight
- Dependency failure

---

# 39. Corrective Action

Corrective action must address the underlying weakness rather than merely changing the appearance of compliance.

---

# 40. Corrective Action Requirements

A material corrective action should identify:

- Required action
- Accountable owner
- Target date
- Required resources
- Dependencies
- Expected evidence
- Validation method
- Retest requirement

as applicable.

---

# 41. One Accountable Owner

Each material finding must have one accountable owner.

Multiple departments may participate in remediation, but accountability must not become ambiguous.

---

# 42. Supporting Owners

Supporting personnel or departments may be identified separately when corrective action requires coordinated work.

---

# 43. Corrective Action Owner

The accountable owner is responsible for ensuring corrective action progresses.

The owner does not need to personally perform every remediation activity.

---

# 44. Target Date

Each material corrective action must have a target completion date appropriate to:

- Finding priority
- Related risk
- Business impact
- Technical complexity
- Required resources
- Dependencies

---

# 45. Target Date Changes

A target date must not be silently changed.

Material extensions require:

- Rationale
- Updated risk consideration
- Appropriate approval
- Revised target date

---

# 46. Overdue Finding

A finding becomes overdue when required corrective action has not been completed by the approved target date.

---

# 47. Overdue Findings

Overdue material findings must be visible to appropriate management.

---

# 48. Overdue High-Priority Findings

Overdue High findings require prompt management review and consideration of:

- Interim safeguards
- Additional resources
- Escalation
- Risk reassessment
- Risk acceptance

---

# 49. Overdue Critical Findings

An overdue Critical finding requires executive attention.

---

# 50. Interim Safeguards

Where final remediation cannot be completed promptly, interim safeguards should be considered.

---

# 51. Compensating Control

A compensating control may reduce exposure while permanent corrective action is pending.

---

# 52. Compensating Control Documentation

A material compensating control should identify:

- Original deficiency
- Compensating mechanism
- Expected protection
- Remaining limitation
- Owner
- Duration
- Validation

---

# 53. Compensating Control Limitation

A compensating control does not automatically close the original finding.

---

# 54. Remediation Evidence

When corrective action is reported complete, the owner must provide evidence showing what changed.

---

# 55. Remediation Evidence Examples

Examples include:

- Updated configuration
- Completed access review
- Updated procedure
- Training record
- Patched system
- Corrected application code
- Updated contract
- New approval workflow
- Recovery documentation
- Physical control change

---

# 56. Claimed Completion

A statement that corrective action is complete does not establish that the finding has been corrected.

---

# 57. Validation Pending

When remediation is reported complete, the finding should normally move to:

**Validation Pending**

until appropriate validation occurs.

---

# 58. Validation

Validation determines whether the corrective action:

- Was actually implemented
- Addresses the identified deficiency
- Produces expected evidence
- Operates as intended

---

# 59. Validation Methods

Validation may use:

- Inspection
- Observation
- Sampling
- Independent Performance
- Technical Testing
- Exercises
- Reconciliation

---

# 60. Validation Independence

Where practical and appropriate to the risk, corrective-action validation should be performed by someone other than the person who performed the corrective action.

---

# 61. Retesting

Retesting is required when demonstrating that the corrected control operates properly requires repeating appropriate assessment activity.

---

# 62. Retest Required

A finding may move to **Retest Required** when corrective action appears complete but effectiveness requires additional testing.

---

# 63. Retest Scope

Retesting should focus on the original deficiency while considering whether remediation introduced material new weaknesses.

---

# 64. Failed Retest

If the corrected control fails retesting:

- The finding remains open.
- The failure must be documented.
- Corrective action must be revised where necessary.
- Management must be informed when the result materially affects risk.

---

# 65. Successful Retest

A successful retest may support closure when:

- Required corrective action is complete.
- Evidence is sufficient.
- The original deficiency is corrected.
- No other required closure condition remains outstanding.

---

# 66. Closure

A finding may be closed only when sufficient evidence supports its approved disposition.

---

# 67. Closure Evidence

Closure evidence should identify:

- Corrective action completed
- Validation performed
- Retest result where applicable
- Remaining limitations
- Closure approval
- Closure date

---

# 68. Closure Is Not Administrative Cleanup

A finding must not be closed solely because:

- A ticket was closed.
- A policy was published.
- Equipment was purchased.
- A change request was submitted.
- The target date arrived.
- The owner states the problem is fixed.

---

# 69. Finding Closure Authority

Routine finding closure may be approved by the appropriate security or assurance authority after sufficient validation.

Findings involving material accepted risk require the approval established in [[POL-005 Risk Management Policy]].

---

# 70. Risk Acceptance

Management may choose to accept the remaining risk rather than remediate a finding when authorized.

---

# 71. Risk Acceptance Is Not Remediation

Risk acceptance does not mean the deficiency has been corrected.

The finding record must preserve that distinction.

---

# 72. Risk Acceptance Record

Risk acceptance must identify:

- Related risk
- Finding
- Rationale
- Approving authority
- Duration
- Conditions
- Required review

---

# 73. Risk Acceptance Authority

Risk acceptance follows [[POL-005 Risk Management Policy]].

| Risk Level | Required Authority |
|---|---|
| Low | Risk Owner |
| Moderate | Risk Owner and Executive Management |
| High | CEO after Information Security and Risk Committee review |
| Critical | CEO after Information Security and Risk Committee review; exceptional use |

---

# 74. High Risk Reassessment

Accepted High risk must be reassessed within 90 days.

---

# 75. Critical Risk Reassessment

Accepted Critical risk must be reassessed within 30 days.

---

# 76. Risk Accepted Finding Status

A finding with accepted risk may use **Risk Accepted** status for the authorized acceptance period.

---

# 77. Expired Risk Acceptance

Expiration of risk acceptance requires:

- Reassessment
- Renewal through proper authority
- Remediation
- Another authorized disposition

The acceptance must not silently become permanent.

---

# 78. Finding and Risk Relationship

Findings provide evidence that may affect enterprise risk.

A finding does not automatically create a new enterprise risk.

---

# 79. Existing Risk

When a finding affects an existing enterprise risk, the finding should reference the applicable Risk ID from [[REG-002 Enterprise Risk Register]].

---

# 80. New Risk Condition

If a finding identifies a material risk not adequately represented in the Enterprise Risk Register, the condition must be evaluated under [[POL-005 Risk Management Policy]].

---

# 81. Risk Reassessment Trigger

A finding may trigger risk reassessment when it demonstrates that:

- A material control is weaker than previously believed.
- A control has failed.
- Exposure has materially increased.
- An important assumption is incorrect.
- Treatment effectiveness differs materially from expectation.

---

# 82. Upward Risk Reassessment

Assessment evidence may justify increasing current residual risk when existing controls are less effective than previously assessed.

---

# 83. Downward Risk Reassessment

A finding closure does not automatically justify reducing risk.

Downward reassessment requires sufficient evidence that relevant controls now operate effectively.

---

# 84. Target Residual Risk

Target residual risk remains a prediction.

Successful corrective action does not require the validated post-treatment risk to equal the target.

---

# 85. Historical Integrity

The original May 2013 risk assessment must remain preserved.

Later findings, remediation, validation, and risk reassessment must not rewrite the historical assessment.

---

# 86. Duplicate Findings

An existing open finding should not be duplicated unnecessarily.

---

# 87. Repeat Observation

If a later assessment identifies the same unresolved weakness, the assessor should:

- Reference the existing finding.
- Update supporting evidence where appropriate.
- Evaluate whether priority or risk has changed.
- Consider whether the repeated condition indicates a broader weakness.

---

# 88. Recurring Finding

A recurring finding after prior closure should be evaluated for:

- Inadequate root-cause correction
- Control-design weakness
- Insufficient training
- Inadequate oversight
- Process weakness
- Technical limitation
- Accountability failure

---

# 89. Reopening a Finding

A previously closed finding may be reopened if later evidence demonstrates that:

- Remediation was ineffective.
- Closure was unsupported.
- The same deficiency materially persists.

---

# 90. New Finding Versus Reopened Finding

A materially different condition should receive a new Finding ID.

A continuation of the original deficiency may use the existing Finding ID when preserving that history provides clearer traceability.

---

# 91. Vulnerability Findings

Not every vulnerability identified by a vulnerability scanner must become an individual entry in this register.

---

# 92. Vulnerability Tracking

Routine vulnerabilities are managed through:

- [[PRO-004 Vulnerability Management Program]]
- [[PROC-006 Vulnerability Assessment Procedure]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]

---

# 93. Vulnerability Escalation to Finding

A vulnerability condition may become a formal finding when it indicates:

- Material control failure
- Repeated remediation failure
- Significant overdue remediation
- Systemic configuration weakness
- Material enterprise risk

---

# 94. Penetration Testing Findings

Material penetration-test findings requiring corrective action must be tracked in this register or through an explicitly linked corrective-action record.

---

# 95. Infinity Penetration Test Chain

Infinity penetration testing supports:

**Penetration Test → Finding → Remediation → Retest → Control Effectiveness → R006 Risk Reassessment**

---

# 96. Incident Findings

An incident may generate findings concerning:

- Prevention
- Detection
- Escalation
- Containment
- Evidence handling
- Recovery
- Communication
- Control design

---

# 97. Incident Does Not Automatically Mean Control Failure

An incident may occur even when controls operate as designed.

Assessment must determine whether a material control deficiency exists.

---

# 98. Recovery-Test Findings

Recovery testing may produce findings involving:

- Recovery Time Objective (RTO)
- Recovery Point Objective (RPO)
- Backup coverage
- Restore capability
- Recovery sequencing
- Documentation
- Personnel readiness
- Technical dependency

---

# 99. R027 Example

R027 Backup Failure has:

- Inherent Risk: **20 Critical**
- Current Residual Risk: **12 High**
- Target Residual Risk: **5 Moderate**

---

# 100. Illustrative Recovery Requirement

Assume a Critical process requires:

- RTO: **8 hours**
- RPO: **4 hours**

---

# 101. Illustrative Initial Test

An authorized recovery test produces:

- Recovery completion: **11 hours 37 minutes**
- Data loss: **58 minutes**

Result:

- RTO: **Fail**
- RPO: **Pass**

---

# 102. Illustrative Finding

The RTO failure could support a finding stating that recovery capability did not satisfy the established recovery-time requirement.

---

# 103. Illustrative Corrective Action

Corrective action could address the actual cause of the failure, such as:

- Recovery procedure
- Recovery sequencing
- Technical configuration
- Documentation
- Personnel readiness

---

# 104. Illustrative Retest

A later authorized retest produces:

- Recovery completion: **6 hours 42 minutes**
- Data loss: **47 minutes**

Result:

- RTO: **Pass**
- RPO: **Pass**

---

# 105. Illustrative Closure

If sufficient evidence demonstrates the original deficiency has been corrected, the finding may be closed.

The successful retest may then support reassessment of R027.

---

# 106. Example Limitation

The recovery values above illustrate the finding and corrective-action process.

They are not records of an actual Dunder Mifflin recovery test or finding.

---

# 107. Access-Control Findings

Access-control findings may involve:

- Excessive access
- Inappropriate privileged access
- Delayed termination
- Dormant accounts
- Contractor access
- Shared accounts
- Failed access review
- Emergency access

---

# 108. Personnel Findings

Personnel-security findings may involve:

- Incomplete termination coordination
- Missing confidentiality requirement
- Unreturned company property
- Key-person dependency
- Insufficient cross-training
- Contractor personnel weakness

---

# 109. Physical Security Findings

Physical-security findings may involve:

- Unauthorized Restricted-area access
- Uncontrolled key
- Unreturned access card
- Visitor-control weakness
- Warehouse cage weakness
- Environmental protection deficiency

---

# 110. Third-Party Findings

Third-party findings may involve:

- Missing contractual requirement
- Missing confidentiality protection
- Excessive third-party access
- Inadequate due diligence
- Missing incident-notification requirement
- Continuity weakness
- Unresolved third-party security deficiency

---

# 111. Secure Development Findings

Secure-development findings may involve:

- Environment separation
- Threat modeling
- Code review
- Security testing
- Change approval
- Contractor access
- Source-code control
- Documentation
- Transferability

---

# 112. Fraud-Control Findings

Fraud-control findings may involve:

- Separation of Duties
- Approval
- Transaction attribution
- Payment verification
- Reconciliation
- Vendor-master access
- Payroll access
- Inventory accountability

---

# 113. Assurance Findings

Assurance-process findings may involve:

- Missing evidence
- Incomplete assessment
- Unsupported control-effectiveness rating
- Overdue corrective action
- Missing retest
- Improper finding closure
- Expired exception
- Expired risk acceptance

---

# 114. Finding Escalation

A finding must be escalated when its significance exceeds the authority of the current owner or operating team.

---

# 115. Immediate Threat

If assessment activity identifies an immediate threat to:

- Human safety
- Sensitive information
- Critical systems
- Material business operations

appropriate response must begin without waiting for formal finding documentation.

---

# 116. Security Event Escalation

Suspected active compromise must be handled under:

- [[PROC-010 Security Event Escalation Procedure]]
- [[PLN-001 Incident Response Plan]]

---

# 117. Safety Priority

Human life and safety take priority over:

- Systems
- Operations
- Facilities
- Equipment
- Inventory
- Revenue
- Other assets

---

# 118. Corrective Action Dependencies

Corrective actions may depend on:

- Budget
- Procurement
- Technology
- Third parties
- Personnel
- Other remediation
- Business scheduling

Dependencies must be visible when they materially affect completion.

---

# 119. Resource Constraints

Resource limitations may affect remediation timing.

They do not erase the finding.

---

# 120. Management Decision

When management cannot complete corrective action within the expected period, management must decide whether to:

- Provide additional resources
- Implement interim safeguards
- Revise the remediation approach
- Accept the risk through proper authority

---

# 121. Finding Metrics

Finding metrics are maintained through [[REG-005 Security Metrics Catalog]].

---

# 122. Potential Finding Metrics

Metrics may include:

- Open findings
- Open findings by priority
- Overdue findings
- Average finding age
- Findings awaiting validation
- Findings awaiting retest
- Corrective actions completed
- Successful retests
- Failed retests
- Reopened findings
- Recurring findings
- Findings with accepted risk

---

# 123. Metric Interpretation

Finding counts must be interpreted in context.

An increase in findings may reflect:

- Increased control weakness
- Expanded assessment coverage
- Improved detection
- Better documentation
- A combination of factors

---

# 124. Finding Aging

Finding age should be measured from the date the finding was formally identified until:

- Closure, or
- The current reporting date for open findings.

---

# 125. Aging Does Not Replace Priority

An older Low finding is not automatically more important than a newly identified Critical finding.

---

# 126. Executive Reporting

Executive reporting should focus on findings that materially affect:

- Enterprise risk
- Business operations
- Significant security exposure
- Required executive decisions
- Risk acceptance
- Resource allocation

---

# 127. Management Reporting

Management reporting should focus on:

- Accountable owner
- Corrective action
- Due date
- Progress
- Overdue status
- Validation
- Retesting
- Recurring weakness

---

# 128. Operational Reporting

Operational reporting should focus on:

- Evidence
- Control condition
- Technical detail
- Corrective tasks
- Validation activity
- Exceptions

---

# 129. Reporting Chain

Finding information should support:

**Technical Evidence → Operational Exception → Management Impact → Enterprise Risk → Executive Decision**

---

# 130. Information Security and Risk Committee

The Information Security and Risk Committee (ISRC) reviews material findings as appropriate.

---

# 131. ISRC Finding Review

ISRC review may include:

- Significant deficiencies
- Material overdue findings
- Repeated control failures
- High or Critical risk implications
- Risk acceptance
- Resource conflicts
- Cross-functional remediation

---

# 132. Sensitive Findings

Finding details must be distributed according to business need.

---

# 133. Restricted Finding Information

Finding evidence involving:

- Credentials
- Sensitive system configuration
- Vulnerability details
- Personal information
- Investigation information
- Restricted business information

must receive appropriate protection.

---

# 134. Personnel Privacy

Personnel-related findings must be handled with appropriate privacy and confidentiality.

---

# 135. Investigation Separation

A security finding is not automatically a disciplinary conclusion.

Human Resources, management, Counsel/Compliance, or law enforcement responsibilities remain separate as appropriate.

---

# 136. Third-Party Confidentiality

Outside assessors receiving sensitive information must have an appropriate Non-Disclosure Agreement (NDA) or equivalent enforceable confidentiality obligation before access.

---

# 137. Assessment Independence

The level of independence used to validate a finding should reflect:

- Risk
- Control importance
- Technical complexity
- Potential conflict of interest
- Required expertise

---

# 138. Independent Performance

Where appropriate, an assessor may perform an authorized procedure independently to determine whether the expected control result occurs.

---

# 139. Independent Performance Limitation

Independent Performance must not create unnecessary operational, security, safety, or business risk.

---

# 140. Finding Disagreement

A control owner may disagree with an assessment finding.

---

# 141. Finding Dispute

A disagreement must be resolved through evidence and appropriate management review rather than by deleting or altering an unfavorable finding without support.

---

# 142. Finding Revision

A finding may be revised when new evidence demonstrates that:

- The original condition was inaccurate.
- Scope was misunderstood.
- Priority requires adjustment.
- Related risks require adjustment.
- Corrective action should change.

The reason for a material revision must be documented.

---

# 143. False Positive

If validation establishes that a reported deficiency did not actually exist, the record may be closed as unsupported or withdrawn while preserving sufficient history to explain the disposition.

---

# 144. Finding Cancellation

A finding must not simply disappear from the register after assignment of a Finding ID.

---

# 145. Register Integrity

Finding history should preserve material changes involving:

- Priority
- Owner
- Target date
- Status
- Corrective action
- Validation
- Closure

---

# 146. No Silent Deletion

Closed, accepted, withdrawn, or superseded findings must not be silently deleted when their history remains relevant to assurance or risk.

---

# 147. Assessment Work Plan Relationship

Findings should be traceable to the applicable [[TMP-001 Assessment Work Plan Template]] record when generated through a planned assessment.

---

# 148. Annual Assurance Plan Relationship

[[PLN-005 Annual Assurance Plan]] determines scheduled assurance work that may generate findings.

---

# 149. Control Inventory Relationship

[[REG-003 Enterprise Security Control Inventory]] provides the authoritative control reference for findings.

---

# 150. Risk Register Relationship

[[REG-002 Enterprise Risk Register]] provides the authoritative enterprise risk reference.

---

# 151. Risk Treatment Relationship

[[RTP-001 Enterprise Risk Treatment Plan]] identifies planned treatments that may become corrective actions or address conditions identified through findings.

---

# 152. Corrective Action Versus Risk Treatment

A corrective action and a risk treatment may overlap but are not automatically the same.

A risk treatment addresses enterprise risk.

A corrective action addresses an identified deficiency.

---

# 153. Finding Closure and Risk Treatment

Closing a finding does not automatically mean the related risk treatment is complete.

---

# 154. Risk Treatment Completion and Finding Closure

Completing a risk-treatment activity does not automatically close a related finding.

Each requires its own required evidence and validation.

---

# 155. Continuous Improvement

Findings provide an important input to continuous improvement.

---

# 156. Continuous Improvement Chain

**Finding → Corrective Action → Validation → Lessons Learned → Control Improvement → Risk Reassessment**

---

# 157. Lessons Learned

Material findings should be considered for lessons involving:

- Control design
- Procedure
- Training
- Architecture
- Governance
- Documentation
- Recovery
- Accountability

---

# 158. Systemic Weakness

Multiple findings affecting different controls may indicate a common systemic weakness.

---

# 159. Systemic Finding

Where several individual conditions share a common root cause, management may establish a broader finding or corrective-action program while preserving traceability to the individual evidence.

---

# 160. Continuous Monitoring

Continuous monitoring may identify conditions requiring formal findings between scheduled assessments.

---

# 161. Continuous Monitoring Is Risk-Based

Continuous monitoring does not mean every control is continuously tested.

Monitoring frequency must reflect:

- Risk
- Business impact
- Control importance
- Available capability

---

# 162. Finding Review Frequency

Open material findings must be reviewed at least monthly.

---

# 163. Monthly Review

Monthly review should consider:

- New findings
- Priority
- Ownership
- Corrective-action progress
- Due dates
- Overdue findings
- Validation status
- Retesting
- Risk implications
- Escalation requirements

---

# 164. Immediate Review

Critical or rapidly changing findings must be reviewed according to their urgency rather than waiting for the monthly cycle.

---

# 165. Closure Review

Before closure, the reviewer should confirm:

- Requirement identified
- Condition documented
- Corrective action complete
- Evidence sufficient
- Validation complete
- Retest complete where required
- Risk implications considered

---

# 166. Register Maintenance

The CIO is accountable for maintenance of this register.

The IT & Information Security Manager coordinates routine finding tracking and reporting.

---

# 167. Finding Owners

Finding owners are responsible for:

- Corrective-action progress
- Evidence
- Communication
- Escalation of delays
- Supporting validation

---

# 168. Assessors

Assessors are responsible for:

- Evidence-based conclusions
- Accurate scope
- Clear findings
- Appropriate validation
- Documenting limitations

---

# 169. Management

Management is responsible for:

- Providing resources
- Resolving cross-functional obstacles
- Reviewing material delays
- Making authorized risk decisions

---

# 170. Information Security and Risk Committee

The ISRC provides oversight of material finding and corrective-action issues requiring cross-functional or executive governance.

---

# 171. CEO

The CEO retains authority for:

- High-risk acceptance after ISRC review
- Critical-risk acceptance after ISRC review
- Material executive risk decisions

---

# 172. Register Update Requirements

The register must be updated when material changes occur to:

- Finding status
- Priority
- Owner
- Corrective action
- Target date
- Validation
- Retest
- Risk acceptance
- Closure

---

# 173. Record Retention

Closed finding records must be retained sufficiently to support:

- Historical assurance
- Recurrence analysis
- Risk history
- Management review
- Future assessments

---

# 174. Historical Record

Later remediation must not erase evidence that a control deficiency previously existed.

---

# 175. Register Quality

The register should allow a reviewer to determine:

1. What was wrong?
2. What requirement was affected?
3. What evidence proved the condition?
4. What control was involved?
5. What risk was affected?
6. Who was accountable?
7. What corrective action was required?
8. Was the correction validated?
9. Was retesting required?
10. Why was the finding closed?

---

# 176. Assurance Principle

A finding is not complete when the problem is merely identified.

The assurance lifecycle is complete when the organization can demonstrate:

**Finding → Corrective Action → Validation → Retest where required → Control Effectiveness → Risk Reassessment where appropriate**

---

# 177. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-004 Vulnerability Management Program]]
- [[PRO-005 Security Operations Program]]
- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[PRO-009 Security Governance Framework]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-005 Security Metrics Catalog]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[STD-007 Penetration Testing Standard]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[STD-009 Infinity Security Standard]]
- [[PROC-001 Joiner-Mover-Leaver Procedure]]
- [[PROC-003 Access Review Procedure]]
- [[PROC-006 Vulnerability Assessment Procedure]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]
- [[PROC-008 Security Monitoring Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-017 Personnel Security Procedure]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-019 Application Security Assessment Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PLN-005 Annual Assurance Plan]]
- [[TMP-001 Assessment Work Plan Template]]
- [[TMP-003 Recovery Test Template]]

---

# 178. Review

This register must be reviewed:

- At least monthly while material findings remain open
- Following material assessment activity
- Following material corrective-action change
- Following validation or retesting
- Following material risk acceptance
- Following significant control failure

Routine finding updates do not require CEO approval.

Material changes to the structure or governance of this register require approval consistent with the enterprise security governance framework.

---

# 179. Revision History

| Version | Date     | Description                                  | Approval |
| ------- | -------- | -------------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Finding & Corrective Action Register | CEO      |