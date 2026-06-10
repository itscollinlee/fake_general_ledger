# Financial Data Platform – Databricks Medallion Architecture

## Overview

This project implements a production-grade Medallion Architecture in Databricks for General Ledger (GL) financial data processing.

The platform follows Bronze, Silver, and Gold data layers and incorporates enterprise data engineering patterns including:

* Incremental batch processing
* Delta Lake storage
* Schema evolution
* Idempotent ingestion
* Data lineage tracking
* Schema change monitoring
* Ingestion observability
* Dimensional modeling
* Financial reporting data marts

The solution is designed to be scalable, reusable, and auditable while supporting financial analytics and reporting workloads.

## Key Features

### Bronze Layer

* Incremental batch ingestion
* File-level lineage tracking
* Schema evolution
* Idempotent processing
* Ingestion control framework
* Schema change logging
* Operational observability

### Silver Layer

* Schema standardization
* Data cleansing
* Business rule enforcement
* Metadata preservation
* Incremental merge processing

### Gold Layer

* Star schema design
* Fact and dimension modeling
* Financial reporting datasets
* Aggregated analytics tables
* Executive KPI support

### Governance

* Batch-level auditing
* Data lineage
* Schema monitoring
* Operational metrics


Architectural Design

Source Files
     │
     ▼
Bronze Layer
     │
     ├── Ingestion Control
     ├── Schema Change Log
     ├── Observability
     └── Metadata Tracking
     │
     ▼
Silver Layer
     │
     ├── Standardization
     ├── Data Quality
     ├── Business Rules
     └── Conformed Data
     │
     ▼
Gold Layer
     │
     ├── Fact General Ledger
     ├── Dim Account
     ├── Dim Territory
     ├── Dim Calendar
     └── Financial Reporting

## Key Technologies

Databricks
Apache Spark
PySpark
Delta Lake
SQL
GitHub
Data Modeling
ETL/ELT
Medallion Architecture
