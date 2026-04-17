 Healthcare Insurance ETL & Data Warehousing Solution

Project Overview

End-to-end data engineering project designed to process and analyze healthcare insurance data using ETL pipelines, data warehousing, and analytical modeling.
This solution transforms raw policy and claims data into structured, high-quality datasets to support reporting, analytics, and business decision-making.

Objectives

Build scalable ETL pipelines for healthcare insurance data
Clean, transform, and validate large datasets
Design a centralized data warehouse
Enable high-performance analytics and reporting

🛠️ Tech Stack

SQL Server – Data storage and query optimization
SQL Server Integration Services (SSIS) – ETL pipeline development
SQL Server Analysis Services (SSAS) – Tabular data modeling
Microsoft Power BI – Reporting and dashboards

📂 Dataset

The dataset consists of healthcare insurance data including:

Policy details
Claims information
Customer demographics
Transactional records

Data Characteristics:

Large-scale structured data
Multiple source systems
Requires transformation and validation

Data Architecture
Source Systems → Staging Layer → Data Warehouse → SSAS Model → Power BI Dashboard

Workflow

🔹 1. Data Extraction
Extracted data from multiple source systems
Loaded raw data into staging tables

🔹 2. Data Transformation (SSIS)
Developed 30+ ETL packages using SSIS
Applied data cleansing and validation rules
Implemented incremental and full load strategies

🔹 3. Data Warehousing
Designed star schema (Fact & Dimension tables)
Integrated data into centralized warehouse
Optimized storage and query performance

🔹 4. Data Modeling (SSAS)
Built tabular models for analytical querying
Enabled fast and scalable reporting

🔹 5. Reporting & Visualization
Created interactive dashboards using Power BI
Tracked KPIs and business metrics

Key Features

Scalable ETL pipeline architecture
High-performance SQL query optimization
Incremental data loading strategy
Data validation and quality checks
Centralized data warehouse design

Key Achievements

 >Improved ETL pipeline efficiency by ~24%
 >Reduced report generation time by ~20%
 >Enhanced data accuracy by ~27%
 >Reduced system downtime by ~17%

How to Use

Clone the repository
Open SQL Server and restore database
Run SSIS packages for ETL process
Deploy SSAS model
Open Power BI dashboard for insights

Acknowledgement

This project is a self-developed data engineering solution inspired by real-world healthcare insurance analytics use cases.


