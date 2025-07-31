# 🏦 Credit Scoring Model - CodeAlpha Internship Project

This project is developed as part of the **CodeAlpha Machine Learning Internship**. The objective is to predict an individual's **creditworthiness** using financial and personal data.

---

## 📌 Objective

Build a machine learning model that classifies individuals as either **"Low Risk"** or **"Likely to Default"** based on financial indicators like income, age, debt ratio, and more.

---

## 🧠 Technologies & Libraries Used

- Python
- Pandas, NumPy
- Scikit-learn (Logistic Regression, Decision Tree, Random Forest)
- Matplotlib & Seaborn
- StandardScaler (for normalization)

---

## 📊 Features Used

- Income  
- Age  
- Debt Ratio  
- Monthly Debt  
- Credit Lines  
- Late Payments  
- Years of Credit History  
- Number of Dependents

---

## 🔍 Algorithms Tested

- ✅ Logistic Regression  
- ✅ Decision Tree  
- ✅ Random Forest

All models were evaluated using:
- Accuracy
- Precision, Recall, F1-score
- ROC-AUC Score
- Confusion Matrix

---

## 🧪 Example Prediction

```python
sample_data = [[50000, 35, 0.3, 800, 5, 1, 10, 2]]
