# PRO-001 Enterprise Information Security & Risk Management Program

## Document Control

| Field | Value |
|---|---|
| Document ID | PRO-001 |
| Title | Enterprise Information Security & Risk Management Program |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Effective Date | May 2013 |
| Review Frequency | Annual |

---

# 1. Purpose

The Dunder Mifflin Enterprise Information Security & Risk Management Program establishes the organization-wide framework for protecting information, technology, business operations, personnel, facilities, and other resources from risks that could interfere with Dunder Mifflin's business objectives.

The program establishes a business-driven and risk-based approach to information security.

Security requirements and controls are selected according to business requirements, information sensitivity, operational criticality, identified risks, contractual obligations, and the potential consequences of control failure.

The program provides the governance structure under which Dunder Mifflin identifies risk, selects appropriate treatment, establishes security requirements, implements controls, evaluates effectiveness, reports results, and continually improves its security posture.

---

# 2. Scope

This program applies to Dunder Mifflin, Inc. and the personnel, information, systems, applications, infrastructure, facilities, business processes, and third-party relationships under its authority or responsibility.

The program applies to:

- Corporate headquarters
- Scranton Branch
- Syracuse Branch
- Utica Branch
- Rochester Branch
- Nashua Branch
- Akron Branch
- Company information
- Cloud-hosted systems and services
- Local information technology infrastructure
- Servers and network equipment
- Company endpoints
- Company-issued mobile devices
- Business applications
- The Infinity customer ordering platform
- Warehousing and inventory operations
- Business continuity and recovery capabilities
- Third parties with access to Dunder Mifflin information, systems, facilities, or significant business processes
- Employees, contractors, consultants, temporary personnel, and other authorized users as applicable

Security requirements applied to a particular person, system, third party, or process must remain proportional to the access, information, business function, and risk involved.

---

# 3. Program Objectives

The program is designed to:

1. Protect the confidentiality, integrity, and availability of information and systems.
2. Protect business operations from material security and continuity risks.
3. Protect personnel and prioritize human life and safety during emergencies.
4. Establish clear security governance and accountability.
5. Identify and evaluate enterprise security risks.
6. Establish appropriate risk treatment.
7. Protect sensitive information according to its classification.
8. Apply least privilege and individual accountability.
9. Protect systems through secure architecture, configuration, maintenance, and monitoring.
10. Reduce the likelihood and impact of security incidents.
11. Establish effective incident detection, response, escalation, and recovery capabilities.
12. Maintain business continuity and disaster recovery capabilities based on business requirements.
13. Manage security risks arising from third parties.
14. Protect Dunder Mifflin's internally developed Infinity application and related intellectual property.
15. Establish evidence supporting security-control operation.
16. Assess whether important controls operate as intended.
17. Identify and correct control deficiencies.
18. Reassess risk following material changes, control implementation, incidents, or significant findings.
19. Provide management with useful security and risk information.
20. Continually improve the security program based on evidence, risk, and business need.

---

# 4. Program Principles

## 4.1 Business-Driven Security

Security exists to support Dunder Mifflin's ability to conduct business.

Controls must be appropriate to the business process, information, system, facility, or other resource being protected.

Security requirements should not be imposed solely because a technology or control is available.

---

## 4.2 Risk-Based Decision-Making

Security resources are prioritized according to risk.

Risk decisions consider:

- Likelihood
- Business impact
- Existing controls
- Control effectiveness
- Information sensitivity
- Business criticality
- Dependencies
- Treatment feasibility
- Cost
- Operational requirements

Risk management is governed by [[POL-005 Risk Management Policy]].

Detailed enterprise risks are maintained in [[REG-002 Enterprise Risk Register]] and analyzed in [[RPT-003 Enterprise Risk Assessment]].

Approved treatment activities are maintained in [[RTP-001 Enterprise Risk Treatment Plan]].

---

## 4.3 Defense in Depth

Material risks should not depend unnecessarily on a single preventive control.

Where appropriate, Dunder Mifflin uses combinations of:

