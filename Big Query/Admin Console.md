
Can do:

1) resource utilization and job monitoring
2) slot capacity mangement
3) policy tag taxonomies
4) Query the INFORMATION_SCHEMA to get a sense of job performance

*Information Schema*

Provides a standardized, queryable, read-only views with metadata about datasets, tables, columns, jobs, etc.

Useful for understanding usage patterns and optimizing performance

*Errors related to jobs*

BQ interface allows you to view errors related to jobs

Jobs explorer should be the first place to look

*quotaExceeded error*

Hit a limit on a specific resource/operation

Identify the specific quote by looking at the error details

Review the current quota usage in GCP Console

Leverage INFORMATION_SCHEMA view

