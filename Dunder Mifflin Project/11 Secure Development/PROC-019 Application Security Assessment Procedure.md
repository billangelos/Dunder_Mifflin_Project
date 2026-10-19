# PROC-019 Application Security Assessment Procedure

## Document Control

| Field | Value |
|---|---|
| Document ID | PROC-019 |
| Title | Application Security Assessment Procedure |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Application, Assessment, or Security Testing Change |

---

# 1. Purpose

This procedure establishes the process for planning, authorizing, performing, documenting, and following up on application security assessments.

Application security assessment is intended to determine whether application security requirements and controls:

- Exist
- Are appropriately designed
- Are implemented
- Operate as expected
- Produce appropriate evidence
- Require corrective action

---

# 2. Scope

This procedure applies to:

- Infinity
- Internally developed applications
- Application architecture
- Application configuration
- Authentication
- Authorization
- Session management
- Input handling
- Sensitive information
- Application logging
- Administrative functionality
- Development controls
- Contractor access
- Application recovery
- Application vulnerabilities
- Application security testing

---

# 3. Authority

This procedure operates under:

- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[PRO-007 Secure Software Development Lifecycle Program]]
- [[STD-009 Infinity Security Standard]]

---

# 4. Supporting Requirements

Application security assessments must consider applicable requirements in:

- [[STD-002 Network Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[STD-007 Penetration Testing Standard]]
- [[STD-009 Infinity Security Standard]]

---

# 5. Assessment Lifecycle

Application security assessment follows:

**Plan → Authorize → Scope → Gather Evidence → Assess → Test → Analyze → Report → Remediate → Retest → Reassess**

---

# 6. Assessment Principle

An assessment must determine actual conditions.

The existence of:

- A policy
- A standard
- A procedure
- A configuration requirement
- A completed checklist
- A prior assessment

does not by itself prove that a control currently operates effectively.

---

# 7. Infinity Annual Assessment

Infinity must receive a security assessment at least annually.

---

# 8. Annual Assessment Purpose

The annual Infinity assessment evaluates whether important application-security controls remain:

- Appropriately designed
- Implemented
- Operating as expected
- Supported by evidence

---

# 9. Additional Assessments

Additional application-security assessment may be required following:

- Material architecture change
- Significant application change
- Significant security incident
- Material vulnerability discovery
- Major contractor change
- Significant control failure
- Significant assessment finding

---

# 10. Assessment Planning

Each material assessment must be planned before testing begins.

---

# 11. Assessment Work Plan

A material application security assessment should use an Assessment Work Plan based on [[TMP-001 Assessment Work Plan Template]].

---

# 12. Assessment Work Plan Purpose

The Assessment Work Plan establishes:

- Assessment objective
- Scope
- Applicable requirements
- Controls to be evaluated
- Assessment methods
- Evidence required
- Sampling
- Technical testing
- Responsible assessor
- Schedule
- Expected output

---

# 13. Assessment Objective

The assessment objective must clearly state what the assessment is intended to determine.

---

# 14. Example Objectives

Assessment objectives may include determining whether:

- Infinity administrative access is appropriately restricted.
- Authorization controls prevent access outside approved roles.
- Production changes follow required controls.
- Contractor access remains appropriately limited.
- Application vulnerabilities are remediated as required.
- Recovery documentation remains adequate.
- Source code remains under Dunder Mifflin control.

---

# 15. Scope

Assessment scope must be defined before testing.

---

# 16. Scope Elements

Scope should identify as applicable:

- Application
- Environment
- Components
- Interfaces
- Accounts
- Data
- Administrative functions
- Development controls
- Contractor activities
- Time period
- Locations
- Applicable requirements

---

# 17. Scope Boundaries

The assessment must distinguish between:

- In scope
- Out of scope
- Not applicable

---

# 18. Scope Limitation

A control outside the assessment scope must not be represented as having been tested.

---

# 19. Scope Change

A material change in assessment scope must be documented.

---

# 20. Assessment Authorization

Technical testing must be appropriately authorized before testing begins.

---

# 21. Authorization Scope

Authorization should identify:

- Authorized application
- Authorized environment
- Authorized testing activity
- Authorized period
- Responsible personnel
- Material restrictions

---

# 22. Production Testing

Testing against production requires explicit authorization and safeguards appropriate to the potential business impact.

---

# 23. Production Safety

Production testing must avoid unnecessary:

- Service disruption
- Data modification
- Customer impact
- Business interruption

---

# 24. Destructive Testing

Destructive testing must not be performed against production unless specifically authorized and justified.

---

# 25. Assessment Independence

Assessment independence must be appropriate to the control and assessment objective.

---

# 26. Independence Principle

The person responsible for designing or operating a control should not be the sole source of assurance that the control is effective when reasonable independent assessment is available.

---

# 27. Internal Assessment

An internal assessor may perform an application security assessment when the assessor has sufficient:

- Competence
- Objectivity
- Authority
- Access to evidence

---

# 28. External Assessment

An appropriately authorized outside assessor may be used when:

- Specialized expertise is required.
- Greater independence is appropriate.
- Penetration testing requires outside capability.
- Management requests independent assurance.

---

# 29. Outside Assessor Confidentiality

Before an outside assessor receives sensitive information, an appropriate Non-Disclosure Agreement (NDA) or equivalent enforceable confidentiality obligation must be in place.

---

# 30. Outside Assessor Access

Outside assessor access must be:

- Authorized
- Limited to assessment need
- Time-limited
- Individually attributable where applicable
- Removed when no longer required

---

# 31. Assessor Competence

The assessor must possess knowledge appropriate to the assessment activity.

---

# 32. Competence Areas

Depending on scope, competence may include:

- Application security
- Web application testing
- Network security
- Authentication
- Authorization
- Databases
- Secure development
- Vulnerability assessment
- Penetration testing
- Evidence evaluation

---

# 33. Assessment Criteria

Assessment criteria must be identified before conclusions are reached.

---

# 34. Criteria Sources

Criteria may come from:

- Policies
- Standards
- Procedures
- Approved architecture
- Security requirements
- Risk treatments
- Contractual requirements
- Business requirements

---

# 35. Requirement Traceability

Assessment testing should identify the requirement or control being evaluated.

---

# 36. Control Identification

Where available, the assessment should reference the applicable control in [[REG-003 Enterprise Security Control Inventory]].

---

# 37. Risk Identification

Assessment work should identify relevant risks from:

- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]