- Preventive controls
- Detective controls
- Corrective controls
- Recovery controls
- Administrative controls
- Technical controls
- Physical controls

Multiple controls may work together to reduce the likelihood, impact, or duration of a security event.

---

## 4.4 Least Privilege

Access must be limited to the minimum privileges reasonably necessary to perform authorized business responsibilities.

Access requirements are governed by [[POL-003 Access Control Policy]] and supported by [[PRO-003 Identity and Access Management Program]].

---

## 4.5 Individual Accountability

Significant actions should be attributable to an individual where practical and appropriate.

Shared access must be limited to circumstances where operational requirements justify it and must not unnecessarily eliminate accountability for significant transactions.

---

## 4.6 Separation of Duties

Responsibilities that could create material fraud, security, or operational risk should be separated where practical.

Dunder Mifflin's size may prevent complete separation of duties for every activity. When complete separation is impractical, compensating controls such as management review, reconciliation, logging, approval, or independent verification should be considered.

---

## 4.7 Information Protection

Information protection requirements are based on sensitivity.

Dunder Mifflin uses the following classification levels:

- Public
- Internal
- Confidential
- Restricted

Classification and handling requirements are established by [[POL-004 Information Classification & Handling Policy]] and [[STD-001 Information Classification Standard]].

---

## 4.8 Safety Priority

Human life and safety take priority during emergencies.

Personnel must not be expected to protect systems, equipment, inventory, records, or facilities when doing so would place people at unreasonable risk.

The general recovery priority is:

**Safety → Critical Business Functions → High-Priority Functions → Moderate-Priority Functions → Low-Priority Functions**

Specific recovery requirements are established through [[RPT-002 Business Impact Analysis]].

---

## 4.9 Evidence-Based Assurance

The existence of a policy, procedure, configuration, or security technology does not by itself demonstrate that a control operates effectively.

Security assertions should be supported by appropriate evidence.

Important controls are subject to assessment according to business importance, risk, control dependency, and potential consequences of failure.

Assurance requirements are established by [[PRO-008 Security Assurance & Continuous Improvement Program]].

---

## 4.10 Proportional Security

Security measures must remain proportional to Dunder Mifflin's business needs and risk.

The program does not require unnecessary complexity merely to demonstrate security maturity.

Examples include:

- A dedicated 24-hour Security Operations Center is not required when the organization's risk and operating model do not justify one.
- A continuously operating alternate data center is not required when business recovery requirements can be satisfied through less complex recovery strategies.
- Security technologies should not be deployed without a business, risk, operational, or compliance requirement that justifies them.

---

# 5. Governance Structure

## 5.1 Chief Executive Officer

The Chief Executive Officer (CEO) has ultimate executive authority for enterprise risk and the security program.

The CEO:

- Approves the enterprise security program.
- Approves major security policies.
- Makes final decisions concerning significant enterprise risk.
- Approves High and Critical risk acceptance as required by [[POL-005 Risk Management Policy]].
- Provides executive direction and resources.
- Resolves significant risk or resource conflicts.

---

## 5.2 Information Security and Risk Committee

The Information Security and Risk Committee (ISRC) provides cross-functional oversight of significant information security and enterprise security risks.

The committee reviews:

- Significant security risks
- High and Critical risk treatment
- Significant treatment dependencies
- Material control failures
- Significant security incidents
- Major findings
- Overdue corrective actions
- Significant third-party risks
- Business continuity and recovery concerns
- Risk acceptance requiring executive review
- Material changes in enterprise risk

The ISRC supports executive decision-making but does not replace the accountability of individual risk owners.

---

## 5.3 Chief Information Officer

The Chief Information Officer (CIO) is responsible for executive oversight of information technology, information security, digital business systems, and the Infinity platform.

The CIO:

- Owns the information security program.
- Establishes technology and cybersecurity direction.
- Coordinates enterprise security governance.
- Oversees technology-related risk management.
- Ensures significant technology risks are reported to executive management.
- Oversees the Information Technology and Information Security function.
- Supports the ISRC.
- Ensures appropriate security-assurance activities are planned.

---

