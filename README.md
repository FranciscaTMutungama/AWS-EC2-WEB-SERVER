## Project: Launching and Managing an Amazon EC2 Instance

This project demonstrates my ability to launch, configure, and manage an Amazon EC2 instance using various AWS services. I performed tasks such as setting up a web server, managing network configurations, resizing the instance, and testing termination protection.

### **Project Overview**
- **Objective**: Launch a web server on AWS EC2, configure security settings, monitor the instance, and resize it to meet changing requirements.
- **Skills Demonstrated**: Cloud computing, network security, automation (User Data scripts), monitoring, and instance management.
- **Technologies Used**: AWS EC2, Amazon Linux 2, VPC, EBS, CloudWatch.


### **Task 1: Launching the EC2 Instance**

1. **Launch Instance**:
   - Launched an EC2 instance in the AWS Management Console.

2. **Name and Tags**:
   - Named the instance "Web Server.
 - Selected the default Amazon Linux 2 AMI.

3. **Choose Instance Type**:
   - Chose `t3.micro` for a balance between performance and cost.

4. **Configure Network Settings**:
   - Selected "Lab VPC" and configured a security group named "Web Server security group."
     
5. **Storage and Advanced Settings**:
   - Enabled termination protection and added a User Data script to install and start an Apache web server.

   **Screenshot**
     ![ec2-web-server](screenshots/ec2-webserver.png)

### **Task 2: Monitoring the EC2 Instance**

1. **Status Checks and Monitoring**:
   - Verified system and instance status checks using AWS CloudWatch.
   - **Screenshot**:
     ![Monitoring Dashboard](screenshots/monitoring-dashboard.png)

### **Task 3: Access the Web Server**

1. **Security Group Update**:
   - Updated the security group to allow HTTP traffic on port 80.
   - **Screenshot**:
     ![Updated Security Group](screenshots/updated-security-group.png)

2. **Access the Web Server**:
   - Accessed the web server using the public IP address, confirming the display of "Hello From Your Web Server!"
   - **Screenshot**:
     ![Web Server Access](screenshots/web-server-access.png)

### **Task 4: Resizing the Instance**

1. **Stop the Instance and Change Instance Type**:
   - Changed the instance type from `t3.micro` to `t3.small`.
   - **Screenshot**:
     ![Change Instance Type](screenshots/change-instance-type.png)

2. **Resize EBS Volume**:
   - Increased the root volume from 8 GiB to 10 GiB.
   - **Screenshot**:
     ![Resize EBS Volume](screenshots/resize-ebs-volume.png)

### **Task 5: Test Termination Protection**

1. **Termination Protection Test**:
   - Attempted to terminate the instance to test termination protection.
   - **Screenshot**:
     ![Termination Protection](screenshots/termination-protection.png)

---

### **Outcome and Reflection**

- **Outcome**: Successfully deployed and managed an EC2 instance, configured security groups, set up a web server, resized the instance, and utilized termination protection.
- **Learning Experience**: Gained hands-on experience in cloud infrastructure management, automated server configuration, and best practices for security in AWS.
- **Real-World Application**: These skills are essential for deploying scalable and secure applications in a cloud environment.

---

### **Summary**

This project illustrates the key skills required for cloud-based infrastructure management, including instance deployment, network configuration, security management, and system scaling. This hands-on experience reflects my capability to manage cloud resources efficiently, a crucial aspect for roles such as Solutions Architect or Cloud Engineer.

---

### **Technologies and Concepts Highlighted**

- **AWS Services**: EC2, VPC, Amazon Linux 2, EBS, CloudWatch.
- **Key Concepts**: Cloud computing, instance resizing, network security, web server configuration, automated provisioning (User Data), monitoring, and termination protection.

---

By presenting the project this way, you provide a comprehensive narrative that demonstrates your technical skills and understanding of AWS services. Including screenshots with captions makes the project more engaging and shows evidence of your hands-on work.
