# Legal Evidence · Building Communities and Tourist Homes

> The fourth layer of permission. Besides the region, the council and the platform, **the neighbours** now decide whether a home in a residential building can operate, and since April 2025 they decide first. Complements [`small-owners.md`](small-owners.md) and [`interviews.md`](interviews.md).

_Summary of secondary sources. Not legal advice. Check the BOE text and newer case law before relying on any point._

> **Scope warning: Catalonia is different.** Everything below about the Horizontal Property Law (LPH) and LO 1/2025 applies to Spain **outside Catalonia**. Catalonia has its own civil law: building communities are governed by Book V of the Catalan Civil Code (arts. 553-1 to 553-59), not by the LPH. See the Catalonia section at the end.

_____

## Source 1 · Vademécum Legal, practical case on community claims against tourist homes

Published June 2022 and last revised June 2026. It analyses rulings from 2020 to 2024, not a single case.

**The legal question, before the reform:** the old art. 17.12 of the Horizontal Property Law (LPH) let a community "limit or condition" tourist use by a 3/5 vote. Courts disagreed on whether that included a full ban:

| Ruling | Criterion | Outcome |
|---|---|---|
| TSJ Asturias 498/2021 | A ban doesn't reach an owner who had already applied to the council and the region **before** the vote | Community's appeal dismissed |
| AP Segovia 129/2020 | Banning and limiting are the same in practice | Owners' claim dismissed |
| JPI Córdoba 45/2022 | Communities can only limit; banning needs unanimity | Ban declared void |
| **Supreme Court 1232/2024 and 1233/2024 (3 Oct 2024)** | "Limit" includes a ban as its maximum; a 3/5 vote is enough | **Ban upheld.** Settles the debate |
| AP Valencia 242/2021 | A cease claim needs a formal demand and a current meeting authorisation | Claim dismissed on procedure |

**How a community stops a tourist home (cease action, art. 7 LPH):**
1. The president formally demands that the owner stop, warning of legal action. Both the content and the receipt must be provable.
2. If the owner continues, a meeting authorises the president to sue. The authorisation must be current.

**Other points:** use limits must be written into the statutes and recorded in the Land Registry to bind third parties. Changing the statutes otherwise needs unanimity.

_____

## Source 2 · OKDiario, 14 November 2026

Popular explainer, with no case law or expert quotes. It adds the post-reform picture:

- **Prior approval.** Since LO 1/2025 took effect on 3 April 2025, art. 7.3 LPH requires the owner to get the community's **express approval before** starting tourist rental in a residential building. Before, the community could only stop it with a majority against.
- **Same majority for everything.** Approving, limiting, conditioning or banning needs 3/5 of owners and 3/5 of quotas.
- **No retroactivity, plus a transitional rule.** Owners already renting to tourists before the reform, and registered under their region's tourism rules, can keep operating on those rules' terms.
- **Surcharge.** With the same 60% vote, a tourist home's share of common costs can rise by up to 20%.
- **Sanction.** If the owner ignores the demand, a judge can deprive them of the use of the home for **up to three years**.
- **Challenge deadlines.** Community agreements can be challenged within three months, or one year if they breach the law or the statutes.

_____

## Catalonia · a different community regime

- The Barcelona-Lleida association of property administrators stated that the LO 1/2025 reform **does not apply in Catalonia**, because it amends the LPH and Catalonia is governed by its own Civil Code. [Noticias Jurídicas](https://noticias.juridicas.com/actualidad/noticias/20123-los-administradores-de-fincas-aclaran-que-la-nueva-ley-de-comunidades-de-propietarios-no-tiene-efectos-en-cataluna/)
- Catalan communities have been able to ban tourist homes since 2006 (art. 553-11, Book V), but they need **four-fifths** of owners and quotas, not three-fifths. [Sepin](https://blog.sepin.es/viviendas-usos-turisticos-comunidades-propietarios-catalunya)
- Land registrars in Catalonia already deny registration where a statutory ban is recorded under art. 553-11 (DGSJFP resolutions published in the BOE, 2025–2026).

**Takeaway:** the building layer is not national either. The majority needed, the prior-approval rule, the surcharge and the transitional protection depend on which civil law applies to the building.

_____

## Implications for the product

0. **Community rules by civil-law regime.** The rules engine needs a community module per regime (LPH for most of Spain, Catalan Civil Code for Catalonia), not one national rule.
1. **The community is an entry condition.** Outside Catalonia, for a new host, community approval comes before the regional or municipal licence. The Compliance Hub checklist starts there: minutes, votes and quotas, and date. → "Community status" added to the Compliance Hub scope in the [roadmap](../08-roadmap/roadmap.md).
2. **Two paths by start date.** Started before 3 April 2025 with a regional registration → the product stores and surfaces that proof (transitional protection). Started after → express approval required. This fits the "legal category per unit" field.
3. **Dates decide outcomes.** Asturias protected an owner because his applications predated the vote. The **dated evidence vault** must store the date of every application, not just the final licence. This confirms Jon Goitia's point in [`interviews.md`](interviews.md).
4. **Staged alerts.** Conflicts move through steps that can be tracked: formal demand → meeting authorisation → lawsuit. If the host logs the demand, the product shows what comes next and when to see a lawyer. It flags the step; it doesn't advise.
5. **Deadline reminders.** When a host uploads an adverse community agreement, the product shows the three-month or one-year challenge deadline as a reminder to get legal advice.
6. **The 20% surcharge is a cost to track.** It belongs in the listing's profitability view: a legal home can stop paying off.
7. **Highest-severity risk.** Losing the use of the home for up to three years is worse than a fine for a small owner. This reinforces the rule that the product never encourages publishing a listing without a complete status.
8. **Don't over-promise.** Case law has shifted several times. The product informs and keeps evidence; it never says "you are protected".
