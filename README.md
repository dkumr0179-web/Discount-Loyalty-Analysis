📊 AI-Assisted Sales & Margin Analytics Executive Dashboard

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge&logo=googlechrome)](https://discountloyaltyanalysis.oneapp.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Stack](https://img.shields.io/badge/Stack-JS%20%7C%20Chart.js%20%7C%20HTML5-blue?style=for-the-badge)](https://developer.mozilla.org/)

An AI-assisted, executive-grade Business Intelligence (BI) dashboard engineered to evaluate the financial impact of discounting strategies, customer loyalty, and profit leakage across enterprise transactional data (US Retail Dataset, 2018–2021).

Designed for C-suite executive presentation (CEO/CFO), this application delivers immediate visual intelligence, threshold monitoring, and automated financial callouts with zero external framework overhead.

🌐 Live Application: https://discountloyaltyanalysis.oneapp.dev/](https://discountloyaltyanalysis.oneapp.dev/ 

---

## 📸 Dashboard Preview

Sales & Margin Analytics Executive Dashboard  : assets/DiscountandLoyalty.png

---

🚀 Key Features & Architectural Highlights

C-Suite KPI Summary Bar:  Real-time reactive cards tracking Gross Commercial Sales ($12.24M), Bottom-Line Earnings ($1.86M), Net Profit Margin % (**15.2%**), Line Items Processed (9,994), and Active Customers (793) with dynamic status threshold badges.
Global Multi-Dimensional Filtering Engine:** Client-side state-management system powering 5 sticky header filters (Year, Region, Customer Segment, Product Category, Shipping Mode) that synchronously re-render all visual assets and KPI cards in real time.
Automated Executive Insights Engine: Real-time text calculation engine generating dynamic financial alerts and operational callouts:
  - 🟢 Category Margin Leader:** Identifies top-performing margin drivers
    (Technology at 22.5% vs. Furniture at -7.2%).
  - 🔴 Discount Erosion Alert:** Flags orders utilizing deep discounts (≥30%) causing margin compression across impacted lines.
  - 🔵 Geo Revenue vs. Margin Gap: Highlights revenue volume leaders versus profit efficiency regions (*Central* gross sales vs. West margin quality).
  - 🟠 Product Drag Warning:** Pinpoints specific sub-categories responsible for cumulative net profit leakage (e.g., Tables at -$169.8K).
- Comprehensive Visual Analytics Grid (11 Interactive Views):
  - Dual-Axis Longitudinal Revenue vs. Profit Trend (48 calendar months)
  - Revenue Share by Category & Sub-Category Margin Ranking
  - Sales vs. Profit Bubble Scatter Matrix
  - Discount Impact Curve revealing exact profitability cliffs
  - Regional Combo Performance & Shipping Mode Logistics Breakdown

---

## 🛠️ Tech Stack & AI Assistance

- Frontend: Vanilla JavaScript (ES6+), HTML5, CSS Grid / Flexbox
- Data Visualization: Chart.js (CDN)
- UI Architecture: Corporate Executive Navy Theme (`#1a2744`), responsive layout, 200ms filter state transition animations
- AI Co-Engineering: Utilized LLM prompt engineering to rapidly generate baseline visualization logic, optimize data-aggregation loops, and prototype real-time insight calculation functions.
