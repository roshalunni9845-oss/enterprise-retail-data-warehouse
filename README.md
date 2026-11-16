# Enterprise Retail Data Warehouse & Sales Dashboard

An end-to-end retail data project using **PostgreSQL** and **SQL** to build a star schema data warehouse, paired with an interactive **Power BI** dashboard that analyzes sales, products, and countries.

![Enterprise Retail Sales Dashboard](Dashboard.png)

---

## 🛠️ Tech Stack

- **Database & Data Warehouse:** PostgreSQL
- **Querying & ETL:** SQL
- **Data Visualization:** Microsoft Power BI
- **Documentation:** PDF project report

---

## 🏗️ Data Warehouse Architecture

- **Schema Design:** Star schema with a central fact table and supporting dimension tables, built for analytical queries.
- **Fact Table:** `fact_sales`
- **Dimension Tables:** `dim_customers`, `dim_products`, `dim_stores`, `dim_date`
- **ETL Process:** Raw retail data was cleaned, transformed, and loaded into the PostgreSQL tables with SQL.
- **Dataset size:** [X] rows in `fact_sales`

---

## 📊 Dashboard Overview

**KPI cards**

| Metric | Value |
|---|---|
| Total Sales | 10.31M |
| Total Orders | 19.69K |
| Units Sold | 5M |
| Average Order Value | 523.51 |

**Visuals**
- **Monthly Sales Trend:** sales by month across the data period.
- **Top 10 Products by Sales:** best-selling products, excluding non-product items such as postage and manual adjustments.
- **Sales by Country:** sales broken down by country.
- **Slicers:** filter by date range and by country.

**Data period:** 1 December 2010 to 6 December 2011. December 2011 is a partial month, so the drop at the end of the trend line is not a real decline.

---

## 🔍 Key Insights

- Sales rise through 2011 and peak in **November 2011** at about 1.5M.
- The **United Kingdom** accounts for the vast majority of sales.
- **Regency Cakestand 3 Tier** is the top-selling product.

---

## 📂 Repository Structure

- `sql_scripts/` – database creation, schema tables, and analytical SQL queries
- `Enterprise Retail Sales Dashboard.pbix` – Power BI report file
- `Dashboard.png` – preview of the dashboard
- `Enterprise_Retail_Data_Warehouse_Project.pdf` – project documentation and methodology

---

## 🚀 How to Run This Project

1. **Database setup:** Create a PostgreSQL database, then run the scripts in `sql_scripts/` to create the schema and load the tables.
2. **Open the dashboard:** Open `Enterprise Retail Sales Dashboard.pbix` in Power BI Desktop.
3. **Refresh the data:** Under **Transform data → Data source settings**, update the PostgreSQL connection details, then click **Refresh**.

---

## 📌 Data Source

[Name the dataset here and add a link, if it is a public one.]

---

## 🚀 Possible Next Steps

- Add profit and margin analysis.
- Add a product category breakdown.
- Add year-over-year comparisons once a full second year of data is available.
