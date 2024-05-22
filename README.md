# Lending Club Case Study
- Lending Club is a marketplace for loans. This case study is to determine which application is suitable to lend the money so that lending club will minimise the risk of losing money while lending to customer. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.
- Two types of risks are associated with the bank’s decision:
- 1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
- 2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.


## Table of Contents
* [General Info](#general-information)
* [Method Used](#method-used)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Recommendation](#Recommendation)


## General Information
- Lending club is financial service platform that provide the loan based on applicant profile and historical data on some interest rates.	This case study is to determine which application is suitable to lend the money for worthy applicant who not cause any loss of money to lending club. this data contains information about loan applicant and weather they default or not.
- This project will solve banking and financial services problem that cause loss of money when applicant can’t repay the loan. Our aim to identify pattern which indicate if a person likely to pay loan or not, to take decision of denying loan or reduce the amount or lending money at higher interest rate etc.
- The dataset we are using has all the information about applicant profile like who's loan accepted and current status of loan weather it has fully paid, currently ongoing or charged off and many other details of applicant which help us to identify worthy applicants.

## Method Used
- Exploratory Data Analysis(EDA)
- Data Visualisation

## Technologies Used
- Python - version 3.11.5
- NumPy - version 1.24.3
- Pandas - version 2.1.4
- Matplotlib - version 3.7.2
- Seaborn - version 0.13.2
- missingno - version 0.5.2
- plotly - version 5.9.0
- datetime

## Conclusions
- Higher the amount cause more defaulter, more than 10,000 have higher chances to be default and amount less than 6000 has very less chances to be defaulter also Funded amount higher than 9,725 associate with high default rates.​
- Loan term with 60 have greater chances to be default than term with 36.​
- High interest rated cause more defaulters, Interest rates more than 13.79% can be defaulters and interest rate less than 11.49% has very less chances to be default. ​
- Lower loan grades E, F, G have higher default rates, defaults increasing as the loan amount rises within these grades.  ​
- Verified applicants with higher loan amounts tend to default more frequently also Loans for verified applicants with high instalments show increased default rates. ​
- Loans taken for small businesses, renewable energy, and educational purposes have higher default rates especially when loan amounts increase, also Loans for vacations with higher instalments also have a higher Possibility for default. ​
- Applicant's from NV and TN state have higher default rates. ​
- Ownership with mortgages tend to default more often compared to those who own or rent their homes. ​
- Lower instalments, particularly in grades F and G, are associated with higher default rates also Higher instalments in loans for small businesses, education, and renewable   energy also correlate with higher default rates.​
- A higher DTI, especially up to 30%, indicates a higher default. ​
- Regardless of verification status, lower-income buckets show more defaults, indicating income level itself is a critical factor.​
- No clear pattern is observed for employment length, suggesting it's not a strong indicator of default. ​
- Mostly do not have significant public records of bankruptcies, but those who do have a slightly increased risk of default.

## Recommendation
- Implement eligibility criteria for loans exceeding 10,000, as higher amounts are linked to increased default rates. and Encourage applicant to select 36-month terms for higher loan amounts.​
- Small business and educational with higher installment bucket has more defaults and Small Business with Medium annual income bucket has more defaults compare to all. ​
- Implement lending criteria for lower grades (E, F, G), maximum loan amounts for these grades to reduce exposure to high-risk loans and Notability Grade F has more defaults with Very High loan amounts.​
- House and renewable energy with very low installment bucket has more defaults and Vacations with higher installments has more defaults.​
- Implement rule for DTI ratio, DTI levels should be a lower, up to 30% indicates a higher risk.​
Establish loan amount Criteria based on annual income levels to prevent applicant from taking extra loan that can cause their repay capacity.


## Contact
Created by -
Github:
 - Sujata Naik - https://github.com/SujataN23
 - Shameer Shaik - https://github.com/rayanustrip

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
