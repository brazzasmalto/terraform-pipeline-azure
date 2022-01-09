# How to create AKS cluster using Terraform
Pre-requistes: 
    Terraform is installed on the client.
    Account setup in Azure.
    Kubectl is installed on the client.
    Azure cli is installed.


Login to Azure using credentials

Make sure you are login to Azure portal first.

az login

Choose your Microsoft credentials. 

Let's create following tf files using Visual studio Code:
1. Variables.tf - where we will define the variables used in main.tf
2. terraform.tfvars - Declare the values for the variables
3. providers.tf - declare the providers with version
4. main.tf - main configuration file with all the resources which will be created
5. output.tf - Export some data to output file
