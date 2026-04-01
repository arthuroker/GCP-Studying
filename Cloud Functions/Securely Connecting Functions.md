
Common for one Cloud Function to invoke another

Require authentication on default
	Thus only principals with the Cloud Invoker role or equivalent permissions can call

To authenticate a call, the caller function generates an ID token and includes it in the authorization header of the HTTP request

Best practice to assign a dedicated service account for functions that need to invoke other functions
	This follows principle of least privilege and zero trust model of security




