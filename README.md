# sql-data-warehouse-project
Building a modern datawarehouse with SQL Server, including ETL processes, data modeling and analytics.
# SQL Data Warehouse Project

## 📌 Project Overview

This project is a modern **SQL Server Data Warehouse** designed to consolidate sales data from two source systems: **ERP** and **CRM**.

The goal is to clean, transform, and integrate raw CSV data into a business-ready data model that supports analytical reporting and decision-making.

The project follows the **Medallion Architecture** approach:

- **Bronze Layer**: Raw data
- **Silver Layer**: Cleaned and transformed data
- **Gold Layer**: Business-ready analytical model

---

## 🚀 Project Objectives

### Data Engineering

The objective is to build a SQL Server data warehouse that:

- Imports data from ERP and CRM CSV files
- Cleans and resolves data quality issues
- Integrates multiple data sources into one model
- Creates a user-friendly analytical data model
- Provides clear documentation for business and analytics teams

### Data Analytics

The project also includes SQL-based analytics focused on:

- Customer behavior
- Product performance
- Sales trends

These insights help stakeholders understand business performance and make better decisions.

---

## 🏗️ Data Architecture

The data warehouse is built using three layers:

### Bronze Layer

The Bronze layer contains raw data loaded directly from the source CSV files.

### Silver Layer

The Silver layer contains cleaned, standardized, and transformed data.

### Gold Layer

The Gold layer contains the final business-ready model used for analytics and reporting.

This layer is designed using a **star schema** with fact and dimension tables.

---

## 📂 Repository Structure

```text
data-warehouse-project/
│
├── datasets/                           # Raw ERP and CRM datasets
│
├── docs/                               # Project documentation and architecture files
│   ├── etl.drawio                      # ETL techniques and methods
│   ├── data_architecture.drawio        # Data warehouse architecture
│   ├── data_catalog.md                 # Dataset catalog and field descriptions
│   ├── data_flow.drawio                # Data flow diagram
│   ├── data_models.drawio              # Data model and star schema
│   ├── naming-conventions.md           # Naming guidelines
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Raw data loading scripts
│   ├── silver/                         # Cleaning and transformation scripts
│   ├── gold/                           # Analytical model scripts
│
├── tests/                              # Data quality and validation scripts
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # MIT License
├── .gitignore                          # Git ignored files
└── requirements.txt                    # Project requirements

📌 Project Scope

This project focuses only on the latest available dataset.

Historical tracking and historization are not included.

🧠 Skills Demonstrated

This project demonstrates skills in:

Data warehousing
SQL Server
T-SQL
ETL development
Data cleaning
Data modeling
Star schema design
Data quality testing
Analytical SQL
Technical documentation
📄 License

This project is licensed under the MIT License.

👤 Author

Amine Malainine

SQL Data Warehouse Project built with SQL Server and T-SQL.
