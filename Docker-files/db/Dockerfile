FROM mysql:8.0.33
LABEL "Project"="Vprofile"
LABEL "Author"="Jalesh"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="acccounts"

ADD db_backup.mysql docker-entrypoint-initdb/db_backup.sql