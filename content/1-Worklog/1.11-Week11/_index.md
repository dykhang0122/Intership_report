---
title: "Week 11 Worklog"
date: 2026-06-26
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---
**Period:** 06/26/2026 – 07/02/2026

### Week 11 Objectives:

* Finalize Textract → Bedrock → DynamoDB pipeline; optimize Lambda.
* Complete QuickSight dashboard; review IAM, S3, Lambda security.
* Perform Integration Testing; prepare final presentation (docs, slides, demo).

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 6 | - **Pipeline Finalization:** Finalize end-to-end flow: S3 upload → Textract → Lambda enrich (Bedrock) → DynamoDB | 06/26/2026 | 06/26/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | - **Metadata Synchronization:** Sync S3 source file metadata with DB records | 06/27/2026 | 06/27/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | - **Duplicate Resolution:** Handle duplicate invoices and idempotency keys | 06/28/2026 | 06/28/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | - **Lambda Optimization:** Optimize Lambda: memory/timeout, reuse boto3 clients, DynamoDB batch writes <br> - **Reduce Cold Start:** Reduce cold start (provisioned concurrency for demo if needed) <br> - **Log Cleanup:** Review CloudWatch Logs; remove noise; add custom metrics | 06/29/2026 | 06/29/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - **QuickSight Refinement:** Finalize QuickSight dashboard: filters, theme, mobile layout <br> - **IAM Audit:** Review IAM: least privilege for Lambda, Textract, Bedrock invoke <br> - **S3 Hardening:** S3 block public access, encryption, deny insecure transport policy | 06/30/2026 | 06/30/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - **Integration Testing:** Integration Testing: batch upload, API list/search, dashboard refresh <br> - **Regression Resolution:** Log bugs, fix regressions, retest <br> - **Load Testing:** Light load test (10–20 files) measuring avg processing time | 07/01/2026 | 07/01/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - **Final Documentation:** Final technical documentation: architecture, deployment guide, lessons learned <br> - **Slide Preparation:** Presentation slides: problem, solution, demo flow, KPIs <br> - **Demo Rehearsal:** Live demo rehearsal: upload invoice → view results → QuickSight dashboard | 07/02/2026 | 07/02/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Week 11 Achievements:

* AI Invoice Scanner pipeline runs reliably from upload through storage and query.
* Lambda performance optimized; QuickSight dashboard polished and readable.
* IAM, S3, and Lambda security reviewed against best practices.
* Integration Testing passed; documentation, slides, and demo ready for final presentation.
