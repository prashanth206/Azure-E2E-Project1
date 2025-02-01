# Azure-E2E-Project1

- This project demonstrates the end-to-end data engineering project following the Medallion Architecture.

## Key Features:
1. **Data Ingestion:** Extract data from an HTTP server and load it into SQL Server. 
2. **Incremental Loading:** Move data incrementally from SQL Server to Azure Data Lake Storage Gen2 (ADLS Gen2).
3. **Data Transformation:** Load data from ADLS Gen2 into Azure Databricks using Unity Catalog and apply data transformations.
4. **Dimension Modeling:** Design and create Fact and Dimension tables for analytical purposes.  
5. **Pipeline Orchestration:** Automate and manage data workflows using Azure Data Factory (ADF) and Databricks Workflows.
