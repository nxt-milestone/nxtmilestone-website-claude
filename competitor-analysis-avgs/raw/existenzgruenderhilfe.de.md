# Competitive Intelligence Report: existenzgruenderhilfe.de

**Research date:** 2026-08-13. Direct HTTP fetches (curl), WebFetch renders, and WebSearch queries against third-party listing sites.

---

## 1. Profile

- **[Data]** Existenzgründerhilfe Naujoks und Marschner GmbH, General-Pape-Str. 18, 12101 Berlin. HRB 162774 B (AG Charlottenburg), USt-IdNr DE297285126. GF: Norbert Naujoks, Torsten Marschner.
- **[Data]** Founded 1997 by Naujoks; Marschner joined as partner 2001. ~29 years in market.
- **[Data]** Offerings: AVGS-funded 1:1 Gründungsberatung, paid Existenzgründerseminare (in-person multi-city + online), Businessplan-Workshops, Freiberufler advice, women-specific AVGS program, "Auswanderer" (emigrant) offshoot tied to Mallorca case studies.
- **[Data]** Team: 2 GF, 2 assistants, 7 named "Beraternetzwerk" consultants with credentials (Diplom-Kaufmann, MBA, Dr., one Prof. Dr.). Claims coverage in all 16 Bundesländer / ~22 locations [unverified directly, WDB page returned connection error].
- **[Data]** ">9,000 erfolgreiche Gründungsaufträge" (own site) vs "9,700 successfully coached participants" (Springest.de) — close but not identical, suggests site lags third-party figure. "77% still active after 3 years" claim — **[Knowledge-Based, unverified primary source]**.

## 2. Trust & Certification Signals

- **[Data]** "Zertifiziert nach AZAV" on homepage, AVGS page, Gründercoaching page. **No AZAV Zulassungsnummer or issuing Stelle displayed anywhere.**
- **[Data]** Listed on WDB-Suchportal and IHK WIS anbieter directory (per WebSearch result titles; WDB page itself could not be fetched directly — **Knowledge-Based, verify independently**).
- **[Data]** Springest.de: 10/10 but only **2 reviews** — thin sample despite perfect score. "4.9/5, 85 reviews" Google figure surfaced via WebSearch summary only, **not independently confirmed**.
- **[Data]** Dedicated `/referenzen-in-der-existenzgruenderberatung` page: **22 named, real founders** with business names and anchor links — genuinely deep reference gallery, stronger than typical star-rating widgets.
- **[Data]** Team bios present with names/roles/qualifications, but no individual photos/LinkedIn links confirmed in raw HTML.

## 3. SEO & On-Page Structure

**Homepage**
- Title: "Existenzgründerhilfe - Existenzgründerseminar - Existenzgründerberatung - Existenzgründerhilfe - Gründungszuschuss" (109 chars, over limit, brand name duplicated, keyword-stuffed).
- Meta description present, listing services.
- H1: "Wir begleiten Sie in die Selbständigkeit". Heading hierarchy loosely semantic (H4s jump straight from H2 in places).
- **~810 words.**
- **Zero JSON-LD/schema.org anywhere, no Open Graph tags found.**
- Meta robots: index, follow.

**AVGS landing page** (`/existenzgruenderberatung-mit-avgs`)
- Title/meta present. H1: "Kostenfreie AVGS-Existenzgründerberatung". ~1,018 words. No JSON-LD.

**Gründercoaching page** (`/gruendercoaching-fuer-existenzgruender`)
- H1: "AVGS-Existenzgründercoaching". **~1,539 words** — deepest page checked. No JSON-LD.

**URL structure**: inconsistent — mix of clean extensionless URLs and legacy `.html` endpoints, suggesting incomplete migration.

**Site scale**: sitemap.xml has **264 URLs**, including ~35 "gruendungsberatung-mit-avgs-in-[stadt]-kostenfrei" city pages, ~34 "anmeldung-fuer-existenzgruenderseminar-in-[stadt]" pages, 17 state-level Businessplanworkshop pages — classic city/keyword doorway-page strategy.

**Freshness**: core AVGS/city pages actively maintained (most-recent lastmod June-July 2026). "Aktuelles" blog hub itself last touched 2023-05-05; individual posts dated to real-world events 2017-2020 — maintenance effort concentrated on conversion pages, not editorial content.

**Technical**: Apache/2.4.68, **PHP 5.6.40 (EOL since Jan 2019)** — notable security/technical liability. No HSTS/CSP/X-Frame-Options headers. No CMS generator tag; front-end libs (bootstrap.min.css, jquery.bxslider, lightbox.js, animate.min.css) suggest a ~2015-2016-era custom/legacy PHP build.

*Methodology note*: a few initial curl requests returned unrelated third-party site content (e.g. akr-consult.de branding) — flagged as a likely transient shared-hosting/edge-cache artifact at the resolved IP, not a confirmed site characteristic; subsequent systematic requests were consistent.

## 4. Content Strategy

- Blog/"Aktuelles": only **~12 total posts** visible.
- Mix of genuinely on-topic advice ("10 Tipps für Existenzgründer aus der Arbeitslosigkeit," Digitalprämien Förderprogramme) and dated PR/lifestyle pieces (Mallorca founder interviews 2017, ex-footballer opening a lounge) — reads as anecdotal marketing, not deliberate SEO/authority content.
- **Cadence effectively dormant since ~2020** (newest dated post 2020-07-09).
- Thin coverage of adjacent topics (Steuer, Rechtsform comparisons, funding-program deep dives) — no FAQ/glossary hub.

## 5. Strengths

1. ~29 years in business (since 1997) — one of the more established AVGS brands.
2. Extensive concrete social proof: 22 named real client case studies + on-page testimonials.
3. Verified, clearly displayed AZAV certification on every key conversion page, reinforced by third-party listings.
4. Credentialed named advisor bench (7 consultants, incl. a Prof. Dr.).
5. Aggressive, currently-maintained local-SEO footprint: 264 indexed URLs, actively updated through June-July 2026.
6. Diversified monetization + thin multilingual (EN/FR/ES) overview pages for international founders.

## 6. Weaknesses

1. Zero structured data on any page tested — no Organization/LocalBusiness/FAQ/Review schema.
2. Blog/content-marketing effectively abandoned since ~2020, tonally inconsistent (startup tips mixed with Mallorca lifestyle pieces).
3. Outdated technical stack: PHP 5.6 (EOL 2019), no modern security headers, 2015-era front-end libraries.
4. Inconsistent URL structure (legacy `.html` mixed with clean URLs).
5. Modest page depth on money pages (810-1,539 words) without schema/FAQ support to compensate.
6. Thin externally-verifiable review volume (Springest: perfect score but only 2 reviews); the oft-cited Google 4.9/5-85-reviews figure unconfirmed via direct fetch.
7. No visible AZAV Zulassungsnummer or named akkreditierende Stelle.
8. Heavy reliance on ~70+ near-duplicate templated city pages — thin/duplicate-content and doorway-page risk.

## 7. Data Gaps

- Google Business Profile rating/count not independently verified (WebSearch summary only).
- WDB-Suchportal listing (AZAV number, course catalog, 22-location count) could not be directly fetched — Knowledge-Based only.
- No backlink/domain-authority/keyword-ranking/traffic data pulled.
- Consultant-network size beyond the 11 named individuals not disclosed.
- Company financials not public (private GmbH).
- Ad spend/paid-search presence not assessed.
- "77% still active after 3 years" stat unconfirmed against a primary source.
