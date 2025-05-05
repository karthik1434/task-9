# Strapi on AWS ECS Fargate using Terraform

This project automates the deployment of a Strapi CMS application on AWS using **ECS Fargate**, with support for **Fargate Spot** fallback, **load balancing**, **CloudWatch monitoring**, **autoscaling**, and **ECR image hosting**, all managed via **Terraform**.

---

## 🔧 Features

- 🐳 Strapi container deployed via AWS ECS Fargate
- 🧠 Auto-switching between FARGATE and FARGATE_SPOT for cost efficiency and reliability
- 📈 Auto Scaling (min: 1, max: 10 tasks) with optional CPU-based scaling policies
- 📦 Image hosted in Amazon ECR
- 🌐 Load Balanced using Application Load Balancer (ALB)
- 📊 Logs and metrics stored and monitored via CloudWatch
- 🔐 IAM role with permissions for ECS task execution and logging


