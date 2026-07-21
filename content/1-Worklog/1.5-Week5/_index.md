---
title: "Week 5 Worklog"
date: 2026-05-15
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---
**Period:** 05/15/2026 – 05/21/2026

### Week 5 Objectives:

* Master core Containerization principles, install Docker Engine, and write optimized multi-stage Dockerfiles to package web applications.
* Create container image repositories on Amazon Elastic Container Registry (ECR), practicing building, tagging, and pushing Docker Images to AWS cloud storage.
* Deploy containerized applications on Amazon Lightsail Containers, configure domain settings, SSL certificates, and verify public runtime availability.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Fri | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Docker Fundamentals:** Study containerization principles, comparing Virtual Machines vs Docker Containers</li><li>- **Docker Installation:** Install Docker Engine/Desktop and run test container (`hello-world`)</li></ul> | 05/15/2026 | 05/15/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Sat | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Dockerfile Writing:** Author multi-stage Dockerfiles for Node.js/Python apps to minimize final image size</li><li>- **Build & Local Testing:** Execute `docker build` and verify container execution locally at `http://localhost:8080`</li></ul> | 05/16/2026 | 05/16/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Sun | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Image Optimization:** Optimize Docker Image size using Alpine base images and cache layer management</li><li>- **Docker CLI Practice:** Master container management commands: `docker ps`, `docker logs`, `docker exec`</li></ul> | 05/17/2026 | 05/17/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Mon | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Amazon ECR Repository Setup:** Create private ECR image repositories via AWS Console</li><li>- **AWS CLI ECR Auth:** Authenticate local Docker CLI with ECR Registry using `aws ecr get-login-password`</li></ul> | 05/18/2026 | 05/18/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Tue | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Push Image to ECR:** Tag local Docker Images (`docker tag`) and push (`docker push`) to Amazon ECR</li><li>- **Vulnerability Scanning:** Enable ECR image scanning on push to detect container dependencies vulnerabilities</li></ul> | 05/19/2026 | 05/19/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Wed | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Lightsail Container Setup:** Provision Amazon Lightsail Container Services</li><li>- **Deployment Setup:** Configure deployment targets pulling ECR images, mapping exposed container ports (80/8080) and env variables</li></ul> | 05/20/2026 | 05/20/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Thu | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **App Verification:** Access default Lightsail public URL, verify SSL certificate and container stability</li><li>- **Review & Audit:** Review build-push-deploy pipeline and document Week 5 progress</li></ul> | 05/21/2026 | 05/21/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Week 5 Achievements:

* Gained solid expertise in application packaging with Docker, utilizing multi-stage builds for lightweight, production-ready images.
* Built secure private Docker Image repositories on Amazon ECR, establishing CLI-driven image deployment workflows.
* Successfully deployed containerized web apps onto Amazon Lightsail Containers, understanding simplified cloud container management.
