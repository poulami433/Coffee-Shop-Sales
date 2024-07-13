![coffee-time-neon-text-and-cup-with-hot-drink-2RF1901](https://github.com/poulami433/Coffee-Shop-Sales/assets/171598364/8e975c79-41eb-4574-9c58-c8fe5bb91f1a)

 # PROJECT DESCRIPTION ::-

I recently completed an exciting project where I leveraged retail sales data for a smarter sales strategy. The main objective was to analyze the sales data to uncover actionable insights that could enhance the coffee shop's performance. Here's a walk-through of my journey, from data cleaning to creating an insightful dynamic dashboard.
![image](https://github.com/poulami433/Coffee-Shop-Sales/assets/171598364/b99b8bbe-c117-4936-8f19-64f565b42b34)

# Project Objectives and Recommended Analysis :

The primary goal was to analyze retail sales data to gain insights that could help improve the coffee shop's operations and sales strategies. The specific questions I aimed to answer included:

1. How do sales vary by day of the week and hour of the day?

2. Are there any peak times for sales activity?

3. What is the total revenue for each month?

4. How do sales vary across different store locations?

5. What is the average price per person?
6. Which products are the best selling in terms of quantity and revenue?

7. How do sales vary by product category and type?

# Steps Undertaken

1. Data Cleaning and Transformation Raw Data: I started with the raw data, which included transaction details such as transaction ID, date, time, store location, product details, and pricing.

2. Data Transformation: Using Power Query, I cleaned and transformed the data by adding new columns such as total bill. month name, day name, hour, day of the week, and month. This process helped in organizing the data for better analysis. Here's a snapshot of the transformed data:
![image](https://github.com/poulami433/Coffee-Shop-Sales/assets/171598364/7e4ed97a-3d94-4d48-9778-17afbdcd0dfb)

# Analysis and Insights:

* Sales by Day and Hour: Analyzed the sales data to observe patterns throughout the week and at different times of the day. This revealed that sales peak during the morning hours, especially between 8 AM and 11 AM, and weekdays see higher sales compared to weekends.

* Peak Times: Identified the busiest times for the coffee shop. which are weekday mornings, correlating with customers' morning routines and work commutes.

* Monthly Revenue: Calculated the total revenue for each month to track performance over time. Noted significant monthly fluctuations, with certain months performing exceptionally well due to promotions or seasonal factors.

* Location-Based Sales: Compared sales data across different store locations to understand geographic performance. Larger stores and those in high-traffic areas see more footfall and higher sales.

* Average Price: Determined the average bill per person, which stands at $4.69, and the average order value per person, which is $1.44.

* Best-Selling Products: Identified the top-selling products in terms of both quantity and revenue. Barista Espresso and Brewed Chai Tea emerged as favorites, indicating a strong preference for these beverages.
  
* Category Performance: Analyzed sales by product category and type, finding that coffee and branded products lead in sales. making up 67% of total revenue.

  ![image](https://github.com/poulami433/Coffee-Shop-Sales/assets/171598364/9e06c16f-50a2-4435-a9fc-369ba49ea9a8)

  # Dashboard Creation

Developed a dynamic dashboard to visualize the data and make the insights easily accessible. The dashboard includes several key metrics and visualizations:

* Total Sales and Footfall: Displays the overall sales revenue and total customer footfall.

* Average Bill and Order Value: This shows the average bill per person and the average order value per person.

* Sales by Hour: A line chart illustrating the quantity ordered based on hours of the day, highlighting peak times.
* Sales Distribution by Category: A pie chart showing thepercentage distribution of sales across different product categories.

* Order Size Distribution: A pie chart detailing the percentage distribution of orders by size (Large, Regular, Small).

* Footfall and Sales by Location Size: A bar chart comparing footfall and sales across different store location sizes.

* Top 5 Products by Sales: A bar chart showcasing the top five products based on sales revenue.

* Orders by Weekday: A bar chart illustrating the distribution of orders across the days of the week.

* Included interactive slicers for months, days of the week. categories, and locations to allow for detailed, drill-down analysis.

# Pivot Tables and DAX Measures

To provide more granular insights. I created several pivot tables and measures using DAX:

1. Hourly Sales Distribution (A): To understand the sales trends by the hour and identify peak sales hours.

This data helps pinpoint specific hours of high activity to optimize staffing and inventory.

1. Sales by Day of the Week: To identify which days of the week have the highest sales and plan promotions or special events accordingly.
