# PROC-020 Contractor Development Access Procedure

## Document Control

| Field | Value |
|---|---|
| Document ID | PROC-020 |
| Title | Contractor Development Access Procedure |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Contractor, Development, Access, or Infinity Support Change |

---

# 1. Purpose

This procedure establishes requirements for granting, managing, reviewing, and terminating technical access provided to contractors supporting Infinity.

The procedure is intended to ensure that contractor access is:

- Authorized
- Sponsored
- Individually attributable
- Limited to legitimate business need
- Time-limited
- Appropriate to the required environment
- Subject to Dunder Mifflin oversight
- Removed when no longer required

---

# 2. Scope

This procedure applies to contractors requiring access to:

- Infinity source code
- Source-code repositories
- Development systems
- Test systems
- Production systems
- Application configuration
- Databases
- Administrative functions
- Technical documentation
- Recovery information
- Dunder Mifflin facilities for Infinity support

---

# 3. Authority

This procedure operates under:

- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[PRO-003 Identity and Access Management Program]]
- [[PRO-007 Secure Software Development Lifecycle Program]]
- [[STD-009 Infinity Security Standard]]

---

# 4. Supporting Procedures

Contractor development access must comply with applicable requirements in:

- [[PROC-002 Privileged Access Procedure]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-014 Facility Access Procedure]]
- [[PROC-015 Visitor & Vendor Access Procedure]]
- [[PROC-016 Restricted Area Access Procedure]]
- [[PROC-018 Secure Change & Release Procedure]]

---

# 5. Access Lifecycle

Contractor development access follows:

**Business Need → Sponsor → Confidentiality → Identify Personnel → Request → Approve → Provision → Verify → Use → Monitor → Review → Renew or Revoke**

---

# 6. Access Principle

Contractor status does not create an entitlement to Dunder Mifflin access.

Access is granted only when required for authorized work.

---

# 7. Infinity Contractor

The third-party contractor supporting Infinity is classified as a Critical third party.

---

# 8. Company Sponsorship

Each contractor requiring Dunder Mifflin access must have an identified company sponsor.

---

# 9. Sponsor Responsibility

The sponsor is responsible for confirming:

- Business need
- Required access
- Required duration
- Appropriate personnel
- Continued need
- Material access changes

---

# 10. Sponsor Limitation

The sponsor does not independently determine technical privilege beyond what is reasonably required for the approved work.

Information Technology (IT) must evaluate technical access requirements.

---

# 11. Confidentiality Requirement

Before a contractor receives sensitive Dunder Mifflin information, an appropriate Non-Disclosure Agreement (NDA) or equivalent enforceable confidentiality obligation must be in place.

---

# 12. Confidentiality Scope

Confidentiality obligations apply according to:

- Information accessed
- Information sensitivity
- Work performed

rather than vendor title alone.

---

# 13. Confidentiality Limitation

The existence of an NDA does not establish that:

- Contractor access is secure.
- Contractor controls are effective.
- Technical access is appropriate.
- Security testing is sufficient.
- Contractor oversight is complete.

---

# 14. Personnel Identification

Contractor personnel expected to perform scheduled onsite Infinity work should be identified at least one business day before arrival where practical.

---

# 15. Personnel Information

The access request should identify:

- Contractor organization
- Individual requiring access
- Company sponsor
- Work to be performed
- Systems or environments required
- Requested privilege
- Requested start date
- Requested expiration date

---

# 16. Emergency Personnel

A legitimate emergency may require contractor personnel who could not reasonably be identified one business day in advance.

---

# 17. Emergency Personnel Exception

Emergency contractor personnel must still receive:

- Identity verification appropriate to the circumstances
- Sponsor authorization
- Required confidentiality protection
- Access limited to the emergency need
- Documentation

---

# 18. Emergency Exception Review

Emergency contractor access must be reviewed after the emergency to determine:

- Who received access
- What access was provided
- What work was performed
- Whether access remains active
- Whether follow-up action is required

---

# 19. Access Request

Contractor technical access must be requested before provisioning.

---

# 20. Access Request Content

The request must identify:

- Individual
- Sponsor
- Business need
- Application or system
- Environment
- Required role
- Required privilege
- Start date
- Expiration date
- Production access requirement, if any

---

# 21. Environment-Specific Access

Access must distinguish among:

- Development
- Test
- Production
- Repository
- Database
- Administrative infrastructure

as applicable.

---

# 22. Development Access

Development access authorizes only the development activity necessary for the approved work.

---

# 23. Test Access

Test access must be limited to the testing required for authorized work.

---

# 24. Production Access

Production access requires specific authorization.

Development or test access does not automatically authorize production access.

---

# 25. Repository Access

Repository access must be granted according to the contractor's authorized development or support responsibilities.

---

# 26. Database Access

Direct database access must be separately justified when required.

Application support responsibility does not automatically require unrestricted database access.

---

# 27. Least Privilege

Contractor personnel must receive only the access necessary to perform authorized work.

---

# 28. Access Minimization

Contractor access should be limited by:

- System
- Environment
- Function
- Privilege
- Information
- Duration

where technically practical.

---

# 29. Individual Accounts

Contractor technical access must use individually attributable accounts where technically practical.

---

# 30. Shared Contractor Accounts

Shared contractor accounts must not be used for routine administrative activity when individual accounts can reasonably be provided.

---

# 31. Account Ownership

A contractor account must identify the individual responsible for its use.

---

# 32. Credential Sharing

Contractor personnel must not share individually assigned credentials.

---

# 33. Authentication

Contractor authentication must comply with applicable requirements in [[STD-005 Authentication & Account Security Standard]].

---

# 34. Smart-Card Authentication

Smart-card multifactor authentication using an associated Personal Identification Number (PIN) or other approved secret should be implemented for contractor access where supported as part of the planned authentication improvements.

Until implemented and validated, this requirement receives no current residual-risk credit.

---

# 35. Credential Protection

Contractor credentials must be protected against:

- Sharing
- Unauthorized disclosure
- Unsecured storage
- Use by unauthorized personnel

---

# 36. Access Duration

Contractor access must be time-limited.

---

# 37. Initial Authorization Period

Initial contractor access may not exceed three months.

---

# 38. Renewal Period

Continued access may be renewed for periods not exceeding six months when legitimate business need continues.

---

# 39. Renewal

Renewal requires confirmation of:

- Current sponsor
- Continued business need
- Required access
- Appropriate privilege
- New expiration date

---

# 40. Automatic Continuation

Contractor access must not remain authorized indefinitely solely because the account already exists.

---

# 41. Expired Access

Expired contractor access must be disabled or otherwise prevented from continued use.

---

# 42. Dormant Contractor Account

Dormant contractor accounts must be addressed under applicable account-security requirements.

---

# 43. Dormant Account Investigation

An account inactive for 30 days must be investigated to determine whether continued access remains required.

---

# 44. Dormant Account Disablement

An account inactive for 60 days must be disabled unless continued need is documented.

---

# 45. Access Approval

Contractor access requires appropriate business and technical approval.

---

# 46. Business Approval

The sponsor confirms the business need.

---

# 47. Technical Approval

Authorized IT personnel confirm:

- Appropriate system
- Appropriate environment
- Required privilege
- Technical feasibility
- Security restrictions

---

# 48. Privileged Approval

Privileged contractor access requires the additional approval required by [[PROC-002 Privileged Access Procedure]].

---

# 49. Production Approval

Production access must be explicitly approved.

Approval for development or test access is insufficient.

---

# 50. Provisioning

Only authorized personnel may provision contractor technical access.

---

# 51. Provisioning Verification

After provisioning, authorized personnel must verify that:

