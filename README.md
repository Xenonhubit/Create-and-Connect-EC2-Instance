# ☁️ Create and Connect to an EC2 Instance

## 📋 Lab Overview
In this lab, I went through the full process of launching an EC2 Linux instance on AWS and connecting to it securely from my local machine using SSH via Git Bash.

---

## 🎯 Objectives
- ✅ Launch an EC2 Linux instance via the AWS Management Console
- ✅ Configure a key pair and security group for SSH access
- ✅ Connect to the instance remotely using Git Bash
- ✅ Run system updates to ensure the instance is secure

---

## 🗺️ Architecture Diagram

<img width="850" height="565" alt="EC2-lab-architecture drawio" src="https://github.com/user-attachments/assets/47890d47-22ec-435a-8a66-78a232a7d2a5" />

---

## 🛠️ Tools & Services Used
| Tool | Purpose |
|------|---------|
| ☁️ AWS EC2 | Cloud virtual machine |
| 🖥️ AWS Console | Launch and configure the instance |
| 🔑 Key Pair (.pem) | Secure SSH authentication |
| 🛡️ Security Group | Firewall — allowed port 22 (SSH) |
| 💻 Git Bash | SSH client on local Windows machine |

---

## 📸 Step-by-Step Screenshots

### 1️⃣ Navigating to EC2 in the AWS Console
<img width="1863" height="993" alt="Aws-console-ec2-launch" src="https://github.com/user-attachments/assets/b6bd3dfa-9012-4f10-80c6-c4b0d16148c1" />

### 2️⃣ Configuring and Launching the Instance
no image 


### 3️⃣ Instance Running ✅
<img width="1866" height="962" alt="Instance-running" src="https://github.com/user-attachments/assets/24b0b895-2ce2-4e4c-8d54-6e35eae0d275" />

### 4️⃣ SSH Connection via Git Bash 🔐
<img width="1881" height="995" alt="gitbash-ssh-connection" src="https://github.com/user-attachments/assets/ee21aa99-9fa7-451c-aabd-fda9f3fcf8fc" />


### 5️⃣ Running System Updates 🛡️
<img width="580" height="457" alt="yum-update-output" src="https://github.com/user-attachments/assets/a18503ae-2734-4c71-823a-895e72a3c416" />


---

## 💡 What I Learned
- How to launch and configure an EC2 instance from scratch
- How SSH key pairs work for secure remote access
- How security groups act as a cloud firewall
- How to keep a Linux instance patched and secure
- How to navigate and use the AWS Management Console confidently

---
*Built as part of my AWS Cloud learning journey ☁️💪*

---
Thank you for looking at my work, My name is Stewart Ayim 
