
---

## ✅ 2) `/heat/README.md`
```md
# Heat project (v0)

## What this is
This is a **v0 baseline** for heat-related climate analytics:
- build a clean workflow (load → clean → aggregate),
- produce communication-ready plots,
- add climate context using **ENSO (ONI-based phase shading)**.

This v0 is intentionally simple: it’s meant to be a stable foundation to expand later into extreme-heat metrics and risk framing.

---

## v0 scope (completed)

### Inputs
- Daily station temperature data (aggregated to monthly means)
- ONI / Niño3-style monthly ENSO indicator (used to derive El Niño / La Niña / Neutral)

### What v0 does
1) **Data cleaning**
   - parse dates safely
   - coerce numeric fields
   - handle missing/sentinel values
   - sort + align monthly time index

2) **Warming signal exploration**
   - visualize annual / monthly temperature behavior
   - show long-run trend context (not a formal attribution study)

3) **ENSO overlay (ONI-based shading)**
   - label months as El Niño / La Niña / Neutral using thresholds + persistence logic
   - shade time periods on top of the temperature series for context

---

## Outputs (v0)

### Notebooks
- `notebooks/01_data_cleaning_v0.ipynb`
- `notebooks/02_warming_trend_v0.ipynb`

### Figures
Saved in `figures/`:
- `01_annual_warming_trend_SFO...png`
- `02_monthly_TAVG_ENSO_v0.png`
- `03_TAVG_anoma_12mthrolling_ENSO_v0.png`

---

## Why this matters (even though it’s “not extreme heat yet”)
Warming-trend + ENSO-context plots are useful because they:
- prove the pipeline works end-to-end,
- create a clean base dataset for later metrics,
- make it easier to extend into **extreme heat frequency / thresholds / return periods** later.

This v0 is the “plumbing + baseline visuals” stage.

---

## Next (planned, not implemented in v0)
v1 will move from “warming context” → “extreme heat risk signal”:
- define an extreme threshold (e.g., 95th percentile of daily Tmax)
- compute **annual counts** of extreme-heat days
- compare periods (e.g., 1980–1999 vs 2000–2024)
- optional: link to simple asset context (GIS exposure layer) once the pipeline is stable
