## Multi-Factor Authentication (MFA) – CLF-C02 Scope 🔐📱

**Multi-Factor Authentication (MFA)** adds an extra layer of security to your AWS account and IAM users.

It is configured using  
AWS Identity and Access Management.

---

## What Is MFA?

MFA requires **two types of authentication**:

1️⃣ Something you know → Password  
2️⃣ Something you have → One-time code (OTP)

Even if someone steals your password, they cannot log in without the second factor.

---

## How MFA Works (Simple Concept)

1️⃣ User enters username + password  
2️⃣ User enters one-time code from:

- Authenticator app
    
- Hardware token
    

Access is granted only if both are correct.

---

## Why MFA Is Important

✔ Protects root account  
✔ Protects IAM users  
✔ Prevents unauthorized access  
✔ Increases security

---

## Example (Exam Scenario)

If question says:

“Company wants to add extra security to AWS account login.”

Correct answer → Enable MFA.

---

## MFA and Root Account (Very Important for Exam)

Best practice:

- Always enable MFA on the **root account**
    
- Do not use root account for daily tasks
    

---

## Exam Keywords 🎯

- “Extra layer of security” → MFA
    
- “One-time password” → MFA
    
- “Protect root account” → Enable MFA
    

---

### For CLF-C02 remember:

> MFA = Password + One-time code for stronger security