# RPT-004 Infinity Transferability Review

## Document Control

| Field | Value |
|---|---|
| Document ID | RPT-004 |
| Title | Infinity Transferability Review |
| Version | 1.0 |
| Classification | Confidential |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Infinity Support, Architecture, Ownership, or Contractor Change |

---

# 1. Purpose

This review evaluates whether Dunder Mifflin retains sufficient ownership, information, access, documentation, and organizational capability to transfer support of the Infinity application from the current contractor to another qualified party without unacceptable business or security disruption.

The review supports treatment of:

**R019 Infinity Contractor**

and also supports management of:

- R006 Infinity Compromise
- R010 Unauthorized / Excessive Access
- R011 Delayed Termination
- R013 Administrative / Configuration Error
- R018 Third-Party Technology Failure / Compromise
- R026 Personnel Loss
- R027 Backup Failure
- R028 Data Corruption

---

# 2. Transferability Objective

Infinity must remain a Dunder Mifflin business asset rather than becoming operationally dependent on knowledge, access, documentation, or intellectual property controlled exclusively by the supporting contractor.

The transferability objective is:

> **Another appropriately qualified party should be able to assume Infinity support using Dunder Mifflin-controlled source code, documentation, access, configuration information, recovery information, and organizational knowledge without unreasonable dependence on the departing contractor.**

---

# 3. Scope

This review covers transferability of:

- Application ownership
- Source code
- Source repository
- Intellectual property
- Application data
- Documentation
- Build information
- Deployment information
- Configuration information
- Administrative knowledge
- Credentials and access
- Development environment
- Test environment
- Production environment
- Third-party dependencies
- Recovery information
- Backup information
- Security requirements
- Open defects
- Open security findings
- Change history
- Contractor knowledge

---

# 4. Out of Scope

This review does not determine:

- Whether the current contractor should be replaced
- Contractor performance unrelated to transferability
- General employee performance
- The commercial value of Infinity
- Whether all application vulnerabilities have been eliminated
- Whether every operational risk has been eliminated

Those matters are addressed through other governance, risk, contractual, assessment, and management processes.

---

# 5. Infinity Ownership

Dunder Mifflin owns applicable Infinity:

- Source code
- Repository
- Intellectual property
- Application data
- Documentation
- Work product
- Backups

Contractor support does not transfer ownership of these assets away from Dunder Mifflin.

---

# 6. Ownership Principle

Dunder Mifflin must remain capable of exercising control over Infinity independent of the continued availability or cooperation of a particular contractor.

Ownership should be demonstrable through actual possession and control of required assets rather than contractual language alone.

---

# 7. Contractor Role

The current third-party contractor supports Infinity.

Contractor support may include authorized:

- Development
- Troubleshooting
- Maintenance
- Testing
- Deployment support
- Production support

Contractor access must remain limited to authorized business need.

---

# 8. Contractor Dependency Risk

Contractor dependency becomes material when Dunder Mifflin cannot reasonably operate, maintain, recover, secure, or transfer Infinity without assistance from a particular external party.

Potential dependency conditions include:

- Contractor-exclusive source code
- Contractor-exclusive repository access
- Undocumented configuration
- Undocumented deployment process
- Contractor-controlled credentials
- Contractor-exclusive recovery knowledge
- Undocumented third-party dependencies
- Missing build instructions
- Missing administrative procedures
- Unrecorded application architecture
- Unresolved ownership ambiguity

---

# 9. Transferability Review Principle

The question is not:

> **Does Dunder Mifflin currently intend to replace the contractor?**

The question is:

> **Could Dunder Mifflin transfer support if it needed to?**

Transferability is a resilience and governance capability even when the existing contractor relationship is satisfactory.

---

# 10. Review Frequency

A formal Infinity transferability review is performed annually.

Additional review is required following a material change involving:

- Contractor relationship
- Application ownership
- Source repository
- Architecture
- Hosting
- Development process
- Deployment process
- Major third-party dependency
- Recovery process
- Material documentation structure

---

# 11. Review Responsibilities

## CIO

The CIO is accountable for ensuring the transferability review occurs and that material deficiencies receive appropriate management attention.

## IT & Information Security Manager

The IT & Information Security Manager coordinates applicable technical and security portions of the review.

## Application Support Personnel

Applicable personnel provide:

- Technical information
- Documentation
- Access information
- Configuration information
- Recovery information

## Contractor

The contractor provides required Dunder Mifflin-owned work product and documentation consistent with the support relationship.

## Information Security

Information Security evaluates security-related transferability concerns and control deficiencies.

---

# 12. Review Method

The transferability review may use:

- Documentation inspection
- Repository inspection
- Access review
- Interviews
- Configuration review
- Recovery-document review
- Sampling
- Independent Performance
- Technical validation

The depth of testing should reflect risk and the condition being evaluated.

---

# 13. Review Evidence

Evidence may include:

- Source repository records
- Source-code availability
- Ownership documentation
- Application architecture documentation
- Build instructions
- Deployment instructions
- Configuration records
- Access records
- Administrative procedures
- Backup records
- Recovery documentation
- Change records
- Security assessment records
- Penetration-test records
- Contractor-access records
- Third-party dependency documentation

---

# 14. Evidence Integrity

Review conclusions must be based on available evidence.

Do not:

- Fabricate documentation.
- Backdate records.
- Claim source possession that cannot be demonstrated.
- Claim successful transferability testing that did not occur.
- Treat verbal knowledge as documented knowledge when no documentation exists.
- Treat contractor possession as equivalent to Dunder Mifflin control.

---

# 15. Transferability Review Areas

The review evaluates ten primary areas:

1. Ownership
2. Source and Repository
3. Architecture
4. Build and Deployment
5. Configuration
6. Access and Credentials
7. Documentation
8. Dependencies
9. Recovery
10. Knowledge Transfer

---

# 16. Area 1: Ownership

Verify that Dunder Mifflin retains ownership or appropriate organizational control of applicable:

- Source code
- Repository
- Intellectual property
- Application data
- Documentation
- Work product
- Backups

---

# 17. Ownership Review

| Review Item | Result | Evidence | Deficiency / Comment |
|---|---|---|---|
| Dunder Mifflin ownership of source code confirmed | | | |
| Repository control confirmed | | | |
| Intellectual property ownership confirmed | | | |
| Application-data ownership confirmed | | | |
| Documentation ownership confirmed | | | |
| Contractor work-product ownership confirmed | | | |
| Backup ownership / control confirmed | | | |

---

# 18. Ownership Concern

A contract stating that Dunder Mifflin owns source code is not sufficient if the company cannot actually obtain or access the current source.

Legal ownership and operational control must support one another.

---

# 19. Area 2: Source and Repository

Verify that Dunder Mifflin can access the current authoritative Infinity source.

Review:

- Repository location
- Repository ownership
- Administrative control
- Source completeness
- Current branch or version
- Change history
- Access restrictions
- Backup

---

# 20. Source Repository Review

| Review Item | Result | Evidence | Deficiency / Comment |
|---|---|---|---|
| Authoritative repository identified | | | |
| Dunder Mifflin retains repository access | | | |
| Dunder Mifflin retains appropriate administrative control | | | |
| Current production source is identifiable | | | |
| Change history is available | | | |
| Repository access is restricted appropriately | | | |
| Repository backup is available | | | |

---

# 21. Source Availability

A qualified replacement party should not need to reconstruct Infinity from:

- Production binaries
- Contractor laptops
- Email attachments
- Obsolete source copies
- Undocumented local files

The authoritative source should be identifiable and controlled.

---

# 22. Area 3: Architecture

Architecture documentation should provide sufficient understanding of:

- Public web tier
- Application tier
- Database tier
- Data flows
- Trust relationships
- External interfaces
- Administrative paths
- Security boundaries
- Major dependencies

---

# 23. Architecture Review

| Review Item | Result | Evidence | Deficiency / Comment |
|---|---|---|---|
| Application architecture documented | | | |
| Web tier documented | | | |
| Application tier documented | | | |
| Database tier documented | | | |
| Major data flows documented | | | |
| External interfaces documented | | | |
| Administrative paths documented | | | |
| Security boundaries documented | | | |

---

# 24. Architecture Security

Infinity maintains logical separation between:

- Web
- Application
- Database

The database is not directly Internet accessible.

Transfer documentation should preserve sufficient information to maintain these security characteristics during support transition.

---

# 25. Area 4: Build and Deployment

A qualified replacement party should be able to determine how Infinity is:

- Built
- Tested
- Packaged
- Configured
- Released
- Deployed
- Verified
- Rolled back where applicable

---

# 26. Build Review

| Review Item | Result | Evidence | Deficiency / Comment |
|---|---|---|---|
| Build instructions available | | | |
| Required development tools identified | | | |
| Required libraries identified | | | |
| Required dependencies identified | | | |
| Build configuration documented | | | |
| Build output identifiable | | | |

---

# 27. Deployment Review

| Review Item | Result | Evidence | Deficiency / Comment |
|---|---|---|---|
| Deployment procedure documented | | | |
| Environment-specific requirements documented | | | |
| Required approvals documented | | | |
| Required testing documented | | | |
| Verification process documented | | | |
| Rollback process documented where applicable | | | |

---

# 28. Secure Change and Release

Infinity changes are governed by:

[[PROC-018 Secure Change & Release Procedure]]

Transferability documentation should allow a replacement support party to continue operating within the established change process.

---

# 29. Area 5: Configuration

Review whether significant Infinity configuration is:

- Identified
- Documented
- Protected
- Recoverable
- Understandable by qualified personnel

---

# 30. Configuration Review

| Review Item | Result | Evidence | Deficiency / Comment |
|---|---|---|---|
| Application configuration documented | | | |
| Web configuration documented | | | |
| Database configuration documented | | | |
| Security-relevant configuration documented | | | |
| External integration configuration documented | | | |
| Recovery configuration documented | | | |
| Configuration backup available where appropriate | | | |

---

# 31. Configuration Knowledge

Critical configuration knowledge should not exist solely:

- In one person's memory
- On one contractor-controlled device
- In undocumented scripts
- In inaccessible accounts
- In an unavailable external system

---

# 32. Area 6: Access and Credentials

Transferability requires Dunder Mifflin to retain administrative control sufficient to authorize a replacement party.

Review applicable access to:

- Source repository
- Development environment
- Test environment
- Production environment
- Database administration
- Hosting administration
- Backup systems
- Supporting services

---

# 33. Access Review

| Review Item | Result | Evidence | Deficiency / Comment |
|---|---|---|---|
| Repository administrative access controlled | | | |
| Development access controlled | | | |
| Test access controlled | | | |
| Production access controlled | | | |
| Database administrative access controlled | | | |
| Hosting administration controlled | | | |
| Backup administration controlled | | | |
| Contractor access can be revoked | | | |

---

# 34. Credential Ownership

A contractor must not become the exclusive holder of credentials required to:

- Administer Infinity
- Recover Infinity
- Access the authoritative source
- Manage required infrastructure
- Manage critical supporting services

---

# 35. Privileged Contractor Access

Privileged contractor production or administrative activity is limited to authorized arrangements.

The approved model includes:

- Named contractor personnel
- Sponsorship
- Time-limited access
- Least privilege
- Individual accountability
- Controlled privileged production activity
- Designated Headquarters contractor workspace
- No general contractor VPN access

---

# 36. Contractor Personnel Identification

