# Skill: SEO Competitive Benchmark From Project Website

## Status
✅ MADURA

## Phase
Investigación + Análisis + Estrategia

---

## Purpose

This skill analyzes a website project folder, deduces the business sector, services, target locations and SEO intent, then performs a competitive SEO benchmark against organic Google results across local, regional, national and international markets.

The goal is not to give generic SEO advice. The goal is to understand what already-ranking websites are doing, extract repeatable patterns, compare them against the provided website, and propose concrete improvements.

---

## Core Principle

Do not ask the user what the sector, city or country is at the beginning.

First inspect the project files.

Then deduce:

- Sector.
- Country.
- Language.
- Main city or target area.
- Services.
- Products.
- Type of business.
- Search intent.
- Conversion goal.
- Current website structure.
- Current menu.
- SEO elements.
- Probable target keywords.
- Probable benchmark locations.

Only ask the user a question if, after inspecting the project files, the critical information cannot be deduced.

---

## When To Use This Skill

Use this skill when the user provides or references a website project folder and wants to:

- Improve SEO.
- Analyze competitors.
- Create local SEO landing pages.
- Benchmark organic Google results.
- Compare their website against ranking competitors.
- Extract SEO patterns from top-ranking pages.
- Improve structure, content, images, menus, conversion and schema.
- Build a better landing or website architecture based on real competitors.

---

## Workflow Overview

Follow this exact order:

1. Inspect the project folder.
2. Deduce business context from the website.
3. Diagnose the current website.
4. Select benchmark locations automatically.
5. Create benchmark keywords.
6. Search Google for each keyword.
7. Filter invalid results.
8. Extract the first 3 valid organic competitors per keyword.
9. Analyze each competitor in depth.
10. Compare competitors against the provided website.
11. Extract global patterns.
12. Recommend improvements.
13. Propose ideal structure, menu, content and architecture.
14. Create a 30/60/90 day action plan.

Do not skip steps.

---

## Phase 1: Inspect The Project Website

Before searching Google, inspect all relevant files in the project folder.

Review, when available:

- HTML files.
- CSS files.
- JavaScript files.
- React components.
- Next.js files.
- Vue files.
- Astro files.
- Svelte files.
- Layout files.
- Route files.
- Config files.
- Metadata files.
- Sitemap.
- Robots.txt.
- JSON-LD.
- Schema markup.
- Images.
- Image filenames.
- Image alt attributes.
- Page titles.
- Meta descriptions.
- Visible page copy.
- Menus.
- Headers.
- Footers.
- Forms.
- CTAs.
- Service sections.
- Product sections.
- Location sections.
- Blog pages.
- Legal pages.
- Contact pages.

---

## Phase 2: Deduce Website Context

From the project files, deduce the following:

- Main sector.
- Business type.
- Country.
- Main language.
- Main city.
- Province, region or community if available.
- Main services.
- Secondary services.
- Products, if any.
- Target customer.
- Main search intent.
- Main conversion goal.
- Current tone of voice.
- Current value proposition.
- Current website structure.
- Current menu.
- Current CTAs.
- Mentioned locations.
- Trust elements.
- Current SEO elements.
- Probable main keywords.
- Probable secondary keywords.
- Initial SEO weaknesses.

Do not invent. If something is uncertain, mark it as `Not detectable`.

---

## Phase 3: Initial Website Diagnosis

Produce this section first:

```markdown
# Initial Diagnosis Of The Provided Website

## Detected Sector
...

## Detected Country, Language And Target Area
...

## Business Type
...

## Detected Services Or Products
- ...

## Main Search Intent
...

## Detected Conversion Goal
...

## Current Website Structure
- Header
- Menu
- Hero
- Main sections
- Services
- Locations
- FAQs
- Contact
- Footer

## Current Menu
List the exact menu items and their order.

## Current Tone Of Voice
...

## Probable Keywords Detected
- Main keyword:
- Secondary keywords:
- Local keywords:
- Service variations:

## Current SEO Elements
- Title:
- Meta description:
- H1:
- H2:
- Schema:
- Internal links:
- Images:
- Alt attributes:
- URLs:

## Initial Problems Detected
- ...

## Unclear Or Missing Information
- ...
```

