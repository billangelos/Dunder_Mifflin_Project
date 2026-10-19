# PLN-005 Annual Assurance Plan

## Document Control

| Field | Value |
|---|---|
| Document ID | PLN-005 |
| Title | Annual Assurance Plan |
| Version | 1.0 |
| Classification | Confidential |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Risk, Control, Business, or Technology Change |

---

# 1. Purpose

This plan establishes Dunder Mifflin's annual security assurance activities.

The Annual Assurance Plan converts the enterprise security assurance program into a risk-based schedule of assessment, testing, review, and validation activities.

---

# 2. Objectives

The Annual Assurance Plan is intended to determine:

- What should be assessed
- Why it should be assessed
- When it should be assessed
- Who should perform the assessment
- What level of independence is appropriate
- Which assessment methods should be used
- What evidence should be collected
- How results should be documented
- When findings require escalation
- When results should trigger risk reassessment

---

# 3. Authority

This plan operates under:

- [[POL-001 Information Security Policy]]
- [[POL-005 Risk Management Policy]]
- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[PRO-009 Security Governance Framework]]

---

# 4. Assurance Principle

Security assurance provides evidence concerning whether security requirements and controls:

- Exist
- Are implemented
- Operate as intended
- Produce expected results
- Remain appropriate to enterprise risk

---

# 5. Assurance Is Evidence-Based

Assurance conclusions must be supported by evidence.

The absence of a known failure does not establish control effectiveness.

---

# 6. Annual Planning

Security assurance must be planned annually.

The plan may be revised during the year when material conditions change.

---

# 7. Risk-Based Planning

Assessment effort should be proportional to:

- Inherent risk
- Current residual risk
- Business impact
- Control criticality
- Information sensitivity
- Prior findings
- Incident history
- Significant changes
- Third-party dependency
- Recovery requirements
- Time since previous assessment

---

# 8. Inherent Risk Still Matters

Assessment prioritization must not rely only on current residual risk.

A control may be responsible for reducing a severe inherent risk to a lower current residual risk.

Failure of that control could restore substantial exposure.

---

# 9. Example

A risk with:

- Inherent Risk: **20 Critical**
- Current Residual Risk: **8 Moderate**

may still justify substantial assurance activity when the lower residual risk depends heavily on a small number of important controls.

---

# 10. Current Residual Risk

Current residual risk represents exposure after considering controls that actually exist and are credited in the current assessment.

It is a primary assurance-planning input.

---

# 11. Target Residual Risk

Target residual risk represents predicted exposure after proposed treatments are implemented and validated.

Target residual risk does not establish current control effectiveness.

---

# 12. No Assurance Credit for Planned Controls

A planned or proposed control must not receive current effectiveness credit merely because it appears in:

- A policy
- A plan
- A roadmap
- A risk treatment
- A purchase request
- A project schedule

---

# 13. Business Impact Analysis

The Business Impact Analysis (BIA) provides another major assurance-planning input.

[[RPT-002 Business Impact Analysis]] identifies:

- Business criticality
- Maximum Tolerable Downtime (MTD)
- Recovery Time Objective (RTO)
- Recovery Point Objective (RPO)

---

# 14. BIA Priority

Controls supporting Critical or High business processes should generally receive greater assurance attention than controls supporting lower-impact functions when other factors are comparable.

---

# 15. Control Criticality

Control criticality considers how important a control is to:

- Preventing material security events
- Detecting material security events
- Limiting impact
- Maintaining business operations
- Supporting recovery
- Protecting sensitive information
- Supporting accountability

---

# 16. Critical Controls

Critical controls require stronger assurance planning.

Criticality does not mean the control must be tested continuously.

---

# 17. Control Inventory

The authoritative inventory of enterprise security controls is:

[[REG-003 Enterprise Security Control Inventory]]

---

# 18. Control Inventory Use

The Annual Assurance Plan uses the control inventory to identify:

- Control owner
- Control objective
- Related requirement
- Related risk
- Implementation status
- Effectiveness status
- Evidence
- Assessment method
- Assessment frequency

---

# 19. Prior Findings

Prior findings must influence future assurance planning.

Relevant information includes:

- Open findings
- High-priority findings
- Critical findings
- Overdue findings
- Failed retests
- Reopened findings
- Recurring findings

