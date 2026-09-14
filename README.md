# Food Delivery Performance and Delay Analysis

## Project Overview
This project analyzes food delivery operations to identify delivery delays, restaurant performance, order cancellations, customer ratings, and location-level issues.

The analysis was performed using Python, Pandas, BeautifulSoup, SQL, Excel, and Power BI.

## Business Problem
The food delivery company is facing issues such as:
- Delayed deliveries
- Order cancellations
- Low customer ratings
- Poor restaurant performance

The goal is to analyze the available data and provide data-driven recommendations for improving operations.

## Objectives
- Identify restaurants with the highest number of orders.
- Identify locations with the highest number of delayed deliveries.
- Analyze cancellation rates by restaurant.
- Study the relationship between delivery performance and customer ratings.
- Identify high-performing restaurants.
- Provide business recommendations for operational improvement.

## Tools and Technologies
- Python
- Pandas
- BeautifulSoup
- PostgreSQL
- Excel
- Power BI

## Key Findings
- Total Orders: 10,000
- Average Delivery Time: 49.37 minutes
- Cancellation Rate: 10.39%
- Average Customer Rating: 3.92
- Delayed Orders: 5,875 (58.75%)
- Normal Orders: 2,827 (28.27%)
- Fast Orders: 1,298 (12.98%)
- Highest Order-Volume Restaurant: Seafood Delight – 1,028 orders
- Highest Average Delivery Time: Pasta Place – 49.85 minutes
- Highest Delayed Orders by Location: San Antonio – 627 orders

## Business Focus Areas

### Pasta Place
Pasta Place has the highest average delivery time. Management should review preparation time, dispatch processes, and delivery-partner coordination.

### San Antonio
San Antonio has the highest number of delayed orders. Delivery capacity, rider availability, routing, and peak-hour demand should be reviewed.

## Business Recommendations
1. Improve restaurant preparation and dispatch processes.
2. Increase delivery-partner availability in high-delay locations.
3. Monitor delivery time, cancellations, and customer ratings regularly.

## Dashboard
An interactive Power BI dashboard was created to monitor:
- Total Orders
- Average Delivery Time
- Cancellation Rate
- Average Customer Rating
- Orders by Location
- Average Delivery Time by Restaurant
- Delivery Status Distribution
- Cancellation Rate by Restaurant
- Customer Rating vs Delivery Performance

## Project Files
- `cleaned_food_delivery.csv` – Cleaned dataset
- `external_city_data.csv` – External city data
- `Food_Delivery_Analysis.sql` – SQL analysis queries
- `Food_Delivery_Analysis.xlsx` – Excel analysis
- `Food_Delivery_Operations_Analysis.pbix` – Power BI dashboard
- `Food_Delivery_Project_Summary_Final.pdf` – Final project report

## Conclusion
The analysis shows that delivery delays are the major operational issue, with 58.75% of orders classified as delayed. Pasta Place and San Antonio were identified as the main focus areas. Improving preparation and dispatch processes, increasing delivery capacity, and continuously monitoring operational KPIs can help improve delivery performance and customer satisfaction.
