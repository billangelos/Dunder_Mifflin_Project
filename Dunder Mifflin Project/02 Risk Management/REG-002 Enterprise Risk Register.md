# REG-002 Enterprise Risk Register

## Document Control

| Field | Value |
|---|---|
| Document ID | REG-002 |
| Title | Enterprise Risk Register |
| Version | 1.0 |
| Classification | Confidential |
| Status | Active |
| Owner | CIO |
| Approved By | CEO |
| Assessment Date | May 2013 |
| Review Frequency | Quarterly and Following Material Change |

---

# 1. Purpose

This register is the authoritative working record of significant enterprise security and operational risks identified by Dunder Mifflin.

The register provides management with a consolidated view of:

- Risk identification
- Risk ownership
- Inherent risk
- Existing controls
- Control effectiveness
- Current residual risk
- Treatment strategy
- Target residual risk
- Treatment status

Detailed assessment methodology and risk analysis are maintained in [[RPT-003 Enterprise Risk Assessment]].

Detailed treatment activities are maintained in [[RTP-001 Enterprise Risk Treatment Plan]].

---

# 2. Risk Scoring

Risk is calculated as:

**Likelihood × Impact = Risk Score**

Likelihood and impact use integer values from 1 through 5.

| Score | Rating |
|---:|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–16 | High |
| 17–25 | Critical |

The register distinguishes among:

- **Inherent Risk:** Risk before existing controls are considered.
- **Current Residual Risk:** Risk remaining after existing controls are considered.
- **Target Residual Risk:** Expected risk following successful implementation and validation of planned treatment.

Proposed controls receive no credit toward current residual risk.

---

# 3. Control Effectiveness

Existing controls are evaluated using:

- Effective
- Partially Effective
- Ineffective
- Not Implemented

The effectiveness rating represents the overall effectiveness of the existing control environment for the specific risk.

Individual controls may perform differently.

---

# 4. Treatment Status

Risk-treatment status uses the following lifecycle:

**Planned → Approved → Implementing → Implemented → Validation Pending → Validated**

**Corrective Action Required** may be assigned when implementation or validation identifies a deficiency.

An Implemented status does not mean the treatment has been demonstrated effective.

---

# 5. Enterprise Risk Summary

