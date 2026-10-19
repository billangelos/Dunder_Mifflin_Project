# STD-001 Information Classification Standard

## Document Control

| Field | Value |
|---|---|
| Document ID | STD-001 |
| Title | Information Classification Standard |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Annual |

---

# 1. Purpose

This standard establishes Dunder Mifflin's information classification model and minimum requirements for protecting information according to its sensitivity.

Information must receive protection appropriate to the potential business, financial, legal, operational, privacy, or security consequences of unauthorized disclosure, alteration, loss, or misuse.

The classification model supports consistent decisions concerning:

- Access
- Storage
- Transmission
- Sharing
- Printing
- Physical handling
- Remote use
- Third-party access
- Backup
- Retention
- Disposal

---

# 2. Scope

This standard applies to information created, received, processed, stored, transmitted, or maintained by or on behalf of Dunder Mifflin.

It applies regardless of information format.

Covered information includes:

- Electronic records
- Paper records
- Email
- Databases
- Application data
- File shares
- Source code
- Backup data
- Removable media
- Printed documents
- Reports
- Contracts
- Personnel records
- Financial records
- Security records
- Business continuity documentation
- Technical documentation
- Information maintained by authorized third parties

---

# 3. Classification Model

Dunder Mifflin uses four information classification levels:

| Classification | General Meaning |
|---|---|
| Public | Information approved for public disclosure |
| Internal | Nonpublic information intended primarily for authorized company use |
| Confidential | Sensitive business or personal information requiring controlled access |
| Restricted | Highly sensitive information requiring the strongest practical protection |

Classification requirements increase from Public through Restricted.

**Public → Internal → Confidential → Restricted**

---

# 4. Classification and Business Criticality

Information classification and business criticality are separate concepts.

**Classification** addresses the sensitivity of information and the potential consequences of unauthorized disclosure, alteration, or misuse.

**Business criticality** addresses the consequences of disruption and the urgency with which a business process or supporting capability must be restored.

A Confidential information set is not automatically associated with a Critical business process.

Likewise, a Critical business process may depend on information that is not Restricted.

Business criticality, Maximum Tolerable Downtime (MTD), Recovery Time Objective (RTO), and Recovery Point Objective (RPO) are established through [[RPT-002 Business Impact Analysis]].

---

# 5. Public Information

## 5.1 Definition

Public information is information approved for unrestricted public disclosure.

Unauthorized disclosure of properly classified Public information is not expected to cause material harm to Dunder Mifflin.

Integrity may still be important even when confidentiality is not required.

## 5.2 Examples

Public information may include:

- Approved marketing material
- Published product information
- Public contact information
- Approved press releases
- Public website content
- Published job advertisements
- Publicly distributed company information

## 5.3 Access

Public information may be accessed without internal authorization once approved for public release.

The ability to modify official Public information must remain restricted to authorized personnel.

## 5.4 Storage

Public information may be stored on company systems appropriate to the business purpose.

## 5.5 Transmission

Public information may be transmitted using ordinary business communication methods.

## 5.6 Disposal

No special confidentiality-based destruction method is required for information whose classification remains Public.

Normal records-management and disposal requirements still apply.

---

# 6. Internal Information

## 6.1 Definition

Internal information is nonpublic business information intended primarily for use by Dunder Mifflin personnel and authorized parties.

Unauthorized disclosure could create inconvenience, minor business impact, or unnecessary exposure but is not expected by itself to cause serious harm.

## 6.2 Examples

Internal information may include:

- Routine internal communications
- General operating procedures
- Internal organizational information
- Internal schedules
- Routine meeting information
- General training materials
- Ordinary internal process documentation
- Non-sensitive internal reports

## 6.3 Access

Access is limited to personnel and authorized parties with a legitimate business reason to receive the information.

Internal information should not be made publicly available without authorization.

## 6.4 Storage

Internal information may be stored on approved company systems and authorized company devices.

## 6.5 Transmission

Internal information may be transmitted through approved company communication systems.

Personnel should verify recipients before transmitting information outside the company.

## 6.6 Physical Handling

Printed Internal information should receive reasonable protection from unnecessary public exposure.

## 6.7 Disposal

Paper containing Internal information should be disposed of through normal company disposal processes unless the information's content requires stronger protection.

