# Retail-Sales-Analysis-Using-Power-BI

## Project Objective
To analyze sales data from multiple store locations in Abuja, Nigeria, with the goal of uncovering key business insights related to revenue generation, profitability, discount strategies, and customer behaviour - ultimately for improved performance.

## Dataset used
https://github.com/Godswill1234/Retail-Sales-Analysis-Using-Power-BI/blob/main/Sales%20Analysis.pbix
https://github.com/Godswill1234/Retail-Sales-Analysis-Using-Power-BI/blob/main/Sales%20Table.xlsx

## Questions
- Which product category has the highest profit margin?				
- Which store location generates the most revenue?				
- How does customer type affect average discount?				
- Between online and offline sales, which is more profitable?				

## Key Points Covered:
-	Product category contribution to overall profit efficiency (via Profit Margin %)
-	Revenue trends across time and store locations
-	Impact of sales channel (Online vs Offline) on profitability
-	Product category contribution to total profit and margin
-	Effect of discounts on customer behavior
-	Use of DAX for calculated fields (Profit, Margin %, Discount %)

## Dashboards


## Procedures:
Data Preparation:
Two raw tables were used: Sales and Products.
Uncalculated fields like Profit, Profit Margin, and Discount % were added using DAX.

Data Modelling:
Established relationships between Sales and Product tables using ProductID.

Calculated Measures:
-	Total Sales = Quantity x Unit Price
-	Net Sales = Total Sales – Discount
-	Total Cost = Cost Price x Quantity
-	Profit = Net Sales - Total Cost
-	Profit Margin (%) = Profit ÷ Net Sales
-	Discount (%) = Discount Amount ÷ Total Sales

Visual Design:
-	Bar/Column Charts for comparison (Product, Store, Customer Type)
-	Line Chart with Forecast for trends
-	Slicers for filtering by date, customer type, and product category
-	Cards for KPIs (Revenue, Profit, Margin %)


## Conclusion:
This sales analysis empowered stakeholders to:
-	Identify high-performing stores and underperformers
-	Understand how discount strategies affect different customer types
-	Make data-driven decisions on pricing, promotions, and inventory
-	Predict future sales outcomes and prepare for high-volume seasons
-	Communicate insights clearly using dynamic visuals and narratives
