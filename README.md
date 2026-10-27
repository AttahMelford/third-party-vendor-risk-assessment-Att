# Third-Party Vendor Risk Assessment

## Project Overview

This project demonstrates a structured third-party cybersecurity risk assessment for a healthcare organization evaluating a cloud-based patient record management provider. The assessment evaluates vendor security controls, identifies risks, establishes remediation priorities, and supports a risk-based vendor approval decision.

The assessment uses **NIST SP 800-161 Rev. 1** as its primary third-party and supply chain risk management reference, supported by the **NIST Cybersecurity Framework (CSF) 2.0**.

## Business Scenario

Northstar Health Network is evaluating MedCloud Solutions as a provider of cloud-based patient record management software. Because the proposed service may process sensitive patient information and connect to healthcare systems, the organization must evaluate the vendor's security posture before authorizing production use.

The assessment identifies control gaps, evaluates potential business and security impacts, documents remediation requirements, and establishes ongoing vendor monitoring activities.

## Assessment Objectives

- Evaluate the vendor's cybersecurity control environment.
- Identify and rate third-party security risks.
- Assess control implementation and supporting evidence.
- Develop risk treatment and remediation recommendations.
- Establish a vendor approval recommendation based on risk.
- Define ongoing monitoring and follow-up reassessment procedures.

## Frameworks and Methodology

**Primary framework:** NIST SP 800-161 Rev. 1 — Cybersecurity Supply Chain Risk Management Practices for Systems and Organizations.

**Supporting framework:** NIST Cybersecurity Framework 2.0.

The assessment uses a 5×5 risk matrix based on likelihood and impact:

| Score | Risk rating |
|---:|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–16 | High |
| 17–25 | Critical |

Control statuses distinguish implemented, partially implemented, not implemented, and not verified controls. Unverified controls are not automatically treated as effective.

## Project Deliverables

| Folder | Deliverable |
|---|---|
| `01-vendor-profile/` | Vendor profile and preliminary risk tier |
| `02-assessment-methodology/` | Risk scoring methodology |
| `03-vendor-questionnaire/` | Vendor security questionnaire covering 20 control areas |
| `04-vendor-responses/` | Vendor responses and evidence assessment |
| `05-risk-register/` | Baseline vendor risk register |
| `06-remediation-plan/` | Remediation actions, owners, and target dates |
| `07-vendor-approval/` | Vendor approval recommendation |
| `08-continuous-monitoring/` | Ongoing monitoring plan |
| `09-follow-up-reassessment/` | Follow-up risk reassessment record |
| `10-executive-report/` | Executive risk assessment report |

## Key Assessment Outcomes

The baseline risk register contains **20 documented risks**:

- **5 Critical**
- **14 High**
- **1 Moderate**

Priority findings include access review weaknesses, unverified MFA coverage, privileged access concerns, insufficient evidence of vulnerability scanning and patch management, and gaps in incident response, resilience, and vendor assurance.

The assessment recommendation is to **defer production approval** until material risks have been treated, remediation evidence has been reviewed, and the remaining risk has been formally evaluated by authorized management.

## Skills Demonstrated

- Third-party and vendor risk assessment
- Governance, Risk, and Compliance (GRC)
- NIST SP 800-161 Rev. 1 and NIST CSF 2.0
- Risk identification, scoring, and prioritization
- Security control assessment and evidence review
- Risk register development
- Remediation planning and risk treatment
- Vendor due diligence and approval governance
- Residual risk reassessment
- Executive reporting and continuous monitoring
- Markdown and GitHub documentation

## Repository Structure

```text
third-party-vendor-risk-assessment/
├── 01-vendor-profile/
├── 02-assessment-methodology/
├── 03-vendor-questionnaire/
├── 04-vendor-responses/
├── 05-risk-register/
├── 06-remediation-plan/
├── 07-vendor-approval/
├── 08-continuous-monitoring/
├── 09-follow-up-reassessment/
├── 10-executive-report/
└── README.md
```

## Project Status

Assessment documentation and baseline risk analysis are complete. Remediation tracking, follow-up reassessment, and the final vendor approval decision remain subject to the scenario's evidence and governance requirements.

**Portfolio note:** Northstar Health Network and MedCloud Solutions are illustrative organizations used to demonstrate a practical third-party risk assessment workflow. The assessment does not represent an actual vendor engagement or independent certification audit.

