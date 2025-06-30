Problem Statement

Employee attrition poses challenges to business continuity and HR planning. This project builds a logistic regression model to predict whether an employee is likely to leave, based on personal, performance, and work-environment features.

📊 Dataset Overview

Rows: 74,610

Columns: 24

Target Variable: Attrition (Yes/No)

🧪 Approach

Data Cleaning: Removed redundant and constant columns

EDA: Visualized feature relationships and target distribution

Feature Engineering: Dummies + StandardScaler

Feature Selection: RFE with Logistic Regression

Model Training: Logistic regression on selected features

Evaluation: Confusion Matrix, ROC, Accuracy, Recall, Precision

🧠 Key Insights

Overtime workers are significantly more likely to leave

Low satisfaction (job/environment) predicts attrition

Younger, lower-income employees have higher attrition

🛠 Tools Used

Python (Pandas, Seaborn, Scikit-learn, Matplotlib)

Jupyter Notebook


✅ Results (Example - Replace with your actual metrics)

Accuracy: 84.2%

Recall: 71.5%

Precision: 68.9%

ROC AUC: 88.1%
