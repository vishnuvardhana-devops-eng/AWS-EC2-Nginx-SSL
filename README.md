# AWS EC2 + Nginx (Production-Ready Starter)

** Need HTTPS on AWS EC2 fast?**  
   An extended version with HTTPS automation and hardening is available here:
  👉 https://vishnudevopseng.gumroad.com/l/vqxzh


This repository helps you quickly launch an AWS EC2 instance with Nginx installed,
using Terraform and simple shell scripts.

⚡ Goal: Get a working web server running in minutes with clean, repeatable setup.

---

## What This Repo Does

- Provisions an EC2 instance using Terraform
- Configures security groups (SSH + HTTP)
- Installs and starts Nginx automatically
- Uses simple, readable scripts (no magic)

---

## Who This Is For

- Freelancers
- Startup engineers
- Anyone who wants a quick EC2 + Nginx setup

---

## Prerequisites

- AWS account
- Terraform installed
- An existing EC2 key pair
- Basic AWS CLI access

---

## Usage

```bash
cd terraform
terraform init
terraform apply

