# PREDICTION-OF-CREDIT-RISK-USING-MACHINE-LEARNING
Optimizing parameters for the prediction of credit risk using Feedforward Neural Networks and comparing the model performance with other machine learning algorithms

## Problem Statement
Credit risk crystalizes in the event that a facility amount or obligation of a borrower is not met, causing the lender to lose. As financial institutions increase in scale and complexity, and in pace of their transactions, there is a growing need for them to develop and adopt advanced techniques to manage risks and keep track of their exposures which are dynamic in nature. Attempts by several scientists to predict credit risk and maximize profits for banks and other financial institutions have proven to be successful. There is now the need to take a step towards optimizing the process. Create a neural network model that attempts to predit credit risk, systemically optimizing the performance of the model and other classifier algorithms and compare their results.
## Objective
This project is aimed at predicting credit risk using a non-linear dataset from a financial institution and optimizing the parameters of different algorithms to compare their performance with that of a Feedforward Neural Network. To achieve this, the following shall be carried out.
- Models from different algorithms will be trained and tested on the dataset.
- Hyperparameter optimization using grid search will be performed on the different models and tested on the dataset to observe their performance.
- The performance of the optimized Neural Network shall be compared with those of other classifier algorithms.
## Evaluation Criteria
Submissions are evaluated using accuracy Score.
## Data Description
The dataset contains information about Loan Applicants. This data has over 148 thousand records. 40 thousand records were randomly selected from the data and appropriate attributes were selected from 34 features for this work. The 32 selected attributes were subjected to dimensionality reduction, reducing the dimension to 8. The following are the variables that make up the data set:

Dependent Variable: Status (0 and 1); This work seeks to predict whether a borrower qualifies for a loan or not, in the near future. Here, a bad loan means that the borrower will
default while a performing loan means that the borrower will not default but will be able to repay the full loan amount. The two classes predicted by the network are 0 which indicates borrower will default and 1 indicating that borrower will not default.

Independent Variable: Following variables are some of the independent variables in the data-
loan_amount, funded amnt; the requested amount by the borrower, funded_amnt_inv; amount approved and offered by the investors, term; the life cycle of the loan, rate_of_interest; interest rate on which loan has been given, instalment; periodic repayment amount, redit_Score; Credit rating assigned to the loan application, emp_length; the borrower’s duration of employment, income; the annual amount the borrower earns, issue_d; the date loan was granted, application_type; whether the application is individual or joint.
