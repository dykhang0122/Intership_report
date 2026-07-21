---
title: "Week 6 Worklog"
date: 2026-05-22
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---
**Period:** 05/22/2026 – 05/28/2026

### Week 6 Objectives:

* Master Microservices architectural design, compare Amazon ECS launch types (EC2 vs serverless AWS Fargate), and study Amazon EKS (Kubernetes) orchestration.
* Build automated Continuous Integration & Continuous Deployment (CI/CD) pipelines using AWS CodePipeline and AWS CodeBuild integrated with GitHub repositories.
* Configure container monitoring via Amazon CloudWatch Container Insights and enforce container security policies using IAM Task Roles and AWS Secrets Manager.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Fri | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- ECS & Fargate Architecture:</b> Study Amazon ECS Cluster components, Task Definitions, Services, and serverless AWS Fargate</li><li><b>- EKS Overview:</b> Learn Amazon EKS concepts for managing production Kubernetes clusters</li></ul> | 05/22/2026 | 05/22/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Sat | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- ECS Cluster Setup:</b> Provision an Amazon ECS Cluster backed by AWS Fargate</li><li><b>- Task Definition Creation:</b> Write Task Definitions defining CPU, Memory, ECR container images, port mappings, and IAM Task Roles</li></ul> | 05/23/2026 | 05/23/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Sun | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- ECS Service Deployment:</b> Launch ECS Service maintaining active running Tasks linked to an Application Load Balancer (ALB)</li></ul> | 05/24/2026 | 05/24/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Mon | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- GitHub Integration:</b> Configure AWS CodeStar Connections to securely connect GitHub code repositories to AWS CodePipeline</li></ul> | 05/25/2026 | 05/25/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Tue | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- AWS CodeBuild Setup:</b> Author `buildspec.yml` to automate Docker builds, ECR authentication, image tagging, and pushing to ECR</li></ul> | 05/26/2026 | 05/26/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Wed | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Pipeline Completion:</b> Add ECS Deployment stage to CodePipeline to trigger rolling ECS updates on new GitHub commits</li><li><b>- CI/CD Testing:</b> Push code update to GitHub and verify automated pipeline triggers</li></ul> | 05/27/2026 | 05/27/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Thu | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Container Insights Monitoring:</b> Enable CloudWatch Container Insights tracking task-level CPU, Memory, and Network metrics</li><li><b>- Security & Secrets Management:</b> Inject secret environment variables from AWS Secrets Manager and complete Week 6 summary</li></ul> | 05/28/2026 | 05/28/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Week 6 Achievements:

* Deeply understood Microservices architecture and serverless container operations with AWS Fargate.
* Successfully built fully automated end-to-end CI/CD pipelines: GitHub commit -> AWS CodeBuild ECR push -> CodePipeline deployment to ECS Fargate.
* Configured full container observability with CloudWatch Container Insights and implemented secure secret injection using AWS Secrets Manager.
