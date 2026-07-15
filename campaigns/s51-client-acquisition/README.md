# S51 Outbound Client-Acquisition Campaign

Evidence-based outreach plan built from the July 2026 prospect list, targeting S51's ICP (B2B SaaS $5-30M and Data & AI services). Prepared 15 July 2026.

## Headline finding

The source prospect list is a stale export (circa 2017-2018): **80% of the 88 unique people have changed employers and 77% of the listed emails are likely dead.** The work re-identifies where each person is *now* and grades ICP fit against their current company. The addressable set is ~14-18 in-ICP leads, not 88, so this list is treated as a proof batch and the 20-client goal is shown to require fresh sourcing on top (see Phase 2, "path-to-20 math").

## Contents

```
inputs/                         Source files (prospect CSV + S51 knowledge base)
phase1-linkedin-assessment/     LinkedIn presence & activity assessment (all 88)
phase2-outreach-strategy/       Personalized sequences for the 14 priority leads
```

### Phase 1 — LinkedIn presence & activity assessment
- `PHASE1_LinkedIn_Assessment.md` - full report: sortable 88-row table, summary dashboard (activity categories, channels, verification, ICP fit), strongest LinkedIn-first opportunities, skip-list, data-quality issues, cross-segment trends.
- `S51_Phase1_Assessment_Ranked.csv` - priority-ranked assessment with per-prospect reasoning, current role, company status, email reachability, and source URLs.
- `S51_Phase1_Assessment_ByID.csv` - same data in original CSV order.

### Phase 2 — Outreach strategy & email drafts
- `PHASE2_Outreach_Strategy.md` - prioritization framework, path-to-20 math, tracking plan, and 14 complete outreach packages (personalization brief + LinkedIn connection/follow-up + QC-passed 5-email sequence with A/B subjects and preview text). Plus a Tier C watchlist of 6 early-stage founders to nurture.
- `S51_Phase2_Sequence_Tracker.csv` - one row per touch (84 touches across 14 leads) for CRM import: tier, current company, channel, pain theme, send day, subjects, and copy.
- `S51_Phase2_Sequences.json` - structured sequence data for programmatic use.

## Method & guardrails

- **Public information only.** No profiles, dates, activity, or facts were fabricated. Unverifiable items are marked "Not verified" / "Not assessable publicly." LinkedIn live profiles are not machine-readable, so activity reflects indexed public traces; the priority profiles should have their last-post date confirmed manually (logged in) before the Day-0 touch.
- **Every sequence targets the person's current company**, not the stale CSV row, and cites only S51's own case studies (Skills Workflow, OneMagnify, LatentView, Arloesi).
- **QC-cleared.** All 14 sequences passed a fact-verification and anti-AI voice audit: within word-count ceilings, zero em dashes, no banned vocabulary, no calendar-link CTAs.
- **Nothing has been sent.** These are drafts for review and approval.
