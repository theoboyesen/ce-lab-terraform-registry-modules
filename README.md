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
