FROM postgres:latest

ARG buildtime_pg_db=postgres
ARG buildtime_pg_user=postgres
ARG buildtime_pg_pw=

ENV POSTGRES_DB=$buildtime_pg_db 
ENV POSTGRES_USER=$buildtime_pg_user 
ENV POSTGRES_PASSWORD=$buildtime_pg_pw 

COPY . /docker-entrypoint-initdb.d/