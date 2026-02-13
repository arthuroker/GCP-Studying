
*What is Kubernetes*

K8s/Kubernetes is an open source platform for automating the deployment, scaling, and operation of containerized applications

*Benefits of containerization*

1. Portability
2. Scalability
3. Reliability

*What problems does Kubernetes solve?*

Manual scaling:

Before - teams had to manually provision and mange servers, making it difficult to handle sudden spikes in traffic

Solution - Kubernetes enables automated scaling through Horizontal Pod Autoscaler (HPA and Cluster Autoscaler)

Unreliable deployments:

Before: Applications could fail because they have different environments across servers

Solution - Ensures reliable, consistent deployments using declarative configurations, rolling updates, and self-healing mechanisms

Lack of portability:

Before - Applications were tightly coupled with infrastructure, thus challenging to move them

Solution - Uses containerization that provides a consistent runtime environment, enabling transportation across different environments

*Intro to GKE*

Managed Kubernetes service which allows you to run, manage, and scale containerized applications using GCP infrastructure

*Benefits of GKE*

1. Uses open source K8S/Kubernetes, thus compatible with other platforms
2. 