# Loan Data from Prosper
## by Borbala Darabos


## Dataset

[Loan Data from Prosper](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1554486256021000) data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

[Prosper Data Dictionary to Explain Dataset's Variables](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) explains the variables in the data set.


## Summary of Findings

What factors affect a loan’s outcome status? - Loans outcome status seemed to be orderly with most of the loans charged off, completed or current.
What affects the borrower’s APR or interest rate? - The loan amount affest these rates,
Are there differences between loans depending on how large the original loan amount was? - Income range and borrower's APR may differ.

## Key Insights for Presentation

Loan amount in the dataset take on a very large range of values, from about 1000 USD at the lowest, to about 35,000 USD at the highest. Plotted histogram takes a multimodal shape with high peaks at 5,000, 10,000, 15,000 USD. The most frequent loan amount is 4,000 USD.

There are some negative outliers of EstimatedEffectiveYield with relation to the 'LoanOriginalAmount', 'BorrowerAPR'. EstimatedEffectiveYield is the highest for smaller loan amounts and proportionately decreases for larger loan amounts. Apparently, the higher the BorrowerAPR is the higher the EstimatedEffectiveYield is.

People in the income range 25k-75k USD take the highest number of loans, which are generally in the 4,000 and 15,000 USD range of loan amounts. People in the 100k USD+ range take mostly loans from  25,000 USD and up.

Regarding loan categories vs loan amount, the debt consolidation and home improvement has some outliers which result in the highest loan amount. If we disregard these outliers, Business, Auto, Engagement ring and Medical/dental spendings stand out. Professionals, teachers and IT people take the highest amount of loans.

There is a definite and regular trend of outliers of larger monthly payments for smaller loan amounts in almost each listing category. The most popular listing categories like debt consolidation, home improvement have a wide range of monthly payments. The financing of the less popular categories does not divert that much. 
