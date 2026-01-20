# 🎯 Data Warehouse and Analytics Project

Welcome to the Data Warehouse and Analytics Project repository! 🚀

This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.comprehensive guide to building a modern data warehouse with SQL Server, including ETL processes, data modeling, and analytics.

---

## 🏗️ Data Architecture
  The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:

<img width="2001" height="1135" alt="Picture1" src="https://github.com/user-attachments/assets/30504891-5e36-4462-82de-2cda65106505" />

  **1. Bronze Layer:** Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.<br>
  **2. Silver Layer:** This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.<br>
  **3. Gold Layer:** Houses business-ready data modeled into a star schema required for reporting and analytics.

---

## 📖 Project Overview

This project involves:

  **1. Data Architecture:** Designing a Modern Data Warehouse Using Medallion Architecture Bronze, Silver, and Gold layers.  <br>
  **2. ETL Pipelines:** Extracting, transforming, and loading data from source systems into the warehouse.  <br>
  **3. Data Modeling:** Developing fact and dimension tables optimized for analytical queries.  <br>
  **4. Analytics & Reporting:** Creating SQL-based reports and dashboards for actionable insights.  

---





## 🚀 Building the Data Warehouse (Data Engineering)

#### Objective

  Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications

  - **Data Sources:** Import data from two source systems (ERP and CRM) provided as CSV files.  <br>
  - **Data Quality:** Cleanse and resolve data quality issues prior to analysis.  <br>
  - **Integration:** Combine both sources into a single, user-friendly data model designed for analytical queries.  <br>
  - **Scope:** Focus on the latest dataset only; historization of data is not required.  <br>
  - **Documentation:** Provide clear documentation of the data model to support both business stakeholders and analytics teams.  

----

### 📊 BI: Analytics & Reporting (Data Analysis)

#### Objective

Develop SQL-based analytics to deliver detailed insights into:

  - **Customer Behavior**  <br>
  - **Product Performance**  <br>
  - **Sales Trends**  <br>

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

---

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project. (ERP and CRM data)
│   ├── source_crm                      # csv file cust_info, prod_info, sales details,
│   ├── source_erp                      # csv file category, customer, location.
│
├── documents/                          # Project documentation and architecture details.
│   ├── etl                             # Draw.io file shows all different techniquies and methods of ETL.
│   ├── data_architecture               # Draw.io file shows the project's architecture.
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata.
│   ├── data_flow                       # Draw.io file for the data flow diagram.
│   ├── data_models                     # Draw.io file for data models (star schema).
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files.
│
├── scripts/                            # SQL scripts for ETL and transformations.
│   ├── bronze_layer/                   # Scripts for extracting and loading raw data.
│   ├── silver_layer/                   # Scripts for cleaning and transforming data.
│   ├── gold_layer/                     # Scripts for creating analytical models.
│
├── tests/                              # Test scripts and quality files.
│
├── README.md                           # Project overview and instructions.
├── LICENSE                             # License information for the repository.

```
---

## 🌐 Important Links & Tools:

Everything is for Free!

- **[Datasets](https://github.com/GajendraTodkar/SQL-Data_Warehouse_Project/tree/main/dataset):** Access to the project dataset (csv files).  <br>
- **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads):** Lightweight server for hosting your SQL database.  <br>
- **[SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16):** GUI for managing and interacting with databases.
  

---
## ☕ Stay Connected

Let's stay in touch! Feel free to connect with me on the following platforms:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)]()
[![Website](https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=google-chrome&logoColor=white)]()


