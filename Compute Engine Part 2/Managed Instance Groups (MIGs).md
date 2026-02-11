
*Definition*

Add some management to VMs

Simplifies deployment and management of VMs
	Things like automated updates, scaling, consistency, high availability, load balancing, operations


*Instance Templates*

A reusable blueprint to specify machine type, disk, OS, network settings, startups scripts, etc.

Can be created from custom images

MIGs use instance templates to create and mange fleets of identical VMs

Can also be used to create standalone VMs

*Autoscaling*

Scales number of VMs in a MIG based on demand

Can specify a max and min replicas
