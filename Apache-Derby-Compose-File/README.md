# Docker Compose

Docker Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application’s services. Then, with a single command, you create and start all the services from your configuration. <br><br>
Compose works in all environments: production, staging, development, testing, as well as CI workflows. 

This sample compose file for Apache Derby provide a starting point for how to deploy Apache Derby using a Compose file and to manage their deployment with Docker Compose.

## Getting started

These instructions will get you through the bootstrap phase of creating and
deploying samples of containerized Apache Derby database along with a set of sample databases and associated data with Docker Compose.

### Prerequisites

- Make sure that you have Docker and Docker Compose installed
  - Windows or macOS:
    [Install Docker Desktop](https://www.docker.com/get-started)
  - Linux: [Install Docker](https://www.docker.com/get-started) and then
    [Docker Compose](https://github.com/docker/compose)
- Download some or all of the samples from this repository.

### Running a sample

This directory contains the `docker-compose.yml` which describes the configuration of Apache Derby service components. Please review both the `docker-compose.yml` and `.env` for details on the environment variables used in the startup and running of this application. This sample can be run in a local environment by going into the root directory of each one and executing:

```console
docker-compose up -d
```

To stop and remove all containers of the sample application run:

```console
docker-compose down
```
