# Loan Data from Prosper
## by Ashley Muthoni


## Dataset

This dataset details data regarding various variables related to loans from the identification details of the borrowers to the various loan amounts, the status of the loan, borrower rate and other related characteristics.
This dataset can be found here (https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)

I performed selection of variables of importance through numpy and dropped the remaining columns through pandas to remain with a dataset of 23 columns across 113937 observations.


## Summary of Findings

In the exploration, monthly payment alone had a long-tailed distribution to the right which required a log transformation for better visualization. However, it had a strong correlation with the amount of money issued as loans in a fairly linear relationship that required no transformation.This relationship was further explored across employment status, the loan status and even the terms of the loan to consistently show that there were upper and lower outliers.
This is justifiable as some borrrowers who wish to complete their payments sooner despite not taking huge loans contributed larger sums of money to complete servicing of their loans regardless of whether they were complete, currently running, deliquent or in default/chargedoff. Even borrowers wtih favourable employment statuses seem to also ocassionaly face uncertainity remitting money towards their higher-priced loans. It's interesting to note that borrowers who take out lower loan amounts in the 12 month term are at risk of also being deliquent or being in default.

The main variables of interest will be brought into the explanatory presentation.
Beyond the main variables of interest, I got to understand key reasons borrowers apply for loans. Debt consolidation took precedence to indicate a likelihood of taking future loans to pay off debt. This is important to lenders who can plan accordingly to structure their loans in an attractive manner to both investors and borrowers.


## Key Insights for Presentation

For the main presentation, I want to focus on the influence of the categoric variables on the loan original amount as well as its monthly payment. I will start by introducing the loan and monthly payment variables with their transformed scales in histograms.

Afterwards, I will introduce the categoric variables. The loan status, employment status and term of loans present a clear representation of how each affects the key variables of interest.I will then include additional plots suitable for borrowers in terms of the income range they declare as well as investors who fund loans in terms of the lender yield they can expect annually from their investments. These wrap up the presentation for the Prosper loans.
