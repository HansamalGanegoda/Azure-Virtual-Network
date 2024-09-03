# Azure Virtual Network with Terraform

This repository contains a Terraform configuration to create an Azure Virtual Network (VNet) and a subnet within it.

## Overview

This project deploys:
- An Azure Resource Group.
- An Azure Virtual Network.
- A Subnet within the Virtual Network.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Terraform](https://www.terraform.io/downloads.html) - Infrastructure as code tool for managing cloud resources.
- [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli) - Command-line tool to interact with Azure services.

## Getting Started

Follow these steps to deploy your Azure Virtual Network using Terraform.

### 1. Clone the Repository

Clone the repository to your local machine and navigate into the project directory:


git clone https://github.com/HansamalGanegoda/Azure-Virtual-Network.git
cd Azure-Virtual-Network

### 2. Configure Azure Credentials
Ensure you are logged in to Azure CLI:
az login

### 3. Initialize Terraform
Initialize the Terraform configuration. This command sets up Terraform and downloads the required provider plugins:
terraform init

### 4. Review the Terraform Plan
Preview the changes Terraform will make. This command shows what will be created, modified, or destroyed:
terraform plan

### 5. Apply the Configuration
Create the resources by applying the Terraform configuration. You will be prompted to confirm the action. Type yes to proceed:
terraform apply

### 6. Verify Deployment
Check the Azure Portal or use Azure CLI to verify that the Virtual Network and Subnet have been created successfully.

### 7. Clean Up (Optional)
To delete the resources created by Terraform, use the following command. Confirm the deletion by typing yes:
terraform destroy