| ID | Risk | Owner | Inherent | Current Residual | Treatment | Target |
|---|---|---|---:|---:|---|---:|
| R001 | Phishing / Credential Compromise | CIO | 20 Critical | 12 High | Mitigate | 6 Moderate |
| R002 | Business Email Compromise | CFO | 16 High | 8 Moderate | Mitigate | 4 Low |
| R003 | Ransomware | CIO | 25 Critical | 12 High | Mitigate | 6 Moderate |
| R004 | Malware | CIO | 20 Critical | 12 High | Mitigate | 6 Moderate |
| R005 | Password / Authentication Weakness | CIO | 16 High | 12 High | Mitigate | 4 Low |
| R006 | Infinity Application Compromise | CIO | 16 High | 12 High | Mitigate | 8 Moderate |
| R007 | Internet Infrastructure Compromise | CIO | 16 High | 12 High | Mitigate | 8 Moderate |
| R008 | Denial-of-Service Attack | CIO | 9 Moderate | 6 Moderate | Mitigate / Accept | 6 Moderate |
| R009 | Sensitive Information Theft / Extortion | CIO | 16 High | 12 High | Mitigate | 4 Low |
| R010 | Unauthorized / Excessive Access | CIO | 16 High | 12 High | Mitigate | 4 Low |
| R011 | Delayed Termination Access Removal | CFO | 16 High | 8 Moderate | Mitigate | 4 Low |
| R012 | Malicious Insider | CEO | 15 High | 10 High | Mitigate | 5 Moderate |
| R013 | Administrative / Configuration Error | CIO | 16 High | 12 High | Mitigate | 6 Moderate |
| R014 | Lost or Stolen Device | CIO | 16 High | 8 Moderate | Mitigate | 4 Low |
| R015 | Shared Warehouse Account | COO | 12 High | 9 Moderate | Mitigate | 4 Low |
| R016 | Cloud Service Outage | CIO | 15 High | 8 Moderate | Mitigate / Transfer | 6 Moderate |
| R017 | Internet Service Provider Outage | CIO | 16 High | 9 Moderate | Mitigate | 4 Low |
| R018 | Third-Party Technology Failure / Compromise | CIO | 12 High | 8 Moderate | Mitigate / Transfer | 6 Moderate |
| R019 | Infinity Contractor Dependency / Compromise | CIO | 12 High | 8 Moderate | Mitigate | 4 Low |
| R020 | Supplier Disruption | COO | 16 High | 9 Moderate | Mitigate | 6 Moderate |
| R021 | Fire | COO | 15 High | 8 Moderate | Mitigate / Transfer | 5 Moderate |
| R022 | Water Damage | COO | 16 High | 9 Moderate | Mitigate / Transfer | 4 Low |
| R023 | Utility / Power / HVAC Failure | COO | 16 High | 9 Moderate | Mitigate | 4 Low |
| R024 | Unauthorized Physical Access | COO | 16 High | 8 Moderate | Mitigate | 4 Low |
| R025 | Vehicle Loss / Accident | COO | 16 High | 9 Moderate | Mitigate / Transfer | 4 Low |
| R026 | Loss of Key Personnel | CEO | 16 High | 9 Moderate | Mitigate | 4 Low |
| R027 | Backup / Recovery Failure | CIO | 20 Critical | 12 High | Mitigate | 5 Moderate |
| R028 | Data Corruption | CIO | 16 High | 9 Moderate | Mitigate | 4 Low |
| R029 | Vendor Fraud | CFO | 16 High | 6 Moderate | Mitigate | 3 Low |
| R030 | Sales Fraud | Sales Management | 16 High | 6 Moderate | Mitigate | 3 Low |
| R031 | Payroll Fraud | CFO | 12 High | 6 Moderate | Mitigate | 3 Low |
| R032 | Inventory Theft | COO | 12 High | 6 Moderate | Mitigate | 3 Low |
| R033 | Manual Outage Processing Error | COO | 12 High | 9 Moderate | Mitigate | 4 Low |
| R034 | Loss of Corporate Headquarters | CEO | 10 High | 8 Moderate | Mitigate / Transfer | 4 Low |
| R035 | Regional Disaster | CEO | 9 Moderate | 6 Moderate | Mitigate / Transfer | 5 Moderate |

---

# 6. Detailed Risk Register

## R001 - Phishing / Credential Compromise

**Owner:** CIO  
**Inherent Risk:** 20 Critical  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 12 High  
**Treatment:** Mitigate  
**Target Residual Risk:** 6 Moderate  
**Treatment Status:** Planned

### Existing Controls

- Commercial antivirus
- Standard user privileges
- Separate privileged IT credentials
- Basic email protections
- Existing user-security practices

### Planned Treatment

- Improved email filtering and anti-phishing controls
- Known malicious sender blocking
- Suspicious-link protections
- Malicious-attachment protections
- Spoofing protections
- Smart-card MFA where supported
- Security awareness
- Monthly phishing simulations
- Authentication-event monitoring
- Endpoint protection improvements
- Incident-response capability

---

## R002 - Business Email Compromise

**Owner:** CFO  
**Inherent Risk:** 16 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 8 Moderate  
**Treatment:** Mitigate  
**Target Residual Risk:** 4 Low  
**Treatment Status:** Planned

### Existing Controls

- Centralized email
- Authentication
- Existing financial approval practices
- Standard user privileges
- User awareness practices

### Planned Treatment

- Stronger authentication
- Improved email protections
- Security awareness
- Verification of sensitive requests
- Independent verification of suspicious payment changes
- Monitoring
- Incident response

---

## R003 - Ransomware

**Owner:** CIO  
**Inherent Risk:** 25 Critical  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 12 High  
**Treatment:** Mitigate  
**Target Residual Risk:** 6 Moderate  
**Treatment Status:** Planned

### Existing Controls

- Centrally managed antivirus
- Standard user privileges
- Central patch management
- Automated/cloud backups
- Encrypted off-site backup rotation

### Planned Treatment

- Endpoint-security improvements
- Vulnerability management
- Security monitoring
- User awareness
- Incident-response playbook
- Backup resilience improvements
- Restoration testing
- Recovery validation

