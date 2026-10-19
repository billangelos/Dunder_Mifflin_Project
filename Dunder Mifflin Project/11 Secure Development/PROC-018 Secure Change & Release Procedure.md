# PROC-018 Secure Change & Release Procedure

## Document Control

| Field | Value |
|---|---|
| Document ID | PROC-018 |
| Title | Secure Change & Release Procedure |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Development, Change Management, Release, or Application Security Change |

---

# 1. Purpose

This procedure establishes the controlled process for developing, reviewing, testing, approving, deploying, validating, and documenting application changes.

The procedure is intended to reduce the risk that application changes introduce:

- Security vulnerabilities
- Unauthorized functionality
- Configuration errors
- Data corruption
- Availability failures
- Recovery problems
- Undocumented dependencies
- Uncontrolled production changes

---

# 2. Scope

This procedure applies to:

- Infinity
- Internally developed applications
- Application source code
- Application configuration
- Database changes
- Application interfaces
- Security-sensitive application changes
- Application releases
- Emergency application changes
- Contractor-developed changes

---

# 3. Authority

This procedure operates under:

- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[PRO-007 Secure Software Development Lifecycle Program]]
- [[STD-009 Infinity Security Standard]]

---

# 4. Supporting Standards

Application changes must comply with applicable requirements in:

