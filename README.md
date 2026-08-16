# Pure minerals microservices
===========================

This repository contains the documentation for the Pure minerals microservices.


## Getting started

For init the project, run the following command:

```./init.sh```

### services

#### pm-gateway

The gateway is a REST API that provides a unified interface to the Pure minerals microservices.

link to repo: https://github.com/pav-dev98/pm-gateway

#### pm-proto

The proto microservice is a gRPC API that provides a unified interface to the Pure minerals microservices.

link to repo: https://github.com/pav-dev98/pm-proto

#### pm-auth-svc

Authentication service for the Pure minerals microservices.

link to repo: https://github.com/pav-dev98/pm-auth-svc

#### pm-user-svc
User service for the Pure minerals microservices.

### Architecture

All services are deployed on Kubernetes and are accessible through the gateway.

The communication between the services is done through gRPC.

Each service has its own database, which is used to store the data.