# TMP-003 Recovery Test Template

## Document Control

| Field | Value |
|---|---|
| Document ID | TMP-003 |
| Title | Recovery Test Template |
| Version | 1.0 |
| Classification | Internal |
| Status | Approved |
| Owner | IT & Information Security Manager |
| Approved By | CIO |
| Effective Date | May 2013 |
| Review Frequency | Annual and Following Material Recovery Testing Process Change |

---

# 1. Purpose

This template provides a standardized method for planning, performing, documenting, and evaluating backup restoration and technology recovery tests.

The template supports validation of recovery capability against requirements established by:

- [[RPT-002 Business Impact Analysis]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PROC-012 Backup & Recovery Procedure]]

---

# 2. Use of This Template

A copy of this template should be completed for each formal recovery test.

The completed test record becomes evidence of the recovery activity performed.

---

# 3. Evidence Principle

The completed record must describe what actually occurred.

Personnel must not:

- Backdate testing.
- Invent test activity.
- Record unperformed steps as complete.
- Change measured recovery time.
- Change measured data loss.
- Hide failed recovery attempts.
- Convert partial success into full success.
- Record unperformed validation as complete.

---

# 4. Test Identification

| Field | Test Information |
|---|---|
| Test ID | `[Enter Test ID]` |
| Test Name | `[Enter Test Name]` |
| Test Date | `[Enter Date]` |
| Test Location | `[Enter Location]` |
| Test Coordinator | `[Enter Name / Role]` |
| System / Service | `[Enter System or Service]` |
| Business Process | `[Enter Business Process]` |
| Business Owner | `[Enter Owner]` |
| System Owner | `[Enter Owner]` |
| Classification | `[Enter Classification]` |
| Test Type | `[Enter Test Type]` |

---

# 5. Test Type

Select the applicable test type.

- [ ] Backup restore test
- [ ] Quarterly representative restore test
- [ ] Annual Critical-system recovery test
- [ ] Application recovery test
- [ ] Server recovery test
- [ ] Active Directory / Authentication recovery test
- [ ] Cloud recovery test
- [ ] Infinity recovery test
- [ ] Network recovery test
- [ ] Data recovery test
- [ ] Business Continuity / Disaster Recovery exercise
- [ ] Cloud exit / migration exercise
- [ ] Other: `[Describe]`

---

# 6. Test Objective

**Objective:**

`[Describe what the test is intended to demonstrate.]`

Examples may include:

- Demonstrate that selected backup data can be restored.
- Determine whether a Critical system can meet its RTO.
- Determine whether restored data meets its RPO.
- Validate recovery documentation.
- Validate required technical dependencies.
- Validate that a qualified alternate administrator can perform recovery.
- Validate recovery after simulated system loss.

---

# 7. Test Scenario

**Scenario:**

`[Describe the outage, failure, loss, or recovery condition being tested.]`

---

# 8. Scenario Assumptions

Document assumptions used during the test.

| # | Assumption |
|---:|---|
| 1 | `[Enter assumption]` |
| 2 | `[Enter assumption]` |
| 3 | `[Enter assumption]` |
| 4 | `[Enter assumption]` |

---

# 9. Test Scope

**In Scope:**

- `[System / component / data]`
- `[System / component / data]`
- `[System / component / data]`

**Out of Scope:**

- `[System / component / data]`
- `[System / component / data]`

---

# 10. Scope Limitations

Document any condition that makes the test less representative of an actual recovery event.

Examples include:

- Reduced dataset
- Simulated dependency
- Nonproduction infrastructure
- Provider not participating
- Limited user validation
- Simplified network environment

**Limitations:**

`[Enter limitations or "None identified."]`

---

# 11. Business Impact Analysis Requirement

Record the applicable requirement from [[RPT-002 Business Impact Analysis]].

| Requirement | Value |
|---|---|
| Business Process / Capability | `[Enter process or capability]` |
| Criticality | `[Critical / High / Moderate / Low]` |
| Maximum Tolerable Downtime (MTD) | `[Enter MTD]` |
| Recovery Time Objective (RTO) | `[Enter RTO]` |
| Recovery Point Objective (RPO) | `[Enter RPO or N/A]` |

---

# 12. BIA Requirement Verification

Before the test begins, verify that the RTO and RPO above match the current approved Business Impact Analysis.

- [ ] BIA requirement verified
- [ ] BIA discrepancy identified

**Comments:**

`[Enter comments]`

---

# 13. Recovery Success Criteria

Define success before performing the test.

| # | Success Criterion | Required? |
|---:|---|---|
| 1 | `[Enter criterion]` | `[Yes / No]` |
| 2 | `[Enter criterion]` | `[Yes / No]` |
| 3 | `[Enter criterion]` | `[Yes / No]` |
| 4 | `[Enter criterion]` | `[Yes / No]` |
| 5 | `[Enter criterion]` | `[Yes / No]` |

