# AWS Three Tier Web Architecture Workshop

This project is based on an AWS workshop and implements a three-tier web architecture. The project sets up a scalable and highly available web application using AWS services like VPC, EC2, RDS, S3, and ELB. Link of the workshop : [Link](https://catalog.us-east-1.prod.workshops.aws/workshops/85cd2bb2-7f79-4e96-bdee-8078e469752a/en-US)


## Table of Contents
1. [Project Overview](#project-overview)
2. [Architecture](#architecture)
3. [Prerequisites](#prerequisites)
4. [Deployment](#deployment)

## Project Overview
This project follows AWS best practices for deploying a three-tier architecture in a cloud environment. It consists of:
- **Web Tier (Frontend)**: Hosted on an EC2 instance behind an ELB.
- **Application Tier (Backend)**: Running on multiple EC2 instances.
- **Database Tier**: Amazon RDS Aurora for relational database management.

## Architecture
The architecture consists of the following key components:
- **VPC**: For networking and isolating resources.
- **EC2 Instances**: For hosting the web application and backend services.
- **Elastic Load Balancer (ELB)**: To distribute incoming traffic across EC2 instances.
- **Amazon RDS**: For relational database storage.
- **S3**: For static content storage.

Architecture Diagram

![image](https://github.com/user-attachments/assets/f161ba5e-3ecf-45ac-9359-c099f2e58c66)


## Prerequisites
- Basic knowledge of AWS services (VPC, EC2, RDS, S3).
- AWS account with administrative access.

## Deployment
Follow the detailed instructions in the workshop guide to manually create the AWS components (VPC, EC2, RDS, S3, ELB).
Deploy your web application and set up the necessary security configurations.
