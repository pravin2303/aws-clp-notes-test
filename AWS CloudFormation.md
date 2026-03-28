## 🏗️ AWS CloudFormation – CLF-C02 Scope

**AWS CloudFormation** is a service used to **create and manage AWS infrastructure using code (templates).**

Instead of creating resources manually, you define them in a **template file**.

---

# 🎯 What CloudFormation Does

✔ Automates infrastructure deployment  
✔ Creates multiple AWS resources at once  
✔ Uses Infrastructure as Code (IaC)  
✔ Ensures consistent environment setup

---

# How It Works (Simple Concept)

1️⃣ Write a **template (JSON or YAML)**  
2️⃣ Define resources like:

- EC2
    
- S3
    
- VPC
    
- RDS
    

3️⃣ Deploy the template  
4️⃣ AWS automatically creates all resources

---

# Example

If you want to create:

- 2 EC2 instances
    
- 1 load balancer
    
- 1 database
    

Instead of manually configuring each service, you define everything in **one CloudFormation template**.

---

# CloudFormation vs Elastic Beanstalk

|Feature|CloudFormation|Elastic Beanstalk|
|---|---|---|
|Purpose|Infrastructure automation|Application deployment|
|Uses templates|Yes|No|
|Control level|High|Managed platform|

👉 “Infrastructure as Code” → CloudFormation  
👉 “Deploy web application quickly” → Elastic Beanstalk

---

# 🎯 Exam Keywords

- “Infrastructure as Code” → CloudFormation
    
- “Automate AWS resource creation” → CloudFormation
    
- “Use templates to create infrastructure” → CloudFormation
    

---

## One-Line Memory

> CloudFormation = Infrastructure as Code for AWS resources