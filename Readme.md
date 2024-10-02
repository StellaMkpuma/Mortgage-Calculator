## Project Title
Mortgage Repayment Calculator

##### Description
This project is a Streamlit web application that helps users calculate their monthly mortgage payments, total payments, and total interest based on the home value, deposit, interest rate, and loan term.

##### Features
* Input Fields:
* Home Value: The total cost of the home.
* Deposit: The upfront amount paid towards the home.
* Interest Rate: The annual percentage interest on the mortgage loan.
* Loan Term: The total duration of the loan in years.
* Output Metrics:
* Monthly Repayment: The amount to be paid each month.
* Total Repayment: The total amount paid over the loan term.
* Total Interest: The total interest paid over the loan term.

  
##### Payment Schedule:
* A detailed table showing the breakdown of each payment into principal and interest, as well as the remaining loan balance.
##### Visual Chart:
* A line chart showing how the remaining loan balance decreases over time.

  
##### How to Run
1.	Install the required dependencies from the requirements.txt.
2.	Run the Streamlit app using the following command: streamlit run mortgage_calculator.py
3.	Enter the required inputs (home value, deposit, interest rate, and loan term) to get the repayment breakdown.


##### Technologies Used
•	Streamlit: For building the interactive user interface.
•	Pandas: For handling the data related to the loan payment schedule.
•	Matplotlib: For plotting the repayment chart.


##### Sample Usage
1.	Input a home value of $500,000 with a $100,000 deposit.
2.	Set the interest rate to 5.5% and a loan term of 30 years.
3.	The app will calculate and display the monthly repayments, total repayments, and total interest, as well as show a chart of the remaining balance over time.