---

## R004 - Malware

**Owner:** CIO  
**Inherent Risk:** 20 Critical  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 12 High  
**Treatment:** Mitigate  
**Target Residual Risk:** 6 Moderate  
**Treatment Status:** Planned

### Existing Controls

- Centrally managed antivirus
- Standard user privileges
- Central patch management
- Basic security monitoring

### Planned Treatment

- Endpoint-security improvements
- Secure configuration
- Vulnerability management
- Security monitoring
- Awareness
- Malware-response procedure

---

## R005 - Password / Authentication Weakness

**Owner:** CIO  
**Inherent Risk:** 16 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 12 High  
**Treatment:** Mitigate  
**Target Residual Risk:** 4 Low  
**Treatment Status:** Planned

### Existing Controls

- Active Directory
- User authentication
- Standard user privileges
- Separate privileged IT credentials

### Planned Treatment

- Smart-card MFA with PIN or other secret where supported
- Individual accountability
- Restricted standing Domain Administrator membership
- Dedicated administrative workstations
- No external remote privileged administration
- Dormant-account controls
- Annual ordinary-user access reviews
- Quarterly privileged-access reviews
- Contractor-access duration controls
- Emergency-access controls
- Authentication monitoring

---

## R006 - Infinity Application Compromise

**Owner:** CIO  
**Inherent Risk:** 16 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 12 High  
**Treatment:** Mitigate  
**Target Residual Risk:** 8 Moderate  
**Treatment Status:** Planned

### Existing Controls

- Logical web/application/database separation
- Database not directly Internet accessible
- Dunder Mifflin ownership of source code and application assets
- Controlled contractor support
- Change-management practices

### Planned Treatment

- Secure development requirements
- Threat modeling
- Development/test/production separation
- Code review
- Security testing
- Annual Infinity security assessment
- Annual application penetration test
- Remediation and retesting
- Stronger contractor-access controls
- Incident-response and recovery improvements

---

## R007 - Internet Infrastructure Compromise

**Owner:** CIO  
**Inherent Risk:** 16 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 12 High  
**Treatment:** Mitigate  
**Target Residual Risk:** 8 Moderate  
**Treatment Status:** Planned

### Existing Controls

- Firewalls/routers
- Unsolicited inbound traffic restrictions
- No intentionally exposed internal administrative services
- Protected remote connectivity
- Limited wireless exposure

### Planned Treatment

- Network-security standard
- Configuration baselines
- Stronger change controls
- Privileged-access restrictions
- Network discovery
- Rogue wireless detection
- Configuration backups
- Appropriate spare equipment

---

## R008 - Denial-of-Service Attack

**Owner:** CIO  
**Inherent Risk:** 9 Moderate  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 6 Moderate  
**Treatment:** Mitigate / Accept  
**Target Residual Risk:** 6 Moderate  
**Treatment Status:** Planned

### Existing Controls

- Commercial Internet providers
- Firewall capabilities
- Multiple customer ordering channels

### Planned Treatment

- Provider escalation procedures
- Incident response
- Business continuity procedures
- Cellular fallback where applicable
- Manual continuity
- Periodic resilience evaluation

### Risk Note

The target remains Moderate because further reduction is not expected to justify disproportionate cost or complexity.

---

## R009 - Sensitive Information Theft / Extortion

**Owner:** CIO  
**Inherent Risk:** 16 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 12 High  
**Treatment:** Mitigate  
**Target Residual Risk:** 4 Low  
**Treatment Status:** Planned

### Existing Controls

- Access controls
- Laptop full-disk encryption
- Standard user privileges
- Physical security
- Confidentiality requirements
- Encrypted backups

### Planned Treatment

- Formal classification and handling controls
- Stronger access management
- Secure disposal
- Security awareness
- Incident response
- Backup protection
- Monitoring

---

## R010 - Unauthorized / Excessive Access

**Owner:** CIO  
**Inherent Risk:** 16 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 12 High  
**Treatment:** Mitigate  
**Target Residual Risk:** 4 Low  
**Treatment Status:** Planned

### Existing Controls

