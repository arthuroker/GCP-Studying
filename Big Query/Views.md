
*Standard views*

Most commonly used type of view

Virtual tables representing the result of a query

Don't actually store the data
	Every time you access the view, the underlying query runs

Choose over materialized views when:

1) Queries are accessed infrequently
2) Computation costs is low
3) Storage costs for materialized views are too high
4) Real-time data reflection 