---

# 14. Required Recovery Source

| Field | Value |
|---|---|
| Backup / Recovery Source | `[Enter source]` |
| Backup Date | `[Enter date]` |
| Backup Time | `[Enter time]` |
| Media / Backup Identifier | `[Enter identifier]` |
| Storage Location | `[Enter location]` |
| Encryption Status | `[Enter status]` |
| Last Known Verification | `[Enter date / status]` |

---

# 15. Recovery Source Selection Rationale

**Why was this recovery source selected?**

`[Enter rationale.]`

---

# 16. Recovery Source Trust

Before use, determine whether there is reason to suspect that the recovery source contains:

- [ ] Malware
- [ ] Unauthorized changes
- [ ] Data corruption
- [ ] Compromised configuration
- [ ] Unknown integrity condition
- [ ] None identified

**Comments:**

`[Enter comments]`

---

# 17. Required Dependencies

| Dependency | Required? | Available? | Notes |
|---|---|---|---|
| Authentication | `[Yes / No]` | `[Yes / No]` | `[Notes]` |
| DNS | `[Yes / No]` | `[Yes / No]` | `[Notes]` |
| Network | `[Yes / No]` | `[Yes / No]` | `[Notes]` |
| Database | `[Yes / No]` | `[Yes / No]` | `[Notes]` |
| Application Service | `[Yes / No]` | `[Yes / No]` | `[Notes]` |
| File Service | `[Yes / No]` | `[Yes / No]` | `[Notes]` |
| Third-Party Service | `[Yes / No]` | `[Yes / No]` | `[Notes]` |
| Other | `[Enter]` | `[Yes / No]` | `[Notes]` |

---

# 18. Dependency Exceptions

**Unknown, missing, or unavailable dependencies:**

`[Enter details or "None identified."]`

---

# 19. Required Personnel

| Role | Participant | Available? |
|---|---|---|
| Test Coordinator | `[Enter]` | `[Yes / No]` |
| System Administrator | `[Enter]` | `[Yes / No]` |
| Network / Security Administrator | `[Enter]` | `[Yes / No]` |
| Information Security Analyst | `[Enter]` | `[Yes / No]` |
| Business Representative | `[Enter]` | `[Yes / No]` |
| Application Owner | `[Enter]` | `[Yes / No]` |
| Third Party | `[Enter if applicable]` | `[Yes / No / N/A]` |

---

# 20. Recovery Documentation

| Field | Value |
|---|---|
| Recovery Procedure | `[Enter document / section]` |
| Procedure Version | `[Enter version]` |
| Documentation Available? | `[Yes / No]` |
| Documentation Independently Available? | `[Yes / No]` |
| Documentation Complete? | `[Yes / No / To Be Determined]` |

---

# 21. Documentation Test

If part of the test objective, identify whether a qualified person unfamiliar with the specific environment can perform recovery using the available documentation.

- [ ] Yes
- [ ] No
- [ ] Partially
- [ ] Not Tested

**Observed undocumented knowledge or dependency:**

`[Enter details]`

---

# 22. Required Credentials

Identify required credential categories without recording passwords or other authentication secrets.

| Credential / Access Type | Available? | Authorized? | Notes |
|---|---|---|---|
| Standard Access | `[Yes / No / N/A]` | `[Yes / No]` | `[Notes]` |
| Privileged Access | `[Yes / No / N/A]` | `[Yes / No]` | `[Notes]` |
| Backup Administration | `[Yes / No / N/A]` | `[Yes / No]` | `[Notes]` |
| Emergency Access | `[Yes / No / N/A]` | `[Yes / No]` | `[Notes]` |
| Third-Party Access | `[Yes / No / N/A]` | `[Yes / No]` | `[Notes]` |

---

# 23. Credential Handling

Do not record:

- Passwords
- Personal Identification Numbers (PINs)
- Private keys
- Recovery secrets
- Other authentication secrets

in this test record.

---

# 24. Test Authorization

| Authorization | Name / Role | Date |
|---|---|---|
| Technical Authorization | `[Enter]` | `[Enter]` |
| Business Authorization | `[Enter if required]` | `[Enter]` |
| Security Authorization | `[Enter if required]` | `[Enter]` |

---

# 25. Pre-Test Safety Review

Confirm that the test will not unnecessarily:

- [ ] Interrupt production
- [ ] Damage production data
- [ ] Expose sensitive information
- [ ] Create unauthorized privileged access
- [ ] Disable required security controls
- [ ] Affect customers
- [ ] Affect warehouse operations
- [ ] Affect financial processing

**Required precautions:**

`[Enter precautions]`

