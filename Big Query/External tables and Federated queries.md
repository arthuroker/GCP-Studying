
*External tables*

Can create an external table in BQ for data that is stored in GCS and run SQL queries directly on that data as if it were in BQ

*Process*

Reads the data

Processing the query

Returns the results

Most of the time, external data is stored in Cloud Storage, but can also use Big Table and Google Drive

*Federated Queries*

Allow you to query other GCP databases

Retrieves results as a temporary table in BQ

Works for:

1) Cloud Spanner
2) 