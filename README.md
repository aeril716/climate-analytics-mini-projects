# Climate Analytics Mini Projects

Small climate analytics mini-projects using open datasets (e.g., NOAA).  
Focus: building practical skills in **Python data analysis + visualization**, with a path toward **climate risk metrics**.

## 1) Heat (v0)
**Current focus (v0):** background warming trend + early ENSO overlay experiments.

**What I’ve done so far**
- Computed monthly/annual temperature summaries (baseline warming signal)
- Built initial visualizations and tested ENSO (ONI) shading overlays

**Why this exists**
This is a foundation project that will be expanded into **extreme heat risk metrics** (v1) and later scaled/automated during UIUC coursework (v2).

**Next milestone (v1) — Extreme Heat Frequency**
- Use daily **TMAX**
- Define an extreme threshold (e.g., 95th percentile with a fixed baseline period)
- Compute annual counts of extreme-heat days and compare early vs. recent periods

_Notebooks_
- `notebooks/00_warming_trend.ipynb` (v0)
- `notebooks/01_extreme_heat.ipynb` (planned v1)

## 2) SLR + Flood (in progress)
GIS + data-driven mini project exploring coastal flood/SLR exposure and overlap logic.  
Details will be added after Heat v1 is locked.

## Repo Structure
- `notebooks/` — Jupyter notebooks
- `figures/` — exported plots

## Data
- NOAA daily station data (TMAX/TMIN/TAVG)
- ENSO index (ONI) for overlay experiments (v0)
