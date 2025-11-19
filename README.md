# Predictive Modeling of Slope Stability using Machine Learning

**Student:** Daniel Mateu  
**Course:** CEG4012 Geotechnical Engineering — Dr. Song  

---

## 📌 Project Overview

This project builds supervised Machine Learning models to predict **slope stability** (Stable vs. Failure) based on core geotechnical parameters. By analyzing empirical soil data, we aim to identify the most robust algorithms for classifying slope risks in civil engineering contexts.

**Key Input Parameters:**
- Cohesion (*c*, kPa)
- Friction Angle (*φ*, degrees)
- Unit Weight (*γ*, kN/m³)
- Slope Angle (*β*, degrees)
- Slope Height (*H*, m)
- Pore-water Pressure Ratio (*rᵤ*)

> **Engineering Context:** The critical objective is to minimize "False Positives" (predicting a slope is Stable when it is actually prone to Failure), as this represents the highest safety risk.

---

## 📂 Repository Structure

```text
Slope-Stability-Modelling-with-ML/
│
├── data/                           # Contains the raw dataset (Dataset.xlsx)
├── plots/                          # Generated figures (Confusion Matrices, ROC Curves, SHAP plots)
├── reports/                        # Generated PDF analysis reports
├── Slope_Stability_Analysis.ipynb  # Main Jupyter Notebook containing all code and logic
├── requirements.txt                # List of Python dependencies
└── README.md                       # Project documentation