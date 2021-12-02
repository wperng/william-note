1. download portable version of postgres.  https://www.enterprisedb.com/download-postgresql-binaries
2. extract to somewhere
*** My Home local
4. initdb -D "C:\Users\William Perng\OneDrive\Desktop\tool\pgsql\data" -U postgres --auth-local=trust
5. pg_ctl.exe -D "C:\Users\William Perng\OneDrive\Desktop\tool\pgsql\data" -l pg.log start
*** My AWS Workspace
initdb -D "D:\Users\yung-hen_perng\Desktop\javadev\pgsql\data" -U postgres --auth-local=trust
pg_ctl.exe -D "D:\Users\yung-hen_perng\Desktop\javadev\pgsql\data" -l pg.log start

*** By service
5. pg_ctl register -N postgres -D D:\Users\yung-hen_perng\Desktop\javadev\pgsql\data
   net start postgres 
