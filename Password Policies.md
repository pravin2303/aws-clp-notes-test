## Password Policies – CLF-C02 Scope

Password policies are configured in  
AWS Identity and Access Management (IAM).

They define **rules for IAM user passwords** to improve security.

---

# 🎯 What Password Policies Control

You can enforce:

✔ Minimum password length  
✔ Require uppercase letters  
✔ Require lowercase letters  
✔ Require numbers  
✔ Require special characters  
✔ Password expiration  
✔ Prevent password reuse

---

# Why It Is Important

Strong password policies help:

- Protect AWS accounts
    
- Reduce risk of unauthorized access
    
- Improve overall security
    

---

# Example (Exam Scenario)

If question says:

“Company wants to enforce strong passwords for IAM users.”

Correct answer → Configure IAM password policy.

---

# Password Policy vs MFA (Exam Concept)

|Feature|Password Policy|MFA|
|---|---|---|
|Controls password strength|Yes|No|
|Adds second authentication factor|No|Yes|
|Improves login security|Yes|Yes|

👉 “Strong password requirements” → Password Policy  
👉 “Extra security layer at login” → MFA

---

# 🎯 Exam Keywords

- “Minimum password length” → Password Policy
    
- “Password complexity requirements” → Password Policy
    
- “Prevent password reuse” → Password Policy
    

---

## One-Line Memory

> Password Policy = Rules that enforce strong IAM passwords