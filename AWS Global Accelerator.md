## 🌍⚡ AWS Global Accelerator – CLF-C02 Scope

**AWS Global Accelerator** is a networking service that **improves the availability and performance of applications for global users**.

It routes user traffic through the **AWS global network** to the nearest healthy endpoint.

---

# 🎯 What Global Accelerator Does

✔ Improves application performance  
✔ Provides static IP addresses  
✔ Routes traffic through AWS global network  
✔ Automatically directs traffic to the nearest healthy endpoint

---

# How It Works (Simple Concept)

1️⃣ User sends request  
2️⃣ Traffic enters AWS global network  
3️⃣ Routed to the nearest healthy AWS endpoint

Endpoints can be:

- EC2 instances
    
- Elastic Load Balancers
    
- Other AWS resources
    

---

# Example

If users from different countries access your application:

Global Accelerator ensures traffic goes through the **fastest AWS network path**.

---

# Global Accelerator vs CloudFront (Exam Concept)

|Feature|Global Accelerator|CloudFront|
|---|---|---|
|Type|Network layer accelerator|CDN|
|Improves|Application availability & performance|Content delivery|
|Uses|AWS global network routing|Edge caching|

👉 “Improve network performance globally” → Global Accelerator  
👉 “Cache content near users” → CloudFront

---

# 🎯 Exam Keywords

- “Static IP for global application” → Global Accelerator
    
- “Improve availability for global users” → Global Accelerator
    
- “Route traffic through AWS global network” → Global Accelerator
    

---

## One-Line Memory

> Global Accelerator = Faster global application routing