# List of features

We can install the following features in our code space.

https://containers.dev/features

## To install terraform

# downloads the latest terraform file
wget https://releases.hashicorp.com/terraform/$(curl -s https://checkpoint-api.hashicorp.com/v1/check/terraform | jq -r .current_version)/terraform_$(curl -s https://checkpoint-api.hashicorp.com/v1/check/terraform | jq -r .current_version)_linux_amd64.zip
# unzip the latest zip file
unzip terraform_*.zip
# Move the Terraform binary to a directory in your PATH
sudo mv terraform /usr/local/bin/
# verify the installation 
terraform --version

