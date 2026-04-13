
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

*High availablility* 