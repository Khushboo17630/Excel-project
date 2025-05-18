# Excel-project

𝑷𝒓𝒐𝒋𝒆𝒄𝒕 𝑶𝒃𝒋𝒆𝒄𝒕𝒊𝒗𝒆:- Online clothing store wants to create an annual sales report for 2024. So that, they can understand their customers and grow more sales in 2025.

Here I have set some questions to forecast future sales on the basis of different categories by using Pivot Table in Excel.

📝𝑸𝒖𝒆𝒔𝒕𝒊𝒐𝒏𝒔 :-
 
1. Who purchase more men vs women in 2023?

2. Compare order vs sales using a single chart and find which month got the highest sales and order.

3. Highest selling category?

4. Top 5 States contributing to the Sales?

5. Which channel is contributing to maximum Sales?

6. Relation between Age and Gender based on number
 of orders.


𝑺𝒕𝒆𝒑𝒔 𝒇𝒐𝒍𝒍𝒐𝒘𝒆𝒅 :

 1. Understanding the data.

 2. Data cleaning( Removing blank, Duplicates, Errors, Removing irrelevant Data, incomplete data within a dataset, etc).
 
 3. Data processing/ Manipulation(Creating new Attributes for better data analysis).

 4. Data visualization( Creating Dashboard with Slicer).


🔎 𝑴𝒂𝒋𝒐𝒓 𝒊𝒏𝒔𝒊𝒈𝒉𝒕𝒔 :

1. Womens buying behaviour : Womens are more likely to buy (about 64% of total sales).

2. Top performing States: Maharashtra, Karnataka, Tamilnadu, Telangana, Uttar Pradesh are identified as top 5 states in terms of sales.

3. Amazon, Flipkart, and Myntra channels are maximum contributing( about 80%) 

4. Age Group Influence : Adult age group (30 to 49 years) is max contributing.

𝑭𝒊𝒏𝒂𝒍 𝒄𝒐𝒏𝒄𝒍𝒖𝒔𝒊𝒐𝒏: 

 Target women👩 customers of age group( 30 to 49 years) living in Uttarpradesh, Maharashtra, Karnataka, Telangana and Tamilnadu by showing advertisement,  offers and coupans available on Amazon, Flipkart and 
 Myntra. 


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
7. [Dashboard Sneak‑Peek](#dashboard-sneak-peek)
8. [Repository Structure](#repository-structure)
9. [How to Reproduce](#how-to-reproduce)
10. [Contributing](#contributing)
11. [License](#license)

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

## Dashboard Sneak‑Peek

![Dashboard](https://github.com/user-attachments/assets/1d099265-7b43-49e3-97fb-c92ae65013b6)

![Status](https://img.shields.io/badge/Status-Completed-green)
> *(Insert screenshot `images/dashboard.png` here)*

## Repository Structure

