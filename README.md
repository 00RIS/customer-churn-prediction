
# Customer Churn Prediction using Machine Learning

## Project Overview

This project aims to predict customer churn for a telecommunications company using Machine Learning techniques. Customer churn refers to customers who stop using the company's services. By identifying customers who are likely to churn, businesses can take proactive retention measures and reduce revenue loss.

## Dataset

Dataset: Telco Customer Churn Dataset

The dataset contains customer information such as:

* Gender
* Senior Citizen Status
* Tenure
* Monthly Charges
* Total Charges
* Contract Type
* Payment Method
* Internet Service
* Churn Status

Target Variable:

* Churn (Yes/No)

## Project Workflow

### 1. Data Preprocessing

* Loaded and explored the dataset.
* Converted TotalCharges from object type to numeric.
* Handled missing values using dropna().
* Removed customerID as it does not contribute to prediction.
* Encoded categorical variables using One-Hot Encoding.
* Converted the target variable (Churn) into numerical format.

### 2. Exploratory Data Analysis (EDA)

* Analyzed customer churn distribution.
* Examined the impact of gender, tenure, contract type, and monthly charges on churn.
* Used count plots and box plots to identify patterns and trends.

### 3. Model Building

Implemented and compared:

* Logistic Regression
* Random Forest Classifier

### 4. Model Evaluation

Evaluated models using:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1-Score

## Results

### Logistic Regression

* Accuracy: 78.5%
* Recall (Churn Class): 51%
* F1-Score: 56%

### Random Forest

* Accuracy: 78.5%
* Recall (Churn Class): 48%
* F1-Score: 54%

Logistic Regression performed slightly better in identifying churning customers, making it more suitable for this business problem.

## Key Insights

* Customers with lower tenure are more likely to churn.
* Higher monthly charges are associated with increased churn risk.
* Total charges and tenure were among the most important predictive features.
* Contract type significantly influences customer retention.

## Business Recommendations

* Focus retention efforts on new customers during their initial months.
* Introduce onboarding and loyalty programs for customers with low tenure.
* Monitor customers with high monthly charges and offer personalized plans.
* Encourage customers to move from month-to-month contracts to longer-term contracts.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Future Improvements

* Handle class imbalance using SMOTE or class weighting.
* Perform hyperparameter tuning.
* Experiment with XGBoost and Gradient Boosting models.
* Deploy the model using Streamlit or Flask.

## Author

Rishabh Jangra
Business Analytics Student

