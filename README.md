# IAAC-Terraform-AWS
Terraform is an open-source infrastructure as code (IaC) tool that can be used with AWS to manage cloud infrastructure.Terraform can automate many tasks, such as creating, changing, and versioning cloud resources. 

![BluePrint](https://github.com/user-attachments/assets/4c77baaf-b186-4ef5-a2be-c4bef62ba89f)


Basically we will be having a VPC(virtual private cloud) created through AWS Cloud Distribution.
In VPC we Create Two public subnets of same regions and this vpc is connected to Internet gateway and we are deploying an static application which include simple context only used for checking of Service.
All the information related to code is stored in S3 Storage service.


## Breif Process

### I done everything by following the Terraform Official Documentation Website.
We Login through IAM User and we configure the AWS with Bash Shell or any other CLI. 
Create and file and open with any code editor(I choosed VSCode).
Created a Provider.tf for basic boiler plate regarding the region to be used and hashicorp sources.
Created a variable.tf for using variables directly which includes the VPC CIDR Range.
Created a main.tf file which has all the configuration to Automate the Process through Terraform.
In the main.tf file, it consists of Information related to 
## Subnet1
## Subnet2
## AWS internet gateway
## Route tables for each subnet
## Security Resource group for VPC with Two Ingress(SSH, HTTP) and Engress
## S3 Storage Bucket
## TWo EC2 Instances or Web Services with Static application code(userdata, userdata2)
## Target Groups 
## Load Balancers

