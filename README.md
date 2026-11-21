# 📊 Executive Sales & Purchase Performance Suite (MTD & YTD)

An end-to-end 4-page Power BI executive dashboard suite built to track Month-to-Date (MTD), Last Month-to-Date (LMTD), Year-to-Date (YTD), and Last Year-to-Date (LYTD) commercial sales and procurement across **INR 233+ Cr** in revenue and **INR 195+ Cr** in procurement.

---

### 📈 1. Sales YTD Executive Comparison
![Sales YTD Dashboard](Sales%20Ytd%20Analysis.png)

- **YTD Growth & Scale:** Tracked **INR 233.29 Cr** in YTD sales across **34,257 units** (+2.3% YoY growth vs INR 228.02 Cr LYTD).
- **Dynamic Executive Insights:** Custom DAX text measures automatically identify top-performing buyers and highest-contributing SKU models.

---

### 📅 2. Sales MTD Executive Comparison
![Sales MTD Dashboard](Sales%20Mtd%20Analysis.png)

- **Month-over-Year Variance:** Compares current month sales (**INR 15.67 Cr**) against same month last year (**INR 29.71 Cr**) to pinpoint buyer-level drop-offs and high-growth SKUs.

---

### 🛒 3. Purchase YTD Executive Comparison
![Purchase YTD Dashboard](Purchase%20Ytd%20Analysis.png)

- **Procurement & Vendor Mix:** Monitors **INR 195.79 Cr** YTD procurement across **34,436 units** (-2.26% vs INR 200.31 Cr LYTD) across 20+ suppliers and device categories.

---

### 🛍️ 4. Purchase MTD Executive Comparison
![Purchase MTD Dashboard](Purchase%20Mtd%20Analysis.png)

- **Monthly Intake Tracking:** Evaluates monthly procurement volume (**2,142 units** / **INR 15.36 Cr**) against LMTD (**INR 27.15 Cr**) to align inventory intake with sales velocity.

---

### 🛠️ Technical Architecture & DAX Implementation
- **Time-Intelligence DAX:** `TOTALYTD`, `TOTALMTD`, `SAMEPERIODLASTYEAR`, `DATEADD`, and fiscal year-end (`03-31`) comparative growth measures.
- **Dynamic NLG Summary Cards:** Automated plain-English insight measures (`Insights_Sales_YTD`, `Insights_Sales_MTD`, `Insights_Purchase_YTD`, `Insights_Purchase_MTD`) with dynamic Cr/Lac formatting.
- **Power Query (ETL):** Automated data transformation, duplicate handling, and multi-party/SKU standardization.
