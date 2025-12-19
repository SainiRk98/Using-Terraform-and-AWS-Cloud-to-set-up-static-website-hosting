Static Website Hosting on AWS using Terraform:

Project Overview
This project demonstrates how to fully automate static website hosting on AWS using Terraform (Infrastructure as Code).
The website is hosted on Amazon S3 and deployed using Terraform with minimal manual effort.

The goal is to understand:
Infrastructure as Code (IaC)
Terraform workflow
AWS S3 static website hosting
DevOps automation concepts

Technologies Used:
Terraform
AWS Cloud
Amazon S3
IAM
Git & GitHub
AWS CLI

Features
Automated S3 bucket creation
Public access configuration for website hosting
Static website hosting enabled
Infrastructure provisioning using Terraform
Reproducible and scalable setup

Prerequisites
Before running this project, make sure you have:
AWS account
AWS CLI installed & configured
Terraform installed
Git installed

AWS Configuration
Configure AWS credentials:
aws configure

Terraform Workflow
Initialize Terraform:
terraform init
Validate configuration:
terraform validate
Preview infrastructure changes:
terraform plan
Apply changes (create resources):
terraform apply -auto-approve

Access the Website
After successful deployment, Terraform will output the S3 website URL.
Example:
http://my-static-site.s3-website-us-east-1.amazonaws.com
Open this URL in your browser to view the website.

Cleanup Resources
To destroy all created AWS resources:
terraform destroy -auto-approve

Learning Outcomes
Hands-on experience with Terraform
Understanding AWS S3 static website hosting
DevOps automation using Infrastructure as Code
Cloud resource management best practices

Future Enhancements
Add CloudFront CDN
Enable HTTPS using ACM
CI/CD pipeline using GitHub Actions
Custom domain with Route 53