---

## Phase 4: Automatic Benchmark Location Selection

After analyzing the website, select benchmark locations automatically.
Do not ask the user unless the country or sector is impossible to deduce.

Select locations across these layers:

1. Main city detected in the website.
2. Province, region or community related to the business.
3. Highly competitive city in the same country.
4. National search in the same country.
5. Competitive city in another country from the same continent.
6. Highly competitive city in another continent, preferably the United States when relevant.

Choose locations based on:

- Detected sector.
- Detected country.
- Language.
- Probable demand.
- SEO competition.
- Purchasing power.
- Commercial relevance.
- Digital maturity.
- Locations mentioned in the website.
- Market competitiveness.

Output:

```markdown
# Benchmark Locations Selected

| Layer | Location | Country | Proposed Keyword | Language | Reason |
|---|---|---|---|---|---|
| Main city detected |  |  |  |  |  |
| Province / region |  |  |  |  |  |
| Competitive city in country |  |  |  |  |  |
| National |  |  |  |  |  |
| Same continent |  |  |  |  |  |
| Other continent |  |  |  |  |  |
```

---

## Phase 5: Keyword Creation

Create one main benchmark keyword for each selected location.
Each keyword must combine: main service + location + commercial intent.
Adapt the keyword to the language of the market.

Examples for plumbing:
- `fontaneros en Madrid`
- `fontaneros Comunidad de Madrid`
- `fontaneros España`
- `plombier Paris`
- `plumber New York`

Output:

```markdown
# Benchmark Keywords

| Layer | Keyword | Country | Language | Search Intent |
|---|---|---|---|---|
| Main city |  |  |  |  |
| Province / region |  |  |  |  |
| Competitive city |  |  |  |  |
| National |  |  |  |  |
| Same continent |  |  |  |  |
| Other continent |  |  |  |  |
```

---

## Phase 6: Google Search Rules

For each keyword, search Google and identify the first 3 valid organic competitors.

**Exclude:**

- Ads / Sponsored results / Google Ads / Local Services Ads.
- Google Maps / Google Business Profiles.
- Directories / Marketplaces / Aggregators / Comparators.
- Social networks (YouTube, Facebook, Instagram, LinkedIn, TikTok).
- PDFs / Job boards.
- News results (unless intent is informational).

**Keep only:**

- Real business websites.
- Service pages.
- Local landing pages.
- Optimized homepages.
- Commercial organic pages owned by the business.

If the first results are ads, directories or social networks, skip them and continue until 3 valid organic business websites are found.

For each valid result, record:

```markdown
# Valid Organic Results

| Layer | Keyword | Valid Position | Approx. Google Position | Title | URL | Page Type | Reason Valid |
|---|---|---:|---:|---|---|---|---|
```

---

## Phase 7: Competitor Page Analysis

For every valid competitor URL, visit the page and analyze:

1. URL, domain, page type.
2. Title, meta description.
3. H1, H2, H3, H4 if relevant. Full heading structure.
4. Approximate number of images. Image types. Real / stock / AI / generic.
5. Whether images build trust. Whether they show service, product, team, city, real work.
6. Content tone. Target customer. Main sales argument.
7. Landing structure top to bottom.
8. Menu items and order. Submenus.
9. Whether menu links to services, locations, products, blog, contact, CTA.
10. Services/products shown. Where they appear. Whether they have own URLs.
11. Conversion elements: phone, WhatsApp, form, CTA, sticky CTA, free quote, urgency.
12. Trust elements: reviews, testimonials, guarantees, team photos, certifications, real work examples.
13. Internal links to cities, areas, services, blog.
14. Breadcrumbs.
15. Schema: LocalBusiness, Organization, Service, FAQPage, Review/AggregateRating, BreadcrumbList.

