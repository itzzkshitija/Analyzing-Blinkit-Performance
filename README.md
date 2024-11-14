<div id="badges">
  <a href="https://www.linkedin.com/in/kshitija-chilbule-b98515309/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
</div>

# Blinkit Analysis Dashboard 📊

## Table of Contents
<div style="text-decoration: none;">
[Problem Statement](#problem-statement)
<br>
[Dax Formulas](#dax-formulas)
<br>
[Overall Insights](#overall-insights)
<br>
[ Chart Wise Insights and Improvements](#chart-wise-insights-and-improvements)
<br>
</div>

<img src="https://github.com/user-attachments/assets/720e9d06-cece-4eb0-9ff7-a6ae1746195e" width="900" height="500">

[Click here to view PowerBI dashboard](https://github.com/itzzkshitija/Blinkit-Analysis-Dashboard/blob/main/Blinkit_Dashboard.pbix)

[Click here to download the dataset](https://github.com/itzzkshitija/Blinkit-Analysis-Dashboard/blob/main/dataset.xlsx)

## Problem Statement 
Blinkit, a leading on-demand grocery delivery service, faces the unique challenge of managing high transaction volumes across numerous locations. The current reporting structure lacks a consolidated view of essential sales metrics, impacting decision-making and complicating efforts to track operational efficiency, optimize product offerings, and boost customer satisfaction. This project tackles these challenges head-on by conducting an in-depth analysis of Blinkit's sales performance, customer satisfaction metrics, and inventory distribution. Leveraging advanced KPIs and visualizations in Power BI, the goal is to deliver actionable insights and pinpoint opportunities for optimization, ultimately enhancing Blinkit’s operational excellence and driving customer loyalty.

## DAX Formulas
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

## Overall Insights 
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
<ul><li>Tier 3 outlets have the highest sales for both low-fat and Regular products, reinforcing their impact across product categories.</li></ul>


## Chart Wise Insights and Improvements

### 1️⃣ Fat Content Chart
![image](https://github.com/user-attachments/assets/39258c3e-aa21-42d1-a985-fe52d1d52098)

<b>Low Fat Product: </b> 
<ul><li> Low-fat products dominate sales, generating $776.32K, which indicates a stronger customer preference for healthier, lower-fat options.</li></ul>

<b>Regular Fat Products: </b>
<ul><li>Regular fat items contribute $425.36K to total sales. Though less popular than low-fat options, they still hold a significant share, suggesting there is demand for a variety of fat content levels.</li></ul>

<b>Implications for Inventory: </b>
<ul><li>Stocking more low-fat products, especially in popular categories like snack foods or dairy, could cater to customer demand and increase sales.</li></ul>

<ul><li>Regular fat items should still be maintained for customer segments that prefer them, especially in Tier 2 and Tier 3 locations where demand is highest.</li></ul>

### 2️⃣ Fat by Outlet Chart
![image](https://github.com/user-attachments/assets/2576706d-3fc4-4193-9366-efe19c427589)

<b>Sales Distribution by Fat Content: </b> 
<ul><li> The total sales are split between "Low Fat" and "Regular" categories, showing the demand across different fat-content products.</li></ul>

<ul><li> Low-fat products generate the highest sales, totaling $776.32K, indicating a preference for healthier, low-fat options among customers.</li></ul>

<b>Sales by Outlet Tier: </b>
<ul><li>Tier 3 Outlets (likely in smaller or rural areas) show the highest total sales for both low-fat and Regular products, with $0.31M sales.</li></ul>

<ul><li>Tier 2 Outlets follow with $0.25M sales.</li></ul>

<ul><li>Tier 1 Outlets (likely in urban areas) show the lowest total sales at $0.22M</li></ul>

<b>Customer Preferences Across Tiers: </b>
<ul><li>Both Low Fat and Regular categories show consistent demand across all tiers, but Tier 3's strong sales in both categories suggest that, while low-fat items are generally more popular, regular-fat options still have substantial demand, especially in less urban areas.</li></ul>

### 3️⃣ Item Type Chart
![image](https://github.com/user-attachments/assets/6c571333-9943-4cfc-8a9a-80dc62ae57f6)

<b>Top-Selling Categories:</b> 
<ul><li>Fruits and Snack Foods dominate with sales of approximately $0.18M each. This suggests a strong customer preference for fresh produce and convenient, ready-to-eat snacks.</li></ul>

<ul><li>Household Items and Frozen Foods also perform well, bringing in about $0.14M and $0.12M respectively. This indicates that customers also rely on these outlets for essentials beyond food.</li></ul>

<b>Moderate Sales Categories:</b>
<ul><li>Dairy Products and Canned Goods follow, with sales of $0.10M and $0.09M respectively, showing a steady demand for these staples.</li></ul>

<ul><li>Baking Goods and Health and Wellness Products are also noteworthy, suggesting that customers may prioritize wellness-oriented products, especially if they are accessible and affordable.</li></ul>

<b>Lower-Selling Categories:</b>
<ul><li>Hard Drinks, Starchy Foods, Breakfast Items, and Seafood show comparatively low sales, each ranging between $0.02M and $0.04M. These items might be less frequently purchased, either due to lower demand or because they are considered specialty items in certain areas.</li></ul>

<ul><li>Soft Drinks also show lower sales, possibly due to a shift in preference toward healthier options.</li></ul>

<b>Customer Trends:</b> 
<ul><li>The dominance of fresh produce and snack foods indicates that convenience and quick meal prep are important for this customer base.</li></ul>

<ul><li>Steady sales across household essentials and wellness products reflect customer reliance on these outlets for daily needs and health-conscious purchases.</li></ul>


### 3️⃣ Outlet Establishment Chart
![image](https://github.com/user-attachments/assets/2a29d1e9-9250-49b9-86b4-0ce97375be45)

<b>Sales Growth Over Time: </b> 
<ul><li>Starting around 2012, the sales values show a gradual but steady increase through the years, indicating consistent growth in the outlet’s customer base and/or market presence.</li></ul>

<ul><li>Peak growth appears in the year 2020 with total sales reaching $205K, which may indicate a spike in demand, potentially due to increased reliance on local outlets during the COVID-19 pandemic.</li></ul>

<b>Recent Plateau:</b> 
<ul><li>After 2020, sales slightly decreased and stabilized around $130K to $132K from 2021 onward. This suggests that while the initial growth period was strong, the outlet's sales might now be reaching a plateau.</li></ul>

<ul><li>The leveling off could be due to market saturation or increasing competition, highlighting the need for innovative strategies or expansion into new product lines or services to reignite growth.</li></ul>

<b>Potential for Expansion:</b>
<ul><li>The highest recorded sales levels around 2020 could serve as a benchmark for future sales targets.</li></ul>

<ul><li>Focusing on new promotional strategies, customer loyalty programs, or even expanding into untapped locations could help surpass the current plateau and boost sales.</li></ul>

### 4️⃣ Outlet Size Chart
![image](https://github.com/user-attachments/assets/71f06e02-c9d7-4483-b4f9-c3ff4cf56f71)

<b>Sales by Outlet Size: </b> 
<ul><li>Small Outlets make up the largest share of total sales, generating $507.90K, or about 42.27% of all sales. This indicates that smaller outlets are highly accessible and popular among customers, perhaps due to their convenience or proximity in residential areas.</li></ul>

<ul><li>Medium Outlets contribute $444.79K in sales, which is approximately 37.01% of the total. These outlets perform nearly as well as small outlets, showing that mid-sized stores effectively meet customer needs with a balance of variety and convenience.</li></ul>

<ul><li>High-Size Outlets have the lowest total sales at $248.99K (around 20.72%), suggesting that larger outlets may be less frequently visited or located in areas with less demand.</li></ul>


<b>Customer Preferences: </b>
<ul><li>The preference for Small and Medium outlets likely reflects customers' desire for convenience, quick trips, and accessible locations. Smaller outlets may serve densely populated residential areas, while medium-sized outlets might offer more variety while still being conveniently located.</li></ul>

<ul><li>The lower sales in High outlets could be attributed to several factors, including fewer high-size locations, higher distances from customers, or possibly less reliance on large-format stores in this market.</li></ul>

<b>Opportunities for Improvement:</b>
<ul><li>Expanding the presence of Small and Medium outlets could cater to the customer preference for accessible, quick shopping experiences.</li></ul>

<ul><li>High-size outlets might benefit from strategies to increase foot traffic, such as targeted promotions, community engagement events, or diversifying product offerings to draw a broader range of customers.</li></ul>


### 5️⃣ Outlet Location Chart
![image](https://github.com/user-attachments/assets/425b6149-7c7f-4df7-8c70-0e6f2c1634f9)

<b>Sales Distribution by Location Tier: </b>
<ul><li>Tier 3 Locations lead in total sales, generating $472.13K, which suggests strong customer engagement in these areas. Tier 3 outlets, typically located in smaller towns or rural regions, may serve as primary shopping destinations, leading to higher dependence on these outlets.</li></ul>

<ul><li>Tier 2 Locations follow with $393.15K in sales, indicating steady demand in semi-urban areas, where outlets meet the needs of a moderately dense population.</li></ul>

<ul><li>Tier 1 Locations contribute the least, with $336.40K in sales, possibly due to increased competition in urban areas, where customers have a wider variety of shopping options.
</li></ul>

<b>Customer Dependency Patterns:</b>

<ul><li>The high sales in Tier 3 and Tier 2 locations reflect customer reliance on these outlets, which may be the most accessible sources of goods in these areas.</li></ul>

<ul><li>Tier 1’s lower sales suggest that urban customers might prefer other shopping options, such as larger retail chains, online shopping, or niche stores, which could impact foot traffic in these outlets</li></ul>


<b>Opportunities for Tier-Specific Strategies:</b>

<ul><li>For Tier 3: Expanding inventory to meet the high demand or offering local promotions could capitalize on the strong customer reliance on these outlets</li></ul>

<ul><li>For Tier 2: Consider a broader product selection or targeted marketing to further increase Tier 2’s solid customer base.</li></ul>

<ul><li>For Tier 1: Since these urban outlets face more competition, adopting online order options, unique product offerings, or loyalty programs might attract a steady urban customer base.</li></ul>


### 6️⃣ Outlet Type Chart
<b>Sales by Outlet Type:</b>
<ul><li>Supermarket Type1 is the clear leader, generating $788K in sales, with 5,577 items sold. This high performance suggests that customers view this type as a comprehensive one-stop shop, likely offering a wide range of products that meet various needs.</li></ul>

<ul><li>Grocery Stores rank second, with $152K in sales and 1,083 items sold, followed by Supermarket Type2 and Supermarket Type3, each contributing around $131K in sales with approximately 928-935 items sold. This distribution suggests that smaller stores like grocery outlets still attract customers, perhaps due to their convenience and accessibility.</li></ul>

<b>Customer Engagement and Satisfaction:</b>
<ul><li>The average rating for all outlets is consistently around 3.9, suggesting that customers generally have a positive experience, regardless of outlet type.</li></ul>

<ul><li>Item visibility is highest for grocery stores at 0.10, compared to 0.06 for supermarket types. This higher visibility could indicate that grocery stores have more prominent shelf placements or that items are easier to locate, enhancing the shopping experience in these stores.</li></ul>

<b>Sales Strategy by Outlet Type:</b>
<ul><li>Supermarket Type1 outlets are the biggest revenue drivers. It may be beneficial to invest further in these outlets, whether through expanding product variety, adding promotional discounts, or focusing on customer loyalty programs.</li></ul>

<ul><li>Grocery Stores could increase their overall sales by leveraging their higher item visibility and customer convenience. Targeted marketing to emphasize their role as quick-access shops might attract more foot traffic.</li></ul>

<b>Opportunities for Improvement:</b>
<ul><li>Supermarket Type2 and Type3 outlets, despite having lower sales, still maintain a steady customer base. Optimizing these outlets with exclusive product lines or specialty items could create a unique shopping experience, potentially boosting their appeal and sales.</li></ul>
