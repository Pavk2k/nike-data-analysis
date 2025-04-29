# Nike Retail Partners (USA) – Product Financials Dashboard

This repository contains an Excel dashboard built to analyze Nike’s retail product performance across U.S. regions, states, and cities. The dashboard uses pivot tables, slicers, and time series forecasting to provide dynamic and visual insights into Nike’s operational and financial data.

---

## 📄 Files Included

- `Nike_data.xlsx`: Contains raw data, multiple pivot tables, dynamic slicers, and visual dashboards for interactive financial analysis.

---

## 🧹 Raw Data Overview

The **Raw Data** tab contains sales transaction records with the following fields:
- **Retailer Name and ID**
- **Invoice Date** (sales date)
- **Region, State, City** (location details)
- **Product Type** (e.g., Men's Apparel, Women's Street Footwear)
- **Price per Unit**
- **Units Sold**
- **Total Sales**
- **Operating Profit and Operating Margin**

The data spans throughout 2021 and captures different product categories across U.S. locations.

---

## 📊 Key Dashboards and Analysis

### 1. Sales Overview
- **Pivot Table** summarizing total sales by Region.
- **Slicers** to filter by Region, State, City, and Invoice Quarter.
- **Bar Chart** showing the regional sales distribution.

### 2. Sales by Retailer
- **Pivot Table** analyzing total sales by Retailer and Product.
- **Line Chart** visualizing the sales trend across different retailers.

### 3. Product Performance
- **Horizontal Bar Chart** ranking products based on sales figures.
- **Pivot and slicer** enabled view for product category analysis.

### 4. Revenue Trend
- **Monthly Sales Analysis** shown via a Line Chart.
- **Pivot Table** aggregating sales figures month by month.

### 5. Profitability Analysis
- **Operating Profit** breakdown by Region and Product.
- **Line Chart** displaying profit contributions across categories and regions.

### 6. Revenue Forecast
- **Time Series Forecasting** built inside Excel:
  - Future sales projection with **confidence intervals**.
  - Dynamic line chart for historical and forecasted sales.

---

## 🔍 How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/nike-retail-financials.git
