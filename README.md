# COFFEE SALES DASHBOARD
### Interactive Power BI dashboard analyzing coffee sales revenue, customer behavior, and product performance

![Dashboard Preview](image/dashboard%20preview.png)

An interactive Power BI dashboard analyzing 4K+ coffee sales transactions to uncover revenue trends, customer behavior, and product performance.

---

## Overview

This dashboard turns raw coffee sales transaction data into a real-time performance story: which products drive revenue, how sales shift by time of day and weekday, and where the biggest opportunities lie. It uses KPI cards, time-based analysis, and dynamic filters to deliver actionable business insights and support data-driven decision-making.

**Key metrics tracked:**
- ₹112K total revenue
- 4K+ total transactions
- ₹32 average transaction value
- Latte as the top-selling coffee

---

## Dashboard Features

| Panel | What it shows |
|---|---|
| **KPI Cards** | Avg. transaction value, top coffee, total revenue, total transactions |
| **Sales Funnel by Coffee** | Revenue ranked across all 8 coffee types |
| **Sales by Coffee Type** | Horizontal bar breakdown of revenue per product |
| **Sales by Time of Day** | Donut chart of revenue split across morning, afternoon, and night |
| **Revenue by Weekday** | Line chart of revenue trend across the week |
| **Revenue by Hour & Day** | Detailed matrix of revenue by hour of day and weekday |
| **Key Insights** | Auto-generated callouts on top/bottom performers and revenue share |

**Interactive filters:** Coffee Name, Date, Time of Day — allowing drill-down into any combination of product and time.

---

## Dataset

- **File:** `dataset/Coffee_sales.xlsx`
- **Records:** 4,000+ transactions
- **Key fields:** coffee name, date, time of day, hour of day, weekday, payment type, transaction value

---

## Tools & Techniques

- **Power BI** — dashboard development, DAX measures, dynamic filters and slicers, interactive visuals
- **Microsoft Excel** — data preparation and storage
- **Design approach:** dark coffee/gold theme, KPI-first layout with funnel, time-based, and matrix visuals

---

## Key Insights

- Latte had the highest total revenue at ₹26,875 — 898.98% higher than Espresso, the lowest at ₹2,690
- Latte accounted for 23.94% of total revenue
- Revenue peaks midweek and tapers toward the weekend
- Afternoon and morning hours drive the majority of sales volume

---

## Repository Contents

```
├── coffee sales dashboard.pbix     # Power BI dashboard file
├── dataset/
│   └── Coffee_sales.xlsx           # Source dataset
├── image/
│   └── dashboard preview.png       # Dashboard screenshot
└── README.md                       # Project documentation
```

---

## How to Use

1. Download or clone this repository.
2. Open `coffee sales dashboard.pbix` using Power BI Desktop.
3. Ensure `Coffee_sales.xlsx` is available in the `dataset` folder.
4. Update the data source path if required.
5. Refresh the data and explore the dashboard using the available filters and visualizations.

---

*Part of a broader data analytics portfolio spanning Power BI, Tableau, SQL, and Excel projects.*

**— Ayesha Safiya**
