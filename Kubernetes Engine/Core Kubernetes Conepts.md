
*Cluster*

Collection of nodes (VMs) that run containerized applications managed by Kubernetes

*Nodes*

Worker machine within a cluster that can run multiple pods

*Pod*

Smallest deployable unit in Kubernetes, can contain one or more containers. When there are multiple identical pods, they are called replicas

*Configuration*

Configuration is managed through a file called the Kubernetes manifest

*Kubernetes Manifest*

a file, usually YAML or JSON, that defines the desired state of objects (pods, services, deployments, etc) in a Kubernetes cluster

Blueprint for what things should look like

*Deployments*

A high-level Kubernetes resource that manages scaling, rolling updates, and high availability of application instances, allowing services to scale independently with seamless updates

Ideal for stateless services

Use a Deployment for each service

Can Specify:

1. Number of Pod replicas
2. Container image
	Image Pull Policy: IfNotPresent ensures that Kubernetes first checks if the image is already available on the node
3. Ports to use
4. Update strategy