---

# 20. Finding Register

Findings and corrective actions are maintained in:

[[REG-004 Finding & Corrective Action Register]]

---

# 21. Incident History

Material security incidents may justify increased assurance activity for affected:

- Controls
- Systems
- Processes
- Third parties
- Business functions

---

# 22. Significant Change

Significant change may trigger additional assurance outside the normal annual schedule.

Examples include:

- Major application release
- Significant architecture change
- New critical vendor
- Major facility change
- Material identity-management change
- Major recovery-design change
- Significant organizational restructuring

---

# 23. Assessment Methods

Authorized assessment methods include:

1. Inspection
2. Observation
3. Independent Performance
4. Technical Testing
5. Sampling
6. Exercises
7. Reconciliation

---

# 24. Inspection

Inspection evaluates documents, configurations, records, or other evidence.

Examples include:

- Policies
- Procedures
- Configuration records
- Access lists
- Contracts
- Logs
- Training records
- Backup records
- Change records

---

# 25. Observation

Observation evaluates a control or process while it is being performed.

Examples include:

- Visitor processing
- Warehouse access
- Backup handling
- Change execution
- Manual processing

---

# 26. Independent Performance

Independent Performance means an assessor performs an authorized procedure independently to determine whether the expected result occurs.

---

# 27. Independent Performance Example

An assessor may independently:

- Verify a sample of access permissions
- Restore selected backup data
- Validate a configuration
- Reconcile selected records

when authorized and safe.

---

# 28. Independent Performance Limitation

Independent Performance must not create unnecessary:

- Operational disruption
- Security exposure
- Data integrity risk
- Safety risk

---

# 29. Technical Testing

Technical Testing may include:

- Vulnerability assessment
- Penetration testing
- Configuration testing
- Application security testing
- Network discovery
- Authentication testing
- Recovery testing

---

# 30. Sampling

Sampling may be used when testing the entire population is unnecessary or impractical.

---

# 31. Sample Selection

Sample selection should consider:

- Risk
- Population size
- Control frequency
- Materiality
- Known exceptions
- Prior findings

---

# 32. Exercises

Exercises may be used to evaluate:

- Incident response
- Business continuity
- Disaster recovery
- Manual processing
- Communication
- Escalation

---

# 33. Reconciliation

Reconciliation compares related records to identify:

- Missing transactions
- Duplicates
- Unauthorized activity
- Inconsistency
- Data integrity problems

---

# 34. Assessment Independence

Assessment independence should reflect:

- Risk
- Control importance
- Required expertise
- Potential conflict of interest
- Nature of the assessment

---

# 35. Independence Is Proportional

Not every control requires an outside assessor.

Routine controls may be reviewed internally.

Higher-risk or technically specialized assessments may require greater independence.

---

# 36. Independent Enterprise Control Assessment

Dunder Mifflin requires an independent enterprise control assessment at least every two years.

---

# 37. Penetration Testing

Enterprise penetration testing is required at least every two years.

Infinity receives application-focused penetration testing annually.

---

# 38. Infinity Security Assessment

Infinity receives a security assessment annually under:

[[PROC-019 Application Security Assessment Procedure]]

---

# 39. Infinity Assurance

Infinity assurance should evaluate:

- Architecture
- Authentication
- Authorization
- Input handling
- Session management
- Data protection
- Application configuration
- Development practices
- Change and release control
- Contractor access
- Vulnerability remediation
- Documentation
- Transferability

---

# 40. Infinity Assessment Chain

Infinity assurance supports:

**Security Assessment / Penetration Test → Finding → Remediation → Retest → Control Effectiveness → R006 Risk Reassessment**

---

# 41. Vulnerability Assessment

Internal vulnerability assessment is performed monthly under:

- [[PRO-004 Vulnerability Management Program]]
- [[PROC-006 Vulnerability Assessment Procedure]]

---

# 42. Vulnerability Remediation Validation

Remediation and retesting are performed under:

[[PROC-007 Vulnerability Remediation & Retest Procedure]]

---

# 43. Network Discovery

Network discovery and rogue wireless assessment are performed every six months.

---

# 44. Expected Wireless Baseline

The expected wireless environment is:

