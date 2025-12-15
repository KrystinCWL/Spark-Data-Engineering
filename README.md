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

- SpaceX Launch Data API: https://api.spacexdata.com/v5/launches  
- CryptoCompare Bitcoin Data API: https://data-api.cryptocompare.com/index/cc/v1/historical/days?market=cadli&instrument=BTC-USD&limit=365&aggregate=1&fill=true&apply_mapping=true&response_format=JSON

---

## 📂 Project Structure

| Project | Description |
|---------------------------------------------------------|-----------------------------------------------------------------------------------|
| [RDD - Life Expectancy](./Spark%20RDD%20LifeExpectancy/Spark%20RDD%20LifeExpectancy.ipynb) | Analyzed Life Expectancy dataset using **RDD transformations** and **actions** to calculate missing values and aggregate mortality rates via `reduceByKey()`. |
| [SQL - Movie Analytics](./Spark%20SQL%20MovieAnalytics/Spark%20SQL%20MovieAnalytics.ipynb) | Implemented **SQL joins** and aggregation logic to compute movie revenues and ratings grouped by production and rating agencies. |
| [Hive Context - SpaceX](./Spark%20Hive%20Context/Spark%20HiveContext%20SpaceX.ipynb) | Retrieved **SpaceX API** data, filtered successful launches, and queried results using **HiveContext SQL**. |
| [Hive Context - Bitcoin Price](./Spark%20Hive%20Context//Spark%20HiveContext%20Bitcoin.ipynb) | Pulled **Bitcoin price data** from CryptoCompare API, transformed JSON, and computed average closing price using Hive SQL.|
| [Streaming - Dept Budget](./Spark%20Streaming%20DeptBudget/Spark%20Streaming%20DeptBudget.ipynb) | Built a **real-time data ingestion pipeline** for department budgets using Spark Structured Streaming. |
| [GraphFrames - Bank Network](./Spark%20GraphFrames%20BankNetwork) | Modeled a **bank relationship graph** of branch heads and customers, applied **PageRank**, and analyzed degrees and triangle counts. |

---

## 🧩 Key Concepts Covered

- **RDD Transformations & Actions**: `map()`, `filter()`, `flatMap()`, `reduceByKey()`, lazy evaluation  
- **DataFrame Operations & SQL**: `groupBy()`, `agg()`, `join()`, `orderBy()`  
- **HiveContext Queries**: Querying semi-structured JSON via SQL syntax  
- **Structured Streaming**: Real-time file ingestion & incremental aggregation  
- **GraphFrames**: Vertex-edge modeling, `inDegrees`, `outDegrees`, `pageRank`, and `triangleCount`

---

## ⚙️ Installation

To run the notebooks, you need to set up the environment by cloning the repository and installing the necessary dependencies.

1. **Clone the repository**
   ```
   git clone https://github.com/KrystinCWL/Spark-Data-Engineering.git
   cd Spark-Data-Engineering
   ```
2. **Install dependencies**
   ```
   pip install -r requirements.txt
   ```

---

## 🧪 How to Run

This repository is organized into distinct subprojects, each focusing on a specific Apache Spark module (RDD, SQL, Hive, Streaming, GraphFrames). Ensure you have the following installed:
* **Python 3.x**
* **Apache Spark**
* **Jupyter Notebook**

Each project is self-contained. Navigate to the specific directory and launch the Jupyter Notebook as shown below.

1. **RDD Life Expectancy:** Performs data analysis using low-level RDD transformations.
```
cd "Spark RDD LifeExpectancy"
jupyter notebook "Spark RDD LifeExpectancy.ipynb"
```

2. **SQL Movie Analytics:** Uses Spark SQL for querying movie datasets.
```
cd "Spark SQL MovieAnalytics"
jupyter notebook "Spark SQL MovieAnalytics.ipynb"
```

3. **Hive Context (Bitcoin & SpaceX):** Demonstrates Spark Hive Context usage with two different datasets.
```
cd "Spark Hive Context"

# Run Bitcoin analysis:
jupyter notebook "Spark HiveContext Bitcoin.ipynb"

# OR Run SpaceX analysis:
jupyter notebook "Spark HiveContext SpaceX.ipynb"
```

4. **Spark Streaming DeptBudget:** Processes streaming data from the DeptDir directory.
```
cd "Spark Streaming DeptBudget"
jupyter notebook "Spark Streaming DeptBudget.ipynb"
```

5. **GraphFrames Bank Network:** Analyzes transaction networks using graph algorithms.
```
cd "Spark GraphFrames BankNetwork"
jupyter notebook "Spark GraphFrames BankNetwork.ipynb"
```

Note: Since the directory names contain spaces, please ensure you include the quotation marks "" when running the cd commands in your terminal.

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
