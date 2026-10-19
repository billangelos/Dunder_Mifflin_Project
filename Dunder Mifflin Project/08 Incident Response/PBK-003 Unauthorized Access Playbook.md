# PBK-003 Unauthorized Access Playbook

## Document Control

| Field | Value |
|---|---|
| Document ID | PBK-003 |
| Title | Unauthorized Access Playbook |
| Version | 1.0 |
| Classification | Confidential |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following a Material Unauthorized-Access Incident |

---

# 1. Purpose

This playbook provides operational guidance for responding to suspected or confirmed unauthorized access to Dunder Mifflin systems, applications, information, accounts, or administrative functions.

It supplements:

- [[PROC-010 Security Event Escalation Procedure]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[PLN-001 Incident Response Plan]]

with focused response actions for unauthorized-access incidents.

---

# 2. Scope

This playbook applies to unauthorized or suspected unauthorized access involving:

- Employee accounts
- Contractor accounts
- Privileged accounts
- Active Directory
- Endpoints
- Servers
- Network infrastructure
- Virtual Private Network (VPN) access
- Cloud-hosted systems
- Business applications
- Infinity
- File resources
- Backup systems
- Databases
- Administrative interfaces
- Sensitive information

---

# 3. Unauthorized Access

Unauthorized access includes access that:

- Was never approved
- Exceeds approved business need
- Uses compromised credentials
- Uses another person's credentials
- Continues after authorization should have ended
- Bypasses required access controls
- Uses privilege beyond authorized scope
- Results from exploitation of a vulnerability or configuration weakness

---

# 4. Authority

This playbook operates under:

- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-009 Incident Response Policy]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[PLN-001 Incident Response Plan]]

---

# 5. Objectives

Unauthorized-access response must:

1. Stop or limit unauthorized access.
2. Protect affected accounts and systems.
3. Protect privileged credentials.
4. Determine reasonable incident scope.
5. Determine what access occurred.
6. Determine what actions were performed.
7. Identify affected information.
8. Identify persistence where practical.
9. Preserve useful evidence.
10. Restore authorized access securely.
11. Validate containment and recovery.
12. Identify corrective action.
13. Support risk reassessment where appropriate.

---

# 6. Response Lifecycle

The unauthorized-access response lifecycle is:

**Detect / Report → Triage → Protect → Preserve Evidence → Determine Scope → Contain → Investigate → Remove Unauthorized Access → Recover → Validate → Monitor → Close → Improve**

Activities may overlap when necessary.

---

# 7. Safety Priority

Human life and safety take priority over:

- Evidence
- Systems
- Operations
- Facilities
- Equipment
- Inventory
- Revenue

Emergency action must not be delayed solely to preserve electronic evidence.

---

# 8. Detection Sources

Potential unauthorized access may be identified through:

- Authentication logs
- User reports
- Administrator observations
- Security monitoring
- Unexpected account activity
- Account lockouts
- Privilege changes
- Unusual VPN activity
- Application logs
- Firewall information
- Business-process anomalies
- Third-party notification
- Physical-security reports
- Malware investigation
- Phishing investigation

---

# 9. Initial Triage

The responder should determine:

- Account involved
- User or owner
- Detection time
- Affected system
- Authentication method
- Access source
- Account privilege
- Information accessible
- Actions observed
- Whether access remains active
- Whether other accounts may be affected
- Whether immediate containment is required

---

# 10. Event Versus Incident

An unusual authentication event does not automatically establish unauthorized access.

Formal incident response is required when evidence indicates or reasonably suggests:

- Unauthorized successful authentication
- Unauthorized privilege use
- Unauthorized system access
- Unauthorized information access
- Unauthorized administrative activity
- Persistence
- Account compromise

---

# 11. Incident Classification

Formal incidents must be classified according to [[STD-008 Incident Classification & Escalation Standard]].

Severity must consider:

- Account privilege
- Systems accessed
- Information accessed
- Scope
- Persistence
- Business impact
- Actions performed
- Recovery impact

---

# 12. Immediate Escalation Conditions

Immediate escalation is required when unauthorized access involves or reasonably suggests:

- Domain Administrator compromise
- Significant privileged compromise
- Multiple Critical systems
- Significant Restricted information exposure
- Active widespread compromise
- Backup administrative compromise
- Destructive activity
- Severe business interruption

---

# 13. Initial Containment

When unauthorized access appears active, responders should take reasonable action to stop continued access.

Actions may include:

