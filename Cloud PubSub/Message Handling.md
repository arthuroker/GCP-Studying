
*Pub/Sub message lifecycle*

1) Topic is created
2) Publisher sends message to that topic
3) The message is either pulled by the subscriber or pushed by PubSub
4) Subscriber acknowledges the message is received
5) Deletes message from the queue after the subscriber acknowledges it

*Message retention*

*Message retention duration* refers to the amount of time which PubSub retains messages before deleting

This retention ensures that messages are available for replay

*Topic retention* retains messages within a topic even after they are acknowledged by all subscribers