Expected contractor personnel should be identified at least one business day before scheduled arrival where practical.

Emergency exceptions must be documented.

---

# 37. Contractor Access Termination

Dunder Mifflin must be able to revoke contractor access without requiring cooperation from the contractor being removed.

This includes applicable:

- Logical access
- Privileged access
- Physical access
- Credentials
- Tokens
- Keys
- Access cards

---

# 38. Area 7: Documentation

Documentation should be sufficient for a qualified party unfamiliar with the current contractor's internal knowledge to understand and support Infinity.

---

# 39. Required Documentation Areas

Documentation should address applicable:

- Architecture
- Build
- Deployment
- Configuration
- Administration
- Security
- Dependencies
- Troubleshooting
- Backup
- Recovery
- Change
- Access
- Contacts

---

# 40. Documentation Review

| Documentation Area | Available | Current | Sufficient | Evidence / Comment |
|---|---|---|---|---|
| Architecture | | | | |
| Build | | | | |
| Deployment | | | | |
| Configuration | | | | |
| Administration | | | | |
| Security | | | | |
| Dependencies | | | | |
| Troubleshooting | | | | |
| Backup | | | | |
| Recovery | | | | |
| Change | | | | |
| Access administration | | | | |

---

# 41. Documentation Quality

Documentation does not need to explain basic professional knowledge to a qualified replacement party.

It must document Dunder Mifflin-specific information that the replacement party could not reasonably know independently.

---

# 42. Documentation Currency

Documentation should be reviewed following material:

- Architecture change
- Configuration change
- Deployment-process change
- Recovery-process change
- Dependency change

A significant technical or configuration change is not complete until applicable recovery and support documentation has been reviewed and updated.

---

# 43. Area 8: Dependencies

Infinity transferability depends on understanding external and internal dependencies.

These may include:

- Hosting services
- Database services
- Domain Name System
- Certificates
- Email services
- Payment-related interfaces
- Libraries
- Application components
- External services
- Administrative tools
- Business processes

---

# 44. Dependency Review

| Review Item | Result | Evidence | Deficiency / Comment |
|---|---|---|---|
| Major internal dependencies documented | | | |
| Major external dependencies documented | | | |
| Third-party services identified | | | |
| Administrative ownership identified | | | |
| Renewal requirements identified where applicable | | | |
| Security dependencies identified | | | |
| Recovery dependencies identified | | | |

---

# 45. Hidden Dependency Risk

A dependency that is understood only by the current contractor may prevent successful transfer even when source code is available.

Transferability requires both code and operational context.

---

# 46. Area 9: Recovery

A replacement support party should be able to understand how Infinity is recovered.

Recovery documentation should address applicable:

- Backup sources
- Application restoration
- Database restoration
- Configuration restoration
- Required dependencies
- Recovery sequence
- Validation
- Business verification

---

# 47. Recovery Review

| Review Item | Result | Evidence | Deficiency / Comment |
|---|---|---|---|
| Infinity backup sources identified | | | |
| Application recovery documented | | | |
| Database recovery documented | | | |
| Configuration recovery documented | | | |
| Recovery dependencies documented | | | |
| Recovery sequence documented | | | |
| Technical validation documented | | | |
| Business validation documented | | | |

---

# 48. Recovery Documentation

Recovery information should be sufficiently independent of the current contractor that Dunder Mifflin can provide it to another qualified party.

Recovery capability is governed by:

- [[PLN-003 Disaster Recovery Plan]]
- [[PROC-012 Backup & Recovery Procedure]]

---

# 49. Area 10: Knowledge Transfer

Transferability requires sufficient organizational knowledge to explain:

- What Infinity does
- How the business uses it
- Who owns it
- How it is supported
- How changes are authorized
- Where required documentation exists
- Where required source and configuration information exists
- How support should be transferred

---

# 50. Knowledge Review

