
*What is Hotspotting*

A performance bottleneck when a disproportionate amount of requests are being sent to a subset of the same cluster because the row key design did not evenly distribute the data across the cluster

*Row key best practices*

1) Reverse domain names
2) Timestamps at the end of the row key
3) String identifiers
   
*Avoid*

1) Domain names that are not reversed
2) Sequential numbers
3) Keys that need to be updated frequently
   
   
*Salting in BigTable*

Salting is the process of adding a random prefix to row keys to more uniformly spread data across nodes

Prefix values are usually random numbers or hash values

Considerations

1) Can complicate range queries because of non-sequential row keys
2) Increases overhead since you need to modify data on ingest, account for prefixes when querying

*Field promotion*

When a column gets merged into a row key

Reduces the need for full table scans

*Key visualizer*





