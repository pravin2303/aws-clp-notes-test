## AWS Global Infrastructure – CLF-C02 Scope 🌍

The **AWS Global Infrastructure** is the worldwide network of data centers managed by  
Amazon Web Services.

It is designed for:

- High availability
    
- Fault tolerance
    
- Low latency
    
- Global scalability
    

---

# 🌎 1️⃣ Regions

A **Region** is a geographical area where AWS has data centers.

Example:

- Mumbai
    
- Singapore
    
- US East
    

Each region is completely independent.

✔ Used for:

- Compliance
    
- Disaster recovery
    
- Data residency
    

---

# 🏢 2️⃣ Availability Zones (AZs)

Each Region contains multiple **Availability Zones**.

An AZ is:

- One or more data centers
    
- Physically separate
    
- Connected with high-speed networking
    

✔ Used for:

- High availability
    
- Fault tolerance
    

Exam concept:  
Deploy across multiple AZs → Higher availability.

---

# 🌐 3️⃣ Edge Locations

Edge locations are used by:

- Amazon CloudFront
    

They cache content closer to users to reduce latency.

✔ Used for:

- Faster content delivery
    

---

# 🧠 Simple Structure

Region  
↳ Multiple Availability Zones  
↳ Many data centers

Edge Locations are separate and distributed globally.

---

# Quick Exam Summary Table

|Component|Purpose|
|---|---|
|Region|Geographic area|
|Availability Zone|High availability inside region|
|Edge Location|Low latency content delivery|

---

## Exam Keywords

- “High availability” → Multiple AZs
    
- “Disaster recovery across geography” → Multiple Regions
    
- “Low latency globally” → Edge locations
    

---

For CLF-C02 remember:

> Region = Geographic  
> AZ = High availability  
> Edge = Low latency