# Spark Streaming with Kafka and Cassandra

## Description
This project implements a real-time data streaming pipeline using **Apache Spark**, **Apache Kafka**, and **Apache Cassandra**. The pipeline consumes messages from a Kafka topic, processes them using Spark, and inserts the transformed data into a Cassandra database.

---

## Key Features
- Connects to Kafka to consume real-time data streams.
- Transforms and processes data using **Apache Spark**.
- Stores processed data into a **Cassandra** database.
- Manages Cassandra keyspaces and tables.
- Utilizes Spark for distributed and scalable data processing.

---

## Prerequisites
1. **Required Software**:
   - Python 3.8 or higher.
   - Apache Spark.
   - Apache Kafka.
   - Cassandra.

2. **Python Dependencies**:
   Install dependencies from `requirements.txt`:
   ```bash
   pip install -r requirements.txt
