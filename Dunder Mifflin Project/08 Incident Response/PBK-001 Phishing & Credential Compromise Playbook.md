# PBK-001 Phishing & Credential Compromise Playbook

## Document Control

| Field | Value |
|---|---|
| Document ID | PBK-001 |
| Title | Phishing & Credential Compromise Playbook |
| Version | 1.0 |
| Classification | Confidential |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following a Material Phishing or Credential-Compromise Incident |

---

# 1. Purpose

This playbook provides operational guidance for identifying, investigating, containing, eradicating, recovering from, and documenting phishing and credential-compromise incidents.

It supplements [[PLN-001 Incident Response Plan]] with response actions specific to:

- Phishing
- Credential theft
- Account compromise
- Malicious email
- Executive impersonation
- Business Email Compromise (BEC)
- Credential reuse
- Unauthorized authentication

---

# 2. Scope

This playbook applies to suspected or confirmed compromise involving:

- Employee accounts
- Executive accounts
- Email accounts
- Active Directory accounts
- VPN accounts
- Cloud-service accounts
- Application accounts
- Privileged accounts
- Contractor accounts
- Infinity-related accounts

---

# 3. Authority

This playbook operates under:

- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-009 Incident Response Policy]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-008 Incident Classification & Escalation Standard]]
- [[PLN-001 Incident Response Plan]]

---

# 4. Objectives

The response must:

1. Protect affected accounts.
2. Stop unauthorized access.
3. Determine whether credentials were compromised.
4. Determine whether compromised credentials were used.
5. Determine reasonable incident scope.
6. Identify affected systems and information.
7. Protect privileged credentials.
8. Contain malicious email where practical.
9. Preserve useful evidence.
10. Restore trusted account access.
11. Identify required corrective action.
12. Support risk reassessment where appropriate.

---

# 5. Response Lifecycle

The phishing and credential-compromise response lifecycle is:

**Report / Detect → Triage → Protect Account → Preserve Evidence → Determine Scope → Contain → Investigate → Eradicate → Recover → Validate → Close → Improve**

Activities may occur concurrently when necessary.

---

# 6. Safety Priority

Human life and safety remain the highest priority.

Personnel must not delay emergency action solely to preserve electronic evidence.

---

# 7. Common Detection Sources

Potential phishing or credential-compromise events may be detected through:

- User reports
- Help Desk reports
- Suspicious email
- Authentication logs
- Account lockouts
- Unexpected password changes
- Unauthorized account activity
- Antivirus alerts
- Administrator observations
- Financial-process anomalies
- Customer reports
- Third-party notification

---

# 8. Common Phishing Indicators

Indicators may include:

- Unexpected request for credentials
- Suspicious links
- Unexpected attachments
- Spoofed sender information
- Unusual urgency
- Requests to bypass normal procedures
- Unexpected financial instructions
- Requests for sensitive information
- Unusual login notifications

No single indicator proves malicious activity.

---

# 9. User Reporting

Employees should report suspicious messages promptly.

Users should not be discouraged from reporting because they:

- Clicked a link
- Opened an attachment
- Entered credentials
- Replied to the sender

Rapid reporting can materially reduce incident impact.

---

# 10. Initial User Questions

The responder should determine:

- What message was received?
- When was it received?
- Was a link clicked?
- Was an attachment opened?
- Were credentials entered?
- Was information submitted?
- Was software executed?
- Was money sent or financial action taken?
- Did the user observe unusual account behavior?
- Is the affected device still connected?

---

# 11. Initial Triage

Initial triage should determine whether the event appears to involve:

- Suspicious email only
- Credential submission
- Confirmed unauthorized login
- Malware execution
- Sensitive information disclosure
- Financial fraud
- Privileged account compromise

---

# 12. Event Versus Incident

Receipt of a phishing message alone may remain a security event.

Formal incident response is required when evidence indicates or reasonably suggests:

- Credential compromise
- Unauthorized access
- Malware execution
- Information exposure
- Financial fraud
- Other material security impact

---

