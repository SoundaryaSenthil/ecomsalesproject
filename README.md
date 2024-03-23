**Azure Data Engineering Project on Ecommerce Sales**

![dataeng](https://github.com/SoundaryaSenthil/ecomsalesproject/assets/161588836/5cfc7602-6c58-4f06-ac82-c6f309958799)
1. **Data Sources**: Various data sources including CSV, REST API, JSON, and on-premise SQL Server.
2. **Data Ingestion**: Ingesting data from these sources into Azure Data Lake Storage Gen2 (ADLS Gen2) using pipelines with basic transformations.
3. **Trigger Mechanisms**: Implementing scheduled and manual triggers for pipeline execution.
4. **Integration Runtime**: Using self-hosted and auto-resolve integration runtime for seamless data movement.
5. **Data Format Standardization**: Converting data to Parquet files for standardization and efficient storage.
6. **Data Processing in Databricks**: Moving data from ADLS Gen2 to Azure Databricks for further processing.
7. **Mounting Data Lake Gen2 to Databricks**: Mounting Azure Data Lake Storage Gen2 (ADLS Gen2) to Azure Databricks for easy access to files and data stored in ADLS Gen2 within the Databricks environment.
    This allows seamless integration of data stored in ADLS Gen2 with Databricks for processing and transformation tasks
8. **Transformations**:Implementing Slowly Changing Dimension (SCD) Type 1 and Type 2 in Databricks for managing changing data.
9.  **Delta Files and Tables**: Utilizing Delta files in Databricks for data storage and management.
   Delta tables are employed for validation purposes, ensuring data consistency, reliability, and integrity throughout the data engineering process. This includes features such as ACID transactions, time travel, and schema enforcement for robust data validation and quality assurance.
11. **Data Quality Checks**: Performing duplication checks and identifying missing or duplicate rows.
12. **Data Storage and Presentation**: Storing final data in Azure Synapse Analytics, creating tables or views based on customer requirements.
13. **Visualization**: Integrating data into Power BI for visualization and analytics. This project demonstrates a robust end-to-end data engineering pipeline on Azure, covering ingestion, processing, transformation, quality checks, storage, and visualization.
