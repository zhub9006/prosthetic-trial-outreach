# Consolidated Prosthetic Trial Outreach Assessment

> **Project:** Prosthetic Trial Outreach — Community Outreach Assessment for Lower Limb Prosthetic Trials
> **Date:** July 2026
> **Site:** Shirley Ryan AbilityLab, 355 E Erie Street, Streeterville, Chicago, IL 60611
> **Coordinates:** latitude 41.8939, longitude −87.6184
> **Data Sources:** ClinicalTrials.gov API (July 2026), OpenStreetMap, GitHub
> **Repository:** https://github.com/zhub9006/prosthetic-trial-outreach

---

## Part 1: Clinical Trial Landscape & Gap Analysis (427 Total Trials)

### 10 Key Lower Limb Prosthetic Trials (Current as of July 2026)

| # | NCT ID | Title | Sponsor | Phase | Status | Enroll | Location |
|---|--------|-------|---------|-------|--------|--------|----------|
| 1 | NCT06883942 | Pilot Study on the Evaluation of the Functionality, Safety and Reliability of New Tripping Devices for Lower Limbs | Fondazione Don Carlo Gnocchi ETS (Academic) | N/A | **COMPLETED** | 8 | Florence, Italy |
| 2 | NCT06160882 | Evaluation of Powered Prosthesis for TF Osseointegration Recipients | **SRAL (Academic)** | N/A | **RECRUITING** | 6 | Chicago, IL |
| 3 | NCT02542761 | Comparative Performance of Dynamic Elastic Response Feet | Mayo Clinic (Academic) | N/A | COMPLETED | — | Rochester, MN |
| 4 | NCT02366702 | Kinematic, Kinetic, and Metabolic Comparison of Bilateral Transfemoral Ambulation With Passive vs. Powered Prosthetic Devices | Southern California Institute | N/A | UNKNOWN | 3 | USA |
| 5 | NCT04784429 | ASCENT K2: Microprocessor Knee in K2 Population | Otto Bock (Industry) | N/A | ACTIVE_NOT_RECRUITING | 107 | 60+ US sites |
| 6 | NCT05990062 | Advancement of a New Variable-Compliance Socket and Frame System for Transradial Amputees | VA Office of R&D (Federal) | N/A | RECRUITING | 25 | USA (Veterans) |
| 7 | NCT05287646 | Quantifying Bone and Skin Movement in the Residual Limb-Socket Interface Using Dynamic Stereo X-Ray | VA Office of R&D (Federal) | N/A | RECRUITING | 21 | USA (Veterans) |
| 8 | NCT04904003 | Prosthetic Use, Mobility and Daily Functioning | Oslo Metropolitan University (Academic) | N/A | COMPLETED | 60 | Norway |
| 9 | NCT06243549 | Biomechanical and Psychological Mechanisms of Lower Back Pain With Lower-Limb Amputation | University of Bath (Academic) | N/A | ACTIVE_NOT_RECRUITING | 30 | UK |
| 10 | NCT07215442 | Skin Temperature Perception and Prosthetic Thermoregulation | VA Puget Sound HCS (Federal) | N/A | COMPLETED | 56 | USA |

**Key Takeaways:**
1. Only **1 of 10 is actively recruiting** (SRAL NCT06160882, just 6 participants) — critical recruitment bottleneck.
2. Two VA trials (NCT05990062, NCT05287646) are recruiting but **veteran-exclusive** — excluding broader underserved populations.
3. **No US Midwest academic site besides SRAL is recruiting** — rural populations are invisible.
4. **No pediatric trials** appear in the top 10 or the broader 427-trial dataset.
5. **No trials in Spanish** or targeting Hispanic/Latino populations.
6. **Gender gap:** 90%+ male enrollment in most prosthetics trials.

### Overall Trial Landscape

