# Exploratory Data Analysis: Product Sales Insights

This repository contains analysis to answer key business questions around product pricing, seasonality, promotions, and sales trends using Python and statistical methods.

---

## Questions & Insights

### 1. Which Products Are Most Price Sensitive?

Performed **linear regression** using `statsmodels.ols` to measure how pricing affects sales.

**Top Price-Sensitive Products:**

See [`Insight_analysis.ipynb`](ExploratoryAnalytics.ipynb) for code and output.

---

### 2. Are Any Products Sales-Driven by Seasonal Factors?

Analyzed monthly sales trends with line plots.

**Findings:**
- **Frozen Pizza** showed strong year-end spikes
- **Bag Snacks** increased steadily toward December
- **Oral Hygiene Products** dipped in December–January

See [`Insight_analysis.ipynb`](ExploratoryAnalytics.ipynb) for code and output.

---

### 3. Impact of Promotions, Displays, and Circulars?

Used bar plots to compare average sales with and without promotional strategies.

**Observation:**  
**Feature + Display** = Sales Boost  
**TPR_ONLY** = No effect

See [`Insight_analysis.ipynb`](ExploratoryAnalytics.ipynb) for code and output.

---

### 4. Sales Trends Worth Further Exploration?

Discovered an unusual **drop in sales across all categories in March 2010**.

See [`Insight_analysis.ipynb`](ExploratoryAnalytics.ipynb) for code and output.

**Recommendation:**  
Investigate internal issues or macroeconomic causes.

---

## Analysis Process

- Linear regression for price sensitivity
- Aggregated monthly sales to detect seasonality
- Bar plots for promotional impact
- Line plots for trend discovery

---

## Business Insights

- Increase prices on sensitive products
- Offer discounts for negatively sensitive products during promos
- Boost inventory of seasonal items (e.g. Frozen Pizza in December)
- Drop or improve underperforming promotions like TPR_ONLY

---

## Recommendations

- Launch awareness campaigns for TPR_ONLY
- Tailor promotions based on customer demographics
- Compare trends with competitors for strategic advantage



