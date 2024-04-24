
**Customer Churn Prediction Project**

**Overview**
This project focuses on predicting customer churn for Teleco company using machine learning classification models. By analyzing customer behavior and historical data, the objective is to develop models that accurately identify customers at risk of churning, ultimately improving profitability and customer retention.

**Key Points**
*Problem Statement:* The project aims to address customer churn by developing reliable machine learning models.
*Scope:* Comprehensive phases include data preprocessing, feature engineering, model development, evaluation, monitoring mechanisms, documentation, and stakeholder communication.
*Hypothesis:* Investigates the likelihood of customers leaving before three years elapse.
*Analytical Questions:* Explores various factors affecting churn, such as payment method, contract type, monthly charges, presence of a partner, type of internet service, and gender.
*Data Understanding:* Data is retrieved from SQL Server and CSV files, inspected for duplicates and missing values, and concatenated for analysis.
*Exploratory Data Analysis (EDA):* Initial exploration involves examining data information and dataset columns.

**Data Preprocessing:**
- Uniformized data by converting "No internet service" to "No" in relevant columns.
- Handled missing values by imputing with mode for categorical columns.
- Ensured consistency in data types across the dataset.

**Exploratory Data Analysis (EDA):**
- Explored distributions and relationships of features with churn.
- Identified factors like internet service type (especially fiber optic), contract type (month-to-month), and payment method (electronic check) as significant predictors of churn.
- Examined outliers, skewness, and patterns in numerical features.

**Hypothesis Testing:**
- Conducted a t-test to compare tenure between churned and non-churned customers, finding a significant difference.

**Answering Analytical Questions:**
- Investigated the impact of various factors on churn, such as payment method, contract type, monthly charges, partner presence, internet service type, and gender.
- Highlighted insights like the higher churn rates for customers with fiber optic internet, electronic check payments, or month-to-month contracts.
- Found that customers without partners were more likely to churn, while gender did not significantly affect churn rates.

**Model Development and Evaluation**
- Trained various models including Decision Tree, Logistic Regression, KNN, and Random Forest.
- Evaluated models based on accuracy, precision, recall, and F1-score.
- Applied SMOTE to balance the dataset and re-trained models.
- Visualized evaluation using ROC-AUC curves for all pipelines and analyzed feature importance for each model.
- Assessed business impact and determined an acceptable threshold for the Logistic Regression model.

**Recommendations and Further Steps**
- Provided recommendations based on model evaluation and business impact assessment.
- Explored hyper-parameter tuning techniques for further model improvement.
- Tested the model with test data and saved trained models and encoders for future use.
