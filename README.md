# 🚀 Power BI Sales Analytics Dashboard

This project is a complete end-to-end **Sales Dashboard** built in **Power BI**, covering all stages from data preparation to delivering actionable insights and business recommendations.

---

## 📁 Project Overview

This dashboard analyzes sales transactions to uncover trends, regional performance, product demand, and fulfillment efficiency.

### ✅ Steps Followed:

1. **Data Preparation**
   - Imported raw data from `Sales.xlsx`
   - Cleaned and transformed data using **Power Query**
   - Split into:
     - `FactSales` – transactional data
     - `DimProducts` – product category and hierarchy
     - `DimDate` – created date table with Year, Month, Quarter, Day
     - `DimStatus` – order status types
     - `DimShipMethods` – shipping methods
     - `DimTerritories` – sales territories

2. **Data Modeling**
   - Designed a **Star Schema** model
   - Built relationships between fact and dimension tables
   - Created **product hierarchy**: Category → Subcategory → Product Name
  
     > 📌 Star Schema 
- `https://github.com/HagerSalahRamadan/Power-BI-Sales-Analytics-Dashboard/blob/main/4.Data%20Modeling%2C%20Dax%20Measures%20and%20Product%20Hierarchy.PNG`

3. **DAX Measures**
   - Orders
   - Order Details
   - Total SubTotal
   - Total Tax
   - Total Freight
   - Total Due
   - % Shipped Orders 
   - % Not Shipped Orders 

4. **Visualizations**
   - 📊 **Sales Overview Dashboard**
   - 📦 **Orders Analysis Dashboard**
   - 🛍️ **Product Performance Dashboard**
   - Included KPIs, time series, bar charts, and hierarchy slicers
---

## 📷 Dashboards Preview

> 📌 Dashboards 
- `[1.Sales Overview.PNG](https://github.com/HagerSalahRamadan/Power-BI-Sales-Analytics-Dashboard/blob/main/1.Sales%20Overview.PNG)`
- `[2.Orders Analysis.PNG](https://github.com/HagerSalahRamadan/Power-BI-Sales-Analytics-Dashboard/blob/main/3.Product%20Performance.PNG)`
- `[3.Product Performance.PNG](https://github.com/HagerSalahRamadan/Power-BI-Sales-Analytics-Dashboard/blob/main/3.Product%20Performance.PNG)`
---

## 📌 Key Insights

- 🗓️ **March and May show peak order volumes** → clear seasonality in sales
- 🚚 **Canada and Northwest regions generate high revenue** but also have high freight costs
- 🛒 **Bikes lead in revenue**, while *Accessories* and *Clothing* underperform
- ❗ **76% of orders are not yet shipped** → major fulfillment bottleneck
- 🧭 *Central* and *Southwest* regions contribute less to overall revenue

---

## 💡 Business Recommendations

- 🔹 Launch **early-bird promotions** before peak months
- 🔹 Create **localized marketing campaigns** to boost sales in weaker regions and categories
- 🔹 Optimize **freight and shipping logistics** in high-cost territories
- 🔹 Improve **order fulfillment efficiency** to reduce unshipped orders

---

## 🛠️ Tools Used

- Power BI
- Power Query 
- DAX
- Star Schema Modeling


---

## 📈 Project Outcome

This project helped me develop skills in:
- Data Modeling  
- Power BI Visualizations  
- DAX Measures  
- Data Storytelling  

---

### 🔗 Contact
For any questions Contact via email **hagersalah.r39@gmail.com**.