# 13. Incident Classification

Formal incidents must be classified according to [[STD-008 Incident Classification & Escalation Standard]].

Classification must consider:

- Account privilege
- Systems accessible
- Information accessible
- Unauthorized activity
- Business impact
- Financial impact
- Scope
- Persistence

---

# 14. Immediate Credential Protection

When credential compromise is reasonably suspected, responders should promptly protect the affected account.

Actions may include:

- Disable the account.
- Reset the password.
- Terminate active sessions where supported.
- Restrict access.
- Review privileged access.
- Review related authentication activity.

The exact action depends on incident context.

---

# 15. Trusted System

Credential changes should be performed from a system reasonably believed to be trusted.

A potentially compromised endpoint should not be relied upon for sensitive credential replacement when a safer alternative is available.

---

# 16. Password Reset

A compromised or reasonably suspected password must be changed.

The replacement password must not reuse the compromised password.

---

# 17. Credential Reuse

The responder should determine whether the affected user may have used the same or similar credentials for other company systems.

Where reuse creates exposure, related credentials must also be protected.

---

# 18. Smart-Card Authentication

Smart-card multifactor authentication (MFA) is a proposed control where supported and required by risk.

Where smart-card authentication has actually been implemented, responders must determine whether the incident affected:

- Password or secret
- Smart card
- Personal Identification Number (PIN)
- Associated account
- Authentication session

The existence of a proposed smart-card control must not be assumed during current-state response.

---

# 19. Lost Authentication Device

If a smart card or other authentication device is lost or stolen, responders must:

- Identify affected accounts.
- Disable or revoke the affected authentication mechanism where appropriate.
- Evaluate unauthorized use.
- Replace the device through authorized procedures.

---

# 20. Privileged Account Compromise

Suspected compromise of a privileged account requires immediate escalation.

Examples include:

- Domain Administrator
- Server administrator
- Network administrator
- Backup administrator
- Cloud administrator
- Application administrator
- Database administrator

---

# 21. Domain Administrator Compromise

Confirmed or strongly suspected Domain Administrator compromise must be escalated immediately under [[STD-008 Incident Classification & Escalation Standard]].

The response must consider potential enterprise-wide exposure.

---

# 22. Separate Privileged Credentials

If an employee's ordinary account is compromised, responders must determine whether the employee also possesses separate privileged credentials.

The existence of separate privileged credentials does not prove that those credentials are compromised.

They must be evaluated based on evidence.

---

# 23. Executive Account Compromise

Executive account compromise requires heightened evaluation because it may enable:

- Executive impersonation
- Sensitive email access
- Fraud
- Business Email Compromise
- Sensitive information disclosure

Executive status alone does not establish incident severity.

---

# 24. Contractor Account Compromise

Contractor account compromise requires evaluation of:

- Systems authorized
- Information accessible
- Privilege
- Access duration
- Remote access
- Contractor activity
- Sponsor
- Third-party involvement

Contractor access requirements are defined in [[PROC-004 Contractor Access Procedure]].

---

# 25. Infinity Contractor Account

Compromise involving the Infinity contractor requires heightened evaluation of:

- Source-code access
- Development access
- Production access
- Administrative access
- Application configuration
- Customer information
- Repository integrity

---

# 26. Preserve the Original Message

Where practical, the original suspicious message should be preserved before deletion.

Useful information may include:

- Sender
- Recipient
- Subject
- Date and time
- Message content
- Links
- Attachments
- Routing information

---

# 27. Email Forwarding

Forwarding a phishing message may not preserve all useful message information.

Where available, responders should preserve the original message or relevant message metadata.

---

# 28. Email Evidence

Email evidence must be handled according to [[PROC-011 Evidence Handling Procedure]].

Sensitive information should not be unnecessarily redistributed while investigating the message.

---

# 29. Suspicious Links

Responders should document suspicious links without unnecessarily visiting them from production systems.

Relevant information may include:

- Displayed link
- Actual destination
- Domain
- User interaction
- Redirect behavior where safely determined

---

