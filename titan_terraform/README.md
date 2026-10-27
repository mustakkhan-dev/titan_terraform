# titan_terraform

Terraform configuration to deploy an AWS EC2 instance inside the default VPC with a custom security group and SSH access enabled.

## Files included:
- `provider.tf`: AWS provider configuration and required version constraints.
- `variable.tf`: Input variables for AMI, instance type, and instance name.
- `main.tf`: VPC data source, security group, and EC2 instance resources.
- `output.tf`: Outputs for instance ID, private IP, and public IP.
