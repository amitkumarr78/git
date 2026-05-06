# 🚀 SIMPLE CI/CD Pipeline using Jenkins, Docker & AWS

This project demonstrates a complete end-to-end CI/CD pipeline where code pushed to GitHub is automatically built and deployed on an AWS EC2 instance using Jenkins and Docker.

---

## 📌 Overview

The goal of this project is to automate the entire software delivery process — from code push to live deployment.

Whenever code is pushed to GitHub:
- Jenkins is triggered using a webhook  
- A Docker image is built  
- The running container is replaced with the latest version  
- The application is deployed and accessible via public IP  

---

## 🏗️ Architecture

GitHub → Webhook → Jenkins → Docker → AWS EC2 → Live Application

---

## ⚙️ Technologies Used

- Jenkins (Automation Server)  
- Docker (Containerization)  
- AWS EC2 (Cloud Server)  
- GitHub (Source Code Management)  
- Nginx (Web Server)  

---

## 🔥 Features

- Automatic build on every code push  
- Continuous integration using Jenkins  
- Docker-based deployment  
- Automatic container replacement  
- Live application hosted on AWS EC2  

---

## 🌐 Live Application

Accessible via public IP and port 8081

---

## 🧠 What I Learned

- How CI/CD works in real-world projects  
- Difference between build and deployment  
- Setting up Jenkins on a cloud server  
- Debugging real issues like:
  - Java version mismatch  
  - Docker daemon errors  
  - Permission issues  
  - Node offline problems  
- Importance of automation in DevOps  

---

## ⚠️ Challenges Faced

- Jenkins not starting due to Java version issues  
- Git not installed causing pipeline failures  
- Docker permission errors  
- Container not updating after new builds  
- Browser cache showing old application  

---

## 🚀 Future Improvements

- Push Docker images to Docker Hub  
- Use Jenkinsfile (Pipeline as Code)  
- Deploy using Kubernetes  
- Implement zero-downtime deployment  

