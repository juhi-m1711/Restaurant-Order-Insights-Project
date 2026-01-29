# 🍽️ Restaurant Order Insights (SQL)

## Project Overview
This project focuses on analyzing restaurant order data using **SQL** to uncover meaningful business insights related to **sales performance, menu effectiveness, and ordering patterns**.

The objective of this project is to demonstrate how raw transactional data can be transformed into **actionable insights** that support data-driven decision-making in the **Food & Beverage (Restaurant Analytics)** domain.

---

## Business Problem
Restaurants generate large volumes of order data daily, but without proper analysis, it becomes difficult to answer key business questions such as:
- Which menu items and categories generate the most revenue?
- What are the peak ordering hours and busiest periods?
- How large are customer orders on average?
- Which items underperform and need optimization?

This project addresses these challenges using structured SQL analysis.

---

## About the Data
- **Data Type:** Simulated / public-style restaurant transaction data  
- **Source:** Maven Analytics  
- **Number of Tables:** 2  
- **Number of Records:** 12,000+  
- **Currency:** All monetary values are represented in **USD**

### Tables Used
- **order_details**
  - `order_id`, `order_date`, `order_time`, `item_id`
- **menu_items**
  - `item_name`, `category`, `price`

---

## Data Model (ER Diagram Summary)
- The database consists of two tables: `order_details` and `menu_items`.
- `order_details` stores item-level order transactions along with date and time.
- `menu_items` stores menu information such as item name, category, and price.
- Both tables are connected using `item_id`, forming a **many-to-one relationship**.
- This structure enables detailed analysis of sales, revenue, and menu performance.

---

## SQL Analyses Performed

- **Sales and Revenue Analysis**
  - Total revenue generated
  - Top-performing and least-performing menu items by revenue and quantity

- **Order Pattern Analysis**
  - Order volume trends by day and hour
  - Average order size (average items per order and average bill value)

- **Menu and Category Performance**
  - Category-wise order volume
  - Revenue contribution by menu category
  - Average item price per category

- **Time-Based Analysis**
  - Identification of peak ordering hours
  - Lunch vs dinner order comparison

- **Advanced SQL Analysis**
  - Use of **Common Table Expressions (CTEs)** for structured and reusable queries
  - **Window functions** to rank items by revenue within each category
  - Running total of daily revenue for trend analysis

---

## Visualization
- The SQL analysis results were visualized using **Power BI**.
---

## Tools & Technologies
- **PostgreSQL** – Data analysis using SQL
- **Power BI** – Data visualization 
- **GitHub** – Version control and project documentation

---

## Key Insights
- A small number of menu items contribute a significant share of total revenue.
- Certain menu categories consistently outperform others.
- Clear peak hours exist, requiring focused staffing and operational planning.
- Average order size indicates opportunities for upselling and combo offers.
- Some items underperform and may require repricing or repositioning.

---

## Proposed Solutions
- Promote high-performing and high-revenue menu items.
- Re-evaluate or redesign low-performing items.
- Optimize staffing and inventory during peak hours.
- Apply data-driven insights for pricing and menu planning decisions.

---

## Future Scope
- Build interactive dashboards for real-time performance monitoring.
- Forecast demand and peak periods using historical trends.
- Use analytics to improve pricing, promotions, and revenue planning.
- Automate reporting to support faster and more informed business decisions.

---

## One-Line Summary
> *A SQL-based restaurant analytics project that transforms order data into actionable insights for sales growth and operational efficiency.*

---


## 📬 Contact
**Juhi Moudekar**  
Aspiring Data Analyst | SQL | Power BI  
Feel free to connect or share feedback!
LinkedIn: www.linkedin.com/in/juhi-moudekar 