- Correct account was created.
- Correct environment was authorized.
- Privilege matches approval.
- Expiration is established.
- Unnecessary access was not granted.

---

# 52. Excess Access

Access discovered beyond the approved requirement must be corrected.

---

# 53. Repository Ownership

The authoritative Infinity source-code repository must remain under Dunder Mifflin control.

---

# 54. Repository Access

Contractor repository access must be individually attributable and limited to authorized work.

---

# 55. Repository Administration

Repository administrative privilege must be limited to personnel who require it.

---

# 56. Source-Code Availability

Dunder Mifflin must maintain access to current Infinity source code independently of the contractor.

---

# 57. Contractor Source Code

Contractor-developed source code for Infinity must be transferred to the Dunder Mifflin-controlled repository as required by the development process.

---

# 58. Contractor Work Product

Contractor-created:

- Source code
- Scripts
- Configuration
- Documentation
- Build information
- Deployment information
- Other contractual work product

must remain available to Dunder Mifflin.

---

# 59. Contractor-Owned Copy

A contractor-maintained working copy does not replace the requirement for Dunder Mifflin to control the authoritative source and required work product.

---

# 60. Source-Code Accountability

Contractor source-code changes must be attributable to the individual making the change.

---

# 61. Source-Code Change Control

Contractor source-code changes must follow [[PROC-018 Secure Change & Release Procedure]].

---

# 62. Development Environment

Contractor development activity must occur within the authorized development environment.

---

# 63. Production Development

Routine contractor development directly within production is prohibited.

---

# 64. Test Environment

Contractor test activity must remain within the approved test scope.

---

# 65. Production Data

Production information must not be copied unnecessarily into contractor development or test environments.

---

# 66. Sensitive Test Information

Sensitive information required for testing must receive protection appropriate to its classification.

---

# 67. Contractor Local Copies

Contractor personnel must not retain unnecessary local copies of:

- Source code
- Sensitive data
- Configuration
- Credentials
- Security documentation

outside authorized storage.

---

# 68. Removable Media

Use of removable media for contractor development or support must be authorized when required and appropriately protected.

---

# 69. Production Privilege

Privileged production access is restricted to authorized contractor personnel with a specific business need.

---

# 70. Controlled Production Workspace

Privileged Infinity contractor production or administrative work must be performed from the designated controlled workspace at Scranton Headquarters when required.

---

# 71. Workspace Purpose

The controlled workspace provides Dunder Mifflin greater control over:

- Physical access
- Administrative activity
- Company equipment
- Sensitive information
- Contractor support activity

---

# 72. Company-Controlled Workstation

Privileged contractor production administration must use an authorized Dunder Mifflin-controlled workstation when required by the access authorization.

---

# 73. Workstation Security

The workstation used for privileged contractor activity must comply with applicable endpoint and administrative security requirements.

---

# 74. General Contractor VPN

The Infinity contractor must not receive general Virtual Private Network (VPN) access for routine privileged production administration.

---

# 75. External Privileged Administration

Routine external remote privileged administration by the Infinity contractor is prohibited.

---

# 76. Emergency Remote Access

A genuine emergency may require an exceptional remote-support method when:

- Material business or security impact requires immediate action.
- Authorized onsite support cannot reasonably respond in time.
- The CIO or authorized delegate approves the exception.
- Access is limited to the emergency need.
- Activity is individually attributable where technically practical.
- Access is removed promptly after the emergency.
- The exception and activity are documented.

---

# 77. Emergency Remote Access Limitation

Emergency remote access does not create standing authorization for future remote privileged administration.

---

# 78. Emergency Remote Access Review

Following emergency remote privileged activity, IT must review:

- Authorization
- Individual involved
- Systems accessed
- Work performed
- Duration
- Changes made
- Access termination
- Required follow-up

---

# 79. Privileged Credentials

Privileged contractor credentials must be separate from ordinary user credentials where separate accounts are provided.

