# POL-004 Information Classification & Handling Policy

## Document Control

| Field | Value |
|---|---|
| Document ID | POL-004 |
| Title | Information Classification & Handling Policy |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Change |

---

# 1. Purpose

This policy establishes requirements for classifying and protecting Dunder Mifflin information according to its sensitivity and business requirements.

Information must receive protection appropriate to:

- Confidentiality requirements
- Integrity requirements
- Business use
- Legal obligations
- Contractual obligations
- Potential harm from unauthorized disclosure
- Potential harm from unauthorized modification
- Potential harm from inappropriate destruction

Detailed classification and handling requirements are established in [[STD-001 Information Classification Standard]].

---

# 2. Scope

This policy applies to information:

- Created by Dunder Mifflin
- Collected by Dunder Mifflin
- Received from customers
- Received from employees
- Received from suppliers
- Received from business partners
- Processed on behalf of Dunder Mifflin
- Stored in company systems
- Stored in cloud-hosted systems
- Stored on endpoints
- Stored on removable media
- Maintained as physical records
- Shared with authorized third parties
- Contained in backups

The policy applies regardless of information format or storage location.

---

# 3. Objectives

Information classification and handling must:

1. Identify information requiring protection.
2. Apply protection according to sensitivity.
3. Restrict unauthorized access.
4. Support appropriate information sharing.
5. Protect information throughout its lifecycle.
6. Establish ownership and handling responsibility.
7. Support risk assessment.
8. Support access-control decisions.
9. Support incident response.
10. Support secure disposal.

---

# 4. Information Classification Model

Dunder Mifflin uses four information classifications:

1. Public
2. Internal
3. Confidential
4. Restricted

Classification reflects the protection required by the information.

Classification does not determine the operational criticality of the system or business process containing the information.

---

# 5. Classification and Business Criticality

Information classification and business criticality are separate concepts.

**Classification** addresses the protection required by information.

**Business criticality** addresses the importance of a business process or system to continued operations.

For example:

- A public-facing system may be operationally important while containing mostly Public information.
- A system containing Restricted information may have limited immediate availability requirements.
- A Critical business process may depend on information at several classification levels.

Business criticality and recovery requirements are addressed through [[RPT-002 Business Impact Analysis]].

---

# 6. Public Information

Public information is approved for disclosure outside Dunder Mifflin.

Examples may include:

- Approved marketing materials
- Public website content
- Published product information
- Approved public statements
- Public contact information
- Approved job postings

Public information does not require confidentiality protection after authorized release.

Integrity remains important because unauthorized modification may harm Dunder Mifflin.

---

# 7. Internal Information

Internal information is intended primarily for Dunder Mifflin business use but would not normally create significant harm if unintentionally disclosed.

Examples may include:

- Routine internal communications
- General operating instructions
- Internal announcements
- Non-sensitive internal directories
- Routine administrative information

Internal information must not be intentionally published externally without appropriate authorization.

---

# 8. Confidential Information

Confidential information could cause meaningful harm to Dunder Mifflin, its employees, customers, suppliers, or business partners if disclosed without authorization.

Examples may include:

- Customer information
- Supplier information
- Nonpublic sales information
- Pricing information
- Contracts
- Internal financial information
- Employee business records
- Security documentation
- System configuration information
- Payment tokens
- Nonpublic business plans

Access to Confidential information must be limited to authorized personnel with legitimate business need.

---

# 9. Restricted Information

Restricted information requires Dunder Mifflin's highest level of information protection because unauthorized disclosure could create serious harm, legal exposure, security compromise, or significant business impact.

Examples may include:

- Authentication secrets
- Highly sensitive personnel information
- Sensitive payroll information
- Sensitive financial-account information
- Cryptographic secrets
- Highly sensitive security information
- Information specifically requiring heightened protection by law or contract

Restricted information must receive enhanced access, storage, transmission, and disposal protection.

---

# 10. Payment Information

