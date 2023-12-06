# Project Name
> ### **Lending Club Case Study**


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
### Problem Statement

A consumer finance company specializing in lending loans to individuals is confronted with the challenge of optimizing loan approvals while minimizing the risks associated with defaulters. The task at hand is to analyze historical data and identify the key factors driving loan defaults.

### Business Objectives

#### 1. Risk Assessment

Utilize Exploratory Data Analysis (EDA) on historical loan data spanning from 2007 to 2011 to evaluate the risk associated with loan applicants based on their likelihood of repayment.

#### 2. Default Identification

Identify patterns indicating the likelihood of loan default by conducting a detailed analysis of consumer and loan attributes. Apply EDA techniques to delve into consumer and loan attributes, seeking insights that can aid in default prediction.

#### 3. Data Understanding

Understand the driving factors (or driver variables) behind loan default, focusing on variables that serve as strong indicators of default.

#### 4. Mitigate Credit Loss

Mitigate credit loss by identifying and optimizing loans to high-risk applicants. Develop strategies to minimize the impact of defaults and enhance overall lending portfolio performance.

### Loan Outcome Categories

When a person applies for a loan, there are two types of decisions that could be taken by the company:

#### Loan Accepted

If the company approves the loan, there are three possible scenarios:

1. **Fully Paid:** Applicant has fully paid the loan, including the principal and the interest rate.
2. **Current:** Applicant is in the process of paying the instalments, and the tenure of the loan is not yet completed. These candidates are not labeled as 'defaulted.'
3. **Charged-Off:** Applicant has not paid the instalments in due time for a long period, indicating a default on the loan.

#### Loan Rejected

The company rejects the loan, typically because the candidate does not meet their requirements. Since the loan was rejected, there is no transactional history of those applicants with the company, and this data is not available in the dataset.

#### About the Dataset:

The dataset represents historical loan data from a consumer finance company operating between 2007 and 2011. It includes various attributes such as loan amounts, borrower information, credit grades, employment details, and loan outcomes (fully paid, current, or charged-off), aiming to analyze and identify factors influencing loan defaults for optimizing future lending decisions by optimizing the defaulters. 



## Conclusions

Following are the summarized points from our EDA analysis on the dataset:
- Higher loan amounts, particularly in the range of $15,000 to $35,000, correlate with an increased likelihood of default.
- Higher loan amount tend to increase the risk of defaulting.
- Annual incomes falling between $4,000 and $45,000 are associated with a higher risk of default, indicating a connection between lower income levels and repayment challenges.
- Loans for small businesses and renewable energy purposes demonstrate a higher tendency to default, possibly due to increased business risks.
- Applicants without property ownership, such as a house, exhibit a higher likelihood of becoming defaulters.
- Debt-to-Income Ratio (DTI), especially in the range of 24-30, significantly raises the chances of loan default, emphasizing the importance of evaluating an applicant's debt burden.
- Credit grades F & G showcase higher default rates, warranting careful scrutiny and cautious approval for applicants in these categories.
- A history of public bankruptcies increases the risk of default, emphasizing the need for thorough evaluation before approving loans for individuals with such backgrounds.



## Technologies Used
- Python
- Python Libraries:
    - NumPy
    - Pandas
- Data Visualization
    - Matplotlib
    - Seaborn
- Editor:
    - Jupyter Notebooks
- Approach:
    - Exploratory Data Analysis (EDA)


## Acknowledgements

- This project is done as a part of IIIT PGP Case Study.
- References:
    1. **Python**
    - [Start with Python](https://www.python.org/)
    2. **NumPy**
    - [NumPy official doc](https://numpy.org/doc/stable/)
    3. **Pandas**
    - [Pandas official doc](https://pandas.pydata.org/pandas-docs/stable/)
    4. **MatPlotlib**
    - [MatPlotlib official doc](https://matplotlib.org/stable/users/index.html)
    5. **Seaborn**
    - [Seaborn official doc](https://seaborn.pydata.org/)
    6. **EDA:**
    - [Wikipedia - Exploratory Data Analysis](https://en.wikipedia.org/wiki/Exploratory_data_analysis)

<!--
## Contact
Created by [@githubusername] - feel free to contact me!
-->
