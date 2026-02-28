# Sudden Incapacitation or Death at the Wheel
## Unravelling the Predictors of Catastrophic Multi-Vehicle Collisions

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Status](https://img.shields.io/badge/Status-SSRN_Pending-orange?style=flat-square)](https://ssrn.com/author=nick-barua)
[![ADAS](https://img.shields.io/badge/Focus-ADAS_Safety-red?style=flat-square)](#key-findings)
[![Study](https://img.shields.io/badge/Study-Retrospective_Cohort-green?style=flat-square)](#methodology)

> **Author:** Dr. Nick Barua · AN Holdings Co., Nishinomiya City, Hyogo, Japan
> **Status:** Preprint — SSRN submission pending
> **Part of:** [4-Paper Road Safety Research Program](#related-publications)

---

## 📌 Abstract

Sudden fatal health events in drivers are a critical road safety concern that can lead to
devastating multi-vehicle collisions (MVCs). This study identifies key predictors that
escalate a driver's sudden incapacitation into an MVC. We conducted a retrospective
cohort study using a national traffic accident database from **2015–2024**, analysing
**1,258 incidents** caused by a driver's sudden medical event.

A binary logistic regression model assessed variables including road type, vehicle type,
speed, and ADAS presence. Results showed that **32.8% of incidents became MVCs**.
The transition to an MVC is not random — it is dictated by predictable, quantifiable
factors. The protective effect of ADAS highlights a critical avenue for technological
intervention.

**Keywords:** Sudden Death · Traffic Accidents · Multi-Vehicle Collision · Road Safety · Driver Incapacitation · ADAS

---

## 🔑 Key Findings

| Predictor | Comparison | Odds Ratio (OR) | 95% CI | P-Value |
| :--- | :--- | :---: | :---: | :---: |
| **Road Type** | Highway vs. Urban/Rural | **3.12** | 2.45–3.98 | <0.05 |
| **Vehicle Type** | Heavy vs. Light | **2.58** | 1.29–1.63 | <0.05 |
| **Initial Speed** | Per 10 km/h increase | **1.45** | 0.89–1.48 | <0.05 |
| **ADAS Presence** | Yes vs. No | **0.61** | — | <0.001 |
| **Time of Day** | Peak vs. Off-Peak | N/S | — | 0.285 |

> N/S = Not Statistically Significant

### 🚨 Headline Statistics
- **32.8%** of sudden incapacitation incidents escalated into MVCs (412 of 1,258)
- **67.2%** remained single-vehicle collisions (846 of 1,258)
- Highway incidents were **3x more likely** to become MVCs
- Heavy vehicles carried **2.58x higher odds** of causing an MVC
- ADAS reduced MVC odds by **39%** (OR = 0.61, p < 0.001)

---

## 📊 Crash Characteristics

| Characteristic | Category | SVC (n=846) | MVC (n=412) |
| :--- | :--- | :---: | :---: |
| **Road Type** | Highway | 1% | 83% |
| | Urban/Rural | 4% | 53% |
| **Vehicle Type** | Light Vehicle | 8% | 49% |
| | Heavy Vehicle | 12% | 32% |
| **ADAS Presence** | No | 21% | 21% |
| | Yes | 6% | 44% |

---

## 🔬 Methodology

- **Study Design:** Retrospective cohort study
- **Data Source:** National Traffic Accident Database (NTAD), 2015–2024
- **Sample Size:** 1,258 incidents of sudden driver incapacitation
- **Primary Outcome:** Binary — Single-Vehicle Collision (SVC) vs. Multi-Vehicle Collision (MVC)
- **Statistical Method:** Binary logistic regression (p < 0.05 significance threshold)

### Independent Variables Analysed
- **Road Type** — Highway vs. Urban/Rural
- **Time of Day** — Peak vs. Off-Peak
- **Vehicle Type** — Sedan/Light vs. Heavy Vehicle
- **Initial Speed** — Estimated speed at time of incapacitation (km/h)
- **ADAS Presence** — AEB + Lane-Keeping Assist (Yes/No)

---

## 💡 Key Conclusions

- **Highway environments** are the single most dangerous context for driver incapacitation events — high speed, traffic density, and limited evasion options create chain-reaction collision risk
- **Heavy vehicles** pose a disproportionate kinetic threat due to mass and longer stopping distances — suggesting need for stricter commercial driver medical screening
- **ADAS is a proven failsafe** — the 39% MVC reduction demonstrates that automated safety technologies can meaningfully intervene when the human element fails
- **Time of day is not a significant predictor** — risk is environment- and vehicle-driven, not temporal

---

## 🔗 Related Publications

This paper is **Part 4** of a unified road safety research program:

| # | Title | Venue | Contribution |
| :---: | :--- | :---: | :--- |
| 1 | [Advanced Multi-Modal Sensor Fusion System for Detecting Falling Humans](https://doi.org/10.3390/vehicles7040149) | MDPI Vehicles | Technical foundation & benchmarks |
| 2 | [From Post-Mortem to Prevention: Redefining "Invisible" Pedestrians through ISO 26262 and Multi-Modal AI](https://doi.org/10.2139/ssrn.6305618) | SSRN | Problem framing & ISO 26262 compliance |
| 3 | [Integrated Safety Architectures: Leveraging Multi-Modal AI and ISO 26262 to Protect Vulnerable Road Users](https://ssrn.com/author=nick-barua) | SSRN | System-level VRU architecture |
| 4 | **Sudden Incapacitation or Death at the Wheel** *(this paper)* | SSRN *(pending)* | Epidemiological evidence for ADAS mandate |

---

## 📝 Citation

Once published on SSRN, please cite as:
```bibtex
@article{barua2026sudden,
  title={Sudden Incapacitation or Death at the Wheel: Unravelling the 
         Predictors of Catastrophic Multi-Vehicle Collisions},
  author={Barua, Nick},
  journal={SSRN Working Paper},
  year={2026},
  publisher={AN Holdings Co.},
  address={Nishinomiya City, Hyogo, Japan}
}
```

> ⚠️ DOI will be added upon SSRN publication. Check back for updates.

---

## 📜 License

This project is licensed under the **Apache 2.0 License** — see the [LICENSE](LICENSE) file for details.
