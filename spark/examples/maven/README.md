# Apache Spark demo example (Maven)
This is a starter app for the Apache Spark Maven template.

## Running the application on a Spark standalone cluster via Docker

To run the application, execute the following steps:

1. Setup a Spark cluster as described on https://github.com/ngocvien21/RideInsight-Scalable-Big-Data-Analytics-Platform.git by just running: 
    ```bash
    git https://github.com/ngocvien21/RideInsight-Scalable-Big-Data-Analytics-Platform.git
    cd docker-spark
    docker-compose up -d
    ```
2. Build the Docker image:
    ```bash
    bash build.sh maven-example examples/maven
    ```
3. Run the Docker container:
    ```bash
    docker run --rm --network dockerspark_default --name spark-maven-example bde2020/spark-maven-example:3.3.0-hadoop3.3
    ```
