# Project: Docker compose app

[![Actions Status](https://github.com/perfectbluedev/devops-for-programmers-project-74/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/perfectbluedev/devops-for-programmers-project-74/actions/workflows/hexlet-check.yml)
[![Push to Docker Hub](https://github.com/perfectbluedev/devops-for-programmers-project-74/actions/workflows/push.yml/badge.svg)](https://github.com/perfectbluedev/devops-for-programmers-project-74/actions/workflows/push.yml)

## Description

This project is wrapping application [JS Fastify Blog](https://github.com/hexlet-components/js-fastify-blog) in docker image using docker compose, testing and running CI.

Image on DockerHub: dockerponome/devops-for-programmers-project-74

## Requirements

* Docker Engine 19.03.0+
* docker-compose 1.27.0+

## Usage

Setup

```bash
make setup
```

Test

```bash
make ci
```

Run with Postgres

```bash
make start
```
