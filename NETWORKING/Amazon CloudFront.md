## Amazon CloudFront – CLF-C02 Scope 🌍⚡

**Amazon CloudFront** is a **Content Delivery Network (CDN)** service that delivers content to users with **low latency and high speed**.

It is provided by  
Amazon Web Services.

---

## What CloudFront Does

- Caches content at **edge locations** worldwide
    
- Delivers content from the **closest location to the user**
    
- Reduces load on the origin server
    

---

## How It Works (Simple Concept)

1️⃣ User requests a file (image, video, website)  
2️⃣ CloudFront checks nearest edge location  
3️⃣ If cached → Delivered immediately  
4️⃣ If not cached → Fetches from origin (S3, EC2, ELB) and stores it

---

## What Can Be an Origin?

- Amazon S3
    
- EC2
    
- Elastic Load Balancer
    
- Custom web servers
    

---

## Why Use CloudFront?

✔ Faster global content delivery  
✔ Reduced latency  
✔ Improved user experience  
✔ Works with AWS Shield for DDoS protection

---

## CloudFront vs S3 (Exam Concept)

|Feature|CloudFront|S3|
|---|---|---|
|Purpose|Content delivery|Storage|
|Global Edge Locations|Yes|No|
|Caching|Yes|No|

---

## Exam Keywords 🎯

- “Low latency globally” → CloudFront
    
- “Edge locations” → CloudFront
    
- “Content delivery network (CDN)” → CloudFront
    

---

### For CLF-C02 remember:

> CloudFront = CDN that delivers content globally using edge locations