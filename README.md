<div id="badges">
  <a href="https://www.linkedin.com/in/kshitija-chilbule-b98515309/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
</div>

# Blinkit Analysis Dashboard 📊

[Click here to view PowerBI dashboard](https://github.com/itzzkshitija/Blinkit-Analysis-Dashboard/blob/main/Blinkit_Dashboard.pbix)

[Click here to download the dataset](https://github.com/itzzkshitija/Blinkit-Analysis-Dashboard/blob/main/dataset.xlsx)

<img src="https://github.com/user-attachments/assets/720e9d06-cece-4eb0-9ff7-a6ae1746195e" width="900" height="500">

# Problem Statement 📌
Blinkit, a leading on-demand grocery delivery service, faces the unique challenge of managing high transaction volumes across numerous locations. The current reporting structure lacks a consolidated view of essential sales metrics, impacting decision-making and complicating efforts to track operational efficiency, optimize product offerings, and boost customer satisfaction. This project tackles these challenges head-on by conducting an in-depth analysis of Blinkit's sales performance, customer satisfaction metrics, and inventory distribution. Leveraging advanced KPIs and visualizations in Power BI, the goal is to deliver actionable insights and pinpoint opportunities for optimization, ultimately enhancing Blinkit’s operational excellence and driving customer loyalty.

# DAX Formulas
<b>1. Average Sales ➥ </b>
The average revenue per sale

`Average Sales = AVERAGE('BlinkIT Grocery Data'[Total Sales])`

<b>2. Average Rating ➥ </b>
The average customer rating for items sold

`Avg Rating = AVERAGE('BlinkIT Grocery Data'[Rating])`

<b>3. Total Sales ➥ </b>
The overall revenue generated from all items sold

`Total Sum Sales = SUM('BlinkIT Grocery Data'[Total Sales])`

<b>4. Number of Items ➥ </b>
The total count of different items sold

`No of Items = COUNTROWS('BlinkIT Grocery Data')`

# Insights 
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

<ul><li> Low-fat products contribute $776.32K, while regular fat products account for $ 425.36 K.</li></ul>

<b>5.Fat Content by Outlet Location:</b>
<ul><li>Tier 3 outlets have the highest sales for both low-fat and Regular fat products, reinforcing their impact across product categories.</li></ul>
