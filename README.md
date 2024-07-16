# Coffee-Shop-Data-Analysis
This project aims to analyze data from coffee chain to uncover trends, insights, and actionable information. The analysis covers several key areas, including sales performance, customer behavior, product preferences.
Data Analysis Report: Coffee Shop Sales
Dataset Information
Source: Maven Analytics - Coffee Shop Sales
Data Preparation
1.	Load Dataset
o	Download the dataset from the provided source.
2.	Data Cleaning
o	Transaction Time and Date: Remove unnecessary columns related to transaction time and date.
o	Product Details: Separate 'lg' and 'rg' from product_details to create a new column named size. Trim product_details to remove size information.
o	Calculate Total Price: Multiply unit_price by quantity to get the total price for each transaction.
o	Clean Columns: Ensure transaction_time and transaction_date are in proper datetime format.
Data Transformation
1.	Pivot Tables Creation
o	Count of Transaction IDs
	By Hour: Count of transactions for each hour of the day.
	By Day: Count of transactions for each day of the week.
o	Total Transactions
	By Hour: Total number of transactions for each hour of the day.
	By Day: Total number of transactions for each day of the week.
2.	Monthly Analysis
o	Total Sales by Month: Sum of sales for each month.
3.	Product Analysis
o	Product Category vs. Total Sales: Total sales for each product category.
o	Top 5 Products by Sales: Products with the highest sales.
o	Top 5 Products by Quantity: Products with the highest quantity sold.
4.	Store Analysis
o	Footfall vs. Store: Count of transactions for each store.
o	Store vs. Total Sales: Total sales for each store.
5.	Detailed Product Analysis
o	Product Quantity vs. Total Sales and Total Quantity (Top 5): Analysis of the top 5 products based on sales and quantity.
o	Product Details by Sales: Detailed sales for each product.
o	Product Type by Sales: Total sales for each product type.
Analysis Summary
1. Count of Transaction IDs vs. Hours and Days
•	By Hour: Identifies peak hours for transactions.
•	By Day: Identifies peak days for transactions.
2. Total Transactions vs. Hours and Days
•	By Hour: Provides insights into the busiest hours.
•	By Day: Highlights the busiest days for sales.
3. Monthly Total Sales
•	Analyzes sales trends across different months to identify seasonality.
4. Product Category vs. Total Sales
•	Highlights which product categories contribute most to the sales.
5. Top 5 Products by Sales and Quantity
•	Identifies the best-selling products and those with the highest quantity sold.
6. Store Analysis
•	Footfall and sales comparison across different stores to identify top-performing locations.
7. Detailed Product Analysis
•	Provides an in-depth view of product performance based on sales and quantity.
________________________________________
This report outlines the necessary steps for data preparation, transformation, and analysis, ensuring comprehensive insights into coffee shop sales. The dataset can be accessed from the provided link for further detailed analysis.

