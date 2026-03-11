
*Vulnerability Scanning*

Container images are stored in Container Registry or Artifact registry are scanned by comparing their contents against a database of known vulnerabilities

*Attestations*

Are cryptographic signatures that serve as proof that a container image meets predefined security or compliance requirements

Typically generated from a CI/CD pipeline
	Usual flow for a container image: Build -> Test -> Scan. Then an attestation is created

*Binary authorization*

Managed GCP service, ensures only trusted image containers are deployed

Binary because it can be applied to any binary executable

Integrates seamlessly with GKE and other GCP services

User is the one that defines policies that specify criteria for authorization for deployment
	If it doesn't, binary authorization blocks the image container from running

Usual flow: 1) Define policy 2) Policy check 