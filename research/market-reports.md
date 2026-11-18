# Research · Market Reports

> Three secondary sources that sharpen the persona, the competitive map and the product scope. Each is labelled by who wrote it and why that matters. Paraphrased, with no long quotes.

_____

## 1 · Strategy& (PwC), "Impact of short-term rentals in Spain", November 2024

[PDF](https://news.airbnb.com/wp-content/uploads/sites/4/2024/12/Informe-PwC-Impacto-del-alquiler-de-corta-duracion-en-Espana.pdf)

_Source note: the report is hosted on Airbnb's newsroom. The document doesn't say who commissioned it, but we treat it as industry-aligned research and cite it that way._

**Method:** public data (INE, Eurostat, Ministry of Housing), a survey of 550 short-term rental owners (2024), and two econometric models of house prices.

**What it says about hosts (useful for the persona):**
- 351,389 short-term rental homes, 1.3% of the housing stock; about 130,000 (0.5%) used intensively. **63% of use is occasional.**
- **73% of owners earn under €10,000 a year** from it, and on average it is **under 20% of their total income**. Most common uses of the income: improving finances (38%), paying the mortgage (30%), renovating (28%).
- 11% are main residences and **52% second homes**: a large mixed-use segment ([opportunity H](../03-opportunities/opportunity-map.md#h-in-detail-the-home-exchange-signal)).
- **More than 76% are in small and medium municipalities**, which is where the [AI regulatory watch](../05-concept/ai-regulatory-watch.md) will find coverage hardest.

**Price sanity check:** at under €10,000 a year, €10–20 per home per month (€120–240 a year, the range two survey respondents accepted) is up to about 2.4% of that income. Affordable, but it has to be justified by protected bookings.

**What it says about housing (contested):** it finds no significant link between short-term rentals and national price levels or municipal price growth, and argues that restrictions in Barcelona, Palma and Ibiza didn't slow rents. **The other side:** the reference peer-reviewed study for Barcelona (García-López et al., *Journal of Urban Economics*, 2020) estimates that Airbnb raised rents by 1.9% in the average neighbourhood and by about 7% in the most exposed ones ([UB repository](https://diposit.ub.edu/handle/2445/175642)). Both can be true: a small national effect and a large local one. **This case doesn't need to take a side:** regulators have already acted, and that is what creates the compliance problem.

_____

## 2 · Brains Real Estate, "The holiday-rental ecosystem in Spain", March 2026 (updated April 2026)

[Article](https://brainsre.news/alquiler-vacacional-plataformas-gestores-inversores/)

**Thesis:** the market is professionalising fast. Platforms, managers, institutional investors and software vendors are dividing up the business while regulation reshapes it.

**What matters for this case:**
- **The small-host segment is shrinking.** Tourist homes on platforms fell to 329,764 in November 2025 (INE), down 12.4% year on year. Retaining the hosts who remain matters more.
- **Booking.com is bigger than Airbnb in Spain**, at least among software users: in a Lodgify sample of 400,000+ bookings (2025), Booking.com had 54.3%, Airbnb 26.7% and direct 17.6%. The sample skews professional, but it confirms that **one number synced on every channel** is critical, and that Hospitable must be strong on Booking.com.
- **It corroborates the "latent pain" finding** from our [host survey](survey-results.md): in a Lodgify survey of 167 owners and managers, the top challenges were cost control (42.5%) and cleaning and maintenance (37.7%). AI interest went to dynamic pricing (48.5%), guest messaging (46.7%) and content (43.7%). Compliance doesn't top either list.
- **Shorter stays:** 57.2% of stays are three nights or fewer. More turnover means more guest-registry submissions.
- **The competitive map** (see section 4 below).

_____

## 3 · PwC NewLaw, "Regulatory obligations for tourist listings in Spain", May 2025 (updated September 2026)

[Article](https://www.pwc.es/es/newlaw-pulse/legaltech/obligaciones-normativas-anuncios-turisticos-espana.html)

**What it adds:**
- **A listing can be non-compliant even when the home is licensed.** Ads must show the licence number, **whether the host is a private individual or a professional**, and relevant accommodation information. Consumer law requires that information to be clear, truthful, sufficient and easy to access.
- **Why the Airbnb listings were removed.** The Consumer Ministry ordered more than 65,000 tourist listings removed; the Madrid High Court upheld it and ordered 5,800 removed in a first phase. The violations: missing licence numbers, not stating whether the host is private or professional, and incorrect or non-existent numbers. **These are exactly the errors an automatic per-listing check can catch.**
- **Hosts and platforms don't know all their obligations.** The article notes some obligations are unknown to both, which fits the latent-pain finding.
- **A seed for the rules engine:** it cites the decree for each region: Madrid (Decreto 79/2014), Catalonia (Decreto 75/2020), Andalucía (Decreto 28/2016), Comunitat Valenciana (Decreto 10/2021), Balearic Islands (Ley 8/2012) and Basque Country (Decreto 101/2018). That covers 4 of our 5 MVP regions; Canarias is missing.
- **A partner, not a competitor.** PwC offers advisory services, not a tool. Large firms review compliance case by case; nobody offers continuous per-listing monitoring. This is the profile of the legal partner the [AI regulatory watch](../05-concept/ai-regulatory-watch.md) needs.

_____

## 4 · The competitive map, and a correction to this case

**Hospitable already partners for guest registration.** Chekin automates guest registration and filing with SES.Hospedajes and integrates with more than 50 property-management systems ([Chekin](https://chekin.com/en/legal-compliance/spain/)). Chekin and Hospitable ran a joint webinar on 23 September 2026 on connecting both platforms to automate guest-data reporting ([Chekin](https://landing.chekin.com/webinar_chekin_and_hospitable)). Hospitable also announced a partnership with GuestArrive for compliance automation.

**What this changes:** guest-registry automation is **not an open gap**; Hospitable covers it through partners. This case now treats it as a partner integration to activate and measure, and focuses the product on what nobody covers: the **per-listing permission-to-operate view** (licence, building community, rules in progress, dated evidence) and the **listing check** (number, host type and mandatory information on every channel). See the updated [opportunity map](../03-opportunities/opportunity-map.md) and [roadmap](../08-roadmap/roadmap.md).

**Spanish host-software competitors named by Brains** (compliance features **to verify** one by one before any claim):

| Player | Type | Price signal (Brains, 2026) | Compliance features |
|---|---|---|---|
| Avantio | Spanish PMS | From €280/month | To verify |
| Avaibook | Spanish PMS | From €23 per property per month | To verify |
| Icnea | Spanish PMS | — | To verify |
| Smoobu | PMS popular with small hosts | — | To verify |
| Chekin | Check-in and guest-registry specialist | — | Guest registration and SES.Hospedajes filing; a Hospitable partner |
| Hostaway, Guesty, Lodgify | International PMS | — | To verify |
