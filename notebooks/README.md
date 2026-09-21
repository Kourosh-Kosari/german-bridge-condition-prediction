# Bridge ML Portfolio — Notebooks

This folder contains the 22 notebooks that document the complete development workflow of the German Bridge Condition Prediction project.

The notebooks cover data engineering, machine learning, validation, engineering decision support, Plan A, Plan B, final integration, and deployment preparation.

## Project workflow

```text
Data Engineering (01–06)
        ↓
Machine Learning & Decision Engine (07–10)
        ↓
Audit / Reproducibility / Production (11–13)
        ↓
Mapping (14)
        ↓
Plan A (15–17)
        ↓
Plan B (18–21)
        ↓
Final Integration (22)
```

## Notebook index

- **01_BASt_GIS.ipynb** — Data Engineering — 0. DATA SOURCE / INPUT–OUTPUT MANIFEST
- **02_Traffic_Features.ipynb** — Data Engineering — Traffic → Bridge-Level Feature Engineering — FINAL WORKFLOW
- **03_Weather_Features.ipynb** — Data Engineering — DWD Weather → Bridge-Level Feature Engineering — FINAL WORKFLOW
- **04_Integrated_Dataset.ipynb** — Data Engineering — 04 — Integrated Dataset / Final Merge → NEU Dataset Preparation
- **05_Dataset_Imputation.ipynb** — Data Engineering — 05 — Dataset Imputation — `bridge_ml_dataset_neu`
- **06_Load_Final_Bridge_Dataset_to_PostgreSQL.ipynb** — Data Engineering — 06 — Load Final Bridge Dataset into PostgreSQL
- **07_ML_Condition_Model_Validation.ipynb** — Machine Learning & Decision Engine — 07 — ML Condition Model Validation
- **08_Bridge_Type_Decision_Engine_Independent_Validation.ipynb** — Machine Learning & Decision Engine — 08 — Bridge Type Decision Engine — Independent Validation
- **09_ML_Bridge_Type_Selection_Explainability_Robustness.ipynb** — Machine Learning & Decision Engine — 09 — ML Bridge-Type Selection — Explainability & Robustness
- **10_Bridge_Type_Engineering_Decision_Report.ipynb** — Machine Learning & Decision Engine — 10 — FINAL Bridge Type Engineering Decision Report
- **11_Pipeline_Audit_and_Reproducibility.ipynb** — Audit, Reproducibility & Production — 11 — FINAL Pipeline Audit and Reproducibility
- **12_ML_Model_Freeze_and_Packaging.ipynb** — Audit, Reproducibility & Production — 12 — Final ML Model Freeze and Packaging
- **13_End_to_End_Inference_and_Production.ipynb** — Audit, Reproducibility & Production — 13 — Final End-to-End Inference and Production Test
- **14_Bridge_Map_Builder.ipynb** — Mapping — 00 — Bridge Map Builder
- **15_Plan_A_Current_Bridge_Condition.ipynb** — Plan A — 15 — Plan A: Current Condition of Existing Bridges
- **16_Plan_A_Future_Condition.ipynb** — Plan A — 16 — Plan A: Future Condition Forecasting
- **17_Plan_A_Germany_Web_Map.ipynb** — Plan A — 17 — Plan A: Germany Interactive Web Map
- **18_Plan_B_Reference_Library_and_Decision_Engine.ipynb** — Plan B — 18 — Plan B: Reference Library + Decision Engine
- **19_Plan_B_Independent_Validation_and_Decision_Engine.ipynb** — Plan B — 19 — Plan B: Independent Validation + Decision Engine
- **20_Plan_B_User_Scenario_Recommendation_Engine.ipynb** — Plan B — 20 — Plan B: User Scenario / Recommendation Engine
- **21_Plan_B_Final_Interactive_Interface.ipynb** — Plan B — 21 — Plan B Final Interactive Interface
- **22_Final_Project_Integration_and_PreDeployment_Gate.ipynb** — Final Integration — 22 — Final Project Integration & Pre-Deployment Gate

## Portfolio presentation

The repository's root `index.html` and the Plan A / Plan B web applications are the public-facing demo layer.
The notebooks are the technical evidence layer for data engineering, machine learning, validation, reproducibility, and deployment.
