# Olist E-Commerce Sales Analysis using SQL

## Project Overview
This project analyses the Brazilian e-commerce dataset from Olist using PostgreSQL to understand sales performance, customer behaviour, payment preferences, product performance, and delivery experience.

The objective is to turn raw e-commerce data into meaningful business insights using SQL queries and data analysis techniques.

## Business Objectives
The analysis aims to answer the following questions:

- How much revenue did the business generate, and what was the average order value?
- Which months had the highest sales and order volumes?
- Which payment methods were most commonly used?
- How do delivery delays affect customer review scores?
- Which product categories and sellers contribute to sales?
- How do order status, freight charges, and delivery timelines vary?
- What data quality issues can affect the accuracy of analysis?

## Dataset
**Source:** [Olist Brazilian E-Commerce Public Dataset — Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

The dataset contains information about orders placed on the Olist marketplace, including customers, orders, order items, payments, reviews, products, sellers, geolocation, and product category translations.

The analysis uses nine related tables:

- Customers
- Orders
- Order Items
- Payments
- Reviews
- Products
- Sellers
- Geolocation
- Product Category Translation

The original dataset is not included in this repository because of its file size. Please download it from the source linked above to reproduce the analysis.

## Key Findings
The following findings were identified during the analysis:

- **Total item revenue:** Approximately R$13.6 million.
- **Average order value:** Approximately R$137.75.
- **Peak sales period:** November 2017, with approximately 7,451 orders and R$1.01 million in revenue.
- **Payment preferences:** Credit cards accounted for approximately 78% of total payment value.
- **Delivery and customer satisfaction:** Orders delivered late had an average review score of 2.57, compared with 4.29 for orders delivered on time.

These results highlight the importance of monitoring sales trends, understanding payment preferences, and improving delivery performance to support customer satisfaction.

*Note: Revenue and average order value depend on the definitions used in the SQL queries. Refer to the query logic when interpreting these metrics.*

## Business Recommendations
Based on the findings:

- Investigate delivery delays and identify opportunities to improve fulfilment performance.
- Monitor customer reviews alongside delivery performance to identify potential service issues.
- Track monthly revenue and order volumes to support sales planning.
- Monitor payment-method trends to understand customer payment preferences.
- Validate joins and aggregation logic before reporting business metrics.

## Project Structure

- `README.md` — Project overview, analysis scope, and key findings.
- `*.sql` — SQL queries used for analysis, once uploaded.

The raw dataset can be downloaded from the Kaggle source linked above.

## Conclusion

This project demonstrates how SQL and PostgreSQL can be used to analyse a relational e-commerce dataset, calculate business metrics, identify trends, and investigate relationships between delivery performance and customer satisfaction.

It also highlights the importance of data quality checks and correct aggregation when working with multiple related tables.

## Tools and Technologies

- **Database:** PostgreSQL
- **Query Language:** SQL
- **Platform:** GitHub

## SQL Concepts Used

- SELECT, WHERE, ORDER BY, and LIMIT
- Aggregate functions: COUNT, SUM, AVG, MIN, and MAX
- GROUP BY and HAVING
- INNER JOIN and LEFT JOIN
- Date and time functions
- CASE statements
- Common Table Expressions (CTEs)
- Subqueries
- COUNT(DISTINCT) for accurate counting
- Data validation and quality checks


## Author

**Ruchika Bisoi**

Aspiring Data Analyst | SQL | PostgreSQL | Python | Power BI

[GitHub](https://github.com/RuchikaBisoi) | [LinkedIn](https://www.linkedin.com/in/ruchika-bisoi/)