| Review Item | Result | Evidence | Deficiency / Comment |
|---|---|---|---|
| Business owner identifiable | | | |
| Technical owner identifiable | | | |
| Security responsibilities identifiable | | | |
| Support process documented | | | |
| Escalation process documented | | | |
| Required internal contacts identifiable | | | |
| Required external contacts identifiable | | | |
| Documentation locations known | | | |

---

# 51. Key-Person Dependency

Transferability should reduce dependency on:

- One contractor
- One developer
- One administrator
- One undocumented specialist

This supports treatment of:

**R026 Personnel Loss**

---

# 52. Transfer Scenario

The annual review should consider a scenario in which the current contractor becomes unavailable with limited notice.

The review should ask whether Dunder Mifflin can:

1. Revoke the former contractor's access.
2. Retain authoritative source code.
3. Retain repository control.
4. Retain application data.
5. Retain required documentation.
6. Identify required infrastructure.
7. Identify required credentials.
8. Provide access to a replacement party.
9. Explain the application architecture.
10. Explain the build and deployment process.
11. Explain significant dependencies.
12. Recover the application if necessary.
13. Continue controlled change and release.

---

# 53. Transferability Test

Where appropriate, selected transferability procedures may be performed independently to determine whether documentation and organizational control are sufficient.

Examples include:

- Locating the authoritative repository without contractor assistance
- Retrieving required documentation
- Identifying production configuration
- Identifying recovery information
- Following documented build instructions
- Following documented deployment instructions in a nonproduction environment
- Identifying required dependencies

Testing must not create unnecessary production risk.

---

# 54. Independent Performance

Independent Performance may be used when direct execution provides stronger evidence than document inspection alone.

The reviewer may perform an approved procedure using existing documentation and authorized access.

The purpose is to determine whether the procedure can be completed without undocumented contractor knowledge.

---

# 55. Production Protection

Transferability testing should not introduce unnecessary production changes.

Where practical, technical validation should use:

- Development
- Test
- Existing backups
- Documentation review
- Controlled read-only inspection

Production activity must follow established change and access requirements.

---

# 56. Review Result Categories

Each review area may be classified as:

### Satisfactory

Available evidence supports the transferability objective.

### Partially Satisfactory

The objective is substantially supported, but one or more deficiencies require correction.

### Unsatisfactory

Material deficiencies prevent reasonable confidence in transferability.

### Unable to Determine

Available evidence is insufficient to reach a supported conclusion.

---

# 57. Overall Transferability Rating

The overall review may use:

- Satisfactory
- Partially Satisfactory
- Unsatisfactory
- Unable to Determine

The overall rating must reflect supporting evidence and must not be assigned solely by averaging individual review areas.

---

# 58. Transferability Review Summary

| Review Area | Result | Material Deficiency | Corrective Action Required |
|---|---|---|---|
| Ownership | | | |
| Source and Repository | | | |
| Architecture | | | |
| Build and Deployment | | | |
| Configuration | | | |
| Access and Credentials | | | |
| Documentation | | | |
| Dependencies | | | |
| Recovery | | | |
| Knowledge Transfer | | | |

---

# 59. Overall Review Result

| Field | Result |
|---|---|
| Overall Transferability Rating | |
| Material Deficiencies Identified | |
| Formal Findings Required | |
| Immediate Management Action Required | |
| R019 Reassessment Required | |
| Next Review Date | |

No result is populated in this portfolio artifact without supporting review evidence.

---

# 60. Deficiency Evaluation

A deficiency should be evaluated based on:

- Importance to support transfer
- Business impact
- Security impact
- Recovery impact
- Availability of compensating information
- Difficulty of correction
- Related risk

---

# 61. Formal Findings

Material deficiencies requiring corrective action should be recorded in:

[[REG-004 Finding & Corrective Action Register]]

Examples may include:

