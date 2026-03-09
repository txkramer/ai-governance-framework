# AI Incident Response Plan

This plan covers what to do when an AI tool produces harmful output, exposes sensitive data, or causes an operational disruption. Speed matters. Follow the steps in order.

---

## Incident Categories

| Category | Description | Examples | Severity |
|----------|-------------|----------|----------|
| **Data Exposure** | Sensitive data was sent to or leaked by an AI tool | PHI pasted into ChatGPT, AI tool exposed in API logs | Critical |
| **Harmful Output** | AI produced content that caused or could cause harm | Biased hiring recommendation, incorrect medical info shared with patients | High |
| **Compliance Violation** | AI usage violated a regulation or policy | HIPAA breach through AI processing, FERPA data in unapproved tool | Critical |
| **Operational Disruption** | AI tool failure impacted business operations | AI-dependent workflow went down, automated process produced bad data at scale | Medium-High |
| **Policy Violation** | Employee used AI in a way that breaks the acceptable use policy | Using unapproved tool, feeding restricted data into approved tool | Medium |

---

## Response Steps

### Step 1: Contain (Within 1 Hour)

- **Stop the activity.** If data is still being processed, revoke access or disable the tool immediately.
- **Preserve evidence.** Screenshot the AI interaction, save chat logs, note the tool and model version, and record timestamps.
- **Assess the blast radius.** Determine what data was involved, who was affected, and whether the exposure is ongoing.
- **Notify IT/Security lead.** Contact [NAME/ROLE] at [CONTACT INFO] immediately for Critical or High severity incidents.

### Step 2: Assess (Within 4 Hours)

- **Classify the data involved.** Use the [Data Classification Guide](../risk-assessment/data-classification.md) to determine sensitivity.
- **Determine regulatory impact.** Does this trigger HIPAA breach notification? FERPA reporting? State privacy law requirements?
- **Identify root cause.** Was this a tool failure, user error, policy gap, or vendor issue?
- **Document findings** using the Incident Report template below.

### Step 3: Notify (Within 24 Hours for Critical)

| Who | When | Method |
|-----|------|--------|
| Internal IT/Security | Immediately | Direct contact |
| Department leadership | Within 4 hours | Email + meeting |
| Legal/Compliance | Within 4 hours for regulated data | Direct contact |
| Affected individuals | Per regulatory requirements | Per legal guidance |
| Vendor | Within 24 hours if vendor-side issue | Support ticket + email |
| Regulatory bodies | Per applicable law (HIPAA: 60 days, varies by state) | Per legal guidance |

### Step 4: Remediate

- **Close the vulnerability.** Update permissions, revoke access, patch the tool, or remove it entirely.
- **Update the acceptable use policy** if a gap was identified.
- **Retrain affected staff** on proper AI usage.
- **Add the scenario to the [Risk Matrix](../risk-assessment/risk-matrix.md)** if it represents a new risk category.

### Step 5: Review (Within 2 Weeks)

- Conduct a post-incident review with all stakeholders.
- Document lessons learned and update this plan if needed.
- Communicate changes to staff through the [Weekly Briefing](../briefings/weekly-briefing-template.md).

---

## Incident Report Template

```
INCIDENT REPORT

Date/Time Discovered:
Reported By:
Severity: Critical / High / Medium

WHAT HAPPENED
Tool involved:
Description:

DATA INVOLVED
Data classification level:
Records/individuals affected:
Regulatory frameworks triggered:

ROOT CAUSE
[ ] User error
[ ] Policy gap
[ ] Tool malfunction
[ ] Vendor issue
[ ] Other: ___________

ACTIONS TAKEN
Containment:
Notifications sent:
Remediation:

FOLLOW-UP
Policy changes needed:
Training needed:
Review date:

Completed By:
Date Closed:
```

---

## Contact List

| Role | Name | Phone | Email |
|------|------|-------|-------|
| IT/Security Lead | | | |
| Compliance Officer | | | |
| Legal Counsel | | | |
| Department Head | | | |
| Vendor Support | | | |

---

*Review this plan quarterly. Test it annually with a tabletop exercise.*
