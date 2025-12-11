# 🌎 Climate Analytics Mini Projects  
Light-weight data science projects exploring climate signals using Python.  
Aimed at building practical skills for data analysis, visualization, and early-stage climate risk reasoning.

---

## 📁 Project Overview  
This repository contains small, focused climate analytics exercises using open datasets (NOAA, NASA, CSIRO).  
The goal is to practice:
- Python data wrangling (pandas, numpy)
- Time series processing
- Basic statistical reasoning (percentiles, trends)
- Visualization for scientific storytelling
- Climate-domain framing (hazard → change → implications)

<p style="font-size:14px; font-weight:normal;">
These projects focus on small, well-defined workflows that mirror real climate analytics tasks—data sourcing, cleaning, hazard analysis, and basic visualization—while keeping the scope compact and reproducible.
</p>

---

## 🔥 Projects Included

### 1️⃣ **Extreme Heat Frequency Analysis (1980–2024)**
**Goal:**  
Examine how extreme heat events have changed over time by comparing the frequency of high-percentile temperature days in early vs. recent decades.

**Key steps:**  
- Load NOAA daily temperature data  
- Define a heatwave threshold (e.g., 95th percentile)  
- Compute annual counts of extreme heat days  
- Compare 1980–1999 vs. 2000–2024  
- Visualize year-to-year variability and long-term trends  

**Skills practiced:**  
`pandas`, time series grouping, percentiles, anomaly detection, line plots  

**Climate relevance:**  
Extreme heat is one of the fastest-growing hazards affecting energy demand, health risks, agriculture, and transportation reliability.

➡️ Notebook: `01_extreme_heat.ipynb`

---

### 2️⃣ **Sea Level Rise: Trend & Acceleration Check**
**Goal:**  
Analyze long-term global sea level data to assess the rate of change and whether recent decades show signs of acceleration.

**Key steps:**  
- Load NASA/NOAA sea level dataset  
- Compute annual and rolling averages  
- Fit linear trends to early vs. recent periods  
- Compare slope differences (mm/year)  
- Visualize long-term change  

**Skills practiced:**  
`pandas`, `numpy.polyfit`, rolling means, time-series visualization  

**Climate relevance:**  
Sea level rise influences storm surge risk, tidal flooding, and long-term coastal infrastructure planning.

➡️ Notebook: `02_sea_level_trend.ipynb`

---
## 📁 Repository Structure

```
climate-analytics-mini-projects/
├── data/
│   ├── noaa_temperature.csv
│   └── sea_level.csv
├── notebooks/
│   ├── 01_extreme_heat.ipynb
│   └── 02_sea_level_trend.ipynb
├── figures/
│   ├── heat_trend.png
│   └── sea_level_trend.png
└── README.md
```



## 📌 Why These Projects Matter

These light projects help build foundations used in:

Climate risk screening
Adaptation analytics
ESG / sustainability data roles
Physical hazard analysis (extreme heat, sea level rise)
Time-series based forecasting models
Scientific communication

They mirror early steps of what is done in larger climate assessments:
data → cleaning → threshold/trend → interpretation → implications.

## 🛠️ Environment Setup

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn
```

## ☕️ Notes

These mini-projects are intentionally small and simple — the goal is to build momentum, practice core climate-analytics workflows, and keep things lightweight.
Future additions may include rainfall-extreme analysis, drought indicators, wildfire weather metrics, or energy-demand correlations.

## 👩🏻‍💻 Author

Aeri Lee
Climate analytics learner • Pivoting into data & climate risk
📍 San Francisco, CA
