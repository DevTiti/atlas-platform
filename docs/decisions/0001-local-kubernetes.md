
# ADR-0001: Local Kubernetes Environment

## Status
Accepted

## Context
We need a repeatable Kubernetes environment
for developing and testing Atlas Platform.

## Decision
Use kind to run local Kubernetes clusters.

## Reasons
- Runs Kubernetes using Docker containers.
- Reproducible development environments.
- Suitable for GitOps and Helm experiments.
- No cloud infrastructure costs for initial labs.

## Consequences
- Local environment does not reproduce every
  production cloud capability.
- Production deployments will require additional
  security, networking and availability controls.