- Active Directory
- Business-based access
- Standard user privileges
- Separate privileged IT credentials

### Planned Treatment

- Formal least privilege
- Information-owner approval
- Transfer revocation and reauthorization
- Prompt termination
- Annual ordinary-user reviews
- Quarterly privileged reviews
- Restricted Domain Administrator membership
- Dormant-account controls
- Contractor-duration controls
- Emergency-access controls
- Individual accountability for significant WMS transactions

---

## R011 - Delayed Termination Access Removal

**Owner:** CFO  
**Inherent Risk:** 16 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 8 Moderate  
**Treatment:** Mitigate  
**Target Residual Risk:** 4 Low  
**Treatment Status:** Planned

### Existing Controls

- HR employment records
- Centralized identity administration
- Existing termination practices

### Planned Treatment

- HR authoritative notification
- Prompt account disablement
- Equipment recovery
- Key/card recovery
- Credential removal
- Smart-card recovery where applicable
- Termination checklist
- Exception testing

---

## R012 - Malicious Insider

**Owner:** CEO  
**Inherent Risk:** 15 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 10 High  
**Treatment:** Mitigate  
**Target Residual Risk:** 5 Moderate  
**Treatment Status:** Planned

### Existing Controls

- Business-based access
- Standard user privileges
- Physical access controls
- Financial approval practices
- Management oversight

### Planned Treatment

- Least privilege
- Separation of duties
- Individual accountability
- Access reviews
- Personnel-security controls
- Classification
- Financial controls
- Security awareness
- Incident response

### Risk Note

Controls must remain proportional and must not create indiscriminate employee surveillance.

---

## R013 - Administrative / Configuration Error

**Owner:** CIO  
**Inherent Risk:** 16 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 12 High  
**Treatment:** Mitigate  
**Target Residual Risk:** 6 Moderate  
**Treatment Status:** Planned

### Existing Controls

- Central patch management
- Basic change management
- Separate privileged credentials
- Technical administration by designated IT personnel

### Planned Treatment

- Configuration baselines
- Formal change controls
- Review and approval
- Testing
- Staged implementation
- Rollback
- Post-change verification
- Configuration backups
- Documentation
- Lessons learned

---

## R014 - Lost or Stolen Device

**Owner:** CIO  
**Inherent Risk:** 16 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 8 Moderate  
**Treatment:** Mitigate  
**Target Residual Risk:** 4 Low  
**Treatment Status:** Planned

### Existing Controls

- Laptop full-disk encryption
- User authentication
- Standard user privileges
- Automatic screen locking
- Central management
- Mobile-device management where supported

### Planned Treatment

- Stronger device inventory
- Remote lock/wipe where supported
- Formal loss reporting
- Credential response
- Incident-response integration

---

## R015 - Shared Warehouse Account

**Owner:** COO  
**Inherent Risk:** 12 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 9 Moderate  
**Treatment:** Mitigate  
**Target Residual Risk:** 4 Low  
**Treatment Status:** Planned

### Existing Controls

- Controlled warehouse environment
- Limited workstation permissions
- WMS records
- Physical access controls

### Planned Treatment

- Shared Windows access only where operationally justified
- Minimal workstation permissions
- Individual authentication or attribution for significant WMS transactions
- Access reviews
- Relevant transaction logging

---

## R016 - Cloud Service Outage

**Owner:** CIO  
**Inherent Risk:** 15 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 8 Moderate  
**Treatment:** Mitigate / Transfer  
**Target Residual Risk:** 6 Moderate  
**Treatment Status:** Planned

### Existing Controls

- Cloud-hosted architecture
- Automated/cloud backups
- Encrypted off-site backup media
- Existing recovery documentation
- Cloud Exit & Emergency Migration Plan

### Planned Treatment

- Formal BC/DR integration
- Provider escalation
- Provider resilience review
- Contract review
- Recovery documentation independent of production
- Manual continuity
- Concentration-risk evaluation
- Recovery testing

---

## R017 - Internet Service Provider Outage

**Owner:** CIO  
**Inherent Risk:** 16 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 9 Moderate  
**Treatment:** Mitigate  
**Target Residual Risk:** 4 Low  
**Treatment Status:** Planned

### Existing Controls

