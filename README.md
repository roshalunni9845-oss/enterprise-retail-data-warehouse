# Enterprise Retail Data Warehouse & Sales Dashboard

An end-to-end **Enterprise Retail Data Warehouse** built using **PostgreSQL** and **SQL**, paired with an interactive **Power BI** executive dashboard to analyze retail sales, customer behavior, and product performance.

![Enterprise Retail Sales Dashboard](Dashboard.png)

---

## 🛠️ Tech Stack
* **Database & Data Warehouse:** PostgreSQL
* **Querying & ETL:** SQL (DDL, DML, Views, Stored Procedures)
* **Data Visualization:** Microsoft Power BI
* **Documentation:** PDF Project Report

---

## 🏗️ Data Warehouse Architecture
* **Schema Design:** Star Schema (Fact and Dimension tables) optimized for analytical queries.
* **Core Fact Table:** `fact_sales` (transactions, revenue, quantity sold, discounts).
* **Dimension Tables:** `dim_customers`, `dim_products`, `dim_stores`, `dim_date`.
* **ETL Process:** Cleaned, transformed, and loaded raw retail datasets into structured PostgreSQL tables.

---

## 📊 Key Dashboard Insights
* **Revenue & Profit Tracking:** Monitors total sales, profit margins, and year-over-year growth.
* **Product Performance:** Identifies top-selling categories, slow-moving inventory, and return rates.
* **Customer & Regional Analysis:** Breaks down sales performance across store locations and customer segments.

---

## 📂 Repository Structure
* `sql_scripts/` – Database creation, schema tables, and analytical SQL queries
* `Enterprise Retail Sales Dashboard.pbix` – Interactive Power BI report file
* `Dashboard.png` – High-resolution preview of the Power BI dashboard
* `Enterprise_Retail_Data_Warehouse_Project.pdf` – Full project documentation and methodology

---

## 🚀 How to Run This Project
1. **Database Setup:** Run the SQL scripts in PostgreSQL to create the schema and load the tables.
2. **Power BI Connection:** Open `Enterprise Retail Sales Dashboard.pbix` in Power BI Desktop.
3. **Refresh Data:** Update the PostgreSQL data source credentials under **Transform data > Data source settings** and click **Refresh**.
4.# enterprise-retail-data-warehouse
End-to-end Enterprise Retail Data Warehouse built with PostgreSQL and SQL (Star Schema &amp; ETL validation), paired with an interactive Power BI sales and customer analytics dashboard.
