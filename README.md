# 🚀 Serverless Data Pipeline on GCP with Airflow, DBT & Terraform

This project demonstrates a scalable, cost-effective **serverless data pipeline** built entirely on **Google Cloud Platform** using:

- **Cloud Storage** for ingestion
- **BigQuery** for data warehousing
- **DBT** for transformation
- **Cloud Composer (Airflow)** for orchestration
- **Terraform** for Infrastructure-as-Code (IaC)

## 🧠 Problem

Companies often struggle with setting up robust, scalable pipelines that are cost-effective and easy to manage without deep DevOps overhead.

## ✅ Solution

This repo provides an end-to-end data pipeline template using **fully-managed GCP services** and **Terraform**, allowing for rapid deployment, version control, and reproducibility.

## 📊 Architecture

## 🛠️ Tech Stack

| Component      | Tool                     |
|----------------|--------------------------|
| Cloud Platform | Google Cloud (GCP)       |
| Storage        | Cloud Storage            |
| ETL Engine     | DBT                      |
| Warehouse      | BigQuery                 |
| Orchestration  | Cloud Composer (Airflow) |
| IaC            | Terraform                |
| Language       | Python, SQL              |

## 📁 Repo Structure
```
gcp-serverless-de-pipeline/
├── dags/                 # Airflow DAGs
│   └── main_dag.py
├── dbt/                  # DBT models
│   └── models/
├── terraform/            # Infra-as-code scripts
│   └── main.tf
├── data/                 # Sample input data
│   └── input.csv
├── notebooks/            # Optional analysis notebooks
└── README.md
```
## 🚀 How to Use

1. Clone the repo
2. Deploy infrastructure with Terraform
3. Upload data to Cloud Storage
4. Trigger DAG to ingest → transform → load data into BigQuery

## 🔄 Future Improvements

- Add streaming ingestion with Pub/Sub or Kafka
- Add unit tests with Pytest
- Extend with real-time ML inference pipeline

## 📣 Author

**Pradeep Kumar**  
[LinkedIn](https://www.linkedin.com/in/pradeep22saini/) | [Portfolio](#)

---