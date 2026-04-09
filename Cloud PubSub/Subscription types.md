
*Push* - Pub/Sub initiates the process, sends the message to the subscriber. Subscriber must be a webhook endpoint that accepts POSTs over HTTPS
	Good for low-latency, real-time streaming use cases.

*Pull* - subscriber initiates the request. Better for batch delivery, larger volume of messages. Require more code in the subscriber

