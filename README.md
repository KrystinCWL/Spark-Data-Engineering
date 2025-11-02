# 🚀 Spark Data Engineering Projects

A comprehensive PySpark portfolio demonstrating end-to-end data engineering and analytics workflows — covering **RDDs**, **SQL**, **Hive Context**, **Streaming**, and **GraphFrames**.  
Each project focuses on a distinct dataset and analytical challenge to showcase versatility in handling structured, semi-structured, and streaming data using Spark.

---

## 🧠 Tech Stack

| Category | Tools / Libraries |
|---------------|----------------------|
| Framework | **Apache Spark (PySpark)** |
| Cluster Manager | YARN / Spark Standalone |
| Data Storage | HDFS / JSON / CSV / API Integration |
| Libraries | pyspark.sql, pyspark.streaming, graphframes |
| Language | Python 3 |
| APIs Used | SpaceX Launch API, CryptoCompare Bitcoin API |

---

## 📂 Project Structure

| Project | Description |
|---------------------------------------------------------|-----------------------------------------------------------------------------------|
| [Spark-RDD-LifeExpectancy](./Spark-RDD-LifeExpectancy) | Analyzed Life Expectancy dataset using **RDD transformations** and **actions** to calculate missing values and aggregate mortality rates via `reduceByKey()`. |
| [Spark-RDD-MovieAnalytics](./Spark-RDD-MovieAnalytics) | Implemented **RDD joins** and aggregation logic to compute movie revenues and ratings grouped by production and rating agencies. |
| [Spark-HiveContext-SpaceX](./Spark-HiveContext-SpaceX) | Retrieved **SpaceX API** data, filtered successful launches, and queried results using **HiveContext SQL**. |
| [Spark-HiveContext-BitcoinPrice](./Spark-HiveContext-BitcoinPrice) | Pulled **Bitcoin price data** from CryptoCompare API, transformed JSON, and computed average closing price using Hive SQL. |
| [Spark-Streaming-DeptBudget](./Spark-Streaming-DeptBudget) | Built a **real-time data ingestion pipeline** for department budgets using Spark Structured Streaming. |
| [Spark-GraphFrames-BankNetwork](./Spark-GraphFrames-BankNetwork) | Modeled a **bank relationship graph** of branch heads and customers, applied **PageRank**, and analyzed degrees and triangle counts. |

---

## 🧩 Key Concepts Covered

- **RDD Transformations & Actions**: `map()`, `filter()`, `flatMap()`, `reduceByKey()`, lazy evaluation  
- **DataFrame Operations & SQL**: `groupBy()`, `agg()`, `join()`, `orderBy()`  
- **HiveContext Queries**: Querying semi-structured JSON via SQL syntax  
- **Structured Streaming**: Real-time file ingestion & incremental aggregation  
- **GraphFrames**: Vertex-edge modeling, `inDegrees`, `outDegrees`, `pageRank`, and `triangleCount`

---

## ⚙️ Installation

```
git clone https://github.com/KrystinCWL/Spark-Data-Engineering-Projects.git
cd Spark-Data-Engineering-Projects
pip install -r requirements.txt
```

---

## 🧪 How to Run

Each subproject contains a Jupyter notebook (.ipynb) that can be executed independently.

```
cd Spark-RDD-LifeExpectancy
jupyter notebook RDD_LifeExpectancy.ipynb
```
---

## 📊 Sample Outputs
| Module | Preview |
|---------------|----------------------|
| RDD Aggregation	|----------------------|
| Hive SQL Query	|----------------------|
| Graph Analysis	|----------------------|

---

## 🏁 Summary

This repository demonstrates the practical integration of data engineering, real-time processing, and graph analytics using the PySpark ecosystem — enabling scalable analysis across diverse data types and formats.
