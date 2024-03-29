# Ad-Hoc-Insights-of-AtliQ-Hardware
---

## Problem Statement:
---
Atliq Hardware (imaginary company) is one of the leading computer hardware producers in India and well expanded in other countries too. However, the management noticed that they did not get enough insights to make quick and smart data-informed decisions. So that find out the insights from the given database.

## Data Source:
---
Data Source
we used one database, and that database contains some tables which are explored below.

Extracted CSV file from the database.[File](https://github.com/arun10ak/Ad-Hoc-Insights-of-AtliQ-Hardware/tree/main/Dataset)
- ### gdb0041
  
    - **dim_customer** 
    - **dim_product** 
    - **dim_market** 
    - **fact_sales_monthly** 
    - **fact_forecast_monthly** 
    - **fact_freight_cost** 
    - **fact_gross_price** 
    - **fact_manufacturing_cost** 
    - **fact_pre_invoice_deduction** 
    - **fact_post_invoice_deduction**

### Depth overview of the above table using [Metadata File](https://github.com/arun10ak/Ad-Hoc-Insights-of-AtliQ-Hardware/blob/main/AtliQ%20Harwar%20-Metadata.txt)

## The below image shows the relationships among the tables.

![Data Modelling](https://github.com/arun10ak/Ad-Hoc-Insights-of-AtliQ-Hardware/assets/117892039/ed0d5224-a655-48cd-8af9-cf30ab870787)

## Task:
---
- Use MySQL database for storing the records.
- Uses Advanced SQL concepts like Joins, Subquery, CTEs, and Window functions to write complex queries to find insight from the records.
- For automation use advanced stuff like Stored Procedures and Views.

## Ad-Hoc question and answer with query and CSV file generated for the  questions as mentioned below.
---

- **Ad Hoc** [Question](https://github.com/arun10ak/SQL-Ad-Hoc-Insights-AtliQ-Hardware/blob/main/AtliQ%20Hardware%20SQL%20Insights%20Questions.pdf)
- **Retrieved** [Query](https://github.com/arun10ak/Ad-Hoc-Insights-of-AtliQ-Hardware-SQL-/tree/main/Retrieved%20Query)
- **Retrieved** [CSV](https://github.com/arun10ak/Ad-Hoc-Insights-of-AtliQ-Hardware-SQL-/tree/main/Retrieved%20CSV)
- **Solution** [File](https://github.com/arun10ak/Ad-Hoc-Insights-of-AtliQ-Hardware-SQL/blob/main/SQL%20AD-HOC%20Solution.pdf)

## Major Insights: 
---
- Croma operated only in the Indian market.
- Croma India sales increased by 180 % in the fiscal year 2021.
- The percentage of unique product increase in 2021 vs. 2020 is 36.33%.
- Accessories and Networking segments had the highest (34) and lowest (3) increase in unique products, respectively, in 2021 vs 2020.
- AQ HOME Allin1 Gen 2 and AQ Master Wired x1 Ms had the highest and lowest manufacturing costs, respectively, among all products.
- The Top 5 customers who received an average high pre-invoice discount percentage for the fiscal year 2021 and in India are, in descending order, Flipkart, Viveks, Ezone, Croma, and Amazon.
- In FY 2020, Q1 (Sep-Nov 2019) and Q3 had the maximum and minimum sold quantity of products, respectively.
- For FY 2021, the top 3 products in the N&S, P&A, and PC divisions were pen drives, mouse, and personal laptops, respectively.



