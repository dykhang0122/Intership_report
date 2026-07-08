---
title: "Week 5 Worklog"
date: 2026-05-15
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---
**Period:** 05/15/2026 – 05/21/2026

### Week 5 Objectives:

* Learn migration from Monolithic to Microservices and Cloud-Native architecture on AWS.
* Build Serverless apps with Lambda, API Gateway, DynamoDB, S3, and messaging (SQS, SNS, Step Functions).
* Deploy RESTful/GraphQL APIs, SPA with Cognito; CI/CD with SAM, CodePipeline; monitor with CloudWatch, X-Ray.
* Explore AWS AI services for modern applications.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 6 | - **Monolithic Architecture:** Compare Monolithic vs Microservices: coupling, scalability, independent deploy | 05/15/2026 | 05/15/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | - **Cloud-Native Design:** Cloud-Native: 12-factor, managed services, event-driven design | 05/16/2026 | 05/16/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | - **Project Planning:** Plan domain split for serverless lab | 05/17/2026 | 05/17/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | - **Serverless Practice:** Lambda (Python/Node), API Gateway trigger <br> - **Database Setup:** DynamoDB table (PK/SK), basic CRUD via Lambda <br> - **S3 Storage:** S3 bucket: upload/download, bucket policy and Lambda IAM role | 05/18/2026 | 05/18/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - **Messaging & Events:** SQS producer/consumer; SNS fan-out notifications <br> - **Workflow Orchestration:** Step Functions: orchestrate multi-step workflow (Lambda + wait + choice) <br> - **Error Handling:** Test async flows with error handling and retries | 05/19/2026 | 05/19/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - **API Development:** RESTful API on API Gateway; GraphQL overview (AppSync or proxy) <br> - **Frontend Integration:** SPA frontend calling API <br> - **Cognito Auth:** Cognito User Pool: sign-up, sign-in, JWT authorizer for API | 05/20/2026 | 05/20/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - **SAM Deployment:** AWS SAM: template.yaml, `sam build`, `sam deploy` <br> - **CI/CD Pipeline:** CodePipeline + CodeBuild: auto build/deploy on code push <br> - **Monitoring & Tracing:** CloudWatch Logs/Metrics, X-Ray tracing; overview of Bedrock/Rekognition | 05/21/2026 | 05/21/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Week 5 Achievements:

* Understood Microservices/Cloud-Native benefits and when to split services.
* Built complete serverless backend: Lambda, API Gateway, DynamoDB, S3.
* Ran async workflows with SQS, SNS, and Step Functions.
* Integrated Cognito for SPA; set up CI/CD pipeline and observability with CloudWatch, X-Ray.