If something cannot be verified: `Not detectable`. Do not invent.

---

## Phase 8: Required Format For Each Competitor

```markdown
## Competitor Analysis: [Domain]

### Basic Data
| Field | Data |
|---|---|
| URL |  |
| Domain |  |
| Layer |  |
| Keyword |  |
| Approx. Google Position |  |
| Page Type |  |

### SEO Metadata
| Element | Content | SEO Observation |
|---|---|---|
| Title |  |  |
| Meta description |  |  |
| Canonical | Not detectable |  |
| Open Graph | Not detectable |  |

### Heading Structure
H1:
H2:
H3:
H2:

### Heading Analysis
- H1 optimized: Yes / No / Partial
- Includes main keyword: Yes / No
- Includes city or location: Yes / No
- Semantic structure: High / Medium / Low
- Observations:

### Image Analysis
| Element | Result |
|---|---|
| Approx. number of images |  |
| Image types |  |
| Real / stock / AI / generic |  |
| Professional quality | High / Medium / Low |
| Images above the fold | Yes / No |
| Reinforce service/product | Yes / No / Partial |
| Build trust | Yes / No / Partial |
| Alt usage | Good / Medium / Poor / Not detectable |

### Tone Of Voice
| Factor | Evaluation |
|---|---|
| Main tone |  |
| Apparent target customer |  |
| Main sales argument |  |
| Closeness | High / Medium / Low |
| Authority | High / Medium / Low |
| Commercial intensity | High / Medium / Low |
| Natural or SEO-forced text |  |

### Landing Structure
| Order | Section | What Appears | SEO / Conversion Function |
|---:|---|---|---|
| 1 | Header |  |  |
| 2 | Hero |  |  |

### Main Menu
| Order | Menu Item | Type | Observation |
|---:|---|---|---|

### Services / Products Detected
| Service / Product | Where It Appears | Has Own URL | Apparent Function |
|---|---|---|---|

### Conversion Elements
| Element | Present | Observation |
|---|---|---|
| Visible phone | Yes / No |  |
| WhatsApp | Yes / No |  |
| Form | Yes / No |  |
| Main CTA |  |  |
| Sticky CTA | Yes / No |  |
| Free quote | Yes / No |  |
| Urgency | Yes / No |  |
| Reviews / testimonials | Yes / No |  |
| Guarantee | Yes / No |  |
| Physical address | Yes / No |  |

### Trust Elements
| Element | Present | Observation |
|---|---|---|
| Reviews | Yes / No |  |
| Testimonials | Yes / No |  |
| Years of experience | Yes / No |  |
| Certifications | Yes / No |  |
| Team photos | Yes / No |  |
| Real work examples | Yes / No |  |

### Internal Linking
| Link Type | Detected | Examples |
|---|---|---|
| Related services | Yes / No |  |
| Locations | Yes / No |  |
| Breadcrumbs | Yes / No |  |
| SEO footer links | Yes / No |  |

### Schema / Structured Data
| Schema Type | Detected | Observation |
|---|---|---|
| LocalBusiness | Yes / No / Not detectable |  |
| Organization | Yes / No / Not detectable |  |
| Service | Yes / No / Not detectable |  |
| FAQPage | Yes / No / Not detectable |  |
| Review / AggregateRating | Yes / No / Not detectable |  |
| BreadcrumbList | Yes / No / Not detectable |  |

### SEO Summary

**Why this URL may be ranking:**
...

**Strengths:**
- ...

**Weaknesses:**
- ...

**Replicable patterns:**
- ...

**How to beat this page:**
- ...
```

---

## Phase 9: Analysis By Benchmark Layer

```markdown
# Layer Analysis: [Layer Name]

## Keyword
...

## URLs Analyzed
1. ...
2. ...
3. ...

## Dominant Page Type
...

## Repeated SEO Patterns
- ...

## Repeated Structure Patterns
- ...

## Repeated Conversion Patterns
- ...

## Competition Level
Low / Medium / High / Very High

## Opportunities In This Layer
- ...

## What The Provided Website Should Learn From This Layer
- ...
```

