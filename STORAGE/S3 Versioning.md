## Amazon S3 Versioning – CLF-C02 Scope 🗂️🔄

**S3 Versioning** allows you to **keep multiple versions of an object** in the same S3 bucket.

It protects against:

- Accidental deletion
    
- Accidental overwrite
    
- Application errors
    

---

## What Happens When Versioning Is Enabled?

If you:

- Upload a file with same name → New version is created
    
- Delete a file → S3 adds a **delete marker** instead of permanently deleting it
    

Old versions are still available.

---

## Why It Is Important

- Helps in data recovery
    
- Protects against human errors
    
- Useful for backup and compliance
    

---

## Simple Example

You upload:

`report.pdf` → Version 1

You upload updated file with same name → Version 2

Both versions are stored.  
You can restore Version 1 anytime.

---

## Key Exam Points

- Versioning is enabled at **bucket level**
    
- Cannot be disabled permanently (only suspended)
    
- Protects from accidental deletion
    
- Works well with lifecycle policies
    

---

## Versioning + Lifecycle (Exam Concept)

You can:

- Keep latest version active
    
- Move older versions to Glacier for cost savings
    

---

### For CLF-C02 remember:

> S3 Versioning = Multiple versions of the same object for protection