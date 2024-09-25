# Loan Default Prediction Using EDA

## Introduction
This project aims to identify the key factors that contribute to loan defaults using exploratory data analysis (EDA) on a dataset of loan applicants. Understanding these factors can help the company mitigate financial losses by making informed lending decisions.

## Approach
- **Univariate Analysis**: Examined the distribution of key variables such as loan amounts, interest rates, and income.
- **Bivariate Analysis**: Investigated relationships between loan status and variables such as interest rate, loan amount, and term.
- **Multivariate Analysis**: Analyzed the correlation between multiple factors to identify key drivers of loan defaults.

# Project Name
Loan Default Prediction Using EDA

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information

Background of the Project: The project focuses on consumer finance, particularly loans granted to  customers. The finance company needs to approve or deny loans based on the risk of default by the applicant. The goal is to build a data-driven understanding of which applicant or loan attributes most strongly correlate with default risk. By identifying these patterns, the company can improve its lending process and minimize financial losses.

Business Problem: The project aims to address the risk of credit loss for financial institutions by identifying risky loan applicants who are more likely to default. Lending to such high-risk individuals often leads to financial loss, and the company wants to minimize these risks by using data-driven insights to either deny loans or charge higher interest rates for risky applicants. By understanding the driving factors behind defaults, the company can optimize its loan approval process and portfolio management.

Dataset: The dataset used for this project includes loan data for customers. It contains detailed information on the loan applicants, the loan status (fully paid, current, charged-off), and various consumer demographics and financial variables. This data helps in performing both univariate, bivariate, multivariate analysis to uncover key insights into customer behavior.

## Conclusions
Analysis Outcome:
This analysis provides actionable insights that can help the company reduce financial losses by identifying risky loan applicants and adjusting their lending criteria.
1.Borrowers with higher DTI ratios (above 15%) are at greater risk of default, especially if their income is not verified or if they have shorter employment histories.
2.Borrowers in the Current or Charged Off categories consistently had higher DTI ratios than those who successfully repaid their loans.
3.Borrowers with 3-7 years of employment face a higher risk of default, particularly when their loan amounts and DTI ratios are higher. While they are offered relatively high loan amounts, they still tend to default at higher rates compared to longer-term employees (10+ years).


Recommndations:
1.Borrowers with high DTI ratios (above 15%) should either receive smaller loan amounts or be charged higher interest rates to compensate for the increased risk. 
2.Lenders should be cautious when lending to borrowers with shorter employment histories (less than 3 years) who have high DTI ratios. Offering smaller loan amounts or additional verification could reduce the risk of default.
3. Verifying income, especially for borrowers with high loan amounts and high DTI ratios, is crucial to reducing default risk. 

## Technologies Used
Jupyter version: 7.0.8
python version: 3.12.3
pandas version: 2.2.2
numpy version: 1.26.4
matplotlib version: 3.8.4
seaborn version: 0.13.2

## Contact
@RajHujigal
@rakbha9
- feel free to contact us!


https://github.com/RajHujigal/LendingClubCaseStudy
