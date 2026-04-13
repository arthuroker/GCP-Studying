
*Setup*

Need to choose region and zone

*Cluster mode* - number of master and worker nodes

*Disk type and size* - for master and worker nodes (ie. Standard versus SSD depending on performance needs)

*Local SSD size* - For high performance, cannot be changed later

*Preemptible nodes* - cost-effective for non critical workloads

*Staging Bucket* - Bucket for job logs, scripts, temp data, output


*Cluster mode options*

*Single node* - 1 master node, no worker nodes
	For development/testing, lightweight

*Standard mode* - 1 master, custom number of worker nodes
	Default for production

*High availability* - 3 master nodes, custom number of worker nodes
	Critical workloads



*Preemptible nodes*

Much cheaper than standard nodes, but can be reclaimed by Google at any time

Need at least 1 standard worker node

Best for tasks that can handle interruptions and do not require persistent storage

Jobs take less time

