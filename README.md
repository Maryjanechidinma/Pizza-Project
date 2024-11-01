https://app.powerbi.com/groups/me/reports/02a2bc6a-0865-4425-be2e-af92a6e8d640/e0fcde84bc3df1136ab6?experience=power-bi


Pizza Sales Analysis Dashboard:
This Power BI project provides a comprehensive analysis of pizza sales data, offering insights into revenue, customer ordering patterns, and product popularity. The dashboard enables users to explore metrics like total revenue, average order value, sales trends by time, and top-performing pizzas.

Table of Contents:
Overview
Data Model
Key Visuals and Metrics
Usage Instructions
Project Setup
Notes and Assumptions

Overview:
The Pizza Sales Analysis Dashboard offers insights into pizza sales performance by examining total revenue, average order value, category breakdowns, and customer ordering trends. This analysis aids business stakeholders in identifying peak periods, popular products, and areas for improvement.

Data Model
The dashboard relies on a single table or dataset:

Table: pizza_sales

pizza_name: Name of each pizza.
pizza_category: Category classification, such as Classic or Premium.
pizza_size: Pizza size (e.g., Small, Medium, Large).
quantity: Number of pizzas sold per order.
total_price: Total sales amount for each order.
order_id: Unique identifier for each order.
order_date: Date the order was placed.
This structure supports various calculations for metrics and trends related to revenue, order patterns, and popular pizza types.

Key Visuals and Metrics
The dashboard includes a variety of key metrics and visualizations to provide insights into the business’s performance:

Total Revenue

Metric: Sum of all sales revenue.
Visual: Card.
Purpose: Shows overall income generated from sales.
Average Order Value

Metric: Average revenue per unique order.
Formula: Total Revenue / Total Orders.
Visual: Card.
Total Pizzas Sold

Metric: Total pizzas sold across all orders.
Visual: Card.
Total Orders

Metric: Total count of unique orders.
Visual: Card.
Average Pizzas per Order

Metric: Number of pizzas on average in each order.
Formula: Total Quantity Sold / Total Orders.
Visual: Card.
Daily Trend for Orders

Metric: Count of orders by day of the week.
Visual: Bar chart.
Purpose: Highlights the busiest days for pizza sales.
Monthly Trend for Orders

Metric: Count of orders by month.
Visual: Line or Bar Chart.
Purpose: Shows seasonal order trends.
Revenue by Pizza Category

Metric: Total revenue by pizza category and percentage of total sales.
Visual: Donut Chart or Stacked Bar Chart.
Purpose: Illustrates revenue contributions by each pizza category.
Top 5 Pizzas by Revenue

Metric: The five pizzas that generated the highest revenue.
Visual: Horizontal Bar Chart.
Top 5 Pizzas by Quantity

Metric: The five pizzas with the highest quantity sold.
Visual: Horizontal Bar Chart.
Top 5 Pizzas by Orders in 'Classic' Category
Metric: Top five most ordered pizzas within the 'Classic' category.
Visual: Horizontal Bar Chart.
Usage Instructions
Interacting with Filters:

Use slicers to drill down by pizza category, pizza size, or order date (e.g., specific months or years).
Selecting Visuals:

Hover over visuals for tooltips with details like exact revenue and quantity values.
Clicking on a data point cross-filters other visuals, allowing more targeted analysis.
Understanding Metrics:

Revenue, Average Order Value, and Top Pizzas provide direct insight into financial performance.
Daily and Monthly Trends reveal ordering patterns and help optimize staffing or promotions for peak days.
Project Setup
Data Import:

Import the pizza_sales table into Power BI.
Data Transformations:

Ensure columns like order_date are set to date format.
Verify calculations for metrics, ensuring they match your SQL queries for consistency.
Report Layout:

Arrange visuals in a clean, organized layout.
Set a consistent color scheme and font style for readability.
Notes and Assumptions
Data Accuracy: Regularly update the pizza_sales data for accurate metrics.
Date Formats: Match date formats in the order_date field to the locale.
Confidentiality: Ensure no sensitive customer data is included in this analysis.
