
# Atlas Platform

## 1. Project objective

Build an Internal Developer Platform that provides
standardized self-service application delivery.

## 2. Target users

- Backend developers
- Frontend developers
- Platform engineers
- Site Reliability Engineers

## 3. Platform components

| Component | Responsibility |
|---|---|
| Backstage | Developer portal |
| Terraform | Infrastructure provisioning |
| Kubernetes | Application runtime |
| Helm | Application packaging |
| Argo CD | GitOps deployment |
| GitHub Actions | CI/CD |
| Prometheus | Metrics collection |
| Grafana | Monitoring dashboards |
| Go | Platform APIs and automation |

## 4. Infrastructure targets

- Local: kind Kubernetes
- Primary cloud: AWS
- Secondary cloud: Azure

## 5. Platform principles

- Self-service provisioning
- Secure by default
- Infrastructure as Code
- GitOps deployment
- Reusable templates
- Observable services
- Developer experience first

## 6. Initial Golden Path

Developer creates a Go microservice through
Backstage.

The platform generates the repository,
build pipeline, Helm configuration and
Kubernetes deployment workflow.