- Commercial ISP connectivity
- Company mobile devices
- Cloud-hosted systems
- Some mobile-capable personnel

### Planned Treatment

- Company-issued cellular secondary connectivity where applicable
- Provider escalation
- Business continuity procedures
- Manual processing where cellular access cannot support the business function

---

## R018 - Third-Party Technology Failure / Compromise

**Owner:** CIO  
**Inherent Risk:** 12 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 8 Moderate  
**Treatment:** Mitigate / Transfer  
**Target Residual Risk:** 6 Moderate  
**Treatment Status:** Planned

### Existing Controls

- Basic due diligence
- Contracts
- Confidentiality requirements for sensitive access
- Multiple service relationships

### Planned Treatment

- Critical/Important/Routine classification
- Critical annual review
- Important biennial review
- Security requirements
- Incident-notification requirements
- Recovery requirements
- Audit/assessment rights
- Third-party inventory
- Access restrictions
- Exit and continuity planning

---

## R019 - Infinity Contractor Dependency / Compromise

**Owner:** CIO  
**Inherent Risk:** 12 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 8 Moderate  
**Treatment:** Mitigate  
**Target Residual Risk:** 4 Low  
**Treatment Status:** Planned

### Existing Controls

- Dunder Mifflin ownership of source code
- Dunder Mifflin ownership of repository, data, documentation, and intellectual property
- Confidentiality obligations
- Controlled headquarters workspace
- No general contractor privileged VPN

### Planned Treatment

- Sponsor-based access
- Time-limited access
- Strong authentication where supported
- Least privilege
- Advance identification of expected personnel
- Secure change requirements
- Annual Infinity security assessment
- Annual application penetration testing
- Remediation/retesting
- Annual transferability review

---

## R020 - Supplier Disruption

**Owner:** COO  
**Inherent Risk:** 16 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 9 Moderate  
**Treatment:** Mitigate  
**Target Residual Risk:** 6 Moderate  
**Treatment Status:** Planned

### Existing Controls

- Multiple suppliers
- Local inventory
- Procurement processes
- Supplier relationships

### Planned Treatment

- Alternate suppliers where practical
- Supplier monitoring
- Inventory planning
- Operational coordination
- Customer communication
- Periodic sourcing review

---

## R021 - Fire

**Owner:** COO  
**Inherent Risk:** 15 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 8 Moderate  
**Treatment:** Mitigate / Transfer  
**Target Residual Risk:** 5 Moderate  
**Treatment Status:** Planned

### Existing Controls

- Building fire-protection systems
- Leased facilities
- Off-site backups
- Geographic distribution
- Insurance

### Planned Treatment

- Evacuation procedures
- Landlord coordination
- Inspection
- BC/DR integration
- Independent recovery documentation
- Recovery testing

### Risk Note

Human life and safety take priority over protection of company assets.

---

## R022 - Water Damage

**Owner:** COO  
**Inherent Risk:** 16 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 9 Moderate  
**Treatment:** Mitigate / Transfer  
**Target Residual Risk:** 4 Low  
**Treatment Status:** Planned

### Existing Controls

- Geographic distribution
- Off-site backups
- Insurance
- Leased-building maintenance

### Planned Treatment

- Avoid known water hazards
- Elevate equipment where appropriate
- Leak inspection
- Landlord coordination
- Paper-record protection
- BC/DR integration

---

## R023 - Utility / Power / HVAC Failure

**Owner:** COO  
**Inherent Risk:** 16 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 9 Moderate  
**Treatment:** Mitigate  
**Target Residual Risk:** 4 Low  
**Treatment Status:** Planned

### Existing Controls

- UPS protection for critical network equipment
- UPS protection for selected management/Sales workstations
- Approximately 30 minutes of UPS support
- Cloud-hosted centralized systems
- Company laptops and mobile devices

### Planned Treatment

- Orderly shutdown procedures
- Landlord escalation
- Inspection and maintenance
- Continuity procedures
- Manual warehouse processing
- Generator evaluation only if later justified by business need

---

## R024 - Unauthorized Physical Access

**Owner:** COO  
**Inherent Risk:** 16 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 8 Moderate  
**Treatment:** Mitigate  
**Target Residual Risk:** 4 Low  
**Treatment Status:** Planned