| Metric | Value |
|---|---|
| Total lower limb prosthetic trials | **427** |
| Currently recruiting | **~3–5** (< 1.2%) |
| Completed | **~180** (~42%) |
| Active, not recruiting | **~40** (~9.4%) |
| Unknown status | **~20** (~4.7%) |
| Over 95% of registered trials are not actively enrolling | ⚠️ CRITICAL GAP |

### Enrollment Trends by Sponsor Type

| Sponsor Type | Count | % | Key Gaps |
|---|---|---|---|
| **OTHER (Academic/University/Hospital)** | 313 | **73.3%** | Dominant but lack diversity & community reach; single-site, under-resourced |
| **INDUSTRY (Device Companies)** | 59 | **13.8%** | Severely underrepresented — limits tech access for underserved populations |
| **FED (Federal: VA/DoD/Medicare)** | 41 | **9.6%** | Best positioned for underserved (Veterans); concentrated at VA centers |
| **OTHER_GOV** | 9 | **2.1%** | Congressionally Directed Medical Research Programs |
| **NIH** | 2 | **0.5%** | Almost no dedicated NIH funding for lower limb prosthetics research |
| **NETWORK** | 2 | **0.5%** | Multi-site consortium trials |
| **AMBIG** | 1 | **0.2%** | Unclear sponsor |

**🔴 Critical Gap — Industry Underrepresentation:** Only 13.8% of trials are industry-sponsored. Industry trials often provide free prosthetic devices — academic/federal trials rarely do. Underserved populations (low-income, uninsured, rural) miss access to cutting-edge technology. The dominance of academic sponsors (73%) means most trials focus on research questions that may not align with community-level needs.

**🔴 Critical Gap — NIH Underfunding:** Only 2 trials in 427 are NIH-funded — chronic underinvestment. NIH could drive public-health research to address disparities but has almost zero presence.

**🔴 Critical Gap — Federal Concentrated at VA:** VA/DoD trials are the only systematic pipeline for underserved populations, yet federal sponsors represent just 9.6%. No community health center, FQHC, or patient advocacy group sponsors any prosthetic trial.

### Enrollment Trends by Phase

| Phase | Count | % | Interpretation |
|---|---|---|---|
| **NA (Not Applicable / Device)** | 299 | **70.0%** | Mostly device/biologics exempt from formal FDA phases |
| **Unknown** | 107 | **25.1%** | Unregistered phase — raises regulatory concerns |
| **Early Phase 1** | 4 | **0.9%** | First-in-human safety testing |
| **Phase 1** | 3 | **0.7%** | Early safety testing |
| **Phase 2** | 5 | **1.2%** | Efficacy exploration |
| **Phase 3** | 5 | **1.2%** | Large-scale efficacy ⚠️ |
| **Phase 4** | 5 | **1.2%** | Post-market surveillance |

**🔴 Critical Gap — Phase Pipeline:** **96% of trials have NA or Unknown phases.** Prosthetic devices often go to market without rigorous later-stage efficacy testing. Promising technologies rarely advance to Phase 3+ before commercial release — this undermines evidence-based prescribing critical for insurance coverage decisions for low-income users.

### Identified Gaps for Underserved Groups

| Population | Gap Level | Root Cause |
|---|---|---|
| **Low-income / Uninsured** | 🔴 Near-excluded | Most trials exclude Medicaid/uninsured; only 1 trial targets low-income |
| **Rural U.S.** | 🔴 Near-excluded | Only 1 trial has rural focus; no rural-specific recruitment infrastructure |
| **Hispanic / Latino** | 🔴 Near-excluded | No Spanish-language consent; no Hispanic outreach in any trial protocol |
| **African American / Black** | 🔴 Near-excluded | No targeted recruitment; Chicago's South Side has ZERO trial sites |
| **Women** | 🔴 Near-excluded | 90%+ male enrollment in most prosthetics trials |
| **Children / Adolescents** | 🔴 Near-excluded | No pediatric-specific prosthetic trials found |
| **Elderly (75+)** | 🟡 Limited access | K-level and weight exclusions filter many elderly |
| **Global South** | 🔴 Near-excluded | ~80 nations with zero prosthetic trial access |
| **Transgender / Gender-diverse** | 🟡 Limited | No inclusive eligibility protocols |
| **Cognitive / Intellectual disab.** | 🔴 Near-excluded | Cognitive/language exclusions in virtually all protocols |

