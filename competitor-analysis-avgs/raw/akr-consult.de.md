# Competitive Intelligence Report: akr-consult.de

**Date-stamped:** 2026-08-13 (all live data fetched this date)

---

## 1. Profile

- **[Data]** AKR Consult GbR, Mehringdamm 48, 10961 Berlin. Managing partners: Matthias Karkuschke, Daniel Reichelt. GbR (lightweight partnership), not a GmbH.
- **[Data]** Founded 1 Jan 2014 → ~12 years active. "AKR" = founders' initials (Andres, Karkuschke, Reichelt); co-founder Jens Andres passed away Dec 2019.
- **[Data]** Two structurally separate AVGS service lines under one brand:
  - **AVGS Gründungscoaching** (§45 SGB III): up to 5 combinable modules, 16-92 units over 4-8 weeks (Businessplan & Geschäftsmodell, Marketing & Vertrieb, Finanzen & Förderung, Organisation & Strategie, Gründerperson & Tragfähigkeit).
  - **AVGS Berufs-/Karrierecoaching** (also §45 SGB III): separate landing page/modules (Gründungsformalia, Verträge, Preiskalkulation, Webseite & Online-Marketing, Finanzplan).
  - Plus "Dienstleistungen für Unternehmen" (QM/AZAV consulting for businesses).
  - Niche differentiator: dedicated career coaching for people with disabilities ("Berufscoaching für Menschen mit Schwerbehinderung"), incl. a 2022 interview series.
  - Segmented landing pages by audience: Akademiker, Arbeitssuchende, Gründer/Gründerin, plus a Berlin city page.
- **[Data]** Sister brand: **AKR Services** (akr.services) — consults *other* Bildungsträger on getting AZAV/ISO 9001:2015 certified, based in Potsdam. Implies deeper in-house regulatory expertise than a typical single-service AVGS-Träger, and a second revenue stream.
- **[Data]** Team: 2 active partners (Karkuschke: Dipl.-Volksw., ISO 9001:2015 auditor; Reichelt: M.Sc./Dipl.-Kfm., systemischer Coach, 17+ yrs) plus named/unnamed coaches (BWL, media/film, gastronomy, online marketing, law, "esoteric/spiritual"). Exact headcount not disclosed — team-page counter appears JS-animated, renders "0" in raw HTML [Estimate: small owner-led consultancy, single-digit to low-teens coaches].
- **[Data, self-reported, unverified]**: "mehr als 7000 KundInnen" since 2014, "mehr als 700 zufriedene Kunden pro Jahr."
- **[Data, verified]** ProvenExpert: **64 reviews, 4.90/5** — real, external, credible trust signal. No reviews yet on golocal.de.

## 2. Trust & Certification Signals

- **[Data]** "AKR Consult ist zertifizierter Maßnahmeträger der Bundesagentur für Arbeit nach AZAV" — homepage badge + Impressum. **No Zulassungsnummer displayed.**
- **[Data, verified via 3x repeated clean fetch]**: homepage "Kundenmeinungen zum AVGS Coaching" section contains **no actual testimonial text or star widget in raw HTML** — only a heading and a logo image. Testimonial content is almost certainly JS-rendered (slider/carousel) — **search engines and most GEO/scraping tools likely cannot see it**, despite the strong underlying ProvenExpert rating.
- **[Data]** Named founders with credentials; broader coach roster described by expertise category rather than individual named bios/photos for everyone.
- **[Data]** No structured case-study format found; some blog posts function as light social proof.
- **[Data]** Professional liability insurance via Hiscox SA disclosed in Impressum — a specific trust signal not all competitors disclose.

## 3. SEO & On-Page Structure

Platform: WordPress 7.0.4 + WP Rocket 3.23.1.1 + Yoast SEO.

| Page | Title | H1 | Words | JSON-LD |
|---|---|---|---|---|
| Homepage | "Beratung für Berufstätige und Gründer bundesweit - AKR Consult" | "Willkommen bei AKR Consult - Gute Beratung ist Teamarbeit." | ~1,480 | **None found** (3x clean fetch) |
| AVGS Gründung LP | "AVGS Coaching Gründung & Selbstständigkeit - AKR Consult" | same | ~1,250 | **None found** |
| AVGS Beruf/Karriere LP | "AVGS Coaching für Beruf & Karriere - AKR Consult" | (not checked) | ~1,890 | (not checked) |

