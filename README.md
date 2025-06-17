# 🧠 IBM HR Analytics – Predicting Employee Attrition

This project applies machine learning and feature engineering to predict voluntary employee attrition using IBM's open HR dataset. It demonstrates how data-driven insights can support strategic HR decision-making by identifying key drivers of turnover, quantifying employee risk, and enabling proactive retention strategies.

---

## 📌 Project Highlights

- **Dataset**: IBM HR Employee Attrition dataset (1,470 entries, 35+ features)
- **Goal**: Predict whether an employee will leave the organization
- **Techniques**: Feature engineering, classification models, SHAP analysis
- **Tools**: Python, pandas, scikit-learn, matplotlib, seaborn, SHAP

---

## 📘 Notebook Structure

| Section | Description |
|---------|-------------|
| `Executive Summary` | Condensed strategic insights for leadership decision-making |
| `1B. Data Consistency & Quality Check` | Validation of missing values, outliers, and logical inconsistencies |
| `2. Exploratory Data Analysis (EDA)` | Attrition patterns by department, job role, age, overtime, etc. |
| `3. Feature Engineering` | Creation of over 30 features across career, compensation, engagement, and demographics |
| `4. Data Preprocessing` | Data splitting, encoding, and scaling for machine learning models |
| `5. Model Development` | Training and evaluation of Logistic Regression, Random Forest, and Gradient Boosting models |
| `6. Feature Importance` | Interpretation of model results using SHAP values and business-driven relevance |
| `7. Risk Scoring System` | Framework to categorize employees into low, medium, and high attrition risk tiers |

---

## 📊 Key Results

| Model | ROC-AUC | Accuracy | Precision | Recall | F1 Score |
|-------|---------|----------|-----------|--------|----------|
| Logistic Regression | 0.81 | 84% | 0.65 | 0.60 | 0.62 |
| Random Forest | 0.87 | 87% | 0.72 | 0.70 | 0.71 |
| **Gradient Boosting** | **0.89** | **88%** | **0.75** | **0.72** | **0.73** |

> ✅ *Gradient Boosting is the recommended model for deployment.*

---

## 🔍 Notable Engineered Features

| Feature | Description |
|--------|-------------|
| `IncomePerLevel` | Monthly income normalized by job level |
| `TenureProgression` | Years at company relative to total working years |
| `EngagementScore` | Composite score of satisfaction and involvement |
| `FrequentJobChanges` | Rate of switching jobs across career span |
| `CareerStabilityIndex` | Years with current manager relative to current role duration |

---

## 🎯 Risk Scoring System

A custom scoring algorithm assigns each employee a **risk tier** (Low, Medium, High) based on model outputs and engineered features. This system enables HR to target at-risk employees for retention interventions and performance reviews.

---

## 🛠 Tech Stack

- Python 3.11+
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- SHAP for model interpretability
- Jupyter Notebook

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `IBM Dataset HR Analytics Complete.ipynb` | Full analysis notebook with code, plots, and annotations |
| `HR_Analytics_Final_Featured_Dataset.xlsx` | Dataset with original + engineered features |
| `README.md` | This documentation |
| `*.csv` or `*.xlsx` | Any exported model outputs, feature logs, or results |

---

## 🚀 How to Use

1. Clone the repository
2. Open the notebook in Jupyter or VS Code
3. Run all cells to reproduce the analysis
4. Modify or extend the model with your own hypotheses

---

## 📈 Use Case Relevance

This analysis can be extended or adapted for:

- Retention strategy simulation
- Workforce planning and budget forecasting
- Targeted performance and engagement interventions
- HR dashboard integration

---

## 📣 Acknowledgements

- IBM for the open dataset
- scikit-learn and SHAP contributors
- This project was created by [Your Name] as part of a data science and analytics portfolio.

---