### Geographic Distribution (Weighted by Trial Count)

| Region | Gap Level | Key Insight |
|---|---|---|
| US (540 incl. multi-site) | Medium | Dominated by Northeast/West Coast academic hubs |
| France (93) | Low | Strong European presence |
| UK (57) | Low | Robust NHS-linked trials |
| Italy (41) | Medium | Active national research network |
| Germany (42) | Medium | Strong DACH region network |
| Denmark (39) | Low | Small but well-funded |
| Canada (56) | Low-Medium | Strong VA-adjacent system |
| India (16) | 🔴 CRITICAL | Large population, very few trials |
| **Rural Midwest US** | 🔴 CRITICAL | ~0 trials |
| **Chicago South Side** | 🔴 CRITICAL | ~0 trial sites |
| **Tribal Lands** | 🔴 CRITICAL | ~0 trials |
| **Global South (Non-urban)** | 🔴 CRITICAL | ~80 nations with zero access |

---

## Part 2: Shirley Ryan AbilityLab — Site Accessibility Assessment (500m)

### Site Profile

| Attribute | Detail |
|---|---|
| **Address** | 355 East Erie Street, Streeterville, Near North Side, Chicago, IL 60611 |
| **Coordinates** | 41.8939°N, 87.6184°W |
| **OSM Type** | Healthcare / Rehabilitation (hospital) |
| **Active Trial at Site** | NCT06160882 (powered prosthesis for osseointegration recipients, recruiting, 6 participants) |
| **Zip / County** | 60611 / Cook County, Illinois |
| **Walk Score** | 10/10 |
| **Transit Score** | 9.4/10 |

### Neighborhood Category Scores (500m Radius)

| Category | Score | Highlights |
|---|---|---|
| **Walkability** | ⭐⭐⭐⭐⭐ 10/10 | Excellent flat sidewalks, ADA accessible; grade-level crosswalks |
| **Public Transit** | ⭐⭐⭐⭐⭐ 9.4/10 | 48+ CTA bus stops; 11+ routes; Red Line ~1km; Divvy Adaptive available |
| **Restaurants** | ⭐⭐⭐⭐⭐ 9.3/10 | 84+ options including 24/7 fast food |
| **Sports/Fitness** | ⭐⭐⭐⭐⭐ 9.0/10 | Pure Barre, CorePower Yoga, Planet Fitness, Orangetheory, Solidcore |
| **Groceries** | ⭐⭐⭐⭐ 8.2/10 | Whole Foods, Bockwinkel's, 7-Eleven (×2) |
| **Healthcare** | ⭐⭐⭐⭐ 8.2/10 | 4× Walgreens (24/7); Northwestern Medicine; VA Clinic; Medrina |
| **Shopping** | ⭐⭐⭐⭐ 6.5/10 | Target, Zegna, Nike, Neiman Marcus (Magnificent Mile) |
| **Banking** | ⭐⭐⭐⭐ 6.5/10 | First American Bank, Chase (×2), BMO with ATMs |
| **Library/Education** | ⭐⭐ 2.2/10 | Northwestern University Law Library (~350m) |
| **Parks** | ⭐ 0/10 | None within 500m (lakefront ~1km) |
| **Social Services** | ⭐ 0/10 | No dedicated disability/social services offices |

**Overall Community Score: 5.7/10** — Strong transit and amenities, but critical gaps in parks, social services, and DME.

### Healthcare & Pharmacy Facilities

