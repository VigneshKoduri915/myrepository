
# Superstore Sales Dashboard

A Tableau dashboard designed to analyze sales, profit, order quantity, regional performance, and customer segment contribution. The dashboard provides an interactive view of business performance across different regions and customer segments, while also identifying monthly order quantity trends and the relationship between sales and profit.


## Problem Statement

The objective of this dashboard is to understand overall sales and profitability performance and identify the regions, customer segments, and months contributing most to business performance.

The dashboard analyzes profit by region and customer segment, sales contribution by region, the relationship between sales and profit, and monthly order quantity trends. These insights can help businesses evaluate regional performance, understand customer profitability, and identify changes in order demand throughout the year.

## Dataset

The Superstore Sales dataset contains **8,399 order records** with information related to:

* Order ID and Order Date
* Order Priority
* Order Quantity
* Sales
* Discount
* Ship Mode
* Profit
* Unit Price
* Shipping Cost
* Customer Name
* City, State and Region
* Customer Segment
* Product Category and Sub-Category
* Product Name
* Product Container
* Product Base Margin
* Ship Date

The dataset covers four major regions: **Central, East, South, and West**.

## Tools & Technologies

* Tableau Public
* Microsoft Excel
* Data Visualization
* Business Intelligence
* Sales & Profit Analysis

## Steps Followed

### Step 1: Loaded the Dataset

The Superstore Sales dataset was imported into Tableau from the Excel workbook.

### Step 2: Data Preparation

The dataset was reviewed to understand fields related to sales, profit, order quantity, regions, customer segments, and dates.

### Step 3: Created Profit Analysis

A stacked bar chart was created to analyze **Profit by Region & Customer Segment**, allowing regional profitability to be compared across different customer segments.

### Step 4: Created Regional Sales Analysis

A donut chart was created to show **Sales Contribution by Region**, providing a percentage-based comparison of regional sales performance.

### Step 5: Created Sales vs Profit Analysis

A scatter plot was created to analyze the relationship between **Sales and Profit** across individual transactions.

### Step 6: Created Monthly Order Quantity Analysis

A line chart was created to analyze **Order Quantity by Month**, allowing seasonal changes in order demand to be identified.

### Step 7: Added Interactive Filtering

A **Unit Price Groups** filter was added to allow users to interactively analyze the dashboard based on different unit price groups.

## Dashboard Snapshot

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/1595b19d-9fd5-49e4-8b6a-f6f5aeb1455e" />


### 1. Profit by Region & Customer Segment

The stacked bar chart compares profitability across Central, East, South, and West regions while breaking the results down by customer segment.

Based on the dataset, total profit is approximately **$1.52M**.

Regional profit is approximately:

* Central: **$481.9K**
* South: **$422.5K**
* East: **$317.9K**
* West: **$299.5K**

Central generates the highest overall profit among the four regions.

### 2. Sales Contribution by Region

The dashboard shows the following regional sales contribution:

* Central: **31.51% — $4.70M**
* West: **24.47% — $3.65M**
* East: **22.91% — $3.42M**
* South: **21.12% — $3.15M**

The Central region contributes the largest share of total sales.

Overall sales across the dataset are approximately **$14.92M**.

### 3. Profit vs Sales

The scatter plot analyzes the relationship between sales and profit.

The visualization shows a generally positive relationship: transactions with higher sales values tend to generate higher profits, although there are several transactions where profitability varies significantly for similar sales levels.

This analysis helps identify unusual transactions and understand how sales volume translates into profitability.

### 4. Order Quantity by Month

The monthly trend shows variations in order quantity throughout the year.

The highest monthly order quantity occurs in **May with 21,273 units**, while the lowest occurs in **November with 16,251 units**.

Other notable months include:

* January: **17,952**
* March: **17,264**
* July: **17,929**
* September: **19,116**
* October: **18,278**
* December: **18,241**

The variation indicates that order demand changes throughout the year, with May showing the strongest monthly order volume.

## Key Insights

### 1. Regional Performance

Central is the strongest-performing region in terms of both sales and profit, generating approximately **$4.70M in sales** and **$481.9K in profit**.

### 2. Customer Segment Profitability

The dataset shows that the **Corporate customer segment** contributes the highest overall profit at approximately **$599.7K**, followed by Home Office, Small Business, and Consumer segments.

### 3. Sales and Profit Relationship

The scatter plot indicates a positive relationship between sales and profit, although individual transactions show considerable variation in profitability.

### 4. Order Demand

May records the highest order quantity at **21,273 units**, while November records the lowest at **16,251 units**, showing noticeable monthly variation in demand.

### 5. Overall Business Performance

The dataset contains approximately:

* **$14.92M Total Sales**
* **$1.52M Total Profit**
* **214.8K Total Units Ordered**
* **8,399 Order Records**

## Conclusion

The Superstore Sales Tableau Dashboard provides a consolidated view of sales and profitability performance across regions, customer segments, transactions, and months.

The analysis highlights **Central as the leading region**, **Corporate as the most profitable customer segment**, and **May as the highest-order month**. The Sales vs Profit analysis further helps understand the relationship between revenue generation and profitability.

Overall, the project demonstrates practical use of **Tableau data visualization, interactive filtering, regional analysis, customer segmentation, trend analysis, and sales-profit relationship analysis** to transform transactional data into meaningful business insights.