- Disabling an account
- Resetting credentials
- Terminating sessions where supported
- Restricting remote access
- Isolating an affected endpoint
- Blocking malicious network activity
- Restricting an administrative interface

---

# 14. Containment Must Not Wait for Perfect Certainty

Responders do not need complete attribution or full incident scope before taking reasonable containment action.

Waiting for complete certainty is inappropriate when continued access may materially increase harm.

---

# 15. Containment Proportionality

Containment must consider:

- Severity
- Business impact
- System criticality
- Information sensitivity
- Account privilege
- Evidence
- Potential spread
- Available recovery options

---

# 16. Account Disablement

An account should be disabled when continued access creates unacceptable risk.

The responder should document:

- Account
- Reason
- Time
- Person performing the action
- Related systems where known

---

# 17. Credential Replacement

Credentials reasonably believed to be compromised must be replaced.

Replacement should occur from a system reasonably believed to be trusted.

---

# 18. Session Termination

Where technically supported, active sessions associated with compromised accounts should be terminated.

Credential replacement alone may not terminate every existing authenticated session.

---

# 19. Privileged Access

Unauthorized privileged access requires heightened response.

Privileged accounts may include:

- Domain Administrator
- Server administrator
- Network administrator
- Backup administrator
- Security-tool administrator
- Cloud administrator
- Application administrator
- Database administrator

---

# 20. Separate Privileged Credentials

IT personnel use separate privileged credentials for administrative activity.

When an ordinary account belonging to an administrator is compromised, responders must determine whether separate privileged credentials may also have been exposed.

Compromise of the ordinary account does not automatically establish compromise of the privileged account.

---

# 21. Domain Administrator Compromise

Confirmed or strongly suspected Domain Administrator compromise requires immediate escalation.

The response must consider:

- Other Domain Administrator accounts
- Domain Controllers
- Privileged-group membership
- Authentication activity
- Account creation
- Persistence
- Credential replacement
- Enterprise-wide exposure

---

# 22. Standing Domain Administrator Access

Standing Domain Administrator access is restricted to:

- IT & Information Security Manager
- System Administrator

unless additional access is specifically authorized and documented.

Unexpected Domain Administrator membership requires immediate investigation.

---

# 23. Dedicated Administrative Workstations

Privileged activity should be performed from dedicated administrative workstations where established.

Unauthorized access involving an administrative workstation requires evaluation of credentials and systems administered from that workstation.

---

# 24. Remote Privileged Administration

External remote privileged administration is prohibited.

Privileged administration of significant production resources must occur through approved company-controlled methods and locations.

Ordinary authorized remote access, including Virtual Private Network (VPN) access, does not authorize privileged administration.

Contractor status, operational convenience, incident response, emergency conditions, or ordinary remote-access authorization do not create an exception to this prohibition.

Any external remote privileged administration requires immediate investigation as unauthorized activity.

---

# 25. VPN Access

Suspicious VPN activity should be evaluated for:

- Account
- Source
- Time
- Device
- Authentication
- Systems accessed
- Session duration
- Related activity

VPN is intended for authorized company laptops connecting from external or untrusted networks to nonpublic company resources.

---

# 26. Public Infinity Access

Normal public access to Infinity does not require VPN.

Unauthorized Infinity access must be evaluated according to:

- Account
- Application function
- Privilege
- Data accessed
- Administrative capability

---

# 27. Contractor Access

Unauthorized contractor access requires evaluation of:

- Contractor identity
- Sponsor
- Authorized systems
- Approved duration
- Privilege
- Access method
- Access location
- Information accessed

Contractor access is governed by [[PROC-004 Contractor Access Procedure]].

---

# 28. Expired Contractor Access

If contractor access remains active after authorized duration, responders must:

1. Determine whether access was used.
2. Restrict or disable unauthorized access.
3. Notify the sponsor.
4. Determine why expiration controls failed.
5. Evaluate corrective action.

---

# 29. Infinity Contractor

Unauthorized access involving the Infinity contractor requires heightened evaluation of:

- Source repository
- Development systems
- Production systems
- Administrative access
- Application configuration
- Customer information
- Database access

---

# 30. Infinity Contractor Remote Access

The Infinity contractor does not receive general VPN access for privileged production administration.

Privileged Infinity production or administrative work must occur through approved company-controlled methods and locations, including the designated contractor workspace at Scranton Headquarters where applicable.

External remote privileged administration is prohibited without exception.

Any external remote privileged production access requires immediate investigation as unauthorized activity.

---

# 31. Terminated Personnel