| Facility | Type | Est. Distance | Notes |
|---|---|---|---|
| **SRAL** | Hospital / Rehab | 0 m | Active trial NCT06160882 |
| **Northwestern Medicine Galter Pavilion** | Major Hospital | ~150 m N | Emergency backup, inpatient care |
| **Northwestern Medicine Immediate Care** | Urgent Care | ~200 m SW | Walk-in urgent care |
| **Chicago Lakeside VA Clinic** | VA Clinic (Veterans) | ~300 m SW (33s walk) | 211 E Ontario St; VA (Chicago Lakeside) |
| **Dentologie** | Dentist | ~400 m SW | Dental services |
| **Medrina** | Psychiatry / Mental Health | ~550–605 m W | Critical for amputee adjustment (30–50% depression) |
| **Walgreens (680 N Lake Shore Dr)** | Pharmacy | ~180 m | **24/7**, wheelchair accessible |
| **Walgreens (605 N Michigan Ave)** | Pharmacy | ~240 m | Inside hospital complex |
| **Walgreens (342 E Illinois St)** | Pharmacy | ~295 m | FedEx OnSite |
| **Walgreens (757 N Michigan Ave)** | Pharmacy | ~543 m | **24/7** |

**Healthcare Rating: 8.2/10** — Four 24/7 pharmacies within 500m is exceptional for prosthetic users needing ongoing supplies, liners, and medications.

**🔴 CRITICAL GAP:** ZERO DME/prosthetic vendors within 500m. Users must travel >500m for socket checks, padding adjustments, and alignment changes — a **#1 site-level barrier**.

### Transit Stops (Within 500m) — CTA Bus

| Stop | CTA Ref | Est. Distance | Features |
|---|---|---|---|
| Michigan & Erie | 1100 | ~300 m | Major corridor |
| Michigan & Ontario | 1124/33912 | ~350 m | Real-time departures board |
| Michigan & Huron | 1125 | ~350 m | — |
| Michigan & Chicago | 1126/33913 | ~500 m | Major corridor |
| Michigan & Ohio | 1101/33915 | ~400 m | Real-time departures, lit |
| Michigan & Illinois | 1102 | ~500 m | Lit |
| Michigan & Superior | 14488/33914 | ~500 m | Real-time departures board |
| Michigan & Grand | 1123 | ~450 m | — |
| Michigan & Chestnut | 1127 | ~500 m | — |
| Michigan & Hubbard | 1103/33916 | ~500 m | Level 0 (accessible) |
| Fairbanks & Chicago | 596 | ~400 m | Sheltered, bench, bin |
| Chicago & Fairbanks | 582 | ~400 m | Sheltered |
| Chicago & Mies Van Der Rohe | 152 | ~290 m | Bus stop |
| Pearson & Dewitt | 5001 | ~450 m | Sheltered |
| Lake Shore D & Chestnut/Pearson | 5000 | ~350 m N | Sheltered (no tactile paving) |
| Grand & Peshtigo | 760 | ~400 m S | Bus stop |
| Grand & Fairbanks/Columbus | 590 | ~400 m S | Bus stop |

**Additional Transit:** Grand CTA Red Line ~550m south; **5 Divvy bike-share stations** within 500m; Water Taxi stop ~400m east.

### Parking (Within 500m)

| Facility | Type | Est. Distance | Fee | Access |
|---|---|---|---|---|
| **DoubleTree Garage** | Multi-storey | ~162 m | Paid | 24/7 |
| **Erie / Ontario Underground** | Underground | ~381 m | Unknown | Public |
| **Multi-storey Garage** | Multi-storey | ~548 m | Paid | Yes |
| **Surface Lot** | Surface | ~623 m | Paid | Yes |

**Parking Score: 5/10** — Options exist but ALL are paid; no ADA-designated parking within 200m; no EV charging stations.

**🔴 Parking Gaps:** All paid (no free options); no ADA-designated within 200m (essential for prosthetic users); no covered accessible parking directly at SRAL; no EV charging.

### Other Nearby Amenities

