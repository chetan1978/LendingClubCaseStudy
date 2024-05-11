# Lending Club Case Study

You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Business Objective
- This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters’. 
- If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
- In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
__There is more probability of defaulting when__
- Borrowers are taking loan for the term 60 months
- Borrowers who take loan amount in the range 0 to 14000
- Borrowers whose annual income is low i.e. (0-20000)
- Borrowers who are having home ownership as ‘Rent’ and take loan for the purpose of debt consolidation
- Borrowers who take loan for the purpose of small business
- Borrowers who are categorized in lower Grades i.e. F & G
- Borrowers who are further sub-categorized in subgrades F5, G3 & G5
- Borrowers who are given loan at interest rate in the range 15%-20%
- Borrowers whose employee length is 1 or less and 10 or 10+ years
- Borrowers who are from the state of NE
- Borrowers who are verified (verification process should be made better)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- [Python](https://www.python.org/) - version 3.11.5
- [Matplotlib](https://matplotlib.org/) - version 3.7.2
- [Numpy](https://numpy.org/) - version 1.24.3
- [Pandas](https://pandas.pydata.org/) - version 2.0.3
- [Seaborn](https://seaborn.pydata.org/) - version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- UpGrad tutorials on Exploratory Data Analysis (EDA) on the learning platform


## Contact
Created by [@chetan1978] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
