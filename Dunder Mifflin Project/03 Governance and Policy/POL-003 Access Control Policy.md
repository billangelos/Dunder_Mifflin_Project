# POL-003 Access Control Policy

## Document Control

| Field | Value |
|---|---|
| Document ID | POL-003 |
| Title | Access Control Policy |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Change |

---

# 1. Purpose

This policy establishes requirements for controlling access to Dunder Mifflin information, systems, applications, networks, and other technology resources.

Access must be granted according to legitimate business need and limited according to the principles of:

- Least privilege
- Need to know
- Individual accountability
- Appropriate authorization
- Separation of duties
- Timely access removal

Access must not be granted solely because of organizational seniority, convenience, or technical capability.

---

# 2. Scope

This policy applies to:

- Employees
- Executives
- Temporary personnel
- Contractors
- Consultants
- Third-party users
- User accounts
- Administrative accounts
- Service accounts
- Emergency accounts
- Applications
- Servers
- Endpoints
- Networks
- Cloud-hosted resources
- Business systems
- Remote access

Physical access requirements are governed principally by [[POL-011 Physical & Environmental Security Policy]].

---

# 3. Objectives

Access controls must:

1. Limit access to authorized individuals.
2. Limit permissions to legitimate business need.
3. Support individual accountability.
4. Protect privileged access.
5. Remove access when business need ends.
6. Adjust access when responsibilities change.
7. Restrict third-party access.
8. Identify inappropriate or unnecessary access.
9. Support investigation of security events.
10. Reduce unauthorized access to sensitive information.
11. Maintain appropriate emergency access.
12. Support practical separation of duties.

---

# 4. Access Control Principles

## 4.1 Least Privilege

Users must receive only the access reasonably required to perform authorized responsibilities.

Additional access must require legitimate business justification.

---

## 4.2 Need to Know

Access to sensitive information must be limited to personnel with an authorized business need.

Technical ability to access information does not independently establish authorization.

---

## 4.3 Individual Accountability

Access should be attributable to an individual where practical.

Individually assigned accounts must be used when individual accountability is required.

Shared access may be permitted only when justified by operational requirements and appropriately controlled.

---

## 4.4 Default Restriction

Access not specifically authorized should be restricted.

The absence of an explicit technical restriction does not grant permission to access information or systems.

---

## 4.5 Separation of Duties

Access must support practical separation of duties where combining responsibilities would create unreasonable opportunity for:

- Fraud
- Unauthorized transactions
- Concealment
- Unreviewed administrative activity
- Inappropriate approval

Separation must remain proportionate to Dunder Mifflin's size and staffing.

---

# 5. Access Ownership

Access decisions require appropriate business authority.

Depending on the resource, approval may involve:

- Manager
- Business owner
- Information owner
- System owner
- Application owner
- CIO
- Designated IT authority

Information Technology personnel administer access but must not independently grant business permissions without required authorization.

---

# 6. Access Requests

Access requests must identify:

- User
- Resource
- Required access
- Business need
- Requesting or approving manager
- Applicable owner approval
- Duration where temporary
- Special privileges where applicable

Requests for sensitive or privileged access require additional review appropriate to the risk.

---

# 7. Access Approval

Access must be approved before being granted.

Approval must establish:

- Legitimate business need
- Appropriate access level
- Appropriate duration
- Required separation of duties
- Information sensitivity
- Applicable security requirements

Approval authority must be appropriate to the resource.

---

# 8. Access Provisioning

Authorized access must be provisioned according to approved requests.

Provisioning personnel must:

- Verify required approval.
- Assign the appropriate account.
- Grant only approved permissions.
- Avoid unnecessary group membership.
- Record significant access assignments.
- Apply required authentication controls.

Access must not exceed approved business need.

---

# 9. Unique User Accounts

Personnel must normally use individually assigned accounts.

Individual accounts must not be shared.

Exceptions may exist for:

- Approved shared operational workstations
- Service accounts
- Emergency accounts
- Other specifically authorized technical requirements

Exceptions must preserve individual accountability where the business activity requires it.

---

# 10. Authentication

