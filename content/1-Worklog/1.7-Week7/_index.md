---
title: "Week 7 Worklog"
date: 2026-05-29
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---
**Period:** 05/29/2026 – 06/04/2026

### Week 7 Objectives:

* Reinforce EC2 knowledge and the role of virtual servers in application deployment.
* Practice creating Amazon Linux EC2 with appropriate AMI, Instance Type, and Key Pair.
* Configure networking (VPC, Subnet, Public IP, Security Group) and secure SSH access.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 6 | - **3-Tier Review:** Review EC2 in 3-tier architecture: web, app, database layers | 05/29/2026 | 05/29/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | - **Pricing Comparison:** Compare On-Demand, Reserved, Spot pricing models | 05/30/2026 | 05/30/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | - **Bootstrap Script:** User data scripts for bootstrap on launch | 05/31/2026 | 05/31/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | - **EC2 Launch:** Launch Amazon Linux 2023, select AMI and t2/t3 Instance Type <br> - **Key Pair Management:** Create and download Key Pair (.pem), set file permissions <br> - **IAM Configuration:** Attach IAM role for EC2 (SSM, S3 read if needed) | 06/01/2026 | 06/01/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - **EC2 Networking:** Configure VPC/Subnet; Elastic IP vs auto-assigned public IP <br> - **Port Security:** Security Group: open only required ports (restricted 22 or SSM-only) <br> - **Network Validation:** Verify route tables and NACLs allow valid traffic | 06/02/2026 | 06/02/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - **EC2 Lifecycle:** Manage lifecycle on Console: monitor, reboot, stop/start, terminate <br> - **Status Checks:** Status checks: system vs instance; handle failures <br> - **EBS Expansion:** Attach additional EBS; expand volume online where supported | 06/03/2026 | 06/03/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - **Remote Connection:** SSH: `ssh -i key.pem ec2-user@ip`; configure `~/.ssh/config` <br> - **Application Deployment:** Deploy demo app (static site or small API) on EC2 <br> - **Security Guidelines:** Patch OS, firewall, avoid direct root login | 06/04/2026 | 06/04/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Week 7 Achievements:

* Understood EC2 role in application architecture and instance purchasing models.
* Created and configured Amazon Linux EC2 with AMI, Instance Type, Key Pair, IAM role.
* Set up VPC/Subnet/Public IP/Security Group following least exposure principles.
* Managed instances on Console; SSH access and demo app deployment successful.
