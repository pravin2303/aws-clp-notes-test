## Amazon Elastic Block Store (EBS) – CLF-C02 Scope 💾🖥️

**Amazon EBS (Elastic Block Store)** provides **block-level storage** for use with  
Amazon EC2.

Think of it as a **virtual hard disk** attached to an EC2 instance.

---

## What EBS Is Used For

- Operating system storage
    
- Application data
    
- Databases running on EC2
    
- Persistent storage
    

---

## Key Characteristics (Exam Focus)

- Block storage
    
- Attached to one EC2 instance at a time
    
- Exists in a single Availability Zone
    
- Data persists when instance is stopped
    

---

## Example

You launch an EC2 instance:

- The OS runs on an EBS volume
    
- If you stop the instance → Data remains
    
- If you terminate (default settings) → Volume may be deleted
    

---

## EBS Snapshots (Important Concept)

You can create **snapshots** (backups) of EBS volumes.

- Stored in S3
    
- Used for backup and disaster recovery
    

---

## EBS vs S3 (Exam Favorite)

|Feature|EBS|S3|
|---|---|---|
|Storage Type|Block|Object|
|Used With|EC2|Web storage, backup|
|Scope|Single AZ|Regional|
|Access|Attached to instance|Access via internet/API|

---

## When to Use EBS

✔ Applications requiring low-latency storage  
✔ Databases on EC2  
✔ Boot volumes

---

### For CLF-C02 remember:

> EBS = Persistent block storage for EC2