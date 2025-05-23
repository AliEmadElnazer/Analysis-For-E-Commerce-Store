﻿# Analysis-For-E-Commerce-Store
---

# 📊 E-Commerce Store Analysis Dashboard

### Created by: Ali Emad – Data Analyst

## 🔍 Project Overview

This project provides a comprehensive analysis of an **E-Commerce store's performance** across multiple years and regions. The analysis was developed using **Power BI** to visually explore key metrics such as **Sales**, **Profit**, **Quantity Sold**, and **Shipping Costs**, enabling strategic insights into business operations and market performance.

---

## 📦 Dataset

The dataset includes transactional sales data for multiple product categories and regions over the span of 4 years (2012 to 2015). Each record contains detailed information such as:
- Sales amount
- Profit
- Quantity
- Shipping cost
- Order date
- Market/Region
- Product category
- Ship mode

---

## 🧹 Data Cleansing Process

Before building the dashboard, several data preparation and cleaning steps were carried out:

1. **Removed Null Values:**
   - Cleaned records with missing or null values in critical columns like `Sales`, `Profit`, `Region`, and `Order Date`.

2. **Standardized Text Formatting:**
   - Unified case for categorical fields such as market names and product categories (e.g., “usca” ➝ “USCA”).

3. **Converted Data Types:**
   - Changed `Order Date` to a proper `Date` format.
   - Converted numerical fields (`Sales`, `Profit`, `Shipping Cost`) from text to decimal for proper aggregation.

4. **Created New Columns:**
   - Extracted **Year** from `Order Date` to enable trend analysis.
   - Calculated **%Profit** using the formula:  
     `Profit % = (Profit / Sales) * 100`

5. **Filtered Duplicates:**
   - Removed duplicate transactions based on `Order ID`.

---

## 📈 Dashboard Overview

The dashboard consists of three main pages:

### 1. **Home Page**

> A visually engaging cover page displaying the title and creator of the dashboard.

---

### 2. **Overview Page**

This page gives a high-level summary of the entire e-commerce store's performance:

- ✅ **KPIs:**
  - **Total Sales:** 12.64M  
  - **Total Profit:** 1.47M  
  - **Profit Percentage:** 11.61%  
  - **Total Quantity Sold:** 178K  
  - **Total Shipping Cost:** 1.36M

- 📍 **Market Distribution:**
  - A **pie chart** showing the number of orders per market (Asia Pacific, Europe, USCA, LATAM, Africa).
  - Market share highlights:
    - Asia Pacific leads with 27.89% of total orders.
    - Africa has the smallest share with 8.94%.

- 🌍 **Geographic Visualization:**
  - An interactive **map** showing the global sales distribution across markets.

- 📦 **Sales by Category:**
  - A bar chart showing:
    - Technology: 4.7M
    - Furniture: 4.1M
    - Office Supplies: 3.8M

---

### 3. **Market Page**

This section dives deeper into market trends over the years:

- 📅 **Trend Line (2012–2015):**
  - Visualizes **profit growth over time**.
  - Steady increase year-over-year from 250K in 2012 to 500K in 2015.

- 📊 **Category Filter:**
  - Allows dynamic filtering between Furniture, Office Supplies, and Technology.

- 🌍 **Market Filter:**
  - Analyze performance for individual markets: Africa, Asia Pacific, Europe, LATAM, and USCA.

---

## 🛠 Tools Used

- **Power BI** – Data visualization and interactive dashboard creation.
- **Microsoft Excel** – Data preprocessing and transformation.
- **Power Query** – Data cleansing and transformation logic.

---

## 🚀 How to Use

1. Download or clone the repository.
2. Open the `.pbix` file in Power BI Desktop.
3. Explore filters and visuals to derive insights based on market, category, or year.

---

## 📌 Key Insights

- Asia Pacific dominates the number of orders and shows high profitability.
- Technology products bring in the highest sales, followed by Furniture.
- There’s a clear year-over-year profit growth trend, indicating healthy business expansion.

---

