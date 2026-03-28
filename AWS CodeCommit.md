## 🗂️ AWS CodeCommit – CLF-C02 Scope

**AWS CodeCommit** is a fully managed **source control service** that hosts **Git repositories**.

It is used by developers to **store and manage application source code** securely.

---

# 🎯 What CodeCommit Does

✔ Stores source code  
✔ Tracks code changes (version control)  
✔ Supports Git repositories  
✔ Enables collaboration between developers

---

# Example

Developers working on a project push their code to **CodeCommit repository**.

From there, the code can be built and deployed using:

- AWS CodePipeline
    
- AWS CodeDeploy
    

---

# CodeCommit vs GitHub (Concept)

|Feature|CodeCommit|GitHub|
|---|---|---|
|Type|AWS managed Git repository|External Git hosting platform|
|Integration|Deep AWS integration|General DevOps platform|
|Security|IAM-based access control|GitHub authentication|

---

# DevOps Pipeline Example

Developer → CodeCommit → CodeBuild → CodeDeploy

---

# 🎯 Exam Keywords

- **Source control service** → CodeCommit
    
- **Git repository hosting** → CodeCommit
    
- **Store application code** → CodeCommit
    

---

## One-Line Memory

> CodeCommit = AWS-managed Git repository for storing source code.