# pacroy's Helm repository

## How to Use this Helm Repository

```sh
helm repo add pacroy https://pacroy.github.io/helm-repo/
helm repo update
helm repo list
```

## How to Add a Package

```sh
helm package [CHART_PATH]
helm repo index .
```