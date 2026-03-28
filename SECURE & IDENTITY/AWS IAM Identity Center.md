## AWS IAM Identity Center – CLF-C02 Scope 🔐👥

**AWS IAM Identity Center** (formerly AWS Single Sign-On) helps you **centrally manage access** to:

- Multiple AWS accounts
    
- AWS applications
    
- Third-party applications
    

Using a single login.

---

## What It Does

✔ Single Sign-On (SSO) access  
✔ Centralized permission management  
✔ Manage multiple AWS accounts easily  
✔ Integrates with corporate directory (like Active Directory)

---

## Why It Is Important

If a company has:

- Multiple AWS accounts
    
- Many employees
    

IAM Identity Center allows:

- Users to log in once
    
- Access all assigned accounts
    

Without creating separate IAM users in each account.

---

## How It Works (Simple Concept)

1️⃣ Create users or connect directory  
2️⃣ Assign permission sets  
3️⃣ Assign users to AWS accounts  
4️⃣ Users log in via central portal

---

## IAM vs IAM Identity Center (Exam Concept)

|Feature|IAM|IAM Identity Center|
|---|---|---|
|Scope|Single AWS account|Multiple AWS accounts|
|SSO|No|Yes|
|Centralized access|Limited|Yes|

---

## When to Use

✔ Organizations with multiple AWS accounts  
✔ Enterprise environments  
✔ Central access management

---

## Exam Keywords 🎯

- “Single sign-on” → IAM Identity Center
    
- “Multiple AWS accounts” → IAM Identity Center
    
- “Centralized access management” → IAM Identity Center
    

---

### For CLF-C02 remember:

> IAM Identity Center = Centralized SSO access for multiple AWS accounts