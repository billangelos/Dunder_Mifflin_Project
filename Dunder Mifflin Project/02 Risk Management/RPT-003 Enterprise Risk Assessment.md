# RPT-003 Enterprise Risk Assessment

## Document Control

| Field | Value |
|---|---|
| Document ID | RPT-003 |
| Title | Enterprise Risk Assessment |
| Version | 1.0 |
| Classification | Confidential |
| Status | Approved |
| Owner | CIO |
| Approved By | CEO |
| Assessment Date | May 2013 |
| Review Frequency | Annual and Following Material Change |

---

# 1. Purpose

This report documents Dunder Mifflin's enterprise information security and operational risk assessment.

The assessment identifies significant risk scenarios affecting the organization's information, systems, personnel, facilities, business processes, third parties, and operational capabilities.

The assessment establishes:

- Risk-assessment scope
- Assessment assumptions
- Risk identification methodology
- Likelihood criteria
- Impact criteria
- Risk scoring
- Risk-rating thresholds
- Control-effectiveness evaluation
- Inherent risk
- Current residual risk
- Target residual risk
- Risk ownership
- Risk treatment considerations
- Reassessment requirements

Detailed risk records are maintained in [[REG-002 Enterprise Risk Register]].

Detailed treatment activities are maintained in [[RTP-001 Enterprise Risk Treatment Plan]].

---

# 2. Assessment Objectives

The assessment is intended to answer five primary questions:

1. What could materially interfere with Dunder Mifflin's business objectives?
2. What would the consequences be?
3. How likely is the event or condition?
4. How much risk remains after existing controls are considered?
5. What additional treatment is appropriate?

The objective is not to eliminate all risk.

The objective is to provide management with sufficient information to make informed risk decisions and prioritize security resources.

---

# 3. Assessment Scope

The assessment considers risks affecting:

- Business operations
- Information
- Applications
- Information Technology infrastructure
- Endpoints
- Identity and authentication
- Cloud-hosted systems
- Infinity
- Third parties
- Suppliers
- Facilities
- Warehouses
- Inventory
- Transportation
- Personnel
- Financial processes
- Backup and recovery
- Business continuity
- Physical security

The assessment uses the enterprise environment documented in [[RPT-001 Enterprise Profile & Security Baseline]].

Assets and dependencies are identified in [[REG-001 Enterprise Asset Register]].

Business criticality and recovery requirements are informed by [[RPT-002 Business Impact Analysis]].

---

# 4. Assessment Perspective

Risk is evaluated from Dunder Mifflin's business perspective.

The assessment considers effects on:

- Confidentiality
- Integrity
- Availability
- Financial performance
- Business operations
- Customers
- Employees
- Suppliers
- Legal and contractual obligations
- Reputation
- Safety

Risk scoring is not based solely on technical severity.

A technically significant vulnerability may create limited enterprise risk if business exposure is small.

A nontechnical event may create substantial enterprise risk if it disrupts an important business function.

---

# 5. Risk Statement Model

Risk scenarios are evaluated using the general relationship:

**Threat/Event + Vulnerability/Condition + Affected Asset or Process + Business Consequence**

For example:

> A phishing attack may exploit employee susceptibility and insufficient authentication protection to compromise user credentials, resulting in unauthorized access to company information or systems.

Risk statements should describe a meaningful business scenario rather than merely naming a vulnerability.

Examples of incomplete risk statements include:

- "No MFA"
- "Phishing"
- "Shared account"
- "Old software"
- "Cloud"

These may represent threats, vulnerabilities, or conditions, but they do not independently describe enterprise risk.

---

# 6. Risk Identification

Risks were identified through review of:

- Business processes
- Enterprise assets
- Information sensitivity
- Business Impact Analysis results
- Technology architecture
- Existing controls
- Personnel dependencies
- Third-party dependencies
- Physical conditions
- Financial processes
- Recovery capabilities
- Operational practices
- Reasonably foreseeable threat scenarios

Risk identification considers technical and nontechnical risk.

---

# 7. Risk Categories

The assessment includes risks involving:

## Cybersecurity and Information

Examples include:

- Phishing
- Credential compromise
- Malware
- Ransomware
- Unauthorized access
- Sensitive-information theft
- Application compromise

## Technology and Service Availability

Examples include:

- Cloud outages
- Internet outages
- Backup failure
- Data corruption
- Technology-provider failure

## Third Parties and Suppliers

Examples include:

- Provider compromise
- Contractor dependency
- Supplier disruption

## Physical and Environmental

Examples include:

- Fire
- Water
- Power failure
- HVAC failure
- Unauthorized physical access
- Facility loss
- Regional disaster

## Personnel

Examples include:

- Malicious insiders
- Delayed termination
- Key-person loss

## Fraud and Business Process

Examples include:

- Vendor fraud
- Sales fraud
- Payroll fraud
- Inventory theft
- Manual-processing errors

---

# 8. Likelihood Scale

Likelihood represents the reasonable probability or frequency of the risk scenario occurring under the conditions being evaluated.

Likelihood is scored using integer values from 1 through 5.

| Score | Rating | General Interpretation |
|---:|---|---|
| 1 | Rare | Unlikely to occur except under unusual circumstances |
| 2 | Unlikely | Could occur, but is not expected frequently |
| 3 | Possible | Reasonably foreseeable and may occur |
| 4 | Likely | Expected to occur or conditions make occurrence reasonably likely |
| 5 | Almost Certain | Expected to occur frequently or exposure is persistent and substantial |

