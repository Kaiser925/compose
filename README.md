# compose

docker-compose files for building local development environments.

## Quick start

All docker run in network ```development```, so need create docker network first.

```sh
docker network create development
```

Then create volumes

```sh
docker volume create development
```

Start services.

```sh
docker-compose -f <service-compose.yml> up -d
```

## Usage

### Start Database services

[database-compose.yml](database-compose.yml) compose for building databases.

```
docker-compose -f database-compose.yml up -d
```

Default user for mysql and mongo is ```root```, default password for all databases is ```1qaz2ws```
