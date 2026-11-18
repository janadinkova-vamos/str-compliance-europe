# Short-Term Rentals in Europe, A Compliance-Led Product Strategy

> European short-term rental hosts are no longer limited by demand but by permission to operate. Regulation is fragmented across EU, national, regional, city and building layers, and it changes faster than hosts can follow. A compliance layer that keeps hosts legal by default, rewards good operators and helps destinations grow responsibly is the most defensible position a host platform can hold, whoever governs.

Jana Alexandrova · Product case study · November 2026

**Presentation:** _pitch.html (coming soon)_ · **Prototype:** _Compliance Hub on Lovable (link coming soon)_

This repo is a product case study on the European short-term rental (STR) market, starting with Spain and Portugal, written from the point of view of a Senior Product Manager at a host-software company. One folder per module; this README is **The Story** that ties them together.

_Independent work. Not affiliated with or endorsed by any company mentioned. Market facts are as of November 2026 and linked to their sources in each module._

---

## Deliverables at a glance

| # | Module | Deliverable | Folder |
|---|---|---|---|
| 1 | **The Market** (Regulatory landscape) | EU, Spain and Portugal regulation, as of November 2026 | [`01-market/`](01-market/market-landscape.md) |
| 2 | **The Problem** (Pain points) | political, social and operational pain points by persona | [`02-problem/`](02-problem/pain-points.md) |
| 3 | **The Opportunities** (Prioritisation) | opportunity map, prioritisation table and what I'm not doing | [`03-opportunities/`](03-opportunities/opportunity-map.md) |
| 4 | **The Scenarios** (Political risk) | Spanish election scenarios and the hotel "level playing field" | [`04-scenarios/`](04-scenarios/scenarios.md) |
| 5 | **The Concept** (GoodHost Score) | host score + cap-and-waitlist engine for saturated areas · AI regulatory watch with human approval | [`05-concept/`](05-concept/goodhost-score.md) · [`AI watch`](05-concept/ai-regulatory-watch.md) |
| 6 | **The Expansion** (Emerging destinations) | growth outside saturated cities, aligned with Spain Tourism 2030 | [`06-expansion/`](06-expansion/emerging-destinations.md) |
| 7 | **The Validation** (Discovery & pilot) | formal hypothesis, interviews, data pulls, pilot design and success metrics | [`07-validation/`](07-validation/hypothesis.md) |
| 8 | **The Roadmap** (Now / Next / Later) | outcome-based roadmap with decision gates · where this case stops and the next 8 weeks of validation | [`08-roadmap/`](08-roadmap/roadmap.md) · [`what comes next`](08-roadmap/what-comes-next.md) |
| 9 | **The Go-To-Market** (Positioning & launch) | cost of inaction, positioning, messaging, pricing & packaging, launch checklist | [`09-go-to-market/`](09-go-to-market/positioning.md) · [`checklist`](09-go-to-market/launch-checklist.md) |
| P | **The Prototype** (Lovable) | Compliance Hub prototype prompt + link | [`prototype/`](prototype/lovable-prompt.md) |
| R | **Research** (Qualitative) | Reddit host and resident voices, coded and counted · two operator interviews · small-owner voices from the press · legal evidence on building communities · first host survey (n = 3) · market reports and competitive map | [`research/`](research/qualitative-reddit.md) · [`interviews`](research/interviews.md) · [`small owners`](research/small-owners.md) · [`communities`](research/legal-communities.md) · [`survey`](research/survey-results.md) · [`market reports`](research/market-reports.md) |

---

## The Story

**The friction.** Walking around Valencia, I'd seen garages turned into tourist flats. Spain welcomed nearly 97 million international tourists in 2025 ([INE](https://www.ine.es/dyngs/Prensa/en/FRONTUR1225.htm)), and in Valencia you could see the debate over tourism and housing play out on the same street. Before applying to Hospitable, I wanted to understand what running a short-term rental actually took and whether there was a problem I'd want to work on.

