
*Boot disk vs. Attached Disks*

Boot disk - contain OS and boot files. Can be resized, generally just for OS and not for application data

Attached disks - extra storage for data and/or applications. Added and removed independently of boot disk. Might even persist if VM is deleted


*Attached, Persistent Disks*

Standard - most cost effective, used for backups and unfrequent access use cases

Balanced - general workloads like web apps or dev VMs

SSD - high performance, low latency like databases, analytics, high volume transactions

Extreme - highest performance, highest cost

Can resize which does not detach or stop VM

*Resize persistent disk in Linux*

1. Resize disk in GCP
2. Verify disk was resized, Linux verifies it
3. Resize file system so it knows it has more space


*Zonal and regional persistent disks*

Default - persistent disks are in the same region and zone as the VM
	Best performance and minimizes latency

Zonal persistent disk - attached disk is in a different zone
	Cost effective with lower availability needs

Regional persistent disk - VM is in one region attached disk is in another, but there are two attached disks in that region in different zones
	High availability, durability, higher cost

*Auto delete*

Boot disks - by default, automatically deleted when the VM is deleted

Persistent disks - retained by default when VM is deleted

*Local SSD, different from persistent disks*

It is physically and directly attached to the VM

Ultra low latency
	Good for high I/O workloads

Temporary and ephemeral
	When VM is stopped or terminated, memory is not persisted

*Filestore*

Shared POSIX compliant file system
	Multiple VMs can mount the same fileshare and read and write the same data

They appear as if they were the local file system, making it easy to integrate

Good for high I/O, high throughput, low latency

Network attached, not physically



