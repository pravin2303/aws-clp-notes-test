## 💰 Consolidated Billing – CLF-C02 Scope

**Consolidated Billing** is a feature of  
AWS Organizations.

It allows multiple AWS accounts to share **one combined bill**.

---

# 🎯 What Consolidated Billing Does

✔ Combines billing for multiple AWS accounts  
✔ One management (master) account pays the bill  
✔ Member accounts keep separate resources  
✔ Aggregates usage for volume discounts

---

# How It Works (Simple Concept)

1️⃣ Create AWS Organization  
2️⃣ Add member accounts  
3️⃣ All accounts use AWS normally  
4️⃣ One single invoice is generated

---

# Why It Is Useful

- Easier billing management
    
- Better cost visibility
    
- Volume pricing discounts across accounts
    

---

# Example (Exam Scenario)

Company has:

- Dev account
    
- Test account
    
- Production account
    

They want one single monthly bill → Use Consolidated Billing.

---

# Consolidated Billing vs Cost Explorer

|Feature|Consolidated Billing|Cost Explorer|
|---|---|---|
|Combines bills|Yes|No|
|Analyze spending|No|Yes|
|Part of Organizations|Yes|No|

---

# 🎯 Exam Keywords

- “Single bill for multiple accounts” → Consolidated Billing
    
- “Centralized payment” → Consolidated Billing
    
- “Aggregate usage discounts” → Consolidated Billing
    

---

## One-Line Memory

> Consolidated Billing = One combined bill for multiple AWS accounts