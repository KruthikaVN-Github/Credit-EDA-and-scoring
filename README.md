# Credit EDA & Credit Score Calculation with Python
This repository contains an analysis of credit data and the calculation of a hypothetical credit score using Python. The project focuses on exploring various factors influencing an individual's creditworthiness, such as income, payment history, credit usage, and loan behavior. The goal is to provide a deeper understanding of the features that affect credit scores and help build a predictive model for assessing credit risk.

# Dataset Overview
The dataset used in this project includes information on various financial attributes of individuals, which can help in the calculation of credit scores and evaluation of creditworthiness. Below is a description of the key columns present in the dataset:

# Columns
ID: Unique identification for each entry in the dataset.
Customer_ID: Unique identification for the person.
Month: Month of the year associated with the data.
Name: Name of the person.
Age: Age of the individual.
SSN: Social Security Number of the individual.
Occupation: Occupation of the person.
Annual_Income: Total annual income of the person.
Monthly_Inhand_Salary: Monthly base salary of the individual.
Num_Bank_Accounts: Number of bank accounts held by the person.
Num_Credit_Card: Number of credit cards held by the individual.
Interest_Rate: Interest rate on the individual's credit card.
Num_of_Loan: Number of loans taken by the person.
Type_of_Loan: Types of loans taken by the person.
Delay_from_due_date: Average number of days a person delays payments.
Num_of_Delayed_Payment: Number of delayed payments made by the person.
Changed_Credit_Limit: Percentage change in the credit card limit.
Num_Credit_Inquiries: Number of inquiries made for the individual's credit.
Credit_Mix: Classification of the mix of credit types the person holds.
Outstanding_Debt: Remaining debt that the person needs to pay (in USD).
Credit_Utilization_Ratio: The ratio of credit used to total available credit.
Credit_History_Age: The duration of the person’s credit history.
Payment_of_Min_Amount: Whether only the minimum payment amount was paid by the individual.
Total_EMI_per_month: Total monthly EMI payments (in USD).
Amount_invested_monthly: Monthly amount invested by the individual (in USD).
Payment_Behaviour: The payment behavior of the customer.
Monthly_Balance: Monthly balance amount of the individual (in USD).

# Objective
This project aims to conduct an Exploratory Data Analysis (EDA) on the credit dataset to uncover key patterns and insights affecting creditworthiness. Additionally, a hypothetical credit score is calculated using the provided features to simulate how various factors contribute to a person's overall credit score.

# Features
Exploratory Data Analysis (EDA): Analyze the distribution, trends, and relationships within the dataset.
Feature Engineering: Create new features and assess their impact on the credit score.
Credit Score Calculation: Build a model or methodology to estimate a hypothetical credit score based on the data.
How to Use
Clone this repository: git clone <repository_url>
Install dependencies: Install the necessary Python libraries (e.g., pandas, numpy, sklearn, etc.).
Run analysis: Explore the data, create visualizations, and calculate credit scores using the available features.
Build predictive model: (Optional) Use the features to train a machine learning model for credit score prediction.