---

# 26. Rollback Plan

**Rollback approach:**

`[Describe how the test environment or affected system will be returned to its prior state if required.]`

---

# 27. Recovery Timing Definition

The test must define when the recovery clock starts and stops.

**Recovery Start Condition:**

`[Define the event that starts RTO measurement.]`

**Recovery Completion Condition:**

`[Define the event that stops RTO measurement.]`

---

# 28. Recovery Timing Record

| Event | Date | Time |
|---|---|---|
| Defined Recovery Start | `[Date]` | `[Time]` |
| Recovery Activity Began | `[Date]` | `[Time]` |
| Technical Restoration Completed | `[Date]` | `[Time]` |
| Security Validation Completed | `[Date]` | `[Time]` |
| Business Validation Completed | `[Date]` | `[Time]` |
| Defined Recovery Completion | `[Date]` | `[Time]` |

---

# 29. Actual Recovery Time

**Approved RTO:** `[Enter RTO]`

**Actual Recovery Time:** `[Enter elapsed time]`

**RTO Result:**

- [ ] Pass
- [ ] Fail
- [ ] Not Applicable
- [ ] Unable to Determine

---

# 30. RTO Conclusion

**RTO analysis:**

`[Explain the measured result and any relevant limitation.]`

---

# 31. Recovery Point Reference

Define the reference point used to calculate data loss.

**Reference Date / Time:**

`[Enter date and time]`

---

# 32. Actual Recovery Point

**Recovered data date / time:**

`[Enter date and time]`

---

# 33. Actual Data Loss

**Approved RPO:** `[Enter RPO]`

**Actual Data Loss:** `[Enter elapsed time]`

**RPO Result:**

- [ ] Pass
- [ ] Fail
- [ ] Not Applicable
- [ ] Unable to Determine

---

# 34. RPO Conclusion

**RPO analysis:**

`[Explain the measured result and any relevant limitation.]`

---

# 35. RTO and RPO Summary

| Requirement | Target | Actual | Result |
|---|---:|---:|---|
| RTO | `[Target]` | `[Actual]` | `[Pass / Fail / N/A]` |
| RPO | `[Target]` | `[Actual]` | `[Pass / Fail / N/A]` |

---

# 36. Recovery Activity Log

| # | Date / Time | Activity | Performed By | Result / Observation |
|---:|---|---|---|---|
| 1 | `[Enter]` | `[Enter activity]` | `[Enter]` | `[Enter]` |
| 2 | `[Enter]` | `[Enter activity]` | `[Enter]` | `[Enter]` |
| 3 | `[Enter]` | `[Enter activity]` | `[Enter]` | `[Enter]` |
| 4 | `[Enter]` | `[Enter activity]` | `[Enter]` | `[Enter]` |
| 5 | `[Enter]` | `[Enter activity]` | `[Enter]` | `[Enter]` |

Add rows as required.

---

# 37. Recovery Errors

| # | Error / Failure | Time | Impact | Action Taken |
|---:|---|---|---|---|
| 1 | `[Enter]` | `[Enter]` | `[Enter]` | `[Enter]` |
| 2 | `[Enter]` | `[Enter]` | `[Enter]` | `[Enter]` |

---

# 38. Failed Recovery Attempts

Every failed recovery attempt must remain part of the test record.

A later successful attempt does not erase an earlier failure.

**Failed attempts:**

`[Describe failed attempts or "None."]`

---

# 39. Alternate Recovery Source

If another backup or recovery source was required:

| Field | Value |
|---|---|
| Alternate Source Used? | `[Yes / No]` |
| Source | `[Enter]` |
| Reason | `[Enter]` |
| Recovery Point | `[Enter]` |
| RPO Impact | `[Enter]` |

---

# 40. Technical Validation

Complete applicable validation.

| Validation Item | Result | Evidence / Notes |
|---|---|---|
| System starts correctly | `[Pass / Fail / N/A]` | `[Enter]` |
| Required services operate | `[Pass / Fail / N/A]` | `[Enter]` |
| Network connectivity operates | `[Pass / Fail / N/A]` | `[Enter]` |
| Required dependencies operate | `[Pass / Fail / N/A]` | `[Enter]` |
| Application operates | `[Pass / Fail / N/A]` | `[Enter]` |
| Database connectivity operates | `[Pass / Fail / N/A]` | `[Enter]` |
| Required integrations operate | `[Pass / Fail / N/A]` | `[Enter]` |
| Expected data is present | `[Pass / Fail / N/A]` | `[Enter]` |
| Logging operates | `[Pass / Fail / N/A]` | `[Enter]` |

---

# 41. Technical Validation Conclusion

- [ ] Passed
- [ ] Failed
- [ ] Partially Passed
- [ ] Not Applicable

