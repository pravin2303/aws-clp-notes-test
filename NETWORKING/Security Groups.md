## Security Groups – CLF-C02 Scope 🔐🖥️

A **Security Group** is a **virtual firewall** that controls inbound and outbound traffic for AWS resources like EC2.

It works inside a  
Amazon Virtual Private Cloud.

---

## What It Protects

Commonly attached to:

- Amazon EC2
    
- RDS databases
    
- Other VPC resources
    

---

## What It Controls

1️⃣ **Inbound Rules** → Incoming traffic  
2️⃣ **Outbound Rules** → Outgoing traffic

If traffic is not explicitly allowed → It is denied.

---

## Key Characteristics (Very Important for Exam)

- Works at **instance level**
    
- It is **stateful**
    
- Supports **Allow rules only**
    
- Default:
    
    - Inbound → Denied
        
    - Outbound → Allowed
        

---

## What Does Stateful Mean? (Exam Favorite)

If you allow inbound traffic:

The response traffic is automatically allowed back.

You do NOT need to create separate return rules.

---

## Example

Web server EC2:

- Allow HTTP (Port 80) from anywhere → Public website
    
- Allow SSH (Port 22) from your IP → Secure login
    

If port not allowed → Access fails.

---

## Security Group vs Network ACL (Quick Difference)

|Feature|Security Group|Network ACL|
|---|---|---|
|Level|Instance|Subnet|
|Stateful|Yes|No|
|Allow & Deny|Allow only|Allow & Deny|

---

## Exam Keywords 🎯

- “Instance-level firewall” → Security Group
    
- “Stateful” → Security Group
    
- “Controls inbound/outbound traffic” → Security Group
    

---

### For CLF-C02 remember:

> Security Group = Stateful instance-level firewall