# 30. Suspicious Attachments

Suspicious attachments must not be casually opened.

The responder should preserve:

- File name
- File type
- Message source
- File hash where useful
- Relevant antivirus results

---

# 31. Malware Escalation

If phishing results in suspected malware execution, response must also follow:

- [[PROC-009 Malware Response Procedure]]
- [[PBK-002 Malware & Ransomware Playbook]]

---

# 32. Endpoint Isolation

If a phishing attachment or link may have caused malicious execution, the affected endpoint should be isolated when appropriate.

Isolation should occur promptly when continued connectivity may increase harm.

---

# 33. Endpoint Investigation

Endpoint investigation may include:

- Managed antivirus status
- Antivirus alerts
- Suspicious files
- Running processes
- Recent software changes
- Relevant logs
- Browser activity
- Persistence indicators
- Authentication activity

Investigation must remain within authorized technical capability.

---

# 34. Account Investigation

Account investigation should determine:

- Whether unauthorized authentication occurred
- When suspicious authentication occurred
- What systems were accessed
- Whether privilege changed
- Whether information was accessed
- Whether settings changed
- Whether additional accounts were affected

---

# 35. Authentication Timeline

The responder should build a reasonable authentication timeline including:

- Known legitimate use
- Suspicious login attempts
- Successful suspicious logins
- Password changes
- Account disablement
- Privileged changes
- Recovery actions

---

# 36. Time Accuracy

Authentication timestamps must be evaluated with awareness of possible:

- Clock differences
- Time-zone differences
- Logging gaps
- Incomplete records

Unknown times must not be invented.

---

# 37. Active Directory Review

Where applicable, Active Directory review may include:

- Authentication activity
- Group membership
- Account status
- Password changes
- Privileged-group changes
- New account creation
- Administrative activity

---

# 38. Cloud Account Review

Cloud-account investigation may include:

- Authentication records
- Account changes
- Administrative activity
- Accessible services
- Provider security information

Investigation depends on available provider capability.

---

# 39. VPN Review

If the affected account can use Virtual Private Network (VPN) access, responders should determine whether suspicious VPN activity occurred.

VPN access is intended for authorized company laptops connecting from external or untrusted networks to nonpublic company resources.

---

# 40. Public Infinity Access

Normal public use of Infinity does not require VPN.

Suspicious Infinity authentication must be evaluated according to the account and application functions involved.

---

# 41. Mailbox Review

Where supported and authorized, investigation of a compromised email account may include:

- Sent messages
- Deleted messages
- Forwarding settings
- Mailbox rules
- Contact changes
- Suspicious replies
- Fraud-related communication

---

# 42. Unauthorized Mailbox Rules

Unexpected mailbox rules or forwarding settings may indicate persistence or information collection.

Unauthorized rules must be:

- Documented
- Removed
- Investigated

---

# 43. Outbound Phishing

A compromised account may be used to send phishing messages to other employees or external recipients.

Responders should determine:

- Messages sent
- Recipients
- Time period
- Whether additional users interacted

---

# 44. Internal Recipients

When malicious messages were sent internally, responders should identify affected recipients where practical.

Response may include:

- User notification
- Message removal where available
- Account review
- Endpoint review

---

# 45. External Recipients

If a compromised company account sent malicious messages externally, management should determine whether external communication is necessary.

Technical personnel must not independently issue public statements.

---

# 46. Similar Messages

Responders should determine whether the same or similar phishing message reached additional employees.

Search criteria may include:

- Sender
- Subject
- Link
- Attachment
- Time period
- Message characteristics

---

# 47. Malicious Message Containment

Where available, responders should remove or quarantine known malicious messages from company mailboxes.

If centralized removal is unavailable, affected users should receive clear instructions.

---

# 48. Sender Blocking

Known malicious senders or infrastructure may be blocked where technically practical and appropriate.

Blocking one sender does not establish complete containment because attackers may change infrastructure.

---

# 49. Link Blocking

Known malicious links or domains may be blocked where available.

The response should consider whether the same destination appears in other messages.