**Comments:**

`[Enter conclusion]`

---

# 42. Security Validation

| Validation Item | Result | Evidence / Notes |
|---|---|---|
| Authentication operates | `[Pass / Fail / N/A]` | `[Enter]` |
| Authorization is appropriate | `[Pass / Fail / N/A]` | `[Enter]` |
| Privileged access is restricted | `[Pass / Fail / N/A]` | `[Enter]` |
| Required encryption operates | `[Pass / Fail / N/A]` | `[Enter]` |
| Managed antivirus operates | `[Pass / Fail / N/A]` | `[Enter]` |
| Required network restrictions exist | `[Pass / Fail / N/A]` | `[Enter]` |
| Administrative interfaces are appropriately restricted | `[Pass / Fail / N/A]` | `[Enter]` |
| Known compromise has been addressed | `[Pass / Fail / N/A]` | `[Enter]` |
| Security logging operates | `[Pass / Fail / N/A]` | `[Enter]` |

---

# 43. Security Validation Conclusion

- [ ] Passed
- [ ] Failed
- [ ] Partially Passed
- [ ] Not Applicable

**Comments:**

`[Enter conclusion]`

---

# 44. Data Validation

| Validation Item | Result | Evidence / Notes |
|---|---|---|
| Required data is present | `[Pass / Fail / N/A]` | `[Enter]` |
| Data is readable | `[Pass / Fail / N/A]` | `[Enter]` |
| Data appears complete | `[Pass / Fail / N/A]` | `[Enter]` |
| Required permissions are present | `[Pass / Fail / N/A]` | `[Enter]` |
| Recovery point is established | `[Pass / Fail / N/A]` | `[Enter]` |
| Material corruption identified | `[Yes / No / N/A]` | `[Enter]` |

---

# 45. Data Validation Conclusion

- [ ] Passed
- [ ] Failed
- [ ] Partially Passed
- [ ] Not Applicable

**Comments:**

`[Enter conclusion]`

---

# 46. Business Validation

| Validation Item | Result | Evidence / Notes |
|---|---|---|
| Required business function operates | `[Pass / Fail / N/A]` | `[Enter]` |
| Business user can access required information | `[Pass / Fail / N/A]` | `[Enter]` |
| Required transaction can be completed | `[Pass / Fail / N/A]` | `[Enter]` |
| Recovered information supports business need | `[Pass / Fail / N/A]` | `[Enter]` |
| Manual continuity records can be reconciled | `[Pass / Fail / N/A]` | `[Enter]` |

---

# 47. Business Validation Conclusion

- [ ] Passed
- [ ] Failed
- [ ] Partially Passed
- [ ] Not Applicable

**Business Validator:**

`[Enter name / role]`

**Comments:**

`[Enter conclusion]`

---

# 48. Manual Processing Reconciliation

If manual continuity activity occurred:

| Field | Value |
|---|---|
| Manual Processing Used? | `[Yes / No]` |
| Manual Records Identified? | `[Yes / No / N/A]` |
| Transactions Entered? | `[Yes / No / N/A]` |
| Reconciliation Completed? | `[Yes / No / N/A]` |
| Verification Completed? | `[Yes / No / N/A]` |
| Unresolved Discrepancies | `[Enter or None]` |

Manual processing follows [[PROC-013 Manual Processing Procedure]].

---

# 49. Manual Processing Lifecycle

Where applicable, confirm:

- [ ] Collect completed
- [ ] Review completed
- [ ] Enter completed
- [ ] Reconcile completed
- [ ] Verify completed

---

# 50. Backup Media Validation

If external backup media was used:

| Field | Value |
|---|---|
| Drive Identifier | `[Enter]` |
| Facility | `[Enter]` |
| Backup Generation | `[Enter]` |
| Encryption Confirmed | `[Yes / No]` |
| Media Condition | `[Enter]` |
| Restore Successful | `[Yes / No]` |

---

# 51. Off-Site Media

If off-site media was required:

| Field | Value |
|---|---|
| Provider Contacted | `[Yes / No]` |
| Requested Date / Time | `[Enter]` |
| Media Received Date / Time | `[Enter]` |
| Correct Media Received | `[Yes / No]` |
| Custody Exception | `[Enter or None]` |

---

# 52. Active Directory Recovery

Complete this section when Active Directory / Authentication is in scope.

| Validation | Result |
|---|---|
| Required directory backup available | `[Pass / Fail]` |
| Recovery documentation available | `[Pass / Fail]` |
| Required privileged access available | `[Pass / Fail]` |
| Directory integrity validated | `[Pass / Fail]` |
| User authentication validated | `[Pass / Fail]` |
| Administrative authentication validated | `[Pass / Fail]` |
| Required dependent services validated | `[Pass / Fail]` |

