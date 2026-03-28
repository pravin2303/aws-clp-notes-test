

## Amazon S3 Glacier – CLF-C02 Scope 🧊📦

**Amazon S3 Glacier** is a **low-cost archival storage** service designed for **long-term data retention**.

It is used for data that is:

- Rarely accessed
    
- Stored for months or years
    
- Needed mainly for compliance or backup
    

---

## Why Use Glacier?

- Very low storage cost 💰
    
- High durability
    
- Ideal for archives
    

---

## Retrieval Time (Important for Exam)

Unlike S3 Standard:

- Data is **not immediately available**
    
- Retrieval can take:
    
    - Minutes
        
    - Hours
        

Lower cost → Longer retrieval time.

---

## Common Use Cases

✔ Compliance archives  
✔ Long-term backups  
✔ Financial records  
✔ Medical records

---

## Glacier vs S3 Standard (Exam Favorite)

|Feature|S3 Standard|S3 Glacier|
|---|---|---|
|Access Frequency|Frequent|Rare|
|Cost|Higher|Very Low|
|Retrieval Time|Immediate|Minutes–Hours|

---

## Works With

- S3 Lifecycle Policies  
    You can automatically move objects to Glacier after a set number of days.
    

---

## Exam Keywords 🎯

- “Long-term archive” → Glacier
    
- “Lowest cost storage” → Glacier
    
- “Rarely accessed data” → Glacier
    
- “Compliance retention” → Glacier
    

---

### For CLF-C02 remember:

> S3 Glacier = Low-cost archival storage with slower retrieval