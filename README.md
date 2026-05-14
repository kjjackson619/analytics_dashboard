Hosted at https://kjjackson619.github.io/analytics_dashboard/

# 📊 E-Commerce Analytics Dashboard

An interactive, browser-based analytics dashboard built with vanilla HTML, CSS, and Chart.js — no frameworks, no dependencies to install. Designed as a portfolio project demonstrating data analyst skills across KPI design, multi-dimensional data visualization, and interactive reporting.

---

## Preview

> Executive KPI summary, revenue trends, sales funnel, customer segmentation, traffic sources, and geographic breakdown — all filterable by time period.

---

## What This Demonstrates

### Analytics & Business Intelligence
- Designed a multi-layered KPI framework covering revenue, conversion, retention, and logistics metrics
- Built period-over-period delta tracking (▲/▼) with directional color coding
- Implemented sales funnel analysis showing drop-off rates at each stage of the customer journey
- Applied RFM (Recency, Frequency, Monetary) customer segmentation — Champions, Loyal, At Risk, Lapsed cohorts
- Included cart abandonment rate, average order value, and traffic channel attribution

### Technical Implementation
- **Chart.js** — bar/line combo chart with dual Y-axis, doughnut chart, horizontal bar, stacked bar
- **Dynamic data switching** — all 7 panels update simultaneously on period change (7D / 30D / 90D / 1Y)
- **Responsive layout** — CSS Grid with auto-fit columns, mobile-friendly breakpoints
- **Zero dependencies** — single self-contained HTML file, no npm, no build step

### Data Visualization Best Practices
- Dual-axis overlay for correlated metrics (revenue bars + order volume line)
- Color used semantically, not decoratively (green = positive trend, red = negative)
- Custom chart legends with value labels (Chart.js defaults replaced)
- Consistent dark theme with sufficient contrast ratios

---

## Dashboard Panels

| Panel | Metrics | Technique |
|---|---|---|
| KPI Cards | Revenue, Orders, AOV, CVR, Cart Abandonment | Period delta calculation |
| Revenue Trend | Daily revenue vs prior period + order volume | Dual-axis combo chart |
| Category Mix | Revenue share by product category | Doughnut chart |
| Sales Funnel | Sessions → Views → Cart → Checkout → Purchase | Custom progress bars |
| Traffic Sources | Sessions by acquisition channel | Horizontal bar chart |
| Top Regions | Revenue by country | Inline bar visualization |
| Top Products | Revenue + unit share for 8 SKUs | Ranked table with data bars |
| Customer Segments | RFM cohort trends over time | Stacked bar chart |

---

## Dataset

Simulated e-commerce data for a fictional retailer (NovaMart). All figures are illustrative and designed to reflect realistic patterns:
- Seasonal uplift in Q4
- Organic search as dominant traffic source (~36–38%)
- US market representing ~47–51% of revenue depending on period
- Electronics as highest-revenue category

## Skills Evidenced

`Data Visualization` `KPI Design` `Chart.js` `HTML/CSS` `JavaScript` `Business Analytics` `E-Commerce Metrics` `RFM Segmentation` `Funnel Analysis` `Responsive Design`

---
