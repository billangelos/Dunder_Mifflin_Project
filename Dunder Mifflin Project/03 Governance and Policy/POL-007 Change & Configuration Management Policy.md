# POL-007 Change & Configuration Management Policy

## Document Control

| Field | Value |
|---|---|
| Document ID | POL-007 |
| Title | Change & Configuration Management Policy |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Change |

---

# 1. Purpose

This policy establishes requirements for controlling changes to Dunder Mifflin technology and maintaining secure, supportable configurations.

Change and configuration management must reduce the likelihood that unauthorized, unnecessary, poorly tested, undocumented, or improperly implemented changes create:

- Security vulnerabilities
- Service outages
- Data corruption
- Recovery failures
- Configuration drift
- Unsupported systems
- Unintended business impact

Changes must receive control proportionate to their risk and business impact.

---

# 2. Scope

This policy applies to changes involving:

- Servers
- Endpoints
- Network devices
- Firewalls
- Applications
- Infinity
- Databases
- Cloud-hosted resources
- Active Directory
- Authentication systems
- Security controls
- Backup systems
- Mobile-device management
- Endpoint-management systems
- Business applications
- System configurations
- Network configurations
- Security configurations
- Production software
- Infrastructure documentation

The policy applies to changes performed by:

- Employees
- Administrators
- Developers
- Contractors
- Consultants
- Third-party service providers

---

# 3. Objectives

Change and configuration management must:

1. Prevent unauthorized changes.
2. Evaluate change risk before implementation.
3. Require appropriate approval.
4. Test changes where practical.
5. Protect production systems.
6. Provide rollback capability where practical.
7. Verify successful implementation.
8. Maintain accurate configuration information.
9. Protect security controls from uncontrolled modification.
10. Support incident investigation.
11. Support recovery.
12. Reduce configuration drift.
13. Preserve appropriate evidence.

---

# 4. General Principles

Technology changes must be:

- Authorized
- Business justified
- Appropriately assessed
- Tested where practical
- Documented
- Recoverable where practical
- Verified after implementation

The amount of control required must reflect:

- Business impact
- Security impact
- Technical complexity
- Scope
- Urgency
- Recovery difficulty

---

# 5. Change Management

Changes to production technology must follow an approved change-management process.

The process must provide sufficient information to determine:

- What is changing
- Why the change is required
- What systems or processes are affected
- What risks are introduced
- How the change will be tested
- How the change will be reversed if necessary
- Who approved the change
- Who will implement it
- How successful implementation will be verified

---

# 6. Change Categories

Changes must be categorized according to their nature and risk.

Dunder Mifflin recognizes:

- Standard Changes
- Normal Changes
- Emergency Changes

The category determines the level and timing of review required.

---

# 7. Standard Changes

A Standard Change is a routine, repeatable, low-risk change that has an established implementation method and has been authorized for repeated use.

Examples may include:

- Routine approved software deployment
- Established account-management activity
- Approved endpoint configuration updates
- Other repeatable administrative activity

Standard Changes must:

- Follow an approved procedure.
- Remain within the authorized scope.
- Be performed by authorized personnel.
- Be documented sufficiently to support accountability.

A change that materially deviates from the approved procedure is no longer a Standard Change.

---

# 8. Normal Changes

A Normal Change is a planned change requiring review and approval before implementation.

Normal Changes may include:

- Server configuration changes
- Network changes
- Firewall changes
- Application releases
- Database changes
- Security-control changes
- Significant software upgrades
- Infrastructure modifications

Normal Changes must receive review proportionate to their potential impact.

---

# 9. Emergency Changes

An Emergency Change is a change that cannot reasonably follow the normal approval timeline because delay would create unacceptable:

- Security risk
- Operational impact
- Safety concern
- Legal or contractual exposure

Emergency status must not be used merely for convenience or poor planning.

---

# 10. Emergency Change Requirements

Emergency Changes must receive as much review and authorization as circumstances reasonably permit before implementation.

When normal documentation cannot be completed beforehand:

