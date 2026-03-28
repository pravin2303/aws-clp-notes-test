## Scalability – CLF-C02 Scope 📈

**Scalability** means the ability of a system to **increase or decrease resources** based on demand.

In AWS, scalability ensures your application can handle:

- Increased traffic
    
- Decreased traffic
    
- Sudden workload changes
    

---

## Types of Scalability (Exam Level)

### 1️⃣ Vertical Scaling (Scale Up ⬆️)

Increase the power of a single instance.

Example:

- Upgrade EC2 from small → large (more CPU & RAM)
    

✔ Simple but limited.

---

### 2️⃣ Horizontal Scaling (Scale Out ➡️)

Add more instances to handle load.

Example:

- 1 EC2 → 3 EC2 instances
    
- Use Load Balancer to distribute traffic
    

✔ Most common in cloud  
✔ Recommended in AWS

---

## Which AWS Services Help?

- Amazon EC2 Auto Scaling
    
- Elastic Load Balancing
    

Auto Scaling adds/removes instances automatically.  
Load Balancer distributes traffic.

---

## Example (Exam Scenario)

If traffic increases during sale season:

Auto Scaling launches more EC2 instances.  
When traffic drops → It removes extra instances.

---

## Scalability vs High Availability (Exam Favorite)

|Concept|Purpose|
|---|---|
|High Availability|Prevent downtime|
|Scalability|Handle workload growth|

---

## Key Exam Keywords

- “Handle increased demand”
    
- “Automatically adjust capacity”
    
- “Add or remove resources”
    

---

### For CLF-C02 remember:

> Scalability = Adjust resources based on demand