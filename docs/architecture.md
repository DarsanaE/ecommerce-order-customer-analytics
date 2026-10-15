# Project Architecture

## E-commerce Order & Customer Analytics

This project demonstrates an end-to-end Azure data engineering workflow for transforming raw e-commerce data into business-ready analytics.

### Technology Stack
- Azure Data Lake Storage Gen2
- Azure Data Factory
- Azure Databricks
- PySpark
- Delta Lake
- Unity Catalog
- Power BI

### Data Flow
Raw CSV files → Bronze layer → Silver layer → Gold layer → Power BI dashboard

### Project Objectives
- Ingest and store raw e-commerce data.
- Clean and validate data using PySpark.
- Transform data into analytics-ready Gold tables.
- Orchestrate processing with Azure Data Factory.
- Visualize sales and customer insights in Power BI.
