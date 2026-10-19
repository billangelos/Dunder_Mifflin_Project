# PROC-005 Emergency Access Procedure

## Document Control

| Field | Value |
|---|---|
| Document ID | PROC-005 |
| Title | Emergency Access Procedure |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Emergency Access Use or Material Access-Control Change |

---

# 1. Purpose

This procedure defines how Dunder Mifflin, Inc. provides controlled emergency access when normal administrative access is unavailable, insufficient, or inappropriate for an urgent situation.

Emergency access exists to support legitimate response to conditions that could materially affect:

- Human safety
- Critical business operations
- Information security
- System availability
- Data integrity
- Incident containment
- Recovery

Emergency access must not become an alternative to normal access provisioning.

---

# 2. Scope

This procedure applies to emergency or break-glass access involving:

- Active Directory
- Windows servers
- Network infrastructure
- Firewalls and routers
- Cloud-hosted systems
- Business applications
- Databases
- Backup systems
- Security systems
- Infinity
- Other significant administrative systems

The procedure applies to authorized employees and, when specifically approved, authorized contractors.

---

# 3. Authority

This procedure implements requirements established by:

- [[POL-003 Access Control Policy]]
- [[PRO-003 Identity and Access Management Program]]
- [[STD-005 Authentication & Account Security Standard]]
- [[PROC-002 Privileged Access Procedure]]

Emergency changes performed through emergency access must also comply with [[POL-007 Change & Configuration Management Policy]].

---

# 4. Emergency Access Objectives

Emergency access must:

1. Remain available for legitimate emergencies.
2. Remain protected from unauthorized use.
3. Provide sufficient access to address the emergency.
4. Avoid unnecessary privilege.
5. Support individual accountability.
6. Require appropriate authorization.
7. Produce evidence of use.
8. Receive post-use review.
9. Be returned to a protected state after use.
10. Remain exceptional rather than routine.

---

# 5. Definition of Emergency Access

Emergency access is elevated or otherwise exceptional access used when ordinary access mechanisms cannot adequately support an urgent authorized action.

Emergency access may be required when:

- Normal administrator credentials are unavailable.
- An administrator is unavailable.
- Authentication infrastructure is impaired.
- A security incident requires urgent containment.
- A critical system requires immediate recovery.
- Ordinary access cannot perform a necessary recovery action.
- A critical administrative function must be restored.

---

# 6. Break-Glass Access

Break-glass access is a form of emergency access using credentials or access mechanisms reserved for emergency use.

Break-glass access must not be used for:

- Routine administration
- Convenience
- Avoiding normal approval
- Avoiding change control
- Bypassing ordinary authentication because it is faster
- Compensating for poor access planning

---

# 7. Safety Priority

Human life and safety take priority over:

- Systems
- Operations
- Facilities
- Equipment
- Inventory
- Revenue
- Information assets

Emergency access requirements must never delay necessary life-safety actions.

---

# 8. Emergency Access Principles

Emergency access must follow:

- Minimum necessary privilege
- Minimum necessary duration
- Individual accountability
- Controlled authorization
- Protected credentials
- Documented use
- Post-use review
- Prompt return to normal access

---

# 9. Emergency Access Workflow

The expected workflow is:

**Emergency Identified → Normal Access Evaluated → Authorization → Credential Release or Access Activation → Emergency Use → Activity Documentation → Access Termination → Credential Protection or Replacement → Post-Use Review → Corrective Action Where Required**

Urgency may alter sequencing, but not accountability.

---

# 10. Determine Whether Emergency Access Is Required

Before using emergency access, the responsible personnel must determine whether normal authorized access can address the condition within the required time.

Emergency access should not be used when:

- An authorized administrator is readily available.
- Existing privileges are sufficient.
- The activity can safely wait for normal authorization.
- The request is merely operationally convenient.

---

# 11. Legitimate Emergency Conditions

Emergency access may be appropriate for:

- Major service outage
- Authentication failure
- Security incident
- Malware containment
- Ransomware response
- Critical configuration failure
- Backup or recovery emergency
- Loss of ordinary privileged access
- Urgent business-system recovery

The emergency must involve a legitimate need for exceptional access.

