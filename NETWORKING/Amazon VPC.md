## Amazon Virtual Private Cloud (VPC) – CLF-C02 Scope 🌐🔒

**Amazon VPC (Virtual Private Cloud)** lets you create a **private network inside AWS** where you launch your resources securely.

It gives you control over:

- IP address range
    
- Subnets
    
- Route tables
    
- Security
    

---

## Simple Meaning

VPC = Your own isolated network in AWS.

Like having your own data center network, but in the cloud.

---

## What You Can Configure

Inside a VPC, you can create:

- Public and Private subnets
    
- Route tables
    
- Internet Gateway
    
- Network ACLs
    
- Security Groups
    

---

## Public vs Private Subnet (Exam Concept)

- **Public Subnet** → Has route to Internet Gateway
    
- **Private Subnet** → No direct internet access
    

Example:

- Web server → Public subnet
    
- Database → Private subnet
    

---

## Key Characteristics (Exam Focus)

- Logically isolated network
    
- Regional service
    
- Can span multiple Availability Zones
    
- Improves security and control
    

---

## Why VPC Is Important

- Secure environment
    
- Network segmentation
    
- High availability across AZs
    

---

## Example Architecture

Users → Internet Gateway → Public Subnet (EC2 Web Server)  
Web Server → Private Subnet (RDS Database)

---

## Exam Keywords 🎯

- “Isolated network” → VPC
    
- “Control IP address range” → VPC
    
- “Public and private subnets” → VPC
    

---

### For CLF-C02 remember:

> VPC = Secure, isolated virtual network in AWS