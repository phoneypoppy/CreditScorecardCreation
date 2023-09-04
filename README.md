# Credit Scorecard Creation

### Main Aim: 
Testing the hypothesis that homeowners would have a higher chance of not defaulting as compared to non-homeowners.
Therefore, we will create a scorecard to see how homeownership affects credit scoring and then evaluate our hypothesis by analysing the score allocation between different attributes in home ownership.

---
The Credit Risk Dataset was used for this analysis because it contained simulated credit bureau data that was available on Kaggle. There were 32581 rows and 12 columns consisting of both numerical and categorical variables. 

<ins>Features of Dataset:

- person_age (Age)
- person_income (Annual Income)
- peronhomeownership (Homeownership)
- Personemplength (Employment Length in years)
- Loan_intent (loan intent)
- Loan_grade (loan grade)
- Loan_amnt (Loan amount)
- Loanintrate (Loan interest rate)
- Loan_status (Loan status)
- Loanpercentincome (Percent income)
- Cbpersondefaultonfile (Historical default)
- Cbpersoncredhistlength (Credit history length)


<ins> Analytics Techniques: 

We used Credit Scorecard, which helps to reduce the rate of default by determining a probabilistic threshold that can be used to decide the risk tolerance. It uses Weight of Evidence to establish the monotonicity, supports outliers and help to deal with missing value. It also uses information value which is used for univariate screening to reduce the number of independent variables.
We also used logistic regression to estimate the probability of whether an event will occur.

