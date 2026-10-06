# Cloud Based Mobile Backend

## Project Overview

This project demonstrates a cloud-based mobile backend infrastructure using
Amazon Web Services (AWS) and Terraform.

## Objective

To create and deploy cloud infrastructure using Infrastructure as Code (IaC)
with Terraform.

## Technologies Used

- AWS
- Terraform
- Amazon EC2
- Amazon S3
- Amazon VPC
- Internet Gateway
- Nginx
- GitHub
- Visual Studio Code

## AWS Resources Created

1. VPC
2. Public Subnet
3. Internet Gateway
4. Route Table
5. Security Group
6. EC2 Instance
7. S3 Bucket

## Architecture

Mobile App
    |
    v
Internet
    |
    v
Internet Gateway
    |
    v
AWS VPC
    |
    v
Public Subnet
    |
    v
EC2 Instance
    |
    +---- Nginx Web Server
    |
    v
S3 Storage

## Terraform Commands Used

```bash
terraform init
terraform validate
terraform plan
terraform apply