**Comments:**

`[Enter comments]`

---

# 53. Infinity Recovery

Complete this section when Infinity is in scope.

| Validation | Result |
|---|---|
| Required infrastructure available | `[Pass / Fail]` |
| Source code available | `[Pass / Fail]` |
| Repository available | `[Pass / Fail]` |
| Documentation available | `[Pass / Fail]` |
| Database restored | `[Pass / Fail]` |
| Application tier restored | `[Pass / Fail]` |
| Web tier restored | `[Pass / Fail]` |
| Authentication validated | `[Pass / Fail]` |
| Authorization validated | `[Pass / Fail]` |
| Database not directly Internet accessible | `[Pass / Fail]` |
| Required integrations validated | `[Pass / Fail]` |
| Order-processing functionality validated | `[Pass / Fail]` |

---

# 54. Infinity Contractor Dependency

If contractor participation was required:

| Field | Value |
|---|---|
| Contractor Required? | `[Yes / No]` |
| Contractor Activity | `[Enter]` |
| Company Documentation Sufficient? | `[Yes / No / Partial]` |
| Undocumented Contractor Knowledge Identified? | `[Yes / No]` |
| Transferability Concern Identified? | `[Yes / No]` |

**Comments:**

`[Enter comments]`

---

# 55. Cloud Recovery

Complete when cloud-hosted recovery is in scope.

| Validation | Result |
|---|---|
| Provider service available | `[Pass / Fail / N/A]` |
| Company backup available | `[Pass / Fail / N/A]` |
| Independent recovery documentation available | `[Pass / Fail]` |
| Authentication available | `[Pass / Fail]` |
| Required application recovered | `[Pass / Fail]` |
| Required data recovered | `[Pass / Fail]` |
| Security configuration validated | `[Pass / Fail]` |
| Business validation completed | `[Pass / Fail]` |

---

# 56. Cloud Provider Dependency

**Provider dependencies observed during recovery:**

`[Enter details]`

**Could recovery proceed without provider assistance?**

- [ ] Yes
- [ ] No
- [ ] Partially
- [ ] Not Tested

---

# 57. Recovery Documentation Assessment

Evaluate the recovery documentation used.

| Criterion | Result |
|---|---|
| Correct procedure available | `[Pass / Fail]` |
| Procedure understandable | `[Pass / Fail]` |
| Required dependencies documented | `[Pass / Fail]` |
| Required configuration documented | `[Pass / Fail]` |
| Required recovery source documented | `[Pass / Fail]` |
| Required validation documented | `[Pass / Fail]` |
| Undocumented knowledge required | `[Yes / No]` |

---

# 58. Documentation Deficiencies

`[Describe any recovery-documentation deficiencies.]`

---

# 59. Recovery Personnel Dependency

Did recovery depend on knowledge held only by one individual?

- [ ] Yes
- [ ] No
- [ ] Unable to Determine

**Details:**

`[Enter details]`

---

# 60. Contractor Dependency

Did recovery depend exclusively on one contractor?

- [ ] Yes
- [ ] No
- [ ] Unable to Determine

**Details:**

`[Enter details]`

---

# 61. Security Incident Considerations

Was the test associated with or based on a security incident scenario?

- [ ] Yes
- [ ] No

If yes, identify applicable considerations:

- [ ] Malware
- [ ] Ransomware
- [ ] Unauthorized access
- [ ] Data exposure
- [ ] Credential compromise
- [ ] Third-party compromise
- [ ] Data corruption
- [ ] Other: `[Enter]`

---

# 62. Evidence Preservation

If a security incident is involved:

- [ ] Evidence requirements identified
- [ ] Destructive action evaluated before execution
- [ ] Required evidence preserved
- [ ] [[PROC-011 Evidence Handling Procedure]] followed
- [ ] Not Applicable

---

# 63. Backup Resilience Review

Where applicable, determine whether compromise of production systems could also compromise the recovery capability.

| Question | Result |
|---|---|
| Backup credentials appropriately restricted? | `[Yes / No / N/A]` |
| Backup media unnecessarily connected? | `[Yes / No / N/A]` |
| Production compromise could alter backups? | `[Yes / No / Unknown]` |
| Backup administrative access reviewed? | `[Yes / No / N/A]` |
| Recovery source reasonably trusted? | `[Yes / No / Unknown]` |

---

# 64. Test Results Summary

| Area | Result |
|---|---|
| Recovery Execution | `[Pass / Fail / Partial]` |
| RTO | `[Pass / Fail / N/A]` |
| RPO | `[Pass / Fail / N/A]` |
| Technical Validation | `[Pass / Fail / Partial / N/A]` |
| Security Validation | `[Pass / Fail / Partial / N/A]` |
| Data Validation | `[Pass / Fail / Partial / N/A]` |
| Business Validation | `[Pass / Fail / Partial / N/A]` |
| Documentation | `[Pass / Fail / Partial]` |
| Overall Test | `[Pass / Fail / Partial]` |

