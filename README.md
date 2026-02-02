# Vijay_Sales_Analysis_Project

🧾 Project Overview

This Tableau project analyzes Vijay Sales retail data to understand sales performance across regions, cities, stores, products, and customers. The dashboard provides business insights that help identify top-performing regions, popular products, and customer purchasing behavior.

The project is built using an Excel dataset and visualized using Tableau with interactive dashboards and filters.

📁 Dataset Description

The project uses the Excel file: Vijay_Sales_Regional_City_Sales.xlsx

It contains the following sheets:

1️⃣ Sales
Column Name	Description
Sale_ID	Unique sales transaction ID
Date	Date of sale
Store_ID	Store identifier
City	City where sale occurred
Region	Sales region (North, South, West, etc.)
Product_ID	Product identifier
Customer_ID	Customer identifier
Quantity	Number of items sold
Sales_Amount	Total sales value

2️⃣ Stores
Column Name	Description
Store_ID	Store identifier
Store_Name	Name of the Vijay Sales store
City	Store city
Region	Store region

3️⃣ Products
Column Name	Description
Product_ID	Product identifier
Product_Name	Name of the product
Category	Product category (Laptop, Mobile, TV, etc.)
Brand	Brand name
Price	Product price
Store_ID	Store selling the product

4️⃣ Customers
Column Name	Description
Customer_ID	Customer identifier
Customer_Name	Customer name
Gender	Gender of customer
City	Customer city

🔗 Data Model (Relationships)

Sales ↔ Stores → Store_ID

Sales ↔ Products → Product_ID

Sales ↔ Customers → Customer_ID

These relationships enable multi-dimensional analysis in Tableau.

📊 Key Visualizations in Tableau

Total Sales by Region

Sales Performance by City

Top Performing Stores

Category-wise & Brand-wise Sales Analysis

Customer Distribution by Gender & City

Monthly / Date-wise Sales Trend

Interactive filters allow users to slice data by:

Region

City

Product Category

Brand

Date

🛠 Tools Used

Tableau Desktop – Dashboard creation & visualization

Microsoft Excel – Data source

🎯 Business Insights

Identifies high-revenue regions and cities

Highlights best-selling product categories and brands

Helps understand customer purchasing patterns

Supports data-driven decisions for inventory and regional strategy

✅ Conclusion

This Tableau project provides a clear and interactive view of Vijay Sales performance across multiple dimensions. By analyzing regional, city-wise, and product-level sales, stakeholders can quickly identify growth opportunities, optimize store performance, and improve customer targeting strategies.

The dashboard is suitable for sales analysis, management reporting, and business decision-making, making it a strong portfolio project for data analysis and BI roles.
