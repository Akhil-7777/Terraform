# Terraform Docker Container Project

## Objective
Provision a local Docker container using Terraform.

## Requirements
- Terraform installed
- Docker installed and running

## Usage
1. Initialize Terraform:
   ```bash
   terraform init
This will download the Docker provider plugin.

2. Review execution plan:
   ```bash
   terraform plan
This shows what resources will be created without actually creating them.

3. Apply configuration:
   ```bash
   terraform apply
Type "yes" when prompted to confirm the changes.

4. Verify the container is running:
   ```bash
   docker ps
You should see your nginx container running. You can also access it at http://localhost:8000.

5. Check Terraform state:
   ```bash
   terraform state list
This shows all resources managed by Terraform.

6. Destroy infrastructure when done:
   ```bash
   terraform destroy
Type "yes" when prompted to confirm.
   
   
