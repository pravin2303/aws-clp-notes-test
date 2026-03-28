## 🔍 AWS X-Ray – CLF-C02 Scope

**AWS X-Ray** is a service used to **analyze and debug distributed applications** in AWS.

It helps developers understand how requests travel through different services in an application.

---

# 🎯 What AWS X-Ray Does

✔ Traces application requests  
✔ Identifies performance bottlenecks  
✔ Finds application errors  
✔ Shows service dependencies

---

# How It Works (Simple Concept)

1️⃣ A request enters your application  
2️⃣ X-Ray tracks the request across services  
3️⃣ It shows the path and performance of each component

Example components:

- EC2
    
- Lambda
    
- API Gateway
    
- Databases
    

---

# Example

If a web application is slow:

AWS X-Ray can show:

- Which service caused the delay
    
- Which component failed
    

---

# X-Ray vs CloudWatch (Exam Concept)

|Service|Purpose|
|---|---|
|CloudWatch|Monitor metrics & logs|
|X-Ray|Trace application requests|

👉 “Monitor CPU usage” → CloudWatch  
👉 “Trace request path in application” → X-Ray

---

# 🎯 Exam Keywords

- “Application tracing” → X-Ray
    
- “Debug distributed applications” → X-Ray
    
- “Analyze request flow” → X-Ray
    

---

## One-Line Memory

> X-Ray = Trace and debug distributed applications in AWS