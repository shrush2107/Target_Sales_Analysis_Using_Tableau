# 🧮 Target Retail Analytics Dashboard (Tableau) – 2020 to 2023

This project showcases **interactive Tableau dashboards** built using **synthetic retail data** adapted to resemble Target's business model. The dashboards are designed to explore customer behavior, sales trends, and geographic performance from **2020 to 2023**.

The goal was to learn and apply **core to advanced Tableau skills** across KPI visualization, interactivity, and storytelling for business decision-making.



## 📸 Dashboard Previews

### 💰 Sales Dashboard
![image](https://github.com/user-attachments/assets/55391065-dee6-4c87-9bdf-6658cbd7869a)
![image](https://github.com/user-attachments/assets/79761a86-9f86-498f-9517-72f8814fcfb7)


### 👥 Customer Dashboard
![image](https://github.com/user-attachments/assets/98bc2900-5d70-4884-a9f6-a9030f2f1685)

---

## 🧠 What I Learned in Tableau

This project helped me gain hands-on experience with a wide range of Tableau features:

### 🔌 Data Connection & Prep
- Connected Tableau to an **Excel workbook** with multiple tables (Orders, Customers, Products).
- Performed data cleaning and **joined tables** using relationships and custom joins.
- Ensured **date consistency** to enable time-based filtering across 2020–2023.

### 🧮 Calculated Fields
- Created **custom KPIs**: Profit per Customer, Sales per Order, YoY Growth.
- Defined **logical buckets** for customer frequency (e.g., orders = 1, 2, 3...).
- Calculated **average lines** (e.g., average weekly sales/profit).

### 🎛️ Filters
- Added **global filters** for:
  - Year (2020 to 2023)
  - Product Subcategory
  - State/Region
- Used **context filters** to drive responsive tooltips and charts.

### 🧪 Parameters
- Implemented **parameter-driven navigation** to switch between:
  - Sales Dashboard
  - Customer Dashboard
- Parameter selection automatically changes views while maintaining filters.

### 📊 Visualization Techniques
- Dual-axis line charts to show **current vs previous year trends**.
- Highlighted **Top 10 customers** based on dynamic current year profit.
- Added **sales distribution by state** and **donut chart for regional splits**.
- Built a **sub-category breakdown** showing 2023 vs 2022 comparisons with profit/loss bars.

### 🧰 Tooltip Design
- Customized tooltips to display additional dimensions (e.g., Order Date, Sales, Profit).
- Used **bar chart tooltips** for comparative context in time-series plots.

---

## KPIs & Metrics

### 🛒 Sales Dashboard

#### 🔹 Performance KPIs
- **Total Sales**   
- **Sales Growth vs PY**  
- **Total Profit**  
- **Profit Growth vs PY**  
- **Total Quantity Sold** 
- **Quantity Growth vs PY**  

#### 🔹 Product-Level Metrics
- **Sales by Sub-Category:** Ranked by sales volume across product types  
- **Profit/Loss by Sub-Category:** Profitability segmented by product lines  
- **Top-Performing vs Underperforming Products:** Based on profit contribution  

#### 🔹 Time-Based Metrics
- **Sales Over Time (Monthly/Weekly):** Line chart with average sales benchmark  
- **Profit Over Time:** Line chart with average profit benchmark  
- **Above/Below Average Periods:** Highlighted to show trends  

#### 🔹 Geographic Insights
- **Quantity Sold by State:** Interactive map view  
- **Quantity Distribution by Region:** Donut chart showing regional breakdown  


### 👥 Customer Dashboard

#### 🔹 Customer-Level KPIs
- **Total Customers**   
- **Customer Growth vs PY**   
- **Average Sales per Customer** 
- **Growth in Sales per Customer vs PY** 
- **Total Orders**  
- **Order Growth vs PY** 

#### 🔹 Customer Performance Metrics
- **Top 10 Customers by Profit:** Ranked list with profit, sales, and order count  
- **Customer Lifetime Sales & Profit:** Year-to-date values  
- **Distinct Orders by Customer:** Shows repeat behavior  

#### 🔹 Behavioral Segmentation
- **Customer Distribution by Order Frequency:** Histogram (e.g., 1-time vs repeat buyers)

---

## 📈 Key Features

| Feature                      | Description |
|-----------------------------|-------------|
| 📊 Dual-Axis KPIs           | Compare metrics across years with trendlines |
| 🧍 Customer Segmentation     | Frequency distribution by number of orders |
| 🔁 Dashboard Navigation     | Parameterized toggle between Customer and Sales dashboards |
| 🧩 Subcategory Insights     | Compare 2022 vs 2023 performance with clear loss/profit encoding |
| 🗺️ Geo Visualization        | State-wise sales density using map |
| 🎯 Top Customer Table       | Ranked customers with drilldown capability |
| 🔎 Tooltips + Highlighting  | Enhanced user experience with contextual info |
| 📅 Time Period              | Full coverage of **2020 to 2023**, filterable |
| 📥 State & Region Filters   | Dynamic charts that respond to geography selections |

---

## 🧪 Data Summary

- Data is **completely synthetic**, designed to replicate common retail patterns (sales, orders, customers, product lines).

![image](https://github.com/user-attachments/assets/4c268ae4-27ab-4b5b-ad06-4621ad5da71c)


---

## 📝 Disclaimer

This is a **portfolio project** created for learning purposes. All data is **synthetic** and not affiliated with Target Corporation.




















Live on: https://public.tableau.com/app/profile/shrushti.agarwal/viz/TargetStoreDashboard/SalesDashboard
