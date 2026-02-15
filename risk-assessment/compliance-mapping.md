# AI Governance Compliance Mapping

This document maps common AI governance controls to major regulatory and compliance frameworks. Use it to identify which parts of this framework satisfy requirements you're already subject to.

---

## Framework Coverage

| Framework | Primary Concern | Applies To |
|-----------|----------------|------------|
| **HIPAA** | Protected health information | Healthcare providers, insurers, business associates |
| **FERPA** | Student education records | Schools, school districts, education vendors |
| **SOC 2** | Security, availability, confidentiality | Service providers, SaaS companies |
| **NIST AI RMF** | AI risk management | Federal agencies, organizations adopting NIST standards |
| **EU AI Act** | AI safety and rights | Organizations serving EU customers |

---

## HIPAA Mapping

| HIPAA Requirement | This Framework's Control | Document |
|-------------------|------------------------|----------|
| Access controls (§164.312(a)) | Approved tool list with role-based access | [Acceptable Use Policy](../templates/acceptable-use-policy.md) |
| Audit controls (§164.312(b)) | Usage logging requirements, vendor audit log requirements | [Tool Evaluation Checklist](../templates/tool-evaluation-checklist.md) |
| Integrity controls (§164.312(c)) | Human review requirements for AI output | [Acceptable Use Policy](../templates/acceptable-use-policy.md) |
| Transmission security (§164.312(e)) | Encryption requirements in tool evaluation | [Tool Evaluation Checklist](../templates/tool-evaluation-checklist.md) |
| Business Associate Agreements (§164.314) | BAA requirement as automatic disqualifier | [Tool Evaluation Checklist](../templates/tool-evaluation-checklist.md) |
| Breach notification (§164.404-410) | Incident response with notification timelines | [Incident Response Plan](../templates/incident-response-plan.md) |
| Risk analysis (§164.308(a)(1)) | Risk matrix with healthcare-specific scenarios | [Risk Matrix](risk-matrix.md) |
| Workforce training (§164.308(a)(5)) | Staff training outline with data handling modules | [Staff Training Outline](../briefings/staff-training-outline.md) |
| Minimum necessary (§164.502(b)) | Data classification restricting PHI from AI tools | [Data Classification Guide](data-classification.md) |

---

## FERPA Mapping

| FERPA Requirement | This Framework's Control | Document |
|-------------------|------------------------|----------|
| Prior consent for disclosure (§99.30) | Restricted classification for student records | [Data Classification Guide](data-classification.md) |
| Legitimate educational interest (§99.31) | Use case justification in tool evaluation | [Tool Evaluation Checklist](../templates/tool-evaluation-checklist.md) |
| Record of disclosures (§99.32) | Audit logging requirements | [Tool Evaluation Checklist](../templates/tool-evaluation-checklist.md) |
| Security safeguards (§99.31(a)(1)(ii)) | Vendor security assessment, encryption requirements | [Vendor AI Assessment](../templates/vendor-ai-assessment.md) |
| De-identification | Guidance on anonymized data usage | [Data Classification Guide](data-classification.md) |

---

## SOC 2 Mapping

| SOC 2 Trust Criteria | This Framework's Control | Document |
|---------------------|------------------------|----------|
| CC6.1 - Logical access | Approved tool list, access controls | [Acceptable Use Policy](../templates/acceptable-use-policy.md) |
| CC6.7 - Data classification | Four-tier data classification system | [Data Classification Guide](data-classification.md) |
| CC7.2 - Monitoring | Vendor audit log requirements, usage logging | [Tool Evaluation Checklist](../templates/tool-evaluation-checklist.md) |
| CC7.3 - Incident management | Full incident response plan with timelines | [Incident Response Plan](../templates/incident-response-plan.md) |
| CC7.4 - Incident response | Containment, assessment, remediation steps | [Incident Response Plan](../templates/incident-response-plan.md) |
| CC9.2 - Risk assessment | Risk matrix with scoring methodology | [Risk Matrix](risk-matrix.md) |
| CC1.4 - Training | Staff training outline, ongoing briefings | [Staff Training Outline](../briefings/staff-training-outline.md) |

---

## NIST AI Risk Management Framework Mapping

| NIST AI RMF Function | This Framework's Control | Document |
|----------------------|------------------------|----------|
| GOVERN 1.1 - Policies | Acceptable use policy, governance structure | [Acceptable Use Policy](../templates/acceptable-use-policy.md) |
| GOVERN 4.1 - Organizational practices | AI committee structure, briefing cadence | [Building an AI Committee](../guides/building-ai-committee.md) |
| MAP 1.1 - Intended purpose | Use case documentation in tool evaluation | [Tool Evaluation Checklist](../templates/tool-evaluation-checklist.md) |
| MAP 5.1 - Impacts to individuals | Risk catalog with impact scoring | [Risk Matrix](risk-matrix.md) |
| MEASURE 2.6 - Bias testing | Vendor bias testing requirements | [Vendor AI Assessment](../templates/vendor-ai-assessment.md) |
| MANAGE 1.1 - Risk prioritization | Risk scoring and action priority levels | [Risk Matrix](risk-matrix.md) |
| MANAGE 2.1 - Incident response | Full incident response plan | [Incident Response Plan](../templates/incident-response-plan.md) |
| MANAGE 4.1 - Regular review | Quarterly review cadence, weekly briefings | [Weekly Briefing Template](../briefings/weekly-briefing-template.md) |

---

## Gap Analysis Template

Use this when preparing for an audit or assessing your current state.

| Requirement | Framework Control | Implemented? | Gap Description | Remediation Plan | Owner | Target Date |
|-------------|------------------|-------------|-----------------|-----------------|-------|-------------|
| | | Yes / Partial / No | | | | |

---

*This mapping is a starting point, not legal advice. Work with your compliance team or legal counsel to validate that controls meet your specific regulatory obligations.*
