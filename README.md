# compose

docker-compose files for building local development environments.

## Quick start

### Create network and volumes

All docker run in network ```development```, so need create docker network first.

```sh
docker network create development
```

Then create volumes

```sh
docker volume create development
```

### Start services

```
docker-compose up -d
```

Default user for mysql and mongo is ```root```, default password for all databases is ```1qaz2ws```
