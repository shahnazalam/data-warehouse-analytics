# 📊 Data Warehouse Analytics Project

## 📌 Project Overview
End-to-end data analytics project using SQL Server Data Warehouse (Gold Layer).
Analyzes sales, customer, and product data to uncover business insights.

## 🔧 Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Microsoft SQL Server Express
- Power BI
- SQLAlchemy + PyODBC

## 🗄️ Database Structure
| Table | Rows | Description |
|---|---|---|
| gold.dim_customers | 18,484 | Customer demographics |
| gold.fact_sales | 60,398 | Sales transactions |
| gold.dim_products | 295 | Product details |

## 📈 Key Findings
- **Bikes** generate 96% of total revenue ($28.3M)
- Customers **aged 56+** are the highest revenue contributors (45.7%)
- **Peak sales** in January 2014

## 💡 Business Recommendations
1. Focus marketing on **56+ age group**
2. Stock up on **Bikes** before winter season
3. Build **loyalty program** for older customers

## 📁 Project Structure
- data-project.ipynb — Python analysis notebook
- DataWarehouseAnalytics_powerbi.pbix — Power BI dashboard
- _sqlQuery/ — SQL queries folder
- csv-files/ — Raw data files
- README.md — Project documentation

## 👤 Author
Shahnaz ALam | Aspiring Data Analyst | Python | SQL | Power BI