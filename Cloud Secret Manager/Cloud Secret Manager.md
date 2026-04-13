
*What is it*

Provides a secure and centralized way to manage sensitive credentials like API keys and tokens

Encrypted at rest

Supports fine-grained access control

Allows for auditing, versioning, and rotation

*Example*

1) Add API key in secret manger
2) Add an ENV var that references the secret manager key
3) At runtime it calls the ENV to retrieve from the secret manager

Thus secretes are never in plain-text nor hardcoded

Dynamic at runtime access

Traceable and auditable

