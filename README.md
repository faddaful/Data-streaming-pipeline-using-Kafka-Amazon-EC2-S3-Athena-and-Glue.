# Data-streaming-pipeline-using-Kafka-Amazon-EC2-S3-Athena-and-Glue.

## Introduction

Welcome to the Stock Market Kafka Real-Time Data Engineering Project! In this project, I created an end-to-end data engineering project focused on real-time stock market data analysis using Apache Kafka.

## Project Scope

My primary objective is to establish a robust data pipeline capable of seamlessly ingesting, processing, and analyzing real-time stock market data. I leveraged a suite of cutting-edge technologies, including Python, Amazon Web Services (AWS), Apache Kafka, Glue, Athena, and SQL.

## Architecture

The project architecture was designed to ensure the smooth flow of data from source to analysis. Here's an overview:

1. **Data Ingestion:** Real-time stock market data was ingested via the Apache Kafka streaming platform. Kafka will act as the central hub for data streaming and distribution.

2. **Data Processing:** Amazon EC2 instances handled data processing tasks. I used Python for data transformations and enrichments, ensuring data is in the desired format for analysis.

3. **Data Storage:** Processed data was stored in Amazon S3 (Simple Storage Service). S3 provides scalable and reliable storage, allowing easy accessibility for further analysis.

4. **Data Cataloging:** AWS Glue came into play for cataloging the data. Glue Crawler automatically discover the schema and create a Glue Catalog, enhancing data discoverability.

5. **Data Analysis:** Amazon Athena, a serverless query service, enabled SQL-based analysis on the stored data. Meaningful insights can be derived without the need for complex setup.

## Technology Utilized

- **Programming Language:** Python drived data transformations and processing.
- **Amazon Web Services (AWS):** Our cloud infrastructure and services was hosted on AWS.
- **S3 (Simple Storage Service):** Storage solution for processed data, scalable and secure.
- **Athena:** Serverless query service for ad-hoc data analysis using SQL.
- **Glue Crawler:** Automatically discovers and catalogs data using AWS Glue.
- **Glue Catalog:** Central repository for metadata management.
- **EC2:** Amazon Elastic Compute Cloud instances for data processing.
- **Apache Kafka:** Streaming platform for data ingestion and distribution.

## Conclusion

This a robust real-time data engineering solution for stock market analysis. I was able harness the power of cutting-edge technologies to build a scalable, reliable, and insightful pipeline that contributes to informed decision-making in the dynamic world of financ! Leave me a comment if you have questions or how I can improve on this.
