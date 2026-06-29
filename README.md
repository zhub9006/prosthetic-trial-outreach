# prosthetic-trial-outreach

Documenting findings on prosthetic clinical trial participation gaps for underserved populations and proposed outreach strategies.

## Project Overview

This project assesses the landscape of lower limb prosthetic clinical trials on ClinicalTrials.gov, evaluates the Shirley Ryan AbilityLab (355 E Erie St, Chicago, IL) as a community outreach site, and proposes strategies to reach underserved populations missing from current trials.

## Key Findings

- **425 studies** match "lower limb prosthetic" on ClinicalTrials.gov (confirmed via API v2 analysis); only **1.9% are Phase III/IV** and **13.6% are industry-sponsored**
- **7 underserved populations** are systematically excluded: non-veteran women, low-income/uninsured, elderly 75+ with comorbidities, non-English speakers, rural residents, wheelchair-dependent users, trauma amputees
- **Shirley Ryan AbilityLab** scores ⭐⭐⭐⭐ (4/5) as a clinical anchor — excellent credibility and transit access (15 CTA bus stops, 5 Divvy stations within 500m), but paid parking and affluent neighborhood create access barriers

## Repository Structure

| File | Description |
|---|---|
| `README.md` | This file |
| `CONSOLIDATED_ASSESSMENT.md` | **Comprehensive master report** — all trial gaps, site accessibility, and 7 outreach strategies in one document |
| `PROSTHETIC_OUTREACH_REPORT.md` | Comprehensive report — clinical trial gap analysis, Shirley Ryan AbilityLab site assessment, and 7 proposed outreach strategies |
| `TRIAL_GAPS_AND_OUTREACH.md` | Full clinical trial gap analysis from ClinicalTrials.gov API data |
| `SITE_ASSESSMENT_SHIRLEY_RYAN.md` | Detailed site accessibility assessment (500 m radius) + 7 outreach strategies + 10 next steps |
| `OUTREACH_ASSESSMENT.md` | Community outreach assessment framework |
| `OUTREACH_REPORT.md` | Outreach strategy report |
| `PROSTHETIC_OUTREACH.md` | Prosthetic outreach summary |
| `PROSTHETIC_TRIAL_ASSESSMENT.md` | Prosthetic trial assessment |
| `prosthetic-trial-outreach-strategies.md` | Outreach strategies document |
| `trial-gaps-and-outreach-strategies.md` | Trial gaps and strategies |
| `TRIAL_OUTREACH_ASSESSMENT.md` | Trial outreach assessment |

## ClinicalTrials.gov Data Summary (Verified — API v2)

| Analysis | Result |
|---|---|
| Total studies (lower limb prosthetic) | **425** unique studies |
| Sponsor: OTHER (Academic) | 312 (73.4%) |
| Sponsor: INDUSTRY | 58 (13.6%) |
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

## Key Gaps Identified

1. **Sponsor Imbalance:** 73.4% academic/unclear sponsors vs. only 13.6% industry — lacks community outreach infrastructure
2. **Phase Shortage:** 95% of studies are NA, Unknown, or early-phase — critical lack of high-quality interventional evidence
3. **Population Exclusion:** 7 underserved groups systematically excluded — women, low-income, elderly, non-English speakers, rural, wheelchair users, trauma amputees

## Shirley Ryan AbilityLab Site Assessment (500 m radius)

| Factor | Rating | Notes |
|--------|--------|-------|
| Clinical Credibility | ⭐⭐⭐⭐⭐ | World-renowned rehab hospital (#1 US News & World Report) |
| Transit Access | ⭐⭐⭐⭐ | 15 CTA bus stops + 5 Divvy stations within 500m; no tactile paving |
| Support Amenities | ⭐⭐⭐⭐ | Walgreens (24/7 pharmacy), banks, diverse food, Whole Foods, AMC |
| Parking | ⭐⭐ | Multi-storey ($) and underground; barrier for low-income users |
| Neighborhood | ⭐⭐⭐ | Affluent Streeterville; may feel unwelcoming to some users |
| Overall | ⭐⭐⭐⭐ (4/5) | Strong candidate with modifications needed |

## Outreach Strategies Proposed

1. **CHW Bridge Program** — Community Health Workers as trial navigators
2. **Mobile Prosthetic Clinics** — On-site screening in underserved communities
3. **Multicultural Outreach** — Faith-based partnerships, multilingual materials
4. **Telehealth Screening** — Remote trial eligibility assessments
5. **Peer Mentor Network** — Diverse prosthetic users as mentors
6. **Transportation/Childcare Support** — Remove practical barriers
7. **Data Equity Audit** — Audit trials for exclusionary criteria

## Start Here

👉 **[CONSOLIDATED_ASSESSMENT.md](CONSOLIDATED_ASSESSMENT.md)** — The complete report covering all three domains: trial gaps, site accessibility, and outreach strategies.

## Access Issues & PTA Chicago

For the full list of the 15 CTA bus stops, parking facilities, pharmacy, and daily-living amenities within 500m of Shirley Ryan AbilityLab, see:
- [Issue #8: Shirley Ryan AbilityLab — Local Amenities & Transit Guide](https://github.com/zhub9006/prosthetic-trial-outreach/issues/8)

## Data Sources

- ClinicalTrials.gov API v2 (`/studies`, `/analysis`) — retrieved 2025-06-29
- OpenStreetMap / OSM MCP (geocoding, nearby search, 500 m radius) — retrieved 2025-06-29

---

*Prosthetic Trial Outreach Initiative | github.com/zhub9006/prosthetic-trial-outreach*