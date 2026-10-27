# Vendor Risk Assessment and Approval Recommendation

## 1. Executive Summary

Northstar Health Network conducted an initial third-party cybersecurity risk assessment of MedCloud Solutions, a proposed provider of cloud-based patient record management software.

The assessment identified weaknesses and evidence gaps across identity and access management, vulnerability and patch management, data protection, security monitoring, incident response, business continuity, and subcontractor oversight.

The initial risk register contains four Critical risks and sixteen High risks. Several important controls remain partially implemented or unverified based on the assessment information available.

Given the sensitivity of patient information and the proposed service's importance to healthcare operations, the current risk exposure requires remediation and management oversight before the service is approved for production use.

## 2. Recommendation

**Recommendation: Defer production approval pending satisfactory risk treatment and review.**

MedCloud Solutions should not be approved for production processing of Northstar Health Network patient information at this stage. The assessment has not established sufficient assurance that the vendor's security controls adequately address the identified risks.

The organization may continue due diligence, contract negotiations, and other non-production evaluation activities where appropriate safeguards are in place and no prohibited data is introduced.

Any exception must be approved by the authorized risk owner and relevant privacy, security, legal, and business stakeholders.

## 3. Key Risk Findings

| Risk Area | Key Finding | Risk IDs | Priority |
|---|---|---|---|
| Identity and Access Management | Periodic access reviews are inconsistent; MFA coverage and privileged-access oversight require further validation. | VR-003, VR-004, VR-005 | Critical |
| Vulnerability and Patch Management | Scanning coverage is unverified and patch remediation timeframes are insufficiently documented. | VR-009, VR-010 | Critical |
| Data Protection and Privacy | Encryption evidence, data classification, and secure deletion practices require stronger assurance. | VR-006, VR-007, VR-008 | High |
| Security Monitoring | Log retention and alert investigation practices are not adequately demonstrated. | VR-011, VR-012 | High |
| Incident Response and Recovery | Incident response exercises, backup restoration, and disaster recovery testing require evidence. | VR-013, VR-015, VR-016 | High |
| Software and Change Management | Secure development and production change controls need improved documentation and evidence. | VR-017, VR-018 | High |
| Third-Party Oversight | The complete subprocessor inventory and independent security assurance remain unverified. | VR-019, VR-020 | High |

## 4. Conditions for Reconsidering Approval

Before production approval is reconsidered, the following conditions should be met:

1. **Access security:** Verify MFA coverage, complete required access reviews, and establish effective privileged-access oversight.
2. **Vulnerability management:** Demonstrate adequate scanning coverage and a documented, risk-based patch management process.
3. **Data protection:** Provide appropriate evidence of encryption, data handling, retention, and secure deletion controls.
4. **Incident notification:** Agree on contractual notification timelines, escalation contacts, and responsibilities.
5. **Resilience:** Provide appropriate backup restoration and business continuity or disaster recovery test results.
6. **Third-party assurance:** Supply relevant independent security assurance documentation and a complete subprocessor inventory.
7. **Risk governance:** Assign accountable owners, agree on remediation deadlines, and document the treatment of remaining risks.

Evidence should be reviewed for relevance, scope, currency, and sufficiency. Findings should be closed only after the relevant corrective actions have been verified.

## 5. Risk Acceptance and Exceptions

Risk acceptance must not be used as a substitute for mandatory legal, regulatory, privacy, or contractual obligations.

Any proposed exception must identify the affected risk, business justification, potential impact, compensating safeguards, duration, accountable risk owner, and approval authority.

Critical risks require explicit escalation and documented authorization. Where adequate safeguards cannot be demonstrated, production approval should remain deferred.

## 6. Ongoing Oversight

If the vendor later satisfies the approval conditions, Northstar Health Network should reassess the relevant risks before authorizing production use.

Following approval, the vendor relationship should be monitored according to its risk tier. Monitoring should include remediation follow-up, changes in service or data processing, security incidents, subcontractor changes, and updated independent assurance.

The initial risk register should be retained as the baseline assessment. Any subsequent reduction in residual risk must be supported by reviewed evidence and recorded in a separate reassessment.

## 7. Decision Record

| Field | Entry |
|---|---|
| Vendor | MedCloud Solutions |
| Service | Cloud-based patient record management SaaS |
| Inherent Vendor Risk Tier | High |
| Initial Risk Register | 4 Critical; 16 High |
| Recommendation | Defer production approval |
| Decision Status | Pending Management Decision |
| Decision Owner | Authorized Business and Risk Owner |
| Conditions for Reconsideration | Completion and verification of required remediation and due diligence |

## 8. Conclusion

The proposed service may offer business value, but the current assessment identifies material security risks and gaps in supporting evidence. Northstar Health Network should defer production approval until the required safeguards are demonstrated, outstanding risks are reviewed, and an authorized decision is documented.
