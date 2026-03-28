## Fault Tolerance – CLF-C02 Scope 🛡️

**Fault Tolerance** means a system continues to operate **without interruption** even if a component fails.

In AWS, fault tolerance is achieved using the global infrastructure of  
Amazon Web Services.

---

## Simple Meaning

If one server fails → System keeps running  
If one data center fails → Application still works

Users should not notice any disruption.

---

## How AWS Achieves Fault Tolerance

### 1️⃣ Multiple Availability Zones

Deploy resources across **multiple AZs**.

If one AZ fails → Other AZ continues serving traffic.

---

### 2️⃣ Elastic Load Balancing

Use:

- Elastic Load Balancing
    

It routes traffic only to healthy instances.

---

### 3️⃣ Auto Scaling

Use:

- Amazon EC2 Auto Scaling
    

Automatically replaces unhealthy instances.

---

### 4️⃣ Multiple Regions (Advanced Level)

Deploy across Regions for protection against regional failures.

---

## Fault Tolerance vs High Availability (Exam Concept)

|Concept|Meaning|
|---|---|
|High Availability|Minimal downtime|
|Fault Tolerance|No interruption during failure|

CLF-C02 does not require deep technical difference — just understand the concept.

---

## Example (Exam Scenario)

If question says:

“Application must continue operating even if one data center fails without any disruption.”

Correct concept:  
Deploy across **multiple Availability Zones** with load balancing.

---

### For CLF-C02 remember:

> Fault Tolerance = System continues working even during failure