Likelihood must be evaluated for the specific risk scenario.

The presence of a vulnerability does not automatically justify a likelihood score of 5.

---

# 9. Impact Scale

Impact represents the potential business consequence if the risk scenario occurs.

Impact is scored using integer values from 1 through 5.

| Score | Rating | General Interpretation |
|---:|---|---|
| 1 | Insignificant | Minimal disruption or loss; easily handled through routine operations |
| 2 | Minor | Limited operational, financial, customer, or administrative impact |
| 3 | Moderate | Material disruption or loss requiring management attention |
| 4 | Major | Serious business, financial, operational, security, or customer impact |
| 5 | Severe | Potentially severe enterprise impact, major operational disruption, substantial financial or legal consequence, or significant safety concern |

Impact should consider the credible consequences of the defined scenario rather than the worst imaginable outcome.

---

# 10. Risk Calculation

Risk is calculated as:

**Likelihood × Impact = Risk Score**

Only integer likelihood and impact values from 1 through 5 are used.

Fractional values are not used.

---

# 11. Risk Rating Thresholds

| Score | Rating |
|---:|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–16 | High |
| 17–25 | Critical |

The numeric score supports consistency.

The rating supports management communication and prioritization.

Two risks with the same numeric score may still require different treatment because their causes, consequences, dependencies, and treatment options differ.

---

# 12. Inherent Risk

Inherent risk represents the risk before existing controls are considered.

It answers:

> How significant would this risk be if the controls on which Dunder Mifflin currently relies were absent?

Inherent risk helps management understand the underlying importance of the risk.

A low current residual risk does not necessarily mean the underlying activity is unimportant.

Strong controls may be the reason the residual risk is low.

---

# 13. Current Residual Risk

Current residual risk represents the risk remaining after existing controls are considered.

Only controls that currently exist may influence current residual risk.

A proposed control does not reduce current residual risk.

A policy written as part of the security improvement program does not retroactively change the assessed environment.

Current residual risk may change when:

- A baseline assumption is corrected.
- An existing control is discovered and appropriately supported.
- A risk was originally scored incorrectly.
- Implemented treatment is later validated.
- Material business or threat conditions change.

Changes must be documented and traceable.

---

# 14. Target Residual Risk

Target residual risk represents the expected risk following successful implementation and validation of planned treatment.

Target residual risk is a planning estimate.

It is not:

- A guaranteed result
- An automatic future score
- A required minimum
- A substitute for testing

Validated post-treatment risk may be:

- Higher than target
- Equal to target
- Lower than target

The validated result becomes the new current residual risk for future assessment purposes while historical assessment results are preserved.

---

# 15. Control Effectiveness

Existing controls are evaluated using the following categories:

| Rating | Meaning |
|---|---|
| Effective | Control is appropriately designed and evidence supports reliable operation for the risk being evaluated |
| Partially Effective | Control provides meaningful risk reduction but has limitations in design, coverage, consistency, or operation |
| Ineffective | Control exists but does not provide meaningful or reliable risk reduction for the scenario |
| Not Implemented | Control does not currently exist |

Control effectiveness must be evaluated in relation to the risk being assessed.

A control may be effective for one risk and provide little protection against another.

---

# 16. Existing Versus Proposed Controls

The assessment maintains a strict distinction between existing and proposed controls.

## Existing Control

An existing control may influence current residual risk when it is relevant to the scenario and reasonably supported.

## Proposed Control

A proposed control may influence target residual risk but receives no credit toward current residual risk.

The general relationship is:

**Inherent Risk → Existing Controls → Current Residual Risk → Proposed Treatment → Target Residual Risk**

After implementation and validation:

**Implemented Control → Evidence → Assessment → Validated Effectiveness → Risk Reassessment**

---

# 17. Avoiding Double Counting

Risk scenarios must maintain meaningful boundaries.

The same consequence should not be repeatedly added to unrelated risks solely to increase their severity.

Examples include:

- **R012 Malicious Insider** addresses malicious use of legitimately authorized insider access.
- **R010 Unauthorized / Excessive Access** addresses inappropriate access authorization or excessive permissions.
- **R016 Cloud Service Outage** addresses loss of cloud-hosted service availability.
- **R017 Internet Service Provider Outage** addresses loss of a facility's primary wired Internet service.
- **R035 Regional Disaster** addresses broader events capable of affecting multiple facilities or communications services simultaneously.

Related risks may share controls without becoming the same risk.

---

# 18. Risk Ownership

Risk ownership follows business accountability.

A technology component does not automatically make Information Technology the owner of every associated business risk.

Examples include:

- CIO ownership of technology and cybersecurity risks
- COO ownership of warehouse, inventory, transportation, supplier, facility, and operational risks
- CFO ownership of financial, accounting, payroll, and fraud risks
- Human Resources responsibility for personnel lifecycle processes
- Business owners responsible for risks associated with their functions

The IT & Information Security Manager coordinates many security controls but does not automatically own the business risks those controls help address.

---

# 19. Risk Treatment Options

Dunder Mifflin recognizes four principal risk-treatment approaches:

## Mitigate

Reduce likelihood, impact, or both through controls.

## Transfer

Shift or share specified financial or operational consequences through mechanisms such as insurance or contracts.

Transfer does not necessarily eliminate the underlying operational risk.

## Avoid

Discontinue or change the activity creating the risk.

## Accept

Consciously retain the risk within approved authority.

Risk treatment is governed by [[POL-005 Risk Management Policy]].

