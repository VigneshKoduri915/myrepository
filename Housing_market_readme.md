# Housing Sales Dashboard

A Power BI dashboard designed to analyze housing sales performance, property prices, sales trends, regional performance, and the relationship between offer prices and purchase prices. The dashboard provides an interactive view of the housing market across different regions, sales types, property characteristics, and time periods.

## Problem Statement

The objective of this dashboard is to provide a comprehensive overview of housing sales performance and help identify important trends in the housing market.

The dashboard analyzes total housing sales, sales performance by region, average price per square meter, median changes between offer and purchase prices, units sold, year-over-year sales growth, and sales performance across different sales types.

It also provides insights into how housing prices vary across regions and how different types of property transactions contribute to overall sales. The relationship between offer price and purchase price is visualized to understand how closely final purchase prices follow the initial offer prices.

The dashboard uses time-based analysis to evaluate recent sales performance, including Last 12 Months Sales, Total YTD Sales, and Year-over-Year Sales Growth. These measures help identify changes in market performance over time and provide a better understanding of current housing sales trends.

## Dataset

The Housing Data dataset contains 100,000 housing transaction records with information related to:

* Date
* Quarter
* House ID
* House Type
* Sales Type
* Year Built
* Purchase Price
* Percentage Change Between Offer and Purchase Price
* Number of Rooms
* Square Meters
* Price per Square Meter
* Address
* ZIP Code
* City
* Area
* Region
* Nominal Interest Rate
* Annual Inflation Rate
* Yield on Mortgage Credit Bonds

The dataset covers housing transactions from 1992 to 2024 and contains four major regions: Jutland, Zealand, Fyn & islands, and Bornholm.

## Tools & Technologies

* Power BI Desktop
* Power Query
* DAX
* Microsoft Excel
* Data Visualization
* Business Intelligence

## Steps Followed

### Step 1: Loaded the Housing Dataset

The housing dataset was imported into Power BI from an Excel workbook containing 100,000 housing transaction records.

### Step 2: Data Preparation

Power Query was used to inspect the dataset, review the available columns, and ensure that fields such as dates, prices, regions, sales types, and property information were appropriately structured for analysis.

### Step 3: Data Type and Data Quality Check

Important fields such as Date, Purchase Price, Square Meters, Price per Square Meter, Sales Type, Region, and percentage-based economic indicators were reviewed.

Missing values were also identified in fields such as City, Annual Inflation Rate, and Yield on Mortgage Credit Bonds.

### Step 4: Created DAX Measures

Several DAX measures were created to calculate the major KPIs and analytical metrics used throughout the dashboard.

The main measures include:

* Average Price SQM
* Last 12 Month Sales
* Median Sales Price Change
* Offer to SQM Ratio
* Sales by Region
* TotalYTD Sales
* Units Sold in Latest Year & Quarter
* YOY_Sales_Growth

### Step 5: Time-Based Sales Analysis

DAX time-intelligence calculations were used to analyze sales performance across different periods.

The dashboard includes:

* Last 12 Months Sales
* Year-to-Date Sales
* Year-over-Year Sales Growth
* Units Sold during the latest period

These calculations make it possible to evaluate recent market performance and identify changes in sales over time.

### Step 6: Offer Price vs Purchase Price Analysis

A scatter plot was created to analyze the relationship between offer price and purchase price.

This helps determine how closely actual purchase prices correspond to the initial offer prices and highlights transactions where the difference between the two is relatively large.

### Step 7: Sales Price Change Analysis

The Median Sales Price Change measure is used to compare changes between offer and purchase prices across regions.

This allows the dashboard to highlight regions where the median sales price movement is relatively higher or lower.

### Step 11: Key Performance Indicators

Card visuals were created to highlight important housing market KPIs, including:

* Units Sold in Latest Year & Quarter
* 12 Months Sales

These KPIs provide a quick summary of the current sales performance.

### Step 12: Dashboard Design

The report was organized into two dashboard pages.

**Page 1 – Housing Market Overview**

This page focuses on the overall housing market and includes:

* Median Sales Price Change by Region
* Units Sold in Latest Year & Quarter
* 12 Months Sales
* Offer Price vs Purchase Price
* YOY Sales Growth by Sales Type

**Page 2 – Sales Performance**

This page provides a deeper analysis of:

* Sales by Region
* Key Influencers
* Detailed sales transaction data
* Offer to SQM Ratio by Sales Type
* Average Price SQM by Region

The dashboard uses consistent formatting, titles, borders, cards, charts, and a light pink/blue visual theme to create an interactive and easy-to-understand report.

## DAX Measures Used

