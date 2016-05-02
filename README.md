# Desde tu lugar - Development environment

## Dependencies
* [Docker 1.10](https://docs.docker.com/engine/installation/)
* [Docker compose v1.6](https://docs.docker.com/compose/install/)

## Configuration

* Map host "api" to localhost

## Run environment
```
    $ docker-compose up -d
```

## Access

* App: http://localhost:8101/
* Api swagger: http://localhost:3030/explorer (or http://api:3030/explorer)
* Mysql: 127.0.0.1:3306

## Run Mobile app unit tests
```
    $ ./unit-tests
```

## Run Mobile app e2e tests
```
    $ ./e2e-tests
```
