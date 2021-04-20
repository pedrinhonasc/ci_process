# Desafio Docker

This repository contains the code that solves the challenge "Desafio Docker" from DevOps course of Code Education.

In this challenge, based on the code in this [repository](https://github.com/pedrinhonasc/laravel_image_2), it is suppose to use the Dockerize template to make the `nginx.conf` more flexible. The expected result is that the `host` and the `port` of the `nginx` can be defined through environment variables in the `docker-compose.yaml`.

**Note**: The Go project image can be pulled from [here](https://hub.docker.com/r/jpedronascimentofilho/codeeducation).

## Goal

The goal of the challenge is to learn `docker` and `docker-compose` in practice.

## Usage

To run this code, in a terminal, execute:

```bash
docker-compose up -d
```

Then, in a browser enter:

```bash
localhost:8000
```

To stop the containers and remove them, execute:

```bash
docker-compose down
```