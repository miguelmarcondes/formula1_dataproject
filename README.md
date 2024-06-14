This project has the purpose of fleshing out Databricks, Spark and Azure environment techniques. I am using the Ergast's Formula 1 API.

The project uses Databricks for data transformation, Azure Delta Lake for storage, Azure Data Factory for orchestration. The Medallion Architecture is in place aswell as different techniques from Databricks like volume mounted,
Delta files, tables, views and optimal implementation of Spark code.

## Project structure

1. Analysis: Folder used for the analysis part of the project, delivering insights based on the processed data
2. Demo: Folder focused on working out examples and getting the synthax down for various functionalities in Spark, Databricks and Delta Lake
3. Includes: Utility folder used for configuration and common functions
4. Ingestion: Folder focused on ingesting data from the API, tipically from CSV and JSON files
5. Raw: Scrip used to create the Raw (Bronze) layer of the project
6. Set-up: Folder focused on mounting the different layers and storages located on ADL
7. Trans: Transformation folder, focused on aggregating data and delivering it to the presentation (Gold) layer
8. Utils: Clean up scripts
