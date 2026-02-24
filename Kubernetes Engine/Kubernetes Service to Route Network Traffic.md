
*Internal*

*Headless*

No virtual IP or use DNS

Exposes Pod IP addresses


*Cluster IP*

Default service type in Kubernetes

Let's app talk to each other inside the cluster using an internal IP address

Includes DNS-based addressing fro seamless communication and scaling, applications can use a stable DNS name instead of managing individual pod IPs

*External*

*Node Port*

Opens a specific port on all cluster nodes, allowing external access via Node IP and port. Often used with Cloud Load Balancer

