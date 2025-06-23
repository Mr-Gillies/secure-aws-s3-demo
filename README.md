# Secure AWS S3 Bucket with Terraform

This project demonstrates how to provision a **secure, private AWS S3 bucket** using [Terraform](https://www.terraform.io/). It's my first step into Infrastructure as Code (IaC) and cloud security.

## 🛠 What It Does

- Creates an S3 bucket with a unique name
- Blocks **all public access**
- Applies tags for easy identification
- Enables **server-side encryption**
- Cleaned up with `terraform destroy` to avoid charges

## 🔒 Why It Matters

Security is a critical part of working in the cloud. This project shows how to:
- Use IaC to deploy consistent and repeatable cloud infrastructure
- Secure cloud storage by default
- Avoid misconfigurations that can lead to data breaches

## 🧪 Tools Used

- [Terraform v1.12.2](https://www.terraform.io/)
- AWS S3
- Visual Studio Code

## 💡 What I Learned

- Basics of Terraform syntax and commands (`init`, `plan`, `apply`, `destroy`)
- How to secure S3 buckets
- How to structure a simple infrastructure project and commit it to GitHub

## 🚀 How to Use

1. Clone this repo  
2. Set up your AWS credentials  
3. Run:
   ```bash
   terraform init
   terraform plan
   terraform apply
