
1) Build the image
2) Push to either Container/Artifact registry
3) Ensure user or service account had read access to registry
4) Deploy image to Cloud Run or GKE, probably

*IAM roles to pulling images*


*Storage object viewer* - role is sufficient for a user or service account to pull images from Container Registry

*Artifact registry reader/viewer* - needed to pull images from Artifact registry

