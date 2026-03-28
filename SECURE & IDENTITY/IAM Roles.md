## AWS Identity and Access Management Roles – CLF-C02 Scope 🎭🔐

An **IAM Role** is an identity in AWS that provides **temporary permissions** to access AWS services.

Unlike IAM users, roles are **not permanently assigned to one person**.

---

## Why Use IAM Roles?

Roles are mainly used for:

- AWS services accessing other AWS services
    
- Temporary access
    
- Cross-account access
    

---

## How It Works (Simple Concept)

1️⃣ Create IAM Role  
2️⃣ Attach permission policy  
3️⃣ Assign role to:

- EC2
    
- Lambda
    
- Another AWS service  
    4️⃣ Service gets temporary credentials
    

---

## Example (Exam Scenario)

Your EC2 instance needs to access S3.

❌ Do NOT store access keys inside EC2.  
✅ Create IAM Role with S3 access → Attach to EC2.

Secure and recommended method.

---

## Key Characteristics (Exam Focus)

- Temporary security credentials
    
- More secure than hardcoding keys
    
- Used for service-to-service access
    
- Supports cross-account access
    

---

## IAM User vs IAM Role (Exam Favorite)

|Feature|IAM User|IAM Role|
|---|---|---|
|Permanent identity|Yes|No|
|Used by people|Yes|Sometimes|
|Used by AWS services|No|Yes|
|Credentials|Long-term|Temporary|

---

## Exam Keywords 🎯

- “Temporary access” → IAM Role
    
- “EC2 needs access to S3” → IAM Role
    
- “Cross-account access” → IAM Role
    

---

### For CLF-C02 remember:

> IAM Role = Temporary permissions for services or users