## 5.4 Chief Operating Officer

The Chief Operating Officer (COO) is responsible for operational risks involving branches, warehousing, fulfillment, distribution, procurement, facilities, inventory, and related business operations.

The COO also provides executive ownership for business continuity planning.

---

## 5.5 Chief Financial Officer

The Chief Financial Officer (CFO) is responsible for risks associated with:

- Finance
- Accounting
- Payroll
- Financial controls
- Financial fraud
- Human Resources oversight

---

## 5.6 Human Resources

Human Resources (HR) serves as the authoritative business source for employee status and personnel lifecycle information.

HR responsibilities include:

- Communicating employment status changes
- Supporting joiner, mover, and leaver processes
- Supporting personnel-security requirements
- Coordinating employee-related investigations as appropriate
- Supporting security-awareness requirements
- Maintaining applicable personnel records

---

## 5.7 Legal and Compliance

Legal and Compliance advises management concerning:

- Legal obligations
- Contractual obligations
- Confidentiality requirements
- Security incidents with legal implications
- Investigations
- Evidence preservation
- Regulatory or contractual notification requirements
- Third-party agreements
- Risk decisions with significant legal implications

---

## 5.8 Business, System, and Information Owners

Business, system, and information owners are responsible for determining legitimate business requirements for the resources under their authority.

Their responsibilities include:

- Identifying business needs
- Approving appropriate access
- Supporting information classification
- Participating in risk assessment
- Participating in Business Impact Analysis activities
- Supporting risk treatment
- Reviewing applicable controls
- Supporting access reviews
- Identifying material business changes
- Participating in continuity planning

Technical personnel may administer controls without owning the underlying business risk.

---

## 5.9 IT & Information Security Manager

The IT & Information Security Manager coordinates operational implementation of the information security program.

Responsibilities include:

- Coordinating security operations
- Implementing approved technical controls
- Coordinating Identity and Access Management
- Coordinating vulnerability management
- Supporting incident response
- Maintaining security documentation
- Coordinating backup and recovery activities
- Supporting security assessments
- Tracking technical remediation
- Supporting security reporting
- Escalating material security issues

The IT & Information Security Manager does not automatically own every risk involving technology.

---

## 5.10 Information Technology and Security Personnel

System administrators, network/security administrators, the Information Security Analyst, and support personnel operate controls according to their assigned responsibilities.

Personnel must use separate privileged credentials where required and must follow approved change, access, incident, configuration, and security procedures.

---

## 5.11 All Personnel

All personnel are responsible for:

- Following applicable security policies
- Protecting company information
- Protecting authentication credentials
- Using company resources appropriately
- Completing required security training
- Reporting suspected security incidents
- Reporting lost or stolen devices
- Reporting suspicious communications
- Following physical-security requirements
- Supporting business continuity procedures when directed

---

# 6. Risk Management

Dunder Mifflin maintains an enterprise risk-management process for identifying, analyzing, treating, monitoring, and reassessing security risks.

Risk is evaluated using likelihood and impact.

**Risk Score = Likelihood × Impact**

Both values use integer scores from 1 through 5.

| Score | Rating |
|---:|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–16 | High |
| 17–25 | Critical |

The program distinguishes among:

### Inherent Risk

Risk before consideration of controls.

### Current Residual Risk

Risk remaining after controls that currently exist and operate are considered.

### Target Residual Risk

The expected risk following successful implementation and validation of planned treatment.

Proposed controls receive no credit toward current residual risk until they are implemented and their effectiveness is supported by appropriate evidence.

Target residual risk is a planning estimate rather than a guaranteed result.

---

# 7. Risk Treatment

Risk may be addressed through:

- Mitigation
- Transfer
- Avoidance
- Acceptance

Treatment decisions must consider the nature of the risk, business requirements, available resources, dependencies, and expected risk reduction.

Detailed treatment activity is maintained in [[RTP-001 Enterprise Risk Treatment Plan]].

Treatment follows the general lifecycle:

**Planned → Approved → Implementing → Implemented → Validation Pending → Validated**

