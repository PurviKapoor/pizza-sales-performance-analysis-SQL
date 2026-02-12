# Pizza-Sales-Performance-Analysis-SQL

## Project Overview
This project analyzes sales data of a restaurant, using SQL to uncover business insights related to revenue, customer demand, product performance, and operational trends.
The objective is to transform raw transactional data into actionable insights that can help restaurant management optimize menu strategy, pricing, and daily operations.

Key goals of this project:
1. Understand overall sales performance
2. Identify top-performing pizzas and categories
3. Analyze ordering patterns by size, category, and time
4. Measure revenue contribution across products
5. Support data-driven business decisions

## Dataset & Schema
The database consists of four core tables:
  1. pizzas – pizza_id, size, price, pizza_type_id
  2. pizza_types – pizza_type_id, name, category, ingredients
  3. orders – order_id, order_date, order_time
  4. order_details – order_details_id, order_id, pizza_id, quantity

These tables were joined using primary–foreign key relationships to create a complete transactional view of sales.

## Key Insights
🔹 Revenue & Orders: 
  1. 21,350 total orders were placed.
  2. Total revenue generated: $817,860+
  3. Revenue shows consistent accumulation over time, indicating stable demand.

🔹 Customer Behavior:
  1. Large size pizzas are the most frequently ordered.
  2. Peak ordering hours are during midday and evening, suggesting lunch and dinner rush periods.

🔹 Product Performance:
  1. The highest priced pizza is The Greek Pizza ($35.95).
  2. Top pizzas by revenue include:
      The Thai Chicken Pizza
      The Barbecue Chicken Pizza
      The California Chicken Pizza
  3. Classic category contributes the largest share of total revenue (~27%), followed closely by Supreme, Chicken, and Veggie.

## Business Recommendations
**1. Menu Optimization:**
  
    Promote top-performing pizzas (Thai Chicken, BBQ Chicken) using combo offers or featured sections on the menu.
    
    Consider introducing premium variants in the Classic category since it drives the highest revenue.

**2. Size Strategy:**

     Since Large pizzas dominate orders, bundle Large pizzas with drinks or sides to increase average order value.

**3. Operational Staffing:**

     Increase staff availability during peak hours (afternoons and evenings) to reduce wait times and improve customer experience.

**4. Category Marketing:**

     Veggie and Supreme categories have growth potential, targeted promotions could balance demand across categories.

**5. Revenue Growth:**

    Use cumulative revenue trends to forecast busy days and prepare inventory accordingly.
