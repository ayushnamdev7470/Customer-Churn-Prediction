# 📉 Customer Churn Prediction

> Random Forest classifier to predict telecom customer churn

## 📊 Results
| Metric | Score |
|--------|-------|
| Accuracy | 78% |
| Precision | 61% |
| Recall | 47.8% |
| Test Samples | 1,407 |

## 🔍 Overview
- Dataset: 7,043 telecom customer records with 21 features
- Label encoded 16 categorical variables
- StandardScaler applied to tenure, MonthlyCharges, TotalCharges
- **Top churn drivers:** TotalCharges, MonthlyCharges, Tenure

## 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

## 📁 Files
| File | Description |
|------|-------------|
| `customer_churn.ipynb` | Main notebook — EDA, preprocessing, model training & evaluation |

## 🚀 Next Steps
- SMOTE oversampling to fix class imbalance (73% non-churn vs 27% churn)
- Probability threshold tuning to improve recall
