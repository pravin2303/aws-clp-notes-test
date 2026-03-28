## Amazon Aurora – CLF-C02 Scope 🚀🗄️

**Amazon Aurora** is a **fully managed relational database engine** that is compatible with **MySQL and PostgreSQL**.

It is part of  
Amazon Relational Database Service (RDS).

---

## What Makes Aurora Different?

- Higher performance than standard MySQL/PostgreSQL
    
- Fully managed by AWS
    
- High availability
    
- Automatic backups
    

---

## Key Characteristics (Exam Focus)

- Relational database
    
- Compatible with MySQL & PostgreSQL
    
- Up to 5x faster than standard MySQL (exam-level concept)
    
- Automatically replicates data across multiple AZs
    

---

## High Availability

Aurora automatically:

- Replicates data across multiple Availability Zones
    
- Provides failover capability
    

This improves fault tolerance.

---

## When to Use Aurora

✔ High-performance applications  
✔ Enterprise workloads  
✔ Applications needing high availability

---

## Aurora vs RDS (Standard Engines) – Exam Concept

|Feature|RDS (MySQL, etc.)|Aurora|
|---|---|---|
|Performance|Standard|Higher|
|Compatibility|Native engine|MySQL/PostgreSQL compatible|
|Management|Managed|Managed|
|Cost|Lower|Higher|

---

## Simple Example

E-commerce site with heavy traffic:

Aurora handles high transaction volume better than standard MySQL.

---

### For CLF-C02 remember:

> Aurora = High-performance managed relational database compatible with MySQL/PostgreSQL