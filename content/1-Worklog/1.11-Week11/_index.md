---
title: "Week 11 Worklog"
date: 2026-06-26
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---
**Period:** 06/26/2026 – 07/02/2026

### Week 11 Objectives:

* Optimize AWS Lambda function code: fine-tune Memory/Timeout settings, optimize `boto3` SDK client initialization, and configure Provisioned Concurrency to eliminate cold starts and lower operational costs.
* Perform comprehensive end-to-end Integration Testing across the entire automated invoice processing pipeline, identifying and resolving operational edge cases (timeouts, JSON parsing errors, retry policies).
* Finalize internship technical reports and capture full system configuration evidence screenshots on the AWS Management Console.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Fri | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Lambda Performance Analysis:</b> Utilize AWS Lambda Power Tuning / CloudWatch Insights to measure Memory consumption and Execution Duration</li><li><b>- Code Refactoring:</b> Refactor Python code to reuse HTTP connections and SDK client connections outside the handler</li></ul> | 06/26/2026 | 06/26/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Sat | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Cost & Cold Start Optimization:</b> Adjust RAM settings from 1024MB to 512MB for cost efficiency; configure Provisioned Concurrency to eradicate cold starts</li></ul> | 06/27/2026 | 06/27/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Sun | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Integration Testing:</b> Run automated load scripts uploading 20 multi-format sample invoices (PDF, PNG, JPG) to S3</li><li><b>- Test Log Inspection:</b> Inspect CloudWatch Logs to identify data extraction discrepancies</li></ul> | 06/28/2026 | 06/28/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Mon | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Bug Fixing & Resilience:</b> Add robust try-except handling for Bedrock JSON responses and attach Dead Letter Queues (DLQ) to SQS/Lambda for failed messages</li></ul> | 06/29/2026 | 06/29/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Tue | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- AWS Evidence Screenshots:</b> Screenshot detailed Console configurations for S3 Buckets, IAM Roles, Lambda Triggers, DynamoDB Tables, and QuickSight Dashboards</li></ul> | 06/30/2026 | 06/30/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Wed | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Technical Report Writing:</b> Embed configuration screenshots and performance charts into the Hugo internship site documentation</li></ul> | 07/01/2026 | 07/01/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Thu | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Review & Summary:</b> Audit codebase, test Hugo static site rendering, and summarize Week 11 achievements</li></ul> | 07/02/2026 | 07/02/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Week 11 Achievements:

* Successfully optimized AWS Lambda functions, achieving a 35% reduction in execution time and lower cloud compute costs.
* Completed full Integration Testing across the invoice processing pipeline, ensuring robust error handling via DLQ and retry mechanisms.
* Gathered complete AWS Console configuration evidence screenshots and published formatted technical documentation on the Hugo site.
