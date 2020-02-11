# CS-Training-Loan-Defaulter-Classification-Analysis

This dataset has been taken from Kaggle, and is about the loan defaulter or not.

This is a Machine Learning Classification problem. Here we will predict whether the person asking for loan will default or not, with the use of certain independent features like RevolvingUtilizationOfUnsecuredLines, age, DebtRatio, MonthlyIncome, NumberOfOpenCreditLinesAndLoans, NumberRealEstateLoansOrLines and NumberOfDependents.

We will first start with data cleaning and will proceed with Exploratory Data Analysis. Then we will build stats model and see accuracy. 
We will also use oversampling technique for handling imbalanced data. Then, will proceed with ML Random Forest Classifier for model building. We will tune the Hyper parameters to achieve the best accuracy.

Finally, will score the data, i.e. use our model to predict on unseen data and based on optimum threshold will recommend whether the Loan application should be accepted or rejected.

RevolvingUtilizationOfUnsecuredLines - Total balance on credit cards and personal lines of credit except real estate and no installment debt like car loans, divided by the sum of credit limits.
age - Age of borrower in years
NumberOfTime30-59DaysPastDueNotWorse - Number of times borrower has been 30-59 days past due but no worse in the last 2 years.
DebtRatio - Monthly debt payments, alimony,living costs divided by monthy gross income.
MonthlyIncome - Monthly income.
NumberOfOpenCreditLinesAndLoans - Number of Open loans (installment like car loan or mortgage) and Lines of credit (e.g. credit cards).
NumberOfTimes90DaysLate - Number of times borrower has been 90 days or more past due.
NumberRealEstateLoansOrLines - Number of mortgage and real estate loans including home equity lines of credit.
NumberOfTime60-89DaysPastDueNotWorse - Number of times borrower has been 60-89 days past due but no worse in the last 2 years.
NumberOfDependents - Number of dependents in family excluding themselves (spouse, children etc.)
