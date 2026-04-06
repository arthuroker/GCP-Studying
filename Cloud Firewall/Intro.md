
*What is Cloud Firewall*

Allows you to define and enforce rules that control network traffic to and from resources

Mainly for VMs
	But also applies to
	Cloud SQL
	Load Balancers
	GKE Clusters

Can control ingress (incoming traffic) and egress (outgoing traffic)

*Firewall Rules*

Rules can be based on protocols, IP ranges, ports, tags, and on identity

What if rules apply to the same given traffic?
	Firewall rules have a *priority* attribute that determines the order they are evaluated in

Each rule has a priority number from 0-65553
	Lower number means higher priority

*Identity-based rules*

Can make rules around service accounts

*Logging*

Logging is off by default

To enable logging for a given rule:

1) Config page for given rule
2) Turn Log option on