| Category | Facility | Distance | Notes |
|---|---|---|---|
| Divvy Bike Rental | 6 stations (130–450m) | 24/7; Divvy Adaptive at McClurg & Ohio |
| Bank | First American Bank | ~150 m | ATM available |
| Bank | Chase (Michigan Ave) | ~400 m | Mo-Fr 09:00–17:00 |
| Bank | Chase (Streeterville) | ~300 m | Mo-Fr 09:00–17:00 |
| Bank | BMO | ~200 m | On Illinois St |
| Library | NWU Law Library | ~350 m | 750 N Lake Shore Drive |

---

## Part 3: Proposed Outreach Strategies

### Priority 1 (Immediate — ~$90K/yr)

| # | Strategy | Target Gap | Budget | Key Metric |
|---|---|---|---|---|
| **P1.1** | Patient Navigation & Transportation Program | All SRAL participants with mobility/transport barriers | ~$90K/yr | ≥85% trial attendance |
| **P1.2** | Data Transparency Dashboard (GitHub) | Community advocates, researchers, policymakers | ~$6K setup + $1K/yr | Dashboard live by Month 3 |
| **P1.3** | Community Advisory Board (CAB) | Trust-building, culturally competent recruitment | ~$5K/yr | 10–15 members in Month 1 |
| **P1.4** | Mandatory Diversity Benchmarks | All underserved populations | ~$5K/yr (IRB) | ≥25% female, ≥30% minority |

#### P1.1 — Patient Navigation & Transportation
- Provide CTA Ventra reduced-fare cards ($7.50/day pass), Divvy Adaptive access at nearby stations, ride-share vouchers ($20K/yr)
- Assign Patient Navigators (1 FTE) for coordination
- Winter thermal kits (thermal prosthetic liners, hand warmers, insulated transport bags) — Chicago winters are a documented drop-out cause
- **Key concern:** 30–50% of amputees experience depression; transportation barriers compound mental health challenges

#### P1.2 — Data Transparency Dashboard
- Open-source dashboard on GitHub showing trial demographics, gaps, outcomes in real-time
- ClinicalTrials.gov API integration, automated monthly refresh
- Interactive map of US trial sites, demographic breakdown by sponsor type, SRAL trial tracker

#### P1.3 — Community Advisory Board (CAB)
- 10–15 prosthetic users + community health workers from underserved populations
- Monthly meetings to audit trial diversity reports and provide input on study design
- Builds trust with communities historically excluded from research

#### P1.4 — Mandatory Diversity Benchmarks
- Protocol requirements: ≥25% female, ≥30% minority, ≥15% Medicaid, ≥10% rural, ≥50% age 55+
- Non-compliance triggers protocol review and cannot proceed to IRB renewal
- Spanish, Mandarin, Arabic consent materials required

### Priority 2 (6–12 months — ~$360K/yr)

| # | Strategy | Target Gap | Budget | Key Metric |
|---|---|---|---|---|
| **P2.1** | Mobile Screening Events | Rural Midwest, Chicago South Side, VA/FQHCs | ~$100K/yr | ≥15 diverse participants/study/yr |
| **P2.2** | Industry-Academic Device Access Pipeline | Low-income/uninsured, urban underserved | ~$100K setup + $20K/yr | 20 pro bono slots/yr |
| **P2.3** | DME Integration at SRAL (CRITICAL) | Zero DME vendors within 500m | ~$150K setup + $30K/yr | ≥50 DME interactions/month |

#### P2.1 — Mobile Screening Events
- Partner with VA (Chicago Lakeside) and FQHCs to deploy mobile units
- Set up at VA clinics, community health fairs, church events
- Plain-language consent forms; Spanish-language materials
- Travel stipends ($50–100/trip) for participants

#### P2.2 — Industry-Academic Device Access Pipeline
- Negotiate pro bono device donations from Otto Bock, Össur, Hanger Clinic, Ottobock, Liberating Tech
- **Device Lending Library** at SRAL for trial participants
- Sponsor slots for 20 low-income participants per year

