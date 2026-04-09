
*Types of imports*

1) SQL dump files, logical backup with schema and data
2) CSV files
3) Replication/direct transfer
4) Database migration service (managed service from GCP)

*Dump Files*

Backups that capture that database's structure and/or data allowing it to be restored or migrated to another instance

PostgreSQL:

Dump file= pg_dump
Import/restore = pg_restore

MySQL:

Dump file = mysqldump
Import/restore= mysqlimport

*Best practices*

Store your data in GCS first before importing it

Use correct flags for dump files

Cannot contain triggers, views, or stored procedures

Compressing data to reduce costs