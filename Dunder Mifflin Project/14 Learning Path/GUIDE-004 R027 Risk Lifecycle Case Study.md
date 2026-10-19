## Document Control

| Field | Value |
|---|---|
| Document ID | GUIDE-004 |
| Title | R027 Risk Lifecycle Case Study |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | CIO |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Following Material Program Change |

---

# 1. Purpose

This guide demonstrates the complete Governance, Risk, and Compliance lifecycle by following one enterprise risk from business requirement through risk reassessment.

The selected risk is:

**R027 - Backup / Recovery Failure**

R027 is useful as a learning example because it connects:

- Business requirements
- Business Impact Analysis
- Assets and dependencies
- Risk assessment
- Risk treatment
- Policy
- Controls
- Procedures
- Technical implementation
- Evidence
- Security assessment
- Findings
- Corrective action
- Retesting
- Risk reassessment
- Management reporting
- Continuous monitoring

The purpose of this guide is not merely to explain each artifact independently.

The purpose is to demonstrate how the artifacts work together as one security and risk-management system.

---

# 2. Educational Simulation Notice

This guide includes an educational simulation of a recovery test, control deficiency, finding, corrective action, retest, and later risk reassessment.

Those simulated events are included to demonstrate how the GRC lifecycle would operate after the May 2013 baseline.

They are not historical Dunder Mifflin operational evidence.

They must not be interpreted as proof that:

- A recovery test actually occurred
- A recovery failure actually occurred
- Corrective action was actually completed
- A successful retest actually occurred
- R027 was actually reassessed after May 2013

The May 2013 enterprise risk assessment remains the authoritative historical baseline.

This distinction supports the repository principles of:

- Historical integrity
- No manufactured evidence
- No premature risk credit

---

# 3. The Complete R027 Lifecycle

The lifecycle demonstrated in this case study is:

**Business Requirement**

↓

**Business Process**

↓

**Business Impact Analysis**

↓

**Assets and Dependencies**

↓

**Risk Identification**

↓

**Inherent Risk**

↓

**Existing Controls**

↓

**Current Residual Risk**

↓

**Risk Treatment**

↓

**Policy and Control Requirements**

↓

**Procedure**

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

**Retest**

↓

**Control Effectiveness**

↓

**Risk Reassessment**

↓

**Management Reporting**

↓

**Continuous Monitoring**

This is the same basic lifecycle used throughout the Dunder Mifflin Enterprise Information Security and Risk Management Program.

---

# 4. Stage 1: Begin With the Business

GRC should not begin with a backup product.

It should begin with a business requirement.

Dunder Mifflin depends on information systems to support important business processes including:

- Customer order processing
- Warehouse operations
- Inventory management
- Sales
- Financial processing
- Payroll
- Communications
- Management activities

If supporting information or systems become unavailable or corrupted, the business may be unable to perform required operations.

The first question is not:

> What backup system should Dunder Mifflin purchase?

The first question is:

> What business operations must Dunder Mifflin be capable of recovering, and how quickly must they be recovered?

That distinction is fundamental to risk-based security.

---

# 5. Stage 2: Identify the Business Requirement

The business requirement can be expressed simply:

> Dunder Mifflin must be capable of restoring important business information and technology services within recovery requirements established by the business.

The requirement exists because prolonged loss of systems or data may affect:

- Revenue
- Customer service
- Warehouse operations
- Financial processing
- Employee productivity
- Management operations
- Contractual obligations
- Reputation

Technology recovery exists to support these business requirements.

---

# 6. Stage 3: Determine Business Impact

Before selecting recovery controls, Dunder Mifflin performs Business Impact Analysis.

See:

[[RPT-002 Business Impact Analysis]]

The Business Impact Analysis determines the effect of disruption and establishes recovery requirements.

Important concepts include:

### Maximum Tolerable Downtime

The longest disruption the business can tolerate before the resulting impact becomes unacceptable.

### Recovery Time Objective

The target amount of time within which a process or supporting capability should be restored.

### Recovery Point Objective

The maximum acceptable amount of data loss measured in time.

These requirements are business requirements rather than arbitrary technical settings.

---

# 7. Recovery Requirements Drive Technical Requirements

The proper sequence is:

**Business Need → Criticality → MTD → RTO / RPO → Recovery Strategy → Technical Design → Implementation → Testing**

This prevents a common mistake:

> Purchase backup technology first and decide later what recovery capability it provides.

A risk-based program works in the opposite direction.

The business establishes what it needs.

Technology is then designed to satisfy that need.

---

# 8. Stage 4: Identify Assets and Dependencies

Recovery does not apply only to individual servers.

