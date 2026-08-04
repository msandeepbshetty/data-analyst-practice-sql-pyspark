# SQL Practice for Data Analysts

This folder contains SQL practice exercises designed for learners preparing for Data Analyst roles. The examples focus on real analytics tasks such as joins, aggregations, grouping, and reporting queries commonly used in business data environments.

## File Format Notice
The SQL practice file is provided in HTML format. This makes it easy to open directly in any web browser without requiring Databricks or a SQL client. You can view the queries, results, and explanations immediately.

## What’s Included

### Customer Revenue Query
Examples include queries that calculate total sales per customer using joins and aggregations. For instance, the notebook demonstrates how to join transaction and customer tables and compute total revenue:

> “SELECT t.customerID, c.first_name, c.last_name, SUM(t.totalPrice) AS total_revenue…” 

This helps learners understand how SQL handles grouping, ordering, and combining data from multiple tables.

### Core SQL Concepts Covered
- Select statements  
- Joins between related tables  
- Aggregations using SUM  
- Grouping and ordering  
- Practical reporting queries  
- Realistic sample datasets

## Purpose
These SQL exercises help Data Analyst learners build confidence with foundational query patterns used in analytics, reporting, and interview assessments.

## How to Use
Open the HTML file in your browser to explore the queries and outputs. You can copy the SQL into Databricks, Snowflake, BigQuery, or any SQL environment to run and modify the examples.

## License
This content is provided for learning and practice. You may reuse the examples with attribution.