---

# 12. Emergency Access Authorization

Emergency access requires authorization from an appropriate responsible authority where circumstances permit.

Authorization may come from:

- IT & Information Security Manager
- CIO
- Other specifically authorized management personnel

The authorizer must understand the reason emergency access is required.

---

# 13. Authorization Information

Emergency-access authorization should identify:

- Requester
- User
- System
- Reason
- Required privilege
- Expected activity
- Expected duration
- Authorizer

The amount of documentation required during the event may be adjusted to the urgency of the situation.

---

# 14. Immediate Emergency

When delay would create unacceptable risk to safety, security, or critical operations, authorized technical personnel may take necessary emergency action before completing normal documentation.

The action must:

- Remain limited to the emergency.
- Be documented as soon as practical.
- Receive post-use review.

Urgency does not eliminate accountability.

---

# 15. Emergency Access Accounts

Emergency accounts must be limited to systems where they provide a legitimate recovery or security capability.

An emergency account must not be created merely to provide another permanent administrative identity.

---

# 16. Account Identification

Emergency accounts must be identifiable as emergency or break-glass accounts where practical.

Records must identify:

- Account purpose
- Systems affected
- Responsible owner
- Credential-control method

---

# 17. Emergency Account Privilege

Emergency accounts may require substantial privilege to perform their intended function.

Privilege must still be limited to the systems and functions necessary for the emergency purpose.

An enterprise-wide emergency account must not be used when a narrower account can reasonably satisfy the requirement.

---

# 18. Credential Protection

Emergency credentials must be protected against:

- Unauthorized disclosure
- Unauthorized use
- Loss
- Uncontrolled copying
- Casual administrator access

Protection must reflect the potential impact of the credential.

---

# 19. Dual Custody

Higher-risk break-glass credentials must use dual custody where practical.

Dual custody means that no single person should routinely be able to obtain and use the emergency credential without another authorized person's participation.

The control must not prevent legitimate emergency response.

---

# 20. Dual-Custody Methods

Dual custody may be implemented through methods such as:

- Separate custody of credential components
- Sealed credential storage requiring two authorized personnel
- Controlled physical access involving two custodians
- Other methods that provide comparable accountability

The method must remain usable during foreseeable emergencies.

---

# 21. Emergency Credential Storage

Emergency credentials must be stored in a protected location.

Storage must:

- Restrict unauthorized access.
- Support legitimate emergency retrieval.
- Protect confidentiality.
- Make unauthorized access difficult.
- Support evidence of release where practical.

Emergency credentials must not be stored in ordinary unsecured notes.

---

# 22. Physical Emergency Credential Storage

Where credentials are maintained physically, they may be stored in a sealed envelope or comparable protected container within a secured location.

The storage method should make unauthorized access or tampering apparent where practical.

---

# 23. Credential Availability

Emergency credential protection must not make the credential unusable during the emergency it was designed to address.

The organization must balance:

- Security
- Availability
- Accountability
- Recovery requirements

A credential that cannot be obtained during a foreseeable emergency does not provide effective emergency access.

---

# 24. Emergency Access Knowledge

Knowledge of break-glass credentials must be restricted.

Personnel must not memorize, copy, or retain emergency credentials for routine future use when doing so defeats the intended control.

---

# 25. Credential Release

When an emergency credential is released, the record should identify:

- Date
- Time
- Person receiving access
- Person authorizing release
- Custodian or custodians
- System
- Reason

Documentation may be completed immediately after urgent action when necessary.

---

# 26. Identity Verification

The person receiving emergency access must be identified before access is released where circumstances permit.

Emergency conditions do not justify releasing privileged credentials to an unidentified individual.

---

# 27. Employee Emergency Access

Employees receiving emergency access must:

- Have legitimate technical responsibility.
- Understand the required action.
- Use the access only for the emergency.
- Protect the credential.
- Document significant activity.
- End use when the emergency requirement ends.

---

# 28. Contractor Emergency Access

Contractor emergency access requires specific authorization.

Contractor affiliation alone does not authorize emergency access.

The contractor must remain subject to:

- Sponsorship
- Confidentiality requirements
- Defined scope
- Individual accountability
- Appropriate supervision
- Post-use review

---

# 29. Infinity Contractor Emergency Access

Emergency Infinity contractor access must remain limited to the access necessary to address the condition.

Privileged production administration must continue to occur from the designated company-controlled contractor workspace at Scranton Headquarters.

An emergency does not authorize general contractor VPN access or external remote privileged administration.

---

# 30. Remote Emergency Access

External remote privileged administration is prohibited.

Emergency conditions do not create an exception to this prohibition.

Ordinary authorized remote access may be used only for nonprivileged activity permitted by the applicable access-control and remote-access requirements.

Emergency access, incident-response authority, operational urgency, contractor status, or recovery requirements do not authorize external remote privileged administration.

---

# 31. Emergency Access Duration

Emergency access must remain active only as long as required.

Access must end when:

- The emergency is resolved.
- Normal administrative access is restored.
- The authorized task is complete.
- The authorization is withdrawn.

Emergency access must not remain active for possible future convenience.

---

# 32. Minimum Necessary Activity

The emergency user must perform only activity necessary to address the authorized emergency.

Emergency access does not provide unrestricted authority to:

- Explore unrelated systems
- Access unrelated information
- Perform unrelated maintenance
- Make unrelated configuration changes

---

# 33. Administrative Workstations

Emergency privileged activity must use approved company-controlled administrative methods and locations.

Where a designated administrative workstation is required and available, it must be used.

An emergency may require use of another controlled company system when the designated workstation is unavailable, provided the activity remains within an approved company-controlled location and does not involve external remote privileged administration.

The reason must be documented when material.

---

# 34. Change Management

Emergency access and emergency change are separate concepts.

Emergency access provides authority to reach the system.

Emergency change management governs the configuration change itself.

Emergency changes must comply with [[POL-007 Change & Configuration Management Policy]].

---

# 35. Emergency Change Documentation

When emergency access is used to perform an emergency change, documentation must identify:

- Condition requiring the change
- System affected
- Change performed
- Person performing the change
- Result
- Required follow-up

Documentation may follow urgent implementation when delay would create unacceptable risk.

---

# 36. Incident Response

Emergency access used during a security incident must support the incident-response process.

Relevant requirements are established by:

- [[POL-009 Incident Response Policy]]
- [[PLN-001 Incident Response Plan]]

Emergency administrative activity must not unnecessarily destroy evidence.

---

# 37. Evidence Preservation

When emergency access is used during an investigation, personnel must consider evidence preservation before making unnecessary changes.

Evidence may include:

- Logs
- Account records
- Configuration
- Malware artifacts
- Files
- Network information

Necessary containment and safety actions take priority when delay would materially increase harm.

---

# 38. Emergency Authentication Failure

If ordinary authentication infrastructure is unavailable, emergency access may provide a recovery path.

The user must limit activity to:

- Diagnosis
- Recovery
- Required security action
- Restoration of normal authentication

Emergency authentication access must not remain the normal method after recovery.

---

# 39. Domain Emergency Access

Emergency access affecting Active Directory or domain administration requires heightened control because of its enterprise-wide impact.

Use must be limited to legitimate requirements involving:

- Authentication recovery
- Domain administration recovery
- Security incident response
- Critical directory-service repair

---

# 40. Server Emergency Access

Emergency server access may be used when normal administration cannot address an urgent server condition.

Actions must comply with [[STD-004 Server Security Standard]] where applicable.

Emergency use must not become a method of bypassing ordinary server administration.

External remote privileged administration remains prohibited.

---

# 41. Network Emergency Access

Emergency access to network infrastructure may be required to:

- Restore connectivity
- Contain malicious traffic
- Recover firewall or router configuration
- Address a critical network failure

Changes must remain limited to the emergency requirement.

External remote privileged administration remains prohibited.

---

# 42. Firewall Emergency Access

Emergency firewall administration may be used to:

- Block malicious traffic
- Restore necessary connectivity
- Correct a critical configuration failure
- Support incident containment

Temporary emergency firewall changes must be reviewed after the event.

External remote privileged administration remains prohibited.

---

# 43. Cloud Emergency Access

