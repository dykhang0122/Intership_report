---
title: "Week 8 Worklog"
date: 2026-06-05
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---
**Period:** 06/05/2026 – 06/11/2026

### Week 8 Objectives:

* Research Amazon Bedrock and RAG (Retrieval-Augmented Generation).
* Analyze AWS/AI documentation; propose AI Invoice Scanner final project architecture.
* Integrate Textract + S3; Lambda combining Textract and Bedrock; store in DynamoDB.
* Test end-to-end invoice processing pipeline.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 6 | - **Amazon Bedrock:** Amazon Bedrock: foundation models, inference, basic prompt engineering | 06/05/2026 | 06/05/2026 | <https://cloudjourney.awsstudygroup.com/7-ai-ml-service-on-aws/> |
| 7 | - **RAG Architecture:** RAG: embeddings, vector store, retrieve context before generation | 06/06/2026 | 06/06/2026 | <https://cloudjourney.awsstudygroup.com/7-ai-ml-service-on-aws/> |
| CN | - **AI Documentation:** Read and summarize AWS Generative AI technical docs | 06/07/2026 | 06/07/2026 | <https://cloudjourney.awsstudygroup.com/7-ai-ml-service-on-aws/> |
| 2 | - **Requirement Analysis:** Analyze final project requirements: upload invoice → extract → store → query <br> - **Architecture Design:** Draw high-level architecture: S3, Textract, Lambda, Bedrock, DynamoDB <br> - **Project Backlog:** List user stories and acceptance criteria | 06/08/2026 | 06/08/2026 | <https://cloudjourney.awsstudygroup.com/7-ai-ml-service-on-aws/> |
| 3 | - **Textract Processing:** S3 put event trigger; call `DetectDocumentText` / `AnalyzeExpense` <br> - **Raw Storage:** Store raw Textract JSON in S3 prefix or pass to processing Lambda <br> - **Input Verification:** Test with sample invoice PDF/images | 06/09/2026 | 06/09/2026 | <https://cloudjourney.awsstudygroup.com/7-ai-ml-service-on-aws/> |
| 4 | - **Lambda Logic:** Lambda: parse Textract output, normalize fields (vendor, date, amount, line items) <br> - **Bedrock Integration:** Invoke Bedrock model to enrich/classify/summarize if needed <br> - **Robustness:** Error handling, timeout, DLQ for failed messages | 06/10/2026 | 06/10/2026 | <https://cloudjourney.awsstudygroup.com/7-ai-ml-service-on-aws/> |
| 5 | - **DynamoDB Design:** DynamoDB: design invoice table (PK invoiceId, GSI by user/date) <br> - **API Development:** Lambda writes metadata; API GET list/detail (Lambda + API Gateway) <br> - **End-to-End Test:** Integration test full pipeline: upload → extract → store → query | 06/11/2026 | 06/11/2026 | <https://cloudjourney.awsstudygroup.com/7-ai-ml-service-on-aws/> |

### Week 8 Achievements:

* Understood Bedrock, RAG, and application to document processing use cases.
* Completed analysis and proposed architecture for AI Invoice Scanner project.
* Integrated Textract with S3 trigger for automatic invoice data extraction.
* Built Lambda pipeline with Textract, Bedrock, and DynamoDB; end-to-end test passed.
