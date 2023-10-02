## Postgres hacking training tasks

This repository contains some Docker images of Postgres containers with well known vulnerabilities.
In every folder you can run **docker-compose up** and then connect to port 5432 with psql. Password is usually "password".

Your objective is to select flag from table secret_table in database secret_db.