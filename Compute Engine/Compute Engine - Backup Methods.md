

*Disks snapshots*

Disk snapshots can be taken and stored in Cloud Storage

Efficient, disk-specific backups that enable easy recovery and migration of data

Can be created for a boot disks and/or attached disk

Use cases - backup critical data, restore a corrupted disk to a previous state, migrate or clone a disk to another region/zone

*Custom Images*

Gets info from the boot disk but not the attached disk
	Only gets system files, OS, and config files

Once taken, stored in an image repository managed by GCP

Can be created from a running disk, existing snapshot, or imported from outside GCP

Use cases - allow for quick deployment of identical instances, create instance templates


*Difference between Disk snapshots and Custom Images*

Snapshots focu