Emergency access to cloud-hosted infrastructure may be required when ordinary administrative access is unavailable.

Cloud emergency credentials must receive protection appropriate to their ability to affect:

- Servers
- Authentication
- Applications
- Data
- Recovery

External remote privileged administration of significant cloud-hosted production resources remains prohibited.

---

# 44. Application Emergency Access

Emergency application access may be used to:

- Restore critical functionality
- Correct an urgent security condition
- Recover administrative capability
- Support incident response

Application emergency access must remain limited to the affected application and authorized function.

External remote privileged administration of significant production applications remains prohibited.

---

# 45. Database Emergency Access

Emergency database access must be controlled because it may permit:

- Sensitive information access
- Data modification
- Data deletion
- Security changes
- Recovery actions

Database emergency activity must be documented sufficiently to support later review.

External remote privileged administration of production databases remains prohibited.

---

# 46. Backup Emergency Access

Emergency access to backup systems may be required during:

- System recovery
- Data restoration
- Disaster recovery
- Ransomware response
- Backup-administration failure

Access must remain limited to legitimate recovery or security requirements.

External remote privileged administration of backup systems remains prohibited.

---

# 47. Recovery Operations

Emergency access used for recovery must support recovery requirements established through the Business Impact Analysis (BIA).

Recovery priority remains:

1. Human safety
2. Critical business functions
3. High-priority functions
4. Moderate-priority functions
5. Low-priority functions

Emergency privilege does not independently change recovery priority.

---

# 48. Emergency Access Logging

Emergency-access use must be logged where supported.

Relevant records may include:

- Authentication
- Account activation
- Administrative actions
- Configuration changes
- Access to sensitive systems
- Credential release
- Credential return or replacement

Available logging capability must be represented accurately.

---

# 49. Manual Emergency Record

When automated logging is unavailable, a manual record must be maintained where practical.

The record should identify:

- User
- Time
- System
- Reason
- Significant actions
- Result

Manual records must be completed as soon as practical.

---

# 50. Activity Documentation

The emergency user must document significant actions performed through emergency access.

Documentation must be sufficient to determine:

- What occurred
- Why it occurred
- Who performed it
- Which systems were affected
- Whether additional action is required

---

# 51. Emergency Access Termination

When the emergency need ends, emergency access must be:

- Logged out
- Disabled where appropriate
- Returned to its protected state
- Otherwise terminated

Temporary emergency authorization must not remain active.

---

# 52. Credential Return

Physical emergency credential material must be returned to controlled custody after use.

The responsible custodian must verify that the material has been returned or appropriately replaced.

---

# 53. Credential Change After Use

Break-glass credentials must be evaluated for change after use.

A credential must be changed when:

- Confidentiality may have been exposed.
- The credential was revealed to a user who should not retain it.
- The access method requires replacement after use.
- Security conditions warrant replacement.

Higher-risk shared emergency credentials should normally be changed after use where technically practical.

---

# 54. Credential Replacement

Replacement of an emergency credential must include:

- Secure generation
- Required system update
- Controlled storage
- Updated custody record
- Verification that the new credential works

Credential replacement is not complete until emergency access remains usable.

---

# 55. Authentication Device Reset

Where emergency access uses a physical authentication device, post-use action must determine whether the device requires:

- Reset
- Reissuance
- PIN change
- Revocation
- Return to secure custody

The action depends on how the device was used.

---

# 56. Post-Use Review

Every material emergency-access use must receive post-use review.

The review must determine:

- Whether the emergency was legitimate.
- Whether authorization was appropriate.
- Whether access was limited to required activity.
- Whether significant actions were documented.
- Whether the credential was appropriately secured afterward.
- Whether corrective action is required.

---

# 57. Post-Use Reviewer

The post-use reviewer should be someone with sufficient authority and technical understanding to evaluate the activity.

Where practical, the reviewer should not be the only individual who performed the emergency activity.

Potential reviewers include:

- IT & Information Security Manager
- CIO
- Information Security Analyst
- Appropriate system owner

---

# 58. Post-Use Review Timing

Post-use review must occur promptly after the emergency has stabilized.

The review must not be delayed until the next annual access review.

