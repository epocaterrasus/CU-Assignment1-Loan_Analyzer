# CU-Assignment1-Loan_Analyzer
This is the First Assignment of the Columbia University Fintech Bootcamp

The python file can be found in this repository under the name loan_analyzer.py
The output csv file can be found in this repository under the name inexpensive_loans.csv

In this assignment we:
-Calculated the number of loans from a list, then calculated the sum of the loans cost and used both parameters to find the average loan cost value.
-Grabbed the future value and remaining months to maturity of a loan and assigned it to variables, then proceeding to calculate the loan's present value using the formula and lastly using a conditional statement to determine whether the loan was worth buying or not (pv>=cost)
-Created a function to calculate present value and then used it to calculate the present value of a new loan stored in a dictionary (requiring us to use get function)
-Created a new list of inexpensive loans and iterated through several loans contained in a list of dictionaries adding those which value was lesser than 500
-Created a csv file, wrote the header and then each row of the inexpensive loans list
