# Common AWS Services

## What is AWS?

- Cloud Service Provider that allow everyone to access and use computing resources over the internet.
- Eliminates maintaining own physical servers and infra.
- Use AWS to rent servers, storage , db etc on pay as you go basis.
- Contains more than 200 Services.

> Common Services that you should know about!!!

## EC2

- Provides Server facility in the cloud that allow us to deploy, run ,host websites without the need of any hardware.

## VPC

- Allows us to create our own virtual network within the AWS cloud. We can also configure and control the network setting such as IP addresses, subnets, routing tables, and gateways.

## S3

- S3 is a storage service that allows users to store and retrieve data in the cloud. We can keep any type of data, images, videos, docs, files etc. We can store everything in a "BUCKET", we can also add permission that who can modify or view the content inside the bucket.

## EBS Volumes

- It provides storage capacity just like a normal harddrive or SSD. It is a virtual harddrive that is attached to our EC2 instance. EC2 has a temporary storage its data is lost whenever the instance is terminated or stopped, we use EBS if we need storage that persists even after the instance is terminated or stopped. We can also attach the same EBS volume to other EC2 instance.

## IAM

- IAM service allows us to create and manage users, groups and roles and we define some permissions that contains what a user, group or role are allowed or denied to perform and access on AWS services. We never gave a user all the permissions, its preferred to give only access to those services that suits their profile role. Suppose there is team of developers and they need access to S3, EC2 and EBS services what we do we will create a group named as Developers and attach the polices to that group and add the users who are developers, in this way they can access or use what is required. IAM is a vital security feature in AWS that ensures the right people have the right access to your resources reduce the security issue, helping you maintain control over your cloud infrastructure.

## Cloudwatch

- Cloudwatch is used for monitoring and observability the AWS resources and applications by collecting and analyzing the logs, metrics. It not only maintain and monitors the logs, metrics but also set alarms when certain metric falls below or exceeds the threshold that we defined. It triggers notifications when certain behaviour arised. These logs provide detailed information about events and activities happening within your applications, helping you troubleshoot and debug potential problems. Suppose a Developer created a EBS volume without encryption, so if is there is compliance in that organistion that you cannot create ebs volume without encryption, then it will trigger an event (mail notification) asking the reason why he created this volume and gave the information about the compliance standards for creating S3 buckets in the organisation.

## LAMBDA

- AWS Lambda is a serverless computing platform that means it lets you run your code without managing any servers. This code is triggered in response to events, such as update in the db, change in S3 bucket etc. Whenever any event occurs, it quickly runs the code, processes the data and then stops. You are only charged for the time your code takes to execute, down to the millisecond. Lambda is very cost-effective and scalable. AS in the above cloudwatch example a developer created an unencrypted EBS volume, so in this case a lambda function is executed that will encrypt the EBS volume and then stops executing.

# AWS CodePipeline (Cloud Build Services)

# AWS CodeBuild (Cloud Build Services)

# AWS CodeDeploy (Cloud Build Services)

## KMS

## Certificate Management

## Cloud Trail

## EKS
