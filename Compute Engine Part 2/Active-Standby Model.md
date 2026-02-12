
*When MIGs are not appropriate*

1. Horizontal scaling is not allowed (ie. when it relies on one instance for state, or can't be duplicated)
2. Concurrent data access is not allowed (MIG instances may try to access the same persistent disk)
3. Enforce no traffic/load sharing. If only one active instance is allowed to handle traffic at a time, MIGs are not good

*Active-standby model*

Having a standby instance re