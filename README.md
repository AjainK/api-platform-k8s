# API Platform on Kubernetes

A production-style API platform on Kubernetes, with Kong as the API gateway.
Built step by step alongside my Kubestronaut certifications.

## Goal
Show how a real API platform is run on Kubernetes: routing, auth and rate
limiting at the gateway, safe deployments, security hardening, GitOps and
observability.

## Planned architecture
Client → Kong (Gateway API) → orders-api / payments-api → Postgres

## Roadmap
- [ ] **Basics:** two small Go services, Dockerfiles, local run
- [ ] **KCNA:** Kubernetes manifests on kind, CI image builds
- [ ] **CKA:** Kong Ingress Controller, Gateway API, Helm chart, Kustomize overlays, RBAC
- [ ] **CKAD:** probes, autoscaling, canary releases, Postgres StatefulSet
- [ ] **KCSA:** threat model and security roadmap
- [ ] **CKS:** NetworkPolicies, Pod Security, image scanning and signing, Falco
- [ ] **Extras:** Argo CD GitOps, Prometheus and Grafana dashboards

## Status
Just started. Follow the commits to see it grow.
