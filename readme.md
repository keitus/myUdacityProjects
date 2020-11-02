# Prosper Loan Dataset 
## by : Abubakar Keita


## Dataset
 
> This data set contains 113,937 loans with 81 variables on eachloan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. My Exploration will focus on 11 variables.

## Summary of Findings

> In this exploration, I found out that there is a strong relationship between the borrower's APR of Prosper loan and prosperRating with modifying effects from the the originalLoanAmount (Amount), debt-to-income ratio, listingCategory, borrowerState and borrowerRate (interest rate). Based on borrower's State, California got the highest beficiaries of prosper loan listing, however, DC (District of Cloumbia) got the higest average amount of loan. I also found out that priority were given to borrowers who were employed and  most of the loan listed were taking for debt consolidation- 58308 counts. Below 5k, we have APR greater than 0.20 and above 15k, the APR is below 0.20. The two variables are negatively correlated based on the plot. One intersting interaction I found is the negative correaltion between the loan amount and borrower's APR. Most importantly, I found out borrowers with good prosper rating  got the lowest the borrower APR. This signifies a strong correlation between them. Finally, most of borrowers with low debt-to-income ratio were able to complete their loans. 

## Key Insights for Presentation

> For my presentation, I focused on features that have strong and undisputable relationship with borrower's APRs of the Propser loan and disregarded those that partially influence my variable of interest. I commence by defining borrower's APR (annaul percentage rate) variable, followed by using univariate plots to explore the partterns of each selected variables. I used hitogram to explore the distribution of borrower's APR and loan amount, barplot for prosper rating since it ordinal categorical variable. I use scatter plot for for each continuous variables , borrowerRate, debt-to-income ratio to clear illustrate their relationship with borrower's APR. Lastly, with categorical variable- prosper rating, I use color encoding to ensure the difference between the plots.


