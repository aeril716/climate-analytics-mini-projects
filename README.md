# 🌎 Climate Analytics Mini Projects
Small, reproducible climate risk analytics projects in Python focused on physical hazards and their implications for infrastructure and business continuity.

**Projects:** Extreme Heat Frequency • Sea Level Trend & Acceleration  
**Data:** NOAA • NASA/NOAA (public open datasets)  
**Tools:** Python (pandas, numpy, matplotlib)

---

## Why this repo
These notebooks mirror early-stage climate risk workflows: data sourcing → cleaning → threshold/trend analysis → interpretation → stakeholder-ready visuals.

---

## Projects

### 1) Extreme Heat Frequency Analysis (1980–2024)
**Question:** Have high-heat days become more frequent over time?

**Approach**
- Use daily temperature data (NOAA)
- Define an extreme threshold (e.g., 95th percentile)
- Compute annual counts of extreme-heat days
- Compare earlier vs. recent periods + visualize variability/trend

**Outputs**
- Annual extreme-heat day counts (time series)
- Comparison across periods (e.g., 1980–1999 vs. 2000–2024)
- Figures saved to `/figures`

➡️ Notebook: `notebooks/01_extreme_heat.ipynb`

### 2) Sea Level Rise: Trend & Acceleration Check
**Question:** Is sea level rise accelerating in recent decades?

**Approach**
- Load long-term sea level time series (NASA/NOAA)
- Compute annual + rolling averages
- Fit linear trends to early vs. recent periods
- Compare rate differences (mm/year)

**Outputs**
- Long-term sea level trend plot
- Early vs. recent slope comparison
- Figures saved to `/figures`

➡️ Notebook: `notebooks/02_sea_level_trend.ipynb`

---

## Repo structure
```text
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
├── requirements.txt
└── README.md
```

## Reproducibility
Install the minimal Python dependencies used in the notebooks:

```bash
pip install -r requirements.txt
```

## Notes / limitations 
- These are lightweight, transparent analyses intended for rapid iteration and clear communication.
- Assumptions (thresholds, periods, smoothing windows) are documented in each notebook.

## Author
Aeri Lee — San Francisco  
Building climate risk analytics projects with Python + GIS (heat, sea level rise/flooding, wildfire)
