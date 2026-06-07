# PRD template

This is the structure I use for product requirements documents. It's written for an engineering and tech lead audience — people who need enough context to build confidently, ask the right questions early, and make good local decisions without coming back to me constantly.

I write these in Jira (as epics with linked stories), but the structure works in any format. The sections marked **required** go in every PRD. The rest are included when relevant.

---

## How to use this template

Copy the structure below. Fill in the required sections before sharing with the team. Add optional sections as the initiative warrants. Delete guidance notes (the *italicised* prompts) before you publish.

A PRD is ready to share when an engineer who knows nothing about this initiative can read it and understand: what we're building, why it matters, what done looks like, and what they should ask me about before starting.

---

## PRD structure

---

### 1. Title and status `required`

```
Title:
Status: Draft / In Review / Approved / In Delivery / Done
Author:
Last updated:
Jira epic:
```

---

### 2. Problem statement `required`

*One to three sentences. What is broken, missing, or inefficient — and for whom? Avoid solution language here. If you find yourself writing "we need to build...", stop and reframe.*

**The problem:**
[What is happening today that shouldn't be, or what isn't happening that should be?]

**Who is affected:**
[Be specific — "portfolio managers running end-of-day reconciliation" is more useful than "users".]

**Evidence:**
[What tells us this is real? Data, support tickets, direct observation, stakeholder feedback. One or two data points is enough.]

---

### 3. Why now `required`

*Why is this the right time to solve this? What changes if we don't? This section is often skipped and shouldn't be — it's what makes prioritisation defensible.*

[Regulatory deadline / business impact / dependency unlocked / competitive pressure / tech debt threshold crossed]

---

### 4. Goals `required`

*What does success look like? Use measurable outcomes where possible. Tie to OKRs if applicable.*

| Goal | Metric | Target | Timeframe |
|---|---|---|---|
| [e.g. Reduce manual reconciliation time] | [e.g. Avg. time per reconciliation run] | [e.g. < 10 mins] | [e.g. 6 weeks post-launch] |

---

### 5. Non-goals `required`

*What are we explicitly not solving with this initiative? This is as important as the goals — it prevents scope creep and surfaces misaligned expectations early.*

- We are not...
- We are not...
- Out of scope for this phase:

---

### 6. Proposed solution `required`

*Describe what we're building. Be specific enough that an engineer can estimate it, but don't design the implementation — that's their job. Include wireframes, flow diagrams, or data models if they add clarity.*

**Overview:**
[What is the feature or change, in plain language?]

**User flow:**
[Step-by-step description of how a user interacts with this. Numbered list works well here.]

**Key decisions made:**
[What did we consider and decide before writing this? Helps engineers understand the constraints without relitigating closed questions.]

**Open questions:**
[What is still unresolved? Assign an owner and a date for each.]

| Question | Owner | Due |
|---|---|---|
| | | |

---

### 7. Requirements `required`

*Functional requirements should be written as user stories or acceptance criteria — not feature lists. Each requirement should be independently testable.*

#### Functional requirements

- [ ] As a [user], I can [action] so that [outcome]
- [ ] As a [user], I can [action] so that [outcome]

#### Non-functional requirements

- [ ] Performance: [e.g. page load < 2s under normal load]
- [ ] Security / data: [e.g. all data handled in line with firm data classification policy]
- [ ] Audit / logging: [e.g. all user actions on this feature are logged with timestamp and user ID]

---

### 8. Compliance and risk `required for regulated features`

*In an investment management context, this section often determines whether something ships on time. Raise these early — not after engineering has started.*

| Area | Consideration | Status | Owner |
|---|---|---|---|
| Regulatory | [e.g. Does this touch reportable data?] | [Pending / Cleared / N/A] | |
| Legal | [e.g. Does this change data retention obligations?] | | |
| Risk | [e.g. What happens if this fails silently?] | | |
| InfoSec | [e.g. New data access patterns — reviewed?] | | |

---

### 9. Dependencies `optional`

*What needs to exist or be completed before this can ship? Upstream systems, other teams, third-party vendors, data availability.*

| Dependency | Owner | Status | Risk if delayed |
|---|---|---|---|
| | | | |

---

### 10. Rollout plan `optional`

*How does this reach users? Include phasing, feature flags, comms plan, and who needs to know before it goes live.*

- Rollout approach: [Big bang / phased / feature flagged / pilot group]
- Internal comms: [Who needs to know before launch, and when?]
- User comms: [Do end users need training, documentation, or a heads-up?]
- Rollback plan: [What do we do if something goes wrong in the first 48 hours?]

---

### 11. Success review `optional`

*When and how will we assess whether this worked? Close the loop — a PRD without a review is a hypothesis that never gets tested.*

- Review date: [Suggested: 4–6 weeks post-launch]
- Who reviews: [PM + tech lead + relevant stakeholder]
- What we'll look at: [Metrics from section 4, plus any qualitative signals]

---

## A note on length

A PRD should be as long as it needs to be and no longer. For a small feature, sections 1–7 might fit on a single page. For a complex, cross-functional initiative, section 8 alone might be substantial.

The test isn't length — it's whether an engineer who reads it can build the right thing, and whether a compliance reviewer can assess it without a meeting. If either of those is true, it's long enough.

