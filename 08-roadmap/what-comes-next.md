# What Comes Next · Where this case stops, and the gated plan from here

> Module 8 · The honest end point of this case study, and the next 8 weeks as a sequence of gates. It details the **NOW** column of the [roadmap](roadmap.md): nothing in **NEXT** starts until these gates are passed.

_____

## Where this case deliberately stops

This is a **discovery-stage case**. It has framed a problem worth validating. It hasn't proven that the problem is worth solving, and it doesn't claim to.

| Done | Not done yet |
|---|---|
| Market and regulation mapped across five layers (EU, state, region, city, building) | Hospitable's own data (delistings, churn, Spanish account base) |
| Evidence: INE, ministry and registry figures, Reddit, press testimonies, 2 operator interviews | Our own interviews with small hosts |
| Persona, friction and a hypothesis with a metric, a guardrail and a decision window | A live experiment |
| A clickable prototype (Compliance Hub + Rule watch) | Usability sessions with real hosts |
| A first survey of real hosts (n = 3) | A sample large enough to decide |

**Why stop here:** the next step needs data only Hospitable has, and a validation budget only a team can approve. Building more on top of unvalidated assumptions would add polish, not certainty.

_____

## The problem, as I'd present it today

**Spanish hosts find out they are non-compliant only after the damage is done.** Five layers of rules don't line up and keep changing, and nothing shows a host, per listing, whether they can still operate next month.

| | |
|---|---|
| **What we know** (observed) | Rules are fragmented and changing: 21% of national-registry applications were denied in 2025, tens of thousands were left pending, and a retroactive council rule took a licensed host's right to operate. 2 of 3 surveyed hosts were hit by a rule change in the past year, and one by a neighbours' vote |
| **What we believe** (hypothesis) | Per-listing visibility and alerts before the damage would raise the compliance-complete rate, protect bookings and reduce churn of Spanish accounts |
| **What challenged us** (against the data) | **None of the surveyed hosts named compliance as their main worry.** They worried about reviews, guests and operations, yet rated the core features 5/5 and 2 of 3 would pay €10–20 per home per month. Compliance looks like a **latent pain**: high value once shown, not top of mind |
| **What we don't know** (riskiest assumptions) | 1. Is the pain strong enough to change behaviour? 2. Does a compliance problem actually predict churn at Hospitable? 3. Is the Aha a protected booking, or just a status screen? 4. Will hosts pay, or upgrade, for it? |

**The refined framing:** the opportunity isn't "compliance software". It's **protecting a host's income and peace of mind**, with compliance as the engine underneath.

_Survey detail ([full results](../research/survey-results.md), anonymised): 3 owners with one home each, renting for 1–3 years, mainly on Airbnb, no management software; Madrid and Comunitat Valenciana; one stopped renting in the past year. Results are a signal to validate, not a conclusion._

_____

## The ask

**Not "build the Compliance Hub".** Instead: **fund 8 weeks of validation**, with access to Hospitable's Spanish account data, one designer-researcher, and a legal partner for one region. At each gate we either earn the next step or stop cheaply.

_____

## The next 8 weeks: four gates, ordered by risk

Each gate answers one riskiest assumption. Thresholds are proposals, to be agreed before each gate starts.

### Gate 1 · Is the pain felt or latent? (weeks 1–3)

| | |
|---|---|
| **Method** | 8–10 interviews with small Spanish hosts (≥3 non-resident), starting with the host whose building voted against tourist rental and the host who stopped renting. Ask each to walk through the last rule or registry change they dealt with, from how they heard to what it cost. Keep the survey open to reach n ≥ 30 |
| **Pass** | ≥50% describe a concrete compliance event in the past 12 months with a real cost (time, bookings or money) |
| **If it fails** | The pain is too latent to sell on its own. Reposition as a **peace-of-mind bundle** (verified guests + automated guest registry + rule alerts) and test that instead |

### Gate 2 · Does compliance predict churn? (weeks 2–4, in parallel)

| | |
|---|---|
| **Method** | Hospitable's own data for Spain: listings delisted or flagged for registration problems, and the 90-day churn of those accounts vs others. Also the week-0 baseline: share of Spanish listings missing a valid number on at least one channel |
| **Pass** | Accounts hit by a compliance delisting churn materially more (for example ≥1.5×) **and** ≥10% of Spanish listings have a gap today |
| **If it fails** | Compliance isn't a retention lever at Hospitable. Keep it as **acquisition content** (rules pages for search and AI answers) and drop the retention bet |

_This is the FinWise lesson: a behaviour linked to retention doesn't prove that causing it will improve retention. Gate 2 checks the link before we build on it._

### Gate 3 · Is the Aha real? (weeks 4–6)

| | |
|---|---|
| **Method** | 5–8 moderated sessions with the prototype. Then a **fake door** in Essentials: a "Check your listings' compliance" entry point for Spanish hosts, measuring click-through and completion of a first fix |
| **Aha to test** | Not seeing a status, but **fixing a real at-risk issue before it causes damage** (for example syncing a missing number to Booking.com) |
| **Pass** | ≥5 of 8 find and fix their first issue unaided in under 5 minutes; fake-door click-through high enough to justify the A/B test |
| **If it fails** | Simplify to the single most valued job (number sync or guest registry) and retest |

### Gate 4 · Will they pay or upgrade? (weeks 6–8)

| | |
|---|---|
| **Method** | Pricing questions in interviews, then a **painted-door upgrade prompt** shown when an action is needed ("Fix on every channel: available on Host") |
| **Pass** | ≥40% of hosts who reach the prompt choose to learn more or start the upgrade |
| **If it fails** | Compliance stays free as a retention feature; monetise through the plans it protects, not as an add-on |

_____

## After the gates

| If… | Then |
|---|---|
| Gates 1–3 pass | Run the **A/B test** in [`hypothesis.md`](../07-validation/hypothesis.md): IF we show new Spanish hosts their per-listing status and guide them to their first real fix, THEN the share who resolve a real alert within 7 days rises, BECAUSE hosts lack visibility, not will. Guest-registry beta in parallel |
| Gate 4 also passes | Package compliance as the upgrade trigger from Essentials (see [`positioning.md`](../09-go-to-market/positioning.md)) |
| Gate 1 fails, others pass | Lead with the peace-of-mind bundle; compliance as the engine |
| Gate 2 fails | Stop the retention bet; keep rules content as acquisition |

**Before building the AI regulatory watch**, run it by hand: the legal partner curates rule changes for one region for 6 weeks (a "Wizard of Oz" version). Automate only once hosts act on the alerts. See [`ai-regulatory-watch.md`](../05-concept/ai-regulatory-watch.md).

_____

## Parked until the gates are passed

- Building the full Compliance Hub and the automated AI watch
- GoodHost Score, cap-and-waitlist and the council pilot
- Portugal and other EU markets
- Paid acquisition for compliance
