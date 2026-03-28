## Disaster Recovery (DR) Basics – CLF-C02 Scope 🌍🔄

**Disaster Recovery (DR)** is the process of restoring applications and data after a major failure, such as:

- Natural disaster
    
- Regional outage
    
- Data center failure
    

In AWS, DR is built using the global infrastructure of  
Amazon Web Services.

---

## Key Goal of Disaster Recovery

- Minimize downtime
    
- Minimize data loss
    
- Restore services quickly
    

---

# Basic DR Strategies (CLF-C02 Level)

You only need high-level understanding of these:

---

## 1️⃣ Backup and Restore 💾

- Regularly back up data (e.g., S3, EBS snapshots)
    
- Restore in another Region when disaster occurs
    

✔ Lowest cost  
❌ Longer recovery time

---

## 2️⃣ Pilot Light 🔥

- Keep core components running in another Region
    
- Scale up when disaster happens
    

✔ Faster than backup-only  
✔ Moderate cost

---

## 3️⃣ Warm Standby 🌤️

- A scaled-down version of full system runs in another Region
    
- Quickly scale to full capacity if needed
    

✔ Faster recovery  
✔ Higher cost

---

## 4️⃣ Multi-Site (Active-Active) 🌐

- Full system running in multiple Regions
    
- Traffic distributed across Regions
    

✔ Fastest recovery  
✔ Highest cost

---

# Important Exam Concepts

- Use **Multiple Regions** for disaster recovery
    
- Use backups like EBS snapshots
    
- Understand cost vs recovery speed trade-off
    

---

# Key Terms (CLF-C02)

- RTO (Recovery Time Objective) → How quickly you recover
    
- RPO (Recovery Point Objective) → How much data loss is acceptable
    

No deep calculation required — just concept.

---

### Quick Exam Summary

|Strategy|Cost|Recovery Speed|
|---|---|---|
|Backup & Restore|Low|Slow|
|Pilot Light|Medium|Faster|
|Warm Standby|Higher|Fast|
|Multi-Site|Highest|Fastest|

---

For CLF-C02 remember:

> Disaster Recovery = Use backups + Multiple Regions