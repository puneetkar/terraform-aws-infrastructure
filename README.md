# terraform-aws-infrastructure
# Terraform AWS Infrastructure

This repository contains Terraform configurations for setting up and managing AWS infrastructure. The configuration files automate the creation of EC2 instances, S3 buckets, VPCs, and other AWS resources.

## Prerequisites

- Install [Terraform](https://www.terraform.io/downloads.html)
- AWS CLI configured with appropriate credentials
- S3 bucket for storing Terraform state

## Usage

1. Initialize Terraform:
    ```bash
    terraform init
    ```

2. Preview the changes:
    ```bash
    terraform plan
    ```

3. Apply the changes:
    ```bash
    terraform apply
    ```

## Example Configurations

- **main.tf** - Defines the main infrastructure components.
- **variables.tf** - Defines the variables used in the Terraform configuration.
- **outputs.tf** - Defines the output values from the Terraform deployment.

