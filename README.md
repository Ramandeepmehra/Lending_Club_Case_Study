# Project Name
> Lending Club Case Study



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Project Information

> The project is a EDA project that uses the provided lending club data set to get an understanding of risk analytics in banking and financial services and also to understand how data is used to minimize the risk of loosing money while lending to the customers.


### Project Background

#### Goal
> How data can be used minimize the risk of losing money while lending to customers.

#### Risk associated with the problem

> If the applicant is likely to repay the loan, then not approving loan is a loss of business to the company (rejecting loans for non - default).
> If the applicant is not likely to repay the loan, then approving loan may lead to financial loss to the company (approving loans for default).

> The given dataset contains information about past loans applicants and whether they ‘defaulted’ or not.
Each row represents the loan details of the applicants.

### Project Statement

> The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. With the help of this case study, company can utilise this knowledge for its portfolio and risk assessment.

### Data Set

> The data set is a csv file with the loan data for the Lending Club.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

#### There is more chances of defaulting when:
- Applicants who use the loan to clear other debts, start a small business, clear off credit card bills or home improvement.
- Applicants who receive interest at the rate of 13-17%.
- Applicants where the employee length is 10+ years.
- Applicants with income less than 50000.
- Applicants for whom the dti is ranging between 12 – 15.
- The Applicant is already having an ongoing “MORTGAGE”
- The loan amount is applied for a larger value (>10000)

#### Few more observations:
- The chances of defaulting increases for applicants:
- Whose home ownership is “Mortgage” and loan value is in range of 14k - 16k
- Employment length is 10+ years and loan amount is in range of 12k - 14k
- When the interest is changed in the range of 15-17% and loan is in the range of 30k - 35k

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Recommendations
1. Verification and Default Rates:
- 43.27% of loans were not verified, with 5.55% resulting in defaults.
- Suggests a need for more thorough verification processes, especially for 10+ years term loans.
2. Impact of default Year 2007 - 2011:
- The introduction of credit card loans in 2011 led to a higher percentage of loans granted.
- Default rates increased, emphasizing the importance of caution when granting loans, especially for 36 months.
3. Home Ownership and Default Rates:
- Majority of loans approved for RENT and MORTGAGE home ownership.
- High default rates in these categories highlight in OTHER and RENT need for careful consideration when granting loans to these homeownership types.
4. Interest Rates and Default Risk:
- Higher interest rates are associated with an increased risk of default.
- Recommends thorough checks and verification before granting loans with higher interest rates.
5. Loan Amount and Default Rates:
- Higher loan amounts correlate with higher default rates.
- Observations show a higher Charged Off rate for larger loans, indicating a potential risk factor.


## Technologies Used
- Python version: 3.7.3
- Pandas version: 1.3.4
- Numpy version: 1.21.5
- Matplotlib: version 3.1.3
- Seaborn: version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- Developed as part of the Exloratory Data Analysis required for UpGrad - IIIT Bangalore ML C60 Programme.

## Contact
    Created by [@Ramandeepmehra] - feel free to contact me!


<!-- Optional -->
## License 
> This project is open source and available without any restrictions

<!-- You don't have to include all sections - just the one's relevant to your project -->