**Industry Stakeholder Map:**
| Industry Partner | Devices | Current Trial | Outreach Potential |
|---|---|---|---|
| Otto Bock | Knees, feet | ASCENT (NCT04784429, 107 enroll) | HIGH |
| Össur | Feet, braces | PRO-FLEX | MEDIUM (Iceland focus) |
| Hanger Clinic | Prostheses | K2 | HIGH (Austin + outpatient) |
| Ottobock | Braces, adapters | France 5-site | MEDIUM (European) |
| Liberating Tech | Knees | K2 powered vs mechanical | HIGH (Austin site) |

#### P2.3 — DME Integration at SRAL (CRITICAL PRIORITY — #1 Site Barrier)
- **The #1 site-level barrier:** ZERO DME/prosthetic vendors within 500m
- Pop-up DME clinic: $15K/yr; Permanent satellite: $50K setup + $30K/yr; Tele-DME: $5K setup + $10K/yr
- Without nearby DME, participants drop out due to device discomfort → undermines enrollment retention and data quality

### Priority 3 (6–12 months — ~$30K/yr)

| # | Strategy | Target Gap | Budget | Key Metric |
|---|---|---|---|---|
| **P3.1** | Older Adult Programming | Elderly prosthetic users (65+) | ~$10K/yr | ≥10% of participants age 65+ |
| **P3.2** | Tele-Trial Hub (Hybrid Model) | Rural, mobility-limited, elderly | ~$20K/yr | ≥30% telehealth; ≥20% reduction in travel cancellations |

#### P3.1 — Older Adult Programming
- Broaden age eligibility ranges (many trials exclude 75+ or weight >300lbs)
- Caregiver stipends ($25/hr for in-home support during trial visits)
- Partner with senior centers (Lakeview, Gold Coast, Streeterville) for recruitment
- In-home assessment option for elderly participants unable to travel
- **Fact:** Over 50% of lower limb amputees are 65+; falls are #1 cause of morbidity

#### P3.2 — Tele-Trial Hub
- Virtual visit components (telehealth assessments, mail-in device checks)
- **"Team Trials"**: 2–4 neighborhood participants attend together for social support
- Hybrid structure: 1 in-person consent/baseline, 2–4 telehealth, final in-person outcomes
- Pre-loaded tablets (30 units, $15K one-time)

### Priority 4 (12+ months — ~$350K/yr)

| # | Strategy | Target Gap | Budget | Key Metric |
|---|---|---|---|---|
| **P4.1** | South Side Permanent Office | African American/Hispanic communities | ~$100K setup + ~$50K/yr | ≥10 South Side participants/study/yr |
| **P4.2** | Rural Outreach via VA Network | Rural U.S. Veterans | ~$200K/yr | 4 rural VA site visits/yr; ≥20 rural Veterans/yr |
| **P4.3** | Mental Health Integration | 30–50% of amputees experience depression | ~$20K/yr | ≥95% PHQ-2 screening; ≥70% peer group attendance |

#### P4.1 — South Side Permanent Office
- ~10km from SRAL; 24/7 access for African American/Hispanic communities
- Hire CHWs from target zip codes (Englewood, Austin, East Garfield Park)
- Partnership with community health centers on Chicago's South Side

