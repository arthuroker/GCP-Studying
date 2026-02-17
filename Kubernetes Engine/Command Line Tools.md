
*kubectl (Kube control)*

Used for:

1. managing workloads and resources within the GKE cluster
2. Deploying an application listing services, scaling pods, checking resource status

Example commands:

kubectl config use-context
	Switch between contexts, different environments like prod

kubectl config view
	 View details about current context

kubectl set image deployment/{Deployment Name} {Image Name}
	Trigger a rolling deployment update

*gCloud*

Used for:

1. managing the cluster itself
2. Creating, updating, deleting clusters

Example commands:

gcloud container clusters get-credentials {cluster_name}
	retrieving credentials and context

gcloud container clusters update {Cluster_name} -enable-autoscaling -min-nodes={min} ma