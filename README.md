Download Link: https://assignmentchef.com/product/solved-loan-calculator
<br>
5/5 - (1 vote)

This program is a simple loan calculator that processes either Auto Loans or Mortgages. Both Auto Loans and Mortgages are types of Loans. All loans track: l) interest rate, loan period in years, and the loan amount in dollars and cents. Create classes to store information for both type of loans.



The program should prompt the user to select if the user wants to have an auto loan or a mortgage loan processed. If the user selects an auto loan, the program should prompt loan amount and period in years. If the user selects a mortgage loan, the program should prompt for loan amount, period in years and the user’s FICO credit score.

Any mortgage loan applications with a FICO score less than 400 should be rejected.

The program should then tell the user what the total payment for the loan would be. The program should the prompt to do another loan calculation and continue to do so till the user presses X for exiting the program

Instructions &amp; Requirements

Rename Program.cs to LoanManager.cs. Name your other classes appropriately.

Import the provided Loan.cs class provide and add it to your project.

You are allowed to change the namespace name (only).

No other change to Loan.cs is allowed.

Create additional classes to model auto loans and mortgage loans.

Any class modelling a loan must inherit the Loan class.

Create any additional classes as needed.

Model this application based on the previous classwork that you have done.

Numeric Formats

Interest rate: store 4.5% as 4.5, not .45. Conversion to .45 takes place in formula later.

Loan years: store as whole numbers without decimals. Will be converted to months later.

Loan amount: store with decimal numbers

Numeric Formats

Interest rate: store 4.5% as 4.5, not .45. Conversion to .45 takes place in formula later.

Loan years: store as whole numbers without decimals. Will be converted to months later.

Loan amount: store with decimal numbers.

Calculation of Auto Loans

The interest rates for auto loans are constant at 4.5% annually.

Monthly Interest Rate = Annual Interest Rate / 1200

Monthly Payment = Loan Amount * Monthly Interest Rate / (l –

(Math.Pow(l / (l + Monthly Interest Rate), Num of Years * 12)));

Total Payment Monthly Payment * 12 * Number of Years

Calculation of Mortgage Loans

Mortgage Loans require a FICO score. No one should qualify for a mortgage with a FICO score

under 400.

FICO Score

400 &lt; interest rate &lt; 700

700

Annual Interest Rate

n/a – No Loan Granted

6.55 %

4.05 %

Monthly Interest Rate — Annual Interest Rate / 1200

Monthly Payment — Loan Amount * Monthly Interest Rate / (l –

(Math.Pow(l / (l + Monthly Interest Rate), Num of Years * 12)));