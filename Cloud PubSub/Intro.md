
*Tightly versus Loosely coupled messaging system*

Imagine a sender and receiver, directly connected. This is tightly coupled

Every time a message is sent, it needs to be immediately processed

Now imagine a vehicle bus between them. Messages can wait in the queue, receiver can process when it's ready. This is loosely coupled

PubSub is this message bus

*What is it?*

PubSub is a global scale messaging buffer

Decouples senders and receivers, making systems more reliable

Serverless, no ops

GCP version of Apache Kafka

*Use cases*

1) Data ingenstion
2) Connect to other pipeline ervices such as Dataflow