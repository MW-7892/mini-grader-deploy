# Mini-grader Deploy
Use this one to deploy the system

## Updating Repo
```
git submodule update --remote --merge
```

## How to Deploy
* Create a docker network, so the backend and the database can connect with each other
```
docker network create mini-grader-network
```
* Start the container
```
docker compose up -d
```
