# Customer-Churn-Prediction-with-Resampling-Techniques
Customer Churn Prediction with Resampling Techniques


## 1. Introduction

Customer churn is when customers stop using a service, and it's a big problem for companies like telecom providers. Predicting churn can help companies take action to keep customers. This project uses **logistic regression** to predict churn based on a telecom dataset. We also use techniques like **cross-validation** and **bootstrap resampling** to check how well the model works.

### Key Objectives:
- Preprocess the data and explore it.
- Train and evaluate a logistic regression model.
- Use resampling methods (cross-validation & bootstrap) to assess performance.
- Visualize key findings and results.

## 2. Dataset Overview

The dataset includes 1,000 customers with these key features:

- **CustomerID**: Unique customer identifier.
- **Age**: Age of the customer.
- **Gender**: Gender of the customer (0 = Female, 1 = Male).
- **Tenure**: Number of months with the company.
- **ContractType**: Type of contract (0 = Month-to-Month, 1 = One-Year, 2 = Two-Year).
- **MonthlyCharges**: Monthly payment amount.
- **InternetService**: Type of internet service (0 = DSL, 1 = Fiber Optic, 2 = None).
- **TechSupport**: Whether the customer has tech support (0 = No, 1 = Yes).
- **Churn**: Whether the customer churned (0 = No, 1 = Yes).

### Target Variable:
- **Churn**: This shows if a customer has left or stayed.

### Key Predictors:
- **Tenure**, **MonthlyCharges**, **ContractType**, **InternetService**, **TechSupport**, **Age**, and **Gender** are the key factors that help predict if a customer will churn.

## 3. Libraries Used

In this project, we use libraries like Pandas, Scikit-Learn, and Matplotlib to process the data, build the model, and visualize results.
