# RideInsight – Scalable Big Data Analytics Platform

## Overview
RideInsight is a scalable big data analytics platform designed to process and analyze ride-booking data. It leverages modern big data technologies to extract insights on profitability, customer demand, and marketing strategies. The platform is built using Hadoop, Spark, Hive, and Power BI to ensure efficient data processing and visualization.

## Features
- **Big Data Infrastructure on Docker**: Deploys a scalable Hadoop ecosystem with Spark and Hive.
- **ETL Pipeline with Spark**: Extracts ride-booking data from an API, transforms it, and loads it into a Hive-based data warehouse.
- **Data Analysis & Visualization**: Uses Power BI to analyze and visualize trends for business decision-making.

## Tech Stack
- **Big Data Frameworks**: Apache Hadoop (HDFS, YARN), Apache Spark, Apache Hive
- **Containerization & Orchestration**: Docker
- **Visualization**: Power BI (JDBC connection)
- **Programming Languages**: Python, SQL

## Architecture
The system processes ride-booking data through the following workflow:
1. **Data Ingestion**: Extract data from an API and store it in HDFS.
2. **Data Processing**: Use Spark for transformation and aggregation.
3. **Data Storage**: Store processed data in Hive (Data Warehouse).
4. **Data Visualization**: Connect Power BI via JDBC to analyze and visualize insights.

## Setup & Installation
### Prerequisites
- Docker installed on your system
- Python 3.x and necessary dependencies
- Power BI for visualization

### Steps to Run the Platform
1. Clone the repository:
   ```sh
   git clone https://github.com/ngocvien21/RideInsight-Scalable-Big-Data-Analytics-Platform.git
   cd RideInsight
   ```
2. Start the Docker containers:
   ```sh
   docker-compose up -d
   ```
3. Connect Power BI to Hive using JDBC for visualization.

## Usage
- Run the Spark ETL job to process ride-booking data.
- Query transformed data in Hive for analysis.
- Use Power BI dashboards to visualize trends and insights.

## Results & Insights
- Identify high-demand ride-booking locations to optimize marketing strategies.
- Analyze profitability trends across different regions.
- Provide data-driven recommendations to improve business decisions.

## Future Improvements
- Implement real-time data streaming using Apache Kafka.
- Optimize Spark jobs for improved processing efficiency.
- Expand analytics features with advanced machine learning models.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

## Contact
For questions or collaboration, reach out via:
- GitHub: [ngocvien21](https://github.com/ngocvien21)
- LinkedIn: [Truong Thi Ngoc Vien](https://www.linkedin.com/in/ngocvien21/)