---

# 50. Attachment Blocking

Known malicious attachments or file indicators may be blocked through available email or endpoint protections where supported.

---

# 51. Email Security Improvements

Proposed email-security improvements include enhanced filtering and anti-phishing capability intended to identify:

- Known malicious senders
- Suspicious links
- Malicious attachments
- Spoofed messages
- Common phishing indicators

These proposed capabilities must not receive current control-effectiveness credit until implemented and validated.

---

# 52. Business Email Compromise

Potential Business Email Compromise requires immediate consideration of:

- Executive impersonation
- Vendor payment changes
- Banking changes
- Invoice manipulation
- Payroll changes
- Sensitive information requests
- Urgent payment requests

---

# 53. Finance Escalation

Finance must be notified promptly when phishing or account compromise may have caused:

- Payment
- Payment instruction change
- Vendor banking change
- Payroll change
- Unauthorized financial commitment

---

# 54. Stop Pending Transactions

Where authorized and practical, suspicious pending financial transactions should be stopped while legitimacy is verified.

---

# 55. Independent Verification

Suspicious or significant vendor banking changes should be independently verified using a trusted contact method rather than contact information supplied solely in the suspicious message.

---

# 56. Payroll Fraud

Potential payroll fraud requires coordination with:

- Finance
- Human Resources
- Information Security
- Legal/Compliance where appropriate

---

# 57. Executive Impersonation

A message appearing to come from an executive must not be considered legitimate solely because:

- The display name is correct.
- The signature appears correct.
- The request sounds urgent.
- The message contains familiar information.

Significant unusual requests must follow established business verification procedures.

---

# 58. Sensitive Information Request

If a phishing incident caused sensitive information disclosure, response must also follow [[PBK-004 Data Exposure Playbook]].

---

# 59. Information Classification

Information exposure must be evaluated according to:

- Public
- Internal
- Confidential
- Restricted

as established by [[STD-001 Information Classification Standard]].

---

# 60. Payment Card Information

Dunder Mifflin does not retain payment card Primary Account Numbers (PANs).

The company retains processor-related information such as:

- Token
- Card brand
- Last four digits
- Expiration information

Unexpected disclosure or discovery of full PAN information requires escalation.

---

# 61. Scope Determination

The responder must determine reasonable incident scope.

Scope may include:

- Initial recipient
- Additional recipients
- Compromised accounts
- Related accounts
- Endpoints
- Servers
- Applications
- VPN activity
- Cloud services
- Infinity
- Information
- Financial processes

---

# 62. Scope Must Not Stop at the First User

A phishing investigation must not assume that the reporting user is the only affected person.

Responders should determine whether:

- Other users received the message.
- Other users clicked the link.
- Other users opened the attachment.
- Other users entered credentials.
- The compromised account contacted additional users.

---

# 63. Related Accounts

Related accounts should be reviewed when evidence indicates:

- Credential reuse
- Shared authentication
- Privileged relationship
- Account recovery relationship
- Similar suspicious activity

---

# 64. Shared Warehouse Accounts

Shared Windows accounts may exist on warehouse workstations for operational reasons.

Significant Warehouse Management System (WMS) transactions should use individual authentication and accountability.

A shared workstation account must not be assumed to identify the individual responsible for a significant transaction.

---

# 65. Dormant Accounts

Investigation should determine whether suspicious activity involves an account that should have been:

- Investigated after 30 days of inactivity
- Disabled after 60 days of inactivity

under established Identity and Access Management requirements.

---

# 66. Terminated Personnel

If a compromised account belongs to terminated personnel, responders must immediately evaluate whether termination controls failed.

The condition may require corrective action under [[PROC-001 Joiner-Mover-Leaver Procedure]].

---

# 67. Account Persistence

Responders should investigate whether the attacker established continued access through:

- Additional accounts
- Privileged-group membership
- Mailbox rules
- Forwarding
- Application changes
- Credential changes
- Other persistence mechanisms

within available technical capability.

---

# 68. Unauthorized Account Creation

