## Amazon S3 Lifecycle Policies – CLF-C02 Scope 🔄💰

**S3 Lifecycle Policies** automatically move or delete objects based on rules you define.

They help in **cost optimization** and storage management.

---

## What Lifecycle Policies Can Do

### 1️⃣ Transition Objects Between Storage Classes

Automatically move data to lower-cost storage.

Example:

- After 30 days → Move from S3 Standard to Standard-IA
    
- After 90 days → Move to Glacier
    

---

### 2️⃣ Expire (Delete) Objects Automatically

Delete objects after a certain number of days.

Example:

- Delete logs after 365 days
    

---

## Why It Is Important

- Reduces storage cost
    
- Automates storage management
    
- Useful for backups and archives
    

---

## Example (Exam Scenario)

Company stores application logs.

- Frequently accessed for 30 days
    
- Rarely accessed afterward
    

Solution:  
Use Lifecycle Policy to move logs to Standard-IA or Glacier after 30 days.

---

## Works Well With

- S3 Versioning (manage older versions)
    
- S3 Glacier (long-term archive)
    

---

## Key Exam Points

- Automated transition or deletion
    
- Used for cost optimization
    
- Defined at bucket level
    

---

## Easy Way to Remember

> Lifecycle = Automatically move or delete old data

---

### For CLF-C02 remember:

If question says:

- “Reduce storage cost automatically” → Lifecycle Policy
    
- “Move data to Glacier after 90 days” → Lifecycle rule