# ☕ **Coffee Sales Analysis - Power BI Dashboard**
# 📌 Project Overview
This Power BI project analyzes sales data for a coffee shop to provide actionable insights into various aspects of sales performance. The dashboard helps the business track total sales, order trends, and product performance across different locations and time periods.

# ❓ Problem Statement
The coffee shop is struggling to understand its sales performance. The key areas of concern include:
- **Total Sales Analysis** - Understanding revenue trends.
- **Total Order Analysis** - Monitoring order frequency.
- **Total Quantity Sold Analysis** - Evaluating product demand.
- **Sales Analysis by Weekdays and Weekends** - Comparing weekday vs. weekend performance.
- **Sales Analysis by Store Location** - Identifying top-performing locations.
- **Daily Sales with Average Line** - Tracking sales trends over time.
- **Sales Analysis by Product Category** - Assessing which product categories drive the most revenue.
- **Top 10 Products by Sales** - Identifying the best-selling items.
- **Sales Analysis by Days and Hours** - Understanding peak sales periods.

The goal is to analyze these aspects to **identify key sales drivers and areas for improvement.**

## 🛠️ **Skills Demonstrated**
- __Power BI__ for data visualization, modeling, and analysis.

## 🔄 **Data Transformation**
•	To optimize performance and structure, **Power Query** was used to transform the raw dataset into a **Snowflake schema**.

•	Source: Excel file containing sales data.

•	Key Columns:
  - `Date`
  - `Product`
  - `Location`
  - `Sales Amount`
  - `Quantity Sold`
  - `Order ID`

# 📐 Data Modeling

Below is the **Snowflake schema** used in this project:

![image](https://github.com/user-attachments/assets/db098cb4-b71a-4764-8e6b-f0b6506a30f1)

## 📈 **Analysis & Visualizations**
The Power BI dashboard consists of various visual elements to display insights:

1. **Total Sales Analysis** - *Card & Line Chart showing sales trends.*
2. **Total Order Analysis** - *Card & Line Chart tracking order volume.*
3. **Total Quantity Sold Analysis** - *Card & Line Chart for total product sales.*
4. **Sales Analysis by Weekdays and Weekends** - *Pie Chart to compare sales on different days.*
5. **Sales Analysis by Store Location** - *Bar Chart visualizing sales performance per location.*
6. **Daily Sales with Average Line** - *Column Chart with an average trend line.*
7. **Sales Analysis by Product Category** - *Bar Chart displaying category-wise revenue distribution.*
8. **Top 10 Products by Sales** - *Bar Chart showing the best-selling items.*
9. **Sales Analysis by Days and Hours** - *Matrix Chart analyzing sales peaks across different days and hours.*
10. **Calendar Map for Monthly & Day-wise Analysis** - *Filtering sales data using a __calendar map__.*
11. **Tooltip in Calendar Map & Days-Hours Chart** - *Interactive tooltips for more detailed insights.*

![image](https://github.com/user-attachments/assets/3dee6e71-5c9f-4995-ade5-0f1012c12ac4)

Key Insights:
- Consistent Growth: Total sales, total orders, and total quantity sold show a significant month-over-month increase, except in February, where all metrics slightly declined by approximately 5.3% to 6.8%.
- Weekday vs. Weekend Orders: Orders placed on weekdays account for 72.1% of total orders, significantly higher than the 27.9% recorded on weekends. This suggests a strong preference for purchases during the workweek.
- Peak Coffee Sales Hours: Coffee sales are highest during the morning and noon hours, highlighting strong demand during typical breakfast and lunch periods.
- End-of-Month Sales Boost: Sales tend to be higher than the average during the middle and end of each month, suggesting possible payday-related purchase patterns.
- Store Performance: Sales across all three store locations (Astoria, Hell's Kitchen, and Lower Manhattan) exhibit steady growth throughout the year. However, February sees a slight decline in sales across all locations, consistent with the overall monthly trend.

![image](https://github.com/user-attachments/assets/1cf97b07-a430-40cf-84be-7927b7500bf9)

The dashboard provides an in-depth analysis of product performance throughout 2023.

Key Insights:
- Correlation Between Unit Price & Sales: Unit price and total sales exhibit a strong positive correlation of 0.85, indicating that higher-priced products tend to generate higher revenue.
- Top-Selling Product Detail: The product RG recorded the highest quantity sold, with approximately 70,186 units.
- Top 10 Product Types: Among all product types, Barista Espresso consistently ranks first in total sales, while Drip Coffee remains at the bottom, highlighting differences in customer preferences and demand.
- Quantity Sold by Category & Type:
  
By Category: Coffee leads with 29,655 units sold, while Packaged Chocolate records the lowest quantity sold at 110 units.

By Product Type: Brewed Chai Tea ranks highest with 9,306 units sold, whereas Green Beans has the lowest sales, with only 40 units.

These insights help businesses understand product demand, optimize inventory, and refine pricing strategies to maximize revenue.

## 📌 **Conclusion & Recommendations**

**Conclusions**:
- **High Sales Days**: Sales peak during weekends and early morning hours.
- **Top Products**: The best-selling products are cappuccinos and espresso-based drinks.
- **Store Performance**: Some locations outperform others due to high foot traffic.
- **Promotional Strategy**: Offering discounts on slow-selling products can help balance demand.

**Recommendations**:
- **Maximize Peak Sales**: Extend weekend hours, offer morning discounts, and implement loyalty rewards for espresso-based drinks.

- **Optimize Store Performance**: Analyze low-performing locations, adjust staffing, and use digital marketing to boost foot traffic.

- **Balance Demand with Promotions**: Offer discounts on slow-selling items, introduce seasonal drinks, and create bundle deals.

## 🚀 **How to Use This Dashboard**
1. **Download the `.pbix` file** from the repository.
2. **Open Power BI Desktop** and load the file.
3. Use filters and slicers to explore insights interactively.

---
🔗 *For further improvements, feel free to fork this project and contribute!* 🚀

