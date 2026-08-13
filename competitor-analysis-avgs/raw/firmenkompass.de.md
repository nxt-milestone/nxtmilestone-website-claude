# Competitive Intelligence Report: firmenkompass.de

**Research date:** 2026-08-13. Verified live via direct HTTP fetch of firmenkompass.de (sitemap, 4 sampled landing pages, homepage, /avgs/, /ueber-uns/, /impressum/, /bildungstraeger/, /fuer-arbeitsagenturen-und-jobcenter/) plus WebSearch corroboration (LinkedIn, Trustindex, Creditreform).

---

## 1. Profile

- **[Data]** Firmenkompass GmbH, Bockenheimer Landstraße 2-4, 60306 Frankfurt am Main. AG Frankfurt, HRB 134633, USt-ID DE367693142, GF Eileen Tambor.
- **[Data]** Founded 2023.
- **[Data]** 2-10 employees (LinkedIn); /ueber-uns/ names 8 people with bios (CEO/Coach, Head of Sales, Head of Startup & Funding Advisory — claims ex-Binance/eToro, Head of Business Growth & Strategy, Head of Tech, coaching/digital roles, Operations). Self-reported claims — [Knowledge-Based, verify independently].
- **[Data]** 78 LinkedIn followers — thin relative to claimed 1,400+ clients.
- **[Data]** Offering: AVGS-funded Gründungscoaching, 100% online, 0€ Eigenanteil with approved voucher. 9 certified modules (Gründeranalyse, Businessplan Text/Zahlen, Finanzierung, Unternehmensorganisation, Marketing & Vertrieb, Website-Erstellung, Onlineshop-Aufbau, Digitalisierung & KI), up to 125 Unterrichtseinheiten, full/part-time options.
- **[Knowledge-Based]** Self-declared "only AZAV-certified provider in Germany offering certified website/e-commerce building as part of AVGS" — unverifiable against a market-wide list.
- **[Data]** Multilingual delivery: DE/EN/TR/RU/UA — concrete edge for migrant/foreign-national founders.
- **[Data]** Dedicated B2G page targeting Arbeitsagenturen/Jobcenter directly — a distribution-side move beyond organic search, positions for direct caseworker referrals.
- **[Data]** Homepage animated counters (raw `data-to-value` attrs): 1,400+ begleitete Gründer/innen, 10+ Jahre Erfahrung, 100% förderfähig, 98% Kundenzufriedenheit. **[Assumption]**: "10+ Jahre" likely refers to team members' individual coaching backgrounds since the legal entity itself is only 3 years old (founded 2023) — not necessarily dishonest but shouldn't be taken at face value.
- **[Data]** Trustindex.io: 5.0/5 from 73 reviews (methodology unverified). 3 curated homepage testimonials naming specific coaches (first name + last initial).
- **[Data]** AZAV certification with specific, checkable registration: Träger-Nr. T-04665-3218, certified by TQCert GmbH Kassel, Maßnahme-Nr. 419/436/24 (Vollzeit) / 419/450/24 (Teilzeit), valid until 23 July 2029. **This is a materially stronger trust signal than a generic "AZAV-zertifiziert" badge** — nxtmilestone currently shows no AZAV info at all.

## 2. Programmatic SEO — the core finding

**Scale [Data, directly counted from live sitemap]**: 181 total indexed URLs, of which **143 (≈79%) are location-specific landing pages**. Sitemap last modified 2026-07-27 — actively maintained.

Two URL/keyword-variant batches:
- `/avgs-gruendungscoaching-{stadt}/` — 80 pages (northern/eastern Germany: Berlin, Hamburg, Brandenburg, MV, Rhineland-Palatinate, Saxony-Anhalt)
- `/avgs-gruendercoaching-{stadt}/` — 63 pages (NRW, Hesse, Thuringia, Saxony)

District-level granularity confirmed exactly as suspected: Berlin has 6 borough pages (Charlottenburg, Marzahn, Pankow, Neukölln, Mitte, Spandau) + 1 city-wide; Hamburg has 5 borough pages (Wandsbek, Harburg, Eimsbüttel, Bergedorf, Altona) + 1 city-wide. No other city gets this treatment — deliberate long-tail play where search-volume density justifies it.

**How much do pages differ — thin-to-medium, with a confirmed QA failure:**
- Meta descriptions: near-verbatim template, only city swapped.
- H2 structure: fixed template repeated across every page in a batch, only city token changes.
- Genuine localization exists in subheads/some body copy (Charlottenburg: "City West"; Marzahn: "unterschätzter Osten Berlins"; Köln: "NRWs Medien- und Startup-Metropole"; Dortmund: "Technologie- und Logistikstadt").
- **Confirmed QA failure** [Data, directly inspected]: the Berlin-Marzahn page's body repeatedly references "Berlin-Pankow" instead of Marzahn — 23 occurrences of "Pankow" vs 16 of "Marzahn," including wrong-district factual claims about which Agentur für Arbeit/Jobcenter is responsible. Only title, meta description, URL, H1 correctly say Marzahn. **Also a typo in that same H1**: "AVGS Gründungs**o**aching Berlin-Marzahn" (missing the "c"). Strong evidence of an unreviewed template/LLM-generation pipeline.
- ~1,270-1,570 words/page (incl. nav/footer).
- `avgs-gruendercoaching-freital` and `-freital-2` both exist simultaneously — likely an uncleaned duplicate/test page.