---

# 20. Risk Acceptance

Risk acceptance authority depends on residual risk.

General requirements are:

- **Low:** Risk owner
- **Moderate:** Risk owner with appropriate executive approval
- **High:** CEO approval following ISRC review
- **Critical:** CEO approval following ISRC review and exceptional justification

High risk acceptance must be reassessed within a maximum of 90 days.

Critical risk acceptance must be reassessed within a maximum of 30 days.

Acceptance does not mean the risk ceases to exist.

---

# 21. Assessment Assumptions

The assessment relies on the enterprise conditions documented in [[RPT-001 Enterprise Profile & Security Baseline]].

Important assumptions include:

- Approximately 138 employees
- Corporate headquarters plus six branch facilities
- Cloud-hosted centralized systems
- Windows 7 endpoints
- Windows Server 2012 Standard
- Centralized Active Directory
- No general enterprise MFA
- Centrally managed commercial antivirus
- No enterprise EDR platform
- No dedicated SIEM
- No 24-hour SOC
- No general corporate wireless network
- One Internet-only guest wireless access point at headquarters
- Standard user privileges for ordinary users
- Separate privileged credentials for IT personnel
- Full-disk encryption on company laptops
- Central Windows patch management
- Company-issued mobile devices where required
- Existing backup and off-site media rotation
- Inconsistent restoration testing
- Basic third-party due diligence
- Existing confidentiality requirements for sensitive third-party access
- Third-party support for Infinity
- No company-operated major data center at headquarters

If a material assumption is found to be inaccurate, the affected risk should be reassessed.

---

# 22. Enterprise Risk Summary

The assessment identifies 35 enterprise risks.

| ID | Risk | Inherent | Current Residual | Target Residual |
|---|---|---:|---:|---:|
| R001 | Phishing / Credential Compromise | 20 Critical | 12 High | 6 Moderate |
| R002 | Business Email Compromise | 16 High | 8 Moderate | 4 Low |
| R003 | Ransomware | 25 Critical | 12 High | 6 Moderate |
| R004 | Malware | 20 Critical | 12 High | 6 Moderate |
| R005 | Password / Authentication Weakness | 16 High | 12 High | 4 Low |
| R006 | Infinity Application Compromise | 16 High | 12 High | 8 Moderate |
| R007 | Internet Infrastructure Compromise | 16 High | 12 High | 8 Moderate |
| R008 | Denial-of-Service Attack | 9 Moderate | 6 Moderate | 6 Moderate |
| R009 | Sensitive Information Theft / Extortion | 16 High | 12 High | 4 Low |
| R010 | Unauthorized / Excessive Access | 16 High | 12 High | 4 Low |
| R011 | Delayed Termination Access Removal | 16 High | 8 Moderate | 4 Low |
| R012 | Malicious Insider | 15 High | 10 High | 5 Moderate |
| R013 | Administrative / Configuration Error | 16 High | 12 High | 6 Moderate |
| R014 | Lost or Stolen Device | 16 High | 8 Moderate | 4 Low |
| R015 | Shared Warehouse Account | 12 High | 9 Moderate | 4 Low |
| R016 | Cloud Service Outage | 15 High | 8 Moderate | 6 Moderate |
| R017 | Internet Service Provider Outage | 16 High | 9 Moderate | 4 Low |
| R018 | Third-Party Technology Failure / Compromise | 12 High | 8 Moderate | 6 Moderate |
| R019 | Infinity Contractor Dependency / Compromise | 12 High | 8 Moderate | 4 Low |
| R020 | Supplier Disruption | 16 High | 9 Moderate | 6 Moderate |
| R021 | Fire | 15 High | 8 Moderate | 5 Moderate |
| R022 | Water Damage | 16 High | 9 Moderate | 4 Low |
| R023 | Utility / Power / HVAC Failure | 16 High | 9 Moderate | 4 Low |
| R024 | Unauthorized Physical Access | 16 High | 8 Moderate | 4 Low |
| R025 | Vehicle Loss / Accident | 16 High | 9 Moderate | 4 Low |
| R026 | Loss of Key Personnel | 16 High | 9 Moderate | 4 Low |
| R027 | Backup / Recovery Failure | 20 Critical | 12 High | 5 Moderate |
| R028 | Data Corruption | 16 High | 9 Moderate | 4 Low |
| R029 | Vendor Fraud | 16 High | 6 Moderate | 3 Low |
| R030 | Sales Fraud | 16 High | 6 Moderate | 3 Low |
| R031 | Payroll Fraud | 12 High | 6 Moderate | 3 Low |
| R032 | Inventory Theft | 12 High | 6 Moderate | 3 Low |
| R033 | Manual Outage Processing Error | 12 High | 9 Moderate | 4 Low |
| R034 | Loss of Corporate Headquarters | 10 High | 8 Moderate | 4 Low |
| R035 | Regional Disaster | 9 Moderate | 6 Moderate | 5 Moderate |

---

# 23. Current High-Risk Concentration

The assessment identifies the following risks with a current residual rating of High:

- **R001 Phishing / Credential Compromise**
- **R003 Ransomware**
- **R004 Malware**
- **R005 Password / Authentication Weakness**
- **R006 Infinity Application Compromise**
- **R007 Internet Infrastructure Compromise**
- **R009 Sensitive Information Theft / Extortion**
- **R010 Unauthorized / Excessive Access**
- **R012 Malicious Insider**
- **R013 Administrative / Configuration Error**
- **R027 Backup / Recovery Failure**

