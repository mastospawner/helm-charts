# Mastospawner Helm Charts

> Helm charts for the Fediverse

This repository contains helm charts for deploying various Federated applications such as:

- Mastodon
- Pixelfed (soon)
- Lemmy (soon)

The helm charts are deployed to Github pages on each new helm chart release.
See each helm chart's readme for instructions on how to get started.

## License

Each helm chart is licensed separately based on the license file in its directory.
This is mostly due to Mastodon's helm chart being copied from the upstream repository.

## Pre-requisites

For all charts in this repository, the following is required before being able to use them.

```bash
helm repo add mastospawner https://mastospawner.github.io/helm-charts
helm repo update
```