Urgent restoration may be completed before the review.

---

# 59. Review of Actions

The reviewer must evaluate whether actions performed through emergency access were consistent with:

- The emergency condition
- Authorization
- Security requirements
- Change requirements
- Incident-response requirements

Unrelated activity must be investigated.

---

# 60. Review of Privilege

The reviewer must determine whether the emergency account provided more privilege than necessary.

Where practical, future emergency access should be narrowed if excessive privilege is identified.

---

# 61. Review of Credential Handling

The reviewer must confirm whether:

- Credential custody was maintained.
- Release was recorded.
- Unauthorized copying occurred.
- Credential change was required.
- Credential replacement was completed.

Credential-control failures must be addressed.

---

# 62. Review of Remote Emergency Access

Post-use review must determine whether any emergency activity involved remote access and whether that access remained within authorized nonprivileged use.

The review must specifically determine:

- Whether external remote privileged administration occurred.
- Whether ordinary remote access remained within its authorized scope.
- Whether access duration was limited.
- Whether access was terminated when no longer required.
- Whether any prohibited administrative pathway remains available.

Any external remote privileged administration must be documented as a control failure and investigated.

Emergency conditions do not create an exception to the prohibition.

---

# 63. Review of Contractor Emergency Access

If a contractor used emergency access, the review must verify:

- Identity
- Sponsor
- Business necessity
- Authorized scope
- Systems accessed
- Privileged activity
- Access termination
- Compliance with approved administrative methods and locations

Contractor access outside approved scope requires investigation.

External remote privileged administration is prohibited.

---

# 64. Emergency Access and Problem Management

Repeated emergency-access use for the same condition indicates that the underlying problem may require permanent correction.

Repeated use must trigger evaluation of:

- Access design
- Administrative staffing
- System reliability
- Authentication architecture
- Recovery procedures
- Documentation
- Training

Emergency access must not compensate indefinitely for a correctable weakness.

---

# 65. Routine Use Prohibited

Emergency access must not be used repeatedly for ordinary administrative work.

Indicators of inappropriate routine use include:

- Frequent break-glass retrieval
- Use during normal maintenance
- Use because ordinary privileges are inconvenient
- Use to bypass approvals
- Use to avoid creating appropriate administrator accounts

Recurring inappropriate use requires corrective action.

---

# 66. Failed Emergency Access

If emergency access fails when required:

1. The failure must be documented.
2. Alternative recovery methods must be evaluated.
3. Business or security impact must be assessed.
4. The emergency-access design must be reviewed.
5. Corrective action must be tracked where required.

A break-glass control that cannot function when required is not effective.

---

# 67. Unavailable Custodian

Emergency-access design must consider the possibility that a credential custodian is unavailable.

Dual custody must not depend on only two specific individuals when that design would create an unreasonable single point of failure.

Authorized alternates should be identified where practical.

---

# 68. Lost Emergency Credential

Loss of emergency credential material must be treated as a security event.

Required actions may include:

- Credential invalidation
- Credential replacement
- Access review
- Incident escalation
- Investigation

The response must reflect the privilege and exposure involved.

---

# 69. Suspected Unauthorized Use

Suspected unauthorized emergency-access use requires prompt escalation.

Potential actions include:

- Disable affected account
- Change credential
- Preserve logs
- Review administrative actions
- Investigate affected systems
- Initiate incident response

---

# 70. Emergency Access Inventory

Information Technology must maintain sufficient records to identify significant emergency-access mechanisms.

The inventory should identify:

- System
- Emergency account or mechanism
- Purpose
- Responsible owner
- Custody method
- Review requirement

---

# 71. Inventory Review

Emergency-access mechanisms must be reviewed periodically to determine whether:

- They remain required.
- They remain appropriately protected.
- Ownership remains current.
- Access remains technically functional.
- Obsolete emergency accounts should be removed.

---

# 72. Personnel Changes

Personnel changes affecting emergency-access custodians or authorized users must trigger review of:

- Credential knowledge
- Custody
- Authorization
- Alternate custodians
- Need for credential replacement

A departing administrator must not retain usable emergency credentials.

---

# 73. Termination of Emergency Access Knowledge

