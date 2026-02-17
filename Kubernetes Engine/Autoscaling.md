
*Cluster Autoscaler*

Scales the number of nodes in the cluster based on the overall resource demands of the pods

Best practice is to also set the minimum and maximum # of nodes

*Horizontal Pod Autoscaler*

Scales the # of pods

Doesn't restart pods, adds/removes instead

Can scale based on either CPU/memory or custom metrics

Some stateful workloads incompatible

*Vertical Autoscaler*

Scales the compute and memory of individual pods based on their usage

May restart pods

Cannot be done based on custom metrics