---

# 38. Evidence

Assessment conclusions must be supported by sufficient evidence.

---

# 39. Evidence Types

Evidence may include:

- Configuration
- Screenshots
- System output
- Logs
- Access records
- Source-code records
- Change records
- Test results
- Vulnerability records
- Penetration-test results
- Contractor records
- Documentation
- Interviews
- Observation

---

# 40. Evidence Quality

Evidence should be evaluated for:

- Relevance
- Reliability
- Completeness
- Timeliness

---

# 41. Evidence Limitation

A statement that a control exists is not equivalent to evidence that the control operates effectively.

---

# 42. Interview Evidence

Interviews may explain how a process is intended to operate.

Where practical, material conclusions about control operation should also be supported by other evidence.

---

# 43. Documentation Evidence

Documentation demonstrates defined requirements or expected processes.

Documentation alone does not establish that the process was performed.

---

# 44. Configuration Evidence

Configuration evidence should reflect the actual environment being assessed.

---

# 45. Evidence Date

Evidence should be sufficiently current for the assessment objective.

---

# 46. Evidence Integrity

Assessment evidence must reflect actual conditions.

---

# 47. Prohibited Evidence Practices

Personnel must not:

- Invent assessment results.
- Backdate evidence.
- Create fictional screenshots.
- Invent security tests.
- Alter logs to support a desired conclusion.
- Conceal failed testing.
- Record unperformed procedures as complete.
- Remove unfavorable evidence from the assessment record solely to improve the result.

---

# 48. Evidence Handling

Potential incident or investigative evidence must be handled according to [[PROC-011 Evidence Handling Procedure]].

---

# 49. Sampling

Sampling may be used when testing every population item is unnecessary or impractical.

---

# 50. Sample Selection

Samples should be selected based on the assessment objective and risk.

---

# 51. Sample Documentation

The assessment should identify:

- Population
- Sample selected
- Selection rationale
- Testing performed
- Exceptions identified

where applicable.

---

# 52. Sample Limitation

A sample result must not be represented as proving conditions outside the reasonable scope of the sample.

---

# 53. Higher-Risk Sampling

Higher-risk items may receive greater testing attention.

Examples include:

- Privileged accounts
- Contractor accounts
- Production changes
- Internet-facing components
- Critical vulnerabilities
- Security-sensitive application changes

---

# 54. Assessment Methods

Application security assessment may use:

- Inspection
- Observation
- Interviews
- Sampling
- Independent Performance
- Technical Testing

---

# 55. Inspection

Inspection examines evidence such as:

- Configuration
- Documentation
- Logs
- Access records
- Change records
- Test results
- Source-code records

---

# 56. Observation

Observation evaluates an authorized process while it is being performed.

---

# 57. Interview

Interviewing personnel may help determine:

- Process understanding
- Responsibility
- Actual practice
- Known exceptions
- Control limitations

---

# 58. Independent Performance

Independent Performance means the assessor performs an authorized control procedure independently to determine whether the expected result occurs.

---

# 59. Independent Performance Example

