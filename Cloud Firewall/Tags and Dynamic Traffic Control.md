
*What is it*

Network tags are labels assigned to VM instances in GCP for traffic control

Can be used to dynamically control traffic with firewall rules as instances are added or removed

This is good because it avoids reliance on static IPs

*Example 1*

Scaling microservices in a VPC

Problem - how do we control inter-service communication in a scalable micro-services architecture on GCP without relying on fixed IPs?

We can group the different micro-services by tags, which then allows us to define traffic rules at the tag level

*Example 2*

Multi-tier application

UI Tier VMs, Business logic Tier VMs, Data Storage Tier VMs

Problem - traffic control between tiers?

VMs are tagged by their tier

*Allow* - UI -> Business, Business -> Storage

*Block* - Storage -> UI, UI -> Storage





