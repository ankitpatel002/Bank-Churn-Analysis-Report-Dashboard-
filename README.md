# Bank-Churn-Analysis-Report-Dashboard-

Bank Churn Analysis Requirement Document.
Description: In this data we are going to learn about how to analysis of bank churn data Churn means like how many people left the bank or u can say attrition also.so; this document is only for practicing of creating reports this is only a sample data set ad sample document.
1)  Data Connection 
2)  Data Preparation 
3)  Data Modeling and Analysis 
4)  Data Visualization 
5)  Report Sharing and distribution

Data Cleaning and Preparation of data.

Check all the data types and column names.
Remove Estimated Salary column.
Make sure the column names starting character is Capital. 
Change the name of the columns.
Credit Score
Credit card Status
Activity Status
Churn Status
           5) Add Example column of (Products) Exp: Prod 1.
           6) Replace the values of Churn Status column (1 – Churned) (0- Not Churned).
           7) Replace values of Activity Status column (1 –Active) (0-Inactive).
           8) Replace values of credit card status column (1-Owned) (0- Not Owned).
           9) Add new conditional column of (Age Group) with the help of Age column in our data.
10) Similarly we can add two more conditional columns (Credit Scores) with the help of credit score column in data. And (Account Balance) with the help of Balance in our dataset.
11) Create a reference table of customer data table and change the name of the table as a (Age Groups) and keep only Age Group column in that table and Remove duplicates.
12) Add conditional column into a Age Groups table which is name ( Age Group ID).
Examples: age group id – 1,2,3,4,5,6,7
13) Similarly we have to add two more reference table which is (Account balance and credit Scores) and keep the Credit Score column and account balance column in that table.
Add conditional column into a Account balance and credit Scores table which is name ( Account Balance ID and Credit Scores ID).
Examples: Account Balance  id – 1,2,3,4,5,6

                         Creating the Measures

Create a Measure to calculate the No of Customers by using Dax.
Create a Measure to calculate the Lost Customers by using Dax.
Create a Measure to calculate the Churn Rate by using Dax.

Visuals That Are Using in Our Report
     Cards
To showing a No of Customers.
Showing a Churn Rate.
Showing Lost Customers.
     Charts 
Make a Donut Chart to showing No of Customers by Gender wise.
Make Another Donut Chart to showing No of Customers by Activity Status wise.
Make Another Donut Chart to showing No of Customers by Credit Card Status.
Make Another Donut Chart to showing No of Customers by Country.
Make Another Donut Chart to showing No of Customers by Churn Rate.
Make a line clustered bar chart to showing customers and churn rate by age group.

Make a line and stacked column chart to showing customers and churn rate by credit score.
Make line chart to showing customer lost by country.
Make a Stacked column chart to showing customers by products. 
