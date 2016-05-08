# Desde tu lugar - Development environment

## Dependencies
* [Docker 1.10](https://docs.docker.com/engine/installation/)
* [Docker compose v1.6](https://docs.docker.com/compose/install/)

## Configuration

* Map host "api" and "api-testing" to localhost

## Start environment
```
    $ docker-compose up -d
```

## Dump DB data
```
    $ ./db-data
```

## Access

* App: http://localhost:8101/
* Api swagger: http://api:3030/explorer
* Mysql: 127.0.0.1:3306

## Run Mobile app unit tests
```
    $ ./run-unit-tests
```

## Run Mobile app e2e tests
```
    $ ./run-e2e-tests
```

## Other DB commands
Load DB schema
```
    $ ./db-schema
```
Load DB data
```
    $ ./db-data
```
