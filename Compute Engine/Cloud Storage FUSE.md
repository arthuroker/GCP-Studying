
aka gcsfuse

*What it is*

A way to mount Cloud Storage buckets as a file system on Linux VMs

Translated file operations to API calls to Cloud Storage

Applications can access data through standard file paths

*Good for*

Works well with sequential read workloads
	ML training data and analytics pipelines

Simple file operations without locking

When you want VMs to access Cloud Storage like a file system

*Reasons to use FUSE instead of Firestore or NFS (Network File System)*

Single source of truth in Cloud Storage

Avoids costs from Filestore compared to Cloud Storage

*Limitations*

Not good for low latency or random I/O needs