### Existing Controls

- Receptionist-controlled front entry
- Controlled employee rear entry
- Restricted rooms
- Keys/access credentials
- Warehouse security cages

### Planned Treatment

- Formal security zones
- Visitor logging
- Escort requirements
- Vendor-access requirements
- Restricted-area authorization
- Annual physical-access review
- Termination credential removal

---

## R025 - Vehicle Loss / Accident

**Owner:** COO  
**Inherent Risk:** 16 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 9 Moderate  
**Treatment:** Mitigate / Transfer  
**Target Residual Risk:** 4 Low  
**Treatment Status:** Planned

### Existing Controls

- Authorized drivers
- Vehicle registration
- Insurance
- Operational management

### Planned Treatment

- Driver qualification
- Inspection
- Maintenance
- Incident reporting
- Delivery continuity
- Information/equipment protection
- Restrictions on unnecessary sensitive or valuable items left unattended

---

## R026 - Loss of Key Personnel

**Owner:** CEO  
**Inherent Risk:** 16 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 9 Moderate  
**Treatment:** Mitigate  
**Target Residual Risk:** 4 Low  
**Treatment Status:** Planned

### Existing Controls

- Multiple management roles
- Six-person IT/security team
- Existing recovery documentation
- Company ownership of Infinity assets

### Planned Treatment

- Identify key-person dependencies
- Improve documentation
- Cross-train personnel
- Designate alternates
- Maintain delegated authority
- Maintain company-controlled credentials/configuration/source/recovery information
- Emergency-access capability
- Periodic dependency review

---

## R027 - Backup / Recovery Failure

**Owner:** CIO  
**Inherent Risk:** 20 Critical  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 12 High  
**Treatment:** Mitigate  
**Target Residual Risk:** 5 Moderate  
**Treatment Status:** Planned

### Existing Controls

- Automated backups
- Cloud-based backup capability
- 21 encrypted external backup drives
- Off-site rotation
- Two recent weekly generations per facility normally held off-site
- Existing recovery documentation

### Planned Treatment

- Validate backup coverage against assets, classification, and BIA
- Monitor backup jobs
- Quarterly representative restoration tests
- Annual meaningful recovery testing for Critical functions
- Validate RTO/RPO achievement
- Improve recovery documentation
- Protect backup administration
- Evaluate resilience against production compromise

---

## R028 - Data Corruption

**Owner:** CIO  
**Inherent Risk:** 16 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 9 Moderate  
**Treatment:** Mitigate  
**Target Residual Risk:** 4 Low  
**Treatment Status:** Planned

### Existing Controls

- Access controls
- Backups
- Application controls
- Basic change management

### Planned Treatment

- Stronger change control
- Validated backups
- Integrity controls
- Restricted administrative/database access
- Logging
- Integrity investigation
- Restore validation
- Business reconciliation

---

## R029 - Vendor Fraud

**Owner:** CFO  
**Inherent Risk:** 16 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 6 Moderate  
**Treatment:** Mitigate  
**Target Residual Risk:** 3 Low  
**Treatment Status:** Planned

### Existing Controls

- Vendor records
- Financial approval processes
- Accounting reconciliation
- Management oversight

### Planned Treatment

- Separation of vendor setup, purchasing, invoice approval, and payment where practical
- Authorization of new vendors
- Authorization of payment changes
- Independent verification of suspicious/significant banking changes
- Restricted vendor-master access
- Restricted payment access
- Due diligence
- Awareness and investigation

---

## R030 - Sales Fraud

**Owner:** Sales Management  
**Inherent Risk:** 16 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 6 Moderate  
**Treatment:** Mitigate  
**Target Residual Risk:** 3 Low  
**Treatment Status:** Planned

### Existing Controls

- Sales records
- Accounting records
- Order/fulfillment records
- Management approval
- Reconciliation

### Planned Treatment

- Individual accountability
- Role permissions
- Approval of significant pricing/discount/credit/refund activity
- Transaction attribution
- Reconciliation
- Anomaly investigation
- Practical separation of duties

---

## R031 - Payroll Fraud

