
*Example*

High amount of financial data from GCP to offsite location

Need > 20Gbps per second throughput

Public internet based transfers are not acceptable due to throughput and vulnerabilities

*Solutions*

Establish a VPC around the GCP resources

Setup a Dedicated Interconnect (allows for secure and fast speeds)

*Another Example*

5TB Database needs to be synchronized with a replica on Cloud SQL

Needs to be near real time sync

Needs to use private IPs

*Solution*

Use a Cloud VPC around Cloud SQL

Dedicated interconnect between the database and Cloud SQL

Datastream allows for sync in near real time, facilities change data capture

*Another example*

On-prem data center connected to VPC through a cloud VPN

Fine for moderate data volumes

As data volume increases, VPNs may fail

