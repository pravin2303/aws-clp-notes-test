## Amazon Elastic File System (EFS) – CLF-C02 Scope 📁☁️

**Amazon EFS (Elastic File System)** is a **fully managed file storage service** for use with  
Amazon EC2.

It provides **shared file storage** that multiple EC2 instances can access at the same time.

---

## What Type of Storage?

- File storage (like a shared network drive)
    
- Uses standard file system protocols
    
- Scales automatically
    

---

## Key Characteristics (Exam Focus)

- Fully managed
    
- Scales automatically
    
- Can be accessed by multiple EC2 instances
    
- Regional service (supports multiple AZs)
    

---

## Simple Example

You have 3 EC2 instances running a web app.

They all need access to the same files (images, shared data).

Solution:  
Use EFS → All instances access the same shared file system.

---

## EFS vs EBS (Exam Favorite)

|Feature|EBS|EFS|
|---|---|---|
|Storage Type|Block|File|
|Multi-instance Access|No (1 instance)|Yes|
|Scope|Single AZ|Multi-AZ|
|Use Case|OS, database|Shared storage|

---

## When to Use EFS

✔ Shared application data  
✔ Content management systems  
✔ Big data workloads  
✔ Multiple EC2 instances needing shared storage

---

### For CLF-C02 remember:

> EFS = Scalable shared file storage for EC2