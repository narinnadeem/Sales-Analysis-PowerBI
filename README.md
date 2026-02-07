# Sales-Analysis-PowerBI
Strategic Growth & Customer Retention Analysis (Power BI)
Project Overview
This project analyzes marketplace data to evaluate business growth, customer behavior, and operational health. The goal was to transform raw data into a strategic dashboard that identifies why the business is scaling rapidly but struggling with long-term profitability.


Data Architecture & Cleaning (ETL)
Using Power Query, I implemented a robust ETL process to ensure data integrity:


Star Schema Optimization: Developed a schema with orders and order_items as central fact tables connected to dimension tables for customers, products, and geography.


Localization: Translated product categories from Portuguese to English for international stakeholder accessibility.


Data Cleaning: Handled null values in category fields and resolved many-to-many relationship conflicts in geolocation data to ensure 1:N spatial accuracy.


Key Insights

The "Leaky Bucket" Problem: Discovered a repeat purchase rate of effectively 0%, indicating the business is scaling solely through expensive new customer acquisition rather than retention.



Revenue Growth: Confirmed a massive scaling phase, with revenue surging from negligible levels in 2016 to a peak of ~Rs 8M in 2018.


Satisfaction Crisis: Identified a systemic quality issue where 1-star reviews are as frequent as 5-star reviews.


Top Categories: Health & Beauty and Watches & Gifts were identified as the primary drivers of Gross Merchandise Value (GMV).

Recommendations

Loyalty Programs: Launch automated incentives specifically for high-replenishment categories like Health & Beauty.


Operational RCA: Investigate the 1-star review segment to address recurring shipping or product description issues.
