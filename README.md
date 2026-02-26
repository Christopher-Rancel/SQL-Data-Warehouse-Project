# SQL Data Warehouse Pipeline (Medallion Architecture)

## Project Overview

This project simulates a simplified end-to-end data engineering pipeline using a layered Medallion Architecture approach (Bronze → Silver → Gold).

The objective was to design and implement a structured data warehouse workflow that transforms raw operational data into analytics-ready datasets suitable for reporting and KPI tracking.

---

## Architecture Design

The project follows a **3-layer Medallion structure**:

### Bronze Layer – Raw Data Ingestion
- Loads raw CSV datasets into staging tables
- Preserves original structure
- Simulates initial ingestion process

### Silver Layer – Data Cleaning & Transformation
- Cleans and standardizes raw data
- Applies transformation logic
- Improves data consistency
- Prepares structured relational entities

### Gold Layer – Analytics-Ready Data
- Builds analytical tables
- Optimized for reporting and KPI analysis
- Supports BI consumption and dashboarding

---

## Data Flow

Raw CSV → Bronze Tables → Silver Transformations → Gold Analytical Tables

This simulates a simplified ETL pipeline fully implemented in SQL.

---

## Technologies & Concepts Used

- SQL
- Data Warehousing
- Medallion Architecture
- ETL Simulation
- Relational Modeling
- Analytical Query Design

---

## Repository Structure

```
dataset/
script/
   bronze/
      ddl_bronze.sql
      proc_load_bronze.sql
   silver/
      ddl_silver.sql
      proc_load_silver.sql
   gold/
      ddl_gold.sql
tests/
```

---

## What This Project Demonstrates

- Understanding of data pipeline layering
- Structured data transformation lifecycle
- Relational data modeling
- Analytical table design
- Data engineering mindset using SQL

---

## Key Learning Outcomes

- Separation of raw, cleaned, and analytical data layers
- Implementation of transformation logic between stages
- Foundation for scalable data warehouse design
- Preparation of BI-ready datasets

---

## Context

This project represents foundational data engineering concepts implemented using pure SQL and structured pipeline design principles. It serves as a stepping stone toward cloud-based data engineering systems.
