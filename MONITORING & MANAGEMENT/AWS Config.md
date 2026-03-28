## AWS Config – CLF-C02 Scope 📋🔍

**AWS Config** is a service that records and evaluates the **configuration of AWS resources**.

It helps with:

- Compliance
    
- Governance
    
- Auditing configuration changes
    

---

## What AWS Config Does

✔ Records configuration of resources  
✔ Tracks configuration changes over time  
✔ Evaluates resources using rules  
✔ Shows compliance status

---

## Example Questions It Answers

- Who changed a security group rule?
    
- Is encryption enabled on S3 buckets?
    
- Is this resource compliant with company policy?
    

---

## AWS Config Rules (Exam Concept)

You can create rules such as:

- S3 buckets must have encryption enabled
    
- Security groups must not allow open SSH access
    

If a resource violates the rule → Marked **Non-Compliant**

---

## AWS Config vs CloudTrail vs CloudWatch (Exam Favorite)

|Service|Focus|
|---|---|
|CloudTrail|Who did what (API activity)|
|CloudWatch|Performance monitoring|
|AWS Config|Resource configuration & compliance|

---

## Key Exam Keywords 🎯

- “Track configuration changes” → AWS Config
    
- “Compliance monitoring” → AWS Config
    
- “Evaluate resources against rules” → AWS Config
    

---

### For CLF-C02 remember:

> AWS Config = Track configuration + Ensure compliance