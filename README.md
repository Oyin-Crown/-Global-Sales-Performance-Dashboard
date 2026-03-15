# Global-Sales-Performance-Dashboard

An interactive Excel dashboard built from 51,000+ rows of global sales data, analyzing revenue, profitability, discount behavior, and segment performance across multiple markets and regions.

## **Overview**

This dashboard was built entirely in Microsoft Excel, using Power Query for data cleaning and transformation, PivotTables, PivotCharts, and Slicers. It transforms raw transactional sales data into clear, actionable visual insights, helping answer key business questions like:

Which regions and categories drive the most revenue and profit?

How do discounts impact profitability?

Which customer segments are most valuable?

Where are we losing money on orders?

## **Features**
 
 KPI Cards

i. Total Sales- Overall revenue across all orders

ii. Total Profit- Net profit after costs and discounts

iii. Total Orders- Volume of transactions

iv. Avg Profit Margin- Overall profitability efficiency

v. Avg Shipping Delay- Operational performance indicator

vi. Avg Discount Rate- Pricing discipline metric

## **Charts & Visuals**

📈 Sales Trend Over Time - Monthly sales line chart showing peaks and slow seasons

🌍 Sales by Region - Horizontal bar chart ranking regions by revenue

💰 Profit vs Sales Comparison - Combo chart comparing revenue and profitability side by side

🍩 Sales Share by Segment - Donut chart showing Consumer, Corporate, and Home Office contribution

🎯 Discount Impact on Profit - Combo chart revealing how discounting erodes margins

## **Interactivity**

1. Slicers for Region, Category, and Segment 

2. Timeline for Months and Years

3. All charts and KPI cards respond to slicer selections simultaneously

## **Dataset**

| Detail | Info |
|---|---|
| Total Records | 51,290 orders |
| Columns | 27 fields |
| Date Range | 2011 – 2014 |
| Markets | APAC, EU, US, Africa, LATAM |
| Key Fields | Sales, Profit, Discount, Shipping Cost, Profit Margin, Order Date, Region, Category, Segment |

## **Tools Used**

i. Microsoft Excel

ii. Power Query (Power BI in Excel) - Data cleaning and transformation

iii. Pivot Tables

iv. PivotCharts

v. Slicers

vi. Timeline

vii. Conditional Formatting

viii. Excel Formulas (SUM, AVERAGE, COUNTIF, COUNTA)

## **Key Insights**

1. Sales grew every year: Revenue increased consistently from $2.26M in 2011 to $4.30M in 2014, nearly doubling over the four years, showing strong overall business growth.

2. Central region dominates: The Central region led all regions with $2.82M in sales and $311K in profit. However, Southeast Asia and EMEA reported weak profit margins despite reasonable sales, suggesting high costs or heavy discounting in those regions.

3. High discounts are destroying profit: Orders in the High Discount band generated $1.93M in sales but produced a loss of -$814K, with an average profit margin of -61%. In contrast, No Discount orders achieved a healthy 26.5% average margin. This is the single biggest profitability risk in the business.

4. 1 in 4 orders is loss-making: 24.5% of all orders (12,544 out of 51,290) had a negative profit margin, meaning the business is losing money on roughly a quarter of everything it sells.

5. Consumer segment leads in revenue: The Consumer segment accounts for 51.5% of total sales, followed by Corporate at 30.3% and Home Office at 18.3%. All three segments are profitable, but Corporate and Home Office deliver stronger margins relative to their sales share.

6. Q4 is peak season: November and December are consistently the strongest months, generating $1.55M and $1.58M, respectively. February is the weakest month at $543K; nearly 3x lower than peak months.

 ## Summary
This dashboard was built to analyze global sales performance across regions, segments, and product categories using 51,290 orders spanning 2011 to 2014. The data was first cleaned and transformed using Power Query in Excel before being analyzed through Pivot Tables and visualized through interactive PivotCharts.

The analysis explored five key areas: sales trends over time, regional performance, profit vs sales comparison, customer segment share, and the impact of discounting on profitability. Together, these visuals paint a clear picture of where the business is thriving, where margins are being eroded, and which segments and regions deserve the most strategic attention.

The most critical finding is that discounting strategy is the biggest threat to profitability - high discount orders are not just low margin, they are actively loss-making at scale. Combined with the fact that 24.5% of all orders have negative margins, there is a strong case for reviewing discount policies, particularly in underperforming regions like Southeast Asia and EMEA.

This project demonstrates the use of Excel as a full end-to-end analytics tool, from raw data cleaning in Power Query to an interactive executive-ready dashboard.

## How to Use

1. Download the .xlsx file from this repository
2. Open in Microsoft Excel
3. Navigate to the Dashboard sheet
4. Use the slicers to filter by Region, Category, Segment, or Year
5. All charts and KPI cards will update automatically