---

## Phase 10: Global Pattern Extraction

```markdown
# Global Patterns Detected

## 1. On-Page SEO Patterns
- ...

## 2. Heading Patterns
- ...

## 3. Landing Structure Patterns
- ...

## 4. Menu Patterns
- ...

## 5. Service / Product Patterns
- ...

## 6. Image Patterns
- ...

## 7. Tone Patterns
- ...

## 8. Conversion Patterns
- ...

## 9. Trust Patterns
- ...

## 10. Internal Linking Patterns
- ...

## 11. Technical / Schema Patterns
- ...

## 12. International Patterns Worth Adapting
- ...
```

---

## Phase 11: Compare Against Provided Website

```markdown
# Comparison Against Provided Website

## What The Website Already Does Well
- ...

## What The Website Is Missing
- ...

## What Competitors Do Better
- ...

## Structural Changes Needed
- ...

## Menu Changes Needed
- ...

## Content Changes Needed
- ...

## Image Changes Needed
- ...

## Conversion Changes Needed
- ...

## Technical / Schema Changes Needed
- ...

## New Pages To Build
- ...
```

---

## Phase 12: Opportunities

```markdown
# Opportunities Detected

## SEO Opportunities
- ...

## Content Opportunities
- ...

## Conversion Opportunities
- ...

## Visual Opportunities
- ...

## Technical / Schema Opportunities
- ...

## International Opportunities To Adapt
- ...
```

---

## Phase 13: Recommended Ideal Landing Structure

```markdown
# Recommended Ideal Landing Structure

1. Header — Logo, menu, phone, CTA, optional WhatsApp
2. Hero — H1 with service + location, value prop, trust signal, CTAs, professional image
3. Service Overview — Main service explanation, benefits, variations
4. Services / Products — Main + secondary + urgent + specialized + related
5. Why Choose Us — Experience, trust, speed, guarantees, differentiators
6. Locations / Areas — Main city, province, nearby towns, neighborhoods if relevant
7. Process — Step 1, Step 2, Step 3
8. Proof — Reviews, testimonials, case studies, real work examples
9. FAQs — SEO and conversion-oriented questions
10. Final CTA — Phone, WhatsApp, form, free quote
11. Footer — Services, locations, contact, legal, trust elements
```

---

## Phase 14: Recommended Menu

```markdown
# Recommended Menu

| Order | Menu Item | Purpose | Notes |
|---:|---|---|---|
| 1 | Home | Navigation / brand |  |
| 2 | Services | SEO / conversion | Include dropdown |
| 3 | Locations | Local SEO | City/area pages |
| 4 | Cases / Reviews | Trust |  |
| 5 | Blog / Resources | Informational SEO |  |
| 6 | Contact | Conversion |  |
| 7 | CTA Button | Conversion | Phone, quote or booking |
```

---

## Phase 15: Recommended Services / Products

```markdown
# Recommended Services / Products To Highlight

## Main Service
- ...

## Secondary Services
- ...

## Urgent / High-Intent Services
- ...

## Specialized Services
- ...

## Location-Based Services
- ...

## Related Services
- ...
```

---

## Phase 16: Concrete SEO Recommendations

```markdown
# Concrete SEO Recommendations

## Recommended Title Formula
[Main service] in [Location] | [Differentiator / Brand]

## Recommended H1
...

## Recommended H2s
- ...

## Recommended H3s
- ...

## Recommended Word Count
...

## Recommended Number Of Images
...

## Recommended Image Types
- ...

## Recommended Tone
...

## Recommended CTAs
- ...

## Recommended Schema
- LocalBusiness
- Organization
- Service
- FAQPage
- BreadcrumbList
- Review / AggregateRating (only if real and valid)

## Recommended Internal Linking
- Service pages → location pages
- Location pages → service pages
- Blog posts → commercial pages
- Footer → key services and locations
```

