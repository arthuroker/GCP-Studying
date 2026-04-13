
*What is it*

Allows you to control access to your web applications and VMs by verifying the identity of users before granting them access

*How it works*

Users requests a Cloud Run resource

IAP intercepts the request to check if the User is authenticated and authorized

Can also protect App Engine, Load Balancers, and GCE resources

*Reducing Attack Surface*

Eliminates the need for backend IPs to be public

Eliminates need for open ports

*Connecting to a VM without a public IP*

Can be enab