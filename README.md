# @ppos/build-orchestrator

This repository is the central hub for the **PrintPrice OS CI/CD and Deployment Automation**.

## Role in the Ecosystem

The Build Orchestrator is responsible for:
- Managing **GitHub Actions Workflows** across the PrintPrice OS organization.
- Orchestrating **Docker Image builds** and registry pushes.
- Executing **Environment-specific deployment scripts** (Staging/Production).
- Validating infrastructure readiness before code promotion.

## Structure

- `.github/workflows/`: Canonical CI/CD pipeline definitions.
- `scripts/`: Implementation-specific deployment and validation scripts.
- `package.json`: Task definitions for build and deployment orchestration.

## Getting Started

To run validation locally:
```bash
npm install
npm run validate
```

For more details on the deployment flow, see the [Bringup Runbook](../brain/bringup_runbook.md).