# MedallionAzure
This project implements a production-ready data engineering pipeline in Azure, focused on analyzing multi-branch car dealership data. It features incremental data loading, Slowly Changing Dimensions (SCD) management, and a robust star schema model. Built using Azure Data Factory, Databricks, and SQL Server, the solution follows the Medallion architecture to support enterprise-grade data orchestration and analytics.

# Concepts Implemented

Data Modeling: Star schema with well-defined fact and dimension tables (fact_sales, dim_branch, dim_dealer, dim_date)

Slowly Changing Dimensions (SCD): Captures historical changes in dealer and branch data

Change Data Capture (CDC): Supports incremental updates for efficient processing

Medallion Architecture: Bronze, Silver, and Gold layers for structured and scalable data transformation

Data Governance: Centralized access control using Unity Catalog

# Key Features

Data Ingestion: Ingest raw data (e.g., dealership transactions) into Azure Data Lake Storage Gen2 via Azure Data Factory

Data Transformation: Clean, enrich, and join datasets in Azure Databricks using PySpark, transforming them across Bronze → Silver → Gold layers

Data Warehousing: Load curated data into Azure SQL Server for reporting and BI consumption

Data Governance: Implement Unity Catalog for secure, scalable access control and metadata management

Pipeline Orchestration: End-to-end automation using Azure Data Factory

# Technologies Used

Azure Data Factory

Azure Databricks (PySpark)

Azure Data Lake Storage Gen2

Azure SQL Server

Unity Catalog

## Project Architecture

  ![image](https://github.com/user-attachments/assets/ccc816cb-6514-43a7-9cbf-d72ceb18596c)
