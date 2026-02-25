<<<<<<< HEAD
# Lab M4.06 - Terraform Registry Modules

## Overview
Deployed complete infrastructure using official Terraform Registry modules.

## Modules Used
- **VPC Module**: `terraform-aws-modules/vpc/aws` v5.1.0
- **EC2 Module**: `terraform-aws-modules/ec2-instance/aws` v5.5.0
- **Security Group**: `terraform-aws-modules/security-group/aws` v5.1.0

## Infrastructure Created
- VPC with 3 public and 3 private subnets
- NAT Gateway for private subnet internet access
- EC2 instance running Apache web server
- Security group allowing HTTP/HTTPS/SSH
=======
# Lab M4.06 - Use Community Modules

**Course:** Cloud Engineering Bootcamp - Week 4
**Estimated Time:** 45-60 minutes

## 🎯 Objectives

- Use modules from Terraform Registry
- Understand module versioning
- Combine multiple community modules
- Compare community vs custom modules

## 📁 Repository Structure

```
ce-lab-terraform-registry-modules/
├── README.md
├── main.tf
├── outputs.tf
├── module-comparison.md
└── screenshots/
```

## ✅ Grading (100pts)

- VPC module usage: 25pts
- EC2 module usage: 25pts
- Module integration: 20pts
- Comparison analysis: 20pts
- Documentation: 10pts
>>>>>>> afd819f609f587033469f91dd706b3a5c5e69dd5