**Corrective Action Required** may be assigned when implementation or validation identifies a deficiency.

Implementation does not automatically demonstrate effectiveness.

---

# 8. Information Classification and Business Impact

Information sensitivity and business criticality are related but separate concepts.

Information classification determines protection requirements based primarily on sensitivity.

The Business Impact Analysis determines the consequences of disruption and establishes recovery requirements.

The Business Impact Analysis establishes:

- Business criticality
- Maximum Tolerable Downtime (MTD)
- Recovery Time Objective (RTO)
- Recovery Point Objective (RPO)

Recovery requirements follow this sequence:

**Business Requirement → Criticality → MTD → RTO/RPO → Recovery Strategy → Technical Design → Implementation → Testing**

Recovery objectives must be based on business requirements rather than arbitrary technical targets.

---

# 9. Security Architecture

Security architecture establishes how security requirements are incorporated into Dunder Mifflin's technology environment.

Architecture requirements address:

- Network security
- System security
- Endpoint security
- Authentication
- Privileged administration
- Remote access
- Cloud-hosted services
- Application architecture
- Configuration management
- Recovery capabilities
- Monitoring

Architecture requirements are maintained through [[PRO-002 Enterprise Security Architecture Program]] and its supporting standards.

---

# 10. Identity and Access Management

Identity and Access Management (IAM) establishes how identities and access rights are created, approved, changed, reviewed, and removed.

IAM requirements include:

- Business need
- Management authorization
- Least privilege
- Individual accountability
- Appropriate authentication
- Privileged-access separation
- Access review
- Contractor-access management
- Prompt termination
- Transfer reauthorization
- Dormant-account management
- Emergency-access controls

Detailed requirements are maintained in [[PRO-003 Identity and Access Management Program]] and its supporting procedures.

---

# 11. Vulnerability and Configuration Management

Dunder Mifflin maintains processes for identifying, evaluating, prioritizing, remediating, and validating vulnerabilities.

Vulnerability-management activities include:

- Patch management
- Vulnerability scanning
- Risk-based remediation
- Remediation validation
- Secure configuration
- Change management
- Application-security assessment
- Penetration testing

Vulnerability-management requirements are maintained in [[PRO-004 Vulnerability Management Program]].

Change and configuration requirements are governed by [[POL-007 Change & Configuration Management Policy]].

---

# 12. Security Operations

Security operations provide ongoing awareness of relevant security conditions and support detection, investigation, escalation, and response.

Operational activities include:

- Security-event review
- Malware detection
- Endpoint-security monitoring
- Authentication-event review
- Vulnerability monitoring
- Network-security monitoring
- Backup monitoring
- Exception identification
- Escalation

Dunder Mifflin does not require continuous human monitoring of every system.

Monitoring frequency and depth are based on risk, business importance, available evidence, and operational requirements.

Security operations are established through [[PRO-005 Security Operations Program]].

---

# 13. Incident Response

Dunder Mifflin maintains an incident-response capability for identifying, reporting, analyzing, containing, eradicating, recovering from, and learning from security incidents.

Incident-response activities must consider:

- Personnel safety
- Business impact
- Containment
- Evidence preservation
- Legal considerations
- Communications
- Recovery
- Third-party involvement
- Corrective action
- Lessons learned

Incident-response requirements are governed by [[POL-009 Incident Response Policy]] and [[PLN-001 Incident Response Plan]].

Specialized Digital Forensics and Incident Response (DFIR) support may be obtained from the retained incident-response provider when an incident exceeds internal capabilities or requires specialized expertise.

---

# 14. Business Continuity and Disaster Recovery

Dunder Mifflin maintains Business Continuity/Disaster Recovery (BC/DR) capabilities based on business requirements established through the Business Impact Analysis.

Continuity and recovery planning addresses:

- Personnel safety
- Critical business functions
- System recovery
- Backup and restoration
- Alternate communications
- Manual processing
- Facility disruption
- Cloud-service disruption
- Internet disruption
- Loss of key personnel
- Regional disruption
- Third-party dependencies
- Recovery documentation
- Testing

