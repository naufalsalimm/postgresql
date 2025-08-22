# postgresql
### Backup Database
``` bash
pg_dump -h 10.239.19.25 -p 5432 -U sso_dev -d nswdbgen2 -f nswdbgen2_20250822.sql 
```
### Restore DB
``` bash
psql -p 5432 -U postgres -d nswdbgen2 -f nswdbgen2_20250822.sql
```
