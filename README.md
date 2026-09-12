# Environmental Data Science – Remote Sensing & Water Resources Portfolio

This repository documents my structured, long-term journey in environmental data science, with a focus on **hydrology, remote sensing, and machine/deep learning for water resources management**.

The work follows a **100-project roadmap**, organized into 10 progressive phases — from Google Earth Engine fundamentals to deep learning and geospatial foundation models (Prithvi, SatMAE). I move through it at my own pace, prioritizing depth and reproducibility over speed.

**Progress: 2 / 100 projects completed**

---

## 🎯 Goals of This Repository

- Build a structured, phase-by-phase portfolio in environmental data science
- Strengthen skills in Google Earth Engine, Python, and remote sensing
- Apply machine learning and deep learning to real environmental datasets, with a focus on water resources
- Create clear, reproducible, and well-documented projects
- Develop a public professional presence through consistent GitHub activity

---

## 📁 Repository Structure

```
phase-01-gee-fundamentals/
├── project-01-setup/
├── project-02-image-collections/
└── .../

phase-02-precipitation-et/
├── project-11-chirps-precipitation/
├── project-12-gpm-vs-station/
└── .../

.../

```


Each project folder contains:

- `code/` → main scripts (`code.js` for GEE Code Editor, `code.py` for Python)
- `data/` → small sample data and AOI/boundary files only (see note below — no large raw imagery)
- `outputs/` → exported maps, figures, tables, or results
- `README.md` → project documentation (objective, tools, steps, results)
- `notes.md` → observations and workflow notes

> **Note on `data/`:** Satellite imagery is pulled directly from Google Earth Engine's API within each script — it is not stored in this repository. The `data/` folder only holds lightweight files such as study-area boundaries (GeoJSON/shapefile) or small reference tables, to keep the repository size manageable.

---

## 🗺️ Roadmap & Progress

> ✅ = completed &nbsp;|&nbsp; ⬜ = not started yet. Each title links directly to its project folder.

### Phase 01 — Google Earth Engine Fundamentals (1–10)
- ✅ [01. GEE Environment Setup](phase-01-gee-fundamentals/project-01-setup)
- ⬜ [02. Working with Image & ImageCollection](phase-01-gee-fundamentals/project-02-image-collections)
- ⬜ [03. Cloud-free Composites](phase-01-gee-fundamentals/project-03-composites)
- ⬜ [04. Basic Spectral Indices (NDVI/NDWI/NDBI)](phase-01-gee-fundamentals/project-04-spectral-indices)
- ⬜ [05. Reducers & Zonal Statistics](phase-01-gee-fundamentals/project-05-zonal-statistics)
- ⬜ [06. Exporting Data from GEE](phase-01-gee-fundamentals/project-06-export-data)
- ⬜ [07. Automation with the Python API](phase-01-gee-fundamentals/project-07-python-automation)
- ⬜ [08. Simple Interactive Dashboard](phase-01-gee-fundamentals/project-08-interactive-dashboard)
- ⬜ [09. Watershed Feature Collections](phase-01-gee-fundamentals/project-09-watershed-boundaries)
- ⬜ [10. Capstone: Basic Basin Monitoring Dashboard](phase-01-gee-fundamentals/project-10-phase1-capstone)

### Phase 02 — Precipitation, Temperature & Evapotranspiration (11–20)
- ⬜ [11. CHIRPS Mean Precipitation](phase-02-precipitation-et/project-11-chirps-precipitation)
- ⬜ [12. GPM IMERG vs. Station Data](phase-02-precipitation-et/project-12-gpm-vs-station)
- ⬜ [13. Land Surface Temperature (LST) Mapping](phase-02-precipitation-et/project-13-lst-mapping)
- ⬜ [14. Actual Evapotranspiration with MOD16](phase-02-precipitation-et/project-14-mod16-et)
- ⬜ [15. ET Estimation with SSEBop](phase-02-precipitation-et/project-15-ssebop-et)
- ⬜ [16. Long-term Precipitation Trend (Mann-Kendall)](phase-02-precipitation-et/project-16-precipitation-trend)
- ⬜ [17. Annual Precipitation Climate Atlas](phase-02-precipitation-et/project-17-precipitation-atlas)
- ⬜ [18. Reservoir Evaporation Estimation](phase-02-precipitation-et/project-18-reservoir-evaporation)
- ⬜ [19. Simple Basin Water Balance Model](phase-02-precipitation-et/project-19-water-balance)
- ⬜ [20. Capstone: Basin Climate-Hydrology Atlas](phase-02-precipitation-et/project-20-phase2-capstone)

