
# 🚀 NYC Taxi Data Engineering Project (End-to-End Pipeline)

## 📌 Overview

This project demonstrates a complete end-to-end data engineering pipeline using Azure and Databricks. The pipeline processes NYC Taxi data and transforms it into analytics-ready datasets using the Medallion Architecture.

The system is designed to handle large-scale data efficiently and provide business insights through Power BI dashboards.

---

## 🏗️ Architecture

The project follows the **Medallion Architecture (Lakehouse Architecture)**:

* **Bronze Layer** → Raw data ingestion from source
* **Silver Layer** → Data cleaning and transformation
* **Gold Layer** → Aggregated data for analytics



---

## 🔧 Tech Stack

* **Azure Data Factory (ADF)** → Data ingestion & orchestration
* **Azure Data Lake Gen2 (ADLS)** → Storage (Bronze, Silver, Gold)
* **Databricks (PySpark)** → Data processing & transformation
* **Delta Lake** → ACID transactions & optimized storage
* **Power BI** → Data visualization

---

## 🔄 Data Pipeline Flow

1. **Data Ingestion (ADF)**

   * Data fetched from API
   * Stored in Bronze layer (ADLS)

2. **Bronze Layer (Raw Data)**

   * Stored in Parquet format
   * No transformation applied

3. **Silver Layer (Transformation)**

   * Data cleaning & filtering
   * Schema inference and transformation using PySpark

4. **Gold Layer (Serving Layer)**

   * Aggregated data
   * Stored in Delta format
   * Optimized for analytics

5. **Visualization (Power BI)**

   * Connected to Databricks
   * Dashboard created for insights

---

## 📊 Key Features

* End-to-End Data Pipeline
* Scalable architecture using Databricks
* Medallion Architecture implementation
* Delta Lake for efficient querying
* Automated ingestion using ADF pipelines

---

## 📸 Project Screenshots

<img width="1919" height="589" alt="Screenshot 2026-04-03 144145" src="https://github.com/user-attachments/assets/59894df8-1220-44cf-b408-ed79a2ff70e4" />
<img width="1919" height="594" alt="Screenshot 2026-04-03 144200" src="https://github.com/user-attachments/assets/354a5b5e-e209-4163-927d-9d6a171f4853" />
<img width="1919" height="914" alt="Screenshot 2026-04-03 142546" src="https://github.com/user-attachments/assets/bc13073b-3f00-43c5-bc30-1d89d3d4d676" />
<img width="1919" height="974" alt="Screenshot 2026-03-31 133328" src="https://github.com/user-attachments/assets/f55f1aef-b981-4363-a331-a92ccce665fa" />
<img width="1919" height="911" alt="Screenshot 2026-04-03 121639" src="https://github.com/user-attachments/assets/6a2e2c78-0f0b-4c6d-a935-d825b49561cb" />

---

## 🎯 Learning Outcomes

* Real-world data engineering workflow
* Hands-on experience with Azure ecosystem
* Data transformation using PySpark
* Building scalable and optimized pipelines

---

## ▶️ Project Demo


---

## 🤝 Connect with Me

* LinkedIn: https://www.linkedin.com/in/vikass1/
* Email: [singhvikas81305@gmail.com](mailto:singhvikas81305@gmail.com)

---

⭐ If you like this project, give it a star!

[1]: https://community.databricks.com/t5/get-started-guides/getting-started-with-databricks-build-a-simple-lakehouse/ta-p/67404?utm_source=chatgpt.com "Getting Started with Databricks - Build a simple Lakehouse ..."
