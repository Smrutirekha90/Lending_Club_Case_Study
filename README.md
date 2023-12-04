# Lending_Club_Case_Study
## Business Objectives
Lending Club is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

## General Information
Identifying those risky applicants helps in cutting down the amount of credit loss to the organization. 
The data set used is 'loan.csv'.
Below are the steps followed in the process
- Step 1: Data Understanding  
- Step 2: Data Cleaning
- Step 3: Univariate Analysis
- Step 4: Bivaraiate/Multivariate Analysis
- Step 5: Results

## Conclusions
- Major Parameter which drive the Defaulters are – Verification Status, Annual Income, Interest Rate, DTI, Purpose of Loan
- Loan taken for Small Business are more likely to be defaulters.
- Applicants whose home ownership is 'MORTGAGE’ or ‘RENT’ are more likely to be defaulters
- Increased interest rate is a strong factor for defaulting loan amount.
- Higher the interest rate , higher chance of getting charged off 

## Technologies Used
- Python - version 3.7.6
- NumPy - version 1.18.1
- Pandas - version 1.2.3
- Matplotlib - version 3.1.3
- Seaborn - version 0.10.0

## Acknowledgements
- This project was created as a case study required for Executive PG Programme in Machine Learning & AI - IIIT, Bangalore 

### Contributors
* [Smrutirekha Khatua](https://github.com/Smrutirekha90)
