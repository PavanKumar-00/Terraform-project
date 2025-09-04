# Terraform AWS Project

This project uses **Terraform** to provision AWS infrastructure including:
- A VPC with subnets and networking configuration
- An EC2 instance
- Configurable variables for easy customization

 # Prerequisites
- An AWS account
- AWS CLI installed and configured 
- Terraform v1.x installed in system

terraform init

terraform validate

terraform plan

terraform apply -auto-approve

terraform destroy -auto-approve

# Project Structure

provider.tf → Configures the AWS provider (region, credentials).
variables.tf → Defines input variables (region, instance type, etc.).
terraform.tfvars → Stores values for the variables.
vpc.tf → Creates VPC, subnets, internet gateway, route tables.
ec2.tf → Creates an EC2 instance in the VPC.
outputs.tf → Prints useful information like instance public IP.

# References

Terraform AWS Provider Docs.
Terraform CLI Commands.

