# AI Implementation Playbook

A step-by-step guide for going from "we should use AI" to a governed, productive rollout. Designed for organizations without a dedicated AI team.

---

## Before You Start

**This playbook assumes:**
- You have leadership buy-in (or at least permission) to explore AI
- You have someone willing to own the initiative (probably you, if you're reading this)
- You don't need to have everything figured out before starting

**This playbook does NOT require:**
- A dedicated AI budget (start with free/existing tools)
- A data science team
- Custom model development

---

## Phase 1: Foundation (Weeks 1-2)

### Goal: Understand where you are and set basic guardrails.

**Step 1: Audit current AI usage.**
You'd be surprised how many people are already using AI. Send a short survey or have conversations to find out:
- Who's using AI tools already? Which ones?
- What are they using them for?
- Has anyone put sensitive data into an AI tool?
- What problems are people trying to solve?

**Step 2: Classify your data.**
Use the [Data Classification Guide](../risk-assessment/data-classification.md) to map out what data exists in your organization and what level it falls into. You don't need to classify every file. Focus on the data types your teams work with daily.

**Step 3: Draft your acceptable use policy.**
Use the [Acceptable Use Policy template](../templates/acceptable-use-policy.md) as your starting point. Customize it for your organization. Get legal and leadership to review it. Don't aim for perfection. Aim for "good enough to publish and iterate."

**Step 4: Pick your first approved tool.**
Choose one AI tool to start with. Evaluate it using the [Tool Evaluation Checklist](../templates/tool-evaluation-checklist.md). Pick something low-risk and high-value, like a writing assistant for internal communications.

**Deliverables:**
- [ ] Current state audit completed
- [ ] Data classification draft
- [ ] Acceptable use policy v1 (reviewed by legal)
- [ ] First tool evaluated and approved

---

## Phase 2: Pilot (Weeks 3-6)

### Goal: Test with a small group, learn what works.

**Step 5: Select a pilot group.**
Pick 5-15 people across 2-3 departments. Choose a mix of enthusiastic early adopters and skeptics. Both perspectives are valuable.

**Step 6: Train the pilot group.**
Use [Module 1 and Module 2](../briefings/staff-training-outline.md) from the training outline, then [Module 3](../briefings/staff-training-outline.md) for the specific tool. Keep it hands-on. Lectures don't work for tool adoption.

**Step 7: Set success criteria.**
Define what "working" looks like before the pilot starts. Examples:
- 80% of pilot users actively using the tool weekly
- At least 3 documented time-saving use cases
- Zero data classification violations
- Feedback survey score above 7/10

**Step 8: Collect feedback weekly.**
Quick check-ins. What's working? What's frustrating? What did the AI get wrong? What would they use it for if they could? Document everything.

**Step 9: Complete your risk assessment.**
With real usage data from the pilot, fill out the [Risk Matrix](../risk-assessment/risk-matrix.md). Real risks are easier to score than hypothetical ones.

**Deliverables:**
- [ ] Pilot group selected and trained
- [ ] Success criteria defined
- [ ] Weekly feedback collected
- [ ] Risk matrix completed with pilot data
- [ ] Pilot results report for leadership

---

## Phase 3: Rollout (Weeks 7-12)

### Goal: Expand to the broader organization with confidence.

**Step 10: Update your policy based on pilot learnings.**
The pilot will expose gaps. Fix them before going wider. Common updates include clearer data handling rules, additional approved use cases, and better prompting guidance.

**Step 11: Train all staff.**
Roll out [Modules 1 and 2](../briefings/staff-training-outline.md) to all staff. Schedule [Module 3](../briefings/staff-training-outline.md) for each department as they gain access.

**Step 12: Launch the tool organization-wide.**
Staged rollout is fine. Department by department works well. Don't try to train and launch everyone on the same day.

**Step 13: Start the weekly briefing cadence.**
Use the [Weekly Briefing Template](../briefings/weekly-briefing-template.md) to keep leadership informed. Consistency matters more than length.

**Step 14: Set up your incident response process.**
Make sure the [Incident Response Plan](../templates/incident-response-plan.md) is finalized, contact info is current, and at least 2 people know how to execute it.

**Deliverables:**
- [ ] Updated acceptable use policy v2
- [ ] Organization-wide training completed
- [ ] Tool rolled out to all applicable staff
- [ ] Weekly briefing cadence started
- [ ] Incident response plan finalized and tested

---

## Phase 4: Mature (Ongoing)

### Goal: Build sustainable governance that grows with your AI usage.

**Step 15: Evaluate additional tools.**
As requests come in, use the [Tool Evaluation Checklist](../templates/tool-evaluation-checklist.md) and [Vendor Assessment](../templates/vendor-ai-assessment.md) to vet them systematically.

**Step 16: Form an AI committee (when ready).**
Once you have 3+ approved tools or significant AI-dependent workflows, stand up a formal oversight group. See [Building an AI Committee](building-ai-committee.md).

**Step 17: Conduct quarterly risk reviews.**
Update the risk matrix quarterly. New tools, new use cases, and new regulations all change your risk profile.

**Step 18: Review compliance mapping.**
Check the [Compliance Mapping](../risk-assessment/compliance-mapping.md) against your actual controls. Identify and close gaps.

**Step 19: Measure and report impact.**
Track and report on AI's actual impact: time saved, quality improved, costs reduced. Leadership needs to see ROI to keep supporting the initiative.

**Ongoing:**
- [ ] Quarterly risk review
- [ ] Annual policy refresh
- [ ] Annual training refresher for all staff
- [ ] Tool re-evaluation annually or at major vendor updates
- [ ] Compliance mapping review before audits

---

## Common Mistakes to Avoid

**Starting too big.** You don't need an enterprise AI platform on day one. Start with one tool, one department, one use case.

**Writing policy in isolation.** If the people using AI don't help shape the policy, they'll ignore it.

**Ignoring shadow AI.** If your approval process takes 3 months, people will use ChatGPT on their phones. Make it easy to get tools approved.

**Treating governance as one-and-done.** AI changes fast. Your governance needs to keep pace.

**Focusing on tools instead of problems.** "We need AI" is not a strategy. "We need to cut invoice processing time by 50%" is.

---

*Timelines are estimates. Adjust based on your organization's size, complexity, and regulatory environment.*
