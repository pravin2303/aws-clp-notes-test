## AWS Key Management Service (KMS) – CLF-C02 Scope 🔐🔑

**AWS KMS** is a managed service that helps you **create and control encryption keys** used to protect your data in AWS.

---

## What AWS KMS Does

✔ Create encryption keys  
✔ Manage and rotate keys  
✔ Control who can use keys  
✔ Integrate with other AWS services

---

## Why It Is Important

It helps protect:

- Data stored in S3
    
- EBS volumes
    
- RDS databases
    
- Many other AWS services
    

Encryption helps secure sensitive information.

---

## How It Works (Simple Concept)

1️⃣ Create a KMS key  
2️⃣ Use the key to encrypt data  
3️⃣ Only authorized users can decrypt

Access is controlled using IAM policies.

---

## Key Characteristics (Exam Focus)

- Fully managed service
    
- Centralized key management
    
- Integrated with many AWS services
    
- Supports automatic key rotation
    

---

## KMS vs CloudHSM (Exam Basic Difference)

|Feature|KMS|CloudHSM|
|---|---|---|
|Managed by AWS|Yes|Customer has more control|
|Ease of Use|Simple|More complex|
|Use Case|General encryption|Strict compliance needs|

(No deep detail required for CLF-C02.)

---

## Exam Keywords 🎯

- “Encryption key management” → KMS
    
- “Control access to encryption keys” → KMS
    
- “Encrypt data in S3 or EBS” → KMS
    

---

### For CLF-C02 remember:

> AWS KMS = Managed service for encryption key management