Dunder Mifflin's payment processor stores payment card account numbers.

Dunder Mifflin retains only limited payment information required for business use, such as:

- Payment token
- Card brand
- Last four digits
- Expiration information where required

Payment tokens are classified as Confidential.

Dunder Mifflin must not intentionally retain complete payment card account numbers when the approved payment-processing model does not require them.

---

# 11. Classification Responsibility

Information owners are responsible for determining appropriate classification.

Classification decisions should consider:

- Information content
- Business use
- Sensitivity
- Legal obligations
- Contractual obligations
- Customer requirements
- Employee privacy
- Security implications
- Potential harm from unauthorized disclosure

Information Technology may assist with classification but does not automatically become the information owner.

---

# 12. Information Owner Responsibilities

Information owners must:

- Determine appropriate classification.
- Identify authorized users.
- Approve access where required.
- Identify handling requirements.
- Support periodic access review.
- Review classification when information changes materially.
- Support investigation of inappropriate access or disclosure.

---

# 13. Custodian Responsibilities

Information custodians manage or maintain information on behalf of information owners.

Custodians may include:

- Information Technology personnel
- System administrators
- Application administrators
- Records personnel
- Cloud service providers
- Other authorized service providers

Custodians must apply required protection but do not automatically determine the business classification of information.

---

# 14. User Responsibilities

Users must:

- Handle information according to classification.
- Access information only for authorized purposes.
- Share information only with authorized recipients.
- Use approved storage.
- Use appropriate transmission methods.
- Protect information from unnecessary exposure.
- Report suspected loss or disclosure.
- Dispose of information appropriately.

---

# 15. Classification Determination

When classification is uncertain, the information owner should consider the consequences of unauthorized disclosure.

Relevant questions include:

- Could disclosure harm a customer?
- Could disclosure harm an employee?
- Could disclosure create financial loss?
- Could disclosure assist an attacker?
- Could disclosure violate a contract?
- Could disclosure expose authentication information?
- Could disclosure materially harm Dunder Mifflin?

Information must not be intentionally classified lower merely for convenience.

---

# 16. Aggregation

A collection of information may require greater protection than individual elements considered separately.

Aggregation risk must be considered when:

- Large quantities of customer information are combined.
- Employee records are combined.
- Security information is consolidated.
- Business information reveals sensitive patterns.
- Multiple data elements together reveal information not apparent individually.

The resulting collection must receive protection appropriate to the combined sensitivity.

---

# 17. Derived Information

Information derived from another source must be classified according to the sensitivity of the resulting information.

Derived information does not automatically become Public or Internal merely because it omits some source details.

---

# 18. Access

Access to information must be based on:

- Business need
- Classification
- User responsibility
- Appropriate authorization
- Least privilege
- Need to know

Access requirements are governed by [[POL-003 Access Control Policy]].

---

# 19. Storage

Information must be stored using methods appropriate to its classification.

Confidential and Restricted information must not be knowingly stored in unauthorized locations.

Storage controls may include:

- Access restrictions
- Encryption
- Physical protection
- Central management
- Backup
- Approved cloud services

---

# 20. Endpoint Storage

Sensitive information stored on endpoints must be limited to legitimate business need.

Company laptops containing company information must use full-disk encryption.

Users should avoid unnecessary local copies of Confidential or Restricted information when approved centralized storage is available.

---

# 21. Removable Media

Confidential or Restricted information stored on removable media requires appropriate protection.

Controls may include:

- Encryption
- Physical protection
- Restricted access
- Inventory where appropriate
- Secure disposal

Use of removable media must be limited to legitimate business need.

---

# 22. Backups

Backups inherit the highest classification of the information contained within them.

Backup media and backup systems must receive protection appropriate to the information being protected.

Backup protection must include, where applicable:

- Encryption
- Access restriction
- Physical protection
- Off-site protection
- Controlled administrative access

Classification requirements apply throughout the backup lifecycle.

---

# 23. Transmission