An assessor evaluating application authorization may:

1. Obtain an authorized test account.
2. Identify the account's approved role.
3. Identify a function outside that role.
4. Attempt the authorized test.
5. Observe the application's response.
6. Preserve relevant evidence.
7. Compare the result with the requirement.
8. Document the conclusion.

---

# 60. Technical Testing

Technical Testing directly evaluates application or supporting technical behavior.

---

# 61. Technical Testing Examples

Technical Testing may include:

- Authentication testing
- Authorization testing
- Session testing
- Input testing
- Configuration review
- Vulnerability testing
- Application-interface testing
- Penetration testing

---

# 62. Technical Testing Authorization

Technical Testing must remain within authorized scope.

---

# 63. Testing Accounts

Testing should use authorized accounts appropriate to the assessment objective.

---

# 64. Testing Data

Testing must avoid unnecessary exposure or modification of sensitive production information.

---

# 65. Test Safety

Testing must be stopped or adjusted if it creates an unexpected material risk to:

- Availability
- Integrity
- Confidentiality
- Customers
- Business operations

---

# 66. Architecture Assessment

The Infinity assessment must evaluate applicable architecture requirements.

---

# 67. Tier Separation

Assessment should determine whether Infinity maintains logical separation among:

- Web tier
- Application tier
- Database tier

---

# 68. Database Exposure

Assessment must determine whether the Infinity database is directly exposed to the public Internet.

The expected result is that it is not.

---

# 69. Administrative Exposure

Assessment should determine whether administrative interfaces are unnecessarily exposed to the public Internet.

---

# 70. Network Exposure

Assessment should determine whether public exposure is limited to required Infinity services.

---

# 71. Environment Separation

Assessment should determine whether:

- Development
- Test
- Production

remain logically separated.

---

# 72. Production Development

Assessment should determine whether routine development is occurring directly in production.

The expected result is that it is not.

---

# 73. Authentication Assessment

Assessment should evaluate application authentication appropriate to the scope.

---

# 74. Authentication Testing

Testing may evaluate:

- Login behavior
- Credential handling
- Administrative authentication
- Authentication failure behavior
- Password exposure
- Service-account use

---

# 75. Plaintext Password Storage

Assessment must identify any evidence that Infinity stores user passwords in recoverable plaintext form.

---

# 76. Authentication Secret Exposure

Assessment should determine whether passwords or other authentication secrets are unnecessarily exposed through:

- Logs
- Source code
- Application output
- Configuration
- Network communication

---

# 77. Administrative Accounts

Administrative accounts must be individually attributable where required.

---

# 78. Shared Administrative Access

Routine shared administrative access should be identified as a control concern when individual credentials can reasonably be used.

---

# 79. Authorization Assessment

Assessment must evaluate whether users are restricted to authorized functions and information.

---

# 80. Authorization Testing

Testing should determine whether a user can improperly gain access by:

- Changing a request
- Modifying a parameter
- Directly requesting a hidden function
- Manipulating client-side controls
- Attempting functions assigned to another role

---

# 81. Server-Side Authorization

Assessment should determine whether security-sensitive authorization is enforced by trusted application components.

---

# 82. Administrative Function Testing

Assessment should determine whether ordinary customer accounts can improperly access administrative functions.

---

# 83. Input Handling Assessment

Assessment should evaluate how Infinity handles untrusted input.

---

# 84. Input Testing

Testing may evaluate:

- Invalid input
- Unexpected input
- Excessive input
- Special characters
- Injection attempts
- Input affecting application logic

within authorized scope.

---

# 85. Server-Side Validation

Assessment should determine whether security-sensitive validation relies solely on client-side controls.

The expected result is that it does not.

---

# 86. Injection Testing

Authorized testing should evaluate material injection risks where applicable.

---

# 87. Database Interaction

Assessment should evaluate whether database interaction uses development practices intended to reduce injection risk.

---

# 88. Output Handling

Assessment should evaluate whether application output creates unnecessary scripting, content-injection, or sensitive-information exposure risk.

---

# 89. Error Handling

Assessment should determine whether public error messages unnecessarily expose:

- Database information
- Internal paths
- Authentication information
- Configuration
- Source-code details
- Infrastructure details

---

# 90. Session Management Assessment

Assessment should evaluate session behavior appropriate to application risk.

---

# 91. Session Testing

Testing may evaluate:

- Session creation
- Session termination
- Session expiration
- Session identifier exposure
- Behavior following material privilege change

---

# 92. Sensitive Information Assessment

Assessment must evaluate protection of sensitive Infinity information.

---

# 93. Payment Information

Assessment should confirm that Dunder Mifflin does not intentionally store full payment card numbers within Infinity.

---

# 94. Payment Token

Assessment should confirm that retained payment tokens receive Confidential handling.

