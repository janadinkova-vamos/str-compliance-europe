# The Hypothesis · STR Europe

> Module 7 · Hypothesis Builder output. A formal, data-backed hypothesis with a success metric, a guardrail and a decision window. Qualitative evidence: [`research/qualitative-reddit.md`](../research/qualitative-reddit.md).

## Slide 1 · Hypothesis statement

**We believe that** small and non-resident hosts in Spain (1–5 listings) lose bookings and peace of mind because they can't tell whether they are legally allowed to operate across fragmented regional, municipal, building and platform rules.

**If we** give them a compliance layer that validates their regional registration, syncs it to every connected channel, submits guest-registry data automatically and alerts them before a listing is at risk,

**then** the share of their listings that are compliance-complete within 30 days will rise by **at least 25%**, without slowing down onboarding.

**We'll decide** after **8 weeks (two monthly onboarding cohorts)**: scale, pivot or kill.

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
| **Role (who)** | Small host or non-resident owner in Spain with 1–5 tourist listings, managing on Airbnb and Booking |
| **Goal** | Keep earning legally and predictably, without legal or platform surprises |
| **Friction** | Fragmented, changing rules (regional licence, building community, guest registry, platform policies) and no single place to see whether each listing is compliant |

**Problem we are solving:** hosts can't see or control their permission to operate, so they discover compliance problems only when a listing is delisted, a booking is lost or a fine arrives.

_____

## Step 5 · Outcome & metrics

**Strategic outcome:** Spanish hosts reach and stay compliance-complete by default, which leads to fewer compliance-driven delistings and lost bookings and, in turn, **lower churn of Spanish accounts** (retention).

**Primary success metric (leading indicator):** **+25%** in the share of Spanish listings that are compliance-complete within 30 days of exposure. A listing counts as compliance-complete when:
1. it has a valid regional registration number,
2. that number is synced to every connected channel, and
3. every guest-registry (SES.Hospedajes) submission was on time.

_Baseline to be measured before launch; the +25% is relative to that baseline._

**Guardrail metric:** **time to first published listing** for new Spanish hosts must not increase, and onboarding completion must not drop. Compliance must not become a new barrier. Secondary watch: compliance-related support tickets.

**Decision window:** **8 weeks, or two full monthly onboarding cohorts**, whichever comes later.
- **Scale** if the primary metric hits +25% and the guardrail holds.
- **Pivot** if it improves but stays under +15%, or the guardrail moves (simplify the flow, start with guest registry only).
- **Kill** if there is no meaningful lift: compliance status alone isn't the lever; revisit platform risk and direct booking.

_____

## Slide 1 · Summary

| | |
|---|---|
| **Bet type** | Optimizing the existing → retention |
| **Evidence** | Hosts say rules take more time than expected and licences take 1–1.5 years; 81,446 applications pending and 64,000 legal homes blocked by formalities |
| **Success metric** | +25% compliance-complete Spanish listings within 30 days |
| **Guardrail** | Time to first published listing must not increase |
| **Decision window** | 8 weeks / two monthly cohorts → scale, pivot or kill |