1. The change must be authorized by an appropriate manager or designated technical authority.
2. The implementer must document the change as soon as practical.
3. The change must receive post-implementation review.
4. Any failure or unintended impact must be documented.
5. Required corrective action must be identified.

Emergency changes remain subject to security and accountability requirements.

---

# 11. Change Request

A Normal Change request should identify:

- Requester
- Business justification
- Systems affected
- Description of change
- Expected benefit
- Security impact
- Business impact
- Dependencies
- Testing approach
- Implementation plan
- Rollback plan
- Proposed implementation time
- Responsible implementer
- Required approvals

Documentation depth must remain proportionate to the change.

---

# 12. Change Risk Assessment

Changes must be evaluated for potential impact on:

- Confidentiality
- Integrity
- Availability
- Authentication
- Authorization
- Logging
- Backup
- Recovery
- Business operations
- Third-party dependencies
- Other security controls

High-impact changes require greater review than routine low-risk changes.

---

# 13. Security Review

Changes with material security impact must receive appropriate security review.

Examples include changes involving:

- Authentication
- Privileged access
- Firewall rules
- Internet exposure
- Encryption
- Logging
- Antivirus
- Security monitoring
- Backup
- Sensitive information
- Infinity
- Administrative interfaces

Security review must occur early enough to influence the change.

---

# 14. Change Approval

Changes must receive approval appropriate to their risk and scope before implementation.

Approval may involve:

- System owner
- Business owner
- IT & Information Security Manager
- Network/Security Administrator
- System Administrator
- CIO
- Other appropriate management

The individual implementing a material change should not be the sole approver when practical.

---

# 15. Separation of Duties

Change management must use practical separation of duties.

Where staffing permits, material changes should separate:

- Request
- Approval
- Implementation
- Verification

Dunder Mifflin's staffing level does not always permit complete separation.

When one individual must perform multiple functions, additional review or evidence should be used where practical.

Separation of duties must remain proportionate to risk.

---

# 16. Testing

Changes must be tested before production implementation where practical.

Testing should determine whether the change:

- Performs its intended function.
- Introduces unexpected errors.
- Affects security controls.
- Affects dependent systems.
- Creates unacceptable performance problems.
- Can be implemented as planned.

Testing depth must reflect the change's potential impact.

---

# 17. Test Environments

Significant application changes should be tested outside production where appropriate.

Development, testing, and production environments must be separated where required by system risk.

Infinity requirements are established in:

- [[POL-012 Application & Secure Development Policy]]
- [[STD-009 Infinity Security Standard]]

---

# 18. Production Testing

When a change cannot reasonably be fully tested outside production, the change must receive additional planning appropriate to the risk.

Considerations should include:

- Implementation timing
- Backup
- Rollback
- Monitoring
- Business coordination
- Verification

Production systems must not be used casually as test environments.

---

# 19. Change Scheduling

Changes should be scheduled to reduce unnecessary business disruption.

Scheduling must consider:

- Business operating hours
- System criticality
- Recovery requirements
- Support availability
- Dependencies
- Customer impact
- Required verification

Higher-risk changes should be scheduled when appropriate technical support is available.

---

# 20. Rollback Planning

Material changes must have a rollback or recovery plan where practical.

The plan should identify:

- Conditions requiring rollback
- Required backups or configuration copies
- Restoration steps
- Responsible personnel
- Verification after rollback

A rollback plan must be realistic for the system being changed.

---

# 21. Backup Before Change

When a change could materially affect data, configuration, or recoverability, appropriate backup or configuration capture must occur before implementation where practical.

Examples include:

- Server configuration backup
- Network-device configuration backup
- Database backup
- Application backup
- Relevant system-state protection

Backup existence alone does not prove recoverability.

---

# 22. Implementation

Changes must be implemented by authorized personnel.

Implementation must follow the approved plan unless:

- Conditions require a documented deviation,
- The change is stopped, or
- Emergency action becomes necessary.

Material deviations must be recorded.

---

# 23. Implementation Evidence

Change records should contain sufficient evidence to determine:

- What was changed
- When it was changed
- Who performed the change
- Whether the change succeeded
- Whether deviations occurred
- Whether rollback was required
- Whether verification was completed

Evidence depth must remain proportionate to risk.

---

# 24. Post-Implementation Verification

Material changes must be verified after implementation.

Verification should determine:

- Whether the intended change occurred
- Whether the system operates correctly
- Whether expected security controls remain operational
- Whether dependent services remain functional
- Whether unexpected effects occurred
- Whether rollback is necessary

A technically completed installation does not independently prove successful change completion.

---

# 25. Failed Changes

A failed change must be:

- Stabilized
- Rolled back where appropriate
- Documented
- Investigated according to significance
- Corrected or rescheduled

Material failures should be reviewed for:

- Planning deficiencies
- Testing deficiencies
- Configuration errors
- Dependency failures
- Documentation problems
- Security impact

---

# 26. Change Closure

A material change should not be considered complete until required:

- Implementation is finished.
- Verification is completed.
- Documentation is updated.
- Configuration records are updated.
- Recovery documentation is reviewed.
- Material issues are addressed or formally tracked.

Change closure must reflect actual completion.

---

# 27. Recovery Documentation Review

A significant technology or configuration change is not complete until applicable recovery documentation has been reviewed.

The review must determine whether the change affects:

- Recovery procedures
- System dependencies
- Configuration requirements
- Backup requirements
- Recovery sequence
- Recovery credentials
- Required software
- Required infrastructure

If documentation requires revision, it must be updated as part of change completion or tracked as an explicit corrective action.

---

# 28. Configuration Management

Dunder Mifflin must maintain configurations that are:

- Authorized
- Supportable
- Appropriately secured
- Documented according to risk
- Recoverable where required

Configuration management must reduce unauthorized or unintended configuration drift.

---

# 29. Secure Configuration Baselines

Significant technology must have approved secure configuration requirements appropriate to its function.

Configuration baselines may address:

- Required services
- Unnecessary services
- Authentication
- Administrative access
- Logging
- Network exposure
- Security software
- Patch configuration
- Remote access
- Encryption
- System hardening

Detailed requirements are established in [[STD-006 Secure Configuration Standard]] and applicable technology-specific standards.

---

# 30. Baseline Development

Configuration baselines must consider:

- Business requirements
- Security risk
- Vendor guidance
- System function
- Compatibility
- Operational requirements
- Supportability

A security setting must not be adopted solely because it is restrictive if it prevents required business operation without a reasonable security benefit.

---

# 31. Baseline Approval

Security configuration baselines must receive appropriate technical and management approval.

Approval must consider both:

- Security requirements
- Operational requirements

Material baseline changes must follow change-management requirements.

---

# 32. Configuration Documentation

Important configuration information must be documented sufficiently to support:

- Administration
- Troubleshooting
- Security assessment
- Recovery
- Personnel replacement
- Incident response

Documentation should allow a qualified administrator unfamiliar with the environment to understand significant configuration requirements.

---

# 33. Configuration Backups

Configurations required for recovery must be backed up where practical.

Examples include:

- Firewall configurations
- Router configurations
- Switch configurations
- Server configuration information
- Application configuration
- Other significant infrastructure settings

Configuration backups must receive protection appropriate to their sensitivity.

---

# 34. Configuration Drift

Material deviation from an approved configuration must be:

- Authorized,
- Corrected, or
- Documented as an approved exception.

Configuration drift must not be ignored merely because a system continues to function.

---

# 35. Unauthorized Changes

Unauthorized configuration changes must be investigated.

The investigation should determine:

- What changed
- Who or what made the change
- When the change occurred
- Business impact
- Security impact
- Whether malicious activity occurred
- Whether additional systems may be affected

Significant unauthorized changes must be handled under [[POL-009 Incident Response Policy]] when appropriate.

---

# 36. Network Configuration

Network and security-device changes must receive appropriate control.

Material changes may include:

- Firewall rules
- Routing
- Internet exposure
- VPN configuration
- Administrative access
- Network services
- Security-device configuration

Network requirements are established in [[STD-002 Network Security Standard]].

