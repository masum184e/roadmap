# DuckDB Learning Roadmap

## 1. Foundations
- [What is DuckDB? (overview, use cases, comparisons with SQLite & OLAP DBs)](#)  
- [Installation & setup](#)  
- [DuckDB CLI](#)    
- [DuckDB architecture basics](#)  
- In-memory columnar storage  
- Single-node analytics vs distributed databases  

## 2. Core SQL in DuckDB
- [Basic SQL syntax (SELECT, WHERE, ORDER BY, LIMIT)](#)  
- [Joins (INNER, LEFT, RIGHT, CROSS)](#)  
- Aggregations (SUM, COUNT, AVG, GROUP BY, HAVING)  
- Subqueries & CTEs (WITH clause)  
- Window functions (ROW_NUMBER, RANK, PARTITION BY, etc.)  

## 3. Data Ingestion & Export
- Reading from CSV, Parquet, JSON  
- Writing to CSV, Parquet  
- Importing data directly from Pandas / R dataframes  
- Reading data from cloud storage (S3, GCS, Azure Blob)  
- Working with large datasets (lazy loading, efficient scanning)  

## 4. Advanced Features
- Vectorized execution model  
- Working with Parquet files efficiently  
- Views & Materialized Views  
- DuckDB extensions (e.g., HTTPFS for remote files)  
- Querying directly on external files without importing  

## 5. Performance Optimization
- Columnar storage benefits  
- Predicate pushdown  
- Parallel execution  
- Efficient joins & query planning  
- Memory management  

## 6. Integration with Ecosystem
- Using DuckDB inside Python (pandas, polars, numpy)  
- Integration with R (dplyr, tidyverse)  
- DuckDB + Arrow interoperability  
- DuckDB in Jupyter Notebooks  
- Using DuckDB with BI tools (Tableau, Power BI, Superset)  

## 7. Advanced SQL & Analytics
- Time-series functions  
- Statistical functions  
- Geospatial extensions (if enabled)  
- Recursive CTEs  
- Complex data types (lists, structs, maps)  

## 8. Deployment & Use Cases
- Embedded database usage (DuckDB as a library)  
- OLAP analytics on laptops/servers  
- ETL pipelines with DuckDB  
- DuckDB in data science workflows  
- DuckDB in serverless & edge computing  

## 9. Internals & Extensions (Optional Deep Dive)
- DuckDB query execution internals  
- Writing custom DuckDB extensions  
- Contributing to DuckDB source code  
- Comparison with other OLAP engines (ClickHouse, Druid, BigQuery)  
