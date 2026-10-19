# ☁️ AWS Cloud Computing – Complete Practical Guide

Welcome to my AWS Cloud Computing practical repository! 🚀

This repository contains hands-on labs, configuration guides, and practical documentation covering essential Amazon Web Services (AWS) cloud services, including Compute, Networking, IAM, Storage, Databases, Monitoring, Security, Backup, and Automation.

It is designed for cloud computing students, AWS beginners, system administrators, cloud engineers, and DevOps learners who want to develop practical AWS skills and prepare for AWS certifications.

## 📚 Topics Covered

### 1. AWS Compute Services – Amazon EC2
Learn how to deploy, configure, secure, and manage virtual servers in AWS.

- Launch Linux and Windows EC2 instances.
- Select AMIs, instance types, and key pairs.
- Configure security groups and instance access.
- Understand user data and EC2 instance metadata.
- Stop, start, reboot, and terminate instances.
- Attach and detach EBS volumes.
- Create EBS snapshots and restore volumes.
- Configure Elastic IP addresses.
- Create AMIs from EC2 instances.
- Configure Launch Templates and Auto Scaling Groups.
- Deploy applications using EC2.

### 2. AWS Networking – Amazon VPC
Understand AWS networking and how cloud resources communicate securely.

- Create VPCs and subnets.
- Configure CIDR blocks and IP addressing.
- Create public and private subnets.
- Configure Internet Gateways.
- Configure route tables and routes.
- Understand NAT Gateways and outbound connectivity.
- Configure security groups and network ACLs.
- Deploy EC2 instances in public and private subnets.
- Configure VPC peering.
- Understand VPC endpoints.
- Explore Site-to-Site VPN and AWS Direct Connect.
- Configure Application and Network Load Balancers.
- Understand Route 53 DNS and routing policies.

### 3. AWS IAM – Identity and Access Management
Learn how to manage identities, permissions, and secure access to AWS resources.

- Understand the AWS account root user.
- Create IAM users and groups.
- Create and attach IAM policies.
- Configure permissions using least privilege.
- Understand managed and inline policies.
- Create IAM roles for AWS services.
- Configure role-based access.
- Enable multi-factor authentication (MFA).
- Understand access keys and their secure management.
- Configure password policies.
- Analyze access activity using CloudTrail.
- Understand IAM Identity Center and federation.

**Best practice:** Use the root user only for tasks that specifically require it, enable MFA, and prefer IAM roles or temporary credentials over long-lived access keys.

### 4. AWS Storage Services

#### Amazon S3
- Create and configure S3 buckets.
- Upload, download, and organize objects.
- Configure bucket policies and IAM permissions.
- Enable versioning and encryption.
- Configure lifecycle rules.
- Understand S3 storage classes.
- Configure replication and access logging.
- Manage public access restrictions.
- Understand presigned URLs and S3 access points.

#### Amazon EBS
- Create and attach EBS volumes.
- Initialize and format additional disks.
- Extend supported filesystems.
- Create and restore snapshots.
- Configure encryption.
- Understand volume types and performance.

#### Amazon EFS
- Create shared file storage.
- Configure mount targets.
- Access EFS from Linux EC2 instances.
- Understand file-system access controls.

### 5. AWS Database Services

#### Amazon RDS
- Understand managed relational databases.
- Create an RDS database instance.
- Explore MySQL and PostgreSQL options.
- Configure database subnets and security groups.
- Connect securely from an EC2 instance.
- Create databases, tables, and database users.
- Configure automated backups and snapshots.
- Understand Multi-AZ deployments.
- Explore read replicas and database monitoring.
- Apply database access and security best practices.

#### Amazon DynamoDB
- Understand NoSQL database concepts.
- Create DynamoDB tables.
- Configure partition keys and sort keys.
- Insert, retrieve, update, and delete items.
- Understand Query and Scan operations.
- Configure indexes.
- Explore on-demand and provisioned capacity.
- Configure point-in-time recovery and backups.
- Access DynamoDB securely using IAM
