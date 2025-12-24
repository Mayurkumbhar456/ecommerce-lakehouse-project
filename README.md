# ecommerce-lakehouse-project
End-to-End Data Engineering pipeline using Databricks, Delta Lake, and Unity Catalog.
# End-to-End E-commerce Data Engineering Project

## Project Overview
This project builds a Lakehouse architecture using Databricks, Delta Lake, and Unity Catalog. It processes raw E-commerce data through Bronze, Silver, and Gold layers to generate business insights.

## Architecture
- **Bronze Layer:** Raw data ingestion (Parquet).
- **Silver Layer:** Data cleaning, deduplication, and schema enforcement (Delta Tables).
- **Gold Layer:** Business aggregations and KPIs.
- **Orchestration:** Databricks Workflows.

## Key Features
- **SCD Type 2:** Implemented for Customer dimension tracking.
- **Data Quality:** Automated validation checks.
- **Time Travel:** Disaster recovery demonstration using Delta Log.

## Tech Stack
- **Platform:** Databricks (Free Edition)
- **Language:** PySpark, SQL
- **Format:** Delta Lake, Parquet