Access by terminated personnel requires immediate escalation and investigation.

Responders must determine:

- Termination date
- Required disablement time
- Actual account status
- Authentication after termination
- Systems accessed
- Information accessed
- Credentials or devices not recovered

---

# 32. Joiner-Mover-Leaver Failure

Unauthorized access caused by failed account lifecycle controls must be evaluated under [[PROC-001 Joiner-Mover-Leaver Procedure]].

The response should determine whether:

- Access was never removed.
- Old-role access remained.
- Termination notification was delayed.
- Account disablement failed.
- Physical credentials remained active.

---

# 33. Mover Access

Employees changing roles must have previous business access revoked before new-role access is authorized.

Unauthorized access caused by retained previous-role permissions requires investigation and corrective action.

---

# 34. Dormant Accounts

Accounts inactive for 30 days require investigation.

Accounts inactive for 60 days should be disabled unless documented business need justifies continued availability.

Unauthorized use of a dormant account requires investigation of the dormant-account control failure.

---

# 35. Shared Warehouse Windows Accounts

Shared Windows accounts may exist on warehouse workstations where operationally justified.

The shared workstation account must not be treated as reliable individual attribution for significant activity.

---

# 36. Significant WMS Transactions

Significant Warehouse Management System (WMS) transactions should require individual authentication and accountability.

Unauthorized WMS activity must consider the individual application identity rather than relying solely on the shared Windows workstation account.

---

# 37. Service Accounts

Unauthorized use of a service account requires evaluation of:

- Intended service
- Systems using the account
- Privilege
- Interactive-use restrictions
- Credential storage
- Recent changes
- Related applications

---

# 38. Interactive Service-Account Use

Unexpected interactive use of a service account should be investigated.

Service accounts should not become substitute personal administrator accounts.

---

# 39. Emergency Accounts

Unexpected use of emergency or break-glass access must be investigated under [[PROC-005 Emergency Access Procedure]].

The responder should determine:

- Who accessed the credential
- Why
- When
- What actions occurred
- Whether dual-custody requirements were followed where applicable

---

# 40. Emergency Credential Protection

If an emergency credential may have been exposed, it must be protected or replaced as appropriate after required evidence is preserved.

---

# 41. Account Ownership

The responder must identify the expected owner or responsible party for each affected account.

Unknown ownership is itself a control concern requiring investigation.

---

# 42. Preserve Evidence

Useful evidence should be preserved before destructive remediation where practical.

Evidence handling must follow [[PROC-011 Evidence Handling Procedure]].

---

# 43. Evidence Sources

Unauthorized-access evidence may include:

- Authentication logs
- Active Directory records
- VPN records
- Application logs
- Server logs
- Firewall information
- Account configuration
- Group membership
- Email
- Files
- Administrator records
- User reports
- Third-party reports
- Physical access records

---

# 44. Authentication Evidence

Authentication evidence should be evaluated for:

- Successful logins
- Failed logins
- Account lockouts
- Password changes
- Source systems
- Times
- Privileged authentication
- Unexpected access patterns

---

# 45. Time Accuracy

Responders must consider possible:

- Time-zone differences
- Clock differences
- Logging gaps
- Incomplete records

Unknown times must not be invented.

---

# 46. Evidence Before Account Modification

Where practical, relevant account information should be preserved before:

- Account deletion
- Group-membership removal
- Permission removal
- Major account modification

Immediate containment may take priority when waiting creates unacceptable risk.

---

# 47. Evidence Before System Changes

Where practical, relevant evidence should be preserved before:

- Reimaging
- Major configuration replacement
- Log clearing
- Application rebuilding
- System retirement

---

# 48. Cryptographic Hashing

Where practical and useful, significant digital evidence should receive a SHA-256 cryptographic hash.

---

# 49. Incident Timeline

Significant unauthorized-access incidents must maintain a timeline sufficient to reconstruct material activity.

The timeline may include:

- Initial unauthorized activity
- Detection
- Authentication
- Privilege changes
- Access to systems
- Evidence collection
- Containment
- Credential replacement
- Recovery
- Return to service

---

# 50. Scope Determination

The responder must determine reasonable incident scope.

Scope may include:

- Accounts
- Endpoints
- Servers
- Applications
- Network devices
- VPN
- Cloud systems
- Infinity
- Databases
- Backup systems
- Information
- Business processes

---

# 51. Scope Questions

The investigation should determine:

- Which account was used?
- How was access obtained?
- When did unauthorized access begin?
- What systems were accessed?
- What information was accessible?
- What information was actually accessed where evidence permits?
- What actions were performed?
- Was privilege increased?
- Was persistence established?
- Were additional accounts affected?
- Is access continuing?

---

# 52. Do Not Assume the First Account Is the Full Scope

The first compromised account may be only one part of the incident.

Responders should evaluate whether the attacker:

- Obtained additional credentials
- Created accounts
- Changed permissions
- Added group memberships
- Accessed other systems
- Established persistence

---

# 53. Initial Access

Where evidence permits, responders should determine how unauthorized access was obtained.

Possible methods include:

- Phishing
- Stolen credentials
- Credential reuse
- Malware
- Excessive permissions
- Unremoved access
- Vulnerability exploitation
- Configuration weakness
- Contractor misuse
- Insider misuse

---

# 54. Phishing Relationship

If unauthorized access resulted from phishing or credential theft, response must also follow [[PBK-001 Phishing & Credential Compromise Playbook]].

---

# 55. Malware Relationship

If unauthorized access involved malware, response must also follow:

- [[PROC-009 Malware Response Procedure]]
- [[PBK-002 Malware & Ransomware Playbook]]

---

# 56. Vulnerability Exploitation

If unauthorized access resulted from vulnerability exploitation, remediation must follow:

- [[PRO-004 Vulnerability Management Program]]
- [[PROC-007 Vulnerability Remediation & Retest Procedure]]

Stopping the unauthorized session does not remediate the vulnerability.

---

# 57. Configuration Weakness

If unauthorized access resulted from configuration weakness, remediation must consider:

- [[POL-007 Change & Configuration Management Policy]]
- [[STD-006 Secure Configuration Standard]]

The same weakness should be evaluated on similar systems.

---

# 58. Excessive Access

If the account had permissions exceeding business need, responders must determine:

- How access was authorized
- Whether access should have been removed
- Whether other accounts have similar excessive permissions
- Whether access-review controls failed

---

# 59. Access Review

Significant unauthorized-access incidents should trigger a targeted access review under [[PROC-003 Access Review Procedure]].

The review should include affected:

- Accounts
- Groups
- Privileges
- Applications
- Sensitive resources

---

# 60. Privilege Escalation

Responders must determine whether the unauthorized user increased privilege.

Indicators may include:

- New group membership
- New administrator account
- Changed permissions
- Modified service accounts
- Administrative configuration changes

---

# 61. Unauthorized Account Creation

Unexpected account creation associated with an incident requires immediate investigation.

The account should be disabled or otherwise contained when unauthorized.

---

# 62. Unauthorized Group Membership

Unexpected membership in a privileged or sensitive group must be:

- Documented
- Removed when unauthorized
- Investigated for related activity

---

# 63. Persistence

Responders should evaluate whether continued access was established through:

- Additional accounts
- Privilege changes
- Service accounts
- Scheduled activity
- Application changes
- Malware
- Remote-access changes
- Configuration changes

within available technical capability.

---

# 64. Active Directory Scope

Active Directory investigation may include:

- Authentication
- Account creation
- Account enablement
- Group membership
- Password changes
- Privileged activity
- Domain Controller activity

---

# 65. Domain Controller Scope

Unauthorized access to a Domain Controller requires heightened response.

Dunder Mifflin maintains at least two cloud-hosted Domain Controller/authentication servers within the same overall cloud provider with reasonable failure-domain separation.

Compromise of one Domain Controller requires evaluation of the other.

---

# 66. Server Scope

Server investigation should consider:

- Authentication
- Administrative access
- Services
- Files
- Configuration
- Logs
- Application access
- Related accounts

---

# 67. Endpoint Scope

Endpoint investigation should consider:

- User activity
- Administrative activity
- Malware
- Stored information
- Authentication
- Configuration changes
- Remote access

---

# 68. Network Infrastructure Scope

Unauthorized network-device access requires evaluation of:

- Firewall configuration
- Router configuration
- Administrative accounts
- Remote-management settings
- Network exposure
- Configuration backups
- Related network devices

---

# 69. Internet-Facing Administration

Internal and administrative services must not be exposed directly to the Internet unless the service is specifically intended and approved for public access.

This requirement does not authorize external remote privileged administration, which is prohibited.

Evidence of unauthorized access through an exposed administrative interface requires investigation of:

- Exposure
- Configuration
- Change history
- Similar systems

---

# 70. Cloud Scope

Unauthorized cloud access requires evaluation of:

- Administrative accounts
- Hosted systems
- Provider logs
- Authentication
- Configuration
- Information
- Recovery capability

---

# 71. Infinity Scope

Unauthorized Infinity access requires evaluation of:

- Web tier
- Application tier
- Database tier
- Administrative accounts
- Customer information
- Application configuration
- Source code
- Contractor access
- Order-processing impact

---

# 72. Infinity Tier Separation

Infinity is designed with logical:

**Web → Application → Database**

separation.

The database is not intended to be directly Internet accessible.

Unauthorized movement between tiers requires investigation.

---

# 73. Infinity Source Repository

Unauthorized access to the Infinity source repository requires evaluation of:

- Source-code access
- Modification
- Credentials
- Repository history
- Malicious-code introduction
- Development integrity

---

# 74. Database Access

Unauthorized database access requires heightened evaluation because it may affect:

- Confidentiality
- Integrity
- Application operation
- Customer information
- Business records

---

# 75. File Resource Access

Unauthorized access to company file resources requires evaluation of:

- Files accessed
- Information classification
- Copying
- Modification
- Deletion
- Account used
- Scope

---

# 76. Backup Access

Unauthorized access to backup systems requires heightened response.

Responders must determine whether the unauthorized party could have:

- Viewed backup data
- Deleted backups
- Modified backups
- Changed retention
- Altered configuration
- Affected recovery capability

---

# 77. Information Classification

Affected information must be evaluated according to:

- Public
- Internal
- Confidential
- Restricted

as defined by [[STD-001 Information Classification Standard]].

---

# 78. Data Exposure

If unauthorized access may have resulted in information exposure, response must also follow [[PBK-004 Data Exposure Playbook]].

---

# 79. Access Does Not Automatically Prove Acquisition

Evidence that an unauthorized party could access information does not automatically prove that the information was copied or exfiltrated.

The incident record must distinguish:

- Accessible
- Viewed where known
- Modified
- Copied where known
- Exfiltrated where supported
- Unknown

---

# 80. Data Integrity

Responders must determine whether unauthorized access resulted in:

- Record modification
- File modification
- Configuration change
- Order changes
- Inventory changes
- Financial changes
- Account changes
- Data deletion

---

# 81. Business Record Integrity

Unauthorized modification of significant business records requires coordination with the responsible business owner.

The business owner should support reconciliation and validation.

---

# 82. Financial Systems

Unauthorized access affecting financial processes requires Finance involvement when it may affect:

- Accounting
- Payments
- Vendor information
- Payroll
- Banking instructions
- Financial records

---

# 83. Business Email Compromise

If unauthorized email access supports fraud or impersonation, response must also follow [[PBK-001 Phishing & Credential Compromise Playbook]].

Finance must be involved when financial activity is implicated.

---

# 84. Insider Access

Unauthorized access may involve a legitimate employee using authorized credentials outside approved business need.

Such activity may require coordination with:

- Human Resources
- Legal/Compliance
- Business management
- Information Security

---

# 85. Authorized Access Versus Malicious Use

Possession of valid credentials does not establish authorized activity.

Responders must distinguish between:

- Authorized access
- Excessive access
- Unauthorized use
- Malicious use of legitimate access

---

# 86. Personnel Investigation

Information Security must provide technical facts and evidence.

Human Resources and management determine appropriate personnel action.

---

# 87. Third-Party Access

Unauthorized third-party access requires evaluation of:

- Provider
- Authorized scope
- Account
- Connection method
- Information
- Privilege
- Contractual requirements
- Other company exposure

---

# 88. Third-Party Incident

When unauthorized access originates through a third-party compromise, response must also follow [[PBK-005 Third-Party Incident Playbook]].

Dunder Mifflin must determine its own impact.

---

# 89. Third-Party Confidentiality

Nonemployees receiving sensitive incident information or system access must have an enforceable Non-Disclosure Agreement (NDA) or equivalent confidentiality obligation before access.

The requirement is based on access and information sensitivity rather than vendor title.

---

# 90. External DFIR Assistance

External Digital Forensics and Incident Response (DFIR) assistance may be appropriate for:

- Domain compromise
- Complex privileged compromise
- Significant persistence
- Significant information exposure
- Complex forensic requirements
- Broad unknown scope

---

# 91. Proposed DFIR Capability

A retained DFIR provider is a proposed Critical Security Response Provider capability.

It must not receive current residual-risk or control-effectiveness credit until implemented and available.

---

# 92. Eradication

Eradication removes unauthorized access and associated persistence.

Actions may include:

- Credential replacement
- Account disablement
- Unauthorized-account removal
- Privilege removal
- Group-membership correction
- Malware removal
- Configuration correction
- Vulnerability remediation
- System rebuilding

---

# 93. Account Deletion

Unauthorized accounts may be deleted after appropriate evidence is preserved.

Immediate disablement is normally preferred during active investigation when preservation of account information remains useful.

---

# 94. Permission Correction

Unauthorized or excessive permissions must be removed.

The responder should verify that the change actually took effect.

---

# 95. Credential Recovery

Affected credentials must be replaced or otherwise protected according to incident scope.

The organization should avoid unnecessary enterprise-wide credential changes unless evidence or risk justifies them.

---

# 96. Trusted Recovery System

Sensitive credential replacement should be performed from a trusted system.

A system still reasonably suspected of compromise must not be relied upon to establish new privileged credentials when a safer alternative exists.

---

# 97. System Recovery

A compromised system may require:

- Configuration correction
- Malware removal
- Reimaging
- Rebuilding
- Patch installation
- Application repair
- Data restoration

The required action depends on the degree of lost trust.

---

# 98. Recovery From Backup

Where unauthorized activity affected system or data integrity, recovery may require validated backup data.

Recovery must follow [[PROC-012 Backup & Recovery Procedure]].

---

# 99. Recovery Validation

Recovery is not complete merely because authentication succeeds or a system starts.

Validation should determine whether:

- Unauthorized access has stopped.
- Credentials are protected.
- Permissions are correct.
- Unauthorized accounts are removed or disabled.
- Persistence is addressed.
- Security configuration is restored.
- Data integrity is acceptable.
- Logging is operating.

---

# 100. Business Validation

When business data or application functionality was affected, the responsible business owner or qualified representative should validate restored business operation.

---

# 101. Return to Service

A system or account should return to normal use when there is reasonable confidence that:

- Immediate unauthorized access is contained.
- Required credentials are protected.
- Required permissions are corrected.
- Material persistence is addressed.
- Required remediation is complete or appropriately mitigated.
- Recovery is validated.

---

# 102. Heightened Monitoring

Following significant unauthorized access, affected accounts and systems may receive heightened monitoring.

Monitoring should focus on relevant indicators such as:

- Authentication
- Privilege changes
- New accounts
- Administrative activity
- Related network activity

---

# 103. Recurring Unauthorized Access

Repeated unauthorized activity after containment may indicate:

- Compromised credentials
- Persistence
- Additional compromised accounts
- Unaddressed vulnerability
- Incomplete remediation
- Incorrect scope

The incident must be reevaluated.

---

# 104. Failed Containment

If unauthorized access continues after containment:

1. Document the failure.
2. Reevaluate scope.
3. Reevaluate credentials.
4. Investigate persistence.
5. Escalate severity where appropriate.
6. Select additional containment measures.

---

# 105. Incident Communications

Communications must be:

- Timely
- Accurate
- Fact based
- Limited to legitimate need
- Appropriate to the recipient

---

# 106. Management Notification

Management notification should communicate available:

- Severity
- Accounts affected
- Systems affected
- Privilege involved
- Information affected
- Containment status
- Business impact
- Major uncertainties
- Decisions required

---

# 107. Executive Notification

Severity 1 incidents require prompt CEO notification.

Executive reporting should focus on:

- Enterprise impact
- Significant information exposure
- Business interruption
- Privileged compromise
- Recovery concerns
- Enterprise risk
- Decisions required

---

# 108. Legal and Compliance

Legal/Compliance should be involved when unauthorized access may create material:

- Legal exposure
- Contractual obligations
- Privacy concerns
- Notification requirements
- Evidence-preservation requirements
- Law-enforcement considerations

---

# 109. External Communication

Technical personnel must not independently:

- Issue public statements
- Notify customers of incident conclusions
- Admit liability
- Make regulatory statements

without authorization.

---

# 110. Incident Closure

An unauthorized-access incident may be closed when:

- Active unauthorized access has been addressed.
- Required containment is complete.
- Reasonable scope has been determined.
- Affected credentials are protected.
- Unauthorized accounts and privileges are addressed.
- Persistence is reasonably addressed.
- Required recovery is complete.
- Material evidence is preserved.
- Corrective actions are documented.
- Remaining risk is understood.

---

# 111. Closure Does Not End Corrective Action

Incident closure does not automatically close:

- Access-review findings
- Vulnerability findings
- Configuration findings
- Corrective actions
- Risk treatments
- Personnel actions
- Third-party remediation