- [[STD-002 Network Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[STD-009 Infinity Security Standard]]

---

# 5. Change Lifecycle

Application changes follow:

**Request → Classify → Assess → Authorize Development → Develop → Review → Test → Approve Release → Deploy → Verify → Close**

Where a material problem occurs:

**Detect → Stop / Stabilize → Roll Back or Correct → Verify → Document → Review**

---

# 6. Change Principle

A production change must not be made solely because:

- A developer believes it is useful.
- A contractor requests it.
- A user asks informally.
- The change appears small.
- The change is technically possible.

Material production changes require appropriate authorization and control.

---

# 7. Change Categories

Application changes are categorized as:

- Standard
- Normal
- Emergency

---

# 8. Standard Change

A Standard change is:

- Repetitive
- Low risk
- Well understood
- Preauthorized
- Performed using an established procedure

---

# 9. Standard Change Requirements

A Standard change must have:

- Defined scope
- Established procedure
- Known expected result
- Defined authorization
- Appropriate testing
- Documented completion

---

# 10. Standard Change Review

Standard change status must be reconsidered if:

- The change repeatedly fails.
- Risk increases.
- Scope changes materially.
- Security impact increases.
- The procedure no longer reflects actual implementation.

---

# 11. Normal Change

A Normal change requires individual review and approval before production implementation.

---

# 12. Normal Change Examples

Normal changes may include:

- New application functionality
- Significant application modification
- Database schema change
- Authentication change
- Authorization change
- External interface change
- Significant configuration change
- Material infrastructure change supporting the application

---

# 13. Emergency Change

An Emergency change is an expedited change required to address an urgent condition such as:

- Active security exposure
- Significant service outage
- Critical application defect
- Serious data-integrity problem
- Other material operational emergency

---

# 14. Emergency Change Limitation

Emergency classification must not be used merely to:

- Avoid normal review.
- Avoid testing.
- Meet an avoidable deadline.
- Correct poor planning.
- Bypass security requirements.
- Bypass required authorization.

---

# 15. Change Request

A material change request must identify as applicable:

- Change description
- Business purpose
- Requestor
- Affected application
- Affected components
- Expected impact
- Security impact
- Dependencies
- Testing requirements
- Deployment approach
- Rollback approach
- Required approval

---

# 16. Change Identification

Each material change must have sufficient identification to distinguish it from other changes.

---

# 17. Business Purpose

A change must have a legitimate:

- Business
- Operational
- Security
- Maintenance
- Compliance

purpose.

---

# 18. Change Owner

Each material change must have an accountable owner responsible for coordinating the change through completion.

---

# 19. Change Scope

The change scope must identify affected components sufficiently to support:

- Review
- Testing
- Deployment
- Verification
- Rollback
- Documentation

---

# 20. Dependency Identification

Material changes must identify important dependencies where reasonably known.

Dependencies may include:

- Database
- Network
- Server
- Authentication
- External service
- Payment processor
- Other application
- Configuration
- Contractor support

---

# 21. Security Impact Review

Material changes must be evaluated for security impact before production release.

---

# 22. Security-Sensitive Changes

Security-sensitive changes include changes affecting:

- Authentication
- Authorization
- Session management
- Input validation
- Sensitive information
- Database access
- Administrative functionality
- Internet exposure
- External interfaces
- Logging
- Encryption
- Security configuration

---

# 23. Higher-Risk Review

Security-sensitive changes require greater review than ordinary low-risk changes.

---

# 24. Security Impact Questions

The review should consider:

- Does the change create new Internet exposure?
- Does it alter authentication?
- Does it alter authorization?
- Does it affect sensitive information?
- Does it change a trust boundary?
- Does it add an external interface?
- Does it alter administrative privilege?
- Does it affect security logging?
- Does it affect recovery?
- Does it create a new contractor dependency?

---

# 25. Information Classification

Changes involving information must consider applicable classification requirements under:

- [[POL-004 Information Classification & Handling Policy]]
- [[STD-001 Information Classification Standard]]

---

# 26. Threat Modeling

Material security-sensitive Infinity changes must receive lightweight threat modeling appropriate to their scope.

---

# 27. STRIDE

STRIDE may be used to consider:

- Spoofing
- Tampering
- Repudiation
- Information Disclosure
- Denial of Service
- Elevation of Privilege

---

# 28. Threat Modeling Proportionality

A minor low-risk change does not require the same analysis as a change involving:

- Authentication
- Internet exposure
- Sensitive information
- Major architecture
- Administrative functionality

---

# 29. Threat Model Record

For a material change, the threat-model record should identify:

- Scope
- Important assets
- Trust boundaries
- Significant threats
- Planned controls
- Unresolved concerns

---

# 30. Development Authorization

Development work may begin after the change is appropriately authorized for development.

Authorization to develop does not automatically authorize production deployment.

---

# 31. Environment Separation

Development, test, and production environments must remain logically separated.

---

# 32. Development Environment

Routine development must occur outside the production environment.

---

# 33. Test Environment

Changes must be tested outside production before release where practical.

---

# 34. Production Environment

Production is the authoritative live business environment and must receive stronger change control than ordinary development activity.

---

# 35. Direct Production Development

Routine development directly within production is prohibited.

---

# 36. Production Data

Production data must not be copied unnecessarily into development or test environments.

---

# 37. Sensitive Test Data

Sensitive information required for testing must be:

- Minimized
- Appropriately protected
- Removed when no longer required

as applicable.

---

# 38. Source-Code Control

Source-code changes must occur through the controlled repository where applicable.

---

# 39. Source-Code Accountability

A source-code change must be attributable to the authorized individual making the change.

---

# 40. Repository Access

Repository access must be limited to personnel with legitimate:

- Development
- Review
- Support
- Administrative

responsibilities.

---

# 41. Contractor Changes

Contractor-developed changes remain subject to the same Dunder Mifflin change requirements as internally developed changes.

---

# 42. Contractor Authority

The Infinity contractor may not independently authorize its own production change merely because the contractor developed the change.

---

# 43. Contractor Access

Contractor development access must comply with [[PROC-020 Contractor Development Access Procedure]].

---

# 44. Development Requirements

Development must address applicable:

- Business requirements
- Security requirements
- Architecture requirements
- Coding requirements
- Configuration requirements
- Recovery requirements

---

# 45. Secure Coding

Development must use practices intended to reduce vulnerabilities such as:

- Injection
- Improper authorization
- Unsafe input handling
- Sensitive-data exposure
- Insecure error handling
- Credential exposure

---

# 46. Input Validation

Security-sensitive input validation must occur on trusted application components and must not rely solely on client-side validation.

---

# 47. Authorization

Authorization controls must be enforced by trusted application components.

---

# 48. Database Access

Database access must follow the least privilege and secure-development requirements established for Infinity.

---

# 49. Authentication Secrets

Passwords or other authentication secrets must not be unnecessarily hard-coded into application source code.

---

# 50. Logging Changes

Changes affecting security-relevant logging must consider whether sufficient information remains available for:

- Monitoring
- Troubleshooting
- Incident investigation
- Accountability

---

# 51. Error Handling

Changes must not unnecessarily expose sensitive technical information through application errors.

---

# 52. Code Review

Material or security-sensitive code changes must receive qualified review where practical.

---

# 53. Code Reviewer

The reviewer should be someone other than the developer when reasonably practical.

---

# 54. Small-Team Limitation

Where complete Separation of Duties is impractical, compensating review or approval must be used.

---

# 55. Code Review Scope

Review should consider as applicable:

- Intended functionality
- Security requirements
- Authorization
- Authentication
- Input handling
- Database interaction
- Sensitive-data handling
- Error handling
- Logging
- Unintended functionality
- Known insecure patterns

---

# 56. Review Evidence

Review evidence should identify:

- Change reviewed
- Reviewer
- Date
- Material concerns
- Required corrections
- Review result

---

# 57. Review Failure

A material review concern must be resolved or appropriately accepted before production release.

---

# 58. Testing Requirement

Changes must receive testing appropriate to:

- Scope
- Risk
- Security impact
- Business impact

---

# 59. Functional Testing

Functional testing must determine whether the change performs its intended function.

---

# 60. Security Testing

Security-sensitive changes must receive appropriate security testing.

---

# 61. Security Testing Methods

Testing may include:

- Manual review
- Input testing
- Authentication testing
- Authorization testing
- Session testing
- Configuration review
- Vulnerability testing
- Code review
- Penetration testing

depending on the change.

---

# 62. Regression Testing

Material changes should receive reasonable regression testing to determine whether existing important functionality was unintentionally affected.

---

# 63. Database Change Testing

Database changes should be tested for:

- Intended functionality
- Data integrity
- Compatibility
- Rollback or recovery considerations

where applicable.

---

# 64. Interface Testing

Changes affecting external interfaces should be tested for:

- Connectivity
- Authentication
- Authorization
- Input handling
- Error behavior
- Expected data exchange

as applicable.

---

# 65. Security Test Failure

A change that fails a material security test must not be approved solely because functional testing passed.

---

# 66. Defect Correction

Material defects identified during testing must be:

- Documented
- Corrected
- Retested

or otherwise addressed through an approved risk process.

---

# 67. Retest

A corrected defect must be retested when necessary to confirm that the corrective action addressed the original problem.

---

# 68. Test Evidence

Test evidence should identify:

- Change tested
- Test scope
- Tester
- Date
- Test method
- Result
- Defects identified
- Retest result where applicable

---

# 69. Test Evidence Integrity

Test results must reflect actual testing.

Personnel must not:

- Invent successful tests.
- Backdate tests.
- Conceal failed tests.
- Record unperformed tests as complete.

---

# 70. Release Readiness

Before a material production release, responsible personnel must determine whether:

- Required review is complete.
- Required testing is complete.
- Material defects are addressed.
- Required approval exists.
- Deployment steps are understood.
- Rollback is reasonably available.
- Required documentation is current.

---

# 71. Release Package

A material release package should identify:

- Included changes
- Version or release identifier
- Required configuration
- Dependencies
- Database changes
- Deployment steps
- Verification steps
- Rollback approach
- Required approvals

---

# 72. Release Identifier

A material release should have sufficient identification to determine what software or configuration entered production.

---

# 73. Release Approval

Production deployment requires appropriate release approval.

---

# 74. Approval Independence

Where practical, the individual approving a material release should not rely solely on the developer's assertion that the release is ready.

---

# 75. Approval Considerations

Release approval should consider:

- Business need
- Test results
- Security impact
- Open defects
- Rollback capability
- Operational impact
- Required timing

---

# 76. Approval Limitation

Approval does not replace technical testing.

---

# 77. Deployment Authorization

Only authorized personnel may deploy application changes to production.

---

# 78. Deployment Window

Material changes should be scheduled to reduce unnecessary business disruption where practical.

---

# 79. Deployment Preparation

Before deployment, responsible personnel should confirm:

- Required files or packages are available.
- Required configuration is known.
- Required credentials are available.
- Backup or recovery prerequisites are satisfied.
- Rollback steps are understood.
- Responsible personnel are available.

---

# 80. Pre-Change Backup

A material change affecting important application data or configuration must consider whether a pre-change backup or other recovery point is required.

---

# 81. Backup Validation

The existence of a backup must not be assumed solely because a backup job is configured.

Where recovery from the change materially depends on backup availability, responsible personnel should confirm the required recovery source is available.

---

# 82. Production Deployment

The authorized deployment must follow the approved release process.

---

# 83. Deployment Record

The deployment record should identify:

- Release
- Date and time
- Person performing deployment
- Environment
- Result
- Exceptions
- Rollback if required

---

# 84. Deployment Deviation

A material deviation from the approved deployment process must be documented.

---

# 85. Post-Deployment Verification

After deployment, responsible personnel must verify the result.

---

# 86. Verification Scope

Verification should determine as applicable whether:

- Application is available.
- Intended functionality works.
- Required configuration is present.
- Security-sensitive functionality works.
- Database changes succeeded.
- External interfaces function.
- No immediately apparent material error exists.

---

# 87. Security Verification

For a security-sensitive change, post-deployment verification must include the affected security function where practical.

---

# 88. Verification Failure

If post-deployment verification fails, responsible personnel must determine whether to:

- Correct the problem
- Roll back
- Stabilize the system
- Escalate the issue

---

# 89. Rollback Principle

A rollback approach must be considered before implementing a material change.

---

# 90. Rollback Scope

Rollback planning should consider:

- Application files
- Configuration
- Database changes
- Dependencies
- Data created after deployment
- External interfaces

---

# 91. Rollback Limitation

Not every change can be perfectly reversed.

Where complete rollback is impractical, the change plan must identify an appropriate recovery or corrective approach.

---

# 92. Rollback Trigger

Rollback may be appropriate when a change causes unacceptable:

- Availability impact
- Security impact
- Integrity impact
- Functional failure
- Business disruption

---

# 93. Rollback Authorization

Rollback may be initiated by authorized personnel when required to protect business operations or security.

---

# 94. Rollback Verification

After rollback, responsible personnel must verify that the application has returned to an acceptable operational state.

---

# 95. Failed Change

A failed change must be documented.

---

# 96. Failed Change Review

A material failed change should be reviewed to determine:

- What failed
- Why it failed
- Whether testing was sufficient
- Whether rollback worked
- Whether documentation requires improvement
- Whether corrective action is required

---

# 97. Change Closure

A material change may be closed when:

- Deployment is complete.
- Verification is complete.
- Required documentation is complete.
- Material exceptions are addressed.
- Required follow-up is assigned.

---

# 98. Closure Evidence

Closure must be supported by actual implementation evidence.

---

# 99. Documentation Update

Material changes must include review of affected:

- Architecture documentation
- Configuration documentation
- Operational procedures
- Security documentation
- Recovery documentation
- Support documentation

---

# 100. Recovery Documentation

A significant technical or configuration change is not complete until affected recovery documentation has been reviewed and updated where necessary.

---

# 101. Configuration Baseline

Approved production configuration must be updated when a change legitimately alters the expected configuration.

---

# 102. Source-Code Documentation

Source-code and release records must be sufficient to identify the production version.

---

# 103. Emergency Change Initiation

An Emergency change may be initiated when delay would create unacceptable:

- Security
- Availability
- Integrity
- Business

risk.

---

# 104. Emergency Authorization

Emergency changes require authorization from an appropriate person with authority over the affected service or environment.

---

# 105. Emergency Minimum Controls

Where circumstances permit, an Emergency change must still include:

- Change identification
- Reason
- Responsible person
- Authorization
- Reasonable testing
- Deployment record
- Verification
- Rollback or recovery consideration

---

# 106. Emergency Testing

Emergency changes must be tested to the extent reasonably possible before implementation.

---

# 107. Emergency Security Fix

A critical security vulnerability may justify expedited testing and deployment when delaying the correction would create greater risk.

---

# 108. Emergency Documentation

Documentation omitted because of a genuine emergency must be completed promptly after stabilization.

---

# 109. Emergency Verification

Emergency changes require post-implementation verification.

---

# 110. Emergency Post-Implementation Review

Material Emergency changes must receive post-implementation review.

---

# 111. Emergency Review Scope

The review should determine:

- Whether Emergency classification was justified.
- Whether the change achieved its objective.
- Whether security or operational problems occurred.
- Whether documentation is complete.
- Whether follow-up action is required.

---

# 112. Repeated Emergency Changes

Repeated Emergency changes involving the same application or problem must be investigated for an underlying weakness.

---

# 113. Unauthorized Change

A production change performed without required authorization must be investigated.

---

# 114. Unauthorized Change Response

Response may include:

- Stabilizing the environment
- Preserving evidence
- Determining the responsible account
- Assessing security impact
- Assessing data integrity
- Rolling back
- Incident escalation
- Corrective action

---

# 115. Security Incident

A suspected malicious or materially unauthorized change may require activation of [[PLN-001 Incident Response Plan]].

---

# 116. Evidence

Potential incident evidence must be handled according to [[PROC-011 Evidence Handling Procedure]].

---

# 117. Change Logging

Where technically available, production systems should retain information sufficient to support investigation of significant administrative and configuration changes.

---

# 118. Individual Accountability

Administrative change activity must use individually attributable credentials where practical.

---

# 119. Shared Privileged Credentials

Routine production change activity must not use shared privileged credentials when individual administrative credentials are available.

---

# 120. Privileged Access

Privileged application and infrastructure access must comply with [[PROC-002 Privileged Access Procedure]].

---

# 121. Contractor Production Work

Privileged Infinity contractor production work must follow the controlled access requirements established for the contractor.

---

# 122. Contractor Workspace

Privileged Infinity contractor production or administrative work must be performed from the designated controlled workspace at Scranton Headquarters when required.

---

# 123. Contractor VPN

The Infinity contractor does not receive general VPN access for privileged production administration.

Routine external remote privileged administration is prohibited.

---

# 124. Contractor Change Accountability

Contractor changes must remain attributable to the responsible contractor personnel.

---

# 125. Contractor Change Review

Contractor-developed changes require Dunder Mifflin review and authorization according to change risk.

---

# 126. Contractor Self-Approval

A contractor must not serve as the sole authority for:

- Developing
- Approving
- Deploying
- Validating

the same material production change.

Where staffing limits full separation, Dunder Mifflin must provide appropriate oversight.

---

# 127. Vulnerability Remediation Change

Changes made to correct vulnerabilities remain subject to this procedure.

---

# 128. Vulnerability Priority

Security remediation timing must coordinate with [[PROC-007 Vulnerability Remediation & Retest Procedure]].

---

# 129. Critical Vulnerability

A Critical vulnerability has a target remediation period of 7 days.

---

# 130. High Vulnerability

A High vulnerability has a target remediation period of 30 days.

---

# 131. Moderate Vulnerability

A Moderate vulnerability has a target remediation period of 45 days.

---

# 132. Low Vulnerability

A Low vulnerability has a target remediation period of 60 days.

---

# 133. Vulnerability Exception

A vulnerability that cannot be corrected within the required target must follow the applicable exception and risk process.

---

# 134. Remediation Retest

A material vulnerability correction must be retested where appropriate.

---

# 135. Remediation Closure

A vulnerability is not closed merely because the related production change was successfully deployed.

The vulnerability correction must be appropriately validated.

---

# 136. Database Changes

Material database changes require special consideration because they may affect:

- Integrity
- Availability
- Application compatibility
- Recovery
- Rollback

---

# 137. Database Backup

Before a material database change, responsible personnel must determine whether an appropriate backup or recovery point is required.

---

# 138. Database Integrity Verification

After a material database change, responsible personnel should verify expected data integrity where practical.

---

# 139. Irreversible Database Change

If a database change cannot be directly reversed, the change record must identify the recovery approach.

---

# 140. External Interface Change

A change involving an external provider or interface must consider:

- Provider coordination
- Authentication
- Data exchange
- Error handling
- Rollback
- Business dependency

---

# 141. Payment Processing Change

Changes affecting payment processing must preserve the established model in which Dunder Mifflin does not intentionally retain full payment card numbers.

---

# 142. Authentication Change

Changes affecting authentication require explicit security review and testing.

---

# 143. Authorization Change

Changes affecting authorization require testing that users cannot improperly access unauthorized functions or data.

---

# 144. Internet Exposure Change

A change creating new public Internet exposure requires explicit network and security review.

---

# 145. Logging Change

A change that removes or materially reduces security-relevant logging requires security review before release.

---

# 146. Recovery Impact

A change affecting recovery requirements, dependencies, or procedures must be coordinated with:

- [[PLN-003 Disaster Recovery Plan]]
- [[PROC-012 Backup & Recovery Procedure]]

---

# 147. Business Continuity Impact

A change materially affecting business continuity must be coordinated with [[PLN-002 Business Continuity Plan]].

---

# 148. Cloud Dependency Change

A change materially affecting cloud-provider dependency or portability must be evaluated against [[PLN-004 Cloud Exit & Emergency Migration Plan]].

---

# 149. Transferability Impact

A material Infinity change must be reviewed for impact on application transferability.

---

# 150. Transferability Documentation

A change must not unnecessarily create contractor-exclusive:

- Knowledge
- Credentials
- Source code
- Configuration
- Deployment capability
- Recovery capability

---

# 151. Annual Transferability Review

Material change records may be used as evidence during [[RPT-004 Infinity Transferability Review]].

---

# 152. Change Evidence

Change evidence may include:

- Change request
- Risk or security-impact review
- Threat model
- Source-code record
- Code review
- Test evidence
- Approval
- Deployment record
- Verification
- Rollback record
- Documentation update
- Post-implementation review

---

# 153. Evidence Integrity

Change evidence must represent actual activity.

Personnel must not:

- Backdate approvals.
- Invent code reviews.
- Invent tests.
- Conceal failed testing.
- Record deployment that did not occur.
- Record verification that was not performed.
- Alter records to make an unauthorized change appear authorized.

---

# 154. Record Retention

Change records must be retained according to applicable business, security, and legal requirements.

---

# 155. Metrics

Change and release metrics may include:

- Number of production changes
- Percentage of successful changes
- Failed changes
- Emergency changes
- Unauthorized changes
- Rollbacks
- Security-sensitive changes reviewed
- Changes missing required evidence
- Repeated Emergency changes
- Post-implementation findings

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 156. Key Performance Indicators

Key Performance Indicators (KPIs) may include:

- Percentage of material changes receiving required testing
- Percentage of security-sensitive changes receiving required security review
- Percentage of material changes receiving post-deployment verification
- Percentage of failed changes receiving required follow-up
- Percentage of required change documentation completed

---

# 157. Key Risk Indicators

Key Risk Indicators (KRIs) may include:

- Unauthorized production change
- Repeated Emergency change
- Failed security-sensitive release
- Production change without rollback or recovery planning
- Change missing required testing
- Contractor change outside approved scope
- Change causing material data-integrity problem

---

# 158. Risk Relationship

This procedure primarily supports treatment of:

- R006 Infinity Compromise
- R013 Administrative / Configuration Error
- R019 Infinity Contractor
- R027 Backup Failure
- R028 Data Corruption

and may support other risks depending on the affected system or process.

---

# 159. R006 Infinity Compromise

R006 has:

- Inherent Risk: **16 High**
- Current Residual Risk: **12 High**
- Target Residual Risk: **8 Moderate**

Controlled development, review, security testing, authorized release, and verification support R006 treatment.

---

# 160. R013 Administrative / Configuration Error

R013 has:

- Inherent Risk: **16 High**
- Current Residual Risk: **12 High**
- Target Residual Risk: **6 Moderate**

---

# 161. R013 Control Relationship

This procedure supports R013 through:

- Controlled changes
- Security-impact review
- Testing
- Approval
- Rollback planning
- Deployment verification
- Documentation
- Post-implementation review

---

# 162. R019 Infinity Contractor

R019 has:

- Inherent Risk: **12 High**
- Current Residual Risk: **8 Moderate**
- Target Residual Risk: **4 Low**

Contractor change oversight, individual accountability, Dunder Mifflin approval, and controlled production access support R019 treatment.

---

# 163. R027 Backup Failure

R027 has:

- Inherent Risk: **20 Critical**
- Current Residual Risk: **12 High**
- Target Residual Risk: **5 Moderate**

Pre-change recovery planning and coordination with backup processes support R027 treatment.

---

# 164. R028 Data Corruption

R028 has:

- Inherent Risk: **16 High**
- Current Residual Risk: **9 Moderate**
- Target Residual Risk: **4 Low**

Testing, database change control, backup, rollback, integrity verification, and post-deployment validation support R028 treatment.

---

# 165. Finding

A finding is a documented conclusion supported by evidence concerning whether a requirement, control, process, or expected outcome was satisfied.

---

# 166. Change Findings

Potential findings include:

- Unauthorized production change
- Missing approval
- Missing security review
- Missing required testing
- Failed test ignored
- Missing rollback planning
- Missing deployment verification
- Uncontrolled contractor change
- Incomplete recovery documentation
- Repeated failed release
- Repeated unjustified Emergency change

---

# 167. Finding Register

Material findings must be tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 168. Corrective Action

Material change-management deficiencies must identify:

- Finding
- Corrective action
- Accountable owner
- Due date
- Validation method
- Retest where appropriate

---

# 169. Corrective Action Validation

A corrective action is not complete merely because a process document was updated.

Validation must determine whether the underlying control weakness was corrected.

---

# 170. Assessment

Secure change and release controls are subject to assurance under [[PRO-008 Security Assurance & Continuous Improvement Program]].

---

# 171. Assessment Methods

Assessment may use:

- Inspection
- Interviews
- Sampling
- Observation
- Technical testing
- Independent Performance

---

# 172. Independent Performance

An assessor may independently perform an authorized change-control procedure.

For example:

1. Select a material production change.
2. Obtain the change request.
3. Identify the business purpose.
4. Verify security-impact review.
5. Verify required code review.
6. Verify required testing.
7. Verify release approval.
8. Verify deployment evidence.
9. Verify post-deployment validation.
10. Verify documentation updates.
11. Identify exceptions.
12. Document the result.

---

# 173. Emergency Change Testing

An assessor may sample Emergency changes and determine whether:

- Emergency classification was justified.
- Authorization existed.
- Reasonable testing occurred.
- Deployment was documented.
- Verification occurred.
- Post-implementation review occurred.

---

# 174. Contractor Change Testing

An assessor may sample contractor-developed changes and determine whether:

- Contractor access was authorized.
- Change activity was attributable.
- Dunder Mifflin oversight occurred.
- Required review and testing occurred.
- Production deployment was authorized.
- Contractor activity remained within approved scope.

---

# 175. Failed Change Testing

An assessor may sample failed changes and determine whether:

- Failure was documented.
- Rollback or corrective action occurred.
- Application stability was verified.
- Root or contributing causes were evaluated where appropriate.
- Required follow-up was completed.

---

# 176. Control Effectiveness

Secure change and release controls may be assessed as:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

---

# 177. Effectiveness Evidence

Control-effectiveness conclusions should consider:

- Change requests
- Security-impact reviews
- Threat models
- Code reviews
- Test results
- Approvals
- Deployment records
- Verification
- Rollback records
- Emergency change reviews
- Findings
- Corrective-action validation

---

# 178. Current and Proposed Controls

Change-management reporting must distinguish among:

- Current controls
- Partially implemented controls
- Planned controls
- Implemented controls awaiting validation
- Validated controls

---

# 179. No Premature Risk Credit

Current residual risk must not be reduced merely because:

- This procedure is approved.
- A new review step is planned.
- Testing is scheduled.
- A rollback process is documented.
- A change-control improvement is assigned.
- A corrective action is open.

Risk reduction requires implementation and appropriate validation.

---

# 180. Target Residual Risk

Target residual risk represents expected risk after planned treatment.

It is a prediction.

---

# 181. Validated Post-Treatment Risk

After controls are implemented and validated, applicable risks may be reassessed.

Actual validated risk may be:

- Higher than target
- Equal to target
- Lower than target

---

# 182. Historical Integrity

The original May 2013 risk assessment must remain preserved.

Later validated assessments may establish a new current residual risk without rewriting the historical assessment.

---

# 183. Exceptions

Exceptions to this procedure must be:

- Documented
- Justified
- Risk evaluated
- Approved under appropriate authority
- Time-limited where practical
- Reviewed when conditions change

---

# 184. Procedure Review

This procedure must be reviewed when material changes affect:

- Application development
- Change management
- Release management
- Infinity
- Contractor development
- Application security testing
- Recovery requirements

---

# 185. Traceability

This procedure supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

A controlled change is not demonstrated merely because a change request exists.

Effective change control requires:

**Request → Risk Review → Authorized Development → Review → Test → Release Approval → Controlled Deployment → Verification → Evidence → Follow-Up**

---

# 186. Related Artifacts

- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[RPT-004 Infinity Transferability Review]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[PRO-002 Enterprise Security Architecture Program]]
- [[PRO-004 Vulnerability Management Program]]
- [[PRO-007 Secure Software Development Lifecycle Program]]
- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[STD-001 Information Classification Standard]]
- [[STD-002 Network Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[STD-009 Infinity Security Standard]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-019 Application Security Assessment Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

---

# 187. Review

This procedure must be reviewed:

- At least annually
- Following material development-process change
- Following material change-management change
- Following significant failed release
- Following significant unauthorized change
- Following significant application-security incident
- Following material assessment findings

The IT & Information Security Manager coordinates review.

Material revisions require CIO approval.

---

# 188. Revision History

| Version | Date     | Description                               | Approval |
| ------- | -------- | ----------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Secure Change & Release Procedure | CIO      |