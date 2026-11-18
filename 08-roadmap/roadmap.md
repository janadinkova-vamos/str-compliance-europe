# The Roadmap · STR Europe

> Module 8 · Outcome-based roadmap. Now / Next / Later, with the outcome each stage must prove and the gate that unlocks the next one. No fixed feature dates: each stage earns the next.

## North Star

**Compliant active listings:** listings that, in the month, had a valid registration on every channel, submitted all guest-registry entries on time, and had no unresolved compliance alert. Defined in [`07-validation/validation-plan.md`](../07-validation/validation-plan.md).

_____

## Roadmap at a glance

| | **NOW** · Q1 2027 | **NEXT** · Q2 2027 | **LATER** · H2 2027 |
|---|---|---|---|
| **Theme** | Prove the pain, ship the quick win | Test the bet | Expand and defend |
| **Outcome to prove** | Compliance is the #1 pain for Spain-based and non-resident hosts | Compliance visibility lifts the 30-day compliance-complete rate by ≥25% | Compliance becomes a retention moat across Iberia |
| **Key initiatives** | Host interviews · baseline measurement · prototype test · guest-registry automation beta | Compliance Hub MVP (5 regions) · A/B test from [`hypothesis.md`](../07-validation/hypothesis.md) | Portugal · GoodHost Score (private) · safe direct booking · destination radar · council pilot |
| **Leading metric** | Interview pain rank; registry-beta activation within 30 days | 30-day compliance-complete rate | Compliant active listings (North Star) |
| **Lagging metric** | Registry-related support tickets | 90-day churn of Spanish accounts | 12-month retention of Iberian accounts; revenue per listing |
| **Gate to move on** | Compliance ranks top 2 in ≥60% of interviews **and** registry beta ≥40% activation | Hypothesis decision: **scale / pivot / kill** at week 12 | Scale only where the Spain result holds |

_____

## NOW · Q1 2027 · Prove the pain, ship the quick win

**Why first:** the qualitative research shows compliance is the #1 pain in Spain but not for hosts in general ([`research/qualitative-reddit.md`](../research/qualitative-reddit.md)). We confirm it with real Spanish hosts before building the bigger bet.

| Initiative | What | Done when |
|---|---|---|
| **Discovery interviews** | 8–10 Spain-based hosts and managers, ≥3 non-resident owners | Pain ranking documented; persona confirmed or revised |
| **Baseline measurement** | Current compliance-complete rate of Spanish listings, using existing data | Week-0 baseline set; +25% target re-checked |
| **Prototype test** | Lovable prototype of the Compliance Hub ([`prototype/`](../prototype/lovable-prompt.md)), 5 moderated usability sessions | Hosts understand their status in under 30 seconds; top confusion points listed |
| **Guest-registry automation (beta)** | Collect guest data in the booking flow, auto-submit to SES.Hospedajes, keep proof | ≥40% of eligible hosts activate within 30 days |

**Not doing yet:** the full compliance layer, Portugal, any council-facing product.

_____

## NEXT · Q2 2027 · Test the bet

**Why now:** the registry beta builds the data pipes and trust that the Compliance Hub needs.

| Initiative | What | Done when |
|---|---|---|
| **Compliance Hub MVP** | Per-listing status (licence, channel sync, guest registry, building), alerts before a listing is at risk, guided fixes | Live for Andalucía, Comunidad Valenciana, Madrid, Canarias, Baleares |
| **Regional rules content** | Partner-verified rules per region, with timestamps and escalation to a professional | 5 regions covered, reviewed by a legal partner |
| **The A/B test** | Hypothesis from [`hypothesis.md`](../07-validation/hypothesis.md) | 12-week read: scale, pivot or kill |

**Decision gate (week 12):**
- **Scale** (≥ +25%, guardrail holds) → LATER.
- **Pivot** (+10% to +25%) → simplify to guest registry + alerts only, re-test.
- **Kill** (< +10%) → shift the roadmap to platform risk: safe direct booking and the evidence vault move to NOW.

_____

## LATER · H2 2027 · Expand and defend

Only if the bet is scaled. Ordered by dependency, not by date.

| Initiative | Depends on | Why |
|---|---|---|
| **Portugal** (AL licence lifecycle, SIBA reporting, municipal containment zones) | Compliance Hub architecture | Same problem, narrower scope: licence maintenance |
| **GoodHost Score (private)** | Compliance data + noise/complaint integrations | Turns compliance into a visible quality signal; foundation for council work ([`05-concept/`](../05-concept/goodhost-score.md)) |
| **Safe direct booking** (verified site, ID check, damage protection, evidence vault) | Compliance status on direct sites | The loudest host pain after compliance: platform dependence |
| **Destination radar** | Rules database + listing data | Supports growth outside saturated cities ([`06-expansion/`](../06-expansion/emerging-destinations.md)) |
| **Council pilot** (Castilla y León) | GoodHost Score + responsible-growth dashboard | Performance-based caps instead of blanket bans |

_____

## Risks that could reshape the roadmap

| Risk | Signal | Response |
|---|---|---|
| Spanish election outcome changes national rules | Coalition agreement (Dec 2026 – Jan 2027) | Regional rules stay; adjust content, not architecture (feature flags) |
| Interviews show compliance isn't #1 | NOW gate fails | Lead with platform risk: direct booking + evidence vault |
| Legal liability for wrong rules content | Any incorrect rule reported | Partner-verified content, timestamps, disclaimers, escalation path |
| Hosts see the Hub as surveillance | Low activation, negative feedback in tests | Frame as protection; never auto-unpublish; host stays in control |