A business process may depend on multiple assets and services.

Examples include:

- Applications
- Databases
- Identity services
- Network infrastructure
- Internet connectivity
- Cloud services
- Backup systems
- Encryption keys
- Administrative credentials
- Configuration information
- Recovery documentation
- Employees
- Contractors
- Third-party providers

Asset information is maintained through:

[[REG-001 Enterprise Asset Register]]

A recovery strategy that protects only one component may fail if another required dependency is unavailable.

---

# 9. Dependency Example

Assume a business application has a valid backup.

That does not automatically mean the application can be recovered.

Recovery may also require:

- Database restoration
- Operating-system configuration
- Network configuration
- Authentication services
- Administrative credentials
- Encryption keys
- Application configuration
- Documentation
- Personnel with recovery knowledge

This creates an important distinction:

**Backup success is not the same as recovery success.**

A backup may exist while the business remains unable to restore the required service within its recovery objective.

---

# 10. Stage 5: Identify the Risk

The enterprise risk assessment identifies:

**R027 - Backup / Recovery Failure**

See:

- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]

The risk addresses the possibility that Dunder Mifflin may be unable to recover required information, systems, or business capabilities following a disruptive event.

Potential causes include:

- Missing backups
- Failed backups
- Corrupted backups
- Incomplete backup coverage
- Backup compromise
- Missing credentials
- Missing documentation
- Configuration problems
- Dependency failure
- Human error
- Inadequate recovery testing
- Excessive recovery time
- Excessive data loss

---

# 11. Risk Is Not the Same as a Finding

R027 is an enterprise risk.

It is not a finding.

The risk describes what could adversely affect the organization.

For example:

> Dunder Mifflin may be unable to recover Critical systems within required recovery objectives.

A finding describes a specific observed deficiency.

For example:

> Recovery testing demonstrated that a Critical system could not be restored within its required RTO.

The finding provides evidence concerning the broader risk.

This distinction is important.

**Risk = What could go wrong**

**Finding = What was actually observed to be deficient**

---

# 12. Stage 6: Determine Inherent Risk

R027 has an inherent risk score of:

**20 Critical**

Inherent risk represents the risk before considering the effect of existing controls.

The risk model is:

**Likelihood × Impact = Risk Score**

The Critical inherent rating communicates that backup and recovery failure could have a significant effect on Dunder Mifflin if appropriate controls did not exist.

Inherent risk remains useful even after controls are implemented because it demonstrates the underlying importance of the risk.

---

# 13. Why Inherent Risk Still Matters

Suppose strong recovery controls eventually reduce R027 substantially.

That does not mean the underlying business dependency disappeared.

The organization may still depend heavily on:

- Business information
- Applications
- Infrastructure
- Recovery capability

The lower risk exists because controls reduce exposure.

Removing those controls could cause risk to increase again.

Inherent risk helps management understand:

> How serious would this risk be without the controls on which we depend?

---

# 14. Stage 7: Identify Existing Controls

At the May 2013 baseline, R027 includes existing controls such as:

- Automated backups
- Cloud-based backup capability
- Encrypted external backup drives
- Off-site backup rotation
- Multiple recent backup generations
- Existing recovery documentation

These controls reduce exposure compared with having no recovery capability.

However, the existence of backups alone does not establish that recovery objectives can actually be achieved.

---

# 15. Stage 8: Evaluate Control Effectiveness

At the May 2013 baseline, control effectiveness for R027 is:

**Partially Effective**

This is an important GRC concept.

A control can:

- Exist
- Perform some useful function
- Reduce risk

while still not provide sufficient assurance.

For example, Dunder Mifflin may successfully create backups but lack enough evidence that Critical systems can consistently be restored within required RTO and RPO values.

---

# 16. Stage 9: Determine Current Residual Risk

After considering controls actually operating at the time of assessment, R027 has a current residual risk of:

**12 High**

This is the May 2013 current residual risk.

The sequence is:

**20 Critical Inherent Risk**

↓

**Existing Controls**

↓

**12 High Current Residual Risk**

The existing controls reduce risk.

They do not reduce it sufficiently.

Additional treatment is required.

---

# 17. Stage 10: Make the Risk Treatment Decision

The selected treatment for R027 is:

**Mitigate**

The organization intends to reduce the likelihood or impact of recovery failure through additional controls and improvements.

Risk treatment is maintained in:

[[RTP-001 Enterprise Risk Treatment Plan]]

The target residual risk is:

**5 Moderate**

This creates the intended progression:

**20 Critical Inherent**

↓

**12 High Current Residual**

↓

**Additional Treatment**

↓

**5 Moderate Target Residual**

The final value is a target.

