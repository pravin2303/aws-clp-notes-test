## AWS WAF – CLF-C02 Scope 🔐🌐

**AWS WAF (Web Application Firewall)** helps protect web applications from **common web exploits**.

It filters and monitors **HTTP/HTTPS traffic**.

---

## What AWS WAF Protects Against

- SQL injection attacks
    
- Cross-site scripting (XSS)
    
- Malicious bots
    
- Unwanted traffic
    

---

## How It Works (Simple Concept)

You create **rules** that:

- Allow traffic
    
- Block traffic
    
- Monitor traffic
    

Example:  
Block requests from specific IP addresses.

---

## Works With

- Amazon CloudFront
    
- Application Load Balancer
    
- API Gateway
    

---

## AWS WAF vs AWS Shield (Exam Favorite)

|Feature|AWS WAF|AWS Shield|
|---|---|---|
|Protects Against|Web attacks (SQLi, XSS)|DDoS attacks|
|Layer|Application layer (Layer 7)|Network & transport layers|
|Custom Rules|Yes|Limited (automatic protection)|

---

## Example (Exam Scenario)

If question says:

“Protect web app from SQL injection.”

Answer → AWS WAF.

If question says:

“Protect against DDoS attack.”

Answer → AWS Shield.

---

## Key Exam Keywords 🎯

- “Web application firewall” → AWS WAF
    
- “Block SQL injection” → AWS WAF
    
- “Control HTTP/HTTPS traffic” → AWS WAF
    

---

### For CLF-C02 remember:

> AWS WAF = Protect web applications from common web attacks