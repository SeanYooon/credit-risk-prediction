# Credit Risk Prediction & Scoring (Banking-Grade ML Pipeline)

## 📚 Overview

This project is an end-to-end credit risk analytics pipeline built for banking applications.  
It predicts loan default, transforms outputs into FICO-style 300–850 credit scores, applies the 5 Cs of Credit assessment, and quantifies business impact (e.g., \$15.6M loss prevented).  
**Key features:** regulatory-ready interpretability (SHAP), business rule integration, and professional-grade performance reporting.

## 🛠️ Tools & Libraries

- **Python** (pandas, numpy, scikit-learn, XGBoost, imblearn)
- **Visualization:** matplotlib, seaborn, SHAP
- **Notebook:** Jupyter

## 🧩 Process

1. **Exploratory Data Analysis (EDA)**
   - Outlier detection, missing value imputation, feature-target relationships
2. **Feature Engineering**
   - Debt-to-income ratio, home ownership flags, employment length
3. **Model Development**
   - XGBoost with hyperparameter tuning (RandomizedSearchCV)
   - SMOTE for class imbalance
4. **Credit Scoring**
   - Logistic scorecard transformation (PDO=50, base odds=1:9, 300–850 scale)
5. **5 Cs of Credit Assessment**
   - Character, Capacity, Capital, Collateral, Conditions
6. **Interpretability**
   - SHAP feature importance and individual prediction explanations
7. **Performance Reporting**
   - ROC, PR curve, confusion matrix, business impact summary

## 📊 Key Results

- **Hold-out AUC:** 0.937 (exceeds industry standard)
- **Default Detection Rate:** 76.4%
- **Loss Prevented:** \$15.6M (portfolio estimate)
- **Approval Automation:** 85%
- **Top Risk Factors:** Home ownership, loan grade, DTI, income, loan purpose

## 📈 Visualizations

| Performance Dashboard                             | Model Interpretability          |
|-------------------------------------------------------|--------------------------------------------|
|![*ROC, Debt-to-Income by Default, Precision-Recall, Confusion Matrix*](images/credit-dashboard.png)    | ![*Top 5 SHAP feature importances (housing status, loan grade, DTI, etc.)*](images/credit-shap.png) |


## 🏦 Banking & Regulatory Context

- **FICO-Equivalent Scoring:** 300–850 scale, points-to-double-odds (PDO=50)
- **5 Cs of Credit:** Integrated into decision logic
- **Model Interpretability:** SHAP values for global & local explainability
- **Regulatory Alignment:** Basel III, SR 11-7, and Fair Lending (ECOA) principles followed
- **Business Impact:** Quantified loss prevention, approval automation, and risk tiering

---

## 💡 Business Impact Summary

- **Loss Prevention:** \$15.6M in prevented defaults (estimate)
- **Detection Rate:** 76.4% of defaults identified
- **Approval Automation:** 85% of applications processed automatically

---

## 📂 Structure

