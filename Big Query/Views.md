
*Standard views*

Most commonly used type of view

Virtual tables representing the result of a query

Don't actually store the data
	Every time you access the view, the underlying query runs

Choose over materialized views when:

1) Queries are accessed infrequently
2) Computation costs is low
3) Storage costs for materialized views are too high
4) Real-time data reflection without frequent refreshes

*Materialized view*

Provide pre-computed and cached query results

Stores the results

Cost-effective for frequently accessed data  especially large datasets

Reduces computational charges associated with on-the-fly query executions

Choose over standard when:

1) Query is accessed frequently
2) Query computation size is high
3) Storage costs for materialized view is low
4) Real-time data reflection is not required

*Authorized views*

Security mechanism that allows users to query specific data without giving them access to the underlying tables

Restrict access to sensitive data while sharing only the results of a defined query

Can control data visibility and enhance security




