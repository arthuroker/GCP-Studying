
*What is it*

Network tags are labels assigned to VM instances in GCP for traffic control

Can be used to dynamically control traffic with firewall rules as instances are added or removed

This is good because it avoids reliance on static IPs

*Example 1*

Scaling microservices in a VPC

Problem - how do we control inter-service communication in a scalable micro-services architecture on GCP without relying on fixed IPs?

We can group the different micro-services by tags, which then allows us to define traffic rules at the tag level



