
*What is it*

Managed, on-demand service version of Apache Hadoop and Apache Spark

*Dataproc Cluster Architecture*

Mater node - central coordinator overseeing two crucial function
	1) HDFS name node - how and where data is distributed across the cluster
	2) YARN resource manager - strategic computation of compute

Worker nodes - each have an

HDFS data node - actual storage and replication of data

YARN node manager - handle the actual work



