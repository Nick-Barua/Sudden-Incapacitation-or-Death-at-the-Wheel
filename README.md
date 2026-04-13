# Sudden Incapacitation or Death at the Wheel
## Unravelling the Predictors of Catastrophic Multi-Vehicle Collisions

![Graphical Abstract](Sudden%20Incapacitation%20or%20Death%20at%20the%20Wheel%20-GA.png)

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Status](https://img.shields.io/badge/Status-SSRN_Live-blue?style=flat-square)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6421086)
[![R-Stats](https://img.shields.io/badge/Language-R_4.0+-blue?style=flat-square)](analysis_script.R)

> [cite_start]**Author:** Dr. Nick Barua · AN Holdings Co., Nishinomiya City, Hyogo, Japan [cite: 3, 4, 181]
> [cite_start]**Study:** A 10-year retrospective cohort analysis ($N=1,258$) of medical driver emergencies[cite: 9, 34, 185, 215].

---

## 📌 Abstract

[cite_start]Sudden driver incapacitation—due to events such as cardiac arrest, acute stroke, or generalized seizure—represents a significant road safety risk, often converting single-vehicle incidents into multi-vehicle collisions (MVCs)[cite: 8, 17, 184, 195]. [cite_start]This study identifies that MVC escalation is dictated by predictable, quantifiable factors, highlighting the critical role of automated intervention systems like ADAS in mitigating catastrophic outcomes[cite: 13, 189, 343].

---

## 🔑 Key Findings (Adjusted Odds Ratios)

[cite_start]Binary logistic regression was used to estimate the independent contribution of predictor variables to MVC escalation[cite: 29, 54, 207, 238].

| Predictor | Comparison | Adjusted $OR$ | 95% CI | $P$-Value |
| :--- | :--- | :---: | :---: | :---: |
| **Road Type** | Highway vs. Urban/Rural | **3.12** | 2.38–4.09 | <0.001 |
| **Vehicle Type** | Heavy vs. Light | **2.58** | 1.85–3.59 | <0.001 |
| **Initial Speed** | Per 10 km/h increase | **1.45** | 1.36–1.55 | <0.001 |
| **ADAS Presence** | Yes vs. No | **0.61** | 0.42–0.90 | 0.012 |

[cite_start][cite: 11, 12, 72, 73, 75, 187, 188, 259, 260, 262]

### 🚨 Headline Statistics
* [cite_start]**32.8%** of sudden incapacitation incidents escalated into MVCs (412 of 1,258)[cite: 10, 61, 186, 245].
* [cite_start]**Highway incidents** carry more than three times the adjusted odds of MVC escalation ($OR = 3.12$)[cite: 72, 187, 259].
* [cite_start]**Heavy vehicles** carry 2.58x higher odds of escalation, driven by kinetic energy factors ($KE = \frac{1}{2}mv^2$)[cite: 73, 104, 187, 260, 295].
* [cite_start]**ADAS (AEB + LKA)** reduced MVC odds by **39%** ($OR = 0.61$)[cite: 75, 116, 188, 309].

---

## 📊 Crash Characteristics (Cohort Distribution)

[cite_start]Detailed breakdown of the $N = 1,258$ incident cohort[cite: 67, 253].

| Characteristic | Category | $N$ (%) | MVC $n$ (% of category) |
| :--- | :--- | :---: | :---: |
| **Road Type** | Highway | 418 (33.2%) | **58.4%** |
| | Urban/Rural | 840 (66.8%) | **20.0%** |
| **Vehicle Type** | Heavy Vehicle | 214 (17.0%) | **57.0%** |
| | Sedan/Light Vehicle | 1,044 (83.0%) | **27.8%** |
| **ADAS Presence** | Yes | 187 (14.9%) | **22.5%** |
| | No | 1,071 (85.1%) | **34.5%** |

[cite_start][cite: 68, 254]

---

## 🔬 Methodology

* [cite_start]**Data Source:** National Traffic Accident Database (NTAD), 2015–2024[cite: 34, 185, 215].
* [cite_start]**Sample Selection:** Eligible cases included driver death from natural causes or sudden medical incapacitation preceding a collision[cite: 38, 185, 219].
* [cite_start]**Statistical Method:** Binary logistic regression with Hosmer–Lemeshow goodness-of-fit test ($\chi^2(8) = 7.32, p = 0.503$)[cite: 54, 77, 238, 264].
* [cite_start]**Code Availability:** The complete analytical workflow is documented in `analysis_script.R`[cite: 58, 242, 346].

---

## 📝 Citation

If you use this research or code in your work, please cite it as follows:

```bibtex
@article{barua2026sudden,
  title={Sudden Incapacitation or Death at the Wheel: Probabilistic Risk Factors for Catastrophic Multi-Vehicle Collisions},
  author={Barua, Nick},
  year={2026},
  journal={SSRN Working Paper},
  url={[https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6421086](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6421086)}
}
