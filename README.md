
# Financial Loan Analysis - Dashboard

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiOWI3YjM1YjYtYzdjMi00ZDlkLWE0ZTgtNDk3ZDkzNTgzYTQwIiwidCI6ImZjZmQ5ODBjLWUwN2QtNDM1Ni1hMjM3LWUwYjk3Njc2NjBjNiJ9

## Problem Statement

This dashboard helps the bank understand its loan portfolio better. It provides insights into key metrics such as total loan applications, funded amounts, and amounts received from borrowers. By monitoring these metrics, the bank can identify areas for improvement, optimize loan operations, and enhance customer satisfaction. Additionally, the dashboard tracks average interest rates and debt-to-income ratios, aiding in financial risk assessment and strategic planning.

Given that the total number of loan applications and funded amounts are critical indicators of the bank's performance, continuous monitoring and analysis are essential. The dashboard also highlights good and bad loans, helping the bank focus on improving loan quality and repayment rates.


### Steps followed 

- Step 1: Load data into Power BI Desktop. The dataset is a CSV file
- Step 2 : Open Power Query Editor and, in the View tab under Data Preview, check "Column distribution," "Column quality," and "Column profile" options.
- Step 3 : Identify and handle errors and empty values, particularly in the "emp_title" column where null values are present.
- Step 4 : Calculate key metrics such as total loan applications, funded amounts, and amounts received from borrowers, excluding null values where necessary.
- Step 5 :Select a theme in the Report view under the View tab. 
- Step 6 : Add visuals to represent various metrics such as loan status, application type, and grade using the three ellipses in the Visualizations pane.
- Step 7 :Add slicers for fields like "home_ownership," "purpose," "verification_status," and "term." 
- Step 8 :Add card visuals for key metrics such as average interest rates and debt-to-income ratios, using visual level filters to exclude null values.
- Step 9 : Add a bar chart representing the number of loans by status and segregate them by state and application type.
           Although, by default, while calculating average, blank values are ignored.
- Step 10 : Use various visuals to represent different loan-related metrics (e.g., grade, sub-grade, and installment amounts).
- Step 11 : Create a calculated column to group customers into various income groups using DAX expressions.      
- Step 12 :  Create a measure to find the total count of loan applications and represent it with a card visual.       
 - Step 13 :Create a measure to calculate the percentage of loans in each status category and represent it with a card visual.
 - Step 14 : New measure was created to calculate total distance travelled by flights & a card visual was used to represent total distance.
 - Step 15 : The report was then published to Power BI Service.
 
 
![Publish_Message](https://user-images.githubusercontent.com/102996550/174094520-3a845196-97e6-4d44-8760-34a64abc3e77.jpg)

# Snapshot of Dashboard (SUMMARY)

![Screenshot (163)](https://github.com/shreedhar13/Bank_loan_analysis_powerbi/assets/153434680/d3a1c390-3c3a-4ea0-b4f2-14a229de5b74)

 
 # Report Snapshot (OVERVIEW)

 
![Screenshot (164)](https://github.com/shreedhar13/Bank_loan_analysis_powerbi/assets/153434680/7170e1f9-7d9f-4e10-bf71-1cca354f31f3)


 # Report Snapshot (DETAILS)

 
![Screenshot (165)](https://github.com/shreedhar13/Bank_loan_analysis_powerbi/assets/153434680/6de3b0aa-7812-4b47-a033-32e0d23caf15)


# Insights

A Three page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Number of Loan Applications: 38,576

- Number of Current Loans: 21,500 (55.7%)
- Number of Fully Paid Loans: 12,345 (32.0%)
- Number of Charged Off Loans: 4,731 (12.3%)

### [2] Average Metrics:

- Average Interest Rate: 14.32%
- Average Debt-to-Income Ratio: 0.12
- Average Loan Amount: $7,500

### [3] Loan Distribution by Grade:

- Grade A: 12.5%
- Grade B: 20.3%
- Grade C: 25.7%
- Grade D: 15.2%
- Grade E: 10.4%
- Grade F: 8.9%
- Grade G: 7.0%

### [4] Home Ownership:

- Rent: 45.6%
- Mortgage: 38.9%
- Own: 15.5%

### [5] Purpose of Loans:

- Debt Consolidation: 48.2%
- Credit Card: 22.7%
- Home Improvement: 12.4%
- Major Purchase: 8.3%
- Other: 8.4%


### [6] Verification Status:

- Source Verified: 60.4%
- Verified: 30.2%
- Not Verified: 9.4%

### [7] Term:

- 36 Months: 58.6%
- 60 Months: 41.4%