---

# 80. Privilege Escalation

A contractor must not increase its own privileges without appropriate Dunder Mifflin authorization.

---

# 81. Administrative Tools

Contractor use of administrative tools must be limited to authorized support activity.

---

# 82. Production Changes

Production changes performed by contractors must comply with [[PROC-018 Secure Change & Release Procedure]].

---

# 83. Change Authorization

Contractor authority to support Infinity does not authorize the contractor to independently approve production changes.

---

# 84. Contractor Self-Approval

A contractor must not be the sole authority for:

- Developing
- Approving
- Deploying
- Validating

the same material production change.

---

# 85. Small-Team Compensating Control

Where staffing limits complete Separation of Duties, Dunder Mifflin must provide reasonable compensating:

- Review
- Approval
- Verification

---

# 86. Change Accountability

Contractor changes must identify the responsible contractor personnel.

---

# 87. Emergency Change

Contractor emergency changes remain subject to applicable emergency change requirements.

---

# 88. Emergency Change Documentation

Emergency conditions do not eliminate requirements for:

- Authorization
- Change identification
- Reasonable testing
- Deployment record
- Verification
- Post-implementation review

---

# 89. Security Testing

Contractor-developed changes must receive security testing appropriate to their risk.

---

# 90. Contractor Testing Limitation

The contractor's own testing may support release decisions but does not eliminate Dunder Mifflin's right or responsibility to perform independent security assessment.

---

# 91. Application Security Assessment

Contractor-supported Infinity controls are subject to [[PROC-019 Application Security Assessment Procedure]].

---

# 92. Annual Infinity Assessment

Infinity must receive a security assessment at least annually.

---

# 93. Annual Penetration Testing

Infinity must receive application penetration testing at least annually.

---

# 94. Penetration Testing

Penetration testing must comply with [[STD-007 Penetration Testing Standard]].

---

# 95. Contractor Assessment Cooperation

The contractor must reasonably support authorized:

- Security assessment
- Vulnerability investigation
- Penetration testing
- Corrective action
- Retesting

related to Infinity.

---

# 96. Contractor Assessment Independence

The Infinity contractor must not be the sole source of assurance concerning the effectiveness of its own security controls.

---

# 97. Vulnerability Remediation

Contractor-supported remediation must comply with [[PROC-007 Vulnerability Remediation & Retest Procedure]].

---

# 98. Vulnerability Targets

Applicable remediation targets are:

| Severity | Target |
|---|---:|
| Critical | 7 days |
| High | 30 days |
| Moderate | 45 days |
| Low | 60 days |

---

# 99. Vulnerability Exception

A vulnerability that cannot be remediated within the required target must follow the approved exception and risk process.

---

# 100. Vulnerability Retesting

Material technical vulnerabilities must be retested after remediation where appropriate.

---

# 101. Remediation Closure

A vulnerability must not be closed solely because the contractor states that it has been corrected.

Appropriate validation is required.

---

# 102. Administrative Logging

Contractor administrative activity should generate sufficient logging to support reasonable accountability and investigation where technically available.

---

# 103. Security Monitoring

Contractor security-relevant activity is subject to applicable monitoring under [[PROC-008 Security Monitoring Procedure]].

---

# 104. Monitoring Scope

Monitoring may include:

- Authentication events
- Administrative activity
- Repository activity
- Material production changes
- Security-control failures
- Suspicious activity

where technically available and appropriate.

---

# 105. Monitoring Limitation

Monitoring requirements do not establish continuous personnel observation of all contractor activity.

---

# 106. Security Event

Suspicious contractor activity must be evaluated according to [[PROC-010 Security Event Escalation Procedure]].

---

# 107. Security Incident

Suspected contractor-related compromise may require activation of:

- [[PLN-001 Incident Response Plan]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-004 Data Exposure Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]

as appropriate.

---

# 108. Incident Notification

