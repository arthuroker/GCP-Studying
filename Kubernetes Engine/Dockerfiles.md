
*Docker*

Docker is a tool to create and mange containers

Docker containers are a standardized implementation of containers, and once created can be deployed to pods on your K8s cluster

Dockerfiles define what goes into a container

Docker image = blueprint for the container

*Steps to Deploy*

1. Create or acquire a Dockerfile
2. Build Docker Image
3. Push Docker image to Artifact registry
4. Create K8s Deployment manifest that references location of image
5. Use kubectl to reference tDeployment Manifest file and deploy

*Optimizing Dockerfiles*

1. Using lightweight base images
2. Minimize final image size
3. Leverage layer caching
4. Avoid unnecessary steps

