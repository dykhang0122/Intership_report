---
title: "Week 3 Worklog"
date: 2026-05-01
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---
**Period:** 05/01/2026 – 05/07/2026

### Week 3 Objectives:

* Learn Amazon EC2 details, Instance Types (t3.micro, c5, r5, etc.), Amazon Machine Images (AMI), and SSH Key Pair management.
* Launch EC2 Linux virtual machines, configure Elastic Block Store (EBS) volumes, build EBS Snapshots, and automate backups.
* Install, configure, and maintain a basic Web Server (Nginx) on an EC2 instance and test public web accessibility.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Fri | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Amazon EC2 Theory:</b> Study EC2 architecture, Instance Types, and EC2 Lifecycle (Launch, Stop, Terminate, Reboot)</li><li>- <b>AMI Types:</b> Understand Amazon Machine Images (Quick Start AMIs, Custom AMIs, Marketplace AMIs)</li></ul> | 05/01/2026 | 05/01/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Sat | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>SSH Key Pair Setup:</b> Generate secure `.pem` Key Pairs for SSH access</li><li>- <b>EC2 Launch:</b> Launch Amazon Linux 2023 EC2 instance (`t3.micro`), assigning Public IP and Security Group</li></ul> | 05/02/2026 | 05/02/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Sun | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>SSH Connection:</b> Connect to EC2 Linux instance via SSH client (`ssh -i key.pem ec2-user@public-ip`)</li><li>- <b>System Updates:</b> Update system packages (`sudo dnf update -y`)</li></ul> | 05/03/2026 | 05/03/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Mon | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>EBS Volume Management:</b> Explore EBS volume types (gp3, io2, st1) and create additional EBS volumes</li><li>- <b>Disk Partitioning & Mount:</b> Practice `fdisk`, format filesystem (ext4/xfs), and mount new volume to `/data`</li></ul> | 05/04/2026 | 05/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Tue | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>EBS Snapshots:</b> Create manual EBS volume snapshots for backup</li><li>- <b>AWS Backup Configuration:</b> Set up automated AWS Backup Plans for EBS volumes and build custom AMIs</li></ul> | 05/05/2026 | 05/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Wed | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Nginx Installation:</b> Install Nginx Web Server on EC2 Linux (`sudo dnf install nginx -y`)</li><li>- <b>Web Server Setup:</b> Write customized `index.html`, start Nginx service, and enable startup auto-run</li></ul> | 05/06/2026 | 05/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Thu | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- <b>Web Testing:</b> Open HTTP port (80) in Security Group and verify web access via browser</li><li>- <b>Review & Audit:</b> Audit EBS storage usage, backup routines, and document Week 3 achievements</li></ul> | 05/07/2026 | 05/07/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Week 3 Achievements:

* Developed clear criteria for selecting EC2 Instance Types and AMIs matched to workload requirements.
* Launched and mastered EC2 Amazon Linux 2023 instances with secure SSH authentication using Key Pairs.
* Proficient in EBS storage management: partitioning, formatting, directory mounting, and automated Snapshot/Backup scheduling.
* Successfully transformed an EC2 Linux virtual machine into an active Nginx Web Server accessible over HTTP.
