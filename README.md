# AWS_terraform_ansible_single_vyos_instance
How to create a single instance and install your configuration using Terraform+Ansible+AWS 
Step by step:
# AWS
1. Create an account with AWS and get your "access_key", "secret key"
2. Create a key pair and download your .pem key
3. Create a security group for the new VyOS instance
# Terraform
1. Create a UNIX or Windows instance
2. Download and install Terraform
3. Create the folder for example ../awsvyos/
4. Copy all files from my folder /Terraform into your Terraform project (vyos.tf, var.tf)
5. Type the commands : #cd /your folder #terraform init
# Ansible


    
