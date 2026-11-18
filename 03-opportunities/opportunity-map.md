# The Opportunities · STR Europe

> Module 3 · Prioritisation. Where a host platform can win, in what order, and what I'm not doing.

## Opportunity map

| # | Opportunity | What it does |
|---|---|---|
| A | **Compliance layer** | Rules by region, city and postcode; licence lifecycle per listing; registration-number sync to every channel; pre-delisting alerts; inspection-ready audit trail |
| B | **Guest-registry automation** | Collect ID in the booking flow, auto-submit to SES.Hospedajes (Spain) and SIBA (Portugal), keep proof |
| C | **Tax module** | Income reports for non-resident owners; VAT-ready invoicing behind a feature flag |
| D | **Mid-term mode, done right** | 32-day+ contracts, documented purpose of stay, deposits |
| E | **Good-neighbour kit** | Noise sensors (decibels only), neighbour contact line, complaint log, evidence pack for building votes |
| F | **Sector data and credibility** | Anonymised compliance and impact data for regions and associations |
| G | **Safe direct booking** | Verified direct site, secure payments, ID verification, repeat-guest CRM |
| H | **Fee-averse and mixed-use hosts** | "Your guests, no commission per booking": compliant direct booking for returning guests, trusted-guest list, and calendar blocks for owners who also swap or use their home ([details below](#h-in-detail-the-home-exchange-signal)) |

_____

## Prioritisation

| Opportunity | Pain | Effort | Revenue | Election risk | Order |
|---|---|---|---|---|---|
| B. Guest registry | High, daily | Low–Med | Retention + add-on | None | **1** |
| A. Compliance layer | Very high | High | Add-on per listing | None | **2** (MVP: 5 regions) |
| C. Tax / VAT | High (foreign owners) | Medium | Partner revenue share | 10% VAT live since 1 Dec 2026; could change after the election | **3** |
| E. Neighbour kit | Medium–High | Low | Hardware partners | None | 4 |
| D. Mid-term mode | Medium | Medium | Expands market | Rules could tighten | 5 |
| F. Data | Strategic | Medium | Indirect | None | Parallel |
| H. Fee-averse and mixed-use hosts | Medium (fees are felt; rules are latent) | Low–Med (builds on G and A) | Retention + direct-booking commission | Low | With G, after the validation gates |

_G and H are sequenced together: direct booking in Spain is only safe once the listing is compliant (licence number and guest registry), so A and B come first._

**MVP regions:** Andalucía, Comunidad Valenciana, Madrid, Canarias, Baleares, where foreign-owner density, regulatory churn and protest pressure overlap.

_____

## Not doing

- **Not building demand generation.** Platforms out-spend any host tool on marketing; we win on operations and compliance.
- **Not giving legal advice.** Rules content is partner-verified (law firms, gestorías), timestamped, with escalation to a professional.
- **Not positioning anything as a way around regulation.** "Compliance made easy" is both the value proposition and what protects us with platforms and regulators.
- **Not building an in-house tax engine.** 10% VAT on tourist rentals is live from 1 December 2026, so VAT-ready invoicing goes in through partners, behind a feature flag in case the next government changes the rate.
- **Not building a home-exchange marketplace.** No money changes hands (nothing to monetise), it needs both sides of a new network, it serves owners who live in their homes rather than hosts running a business, and its legal advantage depends on staying non-commercial. We take the lessons (flat price, trust, community), not the model.
- **Not treating Barcelona as a growth market.** It's a "move to mid-term or exit" use case given the 2028 phase-out.

_____

## H in detail: the home-exchange signal

_Added November 2026._

**What's happening.** Home exchange is growing fast in Spain. HomeExchange went from 7,800 Spanish members in 2021 to 40,600 in 2025, its second market after France ([Forbes](https://forbes.es/?p=860231)). Spanish members made about 40,000 exchanges in summer 2026, up 29.4% year on year, more than half within Spain ([Infoviajera](https://www.infoviajera.com/?p=176825)). Members pay an annual subscription of about €175 with no fee per stay, and 90% renew ([Qué!](https://www.que.es/2026/08/03/intercambio-casas-viajar-ahorrar-alojamiento/)).

**Why it grows (four drivers):**
1. **Price.** Hotel rooms are about 31% more expensive than in May 2022, per INE as reported by [Qué!](https://www.que.es/2026/08/03/intercambio-casas-viajar-ahorrar-alojamiento/).
2. **Fee fatigue.** Since 27 October 2025, hosts using property-management software, Hospitable included, moved to Airbnb's host-only fee ([Hospitable](https://help.hospitable.com/en/articles/4703232)), 15.5% deducted from the payout ([Truvi](https://truvi.com/?p=19958)); Airbnb is moving all EU hosts to it from 13 October 2026. Hosts now see the full commission on every payout.
3. **Social narrative.** Exchange is framed as using empty space without speculation and without taking homes from residents ([Infoviajera](https://www.infoviajera.com/?p=160658)), which resonates during the housing crisis.
4. **A regulatory grey zone, for now.** With no payment, commentators say no tourist licence applies because there's no economic activity ([Vivara](https://www.vivara.io/blog/legal/intercambiar-casa-en-vacaciones/)); the press calls it a legal limbo the tax authority hasn't addressed yet ([idealista](https://www.idealista.com/news/node/870884)). These are secondary sources, not a ruling, and the gap could close if the model keeps growing.

**What Hospitable can take from it:**
- **The message:** flat subscription, not commission per booking. Hospitable already works this way (subscription, plus a 1% fee on Basic direct bookings), so it can speak to hosts tired of the 15.5%: *"Your returning guests can book you direct."*
- **The precondition:** in Spain a direct booking still needs a licence number and guest registry. **The Compliance Hub is what makes direct booking safe**, which ties H back to A and B.
- **Mixed-use owners:** several small owners in our research use their home part of the year ([small-owner voices](../research/small-owners.md)). If they also swap in low season, a calendar block from the exchange platform (if it supports calendar export; to verify) would prevent double bookings and keep them on Hospitable.
- **Trust mechanics:** verification, mutual reviews and community drive HomeExchange's renewal rate. A trusted-guest list for returning guests, with ID verification, is the commercial version, and it fits the "peace of mind" bundle suggested by the [host survey](../research/survey-results.md).

**How we'd validate it:** add two questions to Gate 1 interviews ([`what-comes-next.md`](../08-roadmap/what-comes-next.md)): how hosts feel about the 15.5% fee, and how many of their bookings come from returning guests who would book direct if it were easy and legal.

_____

## Product tiers (matching where regulation is heading)

- **Home-sharer tier:** simple, cheap, minimal compliance (primary residence, occasional lets).
- **Pro tier:** full compliance and VAT stack, multi-unit and building management, hotel-style channels.
