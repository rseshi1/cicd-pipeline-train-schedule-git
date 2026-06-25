# CI/CD

> _Auto-generated DeepWiki. Derived from static analysis of the repository at the referenced commit. Verify against source before relying on operational details._

**Repository:** [`rseshi1/cicd-pipeline-train-schedule-git`](https://github.com/rseshi1/cicd-pipeline-train-schedule-git)  
**Default branch:** `master`  
**Generated:** 2026-06-25 01:16 UTC

## Pipeline overview

```mermaid
flowchart LR
    A[Commit / PR] --> B[Checkout]
    B --> Deps[Install dependencies]
    Deps --> Pages[Publish DeepWiki]
```

## Workflows

_No GitHub Actions workflows detected. This DeepWiki adds `.github/workflows/publish-deepwiki.yml` to publish this documentation._

## Other CI systems

_None detected (Jenkins/GitLab/Travis/Azure Pipelines)._

## DeepWiki publishing

This repository includes `.github/workflows/publish-deepwiki.yml`, which builds
the MkDocs site and deploys it to **GitHub Pages** on push to `master`.
