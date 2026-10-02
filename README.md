# 🛒 Walmart eCommerce ETL Pipeline

## 📌 Project Overview
This project demonstrates an end-to-end **ETL (Extract, Transform, Load) pipeline** built using Python. The pipeline processes Walmart eCommerce data, cleans and transforms it, and generates structured datasets for analysis and reporting.

The goal of this project is to simulate a real-world data engineering workflow involving **data ingestion, cleaning, transformation, and aggregation**.

---

## 🧰 Tech Stack
- Python
- Pandas
- Parquet / CSV Handling
- Jupyter Notebook
- ETL Concepts

---

## 📂 Dataset
The project uses multiple datasets:
- `clean_data.csv` → Processed and cleaned dataset  
- `extra_data.parquet` → Additional structured data  
- `agg_data.csv` → Aggregated output dataset  

---

## ⚙️ ETL Pipeline

### 🔹 Extract
- Loaded raw datasets from CSV and Parquet formats  
- Combined multiple data sources for processing  

### 🔹 Transform
- Cleaned missing and inconsistent values  
- Standardized column formats  
- Performed data type conversions  
- Merged datasets where necessary  
- Applied business logic for transformation  

### 🔹 Load
- Generated cleaned dataset → `clean_data.csv`  
- Created aggregated dataset → `agg_data.csv`  
- Prepared final outputs for analytics and reporting  

---

## 📊 Key Features
- Data cleaning and preprocessing pipeline  
- Handling multiple file formats (CSV + Parquet)  
- Data aggregation for insights  
- Modular ETL workflow design  

---

## 🚀 How to Run

1. Clone the repository
```bash
git clone https://github.com/your-username/walmart-etl-project.git
cd walmart-etl-project
