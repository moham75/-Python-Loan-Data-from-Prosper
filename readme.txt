Dataset : Loan_Data_From_Prosper

data overview :

This data set contains 113,937 loans with 81 variables on each
loan

Main Findings :

The observations that i have decided to work with are 

1 - Term
2 - LoanStatus
3 - BorrowerAPR
4 - EstimatedReturn
5 - Occupation
6 - EmploymentStatus
7 - LoanOriginalAmount
8 - StatedMonthlyIncome


but the main focus was on 

1 - LoanSatus
2 - BorrowerAPR
3 - LoanOriginalAmount

i did search for codes to help me in the wrangling process 
for instance the code i used to remove all columns but for some certain columns 

So i started off with 
A - Univariate Exploration
     So i had to plot several figures in order to get more insights about the data
             1 - Loan Status 
                 * The figure shows the highest number is Current which is above than 50K
             2 - Employment Status
                 * based on the figure, the majority of people who had got loans already employed
                 * which means they should be able to pay for their loans but it'll be based on the monthly income
             3 - Distribution Loan Original Amount
                 * based on the figure above, the interpretation here that the majority of people's loans is from 4000 to 150000
             4 - Distribution Borrower APR
                 * i had the maximize the number of bins so i could get a clear look at the distribution
                 * and as it seems the highest number or peak of the distribution is approximately 0.37 to 0.38
                 * and the distribution left skewed 


B - Bivariate Exploration
     So the next step is to find a correlation between observations however i didn't do much in this part cause of the observations that i      have decided to work
             1 - Loan Status  vs. Employment Status
                 * as it seems from the figure, the Current Loan Status has the highest number of employed people
             2 - Loan Status  vs. Borrower APR
                 * Completed loan alongside with Current loan have the lowest Borrow APR
                 * Charged off considered the have the highest Borrow APR which is the Median


C - Multivariate Exploration
    in this step i had to find a correlation between 3 observations and then communicate my findings
         
             1 - Loan Status vs. Borrower APR vs. Employment Status
                 * The higheset value of BorrowAPR Not Empolyed
                 * The lowest value of BorrowAPR Full Time



So Regarding the first questions which is 
     What factors affect a loan’s outcome status?
           the answer would Borrower APR and Employment Status

     What affects the borrower’s APR or interest rate?
           the factor which effects the Borrower's APR is 
           1- LoanStatus 
           2- EmploymentStatus

so the final Conclusion:

Regarding to Univariate Exploration:

i created several figures cause i wanted to see the insights from almost every single observation that i got so we could say

1 - The highest loan status is current which is above 50k

2 - The majority of people who got loans are already working

3 - the peak of BorrowAPR is 0.37 to 0.38

4 - People's lonas are between 4,000 to 15,000

Regarding to Bivariate Analysis

i have created two plots to look at the correlation between of them

1 - The current loan status, it has the highest number of people who are working or employed

2 - Completed and current loan have the lowest borrowAPR

3 - Chargedoff have the highest borrowAPR

Regarding to Multivariate Analysis

i was trying to create more than one chart but i couldn't think of a certain corration that i could look for then plot it cause of the columns so the interpretations are

1- The higheset value of BorrowAPR Not Empolyed

2- The lowest value of BorrowAPR Full Time