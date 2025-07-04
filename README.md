# Credit Risk Prediction & Scoring Framework

## 📊 Project Overview  
End-to-end machine-learning pipeline that predicts loan default, converts probabilities to **FICO-style 300-850 scores**, applies the **5 Cs of Credit** rules, and quantifies business impact (≈ \$15.6 M loss prevented).

*Built for banking‐grade deployment & model interpretability.*

---

## 🔧 Tools & Techniques  
| Area | Stack | Highlights |
|------|-------|-----------|
| Data Prep | `pandas`, `scikit-learn` | One-hot encoding, SMOTE balancing |
| Modeling | `XGBoost`, `RandomizedSearchCV` | 0.94 AUC (CV) |
| Scoring | NumPy | PDO log-odds scorecard (300-850) |
| Interpretability | `shap` | Feature importance & waterfall plots |
| Business Rules | Custom Python | 5 Cs assessment, approval tiers |
| Reporting | Markdown, Matplotlib | Executive-ready visuals |

---

## 🧠 Key Steps  

1. **EDA & Data Quality**  
   * Outlier removal, missing-value imputation  
2. **Feature Engineering**  
   * Debt-to-income bands, home-ownership flag  
3. **Model Development**  
   * Hyper-parameter tuning → 93 % AUC (hold-out)  
4. **Credit Scoring**  
   * Log-odds transformation → FICO-equivalent scores  
5. **5 Cs Rule Engine**  
   * Character, Capacity, Capital, Collateral, Conditions  
6. **Business Impact**  
   * 💸 \$15.6 M default losses prevented (TP ≈ 76 %)  
7. **Explainability**  
   * SHAP: housing status & loan grade = top drivers  

---

## ✅ Results  

| Metric | Value |
|--------|-------|
| Hold-out AUC | **0.937** |
| Precision | 0.82 |
| Recall | 0.76 |
| Loss Prevented | \$15.6 M |
| Approval Automation | 85 % of applications |

---

## 📂 Repository Structure  

