# AWS 3-Tier Architecture

## Project Overview

Designed a highly available 3-Tier Architecture on AWS using
Web, Application, and Database tiers.

## AWS Services Used

- Amazon VPC
- Public and Private Subnets
- Internet Gateway
- Elastic Load Balancer (ELB)
- Amazon EC2
- Amazon Aurora
- Aurora Read Replica
- Availability Zones

## Architecture Flow

Internet
   ↓
Internet Gateway
   ↓
Elastic Load Balancer
   ↓
Web Tier - EC2
   ↓
App Tier - EC2
   ↓
Database Tier - Amazon Aurora

## Key Features

- 3-Tier Architecture
- Public and Private Subnet design
- High availability using multiple Availability Zones
- Load balancing using ELB
- Database isolation using private subnets
- Aurora Read Replica for read scalability

## What I Learned

- AWS VPC architecture
- Public vs Private Subnets
- EC2 deployment
- Load Balancing
- Database tier architecture
- AWS security and network design
- High Availability architecture
