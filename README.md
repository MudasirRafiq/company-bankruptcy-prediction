# 🏦 Company Bankruptcy Prediction

This project aims to predict whether a company is likely to go bankrupt using ensemble machine learning techniques and extensive exploratory data analysis.

---

## 📌 Objective

To build a robust model that accurately predicts bankruptcy risk using financial indicators, helping institutions make better credit decisions.

---

## 🧾 Dataset Overview

- Financial data of companies with a binary bankruptcy label
- Includes multiple risk indicators such as solvency, liquidity, and profitability metrics
- Imbalanced dataset (minority class: bankrupt companies)

---

## 🛠️ Tools & Libraries

- Python, Jupyter Notebook  
- Pandas, NumPy, Scikit-learn  
- Matplotlib, Seaborn  
- Voting Classifier, Hyperparameter tuning

---

## ⚙️ Project Workflow

1. **EDA**:
   - Visualized distributions, correlations, and outliers  
2. **Feature Selection**:
   - Removed redundant features via correlation analysis  
3. **Preprocessing**:
   - Handled imbalance using undersampling  
4. **Modeling**:
   - Logistic Regression, Random Forest, XGBoost  
   - Combined using Voting Classifier (Ensemble Model)  
5. **Hyperparameter Tuning**:
   - Optimized ensemble model for best performance  
6. **Evaluation**:
   - Accuracy, Precision, Recall, F1-Score, Confusion Matrix

---

## 📈 Results

- Voting classifier achieved higher recall for the bankrupt class
- Ensemble modeling helped reduce bias from single algorithms
- Visualizations made model performance interpretable

---

## 🧠 Learnings

- Importance of ensemble learning in high-stakes predictions  
- Proper feature selection improves both performance and explainability  
- Class imbalance can drastically skew results if not handled

---

## 🗂️ Project Files

- `bankruptcy_prediction.ipynb`: Complete notebook  
- `data.csv`: Dataset used

---

## 👤 Author

Mudasir Rafiq  
[GitHub](https://github.com/MudasirRafiq) | [LinkedIn](https://www.linkedin.com/in/mudasir-rafiq-aa3b72193)
