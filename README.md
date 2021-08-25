# Demo of docker-compose with Postgresql
Demo docker-compose PSQL

# ENV data
POSTGRES_USER: hello

POSTGRES_PASSWORD: world

PGDATA: "/data/postgres"

POSTGRES_DB: "docker_postgres"

# How to run it

## Run with detach mode
docker-compose up -d 

## Run with attach mode
docker-compose up

## Stop container
docker-compose down

## Remove orphan volumes
docker-compose down --remove-orphans --volumes

