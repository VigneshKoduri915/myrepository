# Insurance-Dashboard

A Power BI dashboard designed to analyze insurance policies, customers, premiums, coverage amounts, and claims. The dashboard provides an interactive view of the insurance portfolio and helps identify trends across policy types, customer demographics, policy status, and claim status.


## Problem Statement

This dashboard helps an insurance company understand its overall policy portfolio and claims performance. It provides insights into the total premium collected, total coverage provided, and total claim amount, allowing management to monitor the financial performance of its insurance policies.

The dashboard also analyzes the distribution of customers by gender, policy types, claim status, and age groups. By studying these factors, the company can identify which insurance categories contribute the highest premium, understand the volume of active and inactive policies, and evaluate the status of claims.

The dashboard shows a total **Premium Amount of approximately 5.98M**, a total **Coverage Amount of approximately 600.55M**, and a total **Claim Amount of approximately 16.91M**.

The analysis can help the insurance company make better decisions regarding policy management, customer segmentation, claims handling, and future business strategies.

## Dataset

The dataset contains **10,004 insurance records** with information related to:

* Policy Number
* Customer ID
* Gender
* Age
* Policy Type
* Policy Start Date
* Policy End Date
* Premium Amount
* Coverage Amount
* Claim Number
* Claim Date
* Claim Amount
* Claim Status

## Steps Followed

* **Step 1:** Loaded the insurance dataset into Power BI Desktop. The dataset was provided in CSV format.

* **Step 2:** Opened Power Query Editor to inspect the dataset and verify the quality and structure of the available columns.

* **Step 3:** Checked the data types of important fields such as Policy Number, Customer ID, Age, Policy Type, Policy Start Date, Policy End Date, Premium Amount, Coverage Amount, Claim Amount, and Claim Status.

* **Step 4:** Reviewed missing and blank values, particularly in claim-related fields such as Claim Date.

* **Step 5:** Created the required calculations and measures to analyze total premium amount, coverage amount, and claim amount.

* **Step 6:** Created an age-group classification to analyze claim amounts across different customer age groups.

* **Step 7:** Added slicers for **Policy Number, Claim Number, and Customer ID** so that users can interactively filter the dashboard.

* **Step 8:** Added card visuals to display key performance indicators such as **Premium Amount, Coverage Amount, and Sum of Claim Amount**.

* **Step 9:** Created a visual showing the **number of customers by gender**, allowing the customer base to be compared between Male and Female customers.

* **Step 10:** Created a bar chart representing **Premium Amount by Policy Type** to identify which insurance categories generate the highest premium.

* **Step 11:** Added a donut chart showing the **count of Active and Inactive Policies** to provide an overview of the current policy portfolio.

* **Step 12:** Created a chart representing the **number of claims by Claim Status**, categorizing claims into Rejected, Settled, and Pending.

* **Step 13:** Created an age-group analysis showing the **Claim Amount by Age Group** to understand how claim amounts vary across different customer segments.

* **Step 14:** Added a matrix visual showing **Pending, Rejected, and Settled claim amounts by Policy Type**, providing a detailed comparison of claim performance across insurance categories.

* **Step 15:** Applied formatting, titles, borders, and a dark theme to create a clean and interactive dashboard.

* **Step 16:** The completed report can be published to **Power BI Service** for interactive viewing and analysis.

## Dashboard Snapshot

<img width="1263" height="706" alt="Image" src="https://github.com/user-attachments/assets/f0fdc20f-4389-4fe7-a0dc-d7e0a7c69868" />

## Insights

### 1. Overall Insurance Portfolio

* **Total Premium Amount:** approximately **5.98M**
* **Total Coverage Amount:** approximately **600.55M**
* **Total Claim Amount:** approximately **16.91M**
* The dataset contains **10,004 insurance records**.

### 2. Gender Distribution

* **Female customers:** 5,001
* **Male customers:** 5,003

The customer base is almost equally distributed between Male and Female customers.

### 3. Premium by Policy Type

The **Travel** policy category contributes the highest premium amount at approximately **2.5M**.

The approximate premium contribution by policy type is:

* **Travel:** 2.5M
* **Health:** 1.2M
* **Auto:** 1.0M
* **Life:** 0.7M
* **Home:** 0.6M

Thus, Travel insurance represents the largest contributor to the overall premium amount in the dashboard.

### 4. Active and Inactive Policies

The dashboard provides a comparison of active and inactive policies.

* **Active policies:** approximately 5.82K (**58.13%**)
* **Inactive policies:** approximately 4.19K (**41.87%**)

This indicates that the majority of policies in the portfolio are currently classified as active.

### 5. Claim Status

The dashboard categorizes claims into three statuses:

* **Rejected:** approximately 4.4K
* **Settled:** approximately 3.4K
* **Pending:** approximately 2.3K

The number of rejected claims is higher than the number of settled and pending claims, indicating an area that may require further investigation by the insurance company.

### 6. Claim Amount by Age Group

The dashboard analyzes claim amounts across different age groups, allowing the company to understand which customer segments account for a larger share of claim amounts.

This analysis can be useful for identifying customer segments with relatively higher claim exposure.

### 7. Claim Amount by Policy Type and Status

The detailed matrix compares **Pending, Rejected, and Settled** claim amounts across Auto, Health, Home, Life, and Travel policies.

This allows management to identify policy categories with higher claim values and understand how those claims are distributed across different claim statuses.

## Conclusion

The Insurance Dashboard provides a consolidated view of the company's insurance policies, customers, premiums, coverage, and claims. By combining financial KPIs with customer, policy, and claims analysis, the dashboard makes it easier to identify important trends and areas requiring attention.

The interactive Power BI report can support data-driven decision-making by helping management monitor policy performance, understand customer segments, analyze claim patterns, and evaluate the overall insurance portfolio.
