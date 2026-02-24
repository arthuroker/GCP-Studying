
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

Not ideal, doesn't have advanced features

*Load Balancer*

Creates external IP address, automatically sets up load balancer to route traffic to app

*External Name*

Maps app to a DNS alias to look like it's hosted at another domain

*Ingress*

Adds sophisticated HTTPS gateway/traffic management

