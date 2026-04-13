
*Use Cases*

User request routed to CDN endpoint, checks if the request file is cached

If not, gets it from the GCS bucket and caches it and serves it

*Common Architecture with a Load Balancer*

Global users that hit a Load balancer first, goes to CDN (does the processing above), or for dynamic requests, goes to the Compute Engine backend

