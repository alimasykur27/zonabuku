# Zonabuku

A web application using Flask, NextJS with Docker for Workshop Implementasi Perangkat Lunak Computer Science UGM

## Getting Started

This project consists of Flask application for the backend API, NextJS for client side application and nginx as a reverse-proxy for connecting api and the front-end. This project also use `docker-compose` to make it easy run all of the container at once.

### Prerequisites

Before you run this application make sure you have this installed in your machine:

- [Docker Desktop](https://www.docker.com/products/docker-desktop)
- [docker-compose](https://docs.docker.com/compose/install/)

### Running Locally

To run the application locally, run this command

```
$ docker-compose up
```