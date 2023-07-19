> Common AWS Services

# What is AWS?

- Cloud Service Provider that allow everyone to access and use computing resources over the internet.
- Eliminates maintaining own physical servers and infra.
- Use AWS to rent servers, storage , db etc on pay as you go basis.
- Contains more than 200 Services.

> Common Services that you should know about!!!

\*\* Small Description of these services.

# EC2

- Provides Server facility in the cloud that allow us to deploy, run ,host websites without the need of any hardware.

# VPC

- Allows us to create our own virtual network within the AWS cloud. We can also configure and control the network setting such as IP addresses, subnets, routing tables, and gateways.

# EBS Volumes

- It provides storage capacity just like a normal harddrive or SSD. It is a virtual harddrive that is attached to our EC2 instance. EC2 has a temporary storage its data is lost whenever the instance is terminated or stopped, we use EBS if we need storage that persists even after the instance is terminated or stopped. We can also attach the same EBS volume to other EC2 instance.

# IAM

- IAM service allows us to create and manage users, groups and roles and we define some permissions that contains what a user, group or role are allowed or denied to perform and access on AWS services. We never gave a user all the permissions, its preferred to give only access to those services that suits their profile role. Suppose there is team of developers and they need access to S3, EC2 and EBS services what we do we will create a group named as Developers and attach the polices to that group and add the users who are developers, in this way they can access or use what is required. IAM is a vital security feature in AWS that ensures the right people have the right access to your resources reduce the security issue, helping you maintain control over your cloud infrastructure.

# Cloudwatch

# Cloud Build Services

# KMS

# Certificate Management

# Cloud Trail

# EKS