---

# 65. Overall Test Conclusion

**Overall Conclusion:**

`[Summarize what the test demonstrated.]`

---

# 66. Overall Test Rating

Select one:

- [ ] **Pass**: Required success criteria were satisfied.
- [ ] **Partial**: Some required objectives were satisfied, but one or more material limitations or deficiencies remain.
- [ ] **Fail**: One or more required success criteria were not satisfied.

---

# 67. Success Criteria Results

| # | Success Criterion | Result | Evidence |
|---:|---|---|---|
| 1 | `[Criterion]` | `[Pass / Fail]` | `[Evidence]` |
| 2 | `[Criterion]` | `[Pass / Fail]` | `[Evidence]` |
| 3 | `[Criterion]` | `[Pass / Fail]` | `[Evidence]` |
| 4 | `[Criterion]` | `[Pass / Fail]` | `[Evidence]` |
| 5 | `[Criterion]` | `[Pass / Fail]` | `[Evidence]` |

---

# 68. Observations

Record observations that do not currently constitute material deficiencies.

| # | Observation |
|---:|---|
| 1 | `[Enter observation]` |
| 2 | `[Enter observation]` |
| 3 | `[Enter observation]` |

---

# 69. Findings

A finding is a documented conclusion supported by evidence concerning whether a requirement, control, process, or expected outcome was satisfied.

| Finding ID | Finding | Requirement | Severity / Significance | Evidence |
|---|---|---|---|---|
| `[ID]` | `[Finding]` | `[Requirement]` | `[Enter]` | `[Evidence]` |
| `[ID]` | `[Finding]` | `[Requirement]` | `[Enter]` | `[Evidence]` |

---

# 70. Satisfactory Findings

A test may document satisfactory findings when evidence demonstrates that a requirement was satisfied.

Satisfactory findings do not require corrective action unless another weakness is identified.

---

# 71. Deficiency Findings

Deficiency findings must identify the unmet requirement or expected outcome.

Material deficiencies must be entered into [[REG-004 Finding & Corrective Action Register]].

---

# 72. Corrective Actions

| Finding ID | Corrective Action | Accountable Owner | Due Date | Validation Method |
|---|---|---|---|---|
| `[ID]` | `[Action]` | `[Owner]` | `[Date]` | `[Method]` |
| `[ID]` | `[Action]` | `[Owner]` | `[Date]` | `[Method]` |

---

# 73. Corrective Action Status

Corrective action status:

- [ ] Planned
- [ ] Approved
- [ ] Implementing
- [ ] Implemented
- [ ] Validation Pending
- [ ] Validated
- [ ] Corrective Action Required

---

# 74. Implementation Does Not Equal Effectiveness

An implemented corrective action must not be treated as effective solely because implementation is complete.

Validation must determine whether the identified deficiency was corrected.

---

# 75. Retest Requirement

Is retesting required?

- [ ] Yes
- [ ] No

**Reason:**

`[Enter rationale]`

---

# 76. Retest Scope

If retesting is required:

**Retest Objective:**

`[Enter objective]`

**Retest Scope:**

`[Enter scope]`

**Required Validation:**

`[Enter validation method]`

**Target Completion:**

`[Enter date]`

---

# 77. Retest Results

Complete after retesting.

| Field | Result |
|---|---|
| Retest Date | `[Enter]` |
| Retest Performed By | `[Enter]` |
| Original Finding | `[Enter]` |
| Corrective Action Implemented | `[Enter]` |
| Retest Result | `[Pass / Fail / Partial]` |
| Evidence | `[Enter]` |
| Finding Status | `[Open / Closed / Further Action Required]` |

---

# 78. Failed Retest

A failed retest must remain visible in the assurance record.

Do not remove the original finding or failed retest merely because another remediation attempt will occur.

---

# 79. Risk Relationship

Identify applicable enterprise risks.

| Risk ID | Risk | Relationship |
|---|---|---|
| `[R###]` | `[Risk Name]` | `[Describe relationship]` |
| `[R###]` | `[Risk Name]` | `[Describe relationship]` |

---

# 80. R027 Backup / Recovery Failure

When applicable, evaluate the test against:

**R027 Backup / Recovery Failure**

- Inherent Risk: **20 Critical**
- Current Residual Risk: **12 High**
- Target Residual Risk: **5 Moderate**

---

# 81. R027 Risk Reassessment Question

Does the completed test provide sufficient new evidence to support reassessment of R027?

- [ ] Yes
- [ ] No
- [ ] Additional Evidence Required

