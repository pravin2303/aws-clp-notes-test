## Cross-Region Replication (CRR) – CLF-C02 Scope 🌍🔁

**Cross-Region Replication (CRR)** is an Amazon S3 feature that automatically copies objects from one S3 bucket to another bucket in a different AWS Region.

---

## Why Use Cross-Region Replication?

✔ Disaster recovery  
✔ Compliance requirements  
✔ Data residency  
✔ Lower latency for global users

---

## How It Works (Simple Concept)

1️⃣ Upload object to source bucket (Region A)  
2️⃣ S3 automatically copies it to destination bucket (Region B)  
3️⃣ Both buckets stay synchronized

Replication happens automatically after setup.

---

## Important Requirements (Exam Level)

- Versioning must be enabled on both buckets
    
- Buckets must be in different Regions
    

---

## Example

Company stores data in Mumbai Region.

For disaster recovery, they replicate data to Singapore Region.

If Mumbai Region fails → Data still available in Singapore.

---

## CRR vs Same-Region Replication (Exam Concept)

|Feature|CRR|Same-Region Replication|
|---|---|---|
|Region|Different Regions|Same Region|
|Purpose|Disaster recovery|Compliance / data separation|

---

## Exam Keywords 🎯

- “Disaster recovery across Regions” → CRR
    
- “Replicate data to another Region” → CRR
    
- “Improve global access” → CRR
    

---

### For CLF-C02 remember:

> Cross-Region Replication = Automatic S3 replication to another Region