# E-commerce Order & Customer Analytics

An end-to-end Azure Data Engineering project that transforms raw e-commerce data into business-ready analytics and Power BI visualizations.

## Architecture

**ADLS Gen2 → Azure Data Factory → Azure Databricks / PySpark → Delta Lake → Power BI**

## Technologies Used

- Azure Data Lake Storage Gen2
- Azure Data Factory (ADF)
- Azure Databricks
- PySpark and SQL
- Delta Lake
- Unity Catalog
- Power BI

## Data Engineering Workflow

1. **Bronze:** Store raw e-commerce data.
2. **Silver:** Clean, validate, and transform datasets.
3. **Gold:** Prepare analytics-ready tables for reporting.
4. **Orchestration:** Use Azure Data Factory to run and manage data processing.
5. **Visualization:** Build Power BI reports for sales and customer analytics.

## Key Analytics

- Total sales, order counts, and average order value
- Daily sales trends
- Revenue by product
- Customer spending and order activity
- Customer distribution by country
- Customer sign-up trends

## Project Status

The initial Power BI report has been built. Pipeline validation, documentation, and project cleanup are ongoing.

## Security

No credentials, access tokens, or private customer information should be committed to this repository.

## Author

Personal portfolio project demonstrating Azure data engineering skills.
