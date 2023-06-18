FROM mysql:latest

ENV  MYSQL_ROOT_PASSWORD=1234

# Copy files to Working Dir
COPY ./m_docker/db-load-script.sql /docker-entrypoint-initdb.d/

