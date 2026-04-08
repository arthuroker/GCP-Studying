
*Schema attributes*

Column families group columns together

Columns exist within column families, specific columns are defined dynamically by the data written to the table

"Sparse" - empty cells don't cost any storage

Row keys uniquely identify a row

Only the row key is indexed in Big Table, so they design of the row key greatly affects access patterns and performance

