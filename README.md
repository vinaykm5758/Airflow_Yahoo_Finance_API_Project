# Airflow_Yahoo_Finance_API_Project
This Repo contains details about Extracting Yahoo Finance API using Apache Airflow, Thanks

**End to End Data Flow Diagram:**

![image](https://github.com/user-attachments/assets/aae96315-e56d-4e23-bf3a-a1baf14d386b)

**Project Description:**
1. This Project involved extracting stock prices from Yahoo Finance website using an API URL: https://query1.finance.yahoo.com//v8/finance/chart/.
2. API data is processed using Python and stored in Minio, Postgres DB and Reporting/Dashboarding is performed using Metabase
3. Notifications are performed using Slack for both Success and Failure operations

**Technology Stack:**
1. Apache Airflow installed on Docker
2. MinIO (S3 Like Object Storage)
3. Postgres Database
4. Pyspark
5. Metabase for Reporting
6. Slack for Notifications

**Programming Languages:**
1. Python
2. Pyspark
3. SQL

**Code Files:**
1. stock_market DAG: 
2. stock_market Tasks: 

**Metabase Dashboard:**



**Data Validations**
1. Record Counts from the processed CSV file are compared in the Postgres Table and in Metabase Dashboard and counts matched
   

