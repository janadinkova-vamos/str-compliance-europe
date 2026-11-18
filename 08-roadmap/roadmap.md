# The Roadmap · STR Europe

> Module 8 · Outcome-based roadmap. Now / Next / Later, with the outcome each stage must prove and the gate that unlocks the next one. No fixed feature dates: each stage earns the next.

**Start here:** [`what-comes-next.md`](what-comes-next.md) explains where this case stops, what the first survey challenged, and the four validation gates that make up NOW.

## North Star

**Compliant active listings:** listings that, in the month, had a valid registration on every channel, submitted all guest-registry entries on time, and had no unresolved compliance alert. Defined in [`07-validation/validation-plan.md`](../07-validation/validation-plan.md).

_____

## Roadmap at a glance

| | **NOW** · Q1 2027 | **NEXT** · Q2 2027 | **LATER** · H2 2027 |
|---|---|---|---|
| **Theme** | Prove the pain, ship the quick win | Test the bet | Expand and defend |
| **Outcome to prove** | The pain is felt, predicts churn and has a real Aha ([4 gates](what-comes-next.md)) | Compliance visibility lifts the 30-day compliance-complete rate by ≥25% | Compliance becomes a retention moat across Iberia |
| **Key initiatives** | Host interviews · baseline measurement · prototype test · guest-registry partner activation | Compliance Hub MVP (5 regions) · A/B test from [`hypothesis.md`](../07-validation/hypothesis.md) | Portugal · GoodHost Score (private) · safe direct booking · destination radar · council pilot |
| **Leading metric** | Interview pain rank; registry-beta activation within 30 days | 30-day compliance-complete rate | Compliant active listings (North Star) |
| **Lagging metric** | Registry-related support tickets | 90-day churn of Spanish accounts | 12-month retention of Iberian accounts; revenue per listing |
| **Gate to move on** | Validation gates 1–3 passed ([`what-comes-next`](what-comes-next.md)) **and** registry beta ≥40% partner-registry activation | Hypothesis decision: **scale / pivot / kill** at week 12 | Scale only where the Spain result holds |

_____

## NOW · Q1 2027 · Prove the pain, ship the quick win

**Why first:** the qualitative research shows compliance is the #1 pain in Spain but not for hosts in general ([`research/qualitative-reddit.md`](../research/qualitative-reddit.md)), and the first host survey suggests it is a latent rather than a felt pain. We validate it in four gates before building the bigger bet: see [`what-comes-next.md`](what-comes-next.md).

| Initiative | What | Done when |
|---|---|---|
| **Discovery interviews** | 8–10 Spain-based hosts and managers, ≥3 non-resident owners. Already done: 2 operator interviews and 5 small-owner voices from the press ([`research/`](../research/small-owners.md)) | Pain ranking documented; persona confirmed or revised |
| **Baseline measurement** | Current compliance-complete rate of Spanish listings, using existing data | Week-0 baseline set; +25% target re-checked |
| **Prototype test** | Lovable prototype of the Compliance Hub ([`prototype/`](../prototype/lovable-prompt.md)), 5 moderated usability sessions | Hosts understand their status in under 30 seconds; top confusion points listed |
| **Guest-registry partner activation** | Hospitable already integrates partners such as Chekin for SES.Hospedajes filing ([`market-reports`](../research/market-reports.md)). Promote the integration to Spanish hosts and show submission proof per listing; no in-house build | ≥40% of eligible Spanish hosts activate within 30 days |

**Not doing yet:** the full compliance layer, Portugal, any council-facing product.

_____

## NEXT · Q2 2027 · Test the bet

**Why now:** the registry beta builds the data pipes and trust that the Compliance Hub needs.

