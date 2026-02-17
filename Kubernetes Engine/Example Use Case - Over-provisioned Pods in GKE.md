
*Scanario*

GKE Cluster with 5 pods

Each pod has requested 1CPU and 2GB of ram

But each pod is actually only using .2CPU and .5GB

80% of CPU unused and 75% of RAM unused

You'll have unnecessary costs

*Solution*

Vertical pod autoscaler (in auto mode)

Number of pod