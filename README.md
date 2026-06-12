# Sales Trend Analysis using SQL

## Overview

This project analyzes sales data using SQL aggregation techniques. The objective is to calculate monthly revenue and order volume, identify sales trends, and determine the top-performing months.

## Objectives

* Analyze monthly sales performance.
* Calculate total revenue generated each month.
* Count the number of orders per month.
* Identify the top 3 months with the highest sales.

## Dataset Structure

| Column Name | Description             |
| ----------- | ----------------------- |
| order_id    | Unique order identifier |
| order_date  | Date of order           |
| amount      | Sales amount            |
| product_id  | Product identifier      |

## SQL Concepts Used

* SELECT
* SUM()
* COUNT(DISTINCT)
* GROUP BY
* ORDER BY
* EXTRACT()
* LIMIT

## Queries Performed

### Monthly Sales Trend Analysis
![Monthly Sales Trend Analysis](Monthly%20Sales%20Trend%20Analysis.png)

* Calculated monthly revenue.
* Calculated monthly order volume.
* Sorted results chronologically.

### Top 3 Months by Sales
![Top 3 Months by Sales Revenue](Top%203%20Months%20by%20Sales%20Revenue.png)

* Ranked months based on total revenue.
* Retrieved the top-performing sales months.

## Results

| Year | Month | Revenue | Orders |
| ---- | ----- | ------- | ------ |
| 2024 | 1     | 1200    | 2      |
| 2024 | 2     | 1400    | 2      |
| 2024 | 3     | 2100    | 2      |
| 2024 | 4     | 2500    | 2      |

## Key Findings

* Revenue increased consistently from January to April.
* April recorded the highest sales revenue.
* Sales performance showed a positive growth trend.

## Tools Used

* PostgreSQL
* SQL

## Author

samruddhi Patil