It is not automatically achieved because management approved the treatment plan.

---

# 18. Stage 11: Define the Treatment

Treatment for R027 includes capabilities such as:

- Backup monitoring
- Backup coverage validation
- Encrypted external-drive rotation
- Off-site separation
- Quarterly representative restore testing
- Annual meaningful Critical recovery testing
- Independent recovery documentation
- Protected backup administration
- Recovery credential availability
- Failed-test remediation
- Retesting
- Evaluation of backup resilience against production compromise

The purpose is not simply to create more backups.

The purpose is to establish trustworthy recovery capability.

---

# 19. Stage 12: Establish Governance

Risk treatment must be supported by governance.

Relevant governance includes:

[[POL-010 Business Continuity & Disaster Recovery Policy]]

Policy establishes management expectations.

It answers questions such as:

- What must be protected?
- What recovery capability is required?
- Who is accountable?
- What testing is required?
- What happens when recovery requirements are not met?

Policy provides authority for more detailed controls and procedures.

---

# 20. Policy Is Not Implementation

The existence of a policy does not prove that recovery capability exists.

A policy can require:

> Critical recovery capability must be tested.

That requirement still must be:

- Implemented
- Performed
- Documented
- Evaluated

This creates the distinction:

**Policy says what must happen.**

**Procedure explains how it happens.**

**Evidence demonstrates what actually happened.**

**Assessment determines whether it worked.**

---

# 21. Stage 13: Establish the Recovery Procedure

Operational recovery requirements are supported by:

[[PROC-012 Backup & Recovery Procedure]]

The procedure establishes repeatable activities for areas such as:

- Backup administration
- Backup monitoring
- Backup coverage
- Media protection
- Off-site storage
- Restoration
- Recovery testing
- Documentation
- Recovery validation
- Findings
- Corrective action
- Retesting

The procedure converts governance requirements into repeatable operational activities.

---

# 22. Stage 14: Implement the Controls

Controls now have to become real operating capabilities.

Examples may include:

- Configuring automated backups
- Monitoring backup jobs
- Maintaining encrypted external backups
- Rotating backups off-site
- Protecting backup administration
- Maintaining recovery credentials
- Maintaining recovery documentation
- Performing representative restore tests
- Performing Critical recovery tests

This is implementation.

Implementation is not the same as effectiveness.

---

# 23. Four Different Conditions

Consider the statement:

> Dunder Mifflin will perform quarterly restore testing.

That statement may represent several different conditions.

### Planned

The organization intends to perform quarterly restore testing.

### Implemented

The process and capability required to perform testing exist.

### Operating

Required tests are actually being performed.

### Effective

Evidence demonstrates that the tests and recovery capability satisfy the intended requirements.

These conditions must not be confused.

---

# 24. Stage 15: Collect Evidence

Once controls operate, they should produce evidence.

Relevant R027 evidence may include:

- Backup-job records
- Backup coverage records
- Media rotation records
- Off-site custody records
- Restore-test records
- Recovery-test results
- RTO measurements
- RPO measurements
- Recovery documentation
- Administrative-access records
- Exception records
- Corrective-action records
- Retest results

Evidence allows the organization to move from:

> We believe recovery works.

to:

> Here is the evidence showing how recovery performed.

---

# 25. Evidence Is Not the Same as a Control

A control performs a security or risk-management function.

Evidence demonstrates something about that function.

Example:

**Control**

Quarterly representative restore testing.

**Evidence**

A restore-test record showing:

- Date
- System
- Backup selected
- Personnel
- Start time
- Completion time
- Result
- Exceptions

The evidence does not perform the control.

It proves or helps demonstrate that the control operated.

---

# 26. Stage 16: Assess the Control

Security assurance evaluates whether required controls operate as intended.

Relevant assurance activities may include:

- Inspection
- Observation
- Interviews
- Sampling
- Technical testing
- Reconciliation
- Independent performance

The assessor should not merely ask:

> Do you have backups?

The assessor should determine:

> Can required systems actually be recovered within the business requirements established by the BIA?

---

# 27. Recovery Assessment

For a Critical system, an assessor may:

1. Identify the applicable business process.
2. Identify the BIA recovery requirements.
3. Identify required assets and dependencies.
4. Review the recovery procedure.
5. Select an appropriate recovery source.
6. Perform or observe authorized restoration.
7. Measure recovery time.
8. Determine the recovery point.
9. Validate the restored capability.
10. Compare actual results with required RTO and RPO.

This connects business requirements directly to technical evidence.

---

# 28. Simulated Assessment Scenario

The remainder of this section is an educational simulation.

Assume a Critical process has:

