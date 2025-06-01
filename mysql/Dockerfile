FROM mysql:8.0.0
ENV MYSQL_ROOT_PASSWORD=ExpenseAPP@1
# copy all the mysql scripts and copies to /docker-entrypoint-initdb.d so that the schema, table  is automatically created while creating image 
COPY scripts/*.sql /docker-entrypoint-initdb.d
