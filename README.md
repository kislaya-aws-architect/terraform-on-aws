# 🌍 Terraform on AWS

This repo contains Infrastructure as Code projects to provision and manage AWS infrastructure using **Terraform**.

---

## 📁 Modules & Examples

| Folder | Description |
|--------|-------------|
| `s3-bucket/`       | Create a secure S3 bucket with versioning & encryption |
| `vpc-module/`      | Custom VPC with subnets, IGW, route tables |
| `ec2-instance/`    | Launch EC2 with security groups and key pair |
| `iam-role/`        | Create IAM roles with policies |

---

## 🛠️ Tools

- Terraform CLI
- AWS CLI
- AWS Provider
- GitHub for version control

---

## 🚀 How to Run

1. Initialize Terraform  
   `terraform init`
2. Preview the changes  
   `terraform plan`
3. Apply the config  
   `terraform apply`

Each module has its own `main.tf` and documentation.

---

## 🎯 Learning Goals

- Write reusable modules
- Understand Terraform lifecycle
- Manage resources cleanly with version control

---

🔗 [Back to Portfolio](https://kislaya-aws-architect.github.io)
