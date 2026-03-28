## Edge Locations – CLF-C02 Scope 🌐

**Edge Locations** are AWS data centers located around the world that are used to **deliver content closer to users**.

They are part of the global infrastructure of  
Amazon Web Services.

---

## Main Purpose

- Reduce latency
    
- Improve performance
    
- Deliver content faster
    

---

## Which Service Uses Edge Locations?

Primarily used by:

- Amazon CloudFront
    

CloudFront caches content at edge locations and serves users from the nearest location.

---

## How It Works (Simple Concept)

1. User requests content
    
2. Request goes to nearest edge location
    
3. If content is cached → Delivered immediately
    
4. If not → Retrieved from origin (S3, EC2, etc.) and cached
    

---

## Why It Is Important

- Faster website loading
    
- Better user experience
    
- Reduced load on origin servers
    
- Global content delivery
    

---

## Edge Location vs Region (Exam Favorite)

|Component|Purpose|
|---|---|
|Region|Run applications|
|Availability Zone|High availability inside region|
|Edge Location|Low-latency content delivery|

---

## Exam Keywords

- “Low latency globally” → Edge Locations
    
- “Content caching” → CloudFront + Edge
    
- “Global users” → Edge Locations
    

---

For CLF-C02 remember:

> Edge Location = Faster content delivery near users