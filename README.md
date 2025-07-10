# ML-Based Screening of Sustainable Materials (V1)

This notebook applies machine learning to evaluate sustainable material candidates for CO₂ conversion and energy storage.

## Objectives
- Predict Faradaic Efficiency, Specific Capacitance, and Material Cost Performance Index (MCPI)
- Interpret predictions using SHAP
- Compare baseline models (Linear Regression, Random Forest)

## Dataset
- Manually compiled sample dataset of 20 materials
- Features: bandgap, conductivity, surface area, stability, synthesis complexity, material cost

## Results
- RF outperformed LR for FE and MCPI predictions
- SHAP helped interpret the drivers of performance
- Small data = overfitting risks; performance is not generalized

## Future Work
- Expand dataset (≥100 materials)
- Add XGBoost, LightGBM, and hyperparameter tuning
- Track experiments using MLflow
- Build Streamlit UI
