# prosthetic-trial-outreach

Documenting findings on prosthetic clinical trial participation gaps for underserved populations and proposed outreach strategies.

## Project Overview

This project assesses the landscape of lower limb prosthetic clinical trials on ClinicalTrials.gov, evaluates the Shirley Ryan AbilityLab (355 E Erie St, Chicago, IL) as a community outreach site, and proposes strategies to reach underserved populations missing from current trials.

## Key Findings

- **425 studies** match "lower limb prosthetic" on ClinicalTrials.gov (confirmed via API v2 analysis); only **1.9% are Phase III/IV** and **13.6% are industry-sponsored**
- **7 underserved populations** are systematically excluded: non-veteran women, low-income/uninsured, elderly 75+ with comorbidities, non-English speakers, rural residents, wheelchair-dependent users, trauma amputees
- **Shirley Ryan AbilityLab** scores ⭐⭐⭐⭐ (4/5) as a clinical anchor — excellent credibility and transit access (15 CTA bus stops, 5 Divvy stations + bike-share within 500 m), but paid parking and affluent neighborhood create access barriers
- **6 verified active/upcoming trials** retrieved directly from ClinicalTrials.gov API — all focused on transfemoral amputees; only 1 currently recruiting

## Repository Structure

| File | Description |
|---|---|
| `README.md` | This file |
| `RAW_FINDINGS_THIS_SESSION.md` | **Session-specific raw data** (2025-06-29) — ClinicalTrials.gov trial details, geocoding, nearby amenities (healthcare, pharmacy, transit, parking), and site suitability analysis |
| `CONSOLIDATED_ASSESSMENT.md` | **Consolidated master report** — trial gaps, site accessibility, and 7 outreach strategies |
| `CONSOLIDATED_OUTREACH_ASSESSMENT.md` | **New in Jun 2026** — fully updated consolidated report with 8 strategies, next-steps roadmap, and data-collection appendix |
| `PROSTHETIC_OUTREACH_REPORT.md` | Comprehensive report — clinical trial gap analysis, Shirley Ryan AbilityLab site assessment, and 7 proposed outreach strategies |
| `PROSTHETIC_TRIAL_ASSESSMENT.md` | Clinical trial gap analysis — sponsor distribution, phase distribution, eligibility gaps per trial |
| `SITE_ASSESSMENT_SHIRLEY_RYAN.md` | Detailed site accessibility (500 m radius) + amenities + transit analysis |
| `TRIAL_GAPS_AND_OUTREACH.md` | Full clinical trial gap analysis from ClinicalTrials.gov API data |
| `trial-gaps-and-outreach-strategies.md` | Trial gaps and strategies overview |
| `OUTREACH_ASSESSMENT.md` | Community outreach assessment framework |
| `OUTREACH_REPORT.md` | Outreach strategy report |
| `prosthetic-trial-outreach-strategies.md` | Outreach strategies document |
| `TRIAL_OUTREACH_ASSESSMENT.md` | Trial outreach assessment |

## ClinicalTrials.gov Data Summary (Verified — API v2)

| Analysis | Result |
|---|---|
| Total studies (lower limb prosthetic) | **425** unique studies |
| Sponsor: OTHER (Academic) | 312 (73.5%) |
| Sponsor: INDUSTRY | 58 (13.7%) |
| Sponsor: FED (VA/DOD/Federal) | 41 (9.7%) |
| Sponsor: OTHER_GOV | 9 (2.1%) |
| Sponsor: NETWORK | 2 (0.5%) |
| Sponsor: NIH | 2 (0.5%) |
| Sponsor: AMBIG | 1 (0.2%) |
| Phase: NA (Observational) | 298 (70.1%) |
| Phase: Unknown | 106 (24.9%) |
| Phase: Phase III | 5 (1.2%) |
| Phase: Phase IV | 5 (1.2%) |
| Phase: Phase II | 5 (1.2%) |
| Phase: Early Phase 1 | 4 (1.0%) |
| Phase: Phase 1 | 3 (0.7%) |

**95.0% of studies are observational, unknown, or early-phase.** Only 2.9% reach Phase I–IV efficacy testing. No trials are sponsored by FQHCs, community health centers, or safety-net hospitals.

## Starting Points

