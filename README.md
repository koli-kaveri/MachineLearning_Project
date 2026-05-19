<div align="center">

<img src="https://img.shields.io/badge/Machine%20Learning-Decision%20Tree-4CAF50?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Accuracy-76--82%25-orange?style=for-the-badge"/>

<br/><br/>

# 🧠 Employee Attrition Prediction
### *Using Decision Trees & HR Analytics*

> **Helping organizations identify at-risk employees before it's too late — with transparent, explainable AI.**

<br/>

[📓 View Notebook](#-installation--setup) • [📊 Dataset](#-dataset) • [🔍 Results](#-results-summary) • [📬 Contact](#-contact)

---

</div>

## 📌 Overview

Employee attrition silently drains organizations — through lost productivity, expensive rehires, and disrupted team dynamics. This project leverages the **IBM HR Analytics Dataset** to build a transparent, interpretable machine learning pipeline that helps HR teams detect flight-risk employees *before* they walk out the door.

| What's Inside | Details |
|---|---|
| 🌲 Model | Decision Tree Classifier |
| 📊 Analysis | Full EDA with visualizations |
| 💡 Insights | Key attrition drivers for HR teams |
| 📓 Format | Clean, reproducible Jupyter Notebook |
| 🔁 Fallback | Auto-generates synthetic data if CSV is missing |

---

## 🎯 The Business Problem

> *"It costs 6–9 months of an employee's salary to replace them."*

The HR department is facing high employee turnover. Data-driven prediction can:

- 💸 **Reduce** hiring and training expenses
- 😊 **Improve** employee satisfaction and engagement
- 🎯 **Implement** targeted, personalized retention strategies
- ⚠️ **Flag** high-risk employees early — before resignation

This model provides a clear, actionable **attrition risk indicator** for non-technical HR stakeholders.

---

## 🌲 Why Decision Trees?

Decision Trees are the *ideal* algorithm for HR analytics. Here's why:

```
IF Overtime = "Yes"
  AND JobSatisfaction < 2
    AND MonthlyIncome < 4000
      → HIGH ATTRITION RISK ⚠️
```

| Advantage | Why It Matters for HR |
|---|---|
| ✅ Human-readable rules | Non-technical stakeholders can understand decisions |
| ✅ IF–THEN logic | Aligns with HR policy thinking |
| ✅ Handles mixed data types | Works with both numerical & categorical HR fields |
| ✅ Minimal preprocessing | Faster iteration and prototyping |
| ✅ Built-in feature importance | Reveals *what actually drives* attrition |

---

## 📁 Project Structure

```
MachineLearning_Project/
│
├── 📄 README.md
├── 📦 requirements.txt
├── 📓 employee_attrition_decision_tree.ipynb
└── 📂 data/
    └── WA_Fn-UseC_-HR-Employee-Attrition.csv
```

---

## 📊 Visual Insights

The notebook includes **7 carefully designed visualizations** that make the analysis intuitive for HR audiences:

| # | Visualization | Purpose |
|---|---|---|
| 1 | 🥧 Attrition Distribution | Understand class balance (Yes vs No) |
| 2 | 📦 Age vs Attrition Boxplot | Identify age-related patterns |
| 3 | 💰 Income vs Attrition Boxplot | Spot compensation-driven attrition |
| 4 | ⏰ Overtime Impact Analysis | Quantify burnout risk |
| 5 | 😐 Job Satisfaction vs Attrition | Measure engagement drivers |
| 6 | 🔥 Full Correlation Heatmap | Surface hidden feature relationships |
| 7 | 🌲 Decision Tree Diagram | Visual model explanation |

---

## 🛠️ Tech Stack

<div>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3C78D8?style=flat-square&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

</div>

---

## 📦 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/MachineLearning_Project.git
cd MachineLearning_Project
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch the Notebook

```bash
jupyter notebook
```

> 💡 **No dataset?** No problem. The notebook auto-generates a synthetic dataset with the same schema — just run it end-to-end.

---

## 📚 Dataset

**Source:** [IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) — Kaggle

- 1,470 employee records
- 35 features (age, job role, satisfaction scores, income, overtime, etc.)
- Binary target: `Attrition` → Yes / No

> 🔁 If the CSV is unavailable, the notebook seamlessly generates synthetic data matching the same feature schema.

---

## 🧪 Model Configuration

```python
DecisionTreeClassifier(
    criterion   = 'gini',
    max_depth   = 5,
    random_state = 42
)
```

| Metric | Value |
|---|---|
| Cross-validated Accuracy | ~76% – 82% |
| Interpretability | High ✅ |
| Overfitting Risk | Low (depth-limited) |
| Explainability Tools | `export_text()` + tree visualization + feature importance |

---

## 🔍 Key Attrition Drivers

The model consistently surfaces these top predictors:

```
🥇  Overtime          — Single strongest predictor of attrition
🥈  Job Satisfaction  — Low satisfaction = high flight risk
🥉  Monthly Income    — Below-market pay drives turnover
🏅  Age               — Younger employees leave more frequently
🏅  Years at Company  — Early tenure is highest-risk window
```

> These insights directly inform HR intervention strategies — from compensation reviews to workload balancing.

---

## 🏁 What This Project Demonstrates

| Skill | Applied In |
|---|---|
| 📊 Exploratory Data Analysis | Multi-angle visualizations with HR framing |
| ⚙️ Feature Engineering | Encoding, selection, and importance ranking |
| 🤖 Supervised ML | End-to-end classification pipeline |
| 🎨 Visual Storytelling | Charts designed for non-technical stakeholders |
| 💼 Business Communication | Insights framed in HR language, not ML jargon |
| 🔍 Model Interpretability | Rule extraction + tree diagrams for trust-building |

---

## 📬 Contact

Have ideas to extend this project? Want to turn it into a full HR analytics dashboard or a Flask/Streamlit app?

Feel free to open an issue, fork the repo, or reach out directly.

> *"The best models aren't just accurate — they're explainable enough that people actually use them."*

---

<div align="center">

⭐ **Star this repo** if you found it useful — it helps others discover the project!

<br/>

Made with 🧠 + ❤️ for the ML & HR community

</div>
