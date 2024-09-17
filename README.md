### Project: Launching and Managing an Amazon EC2 Instance

This project involves launching, configuring, and managing an Amazon EC2 instance using various AWS services and features. Below is a summary of the steps taken:

---

#### **Task 1: Launching the EC2 Instance**
1. **Launch Instance**:
   - In the EC2 Dashboard, selected "Launch Instance."
2. **Name and Tags**:
   - Named the instance "Web Server."
3. **Select AMI**:
   - Chose the default Amazon Linux 2 AMI.
4. **Choose Instance Type**:
   - Selected `t3.micro` as the instance type.
5. **Key Pair**:
   - Chose to proceed without a key pair (as login was not required).
6. **Configure Network Settings**:
   - Edited network settings, selected "Lab VPC," and configured a security group named "Web Server security group."
   - Removed SSH access for security.
7. **Storage**:
   - Kept the default storage configuration (8 GiB).
8. **Advanced Settings**:
   - Enabled termination protection.
   - Added a User Data script to install and start an Apache web server.
9. **Launch Instance**:
   - Launched the instance and verified its status.

#### **Task 2: Monitor the EC2 Instance**
1. **Status Checks**:
   - Verified that both system and instance status checks passed.
2. **Monitoring**:
   - Reviewed basic CloudWatch metrics.
   - Captured an instance screenshot for troubleshooting purposes.

#### **Task 3: Access the Web Server**
1. **Security Group Update**:
   - Added an inbound rule to the security group to allow HTTP traffic on port 80.
2. **Access Web Server**:
   - Used the instance's public IPv4 address to access the web server and confirmed the display of the message "Hello From Your Web Server!"

#### **Task 4: Resize the Instance**
1. **Stop the Instance**:
   - Stopped the instance to modify its settings.
2. **Change Instance Type**:
   - Changed the instance type from `t3.micro` to `t3.small`.
3. **Resize EBS Volume**:
   - Modified the root EBS volume size from 8 GiB to 10 GiB.
4. **Start the Instance**:
   - Restarted the instance to apply the changes.

#### **Task 5: Test Termination Protection**
1. **Attempt to Terminate**:
   - Tried to terminate the instance but was prevented due to termination protection.
2. **Disable Termination Protection**:
   - Disabled termination protection in the instance settings.
3. **Terminate the Instance**:
   - Successfully terminated the instance after disabling termination protection.

---

### **Outcome**
- Successfully launched, configured, and managed an EC2 instance.
- Set up a simple web server, adjusted security settings, resized the instance, and tested termination protection.

### **Screenshots**
()

### **Technologies Used**
- **AWS Services**: EC2, Amazon Linux 2, EBS, VPC, CloudWatch
- **Concepts**: Instance launch, storage, network configuration, security groups, resizing instances, termination protection, and monitoring.

