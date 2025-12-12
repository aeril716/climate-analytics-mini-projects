# climate-analytics-mini-projects

Mini projects that build practical climate-risk analytics skills using **Python + GIS** (in progress).
Focus: **physical climate signals → analysis → communication-ready figures**.

This repo is structured as a growing set of small, versioned studies.  
Right now, the main completed deliverable is **Heat (v0)**.

---

## Projects

### 1) Heat (v0 complete)
A starter analysis using station temperature data to:
- clean + aggregate to monthly values,
- visualize long-term warming behavior,
- overlay **ENSO phase (ONI-based shading)** to show climate context.

➡️ Details: `heat/README.md`  
📁 Code: `heat/notebooks/`  
🖼️ Figures: `heat/figures/`

**Status:** ✅ v0 done | ⏳ v1 planned

---

## Repo structure

```text
climate-analytics-mini-projects/
  heat/
    notebooks/
    figures/
    README.md
  slr-flood/              # planned
    qgis/
    notebooks/
    figures/
  README.md
  requirements.txt
```

## How to run
Create an environment and install requirements:

```bash
pip install -r requirements.txt
```
Open notebooks inside each project folder (e.g., heat/notebooks/).

## Notes
- Datasets used here are public/open.
- Output figures are saved under each project’s figures/ folder.
- Each project will evolve in versions (v0 → v1 → v2) as the skill stack grows.

## Author
Aeri Lee (San Francisco, CA) — building climate risk analytics projects (Python + GIS)
