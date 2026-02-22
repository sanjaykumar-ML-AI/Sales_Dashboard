📌 1. Project Overview

This Power BI report was developed to analyze the operational and financial performance of an e-commerce company facing growth and customer satisfaction challenges
The Report provides data-driven insights across:

Financial Performance
Customer Behavior
Logistics & Fulfillment
Product & Inventory Optimization
Customer Satisfaction & Returns
The objective is to support Stakeholders in making informed decisions to drive sustainable growth

🎯 2. Business Objectives

The report addresses the following strategic questions:

🔹 Financial Performance

What is the total revenue trend over time?

Which products and categories drive maximum sales?

What is the Average Order Value (AOV)?

🔹 Customer Insights

Which locations generate the highest sales?

What is the cancellation trend?

How does B2B behavior differ from B2C?

🔹 Logistics & Fulfillment

What is the average shipping time?

Are Amazon-fulfilled orders more efficient than Merchant-fulfilled?

Where are delivery bottlenecks occurring?

🔹 Product & Inventory Optimization

Which product categories have highest demand?

What is the average quantity ordered?


🔹  SKU Returns Insights

Which categories have highest return rates?

🗂 3. Dataset Description

The dataset includes order-level transactional data with the following key fields
Order ID

Date

Status

Fulfillment

Sales Channel

Category

SKU

Quantity

Amount

Shipping details (city, state, country)

B2B flag

Promotion IDs

🛠 4. Data Preparation & Cleaning

The following steps were performed:

Data profiling and validation

Replaced null values in Amount column using median value 

Removed inconsistent order statuses

Standardized date format

Created calculated columns:

Order Month

Cancellation Flag

Return Flag

Built a Star Schema model:

Fact Table: Orders

Dimension Tables: Date, Product, Location

📊 5. Dashboard Structure
🔹 Page 1 – Executive Overview

Total Revenue

Total Orders

AOV

Cancellation %

Return %

Revenue Trend

🔹 Page 2 – Customer Insights

Sales by State ad City

B2B vs B2C comparison

Cancellation by region

🔹 Page 3 – Logistics & Fulfillment

Fulfillment comparison (Amazon vs Merchant)

🔹 Page 4 – Inventory Optimization

High-demand categories

Avg quantity per order

Stock risk indicators

Inventory turnover metrics

🔹 Page 5 – Returns & Customer Experience

Return rate by category

Cancellation Rate

High-Demand SKUs

📈 6. Key KPIs Calculated

Total Revenue

Average Order Value

Cancellation Rate

Return Rate

Inventory KPI's

Average Shipping Time

B2B Contribution %

7. Key Insights

Example insights from analysis:

Merchant-fulfilled orders show higher cancellation rates.

Specific product categories contribute to majority of returns.

B2B customers have higher AOV but lower cancellation.

Certain states show high sales but also high return percentage.

8. Business Recommendations

Based on analysis:

Optimize merchant fulfillment processes.

Implement dynamic safety stock for high-demand categories.

Review product quality for high-return SKUs.

Improve SLA tracking for delayed shipments.

Develop targeted marketing for B2B customers.

📌 9. Tools & Technologies Used

Power BI

DAX (Advanced calculations)

Data Modeling (Star Schema)

Excel (Data cleaning support)

📊 10. Impact of This Report

This report enables:

Data-driven operational decisions

Reduction in stockouts & overstock

Better fulfillment efficiency

Strategic revenue optimization

🧠 11. Learning Outcomes

Applied retail analytics frameworks

Built end-to-end BI solution

Integrated financial, customer, and logistics insights

Transformed raw transactional data into strategic recommendations

🎯 12. Conclusion

This Power BI solution demonstrates how data analytics can transform operational challenges into actionable insights, 
enabling the e-commerce company to achieve sustainable growth and enhanced customer satisfaction
