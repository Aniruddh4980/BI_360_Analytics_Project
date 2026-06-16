# Business Insights 360 — Power BI Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-2026.04-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

A multi-functional Power BI report built for **AtliQ Hardware**, a fictional consumer electronics company, covering Finance, Sales, Marketing, Supply Chain, and Executive performance across global markets.

This project is part of the [Codebasics Data Science & Gen AI Bootcamp](https://codebasics.io/) curriculum and serves as a portfolio-grade demonstration of end-to-end business intelligence development.

---

## 🔗 Live Report

> 📊 [View the Report on Power BI Service](#) *(replace with your published link)*

---

## 📌 Problem Statement

AtliQ Hardware was growing rapidly but still relying on Excel-based reporting to make critical business decisions. This left leadership with fragmented data, no single source of truth, and no ability to drill into performance by market, segment, or product in real time. Business Insights 360 was built to close that gap — giving every function (Finance, Sales, Marketing, Supply Chain) and senior leadership a dedicated analytical view backed by a unified data model.

---

## 🗂️ Report Pages

| Page | Description |
|---|---|
| 🏠 **Home** | Navigation hub with links to all report views |
| 💰 **Finance View** | P&L statements, NS/GM/NP KPIs, trend analysis, benchmark comparisons |
| 📈 **Sales View** | Customer and product performance, GM % vs NS $ scatter, segment breakdown |
| 📣 **Marketing View** | GM % and NP % profitability scatter, region/market analysis, waterfall chart |
| 🚚 **Supply Chain View** | Forecast accuracy, net error, risk assessment by product and customer |
| 🧭 **Executive View** | Consolidated KPIs, market share ribbon, NS by division/channel, top sub-zones |
| 📉 **Sales Trend** | Long-term sales trend line chart |
| 🛟 **Support** | Help page for report users |
| ℹ️ **Info** | Project metadata and documentation |

---

## 📐 Key Measures & Metrics

### Finance
- **NS $** — Net Sales
- **GM $** / **GM %** — Gross Margin and Gross Margin %
- **Net Profit %** — Bottom-line profitability
- **P & L Values** / **P & L Final Value** / **P & L BM** — Full P&L statement with benchmark
- **P & L Chg %** — Year-over-year change

### Sales & Marketing
- **NS BM $** — Net Sales Benchmark
- **GM % BM** — Gross Margin % Benchmark
- **AtliQ MS %** — AtliQ Hardware's market share %
- **Market Share %** — Overall market share over time
- **RC %** — Revenue Contribution %

### Supply Chain
- **FA %** / **FA % LY** — Forecast Accuracy vs Last Year
- **ABS Error** / **ABS Error LY** — Absolute Forecast Error
- **Net Error** / **Net Error LY** / **Net Error %** — Net Forecast Error
- **Risk** — Supply chain risk indicator

---

## 🔍 Filters & Slicers (available across views)

- **Fiscal Year** (`fy_desc`) and **Quarters**
- **YTD / YTG** — Year-to-date vs. year-to-go toggle
- **Market**, **Region**, **Customer**, **Segment**, **Category**
- **Benchmark selector** — compare vs. Last Year or Target
- **Top/Bottom N** — dynamic ranking

---

## 🛠️ Technical Details

### Tools & Technologies

| Tool | Purpose |
|---|---|
| Power BI Desktop (v2.153.777) | Report development and data modeling |
| Power Query (M) | Data transformation and ETL |
| DAX | Measures, KPIs, and calculated columns |
| MySQL | Source database |
| Excel | Supplementary data sources |

### Data Model
- Star schema with fact tables connected to dimension tables
- Custom date table with fiscal year logic
- No auto-created relationships (all manually defined)

### Visuals Used
- KPI cards, Matrix/Pivot tables, Area chart, Scatter chart, Donut chart, Waterfall chart, Ribbon chart, Combo (Line + Column) chart, Slicers, Action buttons

---

## 📁 Project Structure

```
Business-Insights-360/
│
├── BI360.pbix              # Main Power BI report file
├── README.md               # Project documentation
│
└── assets/                 # Screenshots of report pages (optional)
    ├── home.png
    ├── finance_view.png
    ├── sales_view.png
    ├── marketing_view.png
    ├── supply_chain_view.png
    └── executive_view.png
```

---

## 💡 Key Learnings

- Built a unified data model connecting Finance, Sales, Marketing, and Supply Chain data
- Developed dynamic P&L statement rendering using parameterized DAX measures
- Implemented benchmark switching (Last Year / Target) via a disconnected slicer table
- Created forecast accuracy and risk metrics for Supply Chain analysis
- Designed a navigation-first UX with a Home hub and consistent cross-page slicers

---

## 🚀 Getting Started

1. Clone or download this repository
2. Open `BI360.pbix` in **Power BI Desktop** (version 2.153.777 or later recommended)
3. Update data source credentials if connecting to a live MySQL database
4. Publish to Power BI Service to enable scheduled refresh and sharing

---

## 👤 Author

**Aniruddh** — Mechanical Engineer transitioning into Data & AI  
[LinkedIn](#) · [GitHub](#) · [Portfolio](#)

> *This project was built as part of the Codebasics Data Science & Gen AI Bootcamp. AtliQ Hardware is a fictional company used for educational purposes.*
