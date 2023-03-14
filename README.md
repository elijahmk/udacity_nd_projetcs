# Prosper Loan Data Exploration
## by Elie Kibwe MWALINDOMBA


## Dataset

> For this program, I chose to use the Prosper loan dataset which contains 113,937 loans (rows) with 81 variables on each loan including the borrower's rate, current loan status, loan amount, borrower's income, and others. In the preliminary processing of the data, I removed columns that were not important to me for analysis to make the dataset more manageable. I also changed the data types to datetime or categorical as needed and made the variables ordered categorical data types.

## Summary of Findings

> At the outset, I highlighted the loan statuses, as a way to get an overall view of the distribution of the main question in our data. Then I made a histogram of the loan amounts that I transformed into a logarithmic scale because in its origin it was asymmetrical. The data appeared bimodal after the logarithmic transformation. There are peaks at the loan amounts of 4,000, 10,000, and 15,000.

> I started by ploting a correlation matrice on the numeric and categoric variables to determine variables that most impact each other. Then a made a scatter plot of relation between 2 important variable. The scatter plot appears to show some negative relationship between the initial loan amount and the borrower's interest rate. As the initial loan amount increases, the interest rate tends to decrease. It is surprising to see on the heat map above that the strongest correlation was a negative relationship between borrower interest rates and initial loan amount while there was not really a strong correlation between the numerical variables.

> I continued with a grid of box plots to get an overview of the influence of categorical variables on borrower interest rates and loan amounts. We see from these graphs that the "Cosmetic intervention" category has a high average interest rate followed by household expenses. We also see a relationship with a higher interest rate for the "Not employed" category and for the "1-24,999" category. Debt consolidation and adopting a child seem to represent the highest loan amounts, and the more money people earn, the higher the loan seems to be.

> Surprisingly, but not really mystical, those employed full time have the highest rate of default. The highest loan amounts are concentrated in debt consolidation and business and the higher is the income, the higher the loan appears to be. Completed and current loans are dominated by the "home improvement" category, which is the most frequently distributed loan, despite employment status.

> Looking in details at how the loan amount and interest rate affect the final outcome of the loan, I discover that cancelled loans tend to have lower amounts and lower interest rates. Certainly because they don't have much impact on the investor. Through this presentation, it can be seen that delinquent loans tend to have a greater difference in loan amount and loan interest rate.

## Key Insights for Presentation

> It was very interesting to observe that the average loan amount for the delinquent or late data frame is lower than for the data frame as a whole, but the interest rate for these loans is 0.04 higher. Elements that most seemed to affect a loan's outcome was the amount of money borrowed and the interest rate of the loan. Higher interest, high value loans seems to be more likely to be past due. Those with jobs have the highest spread in the data, which makes sense since I assume that those with jobs are more likely to apply for and receive loans. Employed individuals had the highest spread in the data.

> In the Listing category provided, Debt consolidation and business seem to account for the highest loan amounts and the more money people made, the higher the loan appears to be. Also, the larger the loan is, the greater the chance of staying current on payments.