Unexpected account creation associated with a compromise requires immediate investigation.

The new account should be disabled or otherwise contained when unauthorized.

---

# 69. Unauthorized Privilege Change

Unexpected privilege elevation requires immediate escalation.

The response should determine:

- Who changed the privilege
- When
- Which account benefited
- What access resulted
- Whether the change remains active

---

# 70. Session Termination

Where supported, active sessions associated with a compromised account should be terminated.

Password replacement alone may not end all existing authenticated sessions.

---

# 71. Credential Replacement Scope

Credential replacement should include credentials reasonably affected by the incident.

Unnecessary enterprise-wide credential resets should be avoided unless evidence or risk justifies them.

---

# 72. Service Accounts

If a compromised credential is associated with a service account, responders must coordinate replacement carefully to avoid unnecessary business disruption.

Service-account changes must consider:

- Dependencies
- Applications
- Scheduled processes
- Stored credentials
- Recovery requirements

---

# 73. Emergency Access Credentials

Potential exposure of emergency or break-glass credentials must be handled under [[PROC-005 Emergency Access Procedure]].

Affected credentials must be protected or replaced as appropriate.

---

# 74. Backup Credentials

Potential exposure of backup administrative credentials requires heightened response because backup compromise may increase ransomware or destructive-attack impact.

---

# 75. Containment Validation

After containment, responders must verify that intended actions occurred.

Examples include confirming:

- Account disabled
- Password changed
- Session terminated
- Malicious rule removed
- Endpoint isolated
- Malicious message contained

---

# 76. Failed Containment

If containment fails, responders must:

1. Document the failure.
2. Determine the cause.
3. Escalate as appropriate.
4. Select another containment action.
5. Reevaluate incident severity.

---

# 77. Eradication

Eradication removes remaining malicious conditions.

Actions may include:

- Removing malicious mailbox rules
- Removing unauthorized accounts
- Removing malicious software
- Reimaging affected endpoints
- Correcting configuration
- Replacing compromised credentials
- Remediating exploited vulnerabilities

---

# 78. Endpoint Reimaging

An endpoint may require reimaging when responders cannot establish reasonable confidence that malicious software or persistence has been removed.

Relevant evidence should be preserved before reimaging where practical.

---

# 79. Vulnerability Remediation

If the incident involved an exploitable vulnerability, remediation must follow [[PROC-007 Vulnerability Remediation & Retest Procedure]].

Credential reset alone does not correct an underlying technical vulnerability.

---

# 80. Recovery

Account recovery must restore authorized access while preventing continued unauthorized access.

Recovery may include:

- New password
- New authentication device
- Restored account
- Correct permissions
- Verified mailbox settings
- Trusted endpoint
- User notification

---

# 81. User Identity Verification

Before restoring a compromised account, the responder must reasonably verify the user's identity.

The compromised communication channel should not be the sole basis for identity verification when stronger verification is available.

---

# 82. Access Review After Compromise

A significant compromised account should receive an access review before or promptly after restoration.

The review should identify:

- Current business need
- Group memberships
- Sensitive access
- Privileged access
- Unexpected permissions

---

# 83. Privileged Account Recovery

Privileged account recovery requires heightened verification.

The responder must consider:

- Separate privileged credential replacement
- Administrative workstation trust
- Privileged-group membership
- Related administrative activity

---

# 84. Endpoint Trust

An account should not be restored to normal use from a device still reasonably suspected of compromise.

The endpoint must be:

- Validated,
- Remediated, or
- Rebuilt

as appropriate.

---

# 85. Recovery Validation

Recovery is not complete merely because the user can log in.

Validation should determine whether:

- Unauthorized sessions are terminated.
- Credentials are replaced.
- Permissions are correct.
- Malicious mailbox settings are removed.
- Endpoint risk is addressed.
- Suspicious activity has stopped.

---

# 86. Heightened Monitoring

Following significant credential compromise, relevant accounts and systems may receive heightened monitoring.

Monitoring should focus on:

- Authentication
- Account changes
- Privileged activity
- Suspicious email
- Related indicators

