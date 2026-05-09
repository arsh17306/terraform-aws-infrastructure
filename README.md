# Terraform AWS Infrastructure Automation

## Project Overview

This project automates AWS infrastructure provisioning using Terraform and GitHub Actions CI/CD.

The infrastructure includes:
- Custom VPC
- Public Subnet
- Internet Gateway
- Route Tables
- Security Groups
- EC2 Instance
- Nginx Web Server

The project follows Infrastructure-as-Code (IaC) principles with modular Terraform architecture and remote backend state management.

---

## Technologies Used

- Terraform
- AWS
- EC2
- VPC
- S3 Backend
- DynamoDB
- GitHub Actions
- Git
- Linux

---

## Project Architecture

Internet
   │
Internet Gateway
   │
Public Subnet
   │
EC2 Instance (Nginx)

---

## Terraform Features

- Reusable Terraform modules
- Environment-based deployment
- Remote Terraform backend
- State locking with DynamoDB
- Automated provisioning
- Infrastructure version control

---

## CI/CD Pipeline

GitHub Actions pipeline performs:
- Terraform Init
- Terraform Validate
- Terraform Format Check
- Terraform Plan

on every push to the main branch.

---

## Folder Structure

terraform-aws-project/
│
├── modules/
├── environments/
├── backend/
└── .github/workflows/

---

## How to Run

terraform init
terraform plan
terraform apply

---