Applicable contractor agreements should require notification of material security incidents within 24 hours of discovery.

---

# 109. Incident Cooperation

The contractor must reasonably support authorized investigation of security incidents involving its:

- Personnel
- Accounts
- Systems
- Work product
- Access
- Activities

related to Dunder Mifflin.

---

# 110. Evidence Handling

Potential incident evidence must be handled according to [[PROC-011 Evidence Handling Procedure]].

---

# 111. Contractor Access Review

Contractor access must be periodically reviewed.

---

# 112. Review Frequency

Privileged contractor access must be reviewed at least quarterly.

Other contractor access must be reviewed according to applicable account and third-party requirements.

---

# 113. Access Review Scope

The review should determine whether:

- Sponsor remains valid.
- Business need continues.
- Individual remains assigned.
- Access remains appropriate.
- Privilege remains necessary.
- Production access remains justified.
- Expiration remains appropriate.

---

# 114. Review Evidence

Access-review evidence should identify:

- Accounts reviewed
- Reviewer
- Date
- Result
- Required changes
- Completion of required changes

---

# 115. Excess Privilege

Excess contractor privilege identified during review must be removed.

---

# 116. Unknown Account

A contractor account that cannot be tied to a valid individual, sponsor, or business need must be investigated promptly.

---

# 117. Unapproved Production Access

Unapproved contractor production access must be removed or otherwise contained and investigated.

---

# 118. Access Renewal

Access requiring continuation beyond the approved period must be renewed before expiration.

---

# 119. Renewal Limitation

Renewal must not be automatic.

---

# 120. Role Change

When contractor responsibilities change, existing access must be reviewed.

---

# 121. Reauthorization

Access no longer justified by the contractor's new responsibilities must be revoked before new access is authorized where applicable.

---

# 122. Contractor Personnel Replacement

Replacement contractor personnel must receive their own authorization and credentials.

Access must not simply be transferred from one individual to another.

---

# 123. Departure Notification

The contractor and company sponsor must promptly notify IT when an individual no longer requires access.

---

# 124. Access Termination

When contractor access is no longer required, applicable access must be revoked promptly.

---

# 125. Termination Scope

Termination must address as applicable:

- Repository access
- Development access
- Test access
- Production access
- Database access
- Administrative access
- VPN access
- Physical access
- Access cards
- Keys
- Smart cards
- Company credentials
- Company equipment

---

# 126. Access Removal Verification

IT must verify that applicable technical access was removed.

---

# 127. Physical Access Removal

Physical access removal must be coordinated with applicable facility-access procedures.

---

# 128. Credential Recovery

Company-issued authentication devices or credentials must be recovered, disabled, or otherwise invalidated as appropriate.

---

# 129. Company Equipment

Company equipment issued to contractor personnel must be recovered when no longer required.

---

# 130. Sensitive Information

Contractor personnel must return or appropriately dispose of Dunder Mifflin sensitive information when access ends according to applicable requirements.

---

# 131. Source-Code Retention

Contractor departure must not cause Dunder Mifflin to lose:

- Source code
- Repository history
- Build information
- Deployment information
- Configuration
- Documentation
- Recovery information

---

# 132. Contractor Transition

When contractor support ends, Dunder Mifflin must preserve information necessary for another qualified provider to assume support.

---

# 133. Transferability

Infinity must remain reasonably transferable to another qualified development or support provider.

---

# 134. Transferability Review

Infinity transferability must be reviewed at least annually.

---

# 135. Transferability Evidence

Transferability evidence may include:

- Current source code
- Repository access
- Build documentation
- Deployment procedures
- Architecture documentation
- Configuration information
- Required credentials
- Database information
- Recovery procedures
- Contractor work product
- Vendor information

---

# 136. Transferability Report

Transferability results are documented in [[RPT-004 Infinity Transferability Review]].

---

# 137. Contractor Dependency Finding