These risks warrant significant management attention.

The presence of a High residual rating does not automatically require the same treatment priority for every risk. Dependencies, implementation sequencing, treatment feasibility, and expected risk reduction must also be considered.

---

# 24. R001 Phishing / Credential Compromise

**Inherent:** 20 Critical  
**Current Residual:** 12 High  
**Target Residual:** 6 Moderate

Phishing represents a significant path for credential compromise and unauthorized access.

Existing controls provide some protection, including:

- Commercial antivirus
- Standard user privileges
- Basic email protections
- Existing security practices

Current controls do not provide sufficient assurance to reduce the risk below High.

Treatment includes:

- Improved email filtering
- Anti-phishing controls
- Blocking known malicious senders
- Suspicious-link protections
- Malicious-attachment protections
- Spoofing protections
- Common phishing-indicator detection
- Smart-card MFA where supported
- Security awareness
- Monthly phishing simulations
- Least privilege
- Separate privileged credentials
- Authentication and security-event monitoring
- Endpoint protection
- Incident response

The target rating assumes successful implementation and validation of the planned control set.

---

# 25. R002 Business Email Compromise

**Inherent:** 16 High  
**Current Residual:** 8 Moderate  
**Target Residual:** 4 Low

Business Email Compromise may exploit compromised accounts, spoofing, social engineering, or fraudulent business requests.

Potential consequences include:

- Fraudulent payments
- Sensitive information disclosure
- Unauthorized business transactions
- Customer or supplier fraud
- Reputation damage

Treatment emphasizes stronger authentication, email protection, user awareness, verification of sensitive requests, monitoring, and incident response.

---

# 26. R003 Ransomware

**Inherent:** 25 Critical  
**Current Residual:** 12 High  
**Target Residual:** 6 Moderate

Ransomware could disrupt endpoints, shared information, or business systems and may interfere with normal operations.

Existing antivirus, standard-user operation, patch management, and backup capabilities reduce risk but do not provide sufficient assurance to reduce the current rating below High.

Treatment emphasizes:

- Prevention
- Vulnerability reduction
- Endpoint protection
- Monitoring
- Incident response
- Backup resilience
- Restoration testing
- Business continuity

Ransomware treatment must not assume that the mere existence of backups guarantees recovery.

---

# 27. R004 Malware

**Inherent:** 20 Critical  
**Current Residual:** 12 High  
**Target Residual:** 6 Moderate

Malware is used as an umbrella risk category for malicious software capable of compromising endpoints, information, credentials, or business operations.

Existing centrally managed antivirus provides meaningful protection but does not eliminate malware risk.

Treatment emphasizes layered endpoint, configuration, patching, monitoring, awareness, and response controls.

---

# 28. R005 Password / Authentication Weakness

**Inherent:** 16 High  
**Current Residual:** 12 High  
**Target Residual:** 4 Low

The absence of general MFA increases the significance of compromised or weak authentication credentials.

Treatment includes:

- Smart-card MFA with a PIN or other secret where supported
- Individual accountability
- Separate privileged credentials
- Restricted standing Domain Administrator membership
- Dedicated administrative workstations
- No external remote privileged administration
- Dormant-account management
- Access reviews
- Contractor-access duration controls
- Emergency-access protection
- Prompt termination
- Transfer reauthorization
- Authentication monitoring

This risk addresses weaknesses in authentication architecture and account controls.

Phishing and other external credential-acquisition attacks remain separately addressed under R001.

---

# 29. R006 Infinity Application Compromise

**Inherent:** 16 High  
**Current Residual:** 12 High  
**Target Residual:** 8 Moderate

Infinity is Internet-facing and supports customer ordering.

Compromise could affect:

- Customer information
- Order integrity
- Application availability
- Company reputation
- Dunder Mifflin intellectual property

Treatment includes:

- Web, application, and database separation
- Company-controlled source repository and documentation
- Threat modeling
- Development, test, and production separation
- Code review
- Security testing
- Annual Infinity security assessment
- Annual application penetration testing
- Remediation and retesting
- Controlled contractor access
- Incident response
- Recovery capability

Application testing follows:

**Penetration Test → Finding → Remediation → Retest → Control Effectiveness → R006 Reassessment**

---

# 30. R007 Internet Infrastructure Compromise

**Inherent:** 16 High  
**Current Residual:** 12 High  
**Target Residual:** 8 Moderate

Compromise of Internet-facing network infrastructure could provide unauthorized access, disrupt communications, or weaken perimeter security.

Treatment includes:

- Firewall controls
- Denial of unsolicited inbound access
- No directly exposed administrative services
- Protected remote connectivity
- Configuration baselines
- Patch management
- Change management
- Privileged-access restrictions
- Network discovery
- Rogue wireless detection
- Configuration backups
- Appropriate spare equipment

---

# 31. R008 Denial-of-Service Attack

**Inherent:** 9 Moderate  
**Current Residual:** 6 Moderate  
**Target Residual:** 6 Moderate

Dunder Mifflin cannot eliminate external denial-of-service risk.

Treatment uses a combination of mitigation and acceptance.

Controls include:

- Firewall and provider protections
- Incident response
- Provider escalation
- Business continuity
- Cellular connectivity where applicable
- Manual continuity
- Periodic evaluation of additional resilience options

The target remains Moderate because further reduction is not currently expected to justify disproportionate cost or complexity.

---

# 32. R009 Sensitive Information Theft / Extortion

