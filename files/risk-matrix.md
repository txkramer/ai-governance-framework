# AI Risk Matrix

Use this matrix to identify, score, and prioritize AI-related risks for your organization. Review quarterly or whenever you adopt a new AI tool.

---

## How to Use This

1. Identify risks relevant to your organization from the catalog below (or add your own).
2. Score each risk for likelihood and impact.
3. Multiply to get a risk score.
4. Prioritize mitigation based on the score.

## Scoring

**Likelihood:** How likely is this to happen?

| Score | Level | Description |
|-------|-------|-------------|
| 1 | Rare | Could happen but very unlikely in normal operations |
| 2 | Unlikely | Has happened elsewhere, possible here under certain conditions |
| 3 | Possible | Reasonable chance this could occur within the next year |
| 4 | Likely | Expected to occur at some point, probably within 6 months |
| 5 | Almost Certain | Already happening or will happen without intervention |

**Impact:** If it happens, how bad is it?

| Score | Level | Description |
|-------|-------|-------------|
| 1 | Minimal | Minor inconvenience, no data loss, easily corrected |
| 2 | Low | Limited operational disruption, no regulatory impact |
| 3 | Moderate | Noticeable operational impact, potential policy violation, staff retraining needed |
| 4 | High | Regulatory notification required, significant data exposure, financial penalty possible |
| 5 | Severe | Major breach, legal action, loss of contracts or accreditation, public exposure |

**Risk Score = Likelihood × Impact**

| Score Range | Priority | Action |
|-------------|----------|--------|
| 1-5 | Low | Monitor. Review at next quarterly assessment. |
| 6-12 | Medium | Mitigate. Implement controls within 90 days. |
| 13-19 | High | Act now. Implement controls within 30 days. |
| 20-25 | Critical | Immediate action. Escalate to leadership. Consider stopping the activity. |

---

## Risk Catalog

### Data & Privacy Risks

| ID | Risk | Likelihood | Impact | Score | Mitigation |
|----|------|-----------|--------|-------|------------|
| D1 | Employee pastes PHI into unapproved AI tool | | | | Acceptable use policy, data classification training, DLP monitoring |
| D2 | AI vendor uses customer data for model training | | | | Vendor assessment, contractual opt-out, enterprise licensing |
| D3 | AI tool stores conversation history containing sensitive data | | | | Vendor assessment, data retention policies, tool configuration |
| D4 | Student records processed through AI without FERPA compliance | | | | Data classification guide, approved tool list, training |
| D5 | AI-generated output inadvertently contains PII from training data | | | | Output review process, vendor transparency requirements |

### Operational Risks

| ID | Risk | Likelihood | Impact | Score | Mitigation |
|----|------|-----------|--------|-------|------------|
| O1 | Staff over-relies on AI, misses critical errors | | | | Human review requirements, quality sampling |
| O2 | AI tool outage disrupts dependent workflows | | | | Identify dependencies, maintain manual fallback procedures |
| O3 | AI produces inaccurate information used in decisions | | | | Verification requirements, domain expert review |
| O4 | Shadow AI: staff using unapproved tools without IT knowledge | | | | Network monitoring, regular tool audits, easy approval process |
| O5 | AI automation processes bad data at scale before detection | | | | Validation checks, staged rollouts, monitoring alerts |

### Compliance & Legal Risks

| ID | Risk | Likelihood | Impact | Score | Mitigation |
|----|------|-----------|--------|-------|------------|
| C1 | HIPAA violation from AI processing of PHI | | | | BAA requirements, approved tool list, access controls |
| C2 | Copyright infringement from AI-generated content | | | | Staff training, usage guidelines, legal review for published content |
| C3 | AI-assisted hiring decisions create discrimination liability | | | | Human oversight requirements, bias testing, legal review |
| C4 | Regulatory audit finds inadequate AI governance documentation | | | | This framework, regular reviews, audit trail |

### Reputational Risks

| ID | Risk | Likelihood | Impact | Score | Mitigation |
|----|------|-----------|--------|-------|------------|
| R1 | AI generates biased or offensive content shared externally | | | | Review requirements, content guidelines, incident response plan |
| R2 | Public perception damage from AI replacing jobs | | | | Communication plan, focus on augmentation messaging |
| R3 | AI error in patient-facing or student-facing context | | | | Human review, limited AI exposure to end-users, testing protocols |

---

## Completed Assessment

**Assessment Date:**
**Completed By:**
**Next Review Date:**

### Top 5 Risks by Score

| Rank | ID | Risk | Score | Status |
|------|-----|------|-------|--------|
| 1 | | | | |
| 2 | | | | |
| 3 | | | | |
| 4 | | | | |
| 5 | | | | |

### Action Items

| Risk ID | Action | Owner | Deadline | Status |
|---------|--------|-------|----------|--------|
| | | | | |

---

*Reassess whenever you add a new AI tool, change vendors, or experience an incident.*
