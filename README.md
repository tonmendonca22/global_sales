# From SQL to Actionable Insight: Global Sales Data Analysis

This project explores a global sales dataset and transforms raw data into strategic insights using SQL and Power BI. By combining technical analysis with business storytelling, the goal is to demonstrate how data can support smarter business decisions.

## 🔧 Tools & Technologies

- **SQL** – Data exploration, transformation, and aggregation
- **Power BI** – Interactive dashboards and visual storytelling
- **Excel** – Supporting analysis and data validation
- **Data Storytelling Techniques** – To connect insights with business impact

## 📊 Key Deliverables

- ✅ Clean and structured global sales dataset
- ✅ Actionable insights generated through SQL queries
- ✅ Interactive Power BI dashboard with storytelling elements
- ✅ Summary report highlighting business value and recommendations

## 🧠 Topics Covered

- Sales performance by region
- Profitability trends and margins
- Product mix and top-sellers
- Customer segmentation
- Visual storytelling for decision-makers

## 📁 Project Structure

- `/datasets/` – Source and cleaned datasets
- `/sql/` – SQL queries used for data exploration and transformation
- `/powerbi/` – Power BI file (.pbix) and dashboard link
- `/report/` – Summary insights and business recommendations

---

## 🔗 Power BI Dashboard

Access the interactive dashboard here: [▶️ View Dashboard](https://bit.ly/erivelton-mendonca_global_sales)

This dashboard brings the global sales data to life through compelling visualizations and strategic storytelling. It is designed to help business stakeholders quickly understand performance metrics, identify growth opportunities, and make informed decisions.

### 📌 Highlights:
- 📍 **Sales by Region** – Analyze revenue and profit distribution by geography
- 🏆 **Top-Selling Products** – Identify top categories and best-performing items
- 📈 **Profitability Analysis** – Evaluate financial performance across dimensions
- 🧠 **Customer Segmentation** – Understand customer behavior and trends
- 🎯 **Strategic Storytelling** – Visual narratives that connect data to business goals

> 📁 The `.pbix` source file is available in the `/powerbi` folder for further exploration or customization.

---

## 🗃️ SQL Queries

All SQL queries used in this project are available in the [`/sql`](./global_sales/sql_queries) folder.

Each query supports a different stage of the analysis, including data cleaning, aggregation, and insight generation. Example queries:

```sql
-- Total sales and profit by region
SELECT
  region,
  SUM(sales) AS total_sales,
  SUM(profit) AS total_profit
FROM global_sales
GROUP BY region;