**Rationale:**

`[Enter rationale]`

---

# 82. Other Common Risk Relationships

Recovery testing may also provide evidence relevant to:

- R003 Ransomware
- R006 Infinity Application Compromise
- R013 Administrative / Configuration Error
- R016 Cloud Outage
- R017 ISP Outage
- R018 Third-Party Technology Failure / Compromise
- R026 Personnel Loss
- R028 Data Corruption
- R033 Manual Outage Processing Error
- R034 Loss of Headquarters
- R035 Regional Disaster

Only risks actually supported by the test evidence should be associated with the completed test.

---

# 83. Current Residual Risk

Current residual risk must not be changed merely because a recovery test occurred.

The evidence must support a change in the risk conclusion.

---

# 84. Target Residual Risk

Target residual risk remains a prediction of expected risk after planned treatment.

A test may demonstrate that the target is:

- Reasonable
- Too optimistic
- Too conservative
- Not yet supported

---

# 85. Validated Post-Treatment Risk

When treatment has been implemented and validated, the risk owner may reassess the risk.

Actual validated risk may be:

- Higher than target
- Equal to target
- Lower than target

---

# 86. Historical Risk Integrity

A new validated risk assessment must not overwrite the original May 2013 assessment.

Historical risk results must remain preserved.

---

# 87. Control Effectiveness

Identify relevant controls and assessment conclusions.

| Control | Expected Outcome | Evidence | Effectiveness |
|---|---|---|---|
| `[Control]` | `[Outcome]` | `[Evidence]` | `[Effective / Partially Effective / Ineffective / Not Implemented]` |
| `[Control]` | `[Outcome]` | `[Evidence]` | `[Effective / Partially Effective / Ineffective / Not Implemented]` |

---

# 88. Control Effectiveness Rationale

`[Explain why the evidence supports the effectiveness conclusion.]`

---

# 89. Evidence Inventory

| Evidence ID | Evidence | Location | Classification |
|---|---|---|---|
| `[ID]` | `[Description]` | `[Location]` | `[Classification]` |
| `[ID]` | `[Description]` | `[Location]` | `[Classification]` |
| `[ID]` | `[Description]` | `[Location]` | `[Classification]` |

---

# 90. Evidence Examples

Evidence may include:

- Backup logs
- Restore logs
- Screenshots
- System logs
- Configuration records
- Test notes
- Timing records
- Recovered files
- Validation records
- Business-owner confirmation
- Provider correspondence
- Corrective-action records

---

# 91. Evidence Integrity

Evidence should be sufficient to support the recorded conclusion.

The test record must distinguish between:

- Direct observation
- Technical evidence
- Business confirmation
- Provider-supplied information
- Assumption

---

# 92. Provider-Supplied Evidence

Provider statements should be identified as provider-supplied information.

A provider reporting successful recovery does not automatically establish successful Dunder Mifflin recovery.

---

# 93. Test Metrics

Record metrics generated by this test.

| Metric | Result |
|---|---|
| Recovery Time | `[Enter]` |
| RTO Result | `[Pass / Fail / N/A]` |
| Data Loss | `[Enter]` |
| RPO Result | `[Pass / Fail / N/A]` |
| Failed Recovery Attempts | `[Enter number]` |
| Findings | `[Enter number]` |
| Material Deficiencies | `[Enter number]` |
| Corrective Actions | `[Enter number]` |
| Retest Required | `[Yes / No]` |

---

# 94. Lessons Learned

**What worked well?**

`[Enter]`

**What did not work as expected?**

`[Enter]`

**What should change?**

`[Enter]`

---

# 95. Documentation Updates

Identify documentation requiring revision.

| Document | Update Required? | Required Change | Owner |
|---|---|---|---|
| `[Document]` | `[Yes / No]` | `[Change]` | `[Owner]` |
| `[Document]` | `[Yes / No]` | `[Change]` | `[Owner]` |

---

# 96. Architecture Updates

Does the test identify a required architecture change?

- [ ] Yes
- [ ] No

**Details:**

`[Enter details]`

---

# 97. BIA Review

Does the test identify information suggesting the Business Impact Analysis should be reviewed?

- [ ] Yes
- [ ] No

**Details:**

`[Enter details]`

---

# 98. Recovery Plan Review

Does the test identify required changes to:

- [ ] [[PLN-002 Business Continuity Plan]]
- [ ] [[PLN-003 Disaster Recovery Plan]]
- [ ] [[PLN-004 Cloud Exit & Emergency Migration Plan]]
- [ ] [[PROC-012 Backup & Recovery Procedure]]
- [ ] [[PROC-013 Manual Processing Procedure]]
- [ ] System-specific recovery documentation
- [ ] None

---

