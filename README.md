# Medallion Architecture Demo: Python ETL Pipeline

[![Python](https://img.shields.io/badge/Python-3.8+-blue)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

A hands-on demonstration of **Medallion Architecture** (Bronze → Silver → Gold layers) using Python and CSV data. This project shows an end-to-end **ETL pipeline** from raw data ingestion to analytics-ready outputs.

---

## **Project Overview**

This project simulates an **e-commerce transactions dataset** to demonstrate:

* **Bronze Layer:** Raw ingested CSV data
* **Silver Layer:** Cleaned & enriched dataset (duplicates removed, missing values handled, computed columns added)
* **Gold Layer:** Aggregated analytics data (total revenue per product, monthly revenue trends)

The project highlights **continuous learning through practical projects**, showcasing **data engineering best practices**.

---

## **Project Structure**

```text
medallion-architecture-demo/
│
├── bronze_transactions.csv       # Raw dataset
├── silver_transactions.csv       # Cleaned & enriched dataset
├── gold_product_summary.csv      # Aggregated revenue per product
├── gold_monthly_summary.csv      # Aggregated revenue per month
├── medallion_pipeline.ipynb      # Jupyter Notebook with full ETL workflow
├── README.md                     # Project documentation
└── requirements.txt              # Python dependencies
```

---

## **Features**

* Simulated realistic transactions dataset with `Faker`
* Bronze → Silver → Gold ETL pipeline implemented in Python
* Data cleaning, enrichment, and aggregation
* Visualizations for product revenue and monthly trends
* Optional SQLite integration for layered storage
* Logging and row counts for pipeline auditability

---

## **Setup & Usage**

### **Prerequisites**

* Python 3.8+
* Libraries: `pandas`, `numpy`, `faker`, `matplotlib`, `seaborn`, `sqlite3` (standard library)

Install dependencies:

```bash
pip install pandas numpy faker matplotlib seaborn
```

### **Run the Notebook**

1. Clone the repository:

```bash
git clone https://github.com/your-username/medallion-architecture-demo.git
cd medallion-architecture-demo
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook
```

3. Open `medallion_pipeline.ipynb` and run all cells to:

   * Generate Bronze layer CSV
   * Clean and enrich data into Silver layer
   * Aggregate Gold layer for analytics
   * Visualize revenue per product and monthly trends

---



> Replace these placeholder images with your generated charts from the notebook.

---

## **Key Learning Outcomes**

* Implemented **layered data architecture** (Bronze → Silver → Gold)
* Hands-on **ETL workflow in Python**
* Data cleaning, enrichment, and aggregation techniques
* Visualizing insights for stakeholders

---

## **Future Enhancements**

* Integrate with **cloud storage** (Azure Data Lake / AWS S3)
* Use **DuckDB or Spark** for larger datasets
* Add **automated data validation and schema checks**
* Schedule ETL pipeline with **Airflow** or **Prefect**




