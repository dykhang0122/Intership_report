---
title: "Worklog"
date: 2026-04-17
weight: 1
chapter: false
pre: " <b> 1. </b> "
---

Throughout the First Cloud Journey internship program, I have documented my progress and the knowledge accumulated each week. Below is a summary of the tasks performed over the 12 weeks:

#### **[Week 1 (04/17/2026 – 04/23/2026)](1.1-week1/)**
- Create an AWS account and explore core services (Compute, Storage, Networking, Database).
- Practice account management, set up IAM Users/Groups/Policies, and assign permissions based on Least Privilege principles.
- Set up AWS Budgets and Cost Explorer to monitor, manage, and alert on cloud expenditure.

#### **[Week 2 (04/24/2026 – 04/30/2026)](1.2-week2/)**
- Learn AWS VPC networking architecture, create Public/Private Subnets and layered Route Tables.
- Practice configuring Internet Gateway, NAT Gateway for Private Subnets, and Site-to-Site VPN for on-premises connectivity.
- Configure network-level security with Security Groups (stateful) and Network ACLs (stateless).

#### **[Week 3 (05/01/2026 – 05/07/2026)](1.3-week3/)**
- In-depth study of Amazon EC2 (Instance Types, AMIs, Key Pairs, Server Lifecycle).
- Practice creating EC2 Linux virtual machines, configuring EBS volume storage, and setting up automated Backup/Snapshot mechanisms.
- Install and configure basic Web Server applications (Nginx/Apache) on EC2 to host test websites.

#### **[Week 4 (05/08/2026 – 05/14/2026)](1.4-week4/)**
- Connect VS Code to EC2; test and analyze network connection flows using AWS VPC Reachability Analyzer.
- Manage secure server administration without public SSH ports using EC2 Instance Connect Endpoint and SSM Session Manager.
- Install CloudWatch Agent to monitor system metrics (CPU, RAM, Disk) and configure automated CloudWatch Alarms.

#### **[Week 5 (05/15/2026 – 05/21/2026)](1.5-week5/)**
- Learn Docker fundamentals, container packaging workflows, and writing optimized Dockerfiles.
- Build, manage, and store Docker Images on Amazon ECR (Elastic Container Registry).
- Deploy and run containerized test applications on Amazon Lightsail Containers.

#### **[Week 6 (05/22/2026 – 05/28/2026)](1.6-week6/)**
- Study Microservices architecture and serverless container operations on AWS Fargate, Amazon ECS/EKS.
- Set up automated CI/CD pipelines using AWS CodePipeline integrated with GitHub to automatically build to ECR and deploy to ECS/Fargate.
- Configure resource monitoring with Container Insights and establish security policies for container environments.

#### **[Week 7 (05/29/2026 – 06/04/2026)](1.7-week7/)**
- Learn to build RESTful and GraphQL APIs using AWS Lambda and API Gateway.
- Explore object storage with Amazon S3 and NoSQL database management with Amazon DynamoDB for Serverless apps.
- Practice secure user authentication and authorization using Amazon Cognito User Pools and Identity Pools.

#### **[Week 8 (06/05/2026 – 06/11/2026)](1.8-week8/)**
- Research Amazon Bedrock, RAG (Retrieval-Augmented Generation) architectures, and Amazon Textract document data extraction.
- Write a detailed Project Proposal document for the capstone project: AI Invoice Scanner (Automated invoice processing system).
- Translate and study technical blog posts on cloud sustainability (AWS Carbon Footprint, BYOL).

#### **[Week 9 (06/12/2026 – 06/18/2026)](1.9-week9/)**
- Build an automated processing workflow: Upload invoice to S3 -> Lambda triggers Textract to extract text -> Bedrock standardizes data -> Save into DynamoDB.
- Design overall system architecture diagrams and sequence diagrams using Draw.io.
- Write technical documentation, deployment guides, and document IAM, S3, and Lambda configurations on Notion.

#### **[Week 10 (06/19/2026 – 06/25/2026)](1.10-week10/)**
- Learn Data Governance principles (access control, data security, and encryption policies).
- Connect extracted invoice data from DynamoDB to Amazon QuickSight.
- Build interactive QuickSight Dashboards to visualize invoice data, expense trends, and key analytical metrics.

#### **[Week 11 (06/26/2026 – 07/02/2026)](1.11-week11/)**
- Optimize AWS Lambda source code (memory tuning, timeout configuration, reducing execution time and costs).
- Perform end-to-end Integration Testing across the system and fix operational bugs.
- Finalize technical report documentation and capture screenshots of AWS Console configurations.

#### **[Week 12 (07/03/2026 – 07/09/2026)](1.12-week12/)**
- Finalize all deliverables for the final internship report (report documents, presentation slides, demo video).
- Evaluate and summarize the overall internship progress and document key learnings.
- Clean up and delete all initialized AWS resources to avoid post-internship charges.

