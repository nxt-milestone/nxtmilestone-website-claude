# Competitive Intelligence Report: 1a-startup.de

**Research date:** 2026-08-13. All web data reflects live state as of this date unless noted. Sources: direct WebFetch/curl of live pages, WebSearch, ProvenExpert review page.

---

## 1. Profile

- **Legal entity** [Data]: Sole proprietorship ("Einzelunternehmen"), full name "1a-STARTUP Unternehmensberatung für Existenzgründung, Marketing und Fördermittel," proprietor Dagmar Schulz. Registered address: Humboldtstr. 97-99 (Hinterhof), 40237 Düsseldorf. USt-IdNr DE322896720. No Handelsregister number found (consistent with sole-proprietorship status — not a GmbH/UG). Business license under §34c GewO (Gewerbeordnung, for loan-mediation-adjacent activity) issued 2018-03-07 by Stadt Düsseldorf. [Data, source: Impressum page]
- **Founded** [Data]: 2009 by Dagmar Schulz. As of 2026 that is 17 years — **the "~17 years" claim checks out arithmetically** given the 2009 founding date. However, some on-page copy still says "15+ years" [Data] — likely stale marketing copy not updated since ~2024, a minor internal-consistency flag rather than a false claim.
- **Team size** [Data, source: LinkedIn via WebSearch snippet — not independently opened, verify directly]: LinkedIn lists company size as 2–10 employees. Team page shows 1 principal (Dagmar Schulz) plus ~6 named freelance/partner specialists (financing expert, digitalization/AI expert, crisis-coaching partner, copywriter, web/graphic designer, PR consultant) plus unnamed tax/legal partners. This reads as a **solo-consultant-plus-freelance-network model**, not an in-house multi-consultant team — relevant competitive contrast if nxtmilestone has a larger in-house team.
- **Offerings** [Data]: AVGS-funded Gründungscoaching (the core AZAV/AVGS product), free 30-min initial consultation, paid online seminars/courses (via TutorLMS plugin) with certificates, business-plan review services, "Female Edition"/"SHE CAN" women-founder coaching, customer-acquisition coaching, mental coaching for founders, SME/Mittelstandsberatung, Marketing services, Fördermittel (funding/grants) advisory, plus two self-published books sold on-site (~€25).
- **Target audience** [Data]: Primarily unemployed/threatened-by-unemployment individuals eligible for AVGS vouchers (core AZAV segment), plus general founders/SMEs, with a distinct sub-brand for women founders and a "45plus" segment (book: "Existenzgründung 45plus").
- **Traction signals** [Data]: Claims 1,500+ founders supported since 2009 (homepage) vs. an older "1,000+ founders" figure surfaced in one search snippet [Estimate — likely an outdated cached figure, homepage's 1,500+ is the current number]. 375+ total reviews aggregated on ProvenExpert (96 published directly, 285 imported from 5 external sources) — a large review corpus for a solo-consultancy. Active event calendar (free consultations, "Startup Week," webinars) running through Sept 2026 at time of check, indicating ongoing lead-gen activity. Media mentions claimed: ARD, Business On, Neue Ruhr Zeitung, SHE Works, Startup Valley, VGSD, Westdeutsche Zeitung [Data, unverified individually — treat as [Knowledge-Based — verify independently] until each outlet mention is confirmed].

## 2. Trust & Certification Signals

- **AZAV / "zugelassener Träger" display** [Data, verified in raw HTML]: AZAV "Maßnahmenzulassung" seal image present on-page, and body copy on the AVGS blog/landing page explicitly states "von der DEKRA geprüfter Träger" ("DEKRA-audited/certified provider"). This is a **verified live claim on the page**, not fabricated — though the specific accreditation/measure-number or DEKRA certificate ID is not shown on the pages fetched. **No explicit Trägerzulassungsnummer or measure ID was found on the AVGS page, homepage, or Impressum** — this is a gap.
- **DEKRA certification** [Data]: Referenced as "DEKRA-certified training organization" / Dagmar Schulz individually described as "DEKRA-zertifizierte Beraterin für die Arbeitsagentur (AVGS)." No certificate number or DEKRA registry link surfaced.
- **Reviews** [Data, verified via ProvenExpert page fetch]: Overall rating **4.94/5** based on 96 directly-published reviews (out of 385 submitted, ~99% publication rate), plus 285 reviews aggregated from 5 external sources. Rating breakdown of visible set: 88 five-star, 8 four-star, 0 at 3 stars or below. Review date range: October 2024 – July 2026 (live, actively-maintained stream). No dedicated Trustpilot presence found.
- **Testimonials/case studies** [Data]: ~23 detailed, named client success stories with real names, photos, linked businesses. Outcomes qualitative only — **no quantified outcome metrics** (no € amounts, no time-to-launch).
- **Books as authority signal**: Two self-published books sold directly on-site, each with ~15 displayed customer reviews.

## 3. SEO & On-Page Structure

**Homepage (`https://www.1a-startup.de/`)**
- Title: `Existenzgründer- und Unternehmensberatung Düsseldorf` (48 chars, generic/location-anchored).
- Meta description: keyword-dense list, ~144 chars, reads as keyword list not persuasive copy.
- Single H1 (137 chars, keyword-stuffed). 13 H2s. ~1,560 words.
- **Schema.org/JSON-LD**: RankMath-generated (Organization/WebSite/WebPage/Person). **Technical bug**: `Organization` schema's `url` field points to `staging.1a-startup.de` instead of production — leftover staging artifact.
- CMS: WordPress 7.0.4, Divi theme, TutorLMS 4.0.4, WP Download Manager.
- robots.txt / sitemap.xml both returned HTTP 403 to plain curl (bot/WAF protection) — inconclusive, not confirmed blocked.

**AVGS landing page (`/blog/avgs-gruendungscoaching-ihr-schluessel-zum-erfolg/`)**
- Title: `AVGS-Gründungscoaching: Ihr Schlüssel zum Erfolg! - 1a-STARTUP`
- Meta description: **only 36 characters** ("AVGS-Gründercoaching Arbeitsagentur") — significant weakness, keyword fragment not compelling copy.
- Single H1, 5 H2s, 4 H3s. ~1,946 words — solid pillar-page depth.
- Schema present, `datePublished` 2024-04-24, `dateModified` 2025-03-05 — **~17 months stale** as of research date despite being a key funnel page.
- Covers Fördermittel ✓, Businessplan ✓ (light), Finanzierung ✓, Gründungszuschuss ✓ (dedicated section).
- URL nested under `/blog/` despite being a commercial/service landing page — blurs editorial vs. conversion intent; inconsistent with other pages at root level.

## 4. Content Strategy

- Active blog: ~2-4 posts/month as of mid-2026 (4 dated samples June-July 2026 confirm cadence).
- Categories: Existenzgründung, Fördermittel, Marketing. All requested adjacent topics covered.
- Notable: a post directly targets competitor-comparison intent — "AVGS-Träger auswählen: Worauf Sie bei der Gründungsberatung achten sollten" (2026-06-11) — i.e. actively competing for "how to choose an AVGS provider" queries.
- Multi-channel: paid video/live seminars (TutorLMS), webinars, YouTube ("1aStartup"), Instagram/Facebook/TikTok/Pinterest/LinkedIn.
- Freshness concern: cornerstone AVGS page not modified since March 2025 despite active blog cadence elsewhere.

## 5. Strengths

1. Deep, verifiable trust stack for a solo operator: 375+ reviews, 4.94/5, named testimonials with photos, two authored books, DEKRA/AZAV badges displayed on-page.
2. 17 years continuous operation (2009-2026), 1,500+ founders claimed.
3. Active multi-format content engine (blog 2-4x/month, webinars, paid courses, YouTube/social).
4. Already publishing content targeting "how to choose an AVGS-Träger" comparison queries — direct competitive-SEO awareness in exactly nxtmilestone's space.
5. Segment diversification: women-founder and 45+ sub-offers.
6. Solid cornerstone-page depth/structure on core AVGS page (~1,946 words, clean heading hierarchy, schema present).

## 6. Weaknesses

1. Very thin meta description on the money page (36 chars) — concrete, fixable gap nxtmilestone can beat directly.
2. Technical schema bug: staging URL leaked into production Organization schema.
3. Stale cornerstone content: AVGS page unrefreshed for ~17 months.
4. URL/architecture confusion: commercial pages nested under `/blog/`.
5. No quantified outcome metrics in testimonials (qualitative only).
6. Thin bench beyond the founder: 2-10 employees, mostly freelance/partner network rather than in-house team.
7. No visible AZAV Trägerzulassungs-/Maßnahmenzulassungsnummer despite badge/text claims.
8. Crawl-directive opacity: robots.txt/sitemap.xml returned 403 to non-browser fetch.

## 7. Data Gaps

- DEKRA certificate/registration number and AZAV Trägerzulassungsnummer not concretely surfaced.
- Google Business Profile review count/rating not independently opened.
- Trustpilot presence unconfirmed as absent vs. unindexed.
- Full blog archive size not measured (only ~20+ recent titles sampled).
- robots.txt/sitemap.xml contents inaccessible via plain curl (403).
- Exact team headcount and employee-vs-freelancer split not confirmed.
- Media mentions (ARD, Business On, etc.) individually unverified.
- Paid seminar pricing/enrollment volume not surfaced.
- No paid-search/ad-spend check performed (Google Ads Transparency / Meta Ad Library).
