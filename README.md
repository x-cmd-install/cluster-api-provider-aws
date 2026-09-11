# cluster-api-provider-aws

[中文版本](./README.cn.md)

Kubernetes Cluster API Provider AWS provides consistent deployment and day 2 operations of "self-managed" and EKS Kubernetes clusters on AWS.

![cluster-api-provider-aws](https://repo.x-cmd.io/cluster-api-provider-aws.svg)

## Install

```sh
x install cluster-api-provider-aws
```

## Code insight

Total: **261,858** lines of code across **1005** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 145,958 | 24,089 | 19,606 | 675 |
| Yaml | 112,500 | 633 | 402 | 297 |
| Sh | 866 | 578 | 262 | 26 |
| Makefile | 761 | 140 | 227 | 6 |
| Css | 472 | 43 | 73 | 1 |

## OpenSSF Scorecard

Overall score: **6.6 / 10**

Lowest-scoring checks:

- **Packaging** (-1/10) — packaging workflow not detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Fuzzing** (0/10) — project is not fuzzed

## Source

- **Upstream**: <https://github.com/kubernetes-sigs/cluster-api-provider-aws>
- **Homepage**: <http://cluster-api-aws.sigs.k8s.io/>
- **License**: Apache-2.0

## Release

- **Latest**: `v2.13.0` (2026-07-29)
- **Last commit**: 2026-09-09
- **Assets in release**: 42

## Popularity

- **Stars**: 728 · **Forks**: 705 · **Open issues**: 1,872 · **Contributors**: 673

## Totals (cumulative)

- **Releases**: 102 · **Merged PRs**: 3264 · **Open PRs**: 52 · **Closed issues**: 1703 · **Open issues**: 169 · **Commits**: 5828

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 0 | 21 | 20 | 0 | 4 | 14 |
| last60d | 2026-07-13 | 1 | 58 | 25 | 4 | 8 | 56 |
| 90d | 2026-06-13 | 2 | 92 | 28 | 11 | 26 | 87 |
| last180d | 2026-03-15 | 5 | 180 | 37 | 20 | 35 | 177 |
| 360d | 2025-09-16 | 10 | 295 | 49 | 49 | 44 | 301 |
| last720d | 2024-09-21 | 18 | 563 | 50 | 143 | 67 | 1025 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [AWSIAMManagedPolicyCloudProviderControlPlane.json](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/AWSIAMManagedPolicyCloudProviderControlPlane.json) | 3.2 KiB | `other` |
| [AWSIAMManagedPolicyCloudProviderNodes.json](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/AWSIAMManagedPolicyCloudProviderNodes.json) | 1.7 KiB | `other` |
| [AWSIAMManagedPolicyControllers.json](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/AWSIAMManagedPolicyControllers.json) | 7.9 KiB | `other` |
| [AWSIAMManagedPolicyControllersWithEKS.json](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/AWSIAMManagedPolicyControllersWithEKS.json) | 7.9 KiB | `other` |
| [AWSIAMManagedPolicyControllersWithS3.json](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/AWSIAMManagedPolicyControllersWithS3.json) | 8.3 KiB | `other` |
| [CHANGELOG.md](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/CHANGELOG.md) | 248 B | `other` |
| [cluster-api-provider-aws_2.13.0_checksums.txt](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-api-provider-aws_2.13.0_checksums.txt) | 1.1 KiB | `other` |
| [cluster-template-dualstack-ipv4-primary.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-dualstack-ipv4-primary.yaml) | 27.8 KiB | `other` |
| [cluster-template-dualstack-ipv6-primary.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-dualstack-ipv6-primary.yaml) | 28.7 KiB | `other` |
| [cluster-template-eks-clusterclass.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-eks-clusterclass.yaml) | 1.9 KiB | `other` |
| [cluster-template-eks-fargate.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-eks-fargate.yaml) | 1007 B | `other` |
| [cluster-template-eks-ipv6.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-eks-ipv6.yaml) | 2.4 KiB | `other` |
| [cluster-template-eks-machinepool.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-eks-machinepool.yaml) | 1.8 KiB | `other` |
| [cluster-template-eks-managedmachinepool-gpu.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-eks-managedmachinepool-gpu.yaml) | 4.7 KiB | `other` |
| [cluster-template-eks-managedmachinepool-vpccni.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-eks-managedmachinepool-vpccni.yaml) | 1.7 KiB | `other` |
| [cluster-template-eks-managedmachinepool.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-eks-managedmachinepool.yaml) | 1.6 KiB | `other` |
| [cluster-template-eks.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-eks.yaml) | 1.9 KiB | `other` |
| [cluster-template-flatcar-machinepool.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-flatcar-machinepool.yaml) | 28.3 KiB | `other` |
| [cluster-template-flatcar.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-flatcar.yaml) | 28.0 KiB | `other` |
| [cluster-template-ipv6.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-ipv6.yaml) | 28.7 KiB | `other` |
| [cluster-template-machinepool.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-machinepool.yaml) | 26.2 KiB | `other` |
| [cluster-template-multitenancy-clusterclass.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-multitenancy-clusterclass.yaml) | 8.1 KiB | `other` |
| [cluster-template-rosa-machinepool.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-rosa-machinepool.yaml) | 2.9 KiB | `other` |
| [cluster-template-rosa-role-config.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-rosa-role-config.yaml) | 1.4 KiB | `other` |
| [cluster-template-rosa.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-rosa.yaml) | 2.3 KiB | `other` |
| [cluster-template-simple-clusterclass.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-simple-clusterclass.yaml) | 6.5 KiB | `other` |
| [cluster-template.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template.yaml) | 25.8 KiB | `other` |
| [clusterawsadm-darwin-amd64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterawsadm-darwin-amd64) | 91.9 MiB | `native/darwin/x64` |
| [clusterawsadm-darwin-arm64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterawsadm-darwin-arm64) | 82.7 MiB | `native/darwin/arm64` |
| [clusterawsadm-linux-amd64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterawsadm-linux-amd64) | 89.4 MiB | `native/linux/x64` |
| [clusterawsadm-linux-arm64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterawsadm-linux-arm64) | 79.6 MiB | `native/linux/arm64` |
| [clusterawsadm-windows-amd64.exe](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterawsadm-windows-amd64.exe) | 91.2 MiB | `native/win/x64` |
| [clusterawsadm-windows-arm64.exe](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterawsadm-windows-arm64.exe) | 80.6 MiB | `native/win/arm64` |
| [clusterctl-aws-darwin-amd64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterctl-aws-darwin-amd64) | 91.9 MiB | `native/darwin/x64` |
| [clusterctl-aws-darwin-arm64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterctl-aws-darwin-arm64) | 82.7 MiB | `native/darwin/arm64` |
| [clusterctl-aws-linux-amd64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterctl-aws-linux-amd64) | 89.4 MiB | `native/linux/x64` |
| [clusterctl-aws-linux-arm64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterctl-aws-linux-arm64) | 79.6 MiB | `native/linux/arm64` |
| [clusterctl-aws-windows-amd64.exe](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterctl-aws-windows-amd64.exe) | 91.2 MiB | `native/win/x64` |
| [clusterctl-aws-windows-arm64.exe](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterctl-aws-windows-arm64.exe) | 80.6 MiB | `native/win/arm64` |
| [infrastructure-components.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/infrastructure-components.yaml) | 1.2 MiB | `other` |
| [metadata.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/metadata.yaml) | 1.4 KiB | `other` |
| [rosa-network.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/rosa-network.yaml) | 336 B | `other` |

## Improve this data

Install metadata for cluster-api-provider-aws lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `cluster-api-provider-aws` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/cluster-api-provider-aws.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260911.yml` · 2026-09-11T00:10:25Z._