- **RTO: 8 hours**
- **RPO: 4 hours**

Dunder Mifflin performs a controlled recovery test.

The simulated results are:

- Recovery time: **11 hours 37 minutes**
- Data loss: **58 minutes**

Comparison with the business requirements produces:

| Requirement | Target | Actual | Result |
|---|---:|---:|---|
| RTO | 8 hours | 11 hours 37 minutes | Fail |
| RPO | 4 hours | 58 minutes | Pass |

The backup existed.

The data could be restored.

The RPO requirement was satisfied.

The RTO requirement was not satisfied.

---

# 29. Why the Test Failed

A recovery capability should not be judged only by whether data eventually came back.

The business requirement was:

**Recovery within 8 hours.**

Actual recovery required:

**11 hours 37 minutes.**

The difference is:

**3 hours 37 minutes beyond the required RTO.**

The recovery capability did not completely satisfy the business requirement.

This is a control deficiency.

---

# 30. Stage 17: Create a Finding

A material deficiency should be documented as a finding.

For the simulated scenario:

### Simulated Finding

**Condition**

A Critical system required 11 hours 37 minutes to recover during controlled recovery testing.

**Requirement**

The applicable BIA requires recovery within 8 hours.

**Result**

The recovery exceeded the required RTO by 3 hours 37 minutes.

**Risk Relationship**

R027 - Backup / Recovery Failure

This finding does not replace R027.

It provides evidence concerning R027.

---

# 31. Finding Versus Risk

This distinction can be shown as:

### Risk

**R027 - Backup / Recovery Failure**

> The organization may be unable to recover required systems or information within business requirements.

### Finding

> A tested Critical system required 11 hours 37 minutes to recover against an 8-hour RTO.

The risk is broader.

The finding is specific.

A single risk may have multiple findings.

A finding may also affect more than one risk.

---

# 32. Stage 18: Record Corrective Action

Material findings requiring remediation are tracked through:

[[REG-004 Finding & Corrective Action Register]]

Corrective action should identify:

- Deficiency
- Affected system or process
- Accountable owner
- Required action
- Due date
- Required evidence
- Validation method
- Retest requirement

The finding should remain visible until appropriate validation demonstrates that the deficiency has been corrected.

---

# 33. Simulated Root-Cause Analysis

Assume investigation of the simulated recovery failure identifies several contributing conditions:

- Recovery documentation was incomplete.
- Configuration information required additional manual reconstruction.
- Recovery sequencing was inefficient.
- Responsibilities during restoration were not sufficiently clear.

The corrective action should address these causes rather than merely instructing personnel to:

> Recover faster next time.

Corrective action should address the reason the control failed.

---

# 34. Simulated Corrective Action

Assume Dunder Mifflin takes the following actions:

1. Improves recovery documentation.
2. Corrects configuration problems.
3. Documents required dependencies.
4. Improves recovery sequencing.
5. Clarifies personnel responsibilities.
6. Verifies availability of required recovery credentials.
7. Updates the applicable recovery procedure.
8. Schedules a controlled retest.

The finding status may progress through:

**Open → In Progress → Validation Pending**

It should not move to Closed merely because someone reports:

> Fixed.

---

# 35. Remediation Is Not Closure

This is one of the most important concepts in the case study.

A technician may complete the assigned work.

That establishes:

**Remediation reported complete**

It does not automatically establish:

**Deficiency corrected**

Validation is still required.

The organization must determine whether the corrective action actually produced the intended result.

---

# 36. Stage 19: Retest

The original deficiency involved failure to satisfy the RTO.

The retest should evaluate that same condition.

Assume a second controlled recovery test produces the following simulated results:

- Recovery time: **6 hours 42 minutes**
- Data loss: **47 minutes**

Comparison produces:

| Requirement | Target | Retest Actual | Result |
|---|---:|---:|---|
| RTO | 8 hours | 6 hours 42 minutes | Pass |
| RPO | 4 hours | 47 minutes | Pass |

Both recovery requirements are now satisfied.

Again, these values are educational examples and are not actual Dunder Mifflin operational evidence.

---

# 37. What the Retest Demonstrates

The retest provides evidence that:

- The corrective actions were implemented.
- Recovery performance improved.
- The previously failed RTO was satisfied during the retest.
- The RPO remained satisfied.
- The original deficiency may now be eligible for closure following appropriate review.

The sequence is:

**Finding**

↓

**Corrective Action**

↓

**Implementation**

↓

**Retest**

↓

**Validated Result**

This is stronger than simply documenting that corrective action was completed.

---

# 38. Preserve the Failed Test

The original failed test must not be deleted or rewritten.

The record should preserve:

