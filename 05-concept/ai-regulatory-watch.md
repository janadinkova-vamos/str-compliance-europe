# The Concept · AI Regulatory Watch (human-approved)

> The engine behind two Compliance Hub features in the [roadmap](../08-roadmap/roadmap.md): **Rule-change watch** and **Regional rules content**. An AI agent monitors official bulletins, a legal reviewer approves every item, and each host only sees what changes for their own listings.

_____

## Why

Hosts find out they are non-compliant only after the damage is done ([hypothesis](../07-validation/hypothesis.md)). A licensed owner in A Coruña lost his licence to a retroactive council rule that nobody warned him about ([small-owner voices](../research/small-owners.md)). Watching drafts and new rules is the earliest point at which anyone can warn him.

_____

## How it works

```
Official sources ──► AI agent ──► Human review ──► Rules database ──► Personalised alert
BOE, regional         detects,      legal partner     versioned, dated,   only for listings
bulletins, city       classifies,   approves, edits   by region, city,    the rule applies to,
ordinances            summarises,   or rejects        legal category      with action + deadline
                      maps to rules (target: 48 h)
```

1. **Monitor.** The agent reads the official bulletins every day: the BOE, the regional bulletins of the MVP regions, and the bulletins and ordinances of their main cities.
2. **Detect and classify.** It flags items about tourist housing, seasonal rentals, guest registry, building communities and tourism taxes. It labels each one **In force** or **Being drafted** (draft, public consultation), with the region, city and legal categories affected.
3. **Draft.** It writes a plain-language summary: what changes, who it affects, what to do, by when. It always links the source.
4. **Human review.** A legal partner or a small legal-ops team approves, edits or rejects each item. Nothing reaches a host without approval. The AI groups and ranks items so reviewers only judge what matters.
5. **Match.** Approved rules go into a versioned rules database. Each listing is matched by region, city, legal category (tourist home, tourist apartment, seasonal) and whether it's in a residential building.
6. **Alert.** The host gets one alert per change that applies to them, labelled with its status ("In force: action needed" or "Being drafted: heads-up"), the deadline, the source and "Verified by [partner], [date]".

_____

## Help, not burden: design rules

| Rule | Why |
|---|---|
| Only what applies to **this listing** | A generic checklist for everyone is the burden version |
| Only changes that need an action; a monthly "nothing changed for you" summary otherwise | Reassures without nagging |
| Plain language: what changes, what to do, by when | Older and non-digital hosts must understand it in one read |
| Onboarding checklist once, then only the differences | Must never slow the first listing (guardrail: time to first published listing) |
| Drafts and rules in force always labelled apart | A draft is a heads-up, not an obligation |
| Source, date and reviewer on every item | Trust, and a clear line between information and legal advice |
| Never auto-unpublish | The host stays in control |

_____

## Coverage and limits

| Layer | Covered by the agent? |
|---|---|
| EU | Yes (Official Journal), low volume |
| State | Yes (BOE) |
| Region | Yes, starting with the 5 MVP regions |
| City | Partly: main cities of the MVP regions first. Thousands of councils publish in provincial bulletins and local ordinances, the hardest part to scale |
| Building community | **No.** Neighbours' votes are never published; the host uploads the minutes to the evidence vault |

_____

## Metrics

| Metric | Target / use |
|---|---|
| **Precision:** % of AI-flagged items approved as relevant | > 80% before expanding coverage |
| **Review cost:** reviewer minutes per approved alert | Falls as the agent learns; decides team size |
| **Review time:** source published → alert sent | ≤ 48 hours |
| **Usefulness:** % of alerts acted on before the deadline | Leading indicator for the compliance-complete rate |
| **Burden guardrails:** alerts per host per month (capped), alert opt-out rate, time to first published listing | Must not worsen |

_____

## Risks

| Risk | Mitigation |
|---|---|
| AI summary misstates a rule | Human approval on every item; source always linked |
| Liability for legal content | Information, not advice; verified-by label; escalation to a professional |
| Reviewer bottleneck | Legal partner with a turnaround commitment; AI grouping and ranking |
| City coverage gaps | Start with main cities; say clearly which cities are covered |
| Alert fatigue | Per-listing matching, caps, monthly digest |

_____

## Validation

Two questions in the host survey test demand before building: how useful a warning before a rule changes in their area would be, and how hosts find out about changes today (including "Normalmente me entero tarde"). See [`07-validation`](../07-validation/validation-plan.md).
