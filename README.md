# ecommerce-sales-sql-analysis
SQL-based portfolio project analyzing 50K+ e-commerce transactions to uncover customer behavior, sales trends, and business insights. Features advanced queries, window functions, CTEs, and performance metrics designed to demonstrate real-world data analysis skills.


# E-Commerce Sales & Customer Insights using SQL

## Project Overview
This project analyzes over 50,000 e-commerce transactions to extract insights on sales trends, customer behavior, and product performance. It demonstrates practical SQL skills including joins, aggregations, CTEs, window functions, and business-focused query design.

---

## Objectives
- Build and query a relational database simulating real-world e-commerce operations.
- Uncover key sales, customer, and operational insights using SQL.
- Showcase advanced SQL proficiency and business storytelling.

---

## Dataset Structure
**Tables**
1. **Customers** – customer_id, name, region, signup_date  
2. **Products** – product_id, product_name, category, unit_price  
3. **Orders** – order_id, customer_id, order_date, total_amount, payment_method  
4. **Order_Details** – order_detail_id, order_id, product_id, quantity, unit_price  
5. **Returns** – return_id, order_id, product_id, return_reason, return_date  

*(Synthetic dataset designed to mimic real-world retail data.)*

---

## Tech Stack
- **SQL:** PostgreSQL / MySQL  
- **Database Tool:** pgAdmin / DBeaver  
- **Optional:** Python for data loading or Tableau for visualization

---

## Key SQL Concepts Demonstrated
- Complex **JOINs** across multiple tables  
- **Aggregations** (SUM, COUNT, AVG, etc.)  
- **CTEs** (Common Table Expressions)  
- **Window Functions** (RANK, DENSE_RANK, LAG, LEAD)  
- **Subqueries** and **CASE** logic  
- **Views** for recurring business KPIs

---

## Business Questions Answered
1. What are the top 10 products by total revenue?  
2. How do monthly revenue trends compare year over year?  
3. Which regions have the highest customer lifetime value (LTV)?  
4. What is the average order value by payment method?  
5. Which products or categories have the highest return rates?

---

## Insights Summary
- Identified seasonal sales peaks and slow periods.  
- Found that returning customers drive X% of total revenue.  
- Uncovered top-performing product categories and underperformers.  
- Highlighted regions with high potential for marketing focus.

---

##File Structure
https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data

---

## Optional Dashboard


---

## Future Enhancements
- Add Python ETL pipeline for automated loading and transformation.  
- Integrate external data (e.g., marketing spend or ad performance).  
- Deploy dashboard version online for interactive exploration.

---

## Author
**Galen Pike**  
Data Analyst | SQL • Python • Tableau  
[LinkedIn Profile](#) | [Portfolio](3)

---


