
Layer of infrastructure designed to manage communication between micro-services in a distributed application

Provides things like traffic management, observability, security, and fault injection without requiring changes to the application code
	Fault injection can be used to test resilience of the application

Has observability and alerting capabilities tied to performance metrics like response time

*Cloud Service Mesh* is the Google-managed option, based on the OSS Istio

Each pod will create a sidecar proxy which handle the communication between services



