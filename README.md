# Multi-tier Web Application Deployment using Python and AWS

## 📌 Project Overview

This project demonstrates the automated deployment of a multi-tier web application architecture on AWS using Python and Boto3.

The application is divided into three layers:

- Frontend Layer
- Backend Layer
- Database Layer

All AWS resources were provisioned programmatically using Python scripts and the Boto3 AWS SDK instead of manual AWS Console configuration.

The architecture improves scalability, security, maintainability, and high availability.

---

## 🧰 AWS Services Used

- Amazon EC2
- Amazon RDS
- Application Load Balancer (ALB)
- Security Groups
- Python
- Boto3

---

## 🏗️ Architecture

```text
User
  ↓
Application Load Balancer
  ↓
Frontend EC2 Instance
  ↓
Backend EC2 Instance
  ↓
Amazon RDS Database
```

---

## 🎯 Project Objectives

- Automate AWS infrastructure deployment using Python
- Separate frontend, backend, and database layers
- Implement scalable and secure architecture
- Configure database connectivity
- Enable load balancing and high availability

---

## 🚀 Implementation Steps

### 1. Create Frontend EC2 Instance

Used Python and Boto3 to launch frontend EC2 instances.

Configured:
- Amazon Linux AMI
- Apache Web Server
- HTTP and SSH access

---

### 2. Create Backend EC2 Instance

Created backend EC2 instances using Boto3.

Configured:
- Node.js application server
- Custom application port
- Backend security rules

---

### 3. Create Amazon RDS Database

Automated RDS MySQL database creation using Python and Boto3.

Configured:
- MySQL database engine
- Database credentials
- Security groups
- Database connectivity

---

### 4. Configure Security Groups

Created and configured security groups programmatically for:
- Frontend access
- Backend communication
- Database access

---

### 5. Create Application Load Balancer

Configured an Application Load Balancer to distribute incoming traffic across frontend servers.

Features:
- HTTP listener
- Health checks
- Traffic distribution

---

### 6. Connect Application Layers

Established communication between:
- Frontend → Backend
- Backend → Database

---

### 7. Test Application

Verified successful deployment and communication between all three layers.

---

## 🎯 Features

- Automated Infrastructure Deployment
- Multi-tier Architecture
- Load Balancing
- Database Integration
- High Availability
- Scalable Cloud Infrastructure

---

## 📸 Output

The multi-tier application successfully separated frontend, backend, and database components while enabling secure communication and scalable deployment on AWS.

---

## 🎓 Learning Outcomes

- AWS automation using Python and Boto3
- Multi-tier cloud architecture
- EC2 and RDS integration
- Load Balancer configuration
- Security Group management
- Infrastructure automation concepts

---

## ✅ Conclusion

This project successfully implemented an automated multi-tier web application deployment using Python, Boto3, Amazon EC2, Amazon RDS, and Application Load Balancer to create a scalable, secure, and highly available cloud architecture.