Users must authenticate using approved authentication methods.

Authentication requirements must reflect:

- Resource sensitivity
- Access type
- Privilege
- Exposure
- Business risk

Authentication controls are further defined in [[STD-005 Authentication & Account Security Standard]].

---

# 11. Passwords and Authentication Secrets

Authentication secrets must be protected.

Users must not:

- Share individually assigned passwords.
- Disclose authentication secrets.
- Store secrets insecurely.
- Use another person's credentials.
- Permit another person to use their individually assigned credentials.

Suspected credential compromise must be reported promptly.

---

# 12. Multi-Factor Authentication

Smart-card multi-factor authentication using a card and PIN or other approved secret must be implemented where supported and required by risk.

Priority should be given to:

- Privileged access
- Sensitive systems
- Remote access
- Higher-risk authentication scenarios

Where a system cannot support the required stronger authentication, management must evaluate the risk and determine appropriate compensating controls.

---

# 13. Standard User Access

Ordinary users must operate without local administrative privileges unless a documented business or technical requirement justifies an exception.

Standard user access must be sufficient for normal authorized work without granting unnecessary administrative capability.

---

# 14. Privileged Access

Privileged access must receive additional protection.

Privileged access must:

- Be limited to authorized personnel.
- Be based on job responsibility.
- Use separate privileged credentials where required.
- Be used only when elevated permissions are necessary.
- Receive periodic review.
- Be appropriately logged.
- Be promptly removed when no longer required.

Privileged access must not be granted merely because an individual holds a senior position.

---

# 15. Separate Privileged Credentials

Personnel requiring administrative access must use separate credentials for privileged and ordinary activity where supported.

Privileged credentials must not be used for routine activities such as:

- General email
- Ordinary Internet use
- Routine document preparation
- Normal business application use

This separation reduces exposure of highly privileged credentials.

---

# 16. Domain Administrator Access

Standing Domain Administrator membership must be restricted to personnel with a continuing administrative requirement.

Standing Domain Administrator access should normally be limited to:

- IT & Information Security Manager
- System Administrator

Additional standing membership requires documented justification and appropriate approval.

Other authorized administrators should receive only the privileges required for their responsibilities.

---

# 17. Administrative Workstations

Privileged administration of significant systems must be performed from designated administrative workstations where required.

Administrative workstations must be:

- Company controlled
- Appropriately secured
- Restricted to authorized administrators
- Maintained according to applicable endpoint-security requirements

Administrative workstations should not be used for unnecessary general Internet activity.

---

# 18. Remote Privileged Administration

External remote privileged administration is prohibited.

Privileged administration of significant production resources must occur through approved company-controlled methods and locations.

Ordinary authorized remote access does not authorize privileged administration.

Emergency-access procedures do not create an exception to the prohibition on external remote privileged administration.

---

# 19. Privileged Access Review

Privileged access must be reviewed at least quarterly.

The review must determine whether:

- The user remains authorized.
- Privileged access remains necessary.
- The privilege level remains appropriate.
- Unnecessary access should be removed.
- Dormant privileged accounts exist.
- Separation-of-duties concerns exist.

Material deficiencies must be corrected.

---

# 20. Ordinary User Access Review

Ordinary user access must be reviewed at least annually.

Reviews should consider:

- Employment status
- Current job responsibilities
- Business need
- Sensitive access
- Excessive permissions
- Unnecessary group membership

Access that is no longer justified must be removed.

---

# 21. Joiner Process

New personnel must receive access based on approved business need.

The joiner process must include, as applicable:

1. Confirmation of employment or authorized relationship.
2. Manager identification.
3. Required owner approval.
4. Account creation.
5. Appropriate role assignment.
6. Required authentication setup.
7. Security-awareness requirements.
8. Facility-access coordination where applicable.

New personnel must not automatically inherit access solely because another employee in a similar position possesses it.

---

# 22. Mover Process

A material change in job responsibility requires access reevaluation.

For material transfers:

1. Existing business permissions must be reviewed.
2. Permissions associated with the previous role must be revoked unless independently justified.
3. New access must be authorized according to the new role.
4. Privileged access must receive specific review.
5. Physical access must be reviewed where applicable.

