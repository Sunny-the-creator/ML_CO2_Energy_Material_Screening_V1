# ML-Based Multi-Criteria Screening of Sustainable Electrochemical Materials for CO₂ Conversion and Energy Storage

This repository contains machine learning workflows for screening sustainable materials for CO₂ conversion and energy storage.

---

## Version Overview

### V1: Initial Prototype
- Basic ML workflow for predicting `band_gap`
- Small dataset (~30 samples)
- Models: Linear Regression, Random Forest
- Simple evaluation and basic visualization

➡[View V1 Notebook](ML_CO2_Energy_Material_Screening_V1.ipynb)

---

### V2: Research-Grade Update
- Scaled-up to 500+ materials from Materials Project
- Features: volume, density, magnetization, stability ratio, etc.
- Models: Linear Regression, Random Forest, XGBoost
- Interpretation: SHAP, feature importance, visualizations
- Dataset: `clean_materials_dataset_v2.csv`

➡[View V2 Notebook](V2/V2_bandgap_ML_CO2_Energy_Material_Screening_V2.ipynb)

---

## Goals
- Screen materials with potential for CO₂RR and energy storage
- Predict and interpret band gap behavior using ML
- Build reproducible pipelines for academic research

---

## Next Steps
- Extend modeling to other properties: `co2rr_overpotential`, `specific_capacitance`, `MCPI`
- Improve feature engineering and model tuning
- Add UI (Streamlit) or model deployment

---

## Author
Sunny Eke

