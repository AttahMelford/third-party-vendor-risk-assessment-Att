# Third-Party Vendor Remediation Plan

## 1. Assessment Details

| Field | Details |
|---|---|
| Organization | Northstar Health Network |
| Vendor | MedCloud Solutions |
| Service | Cloud-based patient record management SaaS |
| Vendor Risk Tier | High |
| Plan Owner | GRC Analyst |
| Plan Status | Proposed — Pending Vendor Agreement |

## 2. Remediation Objectives

The remediation plan addresses security gaps identified during the vendor risk assessment. Its objectives are to reduce risks affecting patient information, service availability, access control, security monitoring, incident response, and third-party oversight.

The vendor is expected to provide an action owner, target completion date, and evidence of completion for each applicable corrective action. Northstar Health Network's designated risk owner will review outstanding risks before making a final vendor approval decision.

## 3. Priority Definitions

| Priority | Criteria | Expected Handling |
|---|---|---|
| Critical | Risk score 17–25 | Immediate escalation and priority remediation; approval restricted pending risk-owner review and appropriate safeguards. |
| High | Risk score 10–16 | Prioritized remediation with documented milestones and risk-owner oversight. |
| Moderate | Risk score 5–9 | Planned remediation or documented risk acceptance, as appropriate. |
| Low | Risk score 1–4 | Routine monitoring and maintenance. |

## 4. Remediation Actions

| Risk ID | Priority | Required Corrective Action | Responsible Owner | Target Completion | Closure Evidence |
|---|---|---|---|---|---|
| VR-003 | Critical | Establish periodic user access recertification and document access approvals and removals. | Vendor IAM Owner | Within 30 days of agreed remediation start | Completed access review and remediation records |
| VR-004 | Critical | Verify MFA coverage for privileged accounts and applicable remote access; remediate coverage gaps. | Vendor IAM Owner | Within 30 days | Configuration evidence and MFA coverage report |
| VR-005 | Critical | Restrict privileged accounts and implement documented periodic reviews. | Vendor IAM Owner | Within 30 days | Privileged access policy and completed review records |
| VR-009 | Critical | Confirm vulnerability scanning coverage and cadence; prioritize and track identified findings. | Vendor Security Operations Lead | Within 30 days | Scan coverage report and remediation tracking |
| VR-010 | Critical | Define risk-based patch SLAs and track critical and high-severity patches through closure. | Vendor IT Operations Lead | Within 30 days | Approved patch policy and patch compliance report |
| VR-006 | High | Provide evidence of encryption at rest and in transit and validate relevant configurations. | Vendor Data Protection Lead | Within 45 days | Encryption standard and configuration evidence |
| VR-008 | High | Complete data classification and align data handling procedures with sensitivity levels. | Vendor Privacy Lead | Within 60 days | Approved classification standard and handling procedures |
| VR-011 | High | Define log retention requirements and verify logging coverage and retention settings. | Vendor Security Operations Lead | Within 45 days | Logging standard and configuration evidence |
| VR-012 | High | Document alert triage, investigation, escalation, and incident tracking procedures. | Vendor Security Operations Lead | Within 45 days | Monitoring procedures and sample investigation records |
| VR-013 | High | Conduct an incident response exercise and track lessons learned to closure. | Vendor Incident Response Lead | Within 60 days | Exercise report and corrective action log |
| VR-014 | High | Agree contractual incident notification timelines, escalation contacts, and responsibilities. | Vendor Legal and Compliance Lead | Before contract execution | Agreed contract clauses and notification procedure |
| VR-015 | High | Test restoration of backups and document recovery results against service requirements. | Vendor IT Operations Lead | Within 60 days | Backup restoration test report |
| VR-016 | High | Test business continuity and disaster recovery plans against documented recovery objectives. | Vendor Business Continuity Lead | Within 90 days | Approved test report and corrective action log |
| VR-017 | High | Document secure development requirements and retain code review and security testing evidence. | Vendor Engineering Lead | Within 60 days | Secure development standard and testing records |
| VR-019 | High | Provide a complete subprocessor inventory and document security due diligence and oversight. | Vendor Third-Party Risk Owner | Within 45 days | Current subprocessor list and assessment records |
| VR-001 | High | Approve the information security policy and establish a documented review cycle. | Vendor Security Lead | Within 60 days | Approved policy and review record |
| VR-007 | High | Define retention requirements and verify secure deletion procedures. | Vendor Data Protection Lead | Within 60 days | Approved retention standard and deletion-test evidence |
| VR-018 | High | Require documented authorization, testing, and review for production changes. | Vendor IT Operations Lead | Within 60 days | Change management procedure and completed change records |
| VR-020 | High | Provide a current, relevant independent security assurance report or equivalent evidence for review. | Vendor Compliance Lead | Within 45 days | Reviewed assurance report or equivalent evidence |
| VR-002 | Moderate | Formally document security responsibilities, accountability, and escalation authority. | Vendor Security Lead | Within 60 days | Approved responsibility matrix |

## 5. Remediation Governance

The following governance requirements apply to remediation activities:

1. The vendor provides an action owner, agreed target date, progress update, and supporting evidence for each corrective action.
2. The GRC Analyst tracks overdue actions and escalates material delays to the designated risk owner.
3. Critical risks remain subject to heightened review until corrective actions are completed and their effectiveness is verified.
4. High risks require documented treatment plans and risk-owner oversight.
5. Any proposed risk acceptance must include a documented rationale, compensating controls where applicable, and approval by an authorized risk owner.
6. Contractual and regulatory requirements must be satisfied regardless of the proposed risk rating.

## 6. Remediation Closure Criteria

A remediation item may be marked closed only when:

- The agreed corrective action has been implemented.
- Appropriate supporting evidence has been received and reviewed.
- The evidence demonstrates that the identified weakness has been addressed.
- Remaining risk has been reassessed and documented.
- The designated reviewer has approved closure.

A vendor statement that an action is complete is not sufficient by itself to close a finding.

## 7. Relationship to the Risk Register

The initial risk register remains the baseline assessment record. Completion of a remediation action does not automatically change its original score.

Once corrective actions have been implemented and supported by reviewed evidence, the organization will record a follow-up reassessment. That reassessment will document updated control status, revised likelihood and impact where justified, residual risk, evidence reviewed, and reviewer approval.

## 8. Approval Considerations

Vendor approval remains subject to review of the initial risk findings, applicable contractual and regulatory requirements, the sensitivity of the data involved, and the organization's risk acceptance authority.

Outstanding Critical risks require escalation and documented authorization before the affected service is approved for use. Any conditional approval must define permitted activities, required safeguards, remediation deadlines, and consequences if requirements are not met.
