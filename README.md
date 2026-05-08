# 🌳 Employee Attrition Prediction using Decision Tree

Mini Project for MSc Data Science  
Subject: Machine Learning

---

## 📌 Project Overview

This project uses the **Decision Tree Algorithm** to predict whether an employee is likely to leave the company based on HR analytics data.

The model is trained using the IBM HR Analytics Employee Attrition dataset from Kaggle.

---

## 🎯 Objective

To help HR departments identify employees at high risk of attrition so that proactive retention strategies can be applied.

---

## 🏢 Business Problem

Companies often lose talented employees due to factors like:

- Low job satisfaction
- Excessive overtime
- Poor work-life balance
- Low salary
- Limited growth opportunities

This project predicts employee attrition using Machine Learning.

---

## 📂 Dataset

Dataset: IBM HR Analytics Employee Attrition & Performance

Source: Kaggle

https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

Dataset Size:
- 1470 rows
- 35 columns

Target Variable:
- Attrition (Yes/No)

---

## 🧠 Why Decision Tree?

Decision Trees were selected because they:

✅ Are easy to interpret  
✅ Work with categorical and numerical data  
✅ Require no feature scaling  
✅ Produce human-readable IF-THEN rules  
✅ Are suitable for HR analytics

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## ⚙️ Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Exploratory Data Analysis (EDA)
4. Data Preprocessing
5. Label Encoding
6. Train-Test Split
7. Build Decision Tree Model
8. Model Evaluation
9. Feature Importance Analysis
10. Decision Tree Visualization
11. Hyperparameter Tuning
12. Real-world Prediction

---

## 📊 Model Performance

| Metric | Value |
|---|---|
| Training Accuracy | ~88% |
| Test Accuracy | ~84% |
| Cross Validation Accuracy | ~84% ± 2% |
| Algorithm | CART Decision Tree |
| Criterion | Gini Impurity |
| Tree Depth | 5 |

---

## 🔑 Key Insights

Top factors affecting employee attrition:

- OverTime
- TotalWorkingYears
- MonthlyIncome
- Age
- JobSatisfaction

Employees with:
- high overtime,
- low satisfaction,
- lower income,
- and fewer years at company

are more likely to leave.

---

## 📷 Visualizations

### Attrition Distribution
![Attrition](images/plot_attrition_distribution.png)

### Feature Importance
![Feature Importance](images/plot_feature_importance.png)

### Decision Tree Visualization
![Decision Tree](images/plot_decision_tree.png)

---

## 🚀 Future Improvements

- Random Forest
- XGBoost
- SMOTE for class imbalance
- Streamlit/Flask deployment
- SHAP Explainability

---

## ▶️ How to Run

### 1 Clone Repository

```bash
git clone https://github.com/your-username/employee-attrition-decision-tree.git
