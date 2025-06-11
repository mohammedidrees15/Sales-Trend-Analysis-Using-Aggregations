# Sales-Trend-Analysis-Using-Aggregations
Task 6
Step-by-step summary:
1. Created a table called online_sales with columns for order ID, order date, product ID, and amount.

2. Inserted sample data into the table to represent online sales across multiple months in 2024.

3. Created a view named sales_monthly that:

4. Extracts the year and month from the order date,

5. Aggregates sales data to calculate total revenue (SUM(amount)) and total order count (COUNT(DISTINCT order_id)) for each month.

6. Queried the view to retrieve monthly sales trends with revenue and order volume.

7. Filtered results to display only sales data from the year 2024.
