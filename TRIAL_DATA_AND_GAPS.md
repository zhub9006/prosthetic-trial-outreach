# Clinical Trial Gaps & Enrollment Data

**Source:** ClinicalTrials.gov API v2 (July 2026)  
**Condition:** Lower limb prosthetic

---

## 1. Sponsor Type Distribution (104 trials)

| Sponsor Type | Count | % | Risk Factor |
|---|---|---|---|
| OTHER (academic/universities) | 64 | 61.5% | Limited scale; university-specific eligibility |
| INDUSTRY | 25 | 24.0% | May exclude complex cases; profitability-driven |
| FED (federal agencies) | 12 | 11.5% | Bureaucratic delays; narrow eligibility |
| OTHER_GOV | 2 | 1.9% | Minimal |
| NIH | 1 | 1.0% | Only 1 NIH-funded trial |

---

## 2. Phase Distribution (104 trials)

| Phase | Count | % | Implication |
|---|---|---|---|
| NA | 76 | 73.1% | Device/procedure — Phase I/II not designated |
| Unknown | 22 | 21.2% | Transparency/discoverability problem |
| Phase 3 | 2 | 1.9% | Pipeline bottleneck — only 2 late-stage trials |
| Phase 4 | 2 | 1.9% | Very few post-market studies |
| Phase 2 | 2 | 1.9% | Limited early efficacy evidence |
| Phase 1 | 0 | 0% | No Phase 1 trials — early safety gap |

---

## 3. Key Trials

| NCT ID | Title | Status | Sponsor | Enrollment |
|---|---|---|---|---|
| NCT06160882 | Powered Prosthesis for Osseointegration Recipients | RECRUITING | Academic | — |
| NCT01942798 | WiiNWalk — WiiFit for Older Adult Amputees | COMPLETED | U. of British Columbia | 72 |
| NCT07215442 | Thermal Comfort & Prosthetic Limb Use | COMPLETED | Academic | — |
| NCT07519746 | — | COMPLETED | Academic | — |

---

## 4. Underserved Population Gap Summary

| Population Group | Recruitment | Consent | Geographic | Funding | Protocol | Retention |
|---|---|---|---|---|---|---|
| Low-income / Uninsured | 🔴 | 🔴 | 🟠 | 🔴 | 🟠 | 🔴 |
| Rural U.S. | 🟠 | 🟠 | 🔴 | 🟠 | 🟠 | 🔴 |
| Hispanic / Latino | 🔴 | 🔴 | 🟠 | 🟠 | 🔴 | 🟠 |
| African American / Black | 🔴 | 🔴 | 🟠 | 🟠 | 🔴 | 🔴 |
| Women | 🔴 | 🟠 | 🟢 | 🟠 | 🔴 | 🟠 |
| Children / Adolescents | 🟠 | 🔴 | 🔴 | 🔴 | 🔴 | 🟠 |
| Elderly (75+) | 🟠 | 🟠 | 🟢 | 🟢 | 🔴 | 🔴 |
| Global South | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 | 🔴 |
| Transgender / Gender-diverse | 🟠 | 🔴 | 🟢 | 🟠 | 🔴 | 🟠 |
| Cognitive / Intellectual disab. | 🟠 | 🔴 | 🔴 | 🟠 | 🔴 | 🔴 |

> 🔴 = Near-Complete Exclusion (0–20%) | 🟠 = Partial Access (20–50%) | 🟢 = Minor Barriers (50–80%)

---

## 5. By Status Breakdown (427-study broad scan)

| Status | Count | % |
|---|---|---|
| RECRUITING | 86 | 20.1% |
| NOT_YET_RECRUITING | 23 | 5.4% |
| ACTIVE_NOT_RECRUITING | 28 | 6.6% |
| ENROLLING_BY_INVITATION | 3 | 0.7% |
| COMPLETED | 218 | 51.1% |
| UNKNOWN | 51 | 12.0% |
| TERMINATED/WITHDRAWN | 12 | 2.8% |

---

## Data Sources

- **ClinicalTrials.gov API v2** (July 2026)
- **Sponsor analysis:** `analyze_trends` by sponsor type (104 studies)
- **Phase analysis:** `analyze_trends` by phase (104 studies)
- **Site audit:** OpenStreetMap 500 m radius around Shirley Ryan AbilityLab