- No corporate wireless network
- One ceiling-mounted Internet-only guest wireless access point in the Scranton Headquarters lobby

Unexpected wireless infrastructure requires investigation.

---

# 45. Access Review

Ordinary user access is reviewed annually.

Privileged access is reviewed quarterly.

---

# 46. Physical Access Review

Physical access is reviewed annually.

Restricted-area access receives particular attention.

---

# 47. Contractor Access Review

Contractor access must be reviewed according to:

- Approved duration
- Business need
- Sponsorship
- System sensitivity
- Contract requirements

---

# 48. Third-Party Review

Third-party security review frequency is based on classification.

---

# 49. Critical Third Parties

Critical third parties receive security review at least annually.

---

# 50. Important Third Parties

Important third parties receive security review at least every two years.

---

# 51. Routine Third Parties

Routine third parties receive risk-appropriate oversight based on:

- Service
- Access
- Information exposure
- Business dependency

---

# 52. Backup Restore Testing

Representative restore testing is performed quarterly.

---

# 53. Critical Recovery Testing

Critical recovery capability receives meaningful testing at least annually.

---

# 54. Recovery Validation

Recovery testing must evaluate applicable:

- RTO
- RPO
- Technical recovery
- Documentation
- Personnel readiness
- Business validation

---

# 55. Recovery Test Template

Recovery tests are documented using:

[[TMP-003 Recovery Test Template]]

or an equivalent record containing the required information.

---

# 56. Incident Response Exercise

Incident Response capability receives an exercise at least annually.

---

# 57. Business Continuity Exercise

Business Continuity capability receives meaningful exercise at least annually.

---

# 58. Manual Processing Exercise

Manual processing procedures receive periodic exercise appropriate to business criticality.

Critical manual continuity capabilities should be exercised at least annually.

---

# 59. Personnel Security Review

Personnel-security assurance should include review of selected:

- Joiners
- Movers
- Leavers
- Contractor personnel
- Company-property recovery
- Key-person dependencies
- Cross-training

---

# 60. Termination Sampling

Termination testing should evaluate whether:

- Human Resources provided required notification.
- Logical access was disabled promptly.
- Physical access was revoked.
- Company equipment was addressed.
- Keys, cards, and smart cards were addressed.
- Required records were completed.

---

# 61. Physical Security Assessment

Physical security assessment should include selected:

- Public areas
- Controlled areas
- Restricted areas
- Warehouse high-value cages
- Significant Information Technology areas
- Visitor controls
- Access credentials
- Environmental safeguards

---

# 62. Security Awareness Review

Security awareness assurance should evaluate:

- Initial training
- Annual refresher
- Annual assessment
- Monthly phishing simulation activity
- Corrective awareness activity

---

# 63. Change Management Assessment

Change-management assurance should evaluate selected changes for:

- Authorization
- Risk consideration
- Testing
- Separation of duties where practical
- Rollback planning
- Implementation
- Verification
- Documentation

---

# 64. Secure Development Assessment

Secure-development assurance should evaluate:

- Development, test, and production separation
- Threat modeling
- Secure design
- Code review
- Security testing
- Change approval
- Contractor development access
- Documentation
- Source-code control

---

# 65. Configuration Assessment

Configuration assurance should evaluate:

- Approved configuration requirements
- Unauthorized changes
- Security settings
- Administrative access
- Configuration backups
- Exceptions

---

# 66. Security Operations Assessment

Security Operations assurance should evaluate:

- Security event review
- Escalation
- Malware response
- Monitoring records
- After-hours response
- Evidence handling

---

# 67. Incident Response Assessment

Incident Response assurance should evaluate:

- Classification
- Escalation
- Containment
- Evidence handling
- Communication
- Recovery
- Lessons learned
- Corrective action

---

# 68. Fraud-Control Assessment

Selected assurance activity should evaluate controls supporting:

- Vendor fraud prevention
- Sales fraud prevention
- Payroll fraud prevention
- Inventory theft prevention

---

# 69. Fraud-Control Methods

Methods may include:

- Sampling
- Reconciliation
- Inspection
- Approval review
- Access review
- Transaction attribution

---

# 70. Annual Assurance Schedule

The following schedule establishes the baseline annual assurance program.

