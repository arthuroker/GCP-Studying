
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

Can specify a max and min replicas (instances in the group)

Uses CPU utilization as the default metric
	But can specify custom metrics (request latency, queue length)

Good for variable workloads (gaming, web apps, scaling test environments)

*Memory-based scaling*

Autoscaling based on memory must include all relevant states to get an accurate picture

4 types of memory to track:

1. Used memory - actively utilized by applications
2. Buffered memory - used to buffer temporary I/O operations
3. Cached - memory allocated for frequently accessed files/data
4. Slab - kernel allocated memory for managing OS structures

*Preventing over-provisioning*

When you create more instances than needed, perhaps because it thinks the VMs are less healthy than they actual are

Thus, initial delay on health checks should exceed the amount of time it takes VMs to become fully operational, otherwise it could over-provision

