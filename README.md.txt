# Data Pipeline / ETL

## Project Overview
ETL pipeline to ingest, transform, and store large datasets (CSV/JSON). Demonstrates data cleaning, transformation, storage, and automation with Spark.

## Tech Stack
- Python 3
- PySpark
- SQL / MySQL
- Cron / Airflow for automation

## Features
- Data ingestion from multiple sources
- Cleans & transforms data
- Writes output to SQL or Parquet files
- Logs metrics: records processed, time taken

## Metrics
- Processes 1M+ records in < 5 minutes
- Handles missing or malformed data automatically
- Logs stored for tracking & monitoring

## Architecture Diagram
[Raw CSV/JSON] --> [PySpark ETL] --> [SQL DB / Parquet Storage]
|
v
[Logs & Metrics]


## How to Run
1. Clone repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run `etl.py` → processes `sample_data/emissions.csv`
4. Check output in `output/` folder

## Key Learnings
- Big data processing with Spark
- Data pipeline automation & logging
- Working with structured and semi-structured data
