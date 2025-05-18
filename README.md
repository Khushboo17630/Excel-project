
# 🛍️ Online Clothing Store — 2024 Sales Analysis & 2025 Growth Plan


> **Objective**  
> Build an interactive Excel dashboard that summarises *2024* sales, reveals customer behaviour, and guides strategic actions for *2025*.

---

## 📑 Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Business Questions](#business-questions)
4. [Methodology](#methodology)
5. [Insights](#insights)
6. [Recommendations](#recommendations)
7. [Dashboard Sneak‑Peek](#dashboard)

## Project Overview

An e‑commerce fashion retailer wants a clear picture of **who buys what, when and where**. Using Microsoft Excel PivotTables and dashboards we answered key questions, uncovered patterns and produced actionable insights to steer 2025 marketing and inventory decisions.

## Dataset

| Column        | Description                                   |
| ------------- | --------------------------------------------- |
| `Order_ID`    | Unique order number                           |
| `Order_Date`  | Date of purchase (YYYY‑MM‑DD)                 |
| `Customer_ID` | Unique customer identifier                    |
| `Gender`      | *Male* / *Female*                             |
| `Age`         | Age of customer in years                      |
| `State`       | Shipping state within India                   |
| `Category`    | Product category                              |
| `Channel`     | Sales channel (Amazon, Flipkart, Myntra…)     |
| `Quantity`    | Units sold                                    |
| `Sales`       | ₹ value of the order                          |

*(sample data provided in `/data/2024_sales.xlsx`)*

## Business Questions

- **Who purchases more — men or women?**
- **Month‑over‑month**: which month recorded the **highest sales and orders**?
- What is the **best‑selling category**?
- Which **top 5 states** contribute most to sales?
- Which **sales channel** is the biggest revenue driver?
- How are **age and gender** related to ordering behaviour?

## Methodology

1. **Data Understanding**
2. **Data Cleaning**
   - Removed blanks, duplicates & errors  
   - Fixed inconsistent category labels
3. **Data Processing**
   - Added derived columns (e.g. *Month Name*, *Age Group*)
4. **Visualisation & Dashboard**
   - Built PivotTables & PivotCharts  
   - Added slicers for Year, Category, State & Channel  
   - Packaged into a scroll‑free one‑page dashboard

## Insights

| # | Finding |
| - | ------- |
| 1 | **Women account for ~64 % of total sales** in 2024. |
| 2 | **May** recorded the highest orders **and** sales value. |
| 3 | The **“Tops & Tees”** category tops the chart. |
| 4 | **Maharashtra, Karnataka, Tamil Nadu, Telangana, Uttar Pradesh** lead sales contribution. |
| 5 | **Amazon, Flipkart & Myntra** together deliver ~80 % of revenue. |
| 6 | The **30‑49 age group** buys the most across segments. |

## Recommendations

🎯 **Target** women aged **30‑49** residing in the top 5 states with platform‑specific promotions (coupons, free shipping) on **Amazon, Flipkart & Myntra**.  
📦 Increase inventory for high‑turn categories.  
📅 Run campaigns during May‑June to capitalise on peak buying season.

## Dashboard 

![Dashboard](https://github.com/user-attachments/assets/1d099265-7b43-49e3-97fb-c92ae65013b6)

