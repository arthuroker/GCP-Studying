
Health checks are probes sent by the load balancer to backend instances to ensure they are ready to receive traffic

Endpoints based on the configuration you set

If an instance fails its health check, the load balancer stop sending traffic to it until it recovers

Load balancer needs to be able to communicate to the backend services to perform these
	Need to make sure the firewall must allow the probes to reach the instances
	GCP has IP ranges for health checks