These remain tracked through their appropriate processes.

---

# 112. Lessons Learned

Severity 1 and significant Severity 2 unauthorized-access incidents require a documented lessons-learned review.

The review should consider:

- Initial access
- Detection
- Escalation
- Scope
- Privilege
- Persistence
- Containment
- Evidence
- Recovery
- Control performance

---

# 113. Root Cause

Where evidence permits, likely root cause should be identified.

Examples include:

- Credential compromise
- Phishing
- Malware
- Excessive access
- Delayed termination
- Vulnerability
- Configuration weakness
- Contractor access failure
- Insider misuse

---

# 114. Contributing Factors

Contributing factors may include:

- Excessive privilege
- Incomplete access review
- Dormant account
- Weak monitoring
- Incomplete logging
- Delayed escalation
- Missing documentation
- Inadequate account ownership

---

# 115. Broader Access Review

A significant incident may require review beyond the directly affected account.

The review may include:

- Similar accounts
- Similar roles
- Privileged groups
- Contractor accounts
- Dormant accounts
- Application access
- Related systems

---

# 116. Corrective Action

Material deficiencies must identify:

- Deficiency
- Accountable owner
- Required action
- Due date
- Validation method

Material corrective actions are tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 117. Corrective-Action Validation

Corrective action is not complete merely because the action was reported as finished.

Required validation must determine whether the intended condition was achieved.

---

# 118. R005 Relationship

R005 addresses password and authentication weakness.

Inherent risk is:

**16 High**

Current residual risk is:

**12 High**

Target residual risk after proposed treatment is:

**4 Low**

---

# 119. R010 Relationship

R010 addresses unauthorized or excessive access.

Inherent risk is:

**16 High**

Current residual risk is:

**12 High**

Target residual risk after proposed treatment is:

**4 Low**

---

# 120. R011 Relationship

R011 addresses delayed termination.

Inherent risk is:

**16 High**

Current residual risk is:

**8 Moderate**

Target residual risk after proposed treatment is:

**4 Low**

---

# 121. R012 Relationship

R012 addresses malicious insider activity.

Inherent risk is:

**15 High**

Current residual risk is:

**10 High**

Target residual risk after proposed treatment is:

**5 Moderate**

Authorized credentials do not make malicious activity authorized.

---

# 122. R015 Relationship

R015 addresses shared warehouse accounts.

Inherent risk is:

**12 High**

Current residual risk is:

**9 Moderate**

Target residual risk after proposed treatment is:

**4 Low**

Individual accountability for significant WMS transactions is an important treatment component.

---

# 123. Other Risk Relationships

This playbook also supports response for:

- R001 Phishing / Credential Compromise
- R002 Business Email Compromise
- R006 Infinity Application Compromise
- R007 Internet Infrastructure Compromise
- R009 Sensitive Information Theft / Extortion
- R014 Lost Device
- R018 Third-Party Technology Failure / Compromise
- R019 Infinity Contractor Dependency / Compromise
- R027 Backup / Recovery Failure
- R028 Data Corruption
- R029 Vendor Fraud
- R030 Sales Fraud
- R031 Payroll Fraud

---

# 124. Current and Proposed Controls

Response records must distinguish among:

- Current controls
- Partially implemented controls
- Planned controls
- Implemented controls awaiting validation
- Validated controls

---

# 125. No Premature Risk Credit

Current residual risk must not be reduced merely because:

- This playbook exists.
- Smart-card multifactor authentication is planned.
- Access reviews are planned or scheduled.
- New monitoring is proposed.
- A retained DFIR provider is proposed.
- Corrective action has been assigned.

Risk reduction requires implementation and appropriate validation.

---

# 126. Risk Reassessment

Unauthorized-access incidents may require reassessment when evidence demonstrates:

- Greater likelihood
- Greater impact
- Access-control failure
- Authentication weakness
- Unexpected privilege
- New attack path
- Improved control effectiveness

Historical May 2013 risk results must remain preserved.

---

# 127. Operational Metrics

Operational metrics may include:

- Unauthorized-access incidents
- Privileged-access incidents
- Domain Administrator incidents
- Compromised accounts
- Unauthorized contractor access
- Terminated-account access
- Dormant-account incidents
- Unauthorized privilege changes
- Repeat unauthorized-access incidents

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 128. Key Performance Indicators

Key Performance Indicators (KPIs) may include:

