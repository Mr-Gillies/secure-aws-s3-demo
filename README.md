# Secure AWS S3 Bucket with Terraform

This is one of my first projects using Terraform. I wanted to learn how to create a secure S3 bucket on AWS using infrastructure as code, and this was a great place to start.

## What I Learned

- How to use Terraform to build cloud infrastructure
- How to secure an S3 bucket by blocking public access and enabling encryption
- How to structure and clean up a Terraform project
- How to push a proper project to GitHub without uploading unnecessary files

## What This Project Does

- Creates an AWS S3 bucket with a unique name
- Blocks all public access
- Enables server-side encryption
- Adds basic tags for identification
- Cleans up everything with `terraform destroy` to avoid unnecessary charges

## Tools Used

- Terraform
- AWS S3
- Visual Studio Code

## How to Use

1. Clone the repo
2. Set up your AWS credentials
3. Run the following commands:
   ```bash
   terraform init
   terraform plan
   terraform apply
