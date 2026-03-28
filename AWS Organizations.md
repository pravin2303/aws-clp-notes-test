## 🏢 AWS Organizations – CLF-C02 Scope

**AWS Organizations** helps you centrally manage **multiple AWS accounts**.

It is used by companies that want:

- Centralized control
    
- Governance
    
- Policy enforcement
    
- Consolidated billing
    

---

# 🎯 What AWS Organizations Provides

✔ Create and manage multiple AWS accounts  
✔ Group accounts into Organizational Units (OUs)  
✔ Apply Service Control Policies (SCPs)  
✔ Enable consolidated billing

---

# 🔹 Key Concepts (Exam Level)

### 1️⃣ Management Account

Main account that controls others.

### 2️⃣ Member Accounts

Accounts under the organization.

### 3️⃣ Organizational Units (OUs)

Logical grouping of accounts (e.g., Dev, Test, Prod).

### 4️⃣ Service Control Policies (SCPs)

Define maximum permissions for accounts.

👉 SCPs do NOT grant permissions.  
👉 They limit what accounts can do.

---

# 🔥 Example (Exam Scenario)

Company has:

- Dev account
    
- Test account
    
- Production account
    

They want central control and billing → Use AWS Organizations.

---

# Organizations vs IAM (Exam Favorite)

|Feature|AWS Organizations|IAM|
|---|---|---|
|Scope|Multiple accounts|Single account|
|Purpose|Governance & billing|Access control|
|Applies SCPs|Yes|No|

---

# 🎯 Exam Keywords

- “Manage multiple AWS accounts” → AWS Organizations
    
- “Apply guardrails across accounts” → SCPs
    
- “Single combined bill” → Consolidated Billing
    

---

## One-Line Memory

> AWS Organizations = Central management for multiple AWS accounts