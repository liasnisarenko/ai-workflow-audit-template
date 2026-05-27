# AI Workflow Audit Template

A reusable template for auditing a small business or creative agency's operations and recommending three high-leverage AI workflows the team can build in the next 30 days.

This is the actual template I use in my paid AI Workflow Audit engagements ($200, 60-minute call, one-page deliverable within 48 hours). The version in this repo is sanitized for public use.

---

## Who this is for

The template is built for AI Ops practitioners doing one of two things:

1. **Running paid audits** for SMB or creative-agency clients. Use the intake form to scope the call, the rubric to score opportunities during the call, and the deliverable template to write up findings within 48 hours.
2. **Auditing your own operations** before designing your AI stack. Run the audit on yourself. The scoring rubric is the same.

---

## What's in the repo

| File | What it's for |
|------|---------------|
| [`intake-form.md`](intake-form.md) | The pre-call form I send clients before the audit. ~10 questions. |
| [`scoring-rubric.md`](scoring-rubric.md) | The scoring rubric for evaluating workflow opportunities during the call (impact / effort / risk / confidence). |
| [`deliverable-template.md`](deliverable-template.md) | The one-page deliverable template, filled out from the call notes. |
| [`example-output.md`](example-output.md) | A fully redacted example output showing what a finished audit looks like. |

---

## How the audit works

### Before the call (15 min on the client's side)

Client fills out the intake form. The form is short (10 questions) and forces them to surface their biggest workflow pain point before we get on the call. The pre-work itself often reveals the answer.

### The call (60 min)

I run through the workflow inventory: what tools the business uses, what runs daily, what runs weekly, where the bottlenecks are, where the human is doing work an AI could do safely. I take notes against the scoring rubric in real-time.

By minute 45 I have a shortlist of candidate workflows. The last 15 minutes is pressure-testing the top 3: confidence the team can actually build it in 30 days, the tools they'd need, what's in the way.

### The deliverable (within 48 hours)

A one-page write-up with:

- Three recommended workflows, ranked.
- For each: what it is, what it replaces, the tools needed, effort estimate, confidence rating.
- One paragraph on what to do first.
- One paragraph on what NOT to do (the workflow the client thinks they want but shouldn't build).

That last section is what most AI consultants miss. Telling a client what not to build is more valuable than telling them what to build.

---

## The scoring rubric

Every candidate workflow is scored on four axes:

1. **Impact** (1-5) - How much time, money, or quality does this save / improve?
2. **Effort** (1-5, inverse) - How hard is this to build? 1 = days, 5 = a single working session.
3. **Risk** (1-5, inverse) - What's the blast radius if it misfires? 5 = drafts only, 1 = touches money or customer-facing surfaces.
4. **Confidence** (1-5) - How confident am I that this team specifically can build and own it?

Top 3 = highest sum across the four axes, with Confidence acting as a kill criterion (anything scoring 1-2 on Confidence drops out regardless of the other scores).

---

## Why this template exists

Three reasons.

**One.** AI consulting is full of hand-wavy "we'll transform your business with AI" pitches. This template is the opposite - a structured one-hour engagement that produces a concrete one-page plan the team can either execute on or hand off to someone who can.

**Two.** The audit is a real productized service, not a sales call dressed up as an audit. It's priced low enough to be a no-brainer for SMBs ($200), short enough to fit a busy operator's calendar (60 minutes), and concrete enough that the deliverable is useful even if they never engage me again.

**Three.** Open-sourcing the template is a credibility signal. Anyone considering hiring me can read exactly what they'd get. That's worth more to my pipeline than keeping the template private.

---

## License

MIT. Run audits with this template. Charge what makes sense in your market. If you adapt it, I'd love to hear what you changed.

---

*Maintained by [Lia Snisarenko](https://github.com/liasnisarenko). AI Workflow Operator based in Los Angeles. Available for AI Workflow Audits at [audit.snisarenkogallery.com](https://audit.snisarenkogallery.com).*
