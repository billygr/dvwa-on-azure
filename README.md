# dvwa-on-azure
Terraform setup for dvwa on Azure

# Requirements

- Terraform is installed and in the current \$PATH
- Azure cli tools are installed and in the current \$PATH (https://docs.microsoft.com/en-us/cli/azure/)
- Alternative you can run it directly from Azure shell

# Setup

Login to your azure infrastructure with az login

`terraform init`

`terraform plan`

`terraform apply`

ssh to your instance with ssh -i azureuser.pem azureuser@XXX you can find the IP from the running instance created
