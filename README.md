# Customer Shopping Behavior Analysis

![Dashboard](<img width="1348" height="757" alt="Dashboard" src="https://github.com/user-attachments/assets/4fa4fd4b-1ce1-4bcc-bfd6-a85c6b6dbe4e" />
)

An end-to-end data analytics project that analyzes 3,900 customer transactions to understand what drives revenue, discount usage, and subscription value.

## Project Workflow
1. **Python (Jupyter Notebook):** Data cleaning with pandas: missing review ratings filled using the category average, column names standardized, customer age groups and purchase-frequency features created, redundant columns dropped. Data loaded into PostgreSQL with SQLAlchemy.
2. **PostgreSQL:** 10 business queries using aggregations, subqueries, CTEs, CASE statements, and window functions.
3. **Power BI:** An interactive dashboard with KPI cards, category and age-group breakdowns, and slicers for subscription status, gender, category, and shipping type.

## Business Questions Answered
- Revenue by gender
- Discount users who still spend above the average purchase amount
- Top 5 products by average review rating
- Standard vs. Express shipping: average spend
- Subscribers vs. non-subscribers: customers, revenue, and average spend
- Top 5 products by share of discounted purchases
- Customer segmentation: New, Returning, and Loyal
- Top 3 products within each category
- Whether repeat buyers (more than 5 previous purchases) are more likely to subscribe
- Revenue contribution by age group

## Key Insights
Total revenue: $233,081 | Average purchase: $59.76 | Average review rating: 3.75

- **Gender:** Male customers generate 68% of revenue ($157.9K vs $75.2K), driven by customer count (2,652 vs 1,248). Average spend is nearly identical ($59.54 vs $60.25).
- **Subscriptions:** Subscribers (27% of customers) do not spend more per purchase than non-subscribers ($59.49 vs $59.87).
- **Repeat buyers:** Customers with more than 5 previous purchases subscribe more often (27.6% vs 22.4%).
- **Discounts:** 43% of purchases used a discount, with almost no difference in average spend ($59.28 vs $60.13). Hats (50%) and Sneakers (49.7%) have the highest discount share.
- **Shipping:** Express customers spend about 3% more than Standard ($60.48 vs $58.46).
- **Customer base:** 80% of customers are Loyal, 18% Returning, and only 2% New.
- **Categories:** Clothing drives 45% of revenue, followed by Accessories (32%), Footwear (15%), and Outerwear (8%).
- **Top-rated products:** Gloves (3.86), Sandals (3.84), and Boots (3.82).
- **Age groups:** Revenue is spread evenly (24-27% per group), with ages 18-31 slightly ahead.

## Tech Stack
Python · Pandas · SQLAlchemy · PostgreSQL · Power BI · Jupyter Notebook

## Repository Contents
- `"C:\Users\shaikh naved\Downloads\Customer_shopping_behavior.ipynb"`: data cleaning and loading into PostgreSQL
- `"C:\Users\shaikh naved\Downloads\postgre.sql"`: SQL analysis queries
- `"C:\Users\shaikh naved\OneDrive\Desktop\ipl\customer shopping dashboard.pbix"`: Power BI dashboard
- `<img width="1348" height="757" alt="Dashboard" src="https://github.com/user-attachments/assets/d9f25ff3-fcaf-4043-b3a9-3a20159d095b" />
`: dashboard screenshot
