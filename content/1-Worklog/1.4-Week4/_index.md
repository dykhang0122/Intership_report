---
title: "Week 4 Worklog"
date: 2026-05-08
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---
**Period:** 05/08/2026 – 05/14/2026

### Week 4 Objectives:

* Integrate VS Code development environment with EC2 via Remote - SSH and analyze network paths using AWS VPC Reachability Analyzer.
* Eliminate public SSH port (port 22) exposure by adopting EC2 Instance Connect Endpoint (EICE) and AWS Systems Manager (SSM) Session Manager for zero-trust remote access.
* Deploy CloudWatch Agent to monitor OS metrics (RAM, Disk space, CPU) and establish automated alert mechanisms via CloudWatch Alarms.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Fri | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **VS Code Remote SSH Setup:** Configure `~/.ssh/config` file to establish direct remote development connections to EC2</li><li>- **Remote Editing:** Edit web source files directly on the remote EC2 host</li></ul> | 05/08/2026 | 05/08/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Sat | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Reachability Analyzer Overview:** Explore AWS VPC Reachability Analyzer capabilities</li><li>- **Network Path Analysis:** Create Analysis Paths from Internet Gateway/Subnet to EC2 to check connectivity blockages</li></ul> | 05/09/2026 | 05/09/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Sun | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **Troubleshooting Simulation:** Simulate blocked ports in SG/NACL and use Reachability Analyzer to pinpoint exact network hops causing failure</li></ul> | 05/10/2026 | 05/10/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Mon | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **SSM Session Manager Setup:** Attach `AmazonSSMManagedInstanceCore` IAM Policy to EC2 IAM Role</li><li>- **Secure Shell access:** Open browser/CLI shell connections via SSM Session Manager without inbound SSH port 22</li></ul> | 05/11/2026 | 05/11/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Tue | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **EC2 Instance Connect Endpoint:** Provision EICE in private subnets</li><li>- **Private SSH Tunneling:** Tunnel SSH access to private instances lacking Public IPs via EICE</li></ul> | 05/12/2026 | 05/12/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Wed | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **CloudWatch Agent Installation:** Install `amazon-cloudwatch-agent` on Linux EC2</li><li>- **Agent JSON Config:** Configure custom JSON parameters to collect RAM (`mem_used_percent`) and Disk usage (`disk_used_percent`)</li></ul> | 05/13/2026 | 05/13/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Thu | <ul style="list-style-type:none; margin:0; padding-left:0;"><li>- **CloudWatch Alarms Creation:** Set up SNS email alert notifications when CPU > 80% or RAM > 85%</li><li>- **Review & Audit:** Trigger simulated high workload and document Week 4 achievements</li></ul> | 05/14/2026 | 05/14/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Week 4 Achievements:

* Established modern cloud development environment using VS Code Remote SSH for seamless remote code editing.
* Mastered VPC Reachability Analyzer tool for rapid network diagnosis and routing path validation.
* Enhanced server security posture by disabling open public SSH port 22 and leveraging SSM Session Manager & EC2 Instance Connect Endpoint.
* Deployed end-to-end OS resource monitoring using CloudWatch Agent alongside automated SNS email notifications for high resource usage.
