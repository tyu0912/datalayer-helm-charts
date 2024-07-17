# datalayer-spacer

![Version: 0.0.6](https://img.shields.io/badge/Version-0.0.6-informational?style=flat-square) ![AppVersion: 0.0.6](https://img.shields.io/badge/AppVersion-0.0.6-informational?style=flat-square)

Datalayer Spacer

**Homepage:** <https://datalayer.io>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| Datalayer | <support@datalayer.io> | <https://datalayer.io> |

## Source Code

* <https://github.com/datalayer/helm-charts/tree/main/datalayer-spacer>

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| spacer.env.AWS_ACCESS_KEY_ID | string | `""` |  |
| spacer.env.AWS_DEFAULT_REGION | string | `""` |  |
| spacer.env.AWS_SECRET_ACCESS_KEY | string | `""` |  |
| spacer.env.DATALAYER_AUTHZ_ENGINE | string | `""` |  |
| spacer.env.DATALAYER_CDN_URL | string | `""` |  |
| spacer.env.DATALAYER_JWT_ALGORITHM | string | `""` |  |
| spacer.env.DATALAYER_JWT_ISSUER | string | `""` |  |
| spacer.env.DATALAYER_JWT_SECRET | string | `""` |  |
| spacer.env.DATALAYER_OPENFGA_AUTHZ_MODEL_ID | string | `""` |  |
| spacer.env.DATALAYER_OPENFGA_REST_URL | string | `"http://datalayer-openfga.datalayer-openfga.svc.cluster.local:8080"` |  |
| spacer.env.DATALAYER_OPENFGA_STORE_ID | string | `""` |  |
| spacer.env.DATALAYER_RUNTIME_ENV | string | `"prod"` |  |
| spacer.env.DATALAYER_RUN_HOST | string | `""` |  |
| spacer.env.DATALAYER_SMTP_HOST | string | `""` |  |
| spacer.env.DATALAYER_SMTP_PASSWORD | string | `""` |  |
| spacer.env.DATALAYER_SMTP_PORT | string | `""` |  |
| spacer.env.DATALAYER_SMTP_USERNAME | string | `""` |  |
| spacer.env.DATALAYER_SOLR_ZK_HOST | string | `""` |  |
| spacer.image | string | `"datalayer/spacer:0.0.6"` |  |
| spacer.imagePullPolicy | string | `"IfNotPresent"` |  |
| spacer.port | int | `9900` |  |
| spacer.service.name | string | `"spacer"` |  |
| spacer.service.type | string | `"LoadBalancer"` |  |
| spacer.sidecar.image | string | `"datalayer/whoami:0.0.6"` |  |
