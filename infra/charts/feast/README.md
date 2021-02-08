# feast-spark

Feast Extension for running Ingestion on Spark 0.10.0-SNAPSHOT

## Installation

https://docs.feast.dev/v/master/getting-started/deploying-feast/kubernetes

## Requirements

| Repository | Name | Version |
|------------|------|---------|
|  | feast-jobservice | 0.10.0-SNAPSHOT |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| feast-jobservice.enabled | bool | `true` | Flag to install Feast Job Service |

### Documentation development

This `README.md` is generated using [helm-docs](https://github.com/norwoodj/helm-docs/).
Please run `helm-docs` to regenerate the `README.md` every time `README.md.gotmpl`
or `values.yaml` are updated.