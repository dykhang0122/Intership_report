---
title: "Week 2 Worklog"
date: 2026-04-24
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---
**Period:** 04/24/2026 – 04/30/2026

### Week 2 Objectives:

* Gain deep understanding of AWS VPC networking, CIDR block allocation, Public/Private Subnet creation, and Route Table partitioning.
* Practice setting up Internet Gateway (IGW), NAT Gateway for private networks, and simulating Site-to-Site VPN connectivity.
* Configure multi-layered network security controls using Security Groups (stateful) and Network ACLs (stateless).

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Fri | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- VPC Research:</b> Study Amazon VPC fundamentals, CIDR blocks, Private IP, and Public IP design</li><li><b>- Network Diagram:</b> Draw a VPC architecture diagram spanning 2 Availability Zones</li></ul> | 04/24/2026 | 04/24/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Sat | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- VPC & Subnet Creation:</b> Launch Custom VPC (`10.0.0.0/16`), create Public and Private Subnets across AZs</li><li><b>- Route Table Setup:</b> Create separate Public and Private Route Tables</li></ul> | 04/25/2026 | 04/25/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Sun | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Internet Gateway Setup:</b> Create and attach an Internet Gateway (IGW) to the Custom VPC</li><li><b>- Public Routing:</b> Add route `0.0.0.0/0` pointing to IGW in the Public Route Table</li></ul> | 04/26/2026 | 04/26/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Mon | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- NAT Gateway Setup:</b> Allocate Elastic IP (EIP) and create NAT Gateway inside the Public Subnet</li><li><b>- Private Routing:</b> Configure Private Route Table to allow Private Subnet instances to access outbound Internet via NAT Gateway</li></ul> | 04/27/2026 | 04/27/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Tue | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- VPN Architecture Study:</b> Learn Site-to-Site VPN, Virtual Private Gateway (VGW), and Customer Gateway (CGW)</li><li><b>- VPN Simulation:</b> Configure Virtual Private Gateway and set up IPSec tunnels connecting enterprise networks with VPC</li></ul> | 04/28/2026 | 04/28/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Wed | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Security Group Practice:</b> Configure stateful Security Groups for Web Servers (open ports 80, 443, 22)</li><li><b>- Network ACL Practice:</b> Configure stateless Network ACLs at the Subnet boundary with rule number priorities</li></ul> | 04/29/2026 | 04/29/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Thu | <ul style="list-style-type:none; margin:0; padding-left:0;"><li><b>- Testing & Audit:</b> Launch test EC2 instances in both subnets, verify ping, SSH, HTTP connectivity, and audit firewall rules</li></ul> | 04/30/2026 | 04/30/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Week 2 Achievements:

* Mastered VPC architecture concepts, successfully designing and building a multi-tier Public/Private Subnet topology.
* Configured complete network routing: Public Subnet reaches Internet via IGW, Private Subnet connects outbound securely via NAT Gateway.
* Understood Site-to-Site VPN operations and hybrid network integration between On-Premises data centers and AWS Cloud.
* Clearly distinguished stateful Security Groups (instance-level) vs stateless Network ACLs (subnet-level) to enforce strict network security.