---

# 95. Logging Review

Assessment should determine whether logs unnecessarily contain:

- Passwords
- Authentication secrets
- Full payment card numbers
- Other sensitive information unrelated to legitimate logging requirements

---

# 96. Data Minimization

Assessment should identify unnecessary collection or retention of sensitive information where material.

---

# 97. Encryption in Transit

Assessment should determine whether sensitive information transmitted across untrusted networks receives appropriate encrypted protection.

---

# 98. Database Access Assessment

Assessment should evaluate whether direct database access is limited to authorized:

- Application services
- Administrators
- Support personnel

---

# 99. Database Privilege

Assessment should determine whether database accounts possess unnecessary privileges.

---

# 100. Data Integrity

Assessment should consider whether unexplained or unauthorized data modification can be detected and investigated.

---

# 101. Source-Code Assessment

Assessment must evaluate Dunder Mifflin's control of Infinity source code.

---

# 102. Repository Ownership

Assessment should confirm that Dunder Mifflin maintains access to and control of the authoritative repository.

---

# 103. Repository Access

Assessment should determine whether repository access is limited according to legitimate development, support, review, or administrative need.

---

# 104. Source-Code Accountability

Assessment should determine whether source-code changes are attributable to authorized individuals.

---

# 105. Source-Code Availability

Assessment should confirm that current source code remains available to Dunder Mifflin.

---

# 106. Contractor Repository Dependency

Assessment should identify whether the authoritative source code or repository is controlled exclusively by the contractor.

The expected result is that it is not.

---

# 107. Change Management Assessment

Assessment should evaluate material application changes against [[PROC-018 Secure Change & Release Procedure]].

---

# 108. Change Sample

The assessor may select a sample of material production changes.

---

# 109. Change Sample Testing

For each selected change, the assessor should determine whether applicable evidence demonstrates:

- Business purpose
- Security-impact review
- Development authorization
- Code review
- Testing
- Release approval
- Deployment
- Post-deployment verification
- Documentation update

---

# 110. Emergency Change Assessment

Emergency changes should be evaluated for:

- Legitimate emergency justification
- Authorization
- Reasonable testing
- Deployment documentation
- Verification
- Post-implementation review

---

# 111. Unauthorized Change

Evidence of an unauthorized production change must be investigated.

---

# 112. Threat Modeling Assessment

For material security-sensitive changes, assessment should determine whether appropriate threat modeling occurred.

---

# 113. Threat Model Quality

Threat-model assessment should consider whether the analysis addressed appropriate:

- Assets
- Trust boundaries
- Entry points
- Threats
- Controls

rather than merely whether a document exists.

---

# 114. Vulnerability Assessment

Application vulnerabilities must be evaluated under [[PRO-004 Vulnerability Management Program]].

---

# 115. Vulnerability Records

The assessor should review relevant vulnerability records to determine whether:

- Vulnerabilities were documented.
- Severity was assigned.
- Remediation was tracked.
- Exceptions were approved where required.
- Retesting occurred where appropriate.

---

# 116. Remediation Targets

Applicable vulnerability-remediation targets are:

| Severity | Target |
|---|---:|
| Critical | 7 days |
| High | 30 days |
| Moderate | 45 days |
| Low | 60 days |

---

# 117. Overdue Vulnerability

An overdue vulnerability must not be represented as compliant solely because remediation is planned.

---

# 118. Vulnerability Exception

A vulnerability exceeding the required target must have an appropriate approved exception where required.

---

# 119. Retest Evidence

Where retesting is required, evidence must demonstrate that retesting actually occurred.

---

# 120. Penetration Testing

Infinity must receive application penetration testing at least annually.

---

# 121. Penetration Testing Standard

Penetration testing must comply with [[STD-007 Penetration Testing Standard]].

---

# 122. Penetration Test Relationship

The annual application security assessment and annual penetration test are related but distinct assurance activities.

---

# 123. Assessment and Penetration Testing

The annual application security assessment evaluates a broad set of application controls.

Penetration testing uses authorized adversarial technical testing to identify exploitable weaknesses.

---

# 124. Penetration Test Review

The application security assessment should review penetration-test results relevant to the assessment period.

---

# 125. Penetration Test Findings

The assessor should determine whether material penetration-test findings were:

- Recorded
- Assigned
- Remediated
- Retested where appropriate
- Properly closed

---

# 126. Penetration Test Chain

Infinity penetration testing supports:

**Penetration Test → Finding → Remediation → Retest → Control Effectiveness → R006 Risk Reassessment**

---

# 127. Contractor Assessment

The annual Infinity assessment must evaluate applicable contractor controls.

---

# 128. Contractor Sponsorship

Assessment should determine whether contractor personnel with Dunder Mifflin access have valid company sponsorship.