- Heading hierarchy (homepage): 1×H1, 3×H2, 9×H3, 3×H4, 4×H5 — proper semantic structure.
- **Schema.org/JSON-LD confirmed absent** on homepage and main AVGS-Gründung page — no Organization/LocalBusiness/Service/FAQPage/Review schema.
- **English version exists**: `/en/akr-lp-en/start-ups-freelancing/` and `/en/akr-lp-en/job-career/`. **hreflang correctly implemented** (en self-ref, de pointing to German page, x-default → German). Only 2 English pages, no English blog.
- URL structure: clean, keyword-rich, segmented by audience and city (`/avgs-coaching-berlin/`).
- Internal linking solid (~19+ unique links on Gründung LP).
- Sitemap: Yoast sitemap_index (post/page sitemaps) + a legacy `akr-lp-sitemap.xml` (last modified 2023, likely stale).
- OG/Twitter tags present and correctly populated.
- robots.txt permissive for Googlebot; blocks `/category/`, `/author/`, `/tag/`; no explicit AI-crawler rules either way.

## 4. Content Strategy

- Blog: **~30 posts total** (post-sitemap, 2018-2025).
- Cadence: bursty, largely dormant — concentrated in 2021 (~a dozen posts), a few in 2022, then a **~3-year gap** (Nov 2022 → Oct 2025) with only one 2025 post.
- Topics: Existenzgründung/Gründungszuschuss guides, motivation-letter mistakes, Business Model Canvas, net-income calc, BAFA-Förderprogramm, Kompetenzenbilanz, disability-focused mini-series (Jan 2022), company milestones, job openings, event participation.
- Content depth: landing pages moderately substantial (1,200-1,890 words); blog posts skew short/news-style rather than deep guides. No visible pillar/cluster structure.

## 5. Strengths

1. Genuine dual-track AVGS offering (Gründung + Beruf/Karriere) under one brand, well-structured landing pages — broader addressable market than Gründung-only competitors.
2. Real external trust signal: 4.90/5 across 64 ProvenExpert reviews.
3. Regulatory depth as differentiator: second brand (AKR Services) consults *other* Bildungsträger on AZAV/ISO 9001 certification.
4. Clean technical SEO fundamentals: correct canonicals, proper heading hierarchy, working hreflang, clean URLs, WP Rocket caching, Yoast sitemaps.
5. Deliberate audience-segmentation landing-page architecture (Akademiker, Arbeitssuchende, Gründer, Berlin).
6. Niche disability/Schwerbehinderung career-coaching angle — underused differentiator in this market.
7. 12 years continuous operation + disclosed professional liability insurance.

## 6. Weaknesses

1. No structured data (JSON-LD) anywhere checked — no Organization/LocalBusiness/Service/Review schema; rich-result and AI/GEO parsing left on the table.
2. Testimonials section effectively invisible to crawlers/AI (JS-rendered, empty in raw HTML) — undermines the otherwise-strong ProvenExpert rating.
3. Blog largely dormant: 3-year near-total gap (late 2022-late 2025), only one 2025 post.
4. No English blog, only 2 English landing pages — limited relevance for Berlin's international founder/expat population.
5. GbR legal form (not GmbH) — smaller "corporate" trust signal on paper.
6. No individual bios/photos for full coach roster — credibility rests mostly on the two named founders.
7. No case studies/structured success stories.
8. Team-size counter is JS-only animated — no static crawlable headcount figure.

## 7. Data Gaps

- Exact current team headcount (JS-rendered, unresolvable via static fetch).
- AZAV Zulassungsnummer not found on-site.
- Pricing for non-AVGS/private services not published.
- No backlink/traffic/keyword-ranking data pulled (no Ahrefs/Semrush query performed).
- Could not confirm explicit AI-crawler allow/block rules in robots.txt (no rule either way found).
- LinkedIn/social presence not directly verified.
- **Methodology note**: multiple raw curl fetches intermittently returned unrelated third-party sites' content (meine-gruendungsberatung.de, die-gruendungsexperten.de, selbststaendigkeit.de) on first request per URL, self-correcting on repeat — very likely a shared-hosting/CDN cache anomaly, not an AKR-side issue. Every data point here was cross-verified via 2-3 repeated clean fetches before inclusion.
