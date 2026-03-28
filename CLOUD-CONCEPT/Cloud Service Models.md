## Cloud Service Models – CLF-C02 Scope ☁️

Cloud service models define **who manages what** in the cloud.

For the exam, focus on these three:

- IaaS
    
- PaaS
    
- SaaS
    

---

# 1️⃣ IaaS – Infrastructure as a Service

You manage:

- OS
    
- Applications
    
- Data
    

Cloud provider manages:

- Hardware
    
- Networking
    
- Virtualization
    

Example in AWS:

- Amazon EC2
    

👉 You launch a virtual server and manage everything inside it.

---

# 2️⃣ PaaS – Platform as a Service

You manage:

- Applications
    
- Data
    

Cloud provider manages:

- OS
    
- Runtime
    
- Infrastructure
    

Example in AWS:

- AWS Elastic Beanstalk
    

👉 You upload code, AWS handles the environment.

---

# 3️⃣ SaaS – Software as a Service

Cloud provider manages:

- Everything
    

You just use the software.

Example:

- Amazon WorkSpaces
    
- Gmail (non-AWS example)
    

👉 No infrastructure management needed.

---

# Quick Comparison (Exam Table)

|Model|You Manage|Provider Manages|
|---|---|---|
|IaaS|Apps, OS|Infrastructure|
|PaaS|Apps|OS + Infrastructure|
|SaaS|Nothing|Everything|

---

## Easy Way to Remember 🎯

More control → IaaS  
Less management → SaaS

---

## Exam Tip

If question says:

- “User manages OS” → IaaS
    
- “Upload code only” → PaaS
    
- “Fully managed software” → SaaS
    

---

For CLF-C02 remember:

> IaaS = Most control  
> PaaS = Focus on code  
> SaaS = Just use the software