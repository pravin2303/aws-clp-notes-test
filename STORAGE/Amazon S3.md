## Amazon S3 – CLF-C02 Scope 🗄️☁️

**Amazon S3 (Simple Storage Service)** is an **object storage service** used to store and retrieve any amount of data from anywhere.

---

## What S3 Stores

- Images
    
- Videos
    
- Documents
    
- Backups
    
- Application data
    
- Logs
    

---

## Key Characteristics (Very Important for Exam)

- Object storage (not block storage)
    
- Highly durable (11 9’s durability)
    
- Scalable
    
- Data stored in **buckets**
    
- Regional service
    

---

## Basic Terms

### Bucket

A container for storing objects.

### Object

A file stored in S3 (data + metadata).

---

## Why Use S3?

- Backup and restore
    
- Static website hosting
    
- Data storage for applications
    
- Disaster recovery
    

---

## Storage Classes (Basic Awareness for CLF)

S3 offers different storage classes for cost optimization:

- S3 Standard
    
- S3 Intelligent-Tiering
    
- S3 Standard-IA
    
- S3 Glacier
    

Lower cost → Higher retrieval time.

---

## S3 vs EBS (Exam Favorite)

|Feature|S3|EBS|
|---|---|---|
|Storage Type|Object|Block|
|Used With|Web, backups|EC2|
|Scope|Regional|Single AZ|

---

## Security Features

- Bucket policies
    
- IAM policies
    
- Encryption
    

---

## Example

Upload images to S3 → Website retrieves them from S3.

---

### For CLF-C02 remember:

> S3 = Scalable, durable object storage