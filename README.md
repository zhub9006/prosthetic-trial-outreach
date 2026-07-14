# prosthetic-trial-outreach

Community outreach assessment for lower limb prosthetic trials, identifying enrollment gaps and evaluating **Shirley Ryan AbilityLab** (355 E Erie Street, Chicago, IL 60611) as a community outreach site for prosthetic users.

## Overview

This project analyzes the ClinicalTrials.gov landscape for lower limb prosthetic studies across two scales — a **broad 427-study scan** and a **targeted 104-study curated domain** — to identify gaps in underserved population representation, evaluate the accessibility infrastructure surrounding Shirley Ryan AbilityLab, and propose seven concrete outreach strategies to connect prosthetic users with research opportunities.

## Key Findings (July 2026)

| Dimension | Finding |
|---|---|
| **Total global studies** | **427** (broad scan) via ClinicalTrials.gov API v2 |
| **Active recruiting trials** | **~10–12** in targeted window |
| **Phase distribution** | 95% pre-Phase-3; only 5 Phase 3 and 5 Phase 4 globally |
| **Sponsor landscape** | 73% academic/OTHER, 14% Industry, 10% Federal, **0.5% NIH** |
| **Geographic equity** | >88% trials in US/EU; ~80 nations with zero trial access |
| **Socioeconomic gap** | Only **1 trial** (NCT06717938) explicitly targets low-income populations |
| **Shirley Ryan AbilityLab site** | **Walk Score 10/10**, Transit Score 9.4/10, 3 Walgreens pharmacies, 11+ CTA bus stops, 2 parking garages within 500 m |
| **Critical site gap** | **No DME/prosthetic vendor within 500 m** — supply chain missing at site perimeter |

## Repository Structure

| File | Description |
|---|---|
| `OUTREACH_ASSESSMENT.md` | Full detailed assessment: trial gaps (427-study scale), site accessibility audit (500m OSM), underserved populations analysis, and 7 proposed outreach strategies |
| `README.md` | This file — executive summary and quick-reference |

## Site Assessment: Shirley Ryan AbilityLab (355 E Erie Street, Chicago, IL 60611)

**Why this site?** It is both a leading prosthetics research center (active NCT06160882 outcomes registry) and an exceptionally accessible urban location:

- **Walkability:** 10/10 — continuous urban sidewalks
- **Transit:** 9.4/10 — Grand Red Line station (30 min south), 11+ CTA bus stops, wheelchair-accessible water taxi
- **Healthcare:** 3 Walgreens pharmacies + Northwestern Medicine Galter Pavilion adjacent
- **Parking:** 2 multi-storey garages within 500 m (162 m and 550 m)
- **Gap:** No prosthetic/DME vendor within 500 m — proposed Strategy 2 addresses this

## Seven Outreach Strategies (Summary)

1. **"Bridging the Gap"** — Hire community trial navigators from South/West Side Chicago for direct trial access
2. **"Prosthetic Supply Corridor"** — Quarterly pop-up DME vendor within SRAL lobby
3. **"Warm Hands, Warm Access"** — Heated waiting area + winter prosthetic kits (inspired by NCT07215442 thermal discomfort findings)
4. **"South Side Transit Pipeline"** — Paratransit + tele-trial for Grand Red Line corridor communities
5. **"Global Equity Bridge"** — MOU with Colombia, India, Pakistan; co-design <$500 prosthetic trial protocol
6. **"Mental Health & Acceptance"** — PHQ-2 integrated screening + monthly peer-support group
7. **"Women, Children & Gender-Diverse"** — Women's cohort, pediatric sub-study (Lurie Children's), gender-diversity accommodation standards

## Data Sources

- ClinicalTrials.gov API v2 (July 2026) — `analyze_trends` broad scan + curated domain
- OpenStreetMap (2026-07 build) — 500 m radius amenity/transit/parking enumeration
- OSM neighborhood livability scoring — accessibility-adjusted category scores

## License

Open for community use and adaptation. Attribution appreciated.
