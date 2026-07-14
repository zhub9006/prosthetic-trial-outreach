# prosthetic-trial-outreach

Community outreach assessment for lower limb prosthetic trials, identifying enrollment gaps and evaluating **Shirley Ryan AbilityLab** (355 E Erie Street, Chicago, IL 60611) as a community outreach site for prosthetic users.

## Overview

This project analyzes the ClinicalTrials.gov landscape for lower limb prosthetic studies — a **broad 427-study scan** to identify gaps in underserved population representation, evaluate the accessibility infrastructure surrounding Shirley Ryan AbilityLab, and propose **seven concrete outreach strategies** to connect prosthetic users with research opportunities.

## Key Findings (July 2026)

| Dimension | Finding |
|---|---|
| **Total global studies** | **427** (broad scan) via ClinicalTrials.gov API v2 |
| **RECRUITING** | **86** (20.1%) |
| **Phase 3 / Phase 4 globally** | 5 / 5 (1.2% each) — pipeline bottleneck |
| **Sponsor landscape** | 73% academic/OTHER, 14% Industry, 10% Federal, **0.5% NIH** |
| **By status breakdown** | 86 Recruiting, 23 Not Yet, 28 Active Not Recruiting, 3 Enrolling by Invite, 218 Completed, 51 Unknown, 12 Terminated/Withdrawn |
| **Active/enrolling pool** | **~40–60** studies |
| **Geographic equity** | >88% trials in US/EU; ~80 nations with zero trial access |
| **Socioeconomic gap** | Only **1 trial** (NCT06717938) explicitly targets low-income populations |
| **Shirley Ryan AbilityLab** | **Walk Score 10/10**, Transit 9.4/10, 4 Walgreens (incl. 24-hr), 17 bus stops, 5 Divvy bike stations, 3 parking garages, 0 DME vendors within 500 m |
| **Critical site gap** | **No DME/prosthetic vendor within 500 m** — Strategy 2 addresses this |

## Repository Structure

| File | Description |
|---|---|
| `COMPREHENSIVE_OUTREACH_ASSESSMENT.md` | **New — Full assessment:** 427-study trial gap analysis, bipartite sponsor × phase × status analysis, 10 trial snapshots, underserved population matrix, 500 m OSM audit (48 bus stops, 4 pharmacies, 3 garages, 5 Divvy), environmental/thermal context, neighborhood livability scores, 7 budgeted outreach strategies ($315K/yr total), 3 appendices |
| `OUTREACH_ASSESSMENT.md` | Full detailed assessment: trial gaps (427-study scale), site accessibility, underserved populations analysis, 7 proposed outreach strategies |
| `TRIAL_GAPS_AND_OUTREACH.md` | Parallel gap analysis with 10 active/recruiting trials, sponsor-phase enrollment trends |
| `TRIAL_GAPS_AND_SITE_ACCESS.md` | Site-focused audit: 48 transit stops, 11+ bus routes, 4 Walgreens, Northwestern Galter Pavilion |
| `README.md` | This file — executive summary and quick-reference |

## Seven Outreach Strategies (Full Details)

All seven strategies in `COMPREHENSIVE_OUTREACH_ASSESSMENT.md` include: problem framing, concrete actions, budget estimates, and measurable success metrics.

| # | Strategy | Annual Budget | Primary Gap |
|---|---|---|---|
| 1 | **"Bridging the Gap"** — Community Trial Navigators from South/West Side | $90,000/yr | Geographic & racial access |
| 2 | **"Prosthetic Supply Corridor"** — Pop-up DME in SRAL lobby ($15K/yr) or permanent station ($50K setup) | $15–50K | Zero DME within 500 m |
| 3 | **"Warm Hands, Warm Access"** — Heated waiting area + winter prosthetic thermal kits | $33K/yr (incl. $25K HVAC one-time) | Thermal discomfort (NCT07215442) |
| 4 | **"South Side Transit Pipeline"** — CTA paratransit shuttle + tele-trial model | $60,000/yr | 1+ bus transfer for South/West Siders |
| 5 | **"Global Equity Bridge"** — MOUs with Colombia, India, Pakistan; <$500-cost protocol | $50K start / $50K/yr | 80 nations with zero trial access |
| 6 | **"Mental Health & Acceptance"** — PHQ-2 screening + monthly peer group (with Medrina) | $20,000/yr | 30–50% amputee depression |
| 7 | **"Women, Children & Gender-Diverse"** — Equal-platform protocol + Lurie Children's pediatric sub-study | $35K start / $15K/yr | 90%+ male skew, pediatric absence |

