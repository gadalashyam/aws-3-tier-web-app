# AWS 3-Tier Web Application Architecture

## Project Overview
This project demonstrates deployment of a secure and highly available 3-tier web application architecture on AWS.

## AWS Services Used
- Amazon VPC
- EC2
- Application Load Balancer (ALB)
- RDS MySQL
- NAT Gateway
- Internet Gateway
- Bastion Host
- Security Groups

---

## Architecture Diagram

![Architecture](architecture-diagram.jpeg)

---

## Architecture Explanation

### Web Tier
- Hosted in Public Subnets
- Uses Application Load Balancer
- Receives user traffic

### Application Tier
- EC2 instances in Private Subnets
- Apache + PHP installed
- Handles application logic

### Database Tier
- Amazon RDS MySQL
- Multi-AZ deployment
- Hosted in Private Subnets

---

## Features
- High Availability
- Secure Architecture
- Multi-AZ Deployment
- Load Balancing
- Database Integration

---

## Project Steps
Detailed implementation steps available in:

```text
project-steps.txt
```

---

## Author
Gadala Shyam
DevOps & Cloud Enthusiast
