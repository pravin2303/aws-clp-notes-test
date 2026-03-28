## Read Replica – CLF-C02 Scope 📖🔄

A **Read Replica** is a **read-only copy of a database** used to improve **read performance**.

It is commonly used with  
Amazon Relational Database Service.

---

## Why Use Read Replicas?

If your application has:

- Heavy read traffic
    
- Many users viewing data
    

A single database may become overloaded.

Solution:  
Create **Read Replicas** to distribute read requests.

---

## How It Works (Simple Concept)

1️⃣ Primary database handles:

- All write operations
    

2️⃣ Read Replica handles:

- Read-only queries
    

This improves performance.

---

## Key Characteristics (Exam Focus)

- Used to scale read traffic
    
- Read-only
    
- Asynchronous replication
    
- Can be in same Region or different Region
    

---

## Example

E-commerce website:

- Primary DB → Process orders (writes)
    
- Read Replica → Display product listings (reads)
    

---

## Read Replica vs Multi-AZ (Exam Favorite)

|Feature|Read Replica|Multi-AZ|
|---|---|---|
|Purpose|Improve read performance|High availability|
|Read/Write|Read-only|Standby (not for reads)|
|Failover|Manual|Automatic|

---

## Exam Keywords 🎯

- “Improve read performance” → Read Replica
    
- “Scale read traffic” → Read Replica
    
- “High availability” → Multi-AZ
    

---

### For CLF-C02 remember:

> Read Replica = Scale read traffic  
> Multi-AZ = Improve availability