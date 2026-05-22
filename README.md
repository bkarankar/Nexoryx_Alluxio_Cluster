
![License](https://img.shields.io/badge/License-MIT-green)
![Platform](https://img.shields.io/badge/Platform-Ubuntu-orange)
![DevOps](https://img.shields.io/badge/DevOps-Ready-blue)
![Automation](https://img.shields.io/badge/Automation-Enabled-blue)

# Nexoryx_Alluxio_Cluster

Production-ready Alluxio distributed storage and caching platform for Kubernetes with Spark, Trino, MinIO, autoscaling, persistent storage, and high-performance analytics workloads.

## Features

- Alluxio Master and Worker cluster
- Distributed caching layer
- Spark integration
- Trino integration
- MinIO object storage
- Kubernetes-native deployment
- Persistent volumes
- Autoscaling support
- Resource limits
- Health probes
- NGINX Ingress support
- Production-ready manifests

## Stack

- Kubernetes
- Alluxio
- Spark
- Trino
- MinIO
- PostgreSQL
- NGINX Ingress
- Prometheus
- Grafana

## Deployment

```bash
kubectl apply -f kubernetes/
```

## Namespace

```bash
nexoryx-alluxio
```

## Components

- Alluxio Master
- Alluxio Workers
- Spark
- Trino
- MinIO
- Ingress
- HPA Autoscaling

## Notes

Update passwords, storage classes, and ingress domains before production deployment.


## Project Roadmap

- [ ] Kubernetes Helm charts
- [ ] GitOps support
- [ ] CI/CD improvements
- [ ] Monitoring dashboards
- [ ] Multi-cloud support
- [ ] Security hardening

## GitHub Actions

This repository includes:
- Shell validation
- Markdown linting
- Terraform validation (where applicable)

## Example Deployments

See:
- examples/
- docs/

## Related Nexoryx Projects

This repository is part of the Nexoryx infrastructure ecosystem.
