![Lakehouse Architecture](./resources/databricks_architecture.png)

![Legacy Architecture](./resources/legacy_architecture.png)
🚀 E-Commerce Lakehouse Data Platform
📌 Overview

This project builds a complete end-to-end data platform for an e-commerce system using modern Lakehouse architecture.

It simulates how real-world companies process transactional data starting from an on-premise system to a scalable cloud-based analytics platform.

🏗️ Architecture
🧱 Lakehouse Architecture

🏛️ Legacy Architecture (For Comparison)

🔄 Data Flow
OLTP System
Customers interact with the e-commerce platform
Data stored in a relational database
Data Extraction
Python pulls data from the database
Data Lake Storage
Raw data stored in Amazon S3
Data Processing
Transformation and cleaning using Databricks
Data Modeling
Bronze → Silver → Gold layers
Data Serving
Data exposed to BI dashboards
🧠 Key Concepts
Lakehouse Architecture
ETL Pipelines
Data Warehousing
Fact & Dimension Modeling
Batch Processing
Data Ingestion
🛠️ Tech Stack
Python
SQL
Databricks
Amazon S3
AWS (Lambda, Glue, EC2)
Amazon Redshift
📊 Business Use Cases
Sales Analysis
Customer Behavior Insights
Revenue Tracking
Product Performance
⚡ Project Highlights
Built a scalable data pipeline from OLTP to analytics
Compared Legacy Data Warehouse vs Modern Lakehouse
Implemented multi-layer data architecture (Bronze/Silver/Gold)
Designed for real-world production scenarios
📁 Project Structure
.
├── notebooks/
├── scripts/
├── resources/
│   ├── databricks_architecture.png
│   └── legacy_architecture.png
├── README.md
🚀 Future Improvements
Real-time streaming (Kafka / Spark Streaming)
Data Quality Validation
Workflow orchestration (Airflow)
Machine Learning integration
👤 Author

Marwan Sitten
Data Science & Data Engineering Enthusiast