- Missing authoritative source
- Missing critical deployment documentation
- Contractor-exclusive administrative credential
- Undocumented recovery dependency
- Missing repository control
- Material ownership ambiguity
- Inability to identify production configuration

These examples are illustrative and do not represent actual findings.

---

# 62. Corrective Action

Corrective action may include:

- Obtaining missing documentation
- Transferring repository control
- Establishing Dunder Mifflin administrative access
- Documenting configuration
- Documenting dependencies
- Updating recovery procedures
- Removing contractor-exclusive credentials
- Performing knowledge transfer
- Updating contractual requirements

---

# 63. Validation

Corrective action is not complete merely because a document, account, or procedure has been created.

Validation should determine whether the corrected condition actually supports transferability.

---

# 64. Retest

A material transferability finding may require retesting.

Retesting should determine whether:

- The deficiency was corrected.
- Required information is available.
- Required access works.
- Documentation is usable.
- A qualified party can perform the required activity.

---

# 65. Failed Retest

If retesting fails:

- The finding remains visible.
- Corrective action should be revised.
- Control effectiveness should reflect the result.
- R019 may require reassessment.
- Management should be notified when appropriate.

---

# 66. R019 Infinity Contractor

R019 addresses the risk that Dunder Mifflin becomes excessively dependent on the Infinity contractor or that contractor access creates unacceptable exposure.

Risk values are:

| Risk View | Rating |
|---|---|
| Inherent Risk | 12 High |
| Current Residual Risk | 8 Moderate |
| Target Residual Risk | 4 Low |

---

# 67. R019 Treatment

Treatment includes:

- Dunder Mifflin ownership of source, repository, documentation, intellectual property, data, and backups
- Confidentiality requirements
- Sponsored contractor access
- Time-limited access
- Smart-card multifactor authentication where supported
- No general contractor VPN
- Controlled privileged production activity
- Designated Headquarters contractor workspace
- Least privilege
- Expected personnel identification
- Change control
- Code review
- Security testing
- Annual Infinity security assessment
- Annual application penetration testing
- Remediation and retesting
- Documentation
- Annual transferability review

---

# 68. Current Versus Target Risk

The annual transferability review supports treatment of R019.

The target residual risk of:

**4 Low**

is a prediction.

The existence of this review document does not by itself reduce R019.

Risk reduction requires implementation, evidence, validation, and documented risk reassessment.

---

# 69. No Premature Risk Credit

Do not reduce R019 current residual risk because:

- The review is scheduled.
- The review template exists.
- Documentation is requested.
- Corrective action is planned.
- A contractor states that transfer is possible.

Evidence must support the conclusion.

---

# 70. Relationship to R006

R006 Infinity Compromise concerns compromise of the Infinity application.

Transferability supports R006 treatment by helping Dunder Mifflin retain:

- Application knowledge
- Secure configuration knowledge
- Recovery capability
- Source control
- Controlled administrative capability

Transferability does not replace application security testing.

---

# 71. Relationship to R010

R010 Unauthorized / Excessive Access is supported by ensuring that contractor access:

- Is authorized
- Is limited
- Is individually attributable
- Can be reviewed
- Can be revoked

---

# 72. Relationship to R011

R011 Delayed Termination is supported by ensuring that Dunder Mifflin can promptly revoke contractor access without depending on contractor cooperation.

---

# 73. Relationship to R013

R013 Administrative / Configuration Error is supported by maintaining sufficient configuration and deployment documentation.

A replacement party should not need to guess at critical production configuration.

---

# 74. Relationship to R018

R018 Third-Party Technology Failure / Compromise is supported by reducing dependency on a single external support provider.

---

# 75. Relationship to R026

R026 Personnel Loss is supported by reducing exclusive knowledge held by one contractor or specialist.

---

# 76. Relationship to R027

R027 Backup Failure is supported by ensuring that Infinity backup and recovery information remains available to Dunder Mifflin.

---

# 77. Relationship to R028

