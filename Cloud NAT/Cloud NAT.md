
*Network Address Translation*

Used to map private IPs to public IPs to enable communication with external networks

Enables compute resources without public IPs (usually VMs) to access the internet

Imagine Compute Engine VMs in a subnet in a VPC

We need to put Cloud NAT at the VPC level to translate the private IPs to a single public IP that is assigned to the NAT gateway

In Cloud NAT Mapping, you need to select what subnets are eligible for translation

*Available source endpoints*

aka a resource that initiates an outbound request

1) VMs with private IPs
2) Private GKE Clusters
3) Serverless services within a VPC subnet

*Benefits*

1) Eliminates the attack surface
2) Scales automatically
3) High availability
4) Lower costs by reducing the amount of external IPs

*Scenario*

Organization rule: No external IPs on VMs

So we can add 
