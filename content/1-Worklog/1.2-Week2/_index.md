---
title: "Week 2 Worklog"
date: 2026-04-24
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---
**Period:** 04/24/2026 – 04/30/2026

### Week 2 Objectives:

* Deepen understanding of Amazon VPC and layered network design on AWS.
* Practice Subnets, Route Tables, Internet Gateway, NAT Gateway, and VPN Site-to-Site.
* Configure Security Groups, Network ACLs, and validate traffic flow between network tiers.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 6 | - **VPC Concepts:** Learn Amazon VPC: CIDR, Public/Private Subnets, route propagation | 04/24/2026 | 04/24/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | - **Network Models:** Compare hub-spoke and multi-tier network models on AWS | 04/25/2026 | 04/25/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | - **Network Design:** Sketch reference network architecture for lab | 04/26/2026 | 04/26/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | - **VPC Practice:** Create VPC, split Public/Private Subnets across AZs <br> - **Route Configuration:** Configure Route Tables; attach Internet Gateway to Public Subnet <br> - **Connectivity Check:** Verify routing and connectivity from public EC2 | 04/27/2026 | 04/27/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - **NAT Gateway Practice:** Allow Private Subnet outbound Internet safely <br> - **NAT Configuration:** Configure `0.0.0.0/0` route via NAT on private route table <br> - **NAT Testing:** Test outbound connection from Private Subnet instance | 04/28/2026 | 04/28/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - **VPN Site-to-Site:** Virtual Private Gateway, Customer Gateway, VPN connection <br> - **IPSec Tunneling:** Set up IPSec tunnel between on-premises (simulated) and VPC <br> - **VPN Testing:** Check tunnel status and related route tables | 04/29/2026 | 04/29/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - **Network Security:** Configure Security Groups (stateful) and Network ACLs (stateless) <br> - **Firewall Comparison:** Compare inbound/outbound rules and NACL rule order <br> - **Traffic Analysis:** Test and document allowed/denied traffic flows | 04/30/2026 | 04/30/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Week 2 Achievements:

* Understood VPC architecture and roles of Subnets, Route Tables, IGW, and NAT Gateway.
* Deployed Public/Private tiered network; private instances reach Internet via NAT.
* Set up VPN Site-to-Site and understood on-premises-to-VPC routing.
* Configured Security Groups vs Network ACLs effectively for traffic control.