Electronic information must be disposed of through approved system or media-disposal processes.

---

# 7. Confidential Information

## 7.1 Definition

Confidential information is sensitive information whose unauthorized disclosure, alteration, or misuse could cause material harm to Dunder Mifflin, its employees, customers, suppliers, or business partners.

Access must be limited according to legitimate business need.

## 7.2 Examples

Confidential information may include:

- Customer account information
- Customer order history
- Nonpublic pricing information
- Employee information
- Compensation information
- Payroll information
- Financial information
- Vendor banking information
- Contracts
- Payment tokens
- Security incident information
- Business continuity information
- Recovery documentation
- Nonpublic business strategy
- Sensitive supplier information
- Certain security records

The sensitivity of specific records may justify classification as Restricted.

## 7.3 Access

Access to Confidential information requires:

- Legitimate business need
- Appropriate authorization
- Access consistent with job responsibilities
- Appropriate authentication

Access must be removed when no longer required.

## 7.4 Storage

Electronic Confidential information must be stored using approved company systems or devices with access controls appropriate to the information.

Confidential information should not be stored unnecessarily on unmanaged systems or devices.

Physical Confidential records must be protected against unauthorized access.

## 7.5 Transmission

Confidential information transmitted electronically must use approved communication methods appropriate to the sensitivity and destination.

Personnel must verify recipients before transmission.

Sensitive information must not be sent to unauthorized personal accounts or other unapproved destinations.

## 7.6 Remote Use

Remote access to Confidential information must use company-approved devices, services, and access methods appropriate to the business requirement.

Personnel must take reasonable precautions against observation, theft, or unauthorized access when working outside company facilities.

## 7.7 Printing

Printing should be limited to legitimate business need.

Printed Confidential information must not be left unattended in publicly accessible or uncontrolled locations.

## 7.8 Disposal

Paper containing Confidential information must be securely destroyed when disposal is authorized.

Electronic media containing Confidential information must be securely erased, destroyed, or otherwise disposed of through approved methods appropriate to the media.

---

# 8. Restricted Information

## 8.1 Definition

Restricted information is highly sensitive information whose unauthorized disclosure, alteration, misuse, or compromise could cause severe business, financial, security, legal, privacy, or operational harm.

Restricted information requires the strongest practical protection provided by Dunder Mifflin.

## 8.2 Examples

Restricted information may include:

- Privileged authentication credentials
- Administrative passwords
- Authentication secrets
- Emergency-access credentials
- Encryption keys where applicable
- Infinity source code
- Infinity source repository
- Sensitive application architecture information
- Detailed exploitable security information
- Certain vulnerability-assessment results
- Penetration-test results
- Highly sensitive incident evidence
- Highly sensitive personnel information
- Highly sensitive financial or banking information
- Security configurations that could materially assist unauthorized access

## 8.3 Access

Access to Restricted information must be:

- Based on explicit business need
- Limited to specifically authorized personnel
- Limited to the minimum information required
- Protected by appropriate authentication
- Reviewed according to applicable access-control requirements

Restricted information must not be made broadly available merely because a user is an employee, manager, executive, or member of Information Technology.

## 8.4 Storage

Restricted electronic information must be stored only on approved systems with access controls appropriate to its sensitivity.

Encryption must be used where required by the applicable system, device, or security standard.

Physical Restricted information must be stored in an appropriately secured area or container when unattended.

## 8.5 Transmission

Transmission of Restricted information must be limited to legitimate business requirements.

Approved protected communication methods must be used when transmitting Restricted information across untrusted networks or to authorized external recipients.

Recipients must be verified before transmission.

## 8.6 Remote Use

Remote handling of Restricted information should be limited to circumstances where business requirements justify it and appropriate protection can be maintained.

## 8.7 Printing

Restricted information should not be printed unless there is a legitimate business requirement.

Printed Restricted information must remain under authorized control and must be secured when unattended.

## 8.8 Disposal

Paper containing Restricted information must be securely destroyed.

Electronic media containing Restricted information must be securely erased or physically destroyed using an approved method appropriate to the media and information involved.

---

# 9. Classification Summary

