# MedallionAzure
This project implements a production-ready data engineering pipeline in Azure, featuring **incremental data loading** and **Slowly Changing Dimensions (SCD)** management. Built with Azure Data Factory, Databricks, and SQL Server, it follows the Medallion architecture for enterprise-grade data orchestration.

## Concepts Implemented:-
-Data modeling — star schema (Fact & Dimensions modeling)

-Slowly changing dimensions handling & Change Data Capture (CDC)

-Data Design Pattern: Medialion Architecture

-Azure Services for Data Engineering

## Key Features
- **Data Ingestion:** Ingest data from an API into Azure Data Lake Storage Gen2 using Azure Data Factory.
- **Data Transformation:** Clean, transform, and enrich data in Azure Databricks using PySpark (Bronze, Silver, Gold layers).
- **Data Warehousing:** Load processed data into Azure SQL Server for analytics.
- **Data Governance:** Implement Unity Catalog for data governance in Databricks.
- **Automation:** Orchestrate the pipeline using Azure Data Factory.

## Technologies Used
- Azure Data Factory
- Azure Databricks (PySpark)
- Azure Data Lake Storage Gen2
- Azure SQL Server
- Unity Catalog

## Project Architecture

  ![image](https://github.com/user-attachments/assets/ccc816cb-6514-43a7-9cbf-d72ceb18596c)