---

# 37. Firewall Changes

Firewall changes must:

- Have documented business or technical need.
- Limit access to required traffic.
- Avoid unnecessary Internet exposure.
- Receive appropriate approval.
- Be verified after implementation.

Unsolicited inbound Internet access must remain denied unless explicitly authorized for a legitimate service.

Administrative interfaces must not be exposed to the Internet without approved exception.

---

# 38. Server Configuration

Server changes must maintain applicable security requirements.

Changes must not unnecessarily weaken:

- Authentication
- Authorization
- Logging
- Patch management
- Antivirus
- Network protection
- Backup
- Recovery

Server requirements are established in [[STD-004 Server Security Standard]].

---

# 39. Endpoint Configuration

Endpoint changes must maintain required controls including, where applicable:

- Standard-user operation
- Antivirus
- Patch management
- Screen locking
- Full-disk encryption
- Central management

Endpoint requirements are established in [[STD-003 Endpoint Security Standard]].

---

# 40. Active Directory Changes

Significant Active Directory changes require appropriate review and authorization.

Examples include:

- Domain Administrator membership
- Group Policy changes
- Authentication changes
- Significant security-group changes
- Domain-controller configuration changes
- Trust relationships

Changes affecting privileged access must receive heightened review.

---

# 41. Authentication Configuration

Changes to authentication systems must consider:

- Account security
- Password requirements
- Smart-card authentication
- Privileged access
- Service accounts
- Emergency access
- Compatibility
- Recovery

Requirements are established in [[STD-005 Authentication & Account Security Standard]].

---

# 42. Security-Control Changes

Changes that disable, weaken, bypass, or materially alter a security control require explicit authorization.

Examples include changes to:

- Antivirus
- Firewalls
- Authentication
- Encryption
- Logging
- Security monitoring
- Access restrictions
- Backup
- Endpoint management

Temporary security-control changes must have defined duration where practical.

---

# 43. Patch Management

Security patches must be managed through controlled deployment.

The patch process should include:

- Identification
- Review
- Testing where practical
- Scheduling
- Deployment
- Monitoring
- Verification
- Rollback planning where appropriate

Patch urgency must be balanced against the risk of untested deployment.

---

# 44. Patch Exceptions

A required security patch that cannot be deployed within the expected timeframe must be evaluated.

The exception should identify:

- Affected system
- Reason for delay
- Vulnerability
- Associated risk
- Compensating controls
- Planned resolution

Vulnerability-remediation requirements are established in [[PRO-004 Vulnerability Management Program]].

---

# 45. Application Changes

Application changes must follow controlled development and release requirements.

Application changes must consider:

- Business requirements
- Security requirements
- Testing
- Authorization
- Data integrity
- Rollback
- Documentation
- Production verification

Secure-development requirements are established in [[POL-012 Application & Secure Development Policy]].

---

# 46. Infinity Changes

Infinity changes require heightened control because the application supports Dunder Mifflin's digital ordering capability and depends on an external development contractor.

Infinity changes must address:

- Development, test, and production separation
- Source-code control
- Code review
- Security testing
- Contractor access
- Change authorization
- Rollback
- Documentation
- Production verification

Dunder Mifflin must retain ownership and control of applicable source code, repositories, documentation, data, intellectual property, backups, and work product.

---

# 47. Database Changes

Material database changes must receive appropriate control.

Changes should consider:

- Data integrity
- Application compatibility
- Access control
- Backup
- Recovery
- Rollback
- Transaction impact

Production database changes must be limited to authorized personnel.

---

# 48. Cloud-Service Changes

Material configuration changes to cloud-hosted resources must follow the same change-control principles as internally managed systems.

Cloud hosting does not eliminate Dunder Mifflin's responsibility to control configurations within its administrative authority.

Changes should consider:

- Access
- Network exposure
- Authentication
- Logging
- Backup
- Recovery
- Provider dependencies

---

# 49. Third-Party Changes

Third parties performing changes to Dunder Mifflin systems must follow applicable change-control requirements.

