# 🏪 Super Store Sales Analysis & Forecasting – Power BI Report

## 📌 Project Overview

The **Super Store Sales Analysis & Forecasting** project is a Power BI dashboard designed to analyze historical sales performance and predict future sales trends. The report provides detailed insights into product categories, customer segments, shipping performance, and profit trends across regions, empowering business stakeholders to make data-driven decisions.

In addition to standard analysis, the project includes **15-day sales forecasting** using Power BI’s built-in analytics and time-series forecasting models.

---

## 🗂️ Data Source

The dataset used in this report was downloaded from **Kaggle**.
It contains comprehensive details about:

* Orders and Order IDs
* Product Categories and Subcategories
* Customer Segments
* Sales, Profit, and Quantity
* Shipping Modes and Delivery Dates
* Regional and State-wise Sales

**File Format:** `.csv`
**Tool Used:** Power BI Desktop

---

## 🧹 Data Cleaning & Preparation

All preprocessing tasks were handled within **Power Query Editor** in Power BI.

### Steps Performed:

1. **Data Import** – Loaded raw `.csv` file into Power BI.
2. **Data Cleaning**

   * Removed duplicate and null records.
   * Fixed spelling inconsistencies in regions, categories, and subcategories.
   * Checked and standardized data types (e.g., date, currency, numeric).
3. **Transformations**

   * Created relationships between data tables (Orders, Customers, Regions, etc.).
   * Extracted new columns for *Year*, *Month*, and *Quarter*.
   * Applied DAX formulas for key business metrics.
4. **Forecasting Model**

   * Used Power BI’s **Analytics Pane → Forecasting feature** on time series visuals.
   * Generated a **15-day forward forecast** for sales based on historical patterns.

---

## 📊 Dashboard Features & Visuals

### 1️⃣ Sales Overview

* **Total Sales, Orders, Profit, and Avg. Ship Days** KPIs
* Monthly and yearly sales trends (YoY comparison for 2019–2020)

### 2️⃣ Category & Subcategory Insights

* Sales by Category: *Technology*, *Office Supplies*, *Furniture*
* Top subcategories: *Phones*, *Chairs*, *Binders*, *Storage*

### 3️⃣ Regional & State Analysis

* Total sales distribution across **Central, East, South, and West** regions
* Interactive **map visualization** showing sales and profit by state

### 4️⃣ Payment & Segment Insights

* Payment mode breakdown: *Online*, *Cards*, *COD*
* Sales by segment: *Consumer*, *Corporate*, *Home Office*

### 5️⃣ Profitability & Performance

* Monthly profit analysis (YoY trends)
* Profit by region and product category

### 6️⃣ Forecasting Dashboard

* **15-Day Sales Forecast** visualization based on past performance
* Seasonal trend identification and predictive growth insights

---

## ⚙️ Tools & Technologies Used

* **Power BI Desktop** – Data Modeling, Visualization, Forecasting
* **Power Query Editor** – Data cleaning and transformation
* **Kaggle Dataset** – Source of raw sales data
* **DAX (Data Analysis Expressions)** – Used for KPIs and calculated fields

---

## 🚀 How to Use

1. Clone or download the repository:

   ```bash
   git clone https://github.com/<your-username>/Super-Store-Sales-Analysis.git
   ```
2. Open **`Super Store Sales Analysis.pbix`** using **Power BI Desktop**.
3. Explore interactive dashboards, filters, and forecasting visuals.

---

## 📈 Key Insights

* Technology and Office Supplies drive the highest revenue growth.
* *East* and *Central* regions account for major sales shares.
* Standard shipping is the most used mode, covering ~42% of total orders.
* Forecast indicates steady growth for the next 15 days, showing consistent demand across regions.

---

## 🧠 Learning Outcome

Through this project, the focus was on:

* Data cleaning and modeling using Power Query.
* Building business-focused KPIs using DAX.
* Implementing forecasting for time-series sales data.
* Creating an interactive, insight-rich business dashboard.

---

## 📬 Contact

**Author:** Lucky Manikpur
**Role:** Power BI Developer | Data Analyst
**Email:** [[manikpurilucky218@gmail.com](mailto:manikpurilucky218@gmail.com)]
**GitHub:** [https://github.com/lucky001118](https://github.com/lucky001118)

---

### ⭐ If you found this project insightful, please star the repository and share it with others!
