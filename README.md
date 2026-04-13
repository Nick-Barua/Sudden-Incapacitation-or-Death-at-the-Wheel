# Sudden Incapacitation or Death at the Wheel
## Unravelling the Predictors of Catastrophic Multi-Vehicle Collisions

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Status](https://img.shields.io/badge/Status-Preprint_Pending-orange?style=flat-square)](https://ssrn.com/author=nick-barua)
[![R-Stats](https://img.shields.io/badge/Language-R_4.0+-blue?style=flat-square)](analysis_script.R)

> **Author:** Dr. Nick Barua · AN Holdings Co., Nishinomiya City, Hyogo, Japan
> **Manuscript:** Sudden Incapacitation or Death at the Wheel: Probabilistic Risk Factors for Catastrophic Multi-Vehicle Collisions

---

## 📌 Abstract

Sudden driver incapacitation—due to events like cardiac arrest, stroke, or seizure—represents a significant road safety risk, often converting single-vehicle incidents into multi-vehicle collisions (MVCs). This retrospective cohort study ($N = 1,258$) analysed incidents from the National Traffic Accident Database (2015–2024). 

Using binary logistic regression, we modelled MVC occurrence against environmental and vehicular variables. Results demonstrate that MVC escalation is dictated by predictable, quantifiable factors, highlighting the critical role of automated intervention systems like ADAS in mitigating catastrophic outcomes.

---

## 🔑 Key Findings (Adjusted Odds Ratios)

| Predictor | Comparison | Adjusted $OR$ | 95% CI | $P$-Value |
| :--- | :--- | :---: | :---: | :---: |
| **Road Type** | Highway vs. Urban/Rural | **3.12** | 2.38–4.09 | <0.001 |
| **Vehicle Type** | Heavy vs. Light | **2.58** | 1.85–3.59 | <0.001 |
| **Initial Speed** | Per 10 km/h increase | **1.45** | 1.36–1.55 | <0.001 |
| **ADAS Presence** | Yes vs. No | **0.61** | 0.42–0.90 | 0.012 |

*Table data sources:*

### 🚨 Headline Statistics
* **32.8%** of sudden incapacitation incidents escalated into MVCs (412 of 1,258).
* **Highway incidents** carried >3x the adjusted odds of MVC escalation.
* **Heavy vehicles** carry 2.58x higher odds of escalation, driven by kinetic energy factors ($KE = \frac{1}{2}mv^2$).
* **ADAS (AEB + LKA)** reduced MVC odds by **39%** ($OR = 0.61$).

---

## 📊 Crash Characteristics (Cohort Distribution)

| Characteristic | Category | $N$ (%) | MVC $n$ (% of category) |
| :--- | :--- | :---: | :---: |
| **Road Type** | Highway | 418 (33.2%) | **58.4