The preferred approach is to begin the new role with no inherited business permissions except those independently justified and reauthorized.

Transfer processing must not assume that old access remains appropriate.

---

# 23. Leaver Process

Access must be removed promptly when an individual's authorized relationship with Dunder Mifflin ends.

The process must address, where applicable:

- User accounts
- Privileged accounts
- Application access
- Remote access
- Cloud services
- Company equipment
- Smart cards
- Access cards
- Keys
- Shared secrets
- Other company credentials

Human Resources is the authoritative business source for employee termination status.

---

# 24. Termination Notification

Human Resources must provide termination information to personnel responsible for removing access.

Notification must occur early enough to permit access removal at the appropriate termination time.

For urgent or involuntary termination, coordination may occur immediately before access removal to reduce inappropriate advance disclosure.

---

# 25. Termination Timing

Access must be disabled promptly when employment or other authorized access ends.

High-risk access may require coordinated disablement at the time the individual is notified of termination.

Unnecessary delay must be treated as an access-control deficiency.

---

# 26. Termination Verification

The termination process must use a documented checklist or equivalent record.

Completion should verify applicable removal of:

- Network accounts
- Application accounts
- Privileged accounts
- Remote access
- Facility access
- Company equipment
- Keys/cards
- Smart cards
- Other credentials

Termination-control performance must be periodically tested.

---

# 27. Dormant Accounts

Dormant accounts must be reviewed.

An account with no expected activity for 30 days must be investigated to determine whether continued access remains justified.

An unjustified account remaining dormant for 60 days must be disabled.

Exceptions may include:

- Approved service accounts
- Emergency accounts
- Seasonal or temporary business requirements
- Other documented operational requirements

Dormancy alone must not result in automatic disabling of an account when doing so would create unacceptable operational risk without appropriate review.

---

# 28. Disabled Accounts

Disabled accounts should remain unavailable for authentication.

Retention of disabled account records may be necessary for:

- Audit history
- Investigation
- Business records
- System dependencies

Disabling an account does not require immediate deletion.

---

# 29. Contractor Access

Contractor access must:

- Have an identified sponsor.
- Have documented business need.
- Be limited to required resources.
- Be time limited.
- Receive appropriate authentication.
- Be reviewed before renewal.
- End when the authorized need ends.

Initial contractor access should not exceed three months unless a shorter period is appropriate.

Renewals must not exceed six months without another review and authorization.

---

# 30. Contractor Confidentiality

Contractors receiving access to sensitive information must have an enforceable confidentiality obligation in place before sensitive access is provided.

Confidentiality requirements are based on the nature of access and information sensitivity rather than contractor title.

---

# 31. Third-Party Access

Third-party access must be:

- Authorized
- Business justified
- Limited
- Appropriately authenticated
- Monitored according to risk
- Removed when no longer required

Third-party access must comply with [[POL-008 Third-Party Security Policy]].

---

# 32. Infinity Contractor Access

Infinity contractor access requires additional controls.

Requirements include:

- Management sponsorship
- Time-limited authorization
- Least privilege
- Confidentiality protection
- Smart-card MFA where supported
- Identification of expected personnel
- Controlled privileged production access
- Secure change requirements

Expected contractor personnel names should be provided at least one business day before scheduled access when practical.

Emergency exceptions must be documented.

---

# 33. Infinity Privileged Production Access

Infinity contractors must not receive general remote VPN access for privileged production administration.

Privileged production or administrative work must occur from the designated controlled contractor workspace at Dunder Mifflin headquarters.

Access must be limited to authorized activities.

Detailed requirements are established in:

- [[PROC-004 Contractor Access Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]
- [[STD-009 Infinity Security Standard]]

---

# 34. Shared Accounts

Shared user accounts should be avoided.

Shared accounts may be used only when:

- Operationally justified
- Individual accounts are impractical for the specific use
- Permissions are limited
- Sensitive activity remains attributable where required
- Management has accepted the operating requirement

Shared accounts must not be used as a general substitute for individual identity management.

---

# 35. Shared Warehouse Workstations

Shared Windows workstation accounts may be used in warehouses where justified by operational requirements.

Shared Windows access must have minimal permissions.

Significant Warehouse Management System (WMS) transactions must require individual authentication or otherwise provide reliable individual attribution.

Examples of significant transactions may include:

- Material inventory adjustments
- Significant receiving transactions
- Significant shipping transactions
- Other actions designated by Operations management

Shared workstation access must not eliminate accountability for significant inventory activity.

---

# 36. Service Accounts

Service accounts must be used only for legitimate system or application functions.

Service accounts must:

- Have an identified owner.
- Have a documented purpose.
- Receive only required permissions.
- Be protected from interactive use where practical.
- Use appropriately protected credentials.
- Be reviewed periodically.
- Be removed when no longer required.

Service-account credentials must not be shared for ordinary user activity.

---

# 37. Emergency Access

Emergency access may be maintained when required to recover or administer critical systems if normal access is unavailable.

Emergency access must:

- Be limited to legitimate emergency use.
- Be protected against ordinary use.
- Use dual custody where practical.
- Be documented.
- Be reviewed following use.
- Have credentials changed or otherwise secured following use when appropriate.

Emergency access must not become a substitute for ordinary privileged-access management.

Emergency access does not authorize external remote privileged administration prohibited by this policy.

---

# 38. Emergency Access Custody

Where practical, emergency credentials must be protected using dual custody.

No single individual should be able to obtain and use protected emergency credentials without the participation or authorization of another designated individual.

Custody arrangements must not prevent timely emergency response.

---

# 39. Access to Sensitive Information

Access to Confidential and Restricted information must be based on:

- Business need
- Information-owner authorization where required
- Appropriate authentication
- Appropriate role
- Applicable handling requirements

Sensitive access must be removed when the business need ends.

---

# 40. Application Access

Business application access must be based on approved roles or permissions appropriate to the user's responsibilities.

Application owners must support:

- Access authorization
- Role design
- Access review
- Removal of unnecessary permissions
- Investigation of inappropriate access

Applications should support individual accountability for significant transactions where practical.

---

# 41. Network Access

Access to internal network resources must be restricted to authorized systems and users.

Network access must not independently grant access to all information or applications available through the network.

Application and information authorization remain required.

---

# 42. Remote Access

Remote access must:

- Be authorized.
- Have legitimate business need.
- Use approved company equipment where required.
- Use approved protected connectivity.
- Use appropriate authentication.
- Be limited to required resources.

Remote access must not provide unnecessary administrative capability.

Remote access to nonpublic company resources may use approved VPN connectivity where required.

Authorization for ordinary remote access does not authorize external remote privileged administration.

---

# 43. Cloud Resource Access

Access to nonpublic cloud-hosted company resources must follow the same authorization and least-privilege principles as internally hosted resources.

Cloud hosting does not make company information public.

Access must be based on business need and appropriate authentication.

---

# 44. Physical and Logical Access Coordination

Logical and physical access processes must coordinate when employment or responsibilities change.

Termination may require removal of:

- System accounts
- Application access
- Remote access
- Access cards
- Keys
- Smart cards
- Other credentials

Physical access requirements are established in [[POL-011 Physical & Environmental Security Policy]].

---

# 45. Access Logging

Security-relevant access activity must be logged where supported and appropriate to risk.

Priority should be given to:

- Authentication events
- Privileged activity
- Significant administrative changes
- Significant application transactions
- Security-sensitive access

Logs must be protected according to applicable security requirements.

---

# 46. Authentication Monitoring

Dunder Mifflin must monitor authentication activity according to risk and available system capabilities.

Monitoring should support identification of:

- Repeated failed authentication
- Unexpected account use
- Suspicious privileged access
- Dormant-account activity
- Other significant authentication anomalies

Monitoring requirements are further defined in [[PRO-005 Security Operations Program]].

---

# 47. Access Violations

Suspected unauthorized access must be reported and investigated.

Examples include:

- Credential sharing
- Unauthorized privilege escalation
- Access after termination
- Inappropriate sensitive-data access
- Use of another person's account
- Unauthorized privileged activity
- Circumvention of access controls

Security incidents must be handled according to [[POL-009 Incident Response Policy]].

---

# 48. Access Review Evidence

Access reviews must produce sufficient evidence to demonstrate:

- Scope reviewed
- Reviewer
- Date
- Users or privileges examined
- Decisions
- Required removals or changes
- Completion of corrective actions

A statement that an access review occurred without supporting evidence may be insufficient for assurance.

---

# 49. Access Exceptions

Exceptions to access requirements require:

- Documented business justification
- Associated risk
- Defined duration
- Compensating controls where practical
- Responsible owner
- Appropriate approval

Exceptions creating High or Critical residual risk require escalation consistent with [[POL-005 Risk Management Policy]].

This exception process does not authorize exceptions to the prohibition on external remote privileged administration.

---

# 50. Access Control Assessment

Access controls must be periodically assessed.

Assessment may include:

- Inspection
- Sampling
- Observation
- Technical Testing
- Independent Performance

Assessment should evaluate both control design and operation.

Examples include:

- Sampling terminated employees to confirm access removal
- Reviewing privileged-group membership
- Testing dormant-account handling
- Sampling contractor expiration dates
- Reviewing access approvals
- Testing significant WMS transaction attribution

---

# 51. Findings and Corrective Action

Material access-control deficiencies must be documented.

Examples include:

- Former employee accounts remaining active
- Unapproved privileged access
- Excessive permissions
- Unjustified dormant accounts
- Expired contractor access
- Unattributable significant warehouse transactions
- Missing access-review evidence

Material deficiencies requiring remediation must be tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 52. Access Metrics

Access-control metrics may include:

- Termination access-removal timeliness
- Number of dormant accounts
- Privileged-access review completion
- Ordinary-user access-review completion
- Contractor accounts past approved expiration
- Access-review findings
- Unauthorized access incidents
- Emergency-account use
- Access-remediation completion

Metric definitions are maintained in [[REG-005 Security Metrics Catalog]].

---

# 53. Risk Relationships

This policy provides significant treatment support for risks including:

- R001 Phishing / Credential Compromise
- R002 Business Email Compromise
- R005 Password / Authentication Weakness
- R009 Sensitive Information Theft / Extortion
- R010 Unauthorized / Excessive Access
- R011 Delayed Termination Access Removal
- R012 Malicious Insider
- R014 Lost or Stolen Device
- R015 Shared Warehouse Account
- R019 Infinity Contractor Dependency / Compromise

Risk treatment is documented in [[RTP-001 Enterprise Risk Treatment Plan]].

---

# 54. Enforcement

Violations of this policy may result in:

- Access restriction
- Access removal
- Corrective action
- Management review
- Personnel action
- Contractual action
- Legal action where appropriate

Response must consider severity, intent, business impact, repetition, and applicable legal or personnel requirements.

---

# 55. Policy Review

This policy must be reviewed:

- At least annually
- Following material identity-system changes
- Following significant access-control incidents
- Following significant assessment findings
- Following material organizational change
- When access-control requirements materially change

The CIO coordinates review.

Material revisions require appropriate approval.

---

# 56. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-003 Identity and Access Management Program]]
- [[PRO-009 Security Governance Framework]]
- [[POL-001 Information Security Policy]]
- [[POL-002 Acceptable Use Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-011 Physical & Environmental Security Policy]]
- [[STD-001 Information Classification Standard]]
- [[STD-005 Authentication & Account Security Standard]]
- [[PROC-001 Joiner-Mover-Leaver Procedure]]
- [[PROC-002 Privileged Access Procedure]]
- [[PROC-003 Access Review Procedure]]
- [[PROC-004 Contractor Access Procedure]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-020 Contractor Development Access Procedure]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[REG-007 Cross-Reference Matrix]]

---

# 57. Revision History

| Version | Date     | Description                   | Approval |
| ------- | -------- | ----------------------------- | -------- |
| 1.0     | May 2013 | Initial Access Control Policy | CEO      |