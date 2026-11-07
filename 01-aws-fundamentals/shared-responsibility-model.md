# AWS Shared Responsibility Model

## What Is the AWS Shared Responsibility Model?

The AWS Shared Responsibility Model explains how security and compliance responsibilities are divided between AWS and the customer.

AWS is responsible for security **of** the cloud, while customers are responsible for security **in** the cloud.

## 1. AWS Responsibility — Security of the Cloud

AWS manages and protects the underlying cloud infrastructure.

This includes:

- Physical data centers
- Physical servers
- Hardware
- Networking infrastructure
- Facilities and physical access controls
- Infrastructure that supports AWS services

## 2. Customer Responsibility — Security in the Cloud

Customers are responsible for securing the resources and workloads they configure and use in AWS.

This can include:

- IAM users, roles, and permissions
- Data and data encryption choices
- Operating system updates on EC2
- Application security
- Security group configuration
- Network configuration
- Passwords and credentials
- Backups and access controls, depending on the service

## Example: EC2

When using Amazon EC2:

| AWS Responsibility | Customer Responsibility |
|---|---|
| Physical data center security | Configure EC2 security groups |
| Physical server hardware | Manage the guest operating system |
| Underlying infrastructure | Apply OS patches and updates |
| Physical networking infrastructure | Secure applications and data |

## Example

If you launch a Windows EC2 instance:

- AWS manages the physical server and data center.
- You manage Windows updates and the software installed on the instance.
- You configure security groups to control network access.
- You protect credentials and application data.

## Why Is This Model Important?

It helps customers understand which security tasks they must perform and which tasks AWS manages.

Using AWS does not mean AWS automatically handles every security responsibility.

## Interview Questions

### Q1. What is the AWS Shared Responsibility Model?

It explains how AWS and customers divide security responsibilities. AWS is responsible for security of the cloud, while customers are responsible for security in the cloud.

### Q2. What does security of the cloud mean?

It refers to AWS protecting the underlying infrastructure, including physical data centers, hardware, and infrastructure networking.

### Q3. What does security in the cloud mean?

It refers to the customer's responsibility for securing resources, data, permissions, operating systems, and applications according to the AWS service being used.

### Q4. Who manages operating system updates on EC2?

For EC2, the customer is generally responsible for managing the guest operating system and its updates.

## Revision

- AWS = Security of the cloud.
- Customer = Security in the cloud.
- EC2 customer responsibilities include OS updates, application security, data, and security group configuration.
- Responsibilities vary depending on the AWS service.

