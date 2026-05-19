📌 Employee Attrition Prediction using Decision Tree

A Machine Learning mini-project that predicts whether an employee is likely to leave a company based on workplace and HR-related factors. Built to help organizations identify at-risk employees and improve retention strategies.

⭐ Project Overview

Employee attrition affects productivity, hiring costs, and overall team performance.
This project uses the IBM HR Analytics dataset to build:

A Decision Tree Classification Model
Exploratory Data Analysis (EDA) with clear visualizations
HR-friendly insights on key attrition drivers
A clean, reproducible Jupyter Notebook (with synthetic fallback data)

The goal is to provide a transparent, interpretable model that HR teams can understand and trust.

🎯 Business Problem

The HR department is facing high employee turnover. Predictive insights can help:

Reduce hiring and training expenses
Improve employee satisfaction and engagement
Implement targeted retention strategies
Identify high-risk employees early

This model provides a data-driven attrition risk indicator for better decision-making.

🧠 Why a Decision Tree?

Decision Trees are ideal for HR analytics because they are:

Easy to explain with human-readable rules
Interpretable (IF–THEN logic)
Good with both categorical and numerical data
Minimal preprocessing required
Great for uncovering key feature importance

Perfect for communicating results to non-technical stakeholders.

📁 Project Structure
MachineLearning_Project/
│
├── README.md
├── requirements.txt
├── employee_attrition_decision_tree.ipynb
└── data/
    └── WA_Fn-UseC_-HR-Employee-Attrition.csv
📊 Key Features & Visual Insights

The notebook includes:

Attrition distribution (Yes vs No)
Boxplots: Age vs Attrition, Income vs Attrition
Overtime impact analysis
Job Satisfaction vs Attrition
Full correlation heatmap
Decision Tree diagram + rule extraction

These visuals make the analysis intuitive for HR teams.

🛠️ Technologies Used
Python 3.x
pandas
numpy
matplotlib
seaborn
scikit-learn
📦 Installation & Setup
1. Clone the repository
git clone https://github.com/yourusername/MachineLearning_Project.git
cd MachineLearning_Project
2. Install dependencies
pip install -r requirements.txt
3. Run the notebook
jupyter notebook
📚 Dataset

The project uses the IBM HR Analytics Employee Attrition dataset.

If the dataset is missing, the notebook automatically generates a synthetic dataset with the same schema, ensuring it runs end-to-end without breaking.

🧪 Model Details
Model: DecisionTreeClassifier
Criterion: Gini impurity
Max Depth: 5
Cross-validated Accuracy: ~0.76–0.82 (varies)
Interpretability:
export_text() rules
Decision tree visualization
Feature importance analysis
🔍 Results Summary

The model highlights key drivers of employee attrition, including:

Overtime
Job satisfaction
Monthly income
Age
Years at company

These insights help HR craft strategic retention initiatives.

🏁 Conclusion

This mini-project demonstrates strengths in:

Exploratory data analysis
Feature engineering
Supervised machine learning
Strong visual storytelling
Business-oriented communication
Model interpretability


📬 Contact

If you'd like to improve this project further or expand it into a full portfolio series, feel free to reach out!
