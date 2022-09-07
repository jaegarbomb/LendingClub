# Lending Club Case Study
This project uses EDA to analyse Lending Club's customer dataset to infer which customers are likely to default on their loans. Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender  when the borrower refusesto pay or runs away with the money owed.   The main objective is to be able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such features using EDA is the aim of this case study.   

# Objective:
Perform an analysis to understand the driving factors (or driver variables) behind loan default, i.e.the variables which are strong indicators of default.

## Table of Contents
* [General Info](#general-information)
* [Libraries used](#libary-used)
* [Files](#files)
* [Conclusions](#conclusions)
* [Contact](#Contact)

## Libaries Used
- Pandas 1.4.4
- Matplotlib 3.5.3
- Seaborn 0.11.2
- JSON

## Files
- **loan.csv** : The main dataset
- **Data_Dictionary.xlsx** : This contains explanation of all the columns in the dataset. 
- **State_abbr.json** : This JSON file contains the Abbreviation-FullName of all the US states. This is used in analysis of states for better readability.
- **Lending_Club_EDA.ipynb** : The Jupyter notebook containing the analysis of the dataset.
- **Lending Club Case Study Report.pdf** : The final report containing the visualizations and inferences.

## Conclusions
The analysis in the Lending_Club_EDA.ipynb has resulted in the below inferences:
An Applicant is *likely* to default if:

- they have house_ownership as 'RENT'
- they use the loan to clear other debts (debt consolidation)
- they receive interest at the rate of 13-17%
- they have employement length of 10+ years
- their Debt-to-Income ratio is between 12-18
- their loan has a term of 60 months
- their loan Grade is 'B'
- their state of residence is California

There are several other inferences as well but most of them are correlated. For e.g. Grade-Loan amount- Term - Rate of Interest.

## Contact
Created by Jayit Ghosh [@jaegarbomb]
