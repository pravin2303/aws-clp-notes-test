## Amazon Cognito – CLF-C02 Scope 👤🔐📱

**Amazon Cognito** is a service that provides **user authentication and authorization for web and mobile applications**.

It helps you add:

- Sign-up
    
- Sign-in
    
- User management
    
- Access control
    

To your applications.

---

## What Cognito Does

✔ Manages user accounts  
✔ Supports social logins (Google, Facebook, etc.)  
✔ Generates temporary credentials  
✔ Scales automatically

---

## Two Main Components (High-Level)

### 1️⃣ User Pools

- Manages user sign-up and sign-in
    
- Stores user credentials
    

### 2️⃣ Identity Pools

- Grants temporary AWS access
    
- Provides credentials to access AWS services
    

(No deep configuration details required for CLF-C02.)

---

## Example

You build a mobile app:

- Users create account using Cognito
    
- After login → App accesses S3 securely
    

Cognito handles authentication.

---

## Cognito vs IAM (Exam Favorite)

|Feature|Cognito|IAM|
|---|---|---|
|Used For|App users|AWS account users|
|Authentication|Yes|Yes|
|Target Audience|Mobile/Web apps|AWS administrators|

---

## When to Use Cognito

✔ Mobile applications  
✔ Web applications  
✔ User sign-in systems  
✔ Serverless applications

---

## Exam Keywords 🎯

- “User authentication for mobile app” → Cognito
    
- “Sign-up and sign-in” → Cognito
    
- “Temporary AWS credentials for app users” → Cognito
    

---

### For CLF-C02 remember:

> Cognito = User authentication service for applications