---

# 87. Recurrence

Repeated suspicious activity after recovery may indicate:

- Incomplete containment
- Additional compromised credentials
- Compromised endpoint
- Persistence
- Broader account compromise

The incident must be reevaluated.

---

# 88. Evidence

Evidence may include:

- Original phishing message
- Email metadata
- Suspicious links
- Attachments
- File hashes
- Authentication logs
- Account records
- Mailbox rules
- Antivirus alerts
- Endpoint information
- Financial records
- User statements
- Screenshots

---

# 89. Evidence Handling

Evidence must be handled according to [[PROC-011 Evidence Handling Procedure]].

Material evidence must remain traceable to the incident.

---

# 90. Evidence Before Cleanup

Where practical, useful evidence should be collected before:

- Message deletion
- Mailbox-rule removal
- Account deletion
- Endpoint reimaging
- Malware removal
- Log clearing

Immediate containment may take priority when delay would increase harm.

---

# 91. Incident Timeline

Significant incidents should maintain a timeline including:

- Message receipt
- User interaction
- Credential submission if known
- Suspicious authentication
- Detection
- Reporting
- Account containment
- Endpoint containment
- Investigation
- Recovery

---

# 92. Unknown Timeline Elements

Unknown times must be documented as unknown or approximate.

Responders must not create false precision.

---

# 93. User Statement

A user statement may provide important context.

The responder should document what the user reports without representing the statement as independent technical evidence.

---

# 94. Third-Party Evidence

Third-party information may support investigation.

The responder must document:

- Source
- Provider
- Date received
- Relevant limitations

Provider conclusions must not automatically replace Dunder Mifflin's own incident evaluation.

---

# 95. External Assistance

External specialist assistance may be appropriate when the incident involves:

- Significant privileged compromise
- Complex malware
- Large-scale credential theft
- Significant information exposure
- Complex forensic requirements

The retained Digital Forensics and Incident Response (DFIR) capability is proposed and receives no current residual-risk credit until implemented.

---

# 96. Escalation to Legal/Compliance

Legal/Compliance should be involved when the incident may create material:

- Legal exposure
- Contractual obligations
- Privacy concerns
- External notification requirements
- Evidence-preservation requirements

---

# 97. Escalation to Human Resources

Human Resources should be involved when the incident materially involves:

- Employee misconduct
- Personnel information
- Terminated employees
- Employee investigation

---

# 98. Escalation to Executive Management

Executive escalation must follow [[STD-008 Incident Classification & Escalation Standard]].

Severity 1 incidents require prompt CEO notification.

---

# 99. Communications

Incident communications must be:

- Accurate
- Timely
- Limited to legitimate need
- Based on known information

Responders must distinguish confirmed facts from suspected conditions.

---

# 100. External Communication

External communication requires appropriate authorization.

Technical personnel must not independently:

- Contact customers with incident conclusions
- Issue public statements
- Admit liability
- Make regulatory statements

---

# 101. Incident Closure

A phishing or credential-compromise incident may be closed when:

- Required containment is complete.
- Affected credentials are protected.
- Reasonable scope has been determined.
- Required endpoint remediation is complete.
- Unauthorized persistence is addressed.
- Recovery is validated.
- Material evidence is preserved.
- Required corrective actions are documented.
- Remaining risk is understood.

---

# 102. Closure Does Not Mean All Actions Are Complete

Incident closure does not automatically close:

- Vulnerability remediation
- Corrective actions
- Access reviews
- Awareness improvements
- Email-security improvements
- Risk treatments

These actions remain tracked through their respective processes.

---

# 103. Lessons Learned

Significant phishing and credential-compromise incidents should evaluate:

- Why the message reached the user
- Why the user trusted or interacted with it
- Whether authentication controls limited impact
- Whether monitoring detected unauthorized use
- Whether escalation was timely
- Whether account containment was effective
- Whether additional users were affected
- Whether financial controls operated correctly

---

# 104. Awareness Improvement

