# 📊 Shopnest Store Analytics: Sales, Delivery, and Customer Insights

This Power BI project provides detailed analytics on the sales, delivery performance, customer behavior, and product performance for *Shopnest Store* using real-world e-commerce data.

---

## 📁 Project Summary

This dashboard gives a comprehensive overview of key business metrics across sales, customer satisfaction, delayed orders, product insights, and regional performance. It helps stakeholders make data-driven decisions for business improvement.

---

## 📌 Project Steps

- Collected and imported multiple .csv datasets related to orders, products, customers, payments, reviews, sellers, and geography.
- Loaded data into Power BI using *Power Query Editor*.
- Cleaned and transformed data:
  - Handled missing values.
  - Replaced nulls using *running average*.
  - Merged related tables using keys such as order_id, product_id, customer_id, etc.
  - Removed unnecessary columns for performance optimization.
- Created relationships between tables using a star schema model.
- Built custom DAX measures for:
  - On-Time Delivery Rate
  - Average Review Score
  - Revenue per Category/Product
- Created visuals including:
  - Bar and Column Charts
  - Donut Chart
  - Line Graphs
  - Maps for regional analysis
- Added slicers, filters, and drill-through pages for user interactivity.
- Published report to Power BI Service for sharing.

---

## 🔍 Key Insights

- *Total Revenue:* 16.01M  
- *Total Orders:* 98.66K  
- *Total Customers:* 99K  
- *Total Delayed Orders:* 37K  
- *Average Review Score:* 4.07  
- *On-Time Delivery Rate:* 63.88%

---

## 📌 Features

- Top 10 Categories by Total Price
- Top & Bottom 10 Products by Customer Ratings
- Revenue Growth Over Time
- Payment Method Analysis
- Monthly Comparison of Delayed vs On-Time Orders
- High vs Low Sales by State (Map Visuals)
- Seasonal Sales Pattern by Quarter
- Fully interactive filters, slicers, and drillthroughs

---

## 🧰 Tools Used

- *Power BI Desktop*
- *Power Query Editor*
- *DAX (Data Analysis Expressions)*
- *CSV/Excel Files*

---

## 📂 Dataset Details

| Dataset Name                      | Description |
|----------------------------------|-------------|
| customers_dataset              | Contains customer IDs and their location details (city, state) |
| geolocation_dataset            | Maps zip codes to geographic coordinates (latitude, longitude) |
| order_items_dataset            | Contains item-level details per order including product, price, and shipping cost |
| order_payments_dataset         | Includes payment methods and amounts paid for each order |
| order_reviews_dataset          | Customer review scores and comments for each order |
| orders_dataset                 | Core table with order status, purchase date, delivery time, etc. |
| products_dataset               | Includes product ID, category ID, and product-specific attributes |
| product_category_name_dataset  | Maps category IDs to category names (translated to English if needed) |
| sellers_dataset                | Information about each seller including location (city, state) |

---

## 📷 Dashboard Screenshot
<img width="934" height="548" alt="Screenshot 2025-07-21 113129" src="https://github.com/user-attachments/assets/f03ac226-5220-4f4d-b935-5380a5106e7e" />


## 🧠 Learnings

- Data modeling and relationship design
- Cleaning and transforming data in Power Query
- DAX for KPIs and calculated measures
- Advanced visualization design in Power BI
- Dashboard storytelling and insight presentation

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open the .pbix file using *Power BI Desktop*.
3. Explore interactive pages, visuals, and insights.
4. Filter and drill into specific categories, products, or customer segments.

---

