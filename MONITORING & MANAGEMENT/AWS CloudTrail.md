## AWS CloudTrail – CLF-C02 Scope 📜🔍

**AWS CloudTrail** is a service that records **AWS account activity and API calls**.

It helps with:

- Auditing
    
- Compliance
    
- Security monitoring
    
- Troubleshooting
    

---

## What CloudTrail Records

✔ Who made the request  
✔ What action was taken  
✔ When it happened  
✔ From which IP address

Example:

- Who deleted an S3 bucket?
    
- Who modified a security group?
    

---

## How It Works (Simple Concept)

1️⃣ User or service makes an API call  
2️⃣ CloudTrail records the event  
3️⃣ Logs are stored (usually in S3)

---

## Why It Is Important

- Track user activity
    
- Investigate security incidents
    
- Meet compliance requirements
    

---

## CloudTrail vs CloudWatch (Exam Favorite)

|Feature|CloudTrail|CloudWatch|
|---|---|---|
|Tracks|API activity|Performance metrics|
|Purpose|Auditing|Monitoring|
|Example|Who deleted resource?|CPU usage high|

---

## Example (Exam Scenario)

If question says:

“Company wants to track who made changes to AWS resources.”

Correct answer → CloudTrail.

---

## Key Exam Keywords 🎯

- “Audit logs” → CloudTrail
    
- “Track API calls” → CloudTrail
    
- “User activity history” → CloudTrail
    

---

### For CLF-C02 remember:

> CloudTrail = Records who did what in your AWS account