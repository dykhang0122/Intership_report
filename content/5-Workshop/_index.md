---
title: "Workshop"
date: 2026-06-30
weight: 5
chapter: false
pre: " <b> 5. </b> "
---

# Serverless AI Invoice Scanner Workshop

#### Overview

In this hands-on workshop, you will build and deploy a **Serverless AI Invoice Scanner** on AWS. 

This application allows users to upload invoices (images or PDFs), automatically extracts information using **Amazon Textract** (OCR), analyzes and normalizes the data into structured JSON using **OpenAI API**, stores the data in **Amazon DynamoDB**, and manages the invoices via a modern **ReactJS** frontend hosted on **AWS Amplify**.

![Architecture Diagram](/images/architecture-log.png)

#### Contents

1. [Introduction](1-introduce/)
2. [Environment Setup](2-environmentsetup/)
3. [AI-Powered Invoice Processing](3-aipoweredinvoiceprocessing/)
4. [Deploying API Gateway](4-deployingapigateway/)
5. [Testing with Postman](5-testwithpostman/)
6. [Deploying Frontend Application](6-deployingfrontend/)
7. [Resource Cleanup](7-cleanup/)