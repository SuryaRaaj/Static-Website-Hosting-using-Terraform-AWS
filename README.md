# Realtime DevOps Project: Automated Static Website Hosting with Terraform and AWS

## Overview
This project demonstrates how to automate the process of setting up static website hosting using Terraform and AWS Cloud. The setup leverages Infrastructure as Code (IaC) principles to provision and manage the necessary resources, such as S3 buckets for hosting, CloudFront for CDN, and Route 53 for DNS management.

## Key Components
- **Terraform**: Used to define, provision, and manage the AWS resources required for the static website.
- **AWS S3**: Serves as the storage and hosting platform for the static website.
- **AWS CloudFront**: Provides CDN functionality to ensure faster content delivery.
- **AWS Route 53**: Manages domain names and DNS settings for the website.
  
## Project Structure
- `/terraform` - Terraform configuration files to automate the AWS infrastructure setup.
- `/website` - Static website files to be hosted (HTML, CSS, etc.).

