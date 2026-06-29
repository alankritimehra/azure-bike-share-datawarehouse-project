# Bike Share Data Warehouse on Azure

## Overview

This project demonstrates the design and implementation of a cloud-based data warehouse for the Divvy Bike Share dataset using Microsoft Azure. The solution integrates Azure SQL Database, Azure Data Lake Storage Gen2, and Azure Synapse Analytics to ingest, transform, and analyze bike-sharing data.

The project follows modern data warehousing principles by implementing a star schema and creating analytical datasets optimized for reporting and business intelligence.

---

## Architecture

Azure SQL Database → Azure Data Lake Storage Gen2 → Azure Synapse Analytics → Star Schema → Analytics Queries

---

## Technologies Used

- Microsoft Azure
- Azure Synapse Analytics
- Azure SQL Database
- Azure Data Lake Storage Gen2
- SQL
- CETAS (Create External Table As Select)
- External Tables
- Star Schema Design

---

## Project Objectives

- Build a cloud-based analytical data warehouse.
- Import operational bike-share datasets into Azure.
- Design a dimensional model using a star schema.
- Create external tables for querying data stored in Azure Data Lake.
- Generate curated datasets for analytical reporting.

---

## Data Model

The warehouse follows a Star Schema consisting of:

### Fact Table
- FactTrip

### Dimension Tables
- DimDate
- DimStation
- DimRider
- DimPayment

*(Refer to `star_schema/schema.png` for the complete schema.)*

---

## Repository Contents

- `Project_Data_Warehouse.ipynb` – Complete implementation of the Azure data warehouse project.
- `schema.png` – Star schema used for dimensional modeling.

---

## Key Features

- Azure cloud-based data warehouse implementation
- Star schema dimensional modeling
- External table creation in Azure Synapse
- CETAS for optimized analytical datasets
- SQL-based transformation and querying
- End-to-end analytics workflow

---

## Results

Successfully developed an Azure-based data warehouse capable of supporting analytical workloads on bike-sharing data. The implementation demonstrates cloud data warehousing concepts including dimensional modeling, external tables, and data transformation within Azure Synapse Analytics.

---

## Future Improvements

- Automate ingestion using Azure Data Factory
- Implement incremental data loading
- Add Power BI dashboards for visualization
- Optimize query performance through partitioning and indexing

---

## Author

**Alankriti Mehra**

Aspiring Data Engineer | Python | SQL | Azure | Data Warehousing | Apache Spark
