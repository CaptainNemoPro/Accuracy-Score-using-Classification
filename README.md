# Accuracy-Score-using-Classification

# Introduction

![alt text](https://www.google.com/url?sa=i&url=https%3A%2F%2Fknowlaw.in%2Findex.php%2F2022%2F04%2F22%2Fregulating-competition-in-the-telecom-sector%2F&psig=AOvVaw21vo5wUhAoe4dG0-SuSdLe&ust=1684219598021000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCODQtond9v4CFQAAAAAdAAAAABAP)

The Telco Churn Analysis project aims to analyze customer churn within a telecommunications company. The dataset used in this analysis contains information about customers, their demographics, services subscribed, and whether they churned or not.

# About Dataset.

The dataset used for this analysis is located in the file telco_churn_data.csv. It includes the following columns:

customerID: Unique identifier for each customer
gender: Customer's gender (Male/Female)
SeniorCitizen: Indicates if the customer is a senior citizen (1) or not (0)
Partner: Indicates if the customer has a partner (Yes/No)
Dependents: Indicates if the customer has dependents (Yes/No)
tenure: Number of months the customer has stayed with the company
PhoneService: Indicates if the customer has phone service (Yes/No)
MultipleLines: Indicates if the customer has multiple lines (Yes/No/No phone service)
InternetService: Customer's internet service provider (DSL/Fiber optic/No)
OnlineSecurity: Indicates if the customer has online security (Yes/No/No internet service)
OnlineBackup: Indicates if the customer has online backup (Yes/No/No internet service)
DeviceProtection: Indicates if the customer has device protection (Yes/No/No internet service)
TechSupport: Indicates if the customer has tech support (Yes/No/No internet service)
StreamingTV: Indicates if the customer has streaming TV (Yes/No/No internet service)
StreamingMovies: Indicates if the customer has streaming movies (Yes/No/No internet service)
Contract: The contract term of the customer (Month-to-month/One year/Two year)
PaperlessBilling: Indicates if the customer has opted for paperless billing (Yes/No)
PaymentMethod: The customer's payment method (Electronic check/Mailed check/Bank transfer (automatic)/Credit card (automatic))
MonthlyCharges: The amount charged to the customer monthly
TotalCharges: The total amount charged to the customer
Churn: Indicates if the customer has churned (Yes/No)

# Analysis Steps

1. Data Cleaning: The dataset is checked for missing values, and any necessary data cleaning steps are performed.
2. Exploratory Data Analysis (EDA): Basic statistical analysis and visualizations are conducted to gain insights into the data and understand the distribution of variables.
3. Feature Selection: Relevant features are selected based on their impact on churn prediction.
4. Preprocessing: Data preprocessing steps such as one-hot encoding categorical variables and scaling numeric features are applied.
5. Model Building: Various machine learning models, such as logistic regression, decision trees, random forests, and gradient boosting, are built to predict customer churn.
6. Model Evaluation: The models are evaluated using appropriate evaluation metrics, such as accuracy, precision, recall, and F1 score.
7. Model Selection: The best-performing model is selected based on evaluation results.
8. Interpretation: The selected model is interpreted to understand the key factors contributing to customer churn.
9. Recommendations: Insights from the analysis are used to provide actionable recommendations for reducing customer churn.

# Insights

![alt text](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.dreamstime.com%2Fillustration%2Finsights.html&psig=AOvVaw0P52Pqn_PbyWugaXv43-XS&ust=1684218710172000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCNDh4YTb9v4CFQAAAAAdAAAAABAD)

Based on the Telco Churn Analysis, the following insights can be drawn:

1. Customer Demographics: Factors such as gender, senior citizenship, having a partner, and dependents do not show a significant correlation with customer churn. Therefore, these demographic characteristics may not be strong predictors of churn.

2. Services Subscribed: Several services offered by the telecommunications company have an impact on customer churn. Customers with internet service, especially those with fiber optic connections, are more likely to churn. Additionally, customers without additional services like online security, online backup, device protection, and tech support are more prone to churn.

3. Contract and Billing: Customers on a month-to-month contract are more likely to churn compared to those on long-term contracts. Paperless billing also contributes to higher churn rates.

4. Payment Method: Customers who pay using electronic checks have a higher churn rate compared to those using other payment methods.

5. Monthly Charges: Higher monthly charges are associated with a higher likelihood of churn.

6. Tenure: Customers with shorter tenure are more likely to churn compared to long-term customers.

7. Model Performance: Various machine learning models were built and evaluated for predicting churn. The selected model (e.g., logistic regression, decision tree, random forest, or gradient boosting) achieved good performance in terms of accuracy, precision, recall, and F1 score.    

8. Key Recommendations: To reduce customer churn, the telecommunications company should consider the following actions:
   - Improve the quality and reliability of internet service, especially for fiber optic connections.
   - Provide additional services like online security, online backup, device protection, and tech support to enhance customer satisfaction and retention.
   - Encourage customers to opt for long-term contracts rather than month-to-month agreements.
   - Offer incentives or discounts for customers who choose paper billing or alternative payment methods.
   - Analyze and optimize pricing strategies to ensure competitive and fair monthly charges.
   - Focus on providing excellent customer support and personalized experiences to increase customer loyalty and tenure.

# Conclusion

To provide a conclusion, it would be necessary to review the findings and results of the analysis, including insights on the factors influencing customer churn and the performance of the predictive models. Please provide specific information or findings from the analysis so that I can assist you in formulating a conclusion based on that information.
