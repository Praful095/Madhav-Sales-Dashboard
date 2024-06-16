# power-bi-project

# Madhav Sales Dashboard

## Problem Statement

Madhav runs an online retail business that operates across India, selling a variety of products through multiple channels such as their website, mobile app, and third-party e-commerce platforms. With the growing scale of operations, Madhav faces challenges in effectively tracking and analyzing sales performance, identifying trends, and making informed business decisions.

The goal is to create a Power BI dashboard that provides Madhav with comprehensive insights into their online sales performance across India. The dashboard should enable Madhav to monitor key metrics, identify patterns, and make data-driven decisions to optimize sales and marketing strategies.




### Steps followed Creating a Power BI Dashboard for Madhav's Online Sales
To create a Power BI dashboard that tracks and analyzes Madhav's online sales using the provided order and details CSV files, follow these steps:

1. Load Data into Power BI
Open Power BI Desktop.
Import CSV Files:
Go to Home > Get Data > Text/CSV.
Select the order.csv file and click Open.
Repeat the process for the details.csv file.
2. Data Preparation and Cleaning
Examine the Data:

Click on Data view to inspect the loaded data for both order and details tables.
Renamed Columns as required

Ensured that column names are clean and consistent.
 
Created Relationships:

Go to Model view.
Drag and drop order_id from the order table to the details table to create a relationship.
Transform Data (if needed):

Go to Home > Transform Data to open Power Query Editor.
Apply any necessary transformations such as removing duplicates, handling missing values, or changing data types.
3. Create Calculated Columns and Measures
Calculated Columns:

Create calculated columns for additional insights if needed, such as Year or Month from order_date.
Measures:

Create measures for key metrics like total sales, profit, quantity, etc.
DAX
Copy code
Total Sales = SUM(details[amount])
Total Profit = SUM(details[profit])
Total Quantity = SUM(details[quantity])


![trends](https://github.com/Praful095/power-bi-project/assets/158684580/5f9f2506-8cf6-4c1e-a43e-854b69cfaeb8)

4. Build the Dashboard
Sales Performance Overview:

Create visuals like Line Charts, Bar Charts, and Cards to display total sales, profit, and quantity over time.
Use the order_date field to show trends over different periods.
Geographical Analysis:

Use Map or Filled Map visuals to display sales distribution by state and city.
Ensure you use the state and city columns from the order table.
Product Performance:

Create visuals to display sales by category and sub_category from the details table.
Use Pie Charts, Tree Maps, or Bar Charts to show top-selling and least-selling products.
Customer Insights:

Create visuals to analyze customer data such as sales by customer_name.
Use demographic data if available in the order table.
Channel Performance:

Although not directly provided in the CSV files, if you have channel information, include visuals to compare performance across different channels.
Time-Based Trends:


Use Line Charts and Area Charts to display sales trends over different periods.
Highlight peak sales periods and compare them to off-peak periods.
Operational Metrics:

Use metrics related to quantity and payment_mode to analyze operational efficiency.
Create visuals to show order fulfillment rates and delivery times if data is available.

![use of bar-graphs ,line graphs,pie charts for better understanding](https://github.com/Praful095/power-bi-project/assets/158684580/078ee215-2043-40b2-b270-a67850816582)
5. Enhance and Customize the Dashboard
Add Filters and Slicers:

Add slicers for order_date, state, city, category, and sub_category to enable dynamic filtering.
Design and Format:

![use of slicers and filetrs](https://github.com/Praful095/power-bi-project/assets/158684580/8127811f-5fae-4872-9418-126a408be564)

Customize the dashboard layout, color scheme, and fonts to make it visually appealing.
Use consistent formatting for easier interpretation of data.
Add Titles and Labels:

Ensure all visuals have clear titles and labels.
Add tooltips to provide additional context for the data points.
 

# Snapshot of Dashboard (Power BI Service)

![Dashboard Snapshot](https://github.com/Praful095/power-bi-project/assets/158684580/39626793-5210-427e-b235-f5b37312b049)


# Insights
# the Overview:

# Total Sales Amount :
 The total sales amount is 438K

 #  Total Quantity sold :
 The total quantity of items sold is 5615.

# Total Sales Amount:
 Total Profit: The total profit generated is 37K.

 # Avergae Sales:
Average Sales Value: The average sales value is 121K.
# Geographical Analysis
Sales by State:

The states with significant sales are:
Andhra Pradesh
Bihar
Delhi
Goa

Delhi appears to have the highest sales among the states listed.
Customer Insights

Sales by Customer Name:
The top customers in terms of sales amount are:
Aastha
Aayush
Abhijeet
Akshay
Each of these customers has contributed approximately 0.4M to the total sales amount.

Product Performance
Quantity by Category:

The distribution of quantity sold by product category:
Clothing: 63%
Electronics: 21%
Furniture: 17%
Sub-Category Analysis:

The profit distribution by sub-category shows a wide range of values, indicating that some sub-categories are highly profitable while others may incur losses.

Payment Mode Analysis

Sales by Payment Mode:
Cash on Delivery (COD) is the most popular payment mode, accounting for 44% of sales.

UPI payments make up 21% of the sales.

Debit Card payments contribute 13%, and Credit Card payments account for 12% of the sales.

Time-Based Trends
Monthly Profit Count:
The count of profit across the months (October, November, December) shows a consistent trend with each month having around 1500 to 2000 in profit count.

Additional Filters
Quarter and State Filters:

The dashboard allows filtering data by quarters (Q1, Q2, Q3, Q4) and states, providing flexibility to analyze sales performance over different time periods and geographical regions.

# Insights Summary

Delhi is the leading state in terms of sales amount.
Clothing is the dominant product category, making up the majority of the sales quantity.
Cash on Delivery (COD) is the preferred payment mode among customers.

Top Customers like Aastha, Aayush, Abhijeet, and Akshay are crucial to the sales performance.

Monthly profits remain stable over the last three months of the year, suggesting consistent performance.

The sub-category profit analysis reveals a diverse range of profitability across different sub-categories, highlighting potential areas for improvement or focus.

These insights can help Madhav understand key aspects of their online sales, including top-performing regions, customer preferences, and product performance, enabling more informed business decisions.

# Madhav Sales-Dashboard.md.txt
Displaying # Madhav Sales-Dashboard.md.txt.



