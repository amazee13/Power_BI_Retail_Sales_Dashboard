# Power_BI_Retail_Sales_Dashboard

# Retail Sales Performance Dashboard (Power BI)


## Business question
Which regions, products and customer segments drive profit, and are discounts hurting margin?

## Data
Sample dataset of 1,500 retail orders (UK, 2024–2025) with sales, cost, profit, discount, region and customer segment.

## What I did
- Cleaned data in Power Query: removed 12 duplicate orders, replaced missing segments, set data types, added a Discount Band column
- Built a star schema with a custom DAX Date table
- Wrote 7 DAX measures including Profit Margin %, Sales LY and YoY Growth %
- Designed an interactive one-page report with slicers, drill-down and cross-filtering

## Key insights
- Laptops are the most profitable product (£126.9K profit). Pens and Binders contribute under 1%, so focus marketing on Technology.
- Orders with 15–20% discounts earn a 17.8% margin, compared with 32.4% with no discount, so review the discount policy.
- East grew about 35% to become the top region in 2025 (£199.7K, 28% of sales). North led in 2024.
- Total sales grew 20.8% year over year, from £587.6K to £709.6K.

## Tools
Power BI Desktop, Power Query, DAX
