# Employee_Reimbursement_Report_PowerBI

### Dashboard Link : https://app.powerbi.com/groups/me/reports/5aada665-3933-435a-b3a6-abb7295884b7/ReportSection?experience=power-bi

## Problem Statement

Import the data and open the Power Query
The expense type column has some spelling and punctuation errors, correct them
Project names are not uniform, make it uniform.
The Currency column has some missing values, based on the amount, create a new custom column.
Condition: amount >= 1000, = INR; amount < 1000, = USD; else = EURO
Formula: (if [Currency] = null and [Amount] >= 1000 then "INR" else if [Currency] = null and [Amount] < 1000 then "USD" else [Currency] )
Normalize the amount column into INR based on the currency column.
Create a measure to calculate the sum of reimbursed amount in INR.
Use the calculate function and check the total reimbursed amount for Project_B
Create a measure to check the count of declined requests.
Create a slicer visual for the Project and employee
Create a bar chart for employees and reimbursement amount.
Create a pie chart for Project vs reimbursement amount


### Steps followed 

## Data Cleaning: Meticulously handled null values, corrected spelling and punctuation errors, and standardized project names. Ensured a pristine dataset ready for analysis!

## Data Transformation: Implemented a custom rule to fill missing currency values, converted USD & EURO to INR, and crafted a dynamic measure to calculate total reimbursed amounts. Delved deeper to derive insights on Project_B and tracked declined requests.

## Dashboard Creation: Crafted an interactive experience with a slicer visual for projects and employees. Visualized employee reimbursement amounts through a compelling bar chart and presented a clear overview of project vs. reimbursement amounts with a pie chart.

![Capture2](https://github.com/subhadipchatterjee2023/Employee_Reimbursement_Report_PowerBI/assets/128350160/2568c620-77f0-49ac-9f6a-baaa9867eeb9)