### 1. Average Price SQM

Calculates the average housing price per square meter and is used to compare property price levels across different regions.

### 2. Last 12 Month Sales

Calculates the total purchase value generated during the most recent 12-month period, allowing recent housing market performance to be monitored.

### 3. Median Sales Price Change

Calculates the median change between the offer price and final purchase price, helping analyze price negotiation patterns across regions.

### 4. Offer to SQM Ratio

Used to analyze the relationship between housing sales and square-meter pricing across different sales categories.

### 5. Sales by Region

Calculates total housing sales by geographical region and is used in the regional sales visualization.

### 6. TotalYTD Sales

Uses year-to-date analysis to calculate cumulative sales from the beginning of the year up to the selected/latest period.

### 7. Units Sold in Latest Year & Quarter

Calculates the number of housing transactions sold during the relevant latest year/quarter period used by the dashboard.

### 8. YOY_Sales_Growth

Calculates the year-over-year change in sales performance, allowing sales growth or decline to be compared across different sales types.

## Dashboard 1 Snapshot

<img width="1920" height="948" alt="Image" src="https://github.com/user-attachments/assets/a035c578-952f-4d36-9d68-3b567dd3babc" />


### Page 2 – Sales Performance

The second page provides a more detailed view of housing sales.

It includes:

* Sales by Region
* Key Influencers
* Transaction-level sales information
* Offer to SQM Ratio by Sales Type
* Average Price SQM by Region

The regional sales visual shows that **Zealand and Jutland contribute the largest portions of total housing sales**, while Fyn & islands and Bornholm contribute comparatively smaller amounts.

The Average Price SQM analysis also highlights substantial differences between regions, with **Zealand having the highest average price per square meter** among the displayed regions.

## Key Insights

### 1. Regional Sales Performance

Zealand and Jutland account for the largest share of housing sales in the dataset.

The approximate total purchase value by region is:

* Zealand: 94.97B
* Jutland: 81.48B
* Fyn & islands: 14.92B
* Bornholm: 1.24B

This indicates that housing transactions are heavily concentrated in Zealand and Jutland.

### 2. Average Price per Square Meter

The dashboard shows significant variation in average price per square meter between regions.

The approximate average values are:

* Zealand: 20.85K
* Jutland: 13.51K
* Fyn & islands: 13.62K
* Bornholm: 10.60K

Zealand has the highest average price per square meter, while Bornholm has the lowest among the four regions.

### 3. Sales Type Distribution

Regular sales represent the dominant sales category in the dataset, followed by family sales, other sales, and auctions.

This indicates that conventional property transactions form the majority of housing activity represented in the dataset.

### 4. Recent Housing Market Performance

The Last 12 Month Sales KPI indicates approximately **11.48B in sales** for the latest 12-month period available in the dataset.

This KPI provides a useful snapshot of recent market activity compared with the historical transaction data.

### 5. Offer Price vs Purchase Price

The scatter plot demonstrates a strong positive relationship between offer price and purchase price.

As the offer price increases, the purchase price generally increases as well. However, several transactions deviate from the overall relationship, indicating cases where the final purchase price differs more significantly from the initial offer price.

### 6. Year-over-Year Sales Growth

The YOY Sales Growth analysis shows differences in sales performance between sales types.

In the displayed dashboard:

* Auction shows positive YOY growth.
* Regular Sale shows negative YOY growth.
* Other Sale shows negative YOY growth.
* Family Sale shows the largest negative YOY change.

This provides an indication that sales performance varies considerably depending on the type of transaction.

### 7. Regional Price Differences

The Average Price SQM visual highlights the substantial difference in property pricing between regions.

Zealand has the highest average price per square meter, which suggests comparatively higher property valuations in the region.

## Dashboard 2 Snapshot
<img width="1920" height="955" alt="Image" src="https://github.com/user-attachments/assets/5b1b9f4d-eed0-4f63-a4e9-d5d4ab084628" />


## Conclusion

The Housing Sales Dashboard provides a consolidated view of housing market performance by combining sales KPIs, regional analysis, property pricing, sales types, offer-to-purchase price relationships, and time-based sales trends.

By using Power BI, Power Query, and DAX, the dashboard transforms 100,000 housing transaction records into an interactive analytical report.

The dashboard helps identify the regions generating the highest sales, compare price levels per square meter, evaluate recent sales performance, analyze year-over-year changes, and understand the relationship between offer prices and actual purchase prices.

Overall, the project demonstrates the use of data cleaning, DAX calculations, time-intelligence analysis, KPI development, and interactive data visualization to support data-driven understanding of the housing market.
