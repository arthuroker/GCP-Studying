
*1st step*

Check logs from Cloud Logging and metrics in Cloud Monitoring

*Serial Console*

Tool for troubleshooting

Low-level, text-based interface for interacting with VMs

Mimics the functionality of a serial port on a traditional server

Direct access to boot process, system messages, recovery tools

*503 error and resource quotas*

503 indicates the server is temporarily unavailable because it may be overwhelming resources

Exceeding quotas can prevent the creation of new instances

Max number of replicas configured in autoscaling

*Disable health checks when troubleshooting*

Temporarily disable health checks when troubleshooting so it won't disable the VM thinking it's unhealthy

1. Temporarily disable health checks
2. Configure access (eg. add SSH keys)
3. Investigate and resolve
4. Re-enable health checks