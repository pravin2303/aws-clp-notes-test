## AWS Identity and Access Management Policies – CLF-C02 Scope 📜🔐

An **IAM Policy** is a JSON document that defines **permissions** in AWS.

It answers:

- What actions are allowed or denied?
    
- On which resources?
    

---

## What a Policy Contains (High-Level)

A policy defines:

- **Effect** → Allow or Deny
    
- **Action** → What service/action (e.g., s3:GetObject)
    
- **Resource** → Which resource
    

You don’t need to memorize JSON structure for CLF-C02 — just understand the concept.

---

## Types of IAM Policies (Exam Level)

### 1️⃣ Managed Policies

- Created and maintained by AWS
    
- Or created by customer
    
- Can be attached to multiple users, groups, roles
    

### 2️⃣ Inline Policies

- Attached to a single user, group, or role
    
- One-to-one relationship
    

---

## Example

You want a user to access only S3:

Create a policy → Allow S3 actions → Attach to user.

If permission not allowed → Access denied.

---

## Key Characteristics (Exam Focus)

- Define permissions
    
- Follow principle of least privilege
    
- Can allow or deny actions
    
- Attached to users, groups, or roles
    

---

## IAM Policy vs Role (Exam Favorite)

|Feature|Policy|Role|
|---|---|---|
|Defines permissions|Yes|No|
|Provides temporary access|No|Yes|
|Attached to|User/Group/Role|Assumed by user/service|

---

## Exam Keywords 🎯

- “Permission document” → IAM Policy
    
- “Allow or Deny access” → IAM Policy
    
- “Least privilege” → IAM Policy
    

---

### For CLF-C02 remember:

> IAM Policy = Defines what actions are allowed or denied