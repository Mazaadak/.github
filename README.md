# .github

This repository contains organization-level metadata and shared resources for the Mazadak platform.

## Contents

- **`profile/`** - Organization profile README (displayed on the GitHub organization page)
- **`.github/workflows/`** - Reusable GitHub Actions workflows shared across all service repositories
- **`LICENSE`** - Project license
- **Wiki** - Comprehensive documentation for the platform, services, and architecture

## Shared Workflows

The `.github/workflows/` directory contains centralized CI/CD pipelines:

- `java-build-package-push.yml` - Builds and containerizes microservices, pushes Docker images to GHCR
- `java-publish-maven-package.yml` - Publishes the common-module library to GitHub Packages Maven registry

All service repositories reference these workflows to ensure consistent build and deployment processes.

## Wiki Documentation

The wiki contains:
- Platform architecture and design patterns
- Individual service documentation
- Cross-cutting concerns (security, eventing, workflows)
- Deployment and CI/CD guides

Access the wiki at: https://github.com/Mazaadak/.github/wiki


