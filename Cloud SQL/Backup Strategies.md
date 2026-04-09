
*PITR (Point in-time recovery)*

Allows you to restore a database to any past state

For MySQL is uses binary logging and for PostgreSQL is uses write-ahead logging

*binary* - records all changes to the database in binary format after the transaction is committed

*write-ahead logging* - logs changes before applying them to the database

*Backups*

*Automatic* - Can configure daily automatic backups within a 4 hour window, retained for 7 days by default. If you need longer, you can export it to Cloud Storage

*Manual* - self explanatory, keep as long as you want

*Scheduled exports* - Export backups to Cloud Storage for long term retention or compliance purposes



