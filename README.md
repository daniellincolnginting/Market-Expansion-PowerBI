# Market Expansion & Risk Assessment Dashboard 📊

## 📌 Project Overview
This Business Intelligence project focuses on transforming regional macroeconomic data into clear, actionable insights. The dashboard is designed to help executive management determine the optimal locations for new branch expansions by balancing **Purchasing Power (Profit Potential)** against **Inflation Risks (Operational Costs)**.

> **[Click here to view the PDF version of this dashboard](link-to-your-pdf-file.pdf)**

---

## 📸 Dashboard Previews

### 1. Market Strategy (Executive Summary)
*Provides a high-level helicopter view to quickly identify aggregate recommendations for the best target expansion regions.*
![Executive Summary](images/page1.png)

### 2. Market Size & Income
*Analyzes market volume based on population density and minimum wage capacity to gauge regional purchasing power.*
![Market Size](images/page2.png)

### 3. Inflation & Cost Risks
*A risk mitigation matrix dissecting monthly inflation volatility and highlighting provinces operating in the operational "Danger Zone."*
![Risk Assessment](images/page3.png)

---

## 🛠️ Data Pipeline & Methodology
1. **Data Sourcing:** Utilized historical macroeconomic datasets covering Population, Minimum Wage, and Consumer Price Index/Inflation Rates across Indonesian provinces (2024-2025).
2. **Data Transformation (Power Query):** 
   - Enforced strict data type standardization and anomaly cleaning.
   - Performed Feature Engineering, including Chronological Indexing to ensure accurate time-series plotting without circular dependencies.
3. **Data Modeling (DAX & Power BI):** 
   - Architected a highly efficient Star Schema (Fact and Dimension tables).
   - Authored dynamic DAX measures for context-aware aggregations.
   - Implemented Scatter Plots equipped with Constant Lines to construct a precise 4-quadrant business decision matrix.

---

## 💡 Key Business Insights
* **Expansion Sweet Spots:** Based on the quadrant matrix, provinces such as [Insert Province 1, e.g., DKI Jakarta] and [Insert Province 2, e.g., Kepulauan Bangka Belitung] offer the most favorable balance of high purchasing power and low/stable inflation.
* **The Danger Zone:** Provinces like [Insert Province 3] demonstrate the highest operational risk due to low minimum wage coupled with sharp inflation spikes. It is highly recommended to delay physical expansion in these regions.

---

## 📂 How to Open the Project File (.pbix)
For recruiters or data professionals who wish to explore the data model, Star Schema, and DAX formulations:
1. Download the `Market_Expansion_Dashboard.pbix` file from this repository.
2. Open the file using **[Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/)**.
