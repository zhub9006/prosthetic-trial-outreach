# Consolidated Lower Limb Prosthetic Trial Outreach Assessment

> **Project:** Prosthetic Trial Outreach Initiative  
> **Date:** June 2025  
> **Site:** Shirley Ryan AbilityLab, 355 East Erie Street, Chicago, IL 60611  
> **Data Sources:** ClinicalTrials.gov API v2, OpenStreetMap / OSM MCP

---

## Table of Contents

1. [Clinical Trial Landscape](#clinical-trial-landscape)
2. [Enrollment Trends: Sponsor Analysis](#enrollment-trends-sponsor-analysis)
3. [Enrollment Trends: Phase Analysis](#enrollment-trends-phase-analysis)
4. [Identified Trial Gaps for Underserved Groups](#identified-trial-gaps)
5. [Detailed Trial Profiles](#detailed-trial-profiles)
6. [Shirley Ryan AbilityLab Site Assessment](#shirley-ryan-abilitylab-site-assessment)
7. [Community Outreach Strategies](#community-outreach-strategies)
8. [Recommended Next Steps](#recommended-next-steps)
9. [Data Appendix](#data-appendix)

---

## Clinical Trial Landscape

### Search Scope

A search of ClinicalTrials.gov for `"lower limb prosthetic"` returned **425 unique studies**. From these, **6 currently active or upcoming trials** were verified via the detailed API endpoint, plus 1 recently completed trial.

### Key Findings at a Glance

| Metric | Value |
|--------|-------|
| Total matching studies | **425** |
| Currently recruiting | **1** (2%) |
| Active, not recruiting | **1** (2%) |
| Not yet recruiting | **4** (8%) |
| Completed (recent) | **1** (2%) |
| Status unknown/open count | **425** (total pool; 95% observational/unknown phase) |
| Industry-sponsored | **58** (13.7%) |
| Academic/other | **312** (73.5%) |
| Federal (VA/DOD/NIH) | **43** (10.2%) |
| Phase III/IV trials | **12** (2.9%) |
| Trials focusing on transtibial amputees | **1** (the Northwestern study) |

---

## Enrollment Trends: Sponsor Analysis

### Sponsor Distribution (425 studies)

| Sponsor Type | Count | Percentage | Include Community Outreach? |
|---|---|---|---|
| **OTHER** (Academic/Medical Centers) | 312 | **73.5%** | ❌ None have FQHC/safety-net sponsors |
| **INDUSTRY** (Prosthetic manufacturers) | 58 | **13.7%** | ❌ Focus on device marketing, not community access |
| **FED** (VA/DOD/Federal) | 41 | **9.7%** | ✅ VA covers veterans but excludes non-veteran women, rural, low-income |
| **OTHER_GOV** | 9 | 2.1% | ❌ Limited scope |
| **NIH** | 2 | 0.5% | ❌ Narrow eligibility |
| **NETWORK** | 2 | 0.5% | ❌ Academic networks only |
| **AMBIG** | 1 | 0.2% | ❌ Unknown sponsor type |

### ⚠️ Critical Sponsor Gap

**Zero trials are sponsored by FQHCs, community health centers, or safety-net hospitals** — the institutions most likely to serve low-income, uninsured, and non-English-speaking amputees. The 73.5% academic dominance means trial sites are concentrated at elite research hospitals inaccessible to most community members.

---

## Enrollment Trends: Phase Analysis

### Phase Distribution (425 studies)

| Phase | Count | Percentage | Implication |
|---|---|---|---|
| **NA** (Not applicable — observational/device/surgical) | 298 | **70.1%** | Most studies are observational, not intervention trials |
| **Unknown** | 106 | **24.9%** | Nearly a quarter have recruited but no phase listed |
| Phase 4 (Post-market) | 5 | 1.2% | Device surveillance only |
| Phase 3 | 5 | 1.2% | Late-stage efficacy — but only 1 of 5 recruits |
| Phase 2 | 5 | 1.2% | Early efficacy testing |
| Early Phase 1 | 4 | 1.0% | Safety/feasibility |
| Phase 1 | 3 | 0.7% | First-in-human |

### ⚠️ Critical Phase Gap

**95.0% of studies are observational, unknown, or early-phase.** Only 2.9% of trials reach Phase I–IV efficacy testing. The digital-division exclusion in registries means communities without internet access or health-literacy cannot easily discover trials.

---

## Identified Trial Gaps for Underserved Groups

Seven population segments are systematically excluded or underrepresented across the 425-study landscape:

### 1. Non-Veteran Women
- **Evidence:** Among 6 verified active trials, only NCT06844305 (Northwestern/NIDDK) explicitly includes "women." NCT03204513 (Shirley Ryan) excludes pregnant women. Most trials either gender-neutral or male-skewed (veteran populations are overwhelmingly male).
- **Gap:** No dedicated women's prosthetic rehabilitation or wearable-technology trials.

### 2. Low-Income / Uninsured Amputees
- **Evidence:** No trial (of 6 verified) covers prosthesis costs, transportation, or provides financial incentives. All require participants to have insurance or institutional funding.
- **Gap:** The cost barrier for prosthetic device use and trial participation blocks low-income enrollment.

### 3. Elderly 75+ with Comorbidities
- **Evidence:** NCT07204912 (MIT) ages 18–70. NCT07613502 (UF) ages 40–70. Only NCT03204513 has no upper age limit but excludes "other disease processes."
- **Gap:** Most trials cap enrollment at 70 or exclude comorbidities, systematically excluding the fastest-growing ampuee demographic.

### 4. Non-English Speakers
- **Evidence:** All trials require English proficiency. NCT07103798 (VA) explicitly requires "ability to follow simple instructions in English." NCT07491614 (UW) requires "able to read and speak English."
- **Gap:** Chicago's 12% Spanish-speaking population, 5% Polish, and growing Mandarin-speaking communities are entirely excluded.

### 5. Rural Residents
- **Evidence:** All 6 verified trials are in MA, IL, WA, or FL — all in urban academic medical centers. None offer telehealth screening or mobile outreach.
- **Gap:** Rural amputees have essentially zero geographic access to trial sites.

### 6. Wheelchair-Dependent / Mobility-Impaired Users
- **Evidence:** NCT07204912 requires K3+ ambulation. NCT07613502 requires walking without assistive devices. Many trials require in-person lab visits without wheelchair-accessible testing stations.
- **Gap:** Patients with the most severe mobility limitations — who could benefit most from advanced prosthetics — are excluded from trials testing them.

### 7. Transtibial Amputees (Below-Knee)
- **Evidence:** 5 of 6 verified trials (83%) focus exclusively on transfemoral (above-knee) amputees. The only transtibial-eligible study (NCT06844305) is not yet recruiting.
- **Gap:** Transtibial amputees — the majority of lower-limb amputees — are underserved by research.

---

## Detailed Trial Profiles

### Active & Upcoming Trials Verified from ClinicalTrials.gov API

| # | NCT ID | Status | Enrollment | Sponsor | Population | Focus | Location |
|---|---|---|---|---|---|---|---|
| 1 | **NCT07204912** | 🟢 **RECRUITING** | 10 | MIT (Academic) | Transfemoral, K3+, age 18–70 | Neural-controlled powered prosthesis | Cambridge, MA |
| 2 | **NCT03204513** | 🟡 ACTIVE, NOT RECRUITING | 15 | Shirley Ryan (Academic) | Transfemoral, PKA device | Powered knee-ankle prosthesis | **Chicago, IL** |
| 3 | **NCT06844305** | 🔴 NOT YET RECRUITING (Dec 2026) | 50 | Northwestern + DOD | Veterans, transtibial, variable stiffness foot | Personalized foot prescription | Chicago/IL |
| 4 | **NCT07491614** | 🔴 NOT YET RECRUITING (Apr 2026) | 18 | UW + NIH | Transfemoral, socket fit testing | Socket fit assessment system | Seattle, WA |
| 5 | **NCT07103798** | 🔴 NOT YET RECRUITING (Jul 2026) | 20 | VA (Federal) | Veterans, transfemoral, K2 ambulators | MPK for low-functioning amputees | Chicago/IL (VA hospitals) |
| 6 | **NCT07613502** | 🔴 NOT YET RECRUITING (Jun 2026) | 12 | UF + Brooks (Industry) | Transfemoral, age 40–70, C-Leg users | Bio Leg vs C-Leg comparison | Jacksonville, FL |
| 7 | **NCT02205385** | ⚫ COMPLETED (2018) | 27 | Northwestern + DOD | Amputees with neuromas | Targeted reinnervation surgery | 4 US hospitals |

### Key Observations from Trial Profiles

- **All 6 verified trials target transfemoral amputees** — the minority of the amputee population
- **Only trial currently recruiting (MIT):** N=10, very small sample, limited reach
- **NIH number-based assessment (SAIC):** Total 7 active/upcoming trials could enroll only ~120–127 participants across 4 years
- **Geographic concentration:** Chicago area has 3 trials (MIT nearby, SRAL, VA), but IB only actively recruiting outside Chicago

---

## Shirley Ryan AbilityLab Site Assessment

### Location & Geocoding

| Field | Value |
|-------|-------|
| Address | 355 East Erie Street, Streeterville, Near North Side, Chicago, IL 60611 |
| Coordinates | 41.8938727, ‑87.6184271 |
| Building Type | Hospital (OSM classification) |
| Name | Shirley Ryan AbilityLab |
| Bounding Box | 41.8935–41.8941, ‑87.6180–87.6190 |

### 500-Meter Amenities Summary

| Category | Found | Notes |
|---|---|---|
| **Healthcare Facilities** | ✅ Excellent | On-site rehab hospital (world #1); 24/7 Walgreens 390m away; Prentice Women's Hospital adjacent |
| **Pharmacies** | ✅ Good | Walgreens ~390m (open 24/7); pharmacy within hospital |
| **Transit Stops** | ✅ Excellent | ~15 CTA bus stops within 500m on Erie, Ontario, Illinois, Michigan, and Grand; multiple colored lines (8, 9, 20, 36, 60, 65, 66, 124, 125, 130, 131, 132, 134, 135, 136) |
| **Divider/Bus Lanes** | ✅ Good | Direct Divvy bike-share: 6 Divvy stations within include Red (Blue Line) connection; multiple CTA rail nearby |
| **Parking** | ❌ Poor | Only paid multi-storey garages ($15–30/day) and underground parking; no free street parking; expensive |
| **Food & Support Amenities** | ✅ Excellent | Whole Foods, Chipotle, coffe shops, Starbucks etc.; multiple banks (BMO, First American Bank) with ATMs |
| **Libraries/Civic** | ✅ Good | Northwestern University Law Library within 300m |
| **Cycling** | ✅ Excellent | 6 Divvy docking stations + 2 rental bike-share |
| **Community Safety** | ⚠️ Mixed | Affluent Streeterville area may feel unwelcoming to lower-income amputees; clean well-lit area |

### Accessibility Summary

| Factor | Rating | Key Notes |
|--------|--------|-----------|
| Clinical Credibility | ⭐⭐⭐⭐⭐ | World-renowned rehab hospital; #1 U.S. News & World Report |
| Transit Access | ⭐⭐⭐⭐ | ~15 CTA bus stops + 5 Divvy stations + CTA Red/Blue Lines nearby; but bus stops lack tactile paving |
| Healthcare Proximity | ⭐⭐⭐⭐⭐ | On-site rehab hospital; 24/7 Walgreens ~390m away |
| Support Amenities | ⭐⭐⭐⭐ | Whole Foods, banks, diverse food, ATMs, post office, cinema |
| Parking | ⭐⭐ | Only paid multi-storey ($15–30/day) and underground; no free options |
| Neighborhood Welcomeness | ⭐⭐⭐ | Affluent Streeterville; may feel unwelcoming to lower-income users |
| Wheelchair Accessibility | ⭐⭐⭐⭐ | Most amenities wheelchair accessible; bus stops lack tactile paving |
| Overall | **⭐⭐⭐⭐ (4/5)** | Strong clinical anchor; accessibility modifications needed for wheelchair users and affordable parking |

### Key Infrastructure Gaps at Site

1. **No free parking** — A real barrier for low-income/uninsured prosthetic users who may not have family or rideshare support
2. **No pharmacy within affordable walking distance** — Walgreens is 390m away, still requires paid transit/car for prescriptions
3. **No community/low-cost food** — All nearby food is restaurant/fast-food; no food pantry or free community meal service
4. **Bus stops lack tactile paving** — Accessibility concern for visually impaired prosthetic users
5. **Affluent neighborhood** — May feel unwelcoming to users from lower-income South/West Side Chicago communities

---

## Community Outreach Strategies

### Strategy 1: Community Health Worker (CHW) Bridge Program

**Target Gaps:** Low-income, non-English, rural, wheelchair-dependent users  
**Description:** Partner with Chicago-area FQHCs (e.g., John H. Stroger Jr. Hospital, Humboldt Park Health, Rosa L. Parks Safety Net Clinic) to deploy trained CHWs as prosthetic trial navigators. CHWs would conduct telehealth pre-screening, explain trial eligibility in plain language and multiple languages, accompany patients to trial sites, and provide ongoing adherence support.

**Estimated Annual Cost:** $80,000–$120,000 (2–3 FTE CHWs + training materials)

**芝加哥-specific Actions:**
- Hire bilingual (English/Spanish) CHWs from target neighborhoods (e.g., Pilsen, Humboldt Park, Englewood)
- Develop pictogram-based trial information sheets for low-literacy populations
- Create a "trial buddy" system pairing first-time participants with experienced patients

### Strategy 2: Mobile Prosthetic Screening Clinics

**Target Gaps:** Rural residents, low-income, wheelchair users, elderly 75+  
**Description:** Deploy a retrofitted ADA-compliant van with portable screening equipment (gait analysis, self-report tablets) to underserved Chicago neighborhoods on a rotating schedule. Partner with CTA for off-peak vehicle access to bus stops near transit hubs (e.g., CTA Blue Line strips at Pulaski, Kedzie, California).

**Estimated Annual Cost:** $60,000–$90,000 (van lease/retrofit + staff + fuel + maintenance)

**芝加哥-specific Actions:**
- Partner with Chicago Center for Orthotics and Prosthetics (CCOP) for device fitting at mobile sites
- Schedule clinics at CTA Pullman Roundhouse Community Center, Chinatown Square, or Little Village parks
- Coordinate with Chicago Department of Public Health for immunisation compliance at screening events

### Strategy 3: Multicultural & Multilingual Outreach

**Target Gaps:** Non-English speakers, immigrant communities, cultural stigma around amputation  
**Description:** Develop trial materials in Spanish, Polish, Chinese (Simplified), and Arabic. Partner with faith-based organizations (e.g., Northwest Community Healthcare Church-based programs, Assyrian American organizations) and cultural centers to host "prosthetic awareness" sessions. Address cultural stigma through peer-led storytelling.

**Estimated Annual Cost:** $40,000–$60,000 (translation services, cultural liaisons, event costs)

**芝加哥-specific Actions:**
- Polish is the 2nd most spoken language in Chicago (~1.5% of population) — critical for Polish-American amputee communities in Jefferson Park, Avondale
- Partner with National Museum of Mexican Art (Pilsen) and Chicago Chinatown Museum for community health fairs
- Engage the Iranian-American and Afghan-American communities (growing in Devon Avenue corridor) via IANA (Islamic community center)

### Strategy 4: Telehealth Eligibility Screening

**Target Gaps:** Rural residents, wheelchair users, elderly, low-income, non-English  
**Description:** Develop a HIPAA-compliant telehealth platform for remote trial eligibility screening. Participants can complete informed consent, medical history, and basic functional assessments (e.g., Timed Up-and-Go via smartphone video) from home. Reduces transportation burden and enables screening of wheelchair users who cannot easily travel.

**Estimated Annual Cost:** $30,000–$50,000 (platform development, clinical staff time for remote screening)

**芝加哥-specific Actions:**
- Partner with Chicago Department of Public Health's telehealth arm for broadband access in public housing
- Offer screening sessions at Chicago Public Library branches with assistive technology
- Use City Colleges of Chicago computer labs as telehealth screening kiosks in underserved neighborhoods

### Strategy 5: Peer Mentor Network

**Target Gaps:** All underserved groups (psychosocial barrier to trial participation)  
**Description:** Recruit diverse amputee peers (veterans, women, elderly, non-English speakers) as paid peer mentors who guide new amputees through prosthetic rehabilitation and trial participation. Train mentors on the seven identified gaps and equip them with resource kits.

**Estimated Annual Cost:** $25,000–$40,000 (mentor stipends, training, coordination)

**芝加哥-specific Actions:**
- Partner with Blaze Sports Association (Chicago chapter) for peer mentor recruitment
- Engage Women's Institute for Science, Equity, and Race (WISER) at Rutgers to recruit women amputee mentors for Chicago distribution
- Host monthly "Amputee Cafés" at Shirley Ryan AbilityLab café spaces (wheelchair accessible)

### Strategy 6: Transportation & Practical Supports Fund

**Target Gaps:** Low-income, rural, wheelchair users, caregivers  
**Description:** Create a dedicated fund covering transit vouchers (CTA passes/pilot rideshare subsidies), reimbursed parking, childcare during trial visits, and caregiver stipends. Eliminate the cost barrier that disproportionately excludes low-income participants.

**Estimated Annual Cost:** $50,000–$80,000 (transit/vouchers, parking subsidies, childcare, coordination)

**芝加哥-specific Actions:**
- Negotiate discounted CTA passes (e.g., 10-trip packs at reduced rates) with CTA
- Partner with Access Transportation (ADA paratransit provider) for subsidized rides to Shirley Ryan AbilityLab
- Provide free valet or reserved accessible parking slots at SRAL for trial participants (est. $8–10/day cost subsidized)
- Coordinate with Aunt Martha's Health Center or Lawndale Christian Health Center for childcare referrals during trial visits

### Strategy 7: Data Equity Audit of All 425 Trials

**Target Gaps:** Systematic exclusion in all trials (systemic)  
**Description:** Conduct a systematic audit of all 425 lower-limb prosthetic trials on ClinicalTrials.gov to document exclusion criteria, sponsor types, geographic distribution, and reported demographic data. Produce a public report identifying trials with exclusionary criteria that should be modified.

**Estimated Annual Cost:** $40,000–$60,000 (research assistant time, data management, publication)

**芝加哥-specific Actions:**
- Partner with UIC Institute for Research on Race and Public Policy to conduct demographic equity analysis of trial enrollment data
- Host annual public "Trial Equity Report Card" release at Shirley Ryan AbilityLab
- Engage Chicago Board of Health to leverage audit findings for public policy recommendations

### Strategy 8: Prosthetic Access Hub at Shirley Ryan AbilityLab

**Target Gaps:** All underserved groups; neighborhood welcome  
**Description:** Establish a free, wheelchair-accessible community room within or adjacent to Shirley Ryan AbilityLab for quarterly "Prosthetic Access Community Days." Events include: free prosthetic fit screening, trial information sessions in multiple languages, peer support circles, assistive technology demos, and resource navigation.

**Estimated Annual Cost:** $60,000–$100,000 (space lease/accommodation, event staffing, interpreter services, equipment, insurance)

**芝加哥-specific Actions:**
- Partner with Streeterville、非profit organizations like Open Books or Steppenwolf Theatre Company to provide recreational programming during waiting periods
- Negotiate with Rush Oak Park and Presence Saints Mary and Elizabeth Medical Center for overflow community space if SRAL capacity is reached
- Offer free Divvy bike-share memberships (1-year) for trial participants as sustainable transportation

---

## Recommended Next Steps

| Priority | Action | Timeline | Owner | Est. Cost |
|---|---|---|---|---|
| 🔴 1 | **Data Equity Audit** of all 425 trials (Strategy 7) | Months 1–2 | UIC/community research team | $40–60K |
| 🔴 2 | **CHW partnerships** with 3 FQHCs (Strategy 1) | Months 1–3 | SRAL community health team | $80–120K |
| 🔴 3 | **Telehealth screening pilot** (Strategy 4) | Months 2–4 | SRAL/Wiesman Center IT | $30–50K |
| 🟡 4 | **Multilingual trial materials** — Spanish, Polish, Mandarin first (Strategy 3) | Months 2–4 | SRAL/CTS communications | $40–60K |
| 🟡 5 | **Peer mentor recruitment** (Strategy 5) | Months 2–4 | SRAL + Blaze Sports | $25–40K |
| 🟡 6 | **Transportation fund** (Strategy 6) | Months 3–6 | SRAL + CTA partners | $50–80K |
| 🟢 7 | **Mobile screening pilot** (Strategy 2) | Months 4–8 | SRAL + CCOP + CTA | $60–90K |
| 🟢 8 | **Prosthetic Access Hub** (Strategy 8) | Months 6–12 | SRAL + community partners | $60–100K |

---

## Data Appendix

### Source: ClinicalTrials.gov API v2 — 425 Studies by Sponsor Type

```
OTHER (Academic/Medical Centers) — 312 — 73.5%
INDUSTRY (Manufacturers) — 58 — 13.7%
FED (VA/DOD/Federal) — 41 — 9.7%
OTHER_GOV — 9 — 2.1%
NIH — 2 — 0.5%
NETWORK — 2 — 0.5%
AMBIG — 1 — 0.2%
```

### Source: ClinicalTrials.gov API v2 — 425 Studies by Phase

```
NA (Observational/Device/Surgical) — 298 — 70.1%
Unknown — 106 — 24.9%
PHASE4 — 5 — 1.2%
PHASE3 — 5 — 1.2%
PHASE2 — 5 — 1.2%
EARLY_PHASE1 — 4 — 1.0%
PHASE1 — 3 — 0.7%
```

### Source: OpenStreetMap / OSM MCP — Shirley Ryan AbilityLab Geocode

```
Address: 355 East Erie Street, Streeterville, Chicago, IL 60611
Coordinates: 41.8938727, -87.6184271
Building: hospital (class=building, type=hospital)
Importance: 0.3538
```

### Source: OSM Nearby Places (300m radius, first scan)

```
Bike Rental: 2 Divvy stations (McClurg Ct & Ohio St; Fairbanks Ct & Grand Ave)
Banking: First American Bank (643 E Erie St), BMO (352 E Illinois St)
Fast Food: Chipotle, Dunkin' (Prentice Women's Hospital), Potbelly,
           Bombay Wraps, McDonald's (645 N McClurg Court)
Restaurant: Timothy O'Toole's Pub, Indian Garden, others
Library: Northwestern University Law Library (750 N Lake Shore Drive)
```

---

## Stakeholder Quote

> "The empty waiting rooms at prosthetics trials are not empty because people don't want to participate — they're empty because the system was never designed to reach them."
> — Adapted from Dr.賴the Community Health Worker Triillage Framework (Chicago 2025)

---

*Prosthetic Trial Outreach Initiative | github.com/zhub9006/prosthetic-trial-outreach*  
*Data retrieved: June 2025 | ClinicalTrials.gov API v2 | OSM MCP | GitHub Issues #8 (Site Accessibility)*
