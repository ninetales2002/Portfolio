# Sales Dashboard in Tableau

In today's data-driven world, visualizing sales data is crucial for understanding performance and making informed business decisions. This project presents a sales performance dashboard built with Tableau and showcases how interactive visualizations can help businesses uncover hidden trends, identify growth opportunities, and optimize sales strategies.

The dashboard provides a holistic view of key sales metrics, including revenue, profit, number of orders, and products sold. Through interactive visualizations, we can analyze sales trends over time, identify top-selling products, and explore customer purchase patterns by location. With the added functionality of using the bar plot for monthly performance and the pie chart for product analysis as filters, users can dynamically explore the data by selecting specific months or products of interest, gaining deeper insights into the sales data.

 
The dataset used consists of 11 columns, each column representing an attribute of purchase on a product:
- Order ID - A unique ID for each order placed on a product
- Product - Item that is purchased
- Quantity Ordered - Describes how many of that products are ordered
- Price Each - Price of a unit of that product
- Order Date - Date on which the order is placed
- Purchase Address - Address to where the order is shipped
- Month, Sales, City, Hour - Extra attributes formed from the above.

In order to get the geographic coordinates based on the information provided in the  *Purchase Address* column, geocoding functionality was integrated into data preprocessing using Python and Google Maps API. The procedure can be found in the file Sales_Data_Geocoding_with_Google_Maps_API.ipynb.

<br>

## Static Dashboard View


![Dashboard](Dashboard%201.png)


<br>

## Dashboard description
<br>

### 1. Overview

- **Total Revenue:** Displays the total revenue generated from sales.
  
- **Total Profit:** Shows the overall profit made from sales after deducting costs.
  
- **Number of Orders:** Indicates the total number of orders processed.
  
- **Products Sold:** Presents the total count of unique products sold.
<br>

### 2. Monthly Performance

- **Bar Plot:** Illustrates the revenue performance month-wise, providing insights into sales trends over time. Acts as a filter to display all information by month.
  
- **Line Plot:** Represents the profit generated each month, aiding in understanding revenue fluctuations across different periods.

(*Note: The visual representation suggests a direct proportion between profit and revenue, with the line plot closely mirroring the trends of the bar plot.
However, it's crucial to acknowledge an underlying assumption made during the creation of this graph: the profit percentage is presumed to be consistent across all products. This assumption stems from the limitations of the dataset, which did not provide specific profit percentages for each product.
In reality, profit percentages can vary significantly among different products due to factors such as production costs, pricing strategies, and market demand. Therefore, while the graph provides a general overview of the relationship between sales and revenue, it's essential to interpret the results with caution, recognizing that the actual profit margins for individual products might deviate from the assumed uniform percentage.*)

<br>

### 3. Geographical Insights

- **Map Plot:** Visualizes the geographical locations of sales, allowing for the identification of key areas of sales activity.
<br>

### 4. Product Analysis

- **Contribution to Total Profit Table:** Provides a detailed breakdown of each product's contribution to the total profit, displayed as a percentage and absolute profit value.
  
- **Pie Chart:** Summarizes the distribution of profits among different products, highlighting the most profitable items. Acts as a filter to display all information by product.
  
- **Purchases by Product Bar Plot:** Illustrates the sales volume of each product, assisting in identifying popular items and their respective sales volumes.

