Project Name: DynamoDB Creation using Terraform

Introduction
This project demonstrates how to use Terraform to create a DynamoDB table on AWS. DynamoDB is a fully managed NoSQL database service that provides fast and predictable performance with seamless scalability.

Prerequisites
Before you begin, ensure you have the following:
- [Terraform](https://learn.hashicorp.com/tutorials/terraform/install-cli) installed on your local machine.
- AWS credentials configured on your local machine. You can set this up using the AWS Command Line Interface (CLI) with the `aws configure` command.

Setup Instructions
Step 1: Install Terraform
Follow the installation guide for your operating system to install Terraform: [Install Terraform](https://learn.hashicorp.com/tutorials/terraform/install-cli).

Step 2: Configure AWS Credentials
Set up your AWS credentials on your local machine using the AWS CLI:
Type aws configure and configure it appropriately with your credentials

Step 3: Create a Terraform Directory
Create a new directory on your local machine where you will store your Terraform configuration files:
mkdir terraform-dynamodb
cd terraform-dynamodb

Step 4: Create a Terraform Configuration File
Create a new file in your Terraform directory called `main.tf`. This file will contain the configuration for your DynamoDB table.

Step 5: Define the AWS Provider
In your `main.tf` file, define your AWS provider. This tells Terraform which AWS region to use and which AWS credentials to use. 

Step 6: Define the DynamoDB Table
To create a DynamoDB table, define the attributes and settings such as name, hash key, range key, read capacity, write capacity, etc. Add the following code to your `main.tf` file:

Step 7: Initialize Terraform
Initialize the working directory and download the required plugins:
Run “terraform init”

Step 8: Preview Changes
Run `terraform plan` to preview the changes that will be made

Step 9: Apply Changes
Run `terraform apply` to create the DynamoDB table:

10. Conclusion
By following these steps, you will successfully create a DynamoDB table using Terraform. This setup provides a scalable and manageable way to configure your DynamoDB resources.

This project was done in collaboration with other group members and their names is as follows
David
Janet
Ayobami
Yaw
Faith
Reginald
Brian
Naomi
Bargotio
