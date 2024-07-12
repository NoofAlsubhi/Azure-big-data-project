# Azure Big Data Project 🌐💻

This repository contains the code and documentation for an Azure-based Big Data Engineering project. The project involves ingesting data from two sources, processing it using Azure services, and generating a report.

## Project Overview 🤖🗂️

The project aims to build a Big Data Engineering solution on Azure. It involves the following key components:

1. **Data Ingestion 🚚📥**: Data will be ingested from two data sources:
   - RDS Postgres database: The `Users` and `PostTypes` tables will be ingested and stored in the Azure Data Lake.
   - Azure Storage Blob Container: Daily `Posts` data files in Parquet format will be ingested and stored in the Azure Data Lake.

2. **Data Processing and Machine Learning 🧠🔍**:
   - The data in the Azure Data Lake will be processed and cleaned.
   - A Machine Learning model will be developed to classify the topics of the posts.
   - The results of the Machine Learning model will be stored back in the Azure Data Lake.

3. **Reporting 📊📈**:
   - Azure Synapse will be used to connect to the Azure Data Lake and generate a report displaying the top 10 topics of the day.

## Project Infrastructure 🏢⚙️

The project infrastructure is entirely built on Azure, consisting of the following components:

- **Azure Data Lake 🌊💾**: A data lake will be created to store the ingested data, processed data, and the output of the Machine Learning model.
- **Azure Data Factory (ADF) 🔧🤖**: ADF will be used to orchestrate the data ingestion and processing pipelines.
- **Azure Synapse 🔍📊**: Synapse will be used for data analysis and reporting.

## Project Execution 🚀🔬

The project is divided into the following parts:

1. **Data Ingestion 📥🗃️**: ADF pipelines will be created to ingest data from the RDS Postgres database and the Azure Storage Blob Container into the Azure Data Lake.
2. **Data Processing and Machine Learning 🧠🌐**: A Databricks notebook will be used to process the data, run the Machine Learning model, and store the results in the Azure Data Lake.
3. **Reporting 📊📈**: An Azure Synapse report will be created to display the top 10 topics of the day based on the output of the Machine Learning model.

For detailed instructions and implementation details, please refer to the project documentation and code within this repository.

