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

- **Docker:** You'll need Docker installed to use Docker Compose files and run containerized applications. You can download and install Docker from the official [Docker website](https://www.docker.com/get-started).
- **Kubernetes (Optional):** If you plan to use Kubernetes charts for deploying your architectures, ensure you have a Kubernetes cluster set up. You can set up a local Kubernetes cluster using tools like [Minikube](https://minikube.sigs.k8s.io/docs/start/) or [Kind](https://kind.sigs.k8s.io/docs/user/quick-start/).
- **k6:** For performance testing and load generation, I recommend installing k6, an open-source load testing tool. You can download and install k6 from the official [k6 website](https://k6.io/docs/getting-started/installation).
- **Chaos Testing Tool (Optional):** To test the resilience and fault tolerance of your architectural designs, consider using a chaos testing tool such as [Chaos Monkey](https://github.com/Netflix/chaosmonkey) or [Chaos Toolkit](https://chaostoolkit.org/). These tools help you simulate various failure scenarios and assess how well your architecture can withstand unexpected issues.
- **Basic Knowledge of Docker and Kubernetes:** Familiarize yourself with Docker and Kubernetes concepts if you are new to containerization and orchestration technologies. There are plenty of online tutorials and courses available to help you get started.

## Architectural Patterns

- [Leader Based Replication](./database/postgres/README.md) (Postgres)

## Use Cases

TBD

## Performance Testing

TBD

## Chaos Testing

TBD