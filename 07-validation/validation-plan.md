# The Validation · STR Europe

> Module 7 · Discovery & pilot. How I'd find out whether I'm right before committing engineering.

## Riskiest assumptions

| # | Assumption | Why it's risky |
|---|---|---|
| 1 | Compliance pain is bigger than pricing or messaging pain for European hosts | If not, a compliance add-on won't sell |
| 2 | Guest-registry automation is a top-3 time sink | It's the first thing I'd build |
| 3 | Hosts will pay per listing for compliance | Hosts expect compliance to be "included" |
| 4 | Councils will partner with a host platform | A platform may be seen as on the hosts' side |
| 5 | Good hosts will welcome a score | It could be perceived as surveillance |

_____

## Discovery

- **Interviews (n = 15–20):** Spanish PMs, foreign owners, rural hosts. Key questions: _What took most of your admin time last month? Have you lost a listing or a booking to a registration problem? What would you pay to never think about it again?_
- **Data pulls:** delisting and registration-error rate in Spain in 2026; direct-booking share and repeat-guest rate (Spain, Portugal); listing growth outside the top 20 cities vs inside.
- **Council conversations (n = 3–5):** a tourism board in Castilla y León, one coastal municipality near saturation.

_____

## First experiment

**Experiment:** Guest-registry automation beta

**Hypothesis:** If we auto-submit guest-registry data for Spanish listings, at least 40% of eligible hosts will turn it on within 30 days, and their weekly admin time will drop measurably.

**Method:** opt-in beta for Spanish customers, with a holdout of eligible hosts not yet invited.

- **Primary metric:** activation rate of the feature within 30 days.
- **Secondary:** submissions on time, support tickets about registry, self-reported admin time.
- **Guardrails:** submission errors, guest drop-off at the ID step.
- **Read date:** 30 days after launch.

_____

## North Star

**Compliant active listings:** listings that, in the month, had a valid registration on every channel, submitted all guest-registry entries on time, and had no unresolved compliance alert.

It measures the value the strategy promises: hosts operating legally, by default.

_____

## Leading and lagging indicators

- **Leading:** share of listings with a verified registration number synced to all channels; time to resolve a compliance alert; registry submissions on time.
- **Lagging:** delisting rate due to compliance; churn among Spanish and Portuguese customers; revenue per listing from compliance add-ons.

_____

## 12-month outline

| Quarter | Focus |
|---|---|
| Q1 | Discovery + guest-registry beta |
| Q2 | Compliance layer MVP in 5 Spanish regions |
| Q3 | Portugal + GoodHost Score (private) |
| Q4 | Council pilot (Castilla y León) + destination radar |
