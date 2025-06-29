# projectk8s
# AWS EKS Cluster Setup Guide

This repository provides all the necessary resources to set up an AWS EKS Cluster using Terraform.  
**All detailed steps and commands are available in the file:**  
`AWS EKS Cluster Configuration, Setup & Deployment Steps.docx`

---

## How to Use

1. **Follow the Steps in the Document**

   - Open `AWS EKS Cluster Configuration, Setup & Deployment Steps.docx` located in this repository.
   - The document provides a step-by-step guide to provision an EKS cluster using the Terraform scripts in the `Terraform-Code` folder.

2. **Customize Cluster Settings**

   - Before applying Terraform, review the variables and configuration files inside the `Terraform-Code` directory.
   - Update the cluster name, AWS region, node group details, and any other settings to match your environment or requirements.

3. **Run Terraform Commands**

   Use the following commands inside the `Terraform-Code` folder to deploy your EKS cluster:

   ```sh
   terraform init
   terraform plan
   terraform apply
