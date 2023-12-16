FROM mysql:8.0.33
LABEL "project"="JAVA_WEB_APP"
LABEL "Author"= "ARSALAN ZEB"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d