Information must be transmitted using methods appropriate to its classification.

Confidential and Restricted information must receive appropriate protection against unauthorized interception or disclosure.

Transmission requirements may include:

- Protected network connections
- Encryption
- Approved file-transfer methods
- Recipient verification
- Physical protection for transported records or media

---

# 24. Email Transmission

Users must consider information classification before transmitting information through email.

Confidential or Restricted information must not be transmitted to unauthorized recipients.

Users must verify recipients when sending sensitive information.

Restricted information should not be transmitted through ordinary email when the required level of protection cannot be provided.

---

# 25. External Sharing

Information may be shared outside Dunder Mifflin only when:

- A legitimate business purpose exists.
- The recipient is authorized.
- The disclosure is consistent with classification.
- Required confidentiality protection is in place.
- Applicable contractual requirements are satisfied.
- Applicable legal requirements are satisfied.

External sharing must be limited to the information required for the business purpose.

---

# 26. Third-Party Access

Third parties may receive access to sensitive information only when authorized and necessary for an approved business purpose.

Protection must be appropriate to:

- Information classification
- Type of access
- Duration
- Business dependency
- Third-party risk

Third-party security requirements are established in [[POL-008 Third-Party Security Policy]].

---

# 27. Confidentiality Agreements

Nonemployees and outside parties must be subject to an enforceable confidentiality obligation before receiving sensitive information when the nature of the access requires such protection.

This requirement may apply to:

- Contractors
- Consultants
- Information Technology service providers
- Infinity contractors
- Penetration testers
- Temporary specialists
- Outside support personnel
- Other third parties requiring sensitive access

The requirement is determined by access and information sensitivity rather than vendor title.

---

# 28. Ordinary Visitors and Service Personnel

An ordinary visitor, delivery person, vendor sales representative, or building-maintenance worker does not automatically require a confidentiality agreement when the individual is not provided access to sensitive information.

Appropriate visitor and physical-security controls still apply.

If the individual's work changes to require sensitive access, appropriate confidentiality protection must be established before that access is provided.

---

# 29. Physical Records

Physical records must receive protection appropriate to their classification.

Controls may include:

- Locked storage
- Restricted rooms
- Controlled file cabinets
- Controlled distribution
- Appropriate transport
- Secure destruction

Sensitive physical records must not be left unnecessarily exposed in public or uncontrolled areas.

---

# 30. Printing

Printing of Confidential or Restricted information must be limited to legitimate business need.

Sensitive printouts must:

- Be retrieved promptly.
- Be protected from unauthorized viewing.
- Be stored appropriately.
- Be provided only to authorized recipients.
- Be securely destroyed when no longer required.

---

# 31. Workspace Protection

Personnel handling Confidential or Restricted information must take reasonable measures to prevent unauthorized viewing or access.

Measures may include:

- Securing documents when unattended
- Locking computer screens
- Positioning sensitive information away from public view
- Avoiding unnecessary sensitive discussions in public areas
- Retrieving sensitive printouts

Controls should remain proportionate to risk.

---

# 32. Information Labeling

Information should be labeled when labeling materially helps users understand required protection.

Labeling is particularly appropriate for:

- Confidential information
- Restricted information
- Sensitive reports
- Sensitive physical records
- Documents likely to be distributed outside their original context

Absence of a label does not automatically mean information is Public.

---

# 33. System-Level Classification

Systems containing multiple information types must receive protection appropriate to the most sensitive information they routinely process or store unless technical separation provides an appropriate basis for different treatment.

System classification does not replace individual information-owner responsibility.

---

# 34. Reclassification

Information classification may change when:

- Sensitivity changes.
- Business use changes.
- Legal requirements change.
- Contractual requirements change.
- Information becomes obsolete.
- Information is approved for public release.

Reclassification requires appropriate owner authorization.

---

# 35. Public Release

Information must not be treated as Public solely because disclosure appears harmless.

Public release must be:

- Authorized
- Appropriate for external distribution
- Consistent with business requirements
- Consistent with legal and contractual obligations

Once information is legitimately released publicly, confidentiality controls may no longer be necessary, but integrity requirements may remain important.

---

# 36. Retention

Information must be retained according to applicable:

- Business requirements
- Legal requirements
- Contractual requirements
- Financial requirements
- Records requirements
- Investigation or litigation needs

Information must not be retained indefinitely without business or other legitimate need when continued retention creates unnecessary risk.

---

# 37. Legal and Investigation Holds

Information subject to an authorized legal, investigation, or records hold must not be destroyed until the hold is released.

Legal and Compliance must provide applicable direction.

---

# 38. Disposal

Information that no longer requires retention must be disposed of in a manner appropriate to its classification.

Disposal methods may include:

- Cross-cut shredding
- Approved secure destruction
- Secure media disposal
- Appropriate electronic deletion
- Physical destruction of media where required

Sensitive information must not be discarded in ordinary trash when doing so could expose it to unauthorized access.

---

# 39. Reuse of Media

Media previously containing Confidential or Restricted information must be appropriately sanitized before reuse when residual information could otherwise be recovered.

Media that cannot be appropriately sanitized must be securely destroyed when no longer required.

---

# 40. Lost Information or Media

Loss of information or media containing company information must be reported promptly.

Reports should identify, where known:

- Information involved
- Classification
- Approximate quantity
- Affected individuals or business functions
- Storage medium
- Circumstances of loss
- Potential unauthorized access

The event must be evaluated under applicable incident-response requirements.

---

# 41. Unauthorized Disclosure

Suspected unauthorized disclosure of Confidential or Restricted information must be reported promptly.

Personnel must not delay reporting while attempting to determine independently whether actual harm occurred.

Incident response must evaluate:

- Information involved
- Classification
- Recipients
- Exposure
- Business impact
- Required containment
- Required notification
- Corrective action

---

# 42. Information Integrity

Information protection includes integrity as well as confidentiality.

Controls must protect important information against inappropriate:

- Modification
- Deletion
- Corruption
- Substitution
- Incomplete processing

Integrity controls may include:

- Access control
- Change control
- Transaction records
- Reconciliation
- Backup
- Logging
- Review
- Application controls

---

# 43. Information Availability

Classification does not independently establish availability requirements.

Availability requirements must be based on business need and [[RPT-002 Business Impact Analysis]].

Information requiring high confidentiality protection may have modest availability requirements.

Information with low confidentiality sensitivity may support a Critical business process.

---

# 44. Manual Processing

Sensitive information created or processed during manual continuity operations remains subject to classification requirements.

Paper or offline records created during outages must be:

- Controlled
- Protected
- Reconciled
- Entered into restored systems where required
- Retained or destroyed appropriately

Manual processing requirements are established in [[PROC-013 Manual Processing Procedure]].

---

# 45. Security Documentation

Security documentation must be classified according to its content.

Examples may include:

- Network diagrams
- System configurations
- Vulnerability reports
- Penetration-test reports
- Incident records
- Recovery procedures
- Access-control information
- Security-assessment results

Detailed security information that could materially assist unauthorized access should receive Confidential or Restricted treatment as appropriate.

---

# 46. Authentication Information

Authentication secrets must be treated as Restricted information.

Examples include:

- Passwords
- Privileged passwords
- Emergency credentials
- Cryptographic private keys
- Other authentication secrets

Authentication secrets must not be stored or transmitted in an unprotected manner.

---

# 47. Incident and Investigation Records

Security incident and investigation records must be classified according to their contents.

Records containing:

- Sensitive employee information
- Security vulnerabilities
- Authentication information
- Sensitive customer information
- Legal information
- Detailed investigative information

may require Confidential or Restricted protection.

Access must be limited to personnel with legitimate need.

---

# 48. Business Impact Analysis Information

Business Impact Analysis information must be protected according to its contents.

Detailed dependency, recovery, and operational information should not be publicly disclosed unless specifically authorized.

BIA information supports availability and recovery decisions but does not replace information classification.

---

# 49. Information Inventory

Important information assets must be identifiable through appropriate asset and information records.

The enterprise asset inventory is maintained in [[REG-001 Enterprise Asset Register]].

Information ownership, system relationships, and classification should be recorded where appropriate to support:

- Access control
- Risk management
- Recovery
- Assessment
- Incident response

---

# 50. Risk Management

Information classification must inform risk assessment.

Classification may affect:

- Impact
- Access requirements
- Storage requirements
- Transmission requirements
- Third-party requirements
- Incident severity
- Disposal requirements

Information-related risks are maintained in [[REG-002 Enterprise Risk Register]].

---

# 51. Control Selection

Classification requirements must be translated into appropriate controls.

Controls should be selected according to:

- Classification
- Business use
- Exposure
- Threats
- Vulnerabilities
- Business criticality
- Risk

Classification alone does not dictate a single technical control.

---

# 52. Assessment

Information-handling controls must be assessed according to risk.

Assessment may include:

- Inspection
- Observation
- Sampling
- Technical Testing
- Independent Performance

Examples include:

- Reviewing access to sensitive information
- Inspecting storage practices
- Sampling third-party confidentiality agreements
- Testing laptop encryption
- Reviewing sensitive information disposal
- Inspecting backup protection

---

# 53. Findings

Material information-handling deficiencies must be documented and corrected.

Examples include:

- Sensitive information stored without required protection
- Unauthorized external sharing
- Missing confidentiality protection
- Excessive access
- Improper disposal
- Unprotected sensitive backup media
- Authentication secrets stored insecurely
- Inappropriate public disclosure

Material corrective actions must be tracked in [[REG-004 Finding & Corrective Action Register]].

---

# 54. Risk Relationships

This policy provides significant treatment support for risks including:

- R001 Phishing / Credential Compromise
- R002 Business Email Compromise
- R005 Password / Authentication Weakness
- R006 Infinity Application Compromise
- R009 Sensitive Information Theft / Extortion
- R010 Unauthorized / Excessive Access
- R012 Malicious Insider
- R014 Lost or Stolen Device
- R018 Third-Party Technology Failure / Compromise
- R019 Infinity Contractor Dependency / Compromise
- R027 Backup / Recovery Failure
- R028 Data Corruption

Risk treatment is documented in [[RTP-001 Enterprise Risk Treatment Plan]].

---

# 55. Exceptions

Exceptions to this policy require:

- Documented business justification
- Identification of affected information
- Classification
- Associated risk
- Defined duration
- Compensating controls where practical
- Responsible owner
- Appropriate approval

Exceptions creating High or Critical residual risk require escalation according to [[POL-005 Risk Management Policy]].

---

# 56. Enforcement

Violations of this policy may result in:

- Access restriction
- Corrective action
- Management review
- Personnel action
- Contractual action
- Legal action where appropriate

Response must consider severity, intent, business impact, repetition, and applicable legal or personnel requirements.

---

# 57. Policy Review

This policy must be reviewed:

- At least annually
- Following material information-handling changes
- Following significant information-security incidents
- Following significant assessment findings
- Following material legal or contractual changes
- When the classification model materially changes

The CIO coordinates review.

Material revisions require appropriate approval.

---

# 58. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[PRO-009 Security Governance Framework]]
- [[POL-001 Information Security Policy]]
- [[POL-002 Acceptable Use Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[STD-001 Information Classification Standard]]
- [[REG-001 Enterprise Asset Register]]
- [[RPT-002 Business Impact Analysis]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[PROC-013 Manual Processing Procedure]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-007 Cross-Reference Matrix]]

---

# 59. Revision History

| Version | Date     | Description                                          | Approval |
| ------- | -------- | ---------------------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Information Classification & Handling Policy | CEO      |