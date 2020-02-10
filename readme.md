# Prosper Loan Exploration

## Dataset

This document explores a dataset containing 81 attributes for 113937 borrowing records, including borrower rate, credit score range, employment status, and other borrower information. 


## Summary of Findings

In the exploration, I found that there was a strong relationship between the borrower rate and average credit score. The relationship is
approximately negative linear between borrower rate and average credit score, but the decreasing trend of borrower rate seems getting slower when the average credit score getting higher.
I also found a interesting relationship between borrower rate and debt to income ratio. By plotting the scatter plot directly between borrower rate and debt to income ratio, I couldn't see a clear relationship, which suprised me a lot. So I added a new variable "CreditGrade" and the plots showed a positive linear relationship between borrower rate and debt to income ratio in each credit grade category.
And not suprisingly, I noticed that higher credit grade and higher prosper score lead to a lower borrower rate as well.
In addtion, I saw homeowners are more like to have higher average credit score and lower borrower rate, employed borrowers, especially full-time employed borrowers, are likely to have higher credit score and lower borrower rate as well. 
Furthermore, I found the borrower rate was getting more and more sensitive to the change of credit score as year went by. This is reasonable for an economy that was steadily getting stable and growing in the US since the financial crisis from 2007.
Finally, I noticed the borrower rate and the average credit score are more centralized when the term is longer. I think it makes sense, since longterm interest rates are usually more stable than short term interest rates.

Outside of the main variables of interest, I found that borrowers who are employed or full-time employed are often homeowners.


## Key Insights for Presentation

For the presentation, I focus on the relationship between borrower rate and other variables. I start by introducing the
distribution of the borrower rate and the average credit score which I think has the strongest relationship with the borrower rate.
Afterwards, I introduce the relationship between the borrower rate and the average credit score, credit grade, and prosper score.
And then I explain the relatively strong relationship between borrower rate and debt to income ratio by separating records by credit grade.
Finally, I use heatmap to show the relationship between borrower rate between other categorical variables, including Is BorrowerHomeowner, employment status, year, and term and explain the distribution of the records and the attributes of each category.