| Need | Start Here |
|---|---|
| **Complete assessment (trial gaps + site + strategies)** | 📄 [CONSOLIDATED_OUTREACH_ASSESSMENT.md](CONSOLIDATED_OUTREACH_ASSESSMENT.md) |
| **Quick overview of key findings** | 📄 [CONSOLIDATED_ASSESSMENT.md](CONSOLIDATED_ASSESSMENT.md) |
| **Clinical trial detail** | 📄 [PROSTHETIC_TRIAL_ASSESSMENT.md](PROSTHETIC_TRIAL_ASSESSMENT.md) |
| **Site/accessibility detail** | 📄 [SITE_ASSESSMENT_SHIRLEY_RYAN.md](SITE_ASSESSMENT_SHIRLEY_RYAN.md) |
| **Session-specific raw findings (this session)** | 📄 [RAW_FINDINGS_THIS_SESSION.md](RAW_FINDINGS_THIS_SESSION.md) |
| **Community amenities & transit guide** | 📖 [GitHub Issue #8](https://github.com/zhub9006/prosthetic-trial-outreach/issues/8): Shirley Ryan AbilityLab — Local Amenities & Transit Guide |
| **Session raw findings tracking** | 📖 [GitHub Issue #9](https://github.com/zhub9006/prosthetic-trial-outreach/issues/9): Raw Findings This Session data |

## Key Gaps Identified

| # | Gap | Evidence |
|---|-----|----------|
| 1 | **Sponsor Imbalance** — 73.5% academic vs. 13.7% industry | No community outreach infrastructure; zero FQHC/safety-net sponsors |
| 2 | **Phase Shortage** — 95% observational/unknown | Only 12 trials (2.9%) in Phase I–IV; digital-division exclusion in registries |
| 3 | **Population Exclusion** — 7 underserved groups | Women, low-income, elderly 75+, non-English speakers, rural, wheelchair users, trauma amputees all systematically excluded |
| 4 | **No geographic diversity** | Trials concentrated in 5–10 academic medical centers |
| 5 | **Language barrier** | All trials require English/Spanish only |

## Shirley Ryan AbilityLab Site Assessment (500 m Radius)

| Factor | Rating | Key Notes |
|---|---|---|
| Clinical Credibility | ⭐⭐⭐⭐⭐ | World-renowned rehab hospital; #1 U.S. News & World Report |
| Transit Access | ⭐⭐⭐⭐ | 15 CTA bus stops + 5 Divvy stations within 500 m; no tactile paving |
| Healthcare Proximity | ⭐⭐⭐⭐⭐ | On-site rehab hospital; 24/7 Walgreens 390 m away |
| Support Amenities | ⭐⭐⭐⭐ | Whole Foods, banks, diverse food, ATMs, post office, cinema |
| Parking | ⭐⭐ | Only paid multi-storey ($15–30/day) and underground; no free options |
| Neighborhood Welcomeness | ⭐⭐⭐ | Affluent Streeterville; may feel unwelcoming to lower-income users |
| Wheelchair Accessibility | ⭐⭐⭐⭐ | Most amenities accessible; bus stops lack tactile paving |
| Overall | ⭐⭐⭐⭐ (4/5) | Strong clinical anchor; accessibility modifications needed |

## Outreach Strategies (Updated Jun 2026)

| # | Strategy | Target Gaps | Est. Annual Cost |
|---|----------|-------------|-----------------|
| 1 | **CHW Bridge Program** — Community Health Workers as trial navigators | Low-income, non-English, rural | $80K–$120K |
| 2 | **Mobile Prosthetic Screening Clinics** — On-site screening in underserved communities | Rural, low-income, wheelchair users, elderly | $60K–$90K |
| 3 | **Multicultural & Multilingual Outreach** — Faith-based partnerships, translated materials | Non-English speakers, immigrant communities | $40K–$60K |
| 4 | **Telehealth Eligibility Screening** — Remote trial assessment | Rural, wheelchair users, elderly, low-income | $30K–$50K |
| 5 | **Peer Mentor Network** — Diverse amputees as mentors | All underserved groups | $25K–$40K |
| 6 | **Transportation & Practical Supports** — Transit credits, childcare, parking vouchers | Low-income, rural, wheelchair users, caregivers | $50K–$80K |
| 7 | **Data Equity Audit** — Audit trials for exclusionary criteria | All underserved groups (systemic) | $40K–$60K |
| 8 | **Prosthetic Access Hub** — Free community room + quarterly community days | All underserved groups; neighborhood welcome | $60K–$100K |

## Recommended Next Steps (Top 5, Priority Order)

1. 🔴 **Data Equity Audit** of all 425 trials → Month 1–2
2. 🔴 **CHW partnerships** with 3 FQHCs → Month 1–3
3. 🔴 **Telehealth screening pilot** → Month 2–4
4. 🟡 **Multilingual trial materials** (Spanish, Polish, Mandarin first) → Month 2–4
5. 🟡 **Peer mentor recruitment** → Month 2–4

## Full Outreach Roadmap

See [CONSOLIDATED_OUTREACH_ASSESSMENT.md](CONSOLIDATED_OUTREACH_ASSESSMENT.md) for the complete 9-step action plan with timeline, cost estimates, and ownership assignments.

## Data Sources

- **ClinicalTrials.gov API v2** — `/studies` (425 total), `/get_study` (6 verified trials: NCT07204912, NCT03204513, NCT06844305, NCT07491614, NCT07103798, NCT07613502), retrieved 2025-06-29
- **OpenStreetMap / OSM MCP** — Geocoding, nearby POI search, route directions, 500 m radius analysis, retrieved 2025-06-29

---

*Prosthetic Trial Outreach Initiative | github.com/zhub9006/prosthetic-trial-outreach*