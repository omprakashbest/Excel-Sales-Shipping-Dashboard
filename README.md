# 📊 Sales & Shipping Dashboard

An Excel-based interactive dashboard that visualizes sales performance, shipping metrics, and customer insights across product categories and US states — covering data from **2014 to 2017**.

---
[Dashboard Image](./Dashboard_Image.png)

---

## 📁 File

[📥 Download Sales_Dashboard.xlsx](./Sales_Dashboard.xlsx)

---

## 🗂️ Workbook Structure

The workbook contains the following sheets:

| Sheet | Description |
|---|---|
| `Dashboard` | Main visual dashboard — product trend sparklines and top 4 customers by quarterly sales |
| `SparkPivot` | Pivot table powering product trend and top customer sparkline charts |
| `SalesPivot` | Sales breakdown by salesperson (Bob, John, Richard) and product category |
| `SalesPersonPivot` | Monthly and quarterly sales by salesperson for 2015 |
| `AvgPriceShip` | Average shipping cost per item by ship mode and container type |
| `AvgDayToShip` | Average days to ship by order priority and shipping mode |
| `MapCustomerPivot` | Total sales by US state (used for geographic sales map) |
| `MapShipPivot` | Average shipping days by US state (used for geographic shipping map) |
| `Dimension Tables` | Reference data — SKU-to-category mapping, customer-to-state mapping, ship modes, and order priority sort orders |

---

## 📌 Key Metrics Tracked

- **Quarterly & yearly sales** by product category (Bikes, Components, Accessories, Clothing)
- **Top 4 customers** by quarterly revenue (C660, C610, C669, C469)
- **Sales by salesperson** — Bob, John, and Richard
- **Shipping cost analysis** by ship mode (Delivery Truck, Regular Air, Express Air) and container type
- **Days to ship** by order priority (Critical, High, Medium, Low, Not Specified)
- **Geographic distribution** of sales and shipping performance across 39 US states

---

## 🔑 Data Overview

- **Products:** 5 categories — Bikes, Components, Accessories, Clothing (1,000+ SKUs)
- **Customers:** 795+ unique customers across the US (identified by customer IDs C001–C795+)
- **Geography:** Sales data spanning 39 US states
- **Time Range:** 2014 Q1 – 2017 Q4
- **Salespeople:** Bob, John, Richard (total sales ~$743K)
- **Ship Modes:** Delivery Truck, Regular Air, Express Air
- **Order Priorities:** Critical, High, Medium, Low, Not Specified

---

## 💡 Insights Highlighted

- **Bikes** dominate revenue across all years, consistently driving 80–90% of total quarterly sales
- **Components** are the second-largest category; **Accessories** and **Clothing** contribute minor revenue
- **John** leads in total sales (~$301K), followed by **Bob** (~$259K) and **Richard** (~$182K)
- **Regular Air** is the most common shipping mode; **Delivery Truck** has the lowest average shipping cost for bulk containers
- **Critical** priority orders ship fastest on average (~1.78 days via Delivery Truck)
- **New Mexico, Florida, and Georgia** are top-performing states by total sales revenue

---

## 🛠️ Tools Used

- **Microsoft Excel** — Pivot Tables, Sparklines, Dashboard Layout

---

## 🚀 How to Use

1. Open `Sales_Dashboard.xlsx` in Microsoft Excel (2016 or later recommended).
2. Navigate to the **Dashboard** sheet to view the summary visual.
3. Use the **SparkPivot** and other pivot sheets to explore underlying data.
4. The **Dimension Tables** sheet provides reference lookups for SKUs, customers, states, and priority codes.

---

## 📂 Potential Enhancements

- Migrate to **Power BI** or **Tableau** for interactive filtering and drill-down
- Connect to a live database instead of static pivot tables
- Add slicers to the Dashboard sheet for year/quarter filtering
- Expand geographic map visualization with a filled choropleth map

---

## 📄 License

This project is for educational/portfolio purposes.
