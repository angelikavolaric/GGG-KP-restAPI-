FROM postgres:latest

ENV POSTGRES_USER=user
ENV POSTGRES_PASSWORD=passwd
ENV POSTGRES_DB=belezenje_database


COPY ./db/sql-scripts/init-db.sql /docker-entrypoint-initdb.d/

# Expose PostgreSQL port
EXPOSE 5432