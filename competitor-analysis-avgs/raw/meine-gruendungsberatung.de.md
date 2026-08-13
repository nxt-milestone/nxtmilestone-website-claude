# Competitive Intelligence Report: meine-gruendungsberatung.de

**Research date:** 2026-08-13.

---

## 1. Profile

- **[Data]** Brand ("Marke") of Limburg Consulting – Fuhr, Schmitt, Weise Partnerschaftsgesellschaft, Unternehmensberater, HQ Lindemannstraße 13, 40237 Düsseldorf. HR PR 4288 (AG Essen), USt-ID DE233728038.
- **[Data]** Parent firm founded 2003 (21+ years). Age of this specific sub-brand/domain unconfirmed [data gap — Wayback rate-limited].
- **[Data]** Team: 7 consultants named with real bios (BWL degrees, IHK certifications, Vodafone/corporate experience, prior founders themselves).
- **[Data]** Offerings: AVGS-funded Gründercoaching, Businessplan-Erstellung, Finanzierungsberatung, Vermarktungskonzept, Gründungsplan, free downloadable business-plan template, 3-question Gründungszuschuss eligibility quiz on high-intent pages.
- **[Estimate]** "Deutschlandweit" claim vs. reality: ~25 city landing pages skew heavily toward NRW/Rhineland-Ruhr (Düsseldorf, Dortmund, Essen, Köln, Bochum, Duisburg, Wuppertal), with only a few outliers (Berlin, Leipzig, Saarbrücken, Kaiserslautern, Koblenz) — SEO-driven nationwide positioning layered on a regionally-concentrated core business.
- **[Data, self-reported]** Claims "100+ founders annually" — unverified.

## 2. Trust & Certification Signals

- **[Data]** ProvenExpert: **382 reviews, 4.93/5, 100% recommendation**, badge embedded live on-site linking to public profile.
- **[Data]** Schema.org `aggregateRating` on-page shows **5.0/5 from only 75 ratings** — stale/inconsistent vs. the live 382-review ProvenExpert figure.
- **[Data]** Only **one named testimonial** ("Niklas") in page copy despite hundreds of reviews existing off-site — real under-use of available proof.
- **[Data, important finding]**: AZAV certificate displayed **only as an image** (alt text: "Zertifikat Gründungsberatung zugelassener Träger"). **The word "AZAV" does not appear anywhere as indexable text** on homepage, `/avgs-coaching/`, or `/avgs-coaching-deutschlandweit/`, and **no Zulassungsnummer is published** in text form.
- **[Knowledge-Based]** "TÜV Rheinland" accreditation referenced in a WebSearch snippet but not confirmed on any directly-fetched page (a "TÜV" match on the English page was a false positive in minified JS).
- **[Knowledge-Based]** VDSG membership mentioned 5x on homepage, not independently verified.
- **[Data]** No case studies/Erfolgsgeschichten page anywhere in the 41-page sitemap.
- **[Data]** Impressum fully compliant.

## 3. SEO & On-Page Structure

**Homepage**
- Title: "Gründungsberatung Startseite - Für Existenzgründer: meine-gruendungsberatung.de"
- Meta description present, benefit-oriented.
- H1: "Hallo Existenzgründer!" — only **1 H2**, **0 H3** despite many visual section headers (rendered via Avada/Fusion-builder divs/spans, not semantic headings).
- ~1,158 words.
- 1 JSON-LD block (`ProfessionalService`) with full NAP, opening hours, stale aggregateRating (5.0/75).
- Canonical correct, robots `index, follow`.
- ~25 city-specific landing pages linked from footer/nav.

**AVGS landing page** (`/avgs-coaching/`)
- Title: "AVGS Coaching - Für Existenzgründer: meine-gruendungsberatung.de"
- H1: "AVGS Coaching deutschlandweit" — **0 H2, 0 H3** — no subheadings at all in markup.
- ~980 words. Schema: identical `ProfessionalService` JSON-LD reused verbatim from homepage (not page-specific).
- Deeper regional variant `/avgs-coaching-deutschlandweit/` has ~2,652 words but **still zero "AZAV" text mentions.**

**Site architecture**: WordPress + Avada/Fusion Builder + Yoast SEO. 41 static pages, 93 blog posts, blog categorized into 6 taxonomies (Aktuelles, Allgemein, Finanzierung, Förderung, Gründerwissen, Praxistipps). Blog index at `/gruendermagazin/`, flat root-level post slugs.

## 4. Content Strategy

- **93 published blog posts** [Data, post-sitemap.xml].
- Cadence: bursty — ~70 posts clustered Aug-Dec 2024 (initial buildout), then long gaps, a burst of 7 posts on one day (2026-01-04), then scattered singles through 2026-06-12. Sprint-then-silence pattern, not steady editorial rhythm.
- Adjacent-topic coverage strong and broad: Fördermittel (3-part series: NRW.Bank, KfW, Bürgschaftsbank NRW), Businessplan (multiple posts + free template), Finanzierung (Mikrokredit, Finanzplan), Gründungszuschuss (dedicated pages + posts, Einstiegsgeld), Steuern/Buchhaltung, Rechtsform/Scheinselbstständigkeit, Marketing (Kaltakquise, Pitch Deck, Elevator Pitch), plus lifestyle topics (Zeitmanagement, Urlaub für Selbstständige).

## 5. Strengths

1. Deep, credentialed team page (7-8 named consultants, real bios) — strong E-E-A-T signal.
2. Genuinely strong independent social proof off-site (382 ProvenExpert reviews, 4.93/5), actively linked from homepage.
3. Backed by an established 20+ year consulting firm (Limburg Consulting), not a lead-gen shell site.
4. Solid local-SEO footprint (~25 city pages) reinforcing regional relevance while claiming nationwide reach.
5. Large content library (93 posts) with good breadth across the AVGS-adjacent funnel.
6. Interactive eligibility quiz on conversion-critical pages — good lead-qualification UX.
7. Sitewide Schema.org ProfessionalService markup with full NAP; multiple contact channels + English pages.

## 6. Weaknesses

1. **Thin semantic heading structure**: homepage 1×H1/1×H2; primary AVGS page 1×H1/0×H2/0×H3 — real on-page SEO deficiency masked by visual styling.
2. **"AZAV" never appears as text anywhere checked** — core trust/search term exists only inside an unreadable certificate image, no Zulassungsnummer published. Both an SEO gap and a GEO/AI-citability gap (AI answer engines can't cite a credential that only exists as a JPEG).
3. Schema aggregateRating (5.0/75) stale vs. live ProvenExpert (4.93/382).
4. Only one embedded testimonial despite hundreds of reviews elsewhere — social proof under-leveraged on-site.
5. No case-studies/success-stories page anywhere in the 41-page sitemap.
6. Identical, non-page-specific ProfessionalService JSON-LD reused across pages instead of Service/FAQPage/Course schema.
7. Inconsistent blog cadence (sprint-then-silence).
8. Flat, non-hierarchical blog URL structure.
9. "Deutschlandweit" positioning only loosely supported by an actually NRW/Ruhr-concentrated city-page footprint.

## 7. Data Gaps

- Exact age/launch date of the meine-gruendungsberatung.de domain (Wayback rate-limited).
- No independent traffic/ranking data pulled.
- TÜV Rheinland accreditation unconfirmed on operator's own site.
- VDSG membership not independently verified.
- Real client volume/success-rate figures beyond self-reported "100+ founders/year."
- Whether 25+ city pages reflect genuine local presence or are pure SEO landing pages.
- No pricing info for any private-pay (non-AVGS) offering.
