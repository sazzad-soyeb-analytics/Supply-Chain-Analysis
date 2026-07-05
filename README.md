# 🌍 Global Retail Sales — Exploratory Data Analysis

An end-to-end retail analytics project — from raw data to business-ready insights — built using **Python, SQL, and Power BI**.

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Problem Statement](#-problem-statement)
- [Dataset Details](#-dataset-details)
- [Tools Used](#-tools-used)
- [Methodology](#-methodology)
- [Key Insights](#-key-insights)
- [Dashboard Preview](#-dashboard-preview)
- [Results & Conclusion](#-results--conclusion)
- [Author & Contact](#-author--contact)

---

## 📊 Overview

This project analyzes a **global retail sales dataset** covering orders, pricing, marketing, logistics, suppliers, warehouses, and customer segments across five world regions. The goal is to move beyond raw numbers and answer real business questions — using **Python** for exploratory analysis and statistical testing, **SQL** for targeted business queries, and **Power BI** for an interactive, decision-ready dashboard.

## ❓ Problem Statement

Retail businesses generate large volumes of transactional and operational data, but that data only creates value once it's turned into decisions. This project examines revenue drivers, marketing and pricing effectiveness, logistics and supply chain performance, and customer/discount behavior across regions — testing common assumptions (like "lower price wins" or "more traffic means more sales") against what the data actually shows.

## 🗂 Dataset Details

| Property | Detail |
|---|---|
| **Total columns** | 43 |
| **Key domains** | Orders, Marketing, Pricing, Logistics, Warehouse, Supplier |
| **Customer segments** | Retail, Wholesale |
| **Regions covered** | North America, Latin America, Europe, Middle East, Asia Pacific |
| **Source file** | `retail_cleaned.csv` (cleaned via Excel Power Query) |

### Key Columns Used in the Analysis

| Column | Description |
|---|---|
| `Order_ID` | Unique identifier for each customer order |
| `Date` | Date the order was placed |
| `Product_Category` | Category of the product sold (e.g. Electronics, Fashion, Home, Beauty, Sports) |
| `Brand` | Brand associated with the product |
| `Region` | Broad geographic region of the order |
| `Country` | Specific country within the region |
| `Customer_Segment` | Retail or Wholesale customer type |
| `Product_Price` | Selling price of the product |
| `Marketing_Spend` | Marketing budget allocated to the product/category |
| `Conversion_Rate` | Website conversion rate associated with the order |
| `Inventory_Level` | Stock level of the product at the time of the order |
| `Shipping_Mode` | Mode of shipping used (Air, Sea, or Ground) |
| `Total_Logistics_Cost` | Total logistics cost incurred for the order |
| `Carbon_Emission` | Carbon emissions generated from shipping the order |
| `Service_Level` | Delivery service level indicator |
| `Demand_Next_Period` | Forecasted demand for the following period |
| `Warehouse_ID` | Identifier for the warehouse handling the order |

*(The remaining columns provide additional supporting detail on pricing, supplier performance, and operational metrics.)*

## 🛠 Tools Used

- **Python** — Pandas, NumPy, Matplotlib, Seaborn
- **MySQL** — business-question-driven SQL queries
- **Power BI** — interactive multi-page dashboard
- **Excel Power Query** — initial data cleaning

## 🔍 Methodology

The project follows a three-stage workflow, with each tool used for what it does best:

- **Python** — Data preparation, exploratory data analysis (EDA), and statistical hypothesis testing (t-tests, ANOVA, z-tests) to validate patterns seen in the data.
- **SQL** — A set of MySQL queries written to directly answer specific business questions around revenue, marketing, logistics, and warehouse performance.
- **Power BI** — A multi-page interactive dashboard built on the combined findings, designed for ongoing, at-a-glance business monitoring.

## 💡 Key Insights

- Total revenue reached **$8B** from around **25,000 orders**, well balanced across regions, product categories, and brands.
- **Latin America** generates the highest regional revenue, but brand leadership shifts significantly from one region to another.
- Revenue earned outside festival periods is roughly **6x higher** than festival-period revenue — growth is driven by steady, year-round demand.
- Company pricing closely matches competitor pricing, meaning **service and delivery reliability**, not price, is the real differentiator.
- Average discount (~20%) is consistent across brands and categories, but has **little effect on sales volume**.
- Higher marketing spend and website traffic don't reliably translate into more sales — Electronics draws strong traffic but underperforms on conversion.
- Only about **23% of deliveries arrive on time**, with delays occurring across every region and shipping mode — a systemic issue, not a local one.
- Supplier reliability averages **85%** and is consistent globally, with Europe trailing slightly.
- **Warehouse 4** has the highest stockout rate, and **Fashion** is the most stockout-prone category.
- Average product return rate is **~8%**, fairly consistent worldwide, with Japan, Canada, India, the UK, and France leading in returns.
- Retail and Wholesale customers place a similar number of orders but differ meaningfully in average sales value.

## 📈 Dashboard Preview

### 1. Introduction 
![Introduction](Dashboard%20ScreenShots/1.Introduction.png)

### 2. Executive Overview
![Executive Overview](Dashboard%20ScreenShots/2.Executive_Overview.png)

### 3. Sales & Revenue Analysis
![Sales Analysis](Dashboard%20ScreenShots/3.Sales.png)

### 4. Marketing & Pricing Analysis
![Marketing Analysis](Dashboard%20ScreenShots/4.Marketing.png)

### 5. Logistics & Supply Chain Analysis
![Logistics Analysis](Dashboard%20ScreenShots/5.Logistics.png)

### 6. Warehouse & Inventory Analysis
![Warehouse Analysis](Dashboard%20ScreenShots/6.Warehouse.png)



## ✅ Results & Conclusion

This project turned a 43-column, multi-region retail dataset into a clear, decision-ready picture of the business. The analysis confirmed that pricing is already competitive, revenue is well diversified rather than concentrated in one market, and discounting is doing little to drive extra sales — while it also surfaced a genuine, systemic issue in on-time delivery performance that cuts across every region and shipping mode.

Together, the Python EDA, SQL queries, and Power BI dashboard tell a consistent story: the business's biggest opportunity isn't pricing or marketing spend, but tightening logistics reliability and using data-backed, region-specific strategies for brands, categories, and customer segments.

📄 **Additional Documentation:**  
- **`Supply_Chain_Insights.pdf`** – Project overview, business objectives, dashboard insights, and key findings.
- **`Supply_Chain_Strategic_Recommendations.pdf`** – Strategic recommendations and actionable business improvement initiatives based on the analysis.

## 👤 Author & Contact

**Sazzad Soyeb**
Data Analyst

- 🔗 LinkedIn: [Sazzad Soyeb](https://www.linkedin.com/in/sazzadsoyeb/)
- 💻 GitHub: [sazzad-soyeb-analytics](https://github.com/sazzad-soyeb-analytics)
- 📧 Email: sazzadsoyebprof@gmail.com

⭐ If you found this project useful, consider giving the repository a star!
