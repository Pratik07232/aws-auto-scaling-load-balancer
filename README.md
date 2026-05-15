# AWS Auto Scaling & Load Balancer Project

## 📌 Project Overview

This project demonstrates the implementation of a scalable and highly available web application architecture on AWS using Auto Scaling and Application Load Balancer.

The infrastructure automatically adjusts EC2 instances based on traffic demand to improve availability, fault tolerance, and performance.

---

# 🚀 AWS Services Used

* EC2
* Auto Scaling Group
* Launch Template
* Application Load Balancer (ALB)
* Target Group
* CloudWatch
* Security Groups
* VPC

---

# 🏗️ Architecture Diagram

(Add architecture diagram image here)

Example:

```md
![Architecture](screenshots/architecture.png)
```

---

# 🎯 Project Objectives

* Build scalable AWS infrastructure
* Configure automatic EC2 scaling
* Distribute traffic using Load Balancer
* Improve application availability
* Learn cloud monitoring and scaling concepts

---

# ⚙️ Step-by-Step Implementation

## Step 1: Launch EC2 Instance

* Created Ubuntu EC2 instance
* Installed Nginx web server
* Configured sample web page

---

## Step 2: Create AMI

* Created custom AMI from configured EC2 instance
* Used AMI for automatic instance launching

---

## Step 3: Create Launch Template

Configured:

* AMI
* Instance type
* Security Group
* Key Pair

Purpose:

* Automatically launch identical EC2 instances

---

## Step 4: Configure Target Group

Created Target Group for Application Load Balancer.

Purpose:

* Route traffic to healthy EC2 instances

---

## Step 5: Create Application Load Balancer

Configured:

* Internet-facing Load Balancer
* Listener rules
* Target Group attachment

Purpose:

* Distribute traffic across multiple EC2 instances

---

## Step 6: Configure Auto Scaling Group

Configured:

* Minimum instances
* Desired instances
* Maximum instances

Purpose:

* Automatically increase or decrease instances based on traffic

---

## Step 7: Configure CloudWatch Monitoring

Used CloudWatch metrics for:

* CPU utilization
* Monitoring EC2 health
* Auto Scaling triggers

---

# 🔐 Security Best Practices

* Used Security Groups for controlled access
* Allowed HTTP traffic only where required
* Restricted SSH access
* Distributed traffic using Load Balancer

---

# 📈 Project Outcome

Successfully created scalable and highly available AWS infrastructure using Auto Scaling Group and Application Load Balancer.

This project improved understanding of:

* AWS scalability
* High availability
* Cloud monitoring
* Load balancing
* Infrastructure automation

---

# 🖼️ Screenshots

(Add screenshots inside screenshots folder)

Examples:

* EC2 instances
* Load Balancer
* Auto Scaling Group
* CloudWatch metrics
* Launch Template

---

# 🚀 Future Improvements

* Add HTTPS using ACM
* Configure Route 53
* Implement CI/CD pipeline
* Deploy containerized applications
* Add Terraform automation

---

# 👨‍💻 Author

## Pratik Gadekar

Entry-level Cloud Engineer

* GitHub: https://github.com/Pratik07232
* LinkedIn: https://www.linkedin.com/in/pratik-gadekar-a1745731b