**Strategy**: capture long-tail "AVGS Gründungscoaching [Stadt/Stadtteil]" queries at scale, disproportionate district-level investment only where Berlin/Hamburg search volume justifies it. Framed as "online coaching for founders in [city]," not fake local offices — avoids NAP-consistency risk.

## 3. Trust & Certification Signals

- AZAV badge + specific Träger-Nr./Maßnahme-Nr. displayed on homepage, /avgs/, /ueber-uns/ — specific and checkable.
- Certifying body named: TQCert GmbH, Kassel.
- "Vertrauensvolle Partner" logo row: Bundesagentur für Arbeit, Jobcenter, BAFA, BMAS, KfW, Schmidt Partners, DataGuard, Allianz, TQCert, DAkkS. Note: displaying government-agency logos alongside a private brand risks overstating an official partnership — [Knowledge-Based, verify independently].
- Team page: 8 named individuals with role descriptions; Impressum discloses "some website images generated using AI (Google Gemini)" — unclear if this extends to team photos [flag for visual verification].
- 3 named (first name + last-initial) testimonials referencing specific coaches.
- Trustindex: 5.0/5, 73 reviews (external, methodology unverified).
- No case studies found anywhere in the crawl.

## 4. SEO & On-Page Structure (sampled pages)

| Element | Berlin-Charlottenburg | Berlin-Marzahn | Köln | Dortmund |
|---|---|---|---|---|
| Title | AVGS Gründungscoaching Berlin-Charlottenburg \| gefördert | AVGS Gründungscoaching Berlin-Marzahn \| gefördert | AVGS Gründercoaching Köln \| 100% gefördert | AVGS Gründercoaching Dortmund \| 100% gefördert |
| Meta description | Template, city-swapped | Template, city-swapped | Template, city-swapped | Template, city-swapped |
| H1 | "...City West" | "...unterschätzter Osten Berlins" (typo: "Gründungsoaching") | "...NRWs Medien-/Startup-Metropole" | "...Technologie-/Logistikstadt" |
| H2 count | 8 | 7 (wrong-district content) | 7 | 7 |
| JSON-LD | BreadcrumbList only | BreadcrumbList only | BreadcrumbList only | BreadcrumbList + FAQPage |
| Word count | ~1,280 | ~1,570 | ~1,330 | ~1,280 |

Homepage carries a richer `@graph`: EducationalOrganization/Organization, WebSite, WebPage, ImageObject, FAQPage schema. **Location pages under-invest in schema relative to homepage** — FAQ schema present on only some pages despite all having visible FAQ sections; no Course/LocalBusiness/Service schema anywhere in location pages.

Built on WordPress + Rank Math SEO plugin.

## 5. Content Strategy

- **No blog, Ratgeber, or Magazin section exists anywhere** on the site (checked nav, homepage, full 181-URL sitemap).
- Content beyond location pages: core `/avgs/` pillar page (~2,500-3,000 words, 9 module sub-pages `/avgs/modul-1-...` through `-9`), a few founder-resource pages (Businessplan, Gründungszuschuss, Einstiegsgeld, Tragfähigkeitsbescheinigung, Gründerzuschuss-E-Book), small "für Unternehmen" section, B2G page.
- Module sub-pages are product-page-like, not educational/blog content.
- **Conclusion**: content strategy is almost entirely programmatic-SEO- and product-page-driven — no editorial/thought-leadership engine. A genuine gap nxtmilestone could exploit.

## 6. Strengths

1. Programmatic SEO at real scale: 143 location pages for a 2-10 person company, with data-informed district-level prioritization (Berlin/Hamburg only).
2. Framing avoids fake-local-presence NAP risk ("online coaching for founders in [city]").
3. Specific, checkable AZAV registration numbers + named certifying body (TQCert) — more credible than a vague badge.
4. Genuine city-flavored copy variation (not pure mail-merge).
5. Distinct B2G page targeting Arbeitsagenturen/Jobcenter directly.
6. Multilingual delivery (5 languages) — concrete differentiator for non-native-German founders.
7. Named team with specific (if unverified) claimed backgrounds.
8. Homepage has properly implemented Organization + FAQPage + WebSite schema.

## 7. Weaknesses

1. **Confirmed QA failure**: Berlin-Marzahn page's body substantially describes Berlin-Pankow instead (wrong Jobcenter/Agentur referenced), plus a typo in its own H1 — hard evidence of an unreviewed template/AI-generation pipeline.
2. Thin, near-verbatim templated meta descriptions/H2 structure across dozens of pages — classic doorway-page risk pattern.
3. Inconsistent schema implementation across location pages.
4. No blog/content-marketing layer — non-location long-tail/informational queries uncaptured.
5. Very small social footprint (78 LinkedIn followers) vs. "1,400+ founders" claim.
6. "10+ Jahre Erfahrung" claim sits awkwardly next to 2023 founding date.
7. Modest, not independently cross-verified review count/source (Trustindex, 73 reviews).
8. At least one duplicate/orphaned test page in sitemap (freital / freital-2).

## 8. Data Gaps

- No access to actual organic rankings/traffic/conversion data for location pages.
- Trustindex figures not cross-verified against Google's own listing.
- Could not visually confirm team photos are real vs. AI-generated despite the Impressum's AI-image disclosure.
- Self-reported coach backgrounds (Binance, eToro) unverified externally.
- No per-page publish dates in sitemap — historical build-out timeline is inferred, not confirmed.
- No visibility into paid-search/ads activity or CRM/lead-gen tooling.
- Only one district-page content-mismatch bug (Marzahn/Pankow) confirmed — scope across all 143 pages not fully audited.
