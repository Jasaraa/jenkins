# 🚀 Automated CI/CD Pipeline using Jenkins on AWS EC2

## 📌 Project Overview
This project demonstrates a fully automated CI/CD pipeline that eliminates manual deployment by automatically building and deploying code changes to a live web server.

---

## 🎯 Objective
- Automate application deployment
- Reduce manual errors
- Enable faster and reliable releases

---

## 🏗️ Architecture

Developer → GitHub → Jenkins → AWS EC2 → Live Application

---

## ⚙️ Tech Stack

- GitHub (Version Control)
- Jenkins (CI/CD Tool)
- AWS EC2 (Server)
- Apache (Web Server)
- Linux (OS)
- Git

---

## 🔧 Implementation Steps

1. Created a GitHub repository (`jenkins`)
2. Launched an AWS EC2 instance (Linux)
3. Installed:
   - Git
   - Java
   - Jenkins
   - Apache Web Server
4. Configured Jenkins pipeline
5. Connected GitHub with Jenkins using Webhook
6. Automated deployment to `/var/www/html`

---

## 🔄 Workflow

1. Developer pushes code to GitHub  
2. GitHub triggers Jenkins via webhook  
3. Jenkins pulls latest code  
4. Pipeline executes (Build → Test → Deploy)  
5. Application is updated on live server  

---

## 📈 Key Features

✔️ Fully automated deployment  
✔️ Real-time updates  
✔️ Reduced manual intervention  
✔️ Scalable and reliable pipeline  

---

## 🌐 Live Output

Application deployed on AWS EC2 Web Server

---