R028 Data Corruption is supported by documented recovery, configuration, and validation procedures that can be used by qualified replacement personnel.

---

# 78. Contractor Departure

If contractor support ends, Dunder Mifflin should coordinate:

1. Access review
2. Access revocation
3. Physical credential recovery
4. Logical credential removal
5. Repository-access review
6. Source verification
7. Documentation verification
8. Open-change review
9. Open-defect review
10. Open-security-finding review
11. Recovery-information verification
12. Knowledge transfer where available
13. Replacement-support authorization

---

# 79. Unexpected Contractor Unavailability

The transferability program must not depend on an orderly contractor departure.

Dunder Mifflin should retain enough organizational control to respond if the contractor becomes unexpectedly unavailable.

---

# 80. Emergency Support Transition

During an urgent support transition:

- Protect production.
- Preserve source and documentation.
- Restrict access.
- Establish accountable replacement access.
- Maintain change control.
- Preserve evidence.
- Prioritize recovery and business continuity.
- Avoid unnecessary emergency changes.

---

# 81. New Contractor Access

A replacement contractor must not automatically inherit the former contractor's access.

New access must follow:

[[PROC-004 Contractor Access Procedure]]

and:

[[PROC-020 Contractor Development Access Procedure]]

---

# 82. New Contractor Confidentiality

A replacement contractor receiving sensitive access must have an appropriate Non-Disclosure Agreement or equivalent enforceable confidentiality obligation before receiving that access.

Confidentiality does not replace technical access controls.

---

# 83. New Contractor Privilege

Replacement support personnel receive only the access required for authorized responsibilities.

Privileged access should:

- Be individually attributable
- Be separated from ordinary access
- Be time-limited where appropriate
- Be reviewed
- Be removed when no longer required

---

# 84. Transfer and Change Control

Support transfer does not suspend normal change-control requirements.

Changes should continue to follow:

[[PROC-018 Secure Change & Release Procedure]]

Emergency changes should use the approved emergency-change process.

---

# 85. Open Security Findings

A transfer does not close existing security findings.

Open findings remain tracked through:

[[REG-004 Finding & Corrective Action Register]]

The new support party must receive applicable information needed to perform authorized corrective work.

---

# 86. Security Assessment History

Applicable Infinity assessment history should remain under Dunder Mifflin control.

This may include:

- Security assessments
- Penetration tests
- Findings
- Corrective actions
- Retests
- Relevant risk decisions

---

# 87. Penetration Testing

Infinity receives an annual application-focused penetration test.

Testing is governed by:

[[STD-007 Penetration Testing Standard]]

and:

[[PROC-019 Application Security Assessment Procedure]]

---

# 88. Assessment Chain

The Infinity assurance chain is:

**Assessment / Penetration Test → Finding → Remediation → Retest → Control Effectiveness → R006 Risk Reassessment**

Transferability documentation should preserve enough history for a replacement support party to understand unresolved security conditions.

---

# 89. Recovery Requirements

Infinity is rated Moderate in the Business Impact Analysis.

The established values are:

| Requirement | Value |
|---|---|
| Maximum Tolerable Downtime | 3 days |
| Recovery Time Objective | 24 hours |
| Recovery Point Objective | 4 hours |

Transferability should support these requirements rather than create a support transition that makes them unattainable.

---

# 90. Business Continuity

If contractor loss contributes to an Infinity outage, response should coordinate with:

- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PROC-013 Manual Processing Procedure]]

---

# 91. Transferability Metrics

Applicable measures may include:

- Required documentation available
- Required documentation current
- Dunder Mifflin repository access verified
- Administrative control verified
- Contractor-exclusive credentials identified
- Material transferability findings
- Overdue transferability corrective actions
- Transferability retests passed
- Annual review completion

Metric definitions should align with:

[[REG-005 Security Metrics Catalog]]

---

# 92. Management Reporting

