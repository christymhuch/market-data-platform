An evolving data engineering project for ingesting, validating, transforming, and storing financial market data.

## Project Goal

The goal of this project is to build a reliable market-data pipeline that can process trading events while handling common real-world data engineering challenges such as:

- Duplicate events
- Missing sequence numbers
- Out-of-order events
- Invalid or malformed records
- Late-arriving data
- Large historical datasets

## Planned Architecture

Market Data  
↓  
Python Ingestion  
↓  
Data Validation  
↓  
Cleaned Data  
↓  
SQL / Parquet Storage  
↓  
Analytics and Monitoring

## Technologies

### Current
- Python
- SQL
- Git & GitHub

### Planned
- PostgreSQL or SQL Server
- Parquet
- Apache Kafka
- Apache Spark / PySpark
- Databricks
- Linux

## Development Roadmap

- [ ] Build initial market-data dataset
- [ ] Create Python ingestion pipeline
- [ ] Add data validation
- [ ] Detect duplicate and missing events
- [ ] Store processed data in SQL
- [ ] Add Parquet storage and partitioning
- [ ] Implement streaming with Kafka
- [ ] Build order-book reconstruction
- [ ] Process historical data with Spark
- [ ] Build a market replay engine

## Project Status

Currently under development.
