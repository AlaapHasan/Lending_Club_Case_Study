# Lending_Club_Case_Study


One of the biggest challenges facing Lending Club, a consumer finance marketplace that specializes in providing a range of loans to urban clients, is overseeing its loan approval procedure. The business must make wise choices when assessing loan applications in order to reduce losses caused by loans given to applicants that are deemed "risky."

When borrowers default on their debts, they incur these monetary losses, also known as credit losses. The borrowers who have been classified as "charged-off" are, to put it simply, the ones who have caused the company's biggest losses.

Helping Lending Club reduce credit losses is the main goal of this exercise. Two possible situations give birth to this challenge:

1. Since interest payments from borrowers might result in earnings for the business, it is essential to identify those who are likely to return their debts. Potential business would be lost if such applications were turned down.
2.However, the organization may suffer significant financial losses if it approves loans for borrowers who are at danger of default and are unlikely to repay.

## Table of Contents

- [General Info](#general-information)
- [Conclusions](#conclusions)
- [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)
- [Collaborators](#collaborators)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Objectives

The goal is to identify applicants who are at risk of loan default so that credit losses can be minimized. This case study uses exploratory data analysis (EDA) with the given data to accomplish this goal. [dataset](./loan.csv).

The organization seeks to identify the variables that are strong predictors of loan default, or the causes of loan default. The business can use this information for risk assessment and portfolio management.

The main goal of this activity is to help Lending Club reduce credit losses. This problem results from two possible situations:

1. Since loan applicants might profit the business by paying interest, it is essential to identify those who are likely to return their loans. Such candidates would result in lost business if they were rejected.
2. However, the company may suffer significant financial losses if it approves loans for borrowers who are at danger of default and are unlikely to repay.

## Conclusions

1. Since the majority of "Charged Off" loans are from loan applicants in Grades B, C, and D, the corporation ought to think about enforcing more stringent risk assessment and underwriting standards for applicants in these grades.

2. Applicants with Subgrades B3, B4, and B5 should receive particular attention because they are more prone to charge off. Lower loan amounts or the implementation of extra risk mitigation strategies can be taken into consideration.

3. The organization should think about assessing the risk involved with longer-term loans and either limiting the maximum term or modifying interest rates in accordance with the findings that applicants who choose 60-month loans are more likely to default.

4. **Default Probability and Experience** Applicants for loans who have 10 or more years of experience have a higher chance of defaulting. This implies that creditworthiness may not always be accurately determined by experience alone. The business ought to employ a more thorough credit scoring system that takes into account additional risk-related characteristics.

5. **Positive Growth Trend**: The market is expanding, as seen by the consistent rise in loan applications between 2007 and 2011. By preserving a competitive advantage in the market and upholding strong risk management procedures, the business can benefit from this trend.

6. **Seasonal Trends**: Because of the holidays, loan applications are most common in December and Q4. During these times, the business should expect more demand and make sure that processing is done efficiently to satisfy client demands.

7. **Debt Consolidation Risk**: The company should carefully assess applicants for debt consolidation loans and maybe modify interest rates or provide financial counseling services, as this is the category with the highest number of loans and high default rates.

8. **Housing Status and Default Risk**: Applicants who own or rent a home are at a higher risk of defaulting. The underwriting procedure may take this information into account when evaluating housing stability and how it affects repayment capacity.

9. **Verification Process**: Compared to unverified loan applicants, verified loan applicants are more likely to default. The business should examine its verification procedure to make sure it evaluates applicants' creditworthiness accurately and take any necessary changes into account.

10. **Geographic Risk**: Applicants for loans from states with higher default rates include California (CA), Florida (FL), and New York (NY). The business should keep an eye on regional risk patterns and modify lending policies or rates as necessary.

11. **High Loan Amounts**: Those who receive loans totaling $15,000 or more are at a higher risk of defaulting. By performing more extensive evaluations for larger loan requests and maybe regulating loan amounts for applicants that pose a greater risk, the organization can reduce this risk.

12. **DTI and Interest Rates**: Defaults are linked to high debt-to-income (DTI) ratios and interest rates between 13\% and 17\%. To better reflect the borrower's capacity to repay, the business should reevaluate how it determines interest rates and think about modifying them in light of DTI ratios.

13. **Low Annual Income**: Applicants are more likely to default if their yearly income is less than $40,000. To guarantee affordability for borrowers, the business might think about providing financial education materials or establishing limit loan amounts based on income levels.


## Technologies Used

- [Python](https://www.python.org/) - version 3.11.4
- [Matplotlib](https://matplotlib.org/) - version 3.7.1
- [Numpy](https://numpy.org/) - version 1.24.3
- [Pandas](https://pandas.pydata.org/) - version 1.5.3
- [Seaborn](https://seaborn.pydata.org/) - version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was supported by live session of upGrad  on the learning platform which really helped in planning.


Created by Alaap Hasan
