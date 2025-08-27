# 🦗 Regional-Scale Cave Invertebrate Ecology

![R](https://img.shields.io/badge/Language-R-blue?style=flat)
![QGIS](https://img.shields.io/badge/Tools-QGIS-green?style=flat)
![Status](https://img.shields.io/badge/Status-Active-yellow?style=flat)

This folder contains data, scripts, and results from the **regional-scale study** of cave invertebrates.  
The study evaluated **24 caves in the Santana region, Bahia, Brazil**, aiming to understand how **habitat traits** influence **community composition and species richness**, supporting **subterranean conservation efforts**.

---

## 📐 Sampling Design
- **Mesoscale:** 122 transects (10 × 3 m) along cave floors.  
- **Microscale:** 366 quadrats (1 m²) placed in triplicates within transects.  
- **Data collected:** Invertebrate abundance, substrate types, temperature, and humidity.  
- **Collection method:** Visual search; specimens preserved in 70% ethanol and sorted in the lab.  
- **Environmental traits:** Physical, trophic, and microclimatic features recorded.  
- **Spatial info:** Distances measured by laser tape and mapping in QGIS.

---

## 📊 Data Analysis (Summary)
- **Pre-analysis:** Checked correlations, multicollinearity, normality, and spatial autocorrelation.  
- **Community richness:** GLM and GLMM with Poisson family for both scales.    
- **Community composition:** dbRDA at transect and quadrat levels.  
- **Diversity indices:** Shannon-Weaver index for substrate, shelter, and trophic resources.  
- **Tools:** R (`dplyr`, `vegan`, `lme4`, `MuMIn`, `piecewiseSEM`), QGIS.

---

## 🗂 Repository Structure
- `scripts/` – R scripts for data processing and analysis  
- `data/` – raw and processed datasets (as confidentiality allows)  
- `results/` – tables, graphs, and statistical outputs  
- `docs/` – figures, reports, and summaries  

---

## ⚡ Notes
- Scripts are **well-commented** for reproducibility.  
- Repository organized to **support research, documentation, and future projects**.  