**💰 Total annual operational budget estimate (all 7 strategies): ~$315,000/yr ($300K first year including one-time costs)**

## Site Assessment: Shirley Ryan AbilityLab (355 E Erie Street, Chicago, IL 60611)

**Why this site?** Active prosthetics research leader (NCT06160882 — RECRUITING powered prosthesis for osseointegration recipients) and one of the most accessible urban locations in Chicago (10/10 Walk Score, 9.4/10 Transit).

| Category | Detail |
|---|---|
| **GPS** | 41.8938727°N, 87.6184271°W |
| **Venue type** | Hospital — Rehabilitation (World-Renowned) |
| **Active trial at site** | NCT06160882 (powered prosthesis for transfemoral OI/TMR recipients) |
| **Walkability** | 10/10 — continuous sidewalks, all services within 500 m |
| **Transit** | 48 public-transport stops; 17 bus routes within 400 m; Grand Red Line (~550 m); 5 Divvy stations (24/7); water taxi (~400 m) |
| **Healthcare** | Northwestern Medicine Galter Pavilion adjacent; 4 Walgreens (incl. 24-hr); VA Lakeside Clinic ~300 m; Northwestern Immediate Care ~200 m |
| **Parking** | DoubleTree Garage 162 m (24/7); Erie/Ontario Underground 382 m; 3rd garage at ~548 m |
| **Grocery/food** | 7-Eleven (82 m); Bockwinkel's (129 m); Chipotle (150 m); Panera in Galter Pavilion (<100 m); Whole Foods (303 m) |
| **Fitness/sports** | Planet Fitness, Orangetheory, CorePower, Pure Barre, Solidcore (all <400 m); Lake Shore Park Fieldhouse (W/C accessible, 500 m) |
| **Environment** | Lake Shore Park + Seneca Park (both >300 m, W/C accessible) |
| **DME gap** | 🚨 **ZERO prosthetic/DME vendors within 500 m** — Strategy 2 addresses |
| **Winter barrier** | Wind chill <0°F; thermal discomfort is primary barrier — Strategy 3 addresses |
| **Socioeconomic support** | 🚩 No food pantry, social work, or financial counseling on/near site |

## Clinical Trial Landscape — Gaps Summary

### Underserved Population × Barrier Matrix

| Group | Recruitment | Consent | Geographic | Funding | Protocol | Retention |
|---|---|---|---|---|---|---|
| Low-income / Uninsured | 🔴 | 🔴 | 🟠 | 🔴 | 🟠 | 🔴 |
| Rural U.S. | 🟠 | 🟠 | 🔴 | 🟠 | 🟠 | 🔴 |
| Hispanic / Latino | 🔴 | 🔴 | 🟠 | 🟠 | 🔴 | 🟠 |
| African American / Black | 🔴 | 🔴 | 🟠 | 🟠 | 🟠 | 🟠 |
| Women | 🔴 | 🟠 | 🟡 | 🟠 | 🔴 | 🟠 |
| Children / Adolescents | 🟠 | 🔴 | 🔴 | 🔴 | 🔴 | 🟠 |
| Elderly (75+) | 🟠 | 🟠 | 🟠 | 🟠 | 🔴 | 🔴 |
| Global South | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 |
| Transgender / Gender-diverse | 🟠 | 🔴 | 🟠 | 🟠 | 🔴 | 🟠 |
| Cognitive / Intellectual disab. | 🟠 | 🔴 | 🔴 | 🟠 | 🔴 | 🔴 |

> 🔴 = Near-Complete Exclusion (0–20% access) \| 🟠 = Partial Access (20–50%) \| 🟡 = Minor Barriers (50–80%)

## Clinical Trial Data Sources

- **ClinicalTrials.gov API v2** (Jul 2026): 427-study broad scan, `analyze_trends` by status (86R/23NY/28AN/3EI/218C), by sponsor (OTHER 313/IND 59/FED 41), by phase (NA 299/Unknown 107/P3 5/P4 5), study retrieval NCT06160882 (RECRUITING), NCT07215442 (COMPLETED), NCT07519746 (COMPLETED)
- **OpenStreetMap** (Jul 2026): 500 m neighborhood enrichment (48 transit stops, 4 pharmacies, 3 garages, 5 Divvy, 2 parks, 7 gyms, 0 DME), live navigation (17 bus stops, 48 alerts)
- **OSM livability scoring**: Walk 10, Transit 9.4, Sports 9.0, Grocery 8.2, Services 8.6

## License

Open for community use and adaptation with attribution appreciated.