A phishing incident may identify opportunities to improve:

- Security awareness
- Phishing recognition
- Reporting behavior
- Financial verification
- Credential handling

Training improvements must not be used as the sole corrective action when technical or process weaknesses also contributed.

---

# 105. Monthly Phishing Simulations

Monthly phishing simulations are a proposed treatment supporting R001.

Simulation results may help identify:

- Reporting behavior
- Repeated susceptibility
- Training needs
- Organizational trends

Simulation results should be used for security improvement rather than unnecessary punishment.

---

# 106. Email Security Improvement

Recurring phishing incidents should prompt evaluation of:

- Filtering
- Spoofing protection
- Malicious-link controls
- Attachment controls
- Sender blocking
- User reporting mechanisms

---

# 107. Authentication Improvement

Credential-compromise incidents should prompt evaluation of:

- Password controls
- Smart-card MFA deployment
- Privileged-account separation
- Dormant accounts
- Contractor access
- Account-review processes

---

# 108. Corrective Action

Material deficiencies identified during response must have:

- Deficiency
- Accountable owner
- Required action
- Due date
- Validation method

Material corrective actions are tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 109. Corrective-Action Validation

Corrective action is not complete solely because an owner states that it was performed.

Required validation must determine whether the intended condition was achieved.

---

# 110. Risk Relationships

This playbook directly supports treatment and response for:

- R001 Phishing / Credential Compromise
- R002 Business Email Compromise
- R005 Password / Authentication Weakness
- R009 Sensitive Information Theft / Extortion
- R010 Unauthorized / Excessive Access
- R011 Delayed Termination
- R012 Malicious Insider
- R014 Lost Device
- R019 Infinity Contractor Dependency / Compromise
- R029 Vendor Fraud
- R030 Sales Fraud
- R031 Payroll Fraud

It may also provide supporting response capability for other risks when credential compromise is part of the incident.

---

# 111. R001 Relationship

R001 addresses phishing and credential compromise originating primarily from external adversary activity and human interaction.

Current residual risk is:

**12 High**

Target residual risk after proposed treatment is:

**6 Moderate**

---

# 112. R001 Treatment

Proposed R001 treatment includes:

- Improved email filtering and anti-phishing controls
- Smart-card MFA where supported
- Security awareness
- Monthly phishing simulations
- Least privilege
- Separate privileged credentials
- Authentication and security-event monitoring
- Endpoint protection
- Incident-response capability

Proposed treatment does not receive current residual-risk credit before implementation and validation.

---

# 113. R005 Relationship

R005 addresses weakness in the authentication and account-control architecture.

Current residual risk is:

**12 High**

Target residual risk after proposed treatment is:

**4 Low**

R001 and R005 are related but remain distinct risks.

---

# 114. Business Email Compromise Relationship

R002 addresses Business Email Compromise.

Current residual risk is:

**8 Moderate**

Target residual risk after proposed treatment is:

**4 Low**

Financial-process controls remain important because authentication and email controls cannot eliminate all BEC risk.

---

# 115. Current Versus Proposed Controls

Response records must distinguish among:

- Current controls
- Partially implemented controls
- Planned controls
- Implemented controls awaiting validation
- Validated controls

---

# 116. No Premature Risk Credit

Current residual risk must not be reduced merely because:

- This playbook exists.
- Smart-card MFA is planned.
- Email filtering improvements are planned.
- Phishing simulations are planned.
- A retained DFIR provider is proposed.

Risk reduction requires implementation and appropriate validation.

---

# 117. Risk Reassessment

Incident evidence may support risk reassessment when it demonstrates:

- Greater likelihood
- Greater impact
- Authentication-control weakness
- Email-control weakness
- Improved control effectiveness
- Unexpected attack path

Historical May 2013 risk results must remain preserved.

---

# 118. Operational Metrics

Operational metrics may include:

- Phishing messages reported
- Users interacting with confirmed phishing
- Credential-compromise incidents
- Compromised accounts
- Privileged-account compromises
- Business Email Compromise incidents
- Financial actions associated with phishing
- Repeat credential compromise

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 119. Key Performance Indicators

