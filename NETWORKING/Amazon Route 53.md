## Amazon Route 53 – CLF-C02 Scope 🌍🌐

**Amazon Route 53** is a **highly available and scalable Domain Name System (DNS)** web service.

It translates **domain names** (like www.example.com) into IP addresses.

---

## What Route 53 Does

When a user types a website name:

1️⃣ Route 53 receives the DNS request  
2️⃣ It finds the correct IP address  
3️⃣ Routes the user to the correct AWS resource

Such as:

- EC2
    
- Elastic Load Balancer
    
- S3
    
- CloudFront
    

---

## Why It Is Called “53”

DNS uses **Port 53**.

---

## Main Functions (CLF-C02 Level)

### 1️⃣ Domain Registration

You can register domain names.

### 2️⃣ DNS Routing

Maps domain names to AWS resources.

### 3️⃣ Health Checks

Checks resource health and routes traffic only to healthy endpoints.

---

## Routing Policies (Basic Awareness)

- Simple routing
    
- Weighted routing
    
- Latency-based routing
    
- Failover routing
    

No deep details required at CLF level.

---

## Example

User in India types your website:

Route 53 directs traffic to nearest healthy resource.

---

## Key Exam Points 🎯

- It is a DNS service
    
- Highly available
    
- Supports health checks
    
- Routes traffic globally
    

---

### For CLF-C02 remember:

> Route 53 = DNS service that routes traffic to AWS resources