
*Pub/Sub message lifecycle*

1) Topic is created
2) Publisher sends message to that topic
3) The message is either pulled by the subscriber or pushed by PubSub
4) Subscriber acknowledges the message is received
5) Deletes message from the queue after the subscriber acknowledges it

*Message retention*

Message retention duration r