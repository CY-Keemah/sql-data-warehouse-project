# sql-data-warehouse-project
Building a modern data warehouse with SQL Server, including ETL processes, data modeling, and analytics.
## 📌 Project Overview
This project demonstrates the end-to-end design, implementation, and deployment of a modern Data Warehouse using **SQL Server**. It covers data ingestion, dimensional modeling (Star Schema), ETL pipeline execution, and analytical querying.

---

## 📐 Architecture & Layers

1. **Bronze Layer (Raw Data):** Ingests source data as-is into landing tables with minimal transformation.
2. **Silver Layer (Cleaned & Standardized):** Performs data cleansing, handling missing values, standardizing data types, and deduplication.
3. **Gold Layer (Business Aggregations & Analytics):** Organizes data into Fact and Dimension tables ready for reporting and business intelligence tools.

---

## 🛠️ Tech Stack & Tools

* **Database Engine:** Microsoft SQL Server (T-SQL)
* **Modeling Methodology:** Dimensional Modeling (Star Schema)
* **Query Tools:** SQL Server Management Studio (SSMS) / Azure Data Studio
* **Version Control:** Git & GitHub

---

## 📁 Repository Structure

```text
├── data/                    # Sample Datasets & CSV Files
├── scripts/
│   ├── 01_create_database.sql # Database schema setup
│   ├── 02_bronze_layer.sql   # Raw ingestion scripts
│   ├── 03_silver_layer.sql   # Data cleaning & transformation
│   └── 04_gold_layer.sql     # Star schema & view definitions
├── tests/                   # Data quality & integrity tests
└── README.md                # Project documentation
