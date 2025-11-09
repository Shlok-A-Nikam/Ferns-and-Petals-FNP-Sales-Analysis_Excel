# Ferns-and-Petals-FNP-Sales-Analysis_Excel
<img width="1833" height="806" alt="Final Dashboard" src="https://github.com/user-attachments/assets/4ce60509-e558-4e17-9d41-5d6d2dde8ae1" />


## Project Overview
This project presents a comprehensive sales analysis for Ferns and Petals (FNP) — a gifting platform offering products for occasions like Anniversary, Birthday, Diwali, Holi, Raksha Bandhan, and Valentine’s Day.
The dataset includes customer, order, and product information from 2023, analyzed to uncover sales performance trends, popular categories, delivery efficiency, and customer spending behavior.

## The goal is to identify data-driven insights to help FNP:
•	Improve marketing strategies
•	Optimize logistics and delivery performance
•	Enhance customer experience and boost total revenue

## Dataset Description
## 1. Customers Table

Customer_ID =	Unique identifier for each customer
Name =	Full name of the customer
City	= Customer’s city/location
Contact Number =	Customer’s phone number
Email =	Customer’s email ID
Gender =	Male/Female
Address	 = Full delivery address
## 2. Orders Table
Order_Date	 = Date of order placement
Order_Time	 = Time of order placement
Delivery_Date	 = Date of delivery
Delivery_Time	 = Time of delivery
Location	= Delivery city
Occasion	= Type of occasion (e.g., Diwali, Anniversary, etc.)
Month Name	= Month derived from the order date
Hour (Order Time)	= Hour extracted from order time
Diff_Order_Delivery	= Delivery time difference (days)
Price (INR)	= Product unit price
Revenue	= Total order amount
Day Name =	Day of the week of order

## 3. Products Table

Product_ID	= Unique identifier for each product
Category	= Product category (e.g., Soft Toys, Plants, Cake, etc.)
Price (INR) = 	Product price
Occasion	= Related occasion
Description	= Short product description
Product Name	 = Name/title of the product
________________________________________
##  Business Objectives

•	Calculate total revenue, average customer spend, and order–delivery efficiency
•	Identify top-performing products, categories, and cities
•	Analyze sales by occasion, month, and hour
•	Understand customer purchase trends and delivery impact on satisfaction
•	Provide insights for marketing and logistics optimization
________________________________________
##  Key Business Questions
### 1. Sales Performance
1) Total Revenue
2) How does sales performance vary across months?
3) Which are the top 10 cities contributing the highest number of orders?
		
### Product & Revenue Insights
1) Which are the top products by revenue?
2) Category Wise Revenue ?
3) How does revenue differ between occasions (e.g., Diwali vs. Valentine’s Day)?

### Customer Analysis
1) What is the average customer spending per order?
2) What is the average order and delivery time
3) Is there a relationship between order quantity and delivery time?

### Occasion & Popularity Trends
1) Which products are most popular for each occasion?)
________________________________________
## Tools & Techniques Used
•	Microsoft Excel
o	Power Query for data cleaning and merging
o	Pivot Tables & Charts for analysis
o	Functions: SUMIFS, AVERAGEIFS, COUNTIFS, VLOOKUP, INDEX-MATCH, IFERROR
o	Conditional Formatting for KPIs
o	Interactive Dashboard using Slicers and Timelines
________________________________________
## Dashboard KPIs (as per image)
KPI	Value
Total Orders	1,000
Total Revenue	₹35,20,984
Average Delivery Time	5.53 Days
Average Customer Spend	₹3,520.98
________________________________________
## Insights
•	Anniversary occasion generated the highest revenue, followed by Holi and Raksha Bandhan.
•	Colors, Soft Toys, and Sweets are the top-performing categories.
•	The Anniversary Sweet Pack and Holi Color Gift are among the top 5 products by revenue.
•	North Dumdum, Kavali, and Imphal are the top cities by order count.
•	February and August recorded the highest sales, aligning with Valentine’s Day and Raksha Bandhan.
•	Peak order hours are between 12 PM to 4 PM, showing strong midday engagement.
•	Average delivery time (5.53 days) suggests potential improvement opportunities in logistics.
________________________________________
## Future Enhancements
•	Migrate the Excel dashboard to Power BI for advanced interactive visuals
•	Integrate customer feedback to correlate satisfaction with sales
•	Apply predictive analytics to forecast upcoming festival sales
•	Automate monthly data refresh using Power Query or VBA scripting

