# Sudden Incapacitation or Death at the Wheel
## Unravelling the Predictors of Catastrophic Multi-Vehicle Collisions

![Graphical Abstract](Gemini_Generated_Image_dfc5tydfc5tydfc5 (1).jpg)

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Status](https://img.shields.io/badge/Status-Preprint_Live-green?style=flat-square)](https://www.preprints.org/manuscript/XXXX.XXXX/v1)
[![R-Stats](https://img.shields.io/badge/Language-R_4.0+-blue?style=flat-square)](analysis_script.R)

> [cite_start]**Author:** Dr. Nick Barua · AN Holdings Co., Nishinomiya City, Hyogo, Japan [cite: 174-176]
> [cite_start]**Study:** A 10-year retrospective cohort analysis ($N=1,258$) of medical driver emergencies. [cite: 181]

---

## 📌 Abstract
[cite_start]Sudden driver incapacitation—due to events like cardiac arrest or stroke—represents a significant road safety risk, often converting single-vehicle incidents into multi-vehicle collisions (MVCs)[cite: 180]. [cite_start]This study identified that MVC escalation is dictated by predictable, quantifiable factors, highlighting the critical role of automated intervention systems like ADAS in mitigating catastrophic outcomes[cite: 185].

---

## 🔑 Key Findings (Adjusted Odds Ratios)

| Predictor | Comparison | Adjusted $OR$ | 95% CI | $P$-Value |
| :--- | :--- | :---: | :---: | :---: |
| **Road Type** | Highway vs. Urban/Rural | **3.12** | 2.38–4.09 | <0.001 |
| **Vehicle Type** | Heavy vs. Light | **2.58** | 1.85–3.59 | <0.001 |
| **Initial Speed** | Per 10 km/h increase | **1.45** | 1.36–1.55 | <0.001 |
| **ADAS Presence** | Yes vs. No | **0.61** | 0.42–0.90 | 0.012 |

[cite_start][cite: 183-184, 254]

### 🚨 Headline Statistics
* [cite_start]**32.8%** of sudden incapacitation incidents escalated into MVCs (412 of 1,258). [cite: 182, 233]
* [cite_start]**Highway incidents** carried >3x the adjusted odds of MVC escalation ($OR=3.12$). [cite: 183, 244]
* [cite_start]**ADAS (AEB + LKA)** reduced MVC odds by **39%** ($OR=0.61$). [cite: 184, 247]

---

## 📊 Crash Characteristics (Cohort Distribution)

| Characteristic | Category | $N$ (%) | MVC $n$ (% of category) |
| :--- | :--- | :---: | :---: |
| **Road Type** | Highway | 418 (33.2%) | **58.4%** |
| | Urban/Rural | 840 (66.8%) | **20.0%** |
| **Vehicle Type** | Heavy Vehicle | 214 (17.0%) | **57.0%** |
| | Sedan/Light Vehicle | 1,044 (83.0%) | **27.8%** |
| **ADAS Presence** | Yes | 187 (14.9%) | **22.5%** |
| | No | 1,071 (85.1%) | **34.5%** |

[cite_start][cite: 240, 426]

---

## 🔬 Methodology
* [cite_start]**Statistical Method:** Binary logistic regression (Hosmer–Lemeshow $\chi^2(8) = 7.32, p = 0.503$). [cite: 182, 249]
* [cite_start]**Code Availability:** The complete R script for data preprocessing and regression modeling is available in `analysis_script.R`. [cite: 230, 518]

---

## 📝 Citation
```bibtex
@article{barua2026sudden,
  title={Sudden Incapacitation or Death at the Wheel: Probabilistic Risk Factors for Catastrophic Multi-Vehicle Collisions},
  author={Barua, Nick},
  year={2026},
  journal={Preprints.org},
  doi={ENTER_DOI_HERE}
}
