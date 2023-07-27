# CREATING GITEA CONTAINER USING DOCKER-COMPOSE

Gitea, a lightweight git repository

## HOW TO USE
Simply use docker-compose command to create this docker container with minimal config.

```
docker-compose -f docker-compose.yml up -d
```
* You need to provide a valid credentials to postgresql server.
* It will exposing port `3000` from your host to port `3000` inside gitea container. 
* It will create new `data` directory inside project root that will hold all repo and gitea data
* Open `localhost:3000` to check if this container is working.