| Assurance Activity | Frequency | Primary Method | Primary Owner | Independence |
|---|---|---|---|---|
| Internal Vulnerability Assessment | Monthly | Technical Testing | IT & Information Security Manager | Internal |
| Vulnerability Remediation Retest | As Required | Technical Testing | IT & Information Security Manager | Appropriate separation where practical |
| Privileged Access Review | Quarterly | Inspection / Sampling | CIO | Management Review |
| Ordinary Access Review | Annual | Inspection / Sampling | CIO | Management Review |
| Contractor Access Review | Quarterly / At Renewal | Inspection | CIO | Management Review |
| Representative Backup Restore Test | Quarterly | Independent Performance / Technical Testing | CIO | Personnel other than original backup operator where practical |
| Critical Recovery Test | Annual | Exercise / Technical Testing | CIO | Cross-functional |
| Network Discovery / Rogue Wireless Assessment | Every 6 Months | Technical Testing | Network / Security Administrator | Internal |
| Physical Access Review | Annual | Inspection / Sampling | COO | Management Review |
| Personnel Security Review | Annual | Inspection / Sampling | CFO | Cross-functional |
| Security Awareness Program Review | Annual | Inspection / Sampling | CIO | Management Review |
| Incident Response Exercise | Annual | Exercise | CIO | Cross-functional |
| Business Continuity Exercise | Annual | Exercise | COO | Cross-functional |
| Manual Processing Exercise | Annual for Critical Capabilities | Exercise / Reconciliation | COO | Cross-functional |
| Infinity Security Assessment | Annual | Inspection / Technical Testing / Sampling | CIO | Appropriate technical independence |
| Infinity Penetration Test | Annual | Technical Testing | CIO | Independent qualified tester |
| Infinity Transferability Review | Annual | Inspection / Independent Performance where appropriate | CIO | Management / Qualified Reviewer |
| Critical Third-Party Security Review | Annual | Inspection | CIO | Management Review |
| Important Third-Party Security Review | Every 2 Years | Inspection | CIO | Management Review |
| Enterprise Penetration Test | Every 2 Years | Technical Testing | CIO | Independent qualified tester |
| Independent Enterprise Control Assessment | Every 2 Years | Multiple | CIO | Independent assessor |
| Finding & Corrective Action Review | Monthly | Inspection | CIO | Management Review |
| Security Metrics Review | Quarterly | Inspection / Analysis | CIO | Management Review |
| Risk Treatment Validation | As Treatments Reach Validation Pending | Appropriate Method | CIO | Risk-appropriate independence |
| Risk Reassessment | Annual and Event-Driven | Analysis | CIO | Governance Review |

---

# 71. Schedule Interpretation

The schedule establishes minimum planned frequency.

It does not prevent additional assessment when risk warrants it.

---

# 72. Monthly Activities

Monthly assurance activity includes:

- Vulnerability assessment
- Finding review
- Corrective-action review
- Relevant security metric review
- Treatment status review where appropriate

---

# 73. Quarterly Activities

Quarterly assurance activity includes:

- Privileged access review
- Representative restore testing
- Security metrics review
- Contractor access review where applicable
- Risk-treatment progress review

---

# 74. Semiannual Activities

Semiannual activity includes:

- Network discovery
- Rogue wireless assessment

---

# 75. Annual Activities

Annual assurance includes:

- Ordinary access review
- Physical access review
- Personnel security review
- Security awareness review
- Incident Response exercise
- Business Continuity exercise
- Critical recovery testing
- Critical manual continuity exercise
- Infinity security assessment
- Infinity penetration test
- Infinity transferability review
- Critical third-party review
- Enterprise risk reassessment

---

# 76. Biennial Activities

At least every two years:

- Enterprise penetration test
- Independent enterprise control assessment
- Important third-party review

---

# 77. Event-Driven Assurance

Additional assurance may be triggered by:

- Security incident
- Material control failure
- Major finding
- Failed recovery test
- Failed retest
- Significant application release
- Significant architecture change
- Material vendor change
- Significant facility change
- Material personnel change
- Significant risk change

---

# 78. Annual Assessment Work Plan

The Annual Assurance Plan establishes the high-level schedule.

Individual assessments should be defined using:

[[TMP-001 Assessment Work Plan Template]]

---

# 79. Assessment Work Plan Purpose

The Assessment Work Plan converts a scheduled assurance activity into specific assessment work.

---

# 80. Assessment Work Plan Requirements

Each material assessment should define:

- Assessment title
- Objective
- Scope
- Requirement
- Controls
- Related risks
- Systems or processes
- Assessor
- Independence
- Assessment methods
- Evidence
- Sampling
- Schedule
- Expected output

---

# 81. Assessment Objective

The objective states what the assessment is intended to determine.

---

# 82. Scope

Scope must identify what is included and, where important, what is excluded.

---

# 83. Requirement

The work plan should identify the requirement against which the control is being assessed.

---

# 84. Control Selection

The work plan should identify applicable controls from:

[[REG-003 Enterprise Security Control Inventory]]

---

# 85. Risk Selection

The work plan should identify related risks from:

[[REG-002 Enterprise Risk Register]]

---

# 86. Evidence Planning

The work plan should identify expected evidence before assessment begins where practical.

---

# 87. Evidence Examples

Expected evidence may include:

- Configuration
- Logs
- Reports
- Access records
- Change records
- Training records
- Contracts
- Backup records
- Test results
- Incident records
- Physical observations
- Interviews
- Transaction records

---

# 88. Evidence Sufficiency

The assessor must determine whether available evidence is sufficient to support the conclusion.

---

# 89. Missing Evidence

Missing evidence may result in:

- Additional testing
- Expanded sampling
- Unable to Determine
- Finding

depending on the circumstances.

---

# 90. Sampling Plan

Where sampling is used, the work plan should define:

- Population
- Sample size or approach
- Selection method
- Relevant risk factors

---

# 91. Sampling Integrity

Samples must not be selected solely to avoid known problems or produce a favorable result.

---

# 92. Assessment Criteria

Assessment criteria should be established before conclusions are made.

---

# 93. Assessment Output

Assessment output should identify:

- Scope completed
- Methods performed
- Evidence examined
- Limitations
- Conclusions
- Findings
- Required corrective action
- Retest requirements
- Risk implications

as applicable.

---

# 94. Control Effectiveness

Assessment may support a control-effectiveness conclusion of:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

---

# 95. Not Yet Assessed

A control lacking sufficient assessment evidence should remain Not Yet Assessed where applicable rather than being assigned unsupported effectiveness.

---

# 96. Effective

Effective means sufficient evidence demonstrates that the control is appropriately designed and operating sufficiently to achieve its intended objective.

---

# 97. Partially Effective

Partially Effective means the control provides meaningful protection but contains deficiencies or limitations that reduce expected effectiveness.

---

# 98. Ineffective

Ineffective means the control does not provide sufficient protection to achieve its intended objective.

---

# 99. Not Implemented

Not Implemented means the required control does not currently exist or has not been deployed sufficiently to operate.

---

# 100. Implementation Versus Effectiveness

Implementation and effectiveness must remain separate concepts.

**Implemented does not mean Effective.**

---

# 101. Finding Creation

A material deficiency identified during assessment must be recorded in:

[[REG-004 Finding & Corrective Action Register]]

---

# 102. Finding Lifecycle

The finding lifecycle is:

**Assessment → Finding → Corrective Action → Validation → Retest → Closure → Risk Reassessment**

---

# 103. Corrective Action

Corrective action must address the identified weakness.

---

# 104. Validation Pending

A reported corrective action should not be treated as validated merely because the owner reports completion.

---

# 105. Validation

Validation confirms whether the corrective action:

- Was implemented
- Addresses the deficiency
- Produces expected evidence
- Operates as intended

---

# 106. Retesting

Retesting is required when demonstrating effectiveness requires repeating relevant assessment activity.

---

# 107. Failed Retest

A failed retest keeps the finding open and may require:

- Revised remediation
- Additional safeguards
- Escalation
- Risk reassessment

---

# 108. Successful Retest

Successful retesting may support:

- Finding closure
- Updated control-effectiveness assessment
- Risk reassessment

---

# 109. Risk Reassessment

Assessment evidence may justify reassessing enterprise risk.

---

# 110. Upward Risk Reassessment

Risk may increase when assurance demonstrates:

