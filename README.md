# Blinkit Analysis Dashboard 📊

[Click here to view PowerBI dashboard](https://github.com/itzzkshitija/Blinkit-Analysis-Dashboard/blob/main/Blinkit_Dashboard.pbix)

[Click here to download the dataset](https://github.com/itzzkshitija/Blinkit-Analysis-Dashboard/blob/main/dataset.xlsx)

<img src="https://github.com/user-attachments/assets/720e9d06-cece-4eb0-9ff7-a6ae1746195e" width="900" height="500">

# Problem Statement 📌
Blinkit, as a dynamic on-demand grocery delivery service, grapples with the challenge of managing a vast array of transactions across diverse locations. The existing reporting system fails to provide a unified view of critical sales metrics, hindering effective decision-making. This leads to difficulty tracking operational efficiency, optimizing product offerings, and enhancing customer satisfaction.

# Solution: A Comprehensive PowerBI Dashboard ✅
To address these challenges, a robust PowerBI dashboard has been developed to consolidate real-time sales data. 
This data-driven solution offers valuable insights into:

<b>1. Order Volumes and Revenue Trends: </b> Gain a clear understanding of sales performance over time.

<b>2. Popular Products and Regional Demand: </b> Identify top-performing products and regional preferences to optimize inventory and marketing strategies.

<b>3. Delivery Performance: </b> Monitor delivery times, success rates, and potential bottlenecks to streamline operations.

# Steps in Project 👇
`Requirement Gathering / Business Requirements →` 

`Data Walkthrough  →` 

`Data Connection  →` 

`Data Cleaning / Quality Check  →` 

`Data Modeling  →` 

`Data Processing →` 

`DAX Calculations  →` 

`Dashboard Lay outing  →` 

`Charts Development and Formatting  →`  

`Dashboard / Report Development  →` 

`Insights Generation →`

## 1. Requirements Gathering / Business Requirements 

### KPI's Requirements
<b>1. Total Sales: </b> The overall revenue generated from all items sold

<b>2. Average Sales: </b> The average revenue per sale

<b>3. Number of Items: </b> The total count of different items sold

<b>4. Average Rating: </b> The average customer rating for items sold

### Chart's Requirements
<b>1. Total Sales by Fat Content</b>

<b>Objective:</b> Analyze the impact of fat content on total sales.
Additional KPI Metrics: Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with fat content.

Chart Type: Donut Chart

<b>2. Total Sales by Item Type</b> 
<b>Objective:</b> Identify the performance of different item types in terms of total sales.
Additional KPI Metrics: Access how other KPIs (Average Sales, Number of Items, Average rating) vary with fat content. 

Chart Type: Bar Chart

<b>3. Fat Content by Outlet for Total Sales </b> 
<b>Objective:</b> Compare total sales across different outlets segmented by fat content. 
Additional KPI Metrics: Assess how other KPIs (Average Sales, Number of Items, Average rating) vary with fat content. 

Chart Type: Stacked Column Chart

<b>4. Total Sales by Outlet Establishment</b> 
<b>Objective:</b> Evaluate how the age or type of outlet establishment influences total sales.

Chart Type: Line Chart

<b>5. Sales by outlet size</b> 
<b>Objective:</b> Analyze the correlation between outlet size and total sales

Chart Type: Donut Chart / Pie Chart

<b>6. Sales by Outlet Location</b> 
<b>Objective:</b> Assess the geographic distribution of sales across different locations. 

Chart Type: Funnel Map

<b>7. All Metrics by Outlet Type</b> 
<b>Objective:</b> Provide a comprehensive view of all key metrics (Total Sales, Average Sales, Number of Items, Average rating) broken down by different outlet types

Chart Type: Matrix Card

## 2. DAX Formulas
<b>1. Average Sales </b>

`Average Sales = AVERAGE('BlinkIT Grocery Data'[Total Sales])`

<b>2. Average Rating </b>

`Avg Rating = AVERAGE('BlinkIT Grocery Data'[Rating])`

<b>3. Total Sum of Sales </b>

`Total Sum Sales = SUM('BlinkIT Grocery Data'[Total Sales])`

<b>4. Number of Items </b>

`No of Items = COUNTROWS('BlinkIT Grocery Data')`

## 3. Insights 
<b>1. Sales Performance: </b>
<ul><li>Total Sales amount to $1.20M, with an Average Sale per transaction of $141.</li></ul>

<ul><li>Number of Items Sold is 8,523, indicating a broad inventory turnover.</li></ul>

<b>2. Customer Satisfaction: </b>
<ul><li>The Average Rating stands at 3.9, suggesting a satisfactory customer experience with potential for improvement.
</li></ul>

<b>3. Outlet Analysis: </b>
<ul><li>Outlet Establishment Trends show a consistent growth in sales, reaching $205K in recent years.</li></ul>

<ul><li>Medium-sized outlets contribute 42.27% to sales, totaling $444.79K.</li></ul>

<ul><li>Small outlets contribute 37.01% ($248.99K), while high-capacity outlets add 20.72% ($507.90K).</li></ul>

<ul><li>Tier 3 locations generate 71.3% of sales ($472.13K), followed by Tier 2 ($393.15K) and Tier 1 ($336.40K), emphasizing the strength in emerging markets.</li></ul>

<ul><li>Supermarkets lead with $788K in sales, followed by Grocery Stores at $152K.</li></ul>

<b>4. Product Analysis: </b> 
<ul><li>Fruits and Snack Foods are top sellers, each generating around $180K.</li></ul>

<ul><li>Household and Frozen Food items also perform well with $140K and $120K respectively.</li></ul>

<ul><li>Low-Fat Products contribute $776.32K, while regular fat products account for $ 425.36 K.</li></ul>

<b>5.Fat Content by Outlet Location:</b>
<ul><li>Tier 3 outlets have the highest sales for both Low Fat and Regular fat products, reinforcing their impact across product categories.</li></ul>


