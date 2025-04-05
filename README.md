# Covid-19-ICU-Prediction

# Covid-19-ICU-Prediction-Analysis

![image](https://github.com/toryschowdhury/Covid-19-ICU-Prediction-Analysis/assets/30194689/f62f97b4-52f8-42f0-a070-6abe449966bb)

# 🧠 COVID-19 ICU Admission Prediction

A machine learning project using real hospital data from Brazil to predict ICU admissions among COVID-19 patients.

## 🧪 Project Overview
- Dataset: Sírio-Libanês Hospital (Kaggle) — 1925 patients, 230+ features
- Goal: Predict which hospitalized patients will be admitted to ICU
- Models Used: Logistic Regression, Decision Tree, Random Forest, SVC, LightGBM
- Tools: Python, pandas, seaborn, scikit-learn, LightGBM, SHAP

## ✅ Key Results
| Model                | Accuracy | Recall | AUC     |
|---------------------|----------|--------|---------|
| **SVC**              | **88.3%** | 62.1%  | **0.88** |
| LightGBM            | 85.5%    | **65.0%**  | 0.85    |
| Logistic Regression | 87.3%    | 55.3%  | 0.86    |

- ✅ SVC had the best overall AUC and accuracy  
- ✅ LightGBM had the best recall — important for ICU triage  
- 🔍 SHAP analysis provided feature-level interpretability  

## 📈 Visuals
- Correlation heatmaps
- Model performance comparison bar plots
- SHAP summary plots for LightGBM

## 🧠 Why This Matters
In high-risk healthcare scenarios, identifying ICU patients early is critical. This project balances performance and interpretability to make real-world impact possible.


