
*Normalization*

Process of structuring a database to reduce redundancy and improve data integrity by dividing data into smaller, related tables

Make sure the data is only stored in one place

Normalization can introduce performance overhead during queries

Queries that require combining data from different tables may require expensive JOIN operations

*Denormalization*

Process of reversing some of the normalization by combining related tables into one to reduce the need for complex joins

The goal is to reduce the number of tables involved in a query

Can also lead to data redundancy

*Denormalization in BQ*

BQ encourages denormalization to improve cost and performance

BQ uses columnar storage, which scans data more efficiently compared to other databases when normalized

Thus, reduces the need for expensive JOIN operations

BQ allows nested tables and repeated fields to store complex data structures within a single table

RECORD/STRUCT data type, use UNNEST to flatten/normalize nested data for analysis

BQ supports JOIN, but denormalize where possible



