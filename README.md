#  Loan Default Prediction with SHAP Explainability

Predict loan default risk using a clean, interpretable ML pipeline with SHAP explainability.

##  Overview
- **Goal:** Classify `Loan_Status` (1 = Default, 0 = Non-default)  
- **Data:** Customer demographics, account types, financial metrics  
- **Models:** Logistic Regression, Random Forest, XGBoost 
- **Explainability:** SHAP global & local feature attribution

##  Pipeline
1. **Data Prep:** Encode categorical features, scale numerics, train/test split  
2. **Modeling:** Train Logistic Regression,Random Forest & XGBoost, tune hyperparameters  
3. **Evaluation:** Accuracy, Precision, Recall, ROC AUC, Confusion Matrix  
4. **Explainability:** SHAP summary & force plots for behavioral insights


##  Key Insight
Best Model: XGBoost (Accuracy: 88%, ROC AUC: 0.905)

Key Drivers of Default:
Loan Amount, Interest Rate, Credit History Length, Debt-to-Income Ratio

Business Impact:
Automated risk scoring with interpretability enables targeted intervention for high-risk borrowers, improving collection strategies and potentially reducing default rates.
