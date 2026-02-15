# AI Tool Evaluation Checklist

Use this checklist to evaluate any AI tool before approving it for organizational use. Score each category, then use the total to guide your decision.

---

## Tool Information

| Field | Details |
|-------|---------|
| **Tool Name** | |
| **Vendor** | |
| **Version/Tier** | |
| **Evaluator** | |
| **Date** | |
| **Requested By** | |
| **Intended Use Case** | |

---

## Scoring Guide

Rate each item: **0** = Fails or not available, **1** = Partially meets, **2** = Fully meets

### 1. Data Privacy & Security

| # | Criteria | Score | Notes |
|---|---------|-------|-------|
| 1.1 | Vendor has a clear, published privacy policy | /2 | |
| 1.2 | Data is encrypted in transit and at rest | /2 | |
| 1.3 | Organization retains ownership of input data | /2 | |
| 1.4 | User data is NOT used to train the vendor's models (or can be opted out) | /2 | |
| 1.5 | Vendor offers data deletion on request | /2 | |
| 1.6 | Data residency meets organizational requirements (e.g., US-only) | /2 | |
| 1.7 | Vendor will sign a BAA (if handling PHI) | /2 | |
| 1.8 | SOC 2 Type II or equivalent certification | /2 | |
| **Subtotal** | | **/16** | |

### 2. Compliance & Legal

| # | Criteria | Score | Notes |
|---|---------|-------|-------|
| 2.1 | Tool meets HIPAA requirements (if applicable) | /2 | |
| 2.2 | Tool meets FERPA requirements (if applicable) | /2 | |
| 2.3 | Terms of service are acceptable to legal | /2 | |
| 2.4 | Intellectual property ownership of outputs is clear | /2 | |
| 2.5 | Vendor has an incident notification process | /2 | |
| **Subtotal** | | **/10** | |

### 3. Functionality & Reliability

| # | Criteria | Score | Notes |
|---|---------|-------|-------|
| 3.1 | Tool performs the intended task accurately | /2 | |
| 3.2 | Output quality is consistent and reliable | /2 | |
| 3.3 | Tool has acceptable uptime/SLA | /2 | |
| 3.4 | API or integration options exist (if needed) | /2 | |
| 3.5 | Tool provides audit logs or usage tracking | /2 | |
| **Subtotal** | | **/10** | |

### 4. Usability & Adoption

| # | Criteria | Score | Notes |
|---|---------|-------|-------|
| 4.1 | Non-technical staff can use it with minimal training | /2 | |
| 4.2 | Vendor provides documentation and support | /2 | |
| 4.3 | Admin controls exist (user management, permissions) | /2 | |
| 4.4 | Tool works within existing infrastructure (SSO, etc.) | /2 | |
| **Subtotal** | | **/8** | |

### 5. Cost & Sustainability

| # | Criteria | Score | Notes |
|---|---------|-------|-------|
| 5.1 | Pricing is transparent and within budget | /2 | |
| 5.2 | No hidden costs (per-seat, API overages, etc.) | /2 | |
| 5.3 | Vendor appears financially stable | /2 | |
| 5.4 | Exit strategy exists (data export, contract terms) | /2 | |
| **Subtotal** | | **/8** | |

---

## Total Score

| Category | Score |
|----------|-------|
| Data Privacy & Security | /16 |
| Compliance & Legal | /10 |
| Functionality & Reliability | /10 |
| Usability & Adoption | /8 |
| Cost & Sustainability | /8 |
| **Total** | **/52** |

### Decision Guide

| Score Range | Recommendation |
|-------------|---------------|
| **44-52** | Strong approval. Proceed with standard onboarding. |
| **36-43** | Conditional approval. Address gaps before full rollout. |
| **26-35** | Significant concerns. Require remediation plan from vendor. |
| **Below 26** | Do not approve. Risks outweigh benefits. |

### Automatic Disqualifiers

Regardless of total score, **do not approve** if any of the following are true:

- Vendor uses customer data to train models with no opt-out
- No encryption in transit
- Vendor won't sign a BAA when PHI is involved
- Terms of service grant vendor IP rights to your data
- No incident notification process exists

---

## Approval

| Role | Name | Decision | Date |
|------|------|----------|------|
| IT Lead | | Approve / Deny | |
| Compliance/Legal | | Approve / Deny | |
| Department Head | | Approve / Deny | |

**Notes:**

---

*File evaluation results in [designated location]. Re-evaluate annually or when the vendor makes significant changes.*
