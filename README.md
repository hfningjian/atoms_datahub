# Atoms Datahub Helm Charts

This repository contains Helm charts for Atoms Datahub applications.

## Usage

Add the repository to your Helm configuration:

```bash
helm repo add datahub https://hfningjian.github.io/atoms_datahub
helm repo update
```

## Available Charts

- `dagster`: Dagster deployment for Atoms Datahub

## Installing a Chart

To install the Dagster chart:

```bash
helm install datahub-dagster datahub/dagster
```

## Configuration

See the [values.yaml](charts/dagster/values.yaml) file for configurable parameters. 