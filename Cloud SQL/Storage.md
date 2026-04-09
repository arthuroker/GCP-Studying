
*Max storage* - 64 TB

*If you need more than this, use:*

*Spanner* if you still need strong consistency and ACID compliance (more expensive)

*BigTable* if NoSQL is an option and you need strong consistency and ACID compliance

*BigQuery* if you don't need strong consistency or ACID compliance, and OLAP is good enough

*Automatic Storage Increase*

Enables automatic increase when capacity is nearly full

Prevents service disruptions to insufficient space

Bounded by the 64TB max

Is vertical scaling, increases the capacity of existing instances

Not considered auto scaling, does not scale back down

