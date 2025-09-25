# Terraform-Docker
Local Docker container using Terraform

prerequisites Install Terraform and Docker Desktop in your Machine Provide your code in main.tf make sure dosker is running to test the code

steps to configure docker through terraform terraform init #initializes the terraform terraform plan #gives overview plan to create terraform apply #apply the changes terraform destory #destroy the changes

#push your code by adding .gitignore file git rm --cached terraform.tfstate terraform.tfstate.backup git rm --cached -r .terraform/
