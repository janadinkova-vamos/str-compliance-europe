# Prototype · Lovable Prompt

> Paste everything below the line into a new Lovable project. It builds a clickable prototype of the **Compliance Hub**, the treatment tested in [`07-validation/hypothesis.md`](../07-validation/hypothesis.md). Mock data only: no real APIs, no real personal data.

---

Build a clickable web prototype called **Compliance Hub**: a compliance dashboard for short-term rental hosts in Spain. It is a concept prototype for a product case study, not a real product. Use only mock data. Do not connect any real API. Do not use any existing company's name, logo or branding.

## Who it's for

Persona: **Marta**, a host who owns 4 tourist apartments in Spain and lists them on Airbnb and Booking.com. A second persona, **Thomas**, is a non-resident owner living in Germany with 1 apartment in Málaga. Add a persona switcher in the header (Marta / Thomas) that swaps the mock portfolio.

**The problem it solves:** hosts find out they are non-compliant only after the damage is done (a delisted listing, a lost booking or a fine), because nothing shows them their compliance status per listing before it's too late.

**The Aha moment:** within 30 seconds of opening the app, the host sees, for every listing, whether it is legally allowed to operate right now, and exactly what to fix first.

## Screens

### 1. Portfolio overview (home)
- A headline score: "**1 of 4 listings compliance-complete**", with a progress ring.
- One card per listing: photo placeholder, name, city, region, and an overall status badge:
  - 🟢 **Compliant**: all checks pass
  - 🟠 **At risk**: something expires or fails within 30 days
  - 🔴 **Action needed**: a check is failing now; a platform may delist
- Each card shows 4 small check icons: **Licence**, **Channel sync**, **Guest registry**, **Building**.
- A top banner for the most urgent issue, for example: "Casa Albaicín: your regional registration number is missing on Booking.com. Booking.com may hide this listing."
- Sort listings by urgency (red, then orange, then green).

### 2. Listing detail
Click a card to open its detail page with 4 check sections:

1. **Regional licence:** registration number, region, issuing authority, status (valid / pending / expired / missing), expiry date, and a "What this region requires" expandable panel with 3–4 plain-language bullets per region (mock content for Andalucía, Comunitat Valenciana, Madrid, Canarias, Baleares). Each panel shows "Last verified: [date] by legal partner" and a disclaimer: "General information, not legal advice."
2. **Channel sync:** a table of connected channels (Airbnb, Booking.com, Vrbo, Direct site) showing whether the registration number displayed on each matches the official one: ✅ Match / ⚠️ Mismatch / ❌ Missing. A **"Sync to all channels"** button that turns every row green with a short animation.
3. **Guest registry (SES.Hospedajes):** a list of upcoming and recent stays with the submission status for each (Submitted on time / Due in Xh / Late / Missing data). An **"Auto-submit"** toggle. A "Proof of submission" link per stay that opens a mock receipt.
4. **Building community:** status of the owners' community approval (Approved / Not required / Unknown / Restricted), a field to upload the community minutes (mock), and a note that communities can approve, limit or ban tourist use by a 3/5 majority.

At the top of the detail page, show a **"Fix next"** guided panel: the single most important action, a one-line explanation of the risk, and a button that walks the host through it in 2–3 steps.

### 3. Alerts
A timeline of alerts sorted by urgency, for example:
- "Licence for Ático Malvarrosa expires in 21 days."
- "2 guest-registry submissions due in the next 24h."
- "New rule in Comunitat Valenciana: review your listing before 15 Jan."
Each alert has **Fix now** and **Snooze** actions. Never auto-unpublish a listing: the host is always in control.

### 4. Experiment panel (for the case study)
A collapsible panel at the bottom-right, labelled "Experiment view", that shows:
- **Primary metric:** 30-day compliance-complete rate for the current portfolio (live, updates as the user fixes things).
- **Guardrail:** share of listings live and bookable (must not drop).
- A simple event log of tracked events (see below), with timestamps.

## Mock data

**Marta's portfolio (4 listings):**
1. *Ático Malvarrosa*, Valencia (Comunitat Valenciana): licence valid but expires in 21 days → 🟠
2. *Casa Albaicín*, Granada (Andalucía): registration number missing on Booking.com → 🔴
3. *Estudio Malasaña*, Madrid: all checks pass → 🟢
4. *Apartamento Las Canteras*, Las Palmas (Canarias): all checks pass, 1 guest-registry submission due in 6h → 🟠 → becomes 🟢 when auto-submit is on

**Thomas's portfolio (1 listing):**
- *Piso Soho*, Málaga (Andalucía): licence pending, building status unknown, mismatch on Airbnb → 🔴. Show an extra hint for non-residents: "Managing from abroad? Invite a local co-host to receive alerts."

## Event tracking (mock, shown in the Experiment panel)
Track and log these events with timestamp, persona and listing:
`hub_opened`, `listing_viewed`, `fix_next_clicked`, `sync_all_clicked`, `auto_submit_enabled`, `alert_fixed`, `alert_snoozed`, `listing_became_compliant`.

## Design
- Clean, calm, trustworthy: lots of white space, rounded cards, one accent colour (deep teal) plus traffic-light status colours.
- Plain language, no legal jargon; Spanish official terms shown in italics with an English explanation (for example *SES.Hospedajes: Spain's guest-registry system*).
- Language: English UI, with a language toggle stub (EN / ES) that only switches the header labels.
- Fully responsive; must work well on mobile (hosts check on the go).
- Footer: "Concept prototype for a product case study. Mock data only. Not affiliated with any company."

_____

## Follow-up prompt · Rule watch (AI regulatory watch)

> Sent as a second prompt to the same Lovable project, to show the [AI regulatory watch](../05-concept/ai-regulatory-watch.md) from the host's side.

Adds a **Rule watch** section to the Alerts tab with two mock alerts, each showing status, the listing it applies to, what changes, what to do, a key date, the source and "Verified by legal partner · [date]":
- **Being drafted · heads-up** — a draft city rule in Valencia that would affect Ático Malvarrosa; no action yet, check that licence and application dates are saved.
- **In force · action needed** — the registration number must appear on every channel; Casa Albaicín is missing it on Booking.com; "Fix now" opens the existing channel-sync fix.

Plus a "nothing else changed for your other listings this month" line, an "AI-detected, legal-partner reviewed, not legal advice" note, Rule watch badges on affected listing cards, Spanish translations, and four tracked events: `rule_alert_viewed`, `rule_alert_followed`, `rule_alert_dismissed`, `rule_alert_fix_clicked`. All rules shown are example data.
