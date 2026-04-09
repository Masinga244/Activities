# Two-Pot Retirement System Analysis (South Africa)

## Project Overview

This project focuses on analyzing South Africa’s **Two-Pot Retirement System**, a policy designed to balance short-term financial access with long-term retirement security. The system splits retirement savings into:

* **Accessible Pot (Short-term)** → Allows limited withdrawals before retirement
* **Locked Pot (Long-term)** → Preserved until retirement

The goal of this project is to use **data science and machine learning techniques** to understand and predict employee behavior within this system.



## Objectives

This project addresses three key analytical tasks:

### 1. Classification (Predicting Withdrawals)

* Predict whether an individual is likely to withdraw funds from the accessible pot within the next 12 months
* Helps identify high-risk individuals who may deplete retirement savings early

### 2. Forecasting (Locked Pot Growth)

* Estimate the future value of retirement savings in the locked pot
* Uses time-series forecasting techniques to model growth over time

### 3. Sentiment Analysis (Conceptual)

* Analyze employee feedback regarding the Two-Pot system
* Classify opinions as **positive, negative, or neutral**
* No coding required — conceptual explanation only



## 📊 Datasets Used

Since no dataset was provided, multiple datasets were sourced and combined:

### Census / Demographic Data

* Household income
* Household size
* Education level
* Access to services (food, internet, etc.)

### Economic Data

* Inflation rates
* Interest rates
* GDP trends


## Tools and Technologies

* **Python**
* **Google Colab**
* **Pandas** – Data cleaning and manipulation
* **NumPy** – Numerical operations
* **Scikit-learn** – Machine learning models
* **Matplotlib / Seaborn** – Data visualization


## Methodology

### Data Collection

* Data sourced from public platforms such as:

  * Statistics South Africa (Stats SA)
  * World Bank
  * OECD

### Data Preprocessing

* Handling missing values
* Feature selection and engineering
* Encoding categorical variables

### Modeling

#### Classification Models:

* Logistic Regression
* Decision Trees
* Random Forest

#### Forecasting Models:

* ARIMA / Prophet (for time-series analysis)

