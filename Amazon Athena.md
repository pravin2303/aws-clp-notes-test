## 🧮 Amazon Athena – CLF-C02 Scope

**Amazon Athena** is a **serverless query service** that allows you to **analyze data stored in Amazon S3 using SQL**.

You do not need to manage any servers.

---

# 🎯 What Athena Does

✔ Query data directly from Amazon S3  
✔ Uses standard **SQL queries**  
✔ Serverless (no infrastructure to manage)  
✔ Pay only for the data scanned

---

# How It Works (Simple Concept)

1️⃣ Store data in  
Amazon S3

2️⃣ Run SQL query using Athena

3️⃣ Athena processes the query and returns results

---

# Example

A company stores **website logs in S3**.

They want to analyze logs using SQL → Use **Athena**.

---

# Athena vs Redshift (Exam Concept)

|Service|Purpose|
|---|---|
|Athena|Query data in S3 using SQL|
|Redshift|Data warehouse for large-scale analytics|

👉 “Run SQL queries on S3 data” → Athena  
👉 “Petabyte-scale data warehouse” → Redshift

---

# 🎯 Exam Keywords

- “Query S3 data with SQL” → Athena
    
- “Serverless data analytics” → Athena
    
- “Analyze logs stored in S3” → Athena
    

---

## One-Line Memory

> Athena = Serverless SQL queries for data in S3