---

## Phase 17: Recommended Website Architecture

```
/
  /services/
    /services/[main-service]/
    /services/[secondary-service]/
  /locations/
    /locations/[main-city]/
    /locations/[province-or-region]/
    /locations/[nearby-city]/
  /areas/[neighborhood-or-zone]/
  /case-studies/
  /reviews/
  /blog/
    /blog/[informational-topic]/
  /contact/
```

Adapt to the detected sector.

---

## Phase 18: 30 / 60 / 90 Day Action Plan

```markdown
# 30 / 60 / 90 Day Action Plan

## First 30 Days
- Fix titles, metas and headings.
- Improve main landing structure.
- Add missing CTAs.
- Add missing trust elements.
- Improve menu.
- Add or improve schema.
- Improve images and alt attributes.
- Create first priority service/location pages.

## Days 31-60
- Expand location pages.
- Add secondary service pages.
- Build internal linking.
- Add FAQs with schema.
- Add case studies or testimonials.
- Publish supporting blog content.

## Days 61-90
- Strengthen authority.
- Improve conversion based on user behavior.
- Add more local content.
- Expand international-inspired patterns if relevant.
- Improve technical SEO.
- Monitor rankings and iterate.
```

---

## Final Output Structure

```markdown
# SEO Competitive Benchmark Based On Provided Website

## 1. Initial Website Diagnosis
## 2. Deduced Sector, Country, Language And Intent
## 3. Detected Services / Products
## 4. Benchmark Locations Selected
## 5. Keywords Created For Each Location
## 6. Valid Organic Results Detected
## 7. Individual Competitor Analysis
## 8. Analysis By Competition Layer
## 9. Global Patterns Detected
## 10. Comparison Against Provided Website
## 11. Current Website Gaps
## 12. SEO Opportunities
## 13. Content Opportunities
## 14. Conversion Opportunities
## 15. Visual Opportunities
## 16. Technical / Schema Opportunities
## 17. Recommended Ideal Structure
## 18. Recommended Menu
## 19. Recommended Services / Products
## 20. Recommended Website Architecture
## 21. 30 / 60 / 90 Day Action Plan
## 22. Final Strategic Conclusion
```

---

## Mandatory Rules

1. Do not start by asking questions.
2. First inspect the project folder.
3. Deduce sector, country, language, services and locations from the website files.
4. Only ask if critical information is impossible to deduce.
5. Do not invent data.
6. If something cannot be verified, write `Not detectable`.
7. Do not analyze ads.
8. Do not use directories as valid business competitors.
9. Do not use social networks as valid business competitors.
10. Do not mix Google Maps with organic results unless requested.
11. Do not copy long competitor texts.
12. Do not give generic SEO advice without extracted patterns.
13. Always detect real patterns.
14. Always compare against the provided website.
15. Always finish with concrete actions.
16. Always include the ideal structure.
17. Always include the ideal menu.
18. Always include services/products to highlight.
19. Always include schema recommendations.
20. Always include the 30/60/90 day plan.

---

## Important Reminder For The Agent

The analysis does not aim to know only who ranks. It aims to understand **why they rank**.

Analyze every competitor from five angles:

1. **SEO:** Titles, metas, headings, schema, internal linking.
2. **Content:** Services, depth, intent, FAQs, locations, tone.
3. **Conversion:** CTA, phone, WhatsApp, forms, reviews, guarantees.
4. **Design / Trust:** Images, professionalism, visual order, clarity, proof.
5. **Strategy:** Repeated patterns, what to replicate, what to improve, how to beat them.

Do not say:
> "Add good headings."

Say:
> "The competitors ranking in the main city use H1s with service + city, H2s for service variations, H2s for service areas, FAQ blocks and conversion CTAs after the first service section. The provided website lacks service-area H2s and FAQ schema — these should be added."
