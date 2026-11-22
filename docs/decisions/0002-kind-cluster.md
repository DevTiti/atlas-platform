# ADR-0002: Atlas Kubernetes Cluster

## Status
Accepted

## Context
Atlas requires an isolated Kubernetes environment
for platform development and testing.

## Decision
Use kind with one control-plane node and
two worker nodes.

## Namespace strategy
- platform-system
- applications

## Security
Use namespace-scoped RBAC and least privilege.

## Workload strategy
Deploy applications using Kubernetes Deployments
and Services.

## Consequences
The environment is suitable for local development,
integration testing and GitOps experiments.

It is not a production-grade Kubernetes cluster.