# 99. Management Escalation

Does the test require management escalation?

- [ ] Yes
- [ ] No

**Reason:**

`[Enter reason]`

---

# 100. Executive Escalation

Does the test identify a material enterprise risk requiring executive attention?

- [ ] Yes
- [ ] No

**Reason:**

`[Enter reason]`

---

# 101. Risk Acceptance

If a recovery deficiency will not be remediated within the required period, determine whether formal risk acceptance is required under [[POL-005 Risk Management Policy]].

**Risk Acceptance Required?**

- [ ] Yes
- [ ] No
- [ ] To Be Determined

---

# 102. Final Test Disposition

Select one:

- [ ] Test completed, requirements satisfied.
- [ ] Test completed, corrective action required.
- [ ] Test completed, retest required.
- [ ] Test incomplete and must be rescheduled.
- [ ] Test stopped for safety or operational reasons.
- [ ] Other: `[Describe]`

---

# 103. Test Coordinator Sign-Off

| Field | Value |
|---|---|
| Name | `[Enter]` |
| Role | `[Enter]` |
| Date | `[Enter]` |
| Conclusion | `[Enter]` |

---

# 104. Technical Review

| Field | Value |
|---|---|
| Reviewer | `[Enter]` |
| Role | `[Enter]` |
| Date | `[Enter]` |
| Review Result | `[Accepted / Changes Required]` |
| Comments | `[Enter]` |

---

# 105. Business Owner Review

| Field | Value |
|---|---|
| Business Owner / Representative | `[Enter]` |
| Date | `[Enter]` |
| Business Validation Accepted? | `[Yes / No / N/A]` |
| Comments | `[Enter]` |

---

# 106. Security Review

| Field | Value |
|---|---|
| Reviewer | `[Enter]` |
| Role | `[Enter]` |
| Date | `[Enter]` |
| Security Validation Accepted? | `[Yes / No / N/A]` |
| Comments | `[Enter]` |

---

# 107. Final Approval

| Field | Value |
|---|---|
| Approver | `[Enter appropriate authority]` |
| Date | `[Enter]` |
| Test Record Accepted? | `[Yes / No]` |
| Required Follow-Up | `[Enter]` |

---

# 108. Traceability

A completed Recovery Test record supports:

**Business Requirement → Asset / Process → Classification / BIA → Risk → Treatment → Policy / Standard → Control → Procedure → Implementation → Evidence → Test / Audit → Finding → Remediation → Retest → Risk Reassessment**

The test record provides evidence between implemented recovery controls and conclusions about actual recovery capability.

---

# 109. Related Artifacts

- [[RPT-001 Enterprise Profile & Security Baseline]]
- [[RPT-002 Business Impact Analysis]]
- [[RPT-003 Enterprise Risk Assessment]]
- [[REG-001 Enterprise Asset Register]]
- [[REG-002 Enterprise Risk Register]]
- [[RTP-001 Enterprise Risk Treatment Plan]]
- [[POL-004 Information Classification & Handling Policy]]
- [[POL-005 Risk Management Policy]]
- [[POL-007 Change & Configuration Management Policy]]
- [[POL-009 Incident Response Policy]]
- [[POL-010 Business Continuity & Disaster Recovery Policy]]
- [[STD-001 Information Classification Standard]]
- [[STD-004 Server Security Standard]]
- [[STD-006 Secure Configuration Standard]]
- [[PROC-005 Emergency Access Procedure]]
- [[PROC-009 Malware Response Procedure]]
- [[PROC-011 Evidence Handling Procedure]]
- [[PROC-012 Backup & Recovery Procedure]]
- [[PROC-013 Manual Processing Procedure]]
- [[PLN-001 Incident Response Plan]]
- [[PLN-002 Business Continuity Plan]]
- [[PLN-003 Disaster Recovery Plan]]
- [[PLN-004 Cloud Exit & Emergency Migration Plan]]
- [[PBK-002 Malware & Ransomware Playbook]]
- [[PRO-008 Security Assurance & Continuous Improvement Program]]
- [[REG-003 Enterprise Security Control Inventory]]
- [[REG-004 Finding & Corrective Action Register]]
- [[REG-005 Security Metrics Catalog]]
- [[TMP-001 Assessment Work Plan Template]]

---

# 110. Template Maintenance

This template must be reviewed:

- At least annually
- Following material recovery-testing process change
- Following significant BIA methodology change
- Following significant Disaster Recovery process change
- When assurance activities identify a material template deficiency

The IT & Information Security Manager coordinates review.

Material revisions require CIO approval.

---

# 111. Revision History

| Version | Date     | Description                    | Approval |
| ------- | -------- | ------------------------------ | -------- |
| 1.0     | May 2013 | Initial Recovery Test Template | CIO      |