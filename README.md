# Rahul Jha Portfolio
## Data Science Portfolio

### CLICK ON THE PROJECT TITLE TO VIEW THE PROJECT!

# [Project 1:Loan Status Prediction : Project Overview](https://github.com/Rahul713713/Loan_Status_Prediction)
![loan_status](https://github.com/Rahul713713/Rahul_Jha_Portfolio/blob/main/images/loan_status.jpeg "Loan Status Prediction")
- Created multiple charts,graphs,countplots,etc. in order to understand how to minimise the risk of losing money while lending to customers.
- Worked on a dataset consisting of 614 rows of data for 12 different features.
- Performed univariate analysis as well as multivariate analysis on various features to understand the importance of every feature.
- Used EDA to understand how consumer attributes and different features help us in identifying customers who are eligible for a loan from customers who are not.

# Problem Statement
Predicting whether an applicant is eligible for the loan that he/she has applied for based on multiple independent variables and Machine Learning. This will help the company in automating the process of checking the eligibility of the applicant for the loan.Now,when a customer applies for a loan, the company has to make a decision whether to approve the loan or not based on the applicant's profile. 

The data that I have contains information about applicants and their Gender,Education,Self_Employed,ApplicantIncome,etc. and whether they are eligible for the loan or not.

# EDA
After cleaning the data,I started with EDA. These are some of the outcomes of EDA 

![loan_status](https://github.com/Rahul713713/Rahul_Jha_Portfolio/blob/main/images/loan_eligibilty_based_on_credit_history.png "loan_eligibilty_based_on_credit_history")
![loan_status](https://github.com/Rahul713713/Rahul_Jha_Portfolio/blob/main/images/loan_eligibilty_based_on_education.png "loan_eligibilty_based_on_education")
![loan_status](https://github.com/Rahul713713/Rahul_Jha_Portfolio/blob/main/images/most_important_features.png")

# Result
    +--------------------------------------------------------------------------------+
    |           *** Model Summary *** [Performance Metric: Accuracy Score]           |
    +-----------------------------------------------+----------------+---------------+
    |                   Model Name                  | Train Accuracy | Test Accuracy |
    +-----------------------------------------------+----------------+---------------+
    |                  Naive Bayes                  |     0.794      |     0.817     |
    |              K Nearest Neighbors              |     0.836      |      0.8      |
    | Logistic Regression - Without Class Balancing |     0.807      |     0.817     |
    |   Logistic Regression - With Class Balancing  |     0.801      |     0.808     |
    |                   Linear SVC                  |     0.807      |     0.808     |
    |              SVC With Rbf Kernel              |     0.824      |     0.808     |
    |                 Random Forest                 |     0.817      |     0.808     |
    +-----------------------------------------------+----------------+---------------+
