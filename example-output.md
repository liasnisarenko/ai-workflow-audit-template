# Example output: redacted audit deliverable

A fully filled-out example of the deliverable, redacted for client privacy. Shows what a real audit produces.

---

# AI Workflow Audit: [Creative Agency, ~12 people]

Prepared by Lia Snisarenko - May 2026
Audit call: May 14, 2026, 2 PM PT
Attendees: [Founder], [Operations Lead] · Lia Snisarenko

---

## What we covered

A 12-person creative agency producing brand and content work for ~30 active clients. Current stack centers on Notion (project tracker), Slack, Google Workspace, Loom, and a mix of platform-specific tools per client (Meta Ads, Google Ads, Klaviyo, Shopify). Biggest stated pain: weekly client reporting takes the operations lead 6-8 hours every Friday and quality is uneven across reports.

---

## Three workflows to build in the next 30 days

### 1. AI-drafted weekly client reports

**What it is.** A scheduled Claude workflow that pulls last-week data from each client's Meta Ads, Google Ads, and Klaviyo accounts, drafts a section of the client's weekly report (numbers, deltas, commentary), and deposits a draft Google Doc into the right client folder by Thursday at 6 PM.

**What it replaces.** The 6-8 hour Friday session of manually pulling numbers, formatting tables, and writing commentary for ~30 clients. The Ops Lead reviews, edits, and sends rather than starting from blank pages.

**Tools needed.** Claude (already have via team subscription), MCP connectors for Meta Ads, Google Ads, Klaviyo (set up once per client), Google Drive (already connected), a scheduled task trigger.

**Effort estimate.** 2 working sessions to set up the prompt, MCP connections, and a pilot run with 3 clients. Then a phased rollout: 5 clients per week until all 30 are running.

**Confidence rating.** High. Team is already AI-fluent. Ops Lead is the right owner.

**Why this is #1.** Highest Impact in the shortlist with Effort low enough that you can ship the pilot in your next two working sessions and Confidence high enough that the Ops Lead can own it without my help.

---

### 2. New-client intake automation

**What it is.** A workflow that converts a completed new-client intake form (already in Notion) into a starter project structure: project page, milestone tasks, kickoff-call agenda, brand-questionnaire link, contract draft.

**What it replaces.** The 90-minute "set up the new client" ritual that happens 2-3 times a month, plus the inconsistency between projects depending on who set them up.

**Tools needed.** Notion (already have), Claude, a saved project template.

**Effort estimate.** 1 working session to build the prompt and template. A second session to refine after the first new-client run.

**Confidence rating.** High.

---

### 3. Inbound proposal-request triage

**What it is.** Inbound proposal requests (currently arriving via a website contact form into Slack) get pre-processed by Claude: enriched with public information about the prospect, scored against the agency's ideal-client profile, drafted-but-not-sent acknowledgment reply, queued for the founder's review.

**What it replaces.** 30-60 minutes per inbound request the founder spends doing initial research, deciding whether to engage, and drafting the response. Currently ~6-10 requests/week.

**Tools needed.** Claude, MCP connector for the website form provider, Slack (already connected).

**Effort estimate.** 1-2 working sessions.

**Confidence rating.** Medium. Team hasn't done a workflow against inbound public-facing data before. Will benefit from a coaching call after the first 2 weeks of use.

---

## Where to start

Start with the new-client intake automation (workflow #2), not the weekly client reports (workflow #1). Counterintuitive, but here's why: the intake automation is contained, low-risk, and can ship cleanly in a single working session. The team will see a complete win in week one. The client reports are higher-Impact but require more setup time and touch more accounts - if they're the first build and they stall, the whole effort loses momentum. Build #2 first to seed confidence, then go after #1, then #3.

---

## What NOT to build

Do not build the AI chatbot on your marketing site. You raised this on the call and I want to address it directly. Confidence is low - no one on your team has owned a live customer-facing agent before, and the failure modes for an agency chatbot (wrong information about service scope, mis-quoted pricing, awkward handoffs to humans) damage exactly the perception you sell. The proposal-request triage workflow (#3) gets you most of the inbound-handling benefit without exposing a live agent to the public. Revisit the chatbot question in 6 months after you've shipped the three above and have the operational muscle for live-agent work.

---

## Open questions

- Who would own the weekly client report workflow if [Ops Lead] is out for a week? Worth assigning a backup before you ship.
- Are any of your clients in regulated industries (financial services, healthcare) where the auto-drafted report needs explicit human-in-the-loop language?
- What's your current backup for the Notion CRM? Anything we build on top of it should assume an export path in case Notion changes pricing or features.

---

## If you want help building this

I'm available for a follow-on engagement to build the three workflows above. Scope and pricing in a separate proposal if you want one. If the team would rather build them in-house and just have me on call for review sessions, that works too - billed by the session.

---

*This audit is a snapshot in time. AI capabilities and your business both change. If you'd like a revisit in 90 days to score progress, the same $200 rate applies.*