- Control failure
- Greater exposure
- Incorrect assumptions
- Inadequate treatment
- Significant new weakness

---

# 111. Downward Risk Reassessment

Risk may decrease when sufficient evidence demonstrates that relevant controls operate effectively.

---

# 112. No Automatic Risk Reduction

Completing an assessment does not automatically reduce risk.

Implementing a control does not automatically reduce risk.

Closing a finding does not automatically reduce risk.

Risk reduction requires appropriate evidence and risk reassessment.

---

# 113. Target Residual Risk

Target residual risk is a prediction.

Validated post-treatment risk may be:

- Higher than target
- Equal to target
- Lower than target

depending on actual evidence.

---

# 114. Historical Risk Preservation

The original May 2013 risk assessment must remain preserved.

Later validated risk levels become the current assessment without rewriting the historical record.

---

# 115. Assurance Metrics

Assurance performance is measured through:

[[REG-005 Security Metrics Catalog]]

---

# 116. Key Assurance Metrics

Important assurance metrics include:

- Annual Assurance Plan completion
- Critical controls assessed as scheduled
- Effective controls
- Partially Effective controls
- Ineffective controls
- Controls awaiting validation
- Open findings
- High-priority findings
- Critical findings
- Overdue findings
- Failed retests
- Reopened findings
- Recurring findings

---

# 117. Plan Completion

Annual Assurance Plan completion should measure:

**Completed planned assessments ÷ assessments scheduled to date × 100**

---

# 118. Completion Is Not Effectiveness

A high assessment-completion rate does not establish that controls are effective.

It establishes that planned assurance work is being performed.

---

# 119. Assurance Coverage

Management should evaluate whether the annual plan provides sufficient coverage of:

- High-risk areas
- Critical controls
- Critical business processes
- Important systems
- Material third parties
- Prior findings

---

# 120. Coverage Gaps

Material assurance coverage gaps must be documented.

---

# 121. Deferred Assessment

An assessment may be deferred when justified by:

- Operational constraints
- Resource limitations
- Dependency
- Significant competing event
- Safety concern

---

# 122. Deferred Assessment Requirements

A material deferral must identify:

- Assessment
- Reason
- Risk impact
- Interim action
- Revised date
- Approval

---

# 123. Assessment Cancellation

A planned assessment must not be silently removed from the plan.

---

# 124. Plan Change

Material changes to the annual assurance schedule must be documented.

---

# 125. Resource Planning

The CIO must consider whether sufficient:

- Personnel
- Expertise
- Time
- Tools
- Budget

exist to execute the assurance plan.

---

# 126. External Expertise

External expertise may be used when Dunder Mifflin lacks sufficient:

- Independence
- Technical skill
- Specialized testing capability
- Investigation capability

---

# 127. Penetration Testing Independence

Penetration testing should be performed by qualified personnel with appropriate independence from the systems and code being tested.

---

# 128. Confidentiality

Outside assessors receiving sensitive information must have an appropriate Non-Disclosure Agreement (NDA) or equivalent enforceable confidentiality obligation before access.

---

# 129. Confidentiality Limitation

An NDA does not establish:

- Technical competence
- Assessment quality
- Independence
- Appropriate scope
- Adequate testing
- Effective remediation
- Successful retesting

---

# 130. Assessor Access

Assessors receive only the access necessary for authorized assessment activity.

---

# 131. Production Safety

Testing against production systems must be planned to avoid unreasonable:

- Outage
- Data corruption
- Business interruption
- Security exposure

---

# 132. Test Authorization

Technical testing must have documented authorization before execution.

---

# 133. Penetration Test Authorization

Penetration testing authorization should define:

- Scope
- Systems
- Time
- Permitted methods
- Restrictions
- Contacts
- Escalation
- Evidence handling

---

# 134. Assessment Evidence

Assessment evidence must be protected according to:

- Information sensitivity
- Technical sensitivity
- Personnel privacy
- Business need

---

# 135. Evidence Handling

Evidence handling follows:

[[PROC-011 Evidence Handling Procedure]]

where applicable.

---

# 136. Evidence Integrity

Assurance evidence must represent actual activity and conditions.

Personnel must not:

- Fabricate assessment evidence.
- Backdate tests.
- Invent samples.
- Conceal failed tests.
- Modify results to produce a favorable conclusion.
- Record an unperformed retest as successful.

---

# 137. Assessment Limitation

Known assessment limitations must be documented.

---

# 138. Examples of Limitations

Limitations may include:

- Incomplete logs
- Unavailable system
- Limited sample
- Vendor restriction
- Testing restriction
- Missing records
- Operational constraint

---

# 139. Unable to Determine

When evidence is insufficient, the assessor may conclude:

**Unable to Determine**

rather than assigning unsupported effectiveness.

---

# 140. Material Limitation

A material assessment limitation may itself require:

- Finding
- Additional testing
- Management escalation
- Risk consideration

---

# 141. Assurance Reporting

Assessment results are reported according to audience.

---

# 142. Executive Reporting

Executive reporting focuses on:

- Enterprise risk
- Material findings
- Significant control failure
- Overdue material remediation
- Required decisions
- Resource requirements

---

# 143. Management Reporting

Management reporting focuses on:

- Control performance
- Accountability
- Findings
- Corrective action
- Due dates
- Exceptions
- Trends

---

# 144. Operational Reporting

Operational reporting focuses on:

- Execution
- Evidence
- Technical results
- Exceptions
- Remediation activity
- Retesting

---

# 145. Reporting Chain

Assurance reporting should support:

**Technical Evidence → Operational Exception → Management Impact → Enterprise Risk → Executive Decision**

---

# 146. Information Security and Risk Committee

The Information Security and Risk Committee (ISRC) reviews material assurance results as appropriate.

---

# 147. ISRC Review

ISRC review may include:

- Material findings
- Control failures
- High or Critical risk implications
- Overdue remediation
- Failed recovery testing
- Significant third-party weakness
- Significant Infinity weakness
- Risk acceptance

---

# 148. Immediate Escalation

Assurance activity identifying an immediate material threat must be escalated without waiting for the normal reporting cycle.

---

# 149. Security Incident Discovery

If assurance activity identifies suspected active compromise, personnel must follow:

- [[PROC-010 Security Event Escalation Procedure]]
- [[PLN-001 Incident Response Plan]]

---

# 150. Safety Priority

Human life and safety take priority over:

- Assessment completion
- Systems
- Operations
- Facilities
- Equipment
- Inventory
- Revenue
- Other assets

---

# 151. Assurance and Continuous Monitoring

Scheduled assessment and continuous monitoring are complementary.

---

# 152. Continuous Monitoring

Continuous monitoring provides risk-appropriate ongoing awareness of:

- Control condition
- Security events
- Exceptions
- Vulnerabilities
- Findings
- Risk indicators

---

# 153. Continuous Monitoring Does Not Mean 24/7 Testing

Continuous monitoring does not require every control to be monitored or tested continuously.

Frequency should reflect:

- Risk
- Business impact
- Control importance
- Available capability

---

# 154. Continuous Monitoring Input

Continuous monitoring may trigger unscheduled assurance when it identifies:

- Material exception
- Significant trend
- Control failure
- Significant vulnerability
- Incident
- Repeated weakness

---

# 155. Annual Planning Cycle

The assurance planning cycle is:

**Review Risk → Review BIA → Review Controls → Review Findings → Review Incidents and Changes → Prioritize Assurance → Build Schedule → Execute Assessments → Track Findings → Validate Corrections → Reassess Risk**

---

# 156. Annual Planning Inputs

The CIO should review:

- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

before finalizing the annual assurance schedule.

---

# 157. Annual Planning Output

The Annual Assurance Plan should provide management with:

- Assessment priorities
- Assessment schedule
- Ownership
- Required independence
- Resource needs
- Expected evidence
- Known dependencies

---

# 158. Assessment Calendar

The following calendar provides a planning framework.

| Period | Planned Assurance Focus |
|---|---|
| Monthly | Vulnerability assessment; findings; corrective actions; relevant metrics |
| Quarterly | Privileged access; backup restore; treatment status; assurance metrics |
| Every 6 Months | Network discovery; rogue wireless assessment |
| Annual | Enterprise risk reassessment; ordinary access; physical access; personnel security; awareness; Incident Response; Business Continuity; Critical recovery; Infinity assessment; Infinity penetration test; transferability; Critical third parties |
| Every 2 Years | Enterprise penetration test; independent enterprise control assessment; Important third parties |
| Event-Driven | Incidents; major changes; failed tests; material findings; material risk changes |

