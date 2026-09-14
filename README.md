# Data-Analyst-Capstone-Project
# Data Analyst Capstone Project: Executive Sales & Profitability Analysis

## Overview
This project delivers an end-to-end data analysis, dynamic dashboard, and executive presentation evaluating business metrics for global sales, product profitability, and customer segments.

---

## Key Performance Indicators (KPIs)
* **Total Net Sales:** $118,726,350.26
* **Total Profit:** $16,893,702.26
* **Total Units Sold:** 1,125,806
* **Overall Profit Margin:** 14.23%

---

## Visual Dashboard Preview
![Dashboard Preview](dashboard/dashboard_screenshot.png)

---

## Core Findings & Insights
1. **Segment Drivers:** The **Government** segment generates 44.2% of total business revenue ($52.5M) and $11.39M in profit, making it the most critical market driver.
2. **Product Performance:** **Paseo** is the top-performing product with over $33.0M in gross revenue and 338k+ units sold.
3. **Enterprise Segment Loss:** The **Enterprise** customer segment operates at a net loss (-$614k) due to high production costs relative to discounting tiers.
4. **Discount Impact:** High discount band sales significantly reduce net margins compared to low and medium discount band strategy sales.

---

## Strategic Recommendations for Stakeholders
* **Enterprise Contract Restructuring:** Revise pricing and discount structures for Enterprise clients to recover profitability.
* **Optimize Discount Tiers:** Limit the usage of "High" discount bands across lower-performing product lines like *Carretera*.
* **Expand Channel Partners:** Increase investment in Channel Partner sales, which yield the highest profit margin (73.13%).

---

## Technologies Used
* **Python (Pandas, Matplotlib):** Data cleaning, exploratory data analysis (EDA), and summary aggregation.
* **Power BI / Tableau:** Interactive dashboard development and visualization.
* **Excel:** Primary dataset source (`Sample data (1).xlsx`).

---

## Repository Navigation
* `/src/`: Contains `analysis.py` python automation script.
* `/dashboard/`: Contains `.pbix` dashboard source file and visual previews.
* `/data/`: Contains raw Excel file used for input analysis.