Contracts or service arrangements should require appropriate coordination for material changes affecting:

- Security
- Availability
- Data
- Integration
- Recovery

Third-party status does not exempt a change from authorization.

---

# 50. Contractor Changes

Contractors must:

- Operate within authorized scope.
- Follow approved change procedures.
- Use authorized access.
- Document material changes.
- Support testing and verification.
- Provide required technical documentation.

Contractor access requirements are established in [[POL-008 Third-Party Security Policy]] and applicable procedures.

---

# 51. Documentation Changes

Changes affecting significant system architecture or operation must trigger review of applicable documentation.

Documentation may include:

- Network diagrams
- System inventories
- Configuration records
- Administrative procedures
- Recovery procedures
- Application documentation
- Dependency information

Documentation must reflect material production conditions.

---

# 52. Asset Inventory Updates

Changes that materially add, remove, replace, or repurpose significant assets must trigger review of [[REG-001 Enterprise Asset Register]].

The asset inventory must not knowingly remain materially inaccurate after completed changes.

---

# 53. Business Impact Analysis Review

Changes affecting business dependencies or recovery requirements must trigger review of [[RPT-002 Business Impact Analysis]].

A technical change must not silently redefine:

- Business criticality
- Maximum Tolerable Downtime
- Recovery Time Objective
- Recovery Point Objective

Material changes to business recovery requirements require appropriate business review.

---

# 54. Risk Review

Changes that materially alter security exposure must trigger risk review.

Risk review may determine whether:

- An existing risk changed.
- A new risk exists.
- Existing treatment remains appropriate.
- A target residual risk should be revised.
- Additional controls are required.

Risk-management requirements are established in [[POL-005 Risk Management Policy]].

---

# 55. Significant Change and Reassessment

A material change may require reassessment of affected controls or risks.

Examples include:

- New Internet exposure
- Major authentication changes
- Significant application redesign
- Major infrastructure replacement
- New cloud dependency
- Major network changes
- Significant security-control changes
- Material third-party changes

Reassessment depth must be proportionate to impact.

---

# 56. Change Logging

Material change records must be retained according to applicable records requirements.

Records should support determination of:

- Request
- Approval
- Implementation
- Verification
- Failure
- Rollback
- Closure

Change records may also support incident investigation and security assessment.

---

# 57. Configuration Access

Ability to modify significant system configurations must be restricted to authorized personnel.

Configuration access must follow:

- Least privilege
- Appropriate authentication
- Privileged-access requirements
- Individual accountability

Access requirements are established in [[POL-003 Access Control Policy]].

---

# 58. Configuration Secrets

Configuration documentation containing:

- Passwords
- Cryptographic secrets
- Authentication information
- Sensitive security details

must receive protection appropriate to its classification.

Authentication secrets are Restricted information.

Configuration documentation must not unnecessarily contain authentication secrets.

---

# 59. Monitoring Changes

Significant changes should receive monitoring appropriate to their risk following implementation.

Monitoring may identify:

- Service failure
- Security-control failure
- Performance problems
- Unexpected authentication behavior
- Unexpected network activity
- Application errors

Monitoring duration should reflect the expected risk period.

---

# 60. Change-Related Incidents

When a change causes or contributes to a security incident, the incident must be managed under [[POL-009 Incident Response Policy]].

The review should determine whether the cause involved:

- Inadequate testing
- Inadequate approval
- Configuration error
- Undocumented dependency
- Inadequate rollback planning
- Unauthorized deviation
- Control failure

Lessons must inform future change management where appropriate.

---

# 61. Change-Related Findings

Material deficiencies identified through assessment must be documented.

Examples include:

- Unauthorized changes
- Missing approvals
- Missing testing
- Missing rollback plans
- Incomplete verification
- Unsupported configuration drift
- Missing configuration backups
- Recovery documentation not updated
- Repeated emergency-change misuse

Material corrective actions must be tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 62. Change Metrics

Change-management metrics may include:

