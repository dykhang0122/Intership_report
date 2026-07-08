---
title: "Week 6 Worklog"
date: 2026-05-22
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---
**Period:** 05/22/2026 – 05/28/2026

### Week 6 Objectives:

* Package applications with Docker; manage images on Amazon ECR.
* Deploy containers on Lightsail Containers and Amazon EKS.
* Migrate Monolithic to Microservices with Docker and AWS Fargate.
* Build CI/CD (CodePipeline + GitHub); monitor and secure container environments.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 6 | - **Docker Basics:** Write Dockerfile for sample app; build and run container locally | 05/22/2026 | 05/22/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | - **ECR Registry:** Push image to Amazon ECR; tags and basic lifecycle policy | 05/23/2026 | 05/23/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | - **Docker Optimization:** Understand layer cache and image size best practices | 05/24/2026 | 05/24/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | - **Lightsail Containers:** Deploy from ECR image, configure ports and scale <br> - **Lightsail Monitoring:** Check health, logs, and public endpoint <br> - **Comparison:** Compare Lightsail vs ECS/EKS complexity and cost | 05/25/2026 | 05/25/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - **EKS Orchestration:** Cluster, node group (or Fargate profile), basic kubectl <br> - **Deployment on EKS:** Deploy Deployment + Service (LoadBalancer/Ingress) <br> - **EKS Verification:** Verify pod scheduling and rolling updates | 05/26/2026 | 05/26/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - **Microservice Containers:** Split Monolithic into 2–3 microservice containers <br> - **ECS Fargate:** Task definition, service, no EC2 worker management <br> - **Service Discovery:** Service discovery and inter-container communication | 05/27/2026 | 05/27/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - **Container CI/CD:** GitHub → CodePipeline → CodeBuild → deploy to ECR/Fargate <br> - **Insights & Security:** Container Insights, CloudWatch log driver; restrict IAM task roles <br> - **Image Scanning:** Image scan (ECR), secrets via Secrets Manager/SSM Parameter Store | 05/28/2026 | 05/28/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Week 6 Achievements:

* Packaged Docker apps and published images to ECR.
* Deployed containers on Lightsail and EKS; understood pod/service lifecycle.
* Migrated to independent microservices on Fargate.
* Automated build/deploy via CodePipeline; applied container monitoring and security hardening.
