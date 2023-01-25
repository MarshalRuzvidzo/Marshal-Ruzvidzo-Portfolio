(Prosper Loan Data Exploration)
by Marshal Ruzvidzo
Dataset
The prosper loan dataset consisted of 113937 rows and 81 variables. The main variables that were explored included:

LoanKey
Term
LoanStatus
BorrowerAPR
ListingCategory (numeric)
CreditScoreRangeUpper
CreditScoreRangeLower
Occupation
LoanOriginalAmount
IncomeRange
IsBorrowerHomeowner
StatedMonthlyIncome
IncomeVerifiable
DelinquenciesLast7Years
DebtToIncomeRatio The link to the dataset can be found here and its documentation is available here
Summary of Findings
In the exploration process the main variable of interest was BorrowerAPR, which is the total annual amount paid towards the loan. In the exploration process it was found that there is a weak positve correlation coefficient between LoanOriginalAmount and Term. This is expected because the larger the amount the longer it takes to pay back. Also there is weak positve correlation between LoanOriginalAmount and StatedMOnthlyIncome. Lastly there medium negative correlation between CreditScoreUppper and BorrowerAPR. This means if a person has a higher credit score it meant that his/her borrower APR was lower because of less risk to default. This prompted further questions such as how does the StatedMonthlyIncome vary with Loarn Original Amount and also further questions on the variability of BorrowerAPR. Furthermore, the dataset showed that people who borrowed Loans with longer terms had higher DebtToIncome ratio.This makes sense because if the period to pay back the loan is short and the borrower has a higher debt to income ratio it means that there is a higher risk of defaulting the loan due to other loan commitments. So for one to qualify for a short term loan his/her debt to income ratio should be lower to reduce the risk of defaulting. Loans that has terms of 12 and 36 months had the highest LoanOriginalAmount.Hence it can be concluded that the higher the term the more money borrowers can borrow from Prosper. Borrowers with 60 months term, their borrowing amount was populated around 15K. Also another interesting feature found from the dataset is that the people who borrowed from Prosper loans were not high income earners with a typical income range of USD 25K-50K, which is medium income range. All the summary findings here were also part of the exploration presentation slide deck accompanied with the visualizations.

Key Insights for Presentation
The presentation is focused on the main variables variables of interest which are borrower APR and Debt to income ratio. Relationship betweeen those two variables and other variables such as LoanOrginalAMount, Term, Listed Category, CreditScoreRangeUpper, StatedMonthlyInncome were investigated.

.