### Phase 03 — Surface Water, Lakes & Flood Mapping (21–30)
- ⬜ [21. Surface Water Detection (NDWI/MNDWI)](phase-03-surface-water-flood/project-21-surface-water-detection)
- ⬜ [22. Lake/Wetland Area Time Series](phase-03-surface-water-flood/project-22-lake-area-timeseries)
- ⬜ [23. JRC Global Surface Water Analysis](phase-03-surface-water-flood/project-23-jrc-surface-water)
- ⬜ [24. Flood Mapping with Sentinel-1 SAR](phase-03-surface-water-flood/project-24-flood-mapping-sar)
- ⬜ [25. Automated Before/After Flood Detection](phase-03-surface-water-flood/project-25-automated-flood-detection)
- ⬜ [26. Reservoir Volume Estimation](phase-03-surface-water-flood/project-26-reservoir-volume)
- ⬜ [27. Wetland Desiccation Monitoring](phase-03-surface-water-flood/project-27-wetland-desiccation)
- ⬜ [28. River Bank Change Detection](phase-03-surface-water-flood/project-28-riverbank-change)
- ⬜ [29. Early Flood Warning System](phase-03-surface-water-flood/project-29-flood-warning-system)
- ⬜ [30. Capstone: Full Reservoir Monitoring](phase-03-surface-water-flood/project-30-phase3-capstone)

### Phase 04 — Snow Cover & Snowmelt Runoff (31–40)
- ⬜ [31. Snow Cover Mapping (MODIS)](phase-04-snow-runoff/project-31-snow-cover-modis)
- ⬜ [32. High-Resolution Snow Cover (Sentinel-2)](phase-04-snow-runoff/project-32-snow-cover-sentinel2)
- ⬜ [33. Seasonal Snowmelt Trend](phase-04-snow-runoff/project-33-snowmelt-trend)
- ⬜ [34. Approximate SWE Estimation](phase-04-snow-runoff/project-34-swe-estimation)
- ⬜ [35. Snow Cover vs. Streamflow Correlation](phase-04-snow-runoff/project-35-snow-streamflow-correlation)
- ⬜ [36. Glacier Monitoring](phase-04-snow-runoff/project-36-glacier-monitoring)
- ⬜ [37. NDSI & Snowline Elevation](phase-04-snow-runoff/project-37-snowline-elevation)
- ⬜ [38. Simple Temperature-Index Runoff Model](phase-04-snow-runoff/project-38-temperature-index-model)
- ⬜ [39. Cross-Basin Snow Comparison](phase-04-snow-runoff/project-39-cross-basin-snow)
- ⬜ [40. Capstone: Snow Monitoring & Spring Runoff Forecast](phase-04-snow-runoff/project-40-phase4-capstone)

### Phase 05 — Multi-Index Drought Monitoring (41–50)
- ⬜ [41. Standardized Precipitation Index (SPI)](phase-05-drought-indices/project-41-spi)
- ⬜ [42. Vegetation Condition Index (VCI)](phase-05-drought-indices/project-42-vci)
- ⬜ [43. Temperature Condition Index (TCI)](phase-05-drought-indices/project-43-tci)
- ⬜ [44. Vegetation Health Index (VHI)](phase-05-drought-indices/project-44-vhi)
- ⬜ [45. Simple SPEI-like Combined Index](phase-05-drought-indices/project-45-spei-like-index)
- ⬜ [46. Agricultural Drought via NDVI Anomaly](phase-05-drought-indices/project-46-ndvi-anomaly-drought)
- ⬜ [47. Spatiotemporal Drought Severity Analysis](phase-05-drought-indices/project-47-drought-severity-analysis)
- ⬜ [48. Near-Real-Time Drought Dashboard](phase-05-drought-indices/project-48-drought-dashboard)
- ⬜ [49. Drought Effect on Reservoir/Lake Levels](phase-05-drought-indices/project-49-drought-reservoir-effect)
- ⬜ [50. Capstone: Multi-Index Drought Early Warning System](phase-05-drought-indices/project-50-phase5-capstone)