- Successful change rate
- Failed change rate
- Emergency-change rate
- Unauthorized changes
- Changes requiring rollback
- Changes with missing documentation
- Changes causing incidents
- Configuration exceptions
- Overdue corrective actions

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 63. Emergency Change Trends

Emergency changes must be reviewed for patterns.

Repeated emergency changes involving the same system or process may indicate:

- Poor planning
- Inadequate maintenance
- Insufficient staffing
- Weak change discipline
- Technical instability

Emergency-change frequency should not be reduced artificially by misclassifying urgent changes.

---

# 64. Configuration Review

Significant configurations must be periodically reviewed according to risk.

Review may evaluate:

- Compliance with approved baselines
- Unauthorized services
- Unnecessary exposure
- Privileged access
- Security settings
- Configuration drift
- Documentation accuracy

Frequency must reflect system risk and available resources.

---

# 65. Assessment

Change and configuration controls must be periodically assessed.

Assessment may include:

- Inspection of change records
- Sampling changes
- Observation
- Technical Testing
- Configuration review
- Independent Performance
- Comparison of production configuration with approved requirements

Assessment should evaluate both control design and actual operation.

---

# 66. Evidence

Evidence may include:

- Change requests
- Approvals
- Test results
- Implementation records
- Rollback records
- Verification records
- Configuration files
- Configuration backups
- Updated documentation
- System logs
- Assessment results

Evidence must represent actual activity.

---

# 67. Evidence Integrity

Personnel must not:

- Manufacture change records
- Backdate approvals
- Record testing that did not occur
- Conceal failed changes
- Falsify verification
- Alter records to hide unauthorized changes

Control failure must be documented and addressed.

---

# 68. Risk Relationships

This policy provides significant treatment support for risks including:

- R003 Ransomware
- R004 Malware
- R006 Infinity Application Compromise
- R007 Internet Infrastructure Compromise
- R013 Administrative / Configuration Error
- R016 Cloud Service Outage
- R018 Third-Party Technology Failure / Compromise
- R019 Infinity Contractor Dependency / Compromise
- R027 Backup / Recovery Failure
- R028 Data Corruption

Risk treatment is documented in [[RTP-001 Enterprise Risk Treatment Plan]].

---

# 69. Exceptions

Exceptions to this policy require:

- Documented business justification
- Affected requirement
- Associated risk
- Defined duration
- Compensating controls where practical
- Responsible owner
- Appropriate approval

Exceptions must not be used to normalize uncontrolled changes.

High or Critical residual risk resulting from an exception requires escalation according to [[POL-005 Risk Management Policy]].

---

# 70. Enforcement

Failure to comply with this policy may result in:

- Change rejection
- Access restriction
- Corrective action
- Management review
- Personnel action
- Contractual action
- Risk escalation

Intentional unauthorized changes or concealment of material change failures must be escalated.

---

# 71. Policy Review

This policy must be reviewed:

- At least annually
- Following significant change-related incidents
- Following significant assessment findings
- Following material infrastructure changes
- Following material application changes
- When change-management requirements materially change

The CIO coordinates review.

Material revisions require appropriate approval.

---

# 72. Traceability

Change and configuration management must support the enterprise security lifecycle:

**Risk → Treatment → Policy/Standard → Change Requirement → Approved Change → Implementation → Evidence → Verification/Assessment → Finding → Remediation → Retest → Risk Reassessment**

Detailed relationships are maintained through [[REG-007 Cross-Reference Matrix]].

---

# 73. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-002 Enterprise Security Architecture Program]]
- [[PRO-009 Security Governance Framework]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[STD-002 Network Security Standard]]
- [[STD-003 Endpoint Security Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[STD-009 Infinity Security Standard]]
- [[PRO-004 Vulnerability Management Program]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-019 Application Security Assessment Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]
- [[REG-001 Enterprise Asset Register]]
- [[RPT-002 Business Impact Analysis]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[REG-007 Cross-Reference Matrix]]

---

# 74. Revision History

| Version | Date     | Description                                      | Approval |
| ------- | -------- | ------------------------------------------------ | -------- |
| 1.0     | May 2013 | Initial Change & Configuration Management Policy | CEO      |