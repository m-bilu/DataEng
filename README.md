#### Data Engineering End-to-End Project

In this project, we simulate a realtime streaming pipeline from start to finish

- We use Random Name API to get simulated user data in a streaming fashion.
- Write this to a Apache Kafka topic, writing will be controlled by python scripts operated by Apache Airflow DAG 
    - (Puckels Docker-Airflow Github repo)
- Organize stream with Spark Structured Scripting, save into Cassandra NoSQL database.
- All components containerized with Docker.