Material transferability conditions should be reported through:

[[RPT-007 Management Security Report]]

Management reporting should emphasize:

- Accountability
- Deficiencies
- Corrective action
- Transfer dependency
- Risk impact

---

# 93. Executive Reporting

A transferability condition should be elevated to:

[[RPT-006 Executive Security Summary]]

when it creates material enterprise risk or requires executive action.

---

# 94. Operational Reporting

Applicable operational conditions should be reflected in:

[[RPT-008 Operational Security Report & Dashboard]]

---

# 95. Assessment Work Plan

A detailed transferability assessment may use:

[[TMP-001 Assessment Work Plan Template]]

The work plan should define:

- Objective
- Scope
- Requirements
- Evidence
- Assessment method
- Sample
- Procedure
- Expected result
- Reporting

---

# 96. Assurance

The transferability review operates under:

[[PRO-008 Security Assurance & Continuous Improvement Program]]

Review evidence should support conclusions about whether relevant controls are:

- Appropriately designed
- Implemented
- Operating
- Achieving the intended outcome

---

# 97. Review Independence

The annual review should include sufficient independence to avoid relying entirely on the contractor whose transferability is being evaluated.

The contractor may provide evidence and technical information.

The contractor should not be the sole party determining whether Dunder Mifflin can operate independently of that contractor.

---

# 98. Continuous Improvement

Transferability should improve through:

**Review → Deficiency → Finding → Corrective Action → Validation → Retest → Risk Reassessment**

---

# 99. Historical Integrity

Preserve applicable:

- Prior review results
- Identified deficiencies
- Findings
- Corrective actions
- Retest results
- Risk reassessments

A later satisfactory result must not erase earlier deficiencies.

---

# 100. Review Approval

The completed annual transferability review should identify:

| Field | Entry |
|---|---|
| Review Date | |
| Review Lead | |
| Technical Participants | |
| Contractor Participants | |
| Overall Result | |
| Findings Created | |
| Corrective Actions Required | |
| R019 Reassessment Required | |
| Management Review Date | |
| CIO Approval | |

---

# 101. Review Conclusion

Infinity transferability is a business resilience, security, and governance requirement.

Dunder Mifflin should be able to change support providers without losing control of:

- Source
- Data
- Documentation
- Configuration
- Credentials
- Recovery capability
- Security history
- Operational knowledge

The objective is not to eliminate the value of contractor expertise.

The objective is to prevent contractor expertise from becoming an uncontrolled single point of dependency.

The transferability principle is:

> **Dunder Mifflin may depend on qualified external expertise, but it must retain control of the information and authority required to transfer that expertise.**

---

# 102. Related Artifacts

## Enterprise Context

- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[REG-001 Enterprise Asset Register]]
- [[RPT-002 Business Impact Analysis]]

## Risk Management

- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]

## Governance and Policy

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[POL-003 Access Control Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-012 Application & Secure Development Policy]]

## Identity and Access Management

- [[PRO-003 Identity and Access Management Program]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]

## Vulnerability and Security Assessment

- [[STD-007 Penetration Testing Standard]]

## Business Continuity and Disaster Recovery

- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-013 Manual Processing Procedure]]

## Secure Development

- [[PRO-007 Secure Software Development Lifecycle Program]]
- [[STD-009 Infinity Security Standard]]
- [[PROC-018 Secure Change & Release Procedure]]
- [[PROC-019 Application Security Assessment Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]

## Assurance, Metrics, and Improvement

- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[PLN-005 Annual Assurance Plan]]
- [[TMP-001 Assessment Work Plan Template]]

## Reporting

- [[RPT-006 Executive Security Summary]]
- [[RPT-007 Management Security Report]]
- [[RPT-008 Operational Security Report & Dashboard]]

---

# 103. Revision History

| Version | Date     | Description                             | Approval |
| ------- | -------- | --------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Infinity Transferability Review | CEO      |