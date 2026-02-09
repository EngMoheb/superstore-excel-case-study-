# Superstore Excel Case Study
![Superstore Case Study Cover](Assets/Cover.jpg)  
Photo by [Blake Wisz](https://unsplash.com/@blakewisz?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/photos/woman-holding-magnetic-card-q3o_8MteFM0?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)

## 📊 Project Overview
This case study analyzes the **Superstore dataset (~10K rows)** using Excel to uncover insights about sales, profit, discounts, returns, and shipping speed.  
The goal is to demonstrate **data cleaning, DAX measures, exploratory data analysis (EDA), and dashboard storytelling** directly in Excel.

---

## 📂 Data Preparation
- **Profit Column:**  
  - Converted accounting-style negatives (e.g., `(325)` → `-325`).  
  - Replaced dash `-` with `0` to handle missing values.  

- **Discount Column:**  
  - Values ranged from `0.00` to `0.80`.  
  - Grouped into bins for clearer analysis:  
    - 0–10%  
    - 10–20%  
    - 20–30%  
    - 30–40%  
    - 40%+  

- **Date Columns:**  
  - Extracted **Year** and **Month** from Order Date for trend analysis.  

- **Shipping Speed:**  
  - Created `Days to Ship` column.  
  - Categorized into buckets:  
    - Fast (0–2 days)  
    - Standard (3–5 days)  
    - Slow (>5 days)  

---

## 📈 KPIs & Metrics
- **Total Sales & Profit** across categories and regions.  
- **Return Rate** by category.  
- **Discount Impact** on profit margins.  
- **Shipping Speed Analysis** (Fast vs Standard vs Slow).  
- **Yearly Trends** in sales and profitability.  

---

## 🔍 Insights
- Discounts above **40%** strongly correlated with **negative profit**.  
- Certain categories (e.g., **Furniture**) had **higher return rates**.  
- Faster shipping (0–2 days) improved satisfaction but increased costs.  
- Yearly trends showed **steady growth in sales**, but profit margins fluctuated due to discounting strategies.  

---

## 📑 Recommendations
- Limit discounts above **30%** to protect profit margins.  
- Investigate high-return categories and improve product quality or communication.  
- Optimize shipping strategy: balance speed with cost efficiency.  
- Provide managers with dashboards to track KPIs and act on performance.  

---

## 📊 Visuals
Excel dashboards include:  
- Sales & Profit by Category and Region  
- Discount vs Profit Analysis  
- Shipping Speed Distribution  
- Yearly Sales & Profit Trends  
- Returns by Category  

*(Screenshots to be added in repo)*

---

## 📜 Storytelling Flow
1. **Problem:** Profit margins inconsistent, high returns, unclear discount impact.  
2. **Process:** Cleaned dataset, created KPIs, built dashboards in Excel.  
3. **Analysis:** Explored discounts, returns, shipping, yearly trends.  
4. **Insights:** Identified key drivers of profit loss and inefficiencies.  
5. **Recommendations:** Strategic discounting, quality checks, shipping optimization.  

---

## 🚀 Conclusion
This project demonstrates how a **junior data analyst** can transform raw transactional data into actionable insights using Excel alone.  
It highlights skills in **ETL, KPI creation, dashboards, and storytelling**, making it recruiter-ready and business-relevant.

---

## 📌 Author
**Ahmed Moheb Ali (Moheb)**  
Junior Data Analyst | BI Developer  
[LinkedIn Profile]( https://linkedin.com/in/mohebanalyst)  
[GitHub Profile]( https://github.com/EngMoheb)
