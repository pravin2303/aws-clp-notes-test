## VPN (Virtual Private Network) – CLF-C02 Scope 🔐🌐

An **AWS VPN** creates a **secure, encrypted connection** between your on-premises network and your  
Amazon Virtual Private Cloud.

It uses the **public internet**, but the data is encrypted.

---

## Types of AWS VPN (High-Level)

### 1️⃣ Site-to-Site VPN

- Connects on-premises data center to AWS VPC
    
- Used for hybrid cloud setups
    

### 2️⃣ Client VPN

- Allows individual users to securely connect to AWS
    

(No deep technical details required for CLF-C02.)

---

## Why Use VPN?

✔ Secure communication  
✔ Encrypted data transfer  
✔ Hybrid connectivity  
✔ Lower cost than Direct Connect

---

## VPN vs Direct Connect (Exam Favorite)

|Feature|VPN|Direct Connect|
|---|---|---|
|Uses Internet|Yes|No|
|Encryption|Yes|Optional|
|Cost|Lower|Higher|
|Performance|Depends on internet|More consistent|

---

## Example (Exam Scenario)

Company wants secure connection from office to AWS but at lower cost.

Solution → VPN.

If question says “dedicated private connection” → Direct Connect.  
If question says “encrypted internet connection” → VPN.

---

## Key Exam Keywords 🎯

- “Encrypted connection” → VPN
    
- “Hybrid cloud connectivity” → VPN
    
- “Secure tunnel over internet” → VPN
    

---

### For CLF-C02 remember:

> VPN = Encrypted internet connection to AWS