---

# 129. Contractor Access Duration

Assessment should determine whether contractor access remains within authorized duration.

---

# 130. Contractor Least Privilege

Assessment should determine whether contractor access is limited to authorized:

- Systems
- Environments
- Repositories
- Information
- Functions

---

# 131. Contractor Production Access

Assessment should determine whether production access received specific authorization.

Development access does not automatically authorize production access.

---

# 132. Contractor Accountability

Contractor technical activity must remain individually attributable where required.

---

# 133. Contractor Privileged Activity

Assessment should evaluate whether privileged Infinity contractor production or administrative activity follows the established controlled-workspace requirement.

---

# 134. Contractor VPN

Assessment should verify that the Infinity contractor has not been provided general VPN access for routine privileged production administration.

---

# 135. Contractor Physical Access

Assessment may review applicable contractor physical-access evidence under:

- [[PROC-014 Facility Access Procedure]]
- [[PROC-015 Visitor & Vendor Access Procedure]]
- [[PROC-016 Restricted Area Access Procedure]]

---

# 136. Contractor Confidentiality

Assessment should confirm that required confidentiality protection exists before contractor personnel receive sensitive Dunder Mifflin information.

---

# 137. Contractor Departure

Assessment may sample former contractor personnel to determine whether applicable:

- Repository access
- Development access
- Test access
- Production access
- Physical access
- Company credentials

were removed when no longer required.

---

# 138. Contractor Self-Assessment Limitation

The contractor responsible for supporting Infinity must not be the sole source of assurance concerning the effectiveness of its own controls.

---

# 139. Third-Party Review

The Infinity contractor is a Critical third party and is subject to applicable annual review under [[POL-008 Third-Party Security Policy]].

---

# 140. Recovery Assessment

The application security assessment must consider Infinity recovery controls where included in scope.

---

# 141. Infinity Recovery Requirements

Infinity has:

- Maximum Tolerable Downtime: **3 days**
- Recovery Time Objective: **24 hours**
- Recovery Point Objective: **4 hours**

---

# 142. Recovery Requirement Limitation

The existence of recovery requirements does not demonstrate that Infinity can meet them.

---

# 143. Recovery Documentation

Assessment should determine whether recovery documentation is sufficient for a qualified Information Technology professional unfamiliar with the environment to perform required recovery activities.

---

# 144. Contractor Recovery Dependency

Assessment should identify whether Infinity recovery depends solely on undocumented contractor knowledge.

The expected result is that it does not.

---

# 145. Recovery Test Evidence

Where recovery testing occurred during the assessment period, the assessor should evaluate actual evidence rather than assume successful recovery.

---

# 146. Recovery Test Review

Recovery evidence may include:

- Test scope
- Recovery source
- Start time
- Completion time
- Recovery point
- Technical validation
- Security validation
- Business validation where applicable
- Findings
- Corrective actions

---

# 147. Recovery Coordination

Recovery assessment must coordinate with:

- [[PLN-003 Disaster Recovery Plan]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[TMP-003 Recovery Test Template]]

---

# 148. Transferability Assessment

Infinity transferability must be reviewed at least annually.

---

# 149. Transferability Relationship

Transferability is documented in [[RPT-004 Infinity Transferability Review]].

---

# 150. Transferability Assessment Scope

Assessment should determine whether Dunder Mifflin controls or can obtain:

- Current source code
- Repository access
- Build information
- Deployment procedures
- Architecture documentation
- Configuration information
- Required credentials
- Database information
- Recovery information
- Contractor work product
- Important vendor information

---

# 151. Qualified Replacement Test

Where appropriate, the assessor should consider whether a qualified replacement provider could reasonably assume Infinity support using available company-controlled information.

---

# 152. Transferability Finding

A material dependency preventing reasonable transfer must be documented as a finding.

---

# 153. Security Monitoring Assessment

Assessment should evaluate whether Infinity produces security-relevant information sufficient to support reasonable monitoring.

---

# 154. Security-Relevant Events

Assessment may consider logging of:

- Authentication failure
- Significant authorization failure
- Administrative activity
- Material application error
- Security-control failure
- Other suspicious activity

---

# 155. Log Protection

Assessment should determine whether security-relevant logs are protected against unauthorized:

- Modification
- Deletion
- Disclosure

---

# 156. Log Time

Assessment should consider whether Infinity systems maintain reasonably consistent time for investigation and event correlation.

---

# 157. Monitoring Limitation

The absence of a Security Information and Event Management (SIEM) platform does not by itself establish a finding.

Assessment must evaluate the actual monitoring requirement and available controls.

---

# 158. Incident Response Assessment

The assessor should consider whether material application-security events are appropriately connected to:

- [[PROC-010 Security Event Escalation Procedure]]
- [[PLN-001 Incident Response Plan]]

---

# 159. Prior Incident Review

Where a material Infinity security incident occurred during the assessment period, the assessor may evaluate:

- Detection
- Escalation
- Containment
- Evidence handling
- Recovery
- Corrective action
- Lessons learned

as relevant to the assessment objective.

---

# 160. Finding

A finding is a documented conclusion supported by evidence concerning whether a requirement, control, process, or expected outcome was satisfied.

---

# 161. Finding Categories

Assessment conclusions may identify:

- Satisfactory condition
- Partial satisfaction
- Control deficiency
- Significant control deficiency
- Not applicable
- Unable to determine

depending on evidence and scope.

---

# 162. Satisfactory Condition

A satisfactory condition indicates that available evidence supports the assessed requirement or expected control outcome.

---

# 163. Partial Satisfaction

Partial satisfaction indicates that a requirement or control is implemented or operating only in part.

---

# 164. Control Deficiency

A Control Deficiency exists when evidence demonstrates that a required control or expected outcome is not adequately satisfied.

---

# 165. Significant Control Deficiency

A Significant Control Deficiency is a weakness with material security or business significance requiring elevated management attention.

---

# 166. Unable to Determine

Unable to Determine may be used when evidence is insufficient to reach a supportable conclusion.

Insufficient evidence must not automatically be treated as satisfactory.

---

# 167. Finding Components

A material finding should identify:

- Requirement
- Condition
- Evidence
- Risk or impact
- Required corrective action
- Accountable owner
- Due date
- Validation method
- Retest requirement where applicable

---

# 168. Finding Evidence

A finding must be based on actual evidence rather than assumption.

---

# 169. Finding Register

Material deficiency findings must be tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 170. Duplicate Findings

An existing open finding should not be duplicated unnecessarily.

The assessment may update or reference the existing finding when appropriate.

---

# 171. Finding Ownership

Each material deficiency finding must have one accountable owner.

---

# 172. Finding Severity

Finding priority should reflect:

- Security impact
- Business impact
- Exploitability
- Exposure
- Information sensitivity
- Existing controls
- Relevant risk

---

# 173. Corrective Action

Corrective action must address the underlying weakness identified by the finding.

---

# 174. Corrective Action Limitation

A corrective action is not complete solely because:

- Code was changed.
- Configuration was changed.
- A ticket was closed.
- Documentation was updated.
- A developer states the issue is fixed.

---

# 175. Corrective Action Evidence

Corrective-action evidence must demonstrate what was actually changed.

---

# 176. Retesting

A material technical finding must be retested where appropriate.

---

# 177. Retest Objective

Retesting should determine whether:

- The original weakness was corrected.
- The expected control outcome is now achieved.
- The correction introduced another material problem.
- Additional corrective action is required.

---

# 178. Retest Scope

Retesting should include enough of the original condition to support a valid closure decision.

---

# 179. Failed Retest

A failed retest means the finding remains open or requires revised corrective action.

---

# 180. Successful Retest

A successful retest may support finding closure when other required corrective actions are also complete.

---

# 181. Finding Closure

A finding may be closed only when sufficient evidence supports closure.

---

# 182. Closure Authority

Finding closure must follow the accountability and assurance processes established by:

- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[REG-004 Finding & Corrective Action Register]]

---

# 183. Assessment Report

A material application security assessment must produce an assessment record or report.

---

# 184. Assessment Report Content

The assessment report should identify:

- Assessment objective
- Scope
- Criteria
- Assessor
- Assessment period
- Methods
- Evidence
- Testing performed
- Scope limitations
- Conclusions
- Findings
- Corrective actions
- Required retesting
- Relevant risks

---

# 185. No Manufactured Results

An assessment report must not contain fabricated test results to make the assessment appear complete.

---

# 186. Incomplete Assessment

If required assessment work could not be completed, the report must identify:

- Work not completed
- Reason
- Resulting limitation
- Required follow-up

---

# 187. Assessment Conclusion

The assessment conclusion must be supported by the evidence collected.

---

# 188. Control Effectiveness

Controls may be assessed as:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

---

# 189. Effective

Effective means available evidence supports that the control is appropriately implemented and operating sufficiently to achieve its intended outcome.

---

# 190. Partially Effective

Partially Effective means the control provides some intended protection but has meaningful limitations.

---

# 191. Ineffective

Ineffective means the control exists but does not adequately achieve its intended security outcome.

---

# 192. Not Implemented

Not Implemented means the required or planned control has not been implemented.

---

# 193. Design and Operation

Control assessment should distinguish between:

- Control design
- Control implementation
- Control operation
- Control effectiveness

---

# 194. Design Effectiveness

A control may be appropriately designed but not consistently implemented or operated.

