# Data Engineering Portfolio

## Overview

This repository documents my journey to building a complete end-to-end Data Engineering platform while strengthening my skills in modern data technologies.

The project is developed incrementally, with each stage introducing new concepts and tools commonly used in production environments.

## Learning Objectives

- Python
- SQL
- Apache Spark
- Apache Airflow
- Databricks
- Docker
- dbt
- Data Architecture
- Git & GitHub

## Roadmap

- [x] Project initialization
- [ ] Data ingestion with Spark
- [x] Data transformation and processing
- [ ] Spark SQL
- [ ] Spark optimization and partitioning
- [ ] Workflow orchestration with Airflow
- [ ] Containerization with Docker
- [ ] Data modeling with dbt
- [ ] Analytics dashboard
- [ ] Automated testing
- [ ] CI/CD pipeline
- [ ] Complete documentation

## Project Structure

```text
data-engineering-portfolio/
├── data/
│   ├── raw/
│   └── processed/
├── docs/
├── notebooks/
├── src/
├── tests/
├── requirements.txt
└── README.md
```

## Progress Log

### 2026-07-29

- Initialized the repository
- Created the project structure
- Started reviewing Apache Spark fundamentals

### 2026-07-31

- Practiced core PySpark DataFrame transformations
- Worked with filtering, sorting, and derived columns
- Used conditional transformations with when() and otherwise()
- Practiced aggregations with groupBy() and agg()
- Worked with inner joins and joins using different column names
- Handled missing values and duplicate rows
- Combined DataFrames using unionByName()
- Worked with date transformations, filtering, and date differences
- Practiced window functions with partitionBy() and orderBy()
- Compared row_number(), rank(), and dense_rank()
- Reviewed the difference between Spark transformations and actions

### 2026-08-01

- Continued practicing PySpark window functions
- Used `lag()` to compare each transaction with the previous one
- Calculated cumulative values with explicit window frames using `rowsBetween()`
- Compared `rowsBetween()` with Spark's default range-based window behavior
- Created temporary SQL views with `createOrReplaceTempView()`
- Wrote a Spark SQL query using a CTE and `LAG()`
- Practiced date casting, partitioning, ordering, and derived columns in Spark SQL
- Compared the PySpark DataFrame API with Spark SQL


## Final Goal

Build a production-inspired data platform following a modern Data Engineering workflow:

```
Data Sources
     │
     ▼
Apache Spark
     │
     ▼
Data Lake (Parquet)
     │
     ▼
dbt
     │
     ▼
Analytics Dashboard
```

Throughout this project, the architecture will progressively evolve by introducing Airflow, Docker, testing, monitoring, and CI/CD to reflect real-world Data Engineering practices.