| Initiative | What | Done when |
|---|---|---|
| **Compliance Hub MVP** | Per-listing status (licence, channel sync, guest registry via partners, building), alerts before a listing is at risk, guided fixes |
| **Listing check** | Checks each channel's ad for the licence number (present and valid), the private/professional host flag and accurate details: the causes behind the 65,000 Airbnb listings ordered removed ([`market-reports`](../research/market-reports.md)) | Every MVP listing checked on every connected channel | Live for Andalucía, Comunidad Valenciana, Madrid, Canarias, Baleares |
| **Community status** | The fourth layer of permission: community approval, limit, surcharge (up to 20%) or ban, with the date and minutes; a dispute tracker (formal demand → meeting → lawsuit) and challenge-deadline reminders ([`legal-communities`](../research/legal-communities.md)) | Every MVP listing in a residential building has a community status |
| **Rule-change watch (AI regulatory watch)** | An AI agent monitors the BOE, regional bulletins and main-city ordinances daily, labels items *in force* or *being drafted*, and drafts plain-language summaries; a legal reviewer approves every item before hosts see it; alerts reach only the listings each rule applies to ([`ai-regulatory-watch`](../05-concept/ai-regulatory-watch.md), [`small-owners`](../research/small-owners.md)) | Precision > 80%, source-to-alert ≤ 48 h, for the 5 MVP regions and their main cities |
| **Legal category per unit** | Each unit tagged as tourist home, tourist apartment, seasonal or work stay, with the regional stay thresholds that move a booking between regimes; bookings that change regime are flagged ([`interviews`](../research/interviews.md)) | Thresholds verified for the 5 MVP regions |
| **Dated evidence vault** | Licences, applications (with the date each was filed), community minutes and certificates stored with timestamps, including proof of registration before April 2025 for the transitional rule, exportable for an inspection or a dispute | Every MVP listing has its documents and dates on file |
| **Cost view per listing** | 10% VAT (from 1 Dec 2026), community surcharge (up to 20%) and IBI surcharge (up to 100–150% in stressed areas) shown against revenue; VAT-ready invoicing through partners | A host can see whether each legal listing still pays off |
| **Regional rules content** | Partner-verified rules per region, fed by the AI regulatory watch, versioned and timestamped, with escalation to a professional | 5 regions covered, reviewed by a legal partner |
| **The A/B test** | Hypothesis from [`hypothesis.md`](../07-validation/hypothesis.md) | 12-week read: scale, pivot or kill |

**Decision gate (week 12):**
- **Scale** (≥ +25%, guardrail holds) → LATER.
- **Pivot** (+10% to +25%) → simplify to the listing check + alerts only, re-test.
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
| **Licence process tracker (Pro)** | Compliance Hub + rule-change watch | Managers handle dependent licences and rules that change mid-process ([`small-owners`](../research/small-owners.md)) |
| **Council pilot** (Castilla y León) | GoodHost Score + responsible-growth dashboard | Performance-based caps instead of blanket bans |

_____

## Risks that could reshape the roadmap

| Risk | Signal | Response |
|---|---|---|
| Spanish election outcome changes national rules | Coalition agreement (Dec 2026 – Jan 2027) | Regional rules stay; adjust content, not architecture (feature flags) |
| Interviews show compliance isn't #1 | NOW gate fails | Lead with platform risk: direct booking + evidence vault |
| Legal liability for wrong rules content | Any incorrect rule reported | Partner-verified content, timestamps, disclaimers, escalation path |
| Hosts see the Hub as surveillance | Low activation, negative feedback in tests | Frame as protection; never auto-unpublish; host stays in control |
| **Defensive hosts churn if tenant law changes** (owners using tourist rental as protection against tenant law, not for yield) | Faster-eviction rules in a new government's programme; Spanish churn not linked to compliance | Track churn reasons separately; offer mid-term and long-term modes so hosts can switch regime without leaving ([`interviews`](../research/interviews.md)) |
| **Rural seasonality** makes tourist-only portfolios unprofitable | Rural occupancy concentrated in July–August | Seasonal mode switching (tourist in peak, mid-term off-peak) with compliance handled in both |
| **Mid-term mode becomes a regulatory target** (RDL 29/2026, in force: seasonal and room rentals need a real, provable cause) | Inspections or claims that convert seasonal contracts into primary-residence leases | Build mid-term mode compliant from day one, storing the proof of each stay's cause in the evidence vault; never position it as an escape route ([`small-owners`](../research/small-owners.md)) |
| **Community conflict** (a judge can deprive the owner of use for up to 3 years) | Host logs a formal demand from the community | Staged alerts and evidence export; flag the step and point to a lawyer, never advise |
| **Alert fatigue** (the regulatory watch becomes noise) | Alerts per host per month rising; alert opt-outs | Per-listing matching, alert caps, monthly 'nothing changed for you' digest |
