# README: E-Commerce Sales Trends (2015-2016)

## 📌 Overview
This dataset analyzes e-commerce sales trends for **Consumer Electronics** and **Media** categories during **2015-2016**. It includes transactional data, product details, and weather conditions (Ontario climate data) to explore seasonal influences on sales performance.

## 📊 Key Insights from 2015-2016 Sales Trends
### **Top Performers and Key Observations:**
- **Top Performing Sub-Category:** Cameras 📷
- **Most Frequently Sold Product:** Speakers 🔊
- **Least Frequently Sold Product:** Game Value Cards 🎮
- **Highest Sales Value Product:** Cameras
- **Top Sales Month:** October 🍂 (Festive/Promotional Season)
- **Highest Seasonal Sales:** Spring 🌸
- **Lowest Seasonal Sales:** Summer ☀️
- **Preferred Payment Type:** Cash on Delivery (COD) 💰

### **Additional Trends:**
- **Seasonal and Monthly Impact:** Promotional campaigns during **October and Spring** had the highest impact on sales.
- **Product Diversity:** Electronics (Cameras, Gaming Accessories, and Speakers) dominated sales.
- **Weather Influence:** Climate data suggests potential correlations between sales and temperature/precipitation levels.

## 📂 Dataset Contents
### 1️⃣ **E-Commerce Data**
   - Order details: `order_id`, `fsn_id`, `order_date`, `order_item_id`
   - Customer details: `cust_id`, `pincode`
   - Product details: `product_analytic_super_category`, `product_analytic_category`, `product_analytic_sub_category`, `product_analytic_vertical`
   - Sales metrics: `gmv` (Gross Merchandise Value), `units`, `profit_margin`, `order_payment_type`
   
### 2️⃣ **Consumer Electronics & Media Data**
   - Focus on sub-categories like **Cameras, Speakers, Gaming Accessories**.
   - Monthly sales distribution across product categories.
   
### 3️⃣ **Climate Data (Ontario - 2015 & 2016)**
   - Weather conditions impacting sales trends.
   - Columns include: `Max Temp (°C)`, `Min Temp (°C)`, `Mean Temp (°C)`, `Total Rain (mm)`, `Total Snow (cm)`, `Total Precip (mm)`, `weather_condition`

## 📌 How to Use This Dataset in Tableau
1. **Load the dataset** into Tableau.
2. **Create interactive visualizations**, such as:
   - **Sales Trends**: Line charts for GMV across months.
   - **Seasonal Analysis**: Bar charts comparing sales across seasons.
   - **Product Performance**: Stacked bar charts for top-selling sub-categories.
   - **Weather Impact Analysis**: Dual-axis charts (GMV vs. Temperature/Rainfall).
3. **Use Filters for Interactive Insights:**
   - Date Filters (`Month-Year`)
   - Product Filters (`product_analytic_category`, `product_analytic_vertical`)
   - Geographic Filters (`pincode` for regional sales analysis)
   - Weather Filters (`weather_condition`, `temp_range`)

## 📎 Conclusion
This dataset provides valuable insights into **seasonal sales performance**, **consumer preferences**, and **weather impact on e-commerce trends**. By leveraging **Tableau dashboards**, businesses can optimize promotional strategies, predict sales trends, and improve decision-making. 🚀

