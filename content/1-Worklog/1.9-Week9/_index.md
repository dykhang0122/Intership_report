---
title: "Week 9 Worklog"
date: 2026-06-12
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---
**Period:** 06/12/2026 – 06/18/2026

### Week 9 Objectives:

* Develop a fully automated end-to-end invoice processing pipeline: Upload invoice file to S3 -> Trigger Lambda function -> Call Amazon Textract for OCR text extraction -> Pass data to Amazon Bedrock to standardize JSON formatting -> Persist records into Amazon DynamoDB.
* Design detailed overall system architecture diagrams and sequence diagrams illustrating data flows using Draw.io.
* Author complete technical setup documentation, document IAM, S3, and Lambda configurations, and capture system proofs on Notion.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Fri | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>S3 Event Notification Setup:</b> Configure S3 bucket `invoice-upload-bucket` to emit object-created triggers for PDF/image uploads</li><li>- <b>IAM Execution Role Creation:</b> Create Lambda execution role granting `s3:GetObject`, `textract:AnalyzeDocument`, `bedrock:InvokeModel`, and `dynamodb:PutItem` permissions</li></ul> | 06/12/2026 | 06/12/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Sat | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Lambda Textract Integration:</b> Write Python Lambda function using `boto3` invoking Amazon Textract `AnalyzeDocument` to extract key-value pairs (Vendor Name, Total Amount, Date, Tax)</li></ul> | 06/13/2026 | 06/13/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Sun | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Lambda Bedrock Integration:</b> Invoke Amazon Bedrock (Anthropic Claude 3 / Titan models) to process and clean raw Textract output into structured JSON</li></ul> | 06/14/2026 | 06/14/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Mon | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>DynamoDB Persistence:</b> Write function logic persisting standardized JSON records into Amazon DynamoDB `InvoicesTable` with generated auto-uuids</li></ul> | 06/15/2026 | 06/15/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Tue | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>End-to-End Pipeline Testing:</b> Upload sample invoices to S3, inspect CloudWatch Logs, and verify persisted items inside DynamoDB tables</li></ul> | 06/16/2026 | 06/16/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Wed | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Draw.io Architecture Diagramming:</b> Draft 3D Cloud System Architecture Diagrams and detailed Sequence Diagrams in Draw.io</li></ul> | 06/17/2026 | 06/17/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Thu | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Notion Documentation:</b> Create project documentation on Notion: Upload screenshots of IAM Roles, S3 Events, Lambda code, DynamoDB items, and finalize Week 9 log</li></ul> | 06/18/2026 | 06/18/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Week 9 Achievements:

* Built a fully working automated serverless AI invoice processing pipeline (S3 -> Lambda -> Textract -> Bedrock -> DynamoDB).
* Completed professional high-level system architecture diagrams and sequence diagrams in Draw.io.
* Documented step-by-step setup guides, IAM/S3/Lambda configurations, and evidence screenshots on Notion.
