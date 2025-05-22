# POWER-BI-project0
Designed an interactive Power BI dashboard to analyze Adidas sales data across regions, products, and retailers, enabling clear visibility into performance and trends.


---

### ✅ **Objective & Initial Business Questions**

Before creating the dashboard, the primary goal was to gain a comprehensive understanding of Adidas’ sales performance across different dimensions. The key business questions included:

1. **What is the total revenue, profit, and units sold during the selected period?**
2. **Which months saw the highest and lowest sales?**
3. **How does performance vary by region, state, and sales channel?**
4. **Which products are the top-selling?**
5. **Which retailers are contributing most to the revenue?**
6. **What is the average price per unit and operating margin?**
7. **What patterns or trends can be observed for strategic decision-making?**

---

### 🧩 **Steps to Build the Dashboard**

1. **Data Collection & Preparation:**

   * Collected raw transactional data including fields such as invoice date, region, state, product type, sales amount, units sold, cost, profit, and sales method.
   * Cleaned and transformed the data in Power Query Editor: handled missing values, ensured consistent formats, and created calculated columns (e.g., `Price per Unit`, `Operating Margin`).

2. **Data Modeling:**

   * Established relationships between tables (e.g., Date table with Sales table, Product table).
   * Created DAX measures for:

     * `Total Sales`
     * `Operating Profit`
     * `Units Sold`
     * `Price per Unit` (`Sales ÷ Units`)
     * `Operating Margin` (`Profit ÷ Sales`)


3. **Dashboard Design & Visualization:**

   * Created cards for high-level KPIs.
   * Designed a time series chart for monthly trends.
   * Used:

     * **Map** for geographical state-wise distribution.
     * **Donut Chart** for regional sales share.
     * **Bar Charts** for breakdowns by product and retailer.
   * Applied consistent styling for readability (color-coded regions, bold KPI values, etc.).

4. **Interactivity via Slicers:**

   * Implemented **Invoice Date** slicer to allow filtering by time.
   * Added **Sales Method** slicer (In-store, Online, Outlet) for channel-based performance analysis.
   * These slicers make the dashboard dynamic and support self-service exploration by end users.

---

### 🔍 **Key Takeaways from the Analysis**

* **Total Revenue:** \$900M, with a healthy **Operating Profit** of \$332M and a strong **Operating Margin** of 42.3%.
* **Monthly Performance:** Sales peaked in **July (\$95M)** and dipped in **March (\$57M)**, indicating seasonal trends.
* **Top Regions:** The **West** region leads at \$270M, followed by the **Midwest** and **South**.
* **Best-Selling Product:** **Men’s Street Footwear** generated the highest revenue at \$209M.
* **Retailer Performance:** **West Gear** and **Foot Locker** are top performers, accounting for nearly 50% of retailer sales.
* **Geographical Insights:** High sales in **California, Texas, Florida, and New York**, suggesting focus areas for future campaigns.

---

### 🎯 **Final Thoughts**

This dashboard provides stakeholders with a powerful, at-a-glance view of Adidas' performance. It enables data-driven decisions on product strategy, retail partnerships, and regional marketing campaigns. The combination of visuals, metrics, and slicers ensures a user-friendly and insightful analytical tool.
