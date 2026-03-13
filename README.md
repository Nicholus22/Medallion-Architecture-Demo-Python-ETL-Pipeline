# Medallion-Architecture-Demo-Python-ETL-Pipeline

A hands-on demonstration of Medallion Architecture (Bronze → Silver → Gold layers) using Python and CSV data. This project showcases an end-to-end ETL pipeline from raw data ingestion to analytics-ready outputs.

Project Overview

This project simulates an e-commerce transactions dataset to demonstrate:

Bronze Layer: Raw ingested data (audit-ready CSV).

Silver Layer: Cleaned and enriched dataset (duplicates removed, missing values handled, computed columns added).

Gold Layer: Aggregated, analytics-ready data (e.g., total revenue per product, monthly revenue trends).

The goal is to illustrate continuous learning through practical projects, showcasing data engineering best practices and pipeline design.

Project Structure
medallion-architecture-demo/
│
├── bronze_transactions.csv       # Raw dataset
├── silver_transactions.csv       # Cleaned & enriched dataset
├── gold_product_summary.csv      # Aggregated revenue per product
├── gold_monthly_summary.csv      # Aggregated revenue per month
├── medallion_pipeline.ipynb      # Jupyter Notebook with full ETL workflow
├── README.md                     # Project documentation
└── requirements.txt              # Python dependencies
Features

Data generation for a realistic transactions dataset

Bronze → Silver → Gold ETL pipeline implemented in Python

Data cleaning, enrichment, and aggregation

Visualizations for product revenue and monthly trends

SQLite integration for layered data storage (optional)

Logging row counts for pipeline auditability

Getting Started
Prerequisites

Python 3.8+

Libraries: pandas, numpy, faker, matplotlib, seaborn, sqlite3 (standard library)

Install dependencies via pip:

pip install pandas numpy faker matplotlib seaborn
Run the Notebook

Clone the repository:

git clone https://github.com/your-username/medallion-architecture-demo.git
cd medallion-architecture-demo

Launch Jupyter Notebook:

jupyter notebook

Open medallion_pipeline.ipynb and execute cells sequentially to see:

Data generation

Bronze layer creation

Silver layer cleaning & enrichment

Gold layer aggregation and visualizations

Key Learning Outcomes

Understanding layered data architecture

Hands-on ETL implementation using Python

Experience with data cleaning, enrichment, and aggregation

Visualizing insights for stakeholders

Future Enhancements

Integrate with cloud storage (Azure Data Lake / AWS S3)

Use DuckDB or Spark for large-scale processing

Add automated data validation and schema checks

Deploy as a scheduled pipeline using Airflow or Prefect
