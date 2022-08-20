# Kubernetes Helm Charts

[![Release Charts](https://github.com/lewis-green/charts/actions/workflows/release.yml/badge.svg)](https://github.com/lewis-green/charts/actions/workflows/release.yml)

Helm charts for all applications I am running on my personal Kubernetes cluster. Some are third party images built into a Helm chart, and some are personally developed images.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```shell
helm repo add lewis-green https://charts.lewisgreen.co.uk/charts
```

You can then run `helm search repo lewis-green` to see the charts.