**Inherent:** 16 High  
**Current Residual:** 12 High  
**Target Residual:** 4 Low

Sensitive information may be targeted for theft, unauthorized disclosure, coercion, or extortion.

Treatment includes:

- Information classification
- Encryption
- Laptop full-disk encryption
- Least privilege
- Physical security
- Secure disposal
- Confidentiality agreements
- Incident response
- Backup protection
- Security awareness

Malicious misuse by a legitimately authorized insider is principally addressed through R012.

---

# 33. R010 Unauthorized / Excessive Access

**Inherent:** 16 High  
**Current Residual:** 12 High  
**Target Residual:** 4 Low

Users may receive access they do not require, retain access following role changes, or accumulate excessive permissions.

Treatment includes:

- Least privilege
- Business need
- Owner approval
- Transfer revocation and reauthorization
- Prompt termination
- Annual ordinary-user access review
- Quarterly privileged-access review
- Separate privileged credentials
- Restricted standing Domain Administrator membership
- Dormant-account management
- Contractor duration controls
- Emergency-access controls
- Individual accountability for significant WMS transactions

Authorized malicious activity is principally addressed under R012.

---

# 34. R011 Delayed Termination Access Removal

**Inherent:** 16 High  
**Current Residual:** 8 Moderate  
**Target Residual:** 4 Low

Delayed removal of access following employment or contract termination may permit unauthorized access after the legitimate business relationship ends.

Treatment includes:

- HR as authoritative employee-status source
- Prompt termination notification
- Prompt account disablement
- Equipment recovery
- Credential recovery
- Key and access-card recovery
- Smart-card recovery where applicable
- Removal of system and facility access
- Termination checklist
- Testing and exception review

Repeated termination failures require corrective action.

---

# 35. R012 Malicious Insider

**Inherent:** 15 High  
**Current Residual:** 10 High  
**Target Residual:** 5 Moderate

A legitimately authorized individual may intentionally misuse access.

Treatment includes:

- Least privilege
- Separation of duties
- Individual accountability
- Separate privileged credentials
- Access reviews
- Personnel controls
- Information classification
- Physical controls
- Financial approval controls
- Security awareness and reporting
- Incident response

Treatment must remain proportional and respect legitimate privacy expectations.

The risk does not justify indiscriminate employee surveillance.

---

# 36. R013 Administrative / Configuration Error

**Inherent:** 16 High  
**Current Residual:** 12 High  
**Target Residual:** 6 Moderate

Administrative errors or inappropriate configuration changes may create security exposure or service disruption.

Treatment includes:

- Configuration baselines
- Change management
- Review and approval
- Proportional separation of duties
- Testing
- Staged implementation where appropriate
- Rollback capability
- Post-change verification
- Documentation
- Configuration backups
- Privileged-access controls
- Lessons learned

---

# 37. R014 Lost or Stolen Device

**Inherent:** 16 High  
**Current Residual:** 8 Moderate  
**Target Residual:** 4 Low

Existing laptop full-disk encryption, authentication, screen locking, standard-user operation, and central management materially reduce risk.

Treatment strengthens:

- Device management
- Remote lock or wipe where supported
- Inventory
- Reporting
- Credential response
- Incident handling

Physical loss of a device does not automatically mean the information on the device has been compromised.

---

# 38. R015 Shared Warehouse Account

**Inherent:** 12 High  
**Current Residual:** 9 Moderate  
**Target Residual:** 4 Low

Shared Windows workstation accounts may be operationally useful in warehouse environments but can reduce individual accountability.

Treatment does not require elimination of every shared workstation login.

Instead:

- Shared workstation access remains limited to justified operational use.
- Workstation permissions remain minimal.
- Significant WMS transactions require individual authentication or attribution.
- Access is periodically reviewed.
- Relevant activity is logged.

---

# 39. R016 Cloud Service Outage

**Inherent:** 15 High  
**Current Residual:** 8 Moderate  
**Target Residual:** 6 Moderate

Cloud hosting reduces dependence on individual Dunder Mifflin facilities but creates provider dependency.

Treatment includes:

- Business continuity planning
- Disaster recovery planning
- Cloud Exit & Emergency Migration Plan
- Independent recovery documentation
- Encrypted backups
- Manual continuity
- Provider escalation
- Provider resilience review
- Contractual considerations
- Concentration-risk evaluation

Dunder Mifflin does not maintain an unnecessary continuously operating alternate cloud solely to address this risk.

---

# 40. R017 Internet Service Provider Outage

**Inherent:** 16 High  
**Current Residual:** 9 Moderate  
**Target Residual:** 4 Low

This risk addresses loss of a facility's primary wired Internet service.

Treatment includes:

- Company-issued cellular connectivity as a secondary Internet path where applicable
- Provider escalation
- Business continuity procedures
- Manual processes for functions that cannot operate through cellular connectivity

A broader event affecting wired Internet, cellular service, transportation, and multiple facilities is addressed under R035.

---

# 41. R018 Third-Party Technology Failure / Compromise

**Inherent:** 12 High  
**Current Residual:** 8 Moderate  
**Target Residual:** 6 Moderate

Dunder Mifflin depends on external technology providers.

Treatment includes:

- Critical, Important, and Routine third-party classification
- Due diligence
- Contracts
- Confidentiality requirements
- Incident requirements
- Recovery requirements
- Audit or assessment rights where appropriate
- Critical-provider annual review
- Important-provider biennial review
- 24-hour security-incident notification from discovery for applicable providers
- Third-party inventory
- Access restrictions
- Exit and continuity considerations

