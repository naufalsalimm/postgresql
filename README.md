# postgresql
### Backup Database
``` bash
pg_dump -h 127.0.0.1 -p 5432 -U api_user -d mydb -F c -f mydb_20250822.dump
```
