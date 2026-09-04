# Employee Attrition Prediction using Logistic Regression

## 📌 Project Overview

Employee attrition is an important challenge faced by organizations. 
This project uses Machine Learning to predict whether an employee is likely 
to leave the company within the next six months.

A Logistic Regression classification model is developed to predict employee 
attrition risk based on employee-related factors.

## 🎯 Objective

The main objective of this project is to build a binary classification model 
that predicts:

- 0 → Employee is likely to stay
- 1 → Employee is at risk of leaving

## 📊 Dataset

The dataset contains 1,000 employee records with the following variables:

| Feature | Description |
|---|---|
| age | Age of the employee |
| monthly_income | Monthly income |
| years_at_company | Number of years at the company |
| job_satisfaction | Employee job satisfaction level |
| overtime_hours | Number of overtime hours |
| promotion_years | Years since last promotion |
| target | Employee attrition target |

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

## 🔍 Project Workflow

1. Dataset loading
2. Data inspection
3. Missing value checking
4. Duplicate checking
5. Class balance analysis
6. Exploratory Data Analysis
7. Feature and target separation
8. Train-test split
9. Feature scaling
10. Logistic Regression model training
11. Prediction
12. Model evaluation
13. Confusion matrix analysis
14. Feature coefficient interpretation

## 🤖 Machine Learning Algorithm

### Logistic Regression

Logistic Regression is used because this is a binary classification problem.

The model predicts the probability of an employee belonging to the 
attrition-risk class.

## 📈 Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

## 💡 Feature Interpretation

The Logistic Regression coefficients are analyzed to understand how each 
feature influences employee attrition risk.

Positive coefficients indicate an increase in the likelihood of the positive 
class, while negative coefficients indicate a decrease, assuming other 
features remain constant.

## ⚠️ Limitations

- The dataset contains a limited number of employee records.
- The model uses only six predictor variables.
- Employee behavior can be influenced by many factors that are not included.
- Results may not generalize to every organization.
- Additional real-world employee data could improve the model.

## 🚀 Future Improvements

Future versions of this project could include:

- Trying additional classification algorithms
- Hyperparameter tuning
- Cross-validation
- Feature engineering
- Larger real-world datasets
- Model deployment using Streamlit
- Employee attrition risk dashboard
- Explainable AI techniques

## 📁 Repository Contents

```text
employee-attrition-prediction/
│
├── Employee_Attrition_Prediction_Logistic_Regression.ipynb
└── README.md