Business continuity is governed by [[POL-010 Business Continuity & Disaster Recovery Policy]].

Supporting requirements are maintained in [[PLN-002 Business Continuity Plan]], [[PLN-003 Disaster Recovery Plan]], and related procedures.

---

# 15. Third-Party Security

Third-party relationships are evaluated according to the information, systems, facilities, services, and business processes involved.

Third parties may be categorized as:

- Critical
- Important
- Routine

Security requirements may include:

- Due diligence
- Confidentiality obligations
- Access restrictions
- Security requirements
- Incident notification
- Recovery requirements
- Audit or assessment rights
- Access termination
- Continuity considerations
- Exit planning

Confidentiality agreements or equivalent enforceable confidentiality obligations are required before nonemployees or outside parties receive access to sensitive Dunder Mifflin information when appropriate to the access and sensitivity involved.

Third-party security is governed by [[POL-008 Third-Party Security Policy]].

---

# 16. Physical and Personnel Security

Physical and personnel controls protect people, information, systems, equipment, inventory, and facilities.

Requirements address:

- Facility access
- Restricted areas
- Visitor access
- Vendor access
- Keys and access credentials
- Warehouse security
- High-value inventory
- Personnel lifecycle events
- Security responsibilities
- Termination
- Emergency conditions

Physical and personnel security is governed by [[POL-011 Physical & Environmental Security Policy]] and [[PRO-006 Physical & Personnel Security Program]].

---

# 17. Application and Secure Development

Dunder Mifflin maintains security requirements for the internally developed Infinity application.

The company retains ownership and control of:

- Application source code
- Source repository
- Application data
- Documentation
- Intellectual property
- Application backups
- Applicable development work product

Secure development requirements address:

- Development, test, and production separation
- Change control
- Source-code control
- Contractor access
- Code review
- Security testing
- Threat modeling
- Application-security assessment
- Penetration testing
- Remediation
- Retesting
- Recovery
- Documentation
- Supportability
- Transferability

Application security is governed by [[POL-012 Application & Secure Development Policy]] and [[PRO-007 Secure Software Development Lifecycle Program]].

---

# 18. Security Awareness and Training

Personnel receive security awareness and training appropriate to their responsibilities.

The program includes:

- Initial security awareness
- Annual refresher training
- Knowledge assessment
- Phishing exercises
- Role-specific training where required
- Security reminders and communications
- Incident-reporting awareness

Security-awareness requirements are governed by [[POL-006 Security Awareness & Training Policy]].

Security exercises are intended to improve security behavior and evaluate risk. They are not intended primarily as punishment.

---

# 19. Security Assurance

Dunder Mifflin evaluates whether important controls are appropriately designed, implemented, operating, and effective.

Assurance activities may include:

- Inspection
- Observation
- Interviews
- Sampling
- Technical Testing
- Independent Performance
- Exercises
- Reconciliation

Assessment priority considers:

- Business criticality
- Information sensitivity
- Inherent risk
- Current residual risk
- Control dependency
- Previous findings
- Security incidents
- Material changes
- Potential consequences of control failure

A low residual risk rating does not automatically justify low assurance when strong controls are responsible for reducing a significant inherent risk.

Detailed assurance requirements are maintained in [[PRO-008 Security Assurance & Continuous Improvement Program]].

---

# 20. Findings and Corrective Action

Assessment results may identify satisfactory performance, partial performance, deficiencies, or other conditions requiring management attention.

Deficiencies requiring corrective action are tracked through [[REG-004 Finding & Corrective Action Register]].

The corrective-action lifecycle follows:

**Finding → Corrective Action → Remediation → Retest → Closure**

Closure requires evidence appropriate to the nature and significance of the finding.

Self-reported completion alone is not sufficient when validation is required.

Significant or repeated findings may require risk reassessment.

---

# 21. Continuous Monitoring

Continuous monitoring means maintaining risk-appropriate awareness of security conditions over time.

It does not require continuous technical surveillance of every system or activity.

Continuous monitoring may include:

- Security metrics
- Vulnerability results
- Access reviews
- Security events
- Incident trends
- Backup results
- Recovery tests
- Findings
- Corrective-action status
- Third-party reviews
- Risk-treatment progress
- Business and technology changes

Monitoring frequency depends on risk and business need.

---

# 22. Security Reporting

Security reporting is organized into three levels.

## 22.1 Executive Reporting

Executive reporting focuses on:

**Decisions and Enterprise Risk**

See [[RPT-006 Executive Security Summary]].

## 22.2 Management Reporting

Management reporting focuses on:

**Accountability, Performance, and Action**

See [[RPT-007 Management Security Report]].

## 22.3 Operational Reporting

Operational reporting focuses on:

**Execution, Evidence, Exceptions, and Technical Detail**

See [[RPT-008 Operational Security Report & Dashboard]].

Information should be escalated when operational conditions materially affect management responsibilities or enterprise risk.

---

# 23. Program Metrics

Security metrics are used to support decision-making rather than merely to generate activity counts.

Metrics may measure:

- Control performance
- Risk indicators
- Treatment progress
- Vulnerability remediation
- Authentication coverage
- Access reviews
- Personnel termination exceptions
- Security-awareness results
- Backup performance
- Recovery performance
- Incident trends
- Findings
- Corrective actions
- Third-party reviews
- Application-security activity

Metrics are defined in [[REG-005 Security Metrics Catalog]].

---

# 24. Program Review and Improvement

The security program is reviewed at least annually and when significant changes justify earlier review.

Program review considers:

- Changes in business operations
- Changes in technology
- Changes in information use
- New or changed third parties
- Security incidents
- Assessment findings
- Control failures
- Business continuity exercises
- Recovery testing
- Changes in risk
- Changes in legal or contractual requirements
- Management decisions
- Corrective-action trends

Program improvement should be based on evidence and risk rather than on the number of new controls introduced.

---

# 25. Program Traceability

The program maintains traceability through the following lifecycle:

**Business Requirement → Asset/Process → Classification/BIA → Risk → Treatment → Policy/Standard → Control → Procedure → Implementation → Evidence → Test/Assessment → Finding → Remediation → Retest → Risk Reassessment → Management Decision → Continuous Monitoring**

Detailed artifact relationships are maintained in [[REG-007 Cross-Reference Matrix]].

Control-level relationships are maintained in [[REG-003 Enterprise Security Control Inventory]].

---

# 26. Program Documentation

The controlled security document set includes:

- Policies
- Programs
- Standards
- Plans
- Procedures
- Registers
- Risk treatment plans
- Reports
- Templates
- Playbooks

The authoritative artifact inventory is maintained in [[INDEX-001 Artifact Index]].

Document-control information is maintained in [[REG-006 Document Control Register]].

---

# 27. Exceptions

Exceptions to security requirements must be:

1. Based on a legitimate business need.
2. Documented.
3. Evaluated for risk.
4. Approved by the appropriate authority.
5. Limited in scope.
6. Limited in duration when practical.
7. Subject to compensating controls where appropriate.
8. Reviewed before expiration or renewal.

An approved exception does not automatically constitute acceptance of all risk associated with the exception.

Risk acceptance requirements are governed by [[POL-005 Risk Management Policy]].

---

# 28. Enforcement

Failure to comply with applicable security requirements may result in:

- Removal or restriction of access
- Corrective action
- Management review
- Contractual action
- Personnel action consistent with company policy
- Legal action where appropriate

Enforcement should consider the nature, severity, intent, recurrence, and business impact of the violation.

---

# 29. Related Artifacts

- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[POL-001 Information Security Policy]]
- [[POL-003 Access Control Policy]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-006 Security Awareness & Training Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-008 Third-Party Security Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[POL-011 Physical & Environmental Security Policy]]
- [[POL-012 Application & Secure Development Policy]]
- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[REG-007 Cross-Reference Matrix]]

---

# 30. Revision History

| Version | Date     | Description              | Approval |
| ------- | -------- | ------------------------ | -------- |
| 1.0     | May 2013 | Initial approved release | CEO      |