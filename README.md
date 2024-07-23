# Lending Club Case Study

## Table of Contents

- [General Info](#general-information)
- [Conclusions](#conclusions)
- [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)
- [License](#license)
- [Glossary](#glossary)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Project Information:
This is a ****Case study** for **EPGP- ML and AI**, that uses the **Lending Club** data set and use EDA techniques, to decipher, which types of customers default on a loan.
The given "Loan Dataset" contains information, about past loan urban applicants. 
Analyze the Loan Dataset (2007-2011), to identify patterns of the applicants, indicating potential loan defaults or not. 

### Domain Understanding:
Assume you work for a consumer finance company, which specialises in lending various types of loans to urban customers. 
When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.
Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to ‘risky’ applicants, is the largest source of financial loss (called credit loss). 
Credit loss is the amount of money lost by the lender, when the borrower refuses, to pay or runs away, with the money owed. In other words, borrowers who default, cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

### Problem Statement:
Find the driving factors which lead to the defaulted loans, which are major source of loss for the company.
Thereby helping the bank mitigate financial losses by taking various significant actions.

### Data Set:
The data set is a csv file with the 'loan' data for the Lending Club.

### AIM and Approach:
1. The main objective is to be able to identify these risky loan applicants, using EDA. Then such loans can be reduced thereby cutting down the amount of credit loss.
2. We are concerned about determining the driving factors (or driver variables) behind loan default, i.e. the variables that are strong indicators of default. The company can utilize this knowledge, for its portfolio and risk assessment. This is the case of identification, where we are more interested, in identifying the key driver variables, that lead to the outcome of loan defaulters.
3. Identification of such applicants using EDA is the aim of this case study.

### EDA STEPS :
Step 0 - Data Loading, Data Cleaning & Manipulation Checklist.<br>
Step 1 - Dropping Rows - where loan_status = “Current”.<br>
Step 2 - Dropping Columns based on EDA and Domain Knowledge.<br>
Step 3 - Convert the data types.<br>
Step 4 - Identify columns with blank values which need to be imputed.<br>
Step 5 - Analysis of the dataset post cleanup.<br>
Step 6 - Outlier Treatment.<br>
Step 7 - Analysis - Univariate,Segmented Univariate, Bivariate and Derived Metrics Analysis.<br>
Step 8 - Conclusions.

## Conclusions:
#### A) Major Driving factor which can be used to predict the chance of defaulting and avoiding Credit Loss:
* DTI
* Grades
* Verification Status
* Annual income
* Pub_rec_bankruptcies
#### B) Other considerations for 'defaults' :
* Burrowers from large urban cities like california, new york, texas, florida etc.
* Burrowers having annual income in the range 50000-100000.
* Burrowers having Public Recorded Bankruptcy.
* Burrowers with least grades like E,F,G which indicates high risk.
* Burrowers with very high Debt to Income value.
* Burrowers with working experience 10+ years.

## Technologies Used:
1. Name: matplotlib<br>
   Version: 3.8.4<br>
   Summary: Python plotting package<br>
2. Name: seaborn<br>
   Version: 0.13.2<br>
   Summary: Statistical data visualization<br>
3. Name: pandas<br>
   Version: 2.2.2<br>
   Summary: Powerful data structures for data analysis, time series, and statistics<br>
4. Name: numpy<br>
   Version: 1.26.4<br>
   Summary: Fundamental package for array computing in Python<br>
5. Name: plotly<br>
   Version: 5.22.0<br>
   Summary: An open-source, interactive data visualization library for Python

## Acknowledgements:
This project was inspired by UpGrad IIITB Programme, as a case study for the EPGP in Machine Learning and Artificial Intelligence course.

## Contact:
Created by [@Shivani210997] - feel free to contact me!

## Glossary
EDA - Exploratory Data Analysis

## License:
This project is open source and available without restrictions.
