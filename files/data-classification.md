# Data Classification Guide for AI Usage

Before using any data with an AI tool, you need to know what kind of data it is. This guide helps you make that call quickly.

---

## Classification Levels

### 🟢 Public

Data that's already publicly available or intended for public consumption.

**Examples:**
- Published website content, blog posts, marketing materials
- Public press releases and announcements
- General industry information and publicly available research
- Job postings and public-facing policies
- Open-source code and documentation

**AI Rules:** Can be used with any approved AI tool. No special handling required.

---

### 🟡 Internal

Data meant for internal use that wouldn't cause significant harm if exposed, but isn't intended for the public.

**Examples:**
- Internal memos and meeting notes (without sensitive topics)
- Project plans and timelines
- Non-sensitive operational procedures
- Internal training materials
- General IT documentation
- Anonymized and aggregated data

**AI Rules:** Can be used with approved, enterprise-licensed AI tools only. Not consumer-tier free accounts. Verify the tool doesn't use your data for training.

---

### 🟠 Confidential

Data that could cause real harm to the organization or individuals if exposed.

**Examples:**
- Financial records and budgets
- Strategic plans and board materials
- Employee compensation and performance data
- Vendor contracts and pricing
- Unreleased product or service plans
- Internal audit findings
- Proprietary business processes

**AI Rules:** Do not use with AI tools unless the specific tool has been explicitly approved for confidential data by IT and legal. Document every use case.

---

### 🔴 Restricted

Data protected by law or regulation. Exposure could result in legal action, fines, or severe harm to individuals.

**Examples:**
- Protected Health Information (PHI): patient names, diagnoses, treatment records, insurance info
- Student education records (FERPA-protected)
- Social Security numbers
- Payment card data (PCI)
- Authentication credentials (passwords, API keys, certificates)
- Legal hold materials
- Active investigation data
- Biometric data

**AI Rules:** Never use with AI tools unless all of the following are true:
1. The tool has been specifically approved for restricted data
2. A BAA or equivalent agreement is in place (for PHI)
3. The use case has been approved by compliance and legal
4. Access is logged and auditable

---

## Quick Decision Tree

```
Is the data publicly available?
├── Yes → 🟢 Public — use with any approved tool
└── No
    ├── Is it protected by law (HIPAA, FERPA, PCI)?
    │   ├── Yes → 🔴 Restricted — do not use with AI (see exceptions above)
    │   └── No
    │       ├── Would exposure cause financial/competitive/personal harm?
    │       │   ├── Yes → 🟠 Confidential — approved tools with explicit authorization only
    │       │   └── No → 🟡 Internal — approved enterprise tools only
    └── Not sure? → Treat as 🟠 Confidential and ask your manager or IT
```

---

## Common Scenarios

| Scenario | Classification | Can I Use AI? |
|----------|---------------|---------------|
| Drafting an email to a colleague about project timelines | 🟡 Internal | Yes, with approved tools |
| Summarizing a patient's treatment notes | 🔴 Restricted | No (unless tool is PHI-approved with BAA) |
| Writing a job posting | 🟢 Public | Yes |
| Analyzing salary data for budget planning | 🟠 Confidential | Only with explicitly approved tools |
| Debugging code that contains API keys | 🔴 Restricted | No. Remove keys first, then use AI for the code. |
| Drafting a response to a public review | 🟢 Public | Yes |
| Creating training materials from internal SOPs | 🟡 Internal | Yes, with approved tools |
| Reviewing contract terms with a vendor | 🟠 Confidential | Only with explicitly approved tools |
| Generating a lesson plan from student performance data | 🔴 Restricted | No (FERPA). Use anonymized/aggregated data instead. |

---

## What to Do If You Make a Mistake

If you accidentally sent restricted or confidential data to an AI tool:

1. **Stop immediately.** Don't continue the conversation.
2. **Delete the conversation** if the tool allows it.
3. **Report it** using the [Incident Response Plan](../templates/incident-response-plan.md).
4. **Don't panic.** Mistakes happen. Reporting quickly limits the damage.

---

*When in doubt, ask IT before using data with AI. It's always easier to get permission first than to handle an incident after.*
