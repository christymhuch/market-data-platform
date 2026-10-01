# SEC Financial Data Platform

An evolving data engineering project for ingesting, validating, transforming, and storing public financial filing data from the U.S. Securities and Exchange Commission (SEC).

## Project Goal

The goal of this project is to build a reliable financial data pipeline using real public SEC data.

The platform will eventually:

- Ingest company filing data from SEC EDGAR
- Validate and standardize incoming records
- Track new filings incrementally
- Store raw and transformed data
- Handle missing and inconsistent financial fields
- Create analysis-ready datasets
- Add data quality checks and pipeline monitoring

## Planned Architecture

SEC EDGAR  
↓  
Python Ingestion  
↓  
Raw Data  
↓  
Validation & Transformation  
↓  
SQL / Parquet Storage  
↓  
Analytics-Ready Tables

## Technologies

### Current
- Python
- SQL
- Git & GitHub

### Planned
- Pandas
- PostgreSQL or SQL Server
- Parquet
- PySpark
- Databricks
- Azure
- Apache Spark

## Development Roadmap

- [ ] Retrieve first SEC filing dataset
- [ ] Build Python ingestion script
- [ ] Save raw API response
- [ ] Transform filing data into structured tables
- [ ] Add SQL storage
- [ ] Add incremental ingestion
- [ ] Add automated data quality checks
- [ ] Store transformed data as Parquet
- [ ] Add Spark processing
- [ ] Migrate pipeline to Azure / Databricks

## Project Status

Currently under development.