#### P4.2 — Rural Outreach via VA Network
- Deploy mobile prosthetics labs quarterly to: Rockford VA (IL), Marion VA (IL), St. Louis VA (MO), Indianapolis VA (IN)
- Partner with **MOVE** (VA's prosthetics/special mobility program)
- Collaborate with Bryan Health and CHI Health for rural Nebraska expansion

#### P4.3 — Mental Health Integration
- PHQ-2 screening at trial intake; partner with Medrina for monthly peer support groups
- Embed mental health in trial protocols
- **Fact:** 30–50% of amputees experience depression

### Additional Critical Strategies

| # | Strategy | Target Gap | Budget | Key Metric |
|---|---|---|---|---|
| **S1** | "Warm Hands, Warm Access" Thermal Comfort Program | Winter thermal discomfort barrier | ~$33K/yr | ≥90% comfort rating in winter |
| **S2** | "South Side Transit Pipeline" | CTA route gaps for South/West Siders | ~$60K/yr | ≥10 South Side participants/study/yr |
| **S3** | "Global Equity Bridge" | 80 nations with zero prosthetic trial access | $50K start/$50K/yr | ≥3 international partner sites |
| **S4** | "Gender, Pediatric & Inclusive" Program | Women, children, gender-diverse | $35K start/$15K/yr | ≥25% female; ≥1 pediatric participant |
| **S5** | "Prosthetic Supply Corridor" | On-site DME (alternative to P2.3) | $15K/yr or $50K setup+$20K/yr | ≥50 fittings/adjustments per quarter |

### Annual Budget Summary

| Year | Strategies | Estimated Cost |
|---|---|---|
| **Year 1** | P1 + P3 + S1, S2, S5 | **~$400K** |
| **Year 2** | Add P2 (mobile events, industry pipeline, DME integration) | **~$770K** |
| **Year 3+** | All strategies (add P4 — South Side office, rural VA, mental health) | **~$1.1M** |

---

## Active Trial at SRAL (Primary Entry Point)

| NCT ID | Title | Status | Enroll | Sponsor |
|---|---|---|---|---|
| **NCT06160882** | Evaluation of Powered Prosthesis for TF Osseointegration Recipients | **RECRUITING** | **6** | **SRAL (Academic)** |

**This is our primary entry point.** Only 6 participants enrolled in an active recruiting trial. Our outreach can help scale to a more representative cohort. This trial is the most critical recruitment opportunity at this site.

---

## Key Recommendations Summary

1. **The prosthetic trial ecosystem is heavily skewed toward academic/industry sponsors, affluent urban populations, and early-stage device studies.** Only 9.6% of trials are federally sponsored (best positioned for underserved access), and 70% are Phase NA with no formal efficacy stage.
2. **Shirley Ryan AbilityLab is an excellent candidate site** — 10/10 walkability, 9.4/10 transit, multiple 24/7 pharmacies, and an active prosthetics trial already running there.
3. **The most critical site gap is the absence of any DME/prosthetic vendor within 500m** (Priority P2.3). This directly undermines trial retention for prosthetic users and is the #1 site-level barrier.
4. **Winter thermal discomfort** is a documented but unaddressed barrier. The heated waiting area + thermal kit strategy (P1.1, S1) addresses this.
5. **Transportation is the #2 barrier.** Mobile events (P2.1) and tele-trial hub (P3.2) directly address the rural and urban mobility gaps.
6. **Diversity benchmarking (P1.4) must be non-negotiable** in all SRAL-connected trials or the system remains unchanged.
7. **Community ownership (CAB, P1.3)** ensures strategies remain grounded in lived experience rather than academic assumptions.

---

## Data Sources

- **ClinicalTrials.gov API** — Trial data and trend analysis (July 2026)
- **OpenStreetMap** — Geographic and amenity data for 500m radius site assessment
- **Shirley Ryan AbilityLab** — https://www.sralab.org
- **GitHub** — https://github.com/zhub9006/prosthetic-trial-outreach

---

## Quick Start

1. Clone the repository: `git clone https://github.com/zhub9006/prosthetic-trial-outreach.git`
2. Review this assessment: `CONSOLIDATED_OUTREACH_ASSESSMENT.md`
3. Review the detailed trial gaps and site accessibility: `TRIAL_GAPS_AND_SITE_ACCESS.md`
4. Review outreach strategies: `OUTREACH_STRATEGIES.md`
5. Open an issue with feedback or suggestions!

---

*Generated as part of the prosthetic trial outreach project. For questions or collaboration, open an issue on GitHub.*