### Phase 06 — Groundwater & GRACE (51–60)
- ⬜ [51. Intro to GRACE / GRACE-FO](phase-06-groundwater-grace/project-51-grace-intro)
- ⬜ [52. GRACE Time Series Processing](phase-06-groundwater-grace/project-52-grace-timeseries)
- ⬜ [53. Groundwater Storage from TWS](phase-06-groundwater-grace/project-53-groundwater-storage)
- ⬜ [54. GRACE vs. Piezometric Data](phase-06-groundwater-grace/project-54-grace-vs-piezometer)
- ⬜ [55. Agricultural Expansion vs. Groundwater Depletion](phase-06-groundwater-grace/project-55-agriculture-groundwater)
- ⬜ [56. GRACE Downscaling](phase-06-groundwater-grace/project-56-grace-downscaling)
- ⬜ [57. Critical Groundwater Depletion Mapping](phase-06-groundwater-grace/project-57-groundwater-critical-zones)
- ⬜ [58. Consecutive Droughts' Effect on Groundwater Storage](phase-06-groundwater-grace/project-58-drought-gws-effect)
- ⬜ [59. TWS Regression Forecasting Model](phase-06-groundwater-grace/project-59-tws-forecast-model)
- ⬜ [60. Capstone: Aquifer Status Report](phase-06-groundwater-grace/project-60-phase6-capstone)

### Phase 07 — Water Quality (61–70)
- ⬜ [61. Chlorophyll-a Estimation](phase-07-water-quality/project-61-chlorophyll-estimation)
- ⬜ [62. Water Turbidity Monitoring](phase-07-water-quality/project-62-turbidity-monitoring)
- ⬜ [63. Water Surface Temperature](phase-07-water-quality/project-63-water-surface-temperature)
- ⬜ [64. Algal Bloom Detection](phase-07-water-quality/project-64-algal-bloom-detection)
- ⬜ [65. Reservoir Sedimentation Monitoring](phase-07-water-quality/project-65-sedimentation-monitoring)
- ⬜ [66. Water Quality Downstream of Industrial/Agricultural Areas](phase-07-water-quality/project-66-downstream-water-quality)
- ⬜ [67. Regression Model with Field Water Quality Data](phase-07-water-quality/project-67-water-quality-regression)
- ⬜ [68. Water Quality Before/After Dam Construction](phase-07-water-quality/project-68-dam-water-quality-effect)
- ⬜ [69. Combined Thermal-Spectral Ecosystem Health Index](phase-07-water-quality/project-69-ecosystem-health-index)
- ⬜ [70. Capstone: Reservoir Water Quality Monitoring System](phase-07-water-quality/project-70-phase7-capstone)

### Phase 08 — Land Use/Cover & Classical Machine Learning (71–80)
- ⬜ [71. Land Use Classification with Random Forest](phase-08-landuse-ml/project-71-landuse-random-forest)
- ⬜ [72. Land Use Classification with SVM](phase-08-landuse-ml/project-72-landuse-svm)
- ⬜ [73. Classification Accuracy Assessment](phase-08-landuse-ml/project-73-accuracy-assessment)
- ⬜ [74. Land Use Change Detection](phase-08-landuse-ml/project-74-landuse-change-detection)
- ⬜ [75. Agricultural Expansion vs. Water Consumption](phase-08-landuse-ml/project-75-agriculture-water-consumption)
- ⬜ [76. Crop Classification via NDVI Time Series](phase-08-landuse-ml/project-76-crop-classification)
- ⬜ [77. Cropland Area Estimation](phase-08-landuse-ml/project-77-cropland-area-estimation)
- ⬜ [78. Agricultural Expansion vs. Groundwater Trend](phase-08-landuse-ml/project-78-agriculture-groundwater-trend)
- ⬜ [79. Upstream Forest/Rangeland Change](phase-08-landuse-ml/project-79-upstream-landcover-change)
- ⬜ [80. Capstone: 20-Year Land Use & Water Impact Map](phase-08-landuse-ml/project-80-phase8-capstone)

### Phase 09 — Deep Learning for Remote Sensing (81–90)
- ⬜ [81. Preparing GEE Data for Deep Learning](phase-09-deep-learning/project-81-dl-data-preparation)
- ⬜ [82. Simple CNN for Patch Classification](phase-09-deep-learning/project-82-cnn-patch-classification)
- ⬜ [83. Surface Water Segmentation with U-Net](phase-09-deep-learning/project-83-unet-water-segmentation)
- ⬜ [84. Flood Segmentation with U-Net (SAR)](phase-09-deep-learning/project-84-unet-flood-segmentation)
- ⬜ [85. Water Level Forecasting with LSTM](phase-09-deep-learning/project-85-lstm-water-level)
- ⬜ [86. Streamflow Prediction with Neural Networks](phase-09-deep-learning/project-86-streamflow-prediction-nn)
- ⬜ [87. Satellite Image Super-Resolution](phase-09-deep-learning/project-87-super-resolution)
- ⬜ [88. Change Detection with Siamese Networks](phase-09-deep-learning/project-88-siamese-change-detection)
- ⬜ [89. Crop Classification with LSTM/Transformer](phase-09-deep-learning/project-89-crop-classification-dl)
- ⬜ [90. Capstone: End-to-End Hydrological Drought Prediction Model](phase-09-deep-learning/project-90-phase9-capstone)

### Phase 10 — Foundation Models & Final Capstone (91–100)
- ⬜ [91. Intro to Geospatial Foundation Models](phase-10-foundation-models-capstone/project-91-foundation-models-intro)
- ⬜ [92. Working with Prithvi](phase-10-foundation-models-capstone/project-92-prithvi-exploration)
- ⬜ [93. Fine-tuning Prithvi for Water/Flood Classification](phase-10-foundation-models-capstone/project-93-prithvi-finetuning)
- ⬜ [94. Working with SatMAE](phase-10-foundation-models-capstone/project-94-satmae-exploration)
- ⬜ [95. Foundation Model vs. Custom CNN Comparison](phase-10-foundation-models-capstone/project-95-foundation-vs-cnn)
- ⬜ [96. Hydrological Region Clustering via Embeddings](phase-10-foundation-models-capstone/project-96-embedding-clustering)
- ⬜ [97. Fine-tuning for Agricultural Water Stress Prediction](phase-10-foundation-models-capstone/project-97-water-stress-finetuning)
- ⬜ [98. End-to-End Pipeline: GEE → Foundation Model → Analysis](phase-10-foundation-models-capstone/project-98-e2e-pipeline)
- ⬜ [99. Scientific Write-up of a Phase 10 Project](phase-10-foundation-models-capstone/project-99-scientific-writeup)
- ⬜ [100. Final Capstone: Intelligent Water Resources Monitoring System](phase-10-foundation-models-capstone/project-100-final-capstone)

---

## 🛠 Tools & Technologies

### Remote Sensing & Cloud Platforms
- Google Earth Engine (JavaScript & Python APIs)

### Python Ecosystem
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Xarray
- TensorFlow / PyTorch (from Phase 09 onward)

### Datasets
- CHIRPS, GPM IMERG
- MODIS
- Landsat
- Sentinel-1 & Sentinel-2
- GRACE / GRACE-FO

### Version Control
- Git & GitHub for documentation and reproducibility

---

## ▶️ How to Use This Repository

Each project is self-contained. To explore a project:

1. Open the project folder (e.g., `phase-02-precipitation-et/project-11-chirps-precipitation/`)
2. Read the `README.md` for objective, tools, and workflow
3. Check the `code/` folder for scripts
4. Explore the `outputs/` directory for maps, figures, and tables
5. Review `notes.md` for insights and learning steps

---

## 📌 About This Journey

This repository is part of a long-term plan to build a strong, visible portfolio in environmental data science, with an emphasis on remote sensing applications for water resources management. Each project is designed to be:

- Practical
- Reproducible
- Professionally documented
- Useful for future research, collaboration, or job applications

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE).

---

## 📬 Contact

If you're interested in collaboration or research discussions, feel free to reach out:

**Email:** sajjad.moghalanloo@gmail.com
