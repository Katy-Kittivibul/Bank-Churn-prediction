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
All three classification models showed excellent performance, achieving nearly perfect accuracy (0.999) and F1 scores (0.997). Precision and Recall values were both very high (close to 1), indicating that the models are effectively predicting churn without many false positives or false negatives. These results indicate that the models are highly reliable for predicting customer churn with a high degree of confidence.
2. Feature importance
For Logistic regression, complain, age, and account balance were three key features influencing the retention of bank customers, while in Random forest revealed complain, age, and number of product as key features. In XGBoost model, point earned, account balance, and customer estimated salary were indicated as important features. 

---

# Actionable Insights from Model Results
1. Target At-Risk Customers: By predicting which customers are likely to churn, businesses can take proactive steps to intervene before they leave.
2. Understand the Drivers of Churn: The feature importance provides information about key features that can cause customer churn.
3. Customer Support Improvements: Features like customer complaints and satisfaction scores were highlighted, suggesting that improving support services or addressing customer pain points can reduce churn.
4. Product Enhancements: Features like tenure and balance showed that newer customers or those with low balances were more likely to churn, suggesting the need for personalized onboarding and financial product improvements.
5. Behavioral Engagement: Improving engagement for at-risk customers (based on features like low account balance or low usage) can significantly reduce churn.
6. A/B Testing and Intervention Effectiveness: We can implement different intervention strategies and then use A/B testing to evaluate which strategies are most effective in reducing churn.

---



