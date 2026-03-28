## Amazon Relational Database Service (RDS) – CLF-C02 Scope 🗄️☁️

**Amazon RDS** is a **managed relational database service** in AWS.

It makes it easy to **set up, operate, and scale a relational database** in the cloud.

---

## What RDS Does

AWS manages:

- Hardware provisioning
    
- Database installation
    
- Backups
    
- Patching
    
- Monitoring
    

You focus on:

- Database usage
    
- Application data
    

---

## Supported Database Engines (High-Level)

- MySQL
    
- PostgreSQL
    
- MariaDB
    
- Oracle
    
- Microsoft SQL Server
    

(No deep technical details needed for CLF-C02.)

---

## Key Features (Exam Focus)

### 1️⃣ Automated Backups

RDS automatically backs up your database.

### 2️⃣ Multi-AZ Deployment

Improves high availability.

### 3️⃣ Read Replicas

Improves read performance.

### 4️⃣ Scalability

You can scale storage and compute.

---

## Example

If you build an e-commerce website:

- EC2 runs application
    
- RDS stores customer and order data
    

---

## RDS vs EC2 Database (Exam Favorite)

|Feature|RDS|Database on EC2|
|---|---|---|
|Management|Fully managed|Manual management|
|Backups|Automatic|Manual setup|
|Patching|Automatic|Manual|

---

## When to Use RDS

✔ Relational databases  
✔ Structured data  
✔ Applications requiring SQL

---

### For CLF-C02 remember:

> RDS = Managed relational database service