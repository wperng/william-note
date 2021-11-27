1. download portable version of postgres.  https://www.enterprisedb.com/download-postgresql-binaries
2. extract to somewhere
3. initdb -D "C:\Users\William Perng\OneDrive\Desktop\tool\pgsql\data" -U postgres --auth-local=trust
3. pg_ctl.exe -D "C:\Users\William Perng\OneDrive\Desktop\tool\pgsql\data" -l pg.log start
