
*What is it*

Managed, on-demand service version of Apache Hadoop and Apache Spark

*Dataproc Cluster Architecture*

Mater node - central coordinator overseeing two crucial function
	1) HDFS name node - how and where data is distributed across the cluster
	2) YARN resource manager - strategic computation of compute

Worker nodes - each have an

HDFS data node - actual storage and replication of data

YARN node manager - handle the actual work

*Map Reduce*

Method to parallelize and distribute compute on large data sets

Foundation of Apache Hadoop

*Mapping Phase*
1) Input data split into smaller chunks by mappers
2) Each mapper works on a piece of the dataset

*Reduce Phase*
1) Shuffle, outputs of the mappers are reorganized
2) Processed data combined by reducers to produce the output


*HDFS (*