# Architecture Playground

This repository is a versatile collection of Docker Compose files and Kubernetes charts designed to help you experiment with and test various software architecture ideas and design patterns.

## Table of Contents

- [Getting Started](#getting-started)
- [Architectural Patterns](#architectural-patterns)
- [Use Cases](#use-cases)
- [Performance Testing](#performance-testing)
- [Chaos Testing](#chaos-testing)

## Getting Started

Before you begin exploring and testing architectural patterns and use cases in this repository, make sure you have the following prerequisites installed and set up on your development environment:

- **[Docker](https://www.docker.com/get-started):** You'll need Docker installed to use Docker Compose files. You can download and install Docker from the official .
- **[Minikube](https://minikube.sigs.k8s.io/docs/start/) or [Kind](https://kind.sigs.k8s.io/docs/user/quick-start/) (Optional):** If you plan to use Kubernetes charts for deploying your architectures, ensure you have a Kubernetes cluster set up.
- **[K6](https://k6.io/docs/getting-started/installation) (Optional):** For performance testing and load generation.
- **[Chaos Monkey](https://github.com/Netflix/chaosmonkey) or [Chaos Toolkit](https://chaostoolkit.org/) (Optional):** To test the resilience and fault tolerance of architectural designs.

## Architectural Patterns

- [Leader Based Replication](./db/postgres/README.md) (Postgres)

## Use Cases

TBD

## Performance Testing

TBD

## Chaos Testing

TBD
