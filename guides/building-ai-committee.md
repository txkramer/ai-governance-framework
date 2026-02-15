# Building an AI Committee

How to stand up a cross-functional AI oversight group that actually works, without creating another meeting nobody wants to attend.

---

## When You Need One

You probably don't need a formal committee on day one. But you do need one when:

- You have 3+ approved AI tools in active use
- Multiple departments are using AI for different purposes
- You're making decisions that affect compliance or patient/student safety
- Leadership is asking "who's in charge of AI?"
- Vendor evaluations are backing up because one person is doing all of them

If none of these are true yet, keep it informal. One person owning AI governance with a dotted line to leadership is enough to start.

---

## Committee Structure

### Keep It Small

5-7 people maximum. Larger committees become discussion groups that don't decide anything.

### Recommended Roles

| Role | Why They're There | Time Commitment |
|------|------------------|-----------------|
| **AI Lead / IT Representative** | Technical knowledge, tool evaluation, implementation | 3-5 hrs/month |
| **Compliance / Legal** | Regulatory guidance, policy review, risk assessment | 2-3 hrs/month |
| **Clinical / Operations Representative** | Frontline perspective, use case validation | 2-3 hrs/month |
| **Department Manager** | Adoption champion, staff feedback, business case | 2-3 hrs/month |
| **Executive Sponsor** | Decision authority, budget, organizational alignment | 1-2 hrs/month |
| **Data / Privacy Officer** (if you have one) | Data governance, classification oversight | 2-3 hrs/month |

### Optional Additions

- **HR Representative** if AI is being used in hiring or performance management
- **Finance** if AI spending needs budget oversight
- **External advisor** for organizations without in-house AI expertise

---

## Charter Template

Every committee needs a one-page charter. Here's what to include.

```
AI GOVERNANCE COMMITTEE CHARTER

Purpose:
Oversee the responsible adoption and use of AI tools across [Organization],
ensuring alignment with organizational goals, regulatory requirements, and
ethical standards.

Scope:
- Approve or deny new AI tools for organizational use
- Maintain and update the AI Acceptable Use Policy
- Conduct quarterly risk assessments
- Review AI-related incidents and recommend corrective actions
- Advise leadership on AI strategy and investment

Authority:
The committee has decision-making authority for:
- Tool approval/denial (within existing budget)
- Policy updates (with executive sponsor sign-off)
- Training requirements
- Incident response escalation

The committee recommends (but does not decide):
- Budget allocation for AI tools
- Organizational AI strategy
- Staffing changes related to AI

Meeting Cadence: Monthly, 60 minutes
Chair: [Name]
Executive Sponsor: [Name]
Effective Date: [Date]
Review Date: [Annual review date]
```

---

## Meeting Structure

Monthly meetings, 60 minutes. Stick to this format to keep things productive.

| Time | Topic | Owner |
|------|-------|-------|
| 0:00-0:05 | Quick wins and updates since last meeting | AI Lead |
| 0:05-0:20 | Tool evaluations pending decision | AI Lead |
| 0:20-0:35 | Risk review and incident discussion | Compliance |
| 0:35-0:50 | New requests, use cases, or policy questions | All |
| 0:50-0:55 | Decisions and action items | Chair |
| 0:55-1:00 | Next meeting agenda items | Chair |

### Meeting Rules

- **Come prepared.** Tool evaluations and risk assessments should be reviewed before the meeting, not during it.
- **Decide or defer.** Every agenda item ends with a decision or a clear owner and deadline.
- **No spectators.** If someone doesn't have a role in the discussion, they don't need to attend. Send them the notes.
- **Document everything.** Decisions, rationale, and action items go in shared meeting notes. This is your audit trail.

---

## Decision Framework

When the committee needs to make a call, use this framework.

### For Tool Approvals

1. Has the [Tool Evaluation Checklist](../templates/tool-evaluation-checklist.md) been completed? If no, send it back.
2. Does the tool score above the approval threshold? If no, what remediation is the vendor willing to do?
3. Are there any automatic disqualifiers? If yes, deny.
4. Does compliance/legal have concerns? If yes, address before approving.
5. Is there budget? If no, escalate to executive sponsor.
6. Vote: Approve / Conditional Approve / Deny. Simple majority wins, but compliance/legal has veto on regulatory items.

### For Policy Changes

1. What triggered the change? (incident, new regulation, new tool, feedback)
2. Who does the change affect?
3. Is the change adding a restriction or removing one?
4. Has legal reviewed it?
5. What's the communication plan for affected staff?
6. Vote: Approve / Revise / Defer.

### For Incidents

1. Review the [Incident Report](../templates/incident-response-plan.md).
2. Was the response adequate? If not, what needs to change?
3. Does the policy need updating?
4. Does training need to be revised or repeated?
5. Are there systemic issues to address?
6. Assign action items with owners and deadlines.

---

## Common Pitfalls

**The committee that never meets.** Schedule recurring meetings and protect the time. Cancel if there's truly nothing to discuss, but that should be rare.

**Death by consensus.** Not every decision needs unanimous agreement. Define voting rules in the charter and stick to them.

**Rubber-stamping.** If the committee approves everything without scrutiny, it's not governing anything. The committee's value comes from the tools and practices it says no to, not just the ones it approves.

**Scope creep.** The committee governs AI tools and policy. It doesn't manage IT infrastructure, negotiate vendor contracts, or build AI models. Stay in your lane.

**Missing the frontline voice.** If the people actually using AI tools aren't represented, the committee will make disconnected decisions. Always have at least one member from operations.

---

## Measuring Committee Effectiveness

| Metric | Target |
|--------|--------|
| Average time from tool request to decision | Under 30 days |
| Percentage of meetings held as scheduled | 90%+ |
| Open action items older than 60 days | Zero |
| AI-related incidents per quarter | Trending down |
| Staff satisfaction with AI governance (annual survey) | 7/10+ |

---

*Review the charter annually. Adjust membership as organizational needs change. The committee should evolve with your AI maturity.*
