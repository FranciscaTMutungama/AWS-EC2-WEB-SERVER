# AWS-EC2-WEB-SERVER

A project demonstrating the launch of an Amazon EC2 instance, configuration of security groups, setup of a web server and resizing instance type

## Project Overview

- Objective: Launch an EC2 instance, configure security groups for HTTP and SSH access, and set up a simple web server.
- AWS Services Used: EC2, Security Groups
- Skills Demonstrated:
  - Launching and configuring an EC2 instance
  - Setting up security groups for secure access
  - Installing and running a web server (Apache) on the EC2 instance
  - Resizing Instance Type and EBS Volume

## Steps Followed

1. **Launch EC2 Instance:** 
    - Created an EC2 instance using the AWS Management Console with the Amazon Linux 2 AMI.
    -  - Selected an appropriate instance type (e.g., t2.micro) to stay within the free tier.
2. **Configure Security Groups:** 
    - Configured security groups to allow HTTP (port 80) and SSH (port 22) access to the instance.
3. **Connect to the Instance:** 
    - Used SSH to connect to the instance using the key pair created during the launch process.
4. **Install Web Server:** 
    - Updated the package manager and installed the Apache web server on the EC2 instance.
5. **Start the Web Server:** 
    - Started the Apache service and ensured it was running.
6. **Verify Web Server:** 
    - Accessed the web server using the instance's public IP address to verify the setup
