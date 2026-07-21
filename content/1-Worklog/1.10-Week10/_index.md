---
title: "Week 10 Worklog"
date: 2026-06-19
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---
**Period:** 06/19/2026 – 06/25/2026

### Week 10 Objectives:

* Study Data Governance principles, sensitive data classification, privacy protection, and encryption practices (AWS KMS & IAM policies).
* Establish data connectors syncing extracted invoice records from Amazon DynamoDB / Athena into Amazon QuickSight.
* Design and build interactive business intelligence dashboards visualizing invoice spending trends and financial analytics for executive reporting.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Fri | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Data Governance Research:** Study AWS Data Governance framework: Data Lineage, Data Classification, Encryption at rest & in transit (AWS KMS)</li><li>- **IAM Data Policy Setup:** Write IAM Resource Policies restricting access to invoice records</li></ul> | 06/19/2026 | 06/19/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Sat | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Amazon QuickSight Enrollment:** Sign up for Amazon QuickSight Enterprise Edition</li><li>- **QuickSight Permissions:** Grant QuickSight permissions to access DynamoDB, S3, and AWS Glue Data Catalog</li></ul> | 06/20/2026 | 06/20/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Sun | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Connect Data Source:** Create Data Source connecting QuickSight to DynamoDB `InvoicesTable` (or via Amazon Athena querying Glue Crawlers)</li></ul> | 06/21/2026 | 06/21/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Mon | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Dataset Formatting in SPICE:** Create QuickSight DataSets, format data types (Date, Currency, Text), and configure SPICE engine in-memory ingestion</li></ul> | 06/22/2026 | 06/22/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Tue | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Design Dashboard Visuals:** Build charts: Bar charts (Spending per Vendor), Pie charts (Invoice categories), Line charts (Spending trends over time)</li></ul> | 06/23/2026 | 06/23/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Wed | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **KPI Cards & Controls:** Create KPI Cards (Total Expenses, Processed Invoices, Average Spend) and interactive parameter Filter Controls</li></ul> | 06/24/2026 | 06/24/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Thu | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Publish Dashboard & Export:** Publish the final QuickSight Dashboard, export executive PDF reports, and document Week 10 visual achievements</li></ul> | 06/25/2026 | 06/25/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Week 10 Achievements:

* Acquired solid knowledge of Data Governance, data classification rules, and encryption strategies on AWS Cloud.
* Successfully connected Amazon QuickSight to DynamoDB using the SPICE in-memory engine for sub-second query performance.
* Built a complete interactive BI Dashboard displaying invoice analytics, KPI metric summaries, and dynamic filter controls.
