# Desde tu lugar - Development environment

## Dependencies
* [Docker 1.10](https://docs.docker.com/engine/installation/)
* [Docker compose v1.6](https://docs.docker.com/compose/install/)

## Configuration

* Map hosts "api" and "api-testing" to localhost

## Start environment
```
    $ docker-compose up -d
```

## Dump Data to DB for development
```
    $ ./db-development-data
```

## Access

* App: http://localhost:8101/
* Api swagger: http://localhost:3030/explorer
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
Recreate DB for e2e tests
```
    $ ./db-testing
```
