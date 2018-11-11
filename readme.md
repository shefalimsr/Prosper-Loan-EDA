# Loan Data from Prosper Data Exploration
## by Shefali Mishra

## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, interest rate , current loan status, borrower income,employment status and credit history etc


## Summary of Findings

> A majority of the users lie between Credit Score the 600 and 800 mark, which are decent credit scores.
> Max monthly income is 1750003 and minimum is 0. It is observed that a majority of the users lie between the 2500 and 7500 range, which makes complete sense because people with very high monthly income don't need to take loan and the ones with towards 0 are less likely to take loan because they may get into debt.
> The bulk of the loans seem to be 0.08 to 0.25 , which coincides with the credit rating histograms that show that the majority of the users are in the middle of the risk ratings. The lender yield and BorrowerRate plots are similar to borrower APR because they all represent interest rates. 
>Most of the loan amount are in the range of 0 - 10000 . One thing that should be noted is that values at multiple of 5000 are more than the other number which is obvious as people have a tendency to go for numbers that are easy to remember .
> This graph also show that the people in range of 0 - 25000 are not taking loans or maybe are unable to get it . This may be due to basic salary requirements of the organization to grant a loan, which the low income range don’t meet easily and hence might be unable to get a loan.
> Prosper Rating has a direct relation with Credit Score . As the borrower move into lower risk range , his credit score also increases.
> One thing to see here is that there's numberof both delinquent and good borrowers follow the same trend except in 2013. In 2013 number of good borrowers increased drastically while on he other hand number of delinquent borrowers decreased .In 2014 both the numbers decreased significantly . 
> We see the growth of the company through it’s increasing loan openings, but we can also see the performance of loans over time.

## Key Insights for Presentation

> From the above correlation plot, it can be concluded that as such there are no two variables that are strongly correlated , other than 'BorrowerAPR', 'BorrowerRate' and 'LenderYield' which are basically not significantly different from one another .These three are negatively correlated to ProsperScore , but again there is no strong correlation.

> Also I wanted to look at Chargedoff, Completed, Current and Defaulted LoanStatus. Chargedoff Loans have high ProsperScore , but they were not prominent after 2013, Same is the case for Defaulted LoanStatus. Also, it increased for Completed LoanStatus , perhaps reflecting the new strategy of Investors to select loans from the middle ProsperScore distribution.

> The debt consolidation category is somewhat misleading as multiple categories could be lumped into one - which is exactly what it is by definition. But one thing we can take away from the high volume of borrowers requesting debt consolidation loans, is that, many borrowers have debt from multiple sources and is by far the most frequent category.


The graphs related to these findings are present in the presentation.