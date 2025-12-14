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
| [RDD - Life Expectancy](./Spark%20RDD%20LifeExpectancy/Spark%20RDD%20LifeExpectancy.ipynb) | Analyzed Life Expectancy dataset using **RDD transformations** and **actions** to calculate missing values and aggregate mortality rates via `reduceByKey()`. |
| [SQL - Movie Analytics](./Spark%20SQL%20MovieAnalytics/Spark%20SQL%20MovieAnalytics.ipynb) | Implemented **SQL joins** and aggregation logic to compute movie revenues and ratings grouped by production and rating agencies. |
| [Hive Context - SpaceX](./Spark%20HiveContext%20SpaceX.ipynb) | Retrieved **SpaceX API** data, filtered successful launches, and queried results using **HiveContext SQL**. |
| [Hive Context - Bitcoin Price](./Spark%20HiveContext%20BitcoinPrice) | Pulled **Bitcoin price data** from CryptoCompare API, transformed JSON, and computed average closing price using Hive SQL. |
| [Streaming - Dept Budget](./Spark%20Streaming%20DeptBudget/Spark%20Streaming%20DeptBudget.ipynb) | Built a **real-time data ingestion pipeline** for department budgets using Spark Structured Streaming. |
| [Graph Frames - Bank Network](./Spark%20GraphFrames%20BankNetwork) | Modeled a **bank relationship graph** of branch heads and customers, applied **PageRank**, and analyzed degrees and triangle counts. |

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
git clone https://github.com/KrystinCWL/Spark-Data-Engineering.git
cd Spark-Data-Engineering
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