- Percentage of confirmed unauthorized-access incidents receiving documented containment
- Percentage of significant incidents with documented scope
- Percentage of affected credentials receiving required protection
- Percentage of unauthorized privileges removed and verified
- Percentage of significant incidents receiving required access review
- Percentage of corrective actions completed and validated

---

# 129. Key Risk Indicators

Key Risk Indicators (KRIs) may include:

- Increasing unauthorized-access incidents
- Privileged-account compromise
- Unexpected Domain Administrator membership
- Terminated accounts remaining active
- Dormant accounts used successfully
- Repeated contractor-access violations
- Repeat unauthorized access after containment
- Significant access-review deficiencies

---

# 130. Metric Interpretation

Unauthorized-access metrics must be interpreted in context.

An increase may indicate:

- Increased attack activity
- Improved detection
- Better reporting
- Expanded monitoring

Incident count alone does not establish whether risk increased or decreased.

---

# 131. Playbook Exercises

This playbook should be periodically exercised.

Scenarios may include:

- Compromised ordinary user account
- Compromised administrator account
- Unexpected Domain Administrator activity
- Terminated employee access
- Expired contractor access
- Unauthorized Infinity administrative access
- Unauthorized backup administration

---

# 132. Exercise Objectives

Exercises should evaluate whether responders can:

- Identify the affected account
- Determine privilege
- Contain access
- Protect credentials
- Preserve evidence
- Determine scope
- Identify persistence
- Coordinate recovery
- Identify corrective action

---

# 133. Exercise Safety

Exercises must not unnecessarily:

- Alter production accounts
- Disable Critical services
- Expose sensitive information
- Create uncontrolled administrative access
- Disrupt normal business

---

# 134. Playbook Assessment

Assessment may determine whether:

- Unauthorized access is identified.
- Appropriate escalation occurs.
- Accounts are contained.
- Privileged exposure is evaluated.
- Scope is investigated.
- Evidence is preserved.
- Permissions are corrected.
- Recovery is validated.
- Significant incidents receive corrective action.

---

# 135. Assessment Methods

Assessment methods may include:

- Inspection
- Observation
- Interviews
- Sampling
- Exercises
- Technical Testing
- Reconciliation
- Independent Performance

---

# 136. Independent Performance

An assessor may independently perform selected response steps using an authorized scenario.

For example, the assessor may:

1. Receive a simulated unauthorized-access alert.
2. Identify the account and privilege.
3. Determine required containment.
4. Identify evidence requirements.
5. Determine systems requiring review.
6. Identify possible persistence.
7. Determine required recovery.
8. Determine escalation.
9. Compare the result with expected playbook actions.

---

# 137. Assessment Exceptions

Exceptions may include:

- Unauthorized access not escalated
- Compromised account left active
- Privileged exposure overlooked
- Related accounts not investigated
- Persistence not considered
- Evidence not preserved
- Permissions not corrected
- Recovery not validated

---

# 138. Findings

Material playbook deficiencies must be documented.

Examples include:

- Confirmed unauthorized access knowingly left active without justification
- Domain Administrator compromise not escalated
- Terminated employee access not investigated
- Unauthorized privileged membership left in place
- Significant evidence deliberately destroyed
- Compromised account restored without reasonable validation
- Repeated unauthorized access left without corrective action

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 139. Control Effectiveness

Unauthorized-access incident evidence may support conclusions that relevant controls are:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

The conclusion must reflect actual evidence rather than documentation alone.

---

# 140. Traceability

This playbook supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

An unauthorized-access incident may provide evidence across multiple stages of this chain.

---

# 141. Related Artifacts

- [[PRO-003 Identity and Access Management Program]]
- [[PRO-005 Security Operations Program]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[STD-001 Information Classification Standard]]
- [[STD-002 Network Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[PROC-001 Joiner-Mover-Leaver Procedure]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-003 Access Review Procedure]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-008 Security Monitoring Procedure]]
- [[PROC-009 Malware Response Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PBK-001 Phishing & Credential Compromise Playbook]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[PBK-004 Data Exposure Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

---

# 142. Review

This playbook must be reviewed:

- At least annually
- Following a material unauthorized-access incident
- Following a significant privileged-access incident
- Following significant authentication or access-control change
- Following material lessons learned
- Following significant assurance findings

The IT & Information Security Manager coordinates review.

Material revisions require CIO approval.

---

# 143. Revision History

| Version | Date     | Description                          | Approval |
| ------- | -------- | ------------------------------------ | -------- |
| 1.0     | May 2013 | Initial Unauthorized Access Playbook | CIO      |