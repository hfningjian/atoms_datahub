# Xiaoleng Helm Charts

This repository contains Helm charts for Xiaoleng's applications.

## Usage

Add the repository to your Helm configuration:

```bash
helm repo add xiaoleng https://xiaoleng.github.io/xiaoleng-helm-charts
helm repo update
```

## Available Charts

- `dagster`: Dagster deployment for Xiaoleng

## Installing a Chart

To install the Dagster chart:

```bash
helm install xiaoleng-dagster xiaoleng/dagster
```

## Configuration

See the [values.yaml](charts/dagster/values.yaml) file for configurable parameters. 