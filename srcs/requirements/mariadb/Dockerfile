FROM debian:bullseye

RUN apt update -y && apt install mariadb-server -y

COPY ./tools/50-server.cnf /etc/mysql/mariadb.conf.d/