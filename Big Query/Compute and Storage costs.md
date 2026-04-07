
*Query charges*

When performing queries, you are charges for the bytes read during the execution

Also charged for storing data in BQ (Active and Long-term), but charged separately for it

1) Query initiation
2) Compute evaluation
3) Bytes read (cost is incurred)
4) Processing
5) Query result

*Estimating size of a query*

Perform a dry run of query using the bq cmd tool

Also there is a preview number of bytes in the query UI

*Slots*

Slots = BQ units of computation

Sees the query and estimates the amount needed, then provides it

More/fewer slots can be recruited dynamically as query is executed

Two pricing options:

*On demand (default)*:

pay based on number of bytes processed by the query with a soft cap of 2,000 slots

*Capacity based*

pay for a dedicated amount of slots


More slots = faster execution (can do it in parallel) but higher cost


*Cross project queries*

Billing is already applied to where the query is executed, not the source data project



*Storage costs*

*Active*




*Longterm*

