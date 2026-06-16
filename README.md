# 🛒 BlinkIT Grocery Sales Dashboard | Power BI Project

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/DAX-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://learn.microsoft.com/en-us/dax/)
[![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://www.microsoft.com/excel)

## 📌 Project Overview
An interactive Power BI dashboard analyzing **8,523 product-level sales records** across BlinkIT's outlet network, built to identify which outlet types, locations, and item categories drive the most revenue. The dashboard uses DAX measures and slicers (Outlet Location Type, Outlet Size, Item Type) to let stakeholders filter and drill into sales performance in real time.

**Goal:** Pinpoint where BlinkIT's revenue is concentrated — by outlet tier, outlet size, and product category — to support inventory, outlet expansion, and category management decisions.

## 🎯 Business Problem
BlinkIT's leadership needs to know which outlets and products are working, and which aren't. Specifically:
- Which outlet tier (Tier 1/2/3) and outlet size drive the most sales?
- Which item categories and fat-content types sell the most?
- How has performance trended by outlet establishment year?
- Which outlet *type* (Grocery Store vs. Supermarket Type 1/2/3) is most efficient on a per-item basis?

## 📊 Dataset
| Field | Detail |
|---|---|
| Records analyzed | 8,523 product-outlet rows |
| Source file | [`BlinkIT Grocery Data.xlsx`](./data/BlinkIT%20Grocery%20Data.xlsx) |
| Fields | Item Type, Item Fat Content, Item Weight, Item Visibility, Outlet Size, Outlet Location Type, Outlet Type, Outlet Establishment Year, Sales, Rating |

## 🛠️ Tools & Approach
1. **Excel** – Initial review and validation of the raw 8,523-row dataset.
2. **Power Query** – Cleaned inconsistent category labels (e.g., "LF", "low fat", "Low Fat" all merged into a single Low Fat category).
3. **DAX** – Built measures for Total Sales, Average Sales, No. of Items, and Average Rating, plus calculated breakdowns by outlet dimension.
4. **Power BI** – Designed a single-page dashboard with KPI cards, a tab-style matrix (Total/Average Sales, No. of Items, Average Rating), donut and bar charts, and an area chart for the year-over-year trend.
   

## 📈 Dashboard Preview
![BlinkIT Dashboard](./images/blinkit%20dashboard%20image.png)


## 🔍 Key Insights (from the actual 8,523-row dataset)
- **Total Sales: $1.20M** across 8,523 items, with an average sale value of **$140.99** and an average product rating of **3.92**.
- 
- **Tier 3 outlets generate 40% more revenue than Tier 1** ($472K vs. $336K) despite being a "lower tier" classification — a strong signal that outlet tier doesn't equal outlet performance.
- 
- **Medium-sized outlets account for 42% of total sales** ($507K), outperforming both Small (37%) and High-size outlets (21%) — sales density, not outlet size, is the better predictor of revenue.
- 
- **2018 was a breakout year**, with outlets established that year generating **$205K in sales — roughly 53% above** the ~$130K average of surrounding years, pointing to a successful outlet cohort worth replicating.
- 
- **Supermarket Type 1 drives 66% of total revenue** ($787K of $1.20M) from just 5,577 of the 8,523 items — the single most important outlet format in the network.
- 
- **Fruits & Vegetables and Snack Foods are the top 2 categories**, together contributing **$353K (29%) of total sales**, while Seafood and Breakfast are the lowest performers, indicating a clear opportunity to rebalance shelf space and inventory toward fast-moving categories.
- 
- **Low Fat items outsell Regular items by ~75%** ($717K vs. $409K combined with mislabeled variants), reflecting a clear consumer preference worth factoring into procurement.

## 🚀 How to Use This Project
```bash
git clone https://github.com/ankitabisht-data-analyst/blinkit-grocery-sales-dashboard-powerbi.git
```
1. Open [`BLINKIT DASHBOARD.pbix`](./POWERBI/BLINKIT%20DASHBOARD.pbix) in Power BI Desktop.
2. Refresh the data source to point to [`BlinkIT Grocery Data.xlsx`](./data/BlinkIT%20Grocery%20Data.xlsx).
3. Use the slicers (Outlet Location Type, Outlet Size, Item Type) to explore the data interactively.

## 📈 Skills Demonstrated
`Power BI` `DAX` `Power Query` `Data Cleaning` `Excel` `Data Visualization` `Retail Analytics` `KPI Reporting` `Dashboard Design`

## 📬 Contact
**Ankita Bisht** — Data Analyst
[LinkedIn](https://www.linkedin.com/in/ankita-bisht09) · [GitHub](https://github.com/ankitabisht-data-analyst)

⭐ If you found this project useful, consider giving it a star!