---

# 42. R019 Infinity Contractor Dependency / Compromise

**Inherent:** 12 High  
**Current Residual:** 8 Moderate  
**Target Residual:** 4 Low

Dunder Mifflin depends on a third-party contractor for Infinity support.

Treatment includes:

- Dunder Mifflin ownership of source code, repository, documentation, intellectual property, data, and backups
- Confidentiality obligations
- Management sponsorship
- Time-limited access
- Strong authentication where supported
- No general contractor VPN
- Privileged work from a controlled headquarters workstation
- Least privilege
- Advance identification of expected contractor personnel
- Change and code-security requirements
- Annual Infinity assessment
- Annual penetration testing and retesting
- Documentation
- Annual transferability review

---

# 43. R020 Supplier Disruption

**Inherent:** 16 High  
**Current Residual:** 9 Moderate  
**Target Residual:** 6 Moderate

Supplier disruption may affect product availability, fulfillment, pricing, and customer commitments.

Treatment includes:

- Alternate suppliers where practical
- Inventory management
- Supplier monitoring
- Operational coordination
- Customer communication
- Periodic sourcing review

Complete elimination of supplier risk is neither practical nor required.

---

# 44. R021 Fire

**Inherent:** 15 High  
**Current Residual:** 8 Moderate  
**Target Residual:** 5 Moderate

Fire may affect personnel, facilities, inventory, equipment, and business operations.

Treatment prioritizes:

- Life safety
- Fire-protection systems
- Landlord coordination
- Evacuation
- Off-site backups
- Business continuity
- Disaster recovery
- Independent recovery documentation
- Insurance
- Appropriate inspection

No employee is expected to protect company assets at unreasonable personal risk.

---

# 45. R022 Water Damage

**Inherent:** 16 High  
**Current Residual:** 9 Moderate  
**Target Residual:** 4 Low

Water may damage equipment, inventory, paper records, or facilities.

Treatment includes:

- Avoiding unnecessary placement near known water hazards
- Appropriate equipment elevation
- Leak inspection
- Landlord coordination
- Off-site backups
- Continuity planning
- Insurance
- Protection of important paper records

Regional flooding affecting multiple locations is addressed under R035.

---

# 46. R023 Utility / Power / HVAC Failure

**Inherent:** 16 High  
**Current Residual:** 9 Moderate  
**Target Residual:** 4 Low

Loss of electrical power or environmental services may interrupt facility operations.

Existing UPS capability supports critical network equipment and selected management and Sales workstations for approximately 30 minutes.

Treatment includes:

- UPS support
- Orderly shutdown
- Landlord coordination
- Inspection and maintenance
- Continuity procedures
- Cloud-hosted centralized systems
- Company laptops and mobile communications
- Manual warehouse processing

Generators are not required unless later business requirements and cost analysis justify them.

---

# 47. R024 Unauthorized Physical Access

**Inherent:** 16 High  
**Current Residual:** 8 Moderate  
**Target Residual:** 4 Low

Unauthorized physical access could expose personnel, systems, records, equipment, or inventory.

Treatment includes:

- Facility security zones
- Receptionist-controlled entry
- Employee card access
- Visitor logging
- Escort requirements
- Restricted-area authorization
- Vendor-access controls
- Key management
- Annual access review
- Termination credential removal
- Warehouse security cages

---

# 48. R025 Vehicle Loss / Accident

**Inherent:** 16 High  
**Current Residual:** 9 Moderate  
**Target Residual:** 4 Low

Vehicle incidents may cause injury, delivery disruption, financial loss, liability, or loss of company information or equipment.

Treatment includes:

- Authorized drivers
- Driver qualification
- Registration
- Insurance
- Inspection
- Maintenance
- Compliance with traffic laws
- Incident reporting
- Delivery continuity
- Protection of information and equipment
- Avoidance of unnecessary sensitive or valuable items left unattended in vehicles

Safety remains the primary concern.

---

# 49. R026 Loss of Key Personnel

**Inherent:** 16 High  
**Current Residual:** 9 Moderate  
**Target Residual:** 4 Low

Loss or unavailability of personnel with specialized knowledge or authority may disrupt business or recovery activities.

Treatment includes:

- Identification of key dependencies
- Sufficient documentation
- Cross-training
- Alternate personnel
- Delegated authority
- Company ownership of credentials, configurations, source code, and recovery information
- Emergency-access capability
- Periodic review of key-person dependencies

Documentation should permit a qualified replacement unfamiliar with a system to perform required recovery activities.

---

# 50. R027 Backup / Recovery Failure

**Inherent:** 20 Critical  
**Current Residual:** 12 High  
**Target Residual:** 5 Moderate

Dunder Mifflin maintains automated backups, cloud backup capabilities, and encrypted physical backup rotation.

Existing backup capability reduces risk, but inconsistent restoration testing and incomplete validation of coverage prevent stronger assurance.

Treatment includes:

- Validation of backup coverage against the asset inventory, classification requirements, and BIA
- Off-site separation
- Backup-job monitoring
- Quarterly representative restoration tests
- Annual meaningful recovery testing for Critical functions
- Recovery documentation usable by a qualified unfamiliar IT professional
- Appropriate retention and rotation
- Protection of backup administration
- Evaluation of resilience against production compromise

A backup is valuable only if required information can be restored within business requirements.

---

# 51. R028 Data Corruption

