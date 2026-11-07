# AWS Regions and Availability Zones

## What Is an AWS Region?

An AWS Region is a geographic area where AWS operates its infrastructure.

A Region contains multiple Availability Zones.

## What Is an Availability Zone (AZ)?

An Availability Zone is an isolated location within an AWS Region. AZs are designed to provide separation from other AZs.

## Region and AZ Relationship

```text
AWS Region (Example: Mumbai)
│
├── Availability Zone A
│   └── Isolated infrastructure
│
├── Availability Zone B
│   └── Separate infrastructure
│
└── Availability Zone C
    └── Separate infrastructure
```

A Region contains multiple Availability Zones. This structure helps customers design applications for availability and resilience.

## Why Does Region Selection Matter?

### 1. Latency

Choosing a Region closer to users can reduce network delay.

### 2. Cost

Prices for some AWS services vary by Region.

### 3. Compliance

Organizations may have legal or regulatory requirements about where their data is stored.

### 4. Availability

Using multiple Availability Zones can help design applications that continue operating if an individual AZ experiences a problem.

## Region vs Availability Zone

| AWS Region | Availability Zone |
|---|---|
| Geographic area. | Isolated location within a Region. |
| Contains multiple AZs. | Belongs to a Region. |
| Selected based on latency, cost, compliance, and service availability. | Used to improve application availability and resilience. |

## Important Interview Point

AWS resources such as EC2 instances are created in a particular Region. They do not automatically appear in every other Region.

## Interview Questions

### Q1. What is an AWS Region?

An AWS Region is a geographic area where AWS operates its infrastructure. We choose a Region based on latency, service availability, cost, and data requirements.

### Q2. What is an Availability Zone?

An Availability Zone is an isolated location within an AWS Region. Using multiple AZs can help improve application availability.

### Q3. Why do we choose a Region close to users?

A nearby Region can reduce network latency and improve response times.

### Q4. What is the difference between a Region and an AZ?

A Region is a geographic area, while an Availability Zone is an isolated location within that Region.

## Revision

- Region = Geographic area.
- AZ = Isolated location within a Region.
- Multiple AZs can help improve availability.
- Region selection affects latency, cost, compliance, and service availability.

