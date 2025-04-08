# Credit Card Defaultee Prediction

A Machine Learning project to predict whether a customer is likely to default on their credit card payment, using real-world anonymized data and a range of classification models.

---

## Project Highlights

- Built a classification model to predict credit card default.
- Feature selection reduced 122 features to 20 most relevant ones.
- Applied **feature engineering** to enhance predictive power.
- Addressed **class imbalance** using resampling techniques.
- Removed gender-based features to promote ethical AI.
- Achieved **95% accuracy** and **0.95 ROC-AUC** with **XGBoost**.

---

## Problem Statement

Credit card default prediction is a critical task for financial institutions to mitigate risks. This project focuses on building a robust model that can classify users as defaulters or non-defaulters based on historical financial and demographic data.

---

## Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn)
- XGBoost, Random Forest, Logistic Regression
- Matplotlib, Seaborn
- Jupyter Notebook

---

## Feature Engineering

New features created:
- `debt_income_ratio`
- `annuity_income_ratio`
- `external_score_mean`
- `family_load`
- `mobility`

Removed potentially biased or redundant features such as:
- `CODE_GENDER`
- `AMT_INCOME_TOTAL`, `AMT_CREDIT` (after transformation)

---

##  Model Evaluation

- **Train Accuracy**: 95%
- **Validation Accuracy**: 94.8%
- **F1 Score**: 0.95
- **ROC-AUC Score**: 0.95
- **Cross-Validation** ensured model generalization

Evaluation plots include:
- ROC Curve
- Confusion Matrix
- Classification Report

---

## Getting Started

1. Clone the repo  
   ```bash
   git clone https://github.com/yourusername/credit-card-defaultee-prediction.git
   cd credit-card-defaultee-prediction
2. Install dependencies

```bash
   pip install -r requirements.txt
```
3. Run the notebook
Open Credit_Card_Defaultees.ipynb in Jupyter Notebook.

## Tags
`Machine Learning` `Credit Scoring` `Classification` `XGBoost` `Feature Engineering` `Ethical AI`