1. Original requirement
2. Original failed test
3. Finding
4. Root-cause analysis
5. Corrective action
6. Retest
7. Successful result
8. Later risk reassessment

This creates a defensible assurance history.

A mature program does not pretend that controls never fail.

A mature program demonstrates that failures are identified, corrected, validated, and incorporated into risk management.

---

# 39. Stage 20: Reevaluate Control Effectiveness

The May 2013 R027 control-effectiveness assessment is:

**Partially Effective**

The simulated later evidence provides information that could support a new effectiveness assessment.

Relevant evidence may include:

- Backup success
- Backup coverage
- Restore success
- RTO performance
- RPO performance
- Recovery documentation
- Administrative security
- Repeated test results
- Corrective-action results

One successful retest should be interpreted in context.

The organization should determine whether the evidence is sufficient to conclude that recovery controls are operating reliably.

---

# 40. Stage 21: Reassess Risk

Validated evidence may justify reassessment of R027.

The original historical values remain:

### May 2013 Baseline

- Inherent Risk: **20 Critical**
- Current Residual Risk: **12 High**
- Treatment: **Mitigate**
- Target Residual Risk: **5 Moderate**

These values should not be overwritten merely because later conditions improve.

Instead, a later assessment should be recorded separately.

---

# 41. Target Risk Is Not Automatically Achieved

The target residual risk of:

**5 Moderate**

is a prediction.

It represents the expected risk after planned treatment is implemented and validated.

The actual post-treatment risk could be:

- Higher than 5
- Equal to 5
- Lower than 5

Evidence determines the result.

The organization must not simply change:

**12 High**

to:

**5 Moderate**

because the treatment plan was completed.

---

# 42. Simulated Risk Reassessment

Assume sufficient later evidence demonstrates:

- Required backup coverage is operating.
- Backup jobs are monitored.
- Off-site backup separation is maintained.
- Required restore tests are being completed.
- Critical recovery testing is occurring.
- RTO and RPO requirements are being met.
- Recovery documentation is maintained.
- Corrective actions are validated.
- No material unresolved recovery deficiencies remain.

Management could then reassess R027.

For educational purposes, assume the later assessment determines:

**Residual Risk: 5 Moderate**

This would match the original target.

This simulated value does not replace the May 2013 baseline.

The historical record would instead show:

**May 2013 Current Residual Risk: 12 High**

↓

**Treatment**

↓

**Implementation**

↓

**Assessment**

↓

**Finding**

↓

**Corrective Action**

↓

**Successful Retest**

↓

**Later Reassessment: 5 Moderate**

That history demonstrates how risk reduction occurred.

---

# 43. Why Risk Cannot Be Reduced Early

Suppose Dunder Mifflin approves all planned recovery improvements but has not yet tested them.

The current residual risk should not automatically decrease.

Management knows:

> The organization intends to improve recovery.

Management does not yet know:

> The improved recovery capability works.

This is the principle of:

**No Premature Risk Credit**

Risk reduction requires appropriate evidence.

---

# 44. Stage 22: Management Reporting

The R027 lifecycle produces information for different audiences.

### Operational Personnel

Need details such as:

- Backup failures
- Restore failures
- Recovery times
- Configuration issues
- Required corrective actions

### Management

Needs information such as:

- Whether required testing occurred
- Whether RTO and RPO were met
- Whether corrective actions are overdue
- Whether recovery capability is improving
- Whether significant deficiencies remain

### Executive Leadership

Needs information such as:

- Current enterprise risk
- Material recovery weaknesses
- Business exposure
- Required resources
- Significant overdue remediation
- Risk acceptance decisions
- Strategic recovery capability

The same underlying evidence is communicated differently depending on the audience.

---

# 45. Stage 23: Monitor the Risk

A successful recovery test does not permanently solve R027.

Technology changes.

People change.

Applications change.

Dependencies change.

Backup jobs fail.

Credentials change.

Documentation becomes outdated.

New systems are introduced.

For that reason, recovery capability requires continuing monitoring and periodic testing.

---

# 46. Relevant Metrics

R027 monitoring may use metrics such as:

- Percentage of required quarterly restore tests completed
- Restore success rate
- Percentage of Critical systems receiving annual recovery testing
- RTO pass rate
- RPO pass rate
- Failed recovery attempts
- Open recovery findings
- Overdue corrective actions
- Recovery tests requiring retest
- Recovery-documentation deficiencies

Metric definitions are maintained in:

[[REG-005 Security Metrics Catalog]]

---

# 47. Key Performance Indicators

Possible R027 Key Performance Indicators include:

- Percentage of required quarterly restore tests completed
- Percentage of Critical systems receiving annual recovery testing
- Percentage of Critical recovery tests meeting RTO
- Percentage of Critical recovery tests meeting RPO
- Percentage of recovery corrective actions completed and validated

KPIs help management evaluate whether required recovery activities are being performed successfully.

---

# 48. Key Risk Indicators

Possible R027 Key Risk Indicators include:

- Failed Critical recovery test
- Repeated RTO failure
- Repeated RPO failure
- Unrecoverable backup
- Unknown backup coverage
- Significant undocumented dependency
- Single-person recovery dependency
- Critical recovery finding overdue
- Provider recovery weakness

KRIs help management identify conditions that may indicate increasing exposure.

---

# 49. Metrics Require Interpretation

A metric should not be interpreted without context.

Suppose the number of failed recovery tests increases.

That could mean:

- Recovery capability is deteriorating.

It could also mean:

- Testing became more realistic.
- More systems were tested.
- Test scope expanded.
- The organization became better at identifying weaknesses.

A metric provides information.

Management still has to interpret what the information means.

---

# 50. The Complete R027 Traceability Chain

R027 can now be traced through the security program.

### Business Requirement

Maintain business operations and recover required capabilities following disruption.

↓

### Business Impact Analysis

[[RPT-002 Business Impact Analysis]]

Establishes recovery requirements including RTO and RPO.

↓

### Assets and Dependencies

[[REG-001 Enterprise Asset Register]]

Identifies systems, information, infrastructure, people, and services required for recovery.

↓

### Risk

[[REG-002 Enterprise Risk Register]]

**R027 - Backup / Recovery Failure**

↓

### Risk Assessment

[[RPT-003 Enterprise Risk Assessment]]

- Inherent: 20 Critical
- Current Residual: 12 High

↓

### Treatment

[[RTP-001 Enterprise Risk Treatment Plan]]

**Mitigate**

Target residual risk:

**5 Moderate**

↓

### Governance

[[POL-010 Business Continuity & Disaster Recovery Policy]]

↓

### Procedure

[[PROC-012 Backup & Recovery Procedure]]

↓

### Implementation

Backup, recovery, documentation, administrative protection, monitoring, and testing capabilities.

↓

### Evidence

Backup records, restore records, recovery-test results, RTO/RPO measurements, and related evidence.

↓

### Assessment

Compare actual recovery performance against established business requirements.

↓

### Finding

Document material failure to satisfy required recovery performance.

↓

### Corrective Action

[[REG-004 Finding & Corrective Action Register]]

↓

### Retest

Repeat the applicable recovery test after remediation.

↓

### Validation

Determine whether the original deficiency has actually been corrected.

↓

### Risk Reassessment

Determine whether validated evidence supports a new current residual risk.

↓

### Reporting

Communicate operational, management, and executive implications.

↓

### Continuous Monitoring

Continue measuring and testing recovery capability.

---

# 51. Four Concepts That Must Remain Separate

The R027 example demonstrates four concepts that are frequently confused.

## Risk

What could go wrong?

Example:

**R027 - Backup / Recovery Failure**

---

## Control

What reduces the risk?

Example:

**Quarterly representative restore testing**

---

## Evidence

What demonstrates that the control operated?

Example:

**Restore-test record and measured recovery results**

---

## Finding

What deficiency was observed?

Example:

**Critical recovery exceeded its required RTO**

These concepts interact, but they are not interchangeable.

---

# 52. Risk Does Not Disappear When a Finding Closes

Assume the simulated finding is successfully corrected and closed.

R027 still exists.

Dunder Mifflin still depends on recovery capability.

The closed finding means:

> A particular identified deficiency was corrected.

It does not mean:

> Backup and recovery failure is no longer an enterprise risk.

Risk management continues after individual findings are closed.

---

# 53. Controls Do Not Eliminate All Risk

Even strong backup and recovery controls cannot guarantee perfect recovery under every possible condition.

Examples include:

- Regional disasters
- Simultaneous system failures
- Provider outages
- Credential loss
- Sophisticated ransomware
- Human error
- Previously unknown dependencies
- Corruption that propagates into backups

Risk management seeks reasonable and defensible reduction of risk.

It does not require pretending that uncertainty can be eliminated.

---

# 54. R027 Also Supports Other Risks

Backup and recovery capability affects more than R027.

It may also support treatment or response for risks including:

- R003 Ransomware
- R004 Malware
- R013 Administrative / Configuration Error
- R016 Cloud Outage
- R026 Loss of Key Personnel
- R028 Data Corruption
- R033 Manual Outage Processing Error
- R034 Loss of Headquarters
- R035 Regional Disaster

This demonstrates why enterprise controls frequently support multiple risks.

