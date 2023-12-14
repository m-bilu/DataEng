#### Data Engineering End-to-End Project

In this project, we simulate a realtime streaming pipeline from start to finish

- We use Random Name API to get simulated data in a streaming fashion.
- Write this to a Apache Kafka topic, writing will be controlled by Apache Airflow DAG (Puckels Docker-Airflow Github repo)
- Acquire data using Spark, save into Cassandra NoSQL database.
- Run app in Docker container

