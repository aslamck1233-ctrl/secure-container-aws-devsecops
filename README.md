# 🚀 Secure Containerized Application on AWS (DevSecOps Project)

## 📌 Overview
This project demonstrates the secure deployment of a containerized web application on AWS using ECS (Fargate). It focuses on implementing real-world cloud security practices including IAM least privilege, vulnerability scanning, network security, and monitoring.

---

## 🛠️ Tech Stack
- AWS ECS (Fargate)
- Amazon ECR
- Docker
- IAM (Least Privilege)
- CloudWatch & CloudTrail
- Amazon SNS
- Trivy (Vulnerability Scanner)

---

## 🔐 Security Implementation
- Implemented IAM roles with least privilege access
- Configured Security Groups to restrict unnecessary ports
- Used secure Dockerfile (non-root user, minimal base image)
- Performed vulnerability scanning using Trivy (reduced vulnerabilities from 74 → 0)
- Enabled logging using CloudWatch and CloudTrail
- Configured alerts using SNS for suspicious activity

---

## 📊 Architecture
Architecture diagram available in `/architecture` folder.

---

## 📸 Screenshots
Screenshots available in `/screenshots` folder:
- Trivy scan results (before & after)
- ECS running service
- CloudWatch logs
- SNS alert emails

---

## ⚙️ Deployment Steps (High-Level)
1. Build secure Docker image
2. Scan image using Trivy
3. Push image to Amazon ECR
4. Deploy container using ECS (Fargate)
5. Configure IAM roles and Security Groups
6. Enable monitoring using CloudWatch and CloudTrail
7. Set up alerts using SNS

---

## 🔄 CI/CD Pipeline
(To be implemented)

---

## 📈 Key Learnings
- Real-world cloud security implementation
- Container security best
- AWS monitoring and alerting setup
- DevSecOps fundamentals

---

## 👨‍💻 Author
Muhammed Aslam
