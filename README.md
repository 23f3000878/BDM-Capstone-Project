# Case Study: Pizza Planet – Business Data Management Capstone

## 📌 Project Overview

This project focuses on the data-driven analysis of **Pizza Planet**, an emerging restaurant in Najibabad. Despite its growing popularity and strong entrepreneurial roots, the business faced challenges in extracting actionable insights from its unorganized operational data.

The primary goal of this capstone was to transform 12,789 raw transactional records into meaningful business intelligence to optimize marketing, operations, and customer retention.

## 🎯 Objectives

* 
**Identify Sales Patterns**: Determine peak hours, busiest days, and seasonal trends.


* 
**Platform Performance**: Compare revenue and order volume across Dine-In, Zomato, Swiggy, and Parcel.


* 
**Customer Behavior**: Segment customers based on loyalty and analyze retention rates.


* 
**Payment & Pricing**: Evaluate the dominance of cash vs. digital payments and the impact of discounts on net sales.



## 🛠️ Methodology & Tech Stack

The analysis followed a structured data science lifecycle performed entirely in **Python**:

* 
**Data Cleaning**: Standardized column names, handled missing values (e.g., "Unknown" for Customer IDs), and removed duplicate records.


* 
**Feature Engineering**: Derived time components (Hour, Day, Month) and created customer-level summaries.


* **Analytical Framework**:
* 
**RFM Analysis**: Scored customers based on Recency, Frequency, and Monetary value.


* 
**Cohort Analysis**: Measured customer retention over time using a heatmap matrix.


* 
**Profitability Modeling**: Estimated profits assuming a 30% gross margin across channels.




* 
**Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`.



## 📊 Key Findings

* 
**Revenue**: Total revenue of **₹3,161,245.58** with an Average Order Value (AOV) of **₹247.18**.


* 
**Top Channel**: **Dine-In** is the primary driver, contributing **54.3%** of total revenue.


* 
**Peak Activity**: Business peaks between **5 PM – 9 PM**, with **Saturdays** and **Sundays** being the busiest days.


* 
**Loyalty Gap**: While 45% of orders are trackable, **74% of customers are one-time visitors**, indicating a critical need for retention strategies.


* 
**Payment Trends**: Cash remains king at **74.8%**, though digital payments are steadily rising.



## 💡 Strategic Recommendations

1. 
**Retention Programs**: Implement a formal loyalty system to convert the 74% of one-time customers into repeat patrons.


2. 
**Digital Growth**: Optimize the Swiggy platform, which currently underperforms (1.7% of sales) compared to Zomato.


3. 
**Operational Efficiency**: Align staffing and inventory with the 6 PM – 9 PM peak period to improve service speed.


4. 
**Incentivize Prepaid Orders**: Offer small incentives for online payments to reduce the operational complexity of handling 75% cash transactions.



## 📂 Project Structure

* 
`/data`: Contains raw and cleaned CSV files (e.g., `rfm_scores.csv`).


* 
`/outputs`: Generated visualizations (e.g., `cohort_retention.png`, `monthly_trend.png`).


* `Pizza_Planet_Analysis.ipynb`: Full Python source code for EDA and modeling.

---

**Author**: Mohd Saalim **Institution**: IIT Madras, Online BS Degree Program
