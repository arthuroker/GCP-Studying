
*Open Systems Interconnection (OSI) model*

Framework that organizes the functions of a network system in seven layers

Different load balancers operate at different layers

*Common layers for load balancers*

*Layer 4* - Transport Layer
	Responsible for end-to-end communication and error handling
	Balance traffic based on network layer info like IPs and ports
	TCP UDP protocols
	If mentioned, use a TCP, UPD load balancer


*Layer 7* - application layers
	Where user-facing applications operate
	Balances based on application-level info like HTTP headers and content
	HTTP(S), FTP, SMTP protocols
	If mentioned, use a Global Load balancer or HTTPS load balancer

*Typical Layer 7 load balancers*

1) HTTPS traffic
2) Path-based/Content-bas