Key Performance Indicators (KPIs) may include:

- Percentage of reported phishing events triaged
- Percentage of confirmed credential compromises receiving required containment
- Percentage of significant incidents with documented scope
- Percentage of affected accounts receiving recovery validation
- Percentage of material corrective actions completed and validated

---

# 120. Key Risk Indicators

Key Risk Indicators (KRIs) may include:

- Increasing credential-compromise incidents
- Repeated compromise of the same user
- Privileged credential compromise
- Compromised dormant accounts
- Repeated Business Email Compromise
- Delayed account containment
- Repeated malicious-email delivery patterns
- Compromise following known phishing campaigns

---

# 121. Metric Interpretation

A higher number of reported phishing messages may indicate:

- Increased attack volume
- Improved employee reporting
- Improved awareness

The metric must be interpreted in context.

---

# 122. Playbook Exercises

This playbook should be periodically exercised.

Exercise scenarios may include:

- User reports phishing before interaction
- User enters credentials
- Executive account compromise
- Compromised account sends internal phishing
- Vendor-payment fraud attempt
- Privileged credential compromise

---

# 123. Exercise Objectives

Exercises should evaluate whether responders can:

- Triage the event
- Protect the account
- Determine required escalation
- Preserve evidence
- Determine scope
- Coordinate with Finance or Human Resources where required
- Recover the account
- Identify corrective action

---

# 124. Playbook Assessment

Assessment may determine whether:

- Reported phishing is triaged.
- Credential compromise is escalated.
- Accounts are contained.
- Related accounts are evaluated.
- Evidence is preserved.
- Recovery is validated.
- Significant incidents receive corrective action.

---

# 125. Assessment Methods

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

# 126. Independent Performance

An assessor may independently perform selected playbook steps within an authorized exercise.

For example, the assessor may:

1. Receive a simulated phishing report.
2. Determine whether credentials were entered.
3. Identify the affected account.
4. Determine required containment.
5. Determine required evidence.
6. Determine escalation.
7. Identify related systems requiring review.
8. Compare the result with expected playbook actions.

---

# 127. Assessment Exceptions

Exceptions may include:

- Delayed triage
- Account not contained
- Related privileged account overlooked
- Evidence not preserved
- Additional recipients not investigated
- Finance not notified during BEC
- Recovery not validated
- Required escalation omitted

---

# 128. Findings

Material playbook deficiencies must be documented.

Examples include:

- Confirmed compromised account left active without justification
- Privileged compromise not escalated
- Known malicious mailbox rule left in place
- Business Email Compromise not communicated to Finance
- Significant evidence deliberately destroyed
- Compromised account restored without reasonable validation
- Repeated phishing weakness left without corrective action

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 129. Control Effectiveness

Evidence from phishing and credential-compromise incidents may support conclusions that relevant controls are:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

Control effectiveness must reflect actual operation.

---

# 130. Traceability

This playbook supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

A phishing incident may provide evidence across multiple stages of this chain.

---

# 131. Related Artifacts

- [[PRO-003 Identity and Access Management Program]]
- [[PRO-005 Security Operations Program]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-006 Security Awareness & Training Policy]]
- [[POL-009 Incident Response Policy]]
- [[STD-001 Information Classification Standard]]
- [[STD-005 Authentication & Account Security Standard]]
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
- [[PLN-001 Incident Response Plan]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[PBK-004 Data Exposure Playbook]]
- [[PBK-005 Third-Party Incident Playbook]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

---

# 132. Review

This playbook must be reviewed:

- At least annually
- Following a material phishing incident
- Following a material credential-compromise incident
- Following significant email-security change
- Following significant authentication change
- Following material lessons learned
- Following significant assurance findings

The IT & Information Security Manager coordinates review.

Material revisions require CIO approval.

---

# 133. Revision History

| Version | Date     | Description                                       | Approval |
| ------- | -------- | ------------------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Phishing & Credential Compromise Playbook | CIO      |