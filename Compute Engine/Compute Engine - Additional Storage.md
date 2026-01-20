
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
2. Verify disk was 