A material contractor dependency preventing reasonable support transfer must be documented as a finding.

---

# 138. Recovery Information

Contractor access to recovery information must be limited according to legitimate support need.

---

# 139. Recovery Independence

Infinity recovery must not depend solely on undocumented contractor knowledge.

---

# 140. Recovery Documentation

Recovery documentation must remain available to Dunder Mifflin independently of the contractor.

---

# 141. Qualified Replacement

Recovery documentation must be sufficient for a qualified IT professional unfamiliar with the environment to perform required recovery activities.

---

# 142. Contractor Recovery Activity

Contractor participation in recovery does not eliminate Dunder Mifflin's responsibility to maintain its own recovery capability and documentation.

---

# 143. Cloud Exit

Contractor support must not prevent Dunder Mifflin from executing [[PLN-004 Cloud Exit & Emergency Migration Plan]].

---

# 144. Contractor Records

Contractor access records may include:

- Access request
- Sponsor approval
- Confidentiality confirmation
- Account information
- Approved systems
- Approved environments
- Privilege
- Start date
- Expiration date
- Renewal
- Access reviews
- Emergency exceptions
- Termination evidence

---

# 145. Evidence Integrity

Contractor access evidence must reflect actual conditions.

Personnel must not:

- Backdate access approval.
- Invent access reviews.
- Conceal unauthorized access.
- Falsify termination records.
- Record access removal that did not occur.
- Alter evidence to make excessive access appear authorized.

---

# 146. Finding

A finding is a documented conclusion supported by evidence concerning whether a requirement, control, process, or expected outcome was satisfied.

---

# 147. Potential Findings

Potential contractor-access findings include:

- Missing sponsor
- Missing confidentiality obligation
- Unapproved account
- Excess privilege
- Expired account
- Unapproved production access
- Shared privileged credential
- Unauthorized remote privileged administration
- Missing access review
- Missing termination evidence
- Contractor-exclusive source code
- Contractor-exclusive recovery knowledge
- Uncontrolled production change
- Material transferability dependency

---

# 148. Finding Register

Material findings must be tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 149. Corrective Action

A material contractor-access finding must identify:

- Required corrective action
- Accountable owner
- Due date
- Validation method
- Retest requirement where applicable

---

# 150. Corrective Action Validation

A contractor-access finding must not be closed solely because an account-change request was submitted.

Actual access status must be appropriately validated.

---

# 151. Risk Relationship

This procedure primarily supports treatment of:

- R006 Infinity Compromise
- R010 Unauthorized / Excessive Access
- R011 Delayed Termination
- R012 Malicious Insider
- R018 Third-Party Technology Failure / Compromise
- R019 Infinity Contractor

---

# 152. R006 Infinity Compromise

R006 has:

- Inherent Risk: **16 High**
- Current Residual Risk: **12 High**
- Target Residual Risk: **8 Moderate**

Controlled contractor development and production access support R006 treatment.

---

# 153. R010 Unauthorized / Excessive Access

R010 has:

- Inherent Risk: **16 High**
- Current Residual Risk: **12 High**
- Target Residual Risk: **4 Low**

Least privilege, access approval, time limits, reviews, and environment-specific authorization support R010 treatment.

---

# 154. R011 Delayed Termination

R011 has:

- Inherent Risk: **16 High**
- Current Residual Risk: **8 Moderate**
- Target Residual Risk: **4 Low**

Prompt notification, access revocation, credential recovery, and termination verification support R011 treatment.

---

# 155. R012 Malicious Insider

R012 has:

- Inherent Risk: **15 High**
- Current Residual Risk: **10 High**
- Target Residual Risk: **5 Moderate**

Individual accountability, least privilege, controlled privileged access, review, logging, and Separation of Duties support R012 treatment.

---

# 156. R018 Third-Party Technology Failure / Compromise

R018 has:

- Inherent Risk: **12 High**
- Current Residual Risk: **8 Moderate**
- Target Residual Risk: **6 Moderate**

Third-party access governance, incident requirements, and support transferability support R018 treatment.

---

# 157. R019 Infinity Contractor

R019 has:

- Inherent Risk: **12 High**
- Current Residual Risk: **8 Moderate**
- Target Residual Risk: **4 Low**

---

# 158. R019 Control Relationship

This procedure supports R019 through:

- Company sponsorship
- Confidentiality
- Personnel identification
- Individual accounts
- Least privilege
- Time-limited authorization
- Separate production approval
- Controlled privileged activity
- No general contractor VPN for routine privileged administration
- Dunder Mifflin change approval
- Source-code ownership
- Access review
- Prompt termination
- Recovery independence
- Transferability

---

# 159. Metrics

Contractor-development access metrics may include:

- Active contractor accounts
- Privileged contractor accounts
- Accounts approaching expiration
- Expired accounts
- Dormant accounts
- Contractor access exceptions
- Emergency remote-access events
- Access-review completion
- Excess privilege findings
- Termination exceptions
- Unauthorized production-access events

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 160. Key Performance Indicators

Key Performance Indicators (KPIs) may include:

- Percentage of contractor accounts with valid sponsors
- Percentage of contractor accounts with current expiration dates
- Percentage of privileged contractor access reviewed quarterly
- Percentage of expired access disabled as required
- Percentage of contractor departures with verified access removal
- Percentage of identified excess access corrected

---

# 161. Key Risk Indicators

Key Risk Indicators (KRIs) may include:

- Contractor account without valid sponsor
- Expired contractor account remaining active
- Unauthorized production access
- Unapproved privileged access
- Repeated emergency remote access
- Shared privileged contractor credential
- Missing termination evidence
- Contractor-exclusive source code
- Contractor-exclusive recovery knowledge
- Material transferability dependency

---

# 162. Reporting

Material contractor-access issues must be reported according to significance.

---

# 163. Operational Reporting

Operational reporting may include:

- Expiring accounts
- Dormant accounts
- Access-review exceptions
- Required access removal
- Provisioning errors
- Contractor-access findings

---

# 164. Management Reporting

Management reporting may include:

- Privileged contractor access
- Repeated exceptions
- Overdue corrective actions
- Unauthorized production access
- Contractor dependency
- Transferability concerns

---

# 165. Executive Reporting

Executive reporting should be limited to material contractor risks requiring:

- Risk decision
- Significant corrective action
- Contractual action
- Resource decision
- Risk acceptance

---

# 166. Assessment

Contractor development access is subject to assurance under [[PRO-008 Security Assurance & Continuous Improvement Program]].

---

# 167. Assessment Methods

Assessment may use:

- Inspection
- Interviews
- Sampling
- Observation
- Technical Testing
- Independent Performance

---

# 168. Independent Performance

An assessor may independently perform an authorized contractor-access review.

For example:

1. Select an active contractor account.
2. Identify the individual.
3. Verify company sponsor.
4. Verify business need.
5. Verify approved environment.
6. Verify privilege.
7. Verify expiration date.
8. Verify production approval if applicable.
9. Verify recent access review where required.
10. Identify exceptions.
11. Document the result.

---

# 169. Termination Testing

An assessor may sample former contractor personnel and determine whether:

- Technical accounts were disabled.
- Repository access was removed.
- Production access was removed.
- Physical access was removed.
- Company credentials were recovered or invalidated.
- Company equipment was recovered where applicable.

---

# 170. Privileged Access Testing

An assessor may sample privileged contractor activity and determine whether:

- Access was approved.
- Activity was individually attributable.
- Access occurred through the required controlled method.
- Changes were authorized.
- Access remained within approved scope.

---

# 171. Emergency Remote Access Testing

Where emergency remote access occurred, an assessor may determine whether:

- Emergency need was documented.
- Appropriate authorization existed.
- Access was limited.
- Activity was attributable where technically practical.
- Access was removed after the emergency.
- Post-event review occurred.

---

# 172. Repository Testing

An assessor may determine whether:

- Dunder Mifflin controls the authoritative repository.
- Contractor access remains limited.
- Changes remain attributable.
- Current source code is available.
- Contractor work product remains under company control.

---

# 173. Control Effectiveness

Contractor-development access controls may be assessed as:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

---

# 174. Effectiveness Evidence

Control-effectiveness conclusions should consider:

- Access requests
- Sponsorship
- Confidentiality
- Account configuration
- Privilege
- Expiration
- Access reviews
- Repository records
- Production approvals
- Change records
- Emergency exceptions
- Termination evidence
- Assessment results
- Findings

---

# 175. Current and Proposed Controls

Contractor-access reporting must distinguish among:

- Current controls
- Partially implemented controls
- Planned controls
- Implemented controls awaiting validation
- Validated controls

---

# 176. No Premature Risk Credit

Current residual risk must not be reduced merely because:

- This procedure is approved.
- Smart-card authentication is planned.
- A contractor account review is scheduled.
- A new access restriction is documented.
- An account-removal request is open.
- A transferability improvement is planned.

Risk reduction requires implementation and appropriate validation.

---

# 177. Target Residual Risk

Target residual risk represents expected risk after planned treatment.

It is a prediction rather than proof of achieved risk reduction.

---

# 178. Validated Post-Treatment Risk

After contractor-access controls are implemented and validated, applicable risks may be reassessed.

Actual validated risk may be:

- Higher than target
- Equal to target
- Lower than target

---

# 179. Historical Integrity

The original May 2013 risk assessment must remain preserved.

Later validated assessments may establish a new current residual risk without rewriting the historical assessment.

---

# 180. Exceptions

Exceptions to this procedure must be:

- Documented
- Justified
- Risk evaluated
- Approved under appropriate authority
- Time-limited where practical
- Reviewed when conditions change

---

# 181. Exception Limitation

An exception must not be used to create indefinite contractor access without periodic review.

---

# 182. Procedure Review

This procedure must be reviewed when material changes affect:

- Infinity contractor support
- Contractor-access methods
- Development environments
- Production administration
- Authentication
- Source-code management
- Third-party requirements
- Transferability

---

# 183. Traceability

This procedure supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Contractor access is not demonstrated as controlled merely because a contractor has been approved to perform work.

Effective contractor access control requires:

**Business Need → Sponsor → Confidentiality → Authorization → Least Privilege → Time Limit → Controlled Use → Review → Revoke → Validate**

---

# 184. Related Artifacts

- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[RPT-004 Infinity Transferability Review]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[PRO-003 Identity and Access Management Program]]
- [[PRO-004 Vulnerability Management Program]]
- [[PRO-005 Security Operations Program]]
- [[PRO-006 Physical & Personnel Security Program]]
- [[PRO-007 Secure Software Development Lifecycle Program]]
- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-007 Penetration Testing Standard]]
- [[STD-009 Infinity Security Standard]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]
- [[PROC-008 Security Monitoring Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-014 Facility Access Procedure]]
- [[PROC-015 Visitor & Vendor Access Procedure]]
- [[PROC-016 Restricted Area Access Procedure]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-019 Application Security Assessment Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-004 Data Exposure Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

---

# 185. Review

This procedure must be reviewed:

- At least annually
- Following material Infinity contractor change
- Following material contractor-access method change
- Following significant unauthorized contractor access
- Following significant contractor-related security incident
- Following material assessment findings
- Following significant transferability concern

The IT & Information Security Manager coordinates review.

Material revisions require CIO approval.

---

# 186. Revision History

| Version | Date     | Description                                     | Approval |
| ------- | -------- | ----------------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Contractor Development Access Procedure | CIO      |