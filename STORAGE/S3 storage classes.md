**Amazon S3 Standard (S3 Standard)**

Key Features:

- Low latency and high throughput performance
- Designed for durability of 99.999999999% of objects across multiple Availability Zones
- Resilient against events that impact an entire Availability Zone
- Designed for 99.99% availability over a given year

**Amazon S3 Intelligent-Tiering (S3 Intelligent-Tiering)**

Key Features:

- Frequent, Infrequent, and Archive Instant Access tiers have the same low-latency and high-throughput performance of S3 Standard
- The Infrequent Access tier saves up to 40% on storage costs
- Deep Archive Access tier has the same performance as Glacier Deep Archive and saves up to 95% for rarely accessed objects
- Designed for durability of 99.999999999% of objects across multiple Availability Zones and for 99.9% availability over a given year

**Amazon S3 Standard-Infrequent Access(S3 Standard-IA)**

Key Features:

- Same low latency and high throughput performance of S3 Standard
- Designed for durability of 99.999999999% of objects across multiple Availability Zones
- Resilient against events that impact an entire Availability Zone
- Data is resilient in the event of one entire Availability Zone destruction
- Designed for 99.9% availability over a given year

**Amazon S3 One Zone-Infrequent Access (S3 One Zone-IA)**

Key Features:

- Same low latency and high throughput performance of S3 Standard
- Designed for durability of 99.999999999% of objects in a single Availability Zone†
- Designed for 99.5% availability over a given year
- Backed with the [Amazon S3 Service Level Agreement](https://aws.amazon.com/s3/sla/) for availability

**Amazon S3 Glacier Instant Retrieval storage class**

Key Features:

- Data retrieval in milliseconds with the same performance as S3 Standard
- Designed for durability of 99.999999999% of objects across multiple Availability Zones
- Data is resilient in the event of the destruction of one entire Availability Zone
- Designed for 99.9% data availability in a given year
- 128 KB minimum object size

**Amazon S3 Glacier Flexible Retrieval (Formerly S3 Glacier) storage class**

Key Features:

- Designed for durability of 99.999999999% of objects across multiple Availability Zones
- Data is resilient in the event of one entire Availability Zone destruction
- Supports SSL for data in transit and encryption of data at rest
- Ideal for backup and disaster recovery use cases when large sets of data occasionally need to be retrieved in minutes, without concern for costs
- Configurable retrieval times, from minutes to hours, with free bulk retrievals

**Amazon S3 Glacier Deep Archive (S3 Glacier Deep Archive)**

Key Features:

- Designed for durability of 99.999999999% of objects across multiple Availability Zones
- Lowest cost storage class designed for long-term retention of data that will be retained for 7-10 years
- Ideal alternative to magnetic tape libraries
- Retrieval time within 12 hours
## Amazon S3 Storage Classes – CLF-C02 Scope 🗂️💰

S3 offers different **storage classes** to optimize **cost based on access frequency**.

Lower cost storage → Higher retrieval time.

---

# 1️⃣ S3 Standard

- For frequently accessed data
    
- Low latency
    
- High durability
    
- Higher storage cost
    

✔ Best for:

- Active websites
    
- Frequently used data
    

---

# 2️⃣ S3 Intelligent-Tiering

- Automatically moves data between tiers
    
- Optimizes cost based on usage
    
- Small monitoring fee
    

✔ Best for:

- Unpredictable access patterns
    

---

# 3️⃣ S3 Standard-Infrequent Access (Standard-IA)

- For rarely accessed data
    
- Lower storage cost
    
- Retrieval fee applies
    

✔ Best for:

- Backups
    
- Disaster recovery
    

---

# 4️⃣ S3 One Zone-IA

- Stored in one Availability Zone
    
- Lower cost than Standard-IA
    
- Less resilient
    

✔ Best for:

- Re-creatable data
    

---

# 5️⃣ S3 Glacier (Archival Storage)

- Very low cost
    
- Designed for long-term archive
    
- Retrieval takes minutes to hours
    

✔ Best for:

- Compliance archives
    
- Old backups
    

---

# Quick Comparison (Exam Friendly)

|Storage Class|Access Frequency|Cost|Retrieval Time|
|---|---|---|---|
|Standard|Frequent|High|Immediate|
|Intelligent-Tiering|Variable|Optimized|Immediate|
|Standard-IA|Infrequent|Lower|Immediate (fee)|
|One Zone-IA|Infrequent|Lower|Immediate (fee)|
|Glacier|Rare|Lowest|Minutes–Hours|

---

## Exam Keywords 🎯

- “Frequently accessed” → Standard
    
- “Unknown access pattern” → Intelligent-Tiering
    
- “Rarely accessed” → Standard-IA
    
- “Long-term archive” → Glacier
    
- “Lowest cost archive” → Glacier
    

---

### For CLF-C02 remember:

> Choose storage class based on access frequency and cost

