
*Types of imports*

1) SQL dump files, logical backup with schema and data
2) CSV files
3) Replication/direct transfer
4) Database migration service (managed service from GCP)

*Dump Files*

Backups that capture that database's structure and/or data allowing it to be restored or migrated to another instance

PostgreSQL:

Dump_file= pg_dump
Import/restore = pg_restore

