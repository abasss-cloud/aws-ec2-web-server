# AWS EC2 Web Server Deployment

## 📌 Overview
This project demonstrates deploying a secure web server on AWS EC2 using Linux and SSH.

## 🛠 Tools & Services
- AWS EC2
- Amazon Linux 2023
- Nginx
- IAM
- SSH
- WSL (Ubuntu)

## 🏗 Architecture
User → Internet → EC2 (Nginx Web Server)

## 🔐 Security
- IAM user (no root usage)
- Security Group allowing HTTP (80) and SSH (22)
- SSH key-based authentication

## 🚀 Deployment Steps
1. Created EC2 instance (t2.micro)
2. Connected via SSH using WSL
3. Installed and configured Nginx
4. Deployed static website

## 📸 Screenshots


## ✅ Outcome
Successfully deployed a live website on AWS EC2.
