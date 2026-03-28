## Availability Zones (AZs) – CLF-C02 Scope 🏢

An **Availability Zone (AZ)** is one or more **physically separate data centers** within an AWS Region.

They are part of the global infrastructure of  
Amazon Web Services.

---

## Key Characteristics

- Each Region has **multiple AZs**
    
- AZs are **isolated from each other**
    
- Connected with **high-speed, low-latency networking**
    
- Designed for **fault tolerance**
    

---

## Why AZs Are Important

If one AZ fails:

- Other AZs continue running
    
- Your application remains available
    

This improves **high availability**.

---

## Example (Exam Concept)

If you deploy:

- EC2 in AZ-A only → Risk of downtime
    
- EC2 in AZ-A and AZ-B → High availability
    

For CLF-C02:  
Deploy across **multiple AZs** for better reliability.

---

## AZ vs Region (Exam Favorite)

|Component|Meaning|
|---|---|
|Region|Geographic area|
|Availability Zone|Data centers inside a Region|

---

## Important Exam Keywords

- “High availability within a Region” → Use multiple AZs
    
- “Disaster recovery across geography” → Use multiple Regions
    

---

### For CLF-C02 remember:

> AZ = Isolated data center inside a Region  
> Multiple AZs = High availability