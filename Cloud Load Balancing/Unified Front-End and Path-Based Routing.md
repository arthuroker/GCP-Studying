
*Intro to Unified Frontend*

Clients connection meets a load balancer with a DNS name and an SSL certificate

Multiple versions of the backend

This structure simplifies how clients interact with the system

*Path-based routing*

Direct requests based on the paths specified within the request

Operates at the Layer 7 level

Can serve multiple versions of a backend or different micro-services

*Use Cases*

*1*

Managing multiple API versions

Solution - use a single load balancer with path-based routing to directs requests to the right server

*2*

Multi-region game micro-services

Wants a single IP address with backend services deployed around the world

Solution - Global Load Balancer, unify frontend access and route to micro-services based on path

*3*

Mobile app update

Wants to move to a new API while maintaining the legacy API

Solution - Use one load balancer to handle both APIs, voiding DNS 