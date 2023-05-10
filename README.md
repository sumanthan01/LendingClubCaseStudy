# Lending Club Case Study
> 
LendingClub is a financial services company headquartered in San Francisco, California. It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC), and to offer loan trading on a secondary market. At its height, LendingClub was the world's largest peer-to-peer lending platform.

Lending Club is a marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return. 



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.
The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilize this knowledge for its portfolio and risk assessment

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Applicatants who fall under grade ’G’ have a higher chance of defaulting which can be attributed to high interest rate.
- Small business applicants are more prone to defaulting
- Even if the number of application are more for 36 months, there seems to be a higher percentage of defaulters in 60 months tenure. Thus, higher the loan term, higher the chances of defaulting.
- There seems to be a larger number of charged off applicants who rent a house against other values but there is a higher percentage of charged off applicants who  have ‘other’ ownership.
- Loan amount, funded amount and funded amount invested are closely related. Hence, the risk increases if the value for these variables increase.
- Annual income in inversely proportional to loan status indicating that applicants with higher annual income are less likely to default.
- Applicants who have higher records of bankruptcies tend to not pay the loan in full.
- There is a high frequency applications for 
  - annual income range of 40-60k
  - purpose of debt consolidation
  - term of 36 months
  - interest rate between 10 and 15
  - rented property
  - grade B
  - 10+ years of experience 
  - loan amount,funded amount, funded amount invested



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python - version 3.9
- jupyter - version 6.5

## Libraries Used
- pandas - version 2.0
- numpy - version 1.24
- seaborn - version 12.0
- IPython - version 0.7
- matplotlib - version 3.5
- warnings - version 3.11


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- Stack overflow
- References
    - [Lending club resource center](https://www.lendingclub.com/resource-center).


## Contact
- Authors: 
    - [@sumanthan01] 
    - [@TanishaS21] 


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->