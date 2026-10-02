# .project - KubeRay

This repository contains standardized metadata for the [KubeRay](https://github.com/ray-project/kuberay) project, following the [CNCF `.project` specification](https://github.com/cncf/automation/tree/main/utilities/dot-project).

## What is KubeRay?

KubeRay is a Kubernetes operator that simplifies the deployment and management of [Ray](https://github.com/ray-project/ray) applications on Kubernetes.
It provides the RayCluster, RayJob, and RayService custom resources, along with a kubectl plugin, an API server, and a dashboard.

## Files

| File | Purpose |
|------|---------|
| `project.yaml` | Core project metadata (description, repositories, maturity, governance links, etc.) |
| `maintainers.yaml` | Maintainer roster with GitHub handles |
| `LICENSE` | Apache License 2.0 |

## Validation

Project metadata is automatically validated on every pull request and push to `main` using the [CNCF validation actions](https://github.com/cncf/automation).

## Links

- **Main Repository:** <https://github.com/ray-project/kuberay>
- **CNCF Sandbox Application:** <https://github.com/cncf/sandbox/issues/525>
