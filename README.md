# aws-certification-reference

## What is Cloud Computing?

- Cloud computing is the on-demand delivery of compute power, database storage, applications, and other IT resources
- Pay-As-You-Go Pricing
- Can provision exactly the right type and size of computing resources you need

## Deployment Models of the cloud

### Private Cloud

- cloud services used by a single organization, not exposed to public
- complete control
- security for sensitive applications
- meet specific business needs

### Public Cloud

- cloud resources owned and operated by a third-party cloud service provider delievered over the internet

### Hybrid Cloud

- keep some servers on premises and extend some capabilities to the cloud
- control over sensitive assets in your private infrastructure
- flexibility and cost-effectiveness of the public cloud

## The Five Characteristics of Cloud Computing

### On-demand self service

- users can provision resources and use them without human interaxction from the service provider

### Broad network access

- resources available over the network, and can be accessed by diverse client platforms

### Multi-tenancy and resource pooling

- multiple customers can share the same infrastructure and applications with security and privacy
- multiple customers are serviced from the same physical resources

### Rapid elasticity and scalability

- automatically and quickly acquire and dispose resources when needed
- quickly and easily scale based on demand

### Measured service

- usage is measured, users pay correctly for what they have used

## Six Advantages of Cloud Computing

- trade capital expense (CAPEX) for operational expence (OPEX)

  - pay on-demand: don't own hardware
  - reduced total cost of ownership (TCO) & Operational Expense (OPEX)

- Benefit from massive economies of scale
  - prices are reduced as AWS is more efficient due to large scale
- Stop guessing capacity
  - scale based on actual measured usage
- Increase speed and ability
- Stop spending money running and maintaining data centers
- Go global in minutes: leverage the AWS global infrastructure

## Problems solved by the Cloud

- Flexibility: change resource types when needed
- Cost-Effectiveness: pay as you go, for what use
- Scalability: accomodate larger loads by making hardware stronger or adding additional nodes
- Elasticity: ability to scale out and scale-in when needed
- High-availability and fault-tolerance: build across data centers
- Agility: rapidly develop, test and launch software applications

## Types of Cloud Computing

- Infrastructure as a Service (IaaS)
  - provide building blocks for cloud IT
  - provides networking, computers, data storage space
  - highest level of flexibility
  - easy parallel with traditional on-premise IT
- Platform as a service (PaaS)
  - removes the need for your organization to manage the underlying infrastructure
  - focus on the deployment and management of your applications
- Software as a Service (SaaS)
  - completed product that is run and managed by the service provider

## Example of Cloud Computing Types

- Infrastructure as a Service:
  - Amazon EC2 (AWS)
  - GCP, Azure, Rackspace, Digital Ocean, Linode
- Platform as a Service:
  - Elastic Beanstalk (AWS)
  - Heroku, Google App Engine, Windows Azure
- Software as a Service:
  - Many AWS services

## Pricing of the Cloud -- Quick Overview

- AWS has 3 pricing fundamentals (pay-as-you-go)
  - Compute:
    - pay for compute time
  - Storage:
    - pay for data stored
  - Data transfer OUT of the cloud
    - data transfer IN is free
- solves the expensive issue of traditional IT

## AWS Cloud Number Facts

- In 2019, AWS had $35.02 billion in annual revenue
- AWS accounts for 47% of the market (Microsoft 2nd at 22%)
- Pioneer and Leader of the AWS Cloud Market for the 9th consecutive year
- Over 1,000,000 active users

## Use Cases

- AWS enables you to build sophisticated, scalable applications
- applicable to a diverse set of industries
- use cases include:
  - enterprise IT, backup & storage, big data analytics
  - host websites, mobile & social apps
  - gaming

## Global Infrastructure

- Regions
- Availability Zones
- Data Centers
- Edge Locations / Points of Presence

## Regions

- a region is a cluster of data centers
- most AWS services are region-specific

### How to choose an AWS Region?

- compliance with data governance and legal requirements: data leaves a region without your explicit permission

- proximity to customers: reduced latency

- available services: within a Region: new services and new features aren't available in every Region

- pricing: pricing varies region to region and is transparent in the service pricing page

## Availability Zones

- each region has many availability zones (avg 3, min 2, max 6)
- each availability zone is one or more discrete data centers with redundant power, networking and connectivity
- seperate from each other, isolated from disasters

## Point of Presence

- Amazon has 216 POP (205 edge locations & 11 regional caches) in 84 cities across 42 countries

### Example Global and Regional Services

- Global:

  - IAM
  - Route 53 (DNS service)
  - Cloudfront (CDN)
  - WAF (Web Application Firewall)

- Region-scoped:

  - EC2 (IaaS)
  - Elastic Beanstalk (PaaS)
  - Lambda (FaaS)
  - Rekognition (SaaS)

## Shared Responsibility Model

- Customer is responsible for security in the cloud
- AWS is responsible for security of the cloud

## Acceptable Use Policy

- no illegal, harmful, or offensive use or content
- no security violations
- no network abuse
- no e-mail or other message abuse

## IAM: Users & Groups

- IAM = identity and access managment, global service
- root account created by default shouldn't be used or shared
- users are people within your organization and can be grouped
- groups only contain users not other groups
- users can belong to multiple groups

## Permissions

- users or groups can be assigned JSON documents called policies
- policies define permissions of users
- least privilege principle: don't give more permissions than a user needs

## Password Policy

- in aws you can setup a password policy:
  - set min length
  - require specific character types
- allow all IAM users to change their own passwords
- require users to change their password after some time
- prevent password re-use

## Multi Factor Authentication

- protect root and IAM users
- MFA = password + security device

## EC2

- EC2 is one of the most popular of the AWS offerings
- main consists in the capability of:
  - renting VMs (EC2)
  - storing data on virtual drives (EBS)
  - distributing load across machines (ELB)
  - scaling th services using an auto-scaling group (ASG)
