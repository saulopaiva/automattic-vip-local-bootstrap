# Automattic VIP - Local Bootstrap

## Motivation

This repo can be used to be a simple initial repo for WordPress development for the Automattic VIP hosting service.

It follows the [VIP Guide](https://docs.wpvip.com/how-tos/local-development/) and uses the [Official WordPress Docker Image](https://hub.docker.com/_/wordpress).

## Instalation
```
$ git clone --recurse-submodules git@github.com:saulopaiva/automattic-vip-local-bootstrap
$ cd automattic-vip-local-bootstrap
$ docker-compose up
```

Access: http://localhost:8888/

## WP CLI execution
`docker-compose run --rm cli wp`

### User creation
`docker-compose run --rm cli wp user create exampleusername user@example.com --role=administrator`
