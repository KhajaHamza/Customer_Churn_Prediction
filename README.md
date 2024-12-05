# Customer Churn Prediction Project

## Project Overview

This project focuses on predicting customer churn for a bank using machine learning techniques. Customer churn, or customer attrition, is a critical business challenge where customers stop doing business with a company. By accurately predicting potential churners, businesses can take proactive measures to retain valuable customers.

## Dataset

The dataset used in this project is sourced from Kaggle: [Churn for Bank Customers](https://www.kaggle.com/datasets/mathchi/churn-for-bank-customers)

### Key Features
- Customer demographics
- Credit score
- Account balance
- Number of products
- Age
- Tenure
- Balance
- Geography
- Gender
- Other relevant banking-related attributes

## Data Visualization

Several visualizations were created to understand the data:

1. **Credit Score vs Age Scatter Plot**: 
   - Explores the relationship between credit score and age
   - Colored by churn status to identify potential patterns

2. **Balance Distribution by Churn**:
   - Boxplot showing balance distribution for churned and non-churned customers
   - Helps understand if account balance influences churn

3. **Credit Score Distribution by Churn**:
   - Boxplot comparing credit score distributions
   - Investigates whether credit score is a significant factor in customer churn

## Preprocessing

- Data preprocessing steps included:
  - Splitting the data into training and testing sets
  - Applying StandardScaler for feature scaling
  - Ensuring consistent random state for reproducibility

## Machine Learning Models

The following machine learning models were trained and evaluated:

1. **Logistic Regression**
2. **XGBoost Classifier**
3. **Decision Tree Classifier**
4. **Random Forest Classifier**
5. **Naive Bayes**
6. **K-Nearest Neighbors**
7. **Support Vector Machine**

### Model Evaluation Metrics
- Accuracy score
- Classification report (Precision, Recall, F1-Score)
- Confusion Matrix

## Model Saving

All trained models were saved using Python's `pickle` module for future use and deployment.

## Requirements

- Python 3.x
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - xgboost
  - seaborn
  - matplotlib
  - pickle

## Usage

1. Clone the repository
2. Install required dependencies
3. Run the Jupyter notebook or Python script
4. Explore model performances and predictions

## Future Improvements
- Hyperparameter tuning
- Ensemble methods
- Feature engineering
- Handling class imbalance
- Collecting more recent data

## Conclusion

This project demonstrates a comprehensive approach to customer churn prediction, leveraging multiple machine learning algorithms to understand and predict customer behavior.
