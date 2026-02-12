
*Sole-tenant nodes*

Dedicated physical servers in GCP used exclusively by a single customer

Ensuring no other workloads share the hardware

Provides physical isolation for compliance and security

*Using Sole-tenant nodes*

1. Create a node group or individual nodes with gcloud compute sole-tenancy
2. Adding node labels to manage workload/VM placement (eg. business_unit=finance)
3. Create VM instance with node affinity rule, telling GCP which node or node group the WM should be placed on