---

# 195. Operational Effectiveness

A control may exist technically but fail operationally because required activities are not performed consistently.

---

# 196. Evidence of Effectiveness

Evidence of effectiveness may include:

- Technical results
- Samples
- Logs
- Change records
- Access records
- Vulnerability records
- Successful testing
- Recovery results
- Corrective-action validation

---

# 197. Assessment Does Not Guarantee Security

A satisfactory assessment does not establish that the application:

- Has no vulnerabilities.
- Cannot be compromised.
- Will remain secure indefinitely.
- Requires no further monitoring.

---

# 198. Risk Relationship

Application security assessment primarily supports:

- R006 Infinity Compromise
- R013 Administrative / Configuration Error
- R018 Third-Party Technology Failure / Compromise
- R019 Infinity Contractor
- R027 Backup Failure
- R028 Data Corruption

---

# 199. R006 Infinity Compromise

R006 has:

- Inherent Risk: **16 High**
- Current Residual Risk: **12 High**
- Target Residual Risk: **8 Moderate**

---

# 200. R006 Assessment Relationship

R006 assessment should consider:

- Architecture
- Internet exposure
- Authentication
- Authorization
- Input handling
- Environment separation
- Source-code control
- Change management
- Security testing
- Vulnerability management
- Contractor access
- Recovery

---

# 201. R013 Administrative / Configuration Error

R013 has:

- Inherent Risk: **16 High**
- Current Residual Risk: **12 High**
- Target Residual Risk: **6 Moderate**

Change records, configuration evidence, testing, rollback, and verification support assessment of R013 treatment.

---

# 202. R018 Third-Party Technology Failure / Compromise

R018 has:

- Inherent Risk: **12 High**
- Current Residual Risk: **8 Moderate**
- Target Residual Risk: **6 Moderate**

Contractor and external-service dependencies should be considered when assessing applicable application controls.

---

# 203. R019 Infinity Contractor

R019 has:

- Inherent Risk: **12 High**
- Current Residual Risk: **8 Moderate**
- Target Residual Risk: **4 Low**

---

# 204. R019 Assessment Relationship

Assessment of R019 should consider:

- Contractor sponsorship
- Access duration
- Least privilege
- Individual accountability
- Production authorization
- Controlled privileged activity
- Confidentiality
- Source-code ownership
- Documentation
- Transferability

---

# 205. R027 Backup Failure

R027 has:

- Inherent Risk: **20 Critical**
- Current Residual Risk: **12 High**
- Target Residual Risk: **5 Moderate**

Recovery assessment should use actual recovery evidence rather than assume backup success.

---

# 206. R028 Data Corruption

R028 has:

- Inherent Risk: **16 High**
- Current Residual Risk: **9 Moderate**
- Target Residual Risk: **4 Low**

Assessment should consider:

- Database access
- Change control
- Integrity validation
- Logging
- Backup
- Recovery
- Reconciliation

---

# 207. Current Residual Risk

Current residual risk represents risk after controls actually present in the assessed environment.

---

# 208. Proposed Control Limitation

A planned application-security control receives no current residual-risk credit solely because it appears in:

- A policy
- A standard
- A procedure
- A treatment plan
- A project plan

---

# 209. Implemented Control

Implementation alone does not establish effectiveness.

A newly implemented control may require validation before risk reassessment.

---

# 210. Target Residual Risk

Target residual risk represents expected risk after planned treatment.

It is a prediction.

---

# 211. Validated Post-Treatment Risk

After controls are implemented and validated, applicable risk may be reassessed.

Actual validated risk may be:

- Higher than target
- Equal to target
- Lower than target

---

# 212. Risk Reassessment

Risk reassessment must consider:

- Assessment evidence
- Findings
- Corrective actions
- Retest results
- Control effectiveness
- Changes in threat or business conditions

---

# 213. Historical Integrity

The original May 2013 risk assessment must remain preserved.

A later validated assessment may establish a new current residual risk without rewriting the historical assessment.

---

# 214. Assessment Failure

A failed assessment does not automatically mean the application must be shut down.

Management must evaluate:

- Severity
- Exploitability
- Exposure
- Business impact
- Existing controls
- Available corrective action
- Need for immediate containment

---

# 215. Immediate Risk

A finding presenting immediate material risk must be escalated promptly rather than waiting for the final assessment report.

---

# 216. Incident Escalation

Evidence of active or suspected compromise must be escalated under:

- [[PROC-010 Security Event Escalation Procedure]]
- [[PLN-001 Incident Response Plan]]

---

# 217. Assessment Metrics

Application-assessment metrics may include:

- Annual Infinity assessment status
- Controls assessed
- Findings identified
- Significant findings
- Findings overdue
- Findings awaiting retest
- Successful retests
- Failed retests
- Scope limitations
- Vulnerabilities overdue
- Penetration-test findings unresolved

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 218. Key Performance Indicators

