
*What is it*

Delay between a change on the primary database and its replicas

Mainly a concern with write-heavy workloads

*Sharding to reduce replication lag*

Partitions data from primary into smaller shards

Each shard can be distributed across multiple servers

Reduces replication lag by distributing write operations across multiple shards, thereby decreasing the write load on each individual server