| Requirement | Public | Internal | Confidential | Restricted |
|---|---|---|---|---|
| Public Disclosure | Permitted after approval | No | No | No |
| Business Need Required | No for public access | Yes | Yes | Yes |
| Access Restriction | Modification controls | Normal company access | Controlled | Strictly controlled |
| Approved Company Storage | Preferred | Required | Required | Required |
| Recipient Verification | Normal practice | External recipients | Required | Required |
| Secure Disposal | Normal disposal | As appropriate | Required | Required |
| Third-Party Protection | As applicable | As applicable | Required when accessed | Required when accessed |
| Remote Handling Restrictions | Minimal | Normal | Increased | Strongest |
| Security Review | As needed | As needed | Risk-based | Risk-based and heightened |

This table establishes general minimum expectations. More specific policies, standards, contracts, or legal requirements may impose stronger controls.

---

# 10. Classification Responsibilities

## 10.1 Information Owners

Information owners are responsible for:

- Determining appropriate classification
- Identifying legitimate users
- Approving access as required
- Identifying changes in sensitivity
- Supporting periodic access review
- Identifying legal, contractual, or business requirements affecting protection

## 10.2 Information Custodians

Custodians are responsible for implementing applicable protection requirements on behalf of information owners.

Custodians may include:

- Information Technology
- Cloud providers
- Records personnel
- Business personnel
- Authorized third parties

Custodians do not automatically determine the business classification of information.

## 10.3 Users

Users must:

- Handle information according to its classification.
- Access information only for authorized business purposes.
- Protect information from unauthorized disclosure.
- Verify recipients before sharing sensitive information.
- Report suspected loss or unauthorized disclosure.
- Use approved systems and communication methods.
- Dispose of sensitive information appropriately.

---

# 11. Classification Determination

Information should be classified according to the highest reasonable level of sensitivity represented by its content.

Classification decisions should consider:

- Potential business harm
- Financial harm
- Privacy implications
- Security implications
- Fraud potential
- Contractual obligations
- Legal obligations
- Customer expectations
- Employee expectations
- Competitive value
- Potential usefulness to an attacker

When classification is uncertain, the information owner should select the more protective reasonable classification until the classification can be reviewed.

---

# 12. Aggregation

Multiple pieces of information may become more sensitive when combined.

For example, individual pieces of Internal information may collectively reveal:

- Sensitive business strategy
- Security architecture
- Customer patterns
- Employee information
- Operational weaknesses

Information owners must consider aggregation when determining appropriate protection.

---

# 13. Derived Information

Information created from a sensitive source must retain an appropriate classification based on the content of the derived information.

Removing some sensitive content may justify a lower classification when the remaining information no longer requires the original protection level.

Classification must be based on the information that remains rather than solely on the classification of the source.

---

# 14. Backups

Backups inherit the highest applicable classification of the information they contain.

For example, a backup containing Restricted and Confidential information must be protected as Restricted.

Backup protection must consider:

- Access
- Encryption
- Physical security
- Transportation
- Off-site storage
- Recovery access
- Disposal

Backup classification does not establish Recovery Time Objective or Recovery Point Objective.

Recovery requirements are established through [[RPT-002 Business Impact Analysis]].

---

# 15. Removable Media

Sensitive information should not be placed on removable media unless there is a legitimate business requirement.

Removable media containing Confidential or Restricted information must receive protection appropriate to the classification.

Protection may include:

- Encryption
- Physical control
- Restricted access
- Inventory or accountability
- Secure transportation
- Secure disposal

The encrypted external drives used for backup rotation must be protected according to the highest classification of the information they contain.

---

# 16. Email and Electronic Communication

Email users must consider information classification before transmitting sensitive information.

Confidential or Restricted information must not be sent to unauthorized recipients.

Personnel must verify recipients before transmitting sensitive information, particularly when:

- Sending externally
- Sending to multiple recipients
- Sending attachments
- Handling personnel information
- Handling financial information
- Handling security information

Restricted information should not be transmitted through email when a more appropriate approved method is required by the nature of the information.

---

# 17. Physical Records

Physical records must receive protection appropriate to their classification.

Confidential and Restricted records must not be left unattended in areas where unauthorized persons can readily access them.

Restricted records must be secured when unattended.

Sensitive records awaiting disposal must remain protected until securely destroyed.

---

# 18. Third-Party Access

