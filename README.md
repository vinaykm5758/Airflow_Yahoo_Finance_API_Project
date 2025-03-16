# Airflow_Yahoo_Finance_API_Project
This Repo contains details about Extracting Yahoo Finance API using Apache Airflow, Thanks

**End to End Data Flow Diagram:**

![image](https://github.com/user-attachments/assets/aae96315-e56d-4e23-bf3a-a1baf14d386b)

**Project Description:**
1. This Project involved extracting stock prices from Yahoo Finance website using an API URL: https://query1.finance.yahoo.com//v8/finance/chart/ leveraging Python programming language
2. API data is processed using Python and stored in Minio.
3. Using Pyspark, Raw JSON data has been transformed into CSV file format and loaded into Minio and Postgres DB
4. Connected Metabase to Postgres Database tables and created/deployed stock_market Dashboard
5. End to End DAG has been deployed using ASTRO CLI and end to end data validations are performed
6. Notifications are performed using Slack for both Success and Failure operations

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
1. stock_market DAG: https://github.com/vinaykm5758/Airflow_Yahoo_Finance_API_Project/blob/main/stock_market.py
2. stock_market Tasks: https://github.com/vinaykm5758/Airflow_Yahoo_Finance_API_Project/blob/main/tasks.py

**Final Airflow DAG Structure:**

![image](https://github.com/user-attachments/assets/305c1864-3db0-4f40-9040-3b3646892407)

**Minio Object Storage:**

![image](https://github.com/user-attachments/assets/d6d61920-0fc7-478b-bbff-7d5c38bcf123)


**Slack Success Notification:**

![image](https://github.com/user-attachments/assets/80f5847e-d519-4f96-969e-cf4981e7c6d3)


**Metabase Dashboard:**
1. https://github.com/vinaykm5758/Airflow_Yahoo_Finance_API_Project/blob/main/Metabase_Stock_Market_Dashboard.pdf

![image](https://github.com/user-attachments/assets/1e9110ed-8098-4932-8554-330cd7370474)



**Data Validations**
1. Record Counts from the processed CSV file are compared in the Postgres Table and in Metabase Dashboard and counts matched. URL: https://github.com/vinaykm5758/Airflow_Yahoo_Finance_API_Project/blob/main/Postgres_Table_Counts_Validations.PNG

![image](https://github.com/user-attachments/assets/d81529e2-db79-4256-8df2-d10c98bb876b)


