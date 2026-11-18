# The Hypothesis · STR Europe

> Module 7 · Hypothesis Builder output. A formal, data-backed hypothesis with a success metric, a guardrail and a decision window. Qualitative evidence: [`research/qualitative-reddit.md`](../research/qualitative-reddit.md).

## Slide 1 · Hypothesis statement

**We believe that** small hosts in Spain with 1–5 listings, resident or non-resident, lose bookings and peace of mind because they find out they are non-compliant only after the damage is done: nothing shows them, per listing, whether they are legally allowed to operate right now.

**If we** give them a compliance layer that validates their regional registration, syncs it to every connected channel, submits guest-registry data automatically and alerts them before a listing is at risk,

**then** the share of their listings that are compliance-complete within 30 days will rise by **at least 25%**, without reducing the share of listings that are live and bookable.

**We'll decide** after **12 weeks** (two monthly cohorts plus a 30-day read): scale, pivot or kill.

_____

## Step 1 · Path

**My own initiative:** compliance layer for Spanish hosts on a host-software platform.

## Step 2 · Bet

**Optimizing the existing:** fix friction for current Spanish hosts and chase **retention**. It removes a known pain from an existing workflow; it does not create a new value moment.

_____

## Step 3 · Evidence

**Qualitative**

> *"The rules and regs take far more time than you think and are far more important than you think."* (veteran host, r/airbnb_hosts)
>
> A non-resident buyer near Barcelona expects **1–1.5 years** to get a tourist licence and can't tell which rules apply to his town (r/askspain). From the public side: *"lo necesario es prohibir a quien quiere hacerlo legal"*: the compliant host is the one who gets restricted (r/Madrid).

**Quantitative**

- By June 2025, of 178,856 registration applications, 16,133 had been denied and **81,446 were still pending** verification. [Housing Ministry via Bolsamanía](https://www.bolsamania.com/noticias_amp/empresas/economia--registradores-aprueban-el-83-de-solicitudes-tramitadas-para-el-registro-de-alquileres-obligatorio-en-julio--20124484.html)
- The owners' federation Fevitur reports **64,000 legal tourist homes** left off the market by registry formalities, not by failing regional requirements. [Bolsamanía](https://www.bolsamania.com/noticias_print/empresas/economia--fevitur-critica-que-64000-viviendas-turisticas-legales-han-quedado-fuera-del-mercado-por-el-registro-estatal--21650428.html) _(industry figure, attributed)_
- The number of tourist homes fell **10.7% year on year** to 341,001 in May 2026. [INE via Forbes](https://forbes.es/forbestravel/964774/la-vivienda-turistica-cae-un-107-y-marca-uno-de-los-mayores-retrocesos-historicos/)
- Meanwhile, international tourists staying in rented homes grew **6.3%** (Jan–Nov 2025) vs 1.6% for hotels, so each lost listing is lost demand. [INE FRONTUR](https://www.ine.es/dyngs/Prensa/FRONTUR1125.pdf)

**Reconciliation:** the qualitative pain (rules are confusing, slow and catch legal hosts) is confirmed by hard numbers: tens of thousands of legal homes blocked or stuck by formalities while demand grows. One adjustment from the qual data: for hosts in general, platform risk is the louder pain, so the bet focuses on **Spain-based and non-resident owners**, where compliance is the confirmed #1.

_Note: the national registry behind the 2025 figures was annulled in May 2026; regional registries and platform data duties remain. The friction persists in a different shape._

_____

## Step 4 · Persona & problem

| | |
|---|---|
| **Role (who)** | Small hosts in Spain with 1–5 tourist listings on Airbnb and Booking.com, **resident or non-resident**. Non-resident owners are analysed as a subgroup: the research shows the most intense pain there |
| **Goal** | Keep earning legally and predictably, without legal or platform surprises |
| **Friction** | No single, reliable view of whether each listing is legally allowed to operate right now |

**Problem we are solving:** Spanish hosts find out they are non-compliant only after the damage is done (a delisted listing, a lost booking or a fine), because nothing shows them their compliance status per listing before it's too late.

**Causes behind the friction** (why it exists, not separate frictions):
- Regional licences and registries that differ by region and change often
- Building communities that can approve, limit or ban tourist use
- Guest-registry obligations (SES.Hospedajes) with tight deadlines
- Platform policies and registration checks that can delist a listing unilaterally

_____

## Step 5 · Outcome & metrics

**Strategic outcome:** Spanish hosts stop discovering compliance problems after the damage is done. That means fewer compliance-driven delistings and lost bookings, which shows up as **higher retention of Spanish host accounts** (lower 90-day churn, the lagging result) and protected booking revenue per listing.

**Primary success metric (leading indicator + target):** **+25% relative lift in the 30-day compliance-complete rate** of Spanish listings. A listing is compliance-complete when it has:
1. a valid regional registration number,
2. that number synced to every connected channel, and
3. 100% of guest-registry (SES.Hospedajes) submissions on time.

_Example: baseline 60% → target 75%. Baseline measured in week 0, before launch. +25% is the minimum lift worth building for; re-check it once the baseline is known._

**Guardrail metric:** **the share of Spanish listings that are live and bookable on at least one channel must not drop.** This protects the revenue base: compliance checks must never push hosts to unpublish or pause listings they could legally keep.
_Watch metric: time to first published listing for new Spanish hosts._

**Decision window:** **12 weeks**, made up of 8 weeks of enrolment (two monthly cohorts) plus 30 days for the second cohort to reach its measurement point.
- **Scale:** ≥ +25% and the guardrail holds.
- **Pivot:** +10% to +25%, or the watch metric worsens. Simplify, starting with guest-registry automation only.
- **Kill:** under +10%. Compliance visibility isn't the lever, so revisit platform risk and direct booking.

**Subgroup read:** report the result separately for non-resident owners. If their lift is much larger, focus go-to-market on them first.

_____

## Slide 1 · Summary

| | |
|---|---|
| **Bet type** | Optimizing the existing → retention |
| **Evidence** | Hosts say rules take more time than expected and licences take 1–1.5 years; 81,446 applications pending and 64,000 legal homes blocked by formalities |
| **Success metric** | +25% relative lift in 30-day compliance-complete rate (leading); 90-day churn of Spanish accounts (lagging) |
| **Guardrail** | Share of Spanish listings live and bookable must not drop (watch: time to first published listing) |
| **Decision window** | 12 weeks (8 enrolment + 30-day read) → scale, pivot or kill |
