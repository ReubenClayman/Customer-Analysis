## Customer Analysis - Customer Lifetime Value with Purchase Frequency and Recency
Objective: To identify the lifetime value (LTV) of customers by calculating total spend, average purchase frequency, and recency of purchases.

Tables/Columns Used:

customers (columns: customer_id, name, email)
sales (columns: sale_id, customer_id, amount, sale_date)

Explanation:

The customer_transactions CTE aggregates each customer's total purchases, total spend, and calculates the days since their last purchase.
The customer_ltv CTE calculates additional fields like the average purchase value and customer lifetime.
CASE statement is used to segment customers into different categories based on how long they've been customers (New, Regular, Loyal).
The final result provides deep insights into customer lifetime value (LTV), purchase frequency, and recency.
