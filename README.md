📌 Customer Churn Prediction — Machine Learning Project

This project focuses on analyzing telecom customer behavior and building machine learning models to predict customer churn.
The goal is to understand patterns in customer characteristics, visualize key trends, and implement predictive models using Python and scikit-learn.

✅ Project Objectives

Explore and clean the telecom customer churn dataset

Perform target-driven data manipulation

Visualize important patterns affecting churn

Build ML models (Regression, Logistic Regression, Decision Tree, Random Forest)

Compare model performance using evaluation metrics

📂 Data Manipulation Performed
✔ Extracted specific columns

Extracted the 5th and 15th columns into separate variables

✔ Filtered customer segments

Created subsets such as:

Senior male customers using Electronic Check

Customers with tenure > 70 months OR MonthlyCharges > $100

Customers having:

Two-year contract

Mailed check

Churn = Yes

✔ Random Sampling

Extracted 333 random customer records

✔ Churn Distribution

Calculated the count of customers who churned vs those who did not

📊 Data Visualizations

Generated multiple visual insights:

🔸 1. Bar Chart — Internet Service Type

Shows distribution of customers across Fiber optic, DSL, and No Internet.

🔸 2. Histogram — Tenure

30 bins

Gives an overview of customer retention duration

🔸 3. Scatter Plot — Tenure vs Monthly Charges

Highlights relationships between customer loyalty and billing amount

🔸 4. Box Plot — Tenure by Contract Type

Shows variation in tenure for Month-to-Month, One-Year, and Two-Year customers

🤖 Machine Learning Models Developed
⭐ 1. Linear Regression

Target: MonthlyCharges

Feature: Tenure

Train-test split: 70–30

Calculated prediction error and RMSE

⭐ 2. Logistic Regression (Binary Classification)
Model A:

Feature: MonthlyCharges

Target: Churn

Train-test split: 65–35

Confusion matrix + accuracy score

Model B:

Features: Tenure + MonthlyCharges

Target: Churn

Train-test split: 80–20

Improved accuracy reported

⭐ 3. Decision Tree Classifier

Feature: Tenure

Target: Churn

Train-test split: 80–20

Achieved accuracy + confusion matrix

⭐ 4. Random Forest Classifier

Features: Tenure, MonthlyCharges

Train-test split: 70–30

Highest accuracy among all models

📝 Key Outcomes

Understood customer segments most likely to churn

Identified feature relationships and billing/tenure impact

Built and compared four ML approaches

Random Forest achieved the best predictive performance

🛠️ Technologies & Libraries

Python

Pandas

NumPy

Matplotlib / Seaborn

scikit-learn

Jupyter Notebook

🚀 How to Run
pip install -r requirements.txt
jupyter notebook

🏁 Final Notes

This project demonstrates the complete workflow of a churn prediction system:

Data extraction

Filtering

Visualization

Model building

Performance evaluation

A full notebook (.ipynb) is included in this repository showing every step and output.
