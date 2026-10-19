# STD-009 Infinity Security Standard

## Document Control

| Field | Value |
|---|---|
| Document ID | STD-009 |
| Title | Infinity Security Standard |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Infinity, Architecture, Development, or Security Change |

---

# 1. Purpose

This standard establishes mandatory security requirements for the Infinity application.

Infinity is a customer-facing application and requires security controls addressing:

- Internet exposure
- Application architecture
- Authentication
- Authorization
- Sensitive information
- Source code
- Application changes
- Contractor access
- Logging
- Vulnerability management
- Security testing
- Recovery
- Transferability

---

# 2. Scope

This standard applies to:

- Infinity web components
- Infinity application components
- Infinity database components
- Infinity source code
- Infinity source-code repositories
- Infinity development environments
- Infinity test environments
- Infinity production environments
- Infinity administrative functions
- Infinity application data
- Infinity documentation
- Infinity contractor activity
- Infinity security testing
- Infinity recovery information

---

# 3. Authority

This standard operates under:

- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[PRO-007 Secure Software Development Lifecycle Program]]

---

# 4. Supporting Standards

Infinity must comply with applicable requirements in:

- [[STD-001 Information Classification Standard]]
- [[STD-002 Network Security Standard]]
- [[STD-003 Endpoint Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[STD-007 Penetration Testing Standard]]

---

# 5. Infinity Ownership

Dunder Mifflin owns:

- Infinity
- Infinity source code
- Source-code repository
- Application data
- Documentation
- Backups
- Intellectual property
- Contractor work product created for Dunder Mifflin

---

# 6. Ownership Requirement

Infinity assets must remain under Dunder Mifflin control regardless of contractor involvement.

---

# 7. Authoritative Source Code

Dunder Mifflin must maintain access to and control of the authoritative Infinity source code.

---

# 8. Contractor-Controlled Repository

The authoritative Infinity repository must not exist solely under the control of the support contractor.

---

# 9. Security Objectives

Infinity security must support:

- Confidentiality
- Integrity
- Availability
- Accountability
- Recoverability
- Maintainability
- Transferability

---

# 10. Risk-Based Protection

Infinity security controls must reflect:

- Public Internet exposure
- Customer use
- Information sensitivity
- Business importance
- Application architecture
- Administrative privilege
- Contractor dependency
- Known vulnerabilities

---

# 11. Business Impact Analysis

Infinity has the following Business Impact Analysis (BIA) requirements:

| Requirement | Value |
|---|---:|
| Business Criticality | Moderate |
| Maximum Tolerable Downtime | 3 days |
| Recovery Time Objective | 24 hours |
| Recovery Point Objective | 4 hours |

---

# 12. BIA Authority

The authoritative Infinity recovery requirements are maintained in [[RPT-002 Business Impact Analysis]].

---

# 13. Recovery Requirement Limitation

An established Recovery Time Objective (RTO) or Recovery Point Objective (RPO) does not prove that Infinity can meet the requirement.

Recovery capability must be validated through appropriate testing.

---

# 14. Architecture

Infinity must maintain logical separation among:

1. Web tier
2. Application tier
3. Database tier

---

# 15. Web Tier

The web tier provides the public-facing interface required for authorized customer use.

---

# 16. Application Tier

The application tier must not be unnecessarily exposed directly to the public Internet.

---

# 17. Database Tier

The database tier must not be directly accessible from the public Internet.

---

# 18. Tier Communication

Communication among Infinity tiers must be limited to required application functions.

---

# 19. Unnecessary Services

Unnecessary network services must not be enabled on Infinity systems.

---

# 20. Public Exposure

Only services required to provide authorized Infinity functionality should be exposed to the public Internet.

---

# 21. Administrative Interfaces

Infinity administrative interfaces must not be unnecessarily exposed to the public Internet.

---

# 22. Infrastructure Administration

Infrastructure administration must use authorized management methods and must not rely on unnecessary public exposure of administrative services.

---

# 23. Firewall Protection

Infinity network traffic must be protected by applicable firewall controls.

---

# 24. Inbound Traffic

Unsolicited inbound traffic not required for authorized Infinity operation must be denied.

---

# 25. Network Security

Infinity network controls must comply with [[STD-002 Network Security Standard]].

---

# 26. Development Environment

Infinity development must occur in an environment logically separated from production.

---

# 27. Test Environment

Infinity testing must occur in an environment logically separated from production where practical.

---

# 28. Production Environment

The Infinity production environment is the authoritative live environment and requires stronger access restriction than ordinary development activity.

---

# 29. Environment Separation

Development, test, and production environments must not be treated as interchangeable.

---

# 30. Direct Production Development

Routine software development directly within production is prohibited.

---

# 31. Production Change

Production changes must follow [[PROC-018 Secure Change & Release Procedure]].

---

# 32. Emergency Production Change

An emergency may justify expedited production change procedures.

Emergency status does not eliminate requirements for:

- Authorization
- Documentation
- Reasonable testing
- Post-implementation verification
- Post-change review

---

# 33. Production Data in Development

Production information must not be copied unnecessarily into development or test environments.

---

# 34. Sensitive Test Information

Sensitive information used for development or testing must receive protection appropriate to its classification.

---

# 35. Test Data Minimization

Where practical, testing should use data that does not unnecessarily expose actual sensitive customer or business information.

---

# 36. Authentication

Infinity authentication must provide reasonable assurance that users are who they claim to be.

---

# 37. Administrative Authentication

Infinity administrative access must use individually attributable credentials.

---

# 38. Shared Administrative Credentials

Shared administrative credentials must not be used for routine Infinity administration when individual credentials can reasonably be provided.

---

# 39. Administrative Privilege

Administrative access must be limited to personnel with legitimate administrative responsibility.

---

# 40. Contractor Administrative Access

Contractor administrative access must be:

- Specifically authorized
- Individually attributable
- Limited to required systems and functions
- Limited to the authorized period
- Removed when no longer required

---

# 41. Authentication Secrets

Passwords and other authentication secrets must be protected against unnecessary disclosure.

---

# 42. Password Storage

Infinity must not store user passwords in recoverable plaintext form.

---

# 43. Password Handling

Application functions must not unnecessarily:

- Display passwords
- Log passwords
- Transmit passwords in plaintext across untrusted networks
- Include passwords in ordinary application output

---

# 44. Hard-Coded Credentials

Authentication secrets must not be unnecessarily hard-coded in Infinity source code.

---

# 45. Service Accounts

Infinity service accounts must:

- Have an identified purpose.
- Receive only required privileges.
- Be protected against unauthorized use.
- Be documented.
- Be reviewed when their function changes.

---

# 46. Authorization

Infinity must enforce authorization based on approved user roles and permitted functions.

---

# 47. Server-Side Authorization

Security-sensitive authorization decisions must be enforced by trusted application components.

---

# 48. User Interface Limitation

Hiding a function from the user interface does not constitute sufficient authorization control.

---

# 49. Privilege Enforcement

A user must not gain administrative or otherwise unauthorized capability merely by:

- Changing a request
- Modifying a parameter
- Directly requesting a hidden function
- Manipulating client-side controls

---

# 50. Customer Access

Customers must be limited to information and functionality they are authorized to use.

---

# 51. Administrative Functions

Administrative functions must be restricted from ordinary customer accounts.

---

# 52. Access Review

Infinity administrative and privileged access must be included in applicable access reviews.

---

# 53. Privileged Review

Privileged Infinity access must be reviewed at least quarterly.

---

# 54. Contractor Access Review

Contractor access must be reviewed according to [[PROC-004 Contractor Access Procedure]] and applicable third-party requirements.

---

# 55. Input Validation

Infinity must validate untrusted input before using it in security-sensitive processing.

---

# 56. Server-Side Input Validation

Security-sensitive validation must occur on trusted application components and must not depend solely on client-side validation.

---

# 57. Unexpected Input

Infinity should reject or safely handle input that:

- Violates expected format
- Violates expected length
- Contains invalid values
- Attempts unauthorized commands
- Could alter intended application behavior

---

# 58. Injection Protection

Infinity must use development practices intended to reduce injection vulnerabilities.

---

# 59. Database Interaction

Database interaction should use appropriately structured and parameterized methods where practical rather than constructing unsafe queries directly from untrusted input.

---

# 60. Output Handling

Application output must be handled in a manner that reduces unintended execution or disclosure.

---

# 61. Browser-Delivered Content

Content delivered to customer browsers must be appropriately handled to reduce application-generated scripting and content-injection risk.

---

# 62. Error Handling

Infinity must handle application errors without unnecessarily exposing sensitive technical information.

---

# 63. Public Error Messages

Public error messages must not unnecessarily reveal:

- Database details
- Internal file paths
- Authentication secrets
- Internal configuration
- Source-code information
- Detailed infrastructure information

---

# 64. Detailed Error Information

Detailed technical error information required for troubleshooting should be available only to authorized personnel.

---

# 65. Session Management

Infinity must manage authenticated sessions in a manner intended to reduce unauthorized session reuse.

---

# 66. Session Identifier Protection

Session identifiers must be protected against unnecessary disclosure.

---

# 67. Session Termination

Infinity should provide appropriate mechanisms for ending authenticated sessions.

---

# 68. Session Expiration

Authenticated sessions should expire after a reasonable period based on application use and risk.

---

# 69. Session Privilege Change

Where a material privilege change occurs, session behavior should not unnecessarily preserve access that the user is no longer authorized to exercise.

---

# 70. Sensitive Information

Infinity must protect sensitive information according to:

- [[POL-004 Information Classification & Handling Policy]]
- [[STD-001 Information Classification Standard]]

---

# 71. Payment Card Numbers

Infinity must not intentionally store full payment card numbers.

---

# 72. Payment Processing

Full payment card numbers are handled by the designated payment processor rather than stored by Dunder Mifflin.

---

# 73. Retained Payment Information

Dunder Mifflin may retain applicable:

- Payment token
- Card brand
- Last four digits
- Expiration information

required for legitimate business processing.

---

# 74. Payment Token Classification

Payment tokens are Confidential.

---

# 75. Payment Information Logging

Infinity logs must not contain full payment card numbers.

---

# 76. Sensitive Information Logging

Logs must not unnecessarily contain:

- Passwords
- Authentication secrets
- Full payment card numbers
- Other sensitive information unrelated to legitimate logging requirements

---

# 77. Data Minimization

Infinity must not collect or retain sensitive information solely because it may be useful at some unspecified future time.

---

# 78. Database Access

Direct database access must be limited to authorized:

- Application services
- Administrators
- Support personnel

with legitimate need.

---

# 79. Database Privilege

Database accounts must receive only the privileges required for their intended functions.

---

# 80. Database Administration

Administrative database access must be specifically authorized and individually attributable where practical.

---

# 81. Database Integrity

Suspected unauthorized or unexplained changes to application data must be investigated.

---

# 82. Data Corruption

Material Infinity data corruption must be addressed through applicable:

- Incident Response
- Recovery
- Reconciliation
- Backup restoration
- Integrity validation

processes.

---

# 83. Encryption in Transit

Sensitive Infinity information transmitted across untrusted networks must use appropriate encrypted communication.

---

# 84. Administrative Traffic

Administrative traffic across untrusted networks must not be transmitted in plaintext.

---

# 85. Cryptographic Configuration

Cryptographic settings must use approved, supported configurations appropriate to the system and information being protected.

---

# 86. Source-Code Repository

Infinity source code must be maintained in a controlled repository.

---

# 87. Repository Accountability

Repository activity must provide sufficient accountability to identify the individual making a source-code change.

---

# 88. Repository Authorization

Repository access must be based on legitimate:

- Development
- Support
- Review
- Administrative

responsibility.

---

# 89. Repository Privilege

Repository administrative privilege must be limited to personnel who require it.

---

# 90. Source-Code Confidentiality

Infinity source code must not be unnecessarily disclosed outside authorized personnel and service providers.

---

# 91. Source-Code Integrity

Unauthorized modification of Infinity source code must be prevented or detected through reasonable repository and change controls.

---

# 92. Source-Code Availability

Dunder Mifflin must maintain access to current source code required to:

- Maintain Infinity
- Correct defects
- Recover the application
- Transfer support

---

# 93. Source-Code Backup

The authoritative source code must be included in appropriate backup or repository-recovery arrangements.

---

# 94. Contractor Work Product

Contractor-developed source code, scripts, configuration, documentation, and related work product must be transferred to and remain available to Dunder Mifflin.

---

# 95. Change Accountability

Material Infinity changes must identify:

- Request
- Business purpose
- Developer
- Reviewer where required
- Testing
- Approval
- Deployment
- Verification

---

# 96. Code Review

Material or security-sensitive code changes must receive qualified review where practical.

---

# 97. Security-Sensitive Change

Security-sensitive changes include changes affecting:

- Authentication
- Authorization
- Session management
- Input handling
- Sensitive data
- Database access
- Administrative functionality
- External interfaces
- Security logging

---

# 98. Small-Team Compensating Control

Where complete development Separation of Duties is impractical, Dunder Mifflin must use reasonable compensating review or approval.

---

# 99. Threat Modeling

Material Infinity changes must receive lightweight threat modeling appropriate to the change.

---

# 100. Threat Modeling Method

STRIDE may be used to consider:

- Spoofing
- Tampering
- Repudiation
- Information Disclosure
- Denial of Service
- Elevation of Privilege

---

# 101. Threat Modeling Scope

Threat modeling must consider, as appropriate:

- Assets
- Data
- Entry points
- Trust boundaries
- External dependencies
- Privilege
- Significant threats
- Required controls

---

# 102. Higher-Risk Changes

Greater security review is required for changes involving:

- Authentication
- Authorization
- Internet exposure
- Sensitive information
- Major architecture
- Administrative functionality
- New external interfaces

---

# 103. Security Requirements Before Release

Identified material security requirements must be addressed before release or handled through an approved risk process.

---

# 104. Change Testing

Infinity changes must be tested before production release where practical.

---

# 105. Functional Testing

Testing must determine whether the intended application functionality operates as expected.

---

# 106. Security Testing

Security-sensitive changes must receive security testing appropriate to the affected functionality.

---

# 107. Security Test Methods

Testing may include:

- Manual review
- Code review
- Input testing
- Authentication testing
- Authorization testing
- Session testing
- Configuration review
- Vulnerability testing
- Penetration testing

---

# 108. Failed Security Test

A change that fails a material security requirement must not be treated as successfully tested merely because its business functionality works.

---

# 109. Release Approval

Production release requires appropriate approval after required review and testing.

---

# 110. Deployment Authorization

Only authorized personnel may deploy changes to the Infinity production environment.

---

# 111. Deployment Verification

Following deployment, authorized personnel must verify:

- Application availability
- Intended functionality
- Required configuration
- Security-sensitive functionality where applicable
- Absence of immediately apparent material failure

---

# 112. Rollback

Material Infinity changes must have a reasonable rollback approach where technically practical.

---

# 113. Failed Release

A release causing unacceptable security, integrity, availability, or functional impact must be corrected or rolled back as appropriate.

---

# 114. Emergency Change

Emergency change procedures must not be used solely to avoid normal review or testing.

---

# 115. Post-Emergency Review

Material emergency changes must receive post-implementation review.

---

# 116. Secure Configuration

Infinity systems must maintain documented security-relevant configuration appropriate to their functions.

---

# 117. Configuration Management

Configuration changes must follow:

- [[POL-007 Change & Configuration Management Policy]]
- [[STD-006 Secure Configuration Standard]]

---

# 118. Configuration Backup

Important Infinity configuration required for recovery must be:

- Backed up
- Documented
- Otherwise reproducible

as appropriate.

---

# 119. Unauthorized Configuration Change

Suspected unauthorized Infinity configuration changes must be investigated.

---

# 120. Server Security

Infinity servers must comply with [[STD-004 Server Security Standard]].

---

# 121. Patch Management

Infinity operating systems and supporting software must receive security updates according to applicable vulnerability and change-management requirements.

---

# 122. Application Components

Known material vulnerabilities affecting application components must be evaluated.

---

# 123. Unsupported Components

Unsupported or materially insecure components must be evaluated for:

- Upgrade
- Replacement
- Compensating control
- Risk acceptance

---

# 124. Component Dependencies

Important third-party application components and dependencies should be documented sufficiently to support maintenance and security response.

---

# 125. Vulnerability Management

Infinity vulnerabilities must be managed under [[PRO-004 Vulnerability Management Program]].

---

# 126. Vulnerability Assessment

Infinity must receive vulnerability assessment appropriate to its:

- Internet exposure
- Architecture
- Technology
- Business use

---

# 127. Vulnerability Prioritization

Vulnerabilities must be prioritized based on:

- Severity
- Exploitability
- Internet exposure
- Information sensitivity
- Business impact
- Existing controls

---

# 128. Remediation Targets

Applicable vulnerability-remediation targets are:

| Severity | Target |
|---|---:|
| Critical | 7 days |
| High | 30 days |
| Moderate | 45 days |
| Low | 60 days |

---

# 129. Remediation Exception

A vulnerability that cannot be remediated within the required target must follow the approved exception and risk process.

---

# 130. Vulnerability Retesting

Material technical vulnerabilities must be retested after remediation where appropriate.

---

# 131. Vulnerability Closure

A vulnerability must not be closed solely because:

- Code was changed.
- Configuration was changed.
- A ticket was marked complete.
- A developer states that the issue is fixed.

Closure requires appropriate validation.

---

# 132. Annual Security Assessment

Infinity must receive a security assessment at least annually.

---

# 133. Annual Assessment Scope

The annual security assessment must evaluate appropriate areas including:

- Architecture
- Internet exposure
- Authentication
- Authorization
- Session management
- Input handling
- Sensitive information
- Administrative access
- Configuration
- Logging
- Contractor access
- Development controls
- Vulnerability management
- Recovery
- Transferability

---

# 134. Annual Penetration Test

Infinity must receive application penetration testing at least annually.

---

# 135. Penetration Testing Authority

Penetration testing must comply with [[STD-007 Penetration Testing Standard]].

---

# 136. Test Authorization

Penetration testing must have documented authorization before testing begins.

---

# 137. Test Scope

The penetration-test scope must identify:

- Authorized application
- Authorized environment
- Authorized targets
- Test period
- Testing limitations
- Responsible personnel

---

# 138. Production Testing

Testing against production requires explicit authorization and appropriate safeguards against unnecessary:

- Service disruption
- Data modification
- Customer impact
- Business interruption

---

# 139. Penetration Test Evidence

Penetration-test evidence must identify:

- Scope
- Authorization
- Method
- Results
- Findings
- Remediation
- Retest where applicable

---

# 140. Penetration Test Findings

Material penetration-test findings must be tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 141. Penetration Test Chain

Infinity penetration testing supports:

**Penetration Test → Finding → Remediation → Retest → Control Effectiveness → R006 Risk Reassessment**

---

# 142. Assessment Independence

Security conclusions must not rely solely on the developer or contractor responsible for the control being evaluated when reasonable independent assessment is available.

---

# 143. Annual Assessment Limitation

An annual security assessment or penetration test does not prove that Infinity remains secure throughout the entire year.

---

# 144. Security Monitoring

Infinity must generate security-relevant information sufficient to support reasonable operational monitoring.

---

# 145. Security-Relevant Events

Infinity logging should capture appropriate events such as:

- Authentication failure
- Significant authorization failure
- Administrative activity
- Material application error
- Security-control failure
- Other suspicious activity

---

# 146. Log Accountability

Where technically practical, administrative events must identify the responsible account.

---

# 147. Log Time

Infinity systems should maintain reasonably consistent time to support event correlation and investigation.

---

# 148. Log Protection

Infinity logs must be protected against:

- Unauthorized modification
- Unnecessary deletion
- Unnecessary disclosure

---

# 149. Log Review

Infinity security-relevant logs must be included in applicable monitoring activity under [[PROC-008 Security Monitoring Procedure]].

---

# 150. No SIEM Requirement

This standard does not require a Security Information and Event Management (SIEM) platform.

Monitoring must remain appropriate to Dunder Mifflin's environment and available capabilities.

---

# 151. Security Event Escalation

Material Infinity security events must be escalated according to [[PROC-010 Security Event Escalation Procedure]].

---

# 152. Incident Response

Material Infinity security incidents must be handled under [[PLN-001 Incident Response Plan]].

---

# 153. Evidence Handling

Potential incident evidence must be handled according to [[PROC-011 Evidence Handling Procedure]].

---

# 154. Contractor Incident

A security incident involving the Infinity contractor may require [[PBK-005 Third-Party Incident Playbook]].

---

# 155. Unauthorized Access Incident

Suspected unauthorized Infinity access may require [[PBK-003 Unauthorized Access Playbook]].

---

# 156. Data Exposure Incident

Suspected Infinity data exposure may require [[PBK-004 Data Exposure Playbook]].

---

# 157. Contractor Classification

The Infinity contractor is a Critical third party.

---

# 158. Contractor Security Review

The Infinity contractor is subject to annual review under [[POL-008 Third-Party Security Policy]].

---

# 159. Contractor Sponsorship

Contractor personnel requiring Dunder Mifflin access must have an identified company sponsor.

---

# 160. Contractor Confidentiality

An appropriate Non-Disclosure Agreement (NDA) or equivalent enforceable confidentiality obligation must exist before contractor personnel receive sensitive Dunder Mifflin information.

---

# 161. Contractor Personnel Identification

Expected contractor personnel should be identified at least one business day before scheduled onsite activity where practical.

---

# 162. Emergency Personnel Exception

Emergency support may require contractor personnel who could not reasonably be identified one business day in advance.

The exception must be documented.

---

# 163. Contractor Physical Access

Contractor physical access must comply with:

- [[PROC-014 Facility Access Procedure]]
- [[PROC-015 Visitor & Vendor Access Procedure]]
- [[PROC-016 Restricted Area Access Procedure]]

---

# 164. Contractor Development Access

Contractor technical access must comply with [[PROC-020 Contractor Development Access Procedure]].

---

# 165. Contractor Access Duration

Contractor access must be time-limited.

Initial authorization may not exceed three months.

Continued access may be renewed for periods not exceeding six months when the business need continues.

---

# 166. Contractor Least Privilege

Contractor personnel must receive only the access required for authorized work.

---

# 167. Contractor Repository Access

Repository access must be individually attributable and limited to authorized personnel.

---

# 168. Contractor Production Access

Production access must require specific authorization.

Authorization for development access does not automatically authorize production access.

---

# 169. Privileged Contractor Work

Privileged contractor production or administrative work must be performed from the designated controlled workspace at Scranton Headquarters when required.

---

# 170. No General Contractor VPN

The Infinity contractor must not receive general VPN access for privileged production administration.

Routine external remote privileged administration is prohibited.

---

# 171. Contractor Technical Activity

Contractor technical activity remains subject to:

- Access control
- Change management
- Security testing
- Logging
- Incident Response
- Evidence requirements

---

# 172. Contractor Departure

When contractor personnel no longer require access:

- Repository access must be removed.
- Development access must be removed.
- Test access must be removed.
- Production access must be removed.
- Physical access must be removed.
- Company credentials must be recovered or disabled.

as applicable.

---

# 173. Third-Party Incident Notification

Applicable contractor agreements should require notification of material security incidents within 24 hours of discovery.

---

# 174. Contractor Replacement

Dunder Mifflin must be able to replace the support contractor without losing control of:

- Source code
- Documentation
- Configuration
- Credentials
- Application data
- Recovery information
- Intellectual property

---

# 175. Transferability

Infinity must remain reasonably transferable to another qualified development or support provider.

---

# 176. Annual Transferability Review

Infinity transferability must be reviewed at least annually.

---

# 177. Transferability Review

The review must consider whether Dunder Mifflin controls or can obtain:

- Current source code
- Repository access
- Build information
- Deployment procedures
- Architecture documentation
- Configuration information
- Required credentials
- Database information
- Recovery procedures
- Contractor work product
- Important vendor information

---

# 178. Transferability Report

Transferability results are documented in [[RPT-004 Infinity Transferability Review]].

---

# 179. Transferability Finding

A material dependency preventing reasonable transfer must be documented and addressed.

---

# 180. Recovery

Infinity must be included in applicable backup and recovery processes.

---

# 181. Backup Requirements

Infinity backup requirements must comply with [[PROC-012 Backup & Recovery Procedure]].

---

# 182. Recovery Documentation

Infinity recovery documentation must be sufficient for a qualified Information Technology professional unfamiliar with the environment to perform required recovery activities.

---

# 183. Contractor Recovery Dependency

Infinity recovery must not depend solely on undocumented contractor knowledge.

---

# 184. Recovery Documentation Control

Required recovery documentation must remain accessible to Dunder Mifflin independently of the Infinity contractor.

---

# 185. Recovery Testing

Infinity recovery capability must be tested according to applicable Disaster Recovery and backup requirements.

---

# 186. Recovery Measurement

Recovery testing must measure actual results against applicable:

- RTO
- RPO

when the test scope supports those measurements.

---

# 187. Recovery Evidence

Recovery evidence must reflect actual test activity and must not be manufactured to demonstrate compliance.

---

# 188. Cloud Dependency

Infinity recovery planning must consider relevant cloud-provider dependencies.

---

# 189. Cloud Exit

Infinity must be included in [[PLN-004 Cloud Exit & Emergency Migration Plan]] where applicable.

---

# 190. Manual Continuity

If Infinity is unavailable, affected business activity may use authorized manual continuity processes where applicable.

---

# 191. Manual Processing

Manual processing must comply with [[PROC-013 Manual Processing Procedure]].

---

# 192. Post-Recovery Reconciliation

Transactions handled manually during Infinity unavailability must be entered, reconciled, and verified according to applicable continuity procedures after service restoration.

---

# 193. Documentation

Infinity documentation must be maintained sufficiently to support:

- Operation
- Administration
- Development
- Security assessment
- Recovery
- Maintenance
- Contractor transition

---

# 194. Documentation Review

Material Infinity changes must include review of affected documentation.

---

# 195. Recovery Documentation Review

A significant technical or configuration change is not complete until affected recovery documentation has been reviewed and updated where necessary.

---

# 196. Documentation Accuracy

Documentation known to be materially inaccurate must not be represented as current.

---

# 197. Security Bug Reporting

Dunder Mifflin may accept legitimate external reports of Infinity security weaknesses.

---

# 198. Bug Bounty

The approved Infinity security bug bounty may provide rewards up to **$500** based on the validity and value of a reported issue.

---

# 199. Bug Bounty Scope

The bug bounty does not authorize:

- Destructive testing
- Theft of information
- Service disruption
- Social engineering
- Testing outside authorized scope
- Unnecessary access to customer information

---

# 200. Bug Report Lifecycle

Security bug reports should follow:

**Receive → Record → Validate → Prioritize → Remediate → Retest → Close**

---

# 201. Bug Report Evidence

Material bug reports must retain sufficient information to understand:

- Reported weakness
- Validation result
- Severity
- Corrective action
- Retest
- Closure

---

# 202. Finding

A finding is a documented conclusion supported by evidence concerning whether a requirement, control, process, or expected outcome was satisfied.

---

# 203. Infinity Findings

Potential findings include:

- Unauthorized Internet exposure
- Authentication weakness
- Authorization weakness
- Injection vulnerability
- Session weakness
- Sensitive-data exposure
- Excessive administrative access
- Excessive contractor access
- Uncontrolled source-code change
- Unsupported vulnerable component
- Missing recovery documentation
- Failed security testing
- Transferability dependency
- Overdue vulnerability remediation

---

# 204. Finding Register

Material findings must be tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 205. Corrective Action

A material finding must identify:

- Corrective action
- Accountable owner
- Due date
- Validation method
- Retest requirement where applicable

---

# 206. Finding Closure

A finding must not be closed solely because corrective work was reported as complete.

Closure requires evidence that the weakness was appropriately addressed.

---

# 207. Risk Relationship

This standard primarily supports treatment of:

- R006 Infinity Compromise
- R013 Administrative / Configuration Error
- R018 Third-Party Technology Failure / Compromise
- R019 Infinity Contractor
- R027 Backup Failure
- R028 Data Corruption

---

# 208. R006 Infinity Compromise

R006 has:

- Inherent Risk: **16 High**
- Current Residual Risk: **12 High**
- Target Residual Risk: **8 Moderate**

---

# 209. R006 Control Relationship

This standard supports R006 through:

- Layered application architecture
- Restricted Internet exposure
- Authentication
- Authorization
- Input validation
- Source-code control
- Change control
- Security testing
- Annual assessment
- Annual penetration testing
- Vulnerability remediation
- Contractor controls
- Incident Response
- Recovery

---

# 210. R013 Administrative / Configuration Error

R013 has:

- Inherent Risk: **16 High**
- Current Residual Risk: **12 High**
- Target Residual Risk: **6 Moderate**

Controlled configuration, testing, rollback, deployment verification, and documentation support R013 treatment.

---

# 211. R018 Third-Party Technology Failure / Compromise

R018 has:

- Inherent Risk: **12 High**
- Current Residual Risk: **8 Moderate**
- Target Residual Risk: **6 Moderate**

Contractor oversight and third-party dependency controls support R018 treatment.

---

# 212. R019 Infinity Contractor

R019 has:

- Inherent Risk: **12 High**
- Current Residual Risk: **8 Moderate**
- Target Residual Risk: **4 Low**

---

# 213. R019 Control Relationship

This standard supports R019 through:

- Dunder Mifflin ownership
- Contractor sponsorship
- Confidentiality
- Time-limited access
- Individual accountability
- Controlled onsite privileged activity
- No general contractor VPN for privileged production administration
- Source-code control
- Change control
- Security testing
- Documentation
- Annual transferability review

---

# 214. R027 Backup Failure

R027 has:

- Inherent Risk: **20 Critical**
- Current Residual Risk: **12 High**
- Target Residual Risk: **5 Moderate**

Backup, recovery documentation, and recovery testing support R027 treatment.

---

# 215. R028 Data Corruption

R028 has:

- Inherent Risk: **16 High**
- Current Residual Risk: **9 Moderate**
- Target Residual Risk: **4 Low**

Controlled changes, database restrictions, logging, backup, recovery, integrity validation, and reconciliation support R028 treatment.

---

# 216. Metrics

Infinity security metrics may include:

- Security-sensitive changes reviewed
- Application vulnerabilities identified
- Critical vulnerabilities overdue
- High vulnerabilities overdue
- Findings awaiting remediation
- Findings awaiting retest
- Annual security-assessment status
- Annual penetration-test status
- Contractor access exceptions
- Emergency changes
- Failed releases
- Recovery-test results
- Transferability findings

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 217. Key Performance Indicators

Key Performance Indicators (KPIs) may include:

- Percentage of material changes receiving required testing
- Percentage of security-sensitive changes receiving required review
- Percentage of vulnerabilities remediated within target
- Percentage of remediated findings successfully validated
- Completion of annual Infinity security assessment
- Completion of annual Infinity penetration testing
- Completion of annual Infinity transferability review

---

# 218. Key Risk Indicators

Key Risk Indicators (KRIs) may include:

- Overdue Critical vulnerability
- Overdue High vulnerability
- Unauthorized production change
- Unresolved Internet-facing vulnerability
- Excessive contractor access
- Contractor access outside approved scope
- Missing current source code
- Missing recovery documentation
- Failed penetration-test remediation
- Material transferability dependency
- Repeated emergency change

---

# 219. Assessment

Infinity controls are subject to assurance under [[PRO-008 Security Assurance & Continuous Improvement Program]].

---

# 220. Assessment Methods

Assessment may use:

- Inspection
- Interviews
- Sampling
- Code review
- Configuration review
- Technical testing
- Penetration testing
- Independent Performance

---

# 221. Independent Performance

An assessor may independently perform an authorized Infinity control procedure.

For example:

1. Select a material production change.
2. Obtain the change record.
3. Identify the developer.
4. Confirm required review.
5. Confirm testing.
6. Confirm approval.
7. Confirm deployment evidence.
8. Confirm post-deployment verification.
9. Identify exceptions.
10. Document the result.

---

# 222. Authorization Testing

An assessor may test authorized application functions to determine whether users can access functions or data outside their approved role.

Testing must remain within authorized scope.

---

# 223. Vulnerability Testing

An assessor may sample Infinity vulnerabilities and determine whether:

- Severity was assigned.
- Remediation occurred within target or had an approved exception.
- Corrective action was documented.
- Retesting occurred where required.
- Closure was supported by evidence.

---

# 224. Contractor Access Testing

An assessor may sample contractor accounts and determine whether:

- Sponsor remains valid.
- Business need remains.
- Access remains within authorized scope.
- Access duration remains valid.
- Production access was separately authorized.
- Expired access was removed.

---

# 225. Repository Testing

An assessor may determine whether:

- Dunder Mifflin controls the authoritative repository.
- Access is limited.
- Changes are attributable.
- Current source code remains available.
- Contractor work product remains under company control.

---

# 226. Recovery Testing

An assessor may evaluate Infinity recovery evidence to determine whether:

- The test actually occurred.
- Recovery time was measured.
- Recovery point was measured where applicable.
- Technical validation occurred.
- Security validation occurred.
- Business validation occurred where applicable.
- Findings were documented.

---

# 227. Transferability Testing

An assessor may determine whether a qualified replacement could reasonably obtain the information and access necessary to assume Infinity support.

---

# 228. Evidence Integrity

Assessment evidence must reflect actual conditions.

Personnel must not:

- Invent security testing.
- Backdate change approvals.
- Invent code reviews.
- Record a penetration test that did not occur.
- Invent vulnerability remediation.
- Conceal failed testing.
- Invent contractor-access reviews.
- Invent recovery results.
- Alter findings to make controls appear effective.

---

# 229. Control Effectiveness

Infinity controls may be assessed as:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

---

# 230. Effectiveness Evidence

Control-effectiveness conclusions should consider:

- Architecture
- Configuration
- Access records
- Change records
- Code-review evidence
- Security-test results
- Vulnerability records
- Penetration-test results
- Contractor-access records
- Source-code control
- Recovery evidence
- Transferability evidence
- Findings
- Corrective-action validation

---

# 231. Current and Proposed Controls

Infinity security reporting must distinguish among:

- Current controls
- Partially implemented controls
- Planned controls
- Implemented controls awaiting validation
- Validated controls

---

# 232. No Premature Risk Credit

Current residual risk must not be reduced merely because:

- This standard is approved.
- A control is planned.
- A penetration test is scheduled.
- A vulnerability fix is assigned.
- Contractor access restrictions are proposed.
- Recovery documentation is being developed.
- A corrective action is open.

Risk reduction requires implementation and appropriate validation.

---

# 233. Target Residual Risk

Target residual risk represents expected risk after planned treatment.

It is a prediction rather than proof of achieved risk reduction.

---

# 234. Validated Post-Treatment Risk

After Infinity controls are implemented and validated, applicable risks may be reassessed.

Actual validated risk may be:

- Higher than target
- Equal to target
- Lower than target

---

# 235. Historical Integrity

The original May 2013 risk assessment must remain preserved.

Later validated assessments may establish a new current residual risk without rewriting the historical assessment.

---

# 236. Exceptions

Exceptions to this standard must be:

- Documented
- Justified
- Risk evaluated
- Approved under appropriate authority
- Time-limited where practical
- Reviewed when conditions change

---

# 237. Exception Review

An Infinity security exception must not remain active solely because its expiration or corrective action was overlooked.

---

# 238. Standard Review

This standard must be reviewed when material changes affect:

- Infinity architecture
- Internet exposure
- Authentication
- Authorization
- Sensitive information
- Development practices
- Contractor access
- Application security testing
- Recovery
- Transferability

---

# 239. Traceability

This standard supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Infinity security is not demonstrated merely because a security standard exists.

Effective Infinity security requires:

**Requirement → Secure Design → Controlled Development → Review → Test → Authorized Release → Monitor → Assess → Remediate → Retest → Risk Reassessment**

---

# 240. Related Artifacts

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
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[PRO-002 Enterprise Security Architecture Program]]
- [[PRO-003 Identity and Access Management Program]]
- [[PRO-004 Vulnerability Management Program]]
- [[PRO-005 Security Operations Program]]
- [[PRO-007 Secure Software Development Lifecycle Program]]
- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[STD-001 Information Classification Standard]]
- [[STD-002 Network Security Standard]]
- [[STD-003 Endpoint Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[STD-007 Penetration Testing Standard]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]
- [[PROC-008 Security Monitoring Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-013 Manual Processing Procedure]]
- [[PROC-014 Facility Access Procedure]]
- [[PROC-015 Visitor & Vendor Access Procedure]]
- [[PROC-016 Restricted Area Access Procedure]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-019 Application Security Assessment Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-004 Data Exposure Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

---

# 241. Review

This standard must be reviewed:

- At least annually
- Following material Infinity architecture change
- Following significant application-security incident
- Following material development-process change
- Following material contractor-support change
- Following significant application-security assessment findings
- Following material recovery or transferability change

The IT & Information Security Manager coordinates review.

Material revisions require CIO approval.

---

# 242. Revision History

| Version | Date     | Description                        | Approval |
| ------- | -------- | ---------------------------------- | -------- |
| 1.0     | May 2013 | Initial Infinity Security Standard | CIO      |