# ML-Based Screening of Sustainable Materials (Version 1)

This project applies machine learning to evaluate sustainable material candidates for **CO₂ conversion** and **electrochemical energy storage**.

## Project Overview

I built a full ML pipeline using a curated dataset of 20 material systems with the goal of predicting:

- **Faradaic Efficiency** (CO₂RR)
- **Specific Capacitance** (Energy Storage)
- **Material Cost Performance Index (MCPI)**

## Objectives
- Use ML models (Linear Regression, Random Forest) to predict material performance
- Introduce MCPI as a cost-efficiency metric
- Apply SHAP for model interpretability
- Lay the foundation for a scalable screening framework (Version 2)

## Features Used
- Bandgap Energy
- Electrical Conductivity
- Specific Surface Area
- Stability Score
- Synthesis Complexity
- Raw Material Cost

## Results Summary

| Target | Best Model | R² | RMSE |
|--------|------------|----|------|
| Faradaic Efficiency | RF | ~0.30 | ~11 |
| Specific Capacitance | RF | ~0.48 | ~5.1 |
| MCPI | RF | ~0.48 | ~5.1 |

SHAP interpretation highlighted the most influential material descriptors for each target.

## Limitations
- Small dataset (n=20) not suitable for generalization
- Performance is limited by feature diversity and sample size

## Future Work (Version 2 Goals)
- Use larger dataset (100–500+ materials) from Materials Project, NOMAD, or OpenCatalyst
- Generalize pipeline using modular Python functions
- Apply XGBoost, LightGBM, and hyperparameter tuning
- Build a Streamlit tool for real-time screening
- Publish results as a preprint or research blog post
