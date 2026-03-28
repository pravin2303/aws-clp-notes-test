## AWS Identity and Access Management (IAM) – CLF-C02 Scope 🔐👤

**AWS IAM** is a service that helps you **securely control access** to AWS resources.

It answers:

- Who can access AWS?
    
- What actions can they perform?
    

---

## What IAM Manages

You can create:

### 1️⃣ Users 👤

Individual accounts for people or applications.

### 2️⃣ Groups 👥

Collection of users with similar permissions.

### 3️⃣ Roles 🎭

Temporary access for services or applications.

### 4️⃣ Policies 📜

JSON documents that define permissions.

---

## How It Works (Simple Concept)

1️⃣ Create IAM user  
2️⃣ Attach policy  
3️⃣ User gets permissions defined in that policy

If permission is not allowed → Access denied.

---

## Key Characteristics (Exam Focus)

- Global service (not region-specific)
    
- Controls access to AWS services
    
- Supports Multi-Factor Authentication (MFA)
    
- Follows principle of least privilege
    

---

## Example

Developer needs access to S3 only:

Create IAM user → Attach S3 access policy → Restrict other services.

---

## IAM vs Security Group (Exam Favorite)

|Feature|IAM|Security Group|
|---|---|---|
|Controls|AWS service access|Network traffic|
|Scope|Account level|Instance level|
|Example|S3 access|Port 80 access|

---

## Exam Keywords 🎯

- “Access management” → IAM
    
- “Permissions” → IAM policy
    
- “Least privilege” → IAM
    
- “MFA” → IAM
    

---

### For CLF-C02 remember:

> IAM = Control who can access what in AWS