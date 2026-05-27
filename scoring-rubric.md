# Scoring rubric

Every workflow opportunity surfaced during the call is scored against four axes. Top 3 by total score (with Confidence as a kill criterion) make it into the deliverable.

The point of the rubric isn't precision. It's forcing the same four questions for every candidate so I don't anchor on whichever workflow sounded most exciting.

---

## The four axes

### 1. Impact (1-5, higher is better)

How much time, money, or quality does this workflow unlock?

| Score | Meaning |
|-------|---------|
| 5 | Saves 5+ hours/week OR unlocks a revenue line OR fixes a quality issue causing churn |
| 4 | Saves 2-5 hours/week OR materially improves a customer-facing output |
| 3 | Saves 1-2 hours/week OR removes a specific weekly friction point |
| 2 | Nice-to-have, not blocking |
| 1 | Cosmetic improvement only |

### 2. Effort (1-5, higher means easier)

How hard is this workflow to actually build and put into use?

| Score | Meaning |
|-------|---------|
| 5 | Single working session. Off-the-shelf prompts or templates. |
| 4 | Half-day. Some custom prompt engineering, no new tool setup. |
| 3 | 1-2 days. New tool or MCP connection required, but well-documented. |
| 2 | A week. Custom integration work, or significant change management. |
| 1 | Multi-week project. Engineering-grade work. |

### 3. Risk (1-5, higher means safer)

What's the blast radius if this workflow misfires?

| Score | Meaning |
|-------|---------|
| 5 | Drafts only. Output goes to a human before any customer or system sees it. |
| 4 | Internal-only impact (CRM update, internal report). Easily reversible. |
| 3 | Touches an internal communication channel (team Slack, internal email). |
| 2 | Touches a customer-facing surface but in a low-stakes way (scheduling, basic acknowledgments). |
| 1 | Touches money, identity, public publishing, or other irreversible / high-trust actions. |

### 4. Confidence (1-5, higher is better)

How confident am I that THIS specific team can build, own, and maintain this workflow?

| Score | Meaning |
|-------|---------|
| 5 | Team has the AI fluency, the time, and the technical comfort to ship this in 30 days. |
| 4 | Team has the fluency; will need light hand-holding on first build. |
| 3 | Team will need a coach for the first build but should own it after. |
| 2 | Team isn't ready - they'd build it but never use it. |
| 1 | Team isn't ready - they'd struggle to build it at all. |

---

## How the scores combine

**Total = Impact + Effort + Risk + Confidence** (max 20)

Sort candidates by total. Top 3 make the deliverable.

**Kill criterion:** Any workflow scoring 1 or 2 on Confidence drops out, regardless of total. If the team can't own it, recommending it sets everyone up for failure.

---

## Worked example

A creative agency wants to automate their weekly client report generation. Currently the PM spends 4 hours every Friday pulling data from 5 platforms (Meta Ads, Google Ads, GA4, the CRM, the project tracker) into a Google Doc, copying screenshots, adding commentary.

Scoring:

- **Impact: 5** - 4 hours/week recovered = 16 hours/month = a full team-member day every month. Material.
- **Effort: 3** - Will need MCP or API connections to Meta and Google Ads. Not trivial, not hard.
- **Risk: 5** - Output is a draft doc the PM reviews before sending to the client. No customer-facing automation. Highest safety rating.
- **Confidence: 4** - Team has used Claude for content work. Will need light coaching on the first build but will own it.

**Total: 17/20. Top 3 candidate.**

Compare against a candidate the client raised first: "We want a chatbot on our website that books calls." Scoring:

- **Impact: 3** - Replaces ~2 inbound chats per week, modest time savings.
- **Effort: 1** - Multi-week build. Real engineering on the chatbot UX, the booking integration, error handling, escalation paths.
- **Risk: 2** - Live customer-facing surface. Mis-bookings, wrong-info-given, escalation failures.
- **Confidence: 2** - Team has no experience with chatbot tooling or maintaining live agents.

**Total: 8/20. Kill criterion triggered on Confidence. Drops out.**

The chatbot is the workflow the client thought they wanted. The weekly report is the workflow they actually need. This is what the audit is for.

---

## What I write down during the call

A grid in my notebook (or Notion). Columns: Workflow | Impact | Effort | Risk | Confidence | Total | Notes.

By minute 45 of the call I have 8-12 candidates scored. The last 15 minutes is pressure-testing the top 3 on Confidence ("walk me through who would own this and what their week looks like after we ship it"). That conversation is where Confidence scores get refined, and sometimes a top-scoring workflow drops below a runner-up.
