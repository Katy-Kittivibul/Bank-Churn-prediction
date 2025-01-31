# Bank Churn Prediction Model

This repository contains code and analysis for a Churn Prediction Model designed to predict bank customer churn and identify the key factors influencing it. The project uses machine learning models such as Random Forest, Logistic Regression, and XGBoost to predict customer churn and assess feature importance.

---

# Project Overview
This project aims to predict whether a customer will churn (leave a service or product) based on a set of features. The dataset contains information about customer demographics, account details, and usage patterns. The following steps were carried out in the analysis:
1. Data cleaning
2. Data visualisation
3. Data preprocessing
4. Model predition and evaluation
5. Feature importance calculation

---

# Getting Started
To run this project locally, follow the instructions below:

## Prerequisites
Make sure you have the following libraries installed:
- Python 3.x
- pandas
- numpy
- scikit-learn
- xgboost
- matplotlib
- seaborn
- shap
- plotly

You can install the required dependencies using pip:
```bash
pip install -r requirements.txt
```
## Dataset
Dataset link: https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn/data

---

# Model Implementation
The churn prediction is implemented using the following models:

- Logistic Regression: A simple linear model for binary classification (churn/no churn).
- Random Forest: An ensemble model based on decision trees, providing robust predictions.
- XGBoost: A gradient boosting model that uses decision trees to predict churn with improved accuracy.

This study also perform a Linear Regression model to compare the regression model with classification model. 

---

How to Use
1. Clone the repository:
```bash
git clone https://github.com/yourusername/churn-prediction.git
cd churn-prediction
```
2. Place your dataset in the data directory.
3. Run the Jupyter notebook or Python scripts to train the models and evaluate performance:
```bash
python churn_prediction.py
```
---
# Results
1. Model performance

All three classification models (Logistic Regression, Random Forest, and XGBoost) demonstrated exceptional performance, achieving:
  - Accuracy: 0.999
  - F1 Score: 0.997
  - Precision & Recall: Both close to 1

These results indicate that the models are highly reliable for predicting customer churn with minimal false positives or false negatives.

2. Feature importance

Key features influencing customer retention varied across models:
  - Logistic Regression: Customer complaints, age, and account balance were the top predictors of churn.
  - Random Forest: Complaints, age, and number of products were the most influential factors.
  - XGBoost: Points earned, account balance, and estimated salary played a crucial role in churn predictions. 

This variation suggests that different models capture churn patterns from different perspectives, highlighting the need for a comprehensive approach to retention strategies.

---

# Actionable Insights from Model Results
1. Identify and Retain At-Risk Customers

Proactively engage with customers flagged as high churn risks to improve retention.

2. Understand the Key Churn Drivers

Leverage feature importance insights to address the main reasons customers leave.

3. Enhance Customer Support

Address customer complaints and improve satisfaction scores to reduce churn.

4. Optimize Product Offerings

Customers with low balances or short tenure are at higher risk—personalized onboarding and financial incentives may help.

5. Improve Customer Engagement

Encourage active product usage for customers with low engagement to strengthen retention.

6. Test and Measure Retention Strategies

Implement A/B testing to assess which interventions are most effective in reducing churn.

---
## 📄 License
This project is licensed under the MIT License. Feel free to use it as you wish. ✨


