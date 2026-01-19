
Sinks - export destinations for logs based on specific filters

Storing logs have two main purposes:

1. Compliance
2. Logs can be analyzed

**Aggregated Exports**

Example:

You have multiple projects that all route their logs to another one project and puts it in cloud storage

Advantages:

Simplifies log management
Unifies data for analysis
Reduces overhead by putting all logs in one place
Easier auditing/compliance



Long term retention for audit logs - storage bucket with the coldline storage class
	For once a year or less - archive storage



I**ntegrating logs with a SIEM** (security information and event management system)

Designed to ingest, analyze, and act on security events across logs and different sources

Real-time ingestion is critical for effectiveness