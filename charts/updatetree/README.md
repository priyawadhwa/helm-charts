# updatetree

![Version: 0.0.1](https://img.shields.io/badge/Version-0.0.1-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 0.4.3](https://img.shields.io/badge/AppVersion-0.4.3-informational?style=flat-square)

Update the status of an existing Trillian tree

**Homepage:** <https://sigstore.dev/>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| The Sigstore Authors |  |  |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| args.treeID | string | `""` |  |
| args.treeState | string | `""` |  |
| namespace.name | string | `"trillian-system"` |  |
| securityContext.runAsNonRoot | bool | `true` |  |
| securityContext.runAsUser | int | `65533` |  |
| serviceAccount.create | bool | `false` |  |
| serviceAccount.name | string | `"trillian-logserver"` |  |
| spec.image | string | `"ghcr.io/sigstore/scaffolding/updatetree@sha256:22c653b44aef3dc0de4e1bc398a435699b06a01a9b8fdef7880933cb0d79c8ee"` |  |
| spec.replicaCount | int | `1` |  |
| trillian.adminServer | string | `""` |  |
| trillian.logServer.name | string | `"trillian-logserver"` |  |
| trillian.logServer.portRPC | int | `8091` |  |
| trillian.namespace | string | `"trillian-system"` |  |

