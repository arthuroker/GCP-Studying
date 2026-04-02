
*Shared VPC*

Shared VPC allows you to extend he network from one project (host project) to other projects (service projects) within the same organization, allowing seamless communication between GCP services

The host project should be dedicated to network resource control only

*Benefits*

1) Centralized network management
2) Unified security policies
3) Cost efficiency

Note: service accounts in the service project must be granted compute.networkUser role on the shared VPC subnetworks in the host project to access network resources

