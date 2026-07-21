---
title: "Week 7 Worklog"
date: 2026-05-29
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---
**Period:** 05/29/2026 – 06/04/2026

### Week 7 Objectives:

* Build high-performance Serverless Backends supporting RESTful and GraphQL API patterns using AWS Lambda and Amazon API Gateway.
* Explore object storage with Amazon S3 alongside scalable NoSQL database storage using Amazon DynamoDB for cloud-native applications.
* Implement robust end-to-end user authentication and authorization using Amazon Cognito (User Pools & Identity Pools).

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Fri | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Serverless Service Overview:** Study event-driven architecture with AWS Lambda and API Gateway routing</li><li>- **Lambda Function Setup:** Write Python Lambda functions using `boto3` SDK to handle incoming requests</li></ul> | 05/29/2026 | 05/29/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Sat | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **RESTful API Construction:** Configure API Gateway HTTP/REST APIs, defining CRUD HTTP routes (GET, POST, PUT, DELETE)</li><li>- **Lambda Integration:** Integrate API Gateway endpoints with Lambda proxy integration</li></ul> | 05/30/2026 | 05/30/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Sun | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **GraphQL API Research:** Learn GraphQL fundamentals, comparing REST API vs GraphQL paradigms</li><li>- **GraphQL Setup:** Configure API Gateway / AWS AppSync to define GraphQL schemas and resolver functions</li></ul> | 05/31/2026 | 05/31/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Mon | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Amazon S3 Setup:** Create S3 Buckets, configure S3 Bucket Policies, CORS rules, and lifecycle management</li><li>- **DynamoDB Setup:** Provision DynamoDB Tables defining Partition Keys, Sort Keys, and Secondary Indexes</li></ul> | 06/01/2026 | 06/01/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Tue | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Lambda Integration:** Write Lambda code to upload/fetch objects from S3 and execute CRUD operations on DynamoDB</li><li>- **IAM Role Assignment:** Configure IAM execution roles for Lambda with Least Privilege permissions</li></ul> | 06/02/2026 | 06/02/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Wed | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Amazon Cognito Setup:** Provision Cognito User Pools supporting user sign-up, sign-in, and email OTP verification</li><li>- **Identity Pool Setup:** Configure Identity Pools to grant authorized access to AWS cloud resources</li></ul> | 06/03/2026 | 06/03/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Thu | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Authorizer Integration:** Attach Cognito JWT Authorizers to API Gateway routes to protect private endpoints</li><li>- **API Testing & Review:** Use Postman to authenticate, retrieve JWT tokens, and successfully invoke secured APIs</li></ul> | 06/04/2026 | 06/04/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Week 7 Achievements:

* Built fully functional serverless backend architecture using Lambda and API Gateway supporting RESTful and GraphQL APIs.
* Mastered object storage management on Amazon S3 and high-speed NoSQL data operations using Amazon DynamoDB.
* Deployed secure user authentication pipelines using Amazon Cognito User Pools and JWT Authorizers to safeguard cloud endpoints.
