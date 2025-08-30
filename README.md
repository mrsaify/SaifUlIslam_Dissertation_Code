# SaifUlIslam_Dissertation_Code

Code bundle for MSc dissertation: **Feature Engineering and Explainable AI for ICS Threat Detection** (University of Gloucestershire, 2025).

## Folder Structure

- `01_Preprocessing/`  
  Data validation, train–test split, and the corrected cleanup/label-fix steps used in the final pipeline.

- `02_Models/`  
  Final notebooks for Random Forest, XGBoost, SVM/LinearSVC, and MLP as reported in Chapter 4.

- `03_Explainability/`  
  SHAP and LIME analyses for Random Forest and XGBoost (global + local explanations).

- `04_Evaluation/`  
  Final evaluation notebooks for RF and XGB (metrics that appear in Chapter 4).

- `05_Outputs/`  
  Small evidence artifacts used in the dissertation (e.g., class distribution figure, RF classification report), and two small model files (`decision_tree_model.pkl`, `xgboost_model.pkl`). Large datasets and large models are intentionally excluded.

## Data & Reproducibility

- Dataset: **CIC-MODBUS2023** (public). This repository does **not** include the dataset files.  
- To run the notebooks, place the dataset locally and adjust any file paths as needed.

> Note: This repository mirrors the exact notebooks that produced the results reported in the dissertation. Exploratory drafts, large CSVs, and oversized models are excluded for clarity and size.
