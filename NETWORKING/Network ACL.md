## Network ACL (NACL) – CLF-C02 Scope 🔐🌐

A **Network Access Control List (NACL)** is a **firewall for a subnet** inside a  
Amazon Virtual Private Cloud.

It controls traffic entering and leaving a **subnet**.

---

## Where It Works

- Applied at the **subnet level**
    
- Affects **all resources** inside that subnet
    

---

## What It Controls

1️⃣ **Inbound rules** → Traffic entering the subnet  
2️⃣ **Outbound rules** → Traffic leaving the subnet

---

## Key Characteristics (Very Important for Exam)

- Works at **subnet level**
    
- It is **stateless**
    
- Supports both:
    
    - ✅ Allow rules
        
    - ❌ Deny rules
        
- Rules are evaluated in **number order (lowest first)**
    

---

## What Does Stateless Mean? (Exam Favorite)

If you allow inbound traffic:

You must also explicitly allow outbound traffic for the response.

Return traffic is NOT automatically allowed.

---

## Default Behavior

- Default NACL → Allows all inbound and outbound traffic
    
- Custom NACL → Denies all traffic until rules are added
    

---

## Example

If you allow inbound HTTP (Port 80):

You must also allow outbound response traffic.

Otherwise, communication fails.

---

## Security Group vs NACL (Exam Favorite)

|Feature|Security Group|Network ACL|
|---|---|---|
|Level|Instance|Subnet|
|Stateful|Yes|No|
|Allow & Deny|Allow only|Allow & Deny|
|Rule Order Matters|No|Yes|

---

## Exam Keywords 🎯

- “Subnet-level firewall” → NACL
    
- “Stateless” → NACL
    
- “Explicit deny rule” → NACL
    

---

### For CLF-C02 remember:

> NACL = Stateless subnet-level firewall
> 