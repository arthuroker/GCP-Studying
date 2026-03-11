
*Private GKE Clusters*

Where nodes have only internal IP addresses

Nodes in the cluster can only communicate with each other and other resources inside the same VPC. No internet access

*Private Control Plane Endpoint*

Where the control plane is isolated and only accessed via configured access rules

Reduces the attack surface

*Master authorized networks*

Allows you to restrict access to the control plane to authorized IPs only

Ensures only specific networks can communicate with the control plane

Can work with public and private clusters

*Cloud NAT (Network Address Translation)*

Managed GCP service that allows private GKE workloads initiate outbound communications to the internet without being assigned public IPs

*Private Google Access*

Allows private GKE workloads to access Google APIs