---

# 159. Annual Schedule Assignment

Specific calendar dates may be assigned by the CIO and responsible owners according to:

- Operational schedules
- Business cycles
- Personnel availability
- Vendor availability
- Testing constraints

---

# 160. Scheduling Independence

Assessment dates must not be manipulated solely to avoid periods when a control is likely to fail.

---

# 161. Assessment Work Plan Approval

Material Assessment Work Plans should be reviewed and approved by the appropriate security or management authority before execution.

---

# 162. Work Plan Changes

Material scope or method changes during assessment must be documented.

---

# 163. Emergency Assessment Changes

An assessor may take reasonable protective action when unexpected testing conditions create:

- Safety risk
- Operational risk
- Security risk

Material deviations must be documented afterward.

---

# 164. Finding Ownership

Every material finding requires one accountable owner.

---

# 165. Corrective Action Tracking

Corrective actions are tracked in:

[[REG-004 Finding & Corrective Action Register]]

---

# 166. Validation Independence

Where practical and appropriate to risk, corrective-action validation should be performed by someone other than the person who performed the corrective action.

---

# 167. Assurance Quality Review

The CIO should periodically review completed assessments for:

- Scope quality
- Evidence quality
- Conclusion support
- Finding clarity
- Corrective-action traceability
- Retest quality

---

# 168. Assurance Program Improvement

Weaknesses in the assessment process should be treated as assurance-program improvement opportunities.

---

# 169. Assurance Program Findings

Material weaknesses in the assurance process may themselves become findings.

---

# 170. Program Metrics

The effectiveness of the assurance program should be evaluated using metrics defined in:

[[REG-005 Security Metrics Catalog]]

---

# 171. Historical Integrity

Assessment history must be preserved.

Later improvement must not erase:

- Prior control weakness
- Prior failed testing
- Prior findings
- Prior risk levels
- Prior corrective actions

---

# 172. Documentation Quality

Assessment documentation should allow a qualified reviewer to understand:

1. What was assessed?
2. Why was it assessed?
3. What requirement applied?
4. Which control was evaluated?
5. Which method was used?
6. What evidence was examined?
7. What conclusion was reached?
8. Were findings identified?
9. What corrective action was required?
10. Was remediation validated?
11. Did risk require reassessment?

---

# 173. Assurance Traceability

Assurance must preserve:

**Requirement → Control → Assessment → Evidence → Conclusion → Finding → Corrective Action → Validation → Retest → Risk Reassessment**

---

# 174. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-003 Identity and Access Management Program]]
- [[PRO-004 Vulnerability Management Program]]
- [[PRO-005 Security Operations Program]]
- [[PRO-006 Physical & Personnel Security Program]]
- [[PRO-007 Secure Software Development Lifecycle Program]]
- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[PRO-009 Security Governance Framework]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[RPT-004 Infinity Transferability Review]]
- [[REG-002 Enterprise Risk Register]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[POL-003 Access Control Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-006 Security Awareness & Training Policy]]
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
- [[PROC-008 Security Monitoring Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-013 Manual Processing Procedure]]
- [[PROC-017 Personnel Security Procedure]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-019 Application Security Assessment Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[TMP-001 Assessment Work Plan Template]]
- [[TMP-003 Recovery Test Template]]
- [[RPT-006 Executive Security Summary]]
- [[RPT-007 Management Security Report]]
- [[RPT-008 Operational Security Report & Dashboard]]

---

# 175. Review

This plan must be reviewed:

- At least annually
- Following material enterprise risk change
- Following significant BIA change
- Following major control failure
- Following significant security incident
- Following major organizational or technology change
- When assurance results demonstrate that planned coverage is inadequate

Routine scheduling adjustments do not require CEO approval.

Material changes to assurance scope or governance require approval consistent with the enterprise security governance framework.

---

# 176. Revision History

| Version | Date     | Description                   | Approval |
| ------- | -------- | ----------------------------- | -------- |
| 1.0     | May 2013 | Initial Annual Assurance Plan | CEO      |