**Owner:** CFO  
**Inherent Risk:** 12 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 6 Moderate  
**Treatment:** Mitigate  
**Target Residual Risk:** 3 Low  
**Treatment Status:** Planned

### Existing Controls

- HR employee records
- Payroll records
- Financial approval
- Management oversight

### Planned Treatment

- Practical separation of payroll duties
- HR as authoritative employee-status source
- Restricted payroll access
- Authorization of compensation/banking/deduction changes
- Independent verification of suspicious payment changes
- Payroll reconciliation
- Review for unusual adjustments, duplicates, or unexpected employees
- Individual accountability

---

## R032 - Inventory Theft

**Owner:** COO  
**Inherent Risk:** 12 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 6 Moderate  
**Treatment:** Mitigate  
**Target Residual Risk:** 3 Low  
**Treatment Status:** Planned

### Existing Controls

- Controlled warehouse access
- Locked security cages
- WMS inventory records
- Receiving records
- Shipping records
- Inventory counts

### Planned Treatment

- Restricted cage access
- Individual accountability for significant WMS transactions
- Reconciliation
- Discrepancy investigation
- Stronger visitor/vendor/delivery controls
- Personnel and fraud controls

---

## R033 - Manual Outage Processing Error

**Owner:** COO  
**Inherent Risk:** 12 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 9 Moderate  
**Treatment:** Mitigate  
**Target Residual Risk:** 4 Low  
**Treatment Status:** Planned

### Existing Controls

- Experienced business personnel
- Existing paper/manual capability
- Business records
- Management oversight

### Planned Treatment

- Documented manual procedures
- Standardized records
- Customer/order/employee/timestamp attribution
- Review before entry
- Reconciliation
- Verification
- Duplicate/missing transaction investigation
- Training
- Exercises

### Manual Processing Lifecycle

**Collect → Review → Enter → Reconcile → Verify**

---

## R034 - Loss of Corporate Headquarters

**Owner:** CEO  
**Inherent Risk:** 10 High  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 8 Moderate  
**Treatment:** Mitigate / Transfer  
**Target Residual Risk:** 4 Low  
**Treatment Status:** Planned

### Existing Controls

- Cloud-hosted systems
- Geographic distribution
- Off-site encrypted backups
- Company laptops
- Company mobile devices
- Insurance

### Planned Treatment

- Formal BCP
- Independent recovery documentation
- Printed recovery documentation
- Alternate communications
- Relocation/distribution of headquarters functions
- Alternate personnel
- Delegated authority
- Recovery exercises

---

## R035 - Regional Disaster

**Owner:** CEO  
**Inherent Risk:** 9 Moderate  
**Control Effectiveness:** Partially Effective  
**Current Residual Risk:** 6 Moderate  
**Treatment:** Mitigate / Transfer  
**Target Residual Risk:** 5 Moderate  
**Treatment Status:** Planned

### Existing Controls

- Seven geographically distributed facilities
- Cloud-hosted systems
- Off-site encrypted backups
- Company mobile devices
- Multiple suppliers
- Insurance

### Planned Treatment

- Formal BC/DR
- Management succession
- Alternate communications
- Support from unaffected branches
- Manual continuity
- Supplier alternatives
- Transportation alternatives
- Situation monitoring
- Personnel safety/accountability

---

# 7. Current Residual Risk Distribution

| Rating | Number of Risks |
|---|---:|
| Critical | 0 |
| High | 11 |
| Moderate | 24 |
| Low | 0 |
| **Total** | **35** |

The absence of a current Critical risk does not mean Critical inherent risks are unimportant.

Several Critical inherent risks have been reduced to High through existing controls.

---

# 8. Target Residual Risk Distribution

| Rating | Number of Risks |
|---|---:|
| Critical | 0 |
| High | 0 |
| Moderate | 13 |
| Low | 22 |
| **Total** | **35** |

Target residual ratings represent expected outcomes following successful implementation and validation.

They do not represent current risk.

---

# 9. Highest Current Residual Risks

The following risks currently remain High:

