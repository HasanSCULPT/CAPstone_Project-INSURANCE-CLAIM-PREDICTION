# CAPstone_Project-INSURANCE-CLAIM-PREDICTION
Project Overview

This project develops a machine learning model to predict whether a building will experience at least one insurance claim during its insured period. The solution emphasizes interpretability, reproducibility, and alignment with insurance business objectives.

📂 Repository Structure

HassanYusufAfolabi_CP.ipynb – Main analysis and modeling notebook

final_random_forest_claim_model.pkl – Saved tuned model

claim_decision_threshold.pkl – Business decision threshold

model_feature_columns.pkl – Feature schema for inference

Train_data.csv – Training dataset

⚙️ Methodology Summary

Extensive preprocessing and feature engineering

Random Forest model with hyperparameter tuning

ROC-AUC–driven evaluation

Business-aligned threshold optimization (0.30)

Permutation importance for explainability

📊 Key Results

Tuned Random Forest ROC-AUC ≈ 0.72

Reduced false negatives via optimized threshold

Building size and exposure dominate risk prediction

🔍 Explainability

Permutation feature importance confirms that model decisions align with domain intuition, enhancing trust and deployability.

💾 Reproducibility

All artifacts are saved using joblib. Reload tests confirm consistent predictions.

🚀 Deployment Readiness

The model is ready for integration into underwriting or risk-monitoring pipelines, with periodic retraining recommended. 

Author:
Hassan Yusuf Afolabi
(HasanSCULPT)
