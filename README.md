
## Sales Data Analysis and Visualization

![Sales Analysis](images/sales-analysis.png)

### Problem Statement
The goal of this project is to analyze and visualize key aspects of Amazon's sales data, including sales performance by product category, customer segment, region, and sales channel. The analysis aims to identify trends, patterns, and insights that can be used to optimize sales strategies and improve profitability.

### Dashboard Components

1. **Total Sales Overview:**
   - Total sales (in <span style="color: #009688;">green</span>)
   - Total quantity (in <span style="color: #FF5722;">orange</span>)
   - Total profit (in <span style="color: #E91E63;">pink</span>)
   - Total shipment cost (in <span style="color: #FFC107;">yellow</span>)

2. **Sales by Product Category:**
   - Column chart showing the total sales by product category (in <span style="color: #2196F3;">blue</span>)

3. **Sales Trend Over Time:**
   - Line chart displaying the sales trend over time, with the X-axis showing month and year, and the Y-axis showing sales (in <span style="color: #4CAF50;">green</span>)

4. **Sales and Profits by Customer Segment:**
   - Comparison of sales and profits for each product category across different customer segments

5. **Sales and Profits by Product Category and Sub-Category:**
   - Analysis of sales revenue and profit variation across different product categories and sub-categories

6. **Average Discount Percentage by Product Sub-Category:**
   - Insight into the average discount percentage for different product sub-categories

7. **Sales and Profit by Region, State, and City:**
   - Examination of sales and profit variations across different regions, states, and cities
   - Geographic distribution of customers by state, with states ranked by profit

### Dataset Explanation

The dataset used for this analysis contains the following columns:

- **Order ID:** Unique identifier for each order made by customers
- **Order Date:** Date on which the order was made by the customer
- **Ship Date:** Date on which the order was shipped by Amazon
- **Ship Mode:** Shipping method used to deliver the order
- **Customer ID:** Unique identifier for each customer who placed the order
- **Customer Name:** Name of the customer who placed the order
- **Segment:** Segment to which the customer belongs (e.g., consumer or corporate)
- **Country:** Country to which the order was shipped
- **City:** City in which the order was delivered
- **State:** State or province in which the order was delivered
- **Region:** Region or area in which the order was delivered
- **Product ID:** Unique identifier for each product ordered by the customer
- **Category:** Category to which each product belongs (e.g., electronics or home appliances)
- **Sub-Category:** Sub-category to which each product belongs (e.g., laptops or refrigerators)
- **Product Name:** Name of each product ordered by the customer
- **Sales:** Total sales revenue generated by the order
- **Quantity:** Quantity of each product ordered by the customer
- **Discount %:** Percentage of discount given to the customer on the order
- **Profit:** Profit generated by the order (calculated as the difference between sales revenue and cost of goods sold)
- **Shipment Cost:** Cost of shipping the order to the customer


