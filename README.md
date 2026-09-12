# Voltaire Segmentation


## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Business Questions](#-business-questions)
- [Dataset Preparation](#-dataset-preparation)
- [Data Analysis](#-data-analysis)
- [Dashboard Features](#-dashboard-features)
- [Dynamic Filtering](#-dynamic-filtering)
- [Key Findings](#-key-findings)
- [Business Impact](#-business-impact)
- [Expected Business Outcomes](#-expected-business-outcomes)
- [Recommendations](#-recommendations)
- [Tools Used](#-tools-used)
- [Skills Demonstrated](#-skills-demonstrated)

---

## 📊 Project Overview

This project analyses the **Voltaire sales dataset** using **Microsoft Excel** to identify key business trends and actionable insights for key stakeholders.

The dashboard focuses on:

- Profitability
- Sales performance
- Customer segments
- Product performance
- Geographical sales distribution

![Voltaire Segment dashboard](https://github.com/DavidMashishi/Voltaire-Segment-Sales-/blob/4d6323c007e6855c357c0e6511622a9c27c5be18/Images/Voltaire%20Segment%20Dashboard%20Image.png)

The interactive visualisations allow stakeholders to identify business opportunities, understand performance trends, and focus attention on areas requiring improvement.

---

## 🎯 Business Questions

The analysis was designed to answer the following business questions:

1. Which three products generated the highest revenue?
2. Which product generated the highest revenue?
3. Which customer segment performed the worst across all products?
4. Which countries generated the highest sales?

---

## 🧹 Dataset Preparation

Data preparation was performed to improve data quality and ensure accuracy.

Key preparation activities included:

- Created a working copy of the original Voltaire dataset to preserve the raw data.
- Verified that the dataset contained **9,100 distinct records** with no duplicates.
- Prepared summary tables for dashboard visualisation.

---

## 🔍 Data Analysis

Several visualisations and Pivot Tables were created to highlight key business insights.

### Visualisations

| Analysis | Visual |
|---|---|
| Profit by Segment | Line Chart |
| Units Sold by Segment | Line Chart |
| Sales by Product | Bar Chart |
| Total Sales by Country | Bar Chart |

### Pivot Tables

#### Sales by Country

- **Rows:** Country
- **Values:** Sum of Sales

#### Profit by Segment

- **Rows:** Segment
- **Values:** Sum of Profit

#### Sales by Product

- **Rows:** Product
- **Values:** Sum of Sales

#### Units Sold by Segment

- **Filter:** Country
- **Rows:** Segment
- **Columns:** Product
- **Values:** Sum of Units Sold

---

## 📈 Dashboard Features

The dashboard provides an easy-to-understand overview of business performance.

### Dashboard Components

- **Sales by Product**
- **Profit by Segment**
- **Units Sold by Segment**
- **Sales by Country**

---

## 🎛️ Dynamic Filtering

The dashboard includes interactive **Slicers** that allow stakeholders to filter the analysis by:

- Segment
- Product
- Country

These slicers allow users to explore specific business scenarios and compare performance across different categories.

---

## 🔑 Key Findings

The analysis identified several important business insights:

- **Paseo, VTT, and Amarilla** generated the highest overall revenue.
- The **Government segment** delivered the strongest overall profitability.
- The **Enterprise segment** recorded the weakest performance and represents the largest opportunity for improvement.
- **North America** generated some of the strongest sales performance across the dataset.

---

## 💼 Business Impact

By providing an interactive view of sales performance, profitability, customer segments, products, and geographic markets, the dashboard enables stakeholders to quickly identify opportunities and areas requiring attention.

### Business Value

The analysis delivers value by:

- Identifying the highest-performing products to support **inventory planning, marketing investment, and sales prioritisation**.
- Highlighting the most profitable customer segment, enabling management to focus resources on **high-value markets**.
- Revealing underperforming segments that may require **strategic improvements, pricing adjustments, or targeted marketing initiatives**.
- Reducing the time required to analyse sales performance by consolidating key metrics into a **single reporting dashboard**.
- Supporting executives and business stakeholders with clear, actionable insights to improve **long-term revenue growth and profitability**.

---

## 📌 Expected Business Outcomes

The analysis is expected to support:

- Improved sales and forecasting planning.
- Better allocation of marketing and operational resources.
- Increased focus on high-revenue and high-profit products.
- Identification of opportunities to improve underperforming customer segments.
- Greater visibility into regional sales trends and customer behaviour.

---

## 🚀 Recommendations

Based on the analysis, the following recommendations were identified:

### 1. Prioritise High-Performing Products

Increase marketing efforts and maintain efficient inventory planning for **Paseo, VTT, and Amarilla**, as these products contribute the largest share of revenue.

### 2. Maintain Government Segment Profitability

Develop targeted sales strategies with government clients and channel partners to maintain long-term profitability.

### 3. Investigate Enterprise Segment Underperformance

Conduct a thorough review of the **Enterprise segment** to identify the underlying causes of underperformance.

Areas for further investigation include:

- Pricing adjustments
- Product positioning
- Promotional campaigns
- Customer engagement

### 4. Continue Regional Performance Optimisation

Continue investing in high-performing regions such as **North America**, while developing strategies to improve performance in lower-performing markets.

---

## 🛠️ Tools Used

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Slicers
- `SUMIFS`
- `XLOOKUP`
- `COUNTIF`
- `TRIM`
- Conditional Formatting
- Data Validation

---

## 🧠 Skills Demonstrated

- Data Cleaning
- Data Validation
- Data Analysis
- Business Intelligence
- Dashboard Design
- Data Visualisation
- Pivot Table Analysis
- Excel Functions
- Business Recommendations
- Stakeholder Reporting

---

## 📊 Project Outcome

The **Voltaire Segment Dashboard** demonstrates how Excel-based Business Intelligence techniques can transform sales data into an interactive reporting solution.

The project combines **data preparation, analysis, visualisation, segmentation, and business recommendations** to provide stakeholders with a clearer understanding of sales performance, profitability, customer segments, products, and regional markets.
