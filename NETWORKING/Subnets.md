## Subnets – CLF-C02 Scope 🌐📦

A **Subnet** is a subdivision of a  
Amazon Virtual Private Cloud (VPC).

It is a **range of IP addresses** where you place your AWS resources (like EC2).

---

## Key Characteristics (Exam Focus)

- Exists inside a VPC
    
- Created in a **single Availability Zone**
    
- Used to organize and secure resources
    

You must launch resources inside a subnet.

---

## Types of Subnets

### 1️⃣ Public Subnet 🌍

- Has a route to the Internet Gateway
    
- Resources can access the internet
    

Example: Web server

---

### 2️⃣ Private Subnet 🔒

- No direct route to Internet Gateway
    
- Not accessible from the internet
    

Example: Database server

---

## Why Subnets Are Important

✔ Improve security  
✔ Separate application layers  
✔ Enable high availability across AZs

---

## Example Architecture (Exam Concept)

- Public Subnet → EC2 Web Server
    
- Private Subnet → RDS Database
    

Users access web server.  
Database remains protected.

---

## Subnet vs VPC (Exam Favorite)

|Component|Meaning|
|---|---|
|VPC|Entire virtual network|
|Subnet|Smaller network inside VPC|

---

## Exam Keywords 🎯

- “Range of IP addresses” → Subnet
    
- “Single Availability Zone” → Subnet
    
- “Public or Private” → Subnet
    

---

### For CLF-C02 remember:

> Subnet = IP range inside a VPC, created in one AZ