---

# 55. Example: R003 Ransomware Relationship

Ransomware may encrypt or destroy production information.

Backup and recovery controls can reduce the operational impact by providing a recovery mechanism.

However:

**Backup does not prevent ransomware.**

Ransomware treatment also requires controls such as:

- Endpoint protection
- Authentication protection
- Least privilege
- Vulnerability management
- Monitoring
- Incident response
- Security awareness

This illustrates defense in depth.

---

# 56. Example: R028 Data Corruption Relationship

Validated backups can provide a trustworthy recovery source when production information becomes corrupted.

However, recovery also depends on determining:

- When corruption occurred
- Which recovery point is trustworthy
- Whether restored information is complete
- Whether business reconciliation is required

Again:

**Having a backup is not the same as having proven recovery capability.**

---

# 57. Accountability Throughout the Lifecycle

Different roles have different responsibilities.

### Business Owners

Define business requirements and acceptable impact.

### CIO

Owns R027 and provides technology and security leadership.

### IT and Security Personnel

Implement, operate, monitor, and maintain recovery controls.

### Assessors

Evaluate evidence and control effectiveness.

### Finding Owners

Complete assigned corrective actions.

### Management

Reviews material deficiencies and risk.

### Executive Leadership

Makes decisions involving significant risk, funding, resources, and acceptance.

GRC connects these responsibilities.

---

# 58. The GRC Analyst's Role

A GRC analyst does not need to personally configure every backup system.

The analyst should be able to determine:

- What business requirement exists?
- What risk threatens it?
- Who owns the risk?
- What is the inherent risk?
- What controls currently exist?
- What is the current residual risk?
- What treatment was selected?
- What requirements govern the treatment?
- What evidence should exist?
- Was the control tested?
- What did the test demonstrate?
- Was a finding required?
- Who owns remediation?
- Was remediation validated?
- Was the control retested?
- Should the risk be reassessed?
- What does management need to know?

That is the practical GRC lifecycle.

---

# 59. What the GRC Analyst Should Not Do

The analyst should not assume:

> The policy exists, so the control works.

The analyst should not assume:

> The backup job succeeded, so recovery will succeed.

The analyst should not assume:

> The technician said the issue was fixed, so the finding can close.

The analyst should not assume:

> The treatment plan was completed, so residual risk equals the target.

Each conclusion requires appropriate evidence.

---

# 60. Questions a GRC Analyst Should Ask

For R027, useful questions include:

### Business

- Which processes require recovery?
- How long can they remain unavailable?
- How much data loss is acceptable?

### Assets

- Which systems support those processes?
- What dependencies exist?

### Risk

- What could prevent successful recovery?
- What would the business impact be?

### Controls

- What backup and recovery controls currently exist?
- Who owns them?
- How frequently do they operate?

### Evidence

- What records demonstrate that the controls operated?

### Assessment

- Were required tests performed?
- Did recovery satisfy RTO?
- Did recovery satisfy RPO?

### Findings

- Were deficiencies documented?
- Were accountable owners assigned?

### Remediation

- Was the root cause addressed?
- Was corrective action validated?

### Risk

- Does the new evidence justify reassessment?

These questions connect technical activity to governance and business risk.

---

# 61. Common Mistake: Starting With Technology

A weak approach begins with:

> We need a better backup product.

A stronger GRC approach begins with:

> What recovery capability does the business require, and what evidence demonstrates whether the current capability satisfies that requirement?

The second question may eventually lead to new technology.

It may also identify problems involving:

- Process
- Documentation
- Training
- Dependencies
- Credentials
- Configuration
- Staffing
- Testing

Technology is only one part of the solution.

---

# 62. Common Mistake: Treating Backup Success as Recovery Success

A backup job showing:

**Success**

proves something useful.

It demonstrates that the backup process reported successful completion.

It does not independently prove:

- The backup is complete.
- The backup is uncorrupted.
- Required information can be restored.
- Required dependencies are available.
- The application will function after restoration.
- Recovery will meet RTO.
- Recovery will meet RPO.

Restore and recovery testing provide additional assurance.

---

# 63. Common Mistake: Closing Findings Too Early

The sequence should not be:

**Finding → Technician says fixed → Closed**

The stronger sequence is:

**Finding → Corrective Action → Implementation → Evidence → Validation / Retest → Closure**

This protects the integrity of the assurance process.

---

# 64. Common Mistake: Rewriting History

Suppose later controls successfully reduce R027.

Do not rewrite the May 2013 assessment to show:

**5 Moderate**

as though that were always the condition.

Preserve:

**May 2013: 12 High**

Then document the later evidence and reassessment.

