# Third-Party Vendor Risk Assessment — Executive Report

## 1. Executive Summary

Northstar Health Network conducted a third-party security risk assessment of MedCloud Solutions, a proposed provider of cloud-based patient record management software. The assessment evaluated the vendor's security controls, data protection practices, access management, vulnerability management, incident response capabilities, business continuity arrangements, and third-party oversight.

The assessment identified significant control gaps and areas where sufficient supporting evidence was unavailable to establish control effectiveness. The baseline risk register contains **5 Critical risks, 14 High risks, and 1 Moderate risk**. The most significant concerns involve user access reviews, multi-factor authentication coverage, privileged access management, vulnerability scanning, and patch management.

Based on the baseline assessment, the recommendation is to **defer production approval** until critical risks have been addressed, required evidence has been reviewed, and authorized management has accepted any remaining risk.

## 2. Assessment Overview

| Item | Details |
|---|---|
| Organization | Northstar Health Network |
| Vendor | MedCloud Solutions |
| Service | Cloud-based patient record management SaaS |
| Assessment type | Third-party cybersecurity risk assessment |
| Assessment role | GRC Analyst |
| Primary framework | NIST SP 800-161 Rev. 1 |
| Supporting framework | NIST Cybersecurity Framework 2.0 |
| Risk methodology | Likelihood × Impact, using a 5×5 matrix |
| Initial vendor risk tier | High |
| Approval recommendation | Defer production approval |

## 3. Baseline Risk Results

The initial assessment recorded 20 risks across the vendor's security and operational control environment.

| Risk rating | Number of risks | Management priority |
|---|---:|---|
| Critical | 5 | Immediate attention |
| High | 14 | Prioritized remediation |
| Moderate | 1 | Planned treatment and monitoring |
| **Total** | **20** | |

Critical risks require priority treatment because they could expose sensitive patient information, enable unauthorized access, or increase the likelihood of a serious security incident. High risks also require documented remediation plans, accountable owners, and defined target dates.

The baseline risk register remains the reference point for tracking the original findings and evaluating changes over time.

## 4. Key Findings

### 4.1 Identity and Access Management

The assessment identified gaps in periodic user access reviews, confirmation of multi-factor authentication coverage, and privileged access oversight. These weaknesses could increase the likelihood of unauthorized access to systems containing sensitive patient information.

**Recommended response:** Verify MFA coverage for applicable access paths, implement documented access recertification, and strengthen privileged account controls.

### 4.2 Vulnerability and Patch Management

Evidence was insufficient to confirm comprehensive vulnerability scanning coverage and consistent patch management practices. Delayed identification or remediation of vulnerabilities could expose vendor systems and connected services to exploitation.

**Recommended response:** Establish documented scanning coverage, risk-based remediation timelines, patch compliance reporting, and escalation for overdue critical vulnerabilities.

### 4.3 Data Protection and Privacy

The assessment identified evidence gaps concerning encryption configurations, data classification, retention, and secure disposal. These areas are important because the service is intended to process sensitive healthcare information.

**Recommended response:** Verify encryption controls, document data handling requirements, and establish evidence-based retention and secure deletion procedures.

### 4.4 Incident Response and Operational Resilience

Incident response testing, incident notification requirements, backup restoration, and business continuity testing require further assurance. Weaknesses in these areas could delay incident containment or recovery from a service disruption.

**Recommended response:** Review incident response procedures, confirm contractual notification timelines, and obtain evidence of successful backup restoration and continuity testing.

### 4.5 Independent Assurance and Subcontractor Oversight

The assessment did not establish sufficient assurance concerning the vendor's independent security assessment and subcontractor risk management practices.

**Recommended response:** Review the applicable independent assurance report, evaluate relevant exceptions, obtain an up-to-date subcontractor inventory, and confirm that material subcontractors are subject to appropriate due diligence.

## 5. Remediation Priorities

The remediation plan establishes accountable owners, target dates, required closure evidence, and risk reassessment requirements.

| Priority | Focus area | Expected outcome |
|---|---|---|
| 1 | User access reviews | Documented and completed access recertification |
| 2 | MFA coverage | Verified MFA enforcement for applicable access paths |
| 3 | Privileged access | Restricted administrative access and documented reviews |
| 4 | Vulnerability scanning | Confirmed coverage and tracked remediation |
| 5 | Patch management | Defined patch timelines and compliance evidence |
| 6 | Data protection | Verified encryption and documented data handling controls |
| 7 | Incident response and recovery | Tested response, backup restoration, and continuity procedures |
| 8 | Vendor assurance | Reviewed independent assurance and subcontractor due diligence |

Remediation should not be considered complete solely because a vendor reports that an action has been performed. Closure requires appropriate supporting evidence, review by the responsible assessor, and an updated risk rating.

## 6. Follow-Up Risk Reassessment

The follow-up reassessment record demonstrates how risk ratings can change after remediation activities and supporting evidence are evaluated. Some risks may remain High even after corrective actions because the potential impact of a security incident remains significant.

The reassessment should distinguish between:

- **Control implementation:** Whether the corrective action has been completed.
- **Evidence validation:** Whether supporting documentation demonstrates that the control operates effectively.
- **Residual risk:** The risk remaining after the effectiveness of the control is considered.
- **Risk acceptance:** A formal decision by an authorized risk owner to accept a documented residual risk.

Updated ratings should be supported by validated evidence before they are used to authorize production access or data processing.

## 7. Vendor Approval Recommendation

**Recommendation: Defer production approval.**

The current baseline risk profile does not support unconditional production approval for a service intended to process sensitive patient information.

Before approval is reconsidered, management should require:

1. Resolution and evidence-based reassessment of Critical risks.
2. Review of remediation evidence for other material High risks.
3. Verification of contractual security, privacy, incident notification, and subcontractor requirements.
4. Review of independent assurance documentation and relevant exceptions.
5. Formal assessment of remaining residual risks and approval by the designated risk owner.

Any exception should be documented with a business justification, named risk owner, compensating controls where appropriate, an expiration or review date, and formal authorization.

## 8. Ongoing Monitoring and Governance

If the vendor is approved following remediation, Northstar Health Network should maintain continuous oversight through monthly remediation tracking, quarterly risk reviews, and a comprehensive annual reassessment. Significant incidents, service changes, new subcontractors, or material changes to data processing should trigger an additional review.

The vendor's risk status should be updated when new evidence becomes available, remediation milestones are missed, or the threat and control environment changes.

## 9. Conclusion

The assessment provides a structured view of the cybersecurity risks associated with MedCloud Solutions and establishes a basis for remediation, risk ownership, and vendor governance. The principal management priority is to address the Critical findings, validate remediation evidence, and ensure that residual risks are formally evaluated before the vendor is authorized to process patient information in production.

**Management decision:** Pending remediation review and formal authorization.

**Report owner:** GRC Analyst

**Status:** Assessment completed; remediation and approval decision pending.
