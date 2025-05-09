# Chronic Kidney Disease Prediction Using NHANES Data

This repository contains a machine learning project for predicting chronic kidney disease (CKD) using structured clinical data from the National Health and Nutrition Examination Survey (NHANES, 2013–2020). The project explores the use of various supervised learning models and emphasizes interpretability and real-world applicability.

📁 **Repository Structure**

ckd-nhanes-project/
│
├── data/ # Processed dataset (e.g., cleaned CSV)
├── notebooks/ # Jupyter notebooks for preprocessing, modeling, SHAP analysis
├── outputs/ # Model performance plots and SHAP figures
└── report.pdf # Full project report for academic review


🧾 **Dataset**
- Source: NHANES (2013–2020)
- Target label: CKD defined as ACR > 20 mg/g, following early-detection guidelines
- Only blood tests and demographic features were used to simulate limited-resource settings

📊 **Models Implemented**
- Logistic Regression  
- Random Forest  
- XGBoost (selected as primary model for SHAP analysis)  
- Support Vector Machine (RBF kernel)  
- Deep Neural Network (with Focal Loss to handle class imbalance)

📈 **Interpretability**
- SHAP (SHapley Additive exPlanations) was used to explain feature importance in the XGBoost model
- Key predictors include hemoglobin, serum creatinine, and blood urea nitrogen

📄 **Report**
See `report.pdf` for the full methodology, performance comparison, SHAP visualizations, and clinical discussion.

🔍 **Purpose**
This project was developed as part of a data science application portfolio. It aims to demonstrate reproducibility, data cleaning rigor, and practical understanding of machine learning in healthcare applications.




