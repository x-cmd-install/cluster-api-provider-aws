# cluster-api-provider-aws

[中文版本](./README.cn.md)

Kubernetes Cluster API Provider AWS provides consistent deployment and day 2 operations of "self-managed" and EKS Kubernetes clusters on AWS.

[![x-cmd/install — cluster-api-provider-aws Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/cluster-api-provider-aws.svg)](https://x-cmd.com/install/cluster-api-provider-aws)

## Install

```sh
x install cluster-api-provider-aws
```

## Code insight

Total: **262,936** lines of code across **1012** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 147,022 | 24,536 | 19,902 | 682 |
| Yaml | 112,514 | 633 | 402 | 297 |
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

- **Latest**: `v2.11.3` (2026-09-30)
- **Last commit**: 2026-10-07
- **Assets in release**: 42

## Popularity

- **Stars**: 731 · **Forks**: 715 · **Open issues**: 1,887 · **Contributors**: 691

## Totals (cumulative)

- **Releases**: 105 · **Merged PRs**: 3300 · **Open PRs**: 60 · **Closed issues**: 1710 · **Open issues**: 177 · **Commits**: 5877

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-08 | 3 | 37 | 21 | 4 | 11 | 21 |
| last60d | 2026-08-09 | 3 | 57 | 31 | 6 | 13 | 42 |
| 90d | 2026-07-10 | 4 | 94 | 35 | 11 | 17 | 85 |
| last180d | 2026-04-11 | 8 | 195 | 44 | 25 | 41 | 175 |
| 360d | 2025-10-13 | 13 | 307 | 57 | 53 | 51 | 304 |
| last720d | 2024-10-18 | 21 | 581 | 58 | 141 | 73 | 1045 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [AWSIAMManagedPolicyCloudProviderControlPlane.json](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/AWSIAMManagedPolicyCloudProviderControlPlane.json) | 3.2 KiB | `other` |
| [AWSIAMManagedPolicyCloudProviderNodes.json](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/AWSIAMManagedPolicyCloudProviderNodes.json) | 1.7 KiB | `other` |
| [AWSIAMManagedPolicyControllers.json](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/AWSIAMManagedPolicyControllers.json) | 7.9 KiB | `other` |
| [AWSIAMManagedPolicyControllersWithEKS.json](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/AWSIAMManagedPolicyControllersWithEKS.json) | 7.9 KiB | `other` |
| [AWSIAMManagedPolicyControllersWithS3.json](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/AWSIAMManagedPolicyControllersWithS3.json) | 8.3 KiB | `other` |
| [CHANGELOG.md](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/CHANGELOG.md) | 430 B | `other` |
| [cluster-api-provider-aws_2.13.1_checksums.txt](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/cluster-api-provider-aws_2.13.1_checksums.txt) | 1.1 KiB | `other` |
| [cluster-template-dualstack-ipv4-primary.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/cluster-template-dualstack-ipv4-primary.yaml) | 27.8 KiB | `other` |
| [cluster-template-dualstack-ipv6-primary.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/cluster-template-dualstack-ipv6-primary.yaml) | 28.7 KiB | `other` |
| [cluster-template-eks-clusterclass.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/cluster-template-eks-clusterclass.yaml) | 1.9 KiB | `other` |
| [cluster-template-eks-fargate.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/cluster-template-eks-fargate.yaml) | 1007 B | `other` |
| [cluster-template-eks-ipv6.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/cluster-template-eks-ipv6.yaml) | 2.4 KiB | `other` |
| [cluster-template-eks-machinepool.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/cluster-template-eks-machinepool.yaml) | 1.8 KiB | `other` |
| [cluster-template-eks-managedmachinepool-gpu.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/cluster-template-eks-managedmachinepool-gpu.yaml) | 4.7 KiB | `other` |
| [cluster-template-eks-managedmachinepool-vpccni.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/cluster-template-eks-managedmachinepool-vpccni.yaml) | 1.7 KiB | `other` |
| [cluster-template-eks-managedmachinepool.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/cluster-template-eks-managedmachinepool.yaml) | 1.6 KiB | `other` |
| [cluster-template-eks.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/cluster-template-eks.yaml) | 1.9 KiB | `other` |
| [cluster-template-flatcar-machinepool.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/cluster-template-flatcar-machinepool.yaml) | 28.3 KiB | `other` |
| [cluster-template-flatcar.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/cluster-template-flatcar.yaml) | 28.0 KiB | `other` |
| [cluster-template-ipv6.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/cluster-template-ipv6.yaml) | 28.7 KiB | `other` |
| [cluster-template-machinepool.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/cluster-template-machinepool.yaml) | 26.2 KiB | `other` |
| [cluster-template-multitenancy-clusterclass.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/cluster-template-multitenancy-clusterclass.yaml) | 8.1 KiB | `other` |
| [cluster-template-rosa-machinepool.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/cluster-template-rosa-machinepool.yaml) | 2.9 KiB | `other` |
| [cluster-template-rosa-role-config.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/cluster-template-rosa-role-config.yaml) | 1.4 KiB | `other` |
| [cluster-template-rosa.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/cluster-template-rosa.yaml) | 2.3 KiB | `other` |
| [cluster-template-simple-clusterclass.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/cluster-template-simple-clusterclass.yaml) | 6.5 KiB | `other` |
| [cluster-template.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/cluster-template.yaml) | 25.8 KiB | `other` |
| [clusterawsadm-darwin-amd64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/clusterawsadm-darwin-amd64) | 92.0 MiB | `native/darwin/x64` |
| [clusterawsadm-darwin-arm64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/clusterawsadm-darwin-arm64) | 82.8 MiB | `native/darwin/arm64` |
| [clusterawsadm-linux-amd64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/clusterawsadm-linux-amd64) | 89.4 MiB | `native/linux/x64` |
| [clusterawsadm-linux-arm64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/clusterawsadm-linux-arm64) | 79.7 MiB | `native/linux/arm64` |
| [clusterawsadm-windows-amd64.exe](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/clusterawsadm-windows-amd64.exe) | 91.2 MiB | `native/win/x64` |
| [clusterawsadm-windows-arm64.exe](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/clusterawsadm-windows-arm64.exe) | 80.6 MiB | `native/win/arm64` |
| [clusterctl-aws-darwin-amd64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/clusterctl-aws-darwin-amd64) | 92.0 MiB | `native/darwin/x64` |
| [clusterctl-aws-darwin-arm64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/clusterctl-aws-darwin-arm64) | 82.8 MiB | `native/darwin/arm64` |
| [clusterctl-aws-linux-amd64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/clusterctl-aws-linux-amd64) | 89.4 MiB | `native/linux/x64` |
| [clusterctl-aws-linux-arm64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/clusterctl-aws-linux-arm64) | 79.7 MiB | `native/linux/arm64` |
| [clusterctl-aws-windows-amd64.exe](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/clusterctl-aws-windows-amd64.exe) | 91.2 MiB | `native/win/x64` |
| [clusterctl-aws-windows-arm64.exe](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/clusterctl-aws-windows-arm64.exe) | 80.6 MiB | `native/win/arm64` |
| [infrastructure-components.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/infrastructure-components.yaml) | 1.2 MiB | `other` |
| [metadata.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/metadata.yaml) | 1.4 KiB | `other` |
| [rosa-network.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.1/rosa-network.yaml) | 336 B | `other` |

## Improve this data

Install metadata for cluster-api-provider-aws lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `cluster-api-provider-aws` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/cluster-api-provider-aws.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261008.yml` · 2026-10-08T06:06:35Z._
