# 🏥 Healthcare Sales & Purchase Analytics

## 📌 Project Overview

This project analyzes healthcare/pharmacy sales and purchase transaction data to identify important business insights related to sales performance, purchases, products, healthcare categories, trends, staff performance, suppliers, GST, and business KPIs.

The project demonstrates how raw healthcare transaction data can be transformed into meaningful insights for business decision-making.

---

## 🎯 Project Objectives

1. Analyze overall healthcare sales performance.
2. Identify monthly and yearly sales trends.
3. Find the highest-performing healthcare categories.
4. Identify top-selling products.
5. Analyze staff-wise sales performance.
6. Analyze supplier-wise purchase performance.
7. Calculate important business KPIs.
8. Analyze sales and purchase GST.
9. Provide actionable business recommendations.

---

## 🗂️ Dataset

The project uses the `healthcare.xlsx` Excel dataset.

### Dataset Sheets

| Sheet | Description |
|---|---|
| `weekly_sales` | Healthcare sales transactions |
| `weekly_purchase` | Healthcare purchase transactions |
| `summary` | Pre-calculated summaries and KPIs |
| `Dashboard` | Dashboard and visualization area |

### Sales Data Includes

- Bill Number
- Date
- Customer Name
- Staff
- Product Name
- Category
- Quantity
- MRP
- GST
- Net Amount

### Purchase Data Includes

- GRN Number
- Date
- Supplier Name
- Product Name
- Category
- Quantity
- Purchase Price
- GST
- Total Amount

---

## 🛠️ Tools & Technologies

- **Microsoft Excel**
- **Pivot Tables**
- **Excel Charts**
- **Data Cleaning**
- **Data Analysis**
- **KPI Analysis**
- **Dashboarding**

---

## 📊 Key Analysis

### 1. Sales Performance

Analyzed total sales and compared sales performance across different years and months.

Key metrics include:

- Total Net Sales
- Number of Bills
- Total Quantity Sold
- Unique Customers
- Monthly Sales
- Yearly Sales

### 2. Category Analysis

Analyzed sales contribution from different healthcare categories to identify categories generating the highest revenue.

### 3. Product Analysis

Identified top-performing products based on net sales to understand fast-moving products, high-revenue products, demand, and inventory priorities.

### 4. Staff Performance

Analyzed sales contribution by individual staff members to understand sales distribution and performance differences.

### 5. Supplier Analysis

Analyzed purchase transactions by supplier to identify major suppliers, purchase value, supplier concentration, and opportunities for supplier negotiation.

### 6. GST Analysis

Analyzed sales GST and purchase GST as part of the overall transaction analysis.

> Note: GST figures are analytical values from the dataset and should not be treated as final tax liability without proper accounting adjustments.

---

## 📈 Dashboard

The project includes an Excel-based dashboard containing business KPIs and visualizations.

### Dashboard Preview

![Healthcare Dashboard](screenshots/dashboard.png)

### Sales Analysis

![Sales Analysis](screenshots/sales_analysis.png)

### Purchase & Supplier Analysis

![Purchase Analysis](screenshots/purchase_analysis.png)

---

## 🔍 Key Insights

- A small number of healthcare categories contribute a significant portion of total sales.
- Fast-moving products require continuous inventory monitoring.
- Monthly sales fluctuate across the year, making trend analysis useful for inventory planning.
- Supplier purchase concentration should be monitored to reduce supply-chain risk.
- Staff sales contribution can be tracked using regular KPI reporting.
- Data reconciliation is important because pre-calculated summary figures may differ from raw transaction totals.

---

## 💡 Business Recommendations

### Inventory Management
Maintain adequate stock levels for high-demand and fast-moving products.

### Reorder Planning
Set reorder levels for top-selling products to reduce stock-out risk.

### Supplier Management
Review supplier concentration and negotiate better pricing for high-volume purchases.

### Sales Monitoring
Track monthly sales KPIs through a regularly updated dashboard.

### Data Quality
Ensure dashboard and summary KPIs reconcile with the original transaction-level data.

### Profitability Analysis
Add cost-of-goods and margin calculations in future versions to evaluate actual profitability.

---

## 📁 Project Structure

```text
Healthcare-Sales-Purchase-Analytics/
│
├── healthcare.xlsx
├── README.md
│
├── report/
│   ├── Healthcare_Sales_Purchase_Project_Report.pdf
│   └── Healthcare_Sales_Purchase_Project_Report.docx
│
└── screenshots/
    ├── dashboard.png
    ├── sales_analysis.png
    └── purchase_analysis.png
```

---

## 📌 Skills Demonstrated

- Excel
- Data Cleaning
- Data Transformation
- Data Analysis
- Pivot Tables
- KPI Development
- Dashboard Creation
- Business Intelligence
- Trend Analysis
- Sales Analysis
- Purchase Analysis
- Inventory Analysis
- Data Visualization
- Business Insights

---

## 🚀 Future Improvements

- Develop an interactive Power BI dashboard
- Perform SQL-based analysis
- Automate data cleaning using Python
- Add profit and profit-margin analysis
- Implement inventory forecasting
- Analyze customer purchasing behavior
- Build automated KPI reporting

---

## 👨‍💻 Author

**Gajendran**

Aspiring Data Analyst

**Skills:** `SQL` • `Excel` • `Power BI` • `Python` • `Data Analytics`

---

## ⭐ Project Summary

Healthcare Sales & Purchase Analytics is an end-to-end data analytics project that transforms healthcare transaction data into meaningful business insights.

The project analyzes sales, purchases, products, categories, staff performance, suppliers, GST and key business KPIs using Microsoft Excel.

The analysis helps support better **inventory planning, sales monitoring, supplier management and business decision-making**.
