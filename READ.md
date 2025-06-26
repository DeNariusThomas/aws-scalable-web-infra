# AWS Scalable Web Infrastructure (3-Tier Architecture)

This project simulates a highly available and scalable 3-tier web application infrastructure on AWS. It demonstrates best practices in cloud architecture design, automation, and resilience — making it an ideal showcase for Solutions Architect roles.

---

## 📌 Project Overview

This project implements a production-ready infrastructure including:

- **Web Layer**: Auto Scaling Group of EC2 instances behind an Application Load Balancer (ALB)
- **Application Layer**: EC2 or Lambda functions handling business logic
- **Database Layer**: Amazon RDS (MySQL/PostgreSQL) in Multi-AZ for high availability

Additional components include:

- Amazon Route 53 for DNS routing  
- AWS CloudWatch for monitoring and alerts  
- IAM roles with least-privilege access  
- S3 for static content or backups  
- VPC with public/private subnets across multiple Availability Zones  
- NAT Gateway for secure outbound internet access from private subnets  
- Infrastructure-as-Code via AWS CloudFormation or Terraform (optional)

---

## 🎯 Objectives

- Demonstrate architectural best practices for scalable and fault-tolerant systems
- Gain hands-on experience designing multi-tier applications on AWS
- Showcase infrastructure planning skills and AWS resource orchestration
- Prepare for real-world Solutions Architect responsibilities

---

## 🧰 Tools & Services Used

| Service        | Purpose                                |
|----------------|----------------------------------------|
| EC2            | Web & App servers                      |
| ALB            | Traffic distribution/load balancing    |
| RDS            | Managed relational database            |
| Route 53       | DNS and health checks                  |
| S3             | Static asset or backup storage         |
| VPC/Subnets    | Network isolation & segmentation       |
| CloudWatch     | Monitoring and alerting                |
| IAM            | Secure access and role assignment      |
| NAT Gateway    | Secure internet access from private    |

---

## 🗂️ Folder Structure

---

## 📸 Architecture Diagram

![3-tier app diagram](architecture/Scalable_Web_App_Diagram.png)

---

## 🚀 Future Enhancements

- Add IaC templates using CloudFormation or Terraform  
- Integrate with CI/CD pipelines (CodePipeline, GitHub Actions)  
- Use AWS Systems Manager for patching and automation  
- Add caching layer with Amazon ElastiCache

---

## 🔐 Author

**DeNarius Thomas**  
Fort Walton Beach, FL  
[GitHub](https://github.com/DeNariusThomas)

---


