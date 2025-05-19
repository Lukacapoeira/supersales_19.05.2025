# supersales_19.05.2025
-- 🧠 Goal: For each product category, find the top 3 products 
-- with the highest total quantity sold, but only from orders that had a discount (position_discount > 0).

-- 1️⃣ CTE: discount_table
-- We aggregate the quantity sold and the total revenue after discount 
-- for each product within its category, considering only discounted orders.
