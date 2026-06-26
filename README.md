# Retail Sales & Customer Intelligence Data Pipeline

## Overview
This project implements two cloud-based ETL pipelines for a retail company, ABX Retail Group. The pipelines extract transactional and customer data from a MySQL database, transform it using Python, and load it into Amazon S3 and Amazon Redshift for analytics and reporting.

The solution is designed to support sales analysis, customer intelligence, and future machine learning applications.

---

## Pipelines

### 1. Daily Sales Reporting Pipeline
Analyzes:
- Daily revenue and sales trends
- Product and category performance
- High-value orders
- Time-based insights (month, quarter, weekends)

**Business Value:**  
Supports revenue tracking, inventory planning, and demand forecasting.

### 2. Customer Segmentation Pipeline
Implements RFM (Recency, Frequency, Monetary) analysis to classify customers into segments such as:
- VIP
- Loyal
- At-Risk

**Business Value:**  
Enables targeted marketing, customer retention, and personalized campaigns.

---

## Tech Stack
- Python 3.12
- pandas
- SQLAlchemy + PyMySQL
- boto3
- Amazon S3
- Amazon Redshift
- psycopg2

---

## Architecture
MySQL → Python ETL → Amazon S3 → Amazon Redshift

- **MySQL** stores transactional and customer data
- **Python + pandas** handles extraction and transformation
- **Amazon S3** acts as the data lake
- **Amazon Redshift** stores analytics-ready datasets

---

## Features
- Modular ETL architecture
- Cloud-native pipeline design
- Automated data transformation and loading
- RFM-based customer segmentation
- Scalable and extensible workflow
- Ready for orchestration with Apache Airflow

---

## Future Enhancements
- Apache Airflow orchestration
- Docker containerization
- Data quality validation
- BI dashboards using Power BI or QuickSight
- ML-based churn prediction and customer analytics
