# AWS-WEB-APPLICATION
##AWS web app project - LITA
*Building a Scalable Web Infrastructure for "SmartShop"*

# SmartShop Web Infrastructure Setup

## Background

### Company Overview
SmartShop is a fictional mid-sized retail company that is expanding into online sales. To handle anticipated increases in web traffic due to marketing and seasonal campaigns, SmartShop needs a robust and scalable web infrastructure. The solution should be cost-effective, high-performing, and easy to manage, given the company's limited IT resources.

## Project Objective
The objective is to design and deploy a reliable web application infrastructure on AWS that:
- Supports flexible resource allocation for growth.
- Ensures high availability and a consistent user experience.
- Implements strong security measures to protect customer data.
- Remains cost-effective and optimized for performance.

## Your Mission
As a cloud engineer, my task is to leverage AWS services like EC2, VPC, and IAM to meet SmartShop's requirements.

## Project Tasks

### 1. Launch EC2 Instances to Host the Web Application

#### Set Up the Application Environment
- **Chose an Amazon Machine Image (AMI)**: Use Amazon Linux 2 as the base image.
- **Launch EC2 Instances**: Deploy instances in the designated VPC and subnets.
- **Install and Configure Apache**: Set up Apache
- **Deploy Web Application**: Upload SmartShop's web application code (HTML, PHP, or Node.js).

#### Access and Connectivity
- **SSH Access**: Ensure instances are accessible via SSH for management.
- **Web Application Access**: Verify the web application is reachable through a browser.

### 2. Set Up a Virtual Private Cloud (VPC)

#### Design the Network Architecture
- **Create a New VPC**: Host the SmartShop infrastructure within this VPC.
- **Public and Private Subnets**: Divide the VPC into public and private subnets across multiple Availability Zones for redundancy.

#### Configure Networking Components
- **Internet Gateways**: Set up to allow public subnets internet access.
- **Route Tables**: Manage traffic flow between subnets and the internet.

### 3. Configure Security Groups

#### Security Groups
- **Create Security Groups**: Control inbound and outbound traffic to EC2 instances.
  - Allow HTTP (port 80) and HTTPS (port 443) traffic from the internet.
  - Restrict SSH (port 22) access to specific IP addresses.

### 4. Implement Security Best Practices

#### Network Security
- **Network Access Control Lists (NACLs)**: Use for an additional layer of subnet-level security.

### 5. Enable Monitoring and Logging

#### Monitoring with CloudWatch
- **Collect Key Metrics**: Monitor CPU utilization, network traffic, and disk I/O.
- **Set Up Alarms**: Configure CloudWatch Alarms to notify the team of critical events.

#### Logging
- **AWS CloudTrail**: Enable to record AWS API calls for auditing and compliance.

## Setup Instructions

1. **Create AWS Account**: If you don't have one, sign up for an AWS account.
2. **Install AWS CLI**: Ensure the AWS Command Line Interface is installed and configured with your credentials.
3. **Create VPC**:
   - Use the AWS Management Console or CLI to create a new VPC.
   - Create public and private subnets as per the design.

4. **Launch EC2 Instances**:
   - Choose the AMI, instance type, and configure security groups during the setup.
   - Install the web server and deploy the application code.

5. **Configure Networking**:
   - Attach an Internet Gateway to the VPC and configure route tables.

6. **Set Up Monitoring and Logging**:
   - Enable CloudWatch monitoring and set up necessary alarms.
   - Activate CloudTrail for logging AWS API calls.

## Conclusion
This README provides a comprehensive overview of setting up a scalable web infrastructure for SmartShop on AWS. Follow the instructions carefully to ensure a successful deployment.



<img width="957" alt="2024-12-10_22h20_04" src="https://github.com/user-attachments/assets/6ae7a10a-9f0e-444c-88c5-b860fe15227a">

<img width="959" alt="image" src="https://github.com/user-attachments/assets/a70dbd30-2eb1-4e64-92af-ab35f8f0c70f">

<img width="958" alt="image" src="https://github.com/user-attachments/assets/c34bd843-4ea6-43c2-a836-d7290eb3ac6a">




