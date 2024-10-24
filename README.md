# Sample Node.js application

This repository is a sample Node.js application for Docker's documentation.

## create .env

1. SERVER_PORT=8080 (should be identical to the Dockerfile EXPOSE 8080) REQUIRED!
2. POSTGRES_HOST=localhost (not required!)
3. POSTGRES_USER=postgres (not required!)
4. POSTGRES_PASSWORD=postgres (not required!)
5. POSTGRES_DB=docker-nodejs-db (not required!)

## Start docker compose

```
docker compose  up --build
```

## Test Stage

```
docker build -t node-docker-image-test --progress=plain --no-cache --target test .
```
