# Project-3
 Exploratory and Explanatory analysis of Prosper's Loan database 
# (Exploring factors of Prosper Loan Data)
## By (Olusola Samson)


## Dataset

> **The prosperLoanData dataset is a loan data from prosper which provides information about more than 100,00 loans with 81 variables realated to each loans** 
>**There are 77557 loans and 17 variables with of which most are numerical in nature and the rest are dates and categorical data.
most variables e.g credit score are ordered/ranked while Term and Loan status are categorical**
Wrangling steps involve:
>Filtering out the dataset to get the columns that will be used for the analysis
>Filling the column with the mean
>dropping rows that have null values based on borrower apr

## Summary of Findings

people collected loans ranging from \\$1,000 to\\$25,000 , which peaked at around \\$4,000, coming in second is \\$15,000 and third \\$10,000. In depth , we can see that most loans collected ranges from a $1000 to \\$10,000.**
A higher section of people's BorrowerAPR falls between 10 to 40% and a lower section go below that . In the case of the BorrowerRate a higher percent falls between the 10 to 30% range while the rest are below or higher than that. While for LenderYield a fairly decent amount fall between 0 to 10% while most fall between 10 to 30% and the rest belong to a smaller demographic Finally, for EstimatedEffectiveYield like previous analysis most fall between the 10 to 30% range and few fall between 0 to 10% while little or nothing fall between 30 to 40%.

Most loans are still in the current phase ,with those completed coming next to it,and those charged off coming in third. The rest of the observations are not really significant.
The monthly income ranges up to $11,0000 per month.
The more the loan the less Annual percentage rate put on the loan.
More people have an excellent creditscore while an average number of peopel have a fair creditscore ,and the remaining number of people have either a good or very good creditscore.
Most loans have not completed as at the moment the data was created.
Seeing the upward trend which goes like the more you earn the higher the loan you collect , which is shocking since peoplewho earn more are meant to be stable , so what's the loan for?
As expected most of the featues have a positive relationship ,the correlation of the data to each other are really high with some reaching the maximum correlation coefficient .
The amount of loans still ongoing are more than expected , people with very good or fair rating dominating the current loan status, the range of money they make about 4000 to 8000 collecting loans up to 25,0000 which is suprising considering the fact that they earn more and have a stable income.

Then we have the completed loans, the loans which have been fully paid have a creditscore of either very good or fair , people with the upper range of income occuring more in the observation ,  i had a conception thought the completed loans will have been dominated by people with excellent and very good creditscore rating .
Moving on ,we go on to the losses the defaulted and chargedoff loans. These are the loans which have been given up , now lets see the people involved. 
The lower range of loans collected have a higher distribution of fair rating (i.e those with the smaller loans are mostly fair which is understandable).
The loans that are past due are more of what we've been expecting with most coming in at good and fair, with few very-good and excellent.
 The Annual Percentage Rate (APR) for the loan go up to 40% which is a lot for 1 loan.
The interest rate for this loan go up to 35% of the original loan.
The Lender yield which is equal to the interest rate on the loan less the servicing fee also go up to 35%.
Effective yield is equal to the borrower interest rate (i) minus the servicing fee rate, (ii) minus estimated uncollected interest on charge-offs, (iii) plus estimated collected late fees go up to 30%.
Estimated return is the difference between the Estimated Effective Yield and the Estimated Loss Rate: which is the money expeceted to gain even after the loss go up to 25%
the higher the amount of the loan the lower the estimated loss meaning the loan givers are more careful when it comes to loans of high amount .
Also ,we can see that with most current loans the estimated loss(i.e the money the lenders are ready to lose) ranges from 0 to 10% .
Loans up to 15,000 have the highest estimated loss with those chargedoff and completed dominating the upper region meaning either they'v
From the multivariate exploration i deduced that lenders do actually make.

## Key Insights for Presentation
There seems to be a high distribution of loans that are current, which dominates most of the data, with those chargedoff,defaulted and completed having a decent distribution amongst the data, while those past due coming up very few. since the creditscore can be divided into 'Excellent:800-850' 'Very good:740-799', 'Good: 670-739', 'Fair: 580-669', 'Poor: 300-579' most people have a creditscore which are good,fair and very good. it is deduced that more people have an excellent creditscore while an average number of people have a fair creditscore ,and the remaining number of people have either good,fair or very good creditscore The correlation among the features is really high

Those who earn more dont really collect loans as illustrated above ,which is more popular among people with income of about 10,000 or less most loans have not paid completely as at the moment the dataset was created. Therefore the lenders are operating without profit as at that time(i.e creation of the dataset)

**There's no absolute factor to determine whether a person will pay back their loan only a possibility that the person in reference will pay back the loan.**

**Even with the fact that there's it's only a possibility that the loan will be paid ,Lender's still make up to 20% on all loans given out which is really interesting .**

**Also people with high income also get back on loan payment, suprisingly going against my line of thoughts that people with good income dont owe debts.**
