# EDA Lending Club Case Study
Exploratory data analysis for Lending Club Case Study

## Introduction
This case study gives an idea of applying EDA in a real business scenario. In this case study, apart from applying the techniques that you have learnt in the EDA module, you will also develop a basic understanding of risk analytics in banking and understand how data is used to minimise the risk of losing money while lending to customers.

## Business Understanding
1. if the applicants likely to repay the loan,then not approving the loan results in a loss of bussiness to the lending company.
2. If the applicant is not likely to repay the loan, i.e loaner is likely to ‘Charged Off’, then approving loan may lead to a finanical loss for the lending company.

## Steps Followed in this EDA case study
1. Data Understanding.
2. Data Cleaning & Manipulations.
3. Data Analysis with plots.
4. Identify the Driving Factors for 'Charged-off' loan
5. Recommendations

## Data Understanding
1. Importing the Dataset from the csv files.
2. Identified key columns in the dataset to find solution to minimize the risk of loss.
3. loan_status “Current” is ongoing loan, so these rows are ignored from the dataset for our analysis.
4. Dataset contains shape of (39717 rows, 111 columns)

## Data Cleaning & Manipulations
1. Null values > 90% columns are cleaned.
2. Column had same value in all rows are ommitted 
3. Conver the columns data type to expected format. ((removal of %, +Years, months, %b-%y )
4. Identified outliers and standardized values for ‘annual_inc’ columns, which is used for data analysis. Whereas all other columns outliers may not impact our analysis.

## Data Analysis with plots
The following list of data analysis executed on the dataset, which will be shown with result in the uploaded slides.

1. Univariate unordered/ordered categorical.
2. Univariate segemented analysis.
3. Bivariate Analysis.
 
## Identify the Driving Factors
After analyzing the datasets, The driving factors of a loaner with which the bank would be able to identify if loaner 
will ‘Charged-Off or Fully-Paid’ the loan captured in the slides.

## Outcome/Recommendations
Based on the EDA for the loan dataset gives recommendations to the bank, which can reduce the risks.