Key Performance Indicators (KPIs) may include:

- Completion of annual Infinity security assessment
- Percentage of planned assessment work completed
- Percentage of findings with assigned corrective action
- Percentage of corrective actions completed within target
- Percentage of remediated technical findings successfully retested
- Percentage of assessment evidence meeting requirements

---

# 219. Key Risk Indicators

Key Risk Indicators (KRIs) may include:

- Significant unresolved application-security finding
- Overdue Critical vulnerability
- Overdue High vulnerability
- Failed remediation retest
- Repeated authorization weakness
- Unauthorized production change
- Excessive contractor access
- Material assessment scope limitation
- Missing recovery evidence
- Material transferability dependency

---

# 220. Reporting Levels

Application-assessment information must support appropriate reporting.

---

# 221. Operational Reporting

Operational reporting may include:

- Individual vulnerabilities
- Failed tests
- Evidence gaps
- Specific contractor-access issues
- Required technical corrections
- Retest status

---

# 222. Management Reporting

Management reporting may include:

- Finding trends
- Overdue corrective actions
- Vulnerability performance
- Assessment completion
- Penetration-test remediation
- Contractor-control issues
- Recovery weaknesses
- Transferability concerns

---

# 223. Executive Reporting

Executive reporting should focus on:

- Material Infinity risk
- Significant unresolved findings
- Major contractor dependency
- Material overdue treatment
- Required risk decisions

---

# 224. Reporting Principle

Assessment detail should flow upward as:

**Technical Evidence → Finding → Management Impact → Enterprise Risk → Executive Decision**

---

# 225. Continuous Monitoring

Annual assessment does not replace ongoing operational monitoring.

---

# 226. Continuous Monitoring Meaning

Continuous monitoring means maintaining risk-appropriate ongoing awareness of security conditions.

It does not require every application activity to be watched continuously by personnel.

---

# 227. Assessment and Monitoring

Operational monitoring may identify issues requiring:

- Immediate investigation
- Corrective action
- Additional assessment
- Risk reassessment

before the next annual assessment.

---

# 228. Assessment Records

Assessment records must be retained according to applicable:

- Security
- Business
- Legal
- Contractual

requirements.

---

# 229. Assessment Record Protection

Assessment records containing sensitive:

- Vulnerabilities
- Architecture
- Credentials
- Security weaknesses
- Contractor information

must receive appropriate protection.

---

# 230. Distribution

Detailed application-security assessment results must be limited to personnel with legitimate business need.

---

# 231. Exceptions

Exceptions to this procedure must be:

- Documented
- Justified
- Risk evaluated
- Approved under appropriate authority
- Time-limited where practical
- Reviewed when conditions change

---

# 232. Assessment Limitation Exception

An assessment limitation must not be hidden through an exception.

The assessment report must still accurately describe what could and could not be evaluated.

---

# 233. Procedure Review

This procedure must be reviewed when material changes affect:

- Infinity
- Application-security requirements
- Assessment methods
- Penetration testing
- Vulnerability management
- Contractor support
- Assurance requirements

---

# 234. Traceability

This procedure supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Application assurance is not demonstrated merely because an assessment was scheduled or a report was created.

Effective assessment requires:

**Requirement → Objective → Scope → Evidence → Test → Conclusion → Finding → Remediation → Retest → Control Effectiveness → Risk Reassessment**

---

# 235. Related Artifacts

- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[RPT-004 Infinity Transferability Review]]
- [[REG-001 Enterprise Asset Register]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[PRO-004 Vulnerability Management Program]]
- [[PRO-005 Security Operations Program]]
- [[PRO-007 Secure Software Development Lifecycle Program]]
- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[STD-001 Information Classification Standard]]
- [[STD-002 Network Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[STD-007 Penetration Testing Standard]]
- [[STD-009 Infinity Security Standard]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]
- [[PROC-008 Security Monitoring Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-014 Facility Access Procedure]]
- [[PROC-015 Visitor & Vendor Access Procedure]]
- [[PROC-016 Restricted Area Access Procedure]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-004 Data Exposure Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]
- [[TMP-001 Assessment Work Plan Template]]
- [[TMP-003 Recovery Test Template]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

---

# 236. Review

This procedure must be reviewed:

- At least annually
- Following material application-security assessment change
- Following material penetration-testing change
- Following significant assessment failure
- Following significant application-security incident
- Following significant assessment findings

The IT & Information Security Manager coordinates review.

Material revisions require CIO approval.

---

# 237. Revision History

| Version | Date     | Description                                       | Approval |
| ------- | -------- | ------------------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Application Security Assessment Procedure | CIO      |