I started with the headlines and a hunch. I'd heard that some guests were finding hosts on Google Maps and booking directly. I thought there might be an opportunity in keeping those bookings on-platform. The more I read, the more I kept coming back to a question that comes before any booking. How does a host know whether they can still rent out their property next month? The answer can depend on rules set by the EU, the state, the region, the city and the building itself.

**The aha moment.** I came across the account of a host in A Coruña who said he'd had a licence since 2019. He said he lost it after the city changed its rules and that he'd received no warning. His flat stayed empty. What stuck with me was how late he found out. That gave me a problem I could design for. When a rule changes, hosts need to know whether it affects their property while they still have time to act.

**What surprised me.** I sent a short survey to three hosts I know. Two said a rule change had affected them in the past year. One said her building had voted against tourist rentals, and one had stopped renting altogether. Yet when I asked what worried them most, they talked about reviews, guests and day-to-day operations. That changed how I'd position the product. A host already has enough to check. I'd want the first screen to answer one question in seconds. Is there anything I need to do to keep taking bookings? ([survey results](research/survey-results.md))

**What I built.** I built a working prototype of a Compliance Hub with an AI-assisted regulatory watch. I focused on one workflow. Show the host what changed, which property it might affect, and what to check next. Three answers aren't proof, but they were enough to prototype that workflow and test it properly. The prototype gives me a way to test whether it saves hosts time and helps them act sooner.

**What I'd do next.** I'd interview eight to ten hosts, starting with the host whose building voted against tourist rentals and the one who stopped renting last year. I'd ask each to walk me through the last change they dealt with, from how they heard about it to what they did. Then I'd measure how many pilot properties have completed the requirements we can verify and how long hosts take to resolve an outstanding action. I'd use that baseline to test the free status view and see whether ongoing monitoring gives hosts on Essentials a reason to upgrade. The full gated plan is in [`what-comes-next.md`](08-roadmap/what-comes-next.md).

**Why I'd work on this.** At ASISA, I designed health insurance products for international students and residents applying for Spanish visas and residency. The requirement created demand. What customers needed from us was practical. They wanted to know which insurance to buy and when they'd have the certificate they needed for their application.

I see a similar opportunity at Hospitable. A host shouldn't have to spend Sunday evening reading a municipal ordinance to work out what it means for one flat. If Hospitable can give them a clear answer about their property while there's still time to act, that's time back for the host and a reason to trust the product with more of their business.

---

## Repo structure

```
str-compliance-europe/
├── README.md                                ← this dashboard + The Story
├── 01-market/market-landscape.md            ← M1: regulatory landscape
├── 02-problem/pain-points.md                ← M2: pain points by persona
├── 03-opportunities/opportunity-map.md      ← M3: opportunities + prioritisation
├── 04-scenarios/scenarios.md                ← M4: election + level-playing-field scenarios
├── 05-concept/goodhost-score.md             ← M5: GoodHost Score + cap-and-waitlist
├── 05-concept/ai-regulatory-watch.md       ← M5: AI regulatory watch
├── 06-expansion/emerging-destinations.md    ← M6: emerging destinations
├── 07-validation/hypothesis.md              ← M7: formal hypothesis (Hypothesis Builder)
├── 07-validation/validation-plan.md         ← M7: discovery, pilot and metrics
├── 08-roadmap/roadmap.md                    ← M8: Now / Next / Later roadmap
├── 08-roadmap/what-comes-next.md           ← M8: where the case stops + validation gates
├── 09-go-to-market/positioning.md          ← M9: positioning, messaging, pricing
├── 09-go-to-market/launch-checklist.md     ← M9: launch checklist (+ .xlsx)
├── prototype/lovable-prompt.md              ← Compliance Hub prototype (Lovable)
├── research/qualitative-reddit.md           ← qualitative research (Reddit)
├── research/interviews.md                   ← operator interviews
├── research/small-owners.md                 ← small-owner voices (press)
├── research/legal-communities.md            ← building communities: law and case law
├── research/survey-results.md               ← first host survey (n = 3, anonymised)
└── research/market-reports.md               ← PwC, Brains, PwC NewLaw + competitive map
```

---

_Product case study by Jana Alexandrova, November 2026._
