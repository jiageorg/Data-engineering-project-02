# End-to-End Azure Data Engineering Project

## Overview

This comprehensive Azure Data Engineering project focuses on building an end-to-end data platform, encompassing **Data Ingestion**, **Data Transformation**, **Data Loading**, and **Reporting**. The project's use case involves ingesting tables from an on-premise SQL Server database using **Azure Data Factory**, storing the data in **Azure Data Lake**, transforming the raw data using **Azure Databricks**, loading the clean data into **Azure Synapse Analytics**, and creating an interactive dashboard with **Microsoft Power BI**. Additionally, **Azure Active Directory (AAD)** and **Azure Key Vault** are employed for monitoring and governance purposes.

## Architecture

![Project Architecture](https://github.com/jiageorg/Data-engineering-project-02/blob/master/architecture.png)

The architecture diagram provides an overview of the end-to-end data engineering solution, illustrating the flow of data from ingestion to reporting.
# Database Import Instructions

Follow the link below to import the database used in this project to the SQL Server Management Studio (SSMS):

[AdventureWorks Database Import](https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms)

Ensure that you are using the lightweight version of SSMS for a smoother experience.

# Tools Covered in this Project

The project utilizes the following Azure tools:

1. **Azure Data Factory**
2. **Azure Data Lake Storage Gen2**
3. **Azure Databricks**
4. **Azure Synapse Analytics**
5. **Azure Key Vault**
6. **Azure Active Directory (AAD)**
7. **Microsoft Power BI**
   
## Azure Data Factory Pipeline

![ADF Pipeline](https://github.com/jiageorg/Data-engineering-project-02/blob/master/Azure_ADF_Pipeline.png)

The Azure Data Factory (ADF) pipeline image showcases the orchestrated workflow for ingesting data from the on-premise SQL Server database into Azure Data Lake.

## Azure Synapse Analytics Pipeline

![Synapse Pipeline](https://github.com/jiageorg/Data-engineering-project-02/blob/master/Synapse_ADF_pipeline.png)

The Azure Synapse Analytics pipeline image depicts the process of transforming and loading the cleansed data from Azure Data Lake into Azure Synapse Analytics for further analysis and reporting.

Feel free to explore the individual images for a detailed understanding of each stage in the data engineering project. For more information on the project, refer to the relevant documentation and code in the repository.
