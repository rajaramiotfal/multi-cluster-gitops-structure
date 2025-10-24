# Multi-Cluster GitOps Demo (Argo CD + Kargo)

This repository demonstrates a production-grade multi-cluster GitOps flow:
- **Argo CD** manages deployments across Dev/QA/Prod clusters.
- **Kargo** automates promotion between environments.
- **cert-manager** issues internal certificates for Kargo webhooks.

## Folder Structure
```
apps/         -> Argo CD ApplicationSet
envs/         -> Manifests per environment (dev, qa, prod)
kargo/        -> Warehouse and Stage definitions
```
