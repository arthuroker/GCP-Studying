
*Transfer Appliance*

Large-scale, one-time data transfers

1) Order the transfer appliance from GCP (physical device that is shipped)
2) Fill the appliance
3) Ship it back to GCP
4) GCP uploads data into designated GCS bucket using the Transfer Appliance Dehydrator to decrypt and reassemble the files
5) Verify and start using data

This is good for one-time data migrations where network bandwidth is limited

Move petabytes of data efficiently and securely

*Storage Transfer Service*

Managed service that allows you to transfer on-prem or to/from other clouds

Can automate ongoing or scheduled transfers

Need high bandwidth and a stable connection at least 100 Mbps, 1Gbps is preferred

Recommended for up to hundreds of terabytes, if more, consider transfer appliance

*Command line uploads*

![[Pasted image 20260406110101.png]]


*Partitioning files during uploads*

Partitioning large files into smaller segments and using concurrent transfer/upload jobs can help it go more quickly

Can use it with gCloud, gsutil, and Storage Transfer Service

gsutil has a parallel composite uploads feature which automatically breaks larger files into smaller parts and uploads them in parallel 
	Also called *multi-threaded* upload

To do this, use the -m flag with gsutil

Can also add a flag for the size of the chunks

*Ensuring data integrity during upload*

1) Upload file as normal
2) Generate a CRC32C hash for local file
3) Retrieve the hash for the uploaded file
4) Check that the hashes match

CRC32C is a algorithm that GCP uses natively

*Compressive and Decompressive Transcoding*

*Compression* - Compressing files an help reduce transfer time and storage costs. An option for very cost-sensitive use cases

*Decompressive Tr*
