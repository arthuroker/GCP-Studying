
*Shared VPC*

Shared VPC allows you to extend he network from one project (host project) to other projects (service projects) within the same organization, allowing seamless communication between GCP services

The host project should be dedicated to network resource control only

*Benefits*

1) Centralized network management
2) Unified security policies
3) Cost efficiency

Note: service accounts in the service project must be granted compute.networkUser role on the shared VPC subnetworks in the host project to access network resources

*VPC Peering*

Allows you to connect two VPC networks so they can communicate using internal, private IPs over a low-latency and high bandwidth connection

Can connect intra or inter organization in GCP

*Cloud VPN*

Connects an on-prem network, another cloud provider network, or a remote office network to a Cloud VPC in GCP. Encrypted, but uses public internet

Use cases:

1) Hybrid (on-prem to Cloud VPC)
2) Multi-cloud (VPC from another provider to Cloud VPC)
3) Remote office (remote works to Cloud VPC)



