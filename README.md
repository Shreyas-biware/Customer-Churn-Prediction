# Customer Churn Prediction using Machine Learning

## Project Overview

Customer churn is one of the biggest challenges faced by businesses. This project aims to predict whether a customer is likely to leave a bank based on demographic information, account details, and customer behavior.

Using Machine Learning techniques, the model analyzes historical customer data and identifies patterns associated with customer attrition.

---

## Problem Statement

Develop a predictive model to identify customers who are likely to churn so that businesses can take proactive measures to improve customer retention.

Target Variable:

* **Exited = 1** → Customer Churned
* **Exited = 0** → Customer Retained

---

## Dataset Information

The dataset contains information about 10,000 bank customers, including:

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Balance
* Number of Products
* Credit Card Status
* Active Membership Status
* Estimated Salary

Dataset Shape:

* Rows: 10,000
* Columns: 14

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Machine Learning Workflow

### 1. Data Preprocessing

* Removed unnecessary columns

  * RowNumber
  * CustomerId
  * Surname
* Handled categorical variables using:

  * Label Encoding
  * One-Hot Encoding
* Feature Scaling using StandardScaler

### 2. Exploratory Data Analysis (EDA)

Performed visual analysis using:

* Customer Churn Distribution
* Geography vs Churn
* Gender vs Churn
* Age Distribution
* Correlation Analysis
* Feature Importance Analysis

### 3. Model Building

Implemented and compared:

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier

### 4. Model Evaluation

Evaluation Metrics:

* Accuracy Score
* Confusion Matrix
* Classification Report

---

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | ~81%     |
| Random Forest       | ~86%     |
| Gradient Boosting   | ~87%     |

Gradient Boosting achieved the highest performance among the tested models.

---

## Key Insights

* Older customers are more likely to churn.
* Active members are less likely to leave the bank.
* Customers with higher balances show a greater tendency to churn.
* Geography plays an important role in customer retention.
* Age, Balance, and Activity Status are among the most influential features.

---

## Project Structure

Customer-Churn-Prediction/

├── Churn_Modelling.csv

├── Customer_Churn_Prediction.ipynb

├── README.md

├── requirements.txt

└── images/

```
├── churn_distribution.png

├── geography_churn.png

├── age_distribution.png

├── confusion_matrix.png

├── feature_importance.png
```

---

## Future Improvements

* Hyperparameter Tuning
* XGBoost Implementation
* Deployment using Streamlit
* Real-Time Prediction API
* Customer Retention Recommendation System

---

## Author

Shreyas Biware

Aspiring Software Developer | Machine Learning Enthusiast

This project was developed to understand customer behavior patterns and apply machine learning techniques to solve real-world business problems.
