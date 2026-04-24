# Ireland-Forestry-DSS-Modelling-the-Afforestation-Scheme
This repository presents a data-driven Decision Support System (DSS) designed to optimise Ireland’s afforestation strategy (2023–2027). It integrates carbon sequestration modelling, species–soil suitability analysis, and financial projections within an interactive Tableau analytics environment. The platform is built on a core principle: Data-driven analysis first, model-based insights second, policy-aligned decisions final.

![Tableau](https://img.shields.io/badge/Tableau-Public-orange)
![Framework](https://img.shields.io/badge/Framework-FDIKW-blue)
![Method](https://img.shields.io/badge/Method-MCDA-green)
![Analytics](https://img.shields.io/badge/Analytics-Carbon_Modelling-darkgreen)
![GIS](https://img.shields.io/badge/Data-GIS-lightgrey)
![Domain](https://img.shields.io/badge/Domain-Sustainability-brightgreen)
![Strategy](https://img.shields.io/badge/Focus-Climate_Strategy-blueviolet)
![Type](https://img.shields.io/badge/System-Decision_Support-black)
![Viz](https://img.shields.io/badge/Visualisation-Tableau-yellow)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

Tableau Public Decision Intelligence FDIKW MCDA Sustainability Analytics Climate Strategy Data Visualisation

# 🌳 Ireland Forestry DSS

### Modelling the Afforestation Scheme (2023–2027)

🔗 **Live Interactive Dashboard (Tableau Public)**
👉 [https://public.tableau.com/app/profile/sudarshan.e7719/viz/IrelandForestryDSSModellingtheAfforestationScheme/MIS41040?publish=yes](https://public.tableau.com/app/profile/sudarshan.e7719/viz/IrelandForestryDSSModellingtheAfforestationScheme/MIS41040?publish=yes)

---

## 🧭 Executive Summary

This project develops a **Decision Support System (DSS)** to support Ireland’s afforestation targets under the 2023–2027 forestry programme. The system integrates carbon, species, and soil datasets into a unified analytical framework to support **operational, tactical, and strategic decision-making**.

Using the **FDIKW (Data–Information–Knowledge–Wisdom)** model, raw environmental data is transformed into:

* Carbon sequestration projections
* Financial forecasts (premium income)
* Species–soil suitability insights

A **multi-criteria decision analysis (MCDA)** identifies five optimal species balancing carbon performance, yield, and biodiversity.

📌 **Key Finding:**
Achieving **18% national forest cover is feasible** with sustained planting rates and an optimal species mix aligned to soil conditions.

---

## 📌 Problem Context

Ireland currently has **11.6% forest cover**, among the lowest in Europe. The government’s afforestation scheme targets:

* **8,000 hectares planted annually**
* **18% national forest cover by 2027**

However, decision-making is complex due to:

* Fragmented datasets (carbon, soil, species)
* Trade-offs between carbon, biodiversity, and financial returns
* Lack of integrated analytical tools

This DSS addresses these challenges through a **data-driven, interactive modelling approach**.

---

## 🎯 Objectives

* Develop a DSS for afforestation planning
* Integrate carbon, soil, and species datasets
* Identify optimal species using MCDA
* Enable scenario testing for planting strategies
* Support long-term sustainability and policy decisions

---

## 🧠 Methodology

### 🔷 FDIKW Framework

| Level       | Application                                     |
| ----------- | ----------------------------------------------- |
| Data        | Biomass tables, species database, soil GIS data |
| Information | Cleaned and structured datasets                 |
| Knowledge   | Carbon projections, suitability models          |
| Wisdom      | Strategic planting recommendations              |

---

### 🔷 Multi-Criteria Decision Analysis (MCDA)

Species were evaluated across six weighted criteria:

| Criterion                      | Weight |
| ------------------------------ | ------ |
| Carbon sequestration (Year 50) | 25%    |
| Yield class                    | 20%    |
| Carbon standing rate           | 20%    |
| Planting density               | 15%    |
| Debris carbon                  | 10%    |
| Carbon removed from forest     | 10%    |

➡️ Output: **Top 5 species selection**

---

## 🌲 Selected Species & Insights

| Rank | Species         | Key Strength                                |
| ---- | --------------- | ------------------------------------------- |
| 1    | Sitka Spruce    | Best for peat soils & high carbon retention |
| 2    | Grand Fir       | Highest yield class (YC30)                  |
| 3    | Western Hemlock | Highest carbon accumulation rate            |
| 4    | Douglas Fir     | Strong early-stage growth                   |
| 5    | Beech           | Native species for biodiversity compliance  |

📌 Insight:
No single species satisfies all objectives → **mixed-species strategy is essential**

---

## 📊 DSS Features

* 📈 **Carbon Modelling (5–200 years)**
* 🌍 **Soil–Species Suitability Mapping**
* 💰 **Financial Premium Modelling (15–20 years)**
* 🎛️ **Interactive Scenario Testing**
* 📍 **Policy Target Tracking (8,000 ha/year)**

---

## 📈 Key Performance Indicators (KPIs)

* Cumulative hectares planted vs target
* tCO₂e sequestered per hectare/year
* Total carbon over 200-year horizon
* Tax-free premium income by land type
* Species suitability composite score
* Soil availability by texture

---

## 🗂️ Data Sources

1. **Woodland Carbon Calculator (UK)**

   * 19,040 biomass records
   * Core carbon modelling dataset

2. **Tree Species Database**

   * Species classification and mapping

3. **Irish Soil Information System (GIS)**

   * Soil texture, drainage, and spatial distribution

---

## 🔗 Data Integration

Datasets are linked via **species codes**, enabling:

* Carbon projections by soil type
* Species optimisation per land category
* Financial modelling per planting scenario

---

## 🧪 Decision Support Capabilities

The DSS supports:

| Level       | Example                            |
| ----------- | ---------------------------------- |
| Operational | Premium income calculation         |
| Tactical    | Species–soil optimisation          |
| Strategic   | National forest coverage modelling |

---

## 🖥️ Dashboard Navigation

The system is structured as a **12-point Tableau Story**:

1–2: Problem framing & target tracking
3–5: Species selection & biodiversity
6–8: Carbon modelling & analysis
9–10: Soil suitability mapping
11: Financial modelling
12: Final recommendations

---

## 🎛️ Interactive Features

* **Planting Rate Slider:** Simulate 1,000–20,000 ha/year
* **Premium Calculator:** Adjust €197–€573/ha
* **Soil Filter:** Focus by texture type
* **Species Filter:** Compare performance dynamically

---

## 📈 Key Insights

* ✅ 18% forest cover is achievable
* 🌱 Soil-specific planting improves outcomes
* ⚖️ Trade-offs exist between biodiversity and carbon
* 📊 Data-driven decisions outperform heuristic planning

---

## ⚠️ Limitations

* Static datasets (no real-time updates)
* Simplified economic assumptions
* Limited biodiversity metrics

---

## 🔮 Future Enhancements

* Real-time environmental data integration
* Machine learning for predictive modelling
* GIS-based optimisation
* Policy simulation tools

---

## 🎓 Academic Context

Developed as part of MSc coursework at
University College Dublin

---

## 👤 Author

**Sudarshan Ellora**
MSc Business Analyst
Business Analyst | Data & Strategy Enthusiast

---

## ⭐ Portfolio Value

This project demonstrates:

* End-to-end **Decision Support System design**
* Advanced **data integration & modelling**
* Strong **business + policy understanding**
* Professional **data visualisation in Tableau**

