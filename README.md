# 🏠 Property Management Dashboard

> **Power BI Dashboard | Portfolio Project**  
> By [Ibrahim Bolad](https://www.linkedin.com/in/ibrahimbolad) · [GitHub](https://github.com/ibrahimbolad-analytics)

---

## 📌 Project Overview

An interactive multi-page Power BI dashboard analyzing a global real estate portfolio of **200 properties** across **10 countries**, covering sales performance, financial analysis, and property intelligence from 2022 to 2024.

This project demonstrates end-to-end Power BI development — from data modeling and DAX measure creation to multi-page dashboard design with professional UX navigation.

---

## 🖼️ Dashboard Pages

### Page 1 — Overview
High-level snapshot of portfolio performance including revenue, expenses, net income, and properties sold. Features an interactive globe map showing revenue by country, a dynamic time switcher (Month / Quarter / Day), and a clients table with profile images.

### Page 2 — Financial Analysis
Deep dive into the financial structure: income by sales channel (Broker / Online / Direct), expense breakdown by type (Property Taxes / Maintenance / Renovation), and a dual-line revenue vs. expenses trend by month.

### Page 3 — Executive Summary
Strategic view for decision-makers. Highlights year-over-year revenue growth (+36.1% in 2023), income per property, revenue per client, and a geographic performance table with conditional formatting by profit margin. Includes client segment analysis revealing that Lawyers generate $31.6M — the top revenue segment.

### Page 4 — Property Intelligence
Property-level analysis covering sold vs. pending pipeline by type, average sale price by bedrooms and property type, and a treemap of price per square foot by country. Includes a ranked property table sorted by price.

---

## 📊 Key Insights

| Metric | Value |
|--------|-------|
| Total Revenue | $96.2M |
| Net Income | $66.6M |
| Profit Margin | **69.2%** |
| Properties Sold | 160 of 200 (80%) |
| Avg Sale Price | $601K |
| Top Market | Canada ($10.8M) |
| Top Property Type | Condo ($30.8M) |
| Best Margin Country | Canada (75.5%) |
| Top Client Segment | Lawyers ($31.6M from 2 clients) |
| Revenue Growth (2022→2023) | **+36.1%** |

---

## 🛠️ Technical Highlights

**Data Model**
- 5 tables: `Property_Table`, `Sales_Table`, `Client_Table`, `Expense_Table`, `Date Table`
- Star schema with active and inactive relationships
- Custom `Date Table` for time intelligence

**DAX Measures (20+ measures)**
- Time Intelligence: `Revenue PY`, `Revenue YoY %`, `Revenue YTD`, `Income YoY %`
- Ratios: `Profit Margin %`, `Expense Ratio %`, `Sales Rate %`, `Pending Rate %`
- Averages: `Avg Sale Price`, `Avg Price per SqFt`, `Income per Property`, `Revenue per Client`
- Segmentation: `Broker Revenue`, `Online Revenue`, `Direct Revenue`, `Condo Profit Margin`

**UX Features**
- Sidebar navigation across all 4 pages
- Dynamic time switcher (Month / Quarter / Day) using field parameters
- Slicers: Year, Property Type, Means of Sales
- Conditional formatting on geographic performance table
- Tooltip page with Revenue vs Expenses on hover

---

## 📁 Repository Structure
property-management-dashboard/
│
├── PropertyManagementDashboard.pbix   # Main Power BI file
├── README.md                          # Project documentation
└── screenshots/
├── page1-overview.png
├── page2-financial-analysis.png
├── page3-executive-summary.png
└── page4-property-intelligence.png
