# Tyre Sales Performance & Product Demand Analysis  
Excel & Power BI | Sales Analytics | Inventory Insights

---

## 1. Background and Overview

This project analyzes six months of anonymized sales data from a tyre retail and service business.

The objective was to move beyond raw transaction records and answer practical business questions:

- Which months drive the highest revenue?
- Which products and tyre sizes generate the most demand?
- What price segments contribute most to overall sales?
- Where should inventory focus to reduce stock risk?

The goal of this analysis is to support better inventory planning, product prioritization, and revenue optimization decisions.

---

## 2. Data Structure Overview

The dataset contains transactional sales records from January to June 2021.

### Key Fields

- Month  
- Product Name  
- Tyre Size  
- Units Sold  
- Unit Price  
- Total Sales  
- Price Range Category (Low / Medium / High)  

### Summary Statistics

- **884 total units sold**  
- **₦23.7M total revenue**

The dataset was anonymized to protect business confidentiality.

---

## 3. Executive Summary

Between January and June 2021:

- Revenue peaked in **May (₦4.9M)** following a steady rise from March.  
- A small number of products contributed a disproportionate share of revenue.  
- One tyre size (**205/65 R15**) accounted for **135 units sold**.  
- Low-price products generated **88.46% of total unit sales**.  

The business appears volume-driven, with strong reliance on high-demand, lower-priced tyres.

Inventory strategy and product focus should reflect this pattern.

---

## DASHBOARD PREVIEW
<p align="center">
  <img src="images/dashboard_overview.png" width="800">
</p>

---

## 4. Insights Deep Dive

### Insight 1: Sales Surge in Q2

**Metric:** Monthly Revenue  
**Quantified Value:** Revenue increased from **₦3.2M in February** to **₦4.9M in May** (≈53% growth).

**Story:**  
Sales were relatively stable in January and February, then began rising in March, peaking in May before slightly declining in June.

This suggests:
- Seasonal demand increase  
- Promotional impact  
- Increased market activity  

**Business Meaning:**  
The business should anticipate stronger demand during similar periods and prepare inventory in advance.

---

### Insight 2: Revenue Concentration in Few Products

**Metric:** Product Revenue Contribution  

**Quantified Value:**

- S/FULL generated **₦5.1M** (highest revenue)  
- ARMSTRONG generated **₦3.8M**  
- JOK generated **₦3.2M**  

**Story:**  
A small group of products consistently outperformed others in both revenue and units sold.

**Business Meaning:**  
Revenue concentration indicates dependency on top products.  
Stockouts in these products would significantly impact total revenue.

These should be treated as core inventory assets.

---

### Insight 3: High-Demand Tyre Size Drives Volume

**Metric:** Units Sold by Tyre Size  

**Quantified Value:**  
**205/65 R15** recorded **135 units sold**, the highest among all sizes.

**Story:**  
This tyre size significantly outperformed others in volume, indicating strong market demand.

**Business Meaning:**  
This size should:

- Always remain in stock  
- Be prioritized in procurement planning  
- Possibly benefit from supplier negotiation for better margins  

---

### Insight 4: Business Is Volume-Driven (Low-Price Dominance)

**Metric:** Price Range Contribution to Units Sold  

**Quantified Value:**  
Low-price products account for **782 units (88.46%)** of total unit sales.

**Story:**  
Most customers purchase lower-priced tyres, suggesting price sensitivity in the market.

**Business Meaning:**  
The business model appears to rely on volume rather than premium margin products.

**Strategy Implications:**

- Maintain strong supply of low-price inventory  
- Evaluate profitability margins carefully  
- Avoid over-investing in slow-moving premium stock  

---

## 5. Recommendations

Based on the analysis:

### 1. Protect Core Products  
Maintain high stock levels for S/FULL, ARMSTRONG, and top-performing tyre sizes.

### 2. Plan for Q2 Demand Surges  
Prepare inventory ahead of high-performing months to avoid missed revenue.

### 3. Optimize Price Strategy  
Since demand is volume-driven, evaluate margins on low-price tyres to ensure profitability.

### 4. Monitor Revenue Concentration Risk  
Reduce dependency risk by gradually promoting mid-tier products.

---

## 6. Analytical Approach (Brief Technical Note)

- Data cleaning and validation performed in Excel and Power Query.  
- Revenue consistency verified (Units Price × Unit Sold).  
- Measures created using DAX in Power BI.  
- Dashboard designed to prioritize decision-making KPIs over decorative visuals.  
