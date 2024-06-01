# Cohorts Retention and Churn analysis using SQL and Excel
## Project description
This project provides cohort analysis of subscriptions from a weekly retention standpoint, according to the following task:

Provide weekly subscriptions data that shows how many subscribers started their subscription in a particular week and how many remain active in the following 6 weeks. 
Your end result should show weekly retention cohorts for each week of data available in the dataset and their retention from week 0 to week 6.

## Dataset description
Use subscriptions table hosted in BigQuery Project to answer this question. The table contains the following columns:



| Field name  | Type | Mode |
| ------------- | ------------- |---------------|
| user_pseudo_id | STRING  | NULLABLE |
| category  | STRING | NULLABLE |
| country| STRING | NULLABLE |
| subscription_start| DATE | NULLABLE |
| subscription_end | DATE | NULLABLE |

		
## Steps overview
**Step 1:**  Creating SQL query to retrieve weekly cohorts and number of retained customers from week 0 to week 6 for each cohort 

The code can be accessed here: [1. SQL Retained](https://github.com/PatrycjaDanilczuk/Cohort-Renention-Churn-analysis-using-SQL-and-Excel/blob/main/1.%20SQL%20Retained), the result table can be found in the uploaded Excel file, tab name: 1. SQL Retained.

**Step 2:**  Calculating retention rate in SQL

The code can be accessed here: [2. SQL Retention rate](https://github.com/PatrycjaDanilczuk/Cohort-Renention-Churn-analysis-using-SQL-and-Excel/blob/main/2.%20SQL%20Retention%20rate), the result table can be found in the uploaded Excel file, tab name: 2. SQL Retention rate.

**Step 3:**  Creating SQL query to retrieve weekly cohorts and number of retained customers from week 0 to week 6 for each cohort by category (desktop, mobile, tablet)

The code can be accessed here: [3. SQL Retained by category](https://github.com/PatrycjaDanilczuk/Cohort-Renention-Churn-analysis-using-SQL-and-Excel/blob/main/3.%20SQL%20Retained%20by%20category), the result table can be found in the uploaded Excel file, tab name: 3. SQL Retained by category.

**Step 4:** Calculating retention rate by category in SQL

The code can be accessed here: [4. SQL Retention by category](https://github.com/PatrycjaDanilczuk/Cohort-Renention-Churn-analysis-using-SQL-and-Excel/blob/main/4.%20SQL%20Retention%20by%20category), the result table can be found in the uploaded Excel file, tab name: 4. SQL Retention by category.

**Step 5:** Uploading result table to Excel for further analysis

**Step 6:** Providing analysis and actionable insights

The results of the analysis have been provided in the uploaded Excel file: [Cohort_retention_churn_analysis](https://github.com/PatrycjaDanilczuk/Cohort-Renention-Churn-analysis-using-SQL-and-Excel/blob/main/Cohort_retention_churn_analysis.xlsx) in Overview tab.
