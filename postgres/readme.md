# POSTGRESQL Installation

### Download
1. download portable version of postgres.  https://www.enterprisedb.com/download-postgresql-binaries
2. extract to somewhere
### My Home PC
1. initdb -D "C:\Users\William Perng\OneDrive\Desktop\tool\pgsql\data" -U postgres --auth-local=trust
2. pg_ctl.exe -D "C:\Users\William Perng\OneDrive\Desktop\tool\pgsql\data" -l pg.log start
### My AWS Workspace
1. initdb -D "D:\Users\yung-hen_perng\Desktop\javadev\pgsql\data" -U postgres --auth-local=trust
2. pg_ctl.exe -D "D:\Users\yung-hen_perng\Desktop\javadev\pgsql\data" -l pg.log start
### By Windows service
1. pg_ctl register -N postgres -D D:\Users\yung-hen_perng\Desktop\javadev\pgsql\data
2. net start postgres
### Spring boot
server.servlet.context-path=/kongtool<br/>
spring.jpa.hibernate.ddl-auto=update<br/>
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.PostgreSQLDialect<br/>
spring.datasource.url=jdbc:postgresql://localhost:5432/tester<br/>
spring.datasource.username=tester<br/>
spring.datasource.password=tester<br/>
