
*Classic Problem*

Model embedded within application code

Meaning, any model updates require a full application redeployment

Can't experiment with new frameworks without code changes

ML team is dependent on application deployment schedule

Slow to adopt latest AI capabilities

*Solution*

Make the ML a Vertex AI endpoint instead of within the model codebase

Benefits:

1) Deploy new models without touching application
2) Rapidly adopt lastest AI capabilities
3) ML team works independently
4) Reuse endpoint for other applications
5) Autoscaling based on server volume

