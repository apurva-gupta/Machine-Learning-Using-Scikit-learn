
Decision Trees and Random Forest Using Scikit Learn

Dataset: LendingClub.com. Lending Club connects people who need money (borrowers) with people who have money (investors).Create a model to predict that which profile of people show a high probability of paying the money back.

We will use lending data from 2007-2010 and be trying to classify and predict whether or not the borrower paid back their loan in full.

Data : here

Here are what the columns represent:

1. credit.policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
purpose: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other")

2. int.rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates

3. installment: The monthly installments owed by the borrower if the loan is funded

4. log.annual.inc: The natural log of the self-reported annual income of the borrower

5. dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income)

6. fico: The FICO credit score of the borrower

7. days.with.cr.line: The number of days the borrower has had a credit line

8. revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle)

9. revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available)

10. inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months

11. delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years

12. pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments)