**Inherent:** 16 High  
**Current Residual:** 9 Moderate  
**Target Residual:** 4 Low

Data may be corrupted through error, software failure, unauthorized activity, or inappropriate changes.

Treatment includes:

- Controlled access
- Change management
- Validated backups
- Application and database integrity controls
- Restricted administrative access
- Logging
- Investigation of integrity problems
- Restore validation
- Infinity integrity controls
- Business reconciliation

---

# 52. R029 Vendor Fraud

**Inherent:** 16 High  
**Current Residual:** 6 Moderate  
**Target Residual:** 3 Low

Vendor fraud may involve fraudulent vendors, invoices, payment instructions, or unauthorized vendor-record changes.

Treatment includes:

- Separation of vendor setup, purchasing, invoice approval, and payment where practical
- Authorization of new vendors
- Authorization of payment changes
- Independent verification of suspicious or significant banking changes using a trusted contact method
- Restricted vendor-master access
- Restricted payment access
- Record retention
- Reconciliation
- Due diligence
- Awareness
- Investigation

---

# 53. R030 Sales Fraud

**Inherent:** 16 High  
**Current Residual:** 6 Moderate  
**Target Residual:** 3 Low

Sales fraud may involve unauthorized pricing, discounts, credits, refunds, or manipulation of customer transactions.

Treatment includes:

- Individual accountability
- Role-based permissions
- Approval of significant pricing, discount, credit, or refund activity
- Transaction attribution
- Reconciliation among ordering, fulfillment, invoicing, credit, and payment
- Investigation of anomalies
- Practical separation of duties
- Awareness

---

# 54. R031 Payroll Fraud

**Inherent:** 12 High  
**Current Residual:** 6 Moderate  
**Target Residual:** 3 Low

Payroll fraud may involve unauthorized employee records, compensation changes, banking changes, deductions, or payments.

Treatment includes:

- Separation of employee-record maintenance, payroll preparation, approval, and payment where practical
- HR as authoritative employee-status source
- Restricted payroll access
- Authorization of compensation and banking changes
- Independent verification of suspicious payment changes using trusted contact information
- Reconciliation against active employees and approved compensation
- Review of unusual adjustments, duplicates, or unexpected employees
- Individual accountability
- Investigation involving HR, Finance, Legal, and Incident Response as appropriate

---

# 55. R032 Inventory Theft

**Inherent:** 12 High  
**Current Residual:** 6 Moderate  
**Target Residual:** 3 Low

Inventory may be stolen by insiders or outsiders.

Existing warehouse controls include locked security cages for higher-value and theft-attractive inventory.

Treatment includes:

- Controlled warehouse access
- Restricted security-cage access
- WMS records
- Individual accountability for significant transactions
- Inventory counts
- Reconciliation
- Investigation of discrepancies
- Receiving and shipping records sufficient to reconcile inventory movement
- Visitor, vendor, and delivery controls
- Personnel and fraud controls

Material inventory theft should become difficult without bypassing physical controls or creating discrepancies in inventory, receiving, shipping, or transaction records.

---

# 56. R033 Manual Outage Processing Error

**Inherent:** 12 High  
**Current Residual:** 9 Moderate  
**Target Residual:** 4 Low

Manual continuity procedures increase the possibility of missing, duplicate, inaccurate, or unauthorized transactions.

Treatment includes:

- Documented manual procedures
- Standardized paper or offline records
- Customer/order/employee/timestamp attribution
- Review before system entry
- Reconciliation
- Verification
- Investigation of missing or duplicate activity
- Training
- Exercises

The manual transaction lifecycle is:

**Collect → Review → Enter → Reconcile → Verify**

---

# 57. R034 Loss of Corporate Headquarters

**Inherent:** 10 High  
**Current Residual:** 8 Moderate  
**Target Residual:** 4 Low

Loss of corporate headquarters could disrupt executive, corporate, IT coordination, and contractor-support functions.

Headquarters is not a company-operated data center.

Treatment includes:

- Cloud-hosted systems
- Encrypted off-site backups
- Independent recovery documentation
- Printed recovery documentation
- Business continuity planning
- Company laptops
- Company cellular connectivity
- Alternate communications
- Relocation or distribution of headquarters functions
- Insurance
- Alternate personnel
- Delegated authority
- Safety procedures

---

# 58. R035 Regional Disaster

**Inherent:** 9 Moderate  
**Current Residual:** 6 Moderate  
**Target Residual:** 5 Moderate

A regional disaster may simultaneously affect multiple facilities, personnel, communications services, suppliers, utilities, or transportation.

Existing geographic distribution provides some resilience.

Treatment includes:

- Geographic distribution
- Cloud-hosted systems
- Geographically separated encrypted backups
- Business continuity and disaster recovery planning
- Management succession
- Alternate communications
- Support from unaffected branches
- Manual continuity
- Insurance
- Supplier alternatives
- Transportation alternatives
- Situation monitoring
- Personnel safety and accountability

The target remains Moderate because regional events cannot be fully controlled by Dunder Mifflin.

---

# 59. Treatment Prioritization

Treatment priority considers more than the numeric risk score.

Management should also consider:

- Risk rating
- Business criticality
- Control dependencies
- Treatment dependencies
- Treatment cost
- Implementation time
- Expected risk reduction
- Existing projects
- Resource availability
- Legal or contractual requirements
- Common controls that reduce multiple risks

For example, stronger Identity and Access Management may reduce several risks simultaneously.

