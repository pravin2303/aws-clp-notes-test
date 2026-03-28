## 🔑 SSH Key – CLF-C02 Scope

An **SSH Key (Secure Shell Key)** is used to **securely connect to a remote server** without using a password.

In AWS, SSH keys are mainly used to access  
Amazon EC2 instances.

---

## How SSH Key Works

An SSH key pair contains two keys:

|Key Type|Location|Purpose|
|---|---|---|
|**Public Key**|Stored on the server (EC2 instance)|Allows access|
|**Private Key**|Stored on your computer|Used to log in securely|

When you connect, the server checks if the private key matches the stored public key.

---

## Example

When launching an EC2 instance:

1️⃣ AWS creates or you upload a **Key Pair**  
2️⃣ Download the **private key (.pem file)**  
3️⃣ Use the key to connect via SSH

Example command:

ssh -i key.pem ec2-user@public-ip

---

## Why SSH Keys Are Used

✔ More secure than passwords  
✔ Prevents unauthorized access  
✔ Used for Linux server access

---

## SSH vs Password Login

|Feature|SSH Key|Password|
|---|---|---|
|Security|High|Lower|
|Authentication|Key pair|Text password|
|Common Use|EC2 access|Basic login|

---

## 🎯 Exam Keywords

- **Secure login to EC2** → SSH
    
- **Key pair authentication** → SSH key
    
- **Private key (.pem)** → Used to connect to instance
    

---

## One-Line Memory

> SSH Key = Secure key pair used to log into EC2 instances. 🔐