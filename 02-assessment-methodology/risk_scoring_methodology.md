# Third-Party Vendor Risk Assessment Methodology

## 1. Purpose

This document defines the methodology for assessing and scoring cybersecurity risks associated with third-party vendors. It establishes consistent criteria for evaluating vendor security controls, determining risk levels, prioritizing remediation, and supporting vendor approval decisions.

## 2. Assessment Framework

The assessment uses the following guidance:

- NIST SP 800-161 Rev. 1: Cybersecurity Supply Chain Risk Management Practices for Systems and Organizations.
- NIST Cybersecurity Framework (CSF) 2.0: Cybersecurity risk management outcomes.

These frameworks guide the assessment. This project does not represent a formal certification or independent audit.

## 3. Risk Assessment Approach

The assessment will evaluate risks in two stages:

**Inherent risk:** The level of risk associated with the vendor relationship before considering the effectiveness of security controls.

**Residual risk:** The level of risk remaining after considering the vendor's security controls and available supporting evidence.

Vendor responses alone will not be treated as proof that a control is effective. Supporting evidence must be reviewed where appropriate. Missing or insufficient evidence will be recorded as Not Verified.

## 4. Likelihood Scale

| Score | Rating | Description |
|---|---|---|
| 1 | Rare | The event is highly unlikely under the assessed conditions. |
| 2 | Unlikely | The event could occur but is not expected. |
| 3 | Possible | The event could reasonably occur. |
| 4 | Likely | The event is expected to occur in relevant circumstances. |
| 5 | Almost Certain | The event is highly likely or expected to occur frequently. |

## 5. Impact Scale

| Score | Rating | Description |
|---|---|---|
| 1 | Insignificant | Minimal operational or security impact. |
| 2 | Minor | Limited disruption or exposure with straightforward recovery. |
| 3 | Moderate | Meaningful disruption, data exposure, or remediation effort. |
| 4 | Major | Significant disruption, sensitive data exposure, or regulatory consequences. |
| 5 | Severe | Extensive impact involving critical healthcare operations, serious patient data exposure, or major legal and regulatory consequences. |

## 6. Risk Scoring Formula

Risk Score = Likelihood × Impact

Both likelihood and impact are scored from 1 to 5. The resulting risk score ranges from 1 to 25.

| Score | Risk Level | Required Response |
|---|---|---|
| 1–4 | Low | Maintain controls and monitor periodically. |
| 5–9 | Moderate | Document the risk and address gaps through planned improvements. |
| 10–16 | High | Prioritize corrective action and require documented risk-owner review. |
| 17–25 | Critical | Escalate promptly; do not approve the vendor for the affected use without appropriate risk treatment and formal authorization. |

## 7. Inherent Risk Scoring

Inherent risk will be determined by evaluating the likelihood and impact of each identified risk before crediting vendor security controls.

The assessment will consider factors such as:

- Sensitivity and volume of data processed.
- Importance of the vendor service to healthcare operations.
- System connectivity and access privileges.
- Potential patient safety, privacy, legal, and regulatory consequences.
- Exposure to external threats and supply-chain dependencies.

## 8. Residual Risk Scoring

Residual risk will be determined after evaluating relevant controls and the evidence supporting their implementation and effectiveness.

The assessor will reassess likelihood and impact based on the control environment and document the rationale for any change. Residual scores must not be reduced simply because a vendor claims that a control exists.

Where control effectiveness cannot be verified, the uncertainty will be documented and reflected in the risk assessment. An unverified control will not automatically be treated as effective.

## 9. Control Assessment Status

Each control will be assigned one of the following statuses:

- **Implemented:** Available evidence supports that the control is implemented.
- **Partially Implemented:** The control exists but has identified gaps.
- **Not Implemented:** The control is absent or known not to be implemented.
- **Not Verified:** Available information is insufficient to determine implementation or effectiveness.

## 10. Risk Treatment Options

Identified risks may be managed through:

- **Mitigate:** Implement corrective controls or other safeguards.
- **Avoid:** Do not proceed with the vendor relationship or affected service.
- **Transfer:** Allocate certain financial or contractual consequences through appropriate arrangements. This does not eliminate the organization's accountability.
- **Accept:** Formally accept the remaining risk through an authorized risk owner, with documented justification.

High and Critical risks require documented review before vendor approval. Any acceptance must follow the organization's approval authority and applicable legal, privacy, and security requirements.

## 11. Assessment Limitations

This is a simulated portfolio assessment using a fictional healthcare organization and fictional vendor. Vendor responses and evidence introduced in later project stages will be clearly identified as simulated. Scores and recommendations demonstrate the assessment methodology and do not establish the actual security posture of a real company.