Likewise, improved backup and recovery capability may reduce ransomware, corruption, facility-loss, and continuity risks.

---

# 60. Risk Dependencies

Risks may interact.

Examples include:

- R001 may lead to R009 or contribute to R003.
- R005 may increase exposure to R001, R010, or R012.
- R013 may create conditions contributing to R006 or R007.
- R027 may increase the impact of R003, R028, R034, or R035.
- R018 may contribute to service disruption or information compromise.
- R026 may impair incident response or disaster recovery.

Risk relationships do not require combining the risks when separate ownership, causes, controls, or treatment decisions make separate tracking useful.

---

# 61. Risk Treatment Plan

Detailed response activities are maintained in [[RTP-001 Enterprise Risk Treatment Plan]].

The treatment plan identifies:

- Treatment decision
- Treatment objective
- Responsible parties
- Required actions
- Priority
- Dependencies
- Expected evidence
- Validation method
- Target residual risk

Treatment status follows:

**Planned → Approved → Implementing → Implemented → Validation Pending → Validated**

**Corrective Action Required** may be assigned when necessary.

---

# 62. Validation

Implementation alone does not demonstrate control effectiveness.

Validation may include:

- Inspection
- Observation
- Interview
- Sampling
- Technical Testing
- Independent Performance
- Exercises
- Reconciliation

The validation method must be appropriate to the control and risk.

Evidence must not be manufactured, backdated, or altered to create the appearance that a control operated when it did not.

---

# 63. Findings and Corrective Action

Assessment or testing may identify control deficiencies.

Deficiencies requiring remediation are documented in [[REG-004 Finding & Corrective Action Register]].

The general lifecycle is:

**Finding → Corrective Action → Remediation → Retest → Control Effectiveness → Risk Reassessment**

A finding is not automatically closed because remediation has been reported as complete.

Appropriate evidence and validation are required.

---

# 64. Risk Reassessment

Risk should be reassessed when:

- Material treatment has been implemented and validated.
- A significant control fails.
- A major incident occurs.
- Business conditions materially change.
- Technology materially changes.
- Significant third-party relationships change.
- Assessment findings change understanding of control effectiveness.
- Baseline assumptions are found to be incorrect.
- Threat conditions materially change.

Risk reassessment asks:

1. Was treatment actually implemented?
2. Does the control operate as intended?
3. Is there sufficient evidence?
4. Does the control materially reduce likelihood, impact, or both?
5. Have new dependencies or vulnerabilities been introduced?
6. What is the validated residual risk?

The target score must not simply be copied into the current residual-risk field.

---

# 65. Historical Risk Preservation

Prior risk assessments must be preserved when risk ratings change.

For example:

**May 2013 Current Residual Risk: 12 High**

may later become:

**Validated Residual Risk: 5 Moderate**

The earlier assessment remains part of the risk history.

This permits management to understand:

- Previous exposure
- Treatment effectiveness
- Risk movement
- Control improvement
- Changes in assumptions

Historical risk should not be overwritten merely to make the current program appear stronger.

---

# 66. Reporting

Risk information is reported according to audience.

## Executive

Focus:

- Enterprise risk
- Significant changes
- Resource decisions
- Major treatment priorities
- Risk acceptance

See [[RPT-006 Executive Security Summary]].

## Management

Focus:

- Accountability
- Treatment progress
- Findings
- Performance
- Required action

See [[RPT-007 Management Security Report]].

## Operational

Focus:

- Execution
- Evidence
- Exceptions
- Technical details
- Remediation

See [[RPT-008 Operational Security Report & Dashboard]].

---

# 67. Assessment Limitations

This assessment represents a reasoned evaluation based on the information available to Dunder Mifflin.

Risk scoring is not mathematical certainty.

Limitations may include:

- Incomplete evidence
- Changing threats
- Changing business conditions
- Third-party uncertainty
- Human behavior
- Unknown vulnerabilities
- Limited historical security data
- Assumptions concerning control operation

These limitations do not make risk assessment ineffective.

They require management to understand that risk ratings are decision-support tools rather than predictions of exact future loss.

---

# 68. Management Conclusion

The assessment identifies meaningful existing security strengths, including centralized authentication, standard-user operation, endpoint antivirus, laptop encryption, patch management, cloud-hosted systems, geographic distribution, off-site encrypted backups, and existing physical-security controls.

Significant residual risk remains in several areas.

The most important current High risks are concentrated around:

- Credential compromise
- Malware and ransomware
- Authentication
- Infinity security
- Internet infrastructure
- Sensitive information
- Access control
- Insider activity
- Administrative configuration
- Backup and recovery

Risk treatment should prioritize improvements that reduce multiple related risks while maintaining appropriate business usability and cost.

Planned security controls must not be treated as existing protection until implementation and validation occur.

---

# 69. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[REG-001 Enterprise Asset Register]]
- [[STD-001 Information Classification Standard]]
- [[RPT-002 Business Impact Analysis]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[POL-005 Risk Management Policy]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[PLN-005 Annual Assurance Plan]]
- [[TMP-001 Assessment Work Plan Template]]
- [[REG-004 Finding & Corrective Action Register]]
- [[RPT-006 Executive Security Summary]]
- [[RPT-007 Management Security Report]]
- [[RPT-008 Operational Security Report & Dashboard]]

---

# 70. Revision History

| Version | Date     | Description                        | Approval |
| ------- | -------- | ---------------------------------- | -------- |
| 1.0     | May 2013 | Initial Enterprise Risk Assessment | CEO      |