When personnel with knowledge of a shared emergency credential no longer require that knowledge, the credential must be evaluated for replacement.

Higher-risk emergency credentials must be changed when continued knowledge creates material risk.

---

# 74. Emergency Access Testing

Emergency-access capability must be tested periodically.

Testing must determine whether:

- Required credentials can be obtained.
- Authorized personnel understand the procedure.
- Access functions.
- Custody controls operate.
- Logging or manual records can be produced.
- The credential can be returned to a protected state.

Testing must avoid unnecessary disruption to production systems.

Testing must not use external remote privileged administration.

---

# 75. Test Frequency

Emergency-access testing should occur at least annually for significant break-glass mechanisms and following material changes affecting the access path.

Higher-risk mechanisms may be tested more frequently when justified.

---

# 76. Test Planning

Testing must define:

- Emergency mechanism in scope
- Personnel involved
- Expected access
- Safety precautions
- Production restrictions
- Evidence required
- Success criteria

Testing must not create an uncontrolled security condition.

---

# 77. Nonproduction Testing

Where practical, portions of emergency-access testing may be performed without making unnecessary production changes.

Testing must still provide reasonable evidence that the actual emergency mechanism can function.

A purely theoretical review is not sufficient evidence of technical availability.

---

# 78. Credential Retrieval Testing

Testing may verify that:

1. Authorized personnel can locate the emergency credential.
2. Custody requirements can be satisfied.
3. Release can be documented.
4. Access can be obtained.
5. The credential can be returned or replaced.

---

# 79. Authentication Testing

Testing must confirm that emergency authentication functions where practical.

A stored credential that has never been validated may fail when needed.

Testing must be controlled to avoid unnecessary changes.

---

# 80. Post-Test Protection

After testing, the emergency mechanism must be returned to its protected state.

Where the test exposed a credential in a manner requiring replacement, the credential must be changed.

---

# 81. Test Evidence

Emergency-access test evidence may include:

- Test date
- Mechanism tested
- Participants
- Custody verification
- Authentication result
- Issues identified
- Corrective actions
- Final protected state

Evidence must accurately reflect what was tested.

---

# 82. Emergency Access Evidence

Evidence associated with actual emergency use may include:

- Authorization
- Credential-release record
- Authentication logs
- Administrative logs
- Change records
- Incident records
- Manual activity record
- Credential replacement
- Post-use review

Evidence must support reconstruction of significant emergency activity.

---

# 83. Evidence Integrity

Personnel must not:

- Create false emergency-access records.
- Backdate authorization to conceal unauthorized use.
- Conceal break-glass use.
- Alter activity records to conceal administrative actions.
- Record credential replacement that did not occur.
- Record post-use review that was not performed.
- Conceal failed emergency-access testing.
- Represent an untested emergency mechanism as validated.
- Represent prohibited external remote privileged administration as an approved emergency exception.

Known discrepancies must be documented.

---

# 84. Emergency Access Assessment

Emergency-access controls must be periodically assessed.

Assessment may use:

- Inspection
- Interviews
- Sampling
- Technical Testing
- Log review
- Credential-custody review
- Independent Performance

Assessment must evaluate both security and availability.

---

# 85. Custody Assessment

An assessor may determine whether:

- Emergency credentials are stored securely.
- Custodians are authorized.
- Dual custody exists where required.
- Unauthorized personnel can access the credential.
- Personnel changes were reflected in custody.

---

# 86. Use Record Assessment

An assessor may select emergency-access events and determine whether:

- Use was justified.
- Authorization existed.
- Activity was documented.
- Access ended after the emergency.
- Credential handling was appropriate.
- Post-use review occurred.
- Privileged activity complied with approved administrative methods and locations.
- External remote privileged administration did not occur.

---

# 87. Credential Replacement Assessment

Where credential replacement was required, assessment must determine whether:

- Replacement occurred.
- The affected system was updated.
- The new credential was protected.
- Emergency access remained functional.

---

# 88. Independent Performance

An assessor may perform selected emergency-access activities independently.

For example, the assessor may:

1. Select an emergency-access mechanism.
2. Identify its authorized custodians.
3. Verify the documented custody process.
4. Observe controlled credential retrieval.
5. Confirm authorized authentication where safe.
6. Verify return to the protected state.

Independent Performance provides evidence beyond review of written procedures.

---

# 89. Assessment Exceptions

Assessment exceptions must be investigated before a final conclusion is reached.

Potential causes include:

- Unauthorized access
- Failed credential
- Missing custody record
- Incomplete documentation
- Technical failure
- Legitimate emergency deviation
- Approved exception to an eligible requirement

The cause determines the appropriate response.

External remote privileged administration is not an eligible approved exception.

---

# 90. Findings

Material emergency-access deficiencies must be documented.

Examples include:

- Missing emergency credential
- Unauthorized emergency-account use
- Break-glass credential used routinely
- Uncontrolled shared emergency credential
- Failed emergency authentication
- Missing post-use review
- Credential not changed after required exposure
- Former administrator retaining emergency credential knowledge
- Emergency account with unnecessary privilege
- External remote privileged administration
- Missing evidence

Material corrective actions must be tracked through [[REG-004 Finding & Corrective Action Register]].

---

# 91. Corrective Action

Corrective action must identify:

- Deficiency
- Affected system or mechanism
- Responsible owner
- Required remediation
- Due date
- Validation method

Corrective action is not complete until remediation has been implemented and appropriately verified.

---

# 92. Metrics

Emergency-access metrics may include:

- Number of emergency-access events
- Break-glass uses
- Emergency remote-access events
- External remote privileged administration events
- Emergency-access events receiving post-use review
- Emergency credentials requiring replacement
- Failed emergency-access tests
- Unauthorized emergency-access events
- Repeated use of the same emergency mechanism
- Open emergency-access findings
- Overdue corrective actions

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 93. Risk Relationships

This procedure provides significant treatment support for:

- R003 Ransomware
- R004 Malware
- R005 Password / Authentication Weakness
- R006 Infinity Application Compromise
- R007 Internet Infrastructure Compromise
- R009 Sensitive Information Theft / Extortion
- R010 Unauthorized / Excessive Access
- R011 Delayed Termination
- R012 Malicious Insider
- R013 Administrative / Configuration Error
- R016 Cloud Outage
- R018 Third-Party Technology Failure / Compromise
- R019 Infinity Contractor Dependency / Compromise
- R026 Personnel Loss
- R027 Backup / Recovery Failure
- R028 Data Corruption
- R034 Loss of Headquarters
- R035 Regional Disaster

Risk treatment is maintained in [[RTP-001 Enterprise Risk Treatment Plan]].

---

# 94. Exceptions

Exceptions to this procedure require:

- Business justification
- Identification of the affected requirement
- Risk evaluation
- Compensating controls where practical
- Accountable owner
- Defined duration
- Appropriate approval

High or Critical residual risk must be escalated according to [[POL-005 Risk Management Policy]].

Emergency conditions may require immediate action before exception documentation is complete, but the deviation must be documented and reviewed afterward.

This exception process does not authorize an exception to the prohibition on external remote privileged administration.

---

# 95. Traceability

This procedure supports the enterprise traceability model:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

Emergency access must remain traceable from emergency need through authorization, use, evidence, review, remediation, and risk reassessment.

---

# 96. Related Artifacts

- [[PRO-003 Identity and Access Management Program]]
- [[POL-003 Access Control Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[STD-002 Network Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[STD-009 Infinity Security Standard]]
- [[PROC-001 Joiner-Mover-Leaver Procedure]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-003 Access Review Procedure]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-010 Security Event Escalation Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[PBK-003 Unauthorized Access Playbook]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]

---

# 97. Review

This procedure must be reviewed:

- At least annually
- Following material emergency-access use
- Following failure of an emergency-access mechanism
- Following significant privileged-access incidents
- Following material IAM or architecture changes
- Following material assessment findings

The IT & Information Security Manager coordinates review.

Material revisions require CIO approval.

---

# 98. Revision History

| Version | Date     | Description                        | Approval |
| ------- | -------- | ---------------------------------- | -------- |
| 1.0     | May 2013 | Initial Emergency Access Procedure | CIO      |