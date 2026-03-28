## AWS Shared Responsibility Model – CLF-C02 Scope 🔐☁️

The **Shared Responsibility Model** explains **who is responsible for what** in cloud security between:

- Amazon Web Services
    
- The customer
    

---

# 🔹 Core Concept

> AWS is responsible **for security of the cloud**  
> Customer is responsible **for security in the cloud**

---

## 1️⃣ AWS Responsibility

(Security **of** the Cloud)

AWS manages and protects:

- Physical data centers
    
- Hardware
    
- Networking infrastructure
    
- Virtualization layer
    

You do NOT manage physical servers.

---

## 2️⃣ Customer Responsibility

(Security **in** the Cloud)

Customers manage:

- Data
    
- IAM users and permissions
    
- Security groups
    
- Operating system (for EC2)
    
- Application security
    

---

## Example (EC2 Scenario)

If you launch an EC2 instance:

- AWS → Secures physical server
    
- You → Secure OS, install patches, configure firewall
    

---

## Service Model Impact (Exam Concept)

Responsibility depends on service type:

|Service Type|Customer Responsibility|
|---|---|
|IaaS (EC2)|More responsibility|
|PaaS (Elastic Beanstalk)|Less|
|SaaS|Least|

More managed service → Less customer responsibility.

---

## Exam Keywords 🎯

- “Security of the cloud” → AWS
    
- “Security in the cloud” → Customer
    
- “Who patches EC2 OS?” → Customer
    
- “Who secures data centers?” → AWS
    

---

### For CLF-C02 remember:

> AWS secures infrastructure  
> Customer secures data and configurations