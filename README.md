# Snowflake_E2E_Pipeline
Snowflake_E2E_Pipeline

## Overview:
The goal of this project is to build a data pipeline for analyzing Amazon mobile devices sales across 3 regions- IN, US and FR. IT includes:
- Ingesting data from multiple sources (csv data for India, JSON data for France and parquet data for US)
- Loading it into Snowflake Internal stage and creating source (Bronze) tables
- Transforming data and loading it into curated (Silver) tables
- Perform aggregations and load fact and dimension (Gold) tables

## Dataset:
The data used in this project is 3-region-sales-data.zip

## Architecture:

<img src="Snowflake E2E pipeline.jpg">