The improvement becomes more credible because the repository shows how it occurred.

---

# 65. Common Mistake: Confusing Target and Current Risk

Current residual risk answers:

> What risk remains based on controls actually operating now?

Target residual risk answers:

> What risk do we expect after planned treatment succeeds?

For R027:

**Current Residual Risk: 12 High**

**Target Residual Risk: 5 Moderate**

Until treatment is implemented and appropriately validated, the target must not be presented as the current condition.

---

# 66. The Assurance Loop

The R027 case study demonstrates the assurance loop:

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

**Retest**

↓

**Control Effectiveness**

Risk management then extends the loop:

**Control Effectiveness**

↓

**Risk Reassessment**

This is how security operations and GRC connect.

---

# 67. The Improvement Loop

The broader improvement cycle is:

**Assess**

↓

**Identify**

↓

**Prioritize**

↓

**Treat**

↓

**Implement**

↓

**Validate**

↓

**Measure**

↓

**Improve**

R027 never becomes a static document entry.

It remains part of an ongoing management process.

---

# 68. Why This Case Study Matters

The individual artifacts in a GRC program can appear disconnected when viewed separately.

A risk register may look like a spreadsheet.

A policy may look like administrative paperwork.

A procedure may look operational.

A backup log may look technical.

An assessment may look like an audit activity.

A finding may look like a problem ticket.

A management report may look like a summary.

The R027 lifecycle demonstrates that these are connected.

Each answers a different question.

---

# 69. The Questions Answered by Each Layer

| Layer | Question |
|---|---|
| Business | What must the organization accomplish? |
| BIA | How much disruption can the business tolerate? |
| Asset Management | What does the business depend on? |
| Risk Assessment | What could prevent the business from meeting its objectives? |
| Risk Register | Which risks require ongoing management? |
| Risk Treatment | What will the organization do about the risk? |
| Policy | What does management require? |
| Procedure | How will the requirement be carried out? |
| Implementation | What capability actually exists? |
| Evidence | What proves what happened? |
| Assessment | Did the control work as required? |
| Finding | What deficiency was identified? |
| Corrective Action | What must be fixed? |
| Retest | Did the correction work? |
| Risk Reassessment | What risk remains now? |
| Reporting | What does management need to know? |
| Monitoring | Is the condition changing over time? |

Together, these layers form the GRC lifecycle.

---

# 70. Final Case Study Summary

R027 begins with a business dependency.

Dunder Mifflin depends on information and technology to perform important business operations.

The BIA establishes how quickly those operations must recover and how much data loss can be tolerated.

The enterprise risk assessment identifies the possibility that backup and recovery capability may fail to satisfy those requirements.

That produces:

**R027 - Backup / Recovery Failure**

The May 2013 baseline evaluates the risk as:

- **Inherent Risk: 20 Critical**
- **Control Effectiveness: Partially Effective**
- **Current Residual Risk: 12 High**
- **Treatment: Mitigate**
- **Target Residual Risk: 5 Moderate**

Existing controls reduce the risk but do not provide sufficient assurance.

Additional treatment is planned.

Governance establishes requirements.

Procedures establish repeatable activities.

Technical personnel implement and operate the controls.

Those activities produce evidence.

Assessors evaluate the evidence.

A deficiency may produce a finding.

The finding receives corrective action.

Corrective action is validated through retesting.

Validated evidence may justify a new assessment of control effectiveness.

That evidence may then justify reassessment of residual risk.

Management receives the resulting information.

Monitoring continues.

The complete lesson is:

> **GRC is not a collection of documents. It is the traceable process of connecting business requirements to risk, controls, evidence, assurance, decisions, and improvement.**

---

# 71. Related Artifacts

## Enterprise Context

- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[REG-001 Enterprise Asset Register]]
- [[RPT-002 Business Impact Analysis]]

## Risk Management

- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]

## Governance

- [[POL-005 Risk Management Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]

## Business Continuity and Disaster Recovery

- [[PROC-012 Backup & Recovery Procedure]]
- [[PLN-003 Business Continuity Plan]]
- [[PLN-004 Disaster Recovery Plan]]

## Assurance and Improvement

- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

## Repository Reference

- [[INDEX-001 Artifact Index]]
- [[REG-006 Document Control Register]]
- [[REG-007 Cross-Reference Matrix]]
- [[GUIDE-001 GRC Learning Path]]
- [[GUIDE-002 Project Artifact Map]]
- [[GUIDE-003 Acronym & Terminology Guide]]

---

# 72. Revision History

| Version | Date | Description | Approved By |
|---|---|---|---|
| 1.0 | May 2013 | Initial release | CIO |