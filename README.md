# Instructions

## Files and Directories

Create file environment variables `.env`

    POSTGRES_PASSWORD=passw
    POSTGRES_DB=db_name
    POSTGRES_USER=user_name

Create dirs

    mkdir files
    mkdir data

## Create docker network

    docker network create --driver=bridge --subnet=172.20.0.0/16 docker_net

## Launch docker

    docker compose build
    docker compose up -d
