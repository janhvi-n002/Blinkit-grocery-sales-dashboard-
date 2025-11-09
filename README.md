# Blinkit-grocery-sales-dashboard
<img width="1148" height="648" alt="Screenshot 2025-11-09 105032" src="https://github.com/user-attachments/assets/d53c5753-d4c9-4e11-b23c-d90c9c8eb293" />

## Project Overview 
The Blinkit Business Intelligence Project aims to analyze customer purchases, product performance, and delivery efficiency using Power BI. The dashboard provides insights into sales trends, 
By integrating data from multiple sources such as customers, products, orders, transactions, and ratings, the project enables data-driven decision-making. Interactive visuals in Power BI help identify key business drivers, monitor KPIs, and improve overall operational efficiency.
 ## Dataset Description 
The Blinkit Grocery contains comprehensive information on customers, products, orders, transactions, delivery partners, and ratings. It provides a 360° view of the business, enabling analysis of sales performance, customer satisfaction, and delivery efficiency.
Item Identifier: Unique ID for each product.
Item Fat Content: Describes fat type (Low Fat or Regular).
Item Type: Category of the product (e.g., Dairy, Breads, Frozen Foods, Household).
Item Weight: Weight of the product.
Item Visibility: Display percentage of the product in the store.
Sales: Total sales amount for each item.
Outlet Identifier: Unique ID for each store/outlet.
Outlet Establishment Year: The year when the outlet was opened.
Outlet Location Type: Indicates store location (Tier 1, Tier 2, Tier 3).
Outlet Size: Represents store size (Small, Medium, Large).
Outlet Type: Type of outlet (e.g., Supermarket Type)
Business Objectives
The main goal of this project is to analyze the Blinkit Grocery Dataset using Power BI to understand sales patterns, product performance, and outlet characteristics.
 ## Key Objectives:
•	Identify the top-selling items and categories across different outlets.
•	Compare sales performance by outlet size, type, and location tier.
•	Analyze the impact of item visibility and fat content on total sales.
•	Evaluate how outlet establishment year affects sales growth.
•	Create an interactive dashboard that provides quick insights for decision-making.
 ## Tools & Techniques Used
Microsoft Power BI — Used for data cleaning, transformation, and creating interactive dashboards to visualize Blinkit sales data effectively.
Data Cleaning:
Removed missing values, corrected inconsistent entries, and ensured proper data types for columns like sales, item weight, and fat content.
Data Transformation:
Used Power Query Editor to rename columns, filter invalid records, and create calculated columns such as Total Sales and Average Rating.
Data Modeling:
Established relationships between tables and created measures for Sales, Average Rating, Number of Items, and Item Visibility.
DAX Measures:
o	Total Sales = SUM(Sales)
o	Average Sales = AVERAGE(Sales)
o	No of Items = COUNT(Item Identifier)
o	Avg Rating = AVERAGE(Rating)
Visualization:
Created dashboards using charts such as bar, donut, and line charts to show sales trends by item type, fat content, and outlet type.

 ## Key Insights 
The analysis of the Blinkit Grocery dataset in Power BI provided several valuable insights into sales, product trends, and outlet performance.
 Sales Trends
Outlets located in Tier 3 cities show higher total sales compared to Tier 1 and Tier 2 locations.
Medium-sized outlets generate more consistent sales than small or large ones.
Product Performance
Low Fat items are sold more frequently than Regular Fat items.
Categories like Fruits & Vegetables, Snack Foods, and Dairy contribute the most to total sales.
Items with higher visibility on shelves tend to perform better.
Outlet Insights
Supermarket Type3 outlets record the highest total sales among all outlet types.
Newer outlets (established after 2015) are performing better due to better product variety and promotional strategies.
Customer Preference
Customers prefer items that are low in fat and moderately priced.
There is a positive correlation between item visibility and sales volume.
 ## Future Enhancements
Add sales forecasting to predict future demand.
Use customer segmentation to target specific buyer groups.
Include profitability analysis to track margins by product and outlet.
Add interactive filters and slicers for better dashboard control.
Connect to real-time data for live updates and faster decisions.






