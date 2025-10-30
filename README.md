📞 **Telecommunication Customer Churn Prediction**

This project focuses on understanding why customers leave a telecom service and building a model that can predict which customers are likely to churn. By identifying these customers early, a company can take steps to retain them and improve customer satisfaction.

---

✅ Project Purpose

The main goal of this project is to:

Explore customer data and understand patterns.

Identify the most important factors that influence churn.

Build a machine learning model that predicts whether a customer will leave.

Use the model to make predictions on new customer data.

This helps telecom companies reduce customer loss and make better business decisions.

---

📁 What the Dataset Contains

The dataset includes information such as:

Call durations during day, evening, and night

Number of international calls

Whether the customer has international or voicemail plans

Charges and usage patterns

Customer service call frequency

Churn status (whether the customer left or stayed)

🔍 What Was Done in the Project
1. Data Understanding

Checked the dataset for missing values, duplicates, and overall structure.

Reviewed numeric and categorical features.

Calculated basic statistics to understand customer behavior.

2. Exploratory Data Analysis (EDA)

Plotted graphs to see how different features behave.

Compared usage patterns between customers who stayed and those who churned.

Analyzed which customer groups had higher churn rates.

3. Finding Important Features

Used different methods to identify which factors strongly influence churn.
Some key factors were:

Customer service call frequency

International usage

Total charges

Day, evening, and night call minutes

Number of international calls

4. Building Predictive Models

Several machine learning models were tested, including:

Logistic Regression

Decision Tree

Random Forest

Gradient Boosting

Support Vector Machine

XGBoost

LightGBM

Each model was evaluated using accuracy, precision, recall, F1 score, and ROC-AUC.

✅ The best-performing model was LightGBM, which gave the most balanced and reliable results.

5. Predicting New Customer Churn

The best model was saved so it can be used for future predictions.

A scaler was also stored to ensure new data is processed correctly.

A script was added to load new customer data and predict churn probability.

---

🎯 Results Summary

Customers with high customer service calls, international usage, and higher charges showed greater chances of churning.

Customers with a voicemail plan had slightly lower churn.

The LightGBM model provided the most accurate churn predictions.

---

🌟 Why This Project Matters

Understanding churn helps companies:

Improve customer retention

Reduce revenue loss

Identify service issues early

Personalize customer support

---

<img width="1652" height="788" alt="image" src="https://github.com/user-attachments/assets/bd0a616c-b81d-41eb-aa6a-796fed5b730f" />
