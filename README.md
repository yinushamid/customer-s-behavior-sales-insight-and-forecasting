# Customer Behavior, Sales Insight and Forecasting
## Business Story: Why This Project Matters

As a retail business grows, leaders start asking deeper questions:

- *"Who are our best customers?"*
- *"Which products should we promote?"*
- *"When do people buy the most?"*
- *"Can we predict what our sales will look like next quarter?"*

This project answers all these questions by analyzing customer behavior, 
identifying key sales patterns, and using time series forecasting to predict future revenue. 
The result is a set of **clear, data-driven insights** that help the business plan smarter and sell more.

---
## Table of Content
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

### Project Overview
This project is designed to help the business understand:
- Who our customers are and what they buy
- How well we are selling our products
- How much revenue we can expect in the future

The goal is to provide insights for smarter decision-making and business growth.

### Data Sources
- The main dataset used is **sales_data.csv** from Kaggle
- It contains detailed information about each sale made by the company

### Tools
- Python: Used for data cleaning and forecasting
- PostgreSQL: Used for SQL-based analysis
- Power BI: Used for creating interactive dashboards and visual reports

### Data Cleaning and Preparation
The data preparation phase included:
1. Loading and inspecting the data
2. Handling missing or duplicated entries
3. Converting date formats and extracting features like hour and month
4. Formatting product names and standardizing locations

### Exploratory Data Analysis
Key questions explored:
- What is the overall sales trend?
- Which products are top sellers?
- What are the most frequent product pairings?
- What time of day do people buy the most?
- Which cities generate the most revenue?

### Results

#### Customer Behavior
1. Atlanta ($196.13) and New York City ($195.59) have the highest average cart sizes. Boston has the lowest ($150).
2. Product pairings like “Vareebadd Phone + Wired Headphones” and “USB-C Charging Cable + Wired Headphones” are common.
3. Sales peak at 12 PM and 7 PM, showing when customers are most active.

#### Sales Insight
1. Total revenue is $34.49M from about 185.9K orders.
2. San Francisco and Los Angeles contribute the most to revenue, while New York ranks lower.
3. “20in Monitor” sells well across all months. “ThinkPad Laptop” peaks in April and May.
4. Top products by revenue: MacBook Pro Laptop, ThinkPad Laptop, 20in 4K Gaming Monitor.
5. Sales generally increase from March to July and drop toward the end of the year.

#### Forecast
1. Revenue dropped early in 2019, recovered, and grew into 2020.
2. Forecasts follow the historical trend and provide reliable estimates.

### Recommendations

#### Customer Behavior
1. Create product bundles based on common combinations to increase average order value.
2. For cities with lower cart sizes, use free shipping thresholds to increase order size.
3. Focus ad campaigns and customer support during peak sales hours.

#### Sales Strategy
1. Allocate sales and marketing budgets based on city performance.
2. Train staff to upsell accessories alongside high-value items like laptops.
3. Monitor monthly trends to plan inventory and marketing more effectively.
4. Offer discounts or bundles for underperforming products.

#### Forecasting
1. Regularly compare actual vs forecasted revenue to catch early warning signs.
2. Adjust business plans if the actual sales deviate significantly from the forecast.

### Limitations
1. The dataset contains only transaction data—no demographic or marketing info.
2. Time coverage is limited, so it may not reflect long-term changes in the market.

### References
- Dataset: Sales Data from Kaggle



