
*Update Policies*

Strategies to minimize risk when updates need to be made to software or configuration on a MIG

*Opportunistic Mode*

Ensures that only new instances created in the MIG use the new instance template

Existing instance are not touched (not restarted, replaced, or updated in anyway)

Good for incremental updates and want to ensure currently running workloads

*Proactive mode*

Active, applied to all existing instances, usually one-by-one

Create a new one, wait for it to be ready, then replace

maxSurge - max number of new instances that can be created beyond current size

maxUnavailable - number of instances that can be unavailable at any time during the update

maxSurge = 1 and maxUnavailable = 0 makes it very incremental, create one, then replace with ultimate availibility

2 options:

1. Rolling restart - reuses existing instances and restarts them with the new configuration
2. Rolling replace - deletes and recreates instances with the updated template

