# Terraform EC2 Project

Simple Terraform setup that deploys an EC2 instance using a module.

## Structure
.
├── main.tf
├── providers.tf
├── variables.tf
├── outputs.tf
├── terraform.tfvars
└── modules/
    └── ec2/
        ├── main.tf
        ├── variables.tf
        └── outputs.tf


## Commands
terraform init
terraform plan
terraform apply
terraform output
terraform destroy

## Includes
- EC2 instance  
- Security Group (SSH)  
- Reusable module  

## Summary
Minimal, clean Terraform project for learning and portfolio use.