| Risk | Current Residual |
|---|---:|
| R001 Phishing / Credential Compromise | 12 High |
| R003 Ransomware | 12 High |
| R004 Malware | 12 High |
| R005 Password / Authentication Weakness | 12 High |
| R006 Infinity Application Compromise | 12 High |
| R007 Internet Infrastructure Compromise | 12 High |
| R009 Sensitive Information Theft / Extortion | 12 High |
| R010 Unauthorized / Excessive Access | 12 High |
| R012 Malicious Insider | 10 High |
| R013 Administrative / Configuration Error | 12 High |
| R027 Backup / Recovery Failure | 12 High |

These risks receive heightened management attention and treatment priority.

---

# 10. Risk Interdependencies

Several risks share common treatment dependencies.

## Identity and Access Management

Improvements may materially affect:

- R001
- R002
- R005
- R009
- R010
- R011
- R012
- R015
- R019

## Vulnerability and Configuration Management

Improvements may materially affect:

- R003
- R004
- R006
- R007
- R013
- R028

## Backup and Recovery

Improvements may materially affect:

- R003
- R016
- R021
- R022
- R027
- R028
- R034
- R035

## Third-Party Risk Management

Improvements may materially affect:

- R016
- R018
- R019
- R020

## Physical and Personnel Security

Improvements may materially affect:

- R012
- R021
- R022
- R024
- R025
- R026
- R032
- R034
- R035

Common controls should be implemented and assessed as shared enterprise capabilities where practical rather than duplicated independently for every risk.

---

# 11. Risk Review Requirements

The register must be reviewed:

- At least quarterly
- Following significant security incidents
- Following significant assessment findings
- Following material business change
- Following material technology change
- Following major third-party change
- Following significant control failure
- Following validated completion of material treatment
- When assumptions affecting risk scoring are found to be inaccurate

---

# 12. Risk Reassessment

Risk reassessment must consider:

1. Whether treatment was actually implemented.
2. Whether the control operates as intended.
3. Whether appropriate evidence exists.
4. Whether validation supports effectiveness.
5. Whether likelihood changed.
6. Whether impact changed.
7. Whether new dependencies were introduced.
8. Whether the target remains reasonable.

The target residual score must not automatically become the new current residual score.

---

# 13. Historical Records

Previous risk ratings must be preserved when risk is reassessed.

Risk history should show:

- Previous assessment date
- Previous inherent risk where applicable
- Previous current residual risk
- Treatment performed
- Validation results
- Revised residual risk
- Rationale for material changes

Historical records provide evidence of risk movement and program effectiveness.

---

# 14. Risk Acceptance

Risk acceptance follows [[POL-005 Risk Management Policy]].

General approval requirements are:

| Residual Rating | Approval |
|---|---|
| Low | Risk Owner |
| Moderate | Risk Owner + Appropriate Executive |
| High | CEO following ISRC review |
| Critical | CEO following ISRC review and exceptional justification |

High-risk acceptance must be reassessed within 90 days.

Critical-risk acceptance must be reassessed within 30 days.

---

# 15. Relationship to Treatment

Detailed risk-treatment actions are maintained in [[RTP-001 Enterprise Risk Treatment Plan]].

This register records the risk state.

The treatment plan records the actions intended to change that state.

The relationship is:

**Risk Register → Treatment Plan → Implementation → Evidence → Validation → Risk Reassessment → Updated Risk Register**

---

# 16. Relationship to Assurance

Risk information helps prioritize security assurance.

Assessment priority should consider both inherent and residual risk.

A control that reduces a Critical inherent risk to Low residual risk may warrant substantial assurance precisely because the organization depends heavily on that control.

Low residual risk does not automatically mean low assessment priority.

See:

- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[PLN-005 Annual Assurance Plan]]
- [[TMP-001 Assessment Work Plan Template]]

---

# 17. Related Artifacts

- [[PRO-001 Enterprise Information Security & Risk Management Program]]
- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[REG-001 Enterprise Asset Register]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[POL-005 Risk Management Policy]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[PLN-005 Annual Assurance Plan]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[REG-007 Cross-Reference Matrix]]

---

# 18. Revision History

| Version | Date     | Description                                                     | Approval |
| ------- | -------- | --------------------------------------------------------------- | -------- |
| 1.0     | May 2013 | Initial Enterprise Risk Register containing 35 enterprise risks | CEO      |