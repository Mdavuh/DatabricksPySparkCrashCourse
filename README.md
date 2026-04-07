# DatabricksPySparkCrashCourse
Official repository for the Databricks PySpark Crash Course. Contains the dummy datasets (CSV &amp; JSON) and PySpark notebooks used to master modern Data Engineering, Unity Catalog, and Delta Lake.

# Databricks PySpark Crash Course 🚀

Welcome to the official repository for the **Databricks PySpark Crash Course**! 

This repository contains all the dummy datasets, source code, and notebooks needed to follow along with the video tutorials. Whether you are transitioning from traditional data analytics or stepping into Data Engineering for the very first time, this course will take you from an absolute beginner to building production-ready data pipelines on the Data Intelligence Platform.

## 📂 Repository Contents

* **`/data`**: Contains the raw datasets used for ingestion.
    * `sales_data.csv`: Flat tabular data for basic ingestion and schema enforcement.
    * `events.json`: Nested, semi-structured data for arrays, structs, and flattening exercises.
* **`/notebooks`**: The Databricks notebooks containing the Python and SQL code for each module.

## 🧠 What You Will Learn
* **Environment Setup:** Provisioning a serverless Databricks workspace.
* **Data Ingestion:** Securely loading data using Unity Catalog Volumes and the `dbutils` SDK.
* **Core Transformations:** Mastering the PySpark DataFrame API (`select`, `filter`, `withColumn`, `when/otherwise`).
* **Optimization:** Leveraging Lazy Evaluation, Predicate Pushdown, and avoiding DAG Explosions.
* **Delta Lake:** Understanding ACID transactions, Z-Ordering, and Time Travel.

## 🚀 How to Use This Repository
1. Clone this repository or download the ZIP file.
2. Follow Lecture 2 to create a **Unity Catalog Volume** in your Databricks Free Edition workspace.
3. Upload the files from the `/data` folder into your new volume.
4. Import the notebooks into your Databricks workspace and start coding!
