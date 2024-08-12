# Dockerfile for MySQL-Container
FROM mysql:latest

# Avoid Error: InnoDB: Cannot add foreign key constraint (6025)
# https://dev.mysql.com/doc/refman/8.4/en/server-system-variables.html#sysvar_restrict_fk_on_non_standard_key
COPY my.cnf /etc/mysql/my.cnf

# copy world.sql to /docker-entrypoint-initdb.d/ to initialize database
COPY world.sql /docker-entrypoint-initdb.d/

# copy northwind.sql to /docker-entrypoint-initdb.d/ to initialize database
COPY northwind.sql /docker-entrypoint-initdb.d/

# copy chinook.sql to /docker-entrypoint-initdb.d/ to initialize database
COPY chinook.sql /docker-entrypoint-initdb.d/
