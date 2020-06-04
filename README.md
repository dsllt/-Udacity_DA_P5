# Udacity_DA_P5
Code for project 5 of Udacity's Data Analyst Nanodegree.

## Dataset
The data is structured in 113,937 loan entries in which each entry has 81 different variables. The loan data was gathered from an institution named Prosper and can be downloaded [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1554484977406000).

The presented variables are mostly numeric, however there are some categorical variables. Numeric variables are mainly values indicating total loan amount, yield, payment rates and overall rates. On the other hand, categorical variables indicate dates and characteristics of the borrowers.

During the analysis, were considered only 20 variables and some loan entries were not considered, as they presented some values that could possibly be outliers.


## Summary of Findings
The exploration of the data was done in order to understand what factors influence the loan's status and what factors influence the payment of the loan.
It was expected that completed and current status are linked with a smaller number of terms, a lower borrower rate, a positive employment status, homeownership, no delinquencies, a small debt to income ratio, high income range and monthly income.
The exploration of the data revealed that most loans are current and there is a small number of past due loans. The debt to income ratio of loans is usually less than 0.3 and the income range is usually higher than /$25,000. 
Current loans face a wide range of borrower rates between, presenting mostly an income range of $50,000 – $75,999, which is considered to be high. Also, these borrowers with higher incomes present a smaller debt to income ratio.
Past due loans display higher borrower rates range, with values closer to 0.2 and 0.3, and the most frequent income range of individual is $25,000 - $49,999. Also, past due loans have a high frequency of loan original amounts around $4,000, $10,000 and $15,000. Moreover, past due loans have a higher frequency of monthly loan payments around $200, and borrowers with smaller incomes (which is the case of past due loans) are the ones who present higher amount delinquent.


## Key Insights for Presentation

For the presentation, the focus of the investigation stays around loan status and income range. 
The key insights display that higher income ranges tend to have higher loan original values and smaller borrower rates. Also, higher loan original amounts have higher monthly payments, indicating that higher amounts do not have a higher number of terms. 
It is also possible to notice an increasing relationship between borrower rate and monthly loan payment, however this trend is not strong for past due loans. Moreover, past due loans displayed lower loan original amount values.
Overall, the vast majority of borrowers that have no delinquencies are employed, and homeownership  presented no influence in the loan status.