Third-party access to Internal, Confidential, or Restricted information must be based on legitimate business need.

Before a nonemployee or outside party receives sensitive information, applicable confidentiality requirements must be established.

A Non-Disclosure Agreement (NDA) or equivalent enforceable confidentiality obligation is required when appropriate to the information and access involved.

Third-party access must be limited to the information reasonably necessary to perform the authorized service.

Confidentiality obligations do not replace technical, administrative, physical, contractual, or assessment controls required by risk.

Third-party security requirements are governed by [[POL-008 Third-Party Security Policy]].

---

# 19. Information Sharing

Before sharing sensitive information, personnel should determine:

1. Whether the recipient is authorized.
2. Whether the recipient requires the information.
3. Whether the amount of information being shared is necessary.
4. Whether the communication method is appropriate.
5. Whether confidentiality requirements apply.
6. Whether additional contractual or security requirements apply.

Access to information should follow the minimum-necessary principle where practical.

---

# 20. Information Labeling

Information should be labeled when labeling materially assists users in recognizing and applying required protection.

Formal labeling is particularly useful for Confidential and Restricted documents that may otherwise be misunderstood.

Examples include:

**CONFIDENTIAL**

or

**RESTRICTED**

Labeling requirements should remain practical and should not create unnecessary administrative burden for routine information.

The absence of a visible label does not automatically make sensitive information Public or Internal.

---

# 21. Reclassification

Information may be reclassified when:

- Its sensitivity changes.
- Confidentiality requirements expire.
- Information is approved for public release.
- Sensitive content is removed.
- Business circumstances change.
- Legal or contractual requirements change.
- The original classification is found to be incorrect.

Reclassification must be authorized by the information owner or another authority with responsibility for the information.

---

# 22. Public Release

Information must not be treated as Public solely because:

- It is easy to access internally.
- Many employees can access it.
- It was accidentally disclosed.
- Similar information exists publicly.
- A third party possesses a copy.

Information becomes Public when Dunder Mifflin authorizes public disclosure or when another legitimate authority makes the information public in a manner that removes Dunder Mifflin's confidentiality requirement.

---

# 23. Information Retention

Classification and retention are separate requirements.

Information must not be retained indefinitely merely because it is sensitive.

Retention requirements should consider:

- Business need
- Legal requirements
- Contractual requirements
- Records requirements
- Investigation holds
- Litigation holds
- Operational requirements

Information that no longer requires retention should be disposed of using a method appropriate to its classification.

---

# 24. Information Disposal

Sensitive information must remain protected through final disposal.

Approved disposal methods may include:

- Cross-cut shredding
- Approved secure-destruction services
- Secure electronic erasure
- Physical destruction of media where appropriate

Disposal methods must be appropriate to the information classification and storage medium.

---

# 25. Security Incidents

Suspected unauthorized disclosure, loss, alteration, or misuse of Confidential or Restricted information must be reported according to [[POL-009 Incident Response Policy]] and [[PLN-001 Incident Response Plan]].

The classification of affected information is one factor used when evaluating incident severity.

Information classification alone does not determine incident severity.

Other factors include:

- Volume
- Exposure
- Business impact
- Affected individuals
- System compromise
- Fraud potential
- Duration
- Recoverability
- Legal or contractual obligations

---

# 26. Exceptions

Exceptions to this standard require:

- Documented business justification
- Risk evaluation
- Approval by the appropriate authority
- Appropriate compensating controls where practical
- Defined duration where applicable

Exceptions must not be used to avoid reasonable protection requirements merely for convenience.

---

# 27. Compliance

Compliance may be evaluated through:

- Inspection
- Observation
- Access review
- Sampling
- Technical Testing
- Security assessment
- Incident review
- Third-party review

Material deficiencies must be addressed according to applicable corrective-action and risk-management processes.

---

# 28. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[REG-001 Enterprise Asset Register]]
- [[RPT-002 Business Impact Analysis]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[PRO-003 Identity and Access Management Program]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PROC-012 Backup & Recovery Procedure]]

---

# 29. Revision History

| Version | Date     | Description                                 | Approval |
| ------- | -------- | ------------------------------------------- | -------- |
| 1.0     | May 2013 | Initial information classification standard | CEO      |