# 💳 Credit EDA & Credit Score Calculation with Python

## 📋 Overview
This project focuses on **Exploratory Data Analysis (EDA)** and the calculation of a **credit score** for individuals based on a given dataset. The dataset contains information about customers' financial activities, including income, loans, delayed payments, and credit utilization. The goal is to identify patterns in the data, uncover meaningful insights, and calculate a hypothetical credit score to assess customers' creditworthiness.

---

## 🎯 Objectives
1. Perform **Exploratory Data Analysis (EDA)** to understand the dataset's structure and key trends.
2. Clean and preprocess the data to ensure it is ready for analysis.
3. Develop a hypothetical **Credit Score Calculation Model** based on key variables.
4. Generate actionable insights for financial institutions to improve customer credit management.

---

## 📂 Dataset Description
The dataset contains detailed financial information for multiple customers. Below is a brief description of the columns:

| **Column Name**           | **Description**                                                                 |
|----------------------------|---------------------------------------------------------------------------------|
| `ID`                      | Unique identification for each entry in the dataset.                           |
| `Customer_ID`             | Unique identification for the person.                                          |
| `Month`                   | Month of the year associated with the data.                                    |
| `Name`                    | Name of the person.                                                            |
| `Age`                     | Age of the individual.                                                         |
| `SSN`                     | Social Security Number of the individual.                                      |
| `Occupation`              | Occupation of the person.                                                      |
| `Annual_Income`           | Total annual income of the person.                                             |
| `Monthly_Inhand_Salary`   | Monthly base salary of the individual.                                          |
| `Num_Bank_Accounts`       | Number of bank accounts held by the person.                                    |
| `Num_Credit_Card`         | Number of credit cards held by the individual.                                 |
| `Interest_Rate`           | Interest rate on the individual's credit card.                                 |
| `Num_of_Loan`             | Number of loans taken by the person.                                           |
| `Type_of_Loan`            | Types of loans taken by the person.                                            |
| `Delay_from_due_date`     | Average number of days a person delays payments.                               |
| `Num_of_Delayed_Payment`  | Number of delayed payments made by the person.                                 |
| `Changed_Credit_Limit`    | Percentage change in the credit card limit.                                    |
| `Num_Credit_Inquiries`    | Number of inquiries made for the individual's credit.                          |
| `Credit_Mix`              | Classification of the mix of credit types the person holds.                    |
| `Outstanding_Debt`        | Remaining debt that the person needs to pay (in USD).                         |
| `Credit_Utilization_Ratio`| The ratio of credit used to total available credit.                            |
| `Credit_History_Age`      | The duration of the person’s credit history.                                   |
| `Payment_of_Min_Amount`   | Whether only the minimum payment amount was paid by the individual.            |
| `Total_EMI_per_month`     | Total monthly EMI payments (in USD).                                           |
| `Amount_invested_monthly` | Monthly amount invested by the individual (in USD).                            |
| `Payment_Behaviour`       | The payment behavior of the customer.                                          |
| `Monthly_Balance`         | Monthly balance amount of the individual (in USD).                            |

---

## 🔧 Key Skills and Tools
This project demonstrates proficiency in the following tools and techniques:
- **Programming Languages**: Python  
- **Libraries**:
  - **Pandas**: For data cleaning, preprocessing, and analysis.
  - **NumPy**: For numerical operations.
  - **Matplotlib & Seaborn**: For creating insightful visualizations.
- **Techniques**:
  - Exploratory Data Analysis (EDA)
  - Feature Engineering
  - Credit Score Modeling
  - Data Visualization

---

## 📊 Steps Performed
1. **Data Cleaning**:
   - Handled missing values and outliers.
   - Preprocessed categorical and numerical features for analysis.

2. **Exploratory Data Analysis**:
   - Explored distributions, correlations, and patterns in financial behavior.
   - Identified key factors influencing creditworthiness.

3. **Credit Score Calculation**:
   - Developed a scoring model using features like `Credit Utilization Ratio`, `Delayed Payments`, and `Outstanding Debt`.
   - Normalized and weighted features to assign credit scores between 300 and 850.

4. **Insights and Recommendations**:
   - Derived actionable insights for improving creditworthiness and managing financial risks.

---

## 📈 Key Insights
- **Delayed Payments**: Customers with higher delayed payments tend to have lower credit scores.
- **Credit Utilization**: A higher credit utilization ratio negatively impacts credit scores.
- **Income Patterns**: Higher annual